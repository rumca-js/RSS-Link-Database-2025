# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Best practice for allowing access to users without an account
 - [https://www.reddit.com/r/django/comments/1i7pxeo/best_practice_for_allowing_access_to_users](https://www.reddit.com/r/django/comments/1i7pxeo/best_practice_for_allowing_access_to_users)
 - RSS feed: $source
 - date published: 2025-01-22T23:56:34+00:00

<!-- SC_OFF --><div class="md"><p>I need to provide access to users who don&#39;t have an account on the site, and I want it to be properly routed. We manage condo associations, and want to let tenants report problems. Owners are no problem, they already have a website account to pay condo fees etc. But tenants don&#39;t. Is there a better way to do it than just giving them a url with a long UUID (ie <a href="http://domain.com/request/%5BUUID%5D">domain.com/request/[UUID]</a> or similar) where the UUID would be tied to a particular unit so we could share it with the appropriate condo board?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jrenaut"> /u/jrenaut </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7pxeo/best_practice_for_allowing_access_to_users/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7pxeo/best_practice_for_allowing_access_to_users/">[comments]</a></span>

## logging sent emails from allauth
 - [https://www.reddit.com/r/django/comments/1i7opbp/logging_sent_emails_from_allauth](https://www.reddit.com/r/django/comments/1i7opbp/logging_sent_emails_from_allauth)
 - RSS feed: $source
 - date published: 2025-01-22T23:01:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello, wondering how to do this, I have a django project that uses allauth for authentication, registration, password resets etc</p> <p>I setup an AWS SES email service, I can see its sending out emails in the SES console but have no idea what the recipient address is, so wanted to add logging for allauth to log to my app.log anytime it sends out an email</p> <p>Do I need to overwrite allauth views or can I pass a parameter from <a href="http://settings.py">settings.py</a> to have allauth start logging all email actions?</p> <p>I have several users saying they arent getting emails from my website where django is running on, so need to troublshoot it. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vectorx25"> /u/vectorx25 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7opbp/logging_sent_emails_from_allauth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comm

## How to separate each company’s data in Django RF?
 - [https://www.reddit.com/r/django/comments/1i7n6gy/how_to_separate_each_companys_data_in_django_rf](https://www.reddit.com/r/django/comments/1i7n6gy/how_to_separate_each_companys_data_in_django_rf)
 - RSS feed: $source
 - date published: 2025-01-22T21:56:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I’m working on a B2B SaaS product with Django Rest Framework. The intention is that every one of my clients can have different users tied to the same company that can access the same data but with different permissions.</p> <p>I am designing the models for the database but I came across a dilemma. How can I separate each company’s data inside my database? I have a few options:</p> <ul> <li>A different database for each company.</li> <li>A shared database, with a different schema for each company.</li> <li>A shared database, adding a “company” attribute to every row on every table.</li> </ul> <p>Has anyone done something similar that can give me suggestions on what approach to choose? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rippedMorty"> /u/rippedMorty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7n6gy/how_to_separate_each_companys_data_in_django_rf/">[link]</a></span> 

## Any good free Hosting service for Django RestApi
 - [https://www.reddit.com/r/django/comments/1i7ep8b/any_good_free_hosting_service_for_django_restapi](https://www.reddit.com/r/django/comments/1i7ep8b/any_good_free_hosting_service_for_django_restapi)
 - RSS feed: $source
 - date published: 2025-01-22T16:12:18+00:00

<!-- SC_OFF --><div class="md"><p>I want free Hosting service for Django RestApi for my project </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Much-Faithlessness-5"> /u/Much-Faithlessness-5 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7ep8b/any_good_free_hosting_service_for_django_restapi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7ep8b/any_good_free_hosting_service_for_django_restapi/">[comments]</a></span>

## Setting Up Django for Success
 - [https://www.reddit.com/r/django/comments/1i7ekq1/setting_up_django_for_success](https://www.reddit.com/r/django/comments/1i7ekq1/setting_up_django_for_success)
 - RSS feed: $source
 - date published: 2025-01-22T16:07:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I wrote a getting started guide I wish I had myself when I got started with Django around 8 years ago. It goes from setting up a virtual environment using `uv` to having a server side rendered front-end application <em>hydrated</em> using Vue. I tried to write it in such a way that you could achieve the same by using React/Svelte instead of Vue by only changing the Vite template. It contains a short piece of Django Rest Framework to demonstrate persistence via an authenticated API.</p> <p>It&#39;s a collection of ideas that worked for me and others in the Django community. Some from books such as Two Scoops of Django. Others from resources such as <a href="http://LearnDjango.com">LearnDjango.com</a> or DjangoCon US talks. Of course duly credited where mentioned.</p> <p><a href="https://jilles.me/setting-up-django-for-success/">https://jilles.me/setting-up-django-for-success/</a></p> <p>Hopefully there is something useful in the

## How do i go about separating my project?
 - [https://www.reddit.com/r/django/comments/1i7d11b/how_do_i_go_about_separating_my_project](https://www.reddit.com/r/django/comments/1i7d11b/how_do_i_go_about_separating_my_project)
 - RSS feed: $source
 - date published: 2025-01-22T15:01:38+00:00

<!-- SC_OFF --><div class="md"><p>I have a django project, and each app in the project can function on it&#39;s own, but also has cross-app functionality. I wanna show each app off separately on Github.</p> <p>Could i just create a separate repo for the app and direct people to the main project in the README? That&#39;s not aHORRIBLE idea right?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Balance3610"> /u/Upstairs-Balance3610 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7d11b/how_do_i_go_about_separating_my_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7d11b/how_do_i_go_about_separating_my_project/">[comments]</a></span>

## Corporate site in a week
 - [https://www.reddit.com/r/django/comments/1i7ciy6/corporate_site_in_a_week](https://www.reddit.com/r/django/comments/1i7ciy6/corporate_site_in_a_week)
 - RSS feed: $source
 - date published: 2025-01-22T14:38:28+00:00

<!-- SC_OFF --><div class="md"><p>I need to get a corporate site up in a week and just wondering what others do in this situation. Short timeline, simple website with content all ready to go, needs contact forms. I am debating whether to just make it in github pages (but the forms?) or just do it in django and put it on a droplet so I can build out more features later if need be.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AttractiveCorpse"> /u/AttractiveCorpse </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7ciy6/corporate_site_in_a_week/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7ciy6/corporate_site_in_a_week/">[comments]</a></span>

## Issues with ads.txt URL
 - [https://www.reddit.com/r/django/comments/1i7c2ea/issues_with_adstxt_url](https://www.reddit.com/r/django/comments/1i7c2ea/issues_with_adstxt_url)
 - RSS feed: $source
 - date published: 2025-01-22T14:16:56+00:00

<!-- SC_OFF --><div class="md"><p>I am still a beginner in Django</p> <p>Recently realized that my website was not accessible at <a href="http://abc.com">http://abc.com</a> and <a href="https://abc.com">https://abc.com</a> (without www)</p> <p>so I updated godaddy domain forwarding to <a href="http://www.abc.com">http://www.abc.com</a></p> <p>so now I can access those two urls without using www which I was having issue with earlier.</p> <p>But now I am trying to figure out why <a href="http://abc.com/ads.txt">http://abc.com/ads.txt</a> and <a href="https://abc.com/ads.txt">https://abc.com/ads.txt</a> isn&#39;t working.</p> <p>Below is my urls. py</p> <pre><code>path(&#39;ads.txt/&#39;, TemplateView.as_view(template_name=&#39;stats/ads.txt&#39;), name=&#39;ads&#39;), </code></pre> <p>I am using django default settings. Is there something I need to change in Django to make it work?</p> <p>Edit: Just to clarify the url <a href="https://www.abc.com/ads.txt">https://www.abc.com/ads.txt</a

## Hardening my Django server
 - [https://www.reddit.com/r/django/comments/1i7br7c/hardening_my_django_server](https://www.reddit.com/r/django/comments/1i7br7c/hardening_my_django_server)
 - RSS feed: $source
 - date published: 2025-01-22T14:02:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve had a Django app running on a Digital Ocean droplet for several years without issue. Lately it would run out of memory on complex queries. The CPU was also hitting high levels. I decided to move to a Hetzner VM - 4 times the CPU and 4 times the memory for about the same price. Having updated all the software dependencies and dome lots of testing I finally migrated to the new server on Sunday. On Tuesday, by coincidence, I got a notification from Digital Ocean Security saying that they had received a report that my old DO server was making unauthorized connection attempts on a remote third-party server via SSH. As I now no longer needed that server, I responded by destroying it. (I don&#39;t have the time and expertise to analyse exactly what was going on.</p> <p>Of course, I want to avoid such an issue recurring on the new server. So my question is: What measures beyond the standard Django deployment checklist (which I had followed) do you r

## Hello dear friends, I use Django 5 and I have problem
 - [https://www.reddit.com/r/django/comments/1i7bo7h/hello_dear_friends_i_use_django_5_and_i_have](https://www.reddit.com/r/django/comments/1i7bo7h/hello_dear_friends_i_use_django_5_and_i_have)
 - RSS feed: $source
 - date published: 2025-01-22T13:58:12+00:00

<!-- SC_OFF --><div class="md"><p><em>\</em>** $ python <a href="http://manage.py">manage.py</a> runserver </p> <p>Watching for file changes with StatReloader Performing system checks... System check identified no issues (0 silenced). Error: You don&#39;t have permission to access that port. (venv) <em>\</em>** </p> <p>How I can solve it ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hayrapetyansami"> /u/hayrapetyansami </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7bo7h/hello_dear_friends_i_use_django_5_and_i_have/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7bo7h/hello_dear_friends_i_use_django_5_and_i_have/">[comments]</a></span>

## Integrating Node-RED and Django for Easy Smart Applications Development
 - [https://www.reddit.com/r/django/comments/1i77ztn/integrating_nodered_and_django_for_easy_smart](https://www.reddit.com/r/django/comments/1i77ztn/integrating_nodered_and_django_for_easy_smart)
 - RSS feed: $source
 - date published: 2025-01-22T10:15:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi Redditors! 👋</p> <p>I’m excited to share my latest project:<br/> <strong>Node-RED - Django Integration</strong>, which aims to combine <strong>Node-RED</strong>, a fantastic tool for visually building flows, with <strong>Django</strong>, one of the most popular frameworks for web application development.</p> <h1>What Makes This Project Unique?</h1> <p>In Node-RED, you cannot control user access permissions.</p> <ul> <li>For example, if you want one user to view a device&#39;s readings but not modify them, while another user can both view and edit the device&#39;s readings, this is impossible in Node-RED.</li> <li>In Django, advanced permission handling is possible. <ul> <li>You can define specific permissions for each device, allowing precise control over who can view or modify data.</li> </ul></li> <li>However, in Django, it is challenging to connect and manage multiple devices or control the flow of data. <ul> <li>Unlike Node-RED, Django is not 

## DjangoCon 2023 recordings are now available
 - [https://www.reddit.com/r/django/comments/1i77axl/djangocon_2023_recordings_are_now_available](https://www.reddit.com/r/django/comments/1i77axl/djangocon_2023_recordings_are_now_available)
 - RSS feed: $source
 - date published: 2025-01-22T09:22:58+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/TechTalksWeekly"> /u/TechTalksWeekly </a> <br/> <span><a href="https://www.techtalksweekly.io/i/155417658/djangocon">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i77axl/djangocon_2023_recordings_are_now_available/">[comments]</a></span>

## Login and creation of account in django
 - [https://www.reddit.com/r/django/comments/1i779un/login_and_creation_of_account_in_django](https://www.reddit.com/r/django/comments/1i779un/login_and_creation_of_account_in_django)
 - RSS feed: $source
 - date published: 2025-01-22T09:20:36+00:00

<!-- SC_OFF --><div class="md"><p>I am a beginner in django. I want that in admin panel that is built in django I would create a model accounts. In that i could be able to create account. And then cinnect the login there. Is there a tutorial for that all i see is that there is a sign up. What I am trying to do is that the account is created by the admin only.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xxpremierexx"> /u/xxpremierexx </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i779un/login_and_creation_of_account_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i779un/login_and_creation_of_account_in_django/">[comments]</a></span>

## allauth-headless confusion
 - [https://www.reddit.com/r/django/comments/1i776tz/allauthheadless_confusion](https://www.reddit.com/r/django/comments/1i776tz/allauthheadless_confusion)
 - RSS feed: $source
 - date published: 2025-01-22T09:13:48+00:00

<!-- SC_OFF --><div class="md"><p>I have been playing around with different types of authentication lately for my react+django project. When reading about auth you quickly get into the &quot;session cookie vs JWT&quot; rabbit hole.</p> <p>Initially i went with JWT, cause at the time i understood that this is the only auth method that allows for potential mobile integration (or at least the most straight forward method). Another point that comes up is that JWT is stateless and REST APIs are stateless but then you also need a blacklist to invalidate used JWT so it&#39;s not stateless anymore but i don&#39;t know...</p> <p>Anyways, so i added dj-rest-auth + djangorestframework-simplejwt on top of django-allauth.</p> <p>Then you keep reading and some people suggest that the JWT should be stored in an http-only cookie. Okay that in itself is straight forward although it requires some custom middleware since some dj-rest-auth endpoints require the token to be in the body.</p> <p>My project

## Any Vercel like Platform as a service for Django.?
 - [https://www.reddit.com/r/django/comments/1i73znx/any_vercel_like_platform_as_a_service_for_django](https://www.reddit.com/r/django/comments/1i73znx/any_vercel_like_platform_as_a_service_for_django)
 - RSS feed: $source
 - date published: 2025-01-22T05:26:41+00:00

<!-- SC_OFF --><div class="md"><p>Just like Vercel is tailored for Next.js/React, is there a PaaS specifically tailored for Django? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Secure-Composer-9458"> /u/Secure-Composer-9458 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i73znx/any_vercel_like_platform_as_a_service_for_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i73znx/any_vercel_like_platform_as_a_service_for_django/">[comments]</a></span>

## wagtail vs djangoCMS NOT standalone
 - [https://www.reddit.com/r/django/comments/1i714pt/wagtail_vs_djangocms_not_standalone](https://www.reddit.com/r/django/comments/1i714pt/wagtail_vs_djangocms_not_standalone)
 - RSS feed: $source
 - date published: 2025-01-22T02:58:31+00:00

<!-- SC_OFF --><div class="md"><p>I am contemplating adding wagtail or djangoCMS into an already large project. It is multi-tenant. The main goal is to allow each tenant to compose some pages specific to their users, so I need to restrict what tenants can see and modify as well as control what users can see. </p> <p>I would also really love for tenants to be able to embed model data from my existing app into new CMS pages, effectively allowing content creators to create the templates for displaying the data. I understand that this may require some code, but I was hoping I could create a template for each data type and then allow tenants to subclass from these templates and create their own pages. </p> <p>Is integrating either of these into an existing project even possible? They both seem to create their own ecosystems. Am I better off starting with a new project and then merging my existing code into the new structure? Or do I just create multiple servers (one for my data and one fo

## Related Models
 - [https://www.reddit.com/r/django/comments/1i6zsye/related_models](https://www.reddit.com/r/django/comments/1i6zsye/related_models)
 - RSS feed: $source
 - date published: 2025-01-22T01:54:48+00:00

<!-- SC_OFF --><div class="md"><p>HI, I&#39;m developing an app with Django Rest Framework and I want to model some transactions. There are different types of transactions, like sales, refunds, etc, so I need a Model for each one. However, I want to be able to retrieve a list of all transactions. I did some research and I think inheritance might be good, using a parent table called Transactions. Would that work, or is there a better approach?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rippedMorty"> /u/rippedMorty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6zsye/related_models/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6zsye/related_models/">[comments]</a></span>

## I built a codebase to build APIs
 - [https://www.reddit.com/r/django/comments/1i6xy09/i_built_a_codebase_to_build_apis](https://www.reddit.com/r/django/comments/1i6xy09/i_built_a_codebase_to_build_apis)
 - RSS feed: $source
 - date published: 2025-01-22T00:26:01+00:00

<!-- SC_OFF --><div class="md"><p>After being a django dev, i fell in love with FastAPI and saw myself building the same starter project over and over again so I built this starter and called it supafast: </p> <ul> <li><p>Authentication endpoints built on top of Supabase</p></li> <li><p>Fully async api + ORM with SqlAlchemy and alembic migrations </p></li> <li><p>Folder-by-feature structure just like Django apps :)</p></li> <li><p>deployments with render</p></li> <li><p>uv for package dependencies </p></li> </ul> <p>And much much more! </p> <p>Check it out and get access at supa-fast.com</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fraisey99"> /u/fraisey99 </a> <br/> <span><a href="http://Supa-fast.com">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6xy09/i_built_a_codebase_to_build_apis/">[comments]</a></span>

