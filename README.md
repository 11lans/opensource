# 开源项目

本仓库用于存放与发布**开源项目**（公开可见）。

- 仓库地址：https://github.com/11lans/opensource —— 可见性：**Public（任何人可见）**

## 项目索引

| 项目 | 说明 | 状态 |
|---|---|---|
| _（还没有项目，添加后在此登记）_ | | |

## 怎么添加一个新项目

1. 在仓库根目录建立以项目名命名的文件夹，例如 `my-tool/`
2. 放入代码，并为每个项目配自己的 `README.md` 和 `LICENSE`
3. 提交并推送：

```powershell
cd <工作区>\repos\opensource
git add .
git commit -m "add: my-tool"
git push
```

4. 回到上表登记一行

## 约定建议

- 一个项目一个子目录，互不干扰
- 每个项目自带 README（怎么装、怎么用）和 LICENSE（开源协议）
- 需要独立的 issue 跟踪或协作者权限时，建议单独建仓库，再在本索引里链接过去
- **这是公开仓库**：不要放私人资料、密钥、内网地址、他人隐私数据

## 关联仓库

| 仓库 | 可见性 | 用途 |
|---|---|---|
| [personal](https://github.com/11lans/personal) | Private | 私人资料 |
| [opensource](https://github.com/11lans/opensource) | Public | 开源项目（本仓库） |
