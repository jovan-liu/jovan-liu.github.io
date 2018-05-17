# List Item
---
# 请求类型: GET
# URL: http://192.168.0.28:8080/svakom/item/page
# 参数:
参数名 | 说明                             | 类型
----- |--------------------------------- | ----
endId | 上一页的最后一条记录(第一页不用传)  | Long
limit | 每页多少条 （默认20条）            | Int
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "itemList": [
            {
                "itemKey": "Item",
                "itemId": 1,
                "itemName": "SVAKOM BONNIE Double Pleasure Vibrator",
                "itemCode": "SVAKOM Bonnie",
                "itemDesc": "Double Pleasure Vibrator",
                "price": 99.99,
                "icon": "https://www.svakom.net/image/cache/catalog/bonnie/DSC00901-200x200.jpg",
                "url": "https://www.svakom.net/product/Bonnie",
                "createTime": 1526374259620
            },
            {
                "itemKey": "Item",
                "itemId": 2,
                "itemName": "SVAKOM Daisy",
                "itemCode": "SVAKOM Daisy",
                "itemDesc": "Daisy",
                "price": 99.99,
                "icon": "https://www.svakom.net/image/cache/other%20images/1508137602993-200x200.jpg",
                "url": "https://www.svakom.net/product/Daisy",
                "createTime": 1526374296071
            },
            {
                "itemKey": "Item",
                "itemId": 3,
                "itemName": "SVAKOM Barbara Ultra Soft Vibrator",
                "itemCode": "SVAKOM Barbara",
                "itemDesc": "Barbara Ultra Soft Vibrator",
                "price": 114.99,
                "icon": "https://www.svakom.net/image/cache/data/thelovevibes/barbara/146020231643-200x200.jpg",
                "url": "https://www.svakom.net/product/Barbara?poip_ov=13",
                "createTime": 1526374025184
            }
        ],
        "endId": 3
    }
}
</code></pre>
