+++
date = '2025-10-23T12:43:02+08:00'
draft = false
title = '更新博客方法（备忘）'

+++

# 更新的方法

## 进入项目根目录

打开终端

输入

```bash
hugo new posts/文件名.md
```

## 在刚刚创建的文件中输入内容

## 在本地预览（可不做）

在刚刚的终端，输入

```powershell
hugo server -D
```

## 先生成生产环境文件（确保 draft: false）

```powershell
hugo
```



## 写好后，输入这几个指令即可

```powershell
git add .
git commit -m "发布新文章" #说明理由就行
git push
```

