# Get News by newsId
---
# 请求类型: GET
# URL: http://localhost:8080/svakom/news/get
# 参数:
参数名  | 说明          | 类型
------ | ------------- | ----
newsId | 新闻ID，非自增 | Long
# 返回值:
<pre><code>
{
    "code": 1000,
    "data": {
        "news": {
            "newsKey": "News",
            "newsId": 2,
            "title": "Svakom Showcases Products at American Music Awards Celebrity Event",
            "img": "https://www.svakom.net/image/cache/Marketing%20Materials/AMA2-290x218.png",
            "url": "https://www.svakom.net/svakom-news?journal_blog_post_id=26",
            "createTime": 1526371532782
        }
    }
}
</code></pre>
