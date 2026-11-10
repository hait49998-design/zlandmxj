# 磊的剧场 · 张磊21岁生日特别篇

这是已制作完成的生日网站：6集原创互动短剧、48幕对白、Q版人物动作、剧情弹幕、37套冒险家时装图鉴、小游戏、生日结局及海报下载。

## 上传到 GitHub，生成网站

1. **先解压压缩包。不要只把 ZIP 文件上传到 GitHub。**
2. 在 GitHub 新建一个公开仓库，名称建议为 `zhanglei-birthday`。
3. 在仓库页面选择 **uploading an existing file**，或 **Add file → Upload files**。
4. 将解压后的全部文件拖进去，点击 **Commit changes** 保存。确认仓库首页直接能看到 `index.html`，不要让它藏在额外的一层文件夹里。
5. 打开仓库 **Settings → Pages**。
6. 在 **Build and deployment → Source** 中选择 **Deploy from a branch**。
7. Branch 选择 **main**，文件夹选择 **/(root)**，点击 **Save**。
8. 等待发布完成，刷新 Pages 设置页，点击显示的网站网址，就能打开并分享给张磊。

若仓库名为 `zhanglei-birthday`，网址通常为：

`https://你的GitHub用户名.github.io/zhanglei-birthday/`

“你的GitHub用户名”需要替换为实际用户名。以 Pages 设置页显示的网址为准。

以后重新上传新版 `index.html` 并提交，GitHub Pages 会自动更新网站。朋友浏览器仍显示旧版时可刷新页面。

## 包里的文件

- `index.html`：完整网站。人物动画、剧情、图片、小游戏已内嵌，可离线双击，也能直接发布。
- `.nojekyll`：让 GitHub Pages 按静态文件发布。
- `素材来源.json`：37套时装图片的来源记录。
- `第三方许可.txt`：依赖许可。
- `README.md`：本说明。

不需要安装程序，不需要运行构建命令，不需要填写密钥。此包是可直接发布的成品，后续修改网站代码请使用之前的完整源码交付包。

## 使用说明

首页点击“立即开播 · 我来当男主”。每集有8幕演出和两种分支，可以暂停、切换字幕速度、点人物看反应，也能跳到选台词。弹幕提供“热闹／适中”两档，可以发送本人高亮弹幕。

所有追剧与游戏进度仅保存在当前浏览器。弹幕是预设剧情与本地输入；网站无需登录，没有后端或跨设备同步。声音默认关闭，可以手动开启。

生日为农历十月初二，年龄21岁；网站未自动换算公历日期。人物为原创Q版木偶，时装图片另作参考；本站为非官方生日礼物，与红果、网易没有合作关系。时装图版权归原权利方，图片来源见素材记录。

## 遇到打不开时

- 仓库中只有 ZIP：先解压，上传里面的文件。
- 显示404：确认首页文件名为 `index.html`，在仓库根目录；Pages 已选择 `main` 和 `/(root)`，并等待发布完成。
- 找不到 main：先上传文件并完成第一次提交，再进入 Pages 设置。如果自行使用了其他分支名，选择实际存放 `index.html` 的分支。
- 不知道发布是否完成：查看仓库 **Actions** 页中的 Pages 发布任务；有错误时展开查看提示。

GitHub 官方操作说明：
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
