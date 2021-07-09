```json
{
			"name": "EP_6",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "162.55.220.72:5005/object_info_4?name=Test_name&age=12&salary=1000",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_4"
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
					"name": "EP_6",
					"originalRequest": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "162.55.220.72:5005/object_info_4?name=Test_name&age=12&salary=1000",
							"host": [
								"162",
								"55",
								"220",
								"72"
							],
							"port": "5005",
							"path": [
								"object_info_4"
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
							"value": "60"
						},
						{
							"key": "Server",
							"value": "Werkzeug/2.0.1 Python/3.8.10"
						},
						{
							"key": "Date",
							"value": "Fri, 09 Jul 2021 07:47:38 GMT"
						}
					],
					"cookie": [],
					"body": "{\n    \"age\": 12,\n    \"name\": \"Test_name\",\n    \"salary\": [\n        1000,\n        \"2000\",\n        \"3000\"\n    ]\n}"
				}
			]
```