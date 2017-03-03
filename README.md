# Linux From Scratch 8.0 in Chinese
lfs 8.0 中文版

## 联系/加入我们
- 邮箱：ls#linuxstory.org(将#替换为@，并在邮件title标注 lfs 8.0)
- QQ群：580714155

## 原著及早期翻译作品
### 原著
- 原著链接：http://www.linuxfromscratch.org/lfs/view/8.0/
- 原作：Gerard Beekmans 
- 原著版本：Revision 8.0, 28 February 2017

### 译著
- lfs 7.7 连接：https://linux.cn/lfs/LFS-BOOK-7.7-systemd/
- 译者：LCTT 团队
- 译著版本：Revision 7.7 systemd, 2015
- 最新 Revision 8.0 由 Linux Story 社区发起并组织翻译，成员包括：闻其详、陈毅钊、
- Linux Story 通告地址 ：https://linuxstory.org/linux-from-scratch-8-0-released/
- 本项目的经验及组织过程资产将保存在 https://pm.linuxstory.org
- 预发布地址：http://linuxstory.org/lfs/LFS-BOOK-8.0/

### 项目计划


## 翻译作品
翻译作品放在[GitBook](https://www.gitbook.com/book/linuxstory/linux-from-scratch-8-0-book/)上，欢迎阅读！

## 翻译校审流程
### 初始化
1. 首先fork项目
2. 把fork过去的项目clone到本地
3. 命令行下运行 `git checkout -b dev` 创建一个新分支
4. 运行 `git remote add upstream https://github.com/LinuxStory/Advanced-Bash-Scripting-Guide-in-Chinese.git` 添加远端库
5. 运行 `git remote update`更新
6. 运行 `git fetch upstream master` 拉取更新到本地
7. 运行 `git rebase upstream/master` 将更新合并到你的分支

初始化只需要做一遍，之后请在dev分支进行修改。

如果修改过程中项目有更新，请重复5、6、7步。

### 翻译校审流程
1. 保证在dev分支中
2. 打开README.md，在翻译进度后加上你自己的github名
	> 1\. Shell Programming! [@翻译人][@校审人]
3. 本地提交修改，写明提交信息
4. push到你fork的项目中，然后登录GitHub
5. 在你fork的项目的首页可以看到一个 `pull request` 按钮，点击它，填写说明信息，然后提交即可
	> 为了不重复工作，请等待我们确认了你的pull request(即你的名字出现在项目中时)，再进行翻译校审工作
6. 进行翻译校审，重复3-5步提交翻译校审的作品


> 新手可以参阅针对github小白的[《翻译流程详解》](https://github.com/LinuxStory/Advanced-Bash-Scripting-Guide-in-Chinese/wiki/%E7%BF%BB%E8%AF%91%E6%B5%81%E7%A8%8B%E8%AF%A6%E8%A7%A3),妹子写的呦～

## 翻译校审建议
1. 使用markdown进行翻译校审，文件名必须使用英文，单词之间请使用短横线“-”做连字符
2. 翻译校审后的文档请放到source文件夹下的对应章节中，然后pull request即可
3. 有任何问题欢迎随时发issue，并请参与翻译的同学保持邮箱畅通，每天最少检查一次邮件
4. 术语尽量保证和已翻译的一致，也可以查询[微软术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)
5. 请将翻译过程中用到的术语保存到[Linux Story术语词典](https://github.com/LinuxStory/StoryTranslation/blob/master/Dictionary.md)

## 关于版权
根据原著作者的要求，翻译成果属于公有领域(CC0)，翻译参与人员及原著作者享有署名权，署名顺序将按加入项目的顺序排列。
