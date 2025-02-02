# Source:Standard C++ | News, URL:https://isocpp.org/blog/rss/category/news, language:en

## When a default-initializable type actually isn't -- Kaashif Hymabaccus
 - [https://isocpp.org//blog/2025/02/when-a-default-initializable-type-actually-isnt-kaashif-hymabaccus](https://isocpp.org//blog/2025/02/when-a-default-initializable-type-actually-isnt-kaashif-hymabaccus)
 - RSS feed: $source
 - date published: 2025-02-01T21:50:05+00:00

<p>
	<img alt="Depositphotos_170038592_S.jpg" src="https://isocpp.org/files/img/Depositphotos_170038592_S.jpg" style="width: 200px; margin: 10px; float: right; height: 200px;" />The C++ proposal for <code>indirect</code> and <code>polymorphic</code> introduces two new class templates designed to simplify working with dynamically allocated types while retaining value semantics. This post dives into a curious case with <code>polymorphic</code>, exploring why <code>std::default_initializable&lt;polymorphic&lt;T&gt;&gt;</code> evaluates to <code>true</code>&mdash;even when <code>polymorphic&lt;T&gt;</code> can&#39;t actually be default-initialized in practice.</p>
<blockquote>
	<h3>
		<a href="https://kaashif.co.uk/2025/01/18/when-a-default-initializable-type-actually-isn-t/">When a default-initializable type actually isn&#39;t</a></h3>
	<p>
		by Kaashif Hymabaccus</p>
</blockquote>
<p>
	From the article:</p>
<blockquote>
	<p>
		I was looking at a proposal for adding value-semantic dynam

