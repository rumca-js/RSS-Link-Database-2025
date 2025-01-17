# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## User API & C++ Implementation of a Multi Producer, Multi Consumer, Lock Free, Atomic Queue - CppCon
 - [https://www.youtube.com/watch?v=bjz_bMNNWRk](https://www.youtube.com/watch?v=bjz_bMNNWRk)
 - RSS feed: $source
 - date published: 2025-01-16T15:07:07+00:00

https://cppcon.org​
---

User API and C++ Implementation of a Multi Producer, Multi Consumer, Lock Free, Atomic Queue - Erez Strauss - CppCon 2024
---

This presentation introduces a multi-producer, multi-consumer, lock-free queue with unique characteristics. We will cover the C++17 implementation and the std::atomic features required for this queue based on the CPU atomic instructions and discuss the queue's portability across various CPU architectures, beyond just X86_64 and runtime environments.

Efficient message queue-based communication between threads is crucial for optimal performance in multi-threaded applications. Queues are fundamental data structures that interact with various aspects of the application environment, including schedulers, memory allocation systems, and CPU hardware architectures.

Many use cases such as trading platforms, games, audio processing and other fields have strict latency and scaling requirements and this queue implementation has proved to reduce

