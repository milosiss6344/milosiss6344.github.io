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

What we started doing this week was to start building our Flags in Wescheme. We had to use the numbers our flags our made up of in order to properly start programming and use those numbers and the system we wrote in class to perform the witdh and the height of the flags. we kept on wrting the numbers of the glag to perform at least the one or teo lines of the flag 
