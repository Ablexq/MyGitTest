
拉取(Pull)会从远程取得最新版本然后合并（Merge）到本地库

获取(Fetch)则会从远程取得最新版本，并不会合并（Merge）到本地库

可以说 拉取（Pull）=获取（Fetch）+合并（Merge）

从安全角度来说，Fetch更安全，因为我们可以先Fetch新版本，然后进行差异比较后，再选择性的 Merge。

这也是推荐做法，即先Fetch到一个本地副本分支，然后将该副本分支和本地版本比较，合并后，再提交到远程主机。


Git教程经典
[.net 面向对象程序设计进阶] (26) 团队开发利器（五）分布式版本控制系统Git——图形化Git客户端工具TortoiseGit
https://www.cnblogs.com/yubinfeng/p/5183034.html


[.net 面向对象程序设计进阶] (24) 团队开发利器（三）使用SVN多分支并行开发(下)
https://www.cnblogs.com/yubinfeng/p/5177994.html
https://www.cnblogs.com/yubinfeng/p/5180465.html







