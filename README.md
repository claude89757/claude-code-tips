# Claude Code 订阅与使用踩坑记录

个人使用 Claude / Codex 订阅一段时间以来的实践记录，涵盖账号注册、付款订阅、网络代理、封号与退款等环节，并持续更新踩坑日志。内容均为个人经验，仅供参考。

---

## 当前账号使用情况

- ✨ Claude 20x Max 订阅：**京东购买紫卡 + 注册美区 PayPal + 招行万事达 + 苹果商店订阅 + voyracloud VPS + gost**
- Codex 20x Max 订阅：通过 starryblu 和 美区 PayPal + 美区苹果账号（两个方式都可成功订阅）
- 手机网络：Claude App 通过自建代理使用（iOS App：Shadowrocket）

---

## 关于封号

封号是长期存在的，掌握 “**封号 → 退款 ♻️ → 注册订阅**” 的 Loop。

- **封号条件**：确实比较“迷” / 机制复杂，无法一句话说清楚……目前个人感受是：**拼车的封号风险最高**；单人使用 + 稳定环境（不乱切 IP 和设备）相对稳定

打听到的一些方式躲过了这次“大封号”：

- Gmail，搬瓦工 IP，设备少，苹果礼物卡，美国地址/台湾地址
- 外国朋友家放 Mac mini + ZeroTier + 外国手机 + 苹果商店 PayPal

> 备注：仅供参考，博主未亲测

---

## 关于退款

⚠️ **封号后，请第一时间申请退款，无论还剩多少天，无特殊情况，基本 100% 全额退款**

- **信用卡扣款**：通过绑定**招商万事达 / VISA 信用卡**扣款的，可直接在招行信用卡 App（掌上生活）对该笔扣款发起“疑问交易处理”，招行客服非常给力！
  > 案例：Google 一开始不给退款，招行介入后“改口”，最终退款成功。

