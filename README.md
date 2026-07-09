# 业务逻辑问答助手原型

这是一个纯静态 GitHub Pages 原型，入口文件是 `index.html`。

## 发布到 GitHub Pages

1. 新建一个 GitHub 仓库，例如 `marketing-logic-admin-pages`。
2. 把本目录里的文件推到仓库默认分支。
3. 打开仓库 `Settings` -> `Pages`。
4. Source 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub Pages 构建完成。

公网地址一般是：

```text
https://你的GitHub用户名.github.io/marketing-logic-admin-pages/
```

## 本地文件

- `index.html`：业务逻辑问答助手原型
- `.nojekyll`：避免 GitHub Pages 使用 Jekyll 处理静态文件
