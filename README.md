# Linux From Scratch 8.0 (lfs 8.0 & lfs 8.0 systemd) in Chinese
lfs 8.0 中文版 以及  lfs 8.0 systemd 中文版

## 联系/加入我们
- 邮箱：ls#linuxstory.org(将#替换为@，并在邮件title标注 lfs 8.0)
- QQ群：580714155
- 微信：请添加 85241823 之后，由我来拉进 lfs 微信群

## 原著及早期翻译作品
### 英文原著
- 原著链接：http://www.linuxfromscratch.org/lfs/view/8.0/
- systemd版原著：http://www.linuxfromscratch.org/lfs/view/8.0-systemd/
- 原作：Gerard Beekmans 
- 原著版本：Revision 8.0, 28 February 2017

### 旧版译著
- lfs 7.7 连接：https://linux.cn/lfs/LFS-BOOK-7.7-systemd/
- 译者及版本：LCTT 团队  Revision 7.7 systemd, 2015
- 最新 Revision 8.0 由 Linux Story 社区发起并组织翻译，成员包括：闻其详、华华、郭楚谋、陈毅钊、邹泳奎、绘卷、胡震宇、李楠、程昊淼、春雨、黄镇杰、王炯、刘桎、刘楊楊、傅奎、张添翼、xinxinyuan 以及 Linux Story 校稿团队。
- Linux Story 通告地址 ：https://linuxstory.org/linux-from-scratch-8-0-released/
- 本项目的经验及组织过程资产将保存在 https://pm.linuxstory.org
- 预发布地址：http://linuxstory.org/lfs/LFS-BOOK-8.0/  http://linuxstory.org/lfs/LFS-BOOK-8.0-systemd/

### 项目计划 （具体 schedule 可能会随人力动态安排）
1. 2月28日-3月5日 预备以及招募团队（已完成，但是还可以接纳新成员）
2. Milestone：3月7日  initial 项目（请大家 fork 本项目建立自己的 dev 分支）
3. 3月7日-3月10日 任务认领及分配 （在两张任务分配表中认领章节后面加上自己的 github id）
4. Milestone：3月11日 正式开始翻译各自认领的部分 （一般来说，认领了 lfs 8.0 也意味着认领了 lfs 8.0 systemd 的对应章节）
5. 3月11日-4月9日 第一阶段翻译 lfs 8.0
6. Milestone：4月10日 第一次 online review meetup
7. 4月11日-5月9日 第二阶段翻译，lfs 8.0 systemd ，同时查漏补缺，校稿工作同步进行
8. 5月10日-5月15日 校稿验收 整理组织过程资产，把翻译过程中留下来的资料集中在一起，发给大家做经验
9. Milestone：5月16日 正式上线发布，同时交由 Linux Story 运营团队做宣传和推广

## 任务分配 
请大家在认领的章节后面加上自己的 github 用户名，并需要注意，为了提高效率，理论上，如果认领了lfs8.0的某章节，也需要认领 lfs 8.0 systemd 的对应章节。任务认领的时候，建议老手礼让新手，让新手优先认领比较容易（相对）的章节。

请优先认领 lfs-8.0 ，届时也将以 lfs-8.0 任务分配表优先

1. lfs-8.0 任务分配表 https://github.com/LinuxStory/lfs-8.0-Chinese/blob/master/lfs-8.0-tasks-table
2. lfs-8.0-systemd 任务分配表 https://github.com/LinuxStory/lfs-8.0-Chinese/blob/master/lfs-8.0-systemd-tasks-table


### 翻译标准化
- 请参见 <https://github.com/LinuxStory/lfs-8.0-Chinese/blob/master/translate-agreement.md>

### 项目约定
1. 建议大家每天抽出一小时或者每周抽出三小时（或更多），不要把工作留到最后，打铁趁热，一鼓作气
2. 先把 lfs 8.0 翻译完，然后是 lfs 8.0 systemd 版，暂时不考虑 blfs
3. 署名默认是署我们各自的本名和 github 地址，希望留ID 或其他网址可以单独标注
4. 保持沟通，每天至少 check 一次邮件和微信，有任何问题欢迎随时发issue，并请参与翻译的同学保持邮箱畅通，每天最少检查一次邮件
5. 沟通形式，以邮件（单向）和 github issues（public） 为正式，微信为辅助即时通信

