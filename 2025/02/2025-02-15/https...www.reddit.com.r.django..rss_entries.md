# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## HELP: django.core.exceptions.SuspiciousFileOperation: Detected path traversal attempt
 - [https://www.reddit.com/r/django/comments/1iqdi46/help_djangocoreexceptionssuspiciousfileoperation](https://www.reddit.com/r/django/comments/1iqdi46/help_djangocoreexceptionssuspiciousfileoperation)
 - RSS feed: $source
 - date published: 2025-02-15T22:39:32+00:00

<!-- SC_OFF --><div class="md"><p>In a nutshell, I&#39;m trying to convert user-uploaded images in the admin page to .webp format and then re-save it, overwriting the non-webp image file in the specific DB row. This is done by passing the execution off to Celery/Rabbitmq after the admin hits save. I have the code working to convert the image, and I can see the new webp image in the MEDIA_ROOT dir, but when it comes time to save the new image back into the DB and overwrite the current non-webp image, I&#39;m getting a path traversal error. Here is my model&#39;s save method I am overwriting:</p> <pre><code> def save(self, *args, **kwargs): image_fields = { &#39;main_product_img&#39;: self.main_product_img, &#39;product_img_2&#39;: self.product_img_2, &#39;product_img_3&#39;: self.product_img_3, &#39;product_img_4&#39;: self.product_img_4, &#39;product_img_5&#39;: self.product_img_5, &#39;product_img_6&#39;: self.product_img_6, &#39;product_img_7&#39;: self.product_img_7, &#39;product_

## Help me in the backend.
 - [https://www.reddit.com/r/django/comments/1iqcqqa/help_me_in_the_backend](https://www.reddit.com/r/django/comments/1iqcqqa/help_me_in_the_backend)
 - RSS feed: $source
 - date published: 2025-02-15T22:05:11+00:00

<!-- SC_OFF --><div class="md"><p>Anyone who can help me with backend development in Django or provide me with a roadmap for it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Anshumaankhare2403"> /u/Anshumaankhare2403 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iqcqqa/help_me_in_the_backend/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iqcqqa/help_me_in_the_backend/">[comments]</a></span>

## Django in government
 - [https://www.reddit.com/r/django/comments/1iq9qkb/django_in_government](https://www.reddit.com/r/django/comments/1iq9qkb/django_in_government)
 - RSS feed: $source
 - date published: 2025-02-15T19:54:30+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/thibaudcolas"> /u/thibaudcolas </a> <br/> <span><a href="https://thib.me/django-in-government">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iq9qkb/django_in_government/">[comments]</a></span>

## How bad does logging impact performance?
 - [https://www.reddit.com/r/django/comments/1iq7703/how_bad_does_logging_impact_performance](https://www.reddit.com/r/django/comments/1iq7703/how_bad_does_logging_impact_performance)
 - RSS feed: $source
 - date published: 2025-02-15T18:03:09+00:00

<!-- SC_OFF --><div class="md"><p>I run django channels in my application with heavy server-client communication and every message from a client triggers a log. Is that too bad?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/3141666"> /u/3141666 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iq7703/how_bad_does_logging_impact_performance/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iq7703/how_bad_does_logging_impact_performance/">[comments]</a></span>

## 500 error while deploying to Vercel
 - [https://www.reddit.com/r/django/comments/1iq5da5/500_error_while_deploying_to_vercel](https://www.reddit.com/r/django/comments/1iq5da5/500_error_while_deploying_to_vercel)
 - RSS feed: $source
 - date published: 2025-02-15T16:42:52+00:00

<!-- SC_OFF --><div class="md"><p>I created a WhatsApp Chatbot using Django and tried deploying it to Vercel so that Meta could find my endpoints. I&#39;m using SupaBase as the postgres backend for it. But, deployment after deployment, it all fails because of a 500 Internal Server Error. I&#39;m posting the logs that I found in Vercel.</p> <p><code>Traceback (most recent call last):</code><br/> <code>File &quot;/var/task/vc__handler__python.py&quot;, line 14, in &lt;module&gt;</code><br/> <code>__vc_spec.loader.exec_module(__vc_module)</code><br/> <code>File &quot;&lt;frozen importlib._bootstrap_external&gt;&quot;, line 995, in exec_module</code><br/> <code>File &quot;&lt;frozen importlib._bootstrap&gt;&quot;, line 488, in _call_with_frames_removed</code><br/> <code>File &quot;/var/task/chatbot/chatbot/wsgi.py&quot;, line 16, in &lt;module&gt;</code><br/> <code>application = get_wsgi_application()</code><br/> <code>^^^^^^^^^^^^^^^^^^^^^^</code><br/> <code>File &quot;/var/task/django/

## Multi tenant Wagtail deployment
 - [https://www.reddit.com/r/django/comments/1iq3mes/multi_tenant_wagtail_deployment](https://www.reddit.com/r/django/comments/1iq3mes/multi_tenant_wagtail_deployment)
 - RSS feed: $source
 - date published: 2025-02-15T15:22:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I’ve built a multi-tenant Django app running Wagtail for each tenant. I’m expecting a large number of tenants and would like to know the best deployment strategy. I’ve read that Django Tenants can become slow when managing many schemas. Can this be mitigated using something like CloudSQL?</p> <p>Additionally, since multiple websites will be hosted on this app, downtime would have serious consequences. How would you structure the deployment to ensure scalability and reliability?</p> <p>I know this is multiple questions, so any insights on even one of them would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DaddyAbdule"> /u/DaddyAbdule </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1iq3mes/multi_tenant_wagtail_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1iq3mes/multi_tenant_wagtail_deployment/">[comments]</a><

## How to Create a User Registration Page in Django – Simple Guide
 - [https://www.reddit.com/r/django/comments/1ipz6w4/how_to_create_a_user_registration_page_in_django](https://www.reddit.com/r/django/comments/1ipz6w4/how_to_create_a_user_registration_page_in_django)
 - RSS feed: $source
 - date published: 2025-02-15T11:09:45+00:00

<!-- SC_OFF --><div class="md"><p>In this post, we’re setting up user registration in Django, creating forms, handling authentication, and using CSRF tokens to secure user input.</p> <ul> <li><strong>Blog Link:</strong> <a href="https://django-learning.hashnode.dev/how-to-create-a-user-registration-page-in-django">How to Create a User Registration Page in Django</a></li> </ul> <p>In the last blog, we built Login &amp; Logout functionality in Django.</p> <ul> <li><strong>Previous Blog Link:</strong> <a href="https://django-learning.hashnode.dev/add-login-and-logout-in-django-simple-guide?source=more_series_bottom_blogs">Add Login and Logout in Django – Simple Guide</a></li> </ul> <p>Give it a read and let me know your thoughts in the comments! 💬 Your feedback helps me improve these guides! 😊</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rohit8329"> /u/rohit8329 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1ipz6w4/how_to_cr

## Bookmarklets, defaults-from-GET, and iommi
 - [https://www.reddit.com/r/django/comments/1ipz0ah/bookmarklets_defaultsfromget_and_iommi](https://www.reddit.com/r/django/comments/1ipz0ah/bookmarklets_defaultsfromget_and_iommi)
 - RSS feed: $source
 - date published: 2025-02-15T10:56:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2025/02/15/bookmarklets-default-from-GET.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1ipz0ah/bookmarklets_defaultsfromget_and_iommi/">[comments]</a></span>

## Django's Migration Nightmare
 - [https://www.reddit.com/r/django/comments/1iptyrf/djangos_migration_nightmare](https://www.reddit.com/r/django/comments/1iptyrf/djangos_migration_nightmare)
 - RSS feed: $source
 - date published: 2025-02-15T04:49:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been working with Django and DRF for a while now. The one thing that gets me riled up is the migrations nightmare. I have recently been working on a system and in active development I change my models and run migrations all the time. I recently updated a model, and tried to access the model in Django admin, I got hit with </p> <pre><code>relation &quot;laboratory_labtestkit&quot; does not exist LINE 1: SELECT COUNT(*) AS &quot;__count&quot; FROM &quot;laboratory_labtestkit&quot; </code></pre> <p>I thought, easy, I can just delete all migrations and run them again. I run <code>makemigrations</code>, works okay, but when I run <code>migrate</code>, I get no migrations to apply. But when I try to access the model in Django admin, I still get </p> <pre><code>relation &quot;laboratory_labtestkit&quot; does not exist LINE 1: SELECT COUNT(*) AS &quot;__count&quot; FROM &quot;laboratory_labtestkit&quot; </code></pre> <p>So now I&#39;m stuck. Please 

