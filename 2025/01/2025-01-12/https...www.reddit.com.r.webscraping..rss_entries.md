# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Bluesky Starter Pack — Web Scraping & Data Extraction
 - [https://www.reddit.com/r/webscraping/comments/1hzz82d/bluesky_starter_pack_web_scraping_data_extraction](https://www.reddit.com/r/webscraping/comments/1hzz82d/bluesky_starter_pack_web_scraping_data_extraction)
 - RSS feed: $source
 - date published: 2025-01-12T22:43:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1hzz82d/bluesky_starter_pack_web_scraping_data_extraction/"> <img src="https://external-preview.redd.it/zZrJ7RC8YK05Me6d4U7DqoC8dLbpicqlUCsGHNZfpnc.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=6743cf5ca972dc65ba61e26efacdd6f0b343ed80" alt="Bluesky Starter Pack — Web Scraping &amp; Data Extraction" title="Bluesky Starter Pack — Web Scraping &amp; Data Extraction" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/matty_fu"> /u/matty_fu </a> <br/> <span><a href="https://go.bsky.app/MCGkrLB">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzz82d/bluesky_starter_pack_web_scraping_data_extraction/">[comments]</a></span> </td></tr></table>

## Scrape product data by EAN through a B2B shop
 - [https://www.reddit.com/r/webscraping/comments/1hzxna6/scrape_product_data_by_ean_through_a_b2b_shop](https://www.reddit.com/r/webscraping/comments/1hzxna6/scrape_product_data_by_ean_through_a_b2b_shop)
 - RSS feed: $source
 - date published: 2025-01-12T21:34:55+00:00

<!-- SC_OFF --><div class="md"><p>I have a product file from a supplier with 8k rows. But they file does not cotain the product photos. I am looking for a tool that allows me to scrape the photos by using the product EAN or similar to get the correct photos to the products in my file. It is also missing a recomennded price so i need to manually price match my competitors, is there any sulotion to automate this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Skaterman69420"> /u/Skaterman69420 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzxna6/scrape_product_data_by_ean_through_a_b2b_shop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzxna6/scrape_product_data_by_ean_through_a_b2b_shop/">[comments]</a></span>

## Temu Scraper
 - [https://www.reddit.com/r/webscraping/comments/1hzv76j/temu_scraper](https://www.reddit.com/r/webscraping/comments/1hzv76j/temu_scraper)
 - RSS feed: $source
 - date published: 2025-01-12T19:50:58+00:00

<!-- SC_OFF --><div class="md"><p>Has anybody successfully able to scrape the temu(dot)com sites product? I see captcha in every product url they have. That is really frustrating 😁 No idea how they are managing SEO</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Historical-City-7708"> /u/Historical-City-7708 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzv76j/temu_scraper/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzv76j/temu_scraper/">[comments]</a></span>

## Non-Traditional HTTP/HTTPS ports on Target
 - [https://www.reddit.com/r/webscraping/comments/1hzpeq7/nontraditional_httphttps_ports_on_target](https://www.reddit.com/r/webscraping/comments/1hzpeq7/nontraditional_httphttps_ports_on_target)
 - RSS feed: $source
 - date published: 2025-01-12T15:44:38+00:00

<!-- SC_OFF --><div class="md"><p>I’m building an API scraper that must interact with several targets that are hosted on non-traditional HTTP/HTTPS ports. </p> <p>For example, one of my targets looks like, https:<a href="http://www.test.com:444">www.test.com:444</a>. To be clear, these are public-facing sites that the devs decided to host on these ports. They are not someone’s private internal servers. Most residential proxy and scraping tools require the target be located on the traditional ports, HTTP = 8080 and HTTPS = 443. </p> <p>Now, anytime I hit the site without a proxy, my code works flawlessly, but opens my IP up for getting quickly blacklisted. Anytime I use a proxy service they return a 403 error. </p> <p>Any thoughts on a work around? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jaseibert2"> /u/Jaseibert2 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzpeq7/nontraditional_httphttps_ports_on_target/">[l

## How can I scrape api data faster?
 - [https://www.reddit.com/r/webscraping/comments/1hzmggk/how_can_i_scrape_api_data_faster](https://www.reddit.com/r/webscraping/comments/1hzmggk/how_can_i_scrape_api_data_faster)
 - RSS feed: $source
 - date published: 2025-01-12T13:17:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi, have a project on at the moment that involves scraping historical pricing data from Polymarket using python requests. I&#39;m using their gamma api and clob api, but currently it would take something like 70k hours just to get all the pricing data since last year down. Multithreading w/ aiohttp results in http429.<br/> Any help is appreciated !</p> <p>edit: request speed isn&#39;t limiting me (each rq takes ~300ms), it&#39;s my code:</p> <pre><code>import requests import json import time def decoratortimer(decimal): def decoratorfunction(f): def wrap(*args, **kwargs): time1 = time.monotonic() result = f(*args, **kwargs) time2 = time.monotonic() print(&#39;{:s} function took {:.{}f} ms&#39;.format(f.__name__, ((time2-time1)*1000.0), decimal )) return result return wrap return decoratorfunction #@decoratortimer(2) def getMarketPage(page): url = f&quot;https://gamma-api.polymarket.com/markets?closed=true&amp;offset={page}&amp;limit=100&quot; return 

## Is there any way to scrape signup process on irctc
 - [https://www.reddit.com/r/webscraping/comments/1hzkwpt/is_there_any_way_to_scrape_signup_process_on_irctc](https://www.reddit.com/r/webscraping/comments/1hzkwpt/is_there_any_way_to_scrape_signup_process_on_irctc)
 - RSS feed: $source
 - date published: 2025-01-12T11:38:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone i am trying to scrape irctc registration process. The issue is captcha which needs to be bypassed in any way. Can you suggest any tool which can be used to scrape such this website </p> <p><a href="https://www.irctc.co.in/nget/profile/user-signup">https://www.irctc.co.in/nget/profile/user-signup</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Timely_Stop2889"> /u/Timely_Stop2889 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzkwpt/is_there_any_way_to_scrape_signup_process_on_irctc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzkwpt/is_there_any_way_to_scrape_signup_process_on_irctc/">[comments]</a></span>

## How to bypass antibot firewalls for free?
 - [https://www.reddit.com/r/webscraping/comments/1hzkgeg/how_to_bypass_antibot_firewalls_for_free](https://www.reddit.com/r/webscraping/comments/1hzkgeg/how_to_bypass_antibot_firewalls_for_free)
 - RSS feed: $source
 - date published: 2025-01-12T11:06:07+00:00

<!-- SC_OFF --><div class="md"><p>I was webscraping a few websites and came across two firewalls. </p> <ol> <li>Incapsula</li> <li>Cloudflare</li> </ol> <p>I am struggling to bypass these firewalls and unable to scrape these websites. </p> <p>I saw some paid services online but I would like to bypass for free by means of coding and would like to get inputs from the experienced webscrapers here.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Emergency_Job_1187"> /u/Emergency_Job_1187 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzkgeg/how_to_bypass_antibot_firewalls_for_free/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzkgeg/how_to_bypass_antibot_firewalls_for_free/">[comments]</a></span>

## Scraping scholarship data by training with Spacy
 - [https://www.reddit.com/r/webscraping/comments/1hzjvfv/scraping_scholarship_data_by_training_with_spacy](https://www.reddit.com/r/webscraping/comments/1hzjvfv/scraping_scholarship_data_by_training_with_spacy)
 - RSS feed: $source
 - date published: 2025-01-12T10:22:59+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to scrape scholarship name, deadlines, amount from various university websites and I was thinking of using spacy and scrapy for it. Spacy to train the data and scrappy to scrape it. Does this seem like a good trajectory? Is there any advice on how to get this done? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Intelligent_Bed_3310"> /u/Intelligent_Bed_3310 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1hzjvfv/scraping_scholarship_data_by_training_with_spacy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1hzjvfv/scraping_scholarship_data_by_training_with_spacy/">[comments]</a></span>

## Deal sharing bot in telegram
 - [https://www.reddit.com/r/webscraping/comments/1hzj0dw/deal_sharing_bot_in_telegram](https://www.reddit.com/r/webscraping/comments/1hzj0dw/deal_sharing_bot_in_telegram)
 - RSS feed: $source
 - date published: 2025-01-12T09:18:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1hzj0dw/deal_sharing_bot_in_telegram/"> <img src="https://a.thumbs.redditmedia.com/7eIM9PYoPyfvSxnTWJThnrlQrPhmQha_R0-QI1DlpV8.jpg" alt="Deal sharing bot in telegram" title="Deal sharing bot in telegram" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I am trying to create a bot in telegram which shares ecommerce deals on regular intervals. There is a telegram group called &quot;offer box official&quot; and I am trying to create a similar group or channel. I am not able to understand how they are doing it. They are sharing affiliated links. I am not able to find how they are finding these many deals. Can someone please suggest.</p> <p><a href="https://preview.redd.it/htk4xhls5jce1.png?width=1069&amp;format=png&amp;auto=webp&amp;s=321e6b2014700716e862a6befe6affb7daf0796a">https://preview.redd.it/htk4xhls5jce1.png?width=1069&amp;format=png&amp;auto=webp&amp;s=321e6b2014700716e862a6befe6affb7daf07

## Running a proxy on node.js/express for the browser
 - [https://www.reddit.com/r/webscraping/comments/1hziwwd/running_a_proxy_on_nodejsexpress_for_the_browser](https://www.reddit.com/r/webscraping/comments/1hziwwd/running_a_proxy_on_nodejsexpress_for_the_browser)
 - RSS feed: $source
 - date published: 2025-01-12T09:11:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;m attempting to run a proxy middleware on express to proxy any requests to my localhost:5000 to the target url. I&#39;m using a free trial residential proxy for the proxy agent, and the initial request seems to be being proxied just fine - the issue is none of the pages can load any javascript/assets/api. This is what it would look like, using Reddit as an example:</p> <ol> <li>I navigate to localhost:5000 on my browser</li> <li>It takes me to <a href="https://www.reddit.com">https://www.reddit.com</a>, page looks messed up and only html is rendered</li> <li>I open browser console, tons of errors about Axios (Reddit api getting confused?)</li> </ol> <p>This is the relevant code: </p> <pre><code>const url = &#39;https://www.reddit.com/&#39;; const proxyAgent = new HttpsProxyAgent( `https://${proxy_username}:${proxy_password}@${proxy_host}:${proxy_port}`, ); const proxyMiddleware = createProxyMiddleware({ cookieDomainRewrite: { &#39;*&#39;: &
