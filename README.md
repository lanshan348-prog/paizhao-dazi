# 拍照搭子1.0 · Android 测试版官网

本仓库用于官网与 APK 下载发布，不包含 Android 签名密钥。

当前版本：1.0.0-test.5，Android 10 及以上，包体 11.60 MB。这是测试签名的调试安装包，不是应用商店正式版。

## 下载

[下载 Android 手机测试版 APK](https://github.com/lanshan348-prog/paizhao-dazi/raw/refs/heads/main/docs/downloads/paizhaodazi-1.0.0-test.5.apk)

## 网站

静态文件在 docs/。下载按钮读取 docs/release.json 并检查同站 APK 文件存在后启用。APK 地址使用相对路径，可适配 GitHub Pages 的仓库子路径。

## GitHub 发布

1. 官网和 APK 已上传到 [lanshan348-prog/paizhao-dazi](https://github.com/lanshan348-prog/paizhao-dazi)。
2. 仓库 Settings → Pages → Build and deployment → Source 选择 Deploy from a branch；Branch 选择 main，目录选择 /docs，点击 Save。
3. 等待 GitHub 返回实际站点地址，再打开官网验证 APK 下载。网站地址以 Pages 显示结果为准，不在未部署时宣称上线。

[GitHub Pages 官方发布说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 安装与范围

手机下载 APK 后按系统提示安装；此前同签名测试版可覆盖安装。首拍申请相机权限；图像处理在本机执行。1–5× 倍率可能含数码裁剪，照片最长边不超过 2048 像素；暂无全分辨率拍照和闪光灯。已移除 0.5× 和所有人物轮廓，保留加粗井字线。

构建、签名与模拟桥接交互检查已完成，尚未在本次发布环境连接真机验证。请在手机上检查相机方向、倍率、修图和相册保存。

## 文件校验

SHA-256：afc8fc829cfbd781d87d457438ef857ed23c3fb0334a95d2a04482425a26872b

下载后的 APK 应与 docs/downloads/paizhaodazi-1.0.0-test.5.apk.sha256 一致。
