---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Norway by Samir Forde

## Describe your program

I designed the Norwegian flag. I expected a grade of apprentice (2). 

<!--- That's rough, my dude... -->

## Current output

* * *
![Flag](/Images/flagV2.png)
* * *

## Describe your process.

A strategy I used when doing my flag was defining my functions. It was easier to put the images over each other and not have to write the whole thing. It's a good strategy, and I've been teaching it to my peers who don't use definitions.

<!--- Hey... That's pretty goooood! -->


## Explain your code.

I defined the width and the height so that I didn't have to write the numbers in every time. I also defined them to use them in my other shapes I used i the flag. I defined my other shapes as well to make it easier to put them together.
The base is the red background of the Norwegian flag. The strap is the white rectangle that is vertical on the flag. The belt is the white rectangle that is horizontal on the flag.

* * *

```
(define WIDTH 450)

(define HEIGHT 300)

(define BASE(rectangle WIDTH HEIGHT "solid" "red"))

(define STRAP(rectangle 50 HEIGHT "solid" "white"))

(define NOR1(put-image STRAP 160 150 BASE))

(define STRAP2(rectangle 25 HEIGHT "solid" "darkblue"))

(define BELT(rectangle WIDTH 50 "solid" "white"))

(define NOR2(put-image BELT 225 150 NOR1))

```

* * *
Each argument makes all the differnt shapes that make up the Norwegian flag. The code makes the flag look whole and legit.
 
<!--- Ok. -->


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

```
