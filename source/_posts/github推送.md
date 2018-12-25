---
layout: markdown
title: github推送
date: 2018-12-25 15:12:51
tags:
---
###
echo "# abc" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:wuqi931188574/abc.git
git push -u origin master


###   (创建好仓库和指定地址的的时候)

git add *
git commit -m "*"
git push

*　如果要一次性推送多个txt文档
１．先在仓库路径创建多个文档
２．git add *
３．git commit -m "推送多个txt"
４．git push

###   ()




