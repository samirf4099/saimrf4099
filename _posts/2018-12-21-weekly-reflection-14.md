---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Norway by Samir Forde

## Describe your program

I designed the Norwegian flag. I expected a grade of apprentice (2). 

<!--- Delete this comment and add your writing -->

## Current output


![FlagImage](Images/final-flag.png)


## Describe your process.

A strategy I used when doing my flag was defining my functions. It was easier to put the images over each other and not have to write the whole thing. It's a good strategy, and I've been teaching it to my peers who don't use definitions.

<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
(define WIDTH 450)
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
(scale 2 NORWAY)
```
