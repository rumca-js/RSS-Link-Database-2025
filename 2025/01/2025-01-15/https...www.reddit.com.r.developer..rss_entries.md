# Source:The home of developers., URL:https://www.reddit.com/r/developer/.rss, language:en

## Starting in a new company: help!
 - [https://www.reddit.com/r/developer/comments/1i24cki/starting_in_a_new_company_help](https://www.reddit.com/r/developer/comments/1i24cki/starting_in_a_new_company_help)
 - RSS feed: $source
 - date published: 2025-01-15T18:38:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi!<br/> I&#39;m just starting in a new company and I&#39;m working on a app that has a lot of legacy code... I got assigned to a task and looked at the code and I just froze. I honestly couldn&#39;t understand a thing. I didn&#39;t know what the entities were or how the logic worked. I tried looking around but there were so many things I couldn&#39;t understand and didn&#39;t even know what it was (yes, I&#39;ve asked for help but didn&#39;t get much out of it...).</p> <p>It&#39;s like they showed me the actual app for an hour and now they expect me to dive into the code and start to get it, but I just don&#39;t...<br/> Now I&#39;m wondering if this is totally normal, cause the other workers here seem to be just fine even when they only have been working here for a few months.</p> <p>How long does it usually take to get the hang of it? Cause I&#39;m kind of scared that I&#39;m not going to.... it just seems so hard. Am I the problem here?</p> </div>

## What is the correct way of handling canonical/non-indexed pages (.htaccess)?
 - [https://www.reddit.com/r/developer/comments/1i1w1yd/what_is_the_correct_way_of_handling](https://www.reddit.com/r/developer/comments/1i1w1yd/what_is_the_correct_way_of_handling)
 - RSS feed: $source
 - date published: 2025-01-15T12:12:22+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying with different .htaccess formats and nothing seems to work properly for search console, I always get the canonical error for the http-https-www-nonwww variants interfering with each other of my pages.<br/> Google should have figured this out by now...<br/> Since they cant wrap their head around these variants I have to tell it through a .htaccess file which no matter how is written always gets page indexing errors. Anybody has figured out the correct format yet?</p> <p>Mine:</p> <p><code>ErrorDocument 404</code> <a href="http://www.mywebsite.com/404.php"><code>http://www.mywebsite.com/404.php</code></a></p> <p><code>ErrorDocument 500</code> <a href="http://www.mywebsite.com/404.php"><code>http://www.mywebsite.com/404.php</code></a></p> <p><code>RewriteEngine On</code></p> <p><code># Redirect ww and non-www to www</code></p> <p><code>RewriteCond %{HTTP_HOST} ^(ww|)\.mywebsite\.com [NC]</code></p> <p><code>RewriteRule ^(.*)$</code>

