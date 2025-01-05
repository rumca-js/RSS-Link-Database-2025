# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Landing page or splash screen?
 - [https://www.reddit.com/r/django/comments/1htp5l6/landing_page_or_splash_screen](https://www.reddit.com/r/django/comments/1htp5l6/landing_page_or_splash_screen)
 - RSS feed: $source
 - date published: 2025-01-04T21:38:57+00:00

<!-- SC_OFF --><div class="md"><p>Let’s say I’m developing a new django project but I want to get a landing page public with a video and an opt-in form, how would you do that while keeping the alpha app or mvp separate with no access until it’s ready?</p> <p><em>Edit</em></p> <p>I think I may have just answered my own question…</p> <p>I guess just creating the page as a template and then assigning it the view as the root domain would work correct?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mufasis"> /u/mufasis </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1htp5l6/landing_page_or_splash_screen/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1htp5l6/landing_page_or_splash_screen/">[comments]</a></span>

## Need help understanding the annotate method.
 - [https://www.reddit.com/r/django/comments/1htozd3/need_help_understanding_the_annotate_method](https://www.reddit.com/r/django/comments/1htozd3/need_help_understanding_the_annotate_method)
 - RSS feed: $source
 - date published: 2025-01-04T21:31:10+00:00

<!-- SC_OFF --><div class="md"><p>I want to pass extra info to each object of a queryset before passing the latter to a template as context. Is using <code>annotate()</code> a good way to achieve this? What exactly is <code>annotate()</code> for?</p> <p>To be more precise, I want the template to be able to know if it has been more than 1 hour since each object obtained via a for loop on the queryset was created. I believe I found a short and sweet way to do it but it looks like there is some kind of black magic involved in it:</p> <pre><code>queryset = MyModel.objects.annotate( created_less_than_hour_ago=Q(time_of_creation__gt=(now() - timedelta(hours=1))) ) </code></pre> <p>For context, in <code>MyModel</code> there&#39;s a <code>DateTimeField</code> with <code>auto_now_add</code> set to <code>True</code> .</p> <p>Passing this into ChatGPT, it told me Django would throw an error on this. I told it it wasn&#39;t the case and that everything seemed to work fine. It then told me to ver

## API endpoints not working for both Django and VueJS
 - [https://www.reddit.com/r/django/comments/1htod69/api_endpoints_not_working_for_both_django_and](https://www.reddit.com/r/django/comments/1htod69/api_endpoints_not_working_for_both_django_and)
 - RSS feed: $source
 - date published: 2025-01-04T21:04:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, I post a similar question about a week ago. But when I click on the &#39;Register&#39; or &#39;Login&#39; button in my Login Page and Register Page for VueJS, nothing happens. I&#39;m not logged in, e.g. not able to create an account.</p> <p>I have to API calls for both the LoginPage.vue and RegisterPage.vue and all API calls route to the correct backend Django port, 8000.</p> <p>So there is has to be a reason why my VueJS API calls can&#39;t reach my Django API endpoints for both the login/register API in my views.</p> <p>I&#39;ve come to the conclusion that the API error is coming from Django&#39;s end, especially since I can&#39;t get a 200 Response in Postman for both api/login and api/register requests. I don&#39;t believe that this is a VueJS problem.</p> <p>Here are my API views for both login/register ```</p> <pre><code># API endpoint for login @api_view([&#39;POST&#39;]) @permission_classes([AllowAny]) @authentication_classes([JW

## AI Chatbot with Django
 - [https://www.reddit.com/r/django/comments/1htnlx5/ai_chatbot_with_django](https://www.reddit.com/r/django/comments/1htnlx5/ai_chatbot_with_django)
 - RSS feed: $source
 - date published: 2025-01-04T20:30:41+00:00

<!-- SC_OFF --><div class="md"><p>Let’s create a mini gpt using Django and Google Gemini AI :D. We will see and learn how we can use AI and what is the working logic of AI.</p> <p><a href="https://preview.redd.it/l2h58dzse1be1.jpg?width=3024&amp;format=pjpg&amp;auto=webp&amp;s=2496c35787665fbdadc9b07ca8b7ce1d80c54517">https://preview.redd.it/l2h58dzse1be1.jpg?width=3024&amp;format=pjpg&amp;auto=webp&amp;s=2496c35787665fbdadc9b07ca8b7ce1d80c54517</a></p> <p>GitHub URL: <a href="https://github.com/TheHormat/AI__Chatbot">https://github.com/TheHormat/AI__Chatbot</a></p> <p>Medium URL: <a href="https://medium.com/@thehormat/ai-chatbot-with-django-c45d34b73051">https://medium.com/@thehormat/ai-chatbot-with-django-c45d34b73051</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheHormat"> /u/TheHormat </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1htnlx5/ai_chatbot_with_django/">[link]</a></span> &#32; <span><a href="https://www.r

## psycopg2 not being installed!! (same with psycopg2-binary)
 - [https://www.reddit.com/r/django/comments/1htgm7b/psycopg2_not_being_installed_same_with](https://www.reddit.com/r/django/comments/1htgm7b/psycopg2_not_being_installed_same_with)
 - RSS feed: $source
 - date published: 2025-01-04T15:23:37+00:00

<!-- SC_OFF --><div class="md"><p>FYI: I have tried installing both psycopg2 and psycopg2-binary, with /without environments; nothing works!<br/> <strong>The error I keep getting is below.</strong><br/> Collecting psycopg2-binary</p> <p> Using cached psycopg2-binary-2.9.10.tar.gz (385 kB)</p> <p> Preparing metadata (setup.py) ... error</p> <p> <strong>error</strong>: <strong>subprocess-exited-with-error</strong></p> <p> </p> <p> × python <a href="http://setup.py">setup.py</a> egg_info did not run successfully.</p> <p> │ exit code: <strong>1</strong></p> <p> ╰─&gt; [23 lines of output]</p> <p>running egg_info</p> <p>creating /private/var/folders/ls/jx0v9l656sg3rp2d6kw2r_s00000gn/T/pip-pip-egg-info-p43oi6bj/psycopg2_binary.egg-info</p> <p>writing /private/var/folders/ls/jx0v9l656sg3rp2d6kw2r_s00000gn/T/pip-pip-egg-info-p43oi6bj/psycopg2_binary.egg-info/PKG-INFO</p> <p>writing dependency_links to /private/var/folders/ls/jx0v9l656sg3rp2d6kw2r_s00000gn/T/pip-pip-egg-info-p43oi6bj/psycopg2

## I Made a Django Deployment Tutorial with PythonAnywhere—So Grateful It Exists!
 - [https://www.reddit.com/r/django/comments/1hteuwv/i_made_a_django_deployment_tutorial_with](https://www.reddit.com/r/django/comments/1hteuwv/i_made_a_django_deployment_tutorial_with)
 - RSS feed: $source
 - date published: 2025-01-04T13:55:47+00:00

<!-- SC_OFF --><div class="md"><p>I love PythonAnywhere. When I was learning Python, it was a total game-changer—being able to open a browser anywhere and just code was amazing. It gave me a safe space to experiment and learn without the hassle of setting things up.</p> <p>What makes me appreciate it even more now is how much they give back. Their free tier is fantastic, and their paid plans are affordable. They’ve made coding so accessible, and I’m genuinely grateful for that.</p> <p>Back when I was a complete Django newb, I tried deploying on it but struggled a little—Looking back I think it was probably a typo in the WSGI configuration which made me assume it was too complicated and I switched to other services. </p> <p>However, more recently I came to realize how simple PythonAnywhere makes it. Features like persistent disks (even in the free tier!) make it such a practical choice, especially for beginners.</p> <p>A couple of nights ago, I stayed up late to create <a href="https:

