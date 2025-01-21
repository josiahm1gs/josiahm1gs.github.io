你可以在 Midjourney 的服务器，或者 Midjourney Bot 聊天窗口，输入 `/subscribe`，然后按下回车：

![Midjourney 订阅步骤 1](https://res.craft.do/user/full/d845172f-becd-4255-bf79-d722098b2d83/doc/15EA26B6-9B49-4076-B8D8-DFE53ABD52C8/FF0900C2-310C-4919-877B-CE0C5AD57201_2/GYoKiAcee0vFK7gsuffsxLzk9PsopzvV1cvJORt4lEEz/MJ010.png)

接着，Bot 会发送如下消息，点击 **Open subscription** 按钮即可进入付费页面：

![Midjourney 订阅步骤 2](https://res.craft.do/user/full/d845172f-becd-4255-bf79-d722098b2d83/doc/15EA26B6-9B49-4076-B8D8-DFE53ABD52C8/26F1A0DD-C603-41E0-8D2B-1205A1A7658B_2/pYHGFSwBpsnJk9CP2LrhG15wzfZ7z2872Nzqf4kxf0sz/MJ011.png)

> **注意**：Midjourney 的付费功能由 Stripe 提供，目前仅支持信用卡支付，因此需要准备一张信用卡。

---

## 各套餐之间的差异有哪些？

以下是 Midjourney 各套餐的主要差异总结（数据截止至 2025-03-28）：

Midjourney 的计费方式与 OpenAI 不同。OpenAI 按 Token 计费，而 Midjourney 按 GPU 使用时间计费。以下是影响费用的主要因素：

| **低于平均价格**         | **平均价格**                     | **高于平均价格**                     |
|--------------------------|----------------------------------|--------------------------------------|
| 不同任务                 | Variations（图片下的 V 按钮）    | /imagine 生成图片                   |
|                          |                                  | Upscale（图片下的 U 按钮）          |
| Aspect Ratio 长宽比      | 默认                             | tall 或 wide（更改参数会增加费用）  |
| Model Version 模型版本   | 默认（—V 4）                    | —test 或 —testp（更贵）             |
| Quality Parameter 图像质量参数 | --q 0.25 或 —q 0.5             | 默认（—q 1）                        | —q 2 |
| Stop Parameter 停止参数  | --stop 10 到 —stop 99           | 默认（—stop 100）                   |      |

### Relaxed Generation 模式

从 Standard Plan 开始，用户可以使用 **Relaxed Generation** 模式。在该模式下，用户可以无限制生成图片，但生成速度会变慢（官方解释为 0-10 分钟）。本质上，这是一种 GPU 空闲资源排队方案：

- **Fast 模式**：优先使用 GPU 资源，生成速度更快。
- **Relax 模式**：进入排队状态，利用 GPU 闲置资源。

> **提示**：使用 Relax 模式越多，等待时间越长。类似于手机运营商的无限流量套餐逻辑，使用量达到一定阈值后会降速。

每月初，系统会自动将模式切换回 **Fast 模式**。

### Stealth 模式

Midjourney 默认是一个开放社区，所有生成的图片（包括私聊 Bot 生成的图片）都会公开展示在会员 Gallery 中。只有 Pro 版本支持 **Stealth 模式**，可以隐藏图片不公开。

> **注意**：即使开启了 Stealth 模式，在 Discord 公开频道生成的图片仍会被公开。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)