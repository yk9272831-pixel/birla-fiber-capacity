# GitHub Pages 部署说明

这个文件夹已经整理成可以直接上传 GitHub Pages 的结构：

- `index.html`：网页首页，GitHub Pages 会自动识别这个文件。
- `sources/screenshots/`：网页引用的全部证据截图。

## 小白操作步骤

1. 打开 https://github.com 并登录。
2. 点击右上角 `+`，选择 `New repository`。
3. Repository name 填：`birla-fiber-capacity`。
4. 选择 `Public`。
5. 点击 `Create repository`。
6. 进入新仓库页面后，点击 `uploading an existing file`。
7. 把本文件夹 `github-pages` 里面的内容拖进去：
   - `index.html`
   - `sources` 文件夹
   - 这个说明文件可传可不传
8. 点击绿色按钮 `Commit changes`。
9. 进入 `Settings` → `Pages`。
10. `Build and deployment` 选择 `Deploy from a branch`。
11. Branch 选择 `main`，文件夹选择 `/root`，点击 `Save`。
12. 等 1-3 分钟，GitHub 会生成一个链接，通常类似：
    `https://你的用户名.github.io/birla-fiber-capacity/`

## 外发前检查

打开 GitHub Pages 链接后，确认：

- 页面标题能显示。
- 证据区 10 张截图都能显示。
- 点击证据卡片里的原链接可以跳转。

如果图片不显示，通常是因为上传时没有把 `sources/screenshots` 文件夹一起传上去。
