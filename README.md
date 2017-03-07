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
2. Milestone：3月6日  intial 项目（请大家 fork 本项目建立自己的 dev 分支）
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
1. 可参考  CLReq https://www.w3.org/TR/clreq
2. 简单约定：A)专有名词的大小写、连字符等请保持跟原名或注册商标一致；B)一般情况下使用中文全角标点，但是文件名，版本号等其中出现的符号用保持用原来英文半角符号。C）待补充
3. 对于不确定的专有名词翻译，请及时拿出来讨论，发github issue或者微信、邮件
4. 项目中使用到的术语、专业名词，请更新到术语表中 https://github.com/LinuxStory/StoryTranslation/blob/master/Dictionary.md 
5. 编辑器请统一使用 UTF-8 无BOM，Windows 下尽量使用 Notepad++，Linux 和 Mac 不做约束
6. 术语尽量保证和已翻译的一致，也可以查询[微软术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)

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

## 项目进度
1. 闻其详定期跟大家邮件和微信通报项目进度
2. 任何问题请第一时间通报

## 关于版权
根据原著作者的要求，翻译成果属于公有领域(CC0)，翻译参与人员及原著作者享有署名权，署名顺序将按加入项目的顺序排列。
