---
layout: page
title:  "修改苹果系统终端提示符"
tagline: "</br>How to Change Your Default Terminal Prompt in Mac OS X"
date:   2019-09-16 15:24:35 +0200
tags: [MacOS, Terminal, Prompt, Default, Tool]
categories: rust
---

### 终端命令
```bash
echo "export PS1='~.~$ '" >> ~/.profile
. ~/.profile
```

### 参考资料
- [how-to-change-your-default-terminal-prompt-in-mac-os-x-lion](https://mattmazur.com/2012/01/27/how-to-change-your-default-terminal-prompt-in-mac-os-x-lion/)