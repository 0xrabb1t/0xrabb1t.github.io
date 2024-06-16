---
title: Fix errors - solution to error mounting  dev sdc1 at  media 
date: '2024-06-16 15:41:59'
comments: true
categories: [Ubuntu]
tags: [troubleshooting]
---

# Solution

## Open "Disks"
<a href="https://raw.githubusercontent.com/0xrabbitSec/0xrabbitSec.github.io/main/_posts/images/fixErrorMounting-images/image01.png"><img src="https://raw.githubusercontent.com/0xrabbitSec/0xrabbitSec.github.io/main/_posts/images/fixErrorMounting-images/image01.png" height="800" width="950"></a>

## Then disable `User sesssion defaults` and press OK
<a href="https://raw.githubusercontent.com/0xrabbitSec/0xrabbitSec.github.io/main/_posts/images/fixErrorMounting-images/image02.png"><img src="https://raw.githubusercontent.com/0xrabbitSec/0xrabbitSec.github.io/main/_posts/images/fixErrorMounting-images/image02.png" height="800" width="950"></a>
 


## finally execute
`$ systemctl daemon-reload`
