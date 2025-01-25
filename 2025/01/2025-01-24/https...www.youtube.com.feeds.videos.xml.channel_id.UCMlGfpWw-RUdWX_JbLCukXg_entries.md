# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## How to Design a Slimmer Vector of Variants in C++ - Christopher Fretz - CppCon 2024
 - [https://www.youtube.com/watch?v=VDoyQyMXdDU](https://www.youtube.com/watch?v=VDoyQyMXdDU)
 - RSS feed: $source
 - date published: 2025-01-24T15:07:12+00:00

https://cppcon.org​
---

How to Design a Slimmer Vector of Variants in C++ - Christopher Fretz - CppCon 2024
---

Heterogeneous containers ("vectors of variants") are an extremely flexible and useful abstraction across many data domains, but std::vector＜std::variant＜...＞＞ can exhibit extremely bad memory characteristics for mixed types of disparate size, especially if the largest types are relatively uncommon in practice. Variants always have to be at least as large as their largest contained type, and vector implicitly requires all of its members to be the same size, leading to significant bloat in such cases. Motivated by real-world use-cases, this talk explores the design of a bit-packed replacement data structure that can achieve massive improvements in memory usage, and the impacts that these optimizations have on its API. 
---

Slides: https://github.com/CppCon/CppCon2024/blob/main/Presentations/Designing_a_Slimmer_Vector_of_Variants.pdf

Sponsored by JetBrains: https://www.jet

