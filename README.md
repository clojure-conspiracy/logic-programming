# Logic Programming in Clojure

Powered by core.logic:

 * core.logic https://github.com/clojure/core.logic/wiki

## Challenge

The coundown numbers game:

 * Any number of integer choices may be given and any integer target.
 * It will only find exact answers, if there is no solution it will return nil rather than the closest calculation.

Example:

```clojure
(play 674 [5 74 2 3 9])
=> (+ 5 (+ 3 (* 74 9)))
```
