# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Inside STL: Waiting for a std::atomic to change, part 1 -- Raymond Chen
 - [https://isocpp.org//blog/2025/03/inside-stl-waiting-for-a-stdatomicstdshared-ptrt-to-change-part-1-raymond-c](https://isocpp.org//blog/2025/03/inside-stl-waiting-for-a-stdatomicstdshared-ptrt-to-change-part-1-raymond-c)
 - RSS feed: $source
 - date published: 2025-03-03T19:49:56+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />When using std::atomic&lt;std::shared_ptr&lt;T&gt;&gt;, the C++ standard defines a "change" as a modification to either the stored pointer or the control block pointer. However, since atomic wait mechanisms typically track only a single memory address, the Microsoft implementation handles this limitation by using a timeout-based polling strategy to detect changes in the control block.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20250108-00/?p=110732">Inside STL: Waiting for a std::atomic&lt;std::shared_ptr&lt;T&gt;&gt; to change, part 1</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Like other&nbsp;<code>std::atomic</code>&nbsp;specializations,&nbsp;<code>std::atomic&lt;<wbr />std::shared_ptr&lt;T&gt;&gt;</code>&nbsp;supports the&nbsp;<code>wait<

