---
layout: post
title:  "BBB bare bone"
categories: 
tags:  Ubuntu Pycharm 
author: Wenjun Sun
---

## USB tethering / RNDIS
```js
https://www.joshuawise.com/horndis
-Macos 10.13 issues
  -open secuirty and open joshua
  -https://github.com/jwise/HoRNDIS/issues/72#issuecomment-378057820
```

### 
#### https://github.com/ravikp7/node-beagle-boot

### Boot
```js
 - internal ROM -> MLO -> UBOOT -> LINUX
 LMO https://witekio.com/blog/writing-mlo-beagleboard-xm/
 https://github.com/allexoll/BBB-BareMetal
 
 For beagle, it will look for MLO (file name) and copy that to internal ram and run
 MLO then should copy UBOOT to external RAM and RUN
 UBOOT then use the uEnv.txt to boot the programs
 It copies Linux or other program into memory location and then jumps to that location and run
 example: https://elinux.org/Building_BBB_Kernel
 
```
