# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Improving Code Safety in C++26: Managers and Dangling References
 - [https://www.cppstories.com/2025/cpp26-safety-temp](https://www.cppstories.com/2025/cpp26-safety-temp)
 - RSS feed: $source
 - date published: 2025-01-20T00:00:00+00:00

<p>In this blog post, we’ll explore ways to improve the safety of a simple configuration manager. We&rsquo;ll handle common pitfalls like dangling references and excessive stack usage. Additionally, we&rsquo;ll see how C++26 helps enforce safer coding practices with stricter diagnostics and improved handling of large objects.</p>
<p>Let’s go.</p>
<h2 id="step-1-the-buggy-implementation">
Step 1: The Buggy Implementation 
  
<a class="hash-link" href="#step-1-the-buggy-implementation" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light" height="24" viewBox="0 0 24 24" width="22" xmlns="http://www.w3.org/2000/svg" aria-hidden="true"><path d="M0 0h24v24H0z" fill="none"></path><path d="M3.9 12c0-1.71 1.39-3.1 3.1-3.1h4V7H7c-2.76.0-5 2.24-5 5s2.24 5 5 5h4v-1.9H7c-1.71.0-3.1-1.39-3.1-3.1zM8 13h8v-2H8v2zm9-6h-4v1.9h4c1.71.0 3.1 1.39 3.1 3.1s-1.39 3.1-3.1 3.1h-4V17h4c2.76.0 5-2.24 5-5s-2.24-5-5-5z"></path></svg>
    </a>&nbsp;
    
</h2>

<p>Below is a simple example o

