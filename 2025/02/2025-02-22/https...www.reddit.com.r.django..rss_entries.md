# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Having issue with Google Login with flutter front end --> Django using DJ-rest-auth, django-allauth
 - [https://www.reddit.com/r/django/comments/1ivvupm/having_issue_with_google_login_with_flutter_front](https://www.reddit.com/r/django/comments/1ivvupm/having_issue_with_google_login_with_flutter_front)
 - RSS feed: $source
 - date published: 2025-02-22T23:13:03+00:00

<!-- SC_OFF --><div class="md"><p>the error:<br/> raise OAuth2Error(&quot;Request to user info failed&quot;)</p> <p>allauth.socialaccount.providers.oauth2.client.OAuth2Error: Request to user info failed</p> <pre><code>final response = await http.post( loginurl, body: json.encode( { &#39;access_token&#39;: token, //&#39;id_token&#39;: tokentype == &#39;idtoken&#39; ? token : &#39;&#39;, }, ), headers: { &quot;content-type&quot;: &quot;application/json&quot;, &quot;accept&quot;: &quot;application/json&quot;, }, ).timeout(const Duration(seconds: 10), onTimeout: () { throw apiFailure(message: &#39;Timeout&#39;, code: 430); }); </code></pre> <p>I send an id token to the back end. </p> <pre><code>GOOGLE_CALLBACK_URL=&quot;http://127.0.0.1:8000/api/dj-rest-auth/google/callback/&quot; class GoogleLogin(SocialLoginView): adapter_class = GoogleOAuth2Adapter client_class = OAuth2Client callback_url = settings.GOOGLE_CALLBACK_URL SOCIALACCOUNT_PROVIDERS = { &#39;google&#39;: { #&#39;FETCH_USERIN

## Very small web server: SQLite or PostgreSQL?
 - [https://www.reddit.com/r/django/comments/1ivvs5k/very_small_web_server_sqlite_or_postgresql](https://www.reddit.com/r/django/comments/1ivvs5k/very_small_web_server_sqlite_or_postgresql)
 - RSS feed: $source
 - date published: 2025-02-22T23:09:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi devs! :) I am trying to build a simple license server in Django with 2 goals: 1. create and manage license keys, 2. verify license keys of client apps. The project currently has 0 customers and will have max 50-100 customers (client apps) needing verification in ~2 years. The client app will verify license at a few points during its run (start of client app, random check or maybe when user will use an expensive feature like object detection task in my client app). My biggest challenge is not over-engineering things to keep it light, simple but production-ready (meaning actually using the system to verify user license info with basic security in mind).</p> <p>In this case, would you recommend using SQLite or PostgreSQL? What would you say are the pros and cons?</p> <p>More context: I am a beginner at Django. I have several years of data science experience in python. I have the client built in PySide6. I am planning to host the server on an affordab

## Is this true?
 - [https://www.reddit.com/r/django/comments/1ivv74t/is_this_true](https://www.reddit.com/r/django/comments/1ivv74t/is_this_true)
 - RSS feed: $source
 - date published: 2025-02-22T22:42:16+00:00

<!-- SC_OFF --><div class="md"><p>Was listening to ThePrimeAgen and he said something along the lines of:</p> <p><em>&quot;Unless your web-app has 10 million daily active users aka 30 concurrent read/write operations just use SQlite.&quot;</em></p> <p>Curious if this is accurate?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Docs_For_Developers"> /u/Docs_For_Developers </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivv74t/is_this_true/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivv74t/is_this_true/">[comments]</a></span>

## Moving from Flask to Django, need help with best folder practices.
 - [https://www.reddit.com/r/django/comments/1ivuts9/moving_from_flask_to_django_need_help_with_best](https://www.reddit.com/r/django/comments/1ivuts9/moving_from_flask_to_django_need_help_with_best)
 - RSS feed: $source
 - date published: 2025-02-22T22:25:00+00:00

<!-- SC_OFF --><div class="md"><p>So I have decided to move from Flask to a more fully fleshed out framework like Django and was wondering on how the folder structure should be. See in Flask I would just have a routes folder with various routes and then use blueprint to import them. But from my research it seems like Django uses a folder based routing system with each folder containing its own veiws, models, etc.</p> <p>Is it best practice to use folder based routing for different API routes, I am currently using it with React. Or can I create a single &quot;routes&quot; folder and then put all of the folder routes inside of that one route folder so that way I don&#39;t have a bunch of folders cluttering my project folder.</p> <p>This is what I currently have, My Server project folder, then messages, users, and tasks for routes.</p> <p><a href="https://preview.redd.it/7h0h4x5lnrke1.png?width=174&amp;format=png&amp;auto=webp&amp;s=1e09bc289c0fd911522326078907f3b36bd97e46">https://prev

## Django Background task library comparison
 - [https://www.reddit.com/r/django/comments/1ivu6ep/django_background_task_library_comparison](https://www.reddit.com/r/django/comments/1ivu6ep/django_background_task_library_comparison)
 - RSS feed: $source
 - date published: 2025-02-22T21:55:30+00:00

<!-- SC_OFF --><div class="md"><p>How does the following Background task queue library compare? I am looking at background/asynchronous task queue, orchestration of tasks ( kind of DAG, but not too complicated) and scheduling functionality. Monitoring would be nice, but not at the expense of running another service.</p> <ol> <li>Celery based task queue with Flower monitoring, or Django built-in</li> <li><a href="https://github.com/django/deps/blob/main/accepted/0014-background-workers.rst">DEP 0014</a> proposed as one of the battery in Django. Not sure if it is released.</li> <li>django-q2 - It doesn&#39;t require another broker and uses django-ORM.</li> <li>prefect - Originally written as ETL platform. But, it seems to work just fine for <a href="https://www.prefect.io/blog/background-tasks-why-they-matter-in-prefect">background tasks</a> as well.</li> <li><a href="https://dramatiq.io/">dramatiq</a></li> </ol> <p>Does anyone has experience, It would be quite a task to try these out 

## What are some of the challenges that you experience?
 - [https://www.reddit.com/r/django/comments/1ivto1r/what_are_some_of_the_challenges_that_you](https://www.reddit.com/r/django/comments/1ivto1r/what_are_some_of_the_challenges_that_you)
 - RSS feed: $source
 - date published: 2025-02-22T21:32:15+00:00

<!-- SC_OFF --><div class="md"><p>Keen to learn what pain points others experience when it comes to using Django for API development.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Material-Ingenuity-5"> /u/Material-Ingenuity-5 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivto1r/what_are_some_of_the_challenges_that_you/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivto1r/what_are_some_of_the_challenges_that_you/">[comments]</a></span>

## Why is Django so hard to learn?
 - [https://www.reddit.com/r/django/comments/1ivsz2l/why_is_django_so_hard_to_learn](https://www.reddit.com/r/django/comments/1ivsz2l/why_is_django_so_hard_to_learn)
 - RSS feed: $source
 - date published: 2025-02-22T21:01:28+00:00

<!-- SC_OFF --><div class="md"><p>Every tutorial has a different way of doing thing like creating a project… I find the documentation not very helpful it doesn’t explain the why it’s doing something. I’ve done 2 walkthroughs and it seems like I’ve learned next to nothing. I tried to start a project without help and its isn’t going well. Ive spent about 15 hours learning this technology and made little to no progress. Any tips? I should also mention I’ve been trying to make apis with the rest-framework.</p> <p>Sources I’ve been using are w3schools,Django documentation, YouTube videos</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate_Shirt42"> /u/Affectionate_Shirt42 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivsz2l/why_is_django_so_hard_to_learn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivsz2l/why_is_django_so_hard_to_learn/">[comments]</a></span>

## Database Backup
 - [https://www.reddit.com/r/django/comments/1ivr4r7/database_backup](https://www.reddit.com/r/django/comments/1ivr4r7/database_backup)
 - RSS feed: $source
 - date published: 2025-02-22T19:40:19+00:00

<!-- SC_OFF --><div class="md"><p>What&#39;s your go-to solution for a Postgres database backup? I would like to explore some options, I am using docker compose to Postgres container and Django. I have mounted the Postgres data.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/to_sta"> /u/to_sta </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivr4r7/database_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivr4r7/database_backup/">[comments]</a></span>

## WHAT ARE THE PAIN POINTS DJANGO DEVS FACE WHILE BUILDING SOFTWARE
 - [https://www.reddit.com/r/django/comments/1ivox58/what_are_the_pain_points_django_devs_face_while](https://www.reddit.com/r/django/comments/1ivox58/what_are_the_pain_points_django_devs_face_while)
 - RSS feed: $source
 - date published: 2025-02-22T18:06:11+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been learning django now this is my fourth year, and i&#39;m building a product with it. But along the way i have faced a variety of challenges like: Building seamless RESTful APIs; Optmizing database queries; Running security Audits to make sure my app is secure. Just to mention a few, in return my second product to be built is DDT django developer toolkit aiming to simplify django developement and improving productivity for my best framework.</p> <p>So any problems or challenges you face are welcome, i&#39;m dedicated to build this product. And hope you&#39;ll all love it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Soggy-Crab-3355"> /u/Soggy-Crab-3355 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivox58/what_are_the_pain_points_django_devs_face_while/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivox58/what_are_the_pain_points_django_devs

## Issues Running Django Commands on DO’s OpenLiteSpeed Image – Root Ownership problem?
 - [https://www.reddit.com/r/django/comments/1ivmssl/issues_running_django_commands_on_dos](https://www.reddit.com/r/django/comments/1ivmssl/issues_running_django_commands_on_dos)
 - RSS feed: $source
 - date published: 2025-02-22T16:38:41+00:00

<!-- SC_OFF --><div class="md"><p>I started building my Django app using the default project that comes with the OpenLiteSpeed image on DigitalOcean. However, I ran into an issue—my <strong>sudo user can’t run any Django commands</strong> (like <code>manage.py</code>).</p> <p>After checking the file structure, I realized that <strong>everything is owned by root</strong>. I’m guessing this is why my sudo user doesn’t have the necessary permissions.</p> <p>Should I just <code>chown</code> <strong>the project folder</strong> to my sudo user, or is there something else I need to change for full control? Would it be easier to just <strong>start a new project</strong> under my sudo user so I don’t run into permission issues?</p> <p>Any advice would be much appreciated. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PalpitationFalse8731"> /u/PalpitationFalse8731 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivmssl/issues_

## Roast My Resume !!
 - [https://www.reddit.com/r/django/comments/1ivlldc/roast_my_resume](https://www.reddit.com/r/django/comments/1ivlldc/roast_my_resume)
 - RSS feed: $source
 - date published: 2025-02-22T15:46:49+00:00

<!-- SC_OFF --><div class="md"><p>Hey am a 2nd year Undergraduate Student currently am in my 4th sem and am looking to apply for internship remote for django and python Please guide me through my resume should I add one more project ?? What more changes should I made ??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ArcEus_2004"> /u/ArcEus_2004 </a> <br/> <span><a href="https://i.redd.it/rcy7ootmopke1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivlldc/roast_my_resume/">[comments]</a></span>

## Local + GitHub + vps deployment
 - [https://www.reddit.com/r/django/comments/1ivl7g3/local_github_vps_deployment](https://www.reddit.com/r/django/comments/1ivl7g3/local_github_vps_deployment)
 - RSS feed: $source
 - date published: 2025-02-22T15:29:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I was working locally on a Django Rest API, when I deployed to my VPS I had to start making changes there because it wasn&#39;t easy to do the whole commit to GitHub and deploy to the VPS, I had to make specific changes for the production server.</p> <p>But I&#39;m finding it&#39;s kind of a hassle to work only on the VPS and I don&#39;t like that I&#39;m not versioning anything.</p> <p>Before I continue and make a mess, I&#39;d like to know how do you guys and gals work locally, then commit to GitHub and then deploy with different tweaks.</p> <p>When I&#39;m talking about tweaks, I&#39;m talking about changing origin servers, making Allow_all_origins to false, running gunicorn socket.. etc.. I&#39;d like to do all this automatically </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/neocorps"> /u/neocorps </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivl7g3/local_githu

## If I re-deploy Rabbit MQ into ECS, will all messages disappear?
 - [https://www.reddit.com/r/django/comments/1ivjset/if_i_redeploy_rabbit_mq_into_ecs_will_all](https://www.reddit.com/r/django/comments/1ivjset/if_i_redeploy_rabbit_mq_into_ecs_will_all)
 - RSS feed: $source
 - date published: 2025-02-22T14:22:03+00:00

<!-- SC_OFF --><div class="md"><p>I use rabbitMQ for celery and about to set up container in ECS..</p> <p>I realized that messages in RabbitMQ is not persistent.. what if I deploy MQ server again with a docker image? will all messages be gone? what should I do? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivjset/if_i_redeploy_rabbit_mq_into_ecs_will_all/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivjset/if_i_redeploy_rabbit_mq_into_ecs_will_all/">[comments]</a></span>

## I'm referring fresher django developers in Pune India
 - [https://www.reddit.com/r/django/comments/1ivivnm/im_referring_fresher_django_developers_in_pune](https://www.reddit.com/r/django/comments/1ivivnm/im_referring_fresher_django_developers_in_pune)
 - RSS feed: $source
 - date published: 2025-02-22T13:36:23+00:00

<!-- SC_OFF --><div class="md"><p>DM me Google drive link of your resume and I&#39;ll forward it to hr.</p> <p>It&#39;s a service based mnc based in viman Nagar Pune. </p> <p>Full time role: 4.5 LPA Internship also available with stipend.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zakhreef"> /u/zakhreef </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivivnm/im_referring_fresher_django_developers_in_pune/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivivnm/im_referring_fresher_django_developers_in_pune/">[comments]</a></span>

## Host your Django project for free on render
 - [https://www.reddit.com/r/django/comments/1ivioiy/host_your_django_project_for_free_on_render](https://www.reddit.com/r/django/comments/1ivioiy/host_your_django_project_for_free_on_render)
 - RSS feed: $source
 - date published: 2025-02-22T13:26:05+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Crazy-Middle-6383"> /u/Crazy-Middle-6383 </a> <br/> <span><a href="https://youtu.be/2d8Gh8tKos0?si=epDH9IYqDuOOSEtl">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivioiy/host_your_django_project_for_free_on_render/">[comments]</a></span>

## Django for beginners Tutorial
 - [https://www.reddit.com/r/django/comments/1ivihow/django_for_beginners_tutorial](https://www.reddit.com/r/django/comments/1ivihow/django_for_beginners_tutorial)
 - RSS feed: $source
 - date published: 2025-02-22T13:15:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Crazy-Middle-6383"> /u/Crazy-Middle-6383 </a> <br/> <span><a href="https://youtu.be/T8WV7-I-3dM">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivihow/django_for_beginners_tutorial/">[comments]</a></span>

## Build a Blog App with Django. Follow this link to watch the full tutorial on YouTube
 - [https://www.reddit.com/r/django/comments/1ivifmt/build_a_blog_app_with_django_follow_this_link_to](https://www.reddit.com/r/django/comments/1ivifmt/build_a_blog_app_with_django_follow_this_link_to)
 - RSS feed: $source
 - date published: 2025-02-22T13:12:43+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Crazy-Middle-6383"> /u/Crazy-Middle-6383 </a> <br/> <span><a href="https://youtu.be/T8WV7-I-3dM">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivifmt/build_a_blog_app_with_django_follow_this_link_to/">[comments]</a></span>

## Setup Help!!!
 - [https://www.reddit.com/r/django/comments/1ive8ke/setup_help](https://www.reddit.com/r/django/comments/1ive8ke/setup_help)
 - RSS feed: $source
 - date published: 2025-02-22T08:29:28+00:00

<!-- SC_OFF --><div class="md"><p>I was working on a django project and for some reason i uninstalled python and then reinstalled a different version. Now i want to resume my django project how do i set it up ??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kakarot11x"> /u/Kakarot11x </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ive8ke/setup_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ive8ke/setup_help/">[comments]</a></span>

## Please update django with new features just like php & rails
 - [https://www.reddit.com/r/django/comments/1ive11f/please_update_django_with_new_features_just_like](https://www.reddit.com/r/django/comments/1ive11f/please_update_django_with_new_features_just_like)
 - RSS feed: $source
 - date published: 2025-02-22T08:14:18+00:00

<!-- SC_OFF --><div class="md"><p>I used all 3 framework, </p> <p>Laravel Ruby on rails Django</p> <p>I like django but can we get some update now. </p> <p>In laravel you can use Inertia js, livewire and have great support for everything.</p> <p>In ruby on rails you have crud scaffolding, hotwire, channel you just add one line code to have update in real time.</p> <p>I love django and how simple it is but please update django, django needs great features just like laravel and rails.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/himynameisAhhhh"> /u/himynameisAhhhh </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ive11f/please_update_django_with_new_features_just_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ive11f/please_update_django_with_new_features_just_like/">[comments]</a></span>

## railways
 - [https://www.reddit.com/r/django/comments/1ivd9b6/railways](https://www.reddit.com/r/django/comments/1ivd9b6/railways)
 - RSS feed: $source
 - date published: 2025-02-22T07:19:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys i am trying to deploy my hobby project in railways. DB is supabase. i checked everyting in local and ran my application perfectly but when i host it in railways it says cannot connect to my supabase. Can any one give me an idea about this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kushal21346"> /u/kushal21346 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ivd9b6/railways/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ivd9b6/railways/">[comments]</a></span>

## I'm unemployed developer
 - [https://www.reddit.com/r/django/comments/1iv9c7n/im_unemployed_developer](https://www.reddit.com/r/django/comments/1iv9c7n/im_unemployed_developer)
 - RSS feed: $source
 - date published: 2025-02-22T03:21:30+00:00

<!-- SC_OFF --><div class="md"><p>I know web development with mern stack, python django and mobile application development with react native.</p> <p>Is there any freelance clients or software agencies who can help me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/virgin_human"> /u/virgin_human </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iv9c7n/im_unemployed_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iv9c7n/im_unemployed_developer/">[comments]</a></span>

