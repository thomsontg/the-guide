# Concepts in Parallelism
## Parallelism, interactivity, events and GUIs

* Data parallelism, work stealing - rayon
* Data parallelism, non-work stealing - crossbeam
* Mutex
* Async
* Atomic
* Threads
* GPU
* (Sparsity)
* (Random Access and Monte Carlo (Gyro Dropout))
* (Branchless programming)
* (SIMD)
* (Sorting)
* Channels
* Events
* Key and Mouse events
* Event Loops
* (GUIs & egui)
* (Examine egui-winit-wgpu template)
* (Graph representations - pointers and indices)
* (Trees using indices)
* (Parallel work on graphs)

## (Specializations/Exercise - Pick items worth a total of 3 points or more, write a 10+ lines interpretation of each item)

* (1 - Data-oriented design - Entity component systems)
* (1 - Array of Structs, Structs of Arrays, Auto-Vectorization)
* (1 - Linearized octrees)
* (2 - Sorting kernels in divergent workloads - Wavefront path tracing)
* (4 - ORB-SLAM - design and a warning about trying to code it)
* (4 - Nanite)
* (1 - PyTorch - Data-Distributed-Parallelism)
* (1 - PyTorch - Model-Distributed-Parallelism)
* (2 - Shadertoy)
* (1 - Gyro Dropout - MLSys 2022)
* (1 - Hierarchical Frustum Culling)
* (2 - Flash Attention)
* (2 - Custom memory allocators)
* (2 - [JAX](https://jax.readthedocs.io/en/latest/notebooks/Common_Gotchas_in_JAX.html))

## (Exercise)

* Describe the base architecture of the egui-winit-wgpu template.
Expand on the template and program some things (needs suggestions)
using some of the primitives introduced in the module