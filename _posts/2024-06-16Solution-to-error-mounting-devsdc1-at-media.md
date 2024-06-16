---
title: Fix error in mounting
date: '2024-06-16 15:41:59'
categories: [tips]
tags: [linux]    # TAG names should always be lowercase
---

# Solution

## Open "Disks"

![image01](_posts/images/fixErrorMounting-images/image01.png)

## Then disable `User sesssion defaults` and press OK

 ![image02](_posts/images/fixErrorMounting-images/image012.png)


## finally execute
`$ systemctl daemon-reload`
