# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Deciphering C++ Coroutines Part 2 - Mastering Asynchronous Control Flow - Andreas Weis - CppCon 2024
 - [https://www.youtube.com/watch?v=qfKFfQSxvA8](https://www.youtube.com/watch?v=qfKFfQSxvA8)
 - RSS feed: $source
 - date published: 2025-03-05T15:07:09+00:00

https://cppcon.org​
---

Deciphering C++ Coroutines Part 2 - Mastering Asynchronous Control Flow - Andreas Weis - CppCon 2024
---

One of the most powerful applications of coroutines is in the context of asynchronous operations, where their use allows for significant simplifactions of application code. Unfortunately, building an asynchronous library interface to enable such benefits for applications is not exactly straightforward in C++.

In this talk we will explore the essentials of managing asynchronous control flow with coroutines. We will discover how to reconstruct the call stack of nested asynchronous calls and thus bridge a significant gap between C++'s stackless coroutines and the stackful coroutines from other languages. We will learn how to build a mechanism similar to the async/await from languages like Python or Javascript for our own libraries. And we will explore how we can perform arbitrary manipulations of the call stack in such an environment to unleash the full pow

