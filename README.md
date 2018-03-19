# 测试 rebase 是否可以将 develop 分支的配置文件合并过来


1. master 分支的配置文件为：
```
branch:master
```
正确配置！！

2. develop 分支的配置文件为：
```
branch:develop
```
正确配置！！

3. 在 master 分支执行
`git rebase develop`

4. master 分支配置文件变为

```
branch:develop
```
 错误！！！


