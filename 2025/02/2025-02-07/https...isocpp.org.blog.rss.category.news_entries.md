# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Inside STL: The atomic shared_ptr -- Raymond Chen
 - [https://isocpp.org//blog/2025/02/inside-stl-the-atomic-shared-ptr-raymond-chen](https://isocpp.org//blog/2025/02/inside-stl-the-atomic-shared-ptr-raymond-chen)
 - RSS feed: $source
 - date published: 2025-02-07T22:17:26+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://devblogs.microsoft.com/oldnewthing/wp-content/uploads/sites/38/2019/02/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />The C++20 standard introduced a specialization of&nbsp;<code>std::<wbr />atomic</code>&nbsp;for shared pointers:&nbsp;<code>std::<wbr />atomic&lt;<wbr />shared_ptr&lt;<wbr />T&gt;&gt;</code>. How does it work?</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20241219-00/?p=110663">Inside STL: The atomic shared_ptr</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		Recall that a normal&nbsp;<code>shared_ptr</code>&nbsp;consists of two pointers: A stored pointer that the&nbsp;<code>shared_ptr</code>&nbsp;returns when you call&nbsp;<code>get()</code>&nbsp;and a pointer to a control block which holds the strong reference count, the weak reference count, and a pointer to the managed object.</p>
	<p>
		The atomi

## Standard C++ | News
 - [https://isocpp.org/blog/rss/category/news](https://isocpp.org/blog/rss/category/news)
 - RSS feed: $source
 - date published: 2025-02-07T00:19:46.518709+00:00

None

