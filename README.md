<p align="center">
  <img height="100px" src="./zblog.jpeg" />
</p>

# [ZBlog](https://github.com/zblogcn/zblogphp)

Z-BlogPHP 是由 Z-Blog 社区提供的博客程序，一直致力于给国内用户提供优秀的博客写作体验。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署


[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-ZBlog&branch=master)

### 配置

- `ZC_DB_HOST`：数据库地址
- `ZC_DB_USER`：数据库用户名
- `ZC_DB_PWDD`：数据库密码
- `ZC_DB_NAME`：数据库名
- `ZC_BLOG_USER`：管理后台用户名
- `ZC_BLOG_PWDD`：管理后台密码
- `BASE_URL`：网站url


### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
