# gpt3-turbo

免费注册用户，支持每天免费调用1万次gpt-3.5-turbo模型。


# 免费对话

- 访问官网注册用户[https://gpt4api.shop/](https://gpt4api.shop/)
- 获取私有控制台密钥。

```shell
POST https://g3.gpt4api.plus/backend-api/conversation
Content-Type: application/json
Authorization:  <控制台秘钥>

{
  "messages": [
    {
      "content": {
        "content_type": "text",
        "parts": [
          "你是gpt-3还是4?"
        ]
      }
    }
  ]
}
```