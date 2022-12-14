# GBA 开发资源列表

* * *

# 介绍

*   [GBA 技术介绍](https://copetti.org/projects/consoles/game-boy-advance)

## 社区

*   [GBADev Discord Server](https://discord.io/gbadev)——这是如今大家常去的地方。过来打个招呼。

    IRC 用户信息

    所有房间都桥接到[EFnet 上的 IRC 频道](http://www.efnet.org/?module=servers)。

    **主频道**

    + `#gbadev` -一般聊天

    **附加频道**

    + `#gba-meta` -社区反馈/讨论
    + `#gba-help` -帮助&支持
    + `#gba-emudev` -仿真器开发
    + `#gba-asm` - ARM/Thumb 汇编和 CPU 架构
    + `#gba-showcase` -分享你正在做的事情！
    + `#gba-music` -聆听、作曲和音频编程
    + `#gba-offtopic` -题外聊天
    + `#gba-docs` -社区文档项目(教程、技术文档等)。)
    + `#gba-tools`——工具讨论(砂砾、平铺、无菌等。)

    **项目特定渠道**

    + `#gba-toolchain` - gba-toolchain、agbabi 和 gba-plusplus 开发&支持
    + `#butano` - Butano 引擎开发&支持
    + `#natu` - Natu 工具包开发&支持

*   [GBADev](https://gbadev.org) -场景的长期主页。定期更新最新的新闻和发布。

*   打开 GBA temp——该网站带有 GBA 名称，但现在控制台被归入后座议员。

# 证明文件

*   [GBATEK](https://problemkaputt.de/gbatek.htm)-GBA 和 NDS 硬件的编程规格
*   [cow bit 虚拟硬件规格](https://www.cs.rit.edu/~tjh8300/CowBite/CowBiteSpec.htm) -旧的 GBA 硬件文档
*   [音频推进](http://belogic.com/gba/) -音频硬件文档和基本测试 rom 

## 教程

*   [Tonc](https://www.coranac.com/tonc/text/toc.htm) -完整编程教程
*   [game boy 上的声音前进](https://deku.gbadev.org/program/sound1.html)——如何编写自己的混音器/ MOD 音乐播放器

## 文章

*   [Gameboy 高级资源管理](https://www.gamasutra.com/view/feature/131491/gameboy_advance_resource_management.php)-GBA 各内存区域的分配技术
*   [管理GameBoyAdvance 上的精灵 Cel VRAM](https://pineight.com/gba/managing-sprite-vram.txt) 打开——动画精灵的 VRAM 流方法分析
*   [使用 Beepbox 进行 GBA 音乐创作](https://rentry.org/beepbox-gba-music)

# 软件开发

## 编译程序

*   [devkitARM](https://devkitpro.org) - C/C++交叉编译器工具链，该工具链包括 libgba、libtonc、maxmod 以及各种工具和示例项目。
*   [GBA-工具链](https://github.com/felixjones/gba-toolchain) -基于 GNU Arm 嵌入式工具链的 devkitARM 替代方案。
*   [gvasm](https://github.com/velipso/gvasm) ——专门为 GBA 家酿设计的独立汇编器和反汇编器(WIP)

## 工具包

*   [Rust-控制台](https://github.com/rust-console/gba)-Rust 中的 GBA 编程，外加教程。
*   [natu](https://github.com/exelotl/natu)-Nim 中的 GBA 编程(提供了 libtonc、maxmod 等周围的包装器)。
*   [gba-modern](https://github.com/JoaoBaptMG/gba-modern) -用 modern C++编写 gba 游戏。
*   [ZigGBA](https://github.com/wendigojaeger/ZigGBA) - WIP SDK 用于使用 Zig(受 Tonc 启发)创建 GBA 游戏。
*   [布塔诺 打开新窗口](https://github.com/GValiente/butano)——现代 C++高级引擎 GBA。
*   [BPCore 引擎](https://github.com/evanbowman/BPCore-Engine)——用 Lua 编程语言创建 GBA 应用
*   [GBA Dlang](https://github.com/redthing1/gba_dlang) - WIP SDK 用于 GBA 开发使用 D，使用 LLVM 工具链。提供全功能的 TONC、GBFS、Maxmod。
*   [黄昏](https://github.com/redthing1/dusk) -简单、轻量、直观的 GBA 游戏开发框架
*   [gbsenpai](https://github.com/asiekierka/gbsenpai) - GB Studio 播放器 GBA 端口有了一些增强。

## 图书馆

*   [阿格巴比](https://github.com/felixjones/agbabi)——嵌入式应用二进制接口库(上下文切换、除法、irq、memcpy、sine)。
*   [gba-plusplus](https://github.com/felixjones/gba-plusplus)-libgba 和 libtonc 的现代 C++替代。
*   [HeartLib](https://github.com/Sterophonick/HeartLib)——综合 C 库灵感来自经典的 HAMLib。
*   [libseven](https://github.com/LunarLambda/libseven)——轻量级，从零开始替换 libgba。
*   [GBAdv](https://github.com/sverx/GBAdv)-libgba 之上的高级实用程序。
*   [Maxmod](https://maxmod.devkitpro.org) -音乐和声音库(支持。mod，。xm，. s3m，.它)
*   [Apex 音响系统](https://github.com/stuij/apex-audio-system) -音乐和声音库(支持。只有 mod，但是*非常*好的性能)
*   [Krawall](https://github.com/sebknzl/krawall) -音乐和声音库(支持。xm，. s3m)
*   [Pimpmobile](https://github.com/kusma/pimpmobile) -音乐库(支持。mod，。xm)
*   [GBT 播放器](https://github.com/AntonioND/gbt-player) -使用 DMG 声道的音乐库(接近 0%的 CPU 使用率)。
*   [posprintf](http://www.danposluns.com/gbadev/posprintf/index.html) 打开——一个用 Thumb 汇编程序编写的`sprintf`例程。
*   [GBFS](https://pineight.com/gba/#gbfs) -实用文件系统

## 模拟器

*   [mGBA](https://mgba.io)——积极开发 GBA 仿真器。在许多平台上运行。通过 GDB 存根的文本调试器。
*   [No$gba](https://problemkaputt.de/gba.htm) -古老的 gba 模拟器。仅 Windows，但在葡萄酒下运行良好。不是很积极地维护，但仍不时得到更新。运动图形调试器。
*   [NanoBoyAdvance](https://github.com/nba-emu/NanoBoyAdvance) - GBA 仿真器精度高，特别是在时序和 CPU 仿真方面。没有调试功能。
*   [先生 FPGA 实现 打开新窗口](https://github.com/MiSTer-devel/GBA_MiSTer) -需要[先生 打开新窗口](https://github.com/MiSTer-devel/Main_MiSTer/wiki) 设置才能运行。

# 仿真器开发

## 测试

*   [mGBA 测试套件](https://github.com/mgba-emu/suite)
*   [GBA 套件](https://github.com/jsmolka/gba-suite)
*   [240 p-测试-迷你](https://github.com/pinobatch/240p-test-mini) -视频信号测试
*   [NBA 硬件测试](https://github.com/nba-emu/hw-test)

# 自制啤酒

*   [好孩子前进](https://github.com/exelotl/goodboy-advance) 打开——2018 年制造，并且有关于它是如何制造的很好的信息。
*   [Celeste 经典](https://github.com/JeffRuLz/Celeste-Classic-GBA) - 2019 port of Pico8 版 Celeste。
*   [GBADoom](https://github.com/doomhack/GBADoom)-2019/2020 GBA port of pr boom 版 Doom。
*   [BlindJump](https://github.com/evanbowman/blind-jump-portable)——冒险游戏，2020 年开发。实施链接电缆多人，全数字音频。
*   [Tigermoth](https://github.com/pmprog/TigermothGBA)——子弹地狱游戏，为 GBAJam 2021 开发
*   [Duster](https://github.com/redthing1/duster) -一款时尚的 gba 战略棋盘游戏
*   [OpenLara](https://github.com/XProger/OpenLara) -经典古墓丽影开源引擎

# 短裤睡衣

*   [GBA Jam 2021](https://itch.io/jam/gbajam21/entries)
*   [GBA Winter Jam’21](https://itch.io/jam/gba-winter-jam-2021/entries)

# 杂集

*   [gba_bios](https://github.com/PikalaxALT/gba_bios) - WIP 拆卸 Game Boy 进阶 bios
*   [GBA 裸机代码](https://github.com/PeterLemon/GBA)——Krom 的各种实验，如视频回放和 3D，用 ARM 汇编编写
*   [dkarm_gba_docker](https://github.com/redthing1/dkarm_gba_docker) ——一个 docker 映像，包括 DevkitARM 和其他 GBA SDK 工具，打包在一起以允许构建中一致的工具链配置和再现性。也有助于确保持续集成的一致构建环境。

## 转储 GBA BIOS

*   [软件中断$1F / MidiKey2Freq](https://gist.github.com/modwizcode/b4afc78ea74fb453be3bcaf3d3bc8adc) 打开，规范方法
*   [破解 GBA BIOS 通过 endrift](https://mgba.io/2017/06/30/cracking-gba-bios/) 打开
*   [转储 GBA BIOS](https://gist.github.com/MerryMage/797c523724e2dc02ada86a1cfadea3ee) 打开，另一种狂欢的方法

## 逆向工程

*   [逆向工程一个 GameBoyAdvance游戏](https://medium.com/@bruno.macabeus/reverse-engineering-a-gameboy-advance-game-introduction-ec185bd8e02)——一系列详细的帖子以及关于开发一个[关卡编辑器](https://github.com/macabeus/klo-gba.js) 为 *Klonoa:梦想帝国*
*   [口袋妖怪红宝石](https://github.com/pret/pokeruby) - C 编程语言注释口袋妖怪红宝石的反汇编

## 历史链接

*   [HEL](http://www.console-dev.de/project/hel-library-for-gba/) -基于 HAM(过去的经典 SDK)构建的 GBA C 库
*   [大头针指南](http://members.iinet.net.au/~freeaxs/gbacomp/) ，以压缩、文件系统、屏幕效果和为 Gameboy 升级的 MOD 播放器
