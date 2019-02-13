## 1.

| Run | 1 | 2 | 3 | 5 |
| -- | -- | -- | -- | -- |
Q | 1 | 2 | 4 | 8 | 15 |
Acc | 1 | 3 | 7 | 15 | 30 |

It need to be swapped in 5 times.

## 2.

E3 = T0/8 + T1/8 + T2/4 + T3/2

A: 50/8 + 150/8 + 300/4 + 85/2 = 142,5
B: 300/8 + 150/8 + 85/4 + 50/2 = 102,5

The scheduler will take process B first because it has a lower estimated time to run.

## 3.

A CPU-bound process needs a lot of quanta to finish but it has a low priority

A I/O-bound process needs to wait for a user input (when a user for example click the process needs to run immediately)
it needs a low amount of quanta but must have a high priority.

## 4.

∑ Ci/Pi ≤ 1

(35 / 50) + (20 / 100) + (10 / 200) + ($x$ / 250) ≤ 1
0,7 + 0,2 + 0,05 + ($x$ / 250) ≤ 1
0,95 + ($x$ / 250) ≤ 1    | - 0,95 | * 250
$x$ ≤ 12,5

The largest value of $x$ is 12,5.
