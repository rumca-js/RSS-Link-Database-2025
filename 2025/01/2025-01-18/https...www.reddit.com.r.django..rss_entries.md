# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## How can I make a common users auth table shared with Laravel app
 - [https://www.reddit.com/r/django/comments/1i4ktj2/how_can_i_make_a_common_users_auth_table_shared](https://www.reddit.com/r/django/comments/1i4ktj2/how_can_i_make_a_common_users_auth_table_shared)
 - RSS feed: $source
 - date published: 2025-01-18T23:47:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi.</p> <p>I want to use both Laravel and Django for my application. I want to have a shared database and tables accessible by both. I have kind of achieved it, by managing models, migrations etc. for all tables, except users table.</p> <p>According to my current understanding. - Laravel creates a users table with bcrypt to hash passwords.</p> <ul> <li><p>Django saves by default using PBKDF2, with some sequence of $&lt;algorithm&gt;$&lt;iterations&gt;$&lt;salt&gt;$$&lt;hash&gt;$</p></li> <li><p>I have added Django specific columns to users table, is_staff, is_superuser, timestamps etc.</p></li> </ul> <p>In Django I tried changing the hashing password method to bcrypt, but still it saves password differently.</p> <p>I tried with Custom Managers etc. along with changing the password saving format to just hash</p> <p>Any guidance is appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pkdme"> /u/pkdme </a> 

## Session data shared between websockets
 - [https://www.reddit.com/r/django/comments/1i4iaf9/session_data_shared_between_websockets](https://www.reddit.com/r/django/comments/1i4iaf9/session_data_shared_between_websockets)
 - RSS feed: $source
 - date published: 2025-01-18T21:46:12+00:00

<!-- SC_OFF --><div class="md"><p>How can I share data between 2 or more websockets within the same session (the same client connect to more websockets), I tried changing the scope attribute of the consumer but the scope is unique for all the consumers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Consistent-Serve2234"> /u/Consistent-Serve2234 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i4iaf9/session_data_shared_between_websockets/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i4iaf9/session_data_shared_between_websockets/">[comments]</a></span>

## Django Recipe Managment Application
 - [https://www.reddit.com/r/django/comments/1i4g6vw/django_recipe_managment_application](https://www.reddit.com/r/django/comments/1i4g6vw/django_recipe_managment_application)
 - RSS feed: $source
 - date published: 2025-01-18T20:10:32+00:00

<!-- SC_OFF --><div class="md"><p>Hey 👋 folks I just relase a new version of my recipes managment app on github. The new things are: - Scrape recipe from any url with help of openai chat model - Generate and scrape recipe by ingredients again with openai token more is comming </p> <p>Give a star 🌟 to follow for updates. <a href="https://github.com/mikebgrep/fork.recipes">https://github.com/mikebgrep/fork.recipes</a></p> <p>There is an API only if you want to use in your application 😉 </p> <p><a href="https://github.com/mikebgrep/forkapi">https://github.com/mikebgrep/forkapi</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Dog-715"> /u/Affectionate-Dog-715 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i4g6vw/django_recipe_managment_application/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i4g6vw/django_recipe_managment_application/">[comments]</a></span>

## Switch between databases when using Docker
 - [https://www.reddit.com/r/django/comments/1i4e1qm/switch_between_databases_when_using_docker](https://www.reddit.com/r/django/comments/1i4e1qm/switch_between_databases_when_using_docker)
 - RSS feed: $source
 - date published: 2025-01-18T18:34:28+00:00

<!-- SC_OFF --><div class="md"><p>Maybe this is more of a docker question but hopefully I can get an answer or some tips here. I have a local django install running in docker, using postgres. My docker-compose file is below. On my production machine I have postgres db dumps for backup. I&#39;d like to create a new db for my local test machine and import my db dump. I&#39;d then like to revert to my old local test db. Is this possible, and what are the steps?</p> <pre><code>version: &#39;3.8&#39; services: web: build: . command: python /code/manage.py runserver 0.0.0.0:8000 volumes: - .:/code ports: - 8000:8000 stdin_open: true tty: true depends_on: - db environment: - &quot;DJANGO_SECRET_KEY=&quot; - &quot;DJANGO_DEBUG=True&quot; - &quot;ALLOWED_HOSTS=.smartmark.ca,localhost,127.0.0.1&quot; db: image: postgres:14 volumes: - postgres_data:/var/lib/postgresql/data/ environment: - &quot;POSTGRES_HOST_AUTH_METHOD=trust&quot; </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a 

## Creating a Expense Tracker App
 - [https://www.reddit.com/r/django/comments/1i4dhky/creating_a_expense_tracker_app](https://www.reddit.com/r/django/comments/1i4dhky/creating_a_expense_tracker_app)
 - RSS feed: $source
 - date published: 2025-01-18T18:09:39+00:00

<!-- SC_OFF --><div class="md"><p><strong>Hello everyone</strong><br/> Over the next few days, I’m challenging myself to build an <strong>Expense Tracker App</strong>. 🎯 This project is all about improving my <strong>Django</strong> skills, and I’m open to suggestions, feedback, or anything that could help me learn along the way.<br/> I’d love to learn from you all and collaborate—if you&#39;re also looking to level up your Django skills or need an idea for a project, feel free to join in!</p> <p><strong>App Overview</strong>:</p> <ul> <li>Expense tracking app</li> <li>Takes in user data</li> <li>Posts data to MySQL database</li> <li>Visualizes data using <strong>Chart.js / any other technology</strong></li> </ul> <p>Here&#39;s the GitHub repo: <a href="https://github.com/keith244/Expense-Tracker">GitHub </a></p> <p>Snippets of what I&#39;ve made so far :</p> <p><a href="https://preview.redd.it/dw6hqu33lsde1.png?width=589&amp;format=png&amp;auto=webp&amp;s=9700da4ff400bbc83a347a73e98

## 🎬 Django Webflix - Subscription-Based Movie Streaming Platform
 - [https://www.reddit.com/r/django/comments/1i4d913/django_webflix_subscriptionbased_movie_streaming](https://www.reddit.com/r/django/comments/1i4d913/django_webflix_subscriptionbased_movie_streaming)
 - RSS feed: $source
 - date published: 2025-01-18T17:59:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! I wanted to share my Django project that might help other beginners. It&#39;s a subscription based streaming(though streaming isn&#39;t available yet) platform that I built to learn Django and Stripe(dj-stripe) integration.</p> <p><a href="https://preview.redd.it/enj12z69ksde1.png?width=1212&amp;format=png&amp;auto=webp&amp;s=578bd921e3f7a926ac3a80387e3a28f55b2c34c0">https://preview.redd.it/enj12z69ksde1.png?width=1212&amp;format=png&amp;auto=webp&amp;s=578bd921e3f7a926ac3a80387e3a28f55b2c34c0</a></p> <p><strong>Key Features:</strong></p> <ul> <li>User authentication</li> <li>Movie/TV series browsing</li> <li>Watch-lists &amp; Favorites</li> <li>Review system</li> <li>Stripe subscription system</li> <li>Responsive design</li> </ul> <p><strong>What You&#39;ll Learn:</strong></p> <ul> <li>Django models &amp; relationships</li> <li>Class-based views</li> <li>Template inheritance</li> <li>Stripe integration</li> <li>User authentication</li>

## advises to store millions of json
 - [https://www.reddit.com/r/django/comments/1i4cmne/advises_to_store_millions_of_json](https://www.reddit.com/r/django/comments/1i4cmne/advises_to_store_millions_of_json)
 - RSS feed: $source
 - date published: 2025-01-18T17:32:00+00:00

<!-- SC_OFF --><div class="md"><p>Hello Guys</p> <p>so i&#39;m planning to store some scraped data into m y django project i&#39;m too lazy to make for each json a model fields etc ...</p> <p>so i decided to store them as json </p> <p>which better should i store them in jsonfield or just keep them as files and store their path in database<br/> please advise me </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ronoxzoro"> /u/ronoxzoro </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i4cmne/advises_to_store_millions_of_json/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i4cmne/advises_to_store_millions_of_json/">[comments]</a></span>

## Need help for dev
 - [https://www.reddit.com/r/django/comments/1i48vi2/need_help_for_dev](https://www.reddit.com/r/django/comments/1i48vi2/need_help_for_dev)
 - RSS feed: $source
 - date published: 2025-01-18T14:38:47+00:00

<!-- SC_OFF --><div class="md"><p>Long story short, i kinda love doing software dev, but when i actually realize my point of interest it change drastically.<br/> for most of the part i love to do backend logic, and i not able to do enough good frontend in full stacks projects,<br/> suggest some ideas so that for full stack projects i can give my 100% in frontend too...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hour-Echo-9680"> /u/Hour-Echo-9680 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i48vi2/need_help_for_dev/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i48vi2/need_help_for_dev/">[comments]</a></span>

## Need Advice: Transitioning from Python Django Trainer to Full-Time Developer
 - [https://www.reddit.com/r/django/comments/1i46ro0/need_advice_transitioning_from_python_django](https://www.reddit.com/r/django/comments/1i46ro0/need_advice_transitioning_from_python_django)
 - RSS feed: $source
 - date published: 2025-01-18T12:43:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi Redditors, </p> <p>I need some urgent guidance as I’m transitioning in my career and actively looking for a job. For the past 2.3 years, I’ve been working as a Python Django Developer cum Trainer. Most of my experience has been focused on teaching students and helping them with academic projects. While this has given me excellent communication skills and a solid grasp of Django concepts, I lack hands-on experience with live projects or working in a team environment. </p> <p>I’ve always dreamed of becoming a full-time developer, but teaching commitments held me back from pursuing that goal earlier. Recently, I decided to quit my job to focus on upskilling and finding a developer role as soon as possible. I’ve started exploring Django Rest Framework, React, and building projects to strengthen my profile. I’m also doing freelance teaching to stay financially stable during this transition. </p> <p>I have a few questions:<br/> 1. If I start as a freshe

## Workshop
 - [https://www.reddit.com/r/django/comments/1i46o4u/workshop](https://www.reddit.com/r/django/comments/1i46o4u/workshop)
 - RSS feed: $source
 - date published: 2025-01-18T12:37:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello, i want to join workshop or Even for inhance my knowledge, any upcoming events/workshop for python/django developer. Location only indore and remote </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Django_Nik"> /u/Django_Nik </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i46o4u/workshop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i46o4u/workshop/">[comments]</a></span>

## how can i make a form created in admin accessible to all user
 - [https://www.reddit.com/r/django/comments/1i3z2sa/how_can_i_make_a_form_created_in_admin_accessible](https://www.reddit.com/r/django/comments/1i3z2sa/how_can_i_make_a_form_created_in_admin_accessible)
 - RSS feed: $source
 - date published: 2025-01-18T03:55:36+00:00

<!-- SC_OFF --><div class="md"><p>i created several mock data inside the admin page of django. these data are book forms (book title, summary, isbn).</p> <p>im trying to fetch these data and put it on my ui (frontend: reactjs) as well as make sure these mock data are saved in my database (mysql) but everytime i try to access it django tells me i dont have the authorisation. i double checked and configured my jwt token and made sure to [isAuthenticated] my views but i still keep getting 401</p> <p>error: <em>401 Unauthorized</em></p> <p>anyone know how to get around this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cyber_owl9427"> /u/cyber_owl9427 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1i3z2sa/how_can_i_make_a_form_created_in_admin_accessible/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1i3z2sa/how_can_i_make_a_form_created_in_admin_accessible/">[comments]</a></span>

## Ready for Production tutorials/info
 - [https://www.reddit.com/r/django/comments/1i3ukcz/ready_for_production_tutorialsinfo](https://www.reddit.com/r/django/comments/1i3ukcz/ready_for_production_tutorialsinfo)
 - RSS feed: $source
 - date published: 2025-01-18T00:00:05+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks, so basically by reading docs and googling stuff i have a pretty decent MVP for a project.</p> <p>I would like to start thinking of deploying it to a VPS so that i can make it available for my brother who&#39;s gonna be the client/user so that he can start providing feeback on the business side, tell me what works for him, what doesnt, etc.</p> <p>So, is there any good tutorial/checklist that i can read or watch, so i can learn about what NEEDS to be done to deploy? Im using DRF with a frontend.</p> <p>I also have not done auth yet and im guessing i probably should even though i will attempt to handle this from the VPS too.</p> <p>Thanks in advanced</p> <p>Edit: Should i be implementing JWT so the frontend passes this to the apis? Or whats the recommendation in this case?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sunblaze1480"> /u/sunblaze1480 </a> <br/> <span><a href="https://www.reddit.com/r/dj

