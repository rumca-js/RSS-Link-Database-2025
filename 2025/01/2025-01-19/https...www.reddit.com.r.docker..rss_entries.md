# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## GLIBC >=2.39 python container?
 - [https://www.reddit.com/r/docker/comments/1i58q0f/glibc_239_python_container](https://www.reddit.com/r/docker/comments/1i58q0f/glibc_239_python_container)
 - RSS feed: $source
 - date published: 2025-01-19T20:52:33+00:00

<!-- SC_OFF --><div class="md"><p>In short, a django backend needs to run an arm64 binary file, interaction works on host with no problems. </p> <p>Right now I&#39;m building the django container from python:latest, which has glibc 2.36, but the binary has 2.39 dependencies.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kelemangiar0"> /u/kelemangiar0 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i58q0f/glibc_239_python_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i58q0f/glibc_239_python_container/">[comments]</a></span>

## Gdlib >=2.39 python containers?
 - [https://www.reddit.com/r/docker/comments/1i58esu/gdlib_239_python_containers](https://www.reddit.com/r/docker/comments/1i58esu/gdlib_239_python_containers)
 - RSS feed: $source
 - date published: 2025-01-19T20:39:59+00:00

<!-- SC_OFF --><div class="md"><p>In short, a django backend needs to run an arm64 binary file, interaction works on host with no problems. </p> <p>Right now I&#39;m building the django container from python:latest, which has gdlib 2.36, but the binary has 2.39 dependencies.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kelemangiar0"> /u/kelemangiar0 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i58esu/gdlib_239_python_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i58esu/gdlib_239_python_containers/">[comments]</a></span>

## H.pylori help and advice
 - [https://www.reddit.com/r/docker/comments/1i57yqc/hpylori_help_and_advice](https://www.reddit.com/r/docker/comments/1i57yqc/hpylori_help_and_advice)
 - RSS feed: $source
 - date published: 2025-01-19T20:21:02+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Chair-5014"> /u/Ok-Chair-5014 </a> <br/> <span><a href="/r/AskDocs/comments/1i57jh2/hpylori_help_and_advice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i57yqc/hpylori_help_and_advice/">[comments]</a></span>

## Replace macvlan network - best practice
 - [https://www.reddit.com/r/docker/comments/1i57snv/replace_macvlan_network_best_practice](https://www.reddit.com/r/docker/comments/1i57snv/replace_macvlan_network_best_practice)
 - RSS feed: $source
 - date published: 2025-01-19T20:14:11+00:00

<!-- SC_OFF --><div class="md"><p>I need to adjust my current macvlan network. Would the process be as easy as docker rm and docker create with the new settings? I understand I&#39;ll have to modify each container with the new network name, so this questions is about the backend only.</p> <p>Thank you for any advice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ryland0"> /u/Ryland0 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i57snv/replace_macvlan_network_best_practice/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i57snv/replace_macvlan_network_best_practice/">[comments]</a></span>

## Hosting wordpress but the data is lost when I re-create
 - [https://www.reddit.com/r/docker/comments/1i57k3l/hosting_wordpress_but_the_data_is_lost_when_i](https://www.reddit.com/r/docker/comments/1i57k3l/hosting_wordpress_but_the_data_is_lost_when_i)
 - RSS feed: $source
 - date published: 2025-01-19T20:04:20+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Sorry a little new to this but I&#39;m hoping to create a wordpress instance using docker. I can create fine but if I delete and re-create it goes back to the initial setup. I&#39;m guessing I need to add the DB to have access to the host in the YML but I&#39;m not 100% sure. Could someone please confirm and pop me an example?</p> <p><code>version: &quot;3&quot;</code> </p> <p><code>services:</code></p> <p><code>db:</code></p> <p><code>image: mysql:latest</code></p> <p><code>restart: always</code></p> <p><code>environment:</code></p> <p><code>MYSQL_ROOT_PASSWORD: MySQLRootPassword</code></p> <p><code>MYSQL_DATABASE: MySQLDatabaseName</code></p> <p><code>MYSQL_USER: MySQLUsername</code></p> <p><code>MYSQL_PASSWORD: MySQLUserPassword</code></p> <p><code>wordpress:</code></p> <p><code>depends_on:</code></p> <p><code>- db</code></p> <p><code>image: wordpress:latest</code></p> <p><code>restart: always</code></p> <p><code>ports:</code></p> <

## Finding it hard to create two .conf files when I run docker-compose.
 - [https://www.reddit.com/r/docker/comments/1i55v0u/finding_it_hard_to_create_two_conf_files_when_i](https://www.reddit.com/r/docker/comments/1i55v0u/finding_it_hard_to_create_two_conf_files_when_i)
 - RSS feed: $source
 - date published: 2025-01-19T18:55:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>Attached is my docker collection: <a href="mailto:git@github.com">git@github.com</a>:EVO-9/zzzz.git</p> <p>I have a single container for mysql, a single container for nginx and each website will have its own container. They all connect using the network: app-network.</p> <p>When pushing this to the remote server, I need a couple of .conf files, one for my domain and one for my sub-domain. Frontend should use my domain and Backend should post to the sub-domain.</p> <p>I created a file in scripts/replace_and_copy_nginx.sh to create the two .conf files and add them to nginx/conf.d.</p> <p>My issue is, I don&#39;t want to keep running scripts manually every time I want to do something and I thought this is what Docker is for.</p> <p>How can I run this script either using the <a href="http://docker-compose.prod">docker-compose.prod</a> file located in domain1/ or in Dockerfile located in domain1/frontend.</p> <p>or is there a better option?<

## Slow SQL Import When Dockerising WordPress with WSL2 on Windows 10
 - [https://www.reddit.com/r/docker/comments/1i54n3u/slow_sql_import_when_dockerising_wordpress_with](https://www.reddit.com/r/docker/comments/1i54n3u/slow_sql_import_when_dockerising_wordpress_with)
 - RSS feed: $source
 - date published: 2025-01-19T18:04:58+00:00

<!-- SC_OFF --><div class="md"><p>Very new to Docker here. I’ve been experimenting with it for the past few days using WSL2 on a Windows 10 machine. My goal is to copy my live Wordpress site to my local machine, dockerise it, and use it for developing plugins and themes.</p> <p>So far:</p> <ol> <li>I’ve extracted the filesystem backup of my Wordpress site into a project folder.</li> <li>I’m trying to import the SQL backup (364 MB) into a MySQL container in Docker.</li> </ol> <p>Here’s my <code>docker-compose.yml</code> setup:</p> <pre><code>services: wordpress: image: wordpress:latest ports: - &quot;8000:80&quot; volumes: - ./wordpress:/var/www/html environment: WORDPRESS_DB_HOST: db:3306 WORDPRESS_DB_USER: root WORDPRESS_DB_PASSWORD: example WORDPRESS_DB_NAME: wordpress db: image: mysql:5.7 ports: - &quot;3306:3306&quot; volumes: - db_data:/var/lib/mysql - ./db-backups/pressable-backup-foobar-2025-01-18-16-00.sql:/docker-entrypoint-initdb.d/backup.sql environment: MYSQL_ROOT_PASSWOR

## chown operation not permitted?
 - [https://www.reddit.com/r/docker/comments/1i4xw8y/chown_operation_not_permitted](https://www.reddit.com/r/docker/comments/1i4xw8y/chown_operation_not_permitted)
 - RSS feed: $source
 - date published: 2025-01-19T12:59:40+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to add a Piwigo instance to my Ubuntu docker host. It has a mount mapped to a drive on a NAS and I can browse the NAS folders from the Ubuntu box. I have other containers happily accessing other NFS shares.</p> <p>When starting the Piwigo container throws this error:</p> <p>&quot;Error response from daemon: error while creating mount source path &#39;/mnt/photos/gallery&#39;: chown /mnt/photos/gallery: operation not permitted &quot;</p> <p>Here is my compose file:</p> <pre><code>services: mariadb: image: lscr.io/linuxserver/mariadb:latest container_name: mariadb environment: - MYSQL_ROOT_PASSWORD=secretpassword - TZ=Europe/London #change timezone if needed - MYSQL_DATABASE=piwigo #optional - MYSQL_USER=piwigo_user #optional - MYSQL_PASSWORD=secretpassword #optional volumes: - /mnt/photos/piwigodb/db:/config ports: - 3306:3306 #change port if needed restart: unless-stopped networks: macvlan_151: piwigo: image: lscr.io/linuxserver/piwigo

## New to self hosting and docker, could use some advice
 - [https://www.reddit.com/r/docker/comments/1i4v22d/new_to_self_hosting_and_docker_could_use_some](https://www.reddit.com/r/docker/comments/1i4v22d/new_to_self_hosting_and_docker_could_use_some)
 - RSS feed: $source
 - date published: 2025-01-19T09:46:19+00:00

<!-- SC_OFF --><div class="md"><p><strong>Preface:</strong> I’m completely new to self-hosting, but I’m working on a small personal project that requires running a service 24/7. This service needs to expose its APIs to be accessible by a mobile app outside the local network.</p> <p>So far, the best solution I’ve come across is to rent a VM from Hetzner, purchase a random domain from any provider, and map the domain to the VM’s IP address. This setup would cost around €6/month, which feels a bit excessive given how lightweight this project is.</p> <p>Considering the small scale and low resource demands of the project, I’ve been thinking about using a container-based approach with Docker and leveraging a Docker hosting service. However, I’m entirely new to Docker and its ecosystem.</p> <p>Here are my main questions:</p> <ol> <li>Do you have recommendations for providers that could host a Docker container?</li> <li>Would this approach likely save me money, or am I unnecessarily complica

## How can I set up a development environment inside multiple Docker containers with my GitHub repo?
 - [https://www.reddit.com/r/docker/comments/1i4rbyt/how_can_i_set_up_a_development_environment_inside](https://www.reddit.com/r/docker/comments/1i4rbyt/how_can_i_set_up_a_development_environment_inside)
 - RSS feed: $source
 - date published: 2025-01-19T05:26:43+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, im a relatively new user to Ubuntu and Docker so apologies if this is a stupid question! I’m working on a GitHub repo running inside a Docker container. I’d like to develop directly inside the container while using Vim(or something else) on my local machine to edit the code. The issue is I’ll be working in multiple different containers so I currently keep installing vim to each of those. Not sure if there’s a better way to do this? Thank you 🙏 </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jigs01"> /u/Jigs01 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i4rbyt/how_can_i_set_up_a_development_environment_inside/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i4rbyt/how_can_i_set_up_a_development_environment_inside/">[comments]</a></span>

## OpenCTI and Portainer deployment
 - [https://www.reddit.com/r/docker/comments/1i4ov7k/opencti_and_portainer_deployment](https://www.reddit.com/r/docker/comments/1i4ov7k/opencti_and_portainer_deployment)
 - RSS feed: $source
 - date published: 2025-01-19T03:16:28+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to deploy opencti through docker and not having any luck doing so over a docker swarm. If I deploy the images without swarm, i am able to get the images up and running without any issues.</p> <p>The issue is with the opencti_elasticsearch, which is not starting when I try to spin it up through docker smarm either with or without portainer. </p> <p>Not sure what the issue is.</p> <p>I am quite new to docker and not sure how i should troubleshoot to find the issue.</p> <p>Any leads to identify and resolve the problem appreciated.</p> <p>I am using</p> <p>Docker 27.5.0</p> <p>OpenCTI - 6.4.8</p> <p>Portainer: 2.21.5</p> <p>Commands issued:</p> <p>docker stack deploy -c portainer-agent-stack.yml portainer</p> <p>However, when I issue the following command, it works without any problem.</p> <p>docker compose up -d</p> <p>compose file as follows.</p> <p>services:</p> <p>redis:</p> <p>image: redis:7.4.1</p> <p>restart: always</p> <p>volumes:</p>

