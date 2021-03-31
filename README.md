# README

## 安装指南

本项目基于hugo渲染，参考[hugo Start](https://gohugo.io/getting-started/quick-start/)

### Step 1: Install Hugo

```bash
brew install hugo
# or
port install hugo
```

### Step 2: Start the Hugo server

```
hugo
```

## 项目路径描述

```
.
├── archetypes
├── config.toml # 项目整体配置
├── content
│   ├── about
├── data
│   ├── aboutMe.yml # 成员名单配置文件 其中包括领导标签，成员标签 
│   ├── blogSection.yml # 相关项目
│   ├── hero.yml # 页头配置
│   ├── serviceSection.yml # 理由配置页
│   └── testimonialSection.yml # 新闻配置页
├── layouts # 布局 不重要
├── public # hugo之后编译形成的html文件，将本文件传递至网站根目录。
├── readme.md # readme 不重要
├── resources # 不重要
├── static # 静态文件 不重要
└── themes # 主题 不重要
```

## CI配置
