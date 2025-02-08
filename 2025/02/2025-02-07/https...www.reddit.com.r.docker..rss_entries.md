# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Networking Question
 - [https://www.reddit.com/r/docker/comments/1ik8gwe/networking_question](https://www.reddit.com/r/docker/comments/1ik8gwe/networking_question)
 - RSS feed: $source
 - date published: 2025-02-07T23:04:35+00:00

<!-- SC_OFF --><div class="md"><p>I am running a Flask app that, when run locally, will launch a browser window (127.0.0.1:XXXXX) for some authentication. When I run the app within a Docker container, how can I access that same authentication? </p> <p>I am exposing the port in the Dockerfile, and using `docker run -p XXXXX:XXXXX` for port publishing, but I still get an empty response (&quot;127.0.0.1 didn&#39;t send any data.&quot;) when I navigate to 127.0.0.1:XXXXX.</p> <p>Thank you!!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HeadlinesThink"> /u/HeadlinesThink </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ik8gwe/networking_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ik8gwe/networking_question/">[comments]</a></span>

## Host file manager shows data drive listings many times
 - [https://www.reddit.com/r/docker/comments/1ik7q3n/host_file_manager_shows_data_drive_listings_many](https://www.reddit.com/r/docker/comments/1ik7q3n/host_file_manager_shows_data_drive_listings_many)
 - RSS feed: $source
 - date published: 2025-02-07T22:32:06+00:00

<!-- SC_OFF --><div class="md"><p>After a reboot on Ubuntu 24.04, my Files app looks like this:<br/> <a href="https://postimg.cc/zyjfKp8H">https://postimg.cc/zyjfKp8H</a></p> <p>This started after I set up docker on this computer. When I bound an incorrect volume in one container, it created a drive for that an put it in the same listing multiple times.</p> <p>I have confirmed the volumes in the yaml file are all correct and they are all working as expected. My yaml files look like this:</p> <pre><code>services: gluetun: image: qmcgaw/gluetun container_name: gluetun cap_add: - NET_ADMIN volumes: - ./config/gluetun/auth/config.toml:/gluetun/auth/config.toml - ./config/gluetun:/gluetun - ./config/gluetun/info:/tmp/gluetun devices: - /dev/net/tun:/dev/net/tun ... </code></pre> <p>The home drive (Main above) is a SATA drive that I use for data. The docker containers are all in that data drive (/media/user/Main/docker/gluetun/ for example). Every time I restart a container, it seems to sp

## Can I use symbolic links or reference an external .env file in a different folder from the compose file?
 - [https://www.reddit.com/r/docker/comments/1ik5cck/can_i_use_symbolic_links_or_reference_an_external](https://www.reddit.com/r/docker/comments/1ik5cck/can_i_use_symbolic_links_or_reference_an_external)
 - RSS feed: $source
 - date published: 2025-02-07T20:50:38+00:00

<!-- SC_OFF --><div class="md"><p>My folder setup is as follows.</p> <pre><code>&gt; stacks .env &gt; radarr compose.yml &gt; sonarr compose.yml &gt; unmanic compose.yml </code></pre> <p>My <code>.env</code> file has the following</p> <pre><code>PUID=1000 PGID=100 TZ=Europe/London UMASK=002 DOCKER_DATA_PATH=/srv/dev-disk-by-uuid-f94e80d8-a1e4-4ee9-8ca1-dbef7eb0d715/_docker_configs MOVIES=/srv/dev-disk-by-uuid-680132be-a6e7-4aaa-97be-6759d66ddcfe/movies </code></pre> <p>And my unmanic compose file has</p> <pre><code>version: &quot;3&quot; services: unmanic: container_name: unmanic image: josh5/unmanic:latest ports: - 8888:8888 restart: unless-stopped env_file: ../.env networks: - unabatedshagie volumes: - ${DOCKER_DATA_PATH}/unmanic:/config - ${MOVIES}:/movies networks: unabatedshagie: name: unabatedshagie external: true </code></pre> <p>With the <code>.env</code> file outside the folder with the compose file, everything but the path works.</p> <p>If I move the <code>.env</code> file 

## Can I install all my containers on an external HDD and just pick up where I left off after a reinstall?
 - [https://www.reddit.com/r/docker/comments/1ik2e6z/can_i_install_all_my_containers_on_an_external](https://www.reddit.com/r/docker/comments/1ik2e6z/can_i_install_all_my_containers_on_an_external)
 - RSS feed: $source
 - date published: 2025-02-07T18:46:43+00:00

<!-- SC_OFF --><div class="md"><p>I have this shitty mini PC that shits itself so often I keep reinstalling the OS, or maybe I feel adventurous and try another distro altogether. Just curious if putting all my containers on an external HDD would work plug-and-play so long as I point Docker to the right directory of the HDD.</p> <p>Thanks :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Goldillux"> /u/Goldillux </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ik2e6z/can_i_install_all_my_containers_on_an_external/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ik2e6z/can_i_install_all_my_containers_on_an_external/">[comments]</a></span>

## How to deploy existing Vs 2022 C++ based project in docker
 - [https://www.reddit.com/r/docker/comments/1ik0omj/how_to_deploy_existing_vs_2022_c_based_project_in](https://www.reddit.com/r/docker/comments/1ik0omj/how_to_deploy_existing_vs_2022_c_based_project_in)
 - RSS feed: $source
 - date published: 2025-02-07T17:37:09+00:00

<!-- SC_OFF --><div class="md"><p>I see a lot of tutorials mentioning right clicking the project --&gt; Add--&gt; Docker, but that option does not exist in my instance of VS 2022. <a href="https://imgur.com/a/YgIyr09">Screenshot</a></p> <p>So far I have downloaded docker and enabled hyperV &amp; containers in Windows Features as well as virtualization in BIOS.</p> <p>To add, Docker does work with VS Code for me, but that was pretty straightforward with adding the Docker extension.</p> <p>Thanks in advance for any and all advice.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/catalystdownfall"> /u/catalystdownfall </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ik0omj/how_to_deploy_existing_vs_2022_c_based_project_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ik0omj/how_to_deploy_existing_vs_2022_c_based_project_in/">[comments]</a></span>

## Dockerfile append to /etc/hosts
 - [https://www.reddit.com/r/docker/comments/1ijz02n/dockerfile_append_to_etchosts](https://www.reddit.com/r/docker/comments/1ijz02n/dockerfile_append_to_etchosts)
 - RSS feed: $source
 - date published: 2025-02-07T16:28:23+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Currently I am working with &quot;Dev Container&quot; in VScode. I need to append an entry to the /etc/hosts file.</p> <p>I have tried to add &quot;RUN echo &quot;123 hostname&quot; &gt;&gt; /etc/hosts&quot; to the Dockerfile but an error &quot;Read-only file system&quot; appears.</p> <p>Do somebody have any idea how to achieve the above?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Odd-Cartoonist-6647"> /u/Odd-Cartoonist-6647 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ijz02n/dockerfile_append_to_etchosts/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ijz02n/dockerfile_append_to_etchosts/">[comments]</a></span>

## Question regarding gui on server
 - [https://www.reddit.com/r/docker/comments/1ijy7zm/question_regarding_gui_on_server](https://www.reddit.com/r/docker/comments/1ijy7zm/question_regarding_gui_on_server)
 - RSS feed: $source
 - date published: 2025-02-07T15:56:27+00:00

<!-- SC_OFF --><div class="md"><p>My company is considering switching to Linux for our digital signage. I am building a proof of concept. I have no problem when utilizing a LInux desktop and running the docker image. However, I am wanting to run the docker image on ubuntu server. (I am not using the docker snap package). Since server by default has no desktop environment and the docker image runs on x11, I am assuming that I need ot install xorg, and more on the server. My question is this, do I need to make changes to my docker files in order to access the resources on the local machine? Or do I just need to ensure that I install everything that is utilized when running the image on Linux with a DE?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zedboy19752019"> /u/Zedboy19752019 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ijy7zm/question_regarding_gui_on_server/">[link]</a></span> &#32; <span><a href="https://www.reddi

## "How to Properly Deploy a React App Using Docker?"
 - [https://www.reddit.com/r/docker/comments/1ijwtjk/how_to_properly_deploy_a_react_app_using_docker](https://www.reddit.com/r/docker/comments/1ijwtjk/how_to_properly_deploy_a_react_app_using_docker)
 - RSS feed: $source
 - date published: 2025-02-07T14:56:22+00:00

<!-- SC_OFF --><div class="md"><p>Currently facing issue in deployment of react App on Docker what resources to follow? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HalfAdministrative70"> /u/HalfAdministrative70 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ijwtjk/how_to_properly_deploy_a_react_app_using_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ijwtjk/how_to_properly_deploy_a_react_app_using_docker/">[comments]</a></span>

## I just ran my first container using Docker
 - [https://www.reddit.com/r/docker/comments/1ijvoph/i_just_ran_my_first_container_using_docker](https://www.reddit.com/r/docker/comments/1ijvoph/i_just_ran_my_first_container_using_docker)
 - RSS feed: $source
 - date published: 2025-02-07T14:03:35+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Select-Procedure7566"> /u/Select-Procedure7566 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ijvoph/i_just_ran_my_first_container_using_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ijvoph/i_just_ran_my_first_container_using_docker/">[comments]</a></span>

## 🐳 Dive Into Docker with the Latest Tips & News on RubyStackNews! 🚀
 - [https://www.reddit.com/r/docker/comments/1ijuopo/dive_into_docker_with_the_latest_tips_news_on](https://www.reddit.com/r/docker/comments/1ijuopo/dive_into_docker_with_the_latest_tips_news_on)
 - RSS feed: $source
 - date published: 2025-02-07T13:13:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey, Docker enthusiasts! 👋<br/> If you’re looking for fresh Docker tips, news, and tutorials, I’ve got you covered! I’ve been curating the latest and most useful content in my <a href="https://rubystacknews.com/category/programming/docker/"><strong>Docker section</strong></a> over at RubyStackNews. Whether you’re just starting with Docker or looking to improve your skills, there’s something for everyone!</p> <p>Here’s what you’ll find:</p> <ul> <li>🚀 Docker tutorials for developers</li> <li>🛠️ Best practices and tips for containerization</li> <li>🆕 Latest Docker updates and industry news</li> </ul> <p>If you’re into DevOps, containerization, or just want to stay on top of the latest Docker trends, check it out! Let’s talk about how we’re using Docker in our projects and share knowledge. 💬</p> <p>Feel free to visit and explore: <a href="https://rubystacknews.com/category/programming/docker/">Docker section on RubyStackNews</a></p> <p>Hope to see you t

## Looking for the Best IPTV Provider in Canada? The Best IPTV Service in Canada 🇨🇦 2025 Top IPTV Providers Reddit
 - [https://www.reddit.com/r/docker/comments/1ijsl6e/looking_for_the_best_iptv_provider_in_canada_the](https://www.reddit.com/r/docker/comments/1ijsl6e/looking_for_the_best_iptv_provider_in_canada_the)
 - RSS feed: $source
 - date published: 2025-02-07T11:07:51+00:00

<!-- SC_OFF --><div class="md"><p>Hey fellow Canadians! 🇨🇦</p> <p>If you&#39;re on the hunt for a reliable <strong>IPTV PROVIDER</strong> that delivers top-notch streaming quality, I’ve got two solid recommendations for you: <a href="http://Focus4K.com"><strong>Focus4K.com</strong></a> and <strong>IPTVfusionZone</strong>.</p> <p>I recently switched to <strong>Focus4K .com</strong> after trying out a bunch of different <strong>IPTV SERVICES</strong>, and I’ve been blown away by their 4K streaming quality and massive channel selection. Whether you&#39;re into sports, movies, or international content, they’ve got it all. Plus, their customer support is super responsive, which is a huge bonus. Check them out here: Focus4K .com.</p> <p>Another great option is <strong>IPTVfusionZone</strong>. While I haven’t used them personally, I’ve heard amazing things from friends who swear by their stability and affordable pricing. They’re definitely worth considering if you’re looking for a <strong>B

## I can not expose my dacker daemon
 - [https://www.reddit.com/r/docker/comments/1ijrnh8/i_can_not_expose_my_dacker_daemon](https://www.reddit.com/r/docker/comments/1ijrnh8/i_can_not_expose_my_dacker_daemon)
 - RSS feed: $source
 - date published: 2025-02-07T10:02:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi, little bit of DevOps beginner here. I am trying to learn about DevOps in a Windows machine. I am running Jenkins inside a container with another container as its docker host (DinD). In the pipeline process I want to run a container from the image I just created based on the latest Git push in my host machine. To be able to do that I believe I need to use my pc&#39;s dockerd because otherwise the container will be created in the DinD container if I understand the process correct.</p> <p>I might be wrong in everything I said, if so please feel free to correct me but regardless of it I want to expose my daemon (not only in localhost but in every network namespace of my pc) because its started to drive me crazy since I have been failing on it for 2 days. I change the conf file in the Docker Desktop and the daemon.json file but I keep getting this error :</p> <p>&quot;message&quot;:&quot;starting engine: starting vm: context canceled&quot;</p> <p>Mayb

## Macbook M1 python container error ImportError: /lib/aarch64-linux-gnu/libssl.so.3: file too short
 - [https://www.reddit.com/r/docker/comments/1ijmhx9/macbook_m1_python_container_error_importerror](https://www.reddit.com/r/docker/comments/1ijmhx9/macbook_m1_python_container_error_importerror)
 - RSS feed: $source
 - date published: 2025-02-07T04:14:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone I am facing an issue with docker with python and I really appreciate your help. Here is my docker and docker compose Docker Compose version v2.32.4-desktop.1 Docker version 27.5.1, build 9f9e405 I am trying to build a python image which is something like this ``` FROM python:3.12 ENV PYTHONUNBUFFERED=1</p> <h1>install node/npm</h1> <h1>mount /tmp -o remount,exec</h1> <p>RUN --mount=target=/var/lib/apt/lists,type=cache,sharing=locked \ --mount=target=/var/cache/apt,type=cache,sharing=locked \ rm -f /etc/apt/apt.conf.d/docker-clean &amp;&amp; \ echo &quot;deb <a href="https://deb.nodesource.com/node_20.x">https://deb.nodesource.com/node_20.x</a> bookworm main&quot; &gt; /etc/apt/sources.list.d/nodesource.list &amp;&amp; \ wget -qO- <a href="https://deb.nodesource.com/gpgkey/nodesource.gpg.key">https://deb.nodesource.com/gpgkey/nodesource.gpg.key</a> | apt-key add - &amp;&amp; \ apt-get update &amp;&amp; \ apt-get upgrade &amp;&amp; \ apt

## Is the docker registry down?
 - [https://www.reddit.com/r/docker/comments/1ijm9y0/is_the_docker_registry_down](https://www.reddit.com/r/docker/comments/1ijm9y0/is_the_docker_registry_down)
 - RSS feed: $source
 - date published: 2025-02-07T04:01:46+00:00

<!-- SC_OFF --><div class="md"><p>When i ping the registry i get this:</p> <pre><code>PS C:\WINDOWS\system32&gt; ping registry-1.docker.io Pinging registry-1.docker.io [98.85.153.80] with 32 bytes of data: Request timed out. Request timed out. Request timed out. Request timed out. Ping statistics for 98.85.153.80: Packets: Sent = 4, Received = 0, Lost = 4 (100% loss), PS C:\WINDOWS\system32&gt; ping google.com Pinging google.com [142.250.194.174] with 32 bytes of data: Reply from 142.250.194.174: bytes=32 time=32ms TTL=115 Reply from 142.250.194.174: bytes=32 time=29ms TTL=115 Reply from 142.250.194.174: bytes=32 time=28ms TTL=115 Reply from 142.250.194.174: bytes=32 time=30ms TTL=115 Ping statistics for 142.250.194.174: Packets: Sent = 4, Received = 4, Lost = 0 (0% loss), Approximate round trip times in milli-seconds: Minimum = 28ms, Maximum = 32ms, Average = 29ms </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/phuya"> /u/phuya </a> <

## Docker has 250GB Available but container keeps saying not enough disk space when importing files
 - [https://www.reddit.com/r/docker/comments/1ijlkzr/docker_has_250gb_available_but_container_keeps](https://www.reddit.com/r/docker/comments/1ijlkzr/docker_has_250gb_available_but_container_keeps)
 - RSS feed: $source
 - date published: 2025-02-07T03:24:12+00:00

<!-- SC_OFF --><div class="md"><p>As the title says, I am trying to setup a container, and docker at the bottom says it has 250gb available of disk space, and the C:/ drive has 1tb. Yet, this container, when I go to add files to it, it errors out and says not enough disk space. </p> <p>I&#39;ve done pruning and I&#39;ve tried to see in the settings -&gt; advanced if I could increase the disk space, but to no avail. Any assistance would be greatly appreciated.</p> <p>Edit: This is on Windows 10</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Soulcrifice"> /u/Soulcrifice </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ijlkzr/docker_has_250gb_available_but_container_keeps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ijlkzr/docker_has_250gb_available_but_container_keeps/">[comments]</a></span>

