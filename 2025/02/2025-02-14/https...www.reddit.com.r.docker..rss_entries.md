# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Happy Valentine’s
 - [https://www.reddit.com/r/docker/comments/1ipnj0o/happy_valentines](https://www.reddit.com/r/docker/comments/1ipnj0o/happy_valentines)
 - RSS feed: $source
 - date published: 2025-02-14T23:00:12+00:00

<!-- SC_OFF --><div class="md"><p>Did anyone else see the docker valentines message ? I spun up some charming and romantic containers today </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zesty-Close-Mud"> /u/Zesty-Close-Mud </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ipnj0o/happy_valentines/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ipnj0o/happy_valentines/">[comments]</a></span>

## Reduce Image Size
 - [https://www.reddit.com/r/docker/comments/1ipmavx/reduce_image_size](https://www.reddit.com/r/docker/comments/1ipmavx/reduce_image_size)
 - RSS feed: $source
 - date published: 2025-02-14T22:04:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m pretty new to building docker images, and I am trying to build an image that I can get a custom python package installed correctly to use for my research. This dockerfile works, but the image size is ~750MB, which seems pretty excessive for an image whose only purpose is to be able to run some code with that custom package.</p> <p>I imagine the size is due to including a whole debian OS, but I&#39;m not sure how else to make sure the Cmake and fortran compilers are installed and working. Would love any help, thanks!</p> <p>Edit: I forgot to mention that I tried to make it work with multi-stage builds, but since the python package is wrapping up some fortran code when it runs, I kept getting errors about .so.# packages not being installed or being of the wrong version. So, I stuck with just using the original build stage</p> <pre><code>FROM debian:bookworm-slim # Get the necessary build packages and compilers RUN apt-get update &amp;&amp;\ DEB

## WordPress, Docker, and an AI Agent walks into a bar...
 - [https://www.reddit.com/r/docker/comments/1iplltt/wordpress_docker_and_an_ai_agent_walks_into_a_bar](https://www.reddit.com/r/docker/comments/1iplltt/wordpress_docker_and_an_ai_agent_walks_into_a_bar)
 - RSS feed: $source
 - date published: 2025-02-14T21:33:18+00:00

<!-- SC_OFF --><div class="md"><p>How in the heck do i get them to work? </p> <p>I&#39;m coming from buy a VPS like DO or racknerd, setup an environment and build a single or multisite WordPress on it.</p> <p>Now I&#39;d like to graduate to setting up a VPS, add Docker and then place WordPress in it</p> <p>Then add an AI Agent that allows me seo, and newsfeed and newswire the site to communicate with other sites or from our main feed... </p> <p>Newbie and speculative conversation so please no attacking. trying to see can they be merged. thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/7thWardMadeMe"> /u/7thWardMadeMe </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iplltt/wordpress_docker_and_an_ai_agent_walks_into_a_bar/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iplltt/wordpress_docker_and_an_ai_agent_walks_into_a_bar/">[comments]</a></span>

## New to Podman (desktop), need advice
 - [https://www.reddit.com/r/docker/comments/1ipkex8/new_to_podman_desktop_need_advice](https://www.reddit.com/r/docker/comments/1ipkex8/new_to_podman_desktop_need_advice)
 - RSS feed: $source
 - date published: 2025-02-14T20:40:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am trying to used podman desktop to start my journey with podman.</p> <p>Don&#39;t hesitate to correct me if I am saying nonsense</p> <p>Here is my interrogation,<br/> I have the GUI postman desktop for postman CLI.</p> <p>The install has been done but can I still use command line to interact with podman instead of podman desktop ? If yes, how ?</p> <p>For exemple, I would like to create a volume podman. I can create it with podman desktop it&#39;s all good.<br/> And I would like to create another volume using command line of the podman CLI but I don&#39;t see a way nor a terminal to use for the commands. Even tough, some tips on the GUI suggest me some command lines :<br/> (Sorry cannot give image, since this subbreddit deactivated it, but I found this exemple on google image to illustrate <a href="https://www.google.com/search?client=firefox-b-d&amp;sca_esv=b69f56e22fa3a2ef&amp;sxsrf=AHTn8zpNK1etOxRLsK6JOW86KzrrY1a1vQ:173956548679

## How to Reduce Docker Image Size for Cloud Run?
 - [https://www.reddit.com/r/docker/comments/1ipi0tm/how_to_reduce_docker_image_size_for_cloud_run](https://www.reddit.com/r/docker/comments/1ipi0tm/how_to_reduce_docker_image_size_for_cloud_run)
 - RSS feed: $source
 - date published: 2025-02-14T18:58:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to Docker and trying to optimize my image size, but I keep hitting the maximum size limit on Cloud Run. Here&#39;s my current Dockerfile:</p> <pre><code>FROM node:23-alpine as build WORKDIR /app COPY package.json ./ COPY yarn.lock ./ RUN yarn install --frozen-lockfile COPY . . EXPOSE 3000 CMD [&quot;yarn&quot;, &quot;start&quot;] </code></pre> <p>I&#39;ve tried looking up solutions, but nothing seems to work. Any tips on reducing the image size effectively? Would appreciate any advice! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SatisfactionExact136"> /u/SatisfactionExact136 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ipi0tm/how_to_reduce_docker_image_size_for_cloud_run/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ipi0tm/how_to_reduce_docker_image_size_for_cloud_run/">[comments]</a></span>

## docker asp net core migrations issue
 - [https://www.reddit.com/r/docker/comments/1ipg8d9/docker_asp_net_core_migrations_issue](https://www.reddit.com/r/docker/comments/1ipg8d9/docker_asp_net_core_migrations_issue)
 - RSS feed: $source
 - date published: 2025-02-14T17:43:14+00:00

<!-- SC_OFF --><div class="md"><p>I have the following code:</p> <pre><code> public void Initialize() { this.data.Database.Migrate(); foreach (var initialDataProvider in this.initialDataProviders) { if (this.DataSetIsEmpty(initialDataProvider.EntityType)) { var data = initialDataProvider.GetData(); foreach (var entity in data) { this.data.Add(entity); } } } this.data.SaveChanges(); } </code></pre> <p>and my docker-compose.yml and dockerfile looks like:</p> <p>the docker-compose.yml:</p> <pre><code>services: sqlserver: image: mcr.microsoft.com/mssql/server:2022-latest container_name: sqlserver restart: always environment: SA_PASSWORD: &quot;YourStrong!Passw0rd&quot; ACCEPT_EULA: &quot;Y&quot; ports: - &quot;1433:1433&quot; networks: - backend volumes: - sql_data:/var/opt/mssql app: build: context: . dockerfile: server/WodItEasy.Startup/Dockerfile container_name: server depends_on: - sqlserver ports: - &quot;8080:8080&quot; environment: - ConnectionStrings__DefaultConnection=Server=sql

## Help with Dockerizing a CLI Music Player (Python-VLC Audio Output Issue)
 - [https://www.reddit.com/r/docker/comments/1ipcc6s/help_with_dockerizing_a_cli_music_player](https://www.reddit.com/r/docker/comments/1ipcc6s/help_with_dockerizing_a_cli_music_player)
 - RSS feed: $source
 - date published: 2025-02-14T14:54:53+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to Dockerize my CLI-based music player, <strong>Ethos</strong>, which relies on <code>python-vlc</code> for audio playback. The problem is that <code>python-vlc</code> requires VLC to be installed on the host machine, and when I run the container, the UI loads fine, but the audio fails with an infinite loop of errors related to ALSA and PulseAudio.</p> <h1>My Dockerfile:</h1> <pre><code>DockerfileCopyEditFROM python:3.11-slim RUN apt-get update &amp;&amp; apt-get install -y \ vlc \ &amp;&amp; rm -rf /var/lib/apt/lists/* WORKDIR /app COPY requirements.txt . RUN pip install --no-cache-dir -r requirements.txt COPY . . ENV LD_LIBRARY_PATH=/usr/lib/vlc ENV VLC_PLUGIN_PATH=/usr/lib/vlc/plugins CMD [&quot;python&quot;, &quot;ethos/main.py&quot;] </code></pre> <h1>Issue:</h1> <p>When I run the container:</p> <pre><code>$ docker run --rm -it ethos </code></pre> <p>I get these errors first:</p> <pre><code>[0000562689e1b130] vlcpulse audio output

## Docker Stack + Env Variables
 - [https://www.reddit.com/r/docker/comments/1ip9jph/docker_stack_env_variables](https://www.reddit.com/r/docker/comments/1ip9jph/docker_stack_env_variables)
 - RSS feed: $source
 - date published: 2025-02-14T12:32:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to move my stacks from being instantiated in Portainer to being instantiated via YAML files on my swarm via the &quot;docker stack deploy&quot; command.</p> <p>The issue I am struggling with is at the top level of my YAML file I have several volumes that are backed by CIFS shared (Example below). In Portainer I store the CIFS username and password as environment variables and everything works. I&#39;ve come to under stand that &quot;docker stack&quot; does not use/process env variables the same way &quot;docker compose&quot; does. But that leaves me in a state where I&#39;m not certain how to keep the username and password out of the YAML file.</p> <p>Any recommendations?</p> <pre><code>volumes: my_mount: driver_opts: type: cifs device: //192.168.1.1/mount o: &quot;username=${NAS_UN},password=${NAS_PW},uid=1000,gid=1000,vers=3.0&quot; </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/code-

## Stuck on running Freshrss/freshrss docker with Traefik
 - [https://www.reddit.com/r/docker/comments/1ip469b/stuck_on_running_freshrssfreshrss_docker_with](https://www.reddit.com/r/docker/comments/1ip469b/stuck_on_running_freshrssfreshrss_docker_with)
 - RSS feed: $source
 - date published: 2025-02-14T06:10:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi, it&#39;s been a damn long day fighting this.</p> <p>I am trying to run the freshrss docker container behind a Traefik proxy. I am starting it though a docker compose file. Docker is running inside an Alpine Linux VM running on my Truenas server. In this same VM I have about 7 other docker containers running with no issues. Most don&#39;t do a lot, so the box is very quiet.</p> <p>I have two problems:</p> <p>(1) It starts dreadfully slow. I run the docker compose up. It creates the container, and says its running. If I tap into docker logs freshrss it is blank for about 15 minutes, then I get two lines</p> <p><code>[Fri Feb 14 00:53:12.024489 2025] [mpm_prefork:notice] [pid 1:tid 1] AH00163: Apache/2.4.62 (Debian) configured -- resuming normal operations</code></p> <p><code>[Fri Feb 14 00:53:12.024551 2025] [core:notice] [pid 1:tid 1] AH00094: Command line: &#39;apache2 -D FOREGROUND&#39;</code></p> <p>There is no activity on the box, so I assume 

## ELI5 Please
 - [https://www.reddit.com/r/docker/comments/1iozaag/eli5_please](https://www.reddit.com/r/docker/comments/1iozaag/eli5_please)
 - RSS feed: $source
 - date published: 2025-02-14T01:33:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I’m just tipping my toes into docker and trying to learn how all this works. I’ve read docs and watched a few videos but im still struggling until it finally “clicks”. Right now im trying to start easy and do pihole with the image from docker hub. I have specified the ports when i go to start the container but then when i got to localhost port 80 im just getting a 403 forbidden. Im running docker desktop on windows 11 but i also have an Ubuntu box i can use as well.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aford89"> /u/aford89 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iozaag/eli5_please/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iozaag/eli5_please/">[comments]</a></span>

## Running container as root PUID = 0 but mount volume with :ro (read only flag)
 - [https://www.reddit.com/r/docker/comments/1ioy6gv/running_container_as_root_puid_0_but_mount_volume](https://www.reddit.com/r/docker/comments/1ioy6gv/running_container_as_root_puid_0_but_mount_volume)
 - RSS feed: $source
 - date published: 2025-02-14T00:36:50+00:00

<!-- SC_OFF --><div class="md"><p>I want to make a Plex container with access to /dev/dri for hardware transcoding and the easiest way is to run as - PUID=0 and PGID=0. But when I mount my volumes, I want the container to have read/write to a config volume and read only to a Media folder. I want to make sure the :ro read only flag will work to stop write privleges to my Media folder. </p> <p>The idea if that the container does not have write access to any folder with user data. </p> <p>So my question is, if I run the container as as the PUID =0 for root user, if the container were compromized, would could the :ro read only flag get bypassed.<br/> I don&#39;t expect my container to be compromized, but I am trying to learn to deploy containers in a more securie way so I want to make sure the :ro flag works for the container even if it runs as the root PUID.</p> <p>Here is my YAML code</p> <p>version: &#39;3.8&#39;</p> <p>services:</p> <p>dockerplex:</p> <p>image: plexinc/pms-docker:ple

## Should I migrate my homelab IP space if I want to use docker?
 - [https://www.reddit.com/r/docker/comments/1ioxwer/should_i_migrate_my_homelab_ip_space_if_i_want_to](https://www.reddit.com/r/docker/comments/1ioxwer/should_i_migrate_my_homelab_ip_space_if_i_want_to)
 - RSS feed: $source
 - date published: 2025-02-14T00:22:49+00:00

<!-- SC_OFF --><div class="md"><p>My WLAN subnet 172.17.0.0/16 conflicts with Docker default net. Instead of changing every Docker network manually, should I migrate my entire home network to 10.0.0.0/8 instead?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bubba8291"> /u/Bubba8291 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ioxwer/should_i_migrate_my_homelab_ip_space_if_i_want_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ioxwer/should_i_migrate_my_homelab_ip_space_if_i_want_to/">[comments]</a></span>

