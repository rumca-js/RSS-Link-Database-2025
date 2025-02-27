# Source:webscraping, URL:https://www.reddit.com/r/webscraping/.rss, language:en

## how to handle selectors for websites that change html
 - [https://www.reddit.com/r/webscraping/comments/1iysimk/how_to_handle_selectors_for_websites_that_change](https://www.reddit.com/r/webscraping/comments/1iysimk/how_to_handle_selectors_for_websites_that_change)
 - RSS feed: $source
 - date published: 2025-02-26T17:09:33+00:00

<!-- SC_OFF --><div class="md"><p>When a website updates its HTML structure, causing selectors to break, how do you usually handle it? Do you manually review and update them?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crazy-Ad486"> /u/Crazy-Ad486 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iysimk/how_to_handle_selectors_for_websites_that_change/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iysimk/how_to_handle_selectors_for_websites_that_change/">[comments]</a></span>

## How to web scrape from multiple websites with different structures?
 - [https://www.reddit.com/r/webscraping/comments/1iyqdtp/how_to_web_scrape_from_multiple_websites_with](https://www.reddit.com/r/webscraping/comments/1iyqdtp/how_to_web_scrape_from_multiple_websites_with)
 - RSS feed: $source
 - date published: 2025-02-26T15:41:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on creating a comprehensive dataset of degree programs offered by Sri Lankan universities. For each program, I need to collect structured data including:</p> <p>Program duration Prerequisites/entry requirements Tuition fees Course modules/curriculum Degree type/level Faculty/department information</p> <p>The challenge: There&#39;s no datasets related to this in platforms like Kaggle. Each university has its own website with unique structure, HTML layouts, and ways of presenting program information. I&#39;ve considered web scraping, but the variation in website structures makes it difficult to create a single scraper that works across all sites. Manual data collection is possible but extremely time-consuming given the number of programs across multiple universities.</p> <p>My current approach: I can scrape individual university websites by creating custom scrapers for each, but I&#39;m looking for a more efficient method to handle mult

## I could use some help getting around ICheckMovies's bot detection
 - [https://www.reddit.com/r/webscraping/comments/1iyq968/i_could_use_some_help_getting_around](https://www.reddit.com/r/webscraping/comments/1iyq968/i_could_use_some_help_getting_around)
 - RSS feed: $source
 - date published: 2025-02-26T15:35:32+00:00

<!-- SC_OFF --><div class="md"><p>So I&#39;ve been scraping the site for a while to get IMDb IDs of movies from any list (<a href="https://www.icheckmovies.com/lists/1001+movies+you+must+see+before+you+die/">example list</a>). They very recently implemented some other blocking for scraping and I was hoping to get some help to get around it using requests.</p> <pre><code>import requests url = &quot;https://www.icheckmovies.com/lists/1001+movies+you+must+see+before+you+die/&quot; print(f&quot;URL: {url}&quot;) response = requests.get(url, headers={&quot;User-Agent&quot;: &quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:135.0) Gecko/20100101 Firefox/135.0&quot;}) print(response.status_code) print(response.reason) </code></pre> <p>Results</p> <pre><code>URL: https://www.icheckmovies.com/lists/1001+movies+you+must+see+before+you+die/ 403 Forbidden </code></pre> <p>If you look at the response.content it says &quot;This website is using a security service to protect itself from online att

## Think You're a Web Scraping Pro? Prove It & Win Prizes! 🏆
 - [https://www.reddit.com/r/webscraping/comments/1iypvrz/think_youre_a_web_scraping_pro_prove_it_win_prizes](https://www.reddit.com/r/webscraping/comments/1iypvrz/think_youre_a_web_scraping_pro_prove_it_win_prizes)
 - RSS feed: $source
 - date published: 2025-02-26T15:19:13+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/webscraping/comments/1iypvrz/think_youre_a_web_scraping_pro_prove_it_win_prizes/"> <img src="https://external-preview.redd.it/ykvxcboaG6LpupGeN-6p224V3ttglfVGHvhrfjQf7pQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=219946841b164a1d3f7b7eda19cdc45f028adbe7" alt="Think You're a Web Scraping Pro? Prove It &amp; Win Prizes! 🏆" title="Think You're a Web Scraping Pro? Prove It &amp; Win Prizes! 🏆" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey folks! 👋</p> <p>If you love web scraping and enjoy a good challenge, there’s a fun quiz coming up where you can test your skills and compete with other data enthusiasts.</p> <p><strong>🗓️ When?</strong> Feb 27 at 3:00 PM UTC</p> <p><strong>🎁 What’s at stake?</strong> 🥇 <strong>$50 Voucher | 🥈 $50 Zyte Credits | 🥉 $25 Zyte Credits</strong></p> <p><strong>Powered by</strong> <a href="https://www.zyte.com/?utm_campaign=DIS-ONBOARD&amp;utm_activity=Community&amp;utm_medium=social&amp;utm_sou

## Trying to automate appleid registeration, any tips for detectability?
 - [https://www.reddit.com/r/webscraping/comments/1iyn8y4/trying_to_automate_appleid_registeration_any_tips](https://www.reddit.com/r/webscraping/comments/1iyn8y4/trying_to_automate_appleid_registeration_any_tips)
 - RSS feed: $source
 - date published: 2025-02-26T13:15:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m starting to write a script to automate appleid registeration with selenium, my attempt with requests was a pain and it didn&#39;t work for long, I used rotating proxies and captcha solver service but after that I get 400 code with we can&#39;t create your account at this time, it worked for some time and never again, Now I&#39;m going for a selenium approach, I want some solutions for the detectability part, I&#39;m using a rotating premium residential proxy service and a captcha solver service and I don&#39;t want to pay for something else the budget is tight, So what else can I do? Does anyone has experience with apple sites? What I do is getting a temp mail and using that mail with a phone number I have and I just want to send a code to that number 3 times, and I want to do it bulk also so what are the possibilities of me using the script for 80k codes sent per day? I have a deadline of 3 days and I want to be educated on the matter or if 

## A Handy Way to Uncover Hidden APIs with Postman Interceptor
 - [https://www.reddit.com/r/webscraping/comments/1iylkis/a_handy_way_to_uncover_hidden_apis_with_postman](https://www.reddit.com/r/webscraping/comments/1iylkis/a_handy_way_to_uncover_hidden_apis_with_postman)
 - RSS feed: $source
 - date published: 2025-02-26T11:39:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/webscraping">r/webscraping</a>! I’ve learned so much from this subreddit over the years and wanted to give back. I’ve known this trick for a while, so I’m excited to show you how to uncover hidden APIs using Postman Interceptor rather than just the network tab. In the video below, I capture requests on my own site, <strong>FlyFast</strong>, to reveal flight details, booking links, and other data.</p> <p>Check it out here: <a href="https://www.loom.com/share/d2a9ff9993cc4dd7aa714b88cb9e4c6f?sid=f235d739-5a3e-42ca-b213-6257e0875ac0">Loom Video Tutorial</a></p> <p>I hope this helps your scrapes—let me know if you have any questions!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Which_Extension_9576"> /u/Which_Extension_9576 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iylkis/a_handy_way_to_uncover_hidden_apis_with_postman/">[link]</a></span> &#32; <span><a href="https:/

## Are there any Open Source / Free Anti-detect Browsers with GUI?
 - [https://www.reddit.com/r/webscraping/comments/1iyl99t/are_there_any_open_source_free_antidetect](https://www.reddit.com/r/webscraping/comments/1iyl99t/are_there_any_open_source_free_antidetect)
 - RSS feed: $source
 - date published: 2025-02-26T11:18:56+00:00

<!-- SC_OFF --><div class="md"><p>There are like a hundred different companies all offering various products that look very similar it&#39;s a web browser with a bunch of profiles that you can setup and then set up rules for each of them and they can do bot actions or scrape or whatever. </p> <p>I know I can use selenium but for simple tasks these seem like they might be a faster option. Are there any of these tools that are open source or free (maybe they want you to buy their proxy but can support your own proxy too, not sure if that&#39;s compatible with rule 3 as a suggestion, I would prefer open source anyway). </p> <p>I know about camoufox but that&#39;s still more of a tool to integrate into playwrite. </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RoamingDad"> /u/RoamingDad </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iyl99t/are_there_any_open_source_free_antidetect/">[link]</a></span> &#32; <

## Any guidance regarding extracting Midjourney data via python?
 - [https://www.reddit.com/r/webscraping/comments/1iyihqo/any_guidance_regarding_extracting_midjourney_data](https://www.reddit.com/r/webscraping/comments/1iyihqo/any_guidance_regarding_extracting_midjourney_data)
 - RSS feed: $source
 - date published: 2025-02-26T07:58:19+00:00

<!-- SC_OFF --><div class="md"><p>I want the images to be downloaded in bulk along with metadata like prompt, height, width etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Practical-Visual1"> /u/Practical-Visual1 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iyihqo/any_guidance_regarding_extracting_midjourney_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iyihqo/any_guidance_regarding_extracting_midjourney_data/">[comments]</a></span>

## hiring freelancer
 - [https://www.reddit.com/r/webscraping/comments/1iyhvb9/hiring_freelancer](https://www.reddit.com/r/webscraping/comments/1iyhvb9/hiring_freelancer)
 - RSS feed: $source
 - date published: 2025-02-26T07:12:40+00:00

<!-- SC_OFF --><div class="md"><p>Sorry if this is not appropriate to post here - didn&#39;t see anything suggesting I shouldn&#39;t. </p> <p>I need to hire someone for web scraping services. Need to scrape about 300 pages from a single domain &amp; compile the information collected into a spreadsheet, preferably google sheets. </p> <p>Things to be scraped are just basic text information from these pages, photos, &amp; a pdf version of each page on the website. </p> <p>Don&#39;t have a huge budget as I&#39;m just starting my company but not trying to find free/slave/cheap labor either - willing to pay a fair price if someone can deliver on all requirements. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jackphumphrey"> /u/jackphumphrey </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iyhvb9/hiring_freelancer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iyhvb9/hiring_freelancer/

## Scraping strategy for 1 million pages
 - [https://www.reddit.com/r/webscraping/comments/1iyh0ce/scraping_strategy_for_1_million_pages](https://www.reddit.com/r/webscraping/comments/1iyh0ce/scraping_strategy_for_1_million_pages)
 - RSS feed: $source
 - date published: 2025-02-26T06:14:06+00:00

<!-- SC_OFF --><div class="md"><p>I need to scrape data from 1 million pages on a single website. While I&#39;ve successfully scraped smaller amounts of data, I still don&#39;t know what the best approach for this large-scale operation could be. Specifically, should I prioritize speed by using an asyncio scraper to maximize the number of requests in a short timeframe? Or would it be more effective to implement a slower, more distributed approach with multiple synchronous scrapers?</p> <p>Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jibo16"> /u/jibo16 </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iyh0ce/scraping_strategy_for_1_million_pages/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iyh0ce/scraping_strategy_for_1_million_pages/">[comments]</a></span>

## Api requests return empty result when devtools is open
 - [https://www.reddit.com/r/webscraping/comments/1iydimf/api_requests_return_empty_result_when_devtools_is](https://www.reddit.com/r/webscraping/comments/1iydimf/api_requests_return_empty_result_when_devtools_is)
 - RSS feed: $source
 - date published: 2025-02-26T02:56:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to understand the structure of a website (bet365). On one of its pages, there are expanders. Typically, when I click on an expander, it opens and loads the data, making an API request in the backend. However, when I open Chrome DevTools and click on the expander, it doesn’t open, and the API response is empty. Does anyone know what might be happening?</p> <p>The reason I am talking about Chrome DevTools is because I started using <a href="https://seleniumbase.io/">selenium base</a> in <a href="https://seleniumbase.io/help_docs/uc_mode/">UC mode</a> and the same behaviour is happening: most of the pages load, except those expanders and when I click on it, nothing happens: basically it makes some api requests but the result is empty. </p> <p>Any suggestions on how to overcome that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dimem16"> /u/dimem16 </a> <br/> <span><a href="https://www.reddit.com/r

## Anyone had success webscraping doordash?
 - [https://www.reddit.com/r/webscraping/comments/1iyceuy/anyone_had_success_webscraping_doordash](https://www.reddit.com/r/webscraping/comments/1iyceuy/anyone_had_success_webscraping_doordash)
 - RSS feed: $source
 - date published: 2025-02-26T02:01:19+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a group project where I want to webscrape data for alcohol delivery in Georgia cities. </p> <p>I&#39;ve tried puppeteer, selenium, playwright, and beautifulsoup with no success. I&#39;ve successfully pulled the same data from PostMates, Uber Eats, and GrubHub. </p> <p>It&#39;s the dynamic content that&#39;s really blocking me here. GrubHub also had some dynamic content but I was able to work around it using playwright. </p> <p>Any suggestions? Did any of the above packages work for you? I just want a list of the restaurants that come up when you search for alcohol delivery (by city). </p> <p>Appreciate any help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/green_gingerneer"> /u/green_gingerneer </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iyceuy/anyone_had_success_webscraping_doordash/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/

## Scraping dynamic site that requires captcha entry
 - [https://www.reddit.com/r/webscraping/comments/1iybf3d/scraping_dynamic_site_that_requires_captcha_entry](https://www.reddit.com/r/webscraping/comments/1iybf3d/scraping_dynamic_site_that_requires_captcha_entry)
 - RSS feed: $source
 - date published: 2025-02-26T01:12:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I need help with this. I need to scrape some data off this site, but it uses a captcha (recaptcha v1) as far as I can tell. Once the captcha is entered and submitted, only then the data shows up on the site. </p> <p>Can anyone help me on this. The data is openly available on the site but just requires this captcha entry to get it.</p> <p>I cannot bypass the captcha, it is mandatory without which I cannot get the data.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BigDaddy_in_the_Bus"> /u/BigDaddy_in_the_Bus </a> <br/> <span><a href="https://www.reddit.com/r/webscraping/comments/1iybf3d/scraping_dynamic_site_that_requires_captcha_entry/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/webscraping/comments/1iybf3d/scraping_dynamic_site_that_requires_captcha_entry/">[comments]</a></span>

