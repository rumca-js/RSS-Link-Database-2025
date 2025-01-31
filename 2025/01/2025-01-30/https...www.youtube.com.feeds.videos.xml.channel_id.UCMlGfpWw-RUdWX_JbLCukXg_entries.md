# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Build Safer Modern C++ Application: Mix Assertion, Logging, Unit Testing and Fuzzing with ZeroErr
 - [https://www.youtube.com/watch?v=otSPZyXqY_M](https://www.youtube.com/watch?v=otSPZyXqY_M)
 - RSS feed: $source
 - date published: 2025-01-30T15:07:05+00:00

https://cppcon.org​
---

Build Safer Modern C++ Application: Mix Assertion, Logging, Unit Testing and Fuzzing with ZeroErr - Xiaofan Sun - CppCon 2024
---

Unit testing is a crucial practice for ensuring software safety. However, boundary cases, particularly those involving error handling and failure-tolerant logic, can be challenging to test in real-world applications. When writing test cases, the caller side of a target function may lack the necessary information to determine why an error occurred. Additionally, existing unit testing frameworks often cannot identify which path is exercised when multiple paths can produce similar outputs. These challenges are also present during fuzzing.

This talk introduces a lightweight, header-only C++11 library designed to address these issues. By including a single header file, users gain access to an integrated framework that combines assertion, logging, unit testing, and fuzzing, offering a more cohesive solution than using separate framewor

