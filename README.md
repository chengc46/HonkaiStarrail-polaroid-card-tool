# 仿拍立得卡片生成工具

这是一个可通过 GitHub Pages 免费发布的单文件网页工具。用户可以上传角色图片，自定义背景渐变、文字、命途图标，并导出拍立得卡片及烫金层。

## 在线发布方式

1. 在 GitHub 新建一个 repository，例如 `polaroid-card-tool`。
2. 将本文件夹内的所有文件上传到 repository 根目录。
3. 打开 repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. 保存后等待 1–3 分钟，GitHub Pages 会生成公开访问链接。

## 文件结构

```text
polaroid-card-tool/
  index.html          # 当前公开版本，GitHub Pages 会自动作为首页
  archive/v15.html    # 历史版本备份
  docs/CHANGELOG.md   # 更新记录
  README.md           # 发布说明
  .nojekyll           # 避免 GitHub Pages/Jekyll 处理静态文件
```

## 后续更新建议

以后继续优化时，建议始终把最新稳定版本保存为 `index.html`，这样分享链接不会改变。旧版本可以复制到 `archive/` 文件夹中，例如 `archive/v16.html`、`archive/v17.html`。

## 版权说明

本工具中的“命途”图标版权属于《崩坏：星穹铁道》及其相关权利方。本网页工具为免费分享的非商业粉丝向工具，请勿用于商业用途或误导性用途。

用户自行上传的角色图片、素材图片等内容由上传者自行确认使用权利。
