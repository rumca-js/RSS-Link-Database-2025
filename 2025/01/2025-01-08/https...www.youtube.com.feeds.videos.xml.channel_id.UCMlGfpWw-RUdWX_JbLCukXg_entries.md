# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## How to Use the Sender/Receiver Framework in C++ to Create a Simple HTTP Server - Dietmar Kühl - 2024
 - [https://www.youtube.com/watch?v=Nnwanj5Ocrw](https://www.youtube.com/watch?v=Nnwanj5Ocrw)
 - RSS feed: $source
 - date published: 2025-01-08T15:07:05+00:00

https://cppcon.org​
---

How to Use the Sender/Receiver Framework in C++ to Create a Simple HTTP Server - Dietmar Kühl - CppCon 2024
---

The sender/receiver framework for asynchronous operations in C++ is well on its way towards standardization in C++26. Previously, the theoretical background and implementation of the framework was shown but there wasn't much detail on how an application using sender/receiver would look like.

This presentation shows how to create a simple HTTP server using the sender/receiver framework with matching networking senders together with a coroutine task and and async scope. The code is created live using fundamental facilities. The goal is to demonstrate that the use of an asynchronous framework doesn't necessarily lead to excessive complexity when using C++'s facilities effectively. The resulting server could be embedded into any application, e.g., to inspect its state or change configurations. The takeaway is that it is reasonably straight forward to 

