# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Vectorizing Computational Fluid Dynamics (CFD) Code in C++ Using std::simd - Olaf Krzikalla - CppCon
 - [https://www.youtube.com/watch?v=r7T6JifMBkU](https://www.youtube.com/watch?v=r7T6JifMBkU)
 - RSS feed: $source
 - date published: 2025-01-07T15:07:06+00:00

https://cppcon.org​
---

Vectorizing a Computational Fluid Dynamics (CFD) Code in C++ Using std::simd Supplemented by (Almost) Transparent Loading and Storing - Olaf Krzikalla - CppCon 2024
---

Computational Fluid Dynamics (CFD) codes are ubiquitous in high performance computing. Their computational demands require the use of all levels of parallelism provided by the hardware. This includes the SIMD units of today's processors, which provide one level of data parallelism. With `std::simd`, it becomes possible to address these units directly from C++.

The talk reports on our work on the vectorization of a CFD code. The focus will be primarily on the way we have expressed vectorization using `std::experimental::simd` and less on the achieved performance gains. In this context, we have developed a library that complements `std::simd`. The goal of this library is to make loading and saving `std::simd` variables syntactically equivalent to loading and saving their scalar counterparts. L