## 翻译作品
翻译作品将会放在[GitBook](https://www.gitbook.com/book/linuxstory/linux-from-scratch-8-0-book/)上，欢迎阅读！（未发布）

## 翻译流程
1. 首先fork本项目
2. 把fork过去的项目clone到本地
3. 在本地直接修改 html 文件来翻译
4. 完成翻译后 请先自己检查确认无误后，再request合并到主分支
5. 翻译的时候注意不要破坏 html 代码，避免网页显示不正常

## 校稿流程 (待补充)
1. 计划采用交叉校稿的形式来完成校稿

<<<<<<< HEAD
## 项目进度
1. 闻其详定期跟大家邮件和微信通报项目进度
2. 任何问题请第一时间通报
=======

## 翻译进度 （请大家在认领的章节后面加上自己的 github 用户名）
 Table of Contents

    Preface
        Foreword
        Audience
        LFS Target Architectures
        LFS and Standards
        Rationale for Packages in the Book
        Prerequisites
        Typography
        Structure
        Errata
    I. Introduction
        1. Introduction
            How to Build an LFS System
            What's new since the last release
            Changelog
            Resources
            Help
    II. Preparing for the Build
        2. Preparing the Host System
            Introduction
            Host System Requirements
            Building LFS in Stages
            Creating a New Partition
            Creating a File System on the Partition
            Setting The $LFS Variable
            Mounting the New Partition
        3. Packages and Patches
            Introduction
            All Packages
            Needed Patches
        4. Final Preparations
            Introduction
            Creating the $LFS/tools Directory
            Adding the LFS User
            Setting Up the Environment
            About SBUs
            About the Test Suites
        5. Constructing a Temporary System
            Introduction
            Toolchain Technical Notes
            General Compilation Instructions
            Binutils-2.27 - Pass 1
            GCC-6.3.0 - Pass 1
            Linux-4.9.9 API Headers
            Glibc-2.25
            Libstdc++-6.3.0
            Binutils-2.27 - Pass 2
            GCC-6.3.0 - Pass 2
            Tcl-core-8.6.6
            Expect-5.45
            DejaGNU-1.6
            Check-0.11.0
            Ncurses-6.0
            Bash-4.4
            Bison-3.0.4
            Bzip2-1.0.6
            Coreutils-8.26
            Diffutils-3.5
            File-5.30
            Findutils-4.6.0
            Gawk-4.1.4
            Gettext-0.19.8.1
            Grep-3.0
            Gzip-1.8
            M4-1.4.18
            Make-4.2.1
            Patch-2.7.5
            Perl-5.24.1
            Sed-4.4
            Tar-1.29
            Texinfo-6.3
            Util-linux-2.29.1
            Xz-5.2.3
            Stripping
            Changing Ownership
    III. Building the LFS System
        6. Installing Basic System Software
            Introduction
            Preparing Virtual Kernel File Systems
            Package Management
            Entering the Chroot Environment
            Creating Directories
            Creating Essential Files and Symlinks
            Linux-4.9.9 API Headers
            Man-pages-4.09
            Glibc-2.25
            Adjusting the Toolchain
            Zlib-1.2.11
            File-5.30
            Binutils-2.27
            GMP-6.1.2
            MPFR-3.1.5
            MPC-1.0.3
            GCC-6.3.0
            Bzip2-1.0.6
            Pkg-config-0.29.1
            Ncurses-6.0
            Attr-2.4.47
            Acl-2.2.52
            Libcap-2.25
            Sed-4.4
            Shadow-4.4
            Psmisc-22.21
            Iana-Etc-2.30
            M4-1.4.18
            Bison-3.0.4
            Flex-2.6.3
            Grep-3.0
            Readline-7.0
            Bash-4.4
            Bc-1.06.95
            Libtool-2.4.6
            GDBM-1.12
            Gperf-3.0.4
            Expat-2.2.0
            Inetutils-1.9.4
            Perl-5.24.1
            XML::Parser-2.44
            Intltool-0.51.0
            Autoconf-2.69
            Automake-1.15
            Xz-5.2.3
            Kmod-23
            Gettext-0.19.8.1
            Procps-ng-3.3.12
            E2fsprogs-1.43.4
            Coreutils-8.26
            Diffutils-3.5
            Gawk-4.1.4
            Findutils-4.6.0
            Groff-1.22.3
            GRUB-2.02~beta3
            Less-481
            Gzip-1.8
            IPRoute2-4.9.0
            Kbd-2.0.4
            Libpipeline-1.4.1
            Make-4.2.1
            Patch-2.7.5
            Sysklogd-1.5.1
            Sysvinit-2.88dsf
            Eudev-3.2.1
            Util-linux-2.29.1
            Man-DB-2.7.6.1
            Tar-1.29
            Texinfo-6.3
            Vim-8.0.069
            About Debugging Symbols
            Stripping Again
            Cleaning Up
        7. System Configuration
            Introduction
            LFS-Bootscripts-20150222
            Overview of Device and Module Handling
            Managing Devices
            General Network Configuration
            System V Bootscript Usage and Configuration
            The Bash Shell Startup Files
            Creating the /etc/inputrc File
            Creating the /etc/shells File
        8. Making the LFS System Bootable(GitHub username:qq296776435)
            Introduction
            Creating the /etc/fstab File
            Linux-4.9.9
            Using GRUB to Set Up the Boot Process
        9. The End
            The End
            Get Counted
            Rebooting the System
            What Now?
    IV. Appendices
        A. Acronyms and Terms
        B. Acknowledgments
        C. Dependencies
        D. Boot and sysconfig scripts version-20150222
            /etc/rc.d/init.d/rc
            /lib/lsb/init-functions
            /etc/rc.d/init.d/mountvirtfs
            /etc/rc.d/init.d/modules
            /etc/rc.d/init.d/udev
            /etc/rc.d/init.d/swap
            /etc/rc.d/init.d/setclock
            /etc/rc.d/init.d/checkfs
            /etc/rc.d/init.d/mountfs
            /etc/rc.d/init.d/udev_retry
            /etc/rc.d/init.d/cleanfs
            /etc/rc.d/init.d/console
            /etc/rc.d/init.d/localnet
            /etc/rc.d/init.d/sysctl
            /etc/rc.d/init.d/sysklogd
            /etc/rc.d/init.d/network
            /etc/rc.d/init.d/sendsignals
            /etc/rc.d/init.d/reboot
            /etc/rc.d/init.d/halt
            /etc/rc.d/init.d/template
            /etc/sysconfig/modules
            /etc/sysconfig/createfiles
            /etc/sysconfig/udev-retry
            /sbin/ifup
            /sbin/ifdown
            /lib/services/ipv4-static
            /lib/services/ipv4-static-route
        E. Udev configuration rules
            55-lfs.rules
        F. LFS Licenses
            Creative Commons License
            The MIT License



## 翻译校审建议
1. 使用markdown进行翻译校审，文件名必须使用英文，单词之间请使用短横线“-”做连字符
2. 翻译校审后的文档请放到source文件夹下的对应章节中，然后pull request即可
3. 有任何问题欢迎随时发issue，并请参与翻译的同学保持邮箱畅通，每天最少检查一次邮件
4. 术语尽量保证和已翻译的一致，也可以查询[微软术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)
5. 请将翻译过程中用到的术语保存到[Linux Story术语词典](https://github.com/LinuxStory/StoryTranslation/blob/master/Dictionary.md)
>>>>>>> 0bfb1004776aa97a48f403561b27bc8a3213d9f2

## 关于版权
根据原著作者的要求，翻译成果属于公有领域(CC0)，翻译参与人员及原著作者享有署名权，署名顺序将按加入项目的顺序排列。

## 如果不太了解 lfs ？
 - [维基百科上的介绍 Linux From Scratch](https://zh.wikipedia.org/wiki/Linux_From_Scratch)

## 如果不太了解 github 使用？
- [GitHub 入门使用教程-图文并茂](http://developer.51cto.com/art/201407/446249_all.htm) 很简洁的说明如何使用，看图即可明白。 
- [GitHub help](https://help.github.com/) Sometimes you just need a little help. 中文翻译版在此[GitHub 帮助文档](https://github.com/waylau/github-help)。
- [GitHub 之 fork 简介指南](https://linux.cn/article-4292-1.html) 帮你理解清楚什么是fork，fork 的工作流有哪些。
- [GitHub-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) 关于使用 git 和 GitHub 的一些技巧汇总，中文版在此[GitHub秘籍](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)
- [The GitHub Blog](https://github.com/blog) GitHub 官方博客，关注最新动态。
- [How to Build a GitHub](http://zachholman.com/talk/how-to-build-a-github/) GitHub一名早期员工介绍GitHub的历史，5年108名员工无人离职。
- [阳志平：如何高效利用GitHub](http://www.yangzhiping.com/tech/github.html) 介绍的挺全，以及一些用法，如怎样利用GitHub来学习、演讲找工作等。
- [GitHub 支持的 emoji表情 emoji-cheat-sheet](http://www.emoji-cheat-sheet.com/) :v: :clap:  感觉不好找到需要的表情？试试[Emoji Searcher](http://emoji.muan.co/) 
- [GitHub guides](https://guides.github.com/) 从`Contributing to Open Source on GitHub`、`Hello World`、`Forking Projects`、`Be Social`、`Making Your Code Citable`、`Mastering Issues`、`Mastering Markdown`、`Mastering Wikis`、`Getting Started with GitHub Pages` 等9个方面图文详细讲解每一步如何使用，以及能做哪些功能。
- [fork-me-on-GitHub](https://github.com/blog/273-github-ribbons) 个人博客、技术博客等如果需要添加GitHub 的彩带，可以使用此方法。
- [蒋鑫-GotGitHub](GotGitHub.md) 《Git权威指南》的作者，对GitHub有很深的了解。（由于首页打开太慢，放到了本文目录中，下面的文章既是）

## GitHub Skills
- [Using Git blame to trace changes in a file](https://help.github.com/articles/using-git-blame-to-trace-changes-in-a-file/) 如果你想看某一个文件中每一行是谁修改的，为什么修改？那么尽情的使用 `blame` 按钮，发现文件的历史。
- [GitHub 搜索技巧](https://help.github.com/categories/search/)
- [Closing issues via commit messages - 通过提交信息关闭Issues](https://help.github.com/articles/closing-issues-via-commit-messages/)
- [Update your forked code from original repository - 如何更新自己 Fork 的代码](https://github.com/ysc/APDPlat/wiki/%E5%A6%82%E4%BD%95%E6%9B%B4%E6%96%B0%E8%87%AA%E5%B7%B1Fork%E7%9A%84%E4%BB%A3%E7%A0%81)

更多关于 GitHub 的内容请查看：[GitHubHelp](https://help.github.com/) 查找需要的信息。
