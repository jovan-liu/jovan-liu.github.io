# Update Customer
---
# 请求类型: POST
# URL: http://192.168.0.28/svakom/customer/update
# 参数:
参数名 | 说明            | 类型
----- |---------------- | ----
customerId | 用户ID     | Long
hardwareId | 硬件设备ID | String
deviceId   | 手机ID     | String
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "customer": {
            "customerId": 1003,
            "hardwareId": "12qwerq",
            "deviceId": "asdasdasda",
            "category": "ios",
            "name": "Anonymous",
            "updateTime": 1526636058076
        }
    }
}
</code></pre>
