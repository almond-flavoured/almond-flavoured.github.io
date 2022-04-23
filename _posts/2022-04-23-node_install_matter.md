---
title: nvm install node 이후 문제발생
date: 2022-04-23 23:44:00 +/- TTTT
categories: [aws, linux]
tags: [aws, linux] # TAG는 반드시 소문자로 이루어져야함!
---

```bash
ubuntu@ip-172-31-37-146:~$ node --version
node: /lib/x86_64-linux-gnu/libc.so.6: version `GLIBC_2.28' not found (required by node)
```

```bash
ubuntu@ip-172-31-37-146:~$ nvm install v10.13.0
Downloading and installing node v10.13.0...
Downloading https://nodejs.org/dist/v10.13.0/node-v10.13.0-linux-x64.tar.xz...
########################################################################################################################################## 100.0%
Computing checksum with sha256sum
Checksums matched!
Now using node v10.13.0 (npm v6.4.1)
```

```bash
ubuntu@ip-172-31-37-146:~$ node --version
v10.13.0
```
