# RecallPast 回往
追忆往事，用相册回忆种种，让时间记录在眼前
岁月如梭，追忆往事。
相册永远都是一种承载着我们美好的容器，承载了我们记忆、情感、故事和时间。

### 项目框架

采用了Hexo框架进行网站的开发，记录照片内容和排版合理的布局。

Hexo框架是一个 **快速、简洁且高效的静态博客生成框架** 。Hexo基于Node.js，这使得它依赖于较少的外部组件，易于安装和使用。

### 框架指令

Hexo框架的编辑指令主要包括以下几个方面，以下是按照清晰格式归纳的指令列表：

1. **初始化Hexo**
   * 指令：`hexo init [folder]`
   * 描述：用于新建一个Hexo网站。如果未设置 `folder`，Hexo将默认在当前文件夹建立网站。
2. **新建文章**
   * 指令：`hexo new [layout] <title>`
   * 描述：新建一个Markdown文章。如果未设置 `layout`，则默认使用 `_config.yml`中的 `default_layout`参数。如果标题包含空格，请使用引号括起来，如 `hexo new "post title with whitespace"`。
3. **生成静态页面**
   * 指令：`hexo generate` 或简写为 `hexo g`
   * 描述：执行后在Hexo站点根目录下生成 `public`文件夹，其中包含生成的静态网页文件。
4. **清理生成的文件**
   * 指令：`hexo clean`
   * 描述：删除前面通过 `hexo generate`或 `hexo g`命令生成的 `public`文件夹，以便重新生成。
5. **本地预览**
   * 指令：`hexo server` 或简写为 `hexo s`
   * 描述：启动服务，在本地运行Hexo网站，默认地址为 `http://localhost:4000/`，可以在浏览器中预览生成的网页。
6. **部署站点**
   * 指令：`hexo deploy` 或简写为 `hexo d`
   * 描述：将编译后的文件部署到远程服务器或Git仓库，具体部署方式需要在 `_config.yml`中配置。
7. **自定义配置**
   * 指令示例：`hexo server --config custom.yml` 或 `hexo generate --config custom.yml,custom2.json`
   * 描述：允许使用自定义的配置文件来启动Hexo服务或生成静态页面。可以指定一个或多个YAML或JSON文件作为配置文件的路径。
8. **其他常用指令**
   * 简洁模式：`hexo --silent`，隐藏终端信息。
   * 显示草稿：`hexo --draft`，显示 `source/_drafts`文件夹中的草稿文章。
   * 自定义CWD（当前工作目录）：`hexo --cwd /path/to/cwd`，指定当前工作目录的路径。
