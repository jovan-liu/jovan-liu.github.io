# Sava Customer
---
# 请求类型: POST
# URL: http://192.168.0.28/svakom/customer/save
# 参数:
参数名 | 说明                   | 类型
----- |----------------------- | ----
hardwareId | 硬件设备ID         | String
deviceId   | 手机ID            | String
category   | 类型：ios、android | String
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "customer": {
            "customerId": 1003,
            "hardwareId": "miuuunbubi",
            "deviceId": "asdasdasda",
            "category": "ios",
            "name": "Anonymous",
            "updateTime": 1526635788411
        }
    }
}
</code></pre>
