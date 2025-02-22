# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Reverse Iterations -- Coral Kashri
 - [https://isocpp.org//blog/2025/02/reverse-iterations-coral-kashri](https://isocpp.org//blog/2025/02/reverse-iterations-coral-kashri)
 - RSS feed: $source
 - date published: 2025-02-21T22:42:16+00:00

<p>
	<img alt="c-senioreas-v9.png" src="https://isocpp.org/files/img/c-senioreas-v9.png" style="width: 300px; margin: 10px; float: right;" />Sometimes, we all need a way to iterate over a container in the opposite direction. There are several ways to reverse-iterate a container, and in this article, we&rsquo;ll explore them.</p>
<blockquote>
	<h3>
		<a href="https://cppsenioreas.wordpress.com/2025/01/01/reverse-iterations-cpp/">Reverse Iterations</a></h3>
	<p>
		by Coral Kashri</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	Probably the simplest way, taken from C is to iterate using an index location:</blockquote>
<blockquote>
	<div>
		<code>for</code> <code>(</code><code>int64_t</code> <code>index = ssize(container); index &gt;= 0; --index) &#123;</code></div>
	<div>
		&nbsp;&nbsp;&nbsp;&nbsp;<code>// do something with `container[index]`</code></div>
	<div>
		<code>&#125;</code></div>
</blockquote>
<blockquote>
	<div>
		This way is highly not recommended as it might lead

