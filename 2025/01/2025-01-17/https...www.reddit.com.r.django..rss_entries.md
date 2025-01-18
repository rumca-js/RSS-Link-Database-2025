# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django Unfold
 - [https://www.reddit.com/r/django/comments/1i3s2kw/django_unfold](https://www.reddit.com/r/django/comments/1i3s2kw/django_unfold)
 - RSS feed: $source
 - date published: 2025-01-17T22:05:11+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, recently I wanted to use <code>unfold</code> to customize my admin interface, everything was working fine until I started customizing my custom user template, since my template inherits from <code>BaseUserAdmin</code> the unfold customization doesn&#39;t work and when I delete this class there is an error like &quot;<code>password1 is not a defined field&quot;</code>!</p> <p>Any help would be appreciated.</p> <p><a href="https://preview.redd.it/zpg9s32vrmde1.png?width=1142&amp;format=png&amp;auto=webp&amp;s=b8bfc40e12787d44e530b16aa6ccc320f9b6e8d3">https://preview.redd.it/zpg9s32vrmde1.png?width=1142&amp;format=png&amp;auto=webp&amp;s=b8bfc40e12787d44e530b16aa6ccc320f9b6e8d3</a></p> <p><a href="https://preview.redd.it/s7nncqtxrmde1.png?width=2172&amp;format=png&amp;auto=webp&amp;s=4e2815966a948683a39f8a8305787f7a7a55508e">CustomUser fields</a></p> <p><a href="https://preview.redd.it/hmn28q91smde1.png?width=1558&amp;format=png&amp;auto=webp&am

## Run additional script which will capture the data and create a DRF Post request.
 - [https://www.reddit.com/r/django/comments/1i3oxi5/run_additional_script_which_will_capture_the_data](https://www.reddit.com/r/django/comments/1i3oxi5/run_additional_script_which_will_capture_the_data)
 - RSS feed: $source
 - date published: 2025-01-17T19:46:14+00:00

<!-- SC_OFF --><div class="md"><p>I am working with a ZKTeco biometric device and need to capture attendance whenever someone punches in on the device. I want the script to capture this data and send it via a POST request to a Django view, which will then save the data to a Django model.</p> <p>I&#39;m not sure how to set this up properly. The process will involve:</p> <ul> <li>Capturing the data from the ZKTeco device when someone punches in.</li> <li>Sending the data to Django (using a POST request).</li> <li>Saving the data to a Django model.</li> </ul> <p>Any insights or guidance on how to configure this would be much appreciated!</p> <p><a href="https://preview.redd.it/3z53qe5onlde1.png?width=2048&amp;format=png&amp;auto=webp&amp;s=c354f7443791e117560bafde213d1726483a6897">https://preview.redd.it/3z53qe5onlde1.png?width=2048&amp;format=png&amp;auto=webp&amp;s=c354f7443791e117560bafde213d1726483a6897</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

## how the tabs are implemented in the Formula project with Unfold Admin
 - [https://www.reddit.com/r/django/comments/1i3mtpp/how_the_tabs_are_implemented_in_the_formula](https://www.reddit.com/r/django/comments/1i3mtpp/how_the_tabs_are_implemented_in_the_formula)
 - RSS feed: $source
 - date published: 2025-01-17T18:16:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello! I would like to understand how the tabs are implemented in the Formula project with Unfold Admin.<br/> In <a href="http://settings.py"><code>settings.py</code></a>, I see this configuration:</p> <pre><code>&quot;TABS&quot;: [ { &quot;models&quot;: [&quot;formula.driver&quot;, &quot;formula.constructor&quot;], &quot;items&quot;: [ { &quot;title&quot;: _(&quot;Drivers&quot;), &quot;icon&quot;: &quot;sports_motorsports&quot;, &quot;link&quot;: reverse_lazy(&quot;admin:formula_driver_changelist&quot;) }, # other items... { &quot;title&quot;: _(&quot;Constructors&quot;), &quot;icon&quot;: &quot;precision_manufacturing&quot;, &quot;link&quot;: reverse_lazy(&quot;admin:formula_constructor_changelist&quot;), }, { &quot;title&quot;: _(&quot;Custom page&quot;), &quot;icon&quot;: &quot;grade&quot;, &quot;link&quot;: reverse_lazy(&quot;admin:custom_view&quot;), }, ] } ] </code></pre> <p>I would like to know:</p> <pre><code> 1 How are models associated wit

## Packaging a component library for Django
 - [https://www.reddit.com/r/django/comments/1i3mr9a/packaging_a_component_library_for_django](https://www.reddit.com/r/django/comments/1i3mr9a/packaging_a_component_library_for_django)
 - RSS feed: $source
 - date published: 2025-01-17T18:13:16+00:00

<!-- SC_OFF --><div class="md"><p>My designer is coming with some HTML mockups that I need to cut up to make templates. I&#39;d like to start extracting them into components, especially because he&#39;s using Tailwind and, while I like the philosophy, in practice I&#39;ve found reading the class names does not help me understand what part of a page I&#39;m actually looking at. He agrees that we need to be able to just say &quot;accordion&quot; or &quot;destructive button&quot;.</p> <p>So I&#39;m looking for some advice for making reusable templates callable from template tags, *but* I also want to be able to use these templates outside of Django so I think that rules out django-components and django-cotton (which is how I originally thought about doing this).</p> <p>I&#39;m thinking I could make a package with a bunch of Jinja templates and provide an init module that exported a Jinja Environment and then I could figure out how to integrate that into a Django project that imports it.

## It Shouldn't Be This Much Work to Sync Data Between Django and Vue SPA
 - [https://www.reddit.com/r/django/comments/1i3jv5d/it_shouldnt_be_this_much_work_to_sync_data](https://www.reddit.com/r/django/comments/1i3jv5d/it_shouldnt_be_this_much_work_to_sync_data)
 - RSS feed: $source
 - date published: 2025-01-17T16:12:10+00:00

<!-- SC_OFF --><div class="md"><p>I love Django, I love Vue SPAs - but I don&#39;t like spending time writing boilerplate code to link the frontend to backend models. Serializers, Views, Services, State Management, Caching, yeah... it&#39;s a lot. So I built a system that gives Vue SPAs reactive, real-time sync with Django models. No boilerplate - just write Django models and get a reactive frontend data layer where every component&#39;s view is automatically, instantly synced with the actual database state, whether changes come from other clients, background tasks, admin panels, or anywhere else. It&#39;s snappy enough to power real-time applications like chat apps and leverages Django Rest Framework under the hood.</p> <p><strong>Demo - two clients both connected to the remote backend, staying in sync</strong></p> <p><a href="https://i.redd.it/p89ph27enkde1.gif">https://i.redd.it/p89ph27enkde1.gif</a></p> <p>Out of the box, you get smart caching that invalidates correctly when CRUD

## University project in Information system security
 - [https://www.reddit.com/r/django/comments/1i3jm0y/university_project_in_information_system_security](https://www.reddit.com/r/django/comments/1i3jm0y/university_project_in_information_system_security)
 - RSS feed: $source
 - date published: 2025-01-17T16:01:31+00:00

<!-- SC_OFF --><div class="md"><p>I have this project to do and I have already built the base app for it but now I am having trouble starting with the CA server part</p> <p>I don&#39;t know here to start and what should I do </p> <p>any help is very much appreciated </p> <p>below you will find the whole project description (sorry for the poorly translated document):</p> <h1>Creating a Server for Important Documents: Part One</h1> <h1>Objective:</h1> <p>To create a governmental system for storing individuals&#39; important personal documents, allowing electronic access upon request without the need for paper copies.</p> <p>This will be achieved by building a web application hosted on a server, accessible via a browser. Citizens can log in and upload their personal documents. On the other hand, institutional accounts will have access to view citizens&#39; documents.</p> <h1>System Architecture:</h1> <p><strong>Client:</strong></p> <p>Relies on a thin-client model, so no specialized sof

## Not able to save user credential in mysql
 - [https://www.reddit.com/r/django/comments/1i3hwlu/not_able_to_save_user_credential_in_mysql](https://www.reddit.com/r/django/comments/1i3hwlu/not_able_to_save_user_credential_in_mysql)
 - RSS feed: $source
 - date published: 2025-01-17T14:45:45+00:00

<!-- SC_OFF --><div class="md"><pre><code>def login_signup_view(request): if request.method == &quot;POST&quot;: if &#39;signup&#39; in request.POST: # Check if the request is for signup firstname = request.POST.get(&#39;fName&#39;) lastname = request.POST.get(&#39;lName&#39;) email = request.POST.get(&#39;email&#39;) password = request.POST.get(&#39;password&#39;) usertype = request.POST.get(&#39;user_type&#39;) if usertype.strip().lower() == &#39;customer&#39;: user = Customer(firstname=firstname, lastname=lastname, email=email, password=password) user.save() elif usertype.strip().lower() == &#39;partner&#39;: user = Partner(firstname=firstname, lastname=lastname, email=email, password=password) user.save() messages.success(request, &#39;Signed up successfully!&#39;) return redirect(request, &#39;/login_signup_view&#39;) elif &#39;login&#39; in request.POST: # Check if the request is for login email = request.POST[&#39;email&#39;] password = request.POST[&#39;password&#39;] user = 

## Build a Reusable Component with Django Cotton and AlpineJS
 - [https://www.reddit.com/r/django/comments/1i3gj5s/build_a_reusable_component_with_django_cotton_and](https://www.reddit.com/r/django/comments/1i3gj5s/build_a_reusable_component_with_django_cotton_and)
 - RSS feed: $source
 - date published: 2025-01-17T13:38:39+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NodeJS4Lyfe"> /u/NodeJS4Lyfe </a> <br/> <span><a href="https://joshkaramuth.com/blog/django-cotton-alpine-component/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i3gj5s/build_a_reusable_component_with_django_cotton_and/">[comments]</a></span>

## Django project hosted on Pythonanywhere
 - [https://www.reddit.com/r/django/comments/1i3f54k/django_project_hosted_on_pythonanywhere](https://www.reddit.com/r/django/comments/1i3f54k/django_project_hosted_on_pythonanywhere)
 - RSS feed: $source
 - date published: 2025-01-17T12:21:29+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for some advice as to where I should go for hosting. At the moment I run my Django app on Pythonanywhere. The app shows products with scraped data. It always worked quite well. However, as I am coming up to 250k products, the website is understandably getting slower.</p> <p>I&#39;ve started out using Sqlite as my database. I had like 80k product back then and it got a bit slower. I switched over to MySQL and it proved to be much faster. But, as stated, that isn&#39;t going to cut it anymore.</p> <p>Any advice? Is this just the way Pythonanywhere is? Should try another provider?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/EnvisionsRampage"> /u/EnvisionsRampage </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i3f54k/django_project_hosted_on_pythonanywhere/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i3f54k/django_project_hosted_on_pythonanyw

## 127.0.0.1:8000 says error while loading on Django, Python and MySql DB
 - [https://www.reddit.com/r/django/comments/1i3eta4/1270018000_says_error_while_loading_on_django](https://www.reddit.com/r/django/comments/1i3eta4/1270018000_says_error_while_loading_on_django)
 - RSS feed: $source
 - date published: 2025-01-17T12:01:29+00:00

<!-- SC_OFF --><div class="md"><p>I am working on a personal project, specifically migrating from a PHP web app to Python Django. I am struggling with the existing database. My first goal is to load data from the MySQL database into my Django app. However, instead of loading the data into the fields, I encounter an error every time I try to access and navigate through the local Django environment.</p> <p>The error is an Ajax error, and to be honest, I’ve never dealt with it before since I have little experience with Python.</p> <p>The error message is as follows: 127.0.0.1:8000 says: DataTables warning: table id=timerec-table - Ajax error. For more information about this error, please see <a href="http://datatables.net/tn/7">http://datatables.net/tn/7</a></p> <p><a href="https://preview.redd.it/hrcr4qwgnjde1.png?width=2548&amp;format=png&amp;auto=webp&amp;s=dc9d865fff746664a861be980b78e2da74a139d9">This is how it looks when trying to access the DB</a></p> <p>I assume, it&#39;s a synt

## My first “big” project. Am I missing something?
 - [https://www.reddit.com/r/django/comments/1i3cpm4/my_first_big_project_am_i_missing_something](https://www.reddit.com/r/django/comments/1i3cpm4/my_first_big_project_am_i_missing_something)
 - RSS feed: $source
 - date published: 2025-01-17T09:32:33+00:00

<!-- SC_OFF --><div class="md"><p>I’m currently working on my first “big” project. I have a couple of years of experience doing basic Django apps but this one is more complex compared to what I’ve done before.</p> <p>The thing is I am worried about my project missing things that could be highly important.</p> <p>I’ve been on this sub since I started in Django but every time I read anything here makes me paranoid and gets me thinking that I basically know nothing about developing Django apps.</p> <p>I’ve been working on it for a while and have learned a lot of things and improved those I didn’t have much practice on. To mention some, it has mixings, context processors, well related model fields, queries using select_related or prefetch_related, even programmed a package dedicated to send requests to an external server’s API where files are stored and where I get data from for the app. And currently, about to get into Celery because the files can be very big and take many time to uploa

## Beginner Django developer here, I wanna how do i progress ahead
 - [https://www.reddit.com/r/django/comments/1i3cf6i/beginner_django_developer_here_i_wanna_how_do_i](https://www.reddit.com/r/django/comments/1i3cf6i/beginner_django_developer_here_i_wanna_how_do_i)
 - RSS feed: $source
 - date published: 2025-01-17T09:10:27+00:00

<!-- SC_OFF --><div class="md"><p>i am well acquainted with Django and many of its concepts, but now i wanna know what path do i take ahead for Full Stack Development.<br/> What more technologies i must learn, what more options do i have which i can pursue.</p> <p>How do i approach to land a JOB.</p> <p>And maybe can you guys suggest me some intermediate to Advanced level projects i can work on to strengthen my resume </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shinobi6406"> /u/shinobi6406 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i3cf6i/beginner_django_developer_here_i_wanna_how_do_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i3cf6i/beginner_django_developer_here_i_wanna_how_do_i/">[comments]</a></span>

## Live Coding: Reviewing Progress and Adding GraphQL
 - [https://www.reddit.com/r/django/comments/1i34w6b/live_coding_reviewing_progress_and_adding_graphql](https://www.reddit.com/r/django/comments/1i34w6b/live_coding_reviewing_progress_and_adding_graphql)
 - RSS feed: $source
 - date published: 2025-01-17T01:22:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m continuing work on my fitness app project, and I’d love to have you join me for the next live coding session. This is an ongoing project where I’m building a fitness app using a Django backend with plans to integrate a GraphQL API and AI-powered features. If you missed last week’s post, you can check it out here: <a href="https://www.reddit.com/r/django/comments/1hxrz2k/senior_developer_live_coding/">Senior Developer Live Coding</a>.</p> <p>This week’s session will focus on:</p> <ul> <li><strong>Code Review</strong>: We’ll go over the work from last week, discuss decisions made, and look at areas for improvement.</li> <li><strong>GraphQL Implementation</strong>: Starting the GraphQL API integration, including schema design and setting up resolvers.</li> </ul> <p>If you’re interested in full-stack development, building scalable APIs, or just want to see a real-world app in progress, this is a great opportunity to learn and con
