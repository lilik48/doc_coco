Chi tiết tiến độ
===

```
GET umbraco/api/progress/detail/{id}
```

# Nội dung

* Chi tiết tiến độ

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

GET http://118.70.170.147:8089/umbraco/api/progress/detail/1

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

