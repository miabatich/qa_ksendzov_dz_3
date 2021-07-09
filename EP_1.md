
```json
{
			"name": "EP_1",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "162.55.220.72:5005/get_method?name=Test_name&age=12",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"get_method"
					],
					"query": [
						{
							"key": "name",
							"value": "Test_name"
						},
						{
							"key": "age",
							"value": "12"
						}
					]
				}
			},
			"response": [
				{
					"name": "EP_1",
					"originalRequest": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "162.55.220.72:5005/get_method?name=Test_name&age=12",
							"host": [
								"162",
								"55",
								"220",
								"72"
							],
							"port": "5005",
							"path": [
								"get_method"
							],
							"query": [
								{
									"key": "name",
									"value": "Test_name"
								},
								{
									"key": "age",
									"value": "12"
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
							"value": "19"
						},
						{
							"key": "Server",
							"value": "Werkzeug/2.0.1 Python/3.8.10"
						},
						{
							"key": "Date",
							"value": "Fri, 09 Jul 2021 07:46:23 GMT"
						}
					],
					"cookie": [],
					"body": "[\n    \"Test_name\",\n    \"12\"\n]"
				}
			]
		},
		{
			"name": "EP_2",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "formdata",
					"formdata": [
						{
							"key": "name",
							"value": "Test",
							"type": "text"
						},
						{
							"key": "age",
							"value": "12",
							"type": "text"
						},
						{
							"key": "salary",
							"value": "1000",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "162.55.220.72:5005/user_info_3",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"user_info_3"
					]
				}
```
