
## 0) 动态更新:

- 2026-01-09 自行搭建 sub2api，注册1个pro和1个5xmax账号（自己单独使用）
- 2026-01-15 通过sub2api，把账号拼车给一个朋友使用
- 2026-01-16 1个pro和1个5xmax账号被封号（但都申请退款成功了）；特征：全部都用同一个梯子，朋友是外省，用vscode插件配置sub2api的环境变量接入
- 2026-01-18 新注册3个pro和1个5xmax账号，分别挂2个不同类型的梯子，观察中～

---
## 1) 邮箱账号 & AppleID账号

- **使用 Cloudflare Email Routing（推荐，方便统一管理别名邮箱）** ([Cloudflare Docs](https://developers.cloudflare.com/email-routing/?utm_source=chatgpt.com))

- **手动注册 Gmail / Outlook 等邮箱**（稍麻烦，但管理多个注册邮箱会更分散）


- **创建美区 Apple 账号** [account.apple.com](https://account.apple.com/)

----
## 2) 付款方式

- **美区 Apple ID：支付宝充值礼品卡（推荐，步骤相对简单）** [网上教程](https://zhuanlan.zhihu.com/p/636121931)

- **Google Pay**（没试过）

- **海外信用卡**（较麻烦；SafePal 亲测可用，可规避部分平台税，可私聊拿我的邀请码）


----
## 3) 科学上网

**自建（推荐：更可控）**

- **方式一**：腾讯云新加坡LH服务器 + 域名 + gost + Cloudflare WARP  （可用300 元腾讯云体验券）
- **方式二**：自带美国住宅 IP 的 VPS + 域名 + gost（部分自带 `纯净IP` 的 VPS，可免短信验证注册 claude 账号，如lisahost、yinnet）

> 可参考：haoel 的「机场 vs 自建」 ([GitHub](https://github.com/haoel/haoel.github.io?utm_source=chatgpt.com))，这个教程比较多文字，但建议耐心看完


**付费机场（不推荐）**

没用过；且好机场通常比较贵，同时稳定性/风险也更不可控。


----
## 4) 短信验证码

- **接码平台**：[SMSPool](https://www.smspool.net/purchase/sms)（自己一直在用；有些平台可能收不到 anthropic 的验证码）

- **免短信验证码注册技巧**  
	1. 使用 iOS Claude App 通过 Apple 登录，使用私密转发邮箱（待验证）
	2. 使用比较纯净 IP 的 VPS 搭的梯子，可免短信验证，如使用 yinnet（已亲测）


----
## 5) Claude Code 中转站

- **推荐：Sub2API**（便于管理多个 Claude Code 账号，也方便拼车/共享额度） ([GitHub](https://github.com/Wei-Shaw/sub2api?utm_source=chatgpt.com))


---
## 6) 关于封号

- **封号条件**：确实比较“迷”，还在试图摸索....目前个人感受是：**拼车的封号风险最高**；单人使用相对稳定，但也更贵（付费上班～）

## 7) 关于退款

- Apple Store订阅方式退款：提交退款申请（一般第一次更容易成功；多次申请可能不一定通过，具体以审核为准） 入口 [Apple 支持](https://reportaproblem.apple.com/)

> apple账号退款的钱，可以用于充其他claude账号会员，但建议等一定时间后操作（3-7天？）

- Anthropic官网订阅方式退款：提交工单（帮助中心右下角聊天入口），入口 [Claude-Support](https://support.claude.com/en/articles/9015913-how-to-get-support)


> **个人真实案例**：
> 一个 Apple 账号订阅了 Max，用了一段时间后被封号；退款全退回到 Apple 账号余额中。短期内该 Apple 账号无法继续为其他 anthropic 账号开 Max，过一段时间后又恢复可用。(这个号又第二天立刻被封了（用的 lisahost 的住宅 IP，但也可能由于之前被封过）....)

----
## 7) 为什么还要用 Claude Code？没有其他 AI 编程工具平替么？

- 额……


----

欢迎纠正和补充～
