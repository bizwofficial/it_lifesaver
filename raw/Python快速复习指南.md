# 信息技术快速复习指南

🔰本文经过 裨治文 认证

## 本指南正确食用方法

你好！这份指南可以帮你迅速复习高一信息技术的各种知识，从而在信息技术会考中取得好成绩。

以下人群适合马上开始阅读：

* 认真听过信息技术课的同学
* 已掌握Python基础知识的同学
* Python高手
* 有其它语言编程经验的同学

以下人群不适合阅读本指南：

* 完全没听过信息技术课的同学
* 完全不会任何编程语言同学

不适合人群建议在阅读本指南前进行以下活动：

* 上网搜索Python入门教程
* 仔细阅读信息技术课本

## 准备工作

> 提示：“准备工作”是你需要在电脑上进行的、为了与会考所用计算机保持一致的配置，这些配置无需在会考时进行。

### 1. 安装 Python

访问`https://www.python.org/downloads`或者直接[点击此处](https://www.python.org/downloads)访问Python官方下载页，并下载最新版本的Python。

> 提示：会考计算机使用的版本是Python 3.7，但是你仍然可以安装Python 3.8，因为会考测试的特性在Python 3.8中未被修改。

下载完成后安装，:warning:请注意安装时<strong>钩选“Add Python to PATH”</strong>，这一点非常重要！

> 提示：钩选Add Python to PATH让你能够很方便地打开Python和pip。

如果你之前已经安装过Python，按下<kbd>Windows</kbd>+<kbd>R</kbd>组合键，然后输入`python`并回车，如果打开了Python就一切正常；如果提示“Windows找不到文件'`python`'”，请从控制面板卸载Python，然后重新安装。

### 2. 安装会考需要的扩展包

会考需要使用一些第三方Python包，请按如下步骤进行安装：

1. 按下<kbd>Windows</kbd>+<kbd>R</kbd>组合键，输入`cmd`回车；

2. 在命令行窗口输入`pip install numpy matplotlib pandas xlrd -i https://pypi.tuna.tsinghua.edu.cn/simple`，回车，坐等安装完成。

   > 提示：如果提示`'pip'不是可执行文件`，请检查你的Python是否正确安装。

在python中输入`import numpy,matplotlib,pandas,xlrd`来查看是否安装成功：如果没有任何输出，说明安装成功；如果有错误提示，说明安装失败。