# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## In C++, failure to meet the requirements does not always mean that you fail -- Raymond Chen
 - [https://isocpp.org//blog/2025/02/in-cpp-failure-to-meet-the-requirements-does-not-always-mean-that-you-fail](https://isocpp.org//blog/2025/02/in-cpp-failure-to-meet-the-requirements-does-not-always-mean-that-you-fail)
 - RSS feed: $source
 - date published: 2025-02-13T22:27:50+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />When tasked with diagnosing why a pointer passed through a pipeline emerged offset from its original value, I discovered an interesting culprit: the misuse of a wrapper function around <code>SubmitWork</code>. While the wrapper aimed to simplify usage by allowing both raw pointers and references to standard layout types, it inadvertently caused ambiguous overload resolution, leading to incorrect behavior. This analysis explores how the issue arose, the debugging process, and improvements to ensure robust and predictable pointer handling in similar scenarios.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20241227-00/?p=110681">In C++, failure to meet the requirements does not always mean that you fail if you don&rsquo;t meet the requirements</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	Fr

