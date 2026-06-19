# Awesome Game Translations [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 精选的电子游戏社区翻译、汉化与本地化项目列表。

社区翻译让玩家跨越语言障碍，也让经典游戏在不同文化中延续生命力。本列表收录由社区驱动的游戏翻译项目，按目标翻译语言分类。

**其他语言版本 / Other Languages：** [English](README-en.md) · [日本語](README-ja.md) · [한국어](README-ko.md)

> 尚未创建的语言版本欢迎贡献！

---

## 简体中文 / 繁體中文

> `简中` = 简体中文 · `繁中` = 繁體中文。简体与繁体属于同一语言的书写变体，收录在同一分区。

### 翻译工具与框架

通用翻译工具，不限于特定游戏。

- **MisakaTranslator / 御坂翻译器**：Galgame / 文字游戏 / 漫画多语种实时机翻工具。支持 Hook 和 OCR 两种文本提取方式，兼容离线翻译，内置分词与字典功能。`简中` `C#` [GitHub](https://github.com/hanmin0822/MisakaTranslator)
- **LunaTranslator**：视觉小说翻译器。支持 HOOK 提取（几乎适配所有常见和冷门视觉小说）、内嵌翻译、HOOK 模拟器（NS/PSP/PSV/PS2）、OCR、丰富的翻译接口（含大语言模型和离线翻译）、日语分词及假名注音、语音合成与识别。`简中` `繁中` `Python` [GitHub](https://github.com/HIllya51/LunaTranslator)
- **AiNiee**：专注于 AI 翻译的一键自动翻译工具。深度支持 Mtool、Renpy、Translator++、ParaTranz 等游戏文本导出工具，同时支持 Epub/TXT 小说、Srt/Ass 字幕、Word/PDF/MD 文档等格式。`简中` `Python` [GitHub](https://github.com/NEKOparapa/AiNiee)
- **FFXIVChnTextPatch-GP**：FINAL FANTASY XIV 国际服中文漢化器。支持 CSV 汉化、中国服档案导入，修正 5.5X 以后版本的中文字库补丁。支持 Windows / macOS / SteamOS。`繁中` `简中` `C#` [GitHub](https://github.com/GpointChen/FFXIVChnTextPatch-GP)

### FPS / 射击

- **Call of Duty 4: Modern Warfare** 《使命召唤 4：现代战争》：基于游侠汉化组 2009 年原版成果的现代化跨平台安装器。将原版私有 EXE 工具链替换为纯 Python 实现，支持 Windows / Linux (SteamOS) / macOS。`简中` [cod4-cn-patch](https://github.com/thedavidweng/cod4-cn-patch)
- **ULTRAKILL**：社区翻译 Mod，支持将游戏全文本翻译为多种语言。采用 JSON 格式语言文件，方便社区贡献翻译。`简中` `多语言` [UltrakULL](https://github.com/ClearwaterUK/UltrakULL)

### RPG / 角色扮演

- **Deus Ex** 《杀出重围》：通用本地化工具包 (GOTY / 1.112fm)。处理二进制层面的工作：重写 UE1 文本包、从 TTF 生成字体图集、为 CJK 语言打 DLL 自动换行补丁。`简中` `Python` [deus-ex-i18n-toolkit](https://github.com/fmwizard/deus-ex-i18n-toolkit)
- **Shadowrun: Dragonfall – Director's Cut** 《暗影狂奔：龙陨 – 导演剪辑版》：完整简体中文汉化。覆盖全文本，提供 Steam / GOG / Epic 三平台安装包。`简中` [shadowrun-dragonfall-zh](https://github.com/fmwizard/shadowrun-dragonfall-zh)
- **Pokémon Gold / Silver** 《宝可梦·金/银》：韩版 ROM 的简体中文汉化补丁。精细翻译全部游戏文本，修复训练家名称等细节。`简中` [PKMN_GSCHS](https://github.com/TomJinW/PKMN_GSCHS)
- **Starsector** 《远行星号》：简体中文本地化。`简中` [Starsector-0951-Localization](https://github.com/TruthOriginem/Starsector-0951-Localization) · [Starsector-Localization-CN](https://github.com/TruthOriginem/Starsector-Localization-CN)
- **Battle Brothers** 《战场兄弟》：中文翻译项目，通过 Paratranz 协作翻译。`简中` [Battle-Brothers-CN](https://github.com/shabbywu/Battle-Brothers-CN)
- **Lilith's Throne** 《莉莉丝的王座》：中文本地化项目。`简中` [liliths-throne-chinese-localization](https://github.com/chinese-liliths-throne/liliths-throne-chinese-localization)
- **Star Wars: Knights of the Old Republic** 《星球大战：旧共和国武士》(KOTOR)：社区中文本地化，通过 [Paratranz](https://paratranz.cn/projects/16652) 协作翻译。`简中`

### 模拟经营

- **Mewgenics**：简体中文汉化补丁。覆盖 NPC 对话、物品与技能说明、UI 界面文本等。采用 AI 辅助翻译 + 游戏内测试校对，支持自定义字体替换。`简中` [Mewgenics-Chinese-Translation](https://github.com/rainzz-512/Mewgenics-Chinese-Translation)
- **Tropico 6** 《海岛大亨 6》：部分汉化。`简中` [Tropico6-part-zh-hans](https://github.com/gamesyofo/Tropico6-part-zh-hans)

### 冒险 / 叙事

- **The Pale Beyond**：简体中文本地化。25,000+ 条翻译，覆盖全部剧情对话、叙事文本和 UI 界面。`简中` [ThePaleBeyond_Chinese](https://github.com/RandolphVI/ThePaleBeyond_Chinese)
- **SOMA**：Frictional Games 的科幻恐怖游戏简体中文补丁。逐行精细汉化，支持游戏上架的所有平台，支持成就。`简中` [SOMA-Simplified-Chinese](https://github.com/COPtimer/SOMA-Simplified-Chinese)
- **Return of the Obra Dinn** 《奥伯拉丁的回归》：玩家自制中文补丁包。修改游戏内翻译并相应修改贴图，修复字体字形，将对话改为双语显示。支持 Windows 和 macOS。`简中` [obradinn_chinese_pack](https://github.com/Yide-Zhang/obradinn_chinese_pack)
- **Esoteric Ebb** 《奥秘消退》：简体中文汉化补丁。`简中` [EsotericEbb_Chinese](https://github.com/RandolphVI/EsotericEbb_Chinese)

### 解谜 / 平台

- **Hue**：繁體中文汉化补丁。使用 Unity Doorstop 动态注入 + HarmonyX 加载中文数据，不修改游戏原始文件。支持 Steam 和 Epic 版本。`繁中` `C#` [HueZh](https://github.com/Sheep-y/HueZh)
- **Wandersong** 《流浪之歌》：非官方简体中文翻译补丁。使用 xdelta3 制作补丁，支持 Windows 和 Linux（实验性）。`简中` [wandersong-chs](https://github.com/AnXing233/wandersong-chs)

### 集换式卡牌

- **Pokémon TCG Live** 《宝可梦集换式卡牌 Live》：中文化模组（基于 BepInEx）。`简中` [ptcg-live-zh-mod](https://github.com/Hill-98/ptcg-live-zh-mod)
- **Magic: The Gathering** 《万智牌》：全部牌张文本的简体中文翻译，数据存储在 GitHub，通过 [Paratranz](https://paratranz.cn/projects/10112) 协作翻译。`简中` [magic-cards-zhs](https://github.com/HeliumOctahelide/magic-cards-zhs)

### 复古 / 模拟器

- **Neon Genesis Evangelion 2** 《新世纪福音战士 2：被创造的世界》(PSP)：完整、可复现的中文汉化补丁。专注于文本结构解析、翻译管理、自动补丁流程。`简中` [nge_2_re](https://github.com/xeonliu/nge_2_re)

### 策略游戏 Mod

大型策略游戏的 Mod 汉化项目。同一游戏的多个 Mod 排列在一起。

#### Hearts of Iron IV 《钢铁雄心 4》

- **Kaiserreich**：HOI4 最著名的架空历史 Mod，日语翻译通过 [Paratranz](https://paratranz.cn/projects/500) 协作。`日文` [GitHub](https://github.com/Kaiserreich/Kaiserreich-4)
- **千周之国 (Thousand Week Reich)**：DH 系大型架空 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/192) 协作。`简中`
- **Cold War Iron Curtain**：钢四最著名的冷战 Mod 新汉化项目，通过 [Paratranz](https://paratranz.cn/projects/19435) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=1458561226)
- **苍山如海 (The Rolling Hills Sea-blue)**：简中转英文翻译项目，通过 [Paratranz](https://paratranz.cn/projects/9059) 协作。`英文`
- **Roma Invicta**：公元 456 年西罗马帝国背景 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/18463) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3641802283)

#### Crusader Kings II 《十字军之王 2》

- **Chinese Localisation**：CK2 官方中文本地化，从 Paratranz 自动同步。`简中` [paratranz/CK2-Chinese-Localisation](https://github.com/paratranz/CK2-Chinese-Localisation)

#### Crusader Kings III 《十字军之王 3》

- **After the End**：末日之后，北美大陆背景 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/5071) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3192256710)
- **新 More Bookmarks**：CK3 更多书签 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/8855) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/changelog/2216670956)
- **Anbennar**：架空世界大型 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/13438) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3425084845)

#### Europa Universalis IV 《欧陆风云 4》

- **Anbennar**：架空世界类大型模组汉化，通过 [Paratranz](https://paratranz.cn/projects/1732) 协作，106 名成员参与。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=1385440355)

#### Total War: Warhammer III 《全面战争：战锤 3》

- **亚登·KoA (Rework Wonderland)**：重置·修正 Mod 汉化，通过 [Paratranz](https://paratranz.cn/projects/8668) 协作。`简中`

#### Mount & Blade 《骑马与砍杀》

- **Aut Caesar aut nihil**：罗马皇帝尼禄在位时期 Mod，20 多个势力，通过 [Paratranz](https://paratranz.cn/projects/7978) 协作。`简中` [Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=1612746028)

### 经典 / 复古

- **Call of Duty 4: Modern Warfare** 《使命召唤 4：现代战争》：（同上·FPS）将 2009 年汉化补丁现代化，跨平台可用。
- **Deus Ex** 《杀出重围》：（同上·RPG）2000 年经典的完整本地化管线。
- **Unreal / Unreal Tournament / UT2004** 《虚幻》系列：多语言本地化项目。覆盖 Unreal (v227+)、Unreal Tournament (v469+)、UT2004 (v3374+)，支持 20+ 种语言（含简中和繁中进行中）。`简中` `繁中` `多语言` [OldUnreal-Localization](https://github.com/OldUnreal/OldUnreal-Localization)
- **Thief Gold** 《神偷：黄金版》：经典沉浸式模拟游戏初代社区中文本地化，通过 [Paratranz](https://paratranz.cn/projects/19407) 协作，招募译者中。`简中`
- **Warcraft III** 《魔兽争霸 3》：自定义地图「洛丹伦之战：巨变之前」(LORDAERON: TF) 汉化，通过 [Paratranz](https://paratranz.cn/projects/19427) 协作。`简中`

---

## 翻译平台与社区

- [Paratranz](https://paratranz.cn)：协作翻译平台，在中文游戏汉化社区中广泛使用。支持 JSON、CSV 等游戏文本格式的在线协作翻译。
- [Crowdin](https://crowdin.com)：国际化本地化平台，被 Minecraft、CS2 等大型游戏采用。对开源项目免费，支持 GitHub/GitLab 集成。
- [机核 GCORES](https://www.gcores.com)：中文游戏文化社区，常有汉化项目分享。
- [3DM 汉化](https://www.3dmgame.com)：国内老牌游戏汉化组。
- [游侠网](https://www.ali213.net)：国内最大的单机游戏社区之一，拥有众多汉化组。

---

## 贡献

欢迎提交 Pull Request 或通过 [Issue](../../issues/new?template=suggest_project.yml) 推荐项目！请先阅读[贡献指南](CONTRIBUTING.md)。

如需添加新的语言版本（如日文、韩文），请创建对应的 `README-<语言代码>.md` 文件并提交 PR。

## 许可证

[![CC0 1.0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
