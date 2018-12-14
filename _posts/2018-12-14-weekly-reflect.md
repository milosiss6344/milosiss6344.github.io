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

What we started doing this week was to start building our Flags in Wescheme. We had to use the numbers our flags our made up of in order to properly start programming 
