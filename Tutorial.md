- 网站搭建
  - [保姆级教程：从零构建GitHub Pages静态网站-CSDN博客](https://blog.csdn.net/qq_20042935/article/details/133920722)
- 界面渲染
  - [Installation | Jekyll • Simple, blog-aware, static sites (jekyllrb.com)](https://jekyllrb.com/docs/installation/)
  - [Adding a theme to your GitHub Pages site using Jekyll - GitHub Docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)
  - [如何使用Jekyll在GitHub Pages上搭建网站（个人博客）_jekyll github-CSDN博客](https://blog.csdn.net/qq_33919450/article/details/127859193)
- Organization
  - [超详细！Github团队协作教程（Gitkraken版） - thousfeet - 博客园 (cnblogs.com)](https://www.cnblogs.com/thousfeet/p/7840932.html)



界面渲染可以从简,通过remote-jekyll的主题来自动地从md文件转换为html文件,可以不用在本地进行网页的调试, 如果需要进行侧边栏, 主题页选择等工作, 就还是需要通过jekyll的文档进行构建, 即这里只是一个孤立的静态页面





教程

1. 创建Organization
2. 发布一篇博客的话, 就在Organization下创建一个repo,比如demo, 需要有两个文件
   1. _config.yml, 内容仿照即可, 修改title和description
   2. demo.md, 即博客文档
   3. 如果md文档中图片链接为本地链接需要将image文件夹也上传并保持相同路径关系
3. 需要在repo的setting中公布网站
   1. ![image-20240720143102548](https://test4projectwf.oss-cn-hangzhou.aliyuncs.com/imageimage-20240720143102548.png)
4. 提交之后, 静态页面已经生成完毕, 地址为  username.io/demo/demo.html, 即 用户名/组织名.io/repo名/文档名.html  