# super.js

## Badges 

<div align="center">

[![StyleCI](https://github.styleci.io/repos/152890558/shield?branch=master)](https://github.styleci.io/repos/152890558)
[![Build Status](https://travis-ci.org/whizjs/superjs.svg?branch=master)](https://travis-ci.org/whizjs/superjs)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](LICENSE)  

</div>

## Welcome to super.js 欢迎来到super.js
```
欢迎提交issue和PR！
Issues and Pull Requests are welcome
```

## Tech Stack 技术栈

 - vue.js 2
 - @vue/cli 3
 - vuex
 - vue-router
 - libraries:
    - axios
    - lodash
    - bootstrap-vue UI
    - validator
 - Cloud Services
    - SendGrid
    - StyleCI
    - Travis-CI
    - Netlify Lambda Functions
    - Netlify Identity
 - APIs consumed:
    - Google API
    - CNODE
    - Crypto Compare API

## Get Started 快速上手
 - 其实这个项目已经用了`netlify`，下面的步骤都自动运行和部署了。


 - ### Dependency Installation 安装依赖
    ```
    yarn install
    ```

 - ### Local development 本地运行
    ```
    yarn serve:app
    yarn serve:lambda
    ```

 - ### Go production 生产环境构建
    ```
    yarn build
    ```

 - ### Lints and fixes files 
    ```
    yarn lint
    ```
## Features 项目功能
### 本项目全面拥抱云计算，能使用第三方云服务的，都尽量使用第三方云服务

 - [x] 注册登录服务使用`Netlify Identity`服务
 - [x] 搜索YouTube视频
 - [x] API和API文档开启
 - [ ] 找工作信息汇聚
 - [ ] 比特币等加密币行情