

## 准备工作
* 安装 angular 环境
* 安装 ng-zorro 依赖
# 项目资源


`
ng new ng-deerway --style less
`

`
cd ng-deerway
`
### 初始化配置
`
ng add ng-zorro-antd
`
### 安装组件   
`
npm install ng-zorro-antd --save
`
## 运行

`ng s -c [environment] --port [port]`


## 快捷指令

快速生成模块

`
ng g m [保存位置]/modelName
`

快速生成组件

`
ng g c [保存位置]/componentName
`

快速生产服务

`
ng g s [保存位置]/serviceName
`

快速生产管道

`
ng g pipe [保存位置]/pipeName
`

## 项目引用

地图：[maps](http://lbsyun.baidu.com/)

图表：[echarts](http://echarts.baidu.com/index.html)

用户认证：[@delon/auth](https://ng-alain.com/auth/getting-started)

项目框架：[ng-zorro](https://ng.ant.design/version/1.8.x/)

## 项目结构

> * core ng-zorro组件二次封装 通用服务、管道以及通用验证
> * layout   通用模版
> * routes   项目主体内容
> * shared   导入导出项目公用的引用
> * styles   通用样式
> * assets   静态资源（图片与图标）

## ng-zorro组件二次封装(app/shared/meta)
> * 基础表格组件 dw-table
> * 通用时间组件 dw-date-picker
> * 通用搜索组件 dw-search
> * 信息模态框 dw-info-model
> * 分页组件 dw-pagination
> * 动态表格组件 dw-table-dynamic

## 部署

#### 1、打包
`
ng build --prod
`
#### 2、配置WEB服务服务器
[nginx](http://www.nginx.cn/doc/)

#### 3、推送资源

`
scp -r  打包后文件路径 root@服务器IP地址：/root/www
`
#### 4、域名解析，发布完成


