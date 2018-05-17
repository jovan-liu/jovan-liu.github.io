# List News
---
# 请求类型: GET
# URL: http://192.168.0.28:8080/svakom/news/page
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
        "newsList": [
            {
                "newsKey": "News",
                "newsId": 1,
                "title": "SVAKOM Supporting Movember Movement by Participating in Events at USA & Australia",
                "content": "SVAKOM has just announced that it will be making an appearance at this year \"Honoring the American Music\" Award taking place in Los Angeles, CA on the 18th of November, 2017. The event organized by Celebrity Connected will be attended by over 200 celebrities in the world of music. SVAKOM hopes to use the opportunity to connect and network with these celebrities some which include past Emmy Award and Grammy Award winners. With Celebrity Connected estimating the combined social media reach of these celebrities at over 300 million people, SVAKOM also intends to use the opportunity to spread awareness about Prostate Cancer as a part of its Movember Movement.",
                "img": "https://www.svakom.net/image/cache/Marketing%20Materials/Movember%20Giveaway-290x218.jpg",
                "url": "https://www.svakom.net/svakom-news?journal_blog_post_id=24",
                "createTime": 1526371474897
            },
            {
                "newsKey": "News",
                "newsId": 2,
                "title": "Svakom Showcases Products at American Music Awards Celebrity Event",
                "img": "https://www.svakom.net/image/cache/Marketing%20Materials/AMA2-290x218.png",
                "url": "https://www.svakom.net/svakom-news?journal_blog_post_id=26",
                "createTime": 1526371532782
            },
            {
                "newsKey": "News",
                "newsId": 3,
                "title": "SVAKOM Attended XBIZ Awards 2018",
                "img": "https://www.svakom.net/image/cache/Marketing%20Materials/WeChat%20Image_20180226103832-290x218.jpg",
                "url": "https://www.svakom.net/svakom-news/SVAKOM Attended XBIZ Awards 2018",
                "createTime": 1526371564516
            }
        ]
    }
}
</code></pre>
