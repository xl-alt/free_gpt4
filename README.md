## GPT-4-free-api

### 简介

> ❗️ 代码更新，最新网站支持GPT-4-1106，GPT-4-0613,GPT-4,GPT-3.5各个模型，cluade-2 以及 az-gpt-4等等。

> ❗️免费API Key仅可用于个人非商业用途，教育，非营利性科研工作中。严禁商用，严禁大规模训练商用模型！

> 该网站和api高度重视隐私，致力于保护其用户的隐私。该项目不会以任何方式收集、记录或存储用户输入的任何文本或由 OpenAI 服务器返回的任何文本。该项目不会向 OpenAI 或任何第三方提供有关 API 调用者的身份的任何信息，所有文本消息 均保存在本地。

但OpenAI官方会根据其[数据使用政策](https://platform.openai.com/docs/data-usage-policies)保留 30 天的数据。

#### 👏广告

支持GPT4.0, DALLE, Claude, Azure Openai, sd等集成部署。详情查看 [[https://wxblog.xyz](https://ngedlktfticp.cloud.sealos.io/)]([https://wxblog.xyz](https://ngedlktfticp.cloud.sealos.io/))  注册即送 20 $

#### apikey 获取

**apikey 获取地址：[https://ngedlktfticp.cloud.sealos.io/]([https://wxblog.xyz](https://ngedlktfticp.cloud.sealos.io/))  登陆后前往个人中心查看key，加入QQ群 743336487，接口有问题会及时在群内通知哦！！**

**api 完全免费，支持模型包括以下模型，可以根据自己需求调用**

支持模型包括 <div class="semi-card-body"><h6 class="semi-typography semi-typography-primary semi-typography-normal semi-typography-h6">可用模型</h6><div style="margin-top: 10px;"><div class="semi-space semi-space-align-center semi-space-horizontal semi-space-wrap semi-space-tight-horizontal semi-space-tight-vertical" x-semi-prop="children"><div aria-label="Tag: az-gpt-4" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">az-gpt-4</div></div><div aria-label="Tag: claude-2" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">claude-2</div></div><div aria-label="Tag: claude-instant-1" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">claude-instant-1</div></div><div aria-label="Tag: dall-e-3" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">dall-e-3</div></div><div aria-label="Tag: gpt-3.5-turbo" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo</div></div><div aria-label="Tag: gpt-3.5-turbo-0301" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-0301</div></div><div aria-label="Tag: gpt-3.5-turbo-0613" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-0613</div></div><div aria-label="Tag: gpt-3.5-turbo-1106" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-1106</div></div><div aria-label="Tag: gpt-3.5-turbo-16k" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-16k</div></div><div aria-label="Tag: gpt-3.5-turbo-16k-0613" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-16k-0613</div></div><div aria-label="Tag: gpt-3.5-turbo-instruct" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-3.5-turbo-instruct</div></div><div aria-label="Tag: gpt-4" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-4</div></div><div aria-label="Tag: gpt-4-0314" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-4-0314</div></div><div aria-label="Tag: gpt-4-0613" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-4-0613</div></div><div aria-label="Tag: gpt-4-1106-preview" tabindex="0" class="semi-tag semi-tag-default semi-tag-square semi-tag-light semi-tag-cyan-light" role="button"><div class="semi-tag-content semi-tag-content-ellipsis">gpt-4-1106-preview</div></div></div></div></div>

### api 请求地址及参数

#### 付费版

请求地址：`https://ngedlktfticp.cloud.sealos.io/v1/chat/completions`

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

1. 高速免费使用各个模型
2. 与官方完全一致的接口标准，兼容各种软件/插件。
3. 支持流式响应。
4. 国内线路使用动态加速.
5. 无需科学上网，国内环境直接可用。
6. 个人完全免费使用。

#### 如何使用

国内稳定站点：[https://www.openapi.technology/](https://www.openapi.technology/)

在设置中将 `接口地址` 更改为上诉请求地址（tips: 地址中 /v1/chat/completions 请勿粘贴上去`）

在apikey处 填写您的apikey即可使用

















