# Video_Server

## 一、api 设计

* 用URL风格设计（URL：统一资源定位符）
* 通过不同的METHOD（GET, POST, PUT, DELETE）区分对资源的CRUD
* 返回码需要符合HTTP资源描述的规定

handler -> validation{1.request, 2.user} -> business logic -> reponse



## 二、stream

* 静态视频，非RTMP
* 独立的服务，可独立部署
* 同一的api格式

## 1.token bucket

## 三、scheduler

一般负责异步任务

### 1.runner

### 2.task

### 3.timer

timer

setup

start{trigger->task->runner}





## 四、前端模板引擎

* 模板引擎是江html解析和元素预置替换生成最终页面的工具
* 两种模板：text/template和html/template
* 采用动态生成的模式





