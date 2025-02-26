# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Docker-compose project
 - [https://www.reddit.com/r/docker/comments/1iy9b6n/dockercompose_project](https://www.reddit.com/r/docker/comments/1iy9b6n/dockercompose_project)
 - RSS feed: $source
 - date published: 2025-02-25T23:33:16+00:00

<!-- SC_OFF --><div class="md"><p><a href="http://uuvs4qjpzbc7ieire4q6lifnhzi5c5w33eyewnpsctuusw4excsj4rad.onion/">http://uuvs4qjpzbc7ieire4q6lifnhzi5c5w33eyewnpsctuusw4excsj4rad.onion/</a></p> <p>Visit my site while it&#39;s up. This is just a test site that I will ship with the repo. Gonna make it way nicer and add documentation. Will be publishing a repository on my github runthescript. </p> <p>I had a thought, why don&#39;t more people publish onion sites? </p> <p>Seems to hard for most, until I had the thought there&#39;s docker. I could set up the services in torrc and boil this all down to some env variables. This way you just drop your website in and rename it&#39;s directory path. </p> <p>docker compose up --build and you&#39;re on the web. </p> <p>The persistence part is giving me some trouble. Obviously when you build the container you lose your keys and address. Attempting to solve this I tried to copy a local dir to the hidden-services on build and am getting permission 

## V 28.0.0 network issues?
 - [https://www.reddit.com/r/docker/comments/1iy7kx5/v_2800_network_issues](https://www.reddit.com/r/docker/comments/1iy7kx5/v_2800_network_issues)
 - RSS feed: $source
 - date published: 2025-02-25T22:18:21+00:00

<!-- SC_OFF --><div class="md"><p>Anyone been having network issues with 28.0.0? Seem to be having all sorts of issues. </p> <p>Is there a way i can install the previous version? Can&#39;t find any docs anywhere.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juzt4me"> /u/juzt4me </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iy7kx5/v_2800_network_issues/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iy7kx5/v_2800_network_issues/">[comments]</a></span>

## Does Nested Virtualization on macOS give docker room to use GPU passthrough?
 - [https://www.reddit.com/r/docker/comments/1iy2r02/does_nested_virtualization_on_macos_give_docker](https://www.reddit.com/r/docker/comments/1iy2r02/does_nested_virtualization_on_macos_give_docker)
 - RSS feed: $source
 - date published: 2025-02-25T18:58:44+00:00

<!-- SC_OFF --><div class="md"><p>I am going to start this off by saying I am by no means an expert on virtualization or docker, so please correct me if I am wrong.</p> <p>I have a MBP M1 and I am using the Ollama docker image as part of my project. To my surprise the image runs horribly on my computer and is basically unusable. After a lot of research (and pain) I learned that it is because docker does not support GPU passthrough on apple silicon due to apple&#39;s limited virtualization framework. In general, it shocked me that there is not as much discussion on this as I would&#39;ve thought given how popular apple silicon has become for running LLM&#39;s.</p> <p>When looking up solutions I noticed that nested virtualization is not supported for the M1 series chips but is supported starting with the M2 chips. Is docker able to use the nested virtualization capabilities within the new chips to enable GPU passthrough for apple silicon computers?</p> <p>Also if you are an apple silic

## Trying to setup subnet network but can't access it from other hosts on the LAN
 - [https://www.reddit.com/r/docker/comments/1ixz59s/trying_to_setup_subnet_network_but_cant_access_it](https://www.reddit.com/r/docker/comments/1ixz59s/trying_to_setup_subnet_network_but_cant_access_it)
 - RSS feed: $source
 - date published: 2025-02-25T16:32:31+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve created this network on my raspberry pi</p> <pre><code>docker network create --driver macvlan --scope=global --subnet &#39;192.168.124.0/24&#39; --gateway &#39;192.168.124.1&#39; --ip-range &#39;192.168.124.0/24&#39; --aux-address &#39;host=192.168.124.223&#39; --attachable -o parent=wlan0 homelabsetup_frontend </code></pre> <p>and I&#39;m running a nginx reverse proxy docker container on that same pi that connects to the macvlan network</p> <pre><code>nginx_hl: container_name: pihole_lb_hl image: nginx:stable-alpine volumes: - &#39;./nginx.conf:/etc/nginx/conf.d/default.conf&#39; ports: - &quot;80:80&quot; - &quot;53:53&quot; - &quot;443:443/tcp&quot; - &quot;8080:8080&quot; networks: - homelabsetup_frontend depends_on: - pihole_hl networks: homelabsetup_frontend: name: homelabsetup_frontend driver: macvlan external: true </code></pre> <p>but when I try to query it from my PC, using the ip address assigned to the container. I get nothing. I

## docker process cpu usage
 - [https://www.reddit.com/r/docker/comments/1ixx8gg/docker_process_cpu_usage](https://www.reddit.com/r/docker/comments/1ixx8gg/docker_process_cpu_usage)
 - RSS feed: $source
 - date published: 2025-02-25T15:11:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently running one docker container. (docker ps only shows one too) Using --net=host. If I look in the container and run top, it is basically idle. iostat says 94% idle.</p> <p>When I run top on the host, it shows TWO docker process at the top using over 200% cpu each. dockerd seems relatively idle.</p> <p>Why are there two docker processes?<br/> How can I investigate the cause of this high CPU usage while my container seems to be idle?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/eng33"> /u/eng33 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixx8gg/docker_process_cpu_usage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixx8gg/docker_process_cpu_usage/">[comments]</a></span>

## Best IPTV Provider for 2025 – Top Picks Streaming Services & Honest Reviews
 - [https://www.reddit.com/r/docker/comments/1ixv40s/best_iptv_provider_for_2025_top_picks_streaming](https://www.reddit.com/r/docker/comments/1ixv40s/best_iptv_provider_for_2025_top_picks_streaming)
 - RSS feed: $source
 - date published: 2025-02-25T13:35:15+00:00

<!-- SC_OFF --><div class="md"><p>Finding the best IPTV provider in 2025 can be overwhelming, but <strong>Gotivi4k</strong> stands out as the top choice for reliable, high-quality streaming and 24/7 support.</p> <p><strong>Why</strong> <a href="http://Gotivi4k.com"><strong>Gotivi4k.com</strong></a> <strong>is the #1 IPTV Provider in 2025:</strong></p> <ul> <li><strong>40,000+ Live Channels</strong> – Watch global sports, news, entertainment, and premium networks from the USA, UK, Canada, and Europe.</li> <li><strong>100,000+ VOD (Movies &amp; TV Shows)</strong> – Access a huge library of on-demand content, including the latest blockbusters and TV series.</li> <li><strong>4K &amp; FHD Streaming with Anti-Freeze Tech</strong> – Enjoy ultra-HD streaming with no buffering or lag.</li> <li><strong>99.9% Uptime &amp; Stable Servers</strong> – High-quality servers ensure uninterrupted streaming.</li> <li><strong>Multi-Device Compatibility</strong> – Works on Firestick, Android, iOS, Smart T

## How to create a simple ubuntu docker with ssh capability?
 - [https://www.reddit.com/r/docker/comments/1ixu5re/how_to_create_a_simple_ubuntu_docker_with_ssh](https://www.reddit.com/r/docker/comments/1ixu5re/how_to_create_a_simple_ubuntu_docker_with_ssh)
 - RSS feed: $source
 - date published: 2025-02-25T12:46:54+00:00

<!-- SC_OFF --><div class="md"><p>I tried multiple ways but didn&#39;t seem to work. I am planning to run it on my truenas scale server, so that I can ssh into it for programming on vscode.</p> <p>Please help me ( a dockerfile example is much appreciated).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/unstablemamba"> /u/unstablemamba </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixu5re/how_to_create_a_simple_ubuntu_docker_with_ssh/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixu5re/how_to_create_a_simple_ubuntu_docker_with_ssh/">[comments]</a></span>

## Dockerfile stock / default labels
 - [https://www.reddit.com/r/docker/comments/1ixttds/dockerfile_stock_default_labels](https://www.reddit.com/r/docker/comments/1ixttds/dockerfile_stock_default_labels)
 - RSS feed: $source
 - date published: 2025-02-25T12:27:52+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve looked all over the documentation, so I&#39;m going to feel stupid if I missed it.</p> <p>But is their a posted list of the &quot;out of box&quot; labels utilized for docker images? I know that registries like Github use labels such as:</p> <p><code> LABEL org.opencontainers.image.description=&quot;&quot; </code></p> <p>But I can&#39;t seem to locate any lists so that I&#39;m not making my own and re-inventing the wheel.</p> <hr/> <p><strong>Edit</strong>: Apparently the reason I could not find anything in my searches is because I was using the wrong terminology. So in case anyone else has this issue.</p> <p>There appears to be two main specs:</p> <ul> <li>Docker Image Manifest</li> <li>Open Container Initiative (OCI) Specifications</li> </ul> <p>Registries like Github GHCR support both.</p> <p>The OpenContainer spec can be found at: <a href="https://github.com/opencontainers/image-spec/blob/main/annotations.md">https://github.com/opencontai

## Best IPTV Provider for 2025 – Top Picks Streaming Services & Honest Reviews
 - [https://www.reddit.com/r/docker/comments/1ixso64/best_iptv_provider_for_2025_top_picks_streaming](https://www.reddit.com/r/docker/comments/1ixso64/best_iptv_provider_for_2025_top_picks_streaming)
 - RSS feed: $source
 - date published: 2025-02-25T11:17:46+00:00

<!-- SC_OFF --><div class="md"><p>Finding the <strong>best IPTV provider</strong> in 2025 can be overwhelming with so many options available. After testing multiple services, I found that <a href="http://Zylocast.com"><strong>Zylocast.com</strong></a> stands out as the most <strong>reliable, high-quality IPTV service</strong> for those who want <strong>buffer-free streaming, a massive content library, and 24/7 support</strong>.</p> <h1>Why Zylocast .com is the #1 IPTV Provider?</h1> <p>Here’s what makes <strong>Zylocast .com</strong> a top-tier IPTV service in 2025:</p> <p>✔ <strong>Over 40,000 Live Channels</strong> – Enjoy <strong>sports, news, entertainment, and premium networks</strong> from all over the world, including the USA, UK, Canada, and Europe.<br/> ✔ <strong>100,000+ VOD (Movies &amp; TV Shows)</strong> – Access an extensive library of <strong>on-demand content, including the latest blockbusters and TV series</strong>.<br/> ✔ <strong>4K &amp; FHD Streaming with Anti-Fre

## Running docker containers as non root user
 - [https://www.reddit.com/r/docker/comments/1ixrpwt/running_docker_containers_as_non_root_user](https://www.reddit.com/r/docker/comments/1ixrpwt/running_docker_containers_as_non_root_user)
 - RSS feed: $source
 - date published: 2025-02-25T10:13:17+00:00

<!-- SC_OFF --><div class="md"><p>Yet another post on how to make containers work with non root user. I have done some homework reading plenty of posts here and trial &amp; error testing out various things on on my own way but still struggling, so looking for better guidance.</p> <p>I&#39;m setting up a SBC running Dietpi and my setup so far:</p> <p>&gt; Docker instance running as normal (not rootless). From reading many posts, I&#39;m ok to have docker daemon running as root. I want to focus on running containers as non root user for better security.</p> <p>&gt; Created a non-root user with login, UID/GID as 1001.</p> <p>&gt; Added user to docker group as well.</p> <p>&gt; Added &quot;user: 1001:1001&quot; as parameter in docker compose.</p> <p>&gt; For containers that need persistent data storage (e.g. postgres), I created base folders first with non root user&#39;s account and mapped as bind volume.</p> <p>My problem is that on running container (with official images from docker h

## Top IPTV Service Providers for 2025 Honest Reviews & Best Picks
 - [https://www.reddit.com/r/docker/comments/1ixmcsu/top_iptv_service_providers_for_2025_honest](https://www.reddit.com/r/docker/comments/1ixmcsu/top_iptv_service_providers_for_2025_honest)
 - RSS feed: $source
 - date published: 2025-02-25T04:15:35+00:00

<!-- SC_OFF --><div class="md"><p>Are you searching for the <strong>best IPTV service in 2025</strong>? Want to stream live TV, sports, movies, and international channels without the high costs of cable? IPTV (Internet Protocol Television) is the ultimate way to access thousands of channels and on-demand content at a budget-friendly price.</p> <p>With so many providers out there, picking a reliable IPTV service can be tough. That’s why we’ve reviewed and ranked the <strong>top IPTV services for 2025</strong>, considering factors like channel variety, pricing, streaming quality, and customer satisfaction.</p> <h1>🔥 Best IPTV Subscription Services for 2025</h1> <h1>🚀 <a href="http://gotivi4k.com">Gotivi4k </a>– Best Overall IPTV Service</h1> <p>✔️ 33,000+ live TV channels &amp; 80,000+ VOD (Movies &amp; Series)<br/> ✔️ 4K Ultra HD streaming with anti-freeze technology<br/> ✔️ Works with Firestick, Smart TVs, Android, Windows, and iOS<br/> ✔️ Affordable monthly &amp; yearly subscription

## Moving Container to another windows drive
 - [https://www.reddit.com/r/docker/comments/1ixm5ba/moving_container_to_another_windows_drive](https://www.reddit.com/r/docker/comments/1ixm5ba/moving_container_to_another_windows_drive)
 - RSS feed: $source
 - date published: 2025-02-25T04:04:11+00:00

<!-- SC_OFF --><div class="md"><p>Looking at this, it seems like it should be just that simple.</p> <p>Click container, click the compose stack for immich - it says it&#39;s at c:\immich.app</p> <p>I want to move it to f:\immich.app but I&#39;m baffled why I can&#39;t just pick that entire folder up and/or tell Docker directly where that now lives.</p> <p>What am I missing?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Redwhiteandmaple"> /u/Redwhiteandmaple </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixm5ba/moving_container_to_another_windows_drive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixm5ba/moving_container_to_another_windows_drive/">[comments]</a></span>

## Best IPTV Services of 2025 – IPTV VIVO Delivers Premium Streaming
 - [https://www.reddit.com/r/docker/comments/1ixm4hg/best_iptv_services_of_2025_iptv_vivo_delivers](https://www.reddit.com/r/docker/comments/1ixm4hg/best_iptv_services_of_2025_iptv_vivo_delivers)
 - RSS feed: $source
 - date published: 2025-02-25T04:02:56+00:00

<!-- SC_OFF --><div class="md"><p>In today’s digital age, IPTV (Internet Protocol Television) has revolutionized how we consume entertainment. With thousands of channels, on-demand movies, and live sports at your fingertips, IPTV is the future of TV. But with so many providers out there, how do you choose the best one? Look no further than <strong>IPTV VIVO</strong>, a top-tier service that’s redefining the streaming experience.</p> <h1>➡️Why <a href="https://iptvvivo.com/">IPTV VIVO</a> is the Best IPTV Provider in 2025</h1> <p><strong>1. Unmatched Channel Selection</strong><br/> With <strong>over 45,000 live channels</strong>, IPTV VIVO offers something for everyone – from sports and news to international programming and kids&#39; content.</p> <p><strong>2. Massive Video-On-Demand Library</strong><br/> Access <strong>160,000+ movies and TV shows</strong> in HD and 4K quality. Whether you’re into the latest blockbusters or classic films, IPTV VIVO has you covered.</p> <p><strong>3. 

## What’s the best Pandabuy alternative?
 - [https://www.reddit.com/r/docker/comments/1ixlk39/whats_the_best_pandabuy_alternative](https://www.reddit.com/r/docker/comments/1ixlk39/whats_the_best_pandabuy_alternative)
 - RSS feed: $source
 - date published: 2025-02-25T03:33:33+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ADMIN-TEXTBOOK"> /u/ADMIN-TEXTBOOK </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixlk39/whats_the_best_pandabuy_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixlk39/whats_the_best_pandabuy_alternative/">[comments]</a></span>

## Best IPTV Service Providers for 2025 – Honest Reviews & Top Picks
 - [https://www.reddit.com/r/docker/comments/1ixkudq/best_iptv_service_providers_for_2025_honest](https://www.reddit.com/r/docker/comments/1ixkudq/best_iptv_service_providers_for_2025_honest)
 - RSS feed: $source
 - date published: 2025-02-25T02:57:49+00:00

<!-- SC_OFF --><div class="md"><p>🔥 Top-Rated IPTV Subscription Services for 2025</p> <h1>🚀 <a href="https://gotivi4k.com/">Gotivi4k</a> – Best Overall IPTV Service</h1> <p>✔️ Over 33,000 live TV channels &amp; 80,000+ VOD (Movies &amp; Series)✔️ 4K Ultra HD streaming with anti-freeze technology✔️ Compatible with Firestick, Smart TV, Android, Windows, and iOS✔️ Affordable monthly &amp; yearly IPTV subscription plans</p> <p>🌟 <a href="https://tiviorbit.com/">Tiviorbit</a> – Best IPTV for Sports Fans</p> <p>✔️ 22,000+ sports &amp; international channels✔️ 4K/HD IPTV streaming with EPG (Electronic Program Guide) support✔️ Fast IPTV servers for seamless streaming✔️ Catch-Up TV &amp; EPG available</p> <p>📺 <a href="https://catchon.tv/">catchon tv</a> – Best IPTV for Multi-Device Users</p> <p>✔️ 18,000+ live channels &amp; 90,000+ VOD titles✔️ Supports up to 5 devices simultaneously✔️ Ideal for families &amp; multiple users</p> <p>🌍 Meilleur IPTV – Best IPTV for International Channels</p> 

## Best Rep Agent According to Reddit for 2025?
 - [https://www.reddit.com/r/docker/comments/1ixkj45/best_rep_agent_according_to_reddit_for_2025](https://www.reddit.com/r/docker/comments/1ixkj45/best_rep_agent_according_to_reddit_for_2025)
 - RSS feed: $source
 - date published: 2025-02-25T02:42:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ChernoAlpha97"> /u/ChernoAlpha97 </a> <br/> <span><a href="/r/RepKiosk/comments/1ixf6d7/best_private_agent_according_to_reddit_for_2025/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixkj45/best_rep_agent_according_to_reddit_for_2025/">[comments]</a></span>

## The Best Rep Agents for 2025 – "Top Ranked" (Honest Review)
 - [https://www.reddit.com/r/docker/comments/1ixkapp/the_best_rep_agents_for_2025_top_ranked_honest](https://www.reddit.com/r/docker/comments/1ixkapp/the_best_rep_agents_for_2025_top_ranked_honest)
 - RSS feed: $source
 - date published: 2025-02-25T02:30:39+00:00

<!-- SC_OFF --><div class="md"><p>Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MyHatIsAPigeon"> /u/MyHatIsAPigeon </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixkapp/the_best_rep_agents_for_2025_top_ranked_honest/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixkapp/the_best_rep_agents_for_2025_top_ranked_honest/">[comments]</a></span>

## Now that this sub is about IPTV, what is a good one to stream in market MLB games?
 - [https://www.reddit.com/r/docker/comments/1ixjoxa/now_that_this_sub_is_about_iptv_what_is_a_good](https://www.reddit.com/r/docker/comments/1ixjoxa/now_that_this_sub_is_about_iptv_what_is_a_good)
 - RSS feed: $source
 - date published: 2025-02-25T02:01:17+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a IPTV provider for in market MLB games, and this sub seems to be the new leading expert on the topic.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/heydroid"> /u/heydroid </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ixjoxa/now_that_this_sub_is_about_iptv_what_is_a_good/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ixjoxa/now_that_this_sub_is_about_iptv_what_is_a_good/">[comments]</a></span>

