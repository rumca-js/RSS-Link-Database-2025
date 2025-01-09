# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Django course 2025
 - [https://www.reddit.com/r/django/comments/1hwwjbm/django_course_2025](https://www.reddit.com/r/django/comments/1hwwjbm/django_course_2025)
 - RSS feed: $source
 - date published: 2025-01-08T22:12:47+00:00

<!-- SC_OFF --><div class="md"><p>What&#39;s the best Django course/ youtube 2024/2025?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Budget-Philosophy935"> /u/Budget-Philosophy935 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwwjbm/django_course_2025/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwwjbm/django_course_2025/">[comments]</a></span>

## Saving a model object with a foreign key?
 - [https://www.reddit.com/r/django/comments/1hwuutg/saving_a_model_object_with_a_foreign_key](https://www.reddit.com/r/django/comments/1hwuutg/saving_a_model_object_with_a_foreign_key)
 - RSS feed: $source
 - date published: 2025-01-08T21:02:02+00:00

<!-- SC_OFF --><div class="md"><p>I have a simple model (ShopAccount) which references another Model (UserAccount) as a OneToOneField. When a user creates a &quot;shop account&quot;, there should be a relation between the current user and the new shop account. But I&#39;m getting an IntegrityError as:</p> <p><code>NOT NULL constraint failed: shop_account_shopaccount.shop_name</code> </p> <p>This is just a simple process, that&#39;s why I&#39;m not using the many options that django provides. But this should work (In theory). Any help is welcome. Thanks</p> <p>Views. py</p> <pre><code>#Basic Imports @login_required def create_shop_account_view(request): user = request.user context = {} if request.method == &#39;POST&#39;: form = ShopAccountForm(request.POST) if form.is_valid(): shop_name = form.cleaned_data.get(&#39;shop_name&#39;) type_of_shop = form.cleaned_data.get(&#39;type_of_shop&#39;) shop_account0 = ShopAccount(shop_name=shop_name,type_of_shop=type_of_shop,user_account=user) s

## Today I published djc-heroicons: HeroIcons.com icons for django-components.
 - [https://www.reddit.com/r/django/comments/1hwu5zk/today_i_published_djcheroicons_heroiconscom_icons](https://www.reddit.com/r/django/comments/1hwu5zk/today_i_published_djcheroicons_heroiconscom_icons)
 - RSS feed: $source
 - date published: 2025-01-08T20:33:41+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/JuroOravec"> /u/JuroOravec </a> <br/> <span><a href="https://pypi.org/project/djc-heroicons/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwu5zk/today_i_published_djcheroicons_heroiconscom_icons/">[comments]</a></span>

## Why is it does not support writable nested fields?
 - [https://www.reddit.com/r/django/comments/1hws1cf/why_is_it_does_not_support_writable_nested_fields](https://www.reddit.com/r/django/comments/1hws1cf/why_is_it_does_not_support_writable_nested_fields)
 - RSS feed: $source
 - date published: 2025-01-08T19:04:37+00:00

<!-- SC_OFF --><div class="md"><p>Why is it does not support writable nested fields?</p> <p><a href="http://views.py">views.py</a></p> <pre><code>class UserListCreateView(ListModelMixin, CreateModelMixin, GenericAPIView): queryset = CustomUser.objects.prefetch_related(&#39;address&#39;) serializer_class = CustomUserSerializer # permission_classes = [IsAuthenticated] def get(self, request, *args, **kwargs): return self.list(request, *args, **kwargs) def post(self, request, *args, **kwargs): return self.create(request, *args, **kwargs) class UserRetrieveUpdateDestroyView(RetrieveModelMixin, UpdateModelMixin, DestroyModelMixin, GenericAPIView): queryset = CustomUser.objects.prefetch_related(&#39;address&#39;) serializer_class = CustomUserSerializer # permission_classes = [IsAuthenticated] def get(self, request, *args, **kwargs): return self.retrieve(request, *args, **kwargs) def put(self, request, *args, **kwargs): return self.update(request, *args, **kwargs) def delete(self, request, *

## How to do authentication for separate push notification?
 - [https://www.reddit.com/r/django/comments/1hwroa2/how_to_do_authentication_for_separate_push](https://www.reddit.com/r/django/comments/1hwroa2/how_to_do_authentication_for_separate_push)
 - RSS feed: $source
 - date published: 2025-01-08T18:50:00+00:00

<!-- SC_OFF --><div class="md"><p>If project A has User, jwt auth, others.</p> <p>I want to make separate django project for push notification and chat service. </p> <p>In this case, how to do auth and get User info in project B?? I still want to use drf permission class and I dont think adding sensetive info in jwt.. what should I do? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SnooCauliflowers8417"> /u/SnooCauliflowers8417 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwroa2/how_to_do_authentication_for_separate_push/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwroa2/how_to_do_authentication_for_separate_push/">[comments]</a></span>

## How to make JSON to HTML
 - [https://www.reddit.com/r/django/comments/1hwqjs7/how_to_make_json_to_html](https://www.reddit.com/r/django/comments/1hwqjs7/how_to_make_json_to_html)
 - RSS feed: $source
 - date published: 2025-01-08T18:03:50+00:00

<!-- SC_OFF --><div class="md"><p>hi to <a href="/r/django">r/django</a> I recently start working on a web project</p> <p>I done backend part using Rest Framework</p> <p>and it is returning JSON responses, now I need to</p> <p>create frontend, I want to make HTML files but</p> <p><strong>How can I make JSON into HTML file?</strong></p> <p>I would be very thankful if someone helps me.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Arame_Alex"> /u/Arame_Alex </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwqjs7/how_to_make_json_to_html/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwqjs7/how_to_make_json_to_html/">[comments]</a></span>

## What a the best tutorials on django and drf?
 - [https://www.reddit.com/r/django/comments/1hwqdfv/what_a_the_best_tutorials_on_django_and_drf](https://www.reddit.com/r/django/comments/1hwqdfv/what_a_the_best_tutorials_on_django_and_drf)
 - RSS feed: $source
 - date published: 2025-01-08T17:56:51+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys and gals. I am learning django for almost 3 months and tried many tutorials on youtube and liked on few of them. One of the best is by a guy named Corey Schafer. His tutorial is short, simle and almost completely covers many topics of django. Other tutorials are not so good as the one by this guy. Thus I was wondering whether you could recommend other tutorials similar to this. Assume you guys know good playslists which are good but not getting proper attention. Would appreciate your feedback a lot. Have a nice day folks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/random_walker_now"> /u/random_walker_now </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwqdfv/what_a_the_best_tutorials_on_django_and_drf/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwqdfv/what_a_the_best_tutorials_on_django_and_drf/">[comments]</a></span>

## Help! Is there no LSP and auto completions in Python & Django?
 - [https://www.reddit.com/r/django/comments/1hwlwrt/help_is_there_no_lsp_and_auto_completions_in](https://www.reddit.com/r/django/comments/1hwlwrt/help_is_there_no_lsp_and_auto_completions_in)
 - RSS feed: $source
 - date published: 2025-01-08T14:50:32+00:00

<!-- SC_OFF --><div class="md"><p>I have a code base running on Python 3.10. I have tried pylsp, pyright &amp; ruff but the moment I try and use something Django, The auto completions doesn&#39;t exist.</p> <p><code>Users.objects()</code> ? No completions or LSP documentations. Is this normal for python?</p> <p>I have tried Golang, NodeJS and even C. It gives me atleast something to work with. Even to know type of a variable, I need to print with <code>type()</code>.</p> <p>Just want to know if there&#39;s something that I can do to make things easier.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/akza07"> /u/akza07 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwlwrt/help_is_there_no_lsp_and_auto_completions_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwlwrt/help_is_there_no_lsp_and_auto_completions_in/">[comments]</a></span>

## Robust Full-Stack Authentication with Django Allauth, React, and React Router
 - [https://www.reddit.com/r/django/comments/1hwkkjj/robust_fullstack_authentication_with_django](https://www.reddit.com/r/django/comments/1hwkkjj/robust_fullstack_authentication_with_django)
 - RSS feed: $source
 - date published: 2025-01-08T13:45:35+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NodeJS4Lyfe"> /u/NodeJS4Lyfe </a> <br/> <span><a href="https://joshkaramuth.com/blog/django-allauth-react/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwkkjj/robust_fullstack_authentication_with_django/">[comments]</a></span>

## How to proceed learning Django
 - [https://www.reddit.com/r/django/comments/1hwj7sc/how_to_proceed_learning_django](https://www.reddit.com/r/django/comments/1hwj7sc/how_to_proceed_learning_django)
 - RSS feed: $source
 - date published: 2025-01-08T12:35:13+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been learning Django for a few months by following YouTube tutorials and different books, but very often I find myself just copying code (and making it work) without deeply understanding what is going on behind the scenes.</p> <p>Do you recommend pausing the projects I’m working on and diving deep into documentation and other sources to learn everything to the core, or just continuing without full understanding (and hoping the understanding will come with more experience)?</p> <p>What is the best approach here in your opinion? Have you experienced the same problem in your learning journey?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Suspicious_Rough6801"> /u/Suspicious_Rough6801 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwj7sc/how_to_proceed_learning_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwj7sc/how_to_proceed_learning_django/"

## Running gke jobs
 - [https://www.reddit.com/r/django/comments/1hwdzr8/running_gke_jobs](https://www.reddit.com/r/django/comments/1hwdzr8/running_gke_jobs)
 - RSS feed: $source
 - date published: 2025-01-08T07:02:26+00:00

<!-- SC_OFF --><div class="md"><p>Has anybody created and ran gke jobs from django application? I want to query the status of the job i.e if it is in progress/ failed/ succeeded. </p> <p>I am using kubernetes batchV1Api’s create_namespaced_job() method to create the job</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shoyo-02"> /u/Shoyo-02 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwdzr8/running_gke_jobs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwdzr8/running_gke_jobs/">[comments]</a></span>

## Open-Source & Free Django App Generator - Select Design, Edit DB Tables, Extended User Fields, Add Celery, Social Login (GitHub), Docker
 - [https://www.reddit.com/r/django/comments/1hwdqy3/opensource_free_django_app_generator_select](https://www.reddit.com/r/django/comments/1hwdqy3/opensource_free_django_app_generator_select)
 - RSS feed: $source
 - date published: 2025-01-08T06:46:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys!</p> <p><a href="https://App-Generator.dev">App-Generator.dev</a> service released a simple Django App Generator that might help to customize, generate, and download the code as a ZIP archive or from GitHub.</p> <p><a href="https://app-generator.dev/tools/django-generator/">https://app-generator.dev/tools/django-generator/</a></p> <p>The users can customize:</p> <ul> <li>UI: AdminLTE, Soft Dashboard .. etc (10 designs)</li> <li>DB Driver: SQLite (default), PgSQ, MySql/MariaDB</li> <li>DB Tables - table relations supported</li> <li>Extended User Model</li> <li>(optional) Social Login: GitHub</li> <li>(optional) Celery - async tasks</li> <li>(optional) Dynamic API - each model can be managed via a secured DRF endpoint</li> <li>(optional) Docker</li> <li>(optional) Ci/CD scrips for Render</li> </ul> <p>The generator code uses a combination of template code generation and Astor Library for AST manipulation - source code saved on GitHub as cele

## 🚀 Adding MongoEngine Support for DRF-SimpleJWT 🔧
 - [https://www.reddit.com/r/django/comments/1hwdh1n/adding_mongoengine_support_for_drfsimplejwt](https://www.reddit.com/r/django/comments/1hwdh1n/adding_mongoengine_support_for_drfsimplejwt)
 - RSS feed: $source
 - date published: 2025-01-08T06:29:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone! 👋</p> <p>I’m currently working on a project that uses MongoEngine with Django Rest Framework (DRF). However, I’ve hit a roadblock with the drf-simplejwt library, as it’s tightly coupled with Django’s SQL ORM.</p> <p>I want to extend the library to support MongoEngine but could use some guidance on the best approach to achieve this. 💡 If you’ve tackled something similar or have insights to share, I’d love to hear from you!</p> <p>📢 Open for Collaboration: If you’re interested in contributing to this initiative, feel free to join me. Let’s collaborate and make this happen! 💻✨</p> <p>Thanks in advance for your support and ideas! 🙏</p> <h1>MongoEngine #DjangoRestFramework #DRF #SimpleJWT #OpenSource #Collaboration</h1> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ContentCar3092"> /u/ContentCar3092 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hwdh1n/adding_mongoengine_support_for_dr

## InertiaJS Django now supports Inertia 2.0
 - [https://www.reddit.com/r/django/comments/1hwaxh6/inertiajs_django_now_supports_inertia_20](https://www.reddit.com/r/django/comments/1hwaxh6/inertiajs_django_now_supports_inertia_20)
 - RSS feed: $source
 - date published: 2025-01-08T04:01:44+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/smokingconch"> /u/smokingconch </a> <br/> <span><a href="https://github.com/inertiajs/inertia-django">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hwaxh6/inertiajs_django_now_supports_inertia_20/">[comments]</a></span>

