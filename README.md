# phills_clojure_euler_problems

1. in a very basic clojure one liner - ```(reduce + (filter #(or (integer? (/ % 3)) (integer? (/ % 5))) (map inc (range 999))))```
