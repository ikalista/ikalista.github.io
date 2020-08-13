---
layout: post
title: 开始学习操作系统了
---

首先使用install67.iso创建虚拟机，选择其他系统
所有设置选择default（enter到底）
SHA256选择不验证
进入系统

<br>
w: 查看用户列表

<br>
pkg-get <package name>:   安装软件
  
<br>
chmod 777 testfile.c：     给权限

<br>
gcc testfile.c -o testfile:   编译

<br>
./testfile:     运行

<br>
apt-get install build-essential： 安装build-essential

<br>
sudo apt-get update：  更新apt-get

<h1> SVN操作 </h1>
<h2>svn指令</h2>
<p>svn commit 上载，更新服务器文件</p>
<p>(openbsd操作)svn commit -m "message" filename 上载固定文件，更新服务器文件</p>
<p>svn update 下载，更新本地文件</p>
