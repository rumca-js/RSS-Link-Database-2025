# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Bridging the Gap: Writing Portable C++ Programs for CPU and GPU - Thomas Mejstrik - CppCon 2024
 - [https://www.youtube.com/watch?v=7zfROx6KWAI](https://www.youtube.com/watch?v=7zfROx6KWAI)
 - RSS feed: $source
 - date published: 2025-02-12T15:07:11+00:00

https://cppcon.org​
---

Bridging the Gap: Writing Portable C++ Programs for CPU and GPU - Thomas Mejstrik - CppCon 2024
---

This talk presents a series of effective patterns to address challenges arising when code is developed that shall operate seamlessly on both GPU (CUDA) and CPU environments.
This scenario is a common oversight among CUDA developers, given the substantial architectural differences between CPUs and GPUs.

The patterns presented cover a range of scenarios, from handling stray function calls, strategies for conditional compilation, exploiting constexpr functions, leveraging undefined behaviour, usage of CUDA specific macros, conditional instantiation of templates and managing compiler warnings and errors.

Key patterns include: "Host device everything", "Conditional function body", "Constexpr everything", "Disable the warnings", "Defensive Programming", "Conditional Host Device Template", and "Function dispatching".

We evaluate each pattern based on ease of use, 

