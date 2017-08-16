Danh sách lịch trình xe bus
===

```
GET umbraco/api/bus/ScheduleList/?pageIndex={pageIndex}&pageSize={pageSize}
```

# Nội dung

* Lấy danh lịch trình xe bus

# Request Header

| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | Content-Type | application/json |  |

# URL Parameter
| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | pageIndex | ${pageIndex} | Trang hiện tại |
| 2 | pageSize | ${pageSize} | Số bản ghi trong trong |

# Query Parameter

Không có

# Response Body

Không có

# Example

GET http://118.70.170.147:8089/umbraco/api/bus/ScheduleList/?pageIndex=0

```
{
	"status": 200,
	"type": "success",
	"description": "normal",
	"result_data": [
		{
			"id": "0",
			"name": "xe 1",
			"time_between_bus": "15",
			"cost": "7000,000",
			"quantity": "50",
			"time_begin_end": "06:00 - 21:00",
			"schedule_leave": "Bến xe A - Nhà Hàng 1 - Nhà hàng 2 - Bến xe B",
			"schedule_arive": "Bến xe B - Nhà Hàng 3 - Nhà hàng 4 - Bến xe A",
			"bus_list": [
				{
					"id": "0",
					"seat_number": "24",
					"time_leave": "10:00",
					"license_plate": "29X9-9999",
					"driver_list": [
						{
							"id": "0",
							"full_name": "Nguyễn Tử Quảng",
							"phone": "0988988988",
							"address": "Ninh Bình Việt nam",
							"driver_license": "B1",
							"sex": "Name",
							"birthday": "01/02/1970"
						},
						{
							"id": "1",
							"full_name": "Nguyễn Tử Hoàng",
							"phone": "0999999999",
							"address": "Ninh Bình Việt nam",
							"driver_license": "B2",
							"sex": "Name",
							"birthday": "01/02/1972"
						}
					]
				},
				{
					"id": "1",
					"seat_number": "14",
					"time_leave": "09:00",
					"license_plate": "30X9-9999",
					"driver_list": [
						{
							"id": "0",
							"full_name": "Nguyễn Tử Văn",
							"phone": "0988988988",
							"address": "Ninh Bình Việt nam",
							"driver_license": "B1",
							"sex": "Name",
							"birthday": "01/02/1970"
						},
						{
							"id": "1",
							"full_name": "Mai Siêu Phong",
							"phone": "0999999999",
							"address": "Ninh Bình Việt nam",
							"driver_license": "B2",
							"sex": "Name",
							"birthday": "01/02/1972"
						}
					]
				}
			],
			"create_date": "01/02/2017 10:21"
		}
	]
}


```

