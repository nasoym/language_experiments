# clojure test


## use openend leiningen repl session
  * lein repl
  > (-main)
  > app.core :reload
  > (-main)


  > (doc require)


  > (require '[clojure.test :refer [run-tests]])
  > (require 'app.test.core)
  > (in-ns 'app.test.core)
  > (run-tests)

  > (use '[clojure.test :refer [run-tests]])
  > (use 'app.test.core)
  > (run-tests 'app.test.core)
  > (use 'app.test.core :reload-all)
  > (run-tests 'app.test.core)

  > (in-ns 'app.core)
  > (require 'app.test.core :reload-all)


