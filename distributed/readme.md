* [NCCL 개념 및 Ring 기반 집합 통신 최적화](https://computing-jhson.tistory.com/81)



* [Distributed Training with PyTorch: complete tutorial with cloud infrastructure and code](https://www.youtube.com/watch?v=toUSzwR0EV8)

  ```
A complete tutorial on how to train a model on multiple GPUs or multiple servers.
I first describe the difference between Data Parallelism and Model Parallelism. Later, I explain the concept of gradient accumulation (including all the maths behind it). Then, we get to the practical tutorial: first we create a cluster on Paperspace with two servers (each having two GPUs) and then training a model in a distributed manner on the cluster.
We will explore collective communication primitives: Broadcast, Reduce and All-Reduce and the algorithm behind them.
I also provide a template on how to integrate DistributedDataParallel in your existing training loop.
In the last part of the video we review advanced topics, like bucketing and computation-communication overlap during backpropagation.

Code: https://github.com/hkproj/pytorch-tra...
PDF slides: https://github.com/hkproj/pytorch-tra...

Chapters
00:00:00 - Introduction
00:02:43 - What is distributed training?
00:04:44 - Data Parallelism vs Model Parallelism
00:06:25 - Gradient accumulation
00:19:38 - Distributed Data Parallel
00:26:24 - Collective Communication Primitives
00:28:39 - Broadcast operator
00:30:28 - Reduce operator
00:32:39 - All-Reduce
00:33:20 - Failover
00:36:14 - Creating the cluster (Paperspace)
00:49:00 - Distributed Training with TorchRun
00:54:57 - LOCAL RANK vs GLOBAL RANK
00:56:05 - Code walkthrough
01:06:47 - No_Sync context
01:08:48 - Computation-Communication overlap
01:10:50 - Bucketing
01:12:11 - Conclusion
  ```
