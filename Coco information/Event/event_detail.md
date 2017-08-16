Danh sách sự kiện
===

```
GET umbraco/api/events/detail/{id}
```

# Nội dung

* Lấy danh sách sự kiện

# Request Header

| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | Content-Type | application/json |  |

# URL Parameter
| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | id | ${id} | |

# Query Parameter

Không có

# Response Body

Không có

# Example

GET http://118.70.170.147:8089/umbraco/api/events/detail/0

```
{
    "status": 200,
    "type": "success",
    "description": "normal",
    "result_data":              
           {				
            	"title": "leo pellentesque ultrices mattis odio donec vitae nisi nam ultrices libero",
            	"content": "imperdiet et commodo vulputate justo in blandit ultrices enim lorem",            	            	
				"location":"Số 1 Đào Duy Anh",
				"create_date":"01/02/2017"
            }        
}


```

