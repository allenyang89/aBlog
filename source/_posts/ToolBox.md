---
title: Tool Box
date: 2017-02-23 11:21:24
tags: ToolBox
---
# Hexo
- [基础设置](https://munen.cc/tech/hexo-init.html#2-与-GitHub-建立联系)

# Git
- [Multiple ssh keys](https://code.tutsplus.com/tutorials/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574)

# Ruby
- 二进制转换(binary <=> int)
```
9.to_s(2) #=> "1001"; "1001".to_i(2) #=> 9
```

# Rails
- 识别 Controller by path
```
Rails.application.routes.recognize_path(request.referrer)
```