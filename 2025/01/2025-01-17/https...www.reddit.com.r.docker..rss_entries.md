# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Are there tools for add/removing/modifying container image layers?
 - [https://www.reddit.com/r/docker/comments/1i3ta3r/are_there_tools_for_addremovingmodifying](https://www.reddit.com/r/docker/comments/1i3ta3r/are_there_tools_for_addremovingmodifying)
 - RSS feed: $source
 - date published: 2025-01-17T22:59:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve looked at `crane`, which has features like `append` and `rebase` (it&#39;s not clear from the documentation what it does, but I assume it removes the first layer and adds another?).</p> <p>I&#39;m basically interested in something that does some of the manifest and tarballing, i.e. `tool remove layer &lt;sha256sum&gt;` `tool add layer tarball.tar.gz &lt;index&gt;` or similar.</p> <p>Similarly, are there any tools for image composition, i.e. merging different images into one?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GeniusPengiun"> /u/GeniusPengiun </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3ta3r/are_there_tools_for_addremovingmodifying/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3ta3r/are_there_tools_for_addremovingmodifying/">[comments]</a></span>

## Dockerised Laravel App behind Host Nginx reverse proxy always throws 404
 - [https://www.reddit.com/r/docker/comments/1i3phoj/dockerised_laravel_app_behind_host_nginx_reverse](https://www.reddit.com/r/docker/comments/1i3phoj/dockerised_laravel_app_behind_host_nginx_reverse)
 - RSS feed: $source
 - date published: 2025-01-17T20:10:02+00:00

<!-- SC_OFF --><div class="md"><p>I have a laravel app running in ubuntu server and I was using Nginx to directly server the public folder. I had also configured all the SSL certificates for the different domains and subdomains that I am using in my app.</p> <p>Now I decided to dockerize my laravel app, which I did.</p> <p>Now since I already had nginx configured, I decided not to use nginx image in my docker. So I updated my nginx configs so that nginx now acts as a reverse proxy and forwards all requests to the laravel app running in the container. But still whenever I access my website, I am redirected to the 404 page. How do I fix this? </p> <p>Here&#39;s an example nginx config file-</p> <pre><code># Main HTTPS block server { listen 443 ssl http2; listen [::]:443 ssl http2; server_name example.com www.example.com; # root /var/www/backend/groback/public; # SSL Configuration ssl_certificate /etc/letsencrypt/live/example.com-0001/fullchain.pem; ssl_certificate_key /etc/letsencrypt/

## Java 7 application runs in local container but not when deployed to Azure container
 - [https://www.reddit.com/r/docker/comments/1i3o20m/java_7_application_runs_in_local_container_but](https://www.reddit.com/r/docker/comments/1i3o20m/java_7_application_runs_in_local_container_but)
 - RSS feed: $source
 - date published: 2025-01-17T19:08:31+00:00

<!-- SC_OFF --><div class="md"><p>I have very fragile and very old Java application that is an integral part to my client&#39;s business operation. It&#39;s written by the national government so I don&#39;t have much scope to change how this application runs. It absolutely has to use Java 7 and there&#39;s nothing I can do to change this.</p> <p>The application comes with both a .bat file and a .sh file to run it. I have been able to run this application successfully on my Windows 11 machine using the bat file and also in a Linux-based docker container using the .sh file.</p> <p>The problem comes in when I deploy this image to an Azure container registry. There appears to be an issue with processing the javaagent in Azure. Below is a snippet from the Web App startup logs which shows the line in the .sh file where the error is thrown:</p> <p><code>2025-01-17T14:35:25.855384929Z FATAL ERROR in native method: processing of -javaagent failed</code></p> <p><code>2025-01-17T14:35:32.253593

## Getting video out of a container
 - [https://www.reddit.com/r/docker/comments/1i3m69h/getting_video_out_of_a_container](https://www.reddit.com/r/docker/comments/1i3m69h/getting_video_out_of_a_container)
 - RSS feed: $source
 - date published: 2025-01-17T17:48:50+00:00

<!-- SC_OFF --><div class="md"><p>We have a Python script that sends an audio feed to Azure speech recognition services and outputs the returned text to a window via TKinter on an extended monitor, which is then sent to a video switcher. Everything is working as expected but we need to make this scalable and would like to dockerize it. However, of course, we would need to get a video feed from this script. Is it possible to pass through a GPU to a container in, say, TrueNAS and still use Tkinter? Or do we need to adjust our strategy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/justin_quinn"> /u/justin_quinn </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3m69h/getting_video_out_of_a_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3m69h/getting_video_out_of_a_container/">[comments]</a></span>

## Routing Network Traffic Through Docker Containers
 - [https://www.reddit.com/r/docker/comments/1i3kejh/routing_network_traffic_through_docker_containers](https://www.reddit.com/r/docker/comments/1i3kejh/routing_network_traffic_through_docker_containers)
 - RSS feed: $source
 - date published: 2025-01-17T16:35:04+00:00

<!-- SC_OFF --><div class="md"><p>A scalable setup for routing network traffic through Docker containers.</p> <p><a href="https://safelyup.net/routing-network-traffic-through-docker-containers-c33cc91d4eb2">https://safelyup.net/routing-network-traffic-through-docker-containers-c33cc91d4eb2</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/safelyup"> /u/safelyup </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3kejh/routing_network_traffic_through_docker_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3kejh/routing_network_traffic_through_docker_containers/">[comments]</a></span>

## Just Created a Beginner-Friendly Docker Tutorial and Hands-on samples
 - [https://www.reddit.com/r/docker/comments/1i3hday/just_created_a_beginnerfriendly_docker_tutorial](https://www.reddit.com/r/docker/comments/1i3hday/just_created_a_beginnerfriendly_docker_tutorial)
 - RSS feed: $source
 - date published: 2025-01-17T14:20:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi, everyone!</p> <p>I&#39;m a cloud, container, devops enthusiast and recently wrote a Docker tutorial on <strong>DEV</strong>. I wanted to make Docker easier to understand for beginners and share some practical examples.</p> <p>If you’re new to Docker or want to refresh your skills, I’d love for you to check it out!</p> <p>Link in the comment.</p> <p>Feedback, questions, or suggestions are more than welcome. Let me know if there are topics you&#39;d like me to cover in future posts. 😊</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/obsezer"> /u/obsezer </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3hday/just_created_a_beginnerfriendly_docker_tutorial/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3hday/just_created_a_beginnerfriendly_docker_tutorial/">[comments]</a></span>

## Cannot wipe whole data from wordpress container.
 - [https://www.reddit.com/r/docker/comments/1i3fb50/cannot_wipe_whole_data_from_wordpress_container](https://www.reddit.com/r/docker/comments/1i3fb50/cannot_wipe_whole_data_from_wordpress_container)
 - RSS feed: $source
 - date published: 2025-01-17T12:31:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!<br/> I wanted to self host a site using wordpress. I deployed container with wordpress and after playing with it a little I wanted to wipe it, play with it from the start. The issue is that when I have stopped and removed process, deleted directory and &quot;docker-compose.yml&quot; the site still has previous data with all mess. So I started using other ports (8081:80, 8082:80 etc.) and it piled up. There is a mess too because Im learning wordpress but I have no idea how to wipe it to the &quot;choose language&quot; part in very beginning. Please help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/void_deeer"> /u/void_deeer </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3fb50/cannot_wipe_whole_data_from_wordpress_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3fb50/cannot_wipe_whole_data_from_wordpress_container/">[comments]</a></spa

## mysql connector problem + how to dockerize on cqrs
 - [https://www.reddit.com/r/docker/comments/1i3cwdd/mysql_connector_problem_how_to_dockerize_on_cqrs](https://www.reddit.com/r/docker/comments/1i3cwdd/mysql_connector_problem_how_to_dockerize_on_cqrs)
 - RSS feed: $source
 - date published: 2025-01-17T09:47:23+00:00

<!-- SC_OFF --><div class="md"><p>always get error when try to run docker-compose what are the mistakes? when i locally run the code it is working.</p> <pre><code># Use the official ASP.NET Core runtime as a parent image FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS base WORKDIR /app # Copy solution file and project files COPY [&quot;project.sln&quot;, &quot;.&quot;] COPY [&quot;project/API/API.csproj&quot;, &quot;project/API/&quot;] COPY [&quot;project/Application/Application.csproj&quot;, &quot;project/Application/&quot;] COPY [&quot;project/Domain/Domain.csproj&quot;, &quot;project/Domain/&quot;] COPY [&quot;project/Persistence/Persistence.csproj&quot;, &quot;project/Persistence/&quot;] # Restore dependencies RUN dotnet restore # Copy everything else and build COPY . . WORKDIR &quot;/src/project/API&quot; RUN dotnet build -c Release -o /app/build FROM build AS publish RUN dotnet publish -c Release -o /app/publish # Use the runtime image to run the app FROM base AS final WORKDIR /app

## Static IP taken by another container on reboot
 - [https://www.reddit.com/r/docker/comments/1i3cutn/static_ip_taken_by_another_container_on_reboot](https://www.reddit.com/r/docker/comments/1i3cutn/static_ip_taken_by_another_container_on_reboot)
 - RSS feed: $source
 - date published: 2025-01-17T09:43:59+00:00

<!-- SC_OFF --><div class="md"><p>So i have a docker network for my reverse proxy services, im using Caddy. I have set Caddy to have a static IP within the network. However upon reboot other containers in the network start quicker and then take that IP, as such Caddy fails to start causing all the other containers to not work as the reverse proxy is down.</p> <p>My compose files are all individual. Is there a way of either excluding my static IPs from the DHCP range/scope of the subnet OR making it so the other containers need to &quot;depend_on&quot; or wait for Caddy to be online before starting?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Eximo84"> /u/Eximo84 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i3cutn/static_ip_taken_by_another_container_on_reboot/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i3cutn/static_ip_taken_by_another_container_on_reboot/">[comments]</a></span>

## Need help with running CVAT container
 - [https://www.reddit.com/r/docker/comments/1i3ck35/need_help_with_running_cvat_container](https://www.reddit.com/r/docker/comments/1i3ck35/need_help_with_running_cvat_container)
 - RSS feed: $source
 - date published: 2025-01-17T09:20:47+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/docker/comments/1i3ck35/need_help_with_running_cvat_container/"> <img src="https://a.thumbs.redditmedia.com/XLjz6-ThyC7jxbaFOKzePXuyd5aWTVbjcCQEgVF0_P0.jpg" alt="Need help with running CVAT container " title="Need help with running CVAT container " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So I am trying to run CVAT using docker compose </p> <p><a href="https://preview.redd.it/akc0o1lduide1.png?width=1317&amp;format=png&amp;auto=webp&amp;s=c8e9e684809eaefdaf1d057fc2be7f72ec321998">this is their guide on how to do it.</a></p> <p>my issue is when i try to use &quot;docker compose up -d&quot; in cvat folder after its pulled from github it shows this... </p> <p><a href="https://preview.redd.it/y8zx6dbnuide1.png?width=1510&amp;format=png&amp;auto=webp&amp;s=d1533e5ead40fc29ddbca8b21bb39823189fdaa1">https://preview.redd.it/y8zx6dbnuide1.png?width=1510&amp;format=png&amp;auto=webp&amp;s=d1533e5ead40fc29ddbca8b21bb39823189fdaa1</a>

## [FAILED] Failed to start LSB: Bring up/down networking.
 - [https://www.reddit.com/r/docker/comments/1i3ceov/failed_failed_to_start_lsb_bring_updown_networking](https://www.reddit.com/r/docker/comments/1i3ceov/failed_failed_to_start_lsb_bring_updown_networking)
 - RSS feed: $source
 - date published: 2025-01-17T09:09:22+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve already installed h1f0x/rtorrent-rutorrent-openvpn, but I still can&#39;t solve the error. I leave the log to help me on the WD Pr4100 NAS with portainer. Thank you</p> <p>Welcome to CentOS Linux 7 (Core)!</p> <p>Set hostname to &lt;7ec3b2041e9d&gt;.</p> <p>[ OK ] Reached target Paths.</p> <p>[ OK ] Reached target Swap.</p> <p>[ OK ] Created slice Root Slice.</p> <p>[ OK ] Listening on Delayed Shutdown Socket.</p> <p>[ OK ] Listening on Journal Socket.</p> <p>[ OK ] Created slice System Slice.</p> <p>[ OK ] Reached target Slices.</p> <p>Starting Read and set NIS domainname from /etc/sysconfig/network...</p> <p>Starting Configure read-only root support...</p> <p>Starting Journal Service...</p> <p>[ OK ] Started Read and set NIS domainname from /etc/sysconfig/network.</p> <p>[ OK ] Started Configure read-only root support.</p> <p>[ OK ] Reached target Local File Systems.</p> <p>Starting Create Volatile Files and Directories...</p> <p>[ OK ] St

## VPN question
 - [https://www.reddit.com/r/docker/comments/1i39h25/vpn_question](https://www.reddit.com/r/docker/comments/1i39h25/vpn_question)
 - RSS feed: $source
 - date published: 2025-01-17T05:33:20+00:00

<!-- SC_OFF --><div class="md"><p>Still learning the ropes, but it&#39;s it possible to set things up so I can run a program through a VPN while still having access to files on the local machine and network. Would be setup on Windows 11 if that helps. Also would the VPN even be worth it since it has to go through the main OS so would it just show as the local machine? Seems like a lot, but I&#39;m not sure how I would do it or if it could even be done right. </p> <p>Thanks for any help! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nemesis0884"> /u/nemesis0884 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i39h25/vpn_question/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i39h25/vpn_question/">[comments]</a></span>

## Unable to Use Synology Bay in File Sharing - Mac OS Docker Desktop
 - [https://www.reddit.com/r/docker/comments/1i33d3k/unable_to_use_synology_bay_in_file_sharing_mac_os](https://www.reddit.com/r/docker/comments/1i33d3k/unable_to_use_synology_bay_in_file_sharing_mac_os)
 - RSS feed: $source
 - date published: 2025-01-17T00:07:16+00:00

<!-- SC_OFF --><div class="md"><p>Ok, I&#39;m not sure what to do here and I&#39;m at my wits end. Every time I try and add my Synology Bay drives to the File Sharing in Docker Desktop and hit apply, it immediately deletes them and sometimes it crashes the entire docker instance saying it can&#39;t find them. However, I know for sure I&#39;m putting in the right path. In my terminal under Volumes, there are Movies and Shows. If I try and put /Volume/Movies or /Volume/Shows it just doesn&#39;t work. I tried via a docker-compose file it fails saying I don&#39;t have permissions to `mkdir` via the /host_mnt/Volumes/Movies or whatever, which doesn&#39;t make sense to me because it&#39;s right there. What am I doing wrong and how can I fix this? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/valtro05"> /u/valtro05 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i33d3k/unable_to_use_synology_bay_in_file_sharing_mac_os/">[link]</a
