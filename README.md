
# QUANTAXIS 量化金融策略框架

Quantitative Financial FrameWork

从数据爬取-清洗存储-分析回测-可视化-交易复盘的本地一站式解决方案

-------------------------------------------------------------

![pypidownloads](https://img.shields.io/pypi/dm/quantaxis.svg)
![pypidownloads](https://img.shields.io/pypi/dw/quantaxis.svg)
![pypidownloads](https://img.shields.io/pypi/dd/quantaxis.svg)



[![Github workers](https://img.shields.io/github/watchers/quantaxis/quantaxis.svg?style=social&label=Watchers&)](https://github.com/quantaxis/quantaxis/watchers)
[![GitHub stars](https://img.shields.io/github/stars/quantaxis/quantaxis.svg?style=social&label=Star&)](https://github.com/quantaxis/quantaxis/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/quantaxis/quantaxis.svg?style=social&label=Fork&)](https://github.com/quantaxis/quantaxis/fork)


> ENGLISH DOCUMENTS PLEASE CLICK [THIS](README_ENG.md)

[点击右上角Star和Watch来跟踪项目进展! 点击Fork来创建属于你的QUANTAXIS!]


![main_1](http://pic.yutiansut.com/Main_1.gif)


<svg  width="140" height="170" id="图层_1" data-name="图层 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 467.88 578.66"><defs><style>.cls-1{fill:#bcbcbc;}.cls-2{fill:#3f3f3f;}.cls-3{fill:#828282;}.cls-4{fill:#494949;}.cls-5{fill:none;stroke:#fff;stroke-miterlimit:10;stroke-width:0.5px;}.cls-6{font-size:30px;font-family:ErasITC-Light, Eras Light ITC;}.cls-7{font-size:72px;fill:#666;font-family:ErasITC-Medium, Eras Medium ITC;}</style></defs><title>QUANTAXIS_LOGO</title><polygon class="cls-1" points="233.96 202.45 272.88 135.05 311.81 202.45 233.96 202.45"/><polygon class="cls-1" points="117.17 269.85 78.3 202.45 156.1 202.45 117.17 269.85"/><polygon class="cls-1" points="0.43 337.25 78.25 337.25 39.35 404.65 0.43 337.25"/><polygon class="cls-2" points="389.63 337.25 428.55 404.65 350.7 404.65 389.63 337.25"/><polygon class="cls-2" points="389.63 337.25 350.7 404.65 311.81 337.25 389.63 337.25"/><polygon class="cls-1" points="233.96 67.65 272.88 135.05 195.06 135.05 195.04 135.05 195.04 135 233.92 67.65 233.96 67.65"/><polygon class="cls-3" points="350.7 269.85 389.63 337.25 311.81 337.25 350.7 269.85"/><polygon class="cls-3" points="350.7 269.85 389.63 202.45 428.55 269.85 350.7 269.85"/><polygon class="cls-2" points="311.81 337.25 272.88 404.65 272.84 404.65 233.96 337.25 311.81 337.25"/><polygon class="cls-3" points="311.78 67.65 233.96 67.65 233.96 67.6 272.84 0.25 272.88 0.25 311.78 67.65"/><polygon class="cls-3" points="389.63 202.45 350.7 269.85 311.81 202.45 389.63 202.45"/><polygon class="cls-3" points="272.88 269.85 233.96 337.25 195.04 269.85 272.88 269.85"/><polygon class="cls-1" points="272.88 269.85 311.81 202.45 350.7 269.85 272.88 269.85"/><polygon class="cls-2" points="233.96 202.45 195.04 269.85 156.1 202.45 233.96 202.45"/><polygon class="cls-1" points="156.1 67.65 156.14 67.65 195.04 135 195.04 135.05 117.22 135.05 117.22 135 156.1 67.65"/><polygon class="cls-3" points="350.7 135.05 311.81 202.45 272.88 135.05 350.7 135.05"/><polygon class="cls-2" points="156.1 337.25 195.04 404.65 117.22 404.65 156.1 337.25"/><polygon class="cls-2" points="272.88 404.65 311.81 337.25 350.7 404.65 272.88 404.65"/><polygon class="cls-2" points="233.96 337.25 195.04 404.65 156.1 337.25 233.96 337.25"/><polygon class="cls-1" points="272.88 269.85 233.96 202.45 311.81 202.45 272.88 269.85"/><polygon class="cls-3" points="272.88 135.05 311.78 67.65 311.81 67.65 350.7 135.05 272.88 135.05"/><polygon class="cls-3" points="311.81 337.25 272.88 269.85 350.7 269.85 311.81 337.25"/><polygon class="cls-2" points="156.1 337.25 78.3 337.25 117.17 269.85 156.1 337.25"/><polygon class="cls-1" points="233.92 67.65 195.04 135 156.14 67.65 233.92 67.65"/><polygon class="cls-1" points="78.25 337.25 39.35 269.85 117.17 269.85 78.3 337.25 78.25 337.25"/><polygon class="cls-1" points="233.96 67.6 233.96 67.65 233.92 67.65 156.14 67.65 156.1 67.6 195.04 0.25 195.06 0.25 233.96 67.6"/><polygon class="cls-3" points="350.7 269.85 428.55 269.85 389.63 337.25 350.7 269.85"/><polygon class="cls-4" points="156.87 336.92 173.71 308.31 220.25 337.09 156.87 336.92"/><polygon class="cls-3" points="389.63 337.25 428.55 269.85 467.45 337.25 389.63 337.25"/><polygon class="cls-3" points="233.96 67.65 311.78 67.65 272.88 135.05 233.96 67.65"/><polygon class="cls-1" points="117.17 269.85 39.35 269.85 78.3 202.45 117.17 269.85"/><polygon class="cls-1" points="156.1 202.45 78.3 202.45 117.17 135.05 117.22 135.05 156.1 202.4 156.1 202.45"/><polygon class="cls-2" points="39.35 404.65 78.25 337.25 78.3 337.25 117.17 404.65 39.35 404.65"/><polygon class="cls-1" points="272.88 135.05 233.96 202.45 195.06 135.05 272.88 135.05"/><polygon class="cls-2" points="156.1 202.45 195.04 269.85 117.17 269.85 156.1 202.45"/><path class="cls-3" d="M409.36,451.67H331.5l38.94-67.4Zm-13.71-.16-46.54-28.78-16.84,28.62Z" transform="translate(-175.4 -114.42)"/><polygon class="cls-3" points="350.7 135.05 389.63 202.45 311.81 202.45 350.7 135.05"/><polygon class="cls-2" points="428.55 404.65 389.63 337.25 467.45 337.25 428.55 404.65"/><polygon class="cls-3" points="311.81 337.25 233.96 337.25 272.88 269.85 311.81 337.25"/><polygon class="cls-2" points="195.04 135.05 195.06 135.05 233.96 202.45 156.1 202.45 156.1 202.4 195.04 135.05"/><polygon class="cls-1" points="117.22 135.05 195.04 135.05 156.1 202.4 117.22 135.05"/><polygon class="cls-3" points="272.84 0.25 233.96 67.6 195.06 0.25 272.84 0.25"/><polygon class="cls-1" points="39.35 269.85 78.25 337.25 0.43 337.25 39.35 269.85"/><polygon class="cls-2" points="117.17 404.65 78.3 337.25 156.1 337.25 117.22 404.65 117.17 404.65"/><polygon class="cls-2" points="233.96 337.25 272.84 404.65 195.04 404.65 233.96 337.25"/><polygon class="cls-2" points="195.04 269.85 156.1 337.25 117.17 269.85 195.04 269.85"/><line class="cls-5" x1="428.55" y1="404.65" x2="350.7" y2="404.65"/><line class="cls-5" x1="350.7" y1="404.65" x2="272.88" y2="404.65"/><line class="cls-5" x1="117.17" y1="404.65" x2="39.35" y2="404.65"/><line class="cls-5" x1="272.84" y1="404.65" x2="195.04" y2="404.65"/><line class="cls-5" x1="195.04" y1="404.65" x2="117.22" y2="404.65"/><polyline class="cls-5" points="233.96 337.25 195.04 404.65 156.1 337.25"/><polyline class="cls-5" points="311.81 337.25 272.88 404.65 272.84 404.65 233.96 337.25"/><polyline class="cls-5" points="156.1 337.25 117.22 404.65 117.17 404.65 78.3 337.25"/><line class="cls-5" x1="389.63" y1="202.45" x2="428.55" y2="269.85"/><line class="cls-5" x1="156.1" y1="337.25" x2="78.3" y2="337.25"/><line class="cls-5" x1="233.96" y1="337.25" x2="156.1" y2="337.25"/><line class="cls-5" x1="428.55" y1="269.85" x2="467.45" y2="337.25"/><polyline class="cls-5" points="195.04 269.85 156.1 337.25 117.17 269.85"/><line class="cls-5" x1="389.63" y1="202.45" x2="350.7" y2="269.85"/><line class="cls-5" x1="195.04" y1="269.85" x2="117.17" y2="269.85"/><line class="cls-5" x1="311.81" y1="337.25" x2="233.96" y2="337.25"/><line class="cls-5" x1="311.81" y1="337.25" x2="272.88" y2="269.85"/><polyline class="cls-5" points="311.81 202.45 350.7 269.85 272.88 269.85"/><polygon class="cls-5" points="428.55 404.65 389.63 337.25 467.45 337.25 428.55 404.65"/><polyline class="cls-5" points="78.25 337.25 39.35 404.65 0.43 337.25"/><line class="cls-5" x1="39.35" y1="269.85" x2="78.3" y2="202.45"/><polyline class="cls-5" points="350.7 269.85 428.55 269.85 389.63 337.25"/><polyline class="cls-5" points="311.81 337.25 350.7 269.85 389.63 337.25"/><polygon class="cls-5" points="350.7 404.65 311.81 337.25 389.63 337.25 350.7 404.65"/><polyline class="cls-5" points="78.25 337.25 0.43 337.25 39.35 269.85"/><polygon class="cls-5" points="78.3 337.25 78.25 337.25 39.35 269.85 117.17 269.85 78.3 337.25"/><polygon class="cls-5" points="233.96 337.25 195.04 269.85 272.88 269.85 233.96 337.25"/><polyline class="cls-5" points="311.78 67.65 311.81 67.65 350.7 135.05"/><polyline class="cls-5" points="350.7 135.05 389.63 202.45 311.81 202.45"/><polyline class="cls-5" points="311.81 202.45 272.88 269.85 233.96 202.45"/><polyline class="cls-5" points="233.96 202.45 195.04 269.85 156.1 202.45"/><polyline class="cls-5" points="272.88 135.05 350.7 135.05 311.81 202.45"/><polyline class="cls-5" points="117.22 135.05 117.22 135 156.1 67.65 156.14 67.65"/><polyline class="cls-5" points="78.3 202.45 117.17 135.05 117.22 135.05"/><polygon class="cls-5" points="117.17 269.85 78.3 202.45 156.1 202.45 117.17 269.85"/><polygon class="cls-5" points="311.81 202.45 233.96 202.45 272.88 135.05 311.81 202.45"/><line class="cls-5" x1="272.88" y1="135.05" x2="195.06" y2="135.05"/><line class="cls-5" x1="195.04" y1="135.05" x2="195.04" y2="135"/><polyline class="cls-5" points="195.04 135.05 195.06 135.05 233.96 202.45 156.1 202.45 156.1 202.4"/><polygon class="cls-5" points="195.04 135.05 156.1 202.4 117.22 135.05 195.04 135.05"/><polyline class="cls-5" points="233.92 67.65 195.04 135 156.14 67.65"/><line class="cls-5" x1="195.06" y1="0.25" x2="272.84" y2="0.25"/><polyline class="cls-5" points="233.96 67.6 272.84 0.25 272.88 0.25 311.78 67.65"/><polygon class="cls-5" points="272.88 135.05 233.96 67.65 311.78 67.65 272.88 135.05"/><polygon class="cls-5" points="233.92 67.65 156.14 67.65 156.1 67.6 195.04 0.25 195.06 0.25 233.96 67.6 233.96 67.65 233.92 67.65"/><text class="cls-6" transform="translate(24.62 571.16)">Quantitative Financial Framework</text><text class="cls-7" transform="translate(34.94 515.16)">QUANTAXIS</text></svg>


![presentbyyutiansut](http://pic.yutiansut.com/yutiansut-logo.png)

![version](https://img.shields.io/pypi/v/quantaxis.svg)
![build](https://travis-ci.org/QUANTAXIS/QUANTAXIS.svg?branch=master)
[![Codefresh build status]( https://g.codefresh.io/api/badges/build?repoOwner=yutiansut&repoName=QUANTAXIS&branch=master&pipelineName=QUANTAXIS&accountName=yutiansut_marketplace&type=cf-1)]( https://g.codefresh.io/repositories/yutiansut/QUANTAXIS/builds?filter=trigger:build;branch:master;service:5a30c1026e9d6c0001c5143b~QUANTAXIS)
[![BCH compliance](https://bettercodehub.com/edge/badge/QUANTAXIS/QUANTAXIS?branch=master)](https://bettercodehub.com/)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d8504e4af33747bb8117579212425af9)](https://www.codacy.com/app/yutiansut/QUANTAXIS?utm_source=github.com&utm_medium=referral&utm_content=yutiansut/QUANTAXIS&utm_campaign=badger)
[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/yutiansut/quantaxis)
![QAS](https://img.shields.io/badge/QAS-%200.0.8-brown.svg)
![python](https://img.shields.io/badge/python-%203.7/3.6/3.5/win/ubuntu-darkgrey.svg)
![Npm](https://img.shields.io/badge/Npm-%200.4.0-yellow.svg)
![author](https://img.shields.io/badge/Powered%20by-%20%20yutiansut-red.svg)
![license](https://img.shields.io/badge/License-%20MIT-brightgreen.svg)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FQUANTAXIS%2FQUANTAXIS.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FQUANTAXIS%2FQUANTAXIS?ref=badge_shield)
[![Waffle.io - Issues in progress](https://badge.waffle.io/yutiansut/QUANTAXIS.png?label=in%20progress&title=In%20Progress)](http://waffle.io/yutiansut/QUANTAXIS)
[![Reviewed by Hound](https://img.shields.io/badge/Reviewed_by-Hound-8E64B0.svg)](https://houndci.com)



> 欢迎加群讨论: 563280067 [群链接](https://jq.qq.com/?_wv=1027&k=4CEKGzn) 

> QUANTAXIS 开发群: 773602202 (如果想要贡献代码 请加这个群 需要备注你的GITHUB ID)

> 欢迎关注公众号: ![公众号](http://pic.yutiansut.com/qrcode_for_gh_bbb47e0550f7_258%20%281%29.jpg)

> 许多问题 可以在 [GITHUB ISSUE](https://github.com/QUANTAXIS/QUANTAXIS/issues)中找到, 你可以提出新的issue

QUANTAXIS量化金融策略框架,是一个面向中小型策略团队的量化分析解决方案. 我们通过高度解耦的模块化以及标准化协议,可以快速的实现面向场景的定制化解决方案.QUANTAXIS是一个渐进式的开放式框架,你可以根据自己的需要,引入自己的数据,分析方案,可视化过程等,也可以通过RESTful接口,快速实现多人局域网/广域网内的协作.

![qa2018](http://pic.yutiansut.com/qa2018.png)


<!-- TOC -->

- [QUANTAXIS 量化金融策略框架](#quantaxis-量化金融策略框架)
    - [1. 功能](#1-功能)
        - [1.1 行情服务](#11-行情服务)
            - [1.1.1 股票/期货/期权/美股/外汇/宏观的历史/实时行情(日线/分钟线/tick/实时五档)服务](#111-股票期货期权美股外汇宏观的历史实时行情日线分钟线tick实时五档服务)
            - [1.1.2 财务/基本面/宏观数据](#112-财务基本面宏观数据)
            - [1.1.3 自定义数据源的数据](#113-自定义数据源的数据)
        - [1.2 数据运维服务](#12-数据运维服务)
        - [1.3 分析服务](#13-分析服务)
            - [1.3.1 专门为A股股票数据适配的数据结构](#131-专门为a股股票数据适配的数据结构)
            - [1.3.2 精心为A股指标计算适配的指标类](#132-精心为a股指标计算适配的指标类)
        - [1.4 可扩展事件驱动框架](#14-可扩展事件驱动框架)
        - [1.5 回测服务](#15-回测服务)
            - [1.5.1 股票/日内t0/ 的日线/分钟线级别回测](#151-股票日内t0-的日线分钟线级别回测)
        - [1.6 实盘](#16-实盘)
            - [1.6.1 股票(实盘易)](#161-股票实盘易)
            - [1.6.2 期货(python3 CTP win/mac/linux)](#162-期货python3-ctp-winmaclinux)
        - [1.7 网站HTTP服务](#17-网站http服务)
            - [1.7.1 网站后台标准化接口](#171-网站后台标准化接口)
    - [2. 文档](#2-文档)
    - [3. 安装和部署](#3-安装和部署)
        - [3.0 安装说明](#30-安装说明)
        - [3.1 小白式上手](#31-小白式上手)
        - [3.2 部署式安装](#32-部署式安装)
        - [3.3  本地代码 开发式安装](#33--本地代码-开发式安装)
        - [3.4 代码提交式安装](#34-代码提交式安装)
    - [4. 更新](#4-更新)
    - [5. Docker](#5-docker)
    - [6. 使用说明](#6-使用说明)
    - [7. Jupyter示例](#7-jupyter示例)
    - [8. 开发计划](#8-开发计划)
    - [9. 常见问题FAQ](#9-常见问题faq)
    - [10. 项目捐赠](#10-项目捐赠)
    - [11. 回测Webkit插件概览](#11-回测webkit插件概览)
    - [12. QUANTAXIS 标准化协议和未来协议](#12-quantaxis-标准化协议和未来协议)
    - [13. 电脑配置推荐](#13-电脑配置推荐)
    - [License](#license)

<!-- /TOC -->


##  1. 功能
======

![](http://pic.yutiansut.com/QUANTAXIS.png)

已经实现：

### 1.1 行情服务

#### 1.1.1 股票/期货/期权/美股/外汇/宏观的历史/实时行情(日线/分钟线/tick/实时五档)服务

参见 [QUANTAXIS的数据获取指南](Documents/DataFetch.md)

#### 1.1.2 财务/基本面/宏观数据

参见 [QUANTAXIS财务指标](Documents/financial_means.md)

#### 1.1.3 自定义数据源的数据

参见 [QUANTAXIS WEB 爬虫](Documents/crawler.md)

### 1.2 数据运维服务

一键更新 参见[WINDOWS数据自动更新](config/windows_autojob_updatedata.md)


### 1.3 分析服务

#### 1.3.1 专门为A股股票数据适配的数据结构

参见 [QUANTAXIS的数据结构](Documents/DataStruct.md)

参见 [QUANTAXIS行情研究](Documents/analysis.md)

#### 1.3.2 精心为A股指标计算适配的指标类

参见 [QUANTAXIS指标系统](Documents/indicators.md)


### 1.4 可扩展事件驱动框架

参见 [QUANTAXIS事件框架](Documents/about_event.md)


### 1.5 回测服务

#### 1.5.1 股票/日内t0/ 的日线/分钟线级别回测

参见 [QUANTAXIS的账户结构](Documents/account.md)

参见 [QUANTAXIS 账户风险分析插件指南](Documents/risk.md)

参见 [QUANTAXIS回测委托成交结算的说明](Documents/orderanddeal.md)

参见 [QUANTAXIS回测分析](Documents/backtestanalysis.md)

参见 [常见策略整理](Documents/strategy.md)

参见 [简单策略回测详解](Documents/QUANTAXIS回测分析全过程讲解.md)

参见 [T0交易的账户详解](Documents/TEST_ORDER_BACKTEST_T0.md)

### 1.6 实盘

#### 1.6.1 股票(实盘易)

实盘易插件 参见[实盘易](http://www.iguuu.com/e?x=18839)

实盘易安装注意 参见[安装注意](shipane_install_memo.md)

#### 1.6.2 期货(python3 CTP win/mac/linux)

1. CTP 的websocket交易 :  simnow demo:  ws://www.yutiansut.com:7988
2. CTP 的海风broker魔改封装:  [QA_AtBroker](https://github.com/QUANTAXIS/QA_AtBroker)


关于websocket交易(可能存在一些不确定的bug 因此暂时不开放):

- 目前仅提供demo/ 模拟盘接入
- 具体需要私聊我 yutiansut@qq.com


### 1.7 网站HTTP服务(目前已经独立为 QUANTAXIS_WEBSERVICE)

#### 1.7.1 网站后台标准化接口

参见 [QUANTAXIS WEB API说明](Documents/backendapi.md)



![](http://pic.yutiansut.com/framework.png)


- [QUANTAXIS 2018开发计划表](job_list.md)


##  2. 文档

文档参见: [book](http://book.yutiansut.com)

下载文档手册(实时更新)

[PDF](https://www.gitbook.com/download/pdf/book/quantaxis/quantaxis) | [MOBI](https://www.gitbook.com/download/mobi/book/quantaxis/quantaxis) | [EPUB](https://www.gitbook.com/download/epub/book/quantaxis/quantaxis)

##  3. 安装和部署

### 3.0 安装说明
参见 [安装说明](Documents/install.md)

### 3.1 小白式上手


参见 [小白上手教程WIN](Documents/install_for_new_to_coding.md)

### 3.2 部署式安装


```
pip install quantaxis -U
```
### 3.3  本地代码 开发式安装

本地安装
```
git clone https://github.com/quantaxis/quantaxis --depth 1

cd quantaxis

pip install -e .
```
### 3.4 代码提交式安装

代码提交式安装 代码提交参见  [代码提交](https://github.com/QUANTAXIS/QUANTAXIS/blob/master/Documents/about_pr.md)

- fork QUANTAXIS 到你的github账户

```
git clone https://github.com/你的账户名/quantaxis
```

##  4. 更新
参见 [更新说明](Documents/update.md)

##  5. Docker
参见 [Docker](Documents/docker.md)
##  6. 使用说明
参见 


* [QUANTAXIS的使用示例](https://github.com/quantaxis/QADemo)


##  7. Jupyter示例
参见 [Jupyter示例](jupyterexample)


##  8. 开发计划
参见 [开发计划](job_list.md)

##  9. 常见问题FAQ

参见 [FAQ](Documents/FAQ.md)

##  10. 项目捐赠

写代码不易...请作者喝杯咖啡呗?


![](http://pic.yutiansut.com/alipay.png)

(PS: 支付的时候 请带上你的名字/昵称呀 会维护一个赞助列表~ )

[捐赠列表](CONTRIBUTING.md)



##  11. QUANTAXIS 桌面级产品(全平台 WIN/MAC/LINUX)


参见 [QUANTAXIS/QADESKTOP](https://github.com/quantaxis/qadesktop)

![](http://pic.yutiansut.com/qad1.png)
![](http://pic.yutiansut.com/qad2.png)
![](http://pic.yutiansut.com/qad3.png)
![](http://pic.yutiansut.com/qad4.png)
![](http://pic.yutiansut.com/qad5.png)
![](http://pic.yutiansut.com/qad6.png)
![](http://pic.yutiansut.com/qad8.png)


##  12. QUANTAXIS 标准化协议和未来协议


QUANTAXIS-Stardand-Protocol 版本号0.0.8

详情参见  [QUANATXISProtocol](Documents/readme.md)


##  13. 电脑配置推荐

推荐配置:
6代以上CPU+ 16/32GB DDR3/DDR4内存+ 256GB以上SSD硬盘

最低配置:
支持X64位的CPU

因为在存储本地数据的时候,需要存储超过2GB的本地数据,而32位的MONGODB最高只支持2GB左右的数据存储,因此最少需要一个X64位的CPU

如果SSD资源够用,尽量将数据存储在SSD中,增加```wiretiger```写盘的速度

如果是阿里云/腾讯云的服务器,请在最初的时候 选择64位的操作系统

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FQUANTAXIS%2FQUANTAXIS.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FQUANTAXIS%2FQUANTAXIS?ref=badge_large) [![Join the chat at https://gitter.im/QUANTAXIS_tauruswang/Lobby](https://badges.gitter.im/QUANTAXIS_tauruswang/Lobby.svg)](https://gitter.im/QUANTAXIS_tauruswang/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
