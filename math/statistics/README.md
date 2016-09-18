# Statistics
The logic of Uncertainty

## History
Fermat and Pascal (1650's)
    - Began analyzing games of chance.

## [Glossary](http://www.stat.berkeley.edu/~stark/SticiGui/Text/gloss.htm)
Sample Space: The set of all possible outcomes of an experiment
```
S{A,...}
```

## Bibliography
[Statistics 110: Probability  and Counting](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo):
Lectures from Harvar'd Statistics 110 (introductory) course.

## Key Concepts
### Quantifying Uncertainty:

### Naive Definition
Assuming that:

1. All events (outcomes) are equally likely to occur
2. The Sample Space is finite.

Then:
```
P(A):
"""The probability of Event A"""
```

Is the number of Events (A), divided by the number of possible events (S)

```
P(A) = A.count() / S.count()
```


### Counting
#### The Multiplication Rule:
1. Given an experiment with n_1 possible results,
and a subsequent experiment with n_2 possible results for each result in n_1
for each n_r results for the r^th experiment
there are
```
n_1 * n_2 * ... * n_r
```
possible results, for the sequence of experiments.
