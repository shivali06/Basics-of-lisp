# Basics-of-lisp
Write the following LISP functions:
(5 points each)

1. Calculate the area of a circle with radius r

  - ``` (defun circleA (x) (* 3.14 x x)) ```


  - Example:-
    - (circlea 3)
    - 28.26

2. Convert temperatures in Celsius to temperatures in Fahrenheit
  - ``` (defun temp-change (x) (+ (* 1.8 x) 32)) ```
  
  
  - Example:-
    - (temp-change 20)
    - 68.0

3. Return the first item of a list l if it contains an even number of elements, Return the last item of a list l if it contains an odd number of elements
  - ``` defun get-first-if-even-length (list)
        (if (evenp (length list))
        (first list)
        (first (last list)))) ```
  - Example:-
    - (GET-FIRST-IF-EVEN-LENGTH ‘(a b c d))
    - A
    - (GET-FIRST-IF-EVEN-LENGTH ‘(a b c d e))
    - E


4. Create a list containing only c instances of m
  - ```(defun create-list (m c) (+ (make-list c))```

