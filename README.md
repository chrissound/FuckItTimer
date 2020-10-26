```
import Fuckit

start' <- start
timerc start' "begin"
print "hello"
timerc start' "after printing hello"
benchmark
timerc start' "end"
end <- getVals start'
forM_ (timert end) putStrLn
```
