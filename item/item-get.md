# Get Item by itemId
---
# 请求类型: GET
# URL: http://192.168.0.28:8080/svakom/item/get
# 参数:
参数名  | 说明   | 类型
-----  | ------ | ----
itemId | 产品ID | Long
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "item": {
            "itemKey": "Item",
            "itemId": 1,
            "itemName": "SVAKOM BONNIE Double Pleasure Vibrator",
            "itemCode": "SVAKOM Bonnie",
            "itemDesc": "Double Pleasure Vibrator",
            "price": 99.99,
            "icon": "https://www.svakom.net/image/cache/catalog/bonnie/DSC00901-200x200.jpg",
            "url": "https://www.svakom.net/product/Bonnie",
            "createTime": 1526374259620
        }
    }
}
</code></pre>
