# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## I need help
 - [https://www.reddit.com/r/django/comments/1j16goo/i_need_help](https://www.reddit.com/r/django/comments/1j16goo/i_need_help)
 - RSS feed: $source
 - date published: 2025-03-01T18:40:44+00:00

<!-- SC_OFF --><div class="md"><p>I have been learning django(around 2-3 weeks) but the problem is i can&#39;t remember the libraries , i keep jumping between chat gpt and vs code , i don&#39;t know what to do , i keep refering my old projects which i have made from yt lectures , i remember the basic stuff , but i dont know what to do , please help </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/s-o_ul"> /u/s-o_ul </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j16goo/i_need_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j16goo/i_need_help/">[comments]</a></span>

## Just Published Video demonstrating How To Create Weather App in Django Using OpenWeatherMap API Let me know your thoughts on this.
 - [https://www.reddit.com/r/django/comments/1j16e72/just_published_video_demonstrating_how_to_create](https://www.reddit.com/r/django/comments/1j16e72/just_published_video_demonstrating_how_to_create)
 - RSS feed: $source
 - date published: 2025-03-01T18:37:59+00:00

<!-- SC_OFF --><div class="md"><p>Want to build a weather app using Django? In this tutorial, I’ll show you step-by-step how to create a weather application using Django and the OpenWeatherMap API. This is a beginner-friendly project that will help you understand API integration, Django views, templates, and more! </p> <p>What You’ll Learn: </p> <ul> <li>How to set up a Django project </li> <li>How to fetch weather data using the OpenWeatherMap API </li> <li>How to display real-time weather data in Django templates </li> <li>How to handle user input and API requests in Django </li> </ul> <p>Prerequisites: Basic knowledge of Python &amp; Django </p> <p>If you find this video helpful, please like, comment, and subscribe! </p> <p><a href="https://www.youtube.com/watch?v=FwEnjw228Ng&amp;t=694s">https://www.youtube.com/watch?v=FwEnjw228Ng&amp;t=694s</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Both_Ad5623"> /u/Both_Ad5623 </a> <br/> <span><a h

## Passing FileField to function for path modification sometimes results in nothing being saved, sometimes it does.
 - [https://www.reddit.com/r/django/comments/1j13n2m/passing_filefield_to_function_for_path](https://www.reddit.com/r/django/comments/1j13n2m/passing_filefield_to_function_for_path)
 - RSS feed: $source
 - date published: 2025-03-01T16:41:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to keep my repeating code to a minimum. A Video object can have 3 different files (file, thumbnail, audio). When the title of the video changes, I need to update the directory and filenames accordingly. So I came up with this function:</p> <pre><code>def compare_and_save_storage_paths(obj, field, old_storage_path, new_storage_path, commit=True): if old_storage_path == new_storage_path: log.info(f&#39;{obj.pk=} storage paths already match, {field.field.name} does not need renaming.&#39;) return False log.info(f&quot;{obj.pk=} renaming {field.field.name} {commit=}&quot;) log.debug(f&quot;{old_storage_path=}&quot;) log.debug(f&quot;{new_storage_path=}&quot;) if commit: field.storage.move(old_storage_path, new_storage_path) field.name = str(new_storage_path) obj.save() return True </code></pre> <p>Along with 3 functions for renaming each file, I&#39;ll just put one here because they&#39;re almost identical:</p> <pre><code>def video_rename_

## Django is literally too good
 - [https://www.reddit.com/r/django/comments/1j12p6t/django_is_literally_too_good](https://www.reddit.com/r/django/comments/1j12p6t/django_is_literally_too_good)
 - RSS feed: $source
 - date published: 2025-03-01T16:01:20+00:00

<!-- SC_OFF --><div class="md"><p>So i broke my DevTube project into micro services and have made many services so I needed to make an email service where when people register I will send an otp to user and django is literally great for this it has inbuilt for mail service.</p> <p>Ps - my auth service is written in nodejs where i produce send email otp to rabbitMQ queue and in django i made rabbitMQ consumer and send email otp to user.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/virgin_human"> /u/virgin_human </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j12p6t/django_is_literally_too_good/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j12p6t/django_is_literally_too_good/">[comments]</a></span>

## Cheap email backend for small Django app
 - [https://www.reddit.com/r/django/comments/1j0p6ax/cheap_email_backend_for_small_django_app](https://www.reddit.com/r/django/comments/1j0p6ax/cheap_email_backend_for_small_django_app)
 - RSS feed: $source
 - date published: 2025-03-01T02:33:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for suggestions which email backend to use for small django application. </p> <p>Will use for account verification after registration and probably in the future, for user updates.</p> <p>Right now, I know about SendGrid, Anymail, and MailGun. I used SendGrid and MailGun in the past, but is there some alternatives for cheaper option?</p> <p>Would be nice if they have a django email backend support for easy integration.</p> <p>Edit: SendGrid and MailGun has free tier 100 emails per day.</p> <p>I also, heard about using Gmail, anyone have experience using it?</p> <p>TIA.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/elyen-1990s"> /u/elyen-1990s </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j0p6ax/cheap_email_backend_for_small_django_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j0p6ax/cheap_email_backend_for_small_django_app/">[comment

