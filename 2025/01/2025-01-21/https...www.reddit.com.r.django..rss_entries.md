# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Docker + Django: Containerize the Right Way with Nginx, Postgresql & Gunicorn
 - [https://www.reddit.com/r/django/comments/1i6tkok/docker_django_containerize_the_right_way_with](https://www.reddit.com/r/django/comments/1i6tkok/docker_django_containerize_the_right_way_with)
 - RSS feed: $source
 - date published: 2025-01-21T21:16:55+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/JollyShopland"> /u/JollyShopland </a> <br/> <span><a href="https://youtu.be/1v3lqIITRJA">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6tkok/docker_django_containerize_the_right_way_with/">[comments]</a></span>

## Coolify your Django Project
 - [https://www.reddit.com/r/django/comments/1i6nxgh/coolify_your_django_project](https://www.reddit.com/r/django/comments/1i6nxgh/coolify_your_django_project)
 - RSS feed: $source
 - date published: 2025-01-21T17:27:32+00:00

<!-- SC_OFF --><div class="md"><p>I wrote an article on how to deploy a Django project with Coolify. It goes through all the phases: from creating a Django project with a postgres database up until deploying it.</p> <p><a href="https://fmacedo.com/posts/coolify-your-django-project/">https://fmacedo.com/posts/coolify-your-django-project/</a></p> <p>I haven&#39;t seen other tutorials on how to setup a postgres database in coolify and connect it to a Django project properly, so I hope this helps!</p> <p>Let me know if you have any suggestions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thirdmanonthemoon"> /u/thirdmanonthemoon </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6nxgh/coolify_your_django_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6nxgh/coolify_your_django_project/">[comments]</a></span>

## Django-CORS: Security & Best Practices
 - [https://www.reddit.com/r/django/comments/1i6myc7/djangocors_security_best_practices](https://www.reddit.com/r/django/comments/1i6myc7/djangocors_security_best_practices)
 - RSS feed: $source
 - date published: 2025-01-21T16:46:54+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/pyschille"> /u/pyschille </a> <br/> <span><a href="https://www.blueshoe.io/blog/django-cors-in-production/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6myc7/djangocors_security_best_practices/">[comments]</a></span>

## Help Needed: Adding Custom Messages to Structlog Logs and Best Practices for ElasticSearch Logging
 - [https://www.reddit.com/r/django/comments/1i6kh43/help_needed_adding_custom_messages_to_structlog](https://www.reddit.com/r/django/comments/1i6kh43/help_needed_adding_custom_messages_to_structlog)
 - RSS feed: $source
 - date published: 2025-01-21T15:00:45+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a project where logging is crucial. We&#39;re planning to write all logs to ElasticSearch. I&#39;ve set up structlog for logging, but I encountered an issue: the logs don’t include the custom &quot;message&quot; field as I expected.<br/> <strong>Here’s the current log output:</strong></p> <pre><code>{ &quot;code&quot;: 200, &quot;request&quot;: &quot;POST /api/push-notifications/subscribe/&quot;, &quot;event&quot;: &quot;request_finished&quot;, &quot;ip&quot;: &quot;127.0.0.1&quot;, &quot;request_id&quot;: &quot;d0edd77d-d68b-49d8-9d0d-87ee6ff723bf&quot;, &quot;user_id&quot;: &quot;98c78a2d-57f1-4caa-8b2a-8f5c4e295f95&quot;, &quot;timestamp&quot;: &quot;2025-01-21T10:40:43.233334Z&quot;, &quot;logger&quot;: &quot;django_structlog.middlewares.request&quot;, &quot;level&quot;: &quot;info&quot; } </code></pre> <p>I’d like to include a <code>&quot;message&quot;</code> field (e.g., <code>&quot;message&quot;: &quot;subscribed successfull

## London Django.Social Event - Thursday 30th January
 - [https://www.reddit.com/r/django/comments/1i6kbh3/london_djangosocial_event_thursday_30th_january](https://www.reddit.com/r/django/comments/1i6kbh3/london_djangosocial_event_thursday_30th_january)
 - RSS feed: $source
 - date published: 2025-01-21T14:53:48+00:00

<!-- SC_OFF --><div class="md"><p>If you are based in London and have an interest in Django, please come and join several members of the local community for a walk around Hyde Park. </p> <p>This is arranged for Thursday 30th January from 12:30pm </p> <p>Book a spot and let us know you are attending (so we wait for you) here: <a href="https://www.meetup.com/djangosocial-uk/events/305585567/">https://www.meetup.com/djangosocial-uk/events/305585567/</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JonG0uld"> /u/JonG0uld </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6kbh3/london_djangosocial_event_thursday_30th_january/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6kbh3/london_djangosocial_event_thursday_30th_january/">[comments]</a></span>

## Manually deque message from SQS.
 - [https://www.reddit.com/r/django/comments/1i6jz7h/manually_deque_message_from_sqs](https://www.reddit.com/r/django/comments/1i6jz7h/manually_deque_message_from_sqs)
 - RSS feed: $source
 - date published: 2025-01-21T14:38:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I am using Celery and SQS. I have defined a task function using celery&#39;s &quot;shared task&quot; decorator. But I need to acknowledge message immediately I received from the queue. So that message does not go to queue after it&#39;s visibility time is over. How can I do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/khanalfrompali"> /u/khanalfrompali </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6jz7h/manually_deque_message_from_sqs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6jz7h/manually_deque_message_from_sqs/">[comments]</a></span>

## Help choosing the right API for my AI project
 - [https://www.reddit.com/r/django/comments/1i6irdu/help_choosing_the_right_api_for_my_ai_project](https://www.reddit.com/r/django/comments/1i6irdu/help_choosing_the_right_api_for_my_ai_project)
 - RSS feed: $source
 - date published: 2025-01-21T13:38:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I am currently working on a project with LangGraph and Django for backend. It is simply a website where users need to login and upload their own data. Then they are provided with a code they can paste in their website that serves as a custom chatbot. I am having a hard time choosing which API framework to use. From what i have read django-ninja would be the best for my project since I need fast response time. But I also need a secure API with authentication capabilities so I’m wondering if I should use something else like DRF or FastAPI?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Miserable_Phrase6462"> /u/Miserable_Phrase6462 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6irdu/help_choosing_the_right_api_for_my_ai_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6irdu/help_choosing_the_right_api_for_my_ai_project/">[comments]</a></span>

## reddit as database!!!
 - [https://www.reddit.com/r/django/comments/1i6al5x/reddit_as_database](https://www.reddit.com/r/django/comments/1i6al5x/reddit_as_database)
 - RSS feed: $source
 - date published: 2025-01-21T04:32:04+00:00

<!-- SC_OFF --><div class="md"><p>sometimes while making any application i just thought we always use SQL, PSQL as database, but let&#39;s imagine a hypothetical situation, t let say a nerd just making reddit as his database... LOL.. </p> <p>LOL or not LOL.. but what do you think, what are the challenges gonna occur and how can he able to tackle it ...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hour-Echo-9680"> /u/Hour-Echo-9680 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i6al5x/reddit_as_database/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i6al5x/reddit_as_database/">[comments]</a></span>

