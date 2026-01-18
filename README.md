## 1) 邮箱账号

- **使用 Cloudflare Email Routing（推荐，方便统一管理别名邮箱）** ([Cloudflare Docs](https://developers.cloudflare.com/email-routing/?utm_source=chatgpt.com))
- **手动注册 Gmail / Outlook 等邮箱**（更麻烦，但管理多个注册邮箱会更分散）


----
## 2) 付款方式

- **美区 Apple ID：支付宝充值礼品卡（推荐，步骤相对简单）** [网上教程](https://zhuanlan.zhihu.com/p/636121931)
- **Google Pay**（没试过）
- **海外信用卡**（较麻烦；SafePal 亲测可用，可规避部分平台税，我的邀请码：103119）

> **备注**：最近听说 Apple Pay 可能可以绑定招行 Visa 来订阅海外 AI 服务


----
## 3) 科学上网

### 自建（推荐：更可控）

**推荐组合**：海外服务器 + 域名 + gost + Cloudflare WARP（可用300 元腾讯云体验券）
1. **方式一**：腾讯云新加坡服务器 + 域名 + gost + Cloudflare WARP
2. **方式二**：自带美国住宅 IP 的 VPS（如[Lisahost](https://lisahost.com/aff.php?aff=7066)） + 域名 + gost
	
> 可参考：haoel 的「机场 vs 自建」 ([GitHub](https://github.com/haoel/haoel.github.io?utm_source=chatgpt.com))


### 付费机场（不推荐）

没用过；且好机场通常比较贵，同时稳定性/风险也更不可控。


----
## 4) 短信验证码

- **接码平台：SMSPool**（自己一直在用；有些平台可能收不到 anthropic 的验证码）


----
## 5) Claude Code 中转站

- **推荐：Sub2API**（便于管理多个 Claude Code 账号，也方便拼车/共享额度） ([GitHub](https://github.com/Wei-Shaw/sub2api?utm_source=chatgpt.com))


----
## 6) 关于封号

- **封号条件**：确实比较“玄学”。个人感受是：**拼车的封号风险最高**；单人使用相对稳定，但也更贵（付费上班～）

## 7) 关于退款

- Apple Store订阅方式退款：可以通过 Apple 的退款入口提交申请（一般第一次更容易成功；多次申请可能不一定通过，具体以审核为准） [Apple 支持](https://support.apple.com/en-us/118223?utm_source=chatgpt.com)](https://reportaproblem.apple.com/status)

- Anthropic官方网站订阅方式退款：帮助中心右下角聊天入口提交工单：[claude-support](https://support.claude.com/en/articles/9015913-how-to-get-support)


> **个人真实案例**：
> 一个 Apple 账号订阅了 Max，用了一段时间后被封号；退款全退回到 Apple 账号余额中。短期内该 Apple 账号无法继续为其他 anthropic 账号开 Max，过一段时间后又恢复可用。


----
## 7) 为什么还要用 Claude Code？没有其他 AI 编程工具平替么？

- 额……
