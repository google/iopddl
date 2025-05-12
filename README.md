Supplemental materials (i.e., utilities and benchmarks) for [**The ASPLOS 2025 / EuroSys 2025 Contest on Intra-Operator Parallelism for Distributed Deep Learning**](https://github.com/asplos-contest/2025/blob/main/IOPDDL.md).

## Example Usage

```
$ git clone --recursive https://github.com/google/iopddl.git
$ mkdir iopddl/build && cd iopddl/build && cmake .. && make
$ ./iopddl example.json 10
```

## Decompressing Benchmarks

In order to try out the contest problems, you'll first need to run this command one time:

```
$ gzip -d benchmarks/*
```

More details about these benchmarks:

<img src="iopddl-benchmark-details.png">
