# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## l4py - I Created a Logger That Integrates with Django and Regular Python – Looking for Feedback!
 - [https://www.reddit.com/r/django/comments/1i1je0d/l4py_i_created_a_logger_that_integrates_with](https://www.reddit.com/r/django/comments/1i1je0d/l4py_i_created_a_logger_that_integrates_with)
 - RSS feed: $source
 - date published: 2025-01-14T23:13:47+00:00

<!-- SC_OFF --><div class="md"><p>Hey Reddit,</p> <p>I recently built a logger that works seamlessly with both Django and standalone Python projects. It&#39;s currently in its beta stage, and I’d love to get your thoughts on it.</p> <p>The logger includes:</p> <pre><code>- Easy integration with Django settings. - Simple usage in regular Python scripts. - Testing utilities to make it easier to validate your logging logic. - Flexibility and customizability to fit various logging needs. </code></pre> <p>I’m open to any criticism, feature suggestions, or improvements you can think of. Your feedback will help me refine it further!</p> <p>Feel free to give it a try and share your thoughts. Thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InternationalSmell97"> /u/InternationalSmell97 </a> <br/> <span><a href="https://github.com/roymanigley/l4py">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i1je0d/l4

## Redirect function does not change the page even though it returns the necessary codes
 - [https://www.reddit.com/r/django/comments/1i1fnhe/redirect_function_does_not_change_the_page_even](https://www.reddit.com/r/django/comments/1i1fnhe/redirect_function_does_not_change_the_page_even)
 - RSS feed: $source
 - date published: 2025-01-14T20:28:01+00:00

<!-- SC_OFF --><div class="md"><p>Hello everybody,</p> <p>I started trying to llearn Django recently, but I am a bit stumped at the moment. I&#39;m trying to redirect my user to the &quot;main&quot; page of the site after checking their password and email. The problem is, whanever I do this, the redirect function returns code 302 and the page I need to go returns 200, but doesn&#39;t change the page</p> <pre><code>pa = request.build_absolute_uri(&quot;/main/&quot;) valid = redirect(pa) return valid </code></pre> <p>This is literaly what I&#39;m doing to redirect and is what I found in all the redirecting tutorials. I&#39;ve checked before and the function is actually returning the redirect</p> <p><a href="https://preview.redd.it/awlxk5i0r0de1.png?width=503&amp;format=png&amp;auto=webp&amp;s=a1f81185d028f6229b94c185c4f5752a8285603c">The results on the site&#39;s \&quot;network\&quot; DevTools tab</a></p> <p>Any hellp would be apreciated and, if needed, ask me to elaborate more</p> </d

## Good order platform Database Design for a small manufacturer?
 - [https://www.reddit.com/r/django/comments/1i1ch0a/good_order_platform_database_design_for_a_small](https://www.reddit.com/r/django/comments/1i1ch0a/good_order_platform_database_design_for_a_small)
 - RSS feed: $source
 - date published: 2025-01-14T18:15:33+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently working on an order platform using Django, currently designing the database, for a small whirlpool manufacturer. This platform is only for their B2B customers. Now, they main product is of course whirlpools, offered in fixed sizes and colors. There are also some accessories that can be added, depending on the model. There are some restrictions, only certain accessories can be added to certain models. The platform will not deal with payments. </p> <p>Anyways, the question I have here if the Order, whirlPoolOrderItem and accessoryOrderItem make sense. I couldn&#39;t think of a &quot;clean&quot; way to just have a single OrderItem table because their main product (the whirlpool) has different requirements compared to their accessories and otherwise it might get messy. Or should I try regardless, making a single generic &quot;Product&quot; table that encapsulates their Whirlpools and accessories?</p> <p>There might be a case in the futu

## Looking for Python/Django Developer Opportunities | Open to Freelance and Full-Time Roles
 - [https://www.reddit.com/r/django/comments/1i1c7rw/looking_for_pythondjango_developer_opportunities](https://www.reddit.com/r/django/comments/1i1c7rw/looking_for_pythondjango_developer_opportunities)
 - RSS feed: $source
 - date published: 2025-01-14T18:04:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello, everyone!</p> <p>I am Gautam Pardeshi, a passionate Python/Django developer with a strong foundation in web development and project management. I am looking for full-time or freelance opportunities where I can contribute to innovative projects and grow as a professional.</p> <p>Key Highlights:</p> <p>Education:</p> <p>Master of Computer Applications (MCA) – Medi-Caps University, Indore</p> <p>Bachelor of Computer Applications (BCA) – Barkatullah University</p> <p>Work Experience:</p> <p>Python Developer at SKED Group Innovations Pvt. Ltd.</p> <p>Developed the Vital Care Hospital Management System, a scalable full-stack web application with role-based access and database management.</p> <p>Frontend Developer at Indvibe Infotech Pvt. Ltd.</p> <p>Designed and implemented the Car Rental Management System using HTML, CSS, and JavaScript to manage bookings and payments efficiently.</p> <p>Skills:</p> <p>Python, Django, JavaScript, HTML, CSS</p> <p>G

## What tests to focus on while using TDD to code faster?
 - [https://www.reddit.com/r/django/comments/1i1bvsd/what_tests_to_focus_on_while_using_tdd_to_code](https://www.reddit.com/r/django/comments/1i1bvsd/what_tests_to_focus_on_while_using_tdd_to_code)
 - RSS feed: $source
 - date published: 2025-01-14T17:50:20+00:00

<!-- SC_OFF --><div class="md"><p>So, I am learning TDD recently and trying to implement it in my personal project. So the issue is that when I start writing test cases for each functionality and then implementing them, it is taking a lot of time. I have to write test cases for whether the urls are pointing to correct views and url is present and then write url code. In forms I have to check for whether fields are present and validate for each and every field. In views I have to check whether correct template is used, forms submission is valid or not. The project is taking too long and the functionality I would have been able to finish in 2-3 hours is taking me 2-3 days. </p> <p>So whats the practical approach in implementing TDD? What is the approach to test cases you write when you implementing it in professional projects?</p> <p>My project repo link : <a href="https://github.com/nitskp/task-manager">https://github.com/nitskp/task-manager</a></p> </div><!-- SC_ON --> &#32; submitte

## Need advice for python django preparation
 - [https://www.reddit.com/r/django/comments/1i1a9d6/need_advice_for_python_django_preparation](https://www.reddit.com/r/django/comments/1i1a9d6/need_advice_for_python_django_preparation)
 - RSS feed: $source
 - date published: 2025-01-14T16:42:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi I am a python dev. I have worked on flask restx and Django having around 3 years of experience combined (Contains some other tech stacks such as dot net core for BE and angular for FE). My experience is not entirely in Django. Even the flask experience I have I think is not as good as my expectations as it was a basic crud. I want to prepare myself for a Django interview. I have also studied django basic topics and some additional topics such as middlwares, signals etc. I have a good experience in writing raw sql queries. I need your guys advice on how to start preparing well for interviews to switch. Worked on some AWS services and Elastic search as well.</p> <p>I need advice in things such as should I do project based learning or go topic or topic or any other way you guys suggest.</p> <p>Also TBH the experience I have in flask is primarily but even that project has very limited scope and is a basic CRUD. So very less third party integrations. S

## Started My Django Journey – Sharing My Multi-Database Experience
 - [https://www.reddit.com/r/django/comments/1i19qza/started_my_django_journey_sharing_my](https://www.reddit.com/r/django/comments/1i19qza/started_my_django_journey_sharing_my)
 - RSS feed: $source
 - date published: 2025-01-14T16:20:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey Redditors! 👋</p> <p>I recently started working with Django, and I have to say, it’s been a rollercoaster! 🎢 The framework’s ORM and rich libraries are amazing, and I couldn’t wait to dive in.</p> <p>At first, I chose <strong>MongoDB</strong> because of its scalability and schemaless interface, which seemed perfect for storing file and metadata details. But here’s the catch: Django doesn’t have robust support for MongoDB. I tried a few workarounds, but none felt reliable for long-term use.</p> <p>During my research, I discovered the concept of <strong>using multiple databases</strong> in a single project. It was an eye-opener to see how companies combine the strengths of different databases for optimal results.</p> <p>For my project:</p> <ul> <li>I use <strong>MongoDB</strong> for its flexibility with unstructured data.</li> <li>I use <strong>MySQL</strong> for its strong support for relational data, which integrates seamlessly with Django.</li> <

## I created an opensource lightweight django-cookiecutter
 - [https://www.reddit.com/r/django/comments/1i19nc2/i_created_an_opensource_lightweight](https://www.reddit.com/r/django/comments/1i19nc2/i_created_an_opensource_lightweight)
 - RSS feed: $source
 - date published: 2025-01-14T16:16:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p><strong>TLDR</strong>: I created a template to create typical Django projects faster. Details on how to use it in the repo.</p> <p>I often (2-6 times a year) create Django projects. They always use Django-celery, DRF and connected to postgreSQL. Coupling these together always take ~1hr of my time.</p> <p>To save these hours I created a <a href="https://gitlab.com/AverageS/DjangoCookiecutter">Django template cookiecutter</a> - now setting up a Django app takes seconds instead of hours.</p> <p>Template creates you a Django application with</p> <ol> <li>Django-Rest-Framework</li> <li>Django-celery-beat to do async jobs in the background</li> <li>PostgreSQL as database</li> <li>Everything dockerized</li> </ol> <p><strong>Why not use the official Django cookie cutter?</strong></p> <p>Because it is just too much. When I tried to use it it took more time to remove unnecessary staff - it contains bootstrap, all sorts of pluggable libraries - preco

## Show Django forms inside a modal using HTMX
 - [https://www.reddit.com/r/django/comments/1i18rk7/show_django_forms_inside_a_modal_using_htmx](https://www.reddit.com/r/django/comments/1i18rk7/show_django_forms_inside_a_modal_using_htmx)
 - RSS feed: $source
 - date published: 2025-01-14T15:37:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NodeJS4Lyfe"> /u/NodeJS4Lyfe </a> <br/> <span><a href="https://joshkaramuth.com/blog/django-htmx-modal-forms/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i18rk7/show_django_forms_inside_a_modal_using_htmx/">[comments]</a></span>

## Django security releases issued: 5.1.5, 5.0.11, and 4.2.18
 - [https://www.reddit.com/r/django/comments/1i17qj0/django_security_releases_issued_515_5011_and_4218](https://www.reddit.com/r/django/comments/1i17qj0/django_security_releases_issued_515_5011_and_4218)
 - RSS feed: $source
 - date published: 2025-01-14T14:51:36+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/jan/14/security-releases/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i17qj0/django_security_releases_issued_515_5011_and_4218/">[comments]</a></span>

## Mypy integration
 - [https://www.reddit.com/r/django/comments/1i17izm/mypy_integration](https://www.reddit.com/r/django/comments/1i17izm/mypy_integration)
 - RSS feed: $source
 - date published: 2025-01-14T14:41:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys,</p> <p>I have been struggling to get mypy working robustly.</p> <p>When I save files in Pycharm or Vscode, the dmypy Server tends to crash. So I see mypy lints only sometimes.</p> <p>Does anyone have a VsCode Config for mypy and django that work reliably?</p> <p>Would be happy about advice. </p> <p>mypy.ini</p> <pre><code>[mypy] check_untyped_defs = True exclude = venv/ files = ./api/api </code></pre> <p>I have this settings.json:</p> <pre><code>{ &quot;terminal.integrated.env.osx&quot;: { &quot;PYTHONPATH&quot;: &quot;${workspaceFolder}\\api&quot; }, &quot;terminal.integrated.env.linux&quot;: { &quot;PYTHONPATH&quot;: &quot;${workspaceFolder}\\api&quot; }, &quot;terminal.integrated.env.windows&quot;: { &quot;PYTHONPATH&quot;: &quot;${workspaceFolder}\\api&quot; }, &quot;python.analysis.extraPaths&quot;: [&quot;${workspaceFolder}\\api\\api&quot;], &quot;mypy.dmypyExecutable&quot;: &quot;${workspaceFolder}\\venv\\Scripts\\dmypy.exe&quot;, &qu

## Svelte Django Anyone?
 - [https://www.reddit.com/r/django/comments/1i172is/svelte_django_anyone](https://www.reddit.com/r/django/comments/1i172is/svelte_django_anyone)
 - RSS feed: $source
 - date published: 2025-01-14T14:19:50+00:00

<!-- SC_OFF --><div class="md"><p>Just wanted to share my setup and hear what other people are doing for their projects. </p> <p>For mine, I am using:</p> <p>Postgresql</p> <p>Django for apps, views, templates, models, auth, urls, middleware, celery config, context processors, seo etc. </p> <p>DRF for refined querysets, viewsets, serializers, custom actions, user role based logic, endpoint permissions. </p> <p>Svelte components for api hits and variously styled template tags, buttons etc. </p> <p>Capacitor for stylistically adjusted and minimized PWA. </p> <p>Lovin’ the set up</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/musicdumpster"> /u/musicdumpster </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i172is/svelte_django_anyone/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i172is/svelte_django_anyone/">[comments]</a></span>

## Generating Django unit tests with LLMs
 - [https://www.reddit.com/r/django/comments/1i16l5w/generating_django_unit_tests_with_llms](https://www.reddit.com/r/django/comments/1i16l5w/generating_django_unit_tests_with_llms)
 - RSS feed: $source
 - date published: 2025-01-14T13:56:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I tried to use LLMs to generate unit tests but I always end up in the same cycle:<br/> - LLM generates the tests<br/> - I have to run the new tests manually<br/> - The tests fail somehow, I use the LLM to fix them<br/> - Repeat N times until they pass</p> <p>Since this is quite frustrating, I&#39;m experimenting with creating a tool that generates unit tests, tests them in loop using the LLM to correct them, and opens a PR on my repository with the new tests.</p> <p>For now it seems to work on my main repository (python/Django with pytest and React Typescript with npm test), and I&#39;m now trying it against some open source repos.</p> <p>I attached screenshot of a PR I opened on a public repository.</p> <p>I&#39;m considering opening this to more people. Do you think this would be useful? Which language frameworks should I support?</p> <p><a href="https://preview.redd.it/496frgvbtyce1.jpg?width=1280&amp;format=pjpg&amp;auto=webp&amp;s=7

## Am I doing it the right way?
 - [https://www.reddit.com/r/django/comments/1i16bmm/am_i_doing_it_the_right_way](https://www.reddit.com/r/django/comments/1i16bmm/am_i_doing_it_the_right_way)
 - RSS feed: $source
 - date published: 2025-01-14T13:42:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m experienced in coding but in Javascript as I&#39;m a MERN stack developer. Recently, I started to move towards learning Python and Django.</p> <p>I explored python basics like syntax, data types and more as well as practiced little OOPs too. Then I started to explore Django, learned about MVT and more, after that I started to Learn Django Rest Framework explored some video tutorials and tried to build some Rest APIs and some project! Am I doing it the right way? I want to get complete understanding of how Django works not to be a noob developer!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sure-Raspberry116"> /u/Sure-Raspberry116 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i16bmm/am_i_doing_it_the_right_way/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i16bmm/am_i_doing_it_the_right_way/">[comments]</a></span>

## How Russian hackers nearly killed my Django based business
 - [https://www.reddit.com/r/django/comments/1i15n7a/how_russian_hackers_nearly_killed_my_django_based](https://www.reddit.com/r/django/comments/1i15n7a/how_russian_hackers_nearly_killed_my_django_based)
 - RSS feed: $source
 - date published: 2025-01-14T13:07:06+00:00

<!-- SC_OFF --><div class="md"><p>My wife and I were hiking through the scenic hills of Belgium when I received a concerning email from Amazon Web Services (AWS). The email, titled &quot;Amazon SES Complaint Review Period for AWS Account []&quot;, contained the following warning:</p> <blockquote> <p>Your current complaint rate is 0.5%. We measured this rate over the last 10,351 eligible emails you sent. We recommend that you maintain a complaint rate below 0.1%. If your complaint rate exceeds 0.5%, we might pause your ability to send additional email.</p> </blockquote> <p>I use AWS Simple Email Service (SES) to send emails for my nonprofit organization, and this warning came as a shock. It indicated that recipients had flagged emails from my system as spam. This was unexpected because I only send emails to individuals who actively subscribe to the service. I never send unsolicited messages.</p> <p>I run a small nonprofit, <a href="https://www.thelifesigns.com/">TheLifeSigns</a>, whic

## what would be the structure for my django application...?
 - [https://www.reddit.com/r/django/comments/1i12xd7/what_would_be_the_structure_for_my_django](https://www.reddit.com/r/django/comments/1i12xd7/what_would_be_the_structure_for_my_django)
 - RSS feed: $source
 - date published: 2025-01-14T10:10:46+00:00

<!-- SC_OFF --><div class="md"><p>hi,<br/> I want to deploy my django project in ECS, here are my concerns..</p> <p>* I am going to use AWS ELB, AutoScailingGroup for Django.</p> <p>where nginx should go..? I dockerize django, and deploying in ECS is not difficult but when it auto-scails or when ELB distributes to a different duplicated server, what nginx is going to do?</p> <p>ELB does load balancing, so proxy_pass is not going be included in nginx, then when ELB sends a request to nginx, I guess nginx does not know where to send the request..</p> <p>questions: </p> <ol> <li><p>should be a single nginx for multiple auto-scaled django servers or each django servers have own nginx? </p></li> <li><p>when ELB does load balancing, and auto sacailing group duplicates servers, how to set up nginx? </p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/

## Looking for APM Suggestion for my Django App
 - [https://www.reddit.com/r/django/comments/1i12k9h/looking_for_apm_suggestion_for_my_django_app](https://www.reddit.com/r/django/comments/1i12k9h/looking_for_apm_suggestion_for_my_django_app)
 - RSS feed: $source
 - date published: 2025-01-14T09:44:18+00:00

<!-- SC_OFF --><div class="md"><p>My application has been in production for a long time, I am using Graphana and Prometheus for metrics collection/visualization. Now, what I need is an APM where I can see details of an request-response cycle like how much time it takes in DB end, Elasticsearch end, redis end, etc. Could you please suggest any opensource tools for that. Thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mission-Prize-1005"> /u/Mission-Prize-1005 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i12k9h/looking_for_apm_suggestion_for_my_django_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i12k9h/looking_for_apm_suggestion_for_my_django_app/">[comments]</a></span>

## Problema con la api de mercado pago y django
 - [https://www.reddit.com/r/django/comments/1i10a8b/problema_con_la_api_de_mercado_pago_y_django](https://www.reddit.com/r/django/comments/1i10a8b/problema_con_la_api_de_mercado_pago_y_django)
 - RSS feed: $source
 - date published: 2025-01-14T06:52:39+00:00

<!-- SC_OFF --><div class="md"><p>Buenas, estoy intentando probar de distintas formas para poder obtner el total de dinero que tengo en mi mercado pago y que eso se muestre en una web con html, sencilla la cosa pq es solo mostrar cuanto dinero tengo en mi mercado pago y si por ej hay depósitos que haga o que me hagan que eso se actualice, el prob es ese.... el tema de la interacción con la api de mercado pago. Por acá dejo el código que venía probando:</p> <p>import mercadopago</p> <p>from django.http import JsonResponse</p> <p>from django.shortcuts import render</p> <p># Inicializa el SDK con tu token de acceso</p> <p>sdk = mercadopago.SDK(&quot;TU_ACCESS_TOKEN&quot;)</p> <p>def total_acumulado(request):</p> <p># Realiza la consulta a la API de Mercado Pago</p> <p>try:</p> <p># Obtener el saldo total de la cuenta</p> <p>response = sdk.merchant_account().get()</p> <p>if response[&quot;status&quot;] == 200:</p> <p>total = response[&quot;response&quot;][&quot;total_balance&quot;][&quot

## djapy needs your Django wisdom: Help shape the testing infrastructure of this type-safe REST framework
 - [https://www.reddit.com/r/django/comments/1i0yljq/djapy_needs_your_django_wisdom_help_shape_the](https://www.reddit.com/r/django/comments/1i0yljq/djapy_needs_your_django_wisdom_help_shape_the)
 - RSS feed: $source
 - date published: 2025-01-14T05:01:33+00:00

<!-- SC_OFF --><div class="md"><p>Hey Django devs! I&#39;m excited to share djapy - a framework I&#39;ve built to simplify Django REST APIs with type safety. Now I need your expertise to make it production-grade.</p> <p>Quick demo of what <a href="https://github.com/Bishwas-py/djapy">djapy</a> does: ```python</p> <h1>Regular Django views but with superpowers</h1> <p>@djapify def get_user(request) -&gt; {200: UserSchema, 404: str}: return request.user</p> <p>@djapify def create_post(request, data: BlogPostSchema) -&gt; BlogPostSchema: post = Post.objects.create(**data.model_dump()) return post # That&#39;s it! Fully typed, validated, and documented ```</p> <p>Why Django devs might care: - Native Django patterns - no new concepts to learn - Pydantic validation + Django ORM = ❤️ - Endpoints feature and IDE autocompletion that actually works (PyCharm) - OpenAPI/Swagger docs generated automatically, with a touch of dark mode - Just pip install djapy and start coding</p> <p>Now for the har

## Don’t automate screenshots, automate iframes
 - [https://www.reddit.com/r/django/comments/1i0yhg3/dont_automate_screenshots_automate_iframes](https://www.reddit.com/r/django/comments/1i0yhg3/dont_automate_screenshots_automate_iframes)
 - RSS feed: $source
 - date published: 2025-01-14T04:55:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2025/01/14/iframes-not-screenshots.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i0yhg3/dont_automate_screenshots_automate_iframes/">[comments]</a></span>

## Connecting to a Coworker's Local PostgreSQL Database on Ubuntu from My Django Web App on Windows
 - [https://www.reddit.com/r/django/comments/1i0xc8g/connecting_to_a_coworkers_local_postgresql](https://www.reddit.com/r/django/comments/1i0xc8g/connecting_to_a_coworkers_local_postgresql)
 - RSS feed: $source
 - date published: 2025-01-14T03:51:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>So currently, our local setup is as follows:</p> <ul> <li>My Django web app is hosted locally on my laptop (Windows) with a local PostgreSQL database storing usernames and passwords.</li> <li>My coworker has set up a separate local PostgreSQL database on her laptop (Ubuntu), which contains a mailing list and associated dates.</li> </ul> <p>Both systems are on a LAN network, and what I want to do is connect to her local PostgreSQL database and fetch the mailing list data and dates into my Django app.</p> <p>I&#39;m looking for guidance or best practices on how to set up this connection between the two local databases. Any advice on:</p> <ul> <li>How to configure PostgreSQL to allow connections over the LAN</li> <li>What changes I need to make on my Django settings to access her database remotely</li> </ul> <p>so these are my codes so far:</p> <pre><code>class DatabaseRouter: def db_for_read(self, model, **hints): if model._meta.app

## Can I use Multiple DB in Django?
 - [https://www.reddit.com/r/django/comments/1i0uv2s/can_i_use_multiple_db_in_django](https://www.reddit.com/r/django/comments/1i0uv2s/can_i_use_multiple_db_in_django)
 - RSS feed: $source
 - date published: 2025-01-14T01:45:13+00:00

<!-- SC_OFF --><div class="md"><p>The Issue</p> <p>Hi, I have a Django project developed by another developer. It&#39;s a backend for a CMS, so it needs to be highly available all the time. A few days ago, the DB server had a connectivity issue causing 7 hours of downtime. </p> <p>Suggestion I am Seeking</p> <p>To mitigate the issue of downtime can we use multizone DB or multiple DB, for say I keep the primary DB in other VPS providers like Interserver/OVH etc, And the Backup or Read DB in AWS, so when the primary one is unavailable then it get&#39;s to connect with the backup one. And when the Primary instance is come back online then it sync the Data there? </p> <p>Is this possible or any suggestion to achieve high availability?<br/> * It&#39;s a Wagtail CMS. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mfrg4ming"> /u/mfrg4ming </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i0uv2s/can_i_use_multiple_db_in_django/">[lin

