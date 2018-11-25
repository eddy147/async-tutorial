# async-tutorial
The code for the udacy's async tutorial is out-of-date. I keep it up-to-date with lein ancient

# I got errors with my previous .lein/profiles.clj. With this one it works:
# See also in the root.

```
{:user {:dependencies [[org.clojure/clojure "1.9.0"]
                       [org.clojure/tools.namespace "0.2.11"]
                       [org.clojure/tools.nrepl "0.2.13"]
                       [cljfmt "0.6.1"]]
        :plugins [[lein-ancient "0.6.15"]
                  [lein-cljfmt "0.6.1"]
                  [lein-clojars "0.9.1"]
                  [lein-kibit "0.1.6"]]}}
```
