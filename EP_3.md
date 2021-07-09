```json
		{
			"name": "EP_3",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": []
				},
				"url": {
					"raw": "162.55.220.72:5005/object_info_1?name=Test_name&age=12&weight=40",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_1"
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
							"key": "weight",
							"value": "40"
						}
					]
				}
			},
			"response": [
				{
					"name": "EP_3",
					"originalRequest": {
						"method": "GET",
						"header": [],
						"body": {
							"mode": "formdata",
							"formdata": []
						},
						"url": {
							"raw": "162.55.220.72:5005/object_info_1?name=Test_name&age=12&weight=40",
							"host": [
								"162",
								"55",
								"220",
								"72"
							],
							"port": "5005",
							"path": [
								"object_info_1"
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
									"key": "weight",
									"value": "40"
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
							"value": "68"
						},
						{
							"key": "Server",
							"value": "Werkzeug/2.0.1 Python/3.8.10"
						},
						{
							"key": "Date",
							"value": "Fri, 09 Jul 2021 07:47:09 GMT"
						}
					],
					"cookie": [],
					"body": "{\n    \"age\": 12,\n    \"daily_food\": 0.48,\n    \"daily_sleep\": 100,\n    \"name\": \"Test_name\"\n}"
				}
			]
		}
```