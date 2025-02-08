# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Making Hard C++ Tests Easy: A Case Study From the Motion Planning Domain - Chip Hogg - CppCon 2024
 - [https://www.youtube.com/watch?v=8D7vpR9WCtw](https://www.youtube.com/watch?v=8D7vpR9WCtw)
 - RSS feed: $source
 - date published: 2025-02-07T15:07:07+00:00

https://cppcon.org​
---

Making Hard C++ Tests Easy: A Case Study From the Motion Planning Domain - Chip Hogg - CppCon 2024
---

If you've ever struggled to write tests for domain-specific functions with complicated, real-world inputs, this talk is for you!  We'll use the Motion Planning component in a self-driving stack as a case study (although you won't need any prior Motion Planning experience to follow the talk).  In building objects for our test inputs, we faced the classic dilemma.  If we make the objects simple, they're hardly meaningful, and the tests amount to little more than smoke tests.  If we try constructing more realistic objects, it takes tremendous amounts of boilerplate code (which obscures what is actually being tested) --- and what's worse, these finicky construction methods go stale and break easily as implementation details evolve.

There is a better way!  To find it, we take our inspiration from a (paraphrased) Kent Beck quote: "First, make the test easy.  (Wa

