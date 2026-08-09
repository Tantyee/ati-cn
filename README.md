# 微步 ThreatBook CTI 中文在线文档项目

本仓库包含微步 ThreatBook CTI 的中文在线产品文档与 API 接口参考。使用 [Mintlify](https://mintlify.com) 构建与发布。

### 本地预览与开发

1. 安装 [Mintlify CLI](https://www.npmjs.com/package/mintlify)：

```bash
npm i -g mintlify
```

2. 在文档根目录（即 `docs.json` 所在目录）下运行本地开发服务：

```bash
mintlify dev 
```

### 部署与发布

将项目提交并推送至指定的 Git 仓库主分支后，关联的部署系统将自动触发增量更新与生产环境发布。

#### 常见问题排查

- 如果 `mintlify dev` 无法正常运行：尝试执行 `mintlify install` 重新安装依赖。
- 页面加载提示 404：请确保在包含 `docs.json` 的根目录下运行命令。
