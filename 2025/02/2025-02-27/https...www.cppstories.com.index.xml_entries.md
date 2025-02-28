# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Details of std::mdspan from C++23
 - [https://www.cppstories.com/2025/cpp23_mdspan](https://www.cppstories.com/2025/cpp23_mdspan)
 - RSS feed: $source
 - date published: 2025-02-27T00:00:00+00:00

<p>In this article, we&rsquo;ll see details of <code>std::mdspan,</code> a new view type tailored to multidimensional data. We&rsquo;ll go through type declaration, creation techniques, and options to customize the internal functionality.</p>
<h2 id="type-declaration">
Type declaration 
  
<a class="hash-link" href="#type-declaration" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>The type is declared in the following way:</p>
<div class="highlight"><pre tabindex="0" class="chroma"><code class="language-cpp" data-lang="cpp"><span class="line"><span class="c

