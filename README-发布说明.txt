【工作日志跟进系统 · 手机版（PWA）+ GitHub 发布】
把本文件夹“全部文件”上传到任意 https 静态托管即可（推荐 GitHub Pages，免费、不需要备案）。

一、上传到 GitHub Pages
1. 打开 github.com，登录后新建仓库（New repository，建议仓库名：work-log-tracker）；
2. 在本文件夹内 git init → 全部提交 → 添加仓库地址推送；或用网页“Add file → Upload files”直接拖入本文件夹全部文件；
3. 仓库 Settings → Pages → Source 选 Branch: main / root → Save；
4. 等待 1~2 分钟，得到网址 https://你的用户名.github.io/仓库名/
（如果本机没装 Git / 不想用命令行，直接用网页上传文件即可。）

二、手机安装（像 App）
1. 手机浏览器打开上面网址；
2. 安卓 Chrome：菜单 → 「安装应用 / 添加到主屏幕」；
3. iPhone Safari：「分享」→「添加到主屏幕」；
4. 桌面出现「工作日志」图标，支持断网打开（PWA 缓存）。

三、说明
· 登录：首次用 admin / admin123（登录后请修改密码）。
· 数据默认保存在“当前这台设备的浏览器”里。
· 若需要“多台手机/电脑同一账号实时同步共享”，需要后端数据库（如 Supabase/Render）——
  拿到 Project URL + anon key（或部署地址）后，我来接通同步并把桌面版/手机版指向同一地址。
