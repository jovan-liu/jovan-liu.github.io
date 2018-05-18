# Get Customer
---
# 请求类型: GET
# URL: http://192.168.0.28/svakom/customer/get
# 参数:
参数名 | 说明            | 类型
----- |---------------- | ----
customerId | 用户ID     | Long
hardwareId | 硬件设备ID | String
deviceId   | 手机ID     | String
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "customer": {
            "customerId": 1000,
            "hardwareId": "fce83717224a616_android",
            "deviceId": "fce83717224a616",
            "category": "android",
            "name": "Admin",
            "updateTime": 1526367611757
        }
    }
}
</code></pre>
