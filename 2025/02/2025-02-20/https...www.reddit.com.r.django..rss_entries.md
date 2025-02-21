# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Any tips to get a Django site approved for google ads?
 - [https://www.reddit.com/r/django/comments/1iu93ju/any_tips_to_get_a_django_site_approved_for_google](https://www.reddit.com/r/django/comments/1iu93ju/any_tips_to_get_a_django_site_approved_for_google)
 - RSS feed: $source
 - date published: 2025-02-20T20:54:49+00:00

<!-- SC_OFF --><div class="md"><p>I’ve done quite a few things trying to get a site approved for ads and nothing seems to work. The verification is successful in all three methods ads.txt, meta tag, code script. The site has original content, no longer “in construction” or with ipsum texts. I did not add the codes in dead pages such as login or alert screens. I lastly checked if maybe some of the security settings could be affecting but they none is blocking google. And my robots specifically allow Google crawlers. Running out of ideas. Would appreciate any thoughts. If you want to check the site feel free.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yeurymel"> /u/yeurymel </a> <br/> <span><a href="https://sombreros-ole.com">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iu93ju/any_tips_to_get_a_django_site_approved_for_google/">[comments]</a></span>

## Affordable database options
 - [https://www.reddit.com/r/django/comments/1iu8eho/affordable_database_options](https://www.reddit.com/r/django/comments/1iu8eho/affordable_database_options)
 - RSS feed: $source
 - date published: 2025-02-20T20:25:24+00:00

<!-- SC_OFF --><div class="md"><p>Coming from the enterprise world, I am used to just spinning up an AWS RDS instance (or similar) for a project to use as a database. The nice thing about that is they have all the backups, metrics and everything nicely done for you. But for a personal project or micro SaaS, paying even $20 per month for a micro instance seem excessive to me.</p> <p>I heard some people go as simple as using a sqlite in a small project. I was also thinking just a VPC where I have Django and Postgres in docker-compose. Naturally I can make my own backups from the docker instance. But using postgres in docker-compose just feels a bit &quot;flying blind&quot; sort of thing as I do not have metrics.</p> <p>But in an optimal situation I would have the following: - cheap - some way to visualize if database performance is a bottleneck - possibility to grow the instance to give it better performance if user count grows</p> <p>Any recommendations?</p> </div><!-- SC_ON --> &#32;

## Django for beginners - William Vincent
 - [https://www.reddit.com/r/django/comments/1iu6yyn/django_for_beginners_william_vincent](https://www.reddit.com/r/django/comments/1iu6yyn/django_for_beginners_william_vincent)
 - RSS feed: $source
 - date published: 2025-02-20T19:27:13+00:00

<!-- SC_OFF --><div class="md"><p>Everything is good with this book. I am able to understand easily but the only problem i am facing rn is ,at some points , after copying the exact code from the book the code isn&#39;t working. Please help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/That-Complex-8739"> /u/That-Complex-8739 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iu6yyn/django_for_beginners_william_vincent/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iu6yyn/django_for_beginners_william_vincent/">[comments]</a></span>

## I have created an AI Legal Document Analyzer and Consultant. I would like to know your inputs to improve
 - [https://www.reddit.com/r/django/comments/1iu6aqt/i_have_created_an_ai_legal_document_analyzer_and](https://www.reddit.com/r/django/comments/1iu6aqt/i_have_created_an_ai_legal_document_analyzer_and)
 - RSS feed: $source
 - date published: 2025-02-20T19:00:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/shinobi6406"> /u/shinobi6406 </a> <br/> <span><a href="/r/webdev/comments/1iu6a3a/i_have_created_an_ai_legal_document_analyzer_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iu6aqt/i_have_created_an_ai_legal_document_analyzer_and/">[comments]</a></span>

## Job queue in django
 - [https://www.reddit.com/r/django/comments/1iu0q76/job_queue_in_django](https://www.reddit.com/r/django/comments/1iu0q76/job_queue_in_django)
 - RSS feed: $source
 - date published: 2025-02-20T15:12:53+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. First off I&#39;d start and say I&#39;m a newbie in django, it&#39;s my first project (I&#39;m been programming with Python for about a year)</p> <p>I&#39;m working on a website (Angular) which offers image conversion and processing (done via pythonl).</p> <p>I&#39;d like to have some sort of queue for conversion jobs, as its a fairly (computing wise) heavy task and I cant have 100 jobs running at the same time, so I want to make a queue system which will wait for it&#39;s turn and then run the function which submits and return the results to the client.</p> <p>I don&#39;t want to submit the job for later processing and move on, I want to wait for the job to run, then return the results to the client.</p> <p>Any help will be appricated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Notalabel_4566"> /u/Notalabel_4566 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iu0q76/job_

## What could break Celery & Celery Beat on my django hosted project?
 - [https://www.reddit.com/r/django/comments/1iu08uk/what_could_break_celery_celery_beat_on_my_django](https://www.reddit.com/r/django/comments/1iu08uk/what_could_break_celery_celery_beat_on_my_django)
 - RSS feed: $source
 - date published: 2025-02-20T14:52:05+00:00

<!-- SC_OFF --><div class="md"><p>Few days ago Celery &amp; Celery Beat broke suddenly on my t2.small instance, they were working fine for a long time but suddenly they broke. ( Iam running Celery with redis) I restarted them and everything worked fine.</p> <p>My Supervisor configuration are:</p> <pre><code>[program:celery] command=/home/ubuntu/saas-ux/venv/bin/celery -A sass worker --loglevel=info directory=/home/ubuntu/saas-ux/sass user=ubuntu autostart=true autorestart=true stderr_logfile=/var/log/celery.err.log stdout_logfile=/var/log/celery.out.log [program:celery-beat] command=/home/ubuntu/saas-ux/venv/bin/celery -A sass beat --loglevel=info directory=/home/ubuntu/saas-ux/sass user=ubuntu autostart=true autorestart=true stderr_logfile=/var/log/celery-beat.err.log stdout_logfile=/var/log/celery-beat.out.log </code></pre> <p>I suspect that the reason is</p> <ul> <li>High RAM Usage</li> <li>CPU Overload</li> </ul> <p>To prevent this from happening in the feature, i am considering:

## My Ever-Expanding Python & Django Notes
 - [https://www.reddit.com/r/django/comments/1itzskt/my_everexpanding_python_django_notes](https://www.reddit.com/r/django/comments/1itzskt/my_everexpanding_python_django_notes)
 - RSS feed: $source
 - date published: 2025-02-20T14:31:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! 👋</p> <p>I wanted to share a project I&#39;ve been working on: <a href="https://mouhamaddev.github.io/Code-Memo/"><strong>Code-Memo</strong></a> – a personal collection of coding notes. This is NOT a structured learning resource or a tutorial site but more of a <strong>living reference</strong> where I document everything I know (and continue to learn) about Python, Django, Linux, AWS, and more.</p> <p>Some pages:<br/> 📌 <a href="http://mouhamaddev.github.io/Code-Memo/python.html"><strong>Python Notes</strong></a><br/> 📌 <a href="http://mouhamaddev.github.io/Code-Memo/django.html"><strong>Django Notes</strong></a></p> <p>The goal is simple: <strong>collect knowledge, organize it, and keep expanding.</strong> It will never be &quot;finished&quot; because I’m always adding new things as I go. If you&#39;re a Python/Django developer, you might find something useful in there—or even better, you might have suggestions for things to add!</p> 

## Non sequential ids after integrating with all-auth
 - [https://www.reddit.com/r/django/comments/1ityduj/non_sequential_ids_after_integrating_with_allauth](https://www.reddit.com/r/django/comments/1ityduj/non_sequential_ids_after_integrating_with_allauth)
 - RSS feed: $source
 - date published: 2025-02-20T13:23:48+00:00

<!-- SC_OFF --><div class="md"><p>I see 300 users in my page but the ID of the last user is 1600. </p> <p>Is that expected?</p> <p>Are anonymous users part of the issue?</p> <p>I just worry I’ve misconfigured something. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Juancki"> /u/Juancki </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ityduj/non_sequential_ids_after_integrating_with_allauth/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ityduj/non_sequential_ids_after_integrating_with_allauth/">[comments]</a></span>

## Is there an existing mail buffering library or a need for one?
 - [https://www.reddit.com/r/django/comments/1ityd40/is_there_an_existing_mail_buffering_library_or_a](https://www.reddit.com/r/django/comments/1ityd40/is_there_an_existing_mail_buffering_library_or_a)
 - RSS feed: $source
 - date published: 2025-02-20T13:22:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone.</p> <p>I am pretty unfamiliar with mail technical details, SMTP stuff. I am provided with a small challenge in my company.</p> <p>My django app use <code>django.core.mail.send_mass_mail</code> to send mail to an mail server of another department which then transfer the mails to their recipient. However, we can be temporary blacklisted by that mail server if we send it too many mail (~60/minutes). This can be solved by buffering since we are ok by delaying emails by a few hours. My best bet was to find a django library to buffer emails but I haven&#39;t found anything.</p> <p>Not finding anything can mean that :<br/> - There is a need for an open source project.<br/> - Either my interpretation of the problem or proposed solution are wrong. (e.g. buffering should be done by the SMTP server somehow)<br/> - My problem is niche enough that there is not really any need for that open source project. I can solve this with some homebrewed code. <

## Django with cassandra
 - [https://www.reddit.com/r/django/comments/1ity8x6/django_with_cassandra](https://www.reddit.com/r/django/comments/1ity8x6/django_with_cassandra)
 - RSS feed: $source
 - date published: 2025-02-20T13:16:44+00:00

<!-- SC_OFF --><div class="md"><p>Looking for how to integrate Cassandra with django for production level. Any relevant doc or blog would help a lot. </p> <p>Cases handled should be like handling multiple connections, max connection per host, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/premiumshadow008"> /u/premiumshadow008 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ity8x6/django_with_cassandra/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ity8x6/django_with_cassandra/">[comments]</a></span>

## How to simply add a blog, without a giant framework?
 - [https://www.reddit.com/r/django/comments/1ittqo2/how_to_simply_add_a_blog_without_a_giant_framework](https://www.reddit.com/r/django/comments/1ittqo2/how_to_simply_add_a_blog_without_a_giant_framework)
 - RSS feed: $source
 - date published: 2025-02-20T08:22:43+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of a lib I can use to do the following:</p> <ol> <li><p>I have an existing Django project</p></li> <li><p>I want to write blog posts as markdown, put them in a folder</p></li> <li><p>Django publishes them automatically, reading those files </p></li> </ol> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/odwyer_richard"> /u/odwyer_richard </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ittqo2/how_to_simply_add_a_blog_without_a_giant_framework/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ittqo2/how_to_simply_add_a_blog_without_a_giant_framework/">[comments]</a></span>

## Django with MongoDB
 - [https://www.reddit.com/r/django/comments/1ittina/django_with_mongodb](https://www.reddit.com/r/django/comments/1ittina/django_with_mongodb)
 - RSS feed: $source
 - date published: 2025-02-20T08:07:00+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, i built many projects using MySQL and Postgresql.Now I try to use mongodb in my project but I have no idea howto integrate it. I try many tutorials but still have no conclusion about that so please help me out guys</p> <p>Thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Naurangi_lal"> /u/Naurangi_lal </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ittina/django_with_mongodb/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ittina/django_with_mongodb/">[comments]</a></span>

## About using Django choices with Pydantic
 - [https://www.reddit.com/r/django/comments/1itnjfu/about_using_django_choices_with_pydantic](https://www.reddit.com/r/django/comments/1itnjfu/about_using_django_choices_with_pydantic)
 - RSS feed: $source
 - date published: 2025-02-20T02:14:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone. I usually use pydantic in my Django program. I have always been troubled by the inability to apply Django choices to pydantic, so I wrote a <code>Choices</code> class for my Django program. I hope you can help me see if this is a good way to do it, or if there is a more convenient way to achieve the same effect.</p> <p>Defining my <code>Choices</code> class：<br/> <a href="https://melodious-condor-d48.notion.site/django-choices-1a061f9ffe6280ff9eabc172cb852cd8?pvs=4">https://melodious-condor-d48.notion.site/django-choices-1a061f9ffe6280ff9eabc172cb852cd8?pvs=4</a></p> <p>Use it in model:</p> <pre><code>from django.db import models from .choices import Choices, ChoiceField class DataScore(Choices): INCORRECT = ChoiceField(value=-1, label=&quot;错误&quot;) UNKNOWN = ChoiceField(value=0, label=&quot;未知&quot;) CORRECT = ChoiceField(value=1, label=&quot;正确&quot;) class Data(BaseModel): # ... Some content is omitted score = models.IntegerField

