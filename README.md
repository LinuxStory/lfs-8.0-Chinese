# Linux From Scratch 8.0 (lfs 8.0 & lfs 8.0 systemd) in Chinese
lfs 8.0 中文版 以及  lfs 8.0 systemd 中文版

## 联系/加入我们
- 邮箱：ls#linuxstory.org(将#替换为@，并在邮件title标注 lfs 8.0)
- QQ群：580714155

## 原著及早期翻译作品
### 原著
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
- 预发布地址：http://linuxstory.org/lfs/LFS-BOOK-8.0/

### 项目计划 （具体 schedule 可能会随人力动态安排）
1. 2月28日-3月5日 预备以及招募团队（已完成，但是还可以接纳新成员）
2. Milestone：3月6日  intial 项目（请大家加入 Linux Story 的 github 账号）
3. 3月7日-3月10日 任务认领及分配 （在认领章节后面加上自己的 github id）
4. Milestone：3月11日 正式开始翻译各自认领的部分 （一般来说，认领了 lfs 8.0 也意味着认领了 lfs 8.0 systemd 的对应章节）
5. 3月11日-4月9日 第一阶段翻译 lfs 8.0
6. Milestone：4月10日 第一次 online review meetup
7. 4月11日-5月9日 第二阶段翻译，lfs 8.0 systemd ，同时查漏补缺，校稿工作同步进行
8. 5月10日-5月15日 校稿验收 整理组织过程资产，把翻译过程中留下来的资料集中在一起，发给大家做经验
9. Milestone：5月16日 正式上线发布，同时交由 Linux Story 运营团队做宣传和推广

### 翻译标准化
1. 可参考  CLReq https://www.w3.org/TR/clreq
2. 简单约定：A)专有名词的大小写、连字符等请保持跟原名或注册商标一致；B)一般情况下使用中文全角标点，但是文件名，版本号等其中出现的符号用保持用原来英文半角符号。C）待补充
3. 对于不确定的专有名词翻译，请及时拿出来讨论
4. 项目中使用到的术语、专业名词，请更新到术语表中 https://github.com/LinuxStory/StoryTranslation/blob/master/Dictionary.md 
5. 编辑器请统一使用 UTF-8 无BOM，Windows 下尽量使用 Notepad++，Linux 和 Mac 不做约束
6.
### 校稿标准化
1.
### 项目约定及建议
1. 建议大家每天抽出一小时或者每周抽出三小时（或更多），不要把工作留到最后，时间会很被动
2. 先把 lfs 8.0 翻译完，然后是 lfs 8.0 systemd 版，暂时不考虑 blfs
3. 署名默认是署我们各自的本名和 github 地址，希望留ID 或其他网址可以单独标注
4. 保持沟通，每天至少 check 一次邮件和微信
5. 沟通形式，以邮件（单向）和 github issues（public） 为正式，微信为辅助即时通信

## 翻译作品
翻译作品会放在[GitBook](https://www.gitbook.com/book/linuxstory/linux-from-scratch-8-0-book/)上，欢迎阅读！（未发布）

## 翻译流程
### 初始化
1. 首先fork项目
2. 把fork过去的项目clone到本地
3. 命令行下运行 `git checkout -b dev` 创建一个新分支
4. 运行 `git remote add upstream https://github.com/LinuxStory/lfs-8.0-Chinese.git` 添加远端库
5. 运行 `git remote update`更新
6. 运行 `git fetch upstream master` 拉取更新到本地
7. 运行 `git rebase upstream/master` 将更新合并到你的分支

初始化只需要做一遍，之后请在dev分支进行修改。

如果修改过程中项目有更新，请重复5、6、7步。

### 校审流程 (TBD)
1. 保证在dev分支中
2. 打开README.md，在翻译进度后加上你自己的github名
	> 1\. 序言! [@翻译人][@校审人]
3. 本地提交修改，写明提交信息
4. push到你fork的项目中，然后登录GitHub
5. 在你fork的项目的首页可以看到一个 `pull request` 按钮，点击它，填写说明信息，然后提交即可
	> 为了不重复工作，请等待我们确认了你的pull request(即你的名字出现在项目中时)，再进行翻译校审工作
6. 进行翻译校审，重复3-5步提交翻译校审的作品


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
        8. Making the LFS System Bootable
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

## 关于版权
根据原著作者的要求，翻译成果属于公有领域(CC0)，翻译参与人员及原著作者享有署名权，署名顺序将按加入项目的顺序排列。
