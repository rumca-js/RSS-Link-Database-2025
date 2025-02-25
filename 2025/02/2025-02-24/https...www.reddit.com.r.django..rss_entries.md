# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## What the best way to host django,celery workers ?
 - [https://www.reddit.com/r/django/comments/1ixeh4u/what_the_best_way_to_host_djangocelery_workers](https://www.reddit.com/r/django/comments/1ixeh4u/what_the_best_way_to_host_djangocelery_workers)
 - RSS feed: $source
 - date published: 2025-02-24T22:06:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I am using celery as background worker for my django app. and I am really looking for better way to host. Now i am using vps with docker-compose. Any solution? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Any-Data1138"> /u/Any-Data1138 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ixeh4u/what_the_best_way_to_host_djangocelery_workers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ixeh4u/what_the_best_way_to_host_djangocelery_workers/">[comments]</a></span>

## Authenticating against Azure via active directory/SAML?
 - [https://www.reddit.com/r/django/comments/1ixc4a7/authenticating_against_azure_via_active](https://www.reddit.com/r/django/comments/1ixc4a7/authenticating_against_azure_via_active)
 - RSS feed: $source
 - date published: 2025-02-24T20:30:35+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to authenticate against an active directory using SAML. My last experience with AD is 12 years ago so I&#39;m a bit lost and banging my head against a wall. </p> <p>I&#39;ve been given an application ID (Entra ID?) and a tenant ID. I have attempted to use django-auth-ldap, but I think that is not focused on SAML. So I switched to django-saml2-auth. I see a place in that package to configure EntityID, but nothing about tenant ID. So now I&#39;m concerned that I might be going down the wrong road once more.</p> <p>I found this excellent video from BugBytes that helped me understand some of the concepts, but I didn&#39;t see anything about SAML (or I do not understand.) <a href="https://www.youtube.com/watch?v=t02stKhdxi4">https://www.youtube.com/watch?v=t02stKhdxi4</a></p> <p>Do you have any advice for how I can use an application ID and tenant ID to configure my django app to authenticate against AD? Or where I can go to educate myself abo

## High memory usage on delete
 - [https://www.reddit.com/r/django/comments/1ixb489/high_memory_usage_on_delete](https://www.reddit.com/r/django/comments/1ixb489/high_memory_usage_on_delete)
 - RSS feed: $source
 - date published: 2025-02-24T19:50:36+00:00

<!-- SC_OFF --><div class="md"><p>Tldr at button. </p> <p>My app usually consumes upto 300MB of memory but as you can see it sky rockets when I delete a large number of objects. I mistakenly created 420k objects of 3 types so about 2,5 million rows (note to self never use django polymorphic again) + 2,5 million m2m rows. Dumb on my part, poor testing, I know. To fix it I prepared a qs.delete() and expected a rather quick result but instead it takes half an hour and I notice the app (container 1) and postgres (container 2) taking huge amounts of cpu and memory resources, taking turns at it. As I&#39;m writing this post it is still going strong at 10GB of memory. I&#39;ve already had the container exit before because it was out of memory at the third QSs delete and apparently the memes about python garbage collection are true because it chugs along fine after a restart of the container. I&#39;ve read some blogs on slow delete performance and come to understand Django is doing a lot of 

## What’s your opinion on using sessions with REST framework?
 - [https://www.reddit.com/r/django/comments/1ix94lf/whats_your_opinion_on_using_sessions_with_rest](https://www.reddit.com/r/django/comments/1ix94lf/whats_your_opinion_on_using_sessions_with_rest)
 - RSS feed: $source
 - date published: 2025-02-24T18:29:20+00:00

<!-- SC_OFF --><div class="md"><p>By definition, a REST API shouldn’t store state, and the default authentication on DRF uses tokens, but I have been advised to use sessions to improve security without having to deal with JWT. Is it a bad practice to do so? Is it hard to implement? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rippedMorty"> /u/rippedMorty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix94lf/whats_your_opinion_on_using_sessions_with_rest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix94lf/whats_your_opinion_on_using_sessions_with_rest/">[comments]</a></span>

## Minify and Compress JS
 - [https://www.reddit.com/r/django/comments/1ix8h1a/minify_and_compress_js](https://www.reddit.com/r/django/comments/1ix8h1a/minify_and_compress_js)
 - RSS feed: $source
 - date published: 2025-02-24T18:03:14+00:00

<!-- SC_OFF --><div class="md"><p>Guys,</p> <p>What are you using to compress JS?</p> <p>I tried django-compressor today, works well locally but couldn&#39;t get it working on heroku, it will not copy files.</p> <p>I use tailwind for the CSS which is fine.</p> <p>It seems people are using a mixture of Django pipeline, webassets or npm build step.</p> <p>Before trying them I wanted to see what most use.</p> <p>Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Babayaga1664"> /u/Babayaga1664 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix8h1a/minify_and_compress_js/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix8h1a/minify_and_compress_js/">[comments]</a></span>

## What method of authentication do you prefer for REST framework?
 - [https://www.reddit.com/r/django/comments/1ix7v85/what_method_of_authentication_do_you_prefer_for](https://www.reddit.com/r/django/comments/1ix7v85/what_method_of_authentication_do_you_prefer_for)
 - RSS feed: $source
 - date published: 2025-02-24T17:39:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am working on an API that will be consumed by a web and a mobile app. I need granular permissions for each user. I know that DRF has its own built in auth method, but I want to explore all the available options, incluiding paid third party solutions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rippedMorty"> /u/rippedMorty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix7v85/what_method_of_authentication_do_you_prefer_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix7v85/what_method_of_authentication_do_you_prefer_for/">[comments]</a></span>

## Project idea
 - [https://www.reddit.com/r/django/comments/1ix7nu2/project_idea](https://www.reddit.com/r/django/comments/1ix7nu2/project_idea)
 - RSS feed: $source
 - date published: 2025-02-24T17:31:19+00:00

<!-- SC_OFF --><div class="md"><p>Someone, please give me a project idea so that I can upgrade my skills.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Conscious-Network-45"> /u/Conscious-Network-45 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix7nu2/project_idea/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix7nu2/project_idea/">[comments]</a></span>

## How to make DJango learning as addictive as video games? HELP PLEASE!
 - [https://www.reddit.com/r/django/comments/1ix7fjm/how_to_make_django_learning_as_addictive_as_video](https://www.reddit.com/r/django/comments/1ix7fjm/how_to_make_django_learning_as_addictive_as_video)
 - RSS feed: $source
 - date published: 2025-02-24T17:21:57+00:00

<!-- SC_OFF --><div class="md"><p>SO I am tryna learn django to change my career from teaching English to coding. But, during my free time, I mostly spend it playing video games like fortnite, valorant, PUBG, chess,etc. How to overcome this addiction and focus myself in coding? Please help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ek_aprichit"> /u/Ek_aprichit </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix7fjm/how_to_make_django_learning_as_addictive_as_video/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix7fjm/how_to_make_django_learning_as_addictive_as_video/">[comments]</a></span>

## Custom Django User models
 - [https://www.reddit.com/r/django/comments/1ix4dln/custom_django_user_models](https://www.reddit.com/r/django/comments/1ix4dln/custom_django_user_models)
 - RSS feed: $source
 - date published: 2025-02-24T15:16:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am new to Django and I want to know how to create a custom Django User models base on default Django User.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ALEX225civ"> /u/ALEX225civ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ix4dln/custom_django_user_models/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ix4dln/custom_django_user_models/">[comments]</a></span>

## [Release] ninja-keys: API Keys for django-ninja
 - [https://www.reddit.com/r/django/comments/1ix3yfm/release_ninjakeys_api_keys_for_djangoninja](https://www.reddit.com/r/django/comments/1ix3yfm/release_ninjakeys_api_keys_for_djangoninja)
 - RSS feed: $source
 - date published: 2025-02-24T14:58:22+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I just released <a href="https://github.com/feliperalmeida/ninja-keys"><code>ninja-keys</code></a> on <a href="https://pypi.org/project/ninja-keys/">PyPI</a>! It is Django app that adds API Key support to <strong>django-ninja</strong> and makes it easier to manage API keys for users, organizations, or machines.</p> <p>🔹 Simple integration with django-ninja<br/> 🔹 Highly customizable and easy to integrate with other models (such as User or Organization)<br/> 🔹 API Keys can be created via `/admin` or programmatically<br/> 🔹 Can be set globally or per view/router using django-ninja&#39;s `auth` property<br/> 🔹 Based on the battle-tested <a href="https://github.com/florimondmanca/djangorestframework-api-key">djangorestframework-api-key</a></p> <p>Check it out on GitHub: <a href="https://github.com/feliperalmeida/ninja-keys">github.com/feliperalmeida/ninja-keys</a><br/> Let me know what you think or if you have any feature requests! 🚀

## LiveUpdates Package?
 - [https://www.reddit.com/r/django/comments/1ix3owm/liveupdates_package](https://www.reddit.com/r/django/comments/1ix3owm/liveupdates_package)
 - RSS feed: $source
 - date published: 2025-02-24T14:46:27+00:00

<!-- SC_OFF --><div class="md"><p>I use django now for a few projects (including a profesional one) and what bugs me a bit that i cannot find a simple integration of live updates. I have built the functionality in one project using channels &amp; websockets but it feels like a lot of custom code and there is not a simple &quot;add liveupdates&quot; functionality. My implementation works only if websockets are available, Socket.io would be a library which would automatically switch between http polling &amp; ws and might be a great basis for liveupdates eventought might have scaling issues at &gt;10k users. ServerSent Events would be another possibility. I see a few projects which have tried this but all of them are outdated.</p> <p>Why isn&#39;t there a standardized way to do this? How are others doing it?</p> <p>Would there be interest in a package providing this functionality?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mlorin"> /u/mlorin 

## Should I learn Django or stay with Spring Boot?
 - [https://www.reddit.com/r/django/comments/1ix0mts/should_i_learn_django_or_stay_with_spring_boot](https://www.reddit.com/r/django/comments/1ix0mts/should_i_learn_django_or_stay_with_spring_boot)
 - RSS feed: $source
 - date published: 2025-02-24T12:14:03+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not a native English writer, so I may have some mistakes here. I see that these days everyone use Python for AI and other programming languages for building APIs, mostly JavaScript (Node.js), GO and Python. I know Python and I want to go into the field of AI in the future, but I also started to study Spring Boot, and I&#39;m taking a second course about it, and reading &quot;Spring in Action&quot;. I consider moving to building web apps with Django - Python, and that the usage of scripting programming languages will grow, even though I like Java a lot. Do you think it&#39;s a good idea to move to Python completely, or should I study two web frameworks in two programming languages? I also see that Django is much more used in startups, that also pay more, and this is also something to consider.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Traditional-Car-738"> /u/Traditional-Car-738 </a> <br/> <span><a 

## How to deploy Django + Angular on GCP?
 - [https://www.reddit.com/r/django/comments/1iwzl5h/how_to_deploy_django_angular_on_gcp](https://www.reddit.com/r/django/comments/1iwzl5h/how_to_deploy_django_angular_on_gcp)
 - RSS feed: $source
 - date published: 2025-02-24T11:07:21+00:00

<!-- SC_OFF --><div class="md"><p>Is there any good videos/guide on such topic?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Notalabel_4566"> /u/Notalabel_4566 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iwzl5h/how_to_deploy_django_angular_on_gcp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iwzl5h/how_to_deploy_django_angular_on_gcp/">[comments]</a></span>

## Django dev looking to contribute to your personal projects
 - [https://www.reddit.com/r/django/comments/1iwzgqa/django_dev_looking_to_contribute_to_your_personal](https://www.reddit.com/r/django/comments/1iwzgqa/django_dev_looking_to_contribute_to_your_personal)
 - RSS feed: $source
 - date published: 2025-02-24T10:59:46+00:00

<!-- SC_OFF --><div class="md"><p>Hey Djangonauts,</p> <p>I&#39;m a developer with 3 YOE in Django and DRF, and I&#39;m always looking to expand my knowledge and skills within the Django ecosystem.</p> <p>I&#39;m currently looking for a personal project (or a side project) to contribute to in my free time. I have a few hours a week I can dedicate and would love to help bring your ideas to life (or improve existing ones!).</p> <p>If you have a project that you think would be a good fit, please feel free to comment below or send me a DM :D</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/1200isplenty"> /u/1200isplenty </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iwzgqa/django_dev_looking_to_contribute_to_your_personal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iwzgqa/django_dev_looking_to_contribute_to_your_personal/">[comments]</a></span>

## Django Devs: What do you wish your project had in place before you were hired?
 - [https://www.reddit.com/r/django/comments/1iwz88b/django_devs_what_do_you_wish_your_project_had_in](https://www.reddit.com/r/django/comments/1iwz88b/django_devs_what_do_you_wish_your_project_had_in)
 - RSS feed: $source
 - date published: 2025-02-24T10:42:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m considering starting a start-up web project that will likely have to be built on a framework such as Django. </p> <p>As I&#39;m in the very early concept phase, I&#39;m looking to understand what information and level of detail I should have in place before hiring my first dev, (and/ or if a Django dev is a cost effective way of helping me take it from concept to a clear plan, before execution)? </p> <p>I&#39;d also be keen to understand if I&#39;d need any other types of resource/ roles to get going, or if a Django dev is all that I&#39;d need. Any sort of guidance on start up documentation I should have completed or suggests from this experienced community would be greatly appreciated! Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zee_0"> /u/Zee_0 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iwz88b/django_devs_what_do_you_wish_your_project_had_in/">[link]</a></span> &#

## Working with counties and cities
 - [https://www.reddit.com/r/django/comments/1iwyxvs/working_with_counties_and_cities](https://www.reddit.com/r/django/comments/1iwyxvs/working_with_counties_and_cities)
 - RSS feed: $source
 - date published: 2025-02-24T10:23:01+00:00

<!-- SC_OFF --><div class="md"><p>I instaled django-cities-light and quiet enough for my need but is missing zip codes. I know about django-cities package, but seams is to much for my needs. Is there any other solution I could check? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/luigibu"> /u/luigibu </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iwyxvs/working_with_counties_and_cities/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iwyxvs/working_with_counties_and_cities/">[comments]</a></span>

## Call for Proposals for DjangoCon Africa 2025 is now open!
 - [https://www.reddit.com/r/django/comments/1iwxxdz/call_for_proposals_for_djangocon_africa_2025_is](https://www.reddit.com/r/django/comments/1iwxxdz/call_for_proposals_for_djangocon_africa_2025_is)
 - RSS feed: $source
 - date published: 2025-02-24T09:11:21+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/feb/24/cfp-for-djangocon-africa-2025-is-now-open/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iwxxdz/call_for_proposals_for_djangocon_africa_2025_is/">[comments]</a></span>

## Django + React + Vite demo project
 - [https://www.reddit.com/r/django/comments/1iwxt5k/django_react_vite_demo_project](https://www.reddit.com/r/django/comments/1iwxt5k/django_react_vite_demo_project)
 - RSS feed: $source
 - date published: 2025-02-24T09:02:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve put together a small demo project of a Django/React application using Vite and Django Bridge: <a href="https://github.com/django-bridge/django-react-cms">https://github.com/django-bridge/django-react-cms</a></p> <p>Hope this helps anyone looking to start a new project!</p> <p>There is a version of it hosted here: <a href="https://demo.django-bridge.org">https://demo.django-bridge.org</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kaedroho"> /u/kaedroho </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iwxt5k/django_react_vite_demo_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iwxt5k/django_react_vite_demo_project/">[comments]</a></span>

## rabbitMQ cluster failover for celery does not work..
 - [https://www.reddit.com/r/django/comments/1iwruxi/rabbitmq_cluster_failover_for_celery_does_not_work](https://www.reddit.com/r/django/comments/1iwruxi/rabbitmq_cluster_failover_for_celery_does_not_work)
 - RSS feed: $source
 - date published: 2025-02-24T02:50:39+00:00

<!-- SC_OFF --><div class="md"><p>hi.. I set up rabbitMQ(v.4.0) and celery.. and I run 3 rabbitMQ nodes and put into the same cluster.</p> <p><code>rabbitmqctl stop_app</code></p> <p><code>rabbitmqctl reset</code></p> <p><code>rabbitmqctl start_app</code></p> <p><code>rabbitmqctl join_cluster rabbit@rabbitmq-1</code></p> <p>celery settings are:</p> <pre><code>CELERY_BROKER_URL = [ &#39;amqp://guest:guest@rabbitmq-1:5672//&#39;, &#39;amqp://guest:guest@rabbitmq-2:5672//&#39;, &#39;amqp://guest:guest@rabbitmq-3:5672//&#39; ] CELERY_RESULT_BACKEND = &#39;rpc://&#39; CELERY_ACCEPT_CONTENT = [&#39;application/json&#39;] CELERY_RESULT_SERIALIZER = &#39;json&#39; CELERY_TASK_SERIALIZER = &#39;json&#39; </code></pre> <p>I can see nodes in the cluster in localhost:5672// rabbitmq dashboard..</p> <p>since rabbitmq 4.0, ha policy has been removed.. so all Queues are quorum.. for mirrored message.</p> <p>I think I have set correctly.. but when I stop the first rabbitmq server, celery returns err

