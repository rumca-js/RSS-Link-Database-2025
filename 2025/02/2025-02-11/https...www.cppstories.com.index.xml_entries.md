# Source:C++ Stories, URL:https://www.cppstories.com/index.xml, language:en-us

## Adjacency Matrix and std::mdspan, C++23
 - [https://www.cppstories.com/2025/cpp23_mdspan_adj](https://www.cppstories.com/2025/cpp23_mdspan_adj)
 - RSS feed: $source
 - date published: 2025-02-11T00:00:00+00:00

<p>In graph theory, an <strong>adjacency matrix</strong> is a square matrix used to represent a finite (and usually dense) graph. The elements of the matrix indicate whether pairs of vertices are adjacent or not, and in weighted graphs, they store the edge weights.</p>
<p>In many beginner-level tutorials, adjacency matrices are implemented using <strong>vector of vectors</strong> (nested dynamic arrays), but this approach has inefficiencies due to multiple memory allocations. C++23 introduces <code>std::mdspan</code>, which provides a more efficient way to handle multi-dimensional data structures without the overhead of nested containers.</p>
<p>In this blog post we&rsquo;ll explore various implementations of an adjacency matrix, starting with a basic approach and progressively improving it using <code>std::mdspan</code>.</p>
<h2 id="starting-slow">
Starting slow 
  
<a class="hash-link" href="#starting-slow" aria-hidden="true">
<svg class="fill-current o-60 hover-accent-color-light"

