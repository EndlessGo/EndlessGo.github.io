# EndlessGo.github.io

这是一个基于Hexo构建的个人博客网站项目，以下是项目结构说明：

## 目录结构

- `source/`: 存放博客文章的源文件和其他原始内容
- `themes/`: 存放博客主题相关的文件
- `scaffolds/`: 存放文章、页面和草稿的模板文件
- `public/`: 是hexo generate构建输出目录，包含生成的静态网站文件，可以直接把这个目录下的文件部署到任何静态网站服务器上
- `.deploy_git/`: 专门用于 GitHub Pages 部署的 Git 仓库目录
- `.git/`: Git 版本控制目录
- `.github/`: GitHub 相关配置文件目录
- `node_modules/`: Node.js 依赖包目录

## 配置文件

- `_config.yml`: Hexo 的主配置文件
- `_config.landscape.yml`: Landscape 主题的配置文件
- `package.json`: Node.js 项目依赖配置文件
- `package-lock.json`: Node.js 依赖版本锁定文件
- `yarn.lock`: Yarn 包管理器的依赖锁定文件
- `.gitignore`: Git 忽略文件配置
- `db.json`: Hexo 数据缓存文件

## 说明

这是一个使用Hexo搭建的静态博客网站，主要用于展示编程相关的文章和内容。网站支持响应式设计，可以在各种设备上良好显示。 