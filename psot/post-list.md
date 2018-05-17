# List Post
---
# 请求类型: GET
# URL: http://192.168.0.28:8080/svakom/post/page
# 参数:
参数名      | 说明                             | 类型
-----      |--------------------------------- | ----
customerId | 用户ID                           | Long
endId      | 上一页的最后一条记录(第一页不用传)  | Long
limit      | 每页多少条 （默认20条）            | Int
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "postClientList": [
            {
                "post": {
                    "postKey": "Post",
                    "postId": 1526353590754,
                    "customerId": 1000,
                    "userName": "Admin",
                    "content": "jovanTesting post C",
                    "commentNumber": 0,
                    "likeIds": [
                        0
                    ],
                    "likeNumbers": 0,
                    "like": 0,
                    "createTime": 1526353590754
                },
                "customer": {
                    "customerId": 1000,
                    "hardwareId": "fce83717224a616_android",
                    "deviceId": "fce83717224a616",
                    "category": "android",
                    "name": "Admin",
                    "updateTime": 1526367611757
                }
            },
            {
                "post": {
                    "postKey": "Post",
                    "postId": 1526353580961,
                    "customerId": 1000,
                    "userName": "Admin",
                    "content": "jovanTesting post B",
                    "commentNumber": 0,
                    "likeIds": [
                        1002
                    ],
                    "likeNumbers": 1,
                    "like": 1,
                    "createTime": 1526353580961
                },
                "customer": {
                    "customerId": 1000,
                    "hardwareId": "fce83717224a616_android",
                    "deviceId": "fce83717224a616",
                    "category": "android",
                    "name": "Admin",
                    "updateTime": 1526367611757
                }
            }
        ],
        "endId": 1526353580961
    }
}
</code></pre>
