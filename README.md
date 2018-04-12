GogyGit 是我在2010年底写的一本书《Git权威指南》的代号，五年的时间过去了，Git走进了 2.x 版本的时代。
短短几年 Git 爆发式的发展已经让这本书显得过时了。

* GitHub 引领了社区式编程的潮流，成为开源社区的代名词。我曾经应邀写了一个分析 GitHub 的电子书 [《GotGitHub》](http://www.worldhello.net/gotgithub/)，
  但是很难跟上 GitHub 的变化的节奏。

* Gitlab 开源项目诞生于 2011 年，从模仿 GitHub，到被别人拿来照搬，让各种社交式编程社区在中国四处开花。

* Gerrit 和 Gitlab 是公司构建企业内部 Git 仓库托管平台的主要选择，如何构建高可用、可扩展的平台成为很多大公司探索的课题。

* Git 曾经一度遇到外热内冷（外部开源社区热，企业内部遇冷）的情况。在2011到2013年我的主要客户还是使用 SVN，甚至我的 80% 时间用在
  某些企业内部 SVN 平台的定制开发上。不过最近两年又几乎掉了一个个儿。但是在企业中推广 Git 还是很有挑战，一是 Windows 平台上的工具体验不佳，
  再一个是大的 Git 仓库（10GB以上）导致的用户体验差。业界出现了一些解决方案，例如 Git-LFS，在2015年底，我和我的小伙伴们为企业
  内部的 Git 平台加入了 Git-LFS 功能。我也在思考和尝试更好的方案。

* Git 进入 2.x 之后，大的功能上的改变很少，不过小的改变很多，如果照着《Git权威指南》照搬，很多地方会遇到困难。

* 写书之前，我给 Git 只贡献了一两个提交，而这几年，我向Git社区贡献了近两百个提交，其中有一些是有点技术含量的新功能、Bugfix，
  也有相当多的中文本地化。2012年我成为 Git 社区本地化的负责人，关于Git社区的工作流程理解得也更为透彻。

早在三年前，出版社又开始和我约稿，包括热心网友的询问，我一直以 Git 2.0 尚未发布为挡箭牌。但是真的等到 Git 2.0 发布，
我发现再也找不到大块儿的空余时间来专心写作了。这也就是为什么这本书现在已经很难在正规渠道买到了，那些拿到我亲笔签名的亲们，
你们赚到了。 ;)

2015年底，在为华为做咨询顾问一年多之后，我决定接受新的挑战，加入[华为公司](http://www.huawei.com/)，成为这个拥有着最大的开发者群体的世界级公司的一员。
如何有效地在大公司内进行过知识的传递也是一个课题，我决定将这本书的书稿开源，惠及更多的开发者。

书稿由 reStructuredText 格式书写，要想在本地编译和浏览，需要安装相关工具链。我已经将相关工具链做成 Docker 镜像，
使用方法参见 [jiangxin/docker-gotgit](https://github.com/jiangxin/docker-gotgit) 项目。
