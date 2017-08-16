Danh sách sự kiện
===

```
GET umbraco/api/events/list/?pageIndex={pageIndex}&pageSize={pageSize}
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
| 1 | pageIndex | ${pageIndex} | Trang hiện tại |
| 2 | pageSize | ${pageSize} | Số bản ghi trong trong |

# Query Parameter

Không có

# Response Body

Không có

# Example

GET http://118.70.170.147:8089/umbraco/api/events/list/?pageIndex=0

```
{
    "status": 200,
    "type": "success",
    "description": "normal",
    "result_data":  
        [
           {
				"id":"0",
            	"title": "leo pellentesque ultrices mattis odio donec vitae nisi nam ultrices libero",
            	"short_content": "imperdiet et commodo vulputate justo in blandit ultrices enim lorem",            	
            	"img_url": "http://dummyimage.com/147x232.jpg",
				"location":"Số 1 Đào Duy Anh",
				"location_id":"2",
				"create_date":"01/02/2017"
            },
            {
				"id":"1",
            	"title": "convallis morbi odio odio elementum eu interdum eu tincidunt in leo maecenas pulvinar lobortis est",
            	"short_content": "ut dolor morbi vel lectus in quam fringilla rhoncus mauris",            	
            	"img_url": "http://dummyimage.com/206x155.jpg",
				"location":"Sân vận động quốc gia Mỹ Đình",
				"location_id":"3",
				"create_date":"01/02/2017"
            }
        ]
}


```

