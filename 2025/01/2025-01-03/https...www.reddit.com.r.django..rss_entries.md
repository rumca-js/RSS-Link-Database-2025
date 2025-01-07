# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Do you know a site or a person I can work for as a volunteer in Django?
 - [https://www.reddit.com/r/django/comments/1hsxytf/do_you_know_a_site_or_a_person_i_can_work_for_as](https://www.reddit.com/r/django/comments/1hsxytf/do_you_know_a_site_or_a_person_i_can_work_for_as)
 - RSS feed: $source
 - date published: 2025-01-03T21:45:21+00:00

<!-- SC_OFF --><div class="md"><p>I have finished learning Django a year ago and have done some private projects and also have intermediate knowledge of HTML and CSS. I have recently learned DRF and have worked on some of my own projects، But I want to work on real projects, develop and keep up with project experts and learn from them and gain experience in this field. Is it possible to get help?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Frequent_Put_4551"> /u/Frequent_Put_4551 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hsxytf/do_you_know_a_site_or_a_person_i_can_work_for_as/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hsxytf/do_you_know_a_site_or_a_person_i_can_work_for_as/">[comments]</a></span>

## pagination access from the view
 - [https://www.reddit.com/r/django/comments/1hsxbys/pagination_access_from_the_view](https://www.reddit.com/r/django/comments/1hsxbys/pagination_access_from_the_view)
 - RSS feed: $source
 - date published: 2025-01-03T21:18:28+00:00

<!-- SC_OFF --><div class="md"><p>hello, i need to get the &quot;last page&quot; number of a pagination in a view function, because i want to redirect to last page. How to access it? I should add it to </p> <p>return redirect(&#39;manage&#39;) ...</p> <p>thanks</p> <pre><code>def create_shoe(request): if request.method == &#39;POST&#39;: if request.user.is_staff: form = ShoeAdminForm(request.POST) else: form = ShoeForm(request.POST) formset = ShoeImageFormSet(request.POST, request.FILES) if all( [ form.is_valid(), formset.is_valid() ]): shoe_instance = form.save() shoe_instance.user.add(request.user) image_instance = formset.save(commit=False) for instance in image_instance: instance.shoe = shoe_instance instance.save() print(instance.shoe) return redirect(&#39;manage&#39;) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wallbroken"> /u/wallbroken </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hsxbys/pagination_acc

## I deployed some web applications but having trouble trying to add pricing
 - [https://www.reddit.com/r/django/comments/1hswrq8/i_deployed_some_web_applications_but_having](https://www.reddit.com/r/django/comments/1hswrq8/i_deployed_some_web_applications_but_having)
 - RSS feed: $source
 - date published: 2025-01-03T20:54:40+00:00

<!-- SC_OFF --><div class="md"><p>In the past year, I have been dabbling in the jingle, rest framework and react in my journey to become a self-taught web developer. </p> <p>My first project was a ITS management system with an AI agent that is a IT helpdesk support chat bot. </p> <p>I also deployed a small vacation, inspiring cooks can use to store their recipes.</p> <p>The problem I’m having is integrating stripe to these apps! Does anybody know how to integrate strike within a project that has Django framework as the back in area is the front?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dangerous-Mind-4791"> /u/Dangerous-Mind-4791 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hswrq8/i_deployed_some_web_applications_but_having/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hswrq8/i_deployed_some_web_applications_but_having/">[comments]</a></span>

## So is Django + Vue a good stack?
 - [https://www.reddit.com/r/django/comments/1hsvvkk/so_is_django_vue_a_good_stack](https://www.reddit.com/r/django/comments/1hsvvkk/so_is_django_vue_a_good_stack)
 - RSS feed: $source
 - date published: 2025-01-03T20:15:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have been stuck in tutorial hell for a while now and decided to build a project for my school. Essentially, its a webpage will allow students to interact with teachers and each other. Can&#39;t say much more than that because it is a pretty good business idea and I want to monetise it in the future.</p> <p>It will need an authentication system, and it will involve the users updating information (so not view only, its dynamic), so a database would be necessary. Because students are using it there has to be no security issues, and it has to be visually pleasing.</p> <p>I found a teacher at my school that is willing to help me out. He has some experience in Vue, and because I am reasonably familiar with Python, I thought of handling the back end with Django and the front-end with Vue, but I have come across people saying that this is an inefficient stack that doesn&#39;t make the best of either technology.</p> <p>I also tried Firebase initially bu

## Is there a good documentation on using Django AllAuth in headless mode?
 - [https://www.reddit.com/r/django/comments/1hss7o3/is_there_a_good_documentation_on_using_django](https://www.reddit.com/r/django/comments/1hss7o3/is_there_a_good_documentation_on_using_django)
 - RSS feed: $source
 - date published: 2025-01-03T17:45:22+00:00

<!-- SC_OFF --><div class="md"><p>I find the documentation to be incomplete. Could someone point me to some examples or explain how to configure this?</p> <p>My use case is a mobile application and backend should never render any html. I would need OAuth and 3rd party login and JWT. </p> <ol> <li>Do I need to use &quot;/accounts&quot; if I am only using headless mode?<br/></li> <li>How can I use a single endpoint for all types of clients?<br/></li> <li>Do I need a separate allauth rest api for login if I have a mutation for graphene django that has an authentication mutation by default? I will only be using JWT.</li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/give_me_a_job_pls"> /u/give_me_a_job_pls </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hss7o3/is_there_a_good_documentation_on_using_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hss7o3/is_there_a_good_documentation_on

## How to create a dynamic formset by reading data from an uploaded file and then allow it to be modified before final submission and storage
 - [https://www.reddit.com/r/django/comments/1hss4oy/how_to_create_a_dynamic_formset_by_reading_data](https://www.reddit.com/r/django/comments/1hss4oy/how_to_create_a_dynamic_formset_by_reading_data)
 - RSS feed: $source
 - date published: 2025-01-03T17:41:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I have the following usecase:</p> <p>1) Users can upload a csv file of their bank transactions.</p> <p>2) The file is parsed and converted into transactions instances and categorized. The categories and list of transactions are shown to the user.</p> <p>3) The user can then make some modifications (e.g., change categories) and finally submit the formset leading to all transactions being saved in the database.</p> <p>I am currently struggling with the (3) step and not able to get a formset work which is populated from data not yet in database.</p> <p>Does anyone have examples of how to solve this? I can share code snippets of course.</p> <p>Are there better alternatives for this problem? May be HTMX, given that formsets have such bad reviews.</p> <p>p.s. my current approach is as follows:</p> <p>I handle the uploaded csv file in the POST view and extract transactions. Using these transaction instances, I populate a formset and then render i

## Communication channel integration
 - [https://www.reddit.com/r/django/comments/1hspe8i/communication_channel_integration](https://www.reddit.com/r/django/comments/1hspe8i/communication_channel_integration)
 - RSS feed: $source
 - date published: 2025-01-03T15:47:01+00:00

<!-- SC_OFF --><div class="md"><p>I am currently working on a project in DRF where a user can create a chatbot for their business and integrate it with Facebook Messenger or other services.</p> <p>The user flow will be as follows:</p> <ol> <li><p>Login to website </p></li> <li><p>Create chatbot flow</p></li> <li><p>Connect with Messenger (messenger for a specific Facebook page)</p></li> <li><p>Complete OAuth, and the setup is done</p></li> </ol> <p>The OAuth and Messenger integration seem a bit complex to implement, how can I acheive this? Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Athar_Wani"> /u/Athar_Wani </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hspe8i/communication_channel_integration/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hspe8i/communication_channel_integration/">[comments]</a></span>

## Wanna tag along a professional Django project?
 - [https://www.reddit.com/r/django/comments/1hsocpc/wanna_tag_along_a_professional_django_project](https://www.reddit.com/r/django/comments/1hsocpc/wanna_tag_along_a_professional_django_project)
 - RSS feed: $source
 - date published: 2025-01-03T15:00:56+00:00

<!-- SC_OFF --><div class="md"><p>I’m a Sr Backend Developer and I’m about to start a brand new Django project for a little side gig I have.</p> <p>I lurk a lot here and I see many of the same questions over and over. I figured some of you would like to tag along a professional (but small) Django project.</p> <p>Note: this is gonna be completely free, but I’m not going to actively teach; more like stream and comment during my development process. Maybe answer a few questions here and there.</p> <p>The project will involve celery, celery beat, PostgreSQL, and one or more LLMs yet to be chosen.</p> <p>Probably no frontend, and I’ll do everything with Django-unfold customising the admin panel. And no, you won’t be able to use any of the code for commercial purposes.</p> <p>Comment if interested and we’ll see the feasibility. I am in CET.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/raptored01"> /u/raptored01 </a> <br/> <span><a href="https://www

## ValueError on running migrations.
 - [https://www.reddit.com/r/django/comments/1hsm62d/valueerror_on_running_migrations](https://www.reddit.com/r/django/comments/1hsm62d/valueerror_on_running_migrations)
 - RSS feed: $source
 - date published: 2025-01-03T13:12:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello. Junior developer here. I&#39;m developing Users app in my project. When running migration it raises &#39;ValueError: Related model &#39;Users.customuser&#39; cannot be resolved&#39;. Please help.</p> <p><a href="http://models.py">models.py</a></p> <pre><code>class CustomUser(AbstractUser): phone_number = models.CharField(max_length=13, blank=True, null=True) ACCOUNT_TYPE_CHOICES = [ (&#39;Business&#39;, &#39;Business&#39;), (&#39;Personal&#39;, &#39;Personal&#39;), ] account_type = models.CharField(max_length=10, choices=ACCOUNT_TYPE_CHOICES, blank=True, null=True) class Profile(models.Model): user = models.OneToOneField(CustomUser, on_delete=models.CASCADE, primary_key=True) def __str__(self): return f&#39;{self.user.username} Profile&#39; </code></pre> <p><a href="http://apps.py">apps.py</a></p> <pre><code>class UsersConfig(AppConfig): default_auto_field = &#39;django.db.models.BigAutoField&#39; name = &#39;Users&#39; def ready(self): import

## Laravel Telescope Alternative for Django?
 - [https://www.reddit.com/r/django/comments/1hslvlt/laravel_telescope_alternative_for_django](https://www.reddit.com/r/django/comments/1hslvlt/laravel_telescope_alternative_for_django)
 - RSS feed: $source
 - date published: 2025-01-03T12:56:53+00:00

<!-- SC_OFF --><div class="md"><p>Is there any alternative to tool like Laravel Telescope for Django. I have startge my career with Django and been at it for 9+ years. But for last few months, I have been working with a laravel project and I came across telescope. A deep debugging tool for laravel. It got be curious to know if there is any similar tool for django?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sindhichhokro"> /u/sindhichhokro </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hslvlt/laravel_telescope_alternative_for_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hslvlt/laravel_telescope_alternative_for_django/">[comments]</a></span>

## Color picker with defined colors
 - [https://www.reddit.com/r/django/comments/1hslccm/color_picker_with_defined_colors](https://www.reddit.com/r/django/comments/1hslccm/color_picker_with_defined_colors)
 - RSS feed: $source
 - date published: 2025-01-03T12:25:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;am looking some color picker widget for forms in django. I need to define my colors to choice i think this should looks like line where every color is a box. After save form i get the name of the picked color. I&#39;ve check django-colorfield 0.11.0 but &quot;choices option&quot; don&#39;t work as expected - it shows color picker palette too.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kolo81"> /u/kolo81 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hslccm/color_picker_with_defined_colors/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hslccm/color_picker_with_defined_colors/">[comments]</a></span>

## How to find slow tests in a large Django project?
 - [https://www.reddit.com/r/django/comments/1hsk5iz/how_to_find_slow_tests_in_a_large_django_project](https://www.reddit.com/r/django/comments/1hsk5iz/how_to_find_slow_tests_in_a_large_django_project)
 - RSS feed: $source
 - date published: 2025-01-03T11:09:26+00:00

<!-- SC_OFF --><div class="md"><p>I am currently working on a very large, rather legacy product. Our test suite has over 5800 tests and currently takes around 1h 20m to go through everything during every PR.</p> <p>I know some of the tests are slow because they hit the file system, and some tests are slow because they use <code>TransactionalTestCase</code> (because of some over zealous use of signals) some are slow because they hit external services.</p> <p>I want to try and find the slowest test cases that we have so I can refactor them and get some quick wins on the tests that perform the worst, does anyone have any suggestions of the best way to do this? Are there any packages you would recommend? I would ideally like to export a report that can be shared with other members of the team, or build something that can be reported through GitHub actions.</p> <p>Because the project is so big I&#39;m currently limited to Python 3.9 and Django 3.2, we&#39;re using the built in Django unit

## Should I go for Django?
 - [https://www.reddit.com/r/django/comments/1hsi5cz/should_i_go_for_django](https://www.reddit.com/r/django/comments/1hsi5cz/should_i_go_for_django)
 - RSS feed: $source
 - date published: 2025-01-03T08:49:23+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I am in 2nd Year of My bachelor&#39;s degree in Computer Science. I have been using Flask for the past 1 year. Many people have told me that there is no future of Flask. I know that Django is feature rich whereas Flask provides a minimalist approach where you only install what you need. But the problem arises is that I am concerned about my skills in the long run. Is Flask used at the production level? My goal is to crack Big Tech company. Is it really worth the hassle to move towards Django or should I move with Flask? </p> <p>I hope to hear from the community.</p> <h1>django #learndjango #python #drf #rest #api</h1> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ContentCar3092"> /u/ContentCar3092 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hsi5cz/should_i_go_for_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hsi5cz/should_i_go_for_dj

## How to make Django Manager and Model's interactions follow the Open/Closed Principle?
 - [https://www.reddit.com/r/django/comments/1hsh1rz/how_to_make_django_manager_and_models](https://www.reddit.com/r/django/comments/1hsh1rz/how_to_make_django_manager_and_models)
 - RSS feed: $source
 - date published: 2025-01-03T07:29:49+00:00

<!-- SC_OFF --><div class="md"><p>I am designing models for my Django App and am concerned with decoupling the caller&#39;s logic from the model&#39;s implementation, so that future changes to the model itself do not require changes downstream in the codebase. In short <strong>adhering to the Open/Closed Principle (OCP)</strong>.</p> <p>I am wondering what is a best practice to implement this while leveraging Django&#39;s framework best.</p> <p>Conceptually, I believe it would make sense to do the following:</p> <p>```python from django.db import models</p> <p>class FooManager(models.Manager): def is_active(self): return self.filter(is_active=True)</p> <p>class Foo(models.Model): _bar = models.CharField(max_length=100, db_column=&quot;bar&quot;) is_active = models.BooleanField(default=True)</p> <pre><code>objects = FooManager() @property def bar(self): return self._bar @bar.setter def bar(self, value): if not self._bar: self._bar = value else: #some setter logic pass </code></pre> <p

## I think I'm doing something really stupid, if you can help me!
 - [https://www.reddit.com/r/django/comments/1hsb4g1/i_think_im_doing_something_really_stupid_if_you](https://www.reddit.com/r/django/comments/1hsb4g1/i_think_im_doing_something_really_stupid_if_you)
 - RSS feed: $source
 - date published: 2025-01-03T01:56:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I started playing with Django a few days ago, although I have known and used Python for some time, but only to carry out small administrative tasks.</p> <p>Following some Django tutorials, I can&#39;t reproduce it because at some point I&#39;m making something wrong, I simply can&#39;t access the routes that I create in the <a href="http://urls.py">urls.py</a> file.</p> <p>I will leave the prints and how my project is and if you can identify and explain the error to me, so that I can learn, it would help me a lot, thank you!</p> <p><a href="https://preview.redd.it/zhxjce2nqoae1.png?width=313&amp;format=png&amp;auto=webp&amp;s=4851e0a460b7c21853d4263262db80a29bc5ede4">https://preview.redd.it/zhxjce2nqoae1.png?width=313&amp;format=png&amp;auto=webp&amp;s=4851e0a460b7c21853d4263262db80a29bc5ede4</a></p> <p><a href="https://preview.redd.it/mc7mechoqoae1.png?width=356&amp;format=png&amp;auto=webp&amp;s=1cf2453d48280c495a62333a4daeb660c839b

## How to calculate the resources used by my entire django project
 - [https://www.reddit.com/r/django/comments/1hs8usz/how_to_calculate_the_resources_used_by_my_entire](https://www.reddit.com/r/django/comments/1hs8usz/how_to_calculate_the_resources_used_by_my_entire)
 - RSS feed: $source
 - date published: 2025-01-03T00:12:30+00:00

<!-- SC_OFF --><div class="md"><p>I want to know a way to calculate the resources (cpu and ram) my django project uses; I need that information to know the infrastructure requirements of the server where I will deploy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/josueygp"> /u/josueygp </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hs8usz/how_to_calculate_the_resources_used_by_my_entire/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hs8usz/how_to_calculate_the_resources_used_by_my_entire/">[comments]</a></span>
