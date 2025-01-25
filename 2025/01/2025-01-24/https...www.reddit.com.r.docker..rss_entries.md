# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Need clarification on restart and restart_policy in docker compose
 - [https://www.reddit.com/r/docker/comments/1i97w86/need_clarification_on_restart_and_restart_policy](https://www.reddit.com/r/docker/comments/1i97w86/need_clarification_on_restart_and_restart_policy)
 - RSS feed: $source
 - date published: 2025-01-24T22:28:03+00:00

<!-- SC_OFF --><div class="md"><p>Greetings,</p> <p>I&#39;m trying to fix an annoying error that happens on my NAS every time I reboot. I end up regularly rebooting the NAS, because we have power issues in this part of Nashville (I&#39;m considering a generator, but don&#39;t have one yet). I have an nginx proxy manager container that doesn&#39;t come back up after the reboot (logs indicate an IP address conflict and an error 128 is thrown), but will come up after a few minutes. I currently have restart:unless-stopped set, but it is not working. I&#39;m not using a docker swarm.</p> <p>Is there a way to get this thing to try restarting, wait a minute, and then try again for a number of iterations like what restart_policy is supposed to do (but only for swarms, apparently)?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/williamwgant"> /u/williamwgant </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i97w86/need_clarification_on

## When should I NOT use Google’s Docker Distroless? 🤔🐋
 - [https://www.reddit.com/r/docker/comments/1i97ij4/when_should_i_not_use_googles_docker_distroless](https://www.reddit.com/r/docker/comments/1i97ij4/when_should_i_not_use_googles_docker_distroless)
 - RSS feed: $source
 - date published: 2025-01-24T22:11:25+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks! 🤺</p> <p>Quick question about Docker Distroless from Google:<br/> When <em>isn’t</em> it a good idea to use it? And on the flip side, what are the situations where it’s the absolute best choice?</p> <p>Would love to hear your thoughts! 🚀</p> <p>Thanks in advance! 🖖</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/camilocsoto"> /u/camilocsoto </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i97ij4/when_should_i_not_use_googles_docker_distroless/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i97ij4/when_should_i_not_use_googles_docker_distroless/">[comments]</a></span>

## Is haugene/docker-transmission-openvpn broken?
 - [https://www.reddit.com/r/docker/comments/1i962m8/is_haugenedockertransmissionopenvpn_broken](https://www.reddit.com/r/docker/comments/1i962m8/is_haugenedockertransmissionopenvpn_broken)
 - RSS feed: $source
 - date published: 2025-01-24T21:09:09+00:00

<!-- SC_OFF --><div class="md"><p>using docker/portainer on Linux 5.10.60</p> <p>This docker image looked great so i deleted my transmission and I tried to replace it with this image with openvpn built in to it</p> <p>I&#39;m confident its configured correctly but it doesnt work... its starts and seems to run ok but there is no GUI</p> <p>i downloaded and copied my ovpn files from protonvpn to the ovpn folder. </p> <pre><code>version: &#39;3.3&#39; services: transmission-openvpn: cap_add: - NET_ADMIN volumes: - &#39;/share/CACHEDEV1_DATA/Container/Transmission-openvpn/data/:/data&#39; - &#39;/share/CACHEDEV1_DATA/Container/Transmission-openvpn/config/:/config&#39; environment: - OPENVPN_PROVIDER=protonvpn - OPENVPN_CONFIG=nl-free-34.protonvpn.udp - OPENVPN_USERNAME=Cxxxxxxxxxxxxis - OPENVPN_PASSWORD=eQgYOxxxxxxxxxxxxxxxxxxxWwBE8 - LOCAL_NETWORK=192.168.3.0/24 logging: driver: json-file options: max-size: 10m ports: - &#39;9091:9091&#39; image: haugene/transmission-openvpn </code></pr

## Deploying multiple Dockefiles or a Docker-Compose for free for a student project
 - [https://www.reddit.com/r/docker/comments/1i94q0o/deploying_multiple_dockefiles_or_a_dockercompose](https://www.reddit.com/r/docker/comments/1i94q0o/deploying_multiple_dockefiles_or_a_dockercompose)
 - RSS feed: $source
 - date published: 2025-01-24T20:11:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a student working on a Web project. We are required to deploy it online, and my team would prefer to do it for free. I have set up Dockerfiles for all parts of the project (1 frontend + 2 backend) and a docker-compose to launch all at once.</p> <p>Unfortunately I&#39;m struggling to find a solution to host all of this for free. Render doesn&#39;t support docker-compose, and their solution (&quot;Blueprints&quot;) is paid. Is there any way to host this for free?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hungeelug"> /u/hungeelug </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i94q0o/deploying_multiple_dockefiles_or_a_dockercompose/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i94q0o/deploying_multiple_dockefiles_or_a_dockercompose/">[comments]</a></span>

## signal.fyi: Automated Public Docker Image Compliance & Reporting 🚀
 - [https://www.reddit.com/r/docker/comments/1i94b3a/signalfyi_automated_public_docker_image](https://www.reddit.com/r/docker/comments/1i94b3a/signalfyi_automated_public_docker_image)
 - RSS feed: $source
 - date published: 2025-01-24T19:53:30+00:00

<!-- SC_OFF --><div class="md"><p>Managing compliance for public Docker images doesn’t have to be a hassle. <a href="https://www.signal.fyi/">Signal.fyi</a> simplifies the process so your team can focus on what truly matters: delivering impactful solutions.</p> <p>Here’s how we help:<br/> 1️⃣ <strong>Community Insights</strong>: Public Reports &amp; Dashboards—no login required.<br/> 2️⃣ <strong>Pull Request Context</strong>: Vulnerabilities &amp; digest tracking directly in your GitHub repo.<br/> 3️⃣ <strong>Fast Setup</strong>: Install today, see results before tomorrow’s stand-up.</p> <p>👉 <strong>Why it matters:</strong><br/> Every version change in your parent Docker image impacts your security posture. <a href="https://www.signal.fyi/">Signal.fyi</a> surfaces this critical data, helping your team stay ahead and make informed decisions.</p> <p><a href="https://www.lftsolutions.com/are-you-managing-the-hidden-costs-of-public-docker-images/">👉 Are you managing the hidden costs of 

## Best Practice Question...
 - [https://www.reddit.com/r/docker/comments/1i9465s/best_practice_question](https://www.reddit.com/r/docker/comments/1i9465s/best_practice_question)
 - RSS feed: $source
 - date published: 2025-01-24T19:47:28+00:00

<!-- SC_OFF --><div class="md"><p>I want t deploy a couple of containers that both have dependencies on Postgres and Redis. What&#39;s the best way to deploy this:</p> <p>1: Each application has it&#39;s own containerised instance of the 2 databases?<br/> 2: Install single instances of the DBs in their own containers and let the apps share them?<br/> 3: Install the DBs as full apps (not containerised) and let the apps share them?<br/> 4: Something else?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ikothsowe"> /u/ikothsowe </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i9465s/best_practice_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i9465s/best_practice_question/">[comments]</a></span>

## Container using VPN accessing other container without VPN
 - [https://www.reddit.com/r/docker/comments/1i91j89/container_using_vpn_accessing_other_container](https://www.reddit.com/r/docker/comments/1i91j89/container_using_vpn_accessing_other_container)
 - RSS feed: $source
 - date published: 2025-01-24T17:57:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I have a container A that connect to a VPN container B and it works<br/> All the network from container A goes through the VPN in container B<br/> But I&#39;d also like container A to access container C that isnt using the VPN<br/> Is it possible?</p> <p>Thanks!</p> <p>Here is the docker-compose file</p> <pre><code>version: &#39;3.8&#39; services: bot: build: . image: bot-image container_name: bot-container stdin_open: true tty: true restart: unless-stopped volumes: - ./code:/home/bot/code - ./cache:/home/bot/cache environment: - REDIS_OM_URL env_file: - .env depends_on: - cache - wireguard-my network_mode: container:wireguard-my wireguard-my: image: linuxserver/wireguard container_name: wireguard-my restart: unless-stopped ports: - 19876-19876 networks: - net01 volumes: - &#39;./wireguard:/config&#39; - &#39;/lib/modules:/lib/modules:ro&#39; environment: - PUID=1000 - PGID=1000 cap_add: - NET_ADMIN sysctls: - net.ipv4.conf.all.src_valid_

## Air VPN, qBittorrent, port forwarding not working.
 - [https://www.reddit.com/r/docker/comments/1i8zlhl/air_vpn_qbittorrent_port_forwarding_not_working](https://www.reddit.com/r/docker/comments/1i8zlhl/air_vpn_qbittorrent_port_forwarding_not_working)
 - RSS feed: $source
 - date published: 2025-01-24T16:37:47+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I know I&#39;m in over my head here but everything had gone perfectly following the tutorials found here: </p> <p>- <a href="https://greenfrognest.com/index.php">https://greenfrognest.com/index.php</a></p> <p>Everything was set up perfectly and everything seems to be working. However, when I try and check my &#39;connectability&#39; of my qBittorrent client it&#39;s saying I&#39;m not &#39;connectable&#39; and qBittorrent says I&#39;m &#39;firewalled&#39;.</p> <p>I know it&#39;s not my qBittorrent settings as the port is set up there. The website I&#39;m using can see the connection. </p> <p>docker-compose.yml is setup as the following:</p> <p><a href="https://imgur.com/a/Soghx7z">https://imgur.com/a/Soghx7z</a></p> <p>Can anyone point me in the right direction?</p> <p>Air VPN and qBittorret works perfectly on my Windows machine. I&#39;m so lost, I know I don&#39;t have the knowledge to work this out on my own. I&#39;ve been fiddling and

## How I can config the range that should be auto-assigned?
 - [https://www.reddit.com/r/docker/comments/1i8xymc/how_i_can_config_the_range_that_should_be](https://www.reddit.com/r/docker/comments/1i8xymc/how_i_can_config_the_range_that_should_be)
 - RSS feed: $source
 - date published: 2025-01-24T15:28:16+00:00

<!-- SC_OFF --><div class="md"><p>I made this dockerfile: </p> <p>```yaml version: &quot;3.8&quot; name: ${APP_NAME}</p> <p>services:</p> <p># PHP APPS php_app: container_name: ${APP_NAME} image: ${APP_NAME}/php build: context: . dockerfile: ./dockerfiles/Dockerfile args: - COMPOSER_VERSION=latest - XDEBUG_VERSION=latest volumes: - &quot;php_app:/var/www/html&quot; - &quot;./logs/xdebug:/var/log/xdebug&quot; - &quot;./ssl/ca/ca.crt:/usr/local/share/cert_install/ca.crt&quot; - &quot;./volumes/www-home:/home/www-data&quot; networks: default: env_file: env/php.env</p> <p># Supportive services</p> <p>nginx: container_name: ${APP_NAME}-nginx image: nginx networks: default: ipv4_address: ${IP_BASE}.2 volumes: - &quot;php_app:/var/www/html&quot; - &quot;./conf/nginx/nginx.conf:/etc/nginx/nginx.conf:ro&quot; - &quot;./ssl/certs/<a href="http://www.crt:/etc/nginx/ssl/www.crt:ro">www.crt:/etc/nginx/ssl/www.crt:ro</a>&quot; - &quot;./ssl/certs/<a href="http://www.key:/etc/nginx/ssl/www.key:ro">

## SSH Agent Forwarding
 - [https://www.reddit.com/r/docker/comments/1i8wmtv/ssh_agent_forwarding](https://www.reddit.com/r/docker/comments/1i8wmtv/ssh_agent_forwarding)
 - RSS feed: $source
 - date published: 2025-01-24T14:29:44+00:00

<!-- SC_OFF --><div class="md"><p>So, I have this situation where I have multiple ssh-keys added to my ssh-agent on my host machine. The forwarding works and I can see all my keys by running &quot;ssh-add -l&quot; from inside the container.</p> <p>The problem is: because I have multiple keys, when I try to use it on git inside the container, it attempts to use the first key and if it is not the correct key it will fail, without trying the others.</p> <p>I solved this same problem on my host machine by adding custom hosts to the ~/.ssh/config file, but that file doesn&#39;t exists inside the container and I can&#39;t create it there because it references the ssh-key file from my host machine. For that to work I would have to also copy my key inside the container, but I don&#39;t think that&#39;s a good idea and then there would be no point on forwarding the agent.</p> <p>My question is: is there a way to only forward a specific key into a container?</p> <p>I tried specifying only one 

## How to Deploy Multiple Microservices Using Docker-Compose on Code Push?
 - [https://www.reddit.com/r/docker/comments/1i8uf12/how_to_deploy_multiple_microservices_using](https://www.reddit.com/r/docker/comments/1i8uf12/how_to_deploy_multiple_microservices_using)
 - RSS feed: $source
 - date published: 2025-01-24T12:37:50+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m working with a microservices architecture where we have <strong>five separate Git repositories</strong>, each representing a different microservice. We want to deploy these microservices using <strong>Docker-Compose</strong> whenever a developer pushes a change to one of the repositories.</p> <h1>Current Setup:</h1> <ul> <li>Each microservice has its own repository.</li> <li>We use <strong>Docker</strong> to containerize each service.</li> <li>We plan to use <strong>Docker-Compose</strong> to orchestrate them.</li> <li>A developer may push a change to <strong>one</strong> of the repositories, and we want only that updated service to be deployed while keeping the rest running.</li> </ul> <p>How should I structure the <strong>Docker-Compose setup</strong> for multiple repositories?<br/> also <strong>Can we use Docker-Compose for production deployment?</strong> (Considering we expect a max of <strong>500 concurrent users</

## Docker - Nginx-proxy-manager issues logging in
 - [https://www.reddit.com/r/docker/comments/1i8tzlp/docker_nginxproxymanager_issues_logging_in](https://www.reddit.com/r/docker/comments/1i8tzlp/docker_nginxproxymanager_issues_logging_in)
 - RSS feed: $source
 - date published: 2025-01-24T12:12:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Hoping someone can help.</p> <p>I&#39;ve got Nginx-Proxy-manager installed on my main docker host and i&#39;m having issues logging in. On the front end, i get a &quot;bad gateway&quot; error</p> <p>This did work fine previously before i did a refresh on the OS / Docker install</p> <p>If i put the same compose config onto another docker host it works fine. the back end is connected to a mysql host</p> <p>Docker version on the main host:</p> <p>Docker version 27.3.1, build ce12230</p> <p>And docker version on the other host</p> <p>Docker version 20.10.24+dfsg1, build 297e128</p> <p>The error i&#39;m getting is:</p> <p><code>2025/01/24 11:54:31 [error] 192#192: *112736 connect() failed (111: Connection refused) while connecting to upstream, client: 192.168.1.84, server: nginxproxymanager, request: &quot;POST /api/tokens HTTP/1.1&quot;, upstream: &quot;http://127.0.0.1:3000/tokens&quot;, host: &quot;192.168.1.99:81&quot;, referrer: &quot;

## I am missing something about dockerfiles. Assistance appreciated
 - [https://www.reddit.com/r/docker/comments/1i8qiuj/i_am_missing_something_about_dockerfiles](https://www.reddit.com/r/docker/comments/1i8qiuj/i_am_missing_something_about_dockerfiles)
 - RSS feed: $source
 - date published: 2025-01-24T08:00:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m pretty new to dockerfiles but I feel I understand the concept with partial competency. I understand that the RUN command makes layers, and that the commands seem to be run in parrallel.</p> <p>I have forked a repo and have added some commands. The repo worked before I added the commands.</p> <p>My repo is located here: <a href="https://github.com/simonmcnair/arm-dependencies">https://github.com/simonmcnair/arm-dependencies</a></p> <p>I&#39;m just playing with it so I didn&#39;t bother creating branches as it was not made to share with others, it was just a play thing (yes I know that is wrong, and I should follow basic coding practices even for leisure, sorry).</p> <p>I don&#39;t understand why it keeps failing. I&#39;m trying to enable &#39;Intel QuickSync&#39; in <a href="https://github.com/automatic-ripping-machine/automatic-ripping-machine">https://github.com/automatic-ripping-machine/automatic-ripping-machine</a> and I&#39;m having issue

## How do localhost connection go to the container without explicitly specifying it?
 - [https://www.reddit.com/r/docker/comments/1i8q971/how_do_localhost_connection_go_to_the_container](https://www.reddit.com/r/docker/comments/1i8q971/how_do_localhost_connection_go_to_the_container)
 - RSS feed: $source
 - date published: 2025-01-24T07:40:18+00:00

<!-- SC_OFF --><div class="md"><p>I have a very simple Dockerfile:</p> <pre><code>FROM python:3.10.4-slim-bullseye ENV PIP_DISABLE_PIP_VERSION_CHECK=1 ENV PYTHONDONTWRITEBYTECODE=1 ENV PYTHONUNBUFFERED=1 WORKDIR /code COPY ./requirements.txt . RUN pip install -r requirements.txt COPY . . </code></pre> <p>And a docker-compose file:</p> <pre><code>version: &quot;3.9&quot; services: web: build: . ports: - &quot;8000:8000&quot; command: python manage.py runserver 0.0.0.0:8000 volumes: - .:/code version: &quot;3.9&quot; services: web: build: . ports: - &quot;8000:8000&quot; command: python manage.py runserver 0.0.0.0:8000 volumes: - .:/code </code></pre> <p>Here I have mapped the local port 8000 to the container&#39;s port 8000. But how is that only the address <a href="http://128.0.0.1">128.0.0.1</a> goes to the container while no other one does that. Where have we specified this and what if I want some other address to go to the container?</p> </div><!-- SC_ON --> &#32; submitted by &#3

## Need help with gluetun and prowlarr
 - [https://www.reddit.com/r/docker/comments/1i8orq4/need_help_with_gluetun_and_prowlarr](https://www.reddit.com/r/docker/comments/1i8orq4/need_help_with_gluetun_and_prowlarr)
 - RSS feed: $source
 - date published: 2025-01-24T05:56:47+00:00

<!-- SC_OFF --><div class="md"><p>Ok so I&#39;m fairly new to ubuntu and linux. But I&#39;m learning. So I have qbittorrent and prowlarr behind vpn on gluetun I can access everything but when I go to setup my apps in prowlarr I can&#39;t get communication between them. How do I go about this. I&#39;ve got a common network setup between the containers. I&#39;m running the whole thing on an old hp dl360p gen8. Don&#39;t think that makes a difference. I&#39;ve been banging my head against the ground on this one. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/drtyr32"> /u/drtyr32 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i8orq4/need_help_with_gluetun_and_prowlarr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i8orq4/need_help_with_gluetun_and_prowlarr/">[comments]</a></span>

## Django container in Debian Docker sending continuous SYN_SENT requests to public IP on port 9000
 - [https://www.reddit.com/r/docker/comments/1i8opm6/django_container_in_debian_docker_sending](https://www.reddit.com/r/docker/comments/1i8opm6/django_container_in_debian_docker_sending)
 - RSS feed: $source
 - date published: 2025-01-24T05:52:59+00:00

<!-- SC_OFF --><div class="md"><p>I have a Django-based website running inside a Debian Docker container, with the host OS being Ubuntu. I&#39;ve encountered an issue where one of my containers is continuously sending <strong><em>SYN_SENT</em></strong> requests to a destination public IP on port <strong><em>9000</em></strong>.</p> <p>I’ve tried tracing which process is responsible for this by using netstat to find the process ID. However, all the processes are associated with the &quot;<strong><em>gunicorn</em></strong>&quot; process. I’ve used several commands like netstat, ps, and lsof, but I’m unable to pinpoint which part of my code is causing this issue.</p> <p>Has anyone faced something similar or have suggestions on how to track down the source of this behavior?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upset_Shine_352"> /u/Upset_Shine_352 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i8opm6/django_container_in

## I made a complete beginner’s guide to understanding Docker
 - [https://www.reddit.com/r/docker/comments/1i8mxzc/i_made_a_complete_beginners_guide_to](https://www.reddit.com/r/docker/comments/1i8mxzc/i_made_a_complete_beginners_guide_to)
 - RSS feed: $source
 - date published: 2025-01-24T04:08:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I always had trouble understanding Docker when I first started using it so I made a guide.</p> <p>Please let me know what you think : <a href="https://youtu.be/QtH-RqFcDFc">https://youtu.be/QtH-RqFcDFc</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/M0shka"> /u/M0shka </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i8mxzc/i_made_a_complete_beginners_guide_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i8mxzc/i_made_a_complete_beginners_guide_to/">[comments]</a></span>

## Complete noob question, please be kind.
 - [https://www.reddit.com/r/docker/comments/1i8lh9z/complete_noob_question_please_be_kind](https://www.reddit.com/r/docker/comments/1i8lh9z/complete_noob_question_please_be_kind)
 - RSS feed: $source
 - date published: 2025-01-24T02:50:10+00:00

<!-- SC_OFF --><div class="md"><p>I run Immich in a Docker container. I don&#39;t do anything fancy. It runs, and I don&#39;t touch it.</p> <p>I&#39;d like to run another image on Docker, something host an internal Wiki. </p> <p>Q: Do I add the appropriate lines to the existing docker.yml and .env files, or do I somehow setup another pair of files for the the Wiki image?</p> <p>Thanks, and my apologies if this is obvious (which I&#39;m sure it is).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrarieCoastal"> /u/PrarieCoastal </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i8lh9z/complete_noob_question_please_be_kind/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i8lh9z/complete_noob_question_please_be_kind/">[comments]</a></span>

## Can I connect to qBitt if I moved it to Docker?...
 - [https://www.reddit.com/r/docker/comments/1i8ieks/can_i_connect_to_qbitt_if_i_moved_it_to_docker](https://www.reddit.com/r/docker/comments/1i8ieks/can_i_connect_to_qbitt_if_i_moved_it_to_docker)
 - RSS feed: $source
 - date published: 2025-01-24T00:18:23+00:00

<!-- SC_OFF --><div class="md"><p>My setup: Latest Ubuntu LTS. This PC acts as a server. Docker on it. VPN provider is ProtonVPN. My own domain name (connected with Cloudflare) that points to the server&#39;s public IP via NGINX Proxy Manager (NPM).</p> <p>Currently, I have qBittorrent, Real-Debrid Client &amp; Radarr/Sonarr/Bazarr on my native machine and they are <em>not</em> inside Docker, and they all work together perfectly to auto-download stuff. My ProtonVPN is also <strong>not</strong> in Docker. My media client is Jellyfin, which <strong>is</strong> in Docker. So, the only thing in Docker is my Jellyfin server.</p> <p>My entire issue: The moment I turn my VPN on, I can no longer access JF from my domain name; it just times out. The moment I turn it off, it is immediately accessible again. I would even be fine with just having qBitt alone run through the VPN and nothing else, but ProtonVPN on Linux only has IP-based split tunneling and not program-based. This has led me to ma

