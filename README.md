
## 环境搭建

- Node.js
- Xmind 23.08.02122

```bash
npm install -g asar
```

## 如何使用

1. 23.08.02122 版本

2. 克隆项目

   ```bash
   git clone https://github.com/henryau53/xmind-crack-patch.git
   cd xmind-crack-patch
   ```

3. 编译补丁包

   ```bash
   asar pack ./app.asar.non-windows app.asar
   ```

4. 使用上一步生成的 app.asar 文件替换 Xmind 安装路径中的 resources 文件夹中的 app.asar 文件即可。
