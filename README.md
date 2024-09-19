# Several Threads Arch - Branch predictions

## Branching prediction

Most terrifying part of the architecture.
Well, basically you can work without branching prediction at all. (Well-knows paradox)

Just mention all possible pathes.
Minuses - more memory and cache bandwidth consumption.
Pluses - 100% hit accuracy. And its very easy in term of logic and consumes nothing (you know that your 64b addition costs only 0.0001 W of 20W)?

Nowadays all your Heavy computation core can be placed in L3 cache (down to 256 M) (with all possible branches).
