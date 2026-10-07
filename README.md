<div align="center">

# 📚 Cathay 系列软件

**面向人文社会科学研究的电子书处理工具流**

**从找书、OCR、著录，到索引、检索、阅读、摘录 —— 覆盖文献处理全流程**

![license](https://img.shields.io/badge/license-GPL--3.0-blue)
![platform](https://img.shields.io/badge/platform-Windows%2010%2B-lightgrey)
![count](https://img.shields.io/badge/主力软件-5-orange)
![offline](https://img.shields.io/badge/运行-纯本地%20·%20不联网-brightgreen)

</div>

> 🗂️ **这个仓库不装软件，它是 Cathay 全系列的「目录」。**
> 十来个小工具**各自独立** —— 不用全装，**卡在哪一步就拿哪个**。
> 全部**纯本地运行**：不联网、不上传、不动你的原件。

**目录**：[① 卡在哪一步](#-卡在哪一步) · [② 五步流程](#-五步流程一眼看懂) · [③ 主力软件](#-主力软件五个) · [④ 专项小工具](#-专项小工具) · [⑤ 已停更项目](#-已停更项目) · [⑥ 常见问题](#-常见问题)

---

## 🎯 卡在哪一步？

先找到你现在的情况，直接点下载 —— 不用全看，也不用全装。

> ⭐ **主力软件**（日常用得最多，多数人装这五个就够了）
>
> **这五个按下面的顺序走（每一步都是下一步的前提）**：

| 顺序 | 我现在的情况 | 用这个 | 下载 |
|:--:|---|---|:--:|
| ① | 想找一本书，不知道去哪儿下 | **🔍 CathayFinder** —— 11 个渠道一起搜 | [📥 Releases](https://github.com/zzhjim02/CathayFinder/releases/latest) |
| ② | 下下来是压缩包 / 一堆 `.pdg`，打不开 | **🧩 CathayPDG** —— 超星读秀压缩包转 PDF | [📥 Releases](https://github.com/zzhjim02/CathayPDG/releases/latest) · [📦 网盘 v0.2.0](https://pan.baidu.com/s/1Il3JusvDwgK-4zpT_zyt6g?pwd=2026) |
| ③ | 翻开是一页页**影印图片**，字选不中、复制不出来 | **🔤 CathayOCR** —— 让电脑看图认字 | [📥 Releases](https://github.com/zzhjim02/CathayOCR/releases/latest) |
| ④ | 书攒了几百本，文件名乱、摆放乱 | **📚 CathayShelf** —— 批量建档归位、规范命名 | [📥 Releases](https://github.com/zzhjim02/CathayShelf/releases/latest) · 📦 网盘 v0.5.1（链接稍后补） |
| ⑤ | 书太多了，想一秒搜到某句话 | **🏛️ CathayHub** —— 索引 · 检索 · 阅读 · 摘录 | [📦 仓库页](https://github.com/zzhjim02/CathayHub) |

> 🔧 **专项小工具**（碰上特定问题才用，用得少）

| 我现在的情况 | 用这个 | 下载 |
|---|---|:--:|
| PDF 打不开、一翻页就崩 | 🩺 CathayRepair —— 先把坏 PDF 救回来 | [📥 Releases](https://github.com/zzhjim02/CathayRepair/releases/latest) |
| 想把字「印」回 PDF（做成双层） | 📑 CathayRestore —— 图还是原图，底下多一层字 | [📥 Releases](https://github.com/zzhjim02/CathayRestore/releases/latest) |
| 想把 PDF 里的字**整批导出**成 TXT | 📤 CathayExtract —— 文字层导出文本文件 | [📥 Releases](https://github.com/zzhjim02/CathayExtract/releases/latest) |
| 一堆 PDF 摆在面前，想知道各自是**横排还是竖排** | 🧭 CathayDir —— 每 10 页抽一页批量判，能存 CSV / 分三个柜 | [📥 Releases](https://github.com/zzhjim02/CathayDir/releases/latest) · [📦 网盘 v0.1.1](https://pan.baidu.com/s/1aU40yVsfcuvBp95bjqbDIg?pwd=2026) |

---

## 🔗 五步流程，一眼看懂

| ① 找书 | ② 转成 PDF | ③ 认字 | ④ 归档 | ⑤ 检索阅读 |
|:---:|:---:|:---:|:---:|:---:|
| 🔍 | 🧩 | 🔤 | 📚 | 🏛️ |
| **CathayFinder** | **CathayPDG** | **CathayOCR** | **CathayShelf** | **CathayHub** |
| 去哪儿找这本书 | 压缩包变成能翻的 PDF | 影印本认出字，能搜能复制 | 几百本书归位、规范命名 | 搜一句话，直接翻开看 |

```
   找书    ──▶   转 PDF   ──▶    认字    ──▶   归档    ──▶   检索阅读
  ① Finder     ② PDG         ③ OCR        ④ Shelf      ⑤ Hub
                  ▲                                        │
                  │                                        ▼
              ⓪ 修好                                  阅读 · 摘录
        （PDF 打不开先用 CathayRepair 救一下）
```

> ⚠️ **第 ⑤ 步搜的是「字」不是「图」**：没做过第 ③ 步的影印本，在 CathayHub 里**只能按文件名搜到，正文搜不到**。
> 中间哪一步没遇上就跳过 —— 书要是已经能复制文字了，直接从 ④ 或 ⑤ 开始。

---

## ⭐ 主力软件（五个）

> 📥 **两条路都能下**：各软件自己的 **Releases 页面**（旧版本都在那儿），以及**百度网盘**（密码 `2026`）—— 最新版安装包在里面，**发行版 + 源码开发版二合一**：
> CathayShelf v0.5.1（网盘链接稍后补） · [CathayPDG v0.2.0](https://pan.baidu.com/s/1Il3JusvDwgK-4zpT_zyt6g?pwd=2026) · [CathayDir v0.1.1](https://pan.baidu.com/s/1aU40yVsfcuvBp95bjqbDIg?pwd=2026)

### ① 🔍 CathayFinder —— 找书

<div align="center">

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayFinder?color=brightgreen&style=for-the-badge)](https://github.com/zzhjim02/CathayFinder/releases/latest)

</div>

> 在 **11 个渠道**里同时搜一本书，告诉你它在哪儿、编号是多少。

- 🔎 **一次搜完 11 个渠道**：读秀、Z-Library、百度网盘、阿里网盘、维基（百科 / 文库 / 共享资源）、中国地方志、奇点社科、游氏古籍、华中师大近史所，外加你自己的本地文件库
- 🎯 **只给精准结果**：搜「布罗代尔」只出真正含这三个字的，不塞一堆不相干的
- 🧭 **可以只搜某个字段**：书名 / 作者 / 出版社 / 编号（编号支持只写前几位）
- 🖱️ **结果行上直接操作**：点一下就「打开所在文件夹」或「复制 SSID」
- 📤 **导出能挑字段**：11 个字段想导哪几个勾哪几个，自动去重、按拼音排序
- 📁 **自己电脑的文件夹也能搜**：软件里就有「本地文件库索引」页签

<details>
<summary>⚠️ 装之前必读：数据库 27 GB</summary>

程序本身只有 43 MB，但 11 个渠道的数据库**约 27 GB**，GitHub 单文件上限 2 GB 放不下 →
**数据库走网盘**（Releases 页面里会写明）。程序和数据要放在**同一层**，分开就搜不到东西。

</details>

---

### ② 🧩 CathayPDG —— 解压转换

<div align="center">

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayPDG?color=brightgreen&style=for-the-badge)](https://github.com/zzhjim02/CathayPDG/releases/latest)

</div>

> 把超星 / 读秀下载下来的 PDG 压缩包，转成能正常翻看的 PDF。

- 🖱️ **拖进去就行**：把一个文件夹拖进窗口，剩下的全自动排队转完
- 📦 **各种压缩包都能开**：zip / rar / 7z / uvz，**带密码的也能解**（内置密码本自动试）
- 🔤 **中文乱码自动修**：老压缩包里中文名常是一串问号，自动认编码（GBK / Big5 等）并还原
- 📖 **横排竖排分开装**：自动判断版面方向，分两个 PDF 输出，不混在一起
- ✅ **真正的零依赖**：7-Zip、转换引擎全部内置，**你什么都不用装**
- 🩺 **有「环境体检」按钮**：万一缺什么，点一下告诉你是啥、怎么补

---

### ③ 🔤 CathayOCR —— 认字（OCR）

<div align="center">

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayOCR?color=brightgreen&style=for-the-badge)](https://github.com/zzhjim02/CathayOCR/releases/latest)

</div>

> 影印本 / 扫描件翻开是一页页图片，**字选不中、复制不了、也搜不到** ——
> 它让电脑把图片里的字认出来，之后这本书就**能搜、能复制、能引用**了。

> 🗣️ **说人话**：OCR 就是「让电脑看图认字」。没做这一步的书只是一堆图片，
> 你在里面搜一个词是搜不到的 —— 后面 CathayHub 的全文检索**全靠这一步**。

- 📚 **批量处理**：扔进去一整个文件夹，然后去泡茶
- 🀄 **中文识别优化**：对竖排、繁体、古籍版面有专门处理
- 📄 **输出可选**：能直接出双层 PDF，也能只出 TXT
- ⚖️ 有 Pro（专业版）/ Lite（轻量版）等规格，按需选

<details>
<summary>⚠️ 体积较大，可能要走网盘</summary>

OCR 引擎本身就很大，个别版本 GitHub 放不下 —— Releases 页面里会给出网盘地址，**以那边写的为准**。

</details>

---

### ④ 📚 CathayShelf —— 著录整理

<div align="center">

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayShelf?color=brightgreen&style=for-the-badge)](https://github.com/zzhjim02/CathayShelf/releases/latest)

</div>

> 几百本书乱糟糟？批量建档归位、规范命名、繁简转换。

- 🗄️ **批量著录**：按书名 / 作者 / 出版社把书归到规范的目录里
- 🏷️ **规范命名**：文件名统一成好认的格式
- ✍️ **责任方式不叠字**：「李昉编注」不会被写成「李昉编注著」（认得编注 / 编辑 / 辑 / 校释 / 编写等 29 种写法）
- 🔢 **编号补名**：只有书库编号的文件（`15458752_OCR.pdf`）可批量补成 `书名_作者名_原名`，著录后弹表勾选、不勾选就不动
- 🧷 **夹名一定合法**：夹名里的 `:` `/` 等 Windows 非法字符自动转全角 —— 以前书名带全角冒号（`西藏通史：元代卷`）会让整批书一个文件夹都建不出来
- 👤 **著者不怕生僻姓**：少数民族人名（`丹珠昂奔著`）不再因为姓氏不在百家姓表被丢掉；`中国科学院考古研究所编著` 这类单位作者也不会被切成「所编 + 著」
- 🧭 **每条值查得到来源**：双击看详情，版权页原文与 CathayFinder 书目数据并排，每个字段标出它来自 CIP / 版权页 / 文件名 / 书目库，冲突时黄底提醒
- 🔁 **繁简转换**：港台繁体书统一成简体（编码规范化一起做了）；「强制繁转简」只对 `_…FOCR` 结尾生效，`_…OCR` 与 `_【繁转简】` 一律不动
- 📦 支持批量，一次处理整个书库

---

### ⑤ 🏛️ CathayHub —— 索引 · 检索 · 阅读 · 摘录

<div align="center">

[![CathayHub](https://img.shields.io/badge/仓库-CathayHub-blue?style=for-the-badge)](https://github.com/zzhjim02/CathayHub)

</div>

> 给整个书库建索引，然后**一秒搜到某段话**，还能直接翻看、随手摘录。

**这是走完前四步之后的日常入口** —— 索引、检索、阅读、摘录四件事都在它一个里面。

- 🗂️ **索引**：把所有的书（PDF / TXT）扫成全文索引，几万本也能建
- 🔍 **检索**：搜一句话而不是只搜书名，直接命中到「哪一页有这个词」
- 📖 **阅读**：内置阅读器，搜到哪本直接翻开看
- ✂️ **摘录**：看到要紧的段落，直接摘出来存好（不用再复制粘贴）

> ⚠️ **用它的前提：书里得有「字」**。它搜的是文字，不是图片。
> 没经过 CathayOCR 认字的影印本，只能按文件名搜到，**正文里搜不到东西**。
> 所以顺序是：**先 CathayOCR → 再 CathayHub**。

<details>
<summary>⚠️ 为什么这里没有 exe 下载？</summary>

CathayHub **只公开源代码，不提供编译好的 exe**，原因有两条：

1. 它的全文检索是**调用 FileLocator Pro**（Mythicsoft 的商业软件）做的，对方的许可**不允许随本项目再分发**；
2. 完整发行包 250 MB 以上，且要按每个人自己的书库位置配置，公开发一个「开箱即用不了」的二进制意义不大。

- **想自己构建**：源码是完整的（GPL-3.0），照仓库里「从源码构建」一节做即可；检索以外的一切功能
  （浏览、阅读、文件名索引、图文对读、摘录本、截图本、学术引用）**都不依赖** FileLocator Pro。
- **想要现成的可执行版**：在 CathayHub 仓库开一个 Issue 联系作者，会通过网盘单独提供。

</details>

---

## 🔧 专项小工具

<details>
<summary><b>展开看四个专项小工具（碰上特定问题才用，用得少）</b></summary>

### 🩺 CathayRepair —— 修复

> PDF 打不开、一翻页就崩、缺页 —— 先把它抢救回来。

- 修损坏的文件结构，能救回来的先救回来
- 修完自动复核一遍，确认能打开再交给你
- **原件不动**，修好的另存为新文件

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayRepair?color=brightgreen)](https://github.com/zzhjim02/CathayRepair/releases/latest)

### 📑 CathayRestore —— 回写双层

> 把 OCR 出来的 TXT **写回 PDF**，做成「双层」（看着是原图，底下藏着可选可搜的字）。

- 按页对齐，把文字层塞回原来的 PDF
- 原图一像素不动，只是多了一层字
- 支持批量，做完整文件夹

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayRestore?color=brightgreen)](https://github.com/zzhjim02/CathayRestore/releases/latest)

### 📤 CathayExtract —— 文字导出

> 书里已经有文字层了（OCR 过 / 本身是电子排版的），**把文字整批导出成 TXT** ——
> 做笔记、做语料、做统计都方便。

> 📌 **它是「导出」，不是「摘录」**：摘录（看到要紧段落随手存下来）是 CathayHub 里的功能；
> 这个工具干的是**批量把整本书的文字倒出来**。

- **直接取现成的文字层**，不用再跑一遍 OCR（快得多，也更准）
- **保持原来的目录结构**，几百本书导出完还是整整齐齐
- 导出的 TXT 可直接拿去做词频统计、语料分析

[![Releases](https://img.shields.io/github/v/release/zzhjim02/CathayExtract?color=brightgreen)](https://github.com/zzhjim02/CathayExtract/releases/latest)

### 🧭 CathayDir —— 判断横排 / 竖排

> 一批 PDF 摆在那儿，先问一句：**它们到底是横排还是竖排？**
> 古籍多竖排、现代书多横排，分流之后再 OCR，效果差很多。

- 投影法批量判定，**每 10 页抽一页**（可调），几百页的书几秒判完
- 结果列表能**点任意一列表头排序**（文件名按自然序，第 2 册排在第 10 册前面）
- 可存 CSV 留档，也可直接按方向复制成「横排 / 竖排 / 未知」三个文件夹

[![CathayDir](https://img.shields.io/github/v/release/zzhjim02/CathayDir?color=brightgreen)](https://github.com/zzhjim02/CathayDir)


</details>

---

## 📦 已停更项目

<details>
<summary><b>展开看六个已停更的项目（功能已并入后面的工具）</b></summary>

这些**代码都还在、也还能跑**，只是不再更新 —— 功能已经被上面某个新工具收进去。
**如果你是新用户，直接去用右边那个替代品就行。**

| 停更项目 | 原本干什么 | 现在该用什么 |
|---|---|---|
| [CathaySimplify](https://github.com/zzhjim02/CathaySimplify) | 繁简转换 / 编码规范化 | **→ [CathayShelf](https://github.com/zzhjim02/CathayShelf)** |
| [CathayIndex](https://github.com/zzhjim02/CathayIndex) | 本地文件库索引 | **→ [CathayFinder](https://github.com/zzhjim02/CathayFinder)** 的「本地文件库索引」页签 ｜ **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Indexer |
| [CathayViewer](https://github.com/zzhjim02/CathayViewer) | 书库浏览 | **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Viewer |
| [CathayReader](https://github.com/zzhjim02/CathayReader) | 阅读 | **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Viewer |
| [PDF-OCR-Exporter](https://github.com/zzhjim02/PDF-OCR-Exporter) | PDF 文字导出（**无发行版**，仅源码） | **→ [CathayExtract](https://github.com/zzhjim02/CathayExtract)** |
| [PDF-OCR-Exporter-Lite](https://github.com/zzhjim02/PDF-OCR-Exporter-Lite) | 上者的精简版（**无发行版**，仅源码） | **→ [CathayExtract](https://github.com/zzhjim02/CathayExtract)** |

</details>

---

## ❓ 常见问题

<details>
<summary><b>我是新手，先装哪个？</b></summary>

按你书现在的状态往下看，**卡在哪一步就装哪个**：

| 你的书现在什么样 | 装这个 |
|---|---|
| 还没有书，不知道去哪儿找 | ⭐ CathayFinder |
| 有书，但是压缩包 / `.pdg` 打不开 | ⭐ CathayPDG |
| 能打开，但翻开是影印图片，**字复制不出来** | ⭐ CathayOCR（**这一步不补上，后面几步都使不上**） |
| 能复制文字了，书太多要整理归档 | ⭐ CathayShelf |
| 都整理好了，想一秒搜到某句话 | ⭐ CathayHub |

</details>

<details>
<summary><b>怎么判断我的书要不要 OCR？</b></summary>

随便翻开一页，用鼠标**拖一下正文里的字**：

- **能选中、能复制** → 这本书有文字层，**不用 OCR**，直接去 CathayShelf / CathayHub。
- **选不中，整页就像一张图片** → 没有文字层，**必须先跑 CathayOCR**，
  否则既搜不到正文，CathayHub 里也搜不出来。

</details>

<details>
<summary><b>为什么有的软件要跳网盘下载？</b></summary>

每个软件都有自己的 Releases 页面，去那边下就对了。两种情况的差别：

| 情况 | 涉及软件 | 说明 |
|---|---|---|
| **Releases 页面直接下 exe** | ⭐ CathayPDG、⭐ CathayShelf、⭐ CathayFinder（仅程序）、CathayRepair、CathayExtract | 几十 MB，点开就能下、**CathayDir** |
| **Releases 页面里给了网盘地址** | **CathayOCR**（引擎体积大）、**CathayFinder**（27 GB 数据库）、CathayRestore 等 | 超过 GitHub 单文件 2 GB 上限，页面里会写明网盘链接 —— **以那边当时写的为准** |
| **只有源码，没有编译版** | **CathayHub**（许可原因）、两个 PDF-OCR-Exporter（已停更） | 见上文各节的说明 |

</details>

<details>
<summary><b>要装 Python 吗？会不会联网？会不会动我的原文件？</b></summary>

- **要装 Python 吗？** 不用。绝大多数都是打包好的 exe，双击就跑（CathayPDG 连 7-Zip 都内置了）。
- **要联网吗？** 不用，全部纯本地运行，断网也能用。
- **会动我的原文件吗？** 不会。整套工具都不改原件，处理结果另存。
- **这么多软件必须全装吗？** 完全不用。**哪一步卡住了就只装那一个**，它们互不依赖。
- **下载链接失效了怎么办？** 各软件的 Releases 页面会更新；实在找不到就在对应仓库提 Issue 说一声。

</details>

---

## 📄 许可

Cathay 系列软件均为 **GPL-3.0** 开源许可。

<div align="center">

**Cathay 系列软件** —— 面向人文社会科学研究的电子书处理工具流
从找书、OCR、著录，到索引、检索、阅读、摘录

</div>
