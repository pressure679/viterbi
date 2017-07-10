# viterbi

Viterbi is an implementation of the viterbi path finding algorithm
(written in go) used within the context of a trigram hidden markov model
(HMM). The transition probability is passed as a function into the viterbi
algorithm along with initial states and their associated initial
probabilities.

View the [docs](http://godoc.org/github.com/nyxtom/viterbi).

## Installation

```
$ go get github.com/nyxtom/viterbi
```

# Licence

MIT

# Pressure679 - github.com/pressure679/WikiPagerankDB/tools.go

My edit: I took inspiration from this (the Viterbi function and Markov_State type) in collaboration with google's HMM code from their codewalk, in honesty the code wasn't fit for me, but it added some much wanted clarification and thought of train in contrast to pseudocode and python.
My version though should probably end up with a mix between the viterbi method and the brill based pos tagger in collaboration with some NLP/documents algorithms.
