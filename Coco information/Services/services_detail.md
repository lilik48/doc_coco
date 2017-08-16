Chi tiết dịch vụ cocobay
===

```
GET umbraco/api/services/detail/{id}
```

# Nội dung

* Chi tiết dịch vụ

# Request Header

| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | Content-Type | application/json |  |

# URL Parameter
| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | id | ${id} | Id tin tức |


# Query Parameter

Không có

# Response Body

Không có


# Example

GET http://localhost:8080/umbraco/api/services/detail/1

```
{
    "status": 200,
    "type": "success",
    "description": "normal",
    "result_data":               		
           {				
            	"title": "leo pellentesque ultrices mattis odio donec vitae nisi nam ultrices libero",
            	"content": "imperdiet et commodo vulputate justo in blandit ultrices enim lorem",            	            	
				"create_date":"01/02/2017"
            }
}


```

