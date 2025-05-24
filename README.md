# 部署
## Pages
<details>

- 下载[_worker.js](https://github.com/eaqx/edgetunnel/blob/main/_worker.js)文件 移入文件夹
- 进入Cloudflare的"Workers and Pages" 新建Pages项目 上传文件夹并部署
- 点击"设置" 进入"变量和机密" 设置PROXYIP和UUID
- 再次上传文件并部署使变量生效
- 访问 `https://example.pages.dev/example-uuid` 获取节点链接
  
</details>

## Workers
<details>

- 进入Cloudflare的"Workers and Pages" 新建Workers项目
- 复制[_worker.js](https://github.com/eaqx/edgetunnel/blob/main/_worker.js)内容
- 编辑Workers代码 将第一步中复制的文件内容替换掉原有的worker.js代码 点击"保存并部署"
- 点击"设置" 进入"变量和机密" 设置PROXYIP和UUID
- 访问 `https://example.pages.dev/example-uuid` 获取节点链接

</details>
  
# 致谢: [zizifn](https://github.com/zizifn/edgetunnel) [cmliu](https://github.com/cmliu/edgetunnel)
