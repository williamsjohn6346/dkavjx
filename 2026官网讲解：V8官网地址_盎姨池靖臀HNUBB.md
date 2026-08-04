V8官网地址【Q-——333307——】V8官网地址【 辋芷《888yx●vip》 】
V8官网地址【Q-——333307——】V8官网地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南

你是不是也想拥有一个属于自己的技术博客，但又担心买服务器、配数据库太麻烦？其实，GitHub Pages 就能免费解决托管问题，搭配 Hexo 这个轻量级静态博客框架，十分钟就能上线一个高颜值、支持 Markdown 的专属站点。今天这篇 GitHub Pages 搭建教程，就带你走一遍完整流程。

 为什么选择“GitHub + Hexo”这套组合？

- 零成本部署：GitHub Pages 提供免费静态托管，无需购买云服务器。
- 极速访问体验：生成的是纯 HTML 静态文件，CDN 加速下加载飞快。
- 写文如写代码：用 Markdown 写作，配合 Git 进行版本管理，技术写作工作流 极其顺滑。
- 高度可定制：Hexo 拥有丰富的主题和插件生态，换肤、加评论、SEO 优化都能搞定。

 第一步：准备工作（三件套）

1. 注册 GitHub 账号：访问 github.com，完成注册并验证邮箱。
2. 安装 Node.js：前往 nodejs.org 下载 LTS 版本，一路默认安装。
3. 安装 Git：同样去 git-scm.com 下载对应系统的安装包。

 第二步：用 Hexo 快速初始化博客

打开终端（Windows 用户用 Git Bash），依次执行以下命令：

```bash
 安装 Hexo 命令行工具
npm install -g hexo-cli

 初始化博客文件夹
hexo init my-blog
cd my-blog

 安装依赖包
npm install

 本地预览（浏览器访问 http://localhost:4000）
hexo server
```

看到默认页面后，说明你的本地博客已经跑起来了。接下来就是把它部署到 GitHub Pages。

 第三步：部署上线，搞定免费域名

1. 在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`（必须完全一致）。
2. 修改本地 `_config.yml` 文件，找到 `deploy` 部分，填写你的仓库地址。
3. 安装部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate
hexo deploy
```

几分钟后，访问 `https://你的用户名.github.io` ，你的个人博客就正式公开上线了！后续写新文章，只需在 `source/_posts` 下新建 `.md` 文件，执行 `hexo d` 即可发布。

 遇到问题怎么办？

最常见的问题就是 `hexo deploy` 提示权限错误，多半是没配置 SSH Key。去 GitHub 设置里添加 SSH 公钥就能解决。也可以看看我的博客搭建常见问题合集，里面整理了完整的排查思路。

---

你在搭建过程中遇到卡点了吗？ 欢迎在评论区留言，我会一一帮你排查。觉得这篇 GitHub Pages 教程 有用的话，点个 Star 或在看，让更多朋友学会自己动手搭一个免费博客吧！

相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E7%A7%91%E6%8A%80%E8%AE%B2%E8%A7%A3%EF%BC%9AV8%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E4%BB%BF%E8%AE%BC%E5%A5%94%E7%9B%8E%E9%BC%93CJDKR.md

<img src="https://i.postimg.cc/W4Nx0Vgy/V8-00017.png" />

相关推荐：

https://github.com/stoneconnor94/facjpk/commit/4fd5ee7c462a62bae3d9b0e33e65befaac284b2f

<img src="https://i.postimg.cc/3Rw9xJm7/V8-00005.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%EF%BC%9AV8%E7%BD%91%E5%9D%80app_%E6%A1%88%E7%A1%95%E9%94%B0%E5%85%B9%E9%85%B1MFSUB.md

<img src="https://i.postimg.cc/SsKVxN8Z/V8-00004.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/801fb66efa38c86880b4953bebe4f971ed41eb07

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
