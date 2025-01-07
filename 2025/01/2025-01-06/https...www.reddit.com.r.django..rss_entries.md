# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Convert US to UK spelling based on location
 - [https://www.reddit.com/r/django/comments/1hvd06u/convert_us_to_uk_spelling_based_on_location](https://www.reddit.com/r/django/comments/1hvd06u/convert_us_to_uk_spelling_based_on_location)
 - RSS feed: $source
 - date published: 2025-01-06T23:18:37+00:00

<!-- SC_OFF --><div class="md"><p>I have a simple website with a few pages and I want to convert US to UK spelling and vice versa depending on the location of the user. I was thinking of using USE_I18N but it&#39;s only going to be a few words and I want it to change based on user&#39;s location rather than using the browser&#39;s settings. Is using USE_I18N still the best way to go about this or is it overkill? Another way I&#39;m thinking of doing it is to create a replace middleware.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/squidg_21"> /u/squidg_21 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hvd06u/convert_us_to_uk_spelling_based_on_location/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hvd06u/convert_us_to_uk_spelling_based_on_location/">[comments]</a></span>

## Perfomance optimisation
 - [https://www.reddit.com/r/django/comments/1hv8h8k/perfomance_optimisation](https://www.reddit.com/r/django/comments/1hv8h8k/perfomance_optimisation)
 - RSS feed: $source
 - date published: 2025-01-06T20:10:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi, fellas<br/> I am experincing perfomance problems with my app when processing 45 to 50 lines of products when i m transfering them from one, branch to another. The app is hosted on railway so when i initiate a transfer the server timeout, but when i connect the local db to a local development server it works it doesnt timeout. my code is below:</p> <pre><code>class ProcessTransferCartView(LoginRequiredMixin, View): def post(self, request, *args, **kwargs): &quot;&quot;&quot;it have two main functions to create a held transfer and to create a new transfer&quot;&quot;&quot; try: with transaction.atomic(): data = json.loads(request.body) print(data) action = data[&#39;action&#39;] branches = data[&#39;branches_to&#39;] transfer_id = data.get(&#39;transfer_id&#39;, &#39;&#39;) products = Inventory.objects.filter(branch=request.user.branch).select_related(&#39;branch&#39;) suppliers = Supplier.objects.all() products_dict = {product.id: product for prod

## CSS stylesheet order not being respected
 - [https://www.reddit.com/r/django/comments/1hv3qo9/css_stylesheet_order_not_being_respected](https://www.reddit.com/r/django/comments/1hv3qo9/css_stylesheet_order_not_being_respected)
 - RSS feed: $source
 - date published: 2025-01-06T16:59:34+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for advice about a stylesheet import question. I just joined a team using django 4.2.17 and webix JS library. I am trying to change the CSS for webix components, such as turning a label white. </p> <p>I have two stylesheets linked in base.html: webix.css and styles.css. Both files work in that their styles are showing up in the site. But my overrides of webix.css only work with the <code>!important</code> tag.</p> <p>The imports look like:</p> <p><code>&lt;link rel=&quot;stylesheet&quot; href=&quot;{% static &#39;css/webix.css%} &quot;&gt;</code></p> <p><code>&lt;link rel=&quot;stylesheet&quot; href=&quot;{% static &#39;css/styles.css%} &quot;&gt;</code></p> <p>If I comment out the css class declaration from webix.css, the one in styles.css works when I SHIFT + reload. So I am certain that both stylesheets are being read and that I am using the correct css accessor for the label.</p> <p>There is nothing in <a href="http://settings.py"

## First personal project
 - [https://www.reddit.com/r/django/comments/1huyeej/first_personal_project](https://www.reddit.com/r/django/comments/1huyeej/first_personal_project)
 - RSS feed: $source
 - date published: 2025-01-06T12:58:02+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I made my first project in django and react. It&#39;s a website that scraps IT job offers from all most popular websites in Poland. I want to look for junior role soon and created it to help me with that. </p> <p>It&#39;s easy to have all job offers in one place, you can save job and track your recrutation process, add notes. I also summarize description to display only essential info, mainly what company needs.</p> <p>It&#39;s supposed to also help me track what skills are in demand currently. It took longer than I expected, but want to finally be done with it. I would appreciate some suggestions, feedback 😀</p> <p><a href="https://devradar.work/">https://devradar.work/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Reasonable-Bite6193"> /u/Reasonable-Bite6193 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1huyeej/first_personal_project/">[link]</a></span> &#32; <span><a href=

## Hosting for SQL
 - [https://www.reddit.com/r/django/comments/1huvv7f/hosting_for_sql](https://www.reddit.com/r/django/comments/1huvv7f/hosting_for_sql)
 - RSS feed: $source
 - date published: 2025-01-06T10:14:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m at the point of launching my first Django app, so I&#39;m in the wonderful and messed-up world of production and hosting now.</p> <p>Is there a difference between hosting everything (the Django Instance, PostGres and User-Upload File Storage) together on the same VM (EC2 instance or Compute Instance) just in different folders vs. using something like Amazon RDS or Cloud SQL?</p> <p>Because I&#39;m assuming that just throwing everything on the same compute instance will still work (since that is how I&#39;m running it on my RaspberryPi), but there is probably scaling or security issues with it (especially with file uploads), but a dedicated RDS/CloudSQL instance is ludicrously expensive. </p> <p>How does most people here host?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/appietr"> /u/appietr </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1huvv7f/hosting_for_sql/">[link]</a></spa

## Open Source Django Custom Admin on Vue3 and Vuetify
 - [https://www.reddit.com/r/django/comments/1huu98i/open_source_django_custom_admin_on_vue3_and](https://www.reddit.com/r/django/comments/1huu98i/open_source_django_custom_admin_on_vue3_and)
 - RSS feed: $source
 - date published: 2025-01-06T08:11:59+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://innova-group-llc.github.io/custom_admin_docs">https://innova-group-llc.github.io/custom_admin_docs</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/initsbriliance"> /u/initsbriliance </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1huu98i/open_source_django_custom_admin_on_vue3_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1huu98i/open_source_django_custom_admin_on_vue3_and/">[comments]</a></span>

## Any good tutorials on system design for django?
 - [https://www.reddit.com/r/django/comments/1hurja4/any_good_tutorials_on_system_design_for_django](https://www.reddit.com/r/django/comments/1hurja4/any_good_tutorials_on_system_design_for_django)
 - RSS feed: $source
 - date published: 2025-01-06T05:10:19+00:00

<!-- SC_OFF --><div class="md"><p>Can anyone recommend any good articles or tutorial about system architecture or design when building full stack applications with django?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mufasis"> /u/mufasis </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hurja4/any_good_tutorials_on_system_design_for_django/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hurja4/any_good_tutorials_on_system_design_for_django/">[comments]</a></span>

## Django-Elasticsearch and Node-Algolia
 - [https://www.reddit.com/r/django/comments/1hurezz/djangoelasticsearch_and_nodealgolia](https://www.reddit.com/r/django/comments/1hurezz/djangoelasticsearch_and_nodealgolia)
 - RSS feed: $source
 - date published: 2025-01-06T05:03:38+00:00

<!-- SC_OFF --><div class="md"><p>Using Node JS with Algolia is very fast and reliable. Is Django and Elasticsearch also very fast, and does it offer same accuracy and reliability. What would you use for a search-first application, Node/Algolia or Django/Elasticsearch. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Arthurobo"> /u/Arthurobo </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hurezz/djangoelasticsearch_and_nodealgolia/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1hurezz/djangoelasticsearch_and_nodealgolia/">[comments]</a></span>

## Django project to be slowing down after 7 years of operation
 - [https://www.reddit.com/r/django/comments/1huprgl/django_project_to_be_slowing_down_after_7_years](https://www.reddit.com/r/django/comments/1huprgl/django_project_to_be_slowing_down_after_7_years)
 - RSS feed: $source
 - date published: 2025-01-06T03:34:10+00:00

<!-- SC_OFF --><div class="md"><p>My application has been running for 7 years. Note that it&#39;s running 1.9.10. The plan is to upgrade this year to 4.0. But I noticed that it seems to be struggling more than usual. There is a lot of data that gets generated throughout the years. </p> <p>Is there anything I can do to improve performance? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nitrodmr"> /u/nitrodmr </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1huprgl/django_project_to_be_slowing_down_after_7_years/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1huprgl/django_project_to_be_slowing_down_after_7_years/">[comments]</a></span>

## Using Djando in a Full-Stack Application, I want your opinion!
 - [https://www.reddit.com/r/django/comments/1hup0if/using_djando_in_a_fullstack_application_i_want](https://www.reddit.com/r/django/comments/1hup0if/using_djando_in_a_fullstack_application_i_want)
 - RSS feed: $source
 - date published: 2025-01-06T02:55:24+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, how are you? </p> <p>I&#39;m using Django to build a Full-Stack, Frontend and Backend application, using Bootstrap. </p> <p>The application itself will be two, </p> <p>1 - School Management System, where there will be everything a management system has. 2 - System for students to see posted classes </p> <p>Basically, the two complement each other.</p> <p>In a world where everything is Rest API and Frontend (Vue, React or Angular), building everything Full-Stack has become rarer, at least in my opinion. </p> <p>Tell me, what are the pros and cons of this? Mainly I would like to hear from those who deal with applications like this on a daily basis and who tend to grow, any tips? </p> <p>Thanks everyone!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nemseisei"> /u/nemseisei </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1hup0if/using_djando_in_a_fullstack_application_i_want/">[

## django storages Dropbox error: 'C:/static'
 - [https://www.reddit.com/r/django/comments/1humn1j/django_storages_dropbox_error_cstatic](https://www.reddit.com/r/django/comments/1humn1j/django_storages_dropbox_error_cstatic)
 - RSS feed: $source
 - date published: 2025-01-06T00:59:19+00:00

<!-- SC_OFF --><div class="md"><p>i have the problem when i do &quot;python manage.py collectstatic&quot; and i get this error[File &quot;C:\proyect_name\venv\Lib\site-packages\stone\backends\python_rsrc\stone_validators.py&quot;, line 345, in validate</p> <p>raise ValidationError(&quot;&#39;%s&#39; did not match pattern &#39;%s&#39;&quot;</p> <p>stone.backends.python_rsrc.stone_validators.ValidationError: &#39;C:/static&#39; did not match pattern &#39;(/(.|[\r\n])*|id:.*)|(rev:[0-9a-f]{9,})|(ns:[0-9]+(/.*)?)&#39;] y este es mi settings.py []</p> <pre><code>STATIC_URL = &#39;static/&#39; STATICFILES_DIRS = [ os.path.join(BASE_DIR, &quot;static&quot;), ] STATIC_ROOT = os.path.join(BASE_DIR, &#39;staticfiles&#39;) MEDIA_URL = &#39;/media/&#39; STORAGES = { &quot;default&quot;: { &quot;BACKEND&quot;: &quot;storages.backends.dropbox.DropboxStorage&quot;, &quot;OPTIONS&quot;: { &quot;oauth2_refresh_token&quot;: env(&#39;DROPBOX_OAUTH2_TOKEN&#39;), &quot;app_key&quot;: env(&#39;DROPBOX_APP

## N+1 in DRF Nested Serializer.
 - [https://www.reddit.com/r/django/comments/1hulm9w/n1_in_drf_nested_serializer](https://www.reddit.com/r/django/comments/1hulm9w/n1_in_drf_nested_serializer)
 - RSS feed: $source
 - date published: 2025-01-06T00:11:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Hoping someone will be able to help me with this!</p> <p>I have 3 models, for ease of understanding, we&#39;ll call them Publisher, Book, and Page. For now assume a Publisher can only have 1 book, which is a foreignkey field</p> <p>My book serializer looks like this</p> <pre><code>class BookSerializer(serializers.ModelSerializer): number_of_pages = serializers.SerializerMethodField() @staticmethod def get_number_of_pages(book): if hasattr(book, &quot;number_of_pages&quot;): return book.number_of_pages return book.pages_set.count() </code></pre> <p>This works fine with my ModelViewSet, as I annotate that the number_of_pages field, and there is no n+1 query issue.</p> <p>However, in my PublisherSerializer, we have:</p> <pre><code>class PublisherSerializer(serializers.ModelSerializer): book = BookSerializer(read_only=True) </code></pre> <p>I can&#39;t find a way of using Publisher.objects.select_related(&#39;book&#39;) and also annotating
