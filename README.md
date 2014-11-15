CourtStreet
===========

Myriad of data sets from the home. Considering http://metricsgraphicsjs.org/ or http://d3js.org/


Pellet Stove
------------

The *timeStamp* value is the default Date() object.

Format Example:

	{
		"id": 10,
		"hopper": {
			"fill": { "timeStamp": "Wed Nov 12 2014 17:43:00 GMT-0500 (EST)" },
			"empty": { "timeStamp": null }
		},
		"brand": "Green Supreme",
		"type": "Pellet",
		"wood": "Hardwood",
		"stoveAdjustments": [
			{ 
				"timeStamp": "Wed Nov 12 2014 17:43:00 GMT-0500 (EST)",
				"temperature": 72.0,
				"feedAdjusterSetting": 3,
				"roomTemperatureSetting": "Low"
			}
		],
		"temperatureScale": "Fahrenheit",
		"weight": 40.0,
		"weightScale": "Imperial",
		"ambientTemperatures": [
			{
				"timeStamp": "Wed Nov 12 2014 00:00:00 GMT-0500 (EST)",
				"dayTimeTemperature": 56,
				"nightTimeTemperature": 31
			}
		]
	}


Network
-------

Bandwidth tests hardwired to modem, http://en.wikipedia.org/wiki/Data_rate_units#Megabit_per_second as well as https://github.com/sivel/speedtest-cli

	{ "data": [
		{
			"id": 1,
			"ssId": "",
			"ssIdBroadcast": false,
			"equipment": {
				"name": "Linksys N300 Wi-Fi Wireles Router",
				"qos": true
			},
			"bandwidth": [
			  {
			  "duration": {
					"start": { "timeStamp": null },
					"end": { "timeStamp": null }
				},
				"downloadSpeed": 407500,
				"uploadSpeed": 1360000,
				"unit": "bytes",
				"rate": "seconds",
				"server": { 
					"name":"Hosted by Towerstream (Boston, MA)",
					"distance": {
						"measurement": 81.76,
						"unit": "kilometers"
					}
				},
				"latency": {
					"ping": 10.911,
					"unit": "milliseconds"
				}
				}
			],
			"internetServiceProvider": { 
				"name": "Comcast", 
				"connectionType": "DOCSIS 3" 
			}
		}
	]
	}