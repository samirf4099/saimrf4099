---
layout: post
title: "Flag Project"
date: 2018-12-13
---

```(define WIDTH 450)
(define HEIGHT 300)
(define BASE(rectangle WIDTH HEIGHT "solid" "red"))
(define STRAP(rectangle 50 HEIGHT "solid" "white"))
(define NOR1(put-image STRAP 160 150 BASE))
(define STRAP2(rectangle 25 HEIGHT "solid" "darkblue"))
(define BELT(rectangle WIDTH 50 "solid" "white"))
(define NOR2(put-image BELT 225 150 NOR1))
(define NOR3(put-image STRAP2 160 150 NOR2))
(define BELT2(rectangle WIDTH 25 "solid" "darkblue"))
(define NORWAY(put-image BELT2 225 150 NOR3))
```
k.,hggv
