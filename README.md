```racket
(for-each
  (lambda (lang) (printf "I like ~a\n" lang))
  (list "C" "Go" "OCaml"))
(for-each
  (lambda (lang) (printf "I am proficient in ~a\n" lang))
  (list "C++" "Dart" "JavaScript" "Ruby" "Python"))
```
