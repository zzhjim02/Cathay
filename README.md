# Cathay 系列软件

> **Cathay 系列软件 —— 面向人文社会科学研究的电子书处理工具流。**
> **从找书、OCR、著录到索引、阅读、检索、摘录，覆盖文献处理全流程。**

[![platform](https://img.shields.io/badge/platform-Windows%2010%2F11%20x64-brightgreen)]()
[![license](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)
[![local](https://img.shields.io/badge/运行-纯本地%20·%20不联网-lightgrey)]()

**这个仓库不是软件，是 Cathay 全系列的总目录。**

Cathay 是一套给人文社科研究者（历史、文学、哲学、社会学……）做的**电子书处理工具**，
一共十来个小工具，**各自独立、单独下载、单独使用** —— 不需要全装，哪一步卡住就拿哪个。

**全是纯本地运行**：不联网、不上传、不动你的原件。装好就用，断网也能用。

---

## 一、我该用哪个？先看这张表

别急着一个个看，**先找到你现在卡在哪一步**。

⭐ **主力软件**（日常用得最多，多数人装这五个就够了）：

这五个**按下面的顺序走**（每一步都是下一步的前提）：

| 顺序 | 我现在的情况 | 用这个 | 📥 下载 |
|:--:|---|---|---|
| ① | 想找一本书，不知道去哪儿下 | **⭐ 🔍 CathayFinder** —— 11 个渠道一起搜，告诉你书在哪 | [Releases 页](https://github.com/zzhjim02/CathayFinder/releases/latest) |
| ② | 下下来是压缩包 / 一堆 `.pdg`，打不开 | **⭐ 🧩 CathayPDG** —— 超星读秀的压缩包转成能翻的 PDF | [Releases 页](https://github.com/zzhjim02/CathayPDG/releases/latest) |
| ③ | 翻开是一页页**影印图片**，字选不中、复制不了、也搜不到 | **⭐ 🔤 CathayOCR** —— 让电脑把图片里的字认出来（这就是 OCR），书上就**能搜、能复制**了 | [Releases 页](https://github.com/zzhjim02/CathayOCR/releases/latest) |
| ④ | 书攒了几百本，文件名乱、摆放乱 | **⭐ 📚 CathayShelf** —— 批量建档归位、规范命名、繁简转换 | [Releases 页](https://github.com/zzhjim02/CathayShelf/releases/latest) |
| ⑤ | 书太多了，想一秒搜到某句话（**前提：这些书已经认过字，能复制文字**） | **⭐ 🏛️ CathayHub** —— 索引、检索、阅读、摘录一体 | [仓库页](https://github.com/zzhjim02/CathayHub) |

🔧 **专项小工具**（碰上特定问题才需要，用得少）：

| 我现在的情况 | 用这个 | 📥 下载 |
|---|---|---|
| PDF 打不开、一翻页就崩 | 🩺 CathayRepair —— 先把坏 PDF 救回来 | [Releases 页](https://github.com/zzhjim02/CathayRepair/releases/latest) |
| 认完字，想把字"印"回 PDF 里（做双层） | 📑 CathayRestore —— 图还是原图，底下多一层可搜的字 | [Releases 页](https://github.com/zzhjim02/CathayRestore/releases/latest) |
| 想把 PDF 里的字**整批导出**成 TXT | 📤 CathayExtract —— 把文字层导出成文本文件 | [Releases 页](https://github.com/zzhjim02/CathayExtract/releases/latest) |

> 💡 **按顺序走一遍最省事**：① 找书 → ② 转 PDF → ③ 认字 → ④ 归档 → ⑤ 检索阅读。
> 中间哪一步没遇上就跳过。
> ⚠️ **第 ⑤ 步搜的是"字"不是"图"**：没做过第 ③ 步的影印本，在 CathayHub 里是搜不到正文的。

---

## 二、整套流程长什么样

```
   ① 找书          ② 转成 PDF        ③ 认字            ④ 著录            ⑤ 索引检索
 ┌────────┐      ┌────────┐      ┌────────┐      ┌────────┐      ┌────────┐
 │ Finder │ ───▶ │  PDG   │ ───▶ │  OCR   │ ───▶ │ Shelf  │ ───▶ │  Hub   │
 │ 去哪找书│      │ 压缩包 │      │ 影印本 │      │ 书多了 │      │ 搜一句话│
 │        │      │ 变 PDF │      │ 认出字 │      │ 要归档 │      │ 直接翻开│
 └────────┘      └────────┘      └────────┘      └────────┘      └────────┘
                    ▲                                                  │
                    │                                                  ▼
                 ⓪ 修复                                        阅读 · 摘录
            （PDF 打不开先救一下）
```

**旁路小工具**（用得少，需要时才走）：

```
 ③ 认完字 ──▶ 想让字"印"回 PDF ──▶ CathayRestore（做双层 PDF）
           ──▶ 想把字整批存出来 ──▶ CathayExtract（导出 TXT）
```

**每一步都能单独用**，不用从头走到尾。你的书要是**已经能复制文字**了，直接从 ④ 或 ⑤ 开始就行；
**如果翻开是图片、复制不出字，那就必须先走第 ③ 步**。

---

## 三、软件逐个说

> 📥 **所有下载都点「Releases 页面」** —— 那边永远是最新的版本和最新的下载地址
> （本页面不写死具体链接，免得过时）。

### ⭐ 主力软件（日常用得最多的五个）

### ⭐ 🔍 CathayFinder —— 找书

**一句话**：在 11 个渠道里同时搜一本书，告诉你它在哪儿、编号多少。

**特色功能**
- **11 个渠道一次搜完**：读秀、Z-Library、百度网盘、阿里网盘、维基百科 / 文库 / 共享资源、
  中国地方志、奇点社科、游氏古籍、华中师大近史所，外加你自己的本地文件库
- **精准匹配**：搜「布罗代尔」只出真正含这三个字的，不给你一堆不相干的
- **可以按字段搜**：只搜书名 / 只搜作者 / 只搜出版社 / 只搜编号（编号支持只写前几位）
- **结果行上直接操作**：点一下就「打开所在文件夹」或「复制 SSID」，不用手动复制
- **导出能挑字段**：11 个字段想导哪几个勾哪几个；自动去重、按拼音排序
- **自己电脑的文件夹也能搜**：软件里就有「本地文件库索引」页签，拖进去建库
- **随便停用某个库**：把对应的 `.db` 移走，软件自动置灰跳过，不会假装"搜了但没有"

📥 **[下载 → CathayFinder Releases 页面](https://github.com/zzhjim02/CathayFinder/releases/latest)**

> ⚠️ **注意**：程序本身只有 43 MB，但 11 个渠道的数据库**约 27 GB**，GitHub 单文件上限 2 GB
> 放不下。装的时候看 Releases 页面里的说明 —— **数据库走网盘**，程序和数据要放在同一层，
> 分开就搜不到东西。

---

### ⭐ 🧩 CathayPDG —— 解压转换

**一句话**：把超星 / 读秀下载下来的 PDG 压缩包，转成能看的 PDF。

**特色功能**
- **拖进去就行**：把一个文件夹拖进窗口，剩下的全自动
- **各种压缩包都能开**：zip / rar / 7z / uvz，**带密码的也能解**（内置密码本自动试）
- **中文乱码自动修**：老压缩包里中文名常是一串问号，它自动认编码（GBK / Big5 等）并还原
- **横排竖排分开装**：自动判断版面方向，分两个 PDF 输出，不混在一起
- **真正的零依赖**：7-Zip、转换引擎全部内置，**你什么都不用装**
- **有"环境体检"按钮**：万一缺什么，点一下告诉你是啥、怎么补

📥 **[下载 → CathayPDG Releases 页面](https://github.com/zzhjim02/CathayPDG/releases/latest)**

---

### ⭐ 🔤 CathayOCR —— 认字（OCR）

**一句话**：影印本 / 扫描件翻开是一页页图片，**字选不中、复制不了、也搜不到** ——
它让电脑把图片里的字认出来，之后这本书就**能搜、能复制、能引用**了。

> 🗣️ **说人话**：OCR 就是"让电脑看图认字"。没做这一步的书，只是一堆图片，
> 你在里面搜一个词是搜不到的（后面 CathayHub 的全文检索也依赖这一步）。

**特色功能**
- **批量处理**：扔进去一整个文件夹，然后去泡茶
- **中文识别优化**：对竖排、繁体、古籍版面有专门处理
- **输出可选**：能直接出双层 PDF，也能只出 TXT
- 有 Pro（专业版）/ Lite（轻量版）等规格，按需选

📥 **[下载 → CathayOCR Releases 页面](https://github.com/zzhjim02/CathayOCR/releases/latest)**

> ⚠️ **体积较大**：OCR 引擎本身就很大，个别版本 GitHub 放不下，
> Releases 页面里会给出网盘地址 —— 以那边写的为准。

---

### ⭐ 📚 CathayShelf —— 著录整理

**一句话**：几百本书乱糟糟？批量建档归位、规范命名、繁简转换。

**特色功能**
- **批量著录**：按书名 / 作者 / 出版社把书归到规范的目录里
- **规范命名**：文件名统一成好认的格式
- **繁简转换**：港台繁体书统一成简体（编码规范化也一起做了）
- 支持批量，一次处理整个书库

📥 **[下载 → CathayShelf Releases 页面](https://github.com/zzhjim02/CathayShelf/releases/latest)**

---

### ⭐ 🏛️ CathayHub —— 索引 · 检索 · 阅读 · 摘录

**一句话**：书太多了？给整个书库建索引，然后**一秒搜到某段话**，还能直接翻看、随手摘录。

**这是走完前四步之后的日常入口** —— 索引、检索、阅读、摘录四件事都在它一个里面。

> ⚠️ **用它的前提：书里得有"字"**。它搜的是文字，不是图片。
> 那些没经过 CathayOCR 认字的影印本，只能按文件名搜到，**正文里搜不到东西**。
> 所以顺序是：**先 CathayOCR → 再 CathayHub**。

**特色功能**
- **索引**：把你所有的书（PDF / TXT）扫成全文索引，几万本也能建
- **检索**：搜一句话而不是只搜书名，直接命中到"哪一页有这个词"
- **阅读**：内置阅读器，搜到哪本直接翻开看
- **摘录**：看到要紧的段落，直接摘出来存好（不用再复制粘贴）
- 自带 Indexer 与 Viewer 模块，不再需要另开别的工具

📥 **[前往 CathayHub 仓库](https://github.com/zzhjim02/CathayHub)**

> ⚠️ **CathayHub 只公开源代码，不提供编译好的 exe。** 原因有两条：
> ① 它的全文检索是**调用 FileLocator Pro**（Mythicsoft 的商业软件）做的，
> 对方的许可**不允许随本项目再分发**；② 完整发行包 250 MB 以上，且要按每个人自己的书库
> 位置配置，公开发一个"开箱即用不了"的二进制意义不大。
>
> - **想自己构建**：源码是完整的（GPL-3.0），照仓库里「从源码构建」一节做即可；
>   检索以外的一切功能（浏览、阅读、文件名索引、图文对读、摘录本、截图本、学术引用）
>   **都不依赖** FileLocator Pro，源码拿到手就能跑。
> - **想要现成的可执行版**：在 CathayHub 仓库开一个 Issue 联系作者，会通过网盘单独提供。

---

### 🔧 专项小工具（碰上特定问题才用，用得少）

### 🩺 CathayRepair —— 修复

**一句话**：PDF 打不开、一翻页就崩、缺页 —— 先把它抢救回来。

**特色功能**
- 修损坏的文件结构，能救回来的先救回来
- 修完自动复核一遍，确认能打开再交给你
- **原件不动**，修好的另存为新文件

📥 **[下载 → CathayRepair Releases 页面](https://github.com/zzhjim02/CathayRepair/releases/latest)**

---

### 📑 CathayRestore —— 回写双层

**一句话**：把 OCR 出来的 TXT **写回 PDF**，做成"双层"（看着是原图，底下藏着可选可搜的字）。

**特色功能**
- 按页对齐，把文字层塞回原来的 PDF
- 原图一像素不动，只是多了一层字
- 支持批量，做完整文件夹

📥 **[下载 → CathayRestore Releases 页面](https://github.com/zzhjim02/CathayRestore/releases/latest)**

---

### 📤 CathayExtract —— 文字导出

**一句话**：书里已经有文字层了（OCR 过 / 本身是电子排版的），**把文字整批导出成 TXT 文件** ——
做笔记、做语料、做统计都方便。

> 📌 **它是"导出"，不是"摘录"**：摘录（看到要紧段落随手存下来）是 CathayHub 里的功能；
> 这个工具干的是**批量把整本书的文字倒出来**。

**特色功能**
- **直接取现成的文字层**，不用再跑一遍 OCR（快得多，也更准）
- **保持原来的目录结构**，几百本书导出完还是整整齐齐
- 支持批量，一次导整个书库
- 导出的 TXT 可直接拿去做词频统计、语料分析

📥 **[下载 → CathayExtract Releases 页面](https://github.com/zzhjim02/CathayExtract/releases/latest)**

---

## 四、已停更的项目（功能已并入后面的工具）

这些**代码都还在、也还能跑**，只是不再更新了 —— 它们的功能已经被上面某个新工具收进去。
**如果你是新用户，直接去用右边那个替代品就行。**

| 停更项目 | 状态 | 现在该用什么 |
|---|---|---|
| [CathaySimplify](https://github.com/zzhjim02/CathaySimplify) | 已停更 —— 繁简转换 / 编码规范化 | **→ [CathayShelf](https://github.com/zzhjim02/CathayShelf)**（功能已并入） |
| [CathayIndex](https://github.com/zzhjim02/CathayIndex) | 已停更 —— 本地文件库索引 | **→ [CathayFinder](https://github.com/zzhjim02/CathayFinder)** 的「本地文件库索引」页签 ｜ **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Indexer |
| [CathayViewer](https://github.com/zzhjim02/CathayViewer) | 已停更 —— 书库浏览 | **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Viewer |
| [CathayReader](https://github.com/zzhjim02/CathayReader) | 已停更 —— 阅读 | **→ [CathayHub](https://github.com/zzhjim02/CathayHub)** Viewer |
| [PDF-OCR-Exporter](https://github.com/zzhjim02/PDF-OCR-Exporter) | 已停更 —— PDF 文字导出（**无发行版**，仅源码） | **→ [CathayExtract](https://github.com/zzhjim02/CathayExtract)** |
| [PDF-OCR-Exporter-Lite](https://github.com/zzhjim02/PDF-OCR-Exporter-Lite) | 已停更 —— 上者的精简版（**无发行版**，仅源码） | **→ [CathayExtract](https://github.com/zzhjim02/CathayExtract)** |

---

## 五、下载方式：为什么有的要网盘？

Cathay 系列**每个软件都有自己的 Releases 页面**，去那边下就对了。两种情况的差别：

| 情况 | 涉及软件 | 说明 |
|---|---|---|
| **Releases 页面直接下 exe** | ⭐ CathayPDG、⭐ CathayShelf、⭐ CathayFinder（仅程序）、CathayRepair、CathayExtract | 几十 MB，点开就能下 |
| **Releases 页面里给了网盘地址** | **CathayOCR**（引擎体积大）、**CathayFinder**（27 GB 数据库）、CathayRestore 等 | 超过 GitHub 单文件 2 GB 上限，页面里会写明网盘链接 —— **以那边当时写的为准** |
| **只有源码，没有编译版** | **CathayHub**（许可原因）、两个 PDF-OCR-Exporter（已停更） | 见上文各节的说明 |

**本总览页不写死任何下载地址**：链接会变，各软件的 Releases 页面永远是最新、最准的那一个。

---

## 六、常见问题

**要装 Python 吗？**
不用。绝大多数都是打包好的 exe，双击就跑（CathayPDG 连 7-Zip 都内置了）。

**要联网吗？**
不用，全部纯本地运行。断网也能用。

**会动我的原文件吗？**
不会。整套工具都不改原件，处理结果另存。

**这么多软件，必须全装吗？**
完全不用。**哪一步卡住了就只装那一个**，它们互不依赖。

**我是新手，先装哪个？**
按你书现在的状态往下看，**卡在哪一步就装哪个**：

| 你的书现在什么样 | 装这个 |
|---|---|
| 还没有书，不知道去哪儿找 | ⭐ CathayFinder |
| 有书，但是压缩包 / `.pdg` 打不开 | ⭐ CathayPDG |
| 能打开，但翻开是影印图片，**字复制不出来** | ⭐ CathayOCR（**这一步不补上，后面几步都使不上**） |
| 能复制文字了，书太多要整理归档 | ⭐ CathayShelf |
| 都整理好了，想一秒搜到某句话 | ⭐ CathayHub |

**怎么判断我的书要不要 OCR？**
随便翻开一页，用鼠标拖一下正文里的字：

- **能选中、能复制** → 这本书有文字层，**不用 OCR**，直接去 CathayShelf / CathayHub。
- **选不中，整页就像一张图片** → 没有文字层，**必须先跑 CathayOCR**，
  否则既搜不到正文，CathayHub 里也搜不出来。

**下载链接失效了怎么办？**
各软件的 Releases 页面会更新；实在找不到就在对应仓库提 Issue 说一声。

---

## 七、许可

Cathay 系列软件均为 **GPL-3.0** 开源许可。

---

<div align="center">

**Cathay 系列软件** —— 面向人文社会科学研究的电子书处理工具流
从找书、OCR、著录，到索引、阅读、检索、摘录

</div>
