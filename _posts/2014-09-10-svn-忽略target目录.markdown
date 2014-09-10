---
layout: post
styles: [syntax]
title: svn提交代码时忽略target目录
---
在java项目下，鼠标右击target目录，TortoiseSVN-->Unversion and add to ignore list-->target。这样提交代码的时候就自动忽略次目录了。
刚刚操作完了之后，文件夹目录图标可能没有变化，再执行一下clean up就可以了。
