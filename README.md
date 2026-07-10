# Wealth Compliance Dossier 中国大陆直连静态版

[![使用 EdgeOne Pages 部署](https://cdnstatic.tencentcs.com/edgeone/pages/deploy.svg)](https://edgeone.ai/pages/new?repository-url=https%3A%2F%2Fgithub.com%2Fjiguang121%2Fwealth-compliance-cn&project-name=wealth-compliance-cn&output-directory=.)

这是一个不依赖数据库、服务器端框架或第三方字体的单页静态官网，目标是优先保证中国大陆网络可以直接访问。

## 文件

- `index.html`：官网首页及本地诊断信息生成器。
- `404.html`：静态 404 页面。
- `robots.txt`：允许公开搜索引擎抓取。

## 部署优先级

1. 腾讯 EdgeOne Pages 免费默认域名，用于第一轮国内直连验证。
2. 如果默认域名在目标地区不稳定，再迁移到中国大陆对象存储或轻量服务器；绑定大陆节点的自有域名通常需要 ICP 备案。

## 诊断功能

当前版本不会上传或保存客户数据。表单只在浏览器中生成一段非敏感诊断信息并复制到剪贴板，客户可回到来源平台私信发送。这样可以在没有后端的情况下先保证官网可用。
