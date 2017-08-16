Tổng quan dự án
===

```
GET umbraco/api/overview/detail
```

# Nội dung

* Tổng quan dự án

# Request Header

| # | Item | Parameter | Ghi chú |
|---|---|---|---|
| 1 | Content-Type | application/json |  |

# URL Parameter
Không có


# Query Parameter

Không có

# Response Body

Không có


# Example

GET http://localhost:8080/umbraco/api/overview/detail

```
{
    "status": 200,
    "type": "success",
    "description": "normal",
    "result_data":               		
           {				
            	"title": "leo pellentesque ultrices mattis odio donec vitae nisi nam ultrices libero",
            	"short_content": "imperdiet et commodo vulputate justo in blandit ultrices enim lorem",
				"content": "imperdiet et commodo vulputate justo in blandit ultrices enim lorem",
                "img_url": "http://dummyimage.com/206x155.jpg",   
				"create_date":"01/02/2017"
            }
}


```

