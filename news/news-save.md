# Save News
---
# 请求类型: POST
# URL: http://192.168.0.28:8080/svakom/news/save
# 参数:
参数名     | 说明           | 类型
-----     |--------------- | ----
newsId    | 新闻ID          | Long
oldNewsId | 旧新闻ID        | Long
title     | 新闻标题        | String
brief     | 新闻摘要        | String
img       | 新闻封面图片地址 | String
content   | 新闻内容        | String
url       | 新闻全文链接     | String
### 备注: 若传入oldNewsId参数，则为更新新闻
# 返回值:
<pre><code>
{
    "code": 1000
}
</code></pre>
