# Agno 中文文档

## 使用 MCP 搜索文档内容

> 前提条件：需要安装 Node.js

```
npx mint-mcp add coralera -y
```

> 出现以下界面为安装成功

![image](https://github.com/user-attachments/assets/bdb34174-8997-4a7c-a5dc-baff9b9330fa)


## 开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mintlify) 以本地运行文档站点：

```
npm i -g mintlify
```

在文档根目录（即 mint.json 所在位置）运行以下命令：

```
mintlify dev --port 3333
```

## 发布变更

推送至 main 分支即可发布变更

```
git add .
git commit -m "update message"
git push
```

## 故障排除

- Mintlify dev 未运行 - 执行 `mintlify install` 将重新安装依赖项
- 页面加载为404 - 请确保在包含 `mint.json` 的文件夹中运行

## LICENSE
[MIT](LICENSE)
