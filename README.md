# phills_clojure_euler_problems

1. Sum of numbers divisible by 3 or 5 under 1000, in a very basic clojure one liner - 

   ```clojure
   (reduce + (filter #(or (integer? (/ % 3)) (integer? (/ % 5))) (map inc (range 999))))
   ```
   
1. 
