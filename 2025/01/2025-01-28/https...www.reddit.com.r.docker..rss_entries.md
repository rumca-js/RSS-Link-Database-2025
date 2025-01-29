# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Issue with CS 1.6 on Docker: SteamAPI fail and unable to connect to LAN server
 - [https://www.reddit.com/r/docker/comments/1iccwag/issue_with_cs_16_on_docker_steamapi_fail_and](https://www.reddit.com/r/docker/comments/1iccwag/issue_with_cs_16_on_docker_steamapi_fail_and)
 - RSS feed: $source
 - date published: 2025-01-28T21:29:39+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m running a CS 1.6 server in Docker using the image cm2network/steamcmd:latest on WSL with port forwarding set up, but I&#39;m getting this error in the console when refreshing the LAN server list:</p> <p><code>[S_API FAIL] Tried to access Steam interface SteamNetworkingUtils004 before SteamAPI_Init succeeded.</code></p> <p>Also, I&#39;m unable to connect to the server using <code>connect 127.0.0.1:27015</code>. </p> <p>The ports (TCP/UDP) are forwarded (<code>27015</code>). Does SteamAPI require additional initialization? Or is CS 1.6 problematic when running in containers? Has anyone encountered this issue?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FortiByte"> /u/FortiByte </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iccwag/issue_with_cs_16_on_docker_steamapi_fail_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iccwag/issue_with_cs_16_on

## Use atmoz/sftp to manage a volume used by other container
 - [https://www.reddit.com/r/docker/comments/1icc2op/use_atmozsftp_to_manage_a_volume_used_by_other](https://www.reddit.com/r/docker/comments/1icc2op/use_atmozsftp_to_manage_a_volume_used_by_other)
 - RSS feed: $source
 - date published: 2025-01-28T20:55:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I&#39;m trying to use <code>atmoz/sftp</code> to manage the html directory of a nginx instance. </p> <p>Here is the docker-compose file I&#39;m using:</p> <p>```yaml services: webserver: image: nginx:latest container_name: nginx_server ports: - &quot;8080:80&quot; volumes: - html_data:/usr/share/nginx/html restart: always</p> <p>sftp: image: atmoz/sftp:latest container_name: sftp_server ports: - &quot;2222:22&quot; volumes: - html_data:/home/website_user/upload environment: SFTP_USERS: ${SFTP_USERS} # Read credentials from the .env file restart: always</p> <p>volumes: html_data: ```</p> <p>with the following <code>.env</code>:</p> <p>```</p> <h1>USER:PASSWORD:UID</h1> <h1>USER <strong>must</strong> be &quot;website_user&quot; for the container to work</h1> <p>SFTP_USERS=website_user:SOME_PW ```</p> <p>I can login with SFTP just fine to the container on port 2222, but whenever I try to upload a file, I get the following error (using filezil

## Hosting a very small website with Raspberry Pi (Docker) - Security!
 - [https://www.reddit.com/r/docker/comments/1icbphs/hosting_a_very_small_website_with_raspberry_pi](https://www.reddit.com/r/docker/comments/1icbphs/hosting_a_very_small_website_with_raspberry_pi)
 - RSS feed: $source
 - date published: 2025-01-28T20:40:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>maybe you can help me, to sort my thoughts.<br/> I have very small website (views under 100/month).</p> <p>My domain is managed in Cloudflare. So my idea is, to host my wordpress website in a docker container.</p> <p>The traffic goes: Client -&gt; Cloudflare -&gt; Rasp Pi - Cloudflared Container -&gt; Port 80 of wordpress Docker container</p> <p>What&#39;s about security? Cloudflare blocks DDoS attacks ok. But is it even possible, that an attacker get access outside the docker network?</p> <p>Of course Wordpress will be get security things in .htaccess and so on.<br/> But just really in worse case: Can it get outside, in to my personal network? In my understanding docker network is capsuled and nothing can out (of course with exception the port 80 form cloudflared container to Wordpress container network) because of the default iptables.</p> <p>So I think the worse case is to just remove the docker volumes and create new ones. Is there a s

## Error launching Docker
 - [https://www.reddit.com/r/docker/comments/1icacht/error_launching_docker](https://www.reddit.com/r/docker/comments/1icacht/error_launching_docker)
 - RSS feed: $source
 - date published: 2025-01-28T19:45:14+00:00

<!-- SC_OFF --><div class="md"><p>So I have been trying to run Docker for the past 90 mins but no matter what I do I keep getting the “Unexpected WSL error” I did the wsl - - shutdown did update did everything but I wasn’t successful. Please if anyone knows I would really appreciate the help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NymeriaStarkk"> /u/NymeriaStarkk </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1icacht/error_launching_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1icacht/error_launching_docker/">[comments]</a></span>

## Did I mess up my NextCloud Installation by installing Jellyfin?
 - [https://www.reddit.com/r/docker/comments/1ic93gr/did_i_mess_up_my_nextcloud_installation_by](https://www.reddit.com/r/docker/comments/1ic93gr/did_i_mess_up_my_nextcloud_installation_by)
 - RSS feed: $source
 - date published: 2025-01-28T18:55:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;m kind of a beginner at this and recently build a NAS and Personal Cloud server using a Raspberry Pi 5, OMV and NextCloud in a container using Portainer. I hope you&#39;ll excuse my lack of knowledge.</p> <p>Last night I installed Jellyfin with another container through Portainer and now I can&#39;t access NextCloud. When I access it&#39;s address I get this message:</p> <pre><code>Internal Server Error The server encountered an internal error and was unable to complete your request. Please contact the server administrator if this error reappears multiple times, please include the technical details below in your report. More details can be found in the server log. </code></pre> <p>The mobile app also says &quot;Server not available&quot;.</p> <p>I have backups, so I&#39;m not super worried if I need to reset everything, I assume I messed up the NextCloud container when doing another for Jellyfin.</p> <p>Can anyone point me in the 

## Malawarebytes exclusions for Docker
 - [https://www.reddit.com/r/docker/comments/1ic7enn/malawarebytes_exclusions_for_docker](https://www.reddit.com/r/docker/comments/1ic7enn/malawarebytes_exclusions_for_docker)
 - RSS feed: $source
 - date published: 2025-01-28T17:46:56+00:00

<!-- SC_OFF --><div class="md"><p>All,</p> <p>recently I&#39;ve installed Docker Desktop on my Win 11 desktop, I&#39;m currently also running Malawarebytes and I&#39;m having a heck of time adding exclusions for Docker, does anyone have any insights what exe should I exclude? Cross posted on <a href="/r/Malawarebytes">r/Malawarebytes</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Independent_Bad5916"> /u/Independent_Bad5916 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ic7enn/malawarebytes_exclusions_for_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ic7enn/malawarebytes_exclusions_for_docker/">[comments]</a></span>

## Gluetun/Traefik Leak
 - [https://www.reddit.com/r/docker/comments/1ic5rsg/gluetuntraefik_leak](https://www.reddit.com/r/docker/comments/1ic5rsg/gluetuntraefik_leak)
 - RSS feed: $source
 - date published: 2025-01-28T16:40:59+00:00

<!-- SC_OFF --><div class="md"><p>I run Gluetun as a standalone container. Other containers are connected to Gluetun using the docker compose entry: <code>network_mode: container:gluetun</code></p> <p>I confirm VPN connectivity using: <code>docker exec -it &lt;container_name&gt; curl ipconfig.io</code> and all checks out.</p> <p>Adding Traefik labels to the Gluetun container and the IP check result is outside the VPN.</p> <pre><code>labels: - &quot;traefik.enable=true&quot; - &quot;traefik.docker.network=proxy&quot; - &quot;traefik.http.routers.container.entrypoints=web&quot; - &quot;traefik.http.routers.container.rule=Host(`container.serv11.internal`)&quot; - &quot;traefik.http.routers.container.service=bookstack&quot; - &quot;traefik.http.services.container.loadbalancer.server.port=80&quot; </code></pre> <p>Is anyone using Traefik with Gluetun connected containers with confirmed exit IP? If so, please let ne know how you have set this up. Thanks!</p> </div><!-- SC_ON --> &#32; subm

## Problem with running libadwaita apps in containers
 - [https://www.reddit.com/r/docker/comments/1ic5oa0/problem_with_running_libadwaita_apps_in_containers](https://www.reddit.com/r/docker/comments/1ic5oa0/problem_with_running_libadwaita_apps_in_containers)
 - RSS feed: $source
 - date published: 2025-01-28T16:36:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi, for testing purpose I&#39;m trying to run a GTK4/Libadwaita app in docker.</p> <p>I&#39;m running a basic Fedora container which has the &quot;adwaita-1-demo&quot; app install. When running the app in the container, it&#39;s not following my gnome desktop theme (which is expected), it&#39;s always light mode. Is there a way to force an adwaita app to be in adwaita dark mode without a desktop environment? </p> <p>What I&#39;ve tried:<br/> - Mounting ~/.config/gtk-4.0/ -&gt; does absolutely nothing</p> <p>- <code>GTK_THEME=adwaita:dark adwaita-1-demo</code> uses the legacy dark theme, not the adwaita one found on gnome</p> <p>- <a href="https://wiki.archlinux.org/title/GTK">This 4.2</a> -&gt; also does nothing</p> <p>Thanks for any help</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JumpyGame"> /u/JumpyGame </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ic5oa0/problem_with_running_libadwa

## How to connect using ngrok or tailscale to Ollama when it is inside an Open WebUI docker container?
 - [https://www.reddit.com/r/docker/comments/1ic5iaq/how_to_connect_using_ngrok_or_tailscale_to_ollama](https://www.reddit.com/r/docker/comments/1ic5iaq/how_to_connect_using_ngrok_or_tailscale_to_ollama)
 - RSS feed: $source
 - date published: 2025-01-28T16:29:34+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to figure out how to connect to Ollama when it is in a container that also has Open Web UI and other other services. When Ollama is in the Windows environment is works fine and ngrok can connect. When it is in the container it cannot. </p> <p>Ollama in Windows: <a href="http://host.docker.internal:11434">http://host.docker.internal:11434</a> Ollama in Docker with Open WebUI and other services: http://ollama:11434</p> <h3><strong>Docker Compose:</strong></h3> <pre><code>services: ollama: image: ollama/ollama:latest container_name: ollama ports: - &quot;11434:11434&quot; volumes: - openwebui_ollama:/root/.ollama networks: - open-webui-network deploy: resources: reservations: devices: - driver: nvidia count: all capabilities: [gpu] environment: - OLLAMA_DEBUG=1 - OLLAMA_MAX_LOADED_MODELS=3 - OLLAMA_KEEP_ALIVE=60m - OLLAMA_LOAD_TIMEOUT=2m - OLLAMA_NUM_PARALLEL=4 - OLLAMA_FLASH_ATTENTION=true # - OLLAMA_KV_CACHE_TYPE=f16 restart: always open-w

## Which containers do you have connected to gluetun and which is their functionality?
 - [https://www.reddit.com/r/docker/comments/1ic51ir/which_containers_do_you_have_connected_to_gluetun](https://www.reddit.com/r/docker/comments/1ic51ir/which_containers_do_you_have_connected_to_gluetun)
 - RSS feed: $source
 - date published: 2025-01-28T16:09:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!,</p> <p>I think that it would be nice that we shared with each other which containers we are connecting to qmcgaw/gluetun, so we can give each other ideas for different available services that other redditors can use.</p> <p>In my case, I am only using linuxserver/qbittorrent, to basically download torrents through a private VPN that is configured in qmcgaw/gluetun.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fearless_Falcon8785"> /u/Fearless_Falcon8785 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ic51ir/which_containers_do_you_have_connected_to_gluetun/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ic51ir/which_containers_do_you_have_connected_to_gluetun/">[comments]</a></span>

## Missing config directory
 - [https://www.reddit.com/r/docker/comments/1ibz3w1/missing_config_directory](https://www.reddit.com/r/docker/comments/1ibz3w1/missing_config_directory)
 - RSS feed: $source
 - date published: 2025-01-28T11:03:54+00:00

<!-- SC_OFF --><div class="md"><p>I keep getting this when trying to run a container. Would you mind helping me?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LowerYou4514"> /u/LowerYou4514 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ibz3w1/missing_config_directory/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ibz3w1/missing_config_directory/">[comments]</a></span>

## Isolate ethernet for containers and wifi for host?
 - [https://www.reddit.com/r/docker/comments/1ibwtzo/isolate_ethernet_for_containers_and_wifi_for_host](https://www.reddit.com/r/docker/comments/1ibwtzo/isolate_ethernet_for_containers_and_wifi_for_host)
 - RSS feed: $source
 - date published: 2025-01-28T08:09:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I&#39;ve been tinkering with docker containers and networking for a week or two now and I&#39;m wondering...</p> <p>Is it possible to isolate my ethernet adapter for all my contrainers on a separate ipvlan network? While I have managed to create the network and connect to it, the host is still accessible over ssh/port 22.</p> <p>Overall, I&#39;d love to have port-forwarded traffic go to an adapter that can talk to _only_ a single docker container that will be responsible for some security screening and reverse-proxys/redirects.</p> <p>Really, any security advice would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bilateral_melon"> /u/bilateral_melon </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ibwtzo/isolate_ethernet_for_containers_and_wifi_for_host/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ibwtzo/isolate_ethernet_for_conta

## Where have my containers gone?
 - [https://www.reddit.com/r/docker/comments/1ibso8f/where_have_my_containers_gone](https://www.reddit.com/r/docker/comments/1ibso8f/where_have_my_containers_gone)
 - RSS feed: $source
 - date published: 2025-01-28T03:40:12+00:00

<!-- SC_OFF --><div class="md"><p>Thanks for helping me understand this, but I seem to have lost all my containers, but they are all up and running!</p> <p>I&#39;m running docker on an Ubuntu server, and I&#39;m running several containers (NPM Proxy manager, portainer, pi-hole and a CRM). One of the first things I experimented with was Home Assistant, and I also have a container with Home Assistant; I installed this first.</p> <p>Something happened between installing Home Assistant and the other containers, and it never showed up in my docker ps -a. I&#39;ve just rebooted the server, and now all I see is Home Assistant and not the other containers.</p> <p>All my other containers are up and running, but I cannot seem to interact with them using any docker commands or via portainer. </p> <p>My search indicates two instances of docker running somehow, and I am struggling to find the second one. I would love to consolidate back to one and have everything in one instance.</p> </div><!-- S

## Lower Priority Internet For Individual Containers/Compose?
 - [https://www.reddit.com/r/docker/comments/1ibruw0/lower_priority_internet_for_individual](https://www.reddit.com/r/docker/comments/1ibruw0/lower_priority_internet_for_individual)
 - RSS feed: $source
 - date published: 2025-01-28T02:57:46+00:00

<!-- SC_OFF --><div class="md"><p>I have a docker compose that has torrent&#39;s running in it. When I use it, it slows down the other services that require internet access. I would like to set this compose or these containers as lower priority for internet traffic. I don&#39;t care about the speed so much as long as it doesn&#39;t impact my other services. Is this possible?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KatevanDis472"> /u/KatevanDis472 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ibruw0/lower_priority_internet_for_individual/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ibruw0/lower_priority_internet_for_individual/">[comments]</a></span>

## Newcomer to containerization
 - [https://www.reddit.com/r/docker/comments/1ibrrs6/newcomer_to_containerization](https://www.reddit.com/r/docker/comments/1ibrrs6/newcomer_to_containerization)
 - RSS feed: $source
 - date published: 2025-01-28T02:53:22+00:00

<!-- SC_OFF --><div class="md"><p>This might sound crazy to most of you, but until recently my entire network existed as dedicated machines, now they have become a Hyper-converged cluster(lol) as most of my machines are basically the same hardware wise, yea, I didn&#39;t even VM.</p> <p>On my cluster I run a few vm&#39;s, some different storage related VM&#39;s, my workstation, and a small swarm of docker instances which might seem stupid TBH, I&#39;ve had to spiritually go over it a few times for it to make sense, but there really are advantages to this approach.</p> <p>On my docker nodes, I have a few networking related containers for monitoring and traffic handling.</p> <p>Now that my system is functioning like I would like it too, with the reverse proxy and behind Cloudflare with proper access configured I would like to know, since I&#39;m not currently running any public facing web applications yet, how do you guys normally do this, containerized?</p> <p>I&#39;m going to be hone

