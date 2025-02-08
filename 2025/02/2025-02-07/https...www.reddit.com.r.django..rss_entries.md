# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How to allow HTML elments in CKEditor5?
 - [https://www.reddit.com/r/django/comments/1ik5x5o/how_to_allow_html_elments_in_ckeditor5](https://www.reddit.com/r/django/comments/1ik5x5o/how_to_allow_html_elments_in_ckeditor5)
 - RSS feed: $source
 - date published: 2025-02-07T21:15:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi all - when I add classes into the CKEditor5 text editor in my admin, the classes get removed when saving. I below I need to <a href="https://ckeditor.com/docs/ckeditor5/latest/features/general-html-support.html#enabling-all-html-features">do something like this</a> but I have been struggling on how exactly to do this. Do I add it to CKEDITOR_5_CONFIGS in settings.py? Or is there another route to take?</p> <p>I have been trying to add htmlSupport to CKEDITOR_5_CONFIGS in <a href="http://settings.py">settings.py</a> but I think I&#39;m getting the syntax wrong as it&#39;s either causing an errror or not allowing html elements. Below is a simplified version of my current configs. I&#39;ve tried with and without quotes on many items but nothing seems to work.</p> <pre><code>CKEDITOR_5_CONFIGS = { &#39;default&#39;: { &#39;toolbar&#39;: [&#39;heading&#39;, &#39;|&#39;, &#39;bold&#39;, &#39;italic&#39;, &#39;link&#39;, &#39;bulletedList&#39;, &#39;numbe

## New TO Django Anybody help fix below issue
 - [https://www.reddit.com/r/django/comments/1ik4vq2/new_to_django_anybody_help_fix_below_issue](https://www.reddit.com/r/django/comments/1ik4vq2/new_to_django_anybody_help_fix_below_issue)
 - RSS feed: $source
 - date published: 2025-02-07T20:31:15+00:00

<!-- SC_OFF --><div class="md"><table><thead> <tr> <th align="left">Request Method:</th> <th align="left">GET</th> </tr> </thead><tbody> <tr> <td align="left">Request URL:</td> <td align="left"><a href="http://127.0.0.1:8000/admin/">http://127.0.0.1:8000/admin/</a></td> </tr> <tr> <td align="left">Django Version:</td> <td align="left">5.1.6</td> </tr> <tr> <td align="left">Exception Type:</td> <td align="left">OperationalError</td> </tr> <tr> <td align="left">Exception Value:</td> <td align="left">no such table: ArticHub_user</td> </tr> <tr> <td align="left">Exception Location:</td> <td align="left">/home/jprashik/PycharmProjects/ArtsHub/.venv/lib/python3.13/site-packages/django/db/backends/sqlite3/base.py, line 354, in execute</td> </tr> <tr> <td align="left">Raised during:</td> <td align="left">django.contrib.admin.sites.index</td> </tr> <tr> <td align="left">Python Executable:</td> <td align="left">/home/jprashik/PycharmProjects/ArtsHub/.venv/bin/python3</td> </tr> <tr> <td align=

## Is django a good choice for a realtime messaging app ?
 - [https://www.reddit.com/r/django/comments/1ik4owk/is_django_a_good_choice_for_a_realtime_messaging](https://www.reddit.com/r/django/comments/1ik4owk/is_django_a_good_choice_for_a_realtime_messaging)
 - RSS feed: $source
 - date published: 2025-02-07T20:23:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m planning to build a realtime messaging app and considering two approaches:</p> <p><strong>Django with a PostgreSQL backend</strong> : Using Django Channels for WebSocket support and PostgreSQL for message storage.</p> <p><strong>Cloudflare Durable Objects</strong> : It&#39;s serverless, don&#39;t have to worry about slacing, very cheap. i&#39;ll also have a django backend for auth and other stuff and only use durable objects for the chat part. </p> <p>My main concerns are scalability, latency, and ease of maintenance. While Django is great for traditional web apps, I’m wondering if it can handle high-volume realtime messaging efficiently. On the other hand, Cloudflare Durable Objects is purpose built for this kind of use case, I’m not sure about the trade-offs.</p> <p>Has anyone built a similar app before? What would you recommend</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BusinessAstronomer28"> /u/

## would you like to contribute in an open source django chat app
 - [https://www.reddit.com/r/django/comments/1ik4cmb/would_you_like_to_contribute_in_an_open_source](https://www.reddit.com/r/django/comments/1ik4cmb/would_you_like_to_contribute_in_an_open_source)
 - RSS feed: $source
 - date published: 2025-02-07T20:08:27+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I recently built a very basic Django chat app just for fun. It uses Django Channels and WebSockets, but I haven’t integrated Redis yet since it was more of a quick experiment.<br/> Now, I’m thinking of taking it a step further—adding some basic features, hosting it, and making it open-source so others can contribute and improve it.</p> <p>Would anyone be interested in contributing to something like this? It could benefit both the community and your personal portfolio while also enhancing your GitHub presence. Also, if you have suggestions for features or improvements, I’d love to hear them!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Frzn23"> /u/Frzn23 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ik4cmb/would_you_like_to_contribute_in_an_open_source/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ik4cmb/would_you_like_to_contribute_in_an

## My Django based selfhosted PDF manager, viewer and editor reached 700 stars on github / contributions
 - [https://www.reddit.com/r/django/comments/1ik42ed/my_django_based_selfhosted_pdf_manager_viewer_and](https://www.reddit.com/r/django/comments/1ik42ed/my_django_based_selfhosted_pdf_manager_viewer_and)
 - RSS feed: $source
 - date published: 2025-02-07T19:56:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/django">r/django</a>,</p> <p>I am the developer of PdfDing - a selfhosted PDF manager, viewer and editor offering a seamless user experience on multiple devices. You can find the repo <a href="https://github.com/mrmn2/PdfDing">here</a>.</p> <p>Today I reached a big milestone as PdfDing reached over 700 stars on github. A good portion of these stars probably comes from being included in the <em>favorite selfhosted apps launched in 2024</em> on <a href="https://selfh.st/2024-favorite-new-apps/">selfh.st</a>. PdfDing also had two (albeit small) contributions, which also made me quite happy.</p> <p>Remaining on the topic of contributions I noticed that people on this sub are often looking for open source projects they could contribute to. In my opinion PdfDing would be a good starting point for getting your feet wet in regards to open source contributions, as it is not too simple but at the same time also not too complex. So getting starte

## AI-Powered Image Captions: How Large Language Models Automate Alt Text and Improve Accessibility
 - [https://www.reddit.com/r/django/comments/1ik1bey/aipowered_image_captions_how_large_language](https://www.reddit.com/r/django/comments/1ik1bey/aipowered_image_captions_how_large_language)
 - RSS feed: $source
 - date published: 2025-02-07T18:02:59+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/LincolnLoop"> /u/LincolnLoop </a> <br/> <span><a href="https://lincolnloop.com/insights/autofill-image-captions-using-large-language-models/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ik1bey/aipowered_image_captions_how_large_language/">[comments]</a></span>

## Django tip Automatically Reload Your Browser in Development (hot reload)
 - [https://www.reddit.com/r/django/comments/1ik1ayb/django_tip_automatically_reload_your_browser_in](https://www.reddit.com/r/django/comments/1ik1ayb/django_tip_automatically_reload_your_browser_in)
 - RSS feed: $source
 - date published: 2025-02-07T18:02:29+00:00

<!-- SC_OFF --><div class="md"><p>Django’s development server reloads itself when you change code, but it does not tell the browser to reload. And it does not do anything when a template or static asset changes.</p> <p>Whenever you edit a template, or make a code change that restarts the server, django-browser-reload will reload the current page. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djv-mo"> /u/djv-mo </a> <br/> <span><a href="https://i.redd.it/ijwbs1l5brhe1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ik1ayb/django_tip_automatically_reload_your_browser_in/">[comments]</a></span>

## Need help with Celery
 - [https://www.reddit.com/r/django/comments/1ik10s0/need_help_with_celery](https://www.reddit.com/r/django/comments/1ik10s0/need_help_with_celery)
 - RSS feed: $source
 - date published: 2025-02-07T17:51:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I use Celery in my Django project, which has around 10K active users.</p> <p>My experience with Celery has been... terrible.</p> <p>I&#39;m facing frequent random worker crashes (cold shutdowns), and tasks are not being retried, even with acks_late=True.</p> <p>Do you have any advice on how to diagnose these crashes? Are there any tools that could help?</p> <p>Maybe I&#39;m not using Celery correctly or missing something important. I&#39;m open to any suggestions on how to make my setup more robust.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Evktw"> /u/Evktw </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ik10s0/need_help_with_celery/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ik10s0/need_help_with_celery/">[comments]</a></span>

## djangify-package - Use Django ORM/schema migrations anywhere
 - [https://www.reddit.com/r/django/comments/1ik082p/djangifypackage_use_django_ormschema_migrations](https://www.reddit.com/r/django/comments/1ik082p/djangifypackage_use_django_ormschema_migrations)
 - RSS feed: $source
 - date published: 2025-02-07T17:18:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/-domingues"> /u/-domingues </a> <br/> <span><a href="https://github.com/domingues/djangify-package">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ik082p/djangifypackage_use_django_ormschema_migrations/">[comments]</a></span>

## Getting back into Django after 6-7 years
 - [https://www.reddit.com/r/django/comments/1ik05cr/getting_back_into_django_after_67_years](https://www.reddit.com/r/django/comments/1ik05cr/getting_back_into_django_after_67_years)
 - RSS feed: $source
 - date published: 2025-02-07T17:15:09+00:00

<!-- SC_OFF --><div class="md"><p>I was a Django developer back in the 1.5-2.0 era. I know that a ton has changed and I&#39;ll have to relearn nearly everything. Right now my biggest concern is just getting started. Back then we just threw our app on a dedicated server and tied it into Apache. </p> <p>Right now I just want to mess around and learn, however I would like to be able to access things that I&#39;ve made outside of just my local PC. From the research that I&#39;ve done it seems like using Django for the front end isn&#39;t really done anymore. I should be using something like React for my front end. </p> <p>Can anyone recommend an easy way to get started that doesn&#39;t cost an arm and a leg?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/irr1449"> /u/irr1449 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ik05cr/getting_back_into_django_after_67_years/">[link]</a></span> &#32; <span><a href="https://www.reddit.c

## Seniors of django, how did learn the framework?
 - [https://www.reddit.com/r/django/comments/1ijvisj/seniors_of_django_how_did_learn_the_framework](https://www.reddit.com/r/django/comments/1ijvisj/seniors_of_django_how_did_learn_the_framework)
 - RSS feed: $source
 - date published: 2025-02-07T13:55:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m 24 and trying to learn Django, but I’ve been struggling a lot. I have a background in computer engineering and some coding knowledge, but I lack job experience. Whenever I try to study or work on projects, I get tired quickly and lose focus. I also tend to underestimate my skills, which makes learning feel even harder.</p> <p>On top of that, I feel really alone in this process. I don’t have a support system of people who understand what I’m going through, and I can’t use freelance platforms due to my location. All of this makes it hard to stay motivated, especially when I don’t see immediate progress.</p> <p>I’m wondering if anyone has been in a similar situation. How do you push through when you feel isolated and discouraged? How do you deal with feeling like you’re not good enough, even when logically you know you’re making progress? Any tips for managing fatigue while studying?</p> <p>I’d really appreciate any advice or en

## should I put async for celery tasks?
 - [https://www.reddit.com/r/django/comments/1ijsqui/should_i_put_async_for_celery_tasks](https://www.reddit.com/r/django/comments/1ijsqui/should_i_put_async_for_celery_tasks)
 - RSS feed: $source
 - date published: 2025-02-07T11:18:20+00:00

<!-- SC_OFF --><div class="md"><p>hi, some functions send api to the external services like payment gateway, alarm service, I am writing code to distributed these tasks, should I put async or does celery handle all the tasks asyncronously? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ijsqui/should_i_put_async_for_celery_tasks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ijsqui/should_i_put_async_for_celery_tasks/">[comments]</a></span>

## SEARCH YOUTUBE AND VIMEO IN ONE PLACE
 - [https://www.reddit.com/r/django/comments/1ijnlte/search_youtube_and_vimeo_in_one_place](https://www.reddit.com/r/django/comments/1ijnlte/search_youtube_and_vimeo_in_one_place)
 - RSS feed: $source
 - date published: 2025-02-07T05:17:52+00:00

<!-- SC_OFF --><div class="md"><h1>I just found this website that let you search for youtube and Vimeos videos, it rank the best videos from the two platforms based on views and quality of the content. It is cool because you search one place and get videos from two different platform</h1> <p>link: <a href="http://www.tubesynopsis.com/">http://www.tubesynopsis.com</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Used_Ad8743"> /u/Used_Ad8743 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ijnlte/search_youtube_and_vimeo_in_one_place/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ijnlte/search_youtube_and_vimeo_in_one_place/">[comments]</a></span>

