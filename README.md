# GIT 最佳实践
---------

![GIT 最佳实践](git-think.png)



### TODO
--------
> - 如何正确的使用`github_changelog_generator`来创建关于里程碑的CHANGELOG


github_changelog_generator AtwindYu/GITBestPractices --release-branch dev --include-labels enhancement,bug,question


github_changelog_generator AtwindYu/GITBestPractices -v1.0.0



https://api.github.com/repos/AtwindYu/GITBestPractices/issues?milestone=1.0.0&state=closed



获取milestones，注意参数的 内容竟然不包括那个v  v1.0.0 要写成1.0.0：           
https://api.github.com/repos/AtwindYu/GITBestPractices/milestones/1.0.0