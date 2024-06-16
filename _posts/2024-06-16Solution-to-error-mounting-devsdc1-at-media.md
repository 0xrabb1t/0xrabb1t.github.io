---
title: Fix errors - solution to error mounting /dev/sdc1 at /media/
date: '2024-06-16 15:41:59'
comments: false
categories: [Ubuntu]
tags: [troubleshooting]
---


1. Open "Disks"
 

2. Then disable `User sesssion defaults` and press OK

 


3. finally execute
`$ systemctl daemon-reload`
