# Huiyao Zhang Personal Homepage

这是一个静态个人主页项目，适合直接部署到 GitHub Pages。

## 目录说明

- `index.html`: 首页入口
- `style.css`: 页面样式
- `assets/`: 页面实际使用的头像、Logo、论文缩略图、奖项图和 CV

## 上传建议

这个仓库已经按公开发布场景做过一轮整理：

- 页面资源路径统一为稳定的英文路径
- 论文正文链接改成外部链接，避免仓库过大
- 原始证书、照片、论文截图和散落 PDF 默认不纳入 Git 跟踪

## GitHub Pages

上传到 GitHub 后，可以在仓库 `Settings -> Pages` 中开启：

1. `Build and deployment` 选择 `Deploy from a branch`
2. 分支选择 `main`
3. 文件夹选择 `/ (root)`

如果仓库名是 `zhang1huiyao.github.io`，站点会直接挂在根域名下；如果是普通仓库名，则地址会是 `https://zhang1huiyao.github.io/<repo-name>/`。
