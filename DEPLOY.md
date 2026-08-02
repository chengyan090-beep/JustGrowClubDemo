# 手动上传说明

这个文件夹是「恰好关系推荐官 / 筑光公社 AI 社区运营小程序 Demo」的 GitHub Pages 发布包。

## 需要上传的文件

- `index.html`
- `.nojekyll`
- `README.md`
- `DEPLOY.md`
- `assets/` 整个文件夹

## 上传到 GitHub

1. 打开仓库：https://github.com/chengyan090-beep/JustGrowClubDemo
2. 点击 `Add file` -> `Upload files`
3. 把本文件夹里的 `index.html`、`.nojekyll`、`README.md`、`DEPLOY.md` 和 `assets/` 整个文件夹拖进去
4. 页面底部点击 `Commit changes`

## 开启网页访问

1. 进入仓库 `Settings`
2. 左侧点击 `Pages`
3. `Build and deployment` 里选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. 点击 `Save`

## 外部访问链接

发布完成后，访问：

https://chengyan090-beep.github.io/JustGrowClubDemo/

如果刚开启 Pages，通常需要等待 1-3 分钟生效。

## 每次更新后的必检项

每次更新 GitHub 后，都需要用带版本号的公开链接检查，而不是只看本地页面。

示例：

https://chengyan090-beep.github.io/JustGrowClubDemo/?v=commit-id

必检内容：

- 首页推荐区的活动图片是否完整显示
- 活动详情页顶部图片是否完整显示
- `assets/event-dinner-chat.png`、`assets/event-walk-lightmeal.png`、`assets/xiaoc-avatar.png` 是否能从外部直接打开
- 首页关键入口是否跳转正确，尤其是「需求广场」「资源响应」「活动详情」
