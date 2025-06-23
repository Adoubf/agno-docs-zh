# Agno 中文文档

## 本地开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mintlify) 以在本地运行文档站点：

```
npm i -g mintlify
```

在文档根目录（即包含 mint.json 的目录）运行以下命令：

```
mintlify dev --port 3333
```

## 推送版本

通过推送到 main 分支发布更改：

```
git add .
git commit -m "update message"
git push
```

## 故障排除

* Mintlify dev 无法运行 - 执行 `mintlify install` 重新安装依赖。
* 页面显示 404 - 确保你在包含 `mint.json` 的文件夹中运行。
