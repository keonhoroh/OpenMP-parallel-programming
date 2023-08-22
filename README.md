# OpenMP Parallel Programming Project

Expressed loop-level parallelism through OpenMP pragmas.

The project consists of four OpenMP versions:
1. spell_t2_singleloop.c : A version that uses exactly 2 cores or threads and exploits parallelism in only a single loop level.
2. spell_t2_fastest.c: A version that uses exactly 2 cores or thread and runs as fast as possible.
3. spell_t4_singleloop.c : A version that uses exactly 4 cores or threads and exploits parallelism in only a single loop level.
4. spell_t4_fastest.c: A version that uses exactly 4 cores or thread and runs as fast as possible.

Note that all four versions could be identical.
