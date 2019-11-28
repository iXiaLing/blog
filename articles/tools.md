---
layout: post
title: "tools"
date: 2019-11-27 20:41:24 +0800
categories: jekyll update
---

# tools

自己写的自动化任务的小工具。以及配置文件，在 tools 目录下面运行 ./install.sh 可以完成一键安装。

## pull.sh

---
### 功能

一个命令可以把所有仓库的更新拉到本地。

### 场景

上班后的第一件事情，你懂得。

### 演示

![运行效果]({{ site.baseurl }}/images/pull.gif)

### 安装

1. 将 pull.sh 下载到本地，并确保文件的位置关系如下：  

  x-dir    
   |    
   |-- repoA          // 这是 A 仓库的位置  
   |-- repoB          // 这是 B 仓库的位置   
   |-- ......    
   |-- repoN          // 这是 N 仓库的位置   
   |-- ......  
   |-- pull.sh        // 拉取所有仓库的更新    

2. 拉取更新的时候，请在 x-dir 目录下，运行下面的命令，来执行脚本  

  ```sh
  ./pull.sh 
  ```

## status.sh

---
### 功能

一个命令可以查看所有仓库的状态。

### 场景

下班前的第一件事情，你懂得。

### 演示

![运行效果]({{ site.baseurl }}/images/status.gif)

### 安装

1. 将 status.sh 下载到本地，并确保文件的位置关系如下：  

  x-dir    
   |    
   |-- repoA          // 这是 A 仓库的位置  
   |-- repoB          // 这是 B 仓库的位置   
   |-- ......    
   |-- repoN          // 这是 N 仓库的位置   
   |-- ......  
   |-- status.sh      // 查看所有仓库的状态    

2. 检查状态的时候，请在 x-dir 目录下，运行下面的命令，来执行脚本  

  ```sh
  ./status.sh 
  ```

