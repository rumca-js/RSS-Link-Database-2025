# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Confused about Ninja and auth for an SPA/mobile app
 - [https://www.reddit.com/r/django/comments/1inbmqr/confused_about_ninja_and_auth_for_an_spamobile_app](https://www.reddit.com/r/django/comments/1inbmqr/confused_about_ninja_and_auth_for_an_spamobile_app)
 - RSS feed: $source
 - date published: 2025-02-11T22:37:35+00:00

<!-- SC_OFF --><div class="md"><p>I want to host a API that will be separate from the frontend (SPA or mobile app). I found out about the allauth package and Django&#39;s auth, which uses cookies. Upon doing some more research and talking to AI, I found that some people use Ninja along with DRF&#39;s JWT package. Is it normal to use these together? I also found this library that is a fork of DRF&#39;s token package but for ninja: <a href="https://github.com/eadwinCode/django-ninja-jwt">https://github.com/eadwinCode/django-ninja-jwt</a></p> <p>I guess I am a little confused about allauth because I thought I could use it for simple email/password token login because in the future, I will have other ways to login too, like sign in with Google/Apple and phone auth. </p> <p>What would you recommend? Ninja + one of the JWT packages + allauth for social? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Bottle-7626"> /u/Ok-Bottle-7626 </a> <br

## What I learned about Django security from my hidden analytics module
 - [https://www.reddit.com/r/django/comments/1ina9i4/what_i_learned_about_django_security_from_my](https://www.reddit.com/r/django/comments/1ina9i4/what_i_learned_about_django_security_from_my)
 - RSS feed: $source
 - date published: 2025-02-11T21:40:43+00:00

<!-- SC_OFF --><div class="md"><p>I built a hidden statistics module in my Django portfolio and discovered something interesting about security</p> <p>I added a secret stats endpoint to my Django site that tracks all attempts to access my site. After analyzing 2.2k unique visitors, the data tells an interesting story.</p> <p>Legitimate traffic is exactly what you&#39;d expect: homepage (2.6k visits), portfolio (911), blog (661). But here&#39;s where it gets fun - my stats module caught hundreds of automated attacks trying everything from .env file access (64 attempts) to WordPress admin panels.</p> <p>The best part? I didn&#39;t build any special security - Django&#39;s default configurations handled everything. The stats module just silently recorded all these failed attempts while serving my actual visitors without a hitch.</p> <p>My favorite discovery was seeing the persistence of some bots - one tried +50 different variations of WordPress manifest files. On a Django site. I actua

## Path and resources to learn Django
 - [https://www.reddit.com/r/django/comments/1in8nh5/path_and_resources_to_learn_django](https://www.reddit.com/r/django/comments/1in8nh5/path_and_resources_to_learn_django)
 - RSS feed: $source
 - date published: 2025-02-11T20:34:40+00:00

<!-- SC_OFF --><div class="md"><p>I am new to the web dev scene. I have already learn html, css and javascript and made some basic projects. From the beginning I was more interested in the backend part. I decided to learn to Django as I have written some games already using Python and also used OOP concepts.</p> <p>Please suggest me the resources to learn Django.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rohank710"> /u/rohank710 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1in8nh5/path_and_resources_to_learn_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1in8nh5/path_and_resources_to_learn_django/">[comments]</a></span>

## Production system design
 - [https://www.reddit.com/r/django/comments/1in5bhr/production_system_design](https://www.reddit.com/r/django/comments/1in5bhr/production_system_design)
 - RSS feed: $source
 - date published: 2025-02-11T18:19:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have been working on a django project but i cant wrap my head around how to design it for mass use.. its a stock trading project and i need it to execute trades at the same time for multiple people. What is a good resource for learning system design/architecture? I know companies like instagram used django in the beginning but i dont understand how they were able to handle many users. Is celery enough to handle such use cases?</p> <p>Please be kind i am new to this</p> <p>Thanks in advance!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iamjio_"> /u/iamjio_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1in5bhr/production_system_design/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1in5bhr/production_system_design/">[comments]</a></span>

## Django vs Flask for Large-Scale Projects on AWS?
 - [https://www.reddit.com/r/django/comments/1in4rh3/django_vs_flask_for_largescale_projects_on_aws](https://www.reddit.com/r/django/comments/1in4rh3/django_vs_flask_for_largescale_projects_on_aws)
 - RSS feed: $source
 - date published: 2025-02-11T17:57:47+00:00

<!-- SC_OFF --><div class="md"><p>I recently had an interview where the interviewer asked me which framework—Django or Flask—would be better for hosting on AWS. I’ve built small projects with both and deployed them on AWS, but I wasn’t sure how to answer in the context of a large-scale project.</p> <p>For those with real-world experience, how do these frameworks compare when scaling on AWS? Which one would you recommend for a production-level application, and why? Any insights on performance, cost, and ease of scaling would be really helpful!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZaiHighTech"> /u/ZaiHighTech </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1in4rh3/django_vs_flask_for_largescale_projects_on_aws/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1in4rh3/django_vs_flask_for_largescale_projects_on_aws/">[comments]</a></span>

## Regarding deployment and serving a Django app
 - [https://www.reddit.com/r/django/comments/1in201l/regarding_deployment_and_serving_a_django_app](https://www.reddit.com/r/django/comments/1in201l/regarding_deployment_and_serving_a_django_app)
 - RSS feed: $source
 - date published: 2025-02-11T16:03:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a doubt regarding deploying Django app, I have the django app in developement codebase in VS Code, and with DEBUG=True and sqlite as database. If i am going to deploy to AWS, i have to change it all right? but will this be automated or do i have to create a new environment? beginner in this topic or i will use a workflow to automate this everytime and will this be different? (Using Nginx and Gunicorn and all....) ??? #django #automation #AWSdeployment</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ExaminationRoutine89"> /u/ExaminationRoutine89 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1in201l/regarding_deployment_and_serving_a_django_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1in201l/regarding_deployment_and_serving_a_django_app/">[comments]</a></span>

## Soluzioni Multilingue e Multi-Lingua: Espanditi Globalmente con Django-US
 - [https://www.reddit.com/r/django/comments/1imxnrh/soluzioni_multilingue_e_multilingua_espanditi](https://www.reddit.com/r/django/comments/1imxnrh/soluzioni_multilingue_e_multilingua_espanditi)
 - RSS feed: $source
 - date published: 2025-02-11T12:40:45+00:00

<!-- SC_OFF --><div class="md"><p>Espandi la tua portata globale con il nostro sistema multilingue e multi-lingua all&#39;avanguardia alimentato da Django-US. Traduci e localizza i tuoi contenuti con precisione, garantendo una comunicazione accurata su oltre 100 progetti. La nostra soluzione offre un&#39;integrazione multilingue personalizzata per una internazionalizzazione senza interruzioni, migliorando la tua presenza globale con robuste soluzioni linguistiche e strategie sui social media. Ottimizza il tuo SEO con parole chiave localizzate, traduzioni di alta qualità e URL dedicati per ogni versione linguistica. Vivi una crescita accelerata e un miglior processo decisionale con i nostri servizi multilingue e multi-lingua su misura progettati per superare le barriere linguistiche senza sforzo.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/c

## רב-לשוני ופתרונות רב-שפתיים: התרחב גלובלית עם Django-US
 - [https://www.reddit.com/r/django/comments/1imxn92/רבלשוני_ופתרונות_רבשפתיים_התרחב_גלובלית_עם](https://www.reddit.com/r/django/comments/1imxn92/רבלשוני_ופתרונות_רבשפתיים_התרחב_גלובלית_עם)
 - RSS feed: $source
 - date published: 2025-02-11T12:40:00+00:00

<!-- SC_OFF --><div class="md"><p>הרחב את השפעתך הגלובלית עם מערכת המולטילינגואליות והמרובות שפות המתקדמת שלנו המבוססת על Django-US. תרגם ותפעל את התוכן שלך בקלות ובדייקנות, תוך הבטחת תקשורת מדויקת בלמעלה מ-100 פרויקטים. הפתרון שלנו מציע אינטגרציה מרובת שפות מותאמת אישית לגלובליזציה חלקה, ומשפר את הנוכחות הבינלאומית שלך עם פתרונות שפה חזקים ואסטרטגיות מדיה חברתית. מיטב את ה-SEO שלך עם מילות מפתח מקומיות, תרגומים באיכות גבוהה ו-URL ייחודי לכל גרסת שפה. חווה צמיחה מואצת ושיפור בקבלת ההחלטות עם שירותי המולטילינגואליות והמרובות שפות המותאמים אישית שלנו שתוכננו לגשר על מחסומי השפה בקלות.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imxn92/רבלשוני_ופתרונות_רבשפתיים_התרחב_גלובלית_עם/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imxn92/רבלשוני_ופתרונות_רבשפתיים_התרחב_גלובלית_עם/">[comments]</a></span>

## Solutions Multilingues & Multi-Langues : Développez-vous à l'échelle mondiale avec Django-US
 - [https://www.reddit.com/r/django/comments/1imxmsy/solutions_multilingues_multilangues](https://www.reddit.com/r/django/comments/1imxmsy/solutions_multilingues_multilangues)
 - RSS feed: $source
 - date published: 2025-02-11T12:39:18+00:00

<!-- SC_OFF --><div class="md"><p>Élargissez votre portée mondiale avec notre système multilingue et multilangue de pointe propulsé par Django-US. Traduisez et localisez facilement votre contenu avec précision, garantissant une communication précise à travers plus de 100 projets. Notre solution offre une intégration multilangue personnalisée pour une internationalisation harmonieuse, renforçant votre présence mondiale avec des solutions linguistiques robustes et des stratégies de médias sociaux. Optimisez votre SEO avec des mots-clés localisés, des traductions de haute qualité et des URL dédiées pour chaque version linguistique. Expérimentez une croissance accélérée et une prise de décision améliorée avec nos services multilingues et multilangues sur mesure conçus pour surmonter les barrières linguistiques sans effort.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://w

## Soluciones Multilingües y Multilanguage: Expanda Globalmente con Django-US
 - [https://www.reddit.com/r/django/comments/1imxlry/soluciones_multilingües_y_multilanguage_expanda](https://www.reddit.com/r/django/comments/1imxlry/soluciones_multilingües_y_multilanguage_expanda)
 - RSS feed: $source
 - date published: 2025-02-11T12:37:43+00:00

<!-- SC_OFF --><div class="md"><p>Expande tu alcance global con nuestro sistema multilingüe y de múltiples idiomas de vanguardia impulsado por Django-US. Traduce y localiza tu contenido con precisión sin esfuerzo, asegurando una comunicación precisa en más de 100 proyectos. Nuestra solución ofrece integración personalizada de múltiples idiomas para una internacionalización sin problemas, mejorando tu presencia global con soluciones lingüísticas robustas y estrategias de redes sociales. Optimiza tu SEO con palabras clave localizadas, traducciones de alta calidad y URLs dedicadas para cada versión de idioma. Experimenta un crecimiento acelerado y una mejora en la toma de decisiones con nuestros servicios multilingües y de múltiples idiomas diseñados para superar las barreras lingüísticas sin esfuerzo.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/djan

## Multilingual & Multi-Language Solutions: Expand Globally with Django-US
 - [https://www.reddit.com/r/django/comments/1imxj02/multilingual_multilanguage_solutions_expand](https://www.reddit.com/r/django/comments/1imxj02/multilingual_multilanguage_solutions_expand)
 - RSS feed: $source
 - date published: 2025-02-11T12:33:24+00:00

<!-- SC_OFF --><div class="md"><p>Expand your global reach with our cutting-edge multilingual and multi-language system powered by Django-US. Effortlessly translate and localize your content with precision, ensuring accurate communication across more than 100 projects. Our solution offers customized multi-language integration for seamless internationalization, enhancing your global presence with robust language solutions and social media strategies. Optimize your SEO with localized keywords, high-quality translations, and dedicated URLs for each language version. Experience accelerated growth and improved decision-making with our tailored multilingual and multi-language services designed to bridge language barriers effortlessly.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imxj02/multilingual_multilanguage_solutions_expand/">[link]

## Mehrsprachige & Multi-Sprach-Lösungen: Global expandieren mit Django-US
 - [https://www.reddit.com/r/django/comments/1imxigc/mehrsprachige_multisprachlösungen_global](https://www.reddit.com/r/django/comments/1imxigc/mehrsprachige_multisprachlösungen_global)
 - RSS feed: $source
 - date published: 2025-02-11T12:32:30+00:00

<!-- SC_OFF --><div class="md"><p>Erweitern Sie Ihre globale Reichweite mit unserem hochmodernen mehrsprachigen System, das von Django-US unterstützt wird. Übersetzen und lokalisieren Sie Ihre Inhalte mühelos und präzise, um eine genaue Kommunikation über mehr als 100 Projekte hinweg zu gewährleisten. Unsere Lösung bietet maßgeschneiderte mehrsprachige Integration für nahtlose Internationalisierung und stärkt Ihre globale Präsenz mit robusten Sprachlösungen und Social-Media-Strategien. Optimieren Sie Ihr SEO mit lokalisierten Keywords, hochwertigen Übersetzungen und dedizierten URLs für jede Sprachversion. Erleben Sie beschleunigtes Wachstum und verbesserte Entscheidungsfindung mit unseren maßgeschneiderten mehrsprachigen Diensten, die Sprachbarrieren mühelos überwinden.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imxigc/mehrsprac

## الحلول المتعددة اللغات: توسع عالميًا مع Django-US
 - [https://www.reddit.com/r/django/comments/1imxhzt/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous](https://www.reddit.com/r/django/comments/1imxhzt/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous)
 - RSS feed: $source
 - date published: 2025-02-11T12:31:43+00:00

<!-- SC_OFF --><div class="md"><p>وسع نطاق وصولك العالمي باستخدام نظامنا المتطور متعدد اللغات والمدعوم من Django-US. ترجم ومحلي محتواك بدقة وبسهولة، مما يضمن تواصلًا دقيقًا عبر أكثر من 100 مشروع. يقدم حلنا تكاملاً مخصصًا متعدد اللغات لتحقيق التدويل السلس، مما يعزز وجودك العالمي بحلول لغوية قوية واستراتيجيات وسائل التواصل الاجتماعي. قم بتحسين SEO الخاص بك باستخدام الكلمات المفتاحية المحلية، والترجمات عالية الجودة، وعناوين URL المخصصة لكل نسخة لغوية. اختبر النمو السريع وتحسين اتخاذ القرارات مع خدماتنا المخصصة متعددة اللغات المصممة لتجسير حاجز اللغة بكل سهولة.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imxhzt/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imxhzt/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous/">[comments]</a></span>

## الحلول المتعددة اللغات: توسع عالميًا مع Django-US
 - [https://www.reddit.com/r/django/comments/1imxhf5/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous](https://www.reddit.com/r/django/comments/1imxhf5/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous)
 - RSS feed: $source
 - date published: 2025-02-11T12:30:50+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://i.redd.it/jb0iymtl7iie1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imxhf5/الحلول_المتعددة_اللغات_توسع_عالميا_مع_djangous/">[comments]</a></span>

## 多语言解决方案：使用Django-US进行全球扩展
 - [https://www.reddit.com/r/django/comments/1imxgja/多语言解决方案使用djangous进行全球扩展](https://www.reddit.com/r/django/comments/1imxgja/多语言解决方案使用djangous进行全球扩展)
 - RSS feed: $source
 - date published: 2025-02-11T12:29:31+00:00

<!-- SC_OFF --><div class="md"><p>利用我们由Django-US驱动的最先进的多语言和多语言系统拓展您的全球影响力。通过精确翻译和本地化您的内容，轻松实现跨越100多个项目的准确沟通。我们的解决方案提供定制的多语言集成，实现无缝国际化，通过强大的语言解决方案和社交媒体策略增强您的全球存在。通过本地化关键词、高质量翻译和每种语言版本的专属URL来优化您的SEO。体验我们量身定制的多语言和多语言服务，实现语言障碍无缝衔接，加速增长和改进决策。</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ordinary_Store_6701"> /u/Ordinary_Store_6701 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imxgja/多语言解决方案使用djangous进行全球扩展/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imxgja/多语言解决方案使用djangous进行全球扩展/">[comments]</a></span>

## Dockerize a Django App
 - [https://www.reddit.com/r/django/comments/1imvnfk/dockerize_a_django_app](https://www.reddit.com/r/django/comments/1imvnfk/dockerize_a_django_app)
 - RSS feed: $source
 - date published: 2025-02-11T10:33:15+00:00

<!-- SC_OFF --><div class="md"><p>I need help. I want to deploy a project that I&#39;ve been working with. It&#39;s fairly simple, here&#39;s the repo: <a href="https://github.com/gabrielpistore/SiGOS-UFCAT">https://github.com/gabrielpistore/SiGOS-UFCAT</a>. I&#39;ve been thinking about using docker. Anyone could give me some advices on how should I do it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gabrielpistore_"> /u/gabrielpistore_ </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imvnfk/dockerize_a_django_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imvnfk/dockerize_a_django_app/">[comments]</a></span>

## ML + Django
 - [https://www.reddit.com/r/django/comments/1imvlw1/ml_django](https://www.reddit.com/r/django/comments/1imvlw1/ml_django)
 - RSS feed: $source
 - date published: 2025-02-11T10:30:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I’m working on a project that combines machine learning with Django. Users input a problem, and the ML model takes about 3-5 seconds to generate a solution. How should I structure the deployment? Would it be better to host the ML model on one server and the Django app on another?</p> <p>I prefer hosting everything on a VPS, though I’m not sure if that makes a difference.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DaddyAbdule"> /u/DaddyAbdule </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imvlw1/ml_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imvlw1/ml_django/">[comments]</a></span>

## Translation of parameterized messages does not work
 - [https://www.reddit.com/r/django/comments/1imu85p/translation_of_parameterized_messages_does_not](https://www.reddit.com/r/django/comments/1imu85p/translation_of_parameterized_messages_does_not)
 - RSS feed: $source
 - date published: 2025-02-11T08:43:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using Django5 with Jinja2 templates, and got translation to work. That means, my browser has a different language than &quot;en-US&quot; set, and my Django sites use the translated messages from my .po/.mo files in my language. I have confirmed that when I change messages etc., Django uses the newest version.</p> <p>The only thing that is not working is messages using parameters, such as in Jinja2</p> <pre><code>{{ _(&quot;I love number %(number)d&quot;) % {&quot;number&quot;: 43} }} </code></pre> <p>or</p> <pre><code>{% trans number=43 %}I love number {number}{% endtrans %} </code></pre> <p>or in Python/Django</p> <pre><code>from django.utils.translation import gettext_lazy as _ _(&quot;I love number %(number)d!&quot;) % {&quot;number&quot;: 1} </code></pre> <p>I have used both `%(..)d` and `%(..)s` placeholders. For these messages, the site <em>always</em> displays the english reference text, instead of the translation. Even if other messag

## I am a 15-year-old Backend Web Developer. Recently, I decided to film a course on Web Development with Django. Check it out:
 - [https://www.reddit.com/r/django/comments/1imtr4y/i_am_a_15yearold_backend_web_developer_recently_i](https://www.reddit.com/r/django/comments/1imtr4y/i_am_a_15yearold_backend_web_developer_recently_i)
 - RSS feed: $source
 - date published: 2025-02-11T08:06:28+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://youtube.com/playlist?list=PLCop1CJJCr429TJ9i1M3WG5xdwW2N-yIO&amp;si=IkDMR2w0Qz_AGdua">https://youtube.com/playlist?list=PLCop1CJJCr429TJ9i1M3WG5xdwW2N-yIO&amp;si=IkDMR2w0Qz_AGdua</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MirasZ1"> /u/MirasZ1 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1imtr4y/i_am_a_15yearold_backend_web_developer_recently_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imtr4y/i_am_a_15yearold_backend_web_developer_recently_i/">[comments]</a></span>

## Suggestions for a Backend Framework? for langchain
 - [https://www.reddit.com/r/django/comments/1imteym/suggestions_for_a_backend_framework_for_langchain](https://www.reddit.com/r/django/comments/1imteym/suggestions_for_a_backend_framework_for_langchain)
 - RSS feed: $source
 - date published: 2025-02-11T07:41:54+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I currently have a website built with Next.js that serves around 1,000 active users, and I&#39;m using <strong>Supabase</strong> with Next.js. Additionally, I’ve experimented with a study AI application built with <strong>LangChain</strong>, which provided me with valuable insights into AI integration. Now, I&#39;m planning to develop a mobile app using <strong>Expo</strong>, which means I&#39;ll need to build a robust backend. I&#39;m considering two options: <strong>Express.js</strong> and <strong>Django</strong>.</p> <p>Based on your experiences, which framework would you recommend for mobile app backend development? In terms of scalability, community support, documentation, and ease of use, which one do you find more advantageous? Your insights and recommendations would be greatly appreciated.</p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CoupleNo9660"> /u/CoupleNo9660

## Update on my project
 - [https://www.reddit.com/r/django/comments/1imt7i6/update_on_my_project](https://www.reddit.com/r/django/comments/1imt7i6/update_on_my_project)
 - RSS feed: $source
 - date published: 2025-02-11T07:26:40+00:00

<!-- SC_OFF --><div class="md"><p>Many days ago I posted an idea about my university class routin which will be operated by class representatives. </p> <p>Actually in my campus, Class Representatives (CR) send notices at WhatsApp, and it is really difficult to find notices, syllabuses, notes, exam dates etc as a student. Also hassle for CR too. So I made this project.</p> <p>Here, all general students can see their routine by selecting their sections. And CR will operate this from other pages. </p> <p>Here it the link (Select Daffodil&gt;CIS&gt;242&gt;A)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Confident-Flow-8787"> /u/Confident-Flow-8787 </a> <br/> <span><a href="http://crtext.pythonanywhere.com">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imt7i6/update_on_my_project/">[comments]</a></span>

## DSF member of the month - Lily Foote
 - [https://www.reddit.com/r/django/comments/1imr4i6/dsf_member_of_the_month_lily_foote](https://www.reddit.com/r/django/comments/1imr4i6/dsf_member_of_the_month_lily_foote)
 - RSS feed: $source
 - date published: 2025-02-11T05:11:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dwaxe"> /u/dwaxe </a> <br/> <span><a href="https://www.djangoproject.com/weblog/2025/feb/10/dsf-member-of-the-month-lily-foote/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1imr4i6/dsf_member_of_the_month_lily_foote/">[comments]</a></span>

## Seeking unpaid intern
 - [https://www.reddit.com/r/django/comments/1impzrw/seeking_unpaid_intern](https://www.reddit.com/r/django/comments/1impzrw/seeking_unpaid_intern)
 - RSS feed: $source
 - date published: 2025-02-11T04:07:45+00:00

<!-- SC_OFF --><div class="md"><p>If you’re interested in an unpaid internship for a healthtech startup please dm me. zlenox.com</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Moist-Zucchini-8086"> /u/Moist-Zucchini-8086 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1impzrw/seeking_unpaid_intern/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1impzrw/seeking_unpaid_intern/">[comments]</a></span>

