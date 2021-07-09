```json
{
			"name": "EP_4",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "162.55.220.72:5005/object_info_2?name=Test_name&age=12&salary=1000",
					"host": [
						"162",
						"55",
						"220",
						"72"
					],
					"port": "5005",
					"path": [
						"object_info_2"
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
					"name": "EP_4",
					"originalRequest": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "162.55.220.72:5005/object_info_2?name=Test_name&age=12&salary=1000",
							"host": [
								"162",
								"55",
								"220",
								"72"
							],
							"port": "5005",
							"path": [
								"object_info_2"
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
							"value": "240"
						},
						{
							"key": "Server",
							"value": "Werkzeug/2.0.1 Python/3.8.10"
						},
						{
							"key": "Date",
							"value": "Fri, 09 Jul 2021 07:47:22 GMT"
						}
					],
					"cookie": [],
					"body": "{\n    \"person\": {\n        \"u_age\": 12,\n        \"u_name\": [\n            \"Test_name\",\n            1000,\n            12\n        ],\n        \"u_salary_5_years\": 4200\n    },\n    \"qa_salary_after_1.5_year\": 3300,\n    \"qa_salary_after_12_months\": 2700,\n    \"qa_salary_after_3.5_years\": 3800,\n    \"qa_salary_after_6_months\": 2000,\n    \"start_qa_salary\": 1000\n}"
				}
			]
```