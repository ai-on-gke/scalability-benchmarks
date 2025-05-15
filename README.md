# Scalability Benchmarks

This repository is intended to host code and configuration files for various scalability benchmarks on Google Kubernetes Engine (GKE). We're just getting started, so the collection is small for now, but we plan to add more over time!



It uses [terraform](https://developer.hashicorp.com/terraform) for infrastructure setup and [ClusterLoader2](https://github.com/kubernetes/perf-tests/tree/master/clusterloader2) for running the benchmarks. 


Currently, the following benchmark is available:
- **Benchmarking a 65000-node GKE Cluster**: Evaluating performance for simulated mixed AI workloads on CPU-based clusters. Can be found in `65k-cpu-nodes-simulated-ai-benchmark.md`.


