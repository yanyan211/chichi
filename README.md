# 迟迟—拖延症交互网页

通过交互画面了解拖延心理的网站，采用 1920 × 1080、16:9 横屏设计基准，随浏览器窗口等比例适配。

## 文件

- index.html 是网页入口。
- assets 文件夹包含网站使用的图片、音频及矢量素材。
- .nojekyll 用于让 GitHub Pages 直接发布静态文件。

## 上传与部署

1. 在 GitHub 创建一个公开仓库，名称可以使用 chichi-interactive。
2. 点击 Add file → Upload files，将本文件夹中的内容上传到仓库。仓库根目录应直接显示 index.html 和 assets 文件夹。
3. 提交文件到 main 分支。
4. 打开仓库 Settings → Pages。
5. 在 Build and deployment 下，将 Source 设为 Deploy from a branch。
6. 将 Branch 设为 main，文件夹设为 /(root)，点击 Save。
7. 等待发布完成，在 Pages 页面复制网站链接。项目网站地址通常为 https://你的用户名.github.io/仓库名/ 。

GitHub 官方部署说明
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 后续更新

修改并重新上传 index.html 或 assets 中相应文件，提交到 main 后，GitHub Pages 会重新发布。

## 体验说明

- 使用电脑浏览器横屏体验，部分交互使用鼠标、拖动及空格键。
- 背景音乐默认尝试自动播放并循环。浏览器首次访问若拦截有声自动播放，点击页面任意位置即可启动。
- 右下角声音按钮可以开启或关闭音乐和音效。

本文件夹可以作为静态站点直接部署，准备阶段已完成素材整理。
