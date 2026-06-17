# ORIGIN 完整官网静态原型

## 版本入口

- `index.html`：首页主界面，路由定位为 `/`，重点展示产品定位、核心卖点、使用场景、App 联动、公司可信度、主 CTA，并用六大入口承接后续详细页。
- `variant-theater.html`：方案二，产品剧场。首页首屏下方更有连续叙事和场景感。
- `variant-signal.html`：方案三，信号杂志。首页首屏下方更强调强排版、数据感和信息识别。
- `variant-six-zones.html`：方案四，六区分屏。六个页面组各自成为独立区域，用短句、分屏和结构化视觉承接详情页。
- `variant-draft-sketch.html`：官网设计稿草图。按最新草案组织固定导航、滚动进度、视频展示、地图资质、硬件、App、AI 情绪、健康趋势和底部联系入口。
- `variant-signal-care.html`：照护信号版。保留草案结构，但将视觉语言改成 ORIGIN 自己的照护信号系统，弱化 Fi 的黄黑 CTA、追踪器叙事和重叠手机阵列。

## 当前设计记录

- 2026-06-10：底部页脚优先采用简洁白底服务区。参考小米官网底部的信息组织方式，使用购买指南、服务中心、线下与购买、关于 ORIGIN、关注我们、客服咨询、法律备案与信任徽章分层呈现。整体目标是舒服、清楚、可信，不做厚重黑底或强营销收口。

## 草图素材

- `assets/origin-draft-video-still.png`：产品展示 / 宣传视频感首屏。
- `assets/origin-draft-location-map.png`：公司资质与位置地图感背景。
- `assets/origin-draft-ai-health.png`：AI 情绪陪伴与健康趋势视觉。
- `assets/origin-signal-care-hero.png`：照护信号版首屏视觉。
- `assets/origin-signal-care-hardware-lab.png`：照护信号版硬件实验台视觉。
- `assets/origin-signal-care-trust-map.png`：照护信号版公司信任 / 平台网络视觉。

## 首页入口规划

- 产品详情页：`/product`
- App 下载与安装页：`/download`
- 购买渠道页：`/shop`
- 技术与支持中心：`/technology`、`/support`、`/privacy-safety`
- 关于、联系与合作页：`/about`、`/contact`、`/partners`
- 法律页组：`/legal/*`

## 查看方式

直接用浏览器打开对应 HTML 文件即可，不需要启动服务。

## 2026-06-17 Preview Baseline Update

- `index.html` is the current GitHub Pages preview entry for `https://jjunmax.github.io/origin-official-site-preview/#hero`.
- The top navigation uses a fixed black translucent bar with a 66px desktop height.
- The hero media is a looping video asset: `assets/origin-hero-care-loop.webm`.
- The second section uses a card-grid plus lightweight carousel pattern: featured cards on top, daily update cards below.
- Supporting carousel image assets:
  - `assets/origin-company-carousel-cloud.png`
  - `assets/origin-company-carousel-companion.png`
  - `assets/origin-company-carousel-geofence.png`
- `brand-stories.html` keeps the immersive carousel detail page for linked cards.
