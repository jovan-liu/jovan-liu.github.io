# Save Item
---
# 请求类型: POST
# URL: http://192.168.0.28:8080/svakom/item/save
# 参数:
参数名    | 说明    | 类型
--------- | ------- | ----
itemId    | 产品ID   | Long
oldItemId | 旧新闻ID | Long
itemName  | 产品名称 | String
itemCode  | 产品编号 | String
itemDesc  | 产品描述 | String
price     | 价格     | Double
icon      | 封面图片 | String
url       | 产品链接 | String
### 备注: 若传入oldItemId参数，则为更新产品
# 返回值:
<pre><code>
{
    "code": 1000
}
</code></pre>
