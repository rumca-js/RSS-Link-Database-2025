# Source:Django, URL:https://www.reddit.com/r/django/.rss, language:

## Why can't I access "Meta" inner class of model?
 - [https://www.reddit.com/r/django/comments/1j3mxoz/why_cant_i_access_meta_inner_class_of_model](https://www.reddit.com/r/django/comments/1j3mxoz/why_cant_i_access_meta_inner_class_of_model)
 - RSS feed: $source
 - date published: 2025-03-04T22:03:06+00:00

<!-- SC_OFF --><div class="md"><pre><code>class MyObjects(models.Model): field1 = models.CharField(max_length=20) class Meta: verbose_name_plural = &quot;MyObjects&quot; </code></pre> <p>With a model like the one above, why is it then impossible for me to do something like this in a view let&#39;s say:</p> <pre><code>from app.models import MyObjects print(MyObjects.Meta.verbose_name_plural) </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Ad-7865"> /u/Affectionate-Ad-7865 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j3mxoz/why_cant_i_access_meta_inner_class_of_model/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j3mxoz/why_cant_i_access_meta_inner_class_of_model/">[comments]</a></span>

## Changing Model of CreateView and form
 - [https://www.reddit.com/r/django/comments/1j3hnxi/changing_model_of_createview_and_form](https://www.reddit.com/r/django/comments/1j3hnxi/changing_model_of_createview_and_form)
 - RSS feed: $source
 - date published: 2025-03-04T18:26:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I&#39;d like to be able to have one CreateView that can work for a handful of models I have. Based on this portion of the documentation:</p> <p>&quot;These generic views will automatically create a <a href="https://docs.djangoproject.com/en/5.1/topics/forms/modelforms/#django.forms.ModelForm"><code>ModelForm</code></a>, so long as they can work out which model class to use&quot;</p> <p>I believe if I pass the right model to a class inheriting CreateView, I&#39;ll get a form to use for that model. With this in mind, is it possible to change the model a view references when requested? According to the documentation, I should be able to use get_object() or get the queryset, but both of those take me to SingleObjectMixin, which I don&#39;t think is used in CreateView. Am I attempting something impossible, or am I missing a key detail? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Megmachunian"> /u/Megmach

## Shadcn components for django templates, using django-cotton, alpine and tailwind
 - [https://www.reddit.com/r/django/comments/1j3f6t2/shadcn_components_for_django_templates_using](https://www.reddit.com/r/django/comments/1j3f6t2/shadcn_components_for_django_templates_using)
 - RSS feed: $source
 - date published: 2025-03-04T16:47:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gbeier"> /u/gbeier </a> <br/> <span><a href="https://github.com/SarthakJariwala/shadcn-django">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j3f6t2/shadcn_components_for_django_templates_using/">[comments]</a></span>

## Hot to have pretty frontend w/o Vue/react separate frontend. Just using Django itself.
 - [https://www.reddit.com/r/django/comments/1j3bvda/hot_to_have_pretty_frontend_wo_vuereact_separate](https://www.reddit.com/r/django/comments/1j3bvda/hot_to_have_pretty_frontend_wo_vuereact_separate)
 - RSS feed: $source
 - date published: 2025-03-04T14:22:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi, pretty much everything in title. I wonder if it&#39;s possible to have modern and good looking frontend with just Django. Using htmx? I don&#39;t want to add another level of complication to my work but all my Django systems (I&#39;ve developed few of them) look ugly like a old woman without teeth. It works but look like yahoo from 90&#39;. I use crispy form, bootstrap and some custom .js but maybe someone could give a hint to a single hobby developer. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Familyinalicante"> /u/Familyinalicante </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j3bvda/hot_to_have_pretty_frontend_wo_vuereact_separate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j3bvda/hot_to_have_pretty_frontend_wo_vuereact_separate/">[comments]</a></span>

## The first thing I wish someone told me before building a Django product.
 - [https://www.reddit.com/r/django/comments/1j34pis/the_first_thing_i_wish_someone_told_me_before](https://www.reddit.com/r/django/comments/1j34pis/the_first_thing_i_wish_someone_told_me_before)
 - RSS feed: $source
 - date published: 2025-03-04T06:34:51+00:00

<!-- SC_OFF --><div class="md"><p>Since I started with a lot of docs, blogs and tutorials to learn Django, I was never able to prioritize this.</p> <p>But please put more focus on the authentication and permissions part, especially JWT if you are using a separate front-end. Else you will have to do a major restructure. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sirtaskmaster"> /u/sirtaskmaster </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j34pis/the_first_thing_i_wish_someone_told_me_before/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j34pis/the_first_thing_i_wish_someone_told_me_before/">[comments]</a></span>

## Where to put custom form attributes that are not fields?
 - [https://www.reddit.com/r/django/comments/1j34pfq/where_to_put_custom_form_attributes_that_are_not](https://www.reddit.com/r/django/comments/1j34pfq/where_to_put_custom_form_attributes_that_are_not)
 - RSS feed: $source
 - date published: 2025-03-04T06:34:42+00:00

<!-- SC_OFF --><div class="md"><p>If I have a ModelForm with some fields and want to add an attribute to it that&#39;s not a field, should I put it in the &quot;Meta&quot; inner-class or should I put it directly inside the ModelForm class itself, so right beside the other fields?</p> <p>In the same way, is an ok thing to do to add an inner Meta class to forms that are not ModelForms when I want to add attributes to them that are not fields?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Ad-7865"> /u/Affectionate-Ad-7865 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j34pfq/where_to_put_custom_form_attributes_that_are_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j34pfq/where_to_put_custom_form_attributes_that_are_not/">[comments]</a></span>

## I use railway it's response time little slow.(over 1second)
 - [https://www.reddit.com/r/django/comments/1j32mk5/i_use_railway_its_response_time_little_slowover](https://www.reddit.com/r/django/comments/1j32mk5/i_use_railway_its_response_time_little_slowover)
 - RSS feed: $source
 - date published: 2025-03-04T04:25:26+00:00

<!-- SC_OFF --><div class="md"><p>First time, I thought it is related to plan.</p> <p>So I upgrade free tier to hobby plan.</p> <p>But the response time is same as before.</p> <p>So I am considering to change the hosting server.</p> <p>Could you guys recommend to me to deploy django app easily for MVP Testing?</p> <p>I usually used aws, but Deployment process was not really good to me.</p> <p>Railway made me feel deployment more easy.</p> <p>Is there any service give me better performance than railway?</p> <p>Specially, most of users will be located in south korea(East Asia)</p> <p>PS. I already test setting location asis in railway, But the problem was same.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tichangel"> /u/tichangel </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j32mk5/i_use_railway_its_response_time_little_slowover/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j32mk5/i_use

## Search for a front-end developer join to hackathon
 - [https://www.reddit.com/r/django/comments/1j2xyu8/search_for_a_frontend_developer_join_to_hackathon](https://www.reddit.com/r/django/comments/1j2xyu8/search_for_a_frontend_developer_join_to_hackathon)
 - RSS feed: $source
 - date published: 2025-03-04T00:26:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I search I front-end developer (is good if he have a django knowledgebc we work it with it in backend) of join a hackathon by FIC, and it&#39;s like we build a entrepreneurship project, and it&#39;s be presented on a software&#39;s engineering and by entrepreneurs in silicon Valley , if you interest and have under 19 years old send me a message private.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BusFun2932"> /u/BusFun2932 </a> <br/> <span><a href="https://www.reddit.com/r/django/comments/1j2xyu8/search_for_a_frontend_developer_join_to_hackathon/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/django/comments/1j2xyu8/search_for_a_frontend_developer_join_to_hackathon/">[comments]</a></span>

