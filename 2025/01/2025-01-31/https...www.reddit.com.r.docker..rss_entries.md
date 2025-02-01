# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## SonarQube and SonarScanner on docker
 - [https://www.reddit.com/r/docker/comments/1ierpir/sonarqube_and_sonarscanner_on_docker](https://www.reddit.com/r/docker/comments/1ierpir/sonarqube_and_sonarscanner_on_docker)
 - RSS feed: $source
 - date published: 2025-01-31T22:48:31+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, i&#39;am working on a project that basically scans lots of repositories with different languages. To automatize that i write some scripts that clones repos from github and run sonarqube(community edition) and sonarscanner on docker. I use docker because i got issues with Java version. Problem is i can not see the results on sonargubes project section. O also tried semgrep but i can not store the results in json format, file does not contains findings. I will try codeql but my project is not in public repo, and the repositories that i want to scan is not belong to ne, i find them on github. </p> <p>Do you have any suggestions ? I am open to other free SAST tools or something that i can find vulnerabilities on public repos to create a report on them. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Winter-Freedom1174"> /u/Winter-Freedom1174 </a> <br/> <span><a href="https://www.reddit.com/r/docker/

## Docker context with yubikey is unusable
 - [https://www.reddit.com/r/docker/comments/1ieq2ef/docker_context_with_yubikey_is_unusable](https://www.reddit.com/r/docker/comments/1ieq2ef/docker_context_with_yubikey_is_unusable)
 - RSS feed: $source
 - date published: 2025-01-31T21:37:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I use docker context for a while which is great in combination with some tool like lazydocker. However I recently purchased a yubikey and I didn&#39;t except such problem. Because the yubikey ssh-key is resident, it require a pin and a touch, but every command with docker context require multiple confirmation, a simple `docker ps` will ask me two to input my pin and touch the key. Also the tools like lazydocker become completly unusable. </p> <p>I don&#39;t understand what is the problem, because with a simple ssh, if I exit and reenter, it won&#39;t ask me twice to input the private key, it&#39;s cached, but docker context doesn&#39;t seem to be able to do that. How can I solve this issue ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NoahZhyte"> /u/NoahZhyte </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ieq2ef/docker_context_with_yubikey_is_unusable/">[link]</a></span> &#

## I just ran my first container using Docker
 - [https://www.reddit.com/r/docker/comments/1ieogk2/i_just_ran_my_first_container_using_docker](https://www.reddit.com/r/docker/comments/1ieogk2/i_just_ran_my_first_container_using_docker)
 - RSS feed: $source
 - date published: 2025-01-31T20:28:53+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Material-Path-106"> /u/Material-Path-106 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ieogk2/i_just_ran_my_first_container_using_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ieogk2/i_just_ran_my_first_container_using_docker/">[comments]</a></span>

## Permissions help Docker write access on remote mount
 - [https://www.reddit.com/r/docker/comments/1ienuck/permissions_help_docker_write_access_on_remote](https://www.reddit.com/r/docker/comments/1ienuck/permissions_help_docker_write_access_on_remote)
 - RSS feed: $source
 - date published: 2025-01-31T20:02:52+00:00

<!-- SC_OFF --><div class="md"><p>I have setup an Emby docker container using Portainer on a Ubuntu server. PGID=1000 and PUID=1000.<br/> I mounted a few folders on my NAS (a seperate Synology machine).</p> <p>I found out during improper function in the Emby app that I did not have write access to aome of the folders on the remote mount. I changed the access , even giving 777 permission to one of the folders in question. The Ubuntu server machine has RW access to the mounteed folder but the docker container still cannot write to the folder.<br/> I read somewhere that I maybe need to have the permissions on thee remote mount set before I intially set up the container. Is that true? How to fix or troubleshoot further? Is there a way to get the Poratiner stack to start over again without losing my app settings etc</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ahole4Sure"> /u/Ahole4Sure </a> <br/> <span><a href="https://www.reddit.com/r/docker/com

## Architecture for Lab/Learning?
 - [https://www.reddit.com/r/docker/comments/1iencxd/architecture_for_lablearning](https://www.reddit.com/r/docker/comments/1iencxd/architecture_for_lablearning)
 - RSS feed: $source
 - date published: 2025-01-31T19:42:32+00:00

<!-- SC_OFF --><div class="md"><p>So i&#39;m learning Docker/Kubernetes (and eventually other devops stuff too) through KodeKloud. It&#39;s been decent so far but I feel like I need to sorta experiment on it myself on a sort of home lab or similar.</p> <p>One idea was doing something similar to kodekloud (and docker&#39;s) &quot;sample&quot; voting app, but obviously something I do from scratch myself.</p> <p>I feel like connecting everything and figuring out issues as I go along will make things make more sense, but I wanted to get an idea of architecture and get some thoughts.</p> <p>What im sort of thinking right now is:</p> <ul> <li>Some sort of SIMPLE Web app that has a simple front-end/backend. I&#39;m not sure yet here. I&#39;m a JavaScript/TypeScript person at work (I do automation testing) so i&#39;m not exactly an expert when it comes to web dev but this would give me maybe a good opportunity to mess with something neat? Maybe like an Express backend w/some sort of JS front

## MacOS malware bug - nothing works
 - [https://www.reddit.com/r/docker/comments/1ielynt/macos_malware_bug_nothing_works](https://www.reddit.com/r/docker/comments/1ielynt/macos_malware_bug_nothing_works)
 - RSS feed: $source
 - date published: 2025-01-31T18:44:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I&#39;ve started experiencing the ongoing malware bug for macOS and followed these instructions: <a href="https://github.com/docker/for-mac/issues/7527">https://github.com/docker/for-mac/issues/7527</a></p> <p>Uninstalling and reinstalling the specified version did not work. I tried doing this via homebrew instead and it did not work. I also tried downloading the newest version instead, and that also did not work. Each time, I have emptied the trash and closed the malware popup, but this persists. </p> <p>Would appreciate any help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fair_Promise8803"> /u/Fair_Promise8803 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ielynt/macos_malware_bug_nothing_works/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ielynt/macos_malware_bug_nothing_works/">[comments]</a></span>

## Why do we need to delete both Docker Image Container and image?
 - [https://www.reddit.com/r/docker/comments/1iej84z/why_do_we_need_to_delete_both_docker_image](https://www.reddit.com/r/docker/comments/1iej84z/why_do_we_need_to_delete_both_docker_image)
 - RSS feed: $source
 - date published: 2025-01-31T16:51:13+00:00

<!-- SC_OFF --><div class="md"><p>For context, I am new to docker and following a documentation to understand it. </p> <p>To test it (As in the documentation), I pulled nginx and then a container got created in the Docker Desktop. Then next step says to delete the container and then use rmi command to delete the image. My question is, why do we need to delete the image after deleting the container. What would happen if we just delete the container? What is the purpose of deleting both of them.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LeatherRecover7306"> /u/LeatherRecover7306 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iej84z/why_do_we_need_to_delete_both_docker_image/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iej84z/why_do_we_need_to_delete_both_docker_image/">[comments]</a></span>

## Postgres DB for my Vikunja - but where are my DB files?
 - [https://www.reddit.com/r/docker/comments/1ieip8p/postgres_db_for_my_vikunja_but_where_are_my_db](https://www.reddit.com/r/docker/comments/1ieip8p/postgres_db_for_my_vikunja_but_where_are_my_db)
 - RSS feed: $source
 - date published: 2025-01-31T16:29:10+00:00

<!-- SC_OFF --><div class="md"><p>I have a couple of apps running on an RPI. Now I&#39;m working on data backup in case of a catastrophe.</p> <p>I have a containerized postgres DB for my Vikunja instance. However: I can&#39;t find the actual database files. Clearly data is being persisted <em>somewhere</em> - there&#39;s no data loss on restarting Docker or even hard resetting the RPI.</p> <p>These are the relevant parts of my docker compose:</p> <p><code>vikunja:</code></p> <p><code>container_name: vikunja</code></p> <p><code>image: vikunja/vikunja</code></p> <p><code>environment:</code></p> <p><code>VIKUNJA_SERVICE_PUBLICURL:</code> <a href="https://vikunja.$DOMAINNAME"><code>https://vikunja.$DOMAINNAME</code></a></p> <p><code>#VIKUNJA_DATABASE_HOST: db</code></p> <p><code>VIKUNJA_DATABASE_HOST: vikunja_db</code></p> <p><code>VIKUNJA_DATABASE_PASSWORD: changeme</code></p> <p><code>#VIKUNJA_DATABASE_TYPE: mysql</code></p> <p><code>VIKUNJA_DATABASE_TYPE: postgres</code></p> <p><code>

## Cant see Linux option on file explorer
 - [https://www.reddit.com/r/docker/comments/1ieijue/cant_see_linux_option_on_file_explorer](https://www.reddit.com/r/docker/comments/1ieijue/cant_see_linux_option_on_file_explorer)
 - RSS feed: $source
 - date published: 2025-01-31T16:22:44+00:00

<!-- SC_OFF --><div class="md"><p>I recently did an update on my Windows 11 desktop and after restart, I can no longer see the Linux option that was available after I installed docker. This is where I kept my config files for my docker containers and now I cant find them to edit them. Do you have any idea how to get the Linux to show back up in the file explorer? </p> <p>I was under the assumption that if Docker is running that option would appear. My docker is running fine and so is the container I currently have inside it. I just am not able to edit the config files for the containers.</p> <p>Any help would be much appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Visible_Stable_2216"> /u/Visible_Stable_2216 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ieijue/cant_see_linux_option_on_file_explorer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ieijue/cant_see_linux_option_on

## Centralized network "router" in docker compose?
 - [https://www.reddit.com/r/docker/comments/1iegotb/centralized_network_router_in_docker_compose](https://www.reddit.com/r/docker/comments/1iegotb/centralized_network_router_in_docker_compose)
 - RSS feed: $source
 - date published: 2025-01-31T15:01:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;m working in containerizing a network of microservices for local development, which currently looks like this, there&#39;s N containers that all communicate with a database as well as with one another, plus container 1 is accesible to the client; also there&#39;s an exposed admin panel that communicates to the database but not to other containers. </p> <p>My question is, is there a way I can add a sort of router to my compose file, expose it (and only it) to the client, and have all network traffic go through it? I want to do this for a few reasons</p> <ol> <li>I want to have a network wide DNS server to configure each service&#39;s address globally, as opposed to one by one in the config files for all services</li> <li>Some requests are hardcoded to be sent to the production servers, I want them redirected instead to the correct container instead </li> <li>(Optional, nice to have) I would love to be able to see a live log of ever

## How to force Docker Compose to pick the latest tag?
 - [https://www.reddit.com/r/docker/comments/1ieeh3m/how_to_force_docker_compose_to_pick_the_latest_tag](https://www.reddit.com/r/docker/comments/1ieeh3m/how_to_force_docker_compose_to_pick_the_latest_tag)
 - RSS feed: $source
 - date published: 2025-01-31T13:13:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m running this code</p> <p><code> FROM caddy:builder AS builder RUN xcaddy build \ --with github.com/SirLouen/caddy-bunny FROM caddy:latest COPY --from=builder /usr/bin/caddy /usr/bin/caddy </code></p> <p>For some reason say that caddy-bunny is in the tag 1.0.11 and then I update it to tag 1.0.12 unless I force like:</p> <p><code> --with github.com/SirLouen/caddy-bunny@v1.0.12 </code></p> <p>It will keep picking the <code>1.0.11</code> forever</p> <p>I&#39;ve tried using <code>docker builder prune</code> but still is picking the <code>1.0.11</code>. </p> <p>Also tried <code>docker compose build --progress=plain --no-cache</code> but nothing, it&#39;s again, still picking the 1.0.11</p> <p>Is there any solution to this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SirLouen"> /u/SirLouen </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ieeh3m/how_to_force_docker_compose_to_pick_the_late

## Trying to understand how Volumes work
 - [https://www.reddit.com/r/docker/comments/1iebxzx/trying_to_understand_how_volumes_work](https://www.reddit.com/r/docker/comments/1iebxzx/trying_to_understand_how_volumes_work)
 - RSS feed: $source
 - date published: 2025-01-31T10:34:50+00:00

<!-- SC_OFF --><div class="md"><h1>Introduction</h1> <p>I&#39;m new to docker and i&#39;m trying to learn how Volumes communicate beetween Host and Container. I understand the difference between a bind and not bind mount, how relatives paths work and how to setup them correctly inside my compose. But really I can&#39;t understand how unnamed volumes work.</p> <h1>The Problem</h1> <p>I&#39;m binding the service on a relative path <em>./pgadmin:</em> inside my compose directory (locally) and I want to create and use (inside the Container) a new folder called test <em>:/var/lib/pgadmin/test</em>.</p> <p><code> volumes: ./pgadmin:/var/lib/pgadmin/test/ </code></p> <p>Everything works. The folders communicate correctly, and when I compose up the first time a new volume (with a random name) gets created. I&#39;m assuming that it is an unnamed volume and should be temporary, but with a bind mount, shouldn’t it be permanent? Or must it be named (in the volume section) to be a permanent Volum

## Path is Not Shared From the Host
 - [https://www.reddit.com/r/docker/comments/1ie85vt/path_is_not_shared_from_the_host](https://www.reddit.com/r/docker/comments/1ie85vt/path_is_not_shared_from_the_host)
 - RSS feed: $source
 - date published: 2025-01-31T05:52:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I am new to Docker and Docker Compose and am trying to <a href="https://zerodya.net/self-host-jellyfin-media-streaming-stack/">follow this tutorial.</a> The two docker-compose.yml files I am using can be found there.</p> <p>I am using a very new installation of Ubuntu 24.04.01 LTS and my Docker version is 4.37.1. I am using the Docker Compose plugin, not the standalone, and it is version v2.31.0-desktop.2. Currently what I am stuck on is that Docker can not find the folders it needs to in the docker-compose.yml. Here is what it looks like when I try to start up the downloading-stack.</p> <pre><code>mymedia@mymedia-XPS-8900:~/srv/downloading-stack$ docker compose up -d WARN[0000] /home/mymedia/srv/downloading-stack/docker-compose.yml: the attribute `version` is obsolete, it will be ignored, please remove it to avoid potential confusion [+] Running 0/0 ⠋ Container jackett Starting 0.0s ⠋ Container transmission Starting 0.0s Error response from d

## which platform do you guys suggest to deploy docker container?
 - [https://www.reddit.com/r/docker/comments/1ie6oo9/which_platform_do_you_guys_suggest_to_deploy](https://www.reddit.com/r/docker/comments/1ie6oo9/which_platform_do_you_guys_suggest_to_deploy)
 - RSS feed: $source
 - date published: 2025-01-31T04:23:18+00:00

<!-- SC_OFF --><div class="md"><p>I have a Python app running in a docker container. </p> <p>Which platform is cost-effective and has good CPU/GPU resources?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LowZebra1628"> /u/LowZebra1628 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ie6oo9/which_platform_do_you_guys_suggest_to_deploy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ie6oo9/which_platform_do_you_guys_suggest_to_deploy/">[comments]</a></span>

