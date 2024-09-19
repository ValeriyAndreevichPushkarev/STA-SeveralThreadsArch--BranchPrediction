# Several Threads Arch - Branch predictions

## Branching prediction

Most terrifying part of the architecture.
Well, basically you can work without branching prediction at all. (Well-knows paradox)

Just mention all possible execution pathes.
Minuses - more memory and cache bandwidth consumption.
Pluses - 100% hit accuracy. And its very easy in term of logic and consumes nothing (you know that your 64b addition costs only 0.0001 W of 20W)?

Nowadays all your Heavy computation core can be placed in cache (and you can make your instruction cache down to 256 M) (with all possible branches).
How to decrease power consumption - increase cache page size. (you spend more power with searching address in tree than to preform arithmetic/logical/flow control operation)

Or simply map regions directly to some Cache with additional instructions.

(TODO: describe branch dest address translation without searching in tree/page list)
