# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## Solving the Puzzle of Trying to Put an Object into a std::optional -- Raymond Chen
 - [https://isocpp.org//blog/2025/01/solving-the-puzzle-of-trying-to-put-an-object-into-a-stdoptional-raymond-ch](https://isocpp.org//blog/2025/01/solving-the-puzzle-of-trying-to-put-an-object-into-a-stdoptional-raymond-ch)
 - RSS feed: $source
 - date published: 2025-01-10T18:07:18+00:00

<p>
	<img alt="RaymondChen_5in-150x150.jpg" src="https://isocpp.org/files/img/RaymondChen_5in-150x150.jpg" style="width: 150px; margin: 10px; float: right;" />Last time,&nbsp;<a href="https://devblogs.microsoft.com/oldnewthing/20241113-00/?p=110516" title="The puzzle of trying to put an object into a std::optional">we investigated the puzzle of why the compiler wouldn&rsquo;t let us put an object into a&nbsp;<code>std::optional</code></a>. It came down to the fact that the object is not copy-constructible, move-constructible, copy-assignable, or move-assignable, so there&rsquo;s no way to put the temporary object into the&nbsp;<code>std::optional</code>.</p>
<blockquote>
	<h3>
		<a href="https://devblogs.microsoft.com/oldnewthing/20241114-00/?p=110521">Solving the Puzzle of Trying to Put an Object into a std::optional</a></h3>
	<p>
		by Raymond Chen</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		What we have to do is&nbsp;<em>construct</em>&nbsp;the object in place 

