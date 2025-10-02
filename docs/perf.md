# Performance and Systems!

```
This page is currently under development!

Expect for some major changes to occur within the new few hours and days!
```

Junior year, I took performance engineering (6.106) and it was one of the coolest classes I've ever taken! Since then, I've fallen head-on in the performance engineering and systems hole. 

## Experiences

???+ note "Compilers @ MIT"

    I started working on sparse tensor compiler (Finch)! I worked on adding some features to the compiler such as new algorithms and internal functions.

    I'm now working on building infrastructure to build high-performance domain-specific languages in Python!


???+ note "Artephi Computing Inc."

    I worked on developing performant quantum-inspired algorithms in Jax! In total, I managed to get a 10x speedup on some of our benchmarks!


## Projects

???+ note "Finch.jl"

    I added some features like a sparse depth-first search and degree centrality and added features like argmin, argmax, and dropdims.

    ![Finch Logo](https://github.com/finch-tensor/Finch.jl/blob/main/docs/src/assets/icon.png?raw=true)

???+ note "FS"
    
    For my distributed final project, we did an exploration of different file systems, with our final file system with RDMA support (using Soft iWARP). Below is a picture of our setup -- using Ethernet, we could simulate RDMA so we were able to create an efficient file system between the desktop and the laptop shown!

    ![RDMA Setup](imgs/rdma_setup.png)

???+ note "TinySAM"
    
    For my TinyML final project, we benchmarked many segment-any models (SAM) and created quantized SAM models
