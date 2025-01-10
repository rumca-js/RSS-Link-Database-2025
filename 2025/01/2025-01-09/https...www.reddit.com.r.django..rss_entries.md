# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I have a question
 - [https://www.reddit.com/r/django/comments/1hxo5ub/i_have_a_question](https://www.reddit.com/r/django/comments/1hxo5ub/i_have_a_question)
 - RSS feed: $source
 - date published: 2025-01-09T21:45:02+00:00

<!-- SC_OFF --><div class="md"><p>is there a way when writing the helper text to make text associated with an argument show bold when that argument is active? for example <code>:param option_id: integer or string representation of an integer for an option ID</code> in the picture shown here</p> <p><a href="https://preview.redd.it/mi75onaig1ce1.png?width=777&amp;format=png&amp;auto=webp&amp;s=de7916246ce4b51efbfef4e255626834a62dc975">https://preview.redd.it/mi75onaig1ce1.png?width=777&amp;format=png&amp;auto=webp&amp;s=de7916246ce4b51efbfef4e255626834a62dc975</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rexsum420"> /u/Rexsum420 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxo5ub/i_have_a_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hxo5ub/i_have_a_question/">[comments]</a></span>

## Csrf problems with Django backend and vue frontend
 - [https://www.reddit.com/r/django/comments/1hxo4fn/csrf_problems_with_django_backend_and_vue_frontend](https://www.reddit.com/r/django/comments/1hxo4fn/csrf_problems_with_django_backend_and_vue_frontend)
 - RSS feed: $source
 - date published: 2025-01-09T21:43:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>I’m using Django auth to handle logins. When the user logs in they’re sent to my vue application which is on a seperate domain (localhost 5173). However once I’m on the vue application there is no csrf token in my cookies so I’m unable to access it and send it with any requests, leading to a 403 forbidden error.</p> <p>I made a view that returns the csrf token in a json response. I end up with 2 different csrf tokens for some reason, one of them from there being a get request and one that gets returned by the view. And when I try to pass the csrf in a request I still get a 403 forbidden error. </p> <p>How can my frontend access the csrf token so it can make requests to the backend? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ILikeFish69"> /u/ILikeFish69 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxo4fn/csrf_problems_with_django_backend_and_vue_frontend/">[link]</a></span

## django job oportunity
 - [https://www.reddit.com/r/django/comments/1hxkwof/django_job_oportunity](https://www.reddit.com/r/django/comments/1hxkwof/django_job_oportunity)
 - RSS feed: $source
 - date published: 2025-01-09T19:26:29+00:00

<!-- SC_OFF --><div class="md"><pre><code>Hi guys, I&#39;m a developer looking for a Python development opportunity. some of my work: https://readtime.pro stackshare: https://stackshare.io/readtime-pro/readtime-pro GitHub: https://github.com/jeancarlosti Please get in touch if there is availability.Hi guys, I&#39;m a developer looking for a Python development opportunity. some of my work: https://readtime.pro battery: https://stackshare.io/readtime-pro/readtime-pro GitHub: https://github.com/jeancarlosti Please get in touch if there is availability. </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JeanTinoco"> /u/JeanTinoco </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxkwof/django_job_oportunity/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hxkwof/django_job_oportunity/">[comments]</a></span>

## Can someone help identify my error?
 - [https://www.reddit.com/r/django/comments/1hxj7ac/can_someone_help_identify_my_error](https://www.reddit.com/r/django/comments/1hxj7ac/can_someone_help_identify_my_error)
 - RSS feed: $source
 - date published: 2025-01-09T18:15:18+00:00

<!-- SC_OFF --><div class="md"><p>### <strong>Package installed</strong><br/> <code>asgiref==3.8.1</code><br/> <code>autopep8==2.3.1</code><br/> <code>Django==5.1.4</code><br/> <code>django-environ==0.11.2</code><br/> <code>django-silk==5.3.2</code><br/> <code>djangorestframework==3.15.2</code><br/> <code>djangorestframework_simplejwt==5.4.0</code><br/> <code>gprof2dot==2024.6.6</code><br/> <code>pycodestyle==2.12.1</code><br/> <code>PyJWT==2.10.1</code><br/> <code>sqlparse==0.5.3</code></p> <p>### <strong>Models</strong></p> <pre><code>class CustomUser(AbstractUser): USERNAME_FIELD = &#39;email&#39; username = models.CharField(max_length=100, null=True, blank=True) first_name = models.CharField(max_length=100, null=False, blank=False) middle_name = models.CharField(max_length=100, null=True, blank=True) last_name = models.CharField(max_length=100, null=False, blank=False) phone_number = models.CharField(max_length=15, null=True, blank=True) email = models.EmailField(unique=True) pas

## Gunicorn worker restart resulting in 502s from load balancer
 - [https://www.reddit.com/r/django/comments/1hxfvpt/gunicorn_worker_restart_resulting_in_502s_from](https://www.reddit.com/r/django/comments/1hxfvpt/gunicorn_worker_restart_resulting_in_502s_from)
 - RSS feed: $source
 - date published: 2025-01-09T15:55:43+00:00

<!-- SC_OFF --><div class="md"><p>Not technically a Django question but I figured this community might be able to help me (and I am using Django in this setup as well - though I don&#39;t think my issue is directly related to Django). Let me know if you think there&#39;s a better place to post this question.</p> <p>My application is running in ECS behind an AWS Application Load Balancer. I have Gunicorn configured to automatically restart workers periodically via <code>--max-requests</code> and <code>--max-requests-jitter</code>. I also have <code>--keep-alive</code> set to 65 seconds which is greater than the default AWS ALB timeout of 60 seconds.</p> <p>In my Gunicorn logs I see:</p> <ul> <li>&quot;Autorestarting worker after current request.&quot;</li> <li>Serves a request</li> <li>&quot;Closing connection.&quot;</li> <li>&quot;Worker exiting&quot;</li> </ul> <p>Then I see that the AWS ALB sometimes responds to the next request with a 502. Is this because the ALB was holding open 

## What is the best route to build this app?
 - [https://www.reddit.com/r/django/comments/1hxffjy/what_is_the_best_route_to_build_this_app](https://www.reddit.com/r/django/comments/1hxffjy/what_is_the_best_route_to_build_this_app)
 - RSS feed: $source
 - date published: 2025-01-09T15:36:03+00:00

<!-- SC_OFF --><div class="md"><p>I have an idea for an application and I know django and python very well.</p> <p>I know that people will want this application to be a mobile app and that is what it will take for this app to be used more. </p> <p>Before building this out in django, should I not use django to build this app if I know that I will need it to be a mobile app or is it still ok to use django to build out the web app and then use django as the backend for the mobile app while creating the frontend using other tools? What other &quot;tools&quot; are used to create mobile app frontends that could work with a django backend api?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fiboniz"> /u/Fiboniz </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxffjy/what_is_the_best_route_to_build_this_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hxffjy/what_is_the_best_route_to_build_this_ap

## any senior or well knowing devloper can help me pls in my project (Django )
 - [https://www.reddit.com/r/django/comments/1hxcu84/any_senior_or_well_knowing_devloper_can_help_me](https://www.reddit.com/r/django/comments/1hxcu84/any_senior_or_well_knowing_devloper_can_help_me)
 - RSS feed: $source
 - date published: 2025-01-09T13:31:09+00:00

<!-- SC_OFF --><div class="md"><p>i got a project form my collage friend , he go it form client which is half done project , we bot are not able to resolve the thing (we both are bigners ),<br/> the website is not able to load statics file </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ArkonaFoob"> /u/ArkonaFoob </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxcu84/any_senior_or_well_knowing_devloper_can_help_me/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hxcu84/any_senior_or_well_knowing_devloper_can_help_me/">[comments]</a></span>

## I built a "CodePen for Django Templates"
 - [https://www.reddit.com/r/django/comments/1hxbu0f/i_built_a_codepen_for_django_templates](https://www.reddit.com/r/django/comments/1hxbu0f/i_built_a_codepen_for_django_templates)
 - RSS feed: $source
 - date published: 2025-01-09T12:35:58+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have built a <a href="https://tech-playground.com/playgrounds/django-template/">online Django Template Playground</a> that renders the template in the backend using Django&#39;s template engine, letting you even choose which version of Django to use.</p> <p>It also support creating snippets, which allows sharing of specific template snippets in a cool “try, change &amp; play with it” kind of way.<br/> For example this snippet: <a href="https://tech-playground.com/snippet/literate-wonderful-kittiwake/">https://tech-playground.com/snippet/literate-wonderful-kittiwake/</a></p> <p>The whole thing is also a Django app in the background, which I will share some more on in the near future.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProfessorLogout"> /u/ProfessorLogout </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxbu0f/i_built_a_codepen_for_django_templates/">[link]</a></spa

## debug JS with django-vite + sveltejs ?
 - [https://www.reddit.com/r/django/comments/1hxaqdr/debug_js_with_djangovite_sveltejs](https://www.reddit.com/r/django/comments/1hxaqdr/debug_js_with_djangovite_sveltejs)
 - RSS feed: $source
 - date published: 2025-01-09T11:25:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello, trying to debug a Svelte app inside Django template. Can not seem to connect VSCode or Pycharm to breakpoints. Would appreciate any hints.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Live-Conversation-49"> /u/Live-Conversation-49 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hxaqdr/debug_js_with_djangovite_sveltejs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hxaqdr/debug_js_with_djangovite_sveltejs/">[comments]</a></span>

## HTTP 500 internal server error but db is working fine
 - [https://www.reddit.com/r/django/comments/1hx7xqb/http_500_internal_server_error_but_db_is_working](https://www.reddit.com/r/django/comments/1hx7xqb/http_500_internal_server_error_but_db_is_working)
 - RSS feed: $source
 - date published: 2025-01-09T07:56:36+00:00

<!-- SC_OFF --><div class="md"><p>it shows internal server error both on frontend and in console but account is saved in db idk what is the problem and also when loging in with correct email and password it says invalid credential need help new to drf</p> <pre><code>class LoginAPIView(APIView): def post(self, request): email = request.data.get(&quot;email&quot;) password = request.data.get(&quot;password&quot;) # Authenticate the user user = authenticate(request, email=email, password=password) if not user: return Response({&quot;error&quot;: &quot;Invalid credentials&quot;}, status=HTTP_400_BAD_REQUEST) # Get or create the token token, created = Token.objects.get_or_create(user=user) # Serialize user data serializer = UserModelSerializer(user) return Response({&quot;token&quot;: token.key, &quot;user&quot;: serializer.data}, status=HTTP_200_OK) from django.db import IntegrityError class SignupAPIView(APIView): def post(self, request): serializer = UserModelSerializer(data=request.da

## Can we give custom response and status code when lambda is throttling.
 - [https://www.reddit.com/r/django/comments/1hx2n7m/can_we_give_custom_response_and_status_code_when](https://www.reddit.com/r/django/comments/1hx2n7m/can_we_give_custom_response_and_status_code_when)
 - RSS feed: $source
 - date published: 2025-01-09T02:45:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m calling lambda through API gateway(lambda proxy integration), but want to give some custom response when lambda is throttling. </p> <p>Any possible ways? Through api gateway or anything?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dramaking017"> /u/dramaking017 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hx2n7m/can_we_give_custom_response_and_status_code_when/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hx2n7m/can_we_give_custom_response_and_status_code_when/">[comments]</a></span>

## How to model addresses with multiple use cases & endpoint structure?
 - [https://www.reddit.com/r/django/comments/1hx1mnn/how_to_model_addresses_with_multiple_use_cases](https://www.reddit.com/r/django/comments/1hx1mnn/how_to_model_addresses_with_multiple_use_cases)
 - RSS feed: $source
 - date published: 2025-01-09T01:58:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m really stumped, and am finding a really small amount of discussion on this top online. Trying to learn more about DRF by building an API for a multi-vendor marketplace, which of course includes Buyer and Seller Profiles and and Order Model--all of which use addresses. So, I&#39;ve started putting something together below, but I wanted to see if there was a &quot;standard&quot; way of doing this that feels a lot less clunky. If this way is an appropriate approach, how are the serializers, views, and endpoints handled the follow RESTful principles? Right now, this feels like it creates a tangled mess of nested objects and endpoints depending on context.</p> <p><strong>Proposed Models</strong></p> <pre><code>from django.db import models from sellers.models import SellerProfile from accounts.models import BuyerProfile from orders.models import Order class Address(models.Model): line1 = models.CharField(max_length=255) line2 = models.CharField(max

## DSF member of the month - Hiroki Kiyohara
 - [https://www.reddit.com/r/django/comments/1hx094i/dsf_member_of_the_month_hiroki_kiyohara](https://www.reddit.com/r/django/comments/1hx094i/dsf_member_of_the_month_hiroki_kiyohara)
 - RSS feed: $source
 - date published: 2025-01-09T00:51:28+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/jan/08/dsf-member-of-the-month-hiroki-kiyohara/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hx094i/dsf_member_of_the_month_hiroki_kiyohara/">[comments]</a></span>

