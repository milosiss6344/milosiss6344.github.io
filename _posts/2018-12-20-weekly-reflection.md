---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Norway by Milosis Sepulveda

## Describe your program

Norway is a Scandinavian country encompassing mountains, glaciers and deep coastal fjords. Oslo, the capital, is a city of green spaces and museums. Norway is also known for fishing, hiking, and skiing, notably at Lillehammer's Olypic Resort.
A grade i expect out of this a Practioner because i folowed each and every instructions in order to reach this step i also deserve a Practioner because i helped my classmates when they needed help in this project.

## Current output

* * *
![Flag](/images/final-flag.png.png)
* * *

## Describe your process.

Some questions i still had were at first how can any number we put is going to change how our flags look entirely? Another i still have is How can the portions of the flag be so important numbers to this project? A challenge i faced while doing this porject is helping my classmates make their flags but some how i managed to help them and also do my work.


## Explain your code.

* * *

```
;overlay 

(define size 100)

(define width (* 11 size))
(define height (* 8 size))
(define stripe-height (/ height 4))

(define base (rectangle width 200 "outline" "black"))

(put-image (rectangle stripe-height width "solid" "blue") 
                   100 100 
                   base) 

(put-image (rectangle width 30 "solid" "blue") 
           150 100 
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
The code i posted is a little part of my starting to be flag. As you can see in each line i have "define" first so what i did for each line was i took the portion of the flag and covert those numbers in to even numbers so like that it fit each shape. For example if rectangles in the flag were 200 i would define each rectangle with 200 and so and so on.
My code section fit in to all because at the end each shape was on top of each other and was slowly forming the falg i had which was Norway.


## Program code

```
;overlay 

(define size 100)

(define width (* 11 size))
(define height (* 8 size))
(define stripe-height (/ height 4))

(define base (rectangle width 200 "outline" "black"))

(put-image (rectangle stripe-height width "solid" "blue") 
                   100 100 
                   base) 

(put-image (rectangle width 30 "solid" "blue") 
           150 100 
           base) 


(put-image (rectangle 50 200 "solid" "white" ) 
           100 100 
           base) 

;(put-image (rectangle width 50 "solid" "white" ) )  

(overlay
 (put-image
  (rectangle 30 200 "solid" "blue")
  100 100 
  (rectangle 300 200 "outline" "black"))
 (put-image
  (rectangle 300 30 "solid" "blue") 
           150 100 
           (rectangle 300 200 "outline" "black")) 
 (put-image
  (rectangle 50 200 "solid" "white") 
  100 100 
  (rectangle 300 200 "outline" "black")) 
 (put-image(rectangle 300 50 "solid" "white") 
           150 100 
           (rectangle 300 200 "outline" "black")) 
 (rectangle 300 200 "solid" "red"))
;(define shapes)

(define stripe1 (rectangle 30 200 "solid" "blue"))
(define stripe2 (rectangle 300 200 "outline" "black"))
(define stripe3 (rectangle 300 30  "solid" "blue"))
(define stripe4 (rectangle 300 200 "outline" "black"))
(define stripe5 (rectangle 50 200 "solid" "white"))
(define stripe6 (rectangle 300 200 "outline" "black"))
(define stripe7 (rectangle 300 50 "solid" "white"))
(define stripe8 (rectangle 300 200 "outline" "black"))
(define stripe9 (rectangle 300 200 "solid" "red"))
```
