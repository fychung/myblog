---
title: "Hugo command"
date: 2022-09-13T22:40:24+08:00
draft: true
---
# 1、Hugo command:

   1. hugo new site XXX. 生成站点
   2. cd XXX
   3. git init
   4. git submodule add https://github.com/.../theme_XXXX.git themes/XXXX
   5. 添加XXXX到config.toml
   6. hugo new posts/my-first-post.md 生成md页面
   7. 编辑内容
   8. hugo server -D 启动，查看

# 2、在线托管

```
  --destination  指定生成静态文件目录，例如 ./docs
  --buildDrafts  表示posts中被标记为drafts的post，也被包括进来生成静态文件
  --cleanDestinationDir 静态目录中没有的文件，也不会出现在destination目录中

  hugo --destination ./docs --buildDrafts --cleanDestinationDir
```
---
