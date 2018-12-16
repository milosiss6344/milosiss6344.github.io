---
layout: post
tittle: "Flag Project-in Process"
date: 2018-12-14
---
![Flag Image](/images/flagvs.png)

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
```

What we started doing this week was to start building our Flags in Wescheme. We had to use the numbers our flags our made up of in order to properly start programming and use those numbers and the system we wrote in class to perform the witdh and the height of the flags. We kept on writing the numbers of the glag to perform at least the one or two lines of the flag. Next week we'll start upgrading our fags more in Wescheme. Some questions that were being asked in this week learning class were how are we going to convert the portions of the flag into smaller numbers because some of the portios of the flag were too big and had to be reduce to not be that big. 
