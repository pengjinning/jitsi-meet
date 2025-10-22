# jitsi 使用说明

```bash
# 开发文档 https://jitsi.github.io/handbook/docs/dev-guide/dev-guide-web-jitsi-meet
# 设置代理
export http_proxy=http://127.0.0.1:10818 && export https_proxy=http://127.0.0.1:10818
# 要求 "node": ">=22.0.0", "npm": ">=10.0.0"
nvm use 22.7.0
# 安装依赖
npm install
# To build the Jitsi Meet production application:
make
# For development:
make dev
# 访问
https://localhost:8080/
```
