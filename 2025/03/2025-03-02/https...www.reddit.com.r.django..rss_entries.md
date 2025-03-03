# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django In Production Having Too Many Open Files
 - [https://www.reddit.com/r/django/comments/1j1zqet/django_in_production_having_too_many_open_files](https://www.reddit.com/r/django/comments/1j1zqet/django_in_production_having_too_many_open_files)
 - RSS feed: $source
 - date published: 2025-03-02T19:54:23+00:00

<!-- SC_OFF --><div class="md"><p>I have one VPS thats running about 5 Django servers behind nginx. All are using gunicorn and are somewhat complex. Celery tasks and management commands running on cron.</p> <p>But i have one of them that is causing a huge problem.</p> <pre><code>[Errno 24] Too many open files: &#39;myfile.pickle&#39; </code></pre> <p>and</p> <pre><code>could not translate host name &quot;my-rds-server-hostname&quot; </code></pre> <p>When i run this one server the number of handles open when running</p> <pre><code>lsof | wc -l </code></pre> <p>Is 62,000 files / handles. When i kill this one gunicorn server, it goes down to 600 open files / handles.</p> <p>I have no idea what could be causing this many open handles in this one server process. Each other gunicorn has a few hundred but this one has like 59,000 just by itself. These files are opened the SECOND the server starts so its not some kind of long term leak.</p> <p>I was thinking maybe a stray import or something

## Few years as a Django Developer but Still Feel Underqualified — Need Advice to gain Confidence
 - [https://www.reddit.com/r/django/comments/1j1w4ca/few_years_as_a_django_developer_but_still_feel](https://www.reddit.com/r/django/comments/1j1w4ca/few_years_as_a_django_developer_but_still_feel)
 - RSS feed: $source
 - date published: 2025-03-02T17:25:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have few years of experience as a Python Django developer, working from home since day one. I&#39;m currently trying to switch jobs, but I feel like I don&#39;t know enough Django or I don&#39;t have enough confidence in it.</p> <p>During this time, I&#39;ve learned many things other than just django. I haven&#39;t built enough personal projects to showcase my skills. Whenever I try to build something, I end up relying heavily on ChatGPT — although I understand what the code does and why it&#39;s written that way. Most of my learning has come from YouTube tutorials, and I&#39;m a quick learner, but I struggle with consistency.</p> <p>One day I&#39;m learning React, the next day something new, and by the end of the week, I&#39;m exploring something entirely different. I feel like I&#39;m all over the place and not mastering anything.</p> <p>Is this common among self-taught developers? How can I gain real confidence in Django? Sho

## Feeling Underqualified After 3 Years as a Django Developer — Need Advice to Regain Confidence
 - [https://www.reddit.com/r/django/comments/1j1v742/feeling_underqualified_after_3_years_as_a_django](https://www.reddit.com/r/django/comments/1j1v742/feeling_underqualified_after_3_years_as_a_django)
 - RSS feed: $source
 - date published: 2025-03-02T16:47:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,<br/> I have 3 years of experience as a Python Django developer, working from home since day one. I&#39;m currently trying to switch jobs, but I feel like I don&#39;t know enough Django and that I&#39;ve wasted my years.</p> <p>During this time, I&#39;ve learned many things other than just django. I haven&#39;t built enough personal projects to showcase my skills. Whenever I try to build something, I end up relying heavily on ChatGPT — although I understand what the code does and why it&#39;s written that way. Most of my learning has come from YouTube tutorials, and I&#39;m a quick learner, but I struggle with consistency.</p> <p>One day I&#39;m learning React, the next day something new, and by the end of the week, I&#39;m exploring something entirely different. I feel like I&#39;m all over the place and not mastering anything.</p> <p>Is this common among self-taught developers? How can I gain real confidence in Django? Should I stick to

## How to fix Websocket handshake failed in a chatapp
 - [https://www.reddit.com/r/django/comments/1j1qt0w/how_to_fix_websocket_handshake_failed_in_a_chatapp](https://www.reddit.com/r/django/comments/1j1qt0w/how_to_fix_websocket_handshake_failed_in_a_chatapp)
 - RSS feed: $source
 - date published: 2025-03-02T13:26:41+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Suitable_Cash242"> /u/Suitable_Cash242 </a> <br/> <span><a href="/r/djangolearning/comments/1j0x0et/how_to_fix_websocket_handshake_failed/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j1qt0w/how_to_fix_websocket_handshake_failed_in_a_chatapp/">[comments]</a></span>

## Containerized RabbitMQ and Redis or host them on VPN (EC2) on Production
 - [https://www.reddit.com/r/django/comments/1j1ozwv/containerized_rabbitmq_and_redis_or_host_them_on](https://www.reddit.com/r/django/comments/1j1ozwv/containerized_rabbitmq_and_redis_or_host_them_on)
 - RSS feed: $source
 - date published: 2025-03-02T11:39:03+00:00

<!-- SC_OFF --><div class="md"><p>On development, I have containerized Django, Celery worker/beat, PostgreSQL, RabbitMQ, and Redis spun up via docker-compose.</p> <p>On production, I have two separate VPNs (EC2 instances). In the first instance, I host the PostgreSQL. In the second instance, I have the Django, Celery worker/beat, Nginx, RabbitMQ, and Redis running on the docker containers via docker-compose.</p> <p>Do you think this is the best approach? Or should I only containerized the Django, Celery worker/beat, and Nginx and move the RabbitMQ and Redis on the separate instance where the db server resides?</p> <p>What are your suggestions? TIA!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elyen-1990s"> /u/elyen-1990s </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j1ozwv/containerized_rabbitmq_and_redis_or_host_them_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j1ozwv/containeriz

## Use DjangoModelFormMutation to update instance in Graphene-Django
 - [https://www.reddit.com/r/django/comments/1j1o5za/use_djangomodelformmutation_to_update_instance_in](https://www.reddit.com/r/django/comments/1j1o5za/use_djangomodelformmutation_to_update_instance_in)
 - RSS feed: $source
 - date published: 2025-03-02T10:42:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am currently trying out graphql in my Django application. I have installed Graphene Django and tried out the first things. Now I want to implement the CRUD operations for my model as simply as possible.</p> <p>I found in the documentation that you can use the Django Forms for the mutations. So for my model I have</p> <pre><code>class Category(models.Model): id = models.UUIDField(primary_key=True, default=uuid.uuid4, editable=False) name = models.CharField(max_length=255) language = models.ForeignKey(&#39;company.Language&#39;, on_delete=models.CASCADE) </code></pre> <p>i have created a form:</p> <pre><code>class CategoryForm(forms.ModelForm): class Meta: model = Category fields = (&#39;name&#39;, &#39;language&#39;,) </code></pre> <p>And now I use this mutation</p> <pre><code>class CategoryMutation(DjangoModelFormMutation): category = graphene.Field(CategoryType) class Meta: form_class = CategoryForm class Mutation(graphene.ObjectType

## We just released v1.0.0-beta of djangoindia.org !
 - [https://www.reddit.com/r/django/comments/1j1nqk0/we_just_released_v100beta_of_djangoindiaorg](https://www.reddit.com/r/django/comments/1j1nqk0/we_just_released_v100beta_of_djangoindiaorg)
 - RSS feed: $source
 - date published: 2025-03-02T10:12:51+00:00

<!-- SC_OFF --><div class="md"><p>Good news: No more filling out event registration forms every single time.</p> <p>Better news: You can now register for Django India events in just ONE click.</p> <p>We just released v1.0.0-beta of our official website. In which we’ve added:</p> <p>🔑 Login &amp; Signup – Create your profile and stay connected.</p> <p>🎟️ One-Click Event Registration – Tap once, and you’re in!</p> <p>🛠️ Smoother Experience – Small but mighty improvements under the hood.</p> <p>Here’s the best part—the more people join, the more we can build! More signups mean better features, bigger meetups, and a stronger Django community in India.</p> <p>So, don’t just read this—sign up now and be part of it!</p> <p>🔗 <a href="http://djangoindia.org">djangoindia.org</a></p> <p>Also, our website is completely opensource, so do show some support by contributing or evening starring the repository!</p> <p>Repo: <a href="https://github.com/djangoindia/djangoindia.org">https://github.com/d

## Why am I facing this issue with CSRF ?
 - [https://www.reddit.com/r/django/comments/1j1jc4l/why_am_i_facing_this_issue_with_csrf](https://www.reddit.com/r/django/comments/1j1jc4l/why_am_i_facing_this_issue_with_csrf)
 - RSS feed: $source
 - date published: 2025-03-02T05:10:53+00:00

<!-- SC_OFF --><div class="md"><p>I do have decent experience in django but working first time on django+React, so couldn&#39;t get my head around this problem even after lot of research on internet.<br/> I would be grateful if you guys can help me out on this one</p> <p>So I have been trying to develop this Django + React app and deploy it on <a href="http://repl.it">repl.it</a></p> <p>The URL for my hosted frontend is of form &quot;SomethingFrontend.replit.app&quot;<br/> and for backend, it would be &quot;SomethingBackend.replit.app&quot;</p> <p>below are the relevant settings from my settings.py:</p> <pre><code>ALLOWED_HOSTS = [&quot;.replit.dev&quot;, &quot;.replit.app&quot;] CSRF_TRUSTED_ORIGINS = [ &quot;https://SomethingFrontend.replit.app&quot;, &quot;https://*.replit.dev&quot;, &quot;https://*.replit.app&quot; ] CORS_ALLOWED_ORIGINS = [ &quot;https://SomethingFrontend.replit.app&quot; ] CORS_ALLOW_CREDENTIALS = True SESSION_COOKIE_SAMESITE = &#39;None&#39; SESSION_COOKIE_SEC

## How do you setup an API key in your Django DRF project.
 - [https://www.reddit.com/r/django/comments/1j1j59p/how_do_you_setup_an_api_key_in_your_django_drf](https://www.reddit.com/r/django/comments/1j1j59p/how_do_you_setup_an_api_key_in_your_django_drf)
 - RSS feed: $source
 - date published: 2025-03-02T04:59:49+00:00

<!-- SC_OFF --><div class="md"><p>I have been building one DRF project for some time now, installed some API keys libraries but I didn&#39;t figure out how they worked. Anytime I make a request to an API endpoint I got some errors but when I installed the API key library it worked.</p> <p>How have you been setting up your API keys in your project?</p> <p>Thanks for your response.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/primado_"> /u/primado_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j1j59p/how_do_you_setup_an_api_key_in_your_django_drf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j1j59p/how_do_you_setup_an_api_key_in_your_django_drf/">[comments]</a></span>

