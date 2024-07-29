# Myth: ML Synthesizer

The original [myth](https://github.com/silky/myth) repo depends on some order version of `Core` library (before 2018), but arm based macbooks cannot go back to this older version of ocaml. Thanks to @amiltner, this edited version can run on the latest version of `Core` library. 

## Requirements
Tested with `opam 2.1.6`, `ocaml 4.14.0`

## Run
```
dune exec myth tests/pldi-2015-benchmarks/list_nth.ml
```
