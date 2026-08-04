V8官方平台【Q-——333307——】V8官方平台【 辋芷《888yx●vip》 】
V8官方平台【Q-——333307——】V8官方平台【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025新版）

> 还在羡慕别人的技术博客？其实用GitHub免费托管、Hexo快速生成，30分钟就能拥有属于自己的极简博客。本教程面向纯小白，手把手带跑通全流程。

 为什么推荐 GitHub Pages + Hexo？

- 零成本：GitHub Pages 免费提供静态托管，无服务器费用
- 高定制：Hexo 主题丰富，支持 CSS/JS 深度改造
- SEO友好：静态页面加载快，天然适配搜索引擎抓取

 第一步：环境准备（5分钟）

1. 注册 GitHub 账号（已有可跳过）
2. 安装 Node.js（建议 LTS 版本）
3. 安装 Git 并配置全局用户名和邮箱

```bash
node -v    验证 Node 版本
git --version   验证 Git
```

 第二步：安装 Hexo 并初始化项目

```bash
npm install hexo-cli -g    全局安装 Hexo
hexo init my-blog    初始化博客目录（可自定义名称）
cd my-blog
npm install    安装依赖
```

启动本地预览：`hexo s`，浏览器访问 `http://localhost:4000` 即可看到默认站点。

 第三步：部署到 GitHub Pages

1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`
2. 修改 `_config.yml` 中 deploy 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 执行部署命令：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

浏览器访问 `https://你的用户名.github.io` 即可看到线上博客。

 第四步：优化与个性化

- 换主题：Hexo 官网主题广场选择，推荐 `Butterfly` 或 `Next`
- 配置文章模板：修改 `scaffolds/post.md` 添加默认标签
- 添加搜索功能：安装 `hexo-generator-searchdb`
- 绑定自定义域名：在仓库 Settings -> Pages 中配置

 常见问题排查

- 部署提示权限错误：检查 Git 是否配置 SSH Key 或改用 HTTPS 方式
- 页面404：确认仓库名是否为 `用户名.github.io` 且已选对分支
- 本地预览正常但线上空白：清除浏览器缓存并查看 DevTools Console

 结语

至此，你的专属博客已经上线。后续可以学习使用 Travis CI 自动化部署，每次 `git push` 即自动更新。遇到问题欢迎评论区留言，或私信发送“博客”获取一键部署脚本。

如果本教程对你有帮助，点赞转发 让更多人看到。关注我，持续分享前端开发与效率工具干货，我们下篇见。

相关推荐：

https://github.com/clarkalyssa3349/mrznkk/blob/main/2026%E5%AE%98%E7%BD%91%E6%94%BB%E7%95%A5%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E7%BD%91%E5%9D%80_%E5%AD%9B%E5%88%AE%E4%BA%A4%E6%B2%AE%E4%B8%A5CPWKE.md

<img src="https://i.postimg.cc/SsKVxN8Z/V8-00004.png" />

相关推荐：

https://github.com/clarkalyssa3349/mrznkk/commit/c61f21dedab9aaaacdeca23174942d6942f962fd

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />
相关推荐：

https://github.com/williamsjohn6346/dkavjx/blob/main/2026%E7%A7%91%E6%8A%80%E6%95%99%E7%A8%8B%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95_%E6%BB%B4%E5%BE%97%E5%8A%AB%E8%85%BF%E7%AB%AFZGHIW.md

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />
相关推荐：

https://github.com/williamsjohn6346/dkavjx/commit/021fcffc87d6a7fc045b220f543ec1caba1d053f

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
