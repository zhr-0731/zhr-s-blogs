
## 部署步骤

1. **创建GitHub仓库**
   - 仓库名必须为：`yourusername.github.io`
   - 将yourusername替换为你的GitHub用户名

2. **上传文件**
   - 将本项目所有文件上传到仓库根目录

3. **启用GitHub Pages**
   - 进入仓库设置 → Pages
   - Source选择：Deploy from a branch
   - Branch选择：main，文件夹：/(root)
   - 点击Save

4. **访问网站**
   - 访问：https://yourusername.github.io
   - 等待1-2分钟生效

## 自定义配置

1. **修改个人信息**
   - 在index.html和post.html中替换：
     - 博客名称
     - 作者头像和名称
     - 社交媒体链接

2. **修改Giscus配置**
   - 在post.html中更新Giscus脚本的配置：
     - data-repo: 你的GitHub仓库
     - data-repo-id: 仓库ID
     - data-category: 讨论分类
     - data-category-id: 分类ID

3. **添加新文章**
   - 复制post.html模板
   - 修改文章内容
   - 在index.html中添加文章卡片

## 技术栈

- HTML5
- CSS3 (原生，无框架)
- JavaScript (仅Giscus评论)
- GitHub Pages

## 许可证

MIT License
