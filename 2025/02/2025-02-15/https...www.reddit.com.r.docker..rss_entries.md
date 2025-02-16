# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Everyday Project Isolation for Developers
 - [https://www.reddit.com/r/docker/comments/1iqdlh7/everyday_project_isolation_for_developers](https://www.reddit.com/r/docker/comments/1iqdlh7/everyday_project_isolation_for_developers)
 - RSS feed: $source
 - date published: 2025-02-15T22:43:46+00:00

<!-- SC_OFF --><div class="md"><p>I wanted to isolate different development projects from eachother and from my system, and came up with a convenient system using containers. Maybe someone else can use it too!</p> <p>→ <a href="https://evertheylen.eu/p/probox-intro/">https://evertheylen.eu/p/probox-intro/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/evert_heylen"> /u/evert_heylen </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iqdlh7/everyday_project_isolation_for_developers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iqdlh7/everyday_project_isolation_for_developers/">[comments]</a></span>

## What is the point of docker (and container system in general)
 - [https://www.reddit.com/r/docker/comments/1iqchnx/what_is_the_point_of_docker_and_container_system](https://www.reddit.com/r/docker/comments/1iqchnx/what_is_the_point_of_docker_and_container_system)
 - RSS feed: $source
 - date published: 2025-02-15T21:54:01+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I would like to know, in practical field and example, what&#39;s the point of using container system as docker in dev environment. It looks like it has some usage for remote environment (such as production or thing) but I don&#39;t understand in local development for example.</p> <p>I&#39;m all hear</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fair_Distribution275"> /u/Fair_Distribution275 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iqchnx/what_is_the_point_of_docker_and_container_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iqchnx/what_is_the_point_of_docker_and_container_system/">[comments]</a></span>

## Docker Desktop - Can't get bind mount to work
 - [https://www.reddit.com/r/docker/comments/1iqaxho/docker_desktop_cant_get_bind_mount_to_work](https://www.reddit.com/r/docker/comments/1iqaxho/docker_desktop_cant_get_bind_mount_to_work)
 - RSS feed: $source
 - date published: 2025-02-15T20:46:06+00:00

<!-- SC_OFF --><div class="md"><p>Using Docker Desktop on Debian. I do not have the native docker engine installed on the laptop I&#39;ve been working on.</p> <p>I&#39;m new to docker and as a learning project, have been trying to build an image/container to run steamcmd.</p> <p>I&#39;ve been trying to setup a bind mount, which I can use as an install target for downloaded game servers.</p> <p>I can&#39;t seem to get the bind mount to take. My first guess is that it revolves around the fact that I&#39;m using Docker Desktop and the fact that it sounds like it runs in a VM on the host. Under the Resource settings -&gt; Virtual File Shares, I have &quot;/home&quot; and &quot;/tmp/steam&quot;. I had been trying to use a subfolder in my home directory to bind to, but all of the files seem to just end up in the container and not in the actual file system. Tried creating and adding the &quot;/tmp/stream&quot; folder as well, but haven&#39;t seen any change.</p> <p>Just looking for any insi

## docker issue - blew up volume and container
 - [https://www.reddit.com/r/docker/comments/1iqarb9/docker_issue_blew_up_volume_and_container](https://www.reddit.com/r/docker/comments/1iqarb9/docker_issue_blew_up_volume_and_container)
 - RSS feed: $source
 - date published: 2025-02-15T20:38:38+00:00

<!-- SC_OFF --><div class="md"><p>I accidentally messed up my volume for influxdb and all my data collection. I cannot get the container to boot up and I like a moron modified the a yml file and added ulimit in it. </p> <p>root@a5fbc7915511:/etc/defaults/influxdb2# cat config.yml</p> <ul> <li>ulimit -n 4095 &lt;&lt;&lt;</li> <li>bolt-path: /var/lib/influxdb2/influxd.bolt</li> <li>engine-path: /var/lib/influxdb2/engine</li> <li>nats-port: 4222</li> </ul> <p>I get stuck in a loop with this; </p> <p>{&quot;log&quot;:&quot;failed to load config file: While parsing config: yaml: line 2: mapping values are not allowed in this context\n&quot;,&quot;stream&quot;:&quot;stderr&quot;,&quot;time&quot;:&quot;2025-02-15T20:00:44.040044598Z&quot;}</p> <p>{&quot;log&quot;:&quot;failed to load config file: While parsing config: yaml: line 2: mapping values are not allowed in this context\n&quot;,&quot;stream&quot;:&quot;stderr&quot;,&quot;time&quot;:&quot;2025-02-15T20:01:45.575208974Z&quot;}</p> <p>

## Trouble Connecting Docker Swarm Service to External MongoDB Atlas – Overlay Network NAT Issue?
 - [https://www.reddit.com/r/docker/comments/1iq2lrl/trouble_connecting_docker_swarm_service_to](https://www.reddit.com/r/docker/comments/1iq2lrl/trouble_connecting_docker_swarm_service_to)
 - RSS feed: $source
 - date published: 2025-02-15T14:34:35+00:00

<!-- SC_OFF --><div class="md"><h1>The Issue</h1> <ul> <li><strong>NOTE:</strong> I&#39;ve an internal mongo service running, but I&#39;m talking about Mongo Atlas (External in this thread)</li> <li><strong>Environment:</strong> I’m running a backend service in Docker Swarm with an external overlay network (<code>mongo_net</code>) defined in my <code>docker-compose.yml</code>. The service’s MongoDB connection string points to MongoDB Atlas (using TLS) and looks something like:rubyCopymongodb+srv://&lt;user&gt;:&lt;pass&gt;@cluster0.3xyfw.mongodb.net/?retryWrites=true&amp;w=majority&amp;tls=true</li> <li><strong>Symptoms:</strong> Inside the container: Outside the container (on the host), everything works as expected. But inside the container: <ul> <li><code>nslookup</code> for the Atlas hostname works fine.</li> <li><code>ping</code> works.</li> <li>However, <code>nc -vz</code> <a href="http://ac-sqy9upr-shard-00-02.3xyzqow.mongodb.net"><code>ac-sqy9upr-shard-00-02.3xyzqow.mongodb.ne

## [Help] Issues Running Python Project with Docker – Relative Import Errors & Package Recognition
 - [https://www.reddit.com/r/docker/comments/1iq2hvx/help_issues_running_python_project_with_docker](https://www.reddit.com/r/docker/comments/1iq2hvx/help_issues_running_python_project_with_docker)
 - RSS feed: $source
 - date published: 2025-02-15T14:29:11+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Coach_3249"> /u/No_Coach_3249 </a> <br/> <span><a href="/r/learnpython/comments/1iq2dx3/help_issues_running_python_project_with_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iq2hvx/help_issues_running_python_project_with_docker/">[comments]</a></span>

## Help with Docker
 - [https://www.reddit.com/r/docker/comments/1ipz76d/help_with_docker](https://www.reddit.com/r/docker/comments/1ipz76d/help_with_docker)
 - RSS feed: $source
 - date published: 2025-02-15T11:10:18+00:00

<!-- SC_OFF --><div class="md"><p>I work in windows machine and I have created a small project in go and I have created docker file for it. The build was successful, image was created but on running the image the created container stopped and showed no file or directory. Help will be highly appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Express_Sky2557"> /u/Express_Sky2557 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ipz76d/help_with_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ipz76d/help_with_docker/">[comments]</a></span>

## How Learning Cloud & DevOps Jargons/Concepts through Analogies is transforming my Learning Journey (I'm a Non IT Beginner)
 - [https://www.reddit.com/r/docker/comments/1ipxoiv/how_learning_cloud_devops_jargonsconcepts_through](https://www.reddit.com/r/docker/comments/1ipxoiv/how_learning_cloud_devops_jargonsconcepts_through)
 - RSS feed: $source
 - date published: 2025-02-15T09:15:19+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I wanted to share an experience that’s helping me learn and understand better. Coming from a non IT background, I always found Cloud and DevOps jargons/Concepts—think Containerization, Docker, Iac, and CI/CD—to be completely overwhelming. Traditional explanations felt too abstract, and I struggled to connect the dots.</p> <p>During my learning journey I discovered the power of understanding complex concepts through analogies (thanks in large part to tools like ChatGPT). Instead of getting bogged down by complex technical definitions, I started learning these concepts through everyday comparisons. For instance, Docker was explained as being like a standardized shipping container—everything you need to run your application is neatly packed inside, no matter where it goes. Similarly, Kubernetes was likened to an air traffic controller, managing the &quot;takeoffs&quot; and &quot;landings&quot; of containerized apps. These analogies 

## Subscription cancelled?
 - [https://www.reddit.com/r/docker/comments/1ipoxoh/subscription_cancelled](https://www.reddit.com/r/docker/comments/1ipoxoh/subscription_cancelled)
 - RSS feed: $source
 - date published: 2025-02-15T00:08:58+00:00

<!-- SC_OFF --><div class="md"><p>Got a couple of emails all at once today saying my OSS project’s subscription to docker was being cancelled. </p> <p>—-8&lt;[snip]—- Hello comixed!</p> <p>We&#39;re sad to see you go. This email confirms that your Docker-Sponsored Open Source subscription for your account has been canceled.</p> <p>—-8&lt;[snip]—-</p> <p>But I didn’t cancel it. Is there some error at docker, or are they canceling OSS free subscriptions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mcpierceaim"> /u/mcpierceaim </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ipoxoh/subscription_cancelled/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ipoxoh/subscription_cancelled/">[comments]</a></span>

