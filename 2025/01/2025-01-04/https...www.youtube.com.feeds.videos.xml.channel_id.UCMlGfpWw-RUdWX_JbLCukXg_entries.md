# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Async Stacks: Making Senders and Coroutines Debuggable - Ian Petersen & Jessica Wong - CppCon 2024
 - [https://www.youtube.com/watch?v=nHy2cA9ZDbw](https://www.youtube.com/watch?v=nHy2cA9ZDbw)
 - RSS feed: $source
 - date published: 2025-01-04T15:01:39+00:00

https://cppcon.org​
---

Async Stacks: Making Senders and Coroutines Debuggable - Ian Petersen & Jessica Wong - CppCon 2024
---

Debugging asynchronous code is hard; partially because the stack traces that engineers are used to seeing do not provide enough insight to easily determine what went wrong. Often, engineers debug these async bugs by receiving a hint of the issue from the stack trace, going to the source code to read the problematic code, and making educated guesses about the async behavior that could have led to the issue.

But we can do better. In this talk, we introduce async stack trace support, a benefit that becomes possible when adopting coroutines and senders for your asynchronous work. With async stack traces and coroutines, engineers will have visibility into the async call stack leading up to the issue. This was originally developed at Meta in Folly, and we’d like to share this capability so that this could be incorporated into other C++ coroutine libraries and pr

