# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## DjangoCongress JP 2025 Announcement and Live Streaming!
 - [https://www.reddit.com/r/django/comments/1ipmt2y/djangocongress_jp_2025_announcement_and_live](https://www.reddit.com/r/django/comments/1ipmt2y/djangocongress_jp_2025_announcement_and_live)
 - RSS feed: $source
 - date published: 2025-02-14T22:26:31+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/feb/14/djangocongress-jp-2025-announcement-and-livestream/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ipmt2y/djangocongress_jp_2025_announcement_and_live/">[comments]</a></span>

## DjangoCongress JP 2025 Announcement and Live Streaming!
 - [https://www.reddit.com/r/django/comments/1ipmi3r/djangocongress_jp_2025_announcement_and_live](https://www.reddit.com/r/django/comments/1ipmi3r/djangocongress_jp_2025_announcement_and_live)
 - RSS feed: $source
 - date published: 2025-02-14T22:13:05+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/thibaudcolas"> /u/thibaudcolas </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/feb/14/djangocongress-jp-2025-announcement-and-livestream/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ipmi3r/djangocongress_jp_2025_announcement_and_live/">[comments]</a></span>

## About to create a website all on my own
 - [https://www.reddit.com/r/django/comments/1ipl145/about_to_create_a_website_all_on_my_own](https://www.reddit.com/r/django/comments/1ipl145/about_to_create_a_website_all_on_my_own)
 - RSS feed: $source
 - date published: 2025-02-14T21:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, Let me start by saying i have never made website before and this is going to be my first. I have learned django&#39;s basics and I decided to learn everything else with a real project. So i want to create website for a local company and all of it is going to be done by me. What things I should consider and have in mind before starting this project? P.s: which type of html template license is ok for me to use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Echane"> /u/Echane </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ipl145/about_to_create_a_website_all_on_my_own/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ipl145/about_to_create_a_website_all_on_my_own/">[comments]</a></span>

## PostgreSQL & BeyondTrust Zero-Days Exploited in Coordinated Attacks
 - [https://www.reddit.com/r/django/comments/1ipfnkf/postgresql_beyondtrust_zerodays_exploited_in](https://www.reddit.com/r/django/comments/1ipfnkf/postgresql_beyondtrust_zerodays_exploited_in)
 - RSS feed: $source
 - date published: 2025-02-14T17:18:42+00:00

<!-- SC_OFF --><div class="md"><p><strong>Relevant to Django Devs Using PostgreSQL:</strong></p> <p>Threat actors exploited a newly discovered PostgreSQL vulnerability (CVE-2025-1094) alongside a BeyondTrust zero-day (CVE-2024-12356), allowing them to achieve remote code execution. The PostgreSQL flaw enables attackers to execute arbitrary shell commands through SQL injection, significantly raising security risks for affected systems. (<a href="https://www.reddit.com/r/pwnhub/comments/1ipfk3q/postgresql_beyondtrust_zerodays_exploited_in/">View Details on PwnHub</a>)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dark-Marc"> /u/Dark-Marc </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ipfnkf/postgresql_beyondtrust_zerodays_exploited_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ipfnkf/postgresql_beyondtrust_zerodays_exploited_in/">[comments]</a></span>

## Best practice for temporary variable in signals
 - [https://www.reddit.com/r/django/comments/1ipbkb5/best_practice_for_temporary_variable_in_signals](https://www.reddit.com/r/django/comments/1ipbkb5/best_practice_for_temporary_variable_in_signals)
 - RSS feed: $source
 - date published: 2025-02-14T14:19:04+00:00

<!-- SC_OFF --><div class="md"><p>When working with django signals, I often find myself assigning temporary values to the received instance to use in another signal, like:</p> <pre><code>@receiver(pre_delete, sender=Device) def device_pre_delete(sender, instance, **kwargs): instance._user = instance.user if instance.user else None @receiver(post_delete, sender=Device) def device_post_delete(sender, instance, **kwargs): if not hasattr(instance, &#39;_user&#39;) or not instance._user: return user = instance._user </code></pre> <p>It feels pretty dirty to do that and I&#39;m rather new to django and I&#39;d like to design something pretty robust here.</p> <p>What the way to go here?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frouge"> /u/frouge </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ipbkb5/best_practice_for_temporary_variable_in_signals/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comment

## DRF application boilerplate
 - [https://www.reddit.com/r/django/comments/1ip8woh/drf_application_boilerplate](https://www.reddit.com/r/django/comments/1ip8woh/drf_application_boilerplate)
 - RSS feed: $source
 - date published: 2025-02-14T11:52:48+00:00

<!-- SC_OFF --><div class="md"><p>I have a couple of new rest service required to be setup using DRF. This services will communicate with each other via REST and webhooks. I&#39;m looking for some boilerplate like cookie cutter for DRF. My apps will use celery with production ready configuration and postgres as DB. since both apps will use postgres so I need some sort of docker and compose.yml which will start both apps with these dependencies after dockerfile is built.</p> <p>Any suggestions for a boilerplate code for above requirements?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Cold-Supermarket-715"> /u/Cold-Supermarket-715 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ip8woh/drf_application_boilerplate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ip8woh/drf_application_boilerplate/">[comments]</a></span>

## Starter responsive panel template
 - [https://www.reddit.com/r/django/comments/1ip7z5v/starter_responsive_panel_template](https://www.reddit.com/r/django/comments/1ip7z5v/starter_responsive_panel_template)
 - RSS feed: $source
 - date published: 2025-02-14T10:49:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I want to buy simple,modern,responsive design and easy custom templates for an ecommerce app. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Any-Data1138"> /u/Any-Data1138 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ip7z5v/starter_responsive_panel_template/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ip7z5v/starter_responsive_panel_template/">[comments]</a></span>

## Starter templates
 - [https://www.reddit.com/r/django/comments/1ip7ejh/starter_templates](https://www.reddit.com/r/django/comments/1ip7ejh/starter_templates)
 - RSS feed: $source
 - date published: 2025-02-14T10:07:04+00:00

<!-- SC_OFF --><div class="md"><p>Recently started learning django guys so please drop ur top best GitHub django starting templates which u use to build ur apps</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SuStackx0"> /u/SuStackx0 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ip7ejh/starter_templates/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ip7ejh/starter_templates/">[comments]</a></span>

## Robust Auth-Service in Django
 - [https://www.reddit.com/r/django/comments/1ip33m1/robust_authservice_in_django](https://www.reddit.com/r/django/comments/1ip33m1/robust_authservice_in_django)
 - RSS feed: $source
 - date published: 2025-02-14T05:03:07+00:00

<!-- SC_OFF --><div class="md"><p>So i&#39;m splitting my projects into micro services and i need to make a Auth Service that will implement register user , login , logout, refreshToken ....</p> <p>so how can i make a robust auth service? should i just use plain django with jwt or DRF?</p> <p>for DRF i will need to learn it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/virgin_human"> /u/virgin_human </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ip33m1/robust_authservice_in_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ip33m1/robust_authservice_in_django/">[comments]</a></span>

## How to use Django like a Java developer
 - [https://www.reddit.com/r/django/comments/1ip2z0o/how_to_use_django_like_a_java_developer](https://www.reddit.com/r/django/comments/1ip2z0o/how_to_use_django_like_a_java_developer)
 - RSS feed: $source
 - date published: 2025-02-14T04:56:02+00:00

<!-- SC_OFF --><div class="md"><p>Ok, I&#39;m joking a bit in the title. </p> <p>But I know this is a somewhat controversial topic amongst Django developers: to stick it strict with implementing logic in Model/ModelManager, or start using services to help with that.</p> <p>I started out working with DRF sticking as strictly to the former &quot;official&quot; approach as much as possible, but over the years I have had to work on a couple Django projects that just got too complicated to maintain. The last couple of years I started to look at what other framework devs are doing, such as in Java and Go. At the end of the day, while I find other frameworks may be more verbose, they are actually cognitively simpler when given the same amount of complex business logic.</p> <p>I started to propose change of code designs in my last Django project (I was a lead developer on the project), to moved and re-organized our code over time with the goal of achieving this: <a href="https://gist.github.

## Is it easier for a data base admin to become a network engineer or vice versa?
 - [https://www.reddit.com/r/django/comments/1ip2ori/is_it_easier_for_a_data_base_admin_to_become_a](https://www.reddit.com/r/django/comments/1ip2ori/is_it_easier_for_a_data_base_admin_to_become_a)
 - RSS feed: $source
 - date published: 2025-02-14T04:39:06+00:00

<!-- SC_OFF --><div class="md"><p>The United States Marine Corps offers both of these jobs to reservists. </p> <p>I am a 28 year old who wants to get a decent paying job while getting his degree in computer science. </p> <p>My emphasis is on full stack dev then machine learning algorithms as I take more community college math classes. Which one of these two would be more helpful? Data base admins are called 0671 and networking engineers are 0631</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MarkDaShark6fitty"> /u/MarkDaShark6fitty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ip2ori/is_it_easier_for_a_data_base_admin_to_become_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ip2ori/is_it_easier_for_a_data_base_admin_to_become_a/">[comments]</a></span>

## StreamingHttpResponse some questions
 - [https://www.reddit.com/r/django/comments/1ioz4uc/streaminghttpresponse_some_questions](https://www.reddit.com/r/django/comments/1ioz4uc/streaminghttpresponse_some_questions)
 - RSS feed: $source
 - date published: 2025-02-14T01:25:48+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys. Im a miserable person trying to find some joy in programming.</p> <p>In my job Im currently trying to improve a view that sends lots of data in the response. The django API runs in a kubernetes cluster under the memory max of 2GB of its container. Sometimes the response exceeds this limits and the user never gets to see the results. So I heard that StreamingHttpResponse could allow this view to send the data into chunks to protect memory usage. On the frontend I use the EventSource from JS to establish the persistent http connection with the streaming view. But it seems it only works if I use an async view. When I use sync view, django loads everything into memory before sending the response. I dont understand why sync or async has something to do with sending the data into chunks.</p> <p>I’d really appreciate some help on this matter.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jutalor"> /u/Juta

## Rough Estimate or How to Estimate Hosting Costs for a Monolithic Django/HTMX/AlpineJS App with User Data & Social Features
 - [https://www.reddit.com/r/django/comments/1ioxr4y/rough_estimate_or_how_to_estimate_hosting_costs](https://www.reddit.com/r/django/comments/1ioxr4y/rough_estimate_or_how_to_estimate_hosting_costs)
 - RSS feed: $source
 - date published: 2025-02-14T00:15:41+00:00

<!-- SC_OFF --><div class="md"><p>Just trying to get an idea (and not sure how accurate ChatGPT was). Let us say I wanted to host (and this is just an example) a CRUD note taking app in which users can save their data, add friends, and view/bookmark each others notes. Built with Django/HTMX/AlpineJS, monolithic. How could I estimate the costs for:</p> <p>500 daily users, 1,000 daily users, 2,000 daily users, 10,000 users and etc.?</p> <p>Can provide more information if needed (since I know it really depends on how the application is structured and user behavior) but I just want to make a rough estimate. Plan on using PostgreSQL hosted on digital ocean app platform. Any rough estimates or tips on how to calculate an estimate would be much appreciated. </p> <p><a href="https://www.digitalocean.com/pricing/app-platform">https://www.digitalocean.com/pricing/app-platform</a></p> <p><a href="https://www.digitalocean.com/pricing/managed-databases">https://www.digitalocean.com/pricing/manage

