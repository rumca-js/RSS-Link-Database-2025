# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Share NAS folder to external endpoint
 - [https://www.reddit.com/r/selfhosted/comments/1hxpof9/share_nas_folder_to_external_endpoint](https://www.reddit.com/r/selfhosted/comments/1hxpof9/share_nas_folder_to_external_endpoint)
 - RSS feed: $source
 - date published: 2025-01-09T22:51:42+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a tool that would have access to SMB folders, where I can create a shared folder to the internet on the browser.</p> <p>Thinking of a web app that will proxy my network shared folders and files on demand to external users without having to expose my NAS to the internet.</p> <p>Is there such a tool? Ideally, the tool would allow me to set a password to that external share link or something like that, but I&#39;m ok if even basic functionality is available!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dsv591"> /u/dsv591 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpof9/share_nas_folder_to_external_endpoint/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpof9/share_nas_folder_to_external_endpoint/">[comments]</a></span>

## Cloudflared - Tunnel - Redirect subdomain to folder
 - [https://www.reddit.com/r/selfhosted/comments/1hxpo83/cloudflared_tunnel_redirect_subdomain_to_folder](https://www.reddit.com/r/selfhosted/comments/1hxpo83/cloudflared_tunnel_redirect_subdomain_to_folder)
 - RSS feed: $source
 - date published: 2025-01-09T22:51:27+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m setting up cloudflared to act as a reverse proxy and i&#39;ve got almost everything working fine.. except for one url.</p> <p>I need <a href="https://sql.domain.co.uk">https://sql.domain.co.uk</a> to actually append /phpmyadmin to the end of it.</p> <p>i though ti could do this with rules on the domain but i keep ending up with the too many redirects errors..</p> <p>does anyone have any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/d4nm3d"> /u/d4nm3d </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpo83/cloudflared_tunnel_redirect_subdomain_to_folder/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpo83/cloudflared_tunnel_redirect_subdomain_to_folder/">[comments]</a></span>

## Bookstack and mariad from Linux server ate it today.
 - [https://www.reddit.com/r/selfhosted/comments/1hxpi0i/bookstack_and_mariad_from_linux_server_ate_it](https://www.reddit.com/r/selfhosted/comments/1hxpi0i/bookstack_and_mariad_from_linux_server_ate_it)
 - RSS feed: $source
 - date published: 2025-01-09T22:43:43+00:00

<!-- SC_OFF --><div class="md"><p>I noticed I had a update to the mariad container and ran it, checked the logs and I needed to do a DB upgrade via the command. Ran it and ever since bookstack is returning a 502 response. Both maria and bookstack container logs look normal so I am not sure what happened here. Is anyone else having issues?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpi0i/bookstack_and_mariad_from_linux_server_ate_it/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxpi0i/bookstack_and_mariad_from_linux_server_ate_it/">[comments]</a></span>

## How the heck do you do SMTP for a scanner so I can scan something to my email?
 - [https://www.reddit.com/r/selfhosted/comments/1hxorkc/how_the_heck_do_you_do_smtp_for_a_scanner_so_i](https://www.reddit.com/r/selfhosted/comments/1hxorkc/how_the_heck_do_you_do_smtp_for_a_scanner_so_i)
 - RSS feed: $source
 - date published: 2025-01-09T22:11:15+00:00

<!-- SC_OFF --><div class="md"><p>Basically the title. I bought a new scanner recently and can scan to a directory for Paperless but I can&#39;t scan and have it email the scan to us, which my wife really wants.</p> <p>I&#39;ve been trying to just use Google, but it looks like you need a Google Workspace to do it? Then I tried to spin up Stalwart, but am lost on configured Namecheap to allow it.</p> <p>Is this really this complicated? Am I missing something easy?</p> <p>Thanks in advanced!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Some_guitarist"> /u/Some_guitarist </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxorkc/how_the_heck_do_you_do_smtp_for_a_scanner_so_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxorkc/how_the_heck_do_you_do_smtp_for_a_scanner_so_i/">[comments]</a></span>

## Changing Container Hostname After The Fact
 - [https://www.reddit.com/r/selfhosted/comments/1hxo1k3/changing_container_hostname_after_the_fact](https://www.reddit.com/r/selfhosted/comments/1hxo1k3/changing_container_hostname_after_the_fact)
 - RSS feed: $source
 - date published: 2025-01-09T21:39:51+00:00

<!-- SC_OFF --><div class="md"><p>Scenario: I install snippet box with docker run thusly:</p> <pre><code>docker run -d --name=snippet_box \ -p 5212:5000 \ -v /volume1/docker/snippetbox:/app/data \ --restart always \ pawelmalak/snippet-box </code></pre> <p>However, what I neglected to do was add the -h switch thusly:</p> <pre><code>docker run -d --name=snippet_box \ -p 5212:5000 \ -v /volume1/docker/snippetbox:/app/data \ -h --restart always \ pawelmalak/snippet-boxsnippetbox.myreallycooldomain.duckdns.org </code></pre> <p>Is it possible to set a new hostname other than the one docker automatically assigns, after installing the container? The image still remains intact. It would seem that I should be able to re-pull with a new hostname.</p> <p>Could you use something like:</p> <p><code>sudo nano /var/lib/docker/containers/CONTAINER_ID/config.json</code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wild_Magician_4508"> /u/Wild_Magician_4508 </a

## Logging DNS and other traffic
 - [https://www.reddit.com/r/selfhosted/comments/1hxnzd4/logging_dns_and_other_traffic](https://www.reddit.com/r/selfhosted/comments/1hxnzd4/logging_dns_and_other_traffic)
 - RSS feed: $source
 - date published: 2025-01-09T21:37:11+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone have a good solution for recording DNS logs? Or any traffic logs, for that matter? I&#39;m using UniFi as my DNS server and I would love them to have this as a feature. I have been switching a couple places that I manage to UniFi gateways, but I also come from the Fortinet world where their stuff does a great job at giving you a log of traffic and what websites were hit. I do a lot in terms of web filtering and people are asking me now and then to open up websites or &quot;this website is acting goofy&quot; and it turns out it&#39;s cause a domain within the website was blocked. I don&#39;t even really know how to gather that information well when using UniFi. I know using an out of band solution wouldn&#39;t always help pinpoint the specific issue since it wouldn&#39;t be integrated into my wifi controller, but perhaps if I had a timestamp, that would help me know what to do within UniFi. I know PiHole and other software is a thing where

## how to make ddns update ip address instantly?
 - [https://www.reddit.com/r/selfhosted/comments/1hxngdc/how_to_make_ddns_update_ip_address_instantly](https://www.reddit.com/r/selfhosted/comments/1hxngdc/how_to_make_ddns_update_ip_address_instantly)
 - RSS feed: $source
 - date published: 2025-01-09T21:14:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello<br/> I have an ubuntu server running and installed ddclient on it and use duckdns for ddns.<br/> the default setting for ddclient is to update ip every 5 minutes if the ip is changed.<br/> Is there a way to make it update the ip instantly instead? I ask this because if I self host my website on it and it takes 5 minutes for the ddclient to update the ip, that means I have 5 minutes of downtime and I wanna avoid that.</p> <p>Also I know it is possible to change the ddlclient config file so it refreshes more often. but is that the best way?(performance wise)<br/> Is this gonna slow down my server if I make it check for the ip and if the ip of my server is changed then it runs the ddclient or just calls duckdns update api?</p> <p>Thanks for any help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TemporaryConfusion53"> /u/TemporaryConfusion53 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comm

## Self Hosted Simplified
 - [https://www.reddit.com/r/selfhosted/comments/1hxmyp4/self_hosted_simplified](https://www.reddit.com/r/selfhosted/comments/1hxmyp4/self_hosted_simplified)
 - RSS feed: $source
 - date published: 2025-01-09T20:53:18+00:00

<!-- SC_OFF --><div class="md"><p>For those who want to take control of their data, organize things and self host some of the most amazing applications........I have created a simple repository (<a href="https://github.com/pranjulsingh/self-hosted-simplified">self-hosted-simplified</a>)........that can help you in quickly setting up your self hosted server with the following applications:</p> <ul> <li>Cloudflared: <ul> <li>Cloudflare Tunnel to connect securely connect to the home network and access different services.</li> </ul></li> <li>Samba Share: <ul> <li>A <em>Samba</em> file server enables file <em>sharing</em> across different operating systems over a network.</li> <li>I am using this to mount the shared storage drives to different devices connected in my home network.</li> </ul></li> <li>FileBrowser: <ul> <li>Lightweight web based file explorer.</li> <li>I am using this to access and share the files with fiends and family over the internet.</li> </ul></li> <li>Nextcloud: <ul>

## Movie Roulette v3.2 released!
 - [https://www.reddit.com/r/selfhosted/comments/1hxmso7/movie_roulette_v32_released](https://www.reddit.com/r/selfhosted/comments/1hxmso7/movie_roulette_v32_released)
 - RSS feed: $source
 - date published: 2025-01-09T20:46:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hxmso7/movie_roulette_v32_released/"> <img src="https://b.thumbs.redditmedia.com/7nRYKLJVGEFvZYoQebPW4dG7T4tIGY-MJAAQc9wLenI.jpg" alt="Movie Roulette v3.2 released!" title="Movie Roulette v3.2 released!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey!</p> <p>I just realesed a new version of Movie Roulette! Here the last post:</p> <p><a href="https://www.reddit.com/r/PleX/comments/1h3nvju/movie_roulette_v30_released/">https://www.reddit.com/r/PleX/comments/1h3nvju/movie_roulette_v30_released/</a></p> <p>Github: <a href="https://github.com/sahara101/Movie-Roulette">https://github.com/sahara101/Movie-Roulette</a></p> <p>What is Movie Roulette?</p> <p>At its core it is a docker container which chooses a random movie from your Plex/Jellyfin/Emby movie libraries.</p> <p>You can install it either as a docker container or as a macOS dmg.</p> <p>What is new in v3.2?</p> <p>ENV BREAKING CHANGES:</p> <p>Deprecated 

## Digesto: A Lightning-Fast Way to Build Backends with YAML
 - [https://www.reddit.com/r/selfhosted/comments/1hxmqwr/digesto_a_lightningfast_way_to_build_backends](https://www.reddit.com/r/selfhosted/comments/1hxmqwr/digesto_a_lightningfast_way_to_build_backends)
 - RSS feed: $source
 - date published: 2025-01-09T20:44:05+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been there—spending hours setting up a backend when all I wanted was to focus on the frontend. Enter <strong>Digesto</strong>, a tool that lets you define your data model in a YAML file and watch as it does the heavy lifting, spinning up a backend for you. </p> <p>Let’s explore how this experimental Node.js library simplifies backend development for frontend devs like you. You can find the project on GitHub at <a href="https://github.com/nicolasleal570/digesto">Digesto</a>.</p> <h2>What is Digesto?</h2> <p>At its core, <strong>Digesto</strong> is a time-saver. It’s designed for frontend developers who’d rather not wrestle with backend complexities. By writing a simple YAML file, you can auto-generate RESTful APIs for your app in just a few steps. No boilerplate, no fuss—just results.</p> <h2>Why Should You Care?</h2> <p>Here’s the deal: Digesto takes care of the backend so you can focus on what you’re good at—creating beautiful, functional front

## Sunshine and moonlight + tailscale is amazing i get 60-70ms latency on my friend pc i playing gta 5 feels like native ... Distance b/w them is 1212 km
 - [https://www.reddit.com/r/selfhosted/comments/1hxja3p/sunshine_and_moonlight_tailscale_is_amazing_i_get](https://www.reddit.com/r/selfhosted/comments/1hxja3p/sunshine_and_moonlight_tailscale_is_amazing_i_get)
 - RSS feed: $source
 - date published: 2025-01-09T18:18:41+00:00

<!-- SC_OFF --><div class="md"><p>Man it is amzing i cant imagine these both software is free</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NoIron5038"> /u/NoIron5038 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxja3p/sunshine_and_moonlight_tailscale_is_amazing_i_get/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxja3p/sunshine_and_moonlight_tailscale_is_amazing_i_get/">[comments]</a></span>

## Distributed Networking for Home Server Cluster Behind Residential Networks (Germany)
 - [https://www.reddit.com/r/selfhosted/comments/1hxiydp/distributed_networking_for_home_server_cluster](https://www.reddit.com/r/selfhosted/comments/1hxiydp/distributed_networking_for_home_server_cluster)
 - RSS feed: $source
 - date published: 2025-01-09T18:04:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m working on setting up a distributed home server cluster, with nodes spread across multiple remote locations, primarily behind residential networks in Germany. My goal is to run services (e.g., Kubernetes) that are publicly reachable on the internet, but I don’t have access to a public IPv6/IPv4 subnet at home. I’d like the solution to be as distributed as possible.</p> <p>Here are the options I’ve considered so far:</p> <ol> <li><strong>Get an ASN and IPv6 Subnet</strong>: <ul> <li>Announce public IPv6 addresses from my home cluster and other locations.</li> <li>Assign public IPv6 addresses to each pod/service.</li> <li>Use anycast for load balancing.</li> <li><strong>Concerns</strong>: Complex setup, costs, and working with ISPs for BGP announcements.</li> </ul></li> <li><strong>Set Up a Mesh Network with Tools Like Netbird</strong>: <ul> <li>Use a public VPS with a static IP as a coordination server.</li> <li>Expose workload

## Docker User PUID/PGID Question
 - [https://www.reddit.com/r/selfhosted/comments/1hxiov9/docker_user_puidpgid_question](https://www.reddit.com/r/selfhosted/comments/1hxiov9/docker_user_puidpgid_question)
 - RSS feed: $source
 - date published: 2025-01-09T17:53:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I&#39;m currently running an OpenMediaVault server with a few docker containers that I use to organize and serve media, some of which are exposed to the internet behind an nginx reverse proxy and require authentication.</p> <p>Recently, I&#39;ve just noticed that <strong>the user running internally in all of my containers seems to be root</strong>, at least when I check the results of <code>docker exec -it [container] id</code></p> <p>For example:</p> <p>Jellyfin:</p> <p><code>uid=0(root) gid=0(root) groups=0(root)</code></p> <p>SWAG:</p> <p><code>uid=0(root) gid=0(root) groups=0(root),1(bin),2(daemon),3(sys),4(adm),6(disk),10(wheel),11(floppy),20(dialout),26(tape),27(video)</code></p> <p>Sonarr:</p> <p><code>uid=0(root) gid=0(root) groups=0(root),1(bin),2(daemon),3(sys),4(adm),6(disk),10(wheel),11(floppy),20(dialout),26(tape),27(video)</code></p> <p>For context, I am mostly running the linuxserver.io images, in which I followed <a hr

## pivpn through coudflare tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1hxifz4/pivpn_through_coudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1hxifz4/pivpn_through_coudflare_tunnel)
 - RSS feed: $source
 - date published: 2025-01-09T17:43:25+00:00

<!-- SC_OFF --><div class="md"><p>So I have set up a wireguard vpn server on my raspberry pi using pivpn. I have set it up using my domain. Now I want to use cloudflare proxies on that domain (vpn.mydomain.com). When I turn the &quot;proxy&quot; switch on in the cloudflare dashboard my vpn does not work. Has anyone else done this? And what could be the problem? tank you guys in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_armagheadon"> /u/_armagheadon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxifz4/pivpn_through_coudflare_tunnel/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxifz4/pivpn_through_coudflare_tunnel/">[comments]</a></span>

## SSO with Unify Identity Enterprise and Identity Provide middleware?
 - [https://www.reddit.com/r/selfhosted/comments/1hxi6yx/sso_with_unify_identity_enterprise_and_identity](https://www.reddit.com/r/selfhosted/comments/1hxi6yx/sso_with_unify_identity_enterprise_and_identity)
 - RSS feed: $source
 - date published: 2025-01-09T17:32:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey, </p> <p>I&#39;m completely new to doing anything with SSO. I&#39;m planning to set up single sign on for my hosted apps and services. But I have not seen it fully documented the way I intend on using it. </p> <p>I will put down the &#39;user experience&#39;, and please let me know if this is not possible. Especially around Unify Identity, I was not entirely sure if its SSO integration was to sign in to Unifi, or act as an identity provider. The additional middleware is because the free plan for Unifi Identity only covers three SSO apps, so hoping to use a middleware to aggregate as many as I like. </p> <p>User Experience:<br/> - Go to SiteA<br/> - Click login<br/> - Redirect to SSO Middleware<br/> - Redirect to Unify Identity login<br/> - On Success: Callback to SSO Middleware<br/> - Middleware validates the account/email in its system<br/> - On Success: Callback to SiteA</p> <p>I enjoy the simplicity of the Unify Identity login, and the Unify V

## Storage Configuration Conundrum
 - [https://www.reddit.com/r/selfhosted/comments/1hxhx4e/storage_configuration_conundrum](https://www.reddit.com/r/selfhosted/comments/1hxhx4e/storage_configuration_conundrum)
 - RSS feed: $source
 - date published: 2025-01-09T17:21:11+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hxhx4e/storage_configuration_conundrum/"> <img src="https://b.thumbs.redditmedia.com/uVuYLj4tmjmDPOoGPuP0MNFJoEeATSOKKggEn1JwL-g.jpg" alt="Storage Configuration Conundrum" title="Storage Configuration Conundrum" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>TL;DR. Is the accepted wisdom that storage should be connected to one machine that provides NAS functionality or is a SAN/Ceph managed SAN a better idea for redundancy??</p> <p>I have a small home server cluster that started running on Ubuntu Server machines with VMs and Docker containers that I am migrating to Proxmox and LXC containers. It has been a two node Optiplex setup but I&#39;m looking to add a third machine (which one depends on the answer below).</p> <p>Until now the storage has been run through a TrueNAS scale VM with two USB external mirrored HDDs in a ZFS pool. I am looking to make this a bit more robust and as I see it, I have two options

## Does Homepage work well as a Proxmox LXC?
 - [https://www.reddit.com/r/selfhosted/comments/1hxhmcg/does_homepage_work_well_as_a_proxmox_lxc](https://www.reddit.com/r/selfhosted/comments/1hxhmcg/does_homepage_work_well_as_a_proxmox_lxc)
 - RSS feed: $source
 - date published: 2025-01-09T17:08:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m starting to look at setting up a dashboard for my small home server. Would setting up an LXC with the Proxmox Helper Scripts work well for Homepage? How are apps (or instance AdGuard Home) added to Homepage once installed?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tomhusband"> /u/tomhusband </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxhmcg/does_homepage_work_well_as_a_proxmox_lxc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxhmcg/does_homepage_work_well_as_a_proxmox_lxc/">[comments]</a></span>

## What's a good self hosted alternative to Loom?
 - [https://www.reddit.com/r/selfhosted/comments/1hxhcen/whats_a_good_self_hosted_alternative_to_loom](https://www.reddit.com/r/selfhosted/comments/1hxhcen/whats_a_good_self_hosted_alternative_to_loom)
 - RSS feed: $source
 - date published: 2025-01-09T16:56:55+00:00

<!-- SC_OFF --><div class="md"><p>Loom is good, its pricing isn&#39;t</p> <p>what&#39;s a FOOS altenative with comparable features?</p> <p>thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/More_Cherryy"> /u/More_Cherryy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxhcen/whats_a_good_self_hosted_alternative_to_loom/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxhcen/whats_a_good_self_hosted_alternative_to_loom/">[comments]</a></span>

## Guacamole and SSH keys help
 - [https://www.reddit.com/r/selfhosted/comments/1hxgop6/guacamole_and_ssh_keys_help](https://www.reddit.com/r/selfhosted/comments/1hxgop6/guacamole_and_ssh_keys_help)
 - RSS feed: $source
 - date published: 2025-01-09T16:29:24+00:00

<!-- SC_OFF --><div class="md"><p>I am having difficulties trying to use SSH keys with Guacamole <a href="https://krdesigns.com/articles/how-to-install-guacamole-using-docker-step-by-step">hosted in docker containers btw</a>. More specifically, I don&#39;t understand how to generate a key and use it on another machine. I had no issues doing this on my laptop and a server by using <a href="https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-debian-11">this short guide</a>.</p> <p>I&#39;m generating a key on the server, viewing the key with <code>cat</code>, then copying and pasting that output into Guacamole under Private Key. I also put in the IP address, port, and username to be used, but the connection fails. I can log in with a username and password, but I would like to move to keys. What am I doing wrong?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OC_Rookie"> /u/OC_Rookie </a> <br/> <span><a href="https://www.redd

## Which software for my usecase?
 - [https://www.reddit.com/r/selfhosted/comments/1hxgojm/which_software_for_my_usecase](https://www.reddit.com/r/selfhosted/comments/1hxgojm/which_software_for_my_usecase)
 - RSS feed: $source
 - date published: 2025-01-09T16:29:13+00:00

<!-- SC_OFF --><div class="md"><p>Running a cable internet business. Basically reselling top ups for 15% margin. where I have around 300 customers. There are several top ups fixed ones + bandwidth addon. So I want it for 2 things. 1- to log my expenses that I buy top up from my provider. So that at the end of month I know how much exactly I spent. </p> <p>For example customer 1, date, top up, addon. Also pull customers history of top up. Analysis by monthly expenses on top up and by addon.</p> <p>2 - expiry system which shows this customers expiry is coming in next 2 days. Because sometimes I buy 2 months deal and sell on monthly basis.</p> <p>We are doing manual entry in sheet, but it&#39;s hectic. We have to copy rows and paste it in expenses sheets. Enter expiry dates and search those to find who&#39;s expiry is it today.</p> <p>seller didn&#39;t provide any software for this. Because I am just selling top ups like vouchers his system can&#39;t integrate yet</p> </div><!-- SC_ON -

## SFTPGo FTP Server
 - [https://www.reddit.com/r/selfhosted/comments/1hxgnxl/sftpgo_ftp_server](https://www.reddit.com/r/selfhosted/comments/1hxgnxl/sftpgo_ftp_server)
 - RSS feed: $source
 - date published: 2025-01-09T16:28:28+00:00

<!-- SC_OFF --><div class="md"><p>Hallo, ich habe in Docker SFTPGo installiert, um einen FTP Server für eine IP Cam aufzubauen. Nun heisst es in der Weboberfläche unter Status, dass FTP deaktiviert ist. Wie bekomme ich diesen zum laufen? Laut Anleitung muss eine Konfigurationsdatei bearbeitet werden, ich finde aber nichtmal das Verzeichnis (etc/sftpgo). Kann das nicht irgendwie in der Oberfläche aktiviert werden? Vielen Dank.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Careful-Jicama-3349"> /u/Careful-Jicama-3349 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxgnxl/sftpgo_ftp_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxgnxl/sftpgo_ftp_server/">[comments]</a></span>

## Seeking advice on backup plan...
 - [https://www.reddit.com/r/selfhosted/comments/1hxgmv2/seeking_advice_on_backup_plan](https://www.reddit.com/r/selfhosted/comments/1hxgmv2/seeking_advice_on_backup_plan)
 - RSS feed: $source
 - date published: 2025-01-09T16:27:09+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m at a point where I have to make a change in my backup strategy.</p> <p>Currently, my backups are handled by a small Debian Linux box (remote-A) at a friend&#39;s home, she&#39;s port forwarding one port to it for SSH, it&#39;s configured to only allow a single user, and requires ed25519 keys on a non-default port. They have a dynamic IP and remote-A updates DDNS if the IP changes - it doesn&#39;t do that much.</p> <p>I do my off-site backups via rsync and cron jobs twice daily, and it has worked perfectly for years. She lives near me, so if there was a catastrophe, I could drive to her house and recover the whole machine in twenty minutes. Remote-A is not encrypted, I trust her not to play with the machine, and I doubt she&#39;d ever bother to hook up a monitor and keyboard to it. But, she&#39;s getting married, and will almost certainly be moving further away.</p> <p>The data (about 4 TB) is e-mail as individual files and two of the accounts

## Gitlab + Big Repos + CloudFlare?
 - [https://www.reddit.com/r/selfhosted/comments/1hxgi9x/gitlab_big_repos_cloudflare](https://www.reddit.com/r/selfhosted/comments/1hxgi9x/gitlab_big_repos_cloudflare)
 - RSS feed: $source
 - date published: 2025-01-09T16:21:57+00:00

<!-- SC_OFF --><div class="md"><p>Long story short: I spent a few aggravating days hunting down why just ONE repo on my local Gitlab instance behind CloudFlare would constantly throw out RPC Failure 413 - Unexpected Hang Up.</p> <p>Turns out it is CloudFlares free plan, they restrict transfers to a specific max size (100mb+, I never bothered to pin down the exact number.)</p> <p>So; anyone have a solution to big repos behind cloudflare? Paying $20/mo is untenable for what I am doing.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wonderful_Fail_8253"> /u/Wonderful_Fail_8253 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxgi9x/gitlab_big_repos_cloudflare/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxgi9x/gitlab_big_repos_cloudflare/">[comments]</a></span>

## Tandoor - fresh install - database "recipes" does not exist
 - [https://www.reddit.com/r/selfhosted/comments/1hxgfm6/tandoor_fresh_install_database_recipes_does_not](https://www.reddit.com/r/selfhosted/comments/1hxgfm6/tandoor_fresh_install_database_recipes_does_not)
 - RSS feed: $source
 - date published: 2025-01-09T16:19:00+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m not sure if this is the right place to ask exactly but there are other questions about Tandoor here so hopefully it is.</p> <p>I&#39;ve just done a fresh install on my Unraid device. I already have a postgres db container in there, so I set it up connecting to that container with the right username and password but on trying to access the web UI I get this. I mean, I assume it doesn&#39;t exist because it is a fresh install, but can it not add the db for itself? How can I add the db so it can work?</p> <h1>OperationalError at /</h1> <pre><code>connection to server at &quot;x.x.x.x&quot;, port 5433 failed: FATAL: database &quot;recipes&quot; does not exist </code></pre> <table><thead> <tr> <th align="left">Request Method:</th> <th align="left">GET</th> </tr> </thead><tbody> <tr> <td align="left">Request URL:</td> <td align="left"><a href="http://10.92.1.49:8154/">http://10.92.1.49:8154/</a></td> </tr> <tr> <td align="left">Django Version:<

## Is Crowdsec inflating their numbers, or is my site just very exposed? (2024 wrap up numbers)
 - [https://www.reddit.com/r/selfhosted/comments/1hxgexc/is_crowdsec_inflating_their_numbers_or_is_my_site](https://www.reddit.com/r/selfhosted/comments/1hxgexc/is_crowdsec_inflating_their_numbers_or_is_my_site)
 - RSS feed: $source
 - date published: 2025-01-09T16:18:10+00:00

<!-- SC_OFF --><div class="md"><p>So This is the first year in 2-3 of self hosting a public domain where I setup crowdsec bouncer with traefik. I signed up for the free service, and added in a a few of the more popular block lists.</p> <p>This year&#39;s review says...</p> <blockquote> <p>You reported 3053 attacks, placing you in the top 19% of active organizations. You&#39;re on top of things. </p> <p>You identified 430 distinct IPs, ranking you in the top 30% for unique attackers met.</p> <p>Your most eventful day was the 9th of November , with 21 unique attackers, ranking you in the top 23% most targeted organizations for this specific day.</p> <p>Most of your reports were about HTTP Exploit , accounting for 74.88% of attacks and placing you in the top 15% defenders against this behavior.</p> </blockquote> <p>This looks... insane? My site is &#39;private&#39; as in I don&#39;t post the URL online, only shared with friends to do plex requests and automatic inviting, and family to s

## selfhosted application for your smart-gate
 - [https://www.reddit.com/r/selfhosted/comments/1hxg4r9/selfhosted_application_for_your_smartgate](https://www.reddit.com/r/selfhosted/comments/1hxg4r9/selfhosted_application_for_your_smartgate)
 - RSS feed: $source
 - date published: 2025-01-09T16:06:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hxg4r9/selfhosted_application_for_your_smartgate/"> <img src="https://b.thumbs.redditmedia.com/c05SUalDDTQA1UvUSEpfrDV0YEAuu_-Uf7JV_pQSKBM.jpg" alt="selfhosted application for your smart-gate" title="selfhosted application for your smart-gate" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spare_Tomorrow9091"> /u/Spare_Tomorrow9091 </a> <br/> <span><a href="https://www.reddit.com/gallery/1hxg4r9">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxg4r9/selfhosted_application_for_your_smartgate/">[comments]</a></span> </td></tr></table>

## System for medicines inventory
 - [https://www.reddit.com/r/selfhosted/comments/1hxfsvu/system_for_medicines_inventory](https://www.reddit.com/r/selfhosted/comments/1hxfsvu/system_for_medicines_inventory)
 - RSS feed: $source
 - date published: 2025-01-09T15:52:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Im looking for system that would allow me to create inventory of medicines at my home. It doesn&#39;t have to do much, it can be something grocy-alike, which would allow to keep track of medicines at home. Main functions: keep track of place where is medicine stored and expiration date. Do you know if something like this exists?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheGreatShanel"> /u/TheGreatShanel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxfsvu/system_for_medicines_inventory/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxfsvu/system_for_medicines_inventory/">[comments]</a></span>

## Accessing wireguard behind CGNAT
 - [https://www.reddit.com/r/selfhosted/comments/1hxfdw5/accessing_wireguard_behind_cgnat](https://www.reddit.com/r/selfhosted/comments/1hxfdw5/accessing_wireguard_behind_cgnat)
 - RSS feed: $source
 - date published: 2025-01-09T15:34:05+00:00

<!-- SC_OFF --><div class="md"><p>Wireguard server behinf CGNAT</p> <p>Hello. I am trying to set a wireguard server at home, so i can connect to it and access my self hosted services remotely.</p> <p>TL;DR : It doesn&#39;t work :(</p> <p>I think it is because my ISP uses CGNAT.</p> <p>Quick explanation :</p> <p>My home network is like this : ISP Huawei router (Optic fiber) -&gt; TP Link Deco Mesh -&gt; all my home devices including a Container in a Proxmos machine where Wiregurad is running as server.</p> <p>I did port forwarding in both the Deco Mesh, and the isp huawei router.</p> <p>If i am connected to the (mesh) Wifi (from cell phone, for example) and connect the wireguard client to the deco/mesh ip and wireguard port, it connects successfully to the Wireguard server. So i know the forwarding rule in the Deco mesh is working.</p> <p>But, if i try to connect externally, to the public ip, it don&#39;t work.</p> <p>For what i was investigating, the problem is i am behind a CGNAT.</

## Error when loading dashing dashboard on RP3
 - [https://www.reddit.com/r/selfhosted/comments/1hxf8kk/error_when_loading_dashing_dashboard_on_rp3](https://www.reddit.com/r/selfhosted/comments/1hxf8kk/error_when_loading_dashing_dashboard_on_rp3)
 - RSS feed: $source
 - date published: 2025-01-09T15:27:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hxf8kk/error_when_loading_dashing_dashboard_on_rp3/"> <img src="https://b.thumbs.redditmedia.com/WBVLA7bqQq_mAZmAh8YZynqsffkiz853xtydwAvisbY.jpg" alt="Error when loading dashing dashboard on RP3" title="Error when loading dashing dashboard on RP3" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi,</p> <p>This is my first time to setup Dashy Dashboard, I keep having errors with this setup. Please see picture and logs below and please let me know how I fix it?</p> <p><a href="https://preview.redd.it/v9j9h7hukzbe1.png?width=1364&amp;format=png&amp;auto=webp&amp;s=3d7869cfc4054b52795610a48d1d15e27233b0a8">Dashy docker logs</a></p> <p><a href="https://preview.redd.it/9shftgqzkzbe1.png?width=1582&amp;format=png&amp;auto=webp&amp;s=090f441241b1b72a41ef782ab161bf4aed62f77c">Error when boot up webUI</a></p> <pre><code>services: dashy: # To build from source, replace &#39;image: lissy93/dashy&#39; with &#39;build: .&#

## Self-hosted Reddit, Twitter and/or WhatsApp archives?
 - [https://www.reddit.com/r/selfhosted/comments/1hxevwi/selfhosted_reddit_twitter_andor_whatsapp_archives](https://www.reddit.com/r/selfhosted/comments/1hxevwi/selfhosted_reddit_twitter_andor_whatsapp_archives)
 - RSS feed: $source
 - date published: 2025-01-09T15:11:11+00:00

<!-- SC_OFF --><div class="md"><p>Essentially I want to close down or purge some accounts but I want the data to be accessible if I ever want to go back to it. Sometimes the only place I can find something is an old Reddit post on an old account. </p> <p>I want something to download them all, delete the content (can be a different tool), and make archives available. </p> <p>I have a WhatsApp backup already and tried using some of the HTML viewers, but some of the chats are so big (millions of messages) that it crashes my browser. I&#39;d need something like Whatsapp Web where it only loads a few messages but you can search and click to load older ones.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/doolittledoolate"> /u/doolittledoolate </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxevwi/selfhosted_reddit_twitter_andor_whatsapp_archives/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comme

## paperless-gpt –Yet another Paperless-ngx AI companion with LLM-based OCR focus
 - [https://www.reddit.com/r/selfhosted/comments/1hxediz/paperlessgpt_yet_another_paperlessngx_ai](https://www.reddit.com/r/selfhosted/comments/1hxediz/paperlessgpt_yet_another_paperlessngx_ai)
 - RSS feed: $source
 - date published: 2025-01-09T14:47:56+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;ve noticed discussions in other threads about <strong>paperless-ai</strong> (which is awesome), and some folks asked how it differs from my project, <strong>paperless-gpt</strong>. Since I’m a newer user here, I’ll keep things concise:</p> <h3>Context</h3> <ol> <li><strong>paperless-ai</strong> leans toward doc-based AI chat, letting you converse with your documents.<br/></li> <li><strong>paperless-gpt</strong> focuses on <strong>LLM-based OCR</strong> (for more accurate scanning of messy or low-quality docs) and a robust pipeline for auto-generating titles/tags.</li> </ol> <h3>Why Another Project?</h3> <ul> <li><strong>I didn&#39;t know paperless-ai in Sept. &#39;24</strong>: True story :D</li> <li><strong>LLM-based OCR</strong>: I wanted a solution that does advanced text extraction from scans, harnessing Large Language Models (OpenAI or Ollama).<br/></li> <li><strong>Tag &amp; Title Workflows</strong>: My main passion is

## Integrating a standard WG config into headscale for guests.
 - [https://www.reddit.com/r/selfhosted/comments/1hxdy0m/integrating_a_standard_wg_config_into_headscale](https://www.reddit.com/r/selfhosted/comments/1hxdy0m/integrating_a_standard_wg_config_into_headscale)
 - RSS feed: $source
 - date published: 2025-01-09T14:27:10+00:00

<!-- SC_OFF --><div class="md"><p>Basically just asking if anyone has implemented a normal wg server that accesses the same network as your headscale clients?</p> <p>I have my own little mesh nook on the internet but I&#39;d like a way to allow guests in from time to time that doesn&#39;t involve them using tailscale&#39;s app when I could just toss them a conf file.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vanilla_PuddinFudge"> /u/Vanilla_PuddinFudge </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdy0m/integrating_a_standard_wg_config_into_headscale/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdy0m/integrating_a_standard_wg_config_into_headscale/">[comments]</a></span>

## Form builder
 - [https://www.reddit.com/r/selfhosted/comments/1hxdxhc/form_builder](https://www.reddit.com/r/selfhosted/comments/1hxdxhc/form_builder)
 - RSS feed: $source
 - date published: 2025-01-09T14:26:28+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone.</p> <p>I have actually been searching quite a while for a form builder that&#39;s free and open source, and allows me to to input handwriting from a touchscreen.</p> <p>The idea is that when I&#39;ve been on a customer location, they can sign off the work-order on an iPad/Android tablet and a PDF of the work-order with signature is e-mailed to my administration mailbox and ideally also to the customer.</p> <p>Does anyone know if something like this exists?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/KadaverSulmus"> /u/KadaverSulmus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdxhc/form_builder/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdxhc/form_builder/">[comments]</a></span>

## Download system for YouTube Guides - Bonus: Integrate with WordPress
 - [https://www.reddit.com/r/selfhosted/comments/1hxdr9h/download_system_for_youtube_guides_bonus](https://www.reddit.com/r/selfhosted/comments/1hxdr9h/download_system_for_youtube_guides_bonus)
 - RSS feed: $source
 - date published: 2025-01-09T14:17:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello people!</p> <p>I have a small youtube channel, and i sometimes want to point people to a certain file/download-link, and i don&#39;t mind making a mirror for people, to download the same file, from my servers.</p> <p>Because it more often then i wished, gets broken, or people are saying the link is gone dead.</p> <p>But i just need a easy way to offer these downloads to people, prefferably with some kind of integration with WordPress page, like whenever i drop a file into a folder, a new item will be also publicly on the wordpress page, without me having to manually go and add that link via Elementor, etc.</p> <p>Btw, i am fammiliar with:</p> <p>- Docker, portainer, all the basic selfhosting stuff.</p> <p>- Also have an (Xpenology) Synology NAS, virtualised, and this is saddly not an option...<br/> Because the link sharing system doesn&#39;t work, for public use, because it goes to the synology<br/> page, where the Direct Download link, is not 

## self hosting ddos
 - [https://www.reddit.com/r/selfhosted/comments/1hxdhod/self_hosting_ddos](https://www.reddit.com/r/selfhosted/comments/1hxdhod/self_hosting_ddos)
 - RSS feed: $source
 - date published: 2025-01-09T14:05:03+00:00

<!-- SC_OFF --><div class="md"><p>so hello, i have bought a NAS a few days ago and i created a ubuntu VM into it that i plan to use to host my websites, game server and etc and i am wondering if there is any safe way to do so. I need to open ports 22, and from 3000-4000 to host the sites (i wont host that many ofc) and i am wondering what is the best way to defend myself. Is there a device like a special router that i can buy or should i just host it thought cloudflare, i have a pretty good internet but not good enough to survive a ddos attact. Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Weary-Bank-3415"> /u/Weary-Bank-3415 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdhod/self_hosting_ddos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxdhod/self_hosting_ddos/">[comments]</a></span>

## Looking for recommendations for offsite backup + email provider, alternative to Google
 - [https://www.reddit.com/r/selfhosted/comments/1hxdg26/looking_for_recommendations_for_offsite_backup](https://www.reddit.com/r/selfhosted/comments/1hxdg26/looking_for_recommendations_for_offsite_backup)
 - RSS feed: $source
 - date published: 2025-01-09T14:02:48+00:00

<!-- SC_OFF --><div class="md"><p>Currently paying €14/month for Google Workspace Business but reduced my use of it to only email hosting at this point.</p> <p>I would rather use that money for a service that can host my emails and function as a cloud backup when my home server is offline. Offsite data backup + temporary Dockers that boot up when my server goes offline.</p> <p>I don&#39;t mind paying extra for the time that the Dockers go online, but I don&#39;t want to waste the storage that I pay for. I don&#39;t think combining the Google Drive storage that I get with Dockers can provide a seamless service.</p> <p>Tl;dr: I&#39;m looking for a cloud hosting provider with a budgrt of €14/month for: - Email hosting - Offsite data backup that is seamlessly accessible to Docker containers. - Dockers that I pay for as I go during the 0.01% my server is offline (e.g. maintenance).</p> <p>The most important Dockers would be a mirror of my Nextcloud and Home Assistant services.</p> <p>Any 

## Surround sound music, are there really no options?
 - [https://www.reddit.com/r/selfhosted/comments/1hxcraq/surround_sound_music_are_there_really_no_options](https://www.reddit.com/r/selfhosted/comments/1hxcraq/surround_sound_music_are_there_really_no_options)
 - RSS feed: $source
 - date published: 2025-01-09T13:26:57+00:00

<!-- SC_OFF --><div class="md"><p>I am finally setting up a surround sound system and I thought back to a SACD I had and that, &quot;that would be cool&quot;. So I started looking up options.</p> <p>And I got nothing. I would love to be wrong but I can&#39;t find anything selfhosted that supports 5.1 music. Plex had a post about it on the Apple TV(I use the shield) and there has been no news since 2022 about it working on Android.</p> <p>LMS doesn&#39;t support it.</p> <p>Navidrome doesn&#39;t support it.</p> <p>I understand it&#39;s a bit of a niche thing. It just seems weird that I am coming up empty on this.</p> <p>Does anyone have ideas for how I would go about streaming 5.1 music from my NAS to my Shield?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Temporary_Lack_1222"> /u/Temporary_Lack_1222 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxcraq/surround_sound_music_are_there_really_no_options/">[link]</a></span

## I need someone to help me in hosting a vpn!
 - [https://www.reddit.com/r/selfhosted/comments/1hxcpmf/i_need_someone_to_help_me_in_hosting_a_vpn](https://www.reddit.com/r/selfhosted/comments/1hxcpmf/i_need_someone_to_help_me_in_hosting_a_vpn)
 - RSS feed: $source
 - date published: 2025-01-09T13:24:34+00:00

<!-- SC_OFF --><div class="md"><p>Ok so I live in India and currently in college.The college wifi restrictions here is a mess.The firewall is too damn powerful,it has blocked almost all popular vpns(free ofc).</p> <p>So I have decided to selfhost vpn.I did some searching here and there only to be lost in technical stuffs.I have kinda landed in two ways I could do it.</p> <p>The first would be using my wifi router in my home.But for that I need to have a pc running 24/7.I don&#39;t have that so I dropped it.The second would be using a VPS(cheap) and do some tunneling stuff.</p> <p>So basically I am in need of help for doing this.If someone could guide me through the steps I would really appreciate it.Also if there is anyone from India doing the same please help a brother out here.</p> <p>TL;DR need help in selfhosting a vpn</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CartographerOk5678"> /u/CartographerOk5678 </a> <br/> <span><a href="https:/

## Self-hosted books with a folder view?
 - [https://www.reddit.com/r/selfhosted/comments/1hxclsg/selfhosted_books_with_a_folder_view](https://www.reddit.com/r/selfhosted/comments/1hxclsg/selfhosted_books_with_a_folder_view)
 - RSS feed: $source
 - date published: 2025-01-09T13:18:54+00:00

<!-- SC_OFF --><div class="md"><p>I have tried a few already, and none seem to have a folder view. I mean, in addition to any other views that they like to support. Is there a self-hosted solution that does this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aagee"> /u/aagee </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxclsg/selfhosted_books_with_a_folder_view/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxclsg/selfhosted_books_with_a_folder_view/">[comments]</a></span>

## Help me isolate Docker containers on two networks attached to two different interfaces
 - [https://www.reddit.com/r/selfhosted/comments/1hxbzyk/help_me_isolate_docker_containers_on_two_networks](https://www.reddit.com/r/selfhosted/comments/1hxbzyk/help_me_isolate_docker_containers_on_two_networks)
 - RSS feed: $source
 - date published: 2025-01-09T12:45:52+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>In my environment I currently have one QNAP NAS connected to my LAN hosting some containers, visible only to the LAN clients, and a mini-pc &quot;server&quot; (Dell 7040 mini) hosting some other containers accessible from the Internet.</p> <p>The mini-pc is sitting on a separate VLAN which is my DMZ.</p> <p>Today I am considering consolidating all the containers on on single box running UNRAID.</p> <p>The box has two NICs and one interface is connected to the LAN (IP 192.168.1.15), the other is connected to the DMZ (IP 10.19.10.15). I made sure both interfaces are not attached to the same virtual bridge on the UNRAID host, and the box is not routing traffic between the two interfaces.</p> <p>Now, on this box I want to be sure that I have a complete isolation between the containers bound to the LAN interface and the containers bound to the DMZ interface.</p> <p>For this I have created two Docker bridge networks using the following comma

## Audiobookshelf - Expose or not?
 - [https://www.reddit.com/r/selfhosted/comments/1hxav9n/audiobookshelf_expose_or_not](https://www.reddit.com/r/selfhosted/comments/1hxav9n/audiobookshelf_expose_or_not)
 - RSS feed: $source
 - date published: 2025-01-09T11:35:09+00:00

<!-- SC_OFF --><div class="md"><p>So I finally got around to install Audiobookshelf on Docker and get rid of my monthly Audible subscription. As I like to listen to audiobooks while in the car and on walks I was wondering whether I should expose my instance to the internet (I use a Cloudflare tunnel for some of my apps) or if it is sufficient to be able to access/download books while at home or using a VPN. Do I lose functionality if the mobile app cannot access the server while on the road?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carlinhush"> /u/carlinhush </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxav9n/audiobookshelf_expose_or_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hxav9n/audiobookshelf_expose_or_not/">[comments]</a></span>

## Did I do it right?
 - [https://www.reddit.com/r/selfhosted/comments/1hxadwm/did_i_do_it_right](https://www.reddit.com/r/selfhosted/comments/1hxadwm/did_i_do_it_right)
 - RSS feed: $source
 - date published: 2025-01-09T11:01:21+00:00

<!-- SC_OFF --><div class="md"><p>Okay, so I think I’ve now got everything I need to setup my Plex server which I’m going to use exclusively for Remuxes and Encodes. Care to tell me if I’m missing anything? The current parts list is:</p> <p>Phanteks Enthoo Pro 2 Closed Panel case</p> <p>8x extra drive bays (12 total)</p> <p>8x 140mm Arctic P14 fans</p> <p>Intel i-5 14600 CPU</p> <p>Seasonic Focus PX-750W Platinum+ PSU</p> <p>ASRock Z790 Pro RS WiFi ATX mobo</p> <p>32gb G.Skill Trident Z Neo 6400 32CL DDR5 RAM</p> <p>SK Hynix 2TB NVME</p> <p>LSI SAS9305-16i HBA</p> <p>3x Mini SAS HDD SFF-8643 to 4 SFF-8482 cables</p> <p>1x 18TB Toshiba MG09SCP18TA SAS 12gb/s for parity</p> <p>8x 12TB Toshiba MG07SCA12TA SAS 12gb/s</p> <p>Ugoos AM6B+ Box</p> <p>Verbatim 43888</p> <p>I know I’ll need to get an unRAID license, but is there anything else I should have or know before finally putting this all together?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Th

## anyone using n8n self-hosted ? I tried it and I'm disappointed.
 - [https://www.reddit.com/r/selfhosted/comments/1hx9uew/anyone_using_n8n_selfhosted_i_tried_it_and_im](https://www.reddit.com/r/selfhosted/comments/1hx9uew/anyone_using_n8n_selfhosted_i_tried_it_and_im)
 - RSS feed: $source
 - date published: 2025-01-09T10:22:42+00:00

<!-- SC_OFF --><div class="md"><p>Lot of features are available only in paid version. I&#39;m going back to Node-RED.</p> <p>I&#39;m considering to try Windmill in next days.</p> <p>Anyone with similar experience?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bagican"> /u/Bagican </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx9uew/anyone_using_n8n_selfhosted_i_tried_it_and_im/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx9uew/anyone_using_n8n_selfhosted_i_tried_it_and_im/">[comments]</a></span>

## Managing multiple machines
 - [https://www.reddit.com/r/selfhosted/comments/1hx97mf/managing_multiple_machines](https://www.reddit.com/r/selfhosted/comments/1hx97mf/managing_multiple_machines)
 - RSS feed: $source
 - date published: 2025-01-09T09:34:55+00:00

<!-- SC_OFF --><div class="md"><p>I have around 5 laptops (all running ubuntu server) which I run docker containers (*arr stack, paperless, jellyfin etc.) on using docker compose. However, it is getting tiring trying to manage all 5 machines.</p> <p>I also have a DAS connected to one of the machines running the *arr stack. </p> <p>What os or hypervisor or orchestrator should I use to simplify this as much as possible? </p> <p>Please note that I need to autoscale containers if required and have shared storage. I need backups and reproducibility. </p> <p>I know this is asking for a lot of info but I just need to be pointed in the right direction. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beardbreed"> /u/beardbreed </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx97mf/managing_multiple_machines/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx97mf/managing_mul

## Developing a custom email client using NextJS
 - [https://www.reddit.com/r/selfhosted/comments/1hx7vcn/developing_a_custom_email_client_using_nextjs](https://www.reddit.com/r/selfhosted/comments/1hx7vcn/developing_a_custom_email_client_using_nextjs)
 - RSS feed: $source
 - date published: 2025-01-09T07:51:40+00:00

<!-- SC_OFF --><div class="md"><p>we are a startup, and we are currently developing a custom business platform, and now we are thinking about how users can use mail directly through our platform, that is, so that everything is in one place. Is there an opensource solution, i.e. mail servers with an API that could be integrated with our platform? In other words, we want to develop our own custom UI with our settings and features so that mail works together with some of the functionality of our platform (for example, as in Google Workspaces, etc.).<br/> What can you recommend?<br/> We use Appwrite as a backend</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hipsters_linux"> /u/hipsters_linux </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7vcn/developing_a_custom_email_client_using_nextjs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7vcn/developing_a_custom_email_client_using_ne

## Looking for an Open Source Alternative to Rivery.io
 - [https://www.reddit.com/r/selfhosted/comments/1hx7ry2/looking_for_an_open_source_alternative_to_riveryio](https://www.reddit.com/r/selfhosted/comments/1hx7ry2/looking_for_an_open_source_alternative_to_riveryio)
 - RSS feed: $source
 - date published: 2025-01-09T07:44:39+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m looking for an open-source alternative to Rivery.io. Ideally, it would offer connectors (or the ability to develop new connectors) on one side (input), a data integration hub in the middle to set rules and perform transformations using a low-code approach, and on the other side, export capabilities to major databases and data stores.</p> <p>If such a solution doesn&#39;t exist, I would also appreciate suggestions for frameworks that could help me develop one.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/umen"> /u/umen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7ry2/looking_for_an_open_source_alternative_to_riveryio/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7ry2/looking_for_an_open_source_alternative_to_riveryio/">[comments]</a></span>

## Working on Something for Devs, QA, and SDETs – Looking for Quick Feedback!
 - [https://www.reddit.com/r/selfhosted/comments/1hx7afx/working_on_something_for_devs_qa_and_sdets](https://www.reddit.com/r/selfhosted/comments/1hx7afx/working_on_something_for_devs_qa_and_sdets)
 - RSS feed: $source
 - date published: 2025-01-09T07:08:29+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;re working on a new project aimed at helping Software Developers, QAs, and SDETs, and we&#39;re still in the early stages. We’re not looking to sell anything - just genuinely interested in hearing your thoughts, challenges, and whether this product could be useful to you.</p> <p>If you’re open to a brief, no-pressure call to share your feedback, we’d love to hear from you. Your input would really help us shape the direction of what we’re building.</p> <p>Feel free to reach out if you’re interested. Thanks in advance for your time!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sonichigo-1219"> /u/sonichigo-1219 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7afx/working_on_something_for_devs_qa_and_sdets/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx7afx/working_on_something_for_devs_qa_and_sdets/">[comments]</a></span>

## I have a Raspberry Pi 4.
 - [https://www.reddit.com/r/selfhosted/comments/1hx79sj/i_have_a_raspberry_pi_4](https://www.reddit.com/r/selfhosted/comments/1hx79sj/i_have_a_raspberry_pi_4)
 - RSS feed: $source
 - date published: 2025-01-09T07:07:06+00:00

<!-- SC_OFF --><div class="md"><p>I have a raspberry pi 4 lying around in my home. As a context, i am a productivity nerd and reaaalllyyyyy like privacy when it comes to calendar, email and todo. I want to ask this awesome lively community to help me with some tested ideas of what all I can do with this.</p> <p>P.S: alot of experience with Virtualization and Linux. I am a Cybersecurity professional so any project ideas are also welcome.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/me_uncomfy_guy"> /u/me_uncomfy_guy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx79sj/i_have_a_raspberry_pi_4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx79sj/i_have_a_raspberry_pi_4/">[comments]</a></span>

## My first Home Server
 - [https://www.reddit.com/r/selfhosted/comments/1hx62ud/my_first_home_server](https://www.reddit.com/r/selfhosted/comments/1hx62ud/my_first_home_server)
 - RSS feed: $source
 - date published: 2025-01-09T05:47:08+00:00

<!-- SC_OFF --><div class="md"><p>I want help with some creation of home server. </p> <p>I have an old quad 2 duo PC with 8gb ram and old r200 and card. </p> <p>I simply want to build it as centralized hub for file storage from various devices for backups and store my entire business data with my friend on this. </p> <p>Also, if possible, I want to use some heavy software access remotely from laptops. Like adobe illustrator and photoshop or games like dark souls 1 or GTA 5. </p> <p>It is every old and dead but still work pretty great. So this is all I want. </p> <p>If it is possible please help me out. I&#39;m totally new into this and have not any knowledge at all.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UnusualCommercial146"> /u/UnusualCommercial146 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx62ud/my_first_home_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx

## Nice and simple web portal for all my selfhosted apps?
 - [https://www.reddit.com/r/selfhosted/comments/1hx5ivm/nice_and_simple_web_portal_for_all_my_selfhosted](https://www.reddit.com/r/selfhosted/comments/1hx5ivm/nice_and_simple_web_portal_for_all_my_selfhosted)
 - RSS feed: $source
 - date published: 2025-01-09T05:13:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am looking for an easy way to make my selfhosted apps like Stirling and Paperless etc. available to my family. I am thinking of a web portal, allowing me to give them one URL they can bookmark and get to a web page that lists everything on our server(s) and provides a link and maybe description for it.</p> <p>I could use my own web page and do it in raw HTML but it will look ugly. Is there something like a web based bookmark manager or something similar that you could recommend?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hgerstung"> /u/hgerstung </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx5ivm/nice_and_simple_web_portal_for_all_my_selfhosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx5ivm/nice_and_simple_web_portal_for_all_my_selfhosted/">[comments]</a></span>

## 4xRTX 3060 vs single 3090 for llama + stable diffusion
 - [https://www.reddit.com/r/selfhosted/comments/1hx4i1o/4xrtx_3060_vs_single_3090_for_llama_stable](https://www.reddit.com/r/selfhosted/comments/1hx4i1o/4xrtx_3060_vs_single_3090_for_llama_stable)
 - RSS feed: $source
 - date published: 2025-01-09T04:14:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, i got 4 rtx 3060&#39;s and a single rtx 3090 and i want to set up a local but non-internet connectected, self-hosted web-based AI chatbot with llama and hopefully stable diffusion for coding on a linux os (may open to the interweb at a later point, still not sure rn). What is the better set up given that the host system is a threadripper 1950x with a mobo that has 4x16 PCIe lanes and 8x32gb ddr4 ram? is it the 4 rtx 3060&#39;s or the single 3090? Or a 3090 with 3 rtx 3060? Assume PSU can handle all options. Thank you in advance, D.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/girthy1992"> /u/girthy1992 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx4i1o/4xrtx_3060_vs_single_3090_for_llama_stable/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx4i1o/4xrtx_3060_vs_single_3090_for_llama_stable/">[comments]</a></span>

## Nextcloud doesn't seem to agree with my VPS' CPU
 - [https://www.reddit.com/r/selfhosted/comments/1hx3158/nextcloud_doesnt_seem_to_agree_with_my_vps_cpu](https://www.reddit.com/r/selfhosted/comments/1hx3158/nextcloud_doesnt_seem_to_agree_with_my_vps_cpu)
 - RSS feed: $source
 - date published: 2025-01-09T03:03:33+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am a beginner in selfhost, and I have a 2C2G vps on which I installed docker and make docker image/containers on a HHD. I tried to ran other services and everything worked smoothly, however, every time I try to run nextcloud all in one, the CPU usage always goes up to nearly 100% and causes every other service including itself to crash. I tried troubleshooting, but they doesn&#39;t seem to work, because the solutions I have found are focused on optimizing ram usage and responding speed. What would be the possible cause of this? Any advice would be highly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yukikamiki"> /u/yukikamiki </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx3158/nextcloud_doesnt_seem_to_agree_with_my_vps_cpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx3158/nextcloud_doesnt_seem_to_agree_

## Self-hosted object storage servers that can use shared-dictionary compression across separate files?
 - [https://www.reddit.com/r/selfhosted/comments/1hx2oig/selfhosted_object_storage_servers_that_can_use](https://www.reddit.com/r/selfhosted/comments/1hx2oig/selfhosted_object_storage_servers_that_can_use)
 - RSS feed: $source
 - date published: 2025-01-09T02:46:49+00:00

<!-- SC_OFF --><div class="md"><ul> <li>I&#39;ve got a big datalake system that needs to store masses of raw input data (typically JSON/XML etc) forever <ul> <li>Many of the files are very similar, e.g. JSON that is scraped from websites etc... so for this to compress efficiently, there needs to be a shared-dictionary across files.<br/> <ul> <li>...compression where every single file has its own compression dictionary isn&#39;t efficient enough for this.</li> </ul></li> </ul></li> <li>Currently I&#39;ve custom-built something that holds uncompressed files in a dir until it&#39;s over 1gb in size, then compresses the dir into a .squashfs image, it works pretty well for the compression, about 4% of original size overall on average. <ul> <li>But for reading, I&#39;m using automount on a local regular ext4 filesystem on the server</li> </ul></li> <li>I want to move away from direct ext4 filesystem access as much as possible over to S3-compatible object storage. <ul> <li>S3-compatible is 

## A self-hosted digital journal for privacy conscious people
 - [https://www.reddit.com/r/selfhosted/comments/1hx1ux0/a_selfhosted_digital_journal_for_privacy](https://www.reddit.com/r/selfhosted/comments/1hx1ux0/a_selfhosted_digital_journal_for_privacy)
 - RSS feed: $source
 - date published: 2025-01-09T02:09:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello all</p> <p>Here is my first open-source project:<br/> <a href="https://innerpage.org">https://innerpage.org</a></p> <p>InnerPage is a free-to-use, open source and anonymous digital journal. This project emerged from my personal need. I needed a platform to freely share my most sensitive and personal thoughts. For which, notebooks or other online writing platform didn&#39;t feel safe enough.</p> <p>If you&#39;re into journaling and find the above issue relatable, please try InnerPage whenever you get the time. </p> <p>InnerPage is at a nascent stage and hence it is text-only at the moment. Kindly reach out to me in case you have feedback or feature requests.</p> <p>Thanks for reading. Journal freely &amp; fearlessly. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tbhyn_"> /u/tbhyn_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx1ux0/a_selfhosted_digital_journal_for_privacy/">[li

## High IOwait and Load
 - [https://www.reddit.com/r/selfhosted/comments/1hx1sty/high_iowait_and_load](https://www.reddit.com/r/selfhosted/comments/1hx1sty/high_iowait_and_load)
 - RSS feed: $source
 - date published: 2025-01-09T02:06:37+00:00

<!-- SC_OFF --><div class="md"><p>Recently, I bought an AK2 Firebat to use as a media server with Plex, Sonarr, Radarr, and similar applications.</p> <p>The issue is that when Transmission is downloading, Glances shows the IOwait as being too high, marking it as a critical status, and the load sometimes exceeds 100%, occasionally reaching 200%.</p> <p>I believe this might be an issue with the SSD. Perhaps it is slower than I expected, or it could be because the SSD is the only drive in the system.</p> <p>I’m considering buying a DAS (Terramaster-D4-300) to see if this improves performance and also to gain more storage space.</p> <p>Any thoughts on this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Skyorz"> /u/Skyorz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx1sty/high_iowait_and_load/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx1sty/high_iowait_and_load/">[comments]</a

## Solutions for SSO/magic links
 - [https://www.reddit.com/r/selfhosted/comments/1hx0c49/solutions_for_ssomagic_links](https://www.reddit.com/r/selfhosted/comments/1hx0c49/solutions_for_ssomagic_links)
 - RSS feed: $source
 - date published: 2025-01-09T00:55:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, so I&#39;m hosting some services and I have them secured with Authelia behind Nginx/npm reverse proxy. I have OIDC SSO set up, so when I&#39;m redirected to Authelia, that login automatically logs me into the destination server.</p> <p>I&#39;d like to be able to use &quot;magic links&quot;, and I understand it, a link that can be sent to a person that contains the authorization token already so they don&#39;t have to manually log in. I&#39;d also like to enable functionality for when accessing through stuff like a Smart TV, which I think involves &#39;device grants&#39;</p> <p>My question is, can I utilize my current Authelia/NPM setup and implement this functionality?<br/> If not, what would be the best method to achieve this? </p> <p>I&#39;ve attempted to set up Keycloak twice now with little success, and to be honest it&#39;s much more complex than I actually need, so that&#39;s not the ideal solution for me personally.</p> </div><!-- SC_

## calorie counting w/ barcode and/or photo scanning
 - [https://www.reddit.com/r/selfhosted/comments/1hx03oc/calorie_counting_w_barcode_andor_photo_scanning](https://www.reddit.com/r/selfhosted/comments/1hx03oc/calorie_counting_w_barcode_andor_photo_scanning)
 - RSS feed: $source
 - date published: 2025-01-09T00:43:50+00:00

<!-- SC_OFF --><div class="md"><p>hello all, i just went through a frustrating experiencing of registering for and setting up 3 different apps and all of them are pretty useless without paying a monthly fee.</p> <p>is there any good self hosted calorie counting software that has a decent enough android app that will let me scan bar codes and/or take photos of meals to help with automating entry?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MeYaj1111"> /u/MeYaj1111 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx03oc/calorie_counting_w_barcode_andor_photo_scanning/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hx03oc/calorie_counting_w_barcode_andor_photo_scanning/">[comments]</a></span>

## Need help installing Coolify
 - [https://www.reddit.com/r/selfhosted/comments/1hwzy1a/need_help_installing_coolify](https://www.reddit.com/r/selfhosted/comments/1hwzy1a/need_help_installing_coolify)
 - RSS feed: $source
 - date published: 2025-01-09T00:36:13+00:00

<!-- SC_OFF --><div class="md"><p>Hopefully Mods not deleting this for being newly registered, been lurking around checking out this sub and others.</p> <p>Coolify it has pretty much everything I needed and wanted to migrate from Heroku and Wordpress on shared hosting, except that not a techy system admin to handle the steps.</p> <p>DM me if any Coolify experts here willing to help for a fee to complete the setup and migration.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Used_Winner2104"> /u/Used_Winner2104 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hwzy1a/need_help_installing_coolify/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hwzy1a/need_help_installing_coolify/">[comments]</a></span>

