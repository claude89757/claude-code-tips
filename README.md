## 踩坑动态更新:

- 2026-06-15 美区 app Store 礼品卡充值的 20x max 被封，大概特征：air\pro\mini\iphone多台设备登录
- 2026-05-20 用之前被“拉黑”的海外Safepal信用卡开通extra usage, 通过appStore充值的账号被封了
- 2026-04-11 测试了各种姿势的充值方式
	1. safepal直接官网订阅，秒封；
	2. google pay + safepal 官网订阅，秒封；
	3. apple pay + safepal官网订阅5x max，秒封；
	4. **appstore 礼品卡订阅 20x max，暂时正常**
- 2026-04-09  使用近一个月 20x max的账号被封
- 2026-04-08 anthropic 官网申请了 extra usage, 薅送的200美金额度（⚠️）
- 2026-04-07 清明假期在家用新电脑上使用cc(sub2api) ⚠️
- 2026-03-11
	平时一直在 Mac 本地使用 Claude Code + sub2api，最近改到服务器上使用。结果当天凌晨账号被封，而且还连带封了一些同邮箱后缀的号，连订阅早已过期、很久没用的账号也被波及。
	> 目前怀疑与使用环境突然变化，以及本地和云端两种完全不同环境同时使用有关，这类特征可能更容易触发风控。
	> 另外，封号邮件和退款邮件一起发了
- 2026-03-04 这1个月没有被封号，没有拼车；代理使用自建；claude账号也在公司内网直接登录使用
- 2026-01-18 新注册3个pro和1个5xmax账号，分别挂2个不同类型的梯子，观察中～
- 2026-01-16 1个pro和1个5xmax账号被封号（但都申请退款成功了）；特征：全部都用同一个梯子，朋友是外省，用vscode插件配置sub2api的环境变量接入
- 2026-01-15 通过sub2api，把账号拼车给一个朋友使用
- 2026-01-09 自行搭建 sub2api，注册1个pro和1个5xmax账号（自己单独使用）

---

## 邮箱账号 & AppleID账号

- **苹果的匿名邮箱（推荐,  [隐藏邮件](https://support.apple.com/zh-cn/105078)）**

**- 使用 Cloudflare Email Routing** ([Cloudflare Docs](https://developers.cloudflare.com/email-routing/?utm_source=chatgpt.com))**

- 手动注册 Gmail / Outlook 等邮箱**（稍麻烦，但管理多个注册邮箱会更分散）


- **创建美区 Apple 账号** [account.apple.com](https://account.apple.com/)

> 匿名邮箱或邮件路由是为了快速拥有一个新邮箱，方便注册Anthropic账号或美区苹果账号


---
## 付款方式

- **美区 Apple ID：支付宝充值礼品卡（推荐，步骤相对简单）** [网上教程](https://zhuanlan.zhihu.com/p/636121931)

> 有些美区账号充值礼品卡后，无法正常完成订阅，可拨打 400 666 8800 联系苹果人工客服尝试解决；闲鱼也可购买礼品卡，但优先推荐支付宝渠道，感觉靠谱些～

- **Google Pay**（无安卓手机，没试过，据说可使用国内的visa完成付款）

- **海外信用卡**（较麻烦；SafePal 亲测可用，可规避部分平台税，可私聊拿我的邀请码）

>  - SafePal虚拟信用卡被标记，无法官网直接给新号充值了; 


----
## 科学上网

**自建（推荐：更可控）**

- **方式一**：腾讯云新加坡LH服务器 + 域名 + gost + Cloudflare WARP
- **方式二**：自带美国住宅 IP 的 VPS + 域名 + gost（部分自带 `纯净IP` 的 VPS，可免短信验证注册 claude 账号，如lisahost、yinnet（偶尔又需要验证码，不稳定）

> 可参考：haoel 的「机场 vs 自建」 ([GitHub](https://github.com/haoel/haoel.github.io?utm_source=chatgpt.com))，这个教程比较多文字，但建议耐心看完


**付费机场（不推荐）**

没用过；且好机场通常比较贵，同时稳定性/风险也更不可控。


## 注册anthropic账号和开通订阅

- 注册 Anthropic / Claude 账号：推荐苹果匿名邮箱
- 开通 Anthropic / Claude 订阅：
	- iphone手机用户：挂自建梯子 + 美区App stroe + 充值礼品卡 = 完成订阅
	- 安卓手机用户：挂自建梯子 + google pay （我没实践过）

如果使用美区 Apple ID 的礼品卡余额订阅 Anthropic/Claude 时出现“购买无法完成”，尤其是新号或刚充值后，通过 [Apple 支持](https://support.apple.com/contact) 选择 **Billing and subscriptions / App Store Support / Unable to Purchase** 联系客服解除内购限制，类似案例也可参考 [Apple 中文社区讨论](https://discussionschinese.apple.com/thread/255405755)。

----
## 短信验证码

- **接码平台**：[SMSPool](https://www.smspool.net/purchase/sms)（自己一直在用；有些平台可能收不到 anthropic 的验证码）

- **免短信验证码注册技巧**  
	1. 使用 iOS Claude App 通过 Apple 登录，使用私密转发邮箱（待验证）
	2. 使用比较纯净 IP 的 VPS 搭的梯子，可免短信验证，如使用 yinnet（已亲测）


----
## Claude Code 中转站

- **推荐：Sub2API**（便于管理多个 Claude Code 账号，也方便拼车/共享额度） ([GitHub](https://github.com/Wei-Shaw/sub2api?utm_source=chatgpt.com))

> 暂时不推荐使用Sub2API了

---
## 关于封号

- **封号条件**：确实比较“迷” / 机制复杂，无法一句话说清楚.... 目前个人感受是：**拼车的封号风险最高**；单人使用相对稳定

## 关于退款

- Apple Store订阅方式退款：提交退款申请（一般第一次更容易成功；多次申请可能不一定通过，具体以审核为准） 入口 [Apple 支持](https://reportaproblem.apple.com/)

> apple账号退款的钱，可以用于充其他claude/openai账号会员，但建议等一定时间后操作（3-7天？），但强烈不建议同一个苹果账号在被封号退款后，再重复订阅claude，因为第二次不退款的概括非常小！

- Anthropic官网订阅方式退款：提交工单（帮助中心右下角聊天入口），入口 [Claude-Support](https://support.claude.com/en/articles/9015913-how-to-get-support)

----

## FQA

Q2: 一开始选择订阅哪个套餐？

A2: 可以先订阅20美元的套餐，把整个过程熟悉下，后续可补差价订阅更高级的套餐

Q3: 一个账号可以多个人同时使用么？

A3: 可以，但不推荐。有同事在办公网的条件下，同时3个人使用同一个anthropic账号

Q4: 推荐使用什么邮箱注册anthropic账号呢？

A4: 推荐苹果icloud中的匿名邮箱，方便管理；另外，anthropic官方已支持删除账号，可找回之前被封的旧邮箱来重新注册账号

Q5: Codex/OpenAI怎么订阅？是否需要验证手机？

A5: 验证手机可通过smspool等接码平台解决；或者 使用美区苹果账号注册登录ChatGPT APP，可免短信验证（朋友提供）