- **Apple Store 订阅**：提交退款申请（一般第一次更容易成功；多次申请可能不一定通过，具体以审核为准），入口 [Apple 支持](https://support.apple.com/zh-cn/118223)

  > Apple 账号退款的钱，可以用于充其他 Claude / OpenAI 账号会员，但建议等一定时间后操作（3-7 天？）。强烈不建议同一个苹果账号在被封号退款后，再重复订阅 Claude，因为第二次退款成功的概率非常小！

- **Anthropic 官网订阅**：提交工单（帮助中心右下角聊天入口），入口 [Claude Support](https://support.claude.com/en/articles/9015913-how-to-get-support)

---

## 踩坑动态更新

<details>
<summary>Claude 账号使用 / 封号记录（点击展开）</summary>

- 2026-09-24 我又回来了
- 2026-06-29 美区 App Store 礼品卡充值的 20x Max 被封，大概特征：在公司网络使用，网络环境不稳定；周末开的 Max，到工位使用后立刻没了
- 2026-06-15 美区 App Store 礼品卡充值的 20x Max 被封，大概特征：Air / Pro / mini / iPhone 多台设备登录
- 2026-05-20 用之前被“拉黑”的海外 SafePal 信用卡开通 extra usage，通过 App Store 充值的账号被封了
- 2026-04-11 测试了各种姿势的充值方式
  1. SafePal 直接官网订阅，秒封；
  2. Google Pay + SafePal 官网订阅，秒封；
  3. Apple Pay + SafePal 官网订阅 5x Max，秒封；
  4. **App Store 礼品卡订阅 20x Max，暂时正常**
- 2026-04-09 使用近一个月的 20x Max 账号被封
- 2026-04-08 Anthropic 官网申请了 extra usage，薅送的 200 美金额度（⚠️）
- 2026-04-07 清明假期在家用新电脑上使用 CC（sub2api）⚠️
- 2026-03-11 平时一直在 Mac 本地使用 Claude Code + sub2api，最近改到云服务器上使用。结果当天凌晨账号被封，而且还连带封了一些同邮箱后缀的号，连订阅早已过期、很久没用的账号也被波及。
  > 目前怀疑与使用环境突然变化，以及本地和云端两种完全不同环境同时使用有关，这类特征可能更容易触发风控。
  >
  > 另外，封号邮件和退款邮件是一起发的。
- 2026-03-04 这 1 个月没有被封号，没有拼车；代理使用自建；Claude 账号在固定的公司网络环境下直接登录使用
- 2026-01-18 新注册 3 个 Pro 和 1 个 5x Max 账号，分别挂 2 个不同类型的梯子，观察中～
- 2026-01-16 1 个 Pro 和 1 个 5x Max 账号被封号（但都申请退款成功了）；特征：全部都用同一个梯子，朋友在外省，用 VS Code 插件配置 sub2api 的环境变量接入
- 2026-01-15 通过 sub2api，把账号拼车给一个朋友使用
- 2026-01-09 自行搭建 sub2api，注册 1 个 Pro 和 1 个 5x Max 账号（自己单独使用）

</details>

---

## 邮箱账号 & Apple ID 账号

- **苹果的隐藏邮箱（推荐，[Apple 隐藏邮件地址](https://support.apple.com/zh-cn/guide/icloud/mme38e1602db/icloud)）**
- **Cloudflare Email Routing**（[Cloudflare Docs](https://developers.cloudflare.com/email-routing/)）
- **手动注册 Gmail / Outlook 等邮箱**（稍麻烦，但管理多个注册邮箱会更分散）
- **创建美区 Apple 账号**：[account.apple.com](https://account.apple.com/)

> 匿名邮箱或邮件路由是为了快速拥有一个新邮箱，方便注册 Anthropic 账号或美区苹果账号。

⚠️ **特别注意**：新开的美区苹果账号不要立刻充礼品卡进去，不然可能有被锁定账号的风险（封号），后续解锁也很麻烦，建议先用手机养一下新的美区苹果账号。**我已经被苹果风控禁用了 2 个美区账号，里面还有钱，联系苹果客服也不给解封……**

---

## 付款方式

- **美区 PayPal + 招行万事达信用卡**：在京东购买美国的紫卡，每个月 3 刀保号
- **Google Play 商店**：带完整谷歌框架的安卓手机，在美区 Play 商店下载 Claude App 并应用内订阅（可使用国内 Visa 卡）
- **美区 Apple ID：充值礼品卡**
  - 方式 1：美区苹果官网购买礼品卡（[参考教程](https://linux.do/t/topic/2518138)，支付不一定很顺利）
  - 方式 2：支付宝：城市切换成旧金山，右下角礼品卡
  - 方式 3：闲鱼（不太推荐）
- **海外信用卡**：如 starryblu、SafePal（较麻烦；SafePal 亲测可用，可规避部分平台税）
  > 我的 SafePal 虚拟信用卡已被标记，无法在官网直接给新号充值了。

> 最近苹果新建账号风控更严格了，比较烦；
> 有些美区账号充值礼品卡后，无法正常完成订阅，可拨打 400 666 8800 联系苹果人工客服尝试解决；闲鱼也可购买礼品卡，但优先推荐支付宝渠道，感觉靠谱些～

---

## 科学上网

### 自建（推荐：更可控）

- ~~**方式一**：腾讯云新加坡轻量应用服务器 + 域名 + gost + Cloudflare WARP~~（不推荐了）
- **方式二**：自带美国住宅 IP 的 VPS + 域名 + gost（部分自带 `纯净IP` 的 VPS，可免短信验证注册 Claude 账号，如 voyracloud、lisahost、yinnet（偶尔又需要验证码，不稳定））

> 住宅 IP 的 VPS 推荐：[voyracloud](https://www.voyracloud.com/?ref_code=8SXL2Y3G)
>
> 可参考：haoel 的「机场 vs 自建」（[GitHub](https://github.com/haoel/haoel.github.io)），这个教程比较多文字，但建议耐心看完
>
> Tips：把教程链接、VPS 和 Cloudflare 账号授权给智能体，让智能体帮忙配置和启动代理；也可以让智能体帮忙进一步优化代理（比如从 GOST 换成 Hysteria2）。

### 付费机场（不推荐）

没用过；且好机场通常比较贵，同时稳定性/风险也更不可控。

---

## Claude App 网络代理配置

- Claude 官方教程：[Network proxy](https://claude.com/docs/third-party/claude-desktop/network-proxy)

---

## 注册 Anthropic 账号和开通订阅

- **注册 Anthropic / Claude 账号**：在自建梯子的网络环境中，通过 Claude App 或官网注册，推荐苹果匿名邮箱
- **开通 Anthropic / Claude 订阅**：
  - iPhone 用户：挂自建梯子 + 美区 App Store + 充值礼品卡 = 完成订阅
  - 安卓用户：挂自建梯子 + Google Pay

如果使用美区 Apple ID 的礼品卡余额订阅 Anthropic / Claude 时出现“购买无法完成”，尤其是新号或刚充值后，可通过 [Apple 支持](https://support.apple.com/contact) 选择 **Billing and subscriptions / App Store Support / Unable to Purchase** 联系客服解除内购限制，类似案例也可参考 [Apple 中文社区讨论](https://discussionschinese.apple.com/thread/255405755)。

---

## 短信验证码

- **接码平台**：[SMSPool](https://www.smspool.net/purchase/sms)（自己一直在用；有些平台可能收不到 Anthropic 的验证码）
- **免短信验证码注册技巧**
  1. 使用 iOS Claude App 通过 Apple 登录，使用私密转发邮箱（待验证）
  2. 使用比较纯净 IP 的 VPS 搭的梯子，可免短信验证，如使用 yinnet（已亲测）

---

## Claude Code 中转站

- **Sub2API**（便于管理多个 Claude Code 账号，也方便拼车/共享额度）（[GitHub](https://github.com/Wei-Shaw/sub2api)）

> 暂时不推荐使用 Sub2API 了。

---

## FAQ

**Q1：一开始选择订阅哪个套餐？**

A1：可以先订阅 20 美元的套餐，把整个过程熟悉下，后续可补差价订阅更高级的套餐。

**Q2：一个账号可以多个人同时使用么？**

A2：可以，但不推荐。有朋友在同一网络环境下，3 个人同时使用同一个 Anthropic 账号。

**Q3：推荐使用什么邮箱注册 Anthropic 账号呢？**

A3：推荐 iCloud 的隐藏邮件地址，方便管理；另外，Anthropic 官方已支持删除账号，可找回之前被封的旧邮箱来重新注册账号。

**Q4：Codex / OpenAI 怎么订阅？是否需要验证手机？**

A4：验证手机可通过 SMSPool 等接码平台解决；或者使用美区苹果账号注册登录 ChatGPT App，可免短信验证（朋友提供）。

**Q5：注册和订阅过程中网络环境有什么要注意的？**

A5：尽量保持网络环境稳定、不要频繁切换 IP。如果是苹果订阅，需要在 iPhone 上挂自己的梯子完成。已有不少人反馈因为网络突然切换，导致 Claude Code 被封号。

---

欢迎提 Issue / PR 纠正和补充～
