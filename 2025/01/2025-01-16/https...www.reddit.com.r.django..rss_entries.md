# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## inconsistent hour format of forms.TimeField value
 - [https://www.reddit.com/r/django/comments/1i30jmc/inconsistent_hour_format_of_formstimefield_value](https://www.reddit.com/r/django/comments/1i30jmc/inconsistent_hour_format_of_formstimefield_value)
 - RSS feed: $source
 - date published: 2025-01-16T21:58:28+00:00

<!-- SC_OFF --><div class="md"><p><code>{{ form.start_time.value }}</code> returns 12-hour format at first load, but when the form gets an error after submitting, it becomes 24-hour format</p> <p>How should I fix this? I can&#39;t just use the tag <code>|date:&quot;H:i&quot;</code> since the format varies when form is loaded with or without error. Also, why is this the case?</p> <p>The form field is initialized like the following currently:</p> <pre><code>start_time = forms.TimeField(input_formats=[&quot;%H:%M&quot;], localize=False) </code></pre> <p>In my model, it is defined as follows:</p> <pre><code>start_time = models.TimeField(null=True, blank=True) </code></pre> <p>Let me know if you need further information. Thank you so much in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aliasChewyC00kies"> /u/aliasChewyC00kies </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i30jmc/inconsistent_hour_format_of_formstimefi

## Google login verification is not verified in my Django project.
 - [https://www.reddit.com/r/django/comments/1i2yfs4/google_login_verification_is_not_verified_in_my](https://www.reddit.com/r/django/comments/1i2yfs4/google_login_verification_is_not_verified_in_my)
 - RSS feed: $source
 - date published: 2025-01-16T20:26:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am working on a Django project (python 2.7 and Django 1.8) in which I tried to implement Google login authentication. For this, I have created a project on Google Console and added all the necessary redirect URI&#39;s and generated the client ID and secret. I added a secret and client ID to my project, but when I am going to login using Google, I am getting an error: </p> <p>in text:<br/> HTTPError at /complete/google-oauth2/403 Client Error: Forbidden for url: <a href="https://www.googleapis.com/plus/v1/people/me?access_token=ya29.a0ARW5m74QiMSuWBjIjYoH6Aa7CF7pOXTspStejqkLD73ud2zsODyGBPoN11gqTnEUbQz-wYOI78wGRN2T-AXZFC9erAYSyOG6KSI6H-ob8AvkDAsEuqqQwGEkWnhsn60aqghSNBIFE6t_CUn1fctt7dnDqHUytISw_8RRM06saCgYKAZISARISFQHGX2Miy9VyhXHeFWkzY-XBTiCWJA0175&amp;alt=json">https://www.googleapis.com/plus/v1/people/me?access_token=ya29.a0ARW5m74QiMSuWBjIjYoH6Aa7CF7pOXTspStejqkLD73ud2zsODyGBPoN11gqTnEUbQz-wYOI78wGRN2T-AXZFC9erAYSyOG6KSI6H-ob8AvkDAsEuqqQwGEkWnh

## Should i use a frontend framework with django for my project?
 - [https://www.reddit.com/r/django/comments/1i2wvgm/should_i_use_a_frontend_framework_with_django_for](https://www.reddit.com/r/django/comments/1i2wvgm/should_i_use_a_frontend_framework_with_django_for)
 - RSS feed: $source
 - date published: 2025-01-16T19:19:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys.<br/> I&#39;ve used django for one project at uni and not only loved it, but felt that it was easier than other backend frameworks i used previously; because of that for my final project i was thinking of using it.</p> <p>The project consists of a backoffice web app for a client, the app has the purpose of managing the company stock.</p> <p>I&#39;ve never integrated Django with any frontend frameworks so i am a bit worried that if i need to do it in this project i may not be able to deliver it on time.<br/> Do you think i need, or should use a framework such as React, Vue etc for this project?<br/> thank&#39;s in advance .</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mundane_Blueberry942"> /u/Mundane_Blueberry942 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2wvgm/should_i_use_a_frontend_framework_with_django_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/

## Why remote jobs require specific location ?
 - [https://www.reddit.com/r/django/comments/1i2v521/why_remote_jobs_require_specific_location](https://www.reddit.com/r/django/comments/1i2v521/why_remote_jobs_require_specific_location)
 - RSS feed: $source
 - date published: 2025-01-16T18:06:45+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been searching for a Python-Django developer job since last year, but most remote positions still specify location requirements, often limited to Europe or the US. As someone from Africa, I’m finding it challenging to find job openings that are truly open to international applicants.</p> <p>Are there any developers here working remotely from outside Europe or the US? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/awahidanon"> /u/awahidanon </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2v521/why_remote_jobs_require_specific_location/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2v521/why_remote_jobs_require_specific_location/">[comments]</a></span>

## My first django project
 - [https://www.reddit.com/r/django/comments/1i2u65w/my_first_django_project](https://www.reddit.com/r/django/comments/1i2u65w/my_first_django_project)
 - RSS feed: $source
 - date published: 2025-01-16T17:26:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am a college 2nd year trying to get more experience and I learned Django for around 3ish months. With learning, I made this simple project and I wanted to get feedback on where I can improve and if this is good enough to put on my resume. The only thing I&#39;m worried about is if these projects are overdone and putting on my resume is worth it. Thank you! This is the Github: <a href="https://github.com/Ryan11c/mathify">https://github.com/Ryan11c/mathify</a> the live version is also linked inside the repo!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/apoorkid"> /u/apoorkid </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2u65w/my_first_django_project/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2u65w/my_first_django_project/">[comments]</a></span>

## Hello from the new Steering Council; and a quick temporary voting process change
 - [https://www.reddit.com/r/django/comments/1i2tq4l/hello_from_the_new_steering_council_and_a_quick](https://www.reddit.com/r/django/comments/1i2tq4l/hello_from_the_new_steering_council_and_a_quick)
 - RSS feed: $source
 - date published: 2025-01-16T17:07:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/jan/16/hello-from-the-new-steering-council-and-a-quick-te/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2tq4l/hello_from_the_new_steering_council_and_a_quick/">[comments]</a></span>

## create a text area on a line svg
 - [https://www.reddit.com/r/django/comments/1i2s8yj/create_a_text_area_on_a_line_svg](https://www.reddit.com/r/django/comments/1i2s8yj/create_a_text_area_on_a_line_svg)
 - RSS feed: $source
 - date published: 2025-01-16T16:05:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello people </p> <p>I´m trying to create a textarea in a line svg is it possible? I created a program to show a network diagram and i have icons in my diagram and connect them with a line but i would like to put a description like port1 or e/01 for example. I´m using Django and JS for the diagrams. Someone could help me please? If you need any adittional thing a can send it. Thank you. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Physical_Choice_488"> /u/Physical_Choice_488 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2s8yj/create_a_text_area_on_a_line_svg/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2s8yj/create_a_text_area_on_a_line_svg/">[comments]</a></span>

## REST_FRAMEWORK
 - [https://www.reddit.com/r/django/comments/1i2ry9i/rest_framework](https://www.reddit.com/r/django/comments/1i2ry9i/rest_framework)
 - RSS feed: $source
 - date published: 2025-01-16T15:52:14+00:00

<!-- SC_OFF --><div class="md"><p><a href="http://base.py">base.py</a></p> <pre><code>REST_FRAMEWORK = { &#39;DEFAULT_AUTHENTICATION_CLASSES&#39;: ( &#39;apps.users.authentication.CookieJWTAuthentication&#39;, ), &quot;DEFAULT_PERMISSION_CLASSES&quot;: [ &quot;rest_framework_api_key.permissions.HasAPIKey&quot;, ], &#39;DEFAULT_FILTER_BACKENDS&#39;: [&#39;django_filters.rest_framework.DjangoFilterBackend&#39;], } </code></pre> <p>i tried this in <a href="http://local.py">local.py</a> but obviously it wont work</p> <pre><code>REST_FRAMEWORK += { &#39;DEFAULT_SCHEMA_CLASS&#39;: &#39;drf_spectacular.openapi.AutoSchema&#39;, } </code></pre> <p>How do you add spectacular in it? I just want it in local</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FoxEducational2691"> /u/FoxEducational2691 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2ry9i/rest_framework/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/

## Database Indexing in Django
 - [https://www.reddit.com/r/django/comments/1i2ry8j/database_indexing_in_django](https://www.reddit.com/r/django/comments/1i2ry8j/database_indexing_in_django)
 - RSS feed: $source
 - date published: 2025-01-16T15:52:12+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/michaelherman"> /u/michaelherman </a> <br/> <span><a href="https://testdriven.io/blog/django-db-indexing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2ry8j/database_indexing_in_django/">[comments]</a></span>

## Can you make sortable.js work with Bootstrap 5 modal?
 - [https://www.reddit.com/r/django/comments/1i2rmye/can_you_make_sortablejs_work_with_bootstrap_5](https://www.reddit.com/r/django/comments/1i2rmye/can_you_make_sortablejs_work_with_bootstrap_5)
 - RSS feed: $source
 - date published: 2025-01-16T15:38:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m building a checklist app for fun and I&#39;m trying to use sortable.js with python Django.</p> <p>I can make a sortable list work in this example with the html as follows</p> <pre><code>{% extends &#39;BJJApp/base.html&#39; %} {% load static %} {%load crispy_forms_tags %} {% block content %} &lt;br&gt;&lt;br&gt; &lt;div id=&quot;standalone-items-container&quot;&gt; {% for item, formset, links in standalone_items_formsets_links %} &lt;div class=&quot;modal fade&quot; id=&quot;exampleModalToggle-{{ item.id }}&quot; aria-hidden=&quot;true&quot; aria-labelledby=&quot;exampleModalToggleLabel-{{ item.id }}&quot; data-item-id=&quot;{{ item.id }}&quot; tabindex=&quot;-1&quot;&gt; &lt;div class=&quot;modal-dialog modal-dialog-centered&quot;&gt; &lt;div class=&quot;modal-content&quot;&gt; &lt;div class=&quot;modal-header&quot;&gt; &lt;h1 class=&quot;modal-title fs-5&quot; id=&quot;exampleModalToggleLabel-{{ item.id }}&quot; style=&quot;color: {% if ite

## Django Developer Salary Report 2025
 - [https://www.reddit.com/r/django/comments/1i2qpib/django_developer_salary_report_2025](https://www.reddit.com/r/django/comments/1i2qpib/django_developer_salary_report_2025)
 - RSS feed: $source
 - date published: 2025-01-16T14:56:48+00:00

<!-- SC_OFF --><div class="md"><p>Here is our 2025 Django Developer Salary report. </p> <p>This has been put together using the actual salary ranges paid to the developers we speak to crossed with the salaries actually offered by our clients. </p> <p>At <a href="https://www.linkedin.com/company/foxleytalent/">Foxley Talent</a> we work with companies and developers across the UK, Europe and the United States so the information is relevant to these regions.</p> <p>The report is designed to help companies know if they are paying the right salaries for their developers and to help developers looking for work. </p> <p>There are lots of nuances which means the numbers may not fit everyone&#39;s own individual circumstances but should be a guide for the majority. In the report we have also given some of our insights and predictions for the next 12 months. </p> <p>As always, we love to hear your thoughts and feedback.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.red

## While running app without dockerizing, api of the app seems working fine but after using docker i am getting error of integrity error: foreignkey related error
 - [https://www.reddit.com/r/django/comments/1i2pfxe/while_running_app_without_dockerizing_api_of_the](https://www.reddit.com/r/django/comments/1i2pfxe/while_running_app_without_dockerizing_api_of_the)
 - RSS feed: $source
 - date published: 2025-01-16T13:56:20+00:00

<!-- SC_OFF --><div class="md"><p>?????</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/give_it-some"> /u/give_it-some </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2pfxe/while_running_app_without_dockerizing_api_of_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2pfxe/while_running_app_without_dockerizing_api_of_the/">[comments]</a></span>

## Considering Senior Golang vs Senior Django Career Path: Weighing Competition, Algorithms, and Cloud Trends
 - [https://www.reddit.com/r/django/comments/1i2osvh/considering_senior_golang_vs_senior_django_career](https://www.reddit.com/r/django/comments/1i2osvh/considering_senior_golang_vs_senior_django_career)
 - RSS feed: $source
 - date published: 2025-01-16T13:23:47+00:00

<!-- SC_OFF --><div class="md"><p>I self-taught computer science from 2018 to 2020, focusing on Golang and Django the following year. Since 2021, I’ve worked full-time as a middle Golang developer and freelanced with Django, gaining experience in cloud technologies (EC2, EKS, Kafka, Datadog) and microservices.</p> <p>Currently, I’m focused on middle Golang job (at currently company) to maintain financial stability and improve my Codeforces rating (currently 1400), aiming for 1600 in the next 6 months. I’ve paused my Django freelance work to focus on these goals.</p> <p>However, with the increasing number of Golang developers entering the job market, driven by media trends and the tech community&#39;s hype around Golang, I’m unsure whether to continue pursuing a Senior Golang role or shift to Senior Django, which may have less competition. I’ve noticed a growing shift from Python/Django to Golang, making the decision even more complex. I’m weighing both options, considering algorithm 

## Learn Message Brokers and Message Queuing Platforms Online for Free
 - [https://www.reddit.com/r/django/comments/1i2lbkk/learn_message_brokers_and_message_queuing](https://www.reddit.com/r/django/comments/1i2lbkk/learn_message_brokers_and_message_queuing)
 - RSS feed: $source
 - date published: 2025-01-16T09:36:40+00:00

<!-- SC_OFF --><div class="md"><p>I want to learn about message brokers and the message queuing process using various tools or platforms online. Please suggest any free resources.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkObligation5338"> /u/OkObligation5338 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2lbkk/learn_message_brokers_and_message_queuing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2lbkk/learn_message_brokers_and_message_queuing/">[comments]</a></span>

## Django 5.2 alpha 1 released
 - [https://www.reddit.com/r/django/comments/1i2l92s/django_52_alpha_1_released](https://www.reddit.com/r/django/comments/1i2l92s/django_52_alpha_1_released)
 - RSS feed: $source
 - date published: 2025-01-16T09:31:12+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/jan/16/django-52-alpha-1-released/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2l92s/django_52_alpha_1_released/">[comments]</a></span>

## Workflow management in Django
 - [https://www.reddit.com/r/django/comments/1i2jhsb/workflow_management_in_django](https://www.reddit.com/r/django/comments/1i2jhsb/workflow_management_in_django)
 - RSS feed: $source
 - date published: 2025-01-16T07:16:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I am making my first rest API with Django and I love it!</p> <p>I am quite far in the Dev work with integrations, running in k8s, using redis, celery, nginx and gunicorn. I am currently adding features.</p> <p>So far I query data from AWS Athena, pretty much a SQL query and handle that with pandas. I then collate the information in a Django model backed by Postgres. I categorise the next action for each item.</p> <p>For the next actions I wanted to use finite state management. I have used django-fsm some time ago when I was playing, but I now see that it is recommended to use viewflow.</p> <p>I am finding the django-viewflow documentation lacking in pretty much any detail, empty examples is one reason. I also look at the viewflow documentation and it is not clear how to register the state within a Django model.</p> <p>Am I looking at this wrong? Is it the case that I should use something else, not viewflow?</p> </div><!-- SC_ON --> &#

## Learn Django as a React Developer is a good Idea?
 - [https://www.reddit.com/r/django/comments/1i2iv2m/learn_django_as_a_react_developer_is_a_good_idea](https://www.reddit.com/r/django/comments/1i2iv2m/learn_django_as_a_react_developer_is_a_good_idea)
 - RSS feed: $source
 - date published: 2025-01-16T06:30:56+00:00

<!-- SC_OFF --><div class="md"><p>Learning Django Rest Framework to be a full stack developer from a React Frontend developer is a good idea? I&#39;ve explored basics of python including OOP, What learning path I should follow?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure-Raspberry116"> /u/Sure-Raspberry116 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2iv2m/learn_django_as_a_react_developer_is_a_good_idea/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2iv2m/learn_django_as_a_react_developer_is_a_good_idea/">[comments]</a></span>

## Struggling to find a job
 - [https://www.reddit.com/r/django/comments/1i2hkp1/struggling_to_find_a_job](https://www.reddit.com/r/django/comments/1i2hkp1/struggling_to_find_a_job)
 - RSS feed: $source
 - date published: 2025-01-16T05:07:06+00:00

<!-- SC_OFF --><div class="md"><p>6 years of experience using Django in start environments, I’m in the Midwest. Anyone hiring ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Django-fanatic"> /u/Django-fanatic </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2hkp1/struggling_to_find_a_job/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2hkp1/struggling_to_find_a_job/">[comments]</a></span>

## How to starting learning Django
 - [https://www.reddit.com/r/django/comments/1i2g5nk/how_to_starting_learning_django](https://www.reddit.com/r/django/comments/1i2g5nk/how_to_starting_learning_django)
 - RSS feed: $source
 - date published: 2025-01-16T03:45:46+00:00

<!-- SC_OFF --><div class="md"><p>Please guide mei on learning Django how should I start ??</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ArcEus_2004"> /u/ArcEus_2004 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i2g5nk/how_to_starting_learning_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i2g5nk/how_to_starting_learning_django/">[comments]</a></span>
