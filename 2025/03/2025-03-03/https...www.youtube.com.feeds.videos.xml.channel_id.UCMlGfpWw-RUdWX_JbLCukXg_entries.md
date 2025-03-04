# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Modern C++ Error Handling - Phil Nash - CppCon 2024
 - [https://www.youtube.com/watch?v=n1sJtsjbkKo](https://www.youtube.com/watch?v=n1sJtsjbkKo)
 - RSS feed: $source
 - date published: 2025-03-03T15:07:13+00:00

https://cppcon.org​
---

Modern C++ Error Handling - Phil Nash - CppCon 2024
---

We’ve had exceptions in C++ since before the first standard. C++17 introduced std::optional and C++23 std::expected (along with the so-called Monadic Operations for both types).

What should we use and when?

Meanwhile we still have older approaches, such as boolean or error code returns, as well as global or thread local error status or pointer or reference arguments.

Do these still have a place?

And where does assert fit in? And the (hopefully) upcoming contracts?

Perhaps more importantly, once we’ve examined all the trade-offs, can we defer any of those decisions to when we are best positioned to commit to them?

Erroneous conditions can have a big impact on your code’s safety and security, so error handling shouldn’t just be left to the “exercise left for the reader” in the books we used to read. Let’s get this all straight.
---

Slides: https://github.com/CppCon/CppCon2024/blob/main/Presentation

