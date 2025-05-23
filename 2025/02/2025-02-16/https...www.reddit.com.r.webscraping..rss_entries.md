# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## Best way to go about scraping countless dynamic data?
 - [https://www.reddit.com/r/webscraping/comments/1ir47y6/best_way_to_go_about_scraping_countless_dynamic](https://www.reddit.com/r/webscraping/comments/1ir47y6/best_way_to_go_about_scraping_countless_dynamic)
 - RSS feed: $source
 - date published: 2025-02-16T22:16:02+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m unsure if the title makes sense, so here&#39;s more detail: There is a site that I&#39;d like to get data from. On the site, there are many tabs/dropdowns that if you click/hover, open up to provide some numbers that I need. However, because there are 100s of buttons/tabs, using selenium to open every single one to pull the API seems far too tedious. Could anyone direct me into a better direction?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bananarama2318"> /u/bananarama2318 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1ir47y6/best_way_to_go_about_scraping_countless_dynamic/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1ir47y6/best_way_to_go_about_scraping_countless_dynamic/">[comments]</a></span>

## Scraping newegg?
 - [https://www.reddit.com/r/webscraping/comments/1ir2lp4/scraping_newegg](https://www.reddit.com/r/webscraping/comments/1ir2lp4/scraping_newegg)
 - RSS feed: $source
 - date published: 2025-02-16T21:06:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Im trying to scrape newegg (its my first time webscraping) and so far it seems like a tough nut to crack. Im using a python list of user agents and matching request headers, and I still get a code 403 every time I make a request. This list format works for other websites with anti webscraping provisions, such as amazon. Any tips as to what I can do to get into newegg? (Im using requests library to make requests and beautifulsoup to parse html)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/slappy20000"> /u/slappy20000 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1ir2lp4/scraping_newegg/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1ir2lp4/scraping_newegg/">[comments]</a></span>

## Dynamically find the pagination button/method of different pages
 - [https://www.reddit.com/r/webscraping/comments/1ir1ex0/dynamically_find_the_pagination_buttonmethod_of](https://www.reddit.com/r/webscraping/comments/1ir1ex0/dynamically_find_the_pagination_buttonmethod_of)
 - RSS feed: $source
 - date published: 2025-02-16T20:15:53+00:00

<!-- SC_OFF --><div class="md"><p>Lets say im scraping 500 different websites. Each of them could have a &quot;Load more&quot; , a &quot;Show n more&quot; button, a &quot;Next&quot; button, perhaps just page buttons to click on like 1,2,3,4,etc. or potentially more ways of how they do pagination. I&#39;m trying to determine what the pagination method is for each of these websites without having to manually check XHR requests for each one.. </p> <p>Things I&#39;ve thought of so far, converting the entire page to html. Cleaning it up then trying to find the pagination action. I&#39;ve also considered the idea of using computer vision on the entire page and determining where the button is.. It seems like there is no one size fits all solution that I can think of that doesn&#39;t involve paying some API service... Any thoughts/recommendations? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Impressive_Safety_26"> /u/Impressive_Safety_26 </a> <br/> 

## How to connect to a websites websocket?
 - [https://www.reddit.com/r/webscraping/comments/1iqz6yw/how_to_connect_to_a_websites_websocket](https://www.reddit.com/r/webscraping/comments/1iqz6yw/how_to_connect_to_a_websites_websocket)
 - RSS feed: $source
 - date published: 2025-02-16T18:44:11+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to connect to DraftKings to get real time odd updates on games. If you go to <a href="https://sportsbook.draftkings.com/">https://sportsbook.draftkings.com/</a> you see a websocket connection get established and messages coming in through the web console. However, when I try to make the same connection in python, I either get no updates or the session gets terminated. I think I am missing some step to establishing a connection here. Has anyone dealt with this type of thing and know how to subscribe to get the updates?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/exater"> /u/exater </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iqz6yw/how_to_connect_to_a_websites_websocket/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iqz6yw/how_to_connect_to_a_websites_websocket/">[comments]</a></span>

## Building a Proxy to Bypass Expiring Tokens for Mangafox Images
 - [https://www.reddit.com/r/webscraping/comments/1iqxuic/building_a_proxy_to_bypass_expiring_tokens_for](https://www.reddit.com/r/webscraping/comments/1iqxuic/building_a_proxy_to_bypass_expiring_tokens_for)
 - RSS feed: $source
 - date published: 2025-02-16T17:47:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to build a proxy that can serve images from MangaFox without worrying about their expiring tokens. Currently, image URLs look like this:</p> <p><a href="https://zjcdn.mangafox.me/store/manga/33957/016.0/compressed/k000.jpg?token=ed8a12f708841105a735c8b0dc6ac26397f4c889&amp;ttl=1739721600">https://zjcdn.mangafox.me/store/manga/33957/016.0/compressed/k000.jpg?token=ed8a12f708841105a735c8b0dc6ac26397f4c889&amp;ttl=1739721600</a></p> <p>What I Know So Far:</p> <p>There is a working proxy (<a href="https://img.spoilerhat.com/">https://img.spoilerhat.com/</a>) that can fetch images like this:</p> <p><a href="https://img.spoilerhat.com/img/?url=https://zjcdn.mangafox.me/store/manga/33957/088.0/compressed/r001.jpg">https://img.spoilerhat.com/img/?url=https://zjcdn.mangafox.me/store/manga/33957/088.0/compressed/r001.jpg</a></p> <p>This URL never expires, works across devices, and doesn’t need a token.</p> <p>I want to build something similar fo

## Scraping Google Maps
 - [https://www.reddit.com/r/webscraping/comments/1iqqzqs/scraping_google_maps](https://www.reddit.com/r/webscraping/comments/1iqqzqs/scraping_google_maps)
 - RSS feed: $source
 - date published: 2025-02-16T12:15:58+00:00

<!-- SC_OFF --><div class="md"><p>Need to find specific types of vendors e.g. Coffee Shops, Urgent Care Clinics, and seems that Google Maps is only comprehensive option. Just need name and Phone numbers, nothing copyrighted. Is it possible to write a script to get her that info or does Maps prevent that. I am not a programmer and will be hiring one. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VeterinarianOk735"> /u/VeterinarianOk735 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iqqzqs/scraping_google_maps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iqqzqs/scraping_google_maps/">[comments]</a></span>

## Host a non-headless scraper
 - [https://www.reddit.com/r/webscraping/comments/1iqnyxv/host_a_nonheadless_scraper](https://www.reddit.com/r/webscraping/comments/1iqnyxv/host_a_nonheadless_scraper)
 - RSS feed: $source
 - date published: 2025-02-16T08:38:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m looking for a cloud hosting service that allow me to deploy a non-headless scraper (in headless I got detected too easily) with a free tier or at least not too expensive, what do you recommend ?</p> <p>I already tried headless, retro engineering etc the only solution is a non headless scraper but this is not scalable to run it in my computer 😅</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Absolute31"> /u/Absolute31 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iqnyxv/host_a_nonheadless_scraper/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iqnyxv/host_a_nonheadless_scraper/">[comments]</a></span>

