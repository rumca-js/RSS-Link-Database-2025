# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django for Everybody
 - [https://www.reddit.com/r/django/comments/1hukaax/django_for_everybody](https://www.reddit.com/r/django/comments/1hukaax/django_for_everybody)
 - RSS feed: $source
 - date published: 2025-01-05T23:11:55+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone completed the Django for everybody course? </p> <p>I just started the DJ4E course and did the first assignment —&gt; which is the tutorial from the Django website but run on python anywhere. </p> <p>I stumbled through it and had a hard time following the instructions intuitively, and I was able to complete it but I feel like I did a lot of work without knowing much of what’s actually going on. It was a lot of copy and paste. </p> <p>Is that normal? Was this exercise more to get a high level overview of how the framework is structured or should I be going through it a lot slower to actually learn everything? </p> <p>Thanks! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_debugging_life"> /u/_debugging_life </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hukaax/django_for_everybody/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hukaax/django_for_

## Webhook App in Python
 - [https://www.reddit.com/r/django/comments/1hue0qf/webhook_app_in_python](https://www.reddit.com/r/django/comments/1hue0qf/webhook_app_in_python)
 - RSS feed: $source
 - date published: 2025-01-05T18:48:24+00:00

<!-- SC_OFF --><div class="md"><p>I have to make an app in Python that exposes a webhook, processes the request, and makes an HTTP request at the end, which is pretty similar to Zapier/make/n8n.</p> <p>The app is gonna work on a large scale handling around 1k requests every day. I have experience with Flask, but I am not sure if it is the best choice or should I switch to Django or FastAPI or any other stuff you can recommend, I want to make this app as optimized as possible because it has to replace a <a href="http://make.com">make.com</a> scenario. Also, is Python the best choice or I should switch to node.js</p> <p>Last, I wanna know what can be the best and cost effective deployment solution for it, <a href="http://fly.io">fly.io</a>, cloud services, render etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Practical-Willow-858"> /u/Practical-Willow-858 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hue0qf/webhook_app_

## post response
 - [https://www.reddit.com/r/django/comments/1hu84tk/post_response](https://www.reddit.com/r/django/comments/1hu84tk/post_response)
 - RSS feed: $source
 - date published: 2025-01-05T14:25:53+00:00

<!-- SC_OFF --><div class="md"><p>i need someone&#39;s help to handle the response </p> <p>i only get this response</p> <pre><code>{ &quot;first_name&quot;: &quot;John&quot;, &quot;middle_name&quot;: &quot;&quot;, &quot;last_name&quot;: &quot;Doe&quot;, &quot;date_of_birth&quot;: &quot;2000-07-14&quot;, &quot;email&quot;: &quot;johndoe@gmail.com&quot; } </code></pre> <p>with this serializer</p> <pre><code>class RegisterUserSerializer(ModelSerializer): address = AddressSerializer(required=False) class Meta: model = CustomUser fields = (&quot;first_name&quot;, &quot;middle_name&quot;, &quot;last_name&quot;, &quot;date_of_birth&quot;, &quot;email&quot;, &quot;address&quot;) def create(self, validated_data): address_data = validated_data.pop(&#39;address&#39;) user = CustomUser.objects.create(**validated_data) Address.objects.create(**address_data, user=user) return user </code></pre> <p>i want the response something like this</p> <pre><code>{ &quot;first_name&quot;: &quot;John&quot;, &q

## Deploy Django with PyInfra
 - [https://www.reddit.com/r/django/comments/1hu7m1d/deploy_django_with_pyinfra](https://www.reddit.com/r/django/comments/1hu7m1d/deploy_django_with_pyinfra)
 - RSS feed: $source
 - date published: 2025-01-05T13:59:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/madisvain"> /u/madisvain </a> <br/> <span><a href="https://www.konstruktor.ee/blog/deploy-django-with-pyinfra">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hu7m1d/deploy_django_with_pyinfra/">[comments]</a></span>

## I have a scheduling task and would like to ask everyone for some suggestions
 - [https://www.reddit.com/r/django/comments/1hu6j4i/i_have_a_scheduling_task_and_would_like_to_ask](https://www.reddit.com/r/django/comments/1hu6j4i/i_have_a_scheduling_task_and_would_like_to_ask)
 - RSS feed: $source
 - date published: 2025-01-05T12:57:44+00:00

<!-- SC_OFF --><div class="md"><p>I have a long verbatim transcript, possibly exceeding 50,000 words. I’ve written a program to split each person’s dialogue into <code>BeforeTranscriptSegment</code>. However, I have several issues, which I’ve listed below. Please provide me with some suggestions. Thank you.</p> <ul> <li>By default, I use Gemini for translation because its input token count and output token count meet my expectations.</li> <li>The Gemini plan I’m using has a RateLimit, so I want the API request for translation to trigger only once every 4 seconds.</li> <li>If there is no transcript to translate at the moment, I’d also like the 4-second worker not to trigger.</li> <li>If there are untranslated segments or if an API call returns an error, I want to implement a retry mechanism.</li> </ul> <p>Could you suggest a good way to design this task? Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/moonandeye"> /u/moonandeye </a> <br

## Adding Product Pages in Django: A Step-by-Step Guide
 - [https://www.reddit.com/r/django/comments/1hu5um8/adding_product_pages_in_django_a_stepbystep_guide](https://www.reddit.com/r/django/comments/1hu5um8/adding_product_pages_in_django_a_stepbystep_guide)
 - RSS feed: $source
 - date published: 2025-01-05T12:13:48+00:00

<!-- SC_OFF --><div class="md"><p>Today, I shared a in-depth guide on creating a product display page and organizing products into categories, complete with a feature to add sales tags.</p> <ul> <li>Blog Link: <a href="https://django-learning.hashnode.dev/adding-product-pages-in-django-a-step-by-step-guide">Adding Product Pages in Django: A Step-by-Step Guide</a></li> </ul> <p>In our previous blog, we explored setting up the Django frontend, delving into file structure, managing static files, and seamless integration techniques.</p> <ul> <li>Previous Blog Link: <a href="https://django-learning.hashnode.dev/how-to-set-up-a-django-frontend-a-complete-tutorial">How to Set Up a Django Frontend: A Complete Tutorial</a></li> </ul> <p>Building upon that, our earlier discussions covered the foundational aspects of Django, including the admin interface and model creation, providing tips on class structures and effective use of foreign keys.</p> <ul> <li>Blog Before That: <a href="https://djan

## How do I set environment variables in AWS EC2?
 - [https://www.reddit.com/r/django/comments/1httseg/how_do_i_set_environment_variables_in_aws_ec2](https://www.reddit.com/r/django/comments/1httseg/how_do_i_set_environment_variables_in_aws_ec2)
 - RSS feed: $source
 - date published: 2025-01-05T01:11:53+00:00

<!-- SC_OFF --><div class="md"><p>What’s the safest, best, easiest way to set environment variables in an AWS EC2 instance?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mrreddituser111312"> /u/Mrreddituser111312 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1httseg/how_do_i_set_environment_variables_in_aws_ec2/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1httseg/how_do_i_set_environment_variables_in_aws_ec2/">[comments]</a></span>

## Python Backend Programmer Want A Personal SSR Website
 - [https://www.reddit.com/r/django/comments/1http9f/python_backend_programmer_want_a_personal_ssr](https://www.reddit.com/r/django/comments/1http9f/python_backend_programmer_want_a_personal_ssr)
 - RSS feed: $source
 - date published: 2025-01-05T01:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi</p> <p>I know Python and Django well. I also know React enough to get by.</p> <p>I am looking to build a website for myself, showcasing my projects, having a blog and a contact page, and more or less that&#39;s it.</p> <p>I wanted to use a read-made template and tweak it, but couldn&#39;t find anything.</p> <p>Is there a server-side-rendered Django-react (next.js?) app I can fork from Github? I don&#39;t want to re-invent all the boilerplate.</p> <p>If there isn&#39;t something, last resort is the same question without the Django requirement.</p> <p>Thanks :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/noamzilo3"> /u/noamzilo3 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1http9f/python_backend_programmer_want_a_personal_ssr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1http9f/python_backend_programmer_want_a_personal_ssr/">[comments]</a></span>

