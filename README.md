# cpu-vs-gpu-benchmark
The GPU was 37.4 times faster than the CPU for 5000 x 5000 matrix multiplication . Each output cell can be computed independently, so the GPU's thousands of cores work in parallel. Neural networks are mostly matrix multiplications, which is why GPUs matter for AI.

Notes:

A warm-up run and torch.cuda.synchronize() were used for fair timing, since GPU calls are asynchronous.

