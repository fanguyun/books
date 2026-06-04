# Books 与 Skills 索引

本目录用于存放电子书素材，以及基于书籍提炼出来的本地 Codex skills。

说明：原始电子书文件用于本地知识整理，默认不推送到远程仓库；远程仓库应主要保留索引文档和 `.agents/skills/`。

## 目录说明

- 书籍目录：按主题分类存放 EPUB / MOBI 等电子书文件。
- `.agents/skills/`：存放已经生成、可直接调用的本地 skills。
- 版本控制策略：`README.md`、`AGENTS.md`、`.agents/skills/` 纳入 Git；原始电子书文件默认仅本地保留。

## 书籍目录

### 成功学

- `原则_瑞·达利欧 [瑞·达利欧].epub`
- `搞定1~3_戴维·艾伦.epub`
- `纳瓦尔宝典_埃里克·乔根森.epub`
- `思考致富_【美】希尔（Hill，N. ）.epub`
- `李笑来-财富自由之路-电子工业出版社 (2017) (李笑来) (Z-Library).epub`

### 技术类

- `github-roam.epub`
- `JavaScript高级程序设计(第3版) (图灵程序设计丛书) -- 泽卡斯(Zakas_ Nicholas C_) -- John Wiley & Sons, Inc_ (trade), Indianapolis, IN, 2012 -- 人民邮电出版社 -- 9781118026694 -- f6e74e6283600c524d627d52a324627e -- A.epub`
- `JavaScript设计模式与开发实践+(图灵原创).epub`
- `技术人修炼之道：从程序员到百万高管的72项技能（第2版）.mobi`
- `计算机是如何工作的-人人都能懂的计算机软硬件工作原理 -- 【美】马修·贾斯蒂斯 -- ad519e9b6c8b79acf52d766195a65704 -- Anna’s Archive.epub`
- `growth.epub`

### 育儿

- `无条件养育 ([美]艾尔菲·科恩 [[美]艾尔菲·科恩]) (z-library.sk, 1lib.sk, z-lib.sk).epub`

### 经济学

- `底层逻辑 看清这个世界的底牌_刘润.epub`
- `周金涛 - 涛动周期论 (机械出版社工业) - libgen.li.mobi`
- `周期 -- 霍华德·马克斯 [霍华德·马克斯] -- 2019 -- 中信出版集团 -- 9787508699141 -- 0465c7f9e08207bde76112155d873388 -- Anna’s Archive.epub`

### 教育类

- `我在100天内自学英文翻转人生 -- 张同完 -- 2019 -- 北京日报出版社 -- 5ad3878f751976de0e60be82e1f949b3 -- Anna’s Archive.epub`
- `如何阅读一本书_莫提默·J. 艾德勒.mobi`

### 国学

- `论语译注 (国学经典译注) -- 金良年撰 -- 2012 -- 上海古籍出版社 -- 74a137230109f8b5a44446e9c4d8456f -- Anna’s Archive.mobi`

### 心理学

- `逆转思维_姚颖编著 [姚颖编著].epub`
- `思考快与慢_[美]丹尼尔·卡尼曼 [[美]丹尼尔·卡尼曼].epub`
- `影响力_罗伯特•西奥迪尼.epub`

### 社会学

- `局外人 by 加缪 (z-lib.org).epub`
- `加缪作品精装版：西西弗神话 (加缪作品系列) by 阿尔贝·加缪(Albert Camus) [阿尔贝·加缪(Albert Camus)] (z-lib.org).epub`
- `李光耀观天下 -- 李光耀 -- 2018 -- cj5_3411 -- df231a76aed54a989549b9c5eedeeb82 -- Anna’s Archive.mobi`
- `枪炮、病菌与钢铁_[美]贾雷德·戴蒙德 [[美]贾雷德·戴蒙德].epub`
- `加缪作品精装版：鼠疫 by 阿尔贝·加缪(Albert Camus) [阿尔贝·加缪(Albert Camus)] (z-lib.org).epub`

## 已有 Skills

当前 `.agents/skills/` 下已有以下本地 skills：

### `kohn-unconditional-parenting`

- 路径：`.agents/skills/kohn-unconditional-parenting/SKILL.md`
- 作用：`《无条件养育》` 的完整知识库版 skill。
- 用途：用于系统分析奖励、惩罚、控制、自主权、成绩压力、视角转换等核心框架。

### `无条件养育`

- 路径：`.agents/skills/无条件养育/SKILL.md`
- 作用：`《无条件养育》` 的中文别名入口。
- 用途：方便按中文名称调用，并跳转到核心知识库或实战教练版。

### `kohn-unconditional-parenting-coach`

- 路径：`.agents/skills/kohn-unconditional-parenting-coach/SKILL.md`
- 作用：`《无条件养育》` 的实战教练版 skill。
- 用途：把书里的原则转换成具体场景下的分析、建议步骤、示范话术和修复动作。

## 后续维护建议

- 新增书籍时，按现有主题分类补充到对应小节。
- 新生成 skill 时，在“已有 Skills”里同步增加名称、路径和用途说明。
