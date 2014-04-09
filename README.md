# logic-prog

A solver for the countdown numbers game written using core.logic

Usage

```clojure
(play 674 [5 74 2 3 9])
=> (+ 5 (+ 3 (* 74 9)))
```clojure
Any number of integer choices may be given and any integer target.

It will only find exact answers, if there is no solution it will return nil rather than the closest calculation.