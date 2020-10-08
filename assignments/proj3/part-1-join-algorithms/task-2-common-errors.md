# Task 2 Common Errors

### Index out of bounds error while partitioning

Hash codes can be negative. Make sure you handle that case. The hash codes can also be larger than the number of partitions, so make sure you handle that too. We recommend you look at [SimpleHashJoin'](https://github.com/berkeley-cs186/$sem$-moocbase/blob/master/src/main/java/edu/berkeley/cs186/database/query/SimpleHashJoin.java#L53-L56)s implementation to make sure you partition correctly with hash codes.

### Reached the max number of passes cap

This means that you're doing recursive partitioning infinitely. The most likely cause of this is partitioning using the the same hash function every single time. Make sure to use the `hashFunc` object we provide, which should be a different hash function for each pass.

### Code running forever/recursion depth limit exceeded/java.lang.OutOfMemoryError

Make sure every time you make a recursive call to run that you increment the pass number.

### AssertionError: Expected: 1674 Actual: 91

Make sure when you recursively call run that you add all of the resulting records to your output. Additionally make sure that whenever you call buildAndProbe that you also add those records to your output.
