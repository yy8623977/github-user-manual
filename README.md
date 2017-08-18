# github-user-manual

1. ## 概念
git
  工具，版本控制
github
  网站，社交平台，开源项目，远程仓库

2. ## 图解
svn与git区别
集成式
分布式
github作用

3. ## git工具
不同系统，方式不同
windows
官网下载
可视化
命令行(推荐)

4. ## 建立一个库
drag
git  clone  [url]
设置贡献者
name
email
git config --global  user.name
git config --global user.email
git config --list
   查看所有配置项

5. ## git的三个区
工作区
暂存区
  作为过渡层
  避免误操作
  保护工作区和版本区
  分支处理
版本区（库）

6. ## Git命令
git status
git add
  name
  .
git commit
  -m
  -a -m

对比
    git diff
    git diff --cached(--staged)
    git diff master
撤销
    git reset HEAD <file.name>
    git checkout -- <file.name>
    git commit --amend
删除
    git rm <file.name>
    git rm -f <file.name>
    git rm --cached <file.name>
恢复
    git checkout commit_id <file.name>
    git reset --hard commit_id
    HEAD^
    HEAD~<num>
    git reflog

7. ## 同步到远程仓库
git remote
-v
origin
git push origin master
多人协作解决冲突
  git fetch
    Git diff master origin/master
    Git merge  orgin/master
  git pull
  
 8. ## 开源项目协作
fork
pull request

9. ## Git分支
git branch
  -d
  --merged
  --no-merged
git checkout
  -b
git merge

10. ## github上的分支
git push 
github上直接创建

11. ## github上的标签
  git tag
  github上直接创建
 
 12. ## 创建组织
github上创建

13. ## 创建博客
github上创建
https://pages.github.com/
注意格式的正确性

14. ## 总结
如何深入？
技巧
资源
> http://git.oschina.net/progit/
> http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000








