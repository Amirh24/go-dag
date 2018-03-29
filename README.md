# phantom
BlockDAG algorithm's Go language simulation for paper "PHANTOM: A Scalable BlockDAG protocol".

Here is the [paper link on International Association for Cryptologic Research (IACR)](https://eprint.iacr.org/2018/104.pdf) by **Yonatan Sompolinsky** and **Aviv Zohar** in Feb. 2018.

They have setup a start-up company to develop BlockDAG since Q4 2017, their website: [https://www.daglabs.com]. And there's an official DAGlabs slack channel: [https://daglabs.slack.com].

---

# How to build

### build the example on the paper P.7 Fig.3, for algorithm 1: Selection of a blue set.

```bash
$ go build blueSetSelection.go 
```

### build the example on the paper P.16 Fig.4, for algorithm 1: Selection of a blue set.

```bash
$ go build figure4.go
```

### build the example on P.3 Fig.2, P.8 'C. Step #2: ordering blocks', for algorithm 2: Ordering of the DAG.

```bash
$ go build figure2.go
```


