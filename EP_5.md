```json
{
			"name": "EP_5",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "162.55.220.72:5005/object_info_3?name=Test_name&age=12&salary=1000",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_3"
					],
					"query": [
						{
							"key": "name",
							"value": "Test_name"
						},
						{
							"key": "age",
							"value": "12"
						},
						{
							"key": "salary",
							"value": "1000"
						}
					]
				}
			},
			"response": [
				{
					"name": "EP_5",
					"originalRequest": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "162.55.220.72:5005/object_info_3?name=Test_name&age=12&salary=1000",
							"host": [
								"162",
								"55",
								"220",
								"72"
							],
							"port": "5005",
							"path": [
								"object_info_3"
							],
							"query": [
								{
									"key": "name",
									"value": "Test_name"
								},
								{
									"key": "age",
									"value": "12"
								},
								{
									"key": "salary",
									"value": "1000"
								}
							]
						}
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Content-Type",
							"value": "application/json"
						},
						{
							"key": "Content-Length",
							"value": "189"
						},
						{
							"key": "Server",
							"value": "Werkzeug/2.0.1 Python/3.8.10"
						},
						{
							"key": "Date",
							"value": "Fri, 09 Jul 2021 07:47:30 GMT"
						}
					],
					"cookie": [],
					"body": "{\n    \"age\": \"12\",\n    \"family\": {\n        \"children\": [\n            [\n                \"Alex\",\n                24\n            ],\n            [\n                \"Kate\",\n                12\n            ]\n        ],\n        \"pets\": {\n            \"cat\": {\n                \"age\": 3,\n                \"name\": \"Sunny\"\n            },\n            \"dog\": {\n                \"age\": 4,\n                \"name\": \"Luky\"\n            }\n        },\n        \"u_salary_1_5_year\": 4000\n    },\n    \"name\": \"Test_name\",\n    \"salary\": 1000\n}"
				}
			]
		}
```