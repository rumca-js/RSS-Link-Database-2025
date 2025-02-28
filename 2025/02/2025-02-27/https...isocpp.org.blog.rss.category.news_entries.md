# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## C++26: A Placeholder with No Name -- Sandor Dargo
 - [https://isocpp.org//blog/2025/02/cpp26-a-placeholder-with-no-name-sandor-dargo](https://isocpp.org//blog/2025/02/cpp26-a-placeholder-with-no-name-sandor-dargo)
 - RSS feed: $source
 - date published: 2025-02-27T22:51:57+00:00

<p>
	<img alt="SANDOR_DARGO_ROUND.JPG" src="https://isocpp.org/files/img/SANDOR_DARGO_ROUND.JPG" style="width: 250px; margin: 10px; float: right; height: 250px;" />In this post, we are going to discuss a core language feature proposed by Corentin Jabot and Micheal Park in P2169R4. With the new standard we get a cool unnamed placeholder.</p>
<blockquote>
	<h3>
		<a href="https://www.sandordargo.com/blog/2025/01/08/cpp26-unnamed-placeholders">C++26: A Placeholder with No Name</a></h3>
	<p>
		by Sandor Dargo</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	By convention, when we have a variable whose value we don&rsquo;t want to use or care about, we often name it&nbsp;<code>_</code>. The problem is that with higher warning levels (<code>-Wunused-variable</code>), our compilation might fail because&nbsp;<code>_</code>&nbsp;is unused.</blockquote>
<blockquote>
	<pre>
int foo() {&#10;return 42;&#10;}&#10;&#10;auto _ = foo();&#10;/* error: unused variable &#39;_&#39; [-Werror,-Wu

