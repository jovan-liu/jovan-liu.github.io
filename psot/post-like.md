# Like Post
---
# 请求类型: POST
# URL: http://192.168.0.28:8080/svakom/post/like
# 参数:
参数名      | 说明                       | 类型
---------- |--------------------------- | ----
postId     | 帖子ID                     | Long
customerId | 用户ID                     | Long
type       | 类型（1为点赞，0为取消点赞） | Int
# 返回值:
<pre><code>
{
    "code": 1000
}
</code></pre>
