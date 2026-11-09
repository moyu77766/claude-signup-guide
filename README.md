# Claude 注册、登录与 U 卡支付教程

一份面向新手的中文指南：准备网络，注册或登录 Claude，再使用可用的银行卡完成网页订阅。

**已经有 Claude 账号？** 直接看[准备支付卡](#3-准备支付卡u-卡gate-card)和[订阅付款](#4-在-claude-网页订阅并付款)。已有可用信用卡或借记卡，可以跳过开卡步骤。

## 常用入口

| 用途 | 入口 |
| --- | --- |
| Claude 注册、登录 | [claude.ai](https://claude.ai/) |
| Claude 官方套餐与价格 | [查看套餐](https://claude.com/pricing) |
| U 卡支付：Gate 注册入口 | [打开 Gate 分享链接](https://www.gate.com/share/VAMQUF1BBG) |
| 家宽 IP：IPOASIS 入口 | [打开 IPOASIS 分享链接](https://www.ipoasis.com/s/fczsackoo0) |

Gate 和 IPOASIS 使用作者提供的分享链接，可能涉及平台邀请权益，具体规则以平台页面为准。本教程独立维护，与 Anthropic、Gate、IPOASIS 没有官方隶属关系。

## 1. 开始前准备

准备一个能正常收信的邮箱、可用网络，以及付款时使用的信用卡或借记卡。按 Claude 页面要求完成手机号及其他验证。Claude 对用户实际所在地和注册手机号有服务范围要求，代理出口所在地不能替代实际所在地。[Claude 注册说明](https://support.claude.com/en/articles/8325609-how-do-i-sign-up-for-the-pro-plan)

**本教程的顺序：准备网络 → 注册／登录 Claude → 准备支付卡 → 选择套餐 → 付款后确认到账。**

注册账号与订阅付费套餐是两件事。可以先完成账号注册，确认能够使用，再决定是否付费。

## 2. 准备网络，注册并登录 Claude

### 2.1 家宽 IP／静态住宅 IP

需要单独配置 IP 时，可以从这里了解产品：[IPOASIS 分享入口](https://www.ipoasis.com/s/fczsackoo0)。

IPOASIS 官方提供 **Static Residential（静态住宅／ISP）代理**，支持 HTTP(S)、SOCKS5。这里的“家宽 IP”指这类代理产品，不代表购买了一条安装到家里的实体宽带，也不代表 Claude 保证接受该 IP。[官方产品说明](https://www.ipoasis.com/proxy/static-residential)

操作顺序：

1. 打开分享链接，注册或登录 IPOASIS。
2. 查看静态住宅／ISP 产品，核对地区、有效期、协议、价格与售后条件；需要固定出口时，确认所选套餐是否保持同一个 IP。
3. 如果决定购买，付款后在控制台取得连接信息，例如主机、端口、用户名和密码，或按平台说明配置 IP 白名单。
4. 按所用代理客户端的说明添加连接。不同客户端的字段和按钮不同，不要把“订阅链接”与“主机＋端口＋认证信息”混用。
5. 用同一个浏览器检查出口 IP，再打开 Claude。需要帮助时可以参考 [IPOASIS 官方文档](https://docs.ipoasis.com/)。

> 已经能正常访问 Claude，可以直接继续下面的步骤。IP 检测只能说明该次检测请求的出口，不能证明其他浏览器、客户端也走了同一条连接。

### 2.2 注册或登录 Claude

1. 用浏览器打开 [Claude 官网](https://claude.ai/)。
2. 新用户选择邮箱或 Google 登录方式；使用邮箱时，按收到的登录邮件继续。
3. 按页面提示完成验证、资料填写及条款确认。
4. 已有账号直接使用原来的登录方式进入，确认登录的是准备订阅的那个账号。
5. 进入聊天界面，发一条简单消息，确认账号能够正常使用。

[参考：Claude 官方注册与升级步骤](https://support.claude.com/en/articles/8325609-how-do-i-sign-up-for-the-pro-plan)

## 3. 准备支付卡：U 卡／Gate Card

**这里的 U 卡路线，是先取得一张可用于线上支付的卡，再在 Claude 结账页填写银行卡信息。Claude 网页订阅接受信用卡或借记卡，不是向 Claude 转账 USDT。** [Claude 官方支付方式](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)

### 3.1 先确认自己能否申请

入口：[使用分享链接注册 Gate](https://www.gate.com/share/VAMQUF1BBG)。

Gate 有多种 Gate Card 产品，申请地区、身份验证、资金来源与费用可能不同。请按真实居住地核对资格；Gate 全球站用户协议列有受限地区，包括中国大陆、香港等，不能把代理 IP 的所在地当成自己的居住地提交。

[Gate Card 官方页面](https://www.gate.com/card) · [Gate 用户协议](https://www.gate.com/legal/user-agreement)

### 3.2 注册与申请卡片

1. 确认符合平台及卡片的申请条件后，通过上面的 Gate 分享入口注册；已有账号直接登录。
2. 在 Gate 网站或官方 App 中查找 **Gate Card**，查看向自己开放的卡种。
3. 阅读开卡费、维护费、换汇／消费费和扣款规则，再决定是否申请。
4. 按卡片页面要求完成身份验证、资料提交及审核。身份材料只交到官方申请页面。
5. 获批并完成激活后，在卡片详情中查看卡号、有效期、安全码，以及发卡方登记的账单资料。

如果没有申请入口、所在地区不支持或审核未通过，就无法按这条路线继续；可以使用自己已有、符合 Claude 要求的信用卡或借记卡。

### 3.3 准备付款余额

按所选卡片的官方说明确认：

- **扣哪里的钱：** 卡片余额、指定资金账户，还是其他方式。
- **支持哪些资金或币种：** 不要默认 Gate 账户中有 USDT，卡片就一定能够扣款。
- **能否线上订阅：** 确认是否支持该商户、线上支付、周期扣款，以及需要的支付验证。
- **费用是多少：** 以卡片页面为准，预留税费、换汇及支付手续费所需金额。

如需链上充值，先核对官方充值页的资产、网络、地址及最低充值要求，再自行决定和操作；不要使用教程评论区或私信提供的充值地址。

Gate 官方曾发布包含 Claude 的 AI 订阅活动，但这只说明供应商宣传过该用途，不等于每种卡、每个账户都能支付成功。返现资格、名额和期限以当时活动条款为准，先按未获返现的实际账单金额核算成本。[Gate AI 订阅活动页面](https://www.gate.com/campaigns/6017)

## 4. 在 Claude 网页订阅并付款

### 4.1 选择套餐

1. 回到 [Claude 官网](https://claude.ai/)，确认当前登录邮箱。
2. 打开 **Settings → Billing（设置 → 账单）**，选择 **Upgrade plan（升级套餐）**，也可以进入 [官方升级页](https://claude.ai/upgrade)。
3. 选择需要的套餐和月付／年付周期。
4. 核对结账页的币种、当前应付金额、税费和下次续费信息，再填写支付资料。

套餐名称和价格会变化，具体以 [Claude 官方价格页](https://claude.com/pricing) 及自己账号的结账页为准。[官方升级步骤](https://support.claude.com/en/articles/8325609-how-do-i-sign-up-for-the-pro-plan)

### 4.2 填写银行卡资料

下面只是字段解释，实际表单可能有所不同：

| 结账字段 | 填什么 |
| --- | --- |
| Card number | 发卡方提供的卡号，不是 Gate UID |
| Expiration / MM/YY | 卡片有效期 |
| CVC / CVV | 卡片安全码，不是短信验证码 |
| Cardholder name | 发卡方登记的持卡人姓名 |
| Country / Region | 该卡登记的账单国家／地区 |
| Address line 1 | 登记的门牌号与街道 |
| Address line 2 | 登记的公寓、房间或单元，没有可留空 |
| City / State / ZIP | 登记的城市、州／省和邮编 |

**账单地址按发卡方记录填写。** 不确定时向发卡方确认，不使用随机生成的地址。Claude 官方说明，账单地址不匹配、发卡地区不符合要求、余额不足或验证未完成，都可能导致拒付。[官方拒付排查说明](https://support.claude.com/en/articles/9402418-why-was-my-card-declined)

### 4.3 确认付款与到账

1. 核对金额和续费条款，由本人点击订阅并付款。
2. 如果弹出银行或发卡方验证，在其官方页面／App 内完成。
3. 返回 Claude 的 **Settings → Billing**，检查套餐状态、付款记录或收据。
4. 确认套餐已生效，保存收据。付款后套餐未更新时，先按下一节排查。

通过 Claude 网页购买的订阅默认自动续费；需要停止续费时，进入账单页面按提示取消。若通过手机应用商店订阅，则由对应商店管理账单。[Claude 续费说明](https://support.claude.com/en/articles/8325609-how-do-i-sign-up-for-the-pro-plan) · [账单管理说明](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)

## 5. 常见问题

| 情况 | 可以先做什么 |
| --- | --- |
| Claude 页面打不开 | 检查当前网络、浏览器实际出口和服务状态；确认该账号符合服务要求。 |
| 注册或登录邮件没收到 | 检查邮箱拼写、垃圾邮件及是否使用了原来的登录方式，按页面提示重试。 |
| 不知道代理怎么填 | 确认客户端名称、协议，以及拿到的是订阅链接还是连接参数，再查官方文档。 |
| Gate 没有开卡入口 | 核对自己的实际居住地、账号资格及当前开放卡种，向 Gate 官方支持确认。 |
| 卡片被拒绝 | 核对卡状态、线上订阅权限、可用余额、账单地址、发卡地区和支付验证；仍失败时联系发卡方。 |
| 显示扣款，套餐却没变化 | 核对登录邮箱、收据和 Claude 账单；向发卡方确认该记录是待处理预授权还是已入账交易，再联系 Claude 支持。 |
| 想改卡或停止续费 | 网页订阅到 Claude 账单页管理；应用商店订阅到对应商店管理。 |

支付失败的详细排查见 [Claude 官方帮助](https://support.claude.com/en/articles/9402418-why-was-my-card-declined)，账单及套餐问题见 [官方账单 FAQ](https://support.claude.com/en/articles/8325618-paid-plan-billing-faqs)。

## 6. 让 AI 陪你一步一步操作

可以把这份教程的 GitHub 链接或全文发给你正在使用的 AI，再复制下面这段话：

> 请按这份教程用中文陪我注册或登录 Claude，并在我需要时指导网页订阅。先问我有没有 Claude 账号、是否已有可用银行卡；已有的步骤直接跳过。每次只讲一个操作，等我回复看到的页面后再继续。需要 IP 时给我教程中的 IPOASIS 分享链接；符合 Gate 申请资格且需要开卡时，给我教程中的 Gate 分享链接。不确定的按钮和页面请先问我，不要编造。不要向我索取完整卡号、CVV、密码、验证码或身份证件，也不要生成虚假账单地址。付款前提醒我核对金额和续费条件，由我本人确认支付。

## 7. 后续补充实测记录

本版根据公开资料整理，**尚未进行真实账号注册、开卡和 Claude 扣款测试**。欢迎补充脱敏截图和实测结果；一次成功仅代表当次记录。

```text
实测日期：
使用平台：Claude 网页
套餐与付款周期：
卡片名称／卡种（不填卡号）：
账单币种及实际扣款金额：
网络产品类型（不填代理密码）：
结果：成功／失败／待确认
报错原文（去除个人信息）：
补充说明：
```

## 8. 如何修改这份教程

仓库维护者可以直接点 [在线编辑 README](https://github.com/moyu77766/claude-signup-guide/edit/main/README.md)，修改文字后先看 **Preview**，再点 **Commit changes** 保存。其他读者可以提交 Issue 或 Pull Request 补充经验。[GitHub 官方编辑说明](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)

补充截图前，请遮挡邮箱、完整卡号、安全码、身份证件、验证码、登录令牌及代理认证信息。

---

资料核对日期：**2026 年 11 月 9 日**。平台页面与规则可能变化，请以实际操作时的官方说明和结账页面为准。

作者：**moyu77766**。本文采用 [CC BY 4.0（知识共享署名 4.0 国际）](https://creativecommons.org/licenses/by/4.0/deed.zh-hans) 许可，转载或修改请注明作者、来源和所作修改。第三方商标及平台内容归其权利人所有。
