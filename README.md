
icrosoft Windows [Version 6.1.7601]
Copyright (c) 2009 Microsoft Corporation.  All rights reserved.

C:\Users\jwei010>cd C:\weijianying\myPrivate\myBlog\jekyll_demo

C:\weijianying\myPrivate\myBlog\jekyll_demo>git add .

C:\weijianying\myPrivate\myBlog\jekyll_demo>git commit -m "first post"
On branch gh-pages
nothing to commit, working directory clean

C:\weijianying\myPrivate\myBlog\jekyll_demo>git remote add origin http://github.
com/shanshangshu/jekyll_demo.git
fatal: remote origin already exists.

C:\weijianying\myPrivate\myBlog\jekyll_demo>git push origin gh-pages
Username for 'https://github.com': weijianying1@126.com
Password for 'https://weijianying1@126.com@github.com':
remote: Repository not found.
fatal: repository 'https://github.com/shanshangshu/jekyll_demo.git/' not found


C:\weijianying\myPrivate\myBlog\jekyll_demo>git add --all

C:\weijianying\myPrivate\myBlog\jekyll_demo>git show-ref
3570402f52869395064dcc92849bea2376287023 refs/heads/gh-pages
C:\weijianying\myPrivate\myBlog\jekyll_demo>git push origin HEAD:gh-pages
Username for 'https://github.com': shanshangshu
Password for 'https://shanshangshu@github.com':
Counting objects: 12, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (10/10), done.
Writing objects: 100% (12/12), 1.28 KiB | 0 bytes/s, done.
Total 12 (delta 1), reused 0 (delta 0)
To https://github.com/shanshangshu/jekyll_demo.git
 * [new branch]      HEAD -> gh-pages

C:\weijianying\myPrivate\myBlog\jekyll_demo>
