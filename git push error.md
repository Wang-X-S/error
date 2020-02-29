# 关于GitHub的上传问题1

## git push 


* 第一次上传时用的外网传送失败
```
*82037@LAPTOP-F04MEID7 ~/Desktop/ceshi (master)
λ git push -u origin master
ssh: connect to host github.com port 22: Connection timed out
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.
```
* 第二次把网络切回来，传送成功
```
82037@LAPTOP-F04MEID7 ~/Desktop/ceshi (master)
λ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 432 bytes | 216.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To github.com:harrywangxs/blog-text-1.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```
1. 上午准备上传文件练手，但是出现我的本地上传地址是别人的frankfang不会配置，只能把软装重装
到现在也没有找到原因，找到后更新

2. 第二个问题下午上传时发现，原来是因为网络连接不稳定造成