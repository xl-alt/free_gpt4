## GPT-4-free-api

### 简介

> ❗️免费API Key仅可用于个人非商业用途，教育，非营利性科研工作中。严禁商用，严禁大规模训练商用模型！

> 该网站和api高度重视隐私，致力于保护其用户的隐私。该项目不会以任何方式收集、记录或存储用户输入的任何文本或由 OpenAI 服务器返回的任何文本。该项目不会向 OpenAI 或任何第三方提供有关 API 调用者的身份的任何信息，所有文本消息 均保存在本地。

但OpenAI官方会根据其[数据使用政策](https://platform.openai.com/docs/data-usage-policies)保留 30 天的数据。

#### 👏广告

[国内镜像网站](https://docs.chatanywhere.com.cn/) 支持GPT4.0, DALLE, Claude, Azure Openai, sd等集成部署。详情查看 [https://wxblog.xyz](https://wxblog.xyz)

#### apikey 获取

**apikey 获取地址：[https://wxblog.xyz](https://wxblog.xyz)  登陆后前往个人中心查看key，加入QQ群 743876738，接口有问题会及时在群内通知哦！！**

**api 分为付费版和免费版,付费版稳定性较好**

付费版支持模型包括【"gpt-3.5-turbo-0301","gpt-3.5-turbo","gpt-3.5-turbo-0613","gpt-3.5-turbo-16k","gpt-3.5-turbo-16k-0613","gpt-4","gpt-4-0613","claude-instant-100k","claude-instant"】

免费版支持模型包括【"`gpt-4`","`gpt-4-0613","gpt-3.5"】

### api 请求地址及参数

#### 付费版

请求地址：`https://wxblog.xyz/api/blog/v1/chat/completions`

请求headers: `Authorization: Bearer YOURKEY`

参数说明：

```JavaScript
{
    "messages": [
        {
            "role": "user",
            "content": "你是谁"
        }
    ], // messages 必填
    "stream": true, //  是否流式输出
    "model": "gpt-4-0613",  // 选择模型必填
    "temperature": 0.5, // 设置AI思维扩展度
    "presence_penalty": 2
}
```

#### 免费版

请求地址：`https://wxblog.xyz/api/blog/free/v1/chat/completions`

请求headers: `Authorization: Bearer YOURKEY`

参数说明：

```JavaScript
{
    "messages": [
        {
            "role": "user",
            "content": "你是谁"
        }
    ], // messages 必填
    "stream": true, //  是否流式输出
    "model": "gpt-4-0613",  // 选择模型必填
    "temperature": 0.5, // 设置AI思维扩展度
    "presence_penalty": 2
}
```

#### api优点

1. 付费与免费版均支持 4.0 可供使用
2. 与官方完全一致的接口标准（免费版仅输出文本，不能设置system），兼容各种软件/插件。
3. 支持流式响应。
4. 国内线路使用动态加速.
5. 无需科学上网，国内环境直接可用。
6. 个人完全免费使用。

#### 如何使用

国内稳定站点：[https://www.openapi.technology/](https://www.openapi.technology/)

在设置中将 `接口地址` 更改为上诉请求地址（tips: 地址中 /v1/chat/completions 请勿粘贴上去`）

在apikey处 填写您的apikey即可使用



#### 国内镜像网站

[https://wxblog.xyz](https://wxblog.xyz)  此网站可以 直接使用无需翻墙，付费版api使用只需要在此网站升级即可,有问题可以加QQ群留言。我们会随时会接口进行维护，确保接口的稳定性。















