# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Strict-origin-when-cross-origin help !!!!
 - [https://www.reddit.com/r/django/comments/1i8gna5/strictoriginwhencrossorigin_help](https://www.reddit.com/r/django/comments/1i8gna5/strictoriginwhencrossorigin_help)
 - RSS feed: $source
 - date published: 2025-01-23T22:57:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello i have this issue with cross-origins in my django app i try a lot of thing one day working ok the other day not im trying to find the issue but im getting in a loop hole is been day that im trying to find the isuse the cross origin is not working even to my local host this is how i have them set up if anyone knows something please help </p> <pre><code>ORS_URLS_REGEX = r&quot;^/api/.*$&quot; # ALLOWED_HOSTS should be just hostnames, not full URLs ALLOWED_HOSTS = [ &quot;localhost&quot;, &quot;127.0.0.1&quot;, ] # Update CORS_ALLOWED_ORIGINS to include all your frontend URLs CORS_ALLOWED_ORIGINS = [ &quot;http://localhost:3000&quot;, # React default port &quot;http://127.0.0.1:3000&quot;, &quot;https://localhost:3000&quot;, # If using HTTPS locally &quot;https://127.0.0.1:3000&quot;, ] # If you need to allow any subdomains, use CORS_ALLOWED_ORIGIN_REGEXES CORS_ALLOWED_ORIGIN_REGEXES = [ r&quot;^https://\w+\.laughterolympics\.com$&quot;, ] CORS_AL

## Djangonaut Space - New session 2025
 - [https://www.reddit.com/r/django/comments/1i8g20z/djangonaut_space_new_session_2025](https://www.reddit.com/r/django/comments/1i8g20z/djangonaut_space_new_session_2025)
 - RSS feed: $source
 - date published: 2025-01-23T22:31:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/jan/23/djangonaut-space-new-session-2025/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i8g20z/djangonaut_space_new_session_2025/">[comments]</a></span>

## Advice on JS framework to build android app using pre-existing Django backend
 - [https://www.reddit.com/r/django/comments/1i8fho3/advice_on_js_framework_to_build_android_app_using](https://www.reddit.com/r/django/comments/1i8fho3/advice_on_js_framework_to_build_android_app_using)
 - RSS feed: $source
 - date published: 2025-01-23T22:07:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I&#39;ll do my best to keep this succinct.</p> <p>Basically, I&#39;ve built a personal project with Django (ofcourse) and it currently has a basic html/css front end.</p> <p>I really want to create a mobile app/front end (android fan here) that makes use of the existing back end/will consume my API and I&#39;m leaning towards JavaScript because I&#39;ve some familiarity/confidence with basic JS already.</p> <p>Accessing device API&#39;s for the likes of offline storage is important and something I&#39;m excited to learn.</p> <p>The reason I&#39;m asking this group is because it makes sense to hear from those might have done this before or been in a similar situation and hear how they got on. I&#39;ve read about different JS frameworks already and while they give some insight - real world experience would be a great influence.</p> <p>Edit: I forgot to specifically mention if there were recommendations for frameworks that perhaps were less verb

## HTMX and Django Pagination
 - [https://www.reddit.com/r/django/comments/1i89973/htmx_and_django_pagination](https://www.reddit.com/r/django/comments/1i89973/htmx_and_django_pagination)
 - RSS feed: $source
 - date published: 2025-01-23T17:49:34+00:00

<!-- SC_OFF --><div class="md"><p>Hey Folks! </p> <p>I do have to links that do swap=&quot;innerHTML&quot; with sorted content. But I could have a case where there are to much data and I need to paginated it. </p> <p>It is working fine if I use pagination without sorting my data, but once I want first sort data and then click Prev/Next data becomes unsorted. </p> <p>Here is what I have </p> <pre><code>&lt;div class=&quot;emotion-cards__links&quot;&gt; &lt;a class=&quot;button-link button-link-mr&quot; href=&quot;{% url &#39;main:emotions&#39; %}&quot;&gt;All&lt;/a&gt; &lt;a class=&quot;button-link button-link-mr&quot; href=&quot;{% url &#39;main:emotions-positive&#39; %}&quot; hx-get=&quot;{% url &#39;main:emotions-positive&#39; %}&quot; hx-trigger=&quot;click&quot; hx-target=&quot;#emotion-data&quot; hx-swap=&quot;innerHTML&quot;&gt;Uplifting&lt;/a&gt; &lt;a class=&quot;button-link&quot; href=&quot;{% url &#39;main:emotions-negative&#39; %}&quot; hx-get=&quot;{% url &#39;main:emotio

## Strip spaces
 - [https://www.reddit.com/r/django/comments/1i88c1x/strip_spaces](https://www.reddit.com/r/django/comments/1i88c1x/strip_spaces)
 - RSS feed: $source
 - date published: 2025-01-23T17:11:23+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/kankyo"> /u/kankyo </a> <br/> <span><a href="https://kodare.net/2025/01/23/strip-spaces.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i88c1x/strip_spaces/">[comments]</a></span>

## Rotate refresh tokens in JWT
 - [https://www.reddit.com/r/django/comments/1i87gal/rotate_refresh_tokens_in_jwt](https://www.reddit.com/r/django/comments/1i87gal/rotate_refresh_tokens_in_jwt)
 - RSS feed: $source
 - date published: 2025-01-23T16:35:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi. If anyone has worked with JWT tokens where rotate refresh tokens is set to True, can you please explain how rotation works?</p> <p>For example, below is my simple JWT settings. </p> <p>ACCESS_TOKEN_LIFETIME&quot;: timedelta(minutes=5), &quot;REFRESH_TOKEN_LIFETIME&quot;: timedelta(days=1), &quot;ROTATE_REFRESH_TOKENS&quot;: True, &quot;BLACKLIST_AFTER_ROTATION&quot;: True. </p> <p>Here’s how I think it works:</p> <ol> <li>when the access token expires after 5 minutes, user requests a new access token using the refresh token (let&#39;s call it RT1) . </li> <li>Along with the access token, a new refresh token (RT2) is sent to the user. RT1 is invalidated/blacklisted.</li> <li>when again this new access token expires after 5 minutes, RT2 is used for requesting the new access token. </li> </ol> <p>I believe I have understood the process correctly so far.</p> <p>My question is, what is the validity of RT2? Is it 1 day from the time RT2 was issued or 1

## Migrating my data from one database to another in Django
 - [https://www.reddit.com/r/django/comments/1i866io/migrating_my_data_from_one_database_to_another_in](https://www.reddit.com/r/django/comments/1i866io/migrating_my_data_from_one_database_to_another_in)
 - RSS feed: $source
 - date published: 2025-01-23T15:41:20+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a project that uses Posgresql for database, but I want to migrate the records that were already created in posgresql to MySQL. Is there any timely solution to make this migration?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/josueygp"> /u/josueygp </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i866io/migrating_my_data_from_one_database_to_another_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i866io/migrating_my_data_from_one_database_to_another_in/">[comments]</a></span>

## How to Implement Role-Based Access Control (RBAC) into a Django Application
 - [https://www.reddit.com/r/django/comments/1i85rzv/how_to_implement_rolebased_access_control_rbac](https://www.reddit.com/r/django/comments/1i85rzv/how_to_implement_rolebased_access_control_rbac)
 - RSS feed: $source
 - date published: 2025-01-23T15:23:27+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Permit_io"> /u/Permit_io </a> <br/> <span><a href="https://www.permit.io/blog/how-to-implement-role-based-access-control-rbac-into-a-django-application">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i85rzv/how_to_implement_rolebased_access_control_rbac/">[comments]</a></span>

## Django Request Logger: Visualise request behaviour in form of graphs and charts!
 - [https://www.reddit.com/r/django/comments/1i8023s/django_request_logger_visualise_request_behaviour](https://www.reddit.com/r/django/comments/1i8023s/django_request_logger_visualise_request_behaviour)
 - RSS feed: $source
 - date published: 2025-01-23T10:00:58+00:00

<!-- SC_OFF --><div class="md"><p>🚀 Introducing Django Request Logger! 🚀</p> <p>Django Request Logger — a plug-and-play utility tool for Django developers that allows you to visually analyze your views and endpoint behaviors through detailed graphs and charts. 📊</p> <p>With just a few minutes of setup, you can start visualizing valuable insights from your Django app, helping you understand traffic patterns, request statistics, and much more.</p> <p>It takes just minutes to configure into your existing Django app, try it out today and start visualizing your app’s performance with beautiful graphs!</p> <p>Check it out here: <a href="https://github.com/9tykeshav/django-request-logger">https://github.com/9tykeshav/django-request-logger</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/uwuKeshav"> /u/uwuKeshav </a> <br/> <span><a href="https://i.redd.it/5x3fx91lvpee1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/commen

## How do I find internships?
 - [https://www.reddit.com/r/django/comments/1i7ybxu/how_do_i_find_internships](https://www.reddit.com/r/django/comments/1i7ybxu/how_do_i_find_internships)
 - RSS feed: $source
 - date published: 2025-01-23T07:45:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone. I&#39;m currently on the lookout for a Django-related internship and wanted to ask for some advice. I&#39;ve worked on quite a few Django projects. While I feel confident in my skills, I’m unsure how to approach finding the right internship opportunities. </p> <p>For those of you who’ve landed Django internships, how did you do it? Did you find opportunities through specific job boards, open-source contributions, or cold emailing companies?</p> <p>Any tips, resources, or strategies would be super helpful!<br/> Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Frzn23"> /u/Frzn23 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7ybxu/how_do_i_find_internships/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7ybxu/how_do_i_find_internships/">[comments]</a></span>

## Live Django app on DO
 - [https://www.reddit.com/r/django/comments/1i7vjc8/live_django_app_on_do](https://www.reddit.com/r/django/comments/1i7vjc8/live_django_app_on_do)
 - RSS feed: $source
 - date published: 2025-01-23T04:38:03+00:00

<!-- SC_OFF --><div class="md"><p>What are some good references for putting up my first Django app up on a live server using digital ocean? anybody have some good references on how to run a live application a production server?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PalpitationFalse8731"> /u/PalpitationFalse8731 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i7vjc8/live_django_app_on_do/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i7vjc8/live_django_app_on_do/">[comments]</a></span>

