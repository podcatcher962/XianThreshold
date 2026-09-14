# 四扇门 XianThreshold

**单文件本地自省工具** — 双击即用，零依赖，零网络请求。

> 它不预测、不诊断、不算命。只是把你走过的路画成一张图，在你又一次走到同一道门前时，把灯留着。

[中文](#中文) | [English](#english)

---

## 中文

四扇门是一个**单个 HTML 文件**构成的自省工具。用手机或电脑的浏览器打开就能用，不需要安装、不需要账号、不需要联网。所有记录都留在你自己的设备上。

### 在线版

👉 **https://podcatcher962.github.io/XianThreshold/**

手机浏览器打开后建议「添加到主屏幕」，用起来和 App 一样。

### 它做什么

不预测、不诊断、不算命。只做三件事：

1. 帮你把每天三次起心动念记下来（晨 / 午 / 夜三节）；
2. 把你已经走过的路画成一张图（业力图谱，灰的是没走过的路）；
3. 在你第 N 次走进同一条路时，轻轻说一句「又来了」，并给一个可做可不做的替代行为。

**成败不在功能表，在一句话**：

> 这不是批评——你以前就是这样活下来的，它保护过你。

### 功能

| 分类 | 说明 |
| --- | --- |
| 🌅 **今日** | 晨 / 午 / 夜三节，各一次起心动念记录；当天水墨题图随日期生成 |
| 📖 **随览** | 只读浏览：民俗条目、东西对读、条目问答 —— **不出题、不打分**，翻到哪算哪 |
| ✍️ **录事** | 记下日常小事与身体小异动，自动与民俗词表对照 |
| 🗺 **显影** | 业力图谱：把走过的路画成一张图，灰的是没走过的路 |
| 🪞 **自照** | 十六题自省问卷 → 一张「业力画像」；只描述模式，不贴标签 |
| 🕯 **静室** | 呼吸涟漪，只有缓慢的起伏，没有计时、没有打卡 |
| 📚 **案头** | 说明、常见问题、免责、关于、作者与授权 |
| 🌗 **主题** | 深色 / 浅色双主题，随系统自动切换 |
| 🌐 **语言** | 简体中文 / English 全量双语（约 330 条 UI 文案） |

内置内容规模（均为本地数据，无网络请求）：

- **民俗知识库 约 150 条**（节气、物候、民俗兆应等）
- **东西对读 约 150 条**（同一处境下的东方与西方视角并置）
- **自照问卷 16 题**、**自问 24 条**、**替代动作 12 组**
- **常见问题 12 条**

### 使用说明

1. **今天** — 打开就落在今日页，点一处起心动念记下来即可，不必点满。
2. **随便翻翻** — 不想做题就去「随览」，那里只有内容，没有提问。
3. **看自己** — 「自照」答一遍问卷，会得到一张画像；它不是定义，只是一面镜子。
4. **静一下** — 「静室」里只有呼吸的涟漪，不看时间。
5. **换主题 / 语言** — 右上角月亮按钮或「设置」页。

### 存储说明

所有记录存在浏览器的 localStorage 里，键名 `fourdoors_v1`。**清除浏览器数据会一并清掉记录**，建议定期用设置页的「导出」做备份（导出为 JSON）。

### 技术说明

- 纯单文件 HTML，**无任何第三方库、无 CDN、无外部字体、无位图**
- 全站意象均为**内联 SVG**（水墨题图、笔触图标、远山与月），零外部请求
- 全部数据内置为 JS 字面量，**零 fetch / 零 XHR**
- CSS 动画受 `prefers-reduced-motion` 与「减少动效」设置双重约束
- 存储键 `fourdoors_v1` 自 v0.1 起从未改动，保证跨版本数据不丢

### 免责声明

- 本工具是**个人作品**，不是医疗器械、不是心理治疗、不是占卜预测工具，**不构成任何医疗、心理或法律建议**。
- 内容中的民俗、医巫、业力等概念均作为**文化材料**呈现，不代表作者主张其真实性或有效性。
- 若你正处于情绪困扰或健康问题中，请寻求**专业医师或心理咨询师**的帮助，本工具不能替代任何专业服务。
- 所有数据仅存于使用者本机浏览器中，作者不收集、不上传、不存储任何用户数据。
- 本软件按「现状」提供，不附带任何明示或暗示的担保。

### 作者

**永远的兰兰 (Lanlan Eternal)**

### 许可

**保留所有权利**（source-available，非 OSI 开源许可）。可自由使用、原样转发，请保留署名；若要改动，请只留给自己看，**改过的版本不要对外分发**。详见 [LICENSE](LICENSE)。

---

## English

XianThreshold (四扇门, "Four Doors") is a self-reflection tool that ships as **a single HTML file**. Open it in any browser on your phone or desktop — no installation, no account, no network. Everything you write stays on your own device.

> It explains no fate and promises no answer. It only keeps the lamp lit for the next time you reach the same door.

### Live version

👉 **https://podcatcher962.github.io/XianThreshold/**

On mobile, add it to your home screen for an app-like experience.

### What it does

It does not predict, diagnose, or divine. It does exactly three things:

1. Helps you note three passing impulses a day (morning / noon / night);
2. Draws the roads you have already walked into a single map (the grey parts are the roads not taken);
3. The Nth time you walk into the same road, it quietly says "here it is again" and offers one alternative you are free to ignore.

**The whole product rests on one sentence**:

> This is not a scolding — you survived this way before. It protected you.

### Features

| Area | What you get |
| --- | --- |
| 🌅 **Today** | Three moments a day (morning / noon / night); the day's ink illustration is generated from the date |
| 📖 **Wander** | Read-only browsing: folk-lore entries, East–West pairings, Q&A — **no questions, no scoring** |
| ✍️ **Record** | Log small events and bodily oddities; matched against a folk-omen word list |
| 🗺 **Map** | The map of your roads — grey where you have never walked |
| 🪞 **Mirror** | A 16-question self-inventory → a "portrait" that describes patterns without labelling you |
| 🕯 **Stillness** | Breathing ripples only — no timer, no streaks, no check-ins |
| 📚 **Docs** | Help, FAQ, disclaimer, about, author & licence |
| 🌗 **Theme** | Dark / light, follows the system |
| 🌐 **Language** | Full Simplified Chinese / English (≈330 UI strings) |

Built-in content (all local, zero network requests):

- **~150 folk-lore entries** (solar terms, phenology, traditional omens)
- **~150 East–West readings** (the same predicament seen from two traditions)
- **16 self-inventory questions**, **24 self-inquiries**, **12 alternative-action sets**
- **12 FAQ entries**

### Usage

1. **Today** — the app opens here; note one impulse and you are done. No need to fill everything.
2. **Just browse** — if you don't want questions, go to *Wander*. Content only.
3. **Look at yourself** — answer the *Mirror* inventory once; it returns a portrait. Not a definition, just a mirror.
4. **Sit still** — *Stillness* has nothing but breathing ripples.
5. **Theme / language** — the moon button in the corner, or the Settings page.

### Storage notes

Everything is stored in the browser's localStorage under the key `fourdoors_v1`. **Clearing browser data clears your records** — use *Export* in Settings to keep a JSON backup.

### Technical notes

- Single-file HTML — **no third-party libraries, no CDN, no external fonts, no bitmap images**
- Every illustration is **inline SVG** (ink scenes, brush glyphs, distant mountains and moon) — zero external requests
- All data is embedded as JS literals — **zero fetch / zero XHR**
- CSS animations are gated by `prefers-reduced-motion` and a "reduce motion" setting
- The storage key `fourdoors_v1` has never changed since v0.1, so data survives upgrades

### Disclaimer

- This is a **personal project**. It is not a medical device, not psychotherapy, and not a divination tool. It **does not constitute medical, psychological, or legal advice**.
- Concepts such as folk custom, folk medicine, and karma are presented as **cultural material**, not as claims of truth or efficacy by the author.
- If you are in emotional distress or have a health concern, please consult a **qualified professional**. This tool is not a substitute for any professional service.
- All data stays in your local browser. The author collects, uploads, and stores nothing.
- Provided "as is", without warranty of any kind.

### Author

**Lanlan Eternal (永远的兰兰)**

### License

**All rights reserved** (source-available; not an OSI-approved open-source licence). Free to use and to pass on unchanged with credit kept; if you modify it, keep the change to yourself and **do not distribute modified copies**. See [LICENSE](LICENSE).
