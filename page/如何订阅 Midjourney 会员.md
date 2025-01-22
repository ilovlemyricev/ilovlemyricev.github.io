你可以通过以下步骤轻松订阅 Midjourney 会员：

1. 在 Midjourney 的服务器或 Midjourney Bot 聊天窗口，输入 `/subscribe`，然后按下回车。
2. Bot 会发送一条消息，点击其中的 **Open subscription** 按钮，即可进入付费页面。

> 注意：Midjourney 的付费功能由 Stripe 提供，目前仅支持信用卡支付，因此需要准备一张信用卡。

---

## 各套餐之间的差异

Midjourney 的计费方式与 OpenAI 不同。OpenAI 按 Token 计费，而 Midjourney 按 GPU 使用时间计费。以下是各套餐的主要差异（数据截止至 2025-03-28）：

### 计费方式
- **Basic 版本**：Fast Generation 时间为 3 小时 20 分钟，约可生成 200 多张图片。
- **Standard Plan**：提供 Relaxed Generation 模式，可无限制生成图片，但速度较慢（0-10 分钟）。

### 影响费用的因素
以下参数会影响 GPU 时间的消耗，从而影响费用：
- **任务类型**：
  - 低于平均价格：不同任务
  - 平均价格：Variations（V 按钮）
  - 高于平均价格：/imagine 生成图片、Upscale（U 按钮）
- **长宽比（Aspect Ratio）**：
  - 默认：无额外费用
  - 自定义（如 tall 或 wide）：费用增加
- **模型版本（Model Version）**：
  - 默认：—V 4
  - 更高费用：—test 或 —testp
- **图像质量参数（Quality Parameter）**：
  - 低于平均价格：--q 0.25 或 --q 0.5
  - 默认：--q 1
  - 高于平均价格：--q 2
- **停止参数（Stop Parameter）**：
  - 默认：--stop 100
  - 低于平均价格：--stop 10 到 --stop 99

### Relaxed Generation 模式
Relaxed 模式是一种 GPU 空闲资源排队方案：
- 在 Relax 模式下，图片生成请求会进入排队状态，等待 GPU 空闲资源。
- 使用 Relax 模式越多，等待时间越长。
- 每月初系统会自动切换回 Fast 模式。

### Stealth 模式
Midjourney 默认是一个开放社区，所有生成的图片（包括私聊 Bot 生成的图片）都会公开：
- **Pro 版本**：支持 Stealth 模式，可隐藏图片不公开到 Gallery。
- 注意：即使开启 Stealth 模式，在 Discord 公开频道生成的图片仍会被公开。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

> 使用 WildCard，轻松解决信用卡支付问题，快速订阅 Midjourney 等海外服务。