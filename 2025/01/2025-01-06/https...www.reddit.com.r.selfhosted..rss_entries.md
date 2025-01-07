# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Creating my own home automation
 - [https://www.reddit.com/r/selfhosted/comments/1hvcn9r/creating_my_own_home_automation](https://www.reddit.com/r/selfhosted/comments/1hvcn9r/creating_my_own_home_automation)
 - RSS feed: $source
 - date published: 2025-01-06T23:02:54+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I&#39;ve been planning this project for a few months now. I really dig the idea of having a smart room but honestly, I hate apple home kit, alexa, philips hue lights and these kind of proprietary bullshit products that just make you use their apps.</p> <p>I have a protocol in mind that would allow me to easily add gadgets to my smart home, but one thing I can&#39;t think of is, how do I control the light. </p> <p>In a perfect world, I imagine I would have a bulb that listens on a port for a request. That way it wouldn&#39;t matter if I controlled it using a c script or a web application. Do you know if there&#39;s something like that? Is there a smart light bulb I could control like that? Also, any tips and recommendations are welcome. I haven&#39;t done anything like this but I&#39;m really hyped up. I know I have the programming and electronics skills to pull this off.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.redd

## Rescue or backup entire Proxmox VE host
 - [https://www.reddit.com/r/selfhosted/comments/1hvc7pn/rescue_or_backup_entire_proxmox_ve_host](https://www.reddit.com/r/selfhosted/comments/1hvc7pn/rescue_or_backup_entire_proxmox_ve_host)
 - RSS feed: $source
 - date published: 2025-01-06T22:44:03+00:00

<!-- SC_OFF --><div class="md"><p>This post takes a brief look at how to access PVE host root filesystem when booting off Proxmox installer ISO. An example with particularly problematic ZFS-on-root install is examined as it is not supported by regular Live Debian and it is rather non-intuitive. As part of the demonstration, a fast full host backup (no guests) resulting in ~1G archive is taken and sent out over SSH - format that will allow for flexible redeployment in a follow-up guide. No special or proprietary tools used whatsover, just regular Debian tooling.</p> <p>Better formatted - no tracking - at: <a href="https://free-pmx.github.io/guides/host-backup/">https://free-pmx.github.io/guides/host-backup/</a></p> <hr/> <p>We will take a look at multiple unfortunate scenarios - all in one - none of which appear to be well documented, let alone <em>intuitive</em> when it comes to either:</p> <ul> <li>troubleshooting a Proxmox VE host that <em>completely fails to boot</em>; or</li> <li

## How are you securing your private applications?
 - [https://www.reddit.com/r/selfhosted/comments/1hvbg11/how_are_you_securing_your_private_applications](https://www.reddit.com/r/selfhosted/comments/1hvbg11/how_are_you_securing_your_private_applications)
 - RSS feed: $source
 - date published: 2025-01-06T22:11:10+00:00

<!-- SC_OFF --><div class="md"><p>I run a handful of web applications on my VPS behind an Nginx reverse proxy. Recently I&#39;ve wanted to increase the secuity of my private applications since I am not sure I trust them fully. In particular I would like to whitelist only certain devices to access these applications, e.g. using mTLS or webauthn.</p> <p>As I use cloudflare as NS for my domain, one option is to remove the sensitive applications from my reverse proxy and instead setup a cloudflare tunnel (Zero trust and mTLS).</p> <p>Another, perhaps simpler method is to simply roll my own client side certificates and do the authentication within nginx. <a href="https://fardog.io/blog/2017/12/30/client-side-certificate-authentication-with-nginx/">https://fardog.io/blog/2017/12/30/client-side-certificate-authentication-with-nginx/</a></p> <p>The obvious pros and cons to me are * Rolling your own comes with the risk of messing it up and leaving it less secure, in that case trusting cloudfl

## Question For Those Hosting A FreeTube Instance
 - [https://www.reddit.com/r/selfhosted/comments/1hvba8o/question_for_those_hosting_a_freetube_instance](https://www.reddit.com/r/selfhosted/comments/1hvba8o/question_for_those_hosting_a_freetube_instance)
 - RSS feed: $source
 - date published: 2025-01-06T22:04:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m using LibRedirect to point to my instance. LibRedirect is a FireFox plugin that will redirect a lof of services to an opensource, crap free, interface. </p> <p>I have no complaints about FreeTube except passing the url from a DDG search to FreeTube. For instance: I open a browser and search for DJ Quick - Digging You Out. The search results come up in DDG, and I select the song from the search results. That triggers LibRedirect to funnel the request to my FreeTube instance. The problem is that it won&#39;t forward the url segment (example: myreallycooldomain.duckdns.org<strong>/watch?v=FW0b_n_Sch4</strong>) </p> <p>The part <strong>FW0b_n_Sch4</strong> is the correct Youtube locator id, but I get an error of &#39;Cannot GET /watch&#39; . If I pull up FreeTube by itself and search for DJ Quick - Digging You Out, FreeTube will work perfectly. It just doesn&#39;t pass the url ID from a standard search engine.</p> <p>I&#39;ve been through the set

## transfer ssh keys from Windows PC to Linux lite laptop
 - [https://www.reddit.com/r/selfhosted/comments/1hvb2ir/transfer_ssh_keys_from_windows_pc_to_linux_lite](https://www.reddit.com/r/selfhosted/comments/1hvb2ir/transfer_ssh_keys_from_windows_pc_to_linux_lite)
 - RSS feed: $source
 - date published: 2025-01-06T21:55:18+00:00

<!-- SC_OFF --><div class="md"><p>(I am sorry if I&#39;m asking in the wrong community )</p> <p>Hey,</p> <p>I host linux server whitch I can access via ssh. I authenticate using ssh keys and passwords aren&#39;t allowed.<br/> I&#39;m going to be away from home for a few days, so to still have access to my linux server, I wanted to copy keys from windows to my linux laptop. I know I could generate new keys and all that, but last time I did that, It took me a lot of time so I would like to just copy keys from one to the other machine if possible.<br/> I am not really sure where to put those keys and how to use them. I am using Linux lite.</p> <p>Any suggestons? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/akisha_009"> /u/akisha_009 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hvb2ir/transfer_ssh_keys_from_windows_pc_to_linux_lite/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comm

## Paperless-ngx doesn't work on my Synology NAS
 - [https://www.reddit.com/r/selfhosted/comments/1hvaeke/paperlessngx_doesnt_work_on_my_synology_nas](https://www.reddit.com/r/selfhosted/comments/1hvaeke/paperlessngx_doesnt_work_on_my_synology_nas)
 - RSS feed: $source
 - date published: 2025-01-06T21:27:50+00:00

<!-- SC_OFF --><div class="md"><p>Just to clarify upfront: I don&#39;t really have much technical knowledge, but after I managed to get Paperless running on my laptop using Docker, I thought switching to the Synology NAS (216+II) would work just as smoothly.</p> <p>I adjusted the file paths in the docker-compose.yml file accordingly, and the containers seem to be running fine. However, when I go to [http://ip:8000](), I only get a black screen with the message &#39;not found&#39;, not even the typical 404 error.</p> <p>I&#39;ve tried using Portainer and have completely reinstalled the containers 10 times, but it just doesn&#39;t work... which is strange because it worked fine with Docker on my laptop.</p> <p>I can provide the code later if needed, but is there anyone here who might already have an idea of what could be causing this? The container manager on the NAS looks almost identical to the one on Docker, so I don&#39;t understand where it could be failing. Did I miss any step?</

## WeddingShare v1.4.6 - Now with video support
 - [https://www.reddit.com/r/selfhosted/comments/1hva1v9/weddingshare_v146_now_with_video_support](https://www.reddit.com/r/selfhosted/comments/1hva1v9/weddingshare_v146_now_with_video_support)
 - RSS feed: $source
 - date published: 2025-01-06T21:13:24+00:00

<!-- SC_OFF --><div class="md"><p>For those not following the progress on GitHub or DockerHub, WeddingShare v1.4.6 now includes the following features:</p> <ul> <li>Video support in galleries.</li> <li>Identity request to allow guests take credit for their uploads.</li> <li>Better multi-language support.</li> <li>&quot;All&quot; gallery to display all items in a single gallery.</li> <li>Admin panel improvements.</li> </ul> <p>And many more features and changes.</p> <p><strong>If you have any features you would like me to add in the future I highly encourage you to submit a ticket over on the GitHub page and star the project while you&#39;re there to keep up to date with the latest releases!</strong></p> <p>Documentation - <a href="https://docs.wedding-share.org">https://docs.wedding-share.org</a></p> <p>GitHub - <a href="https://github.com/Cirx08/WeddingShare">https://github.com/Cirx08/WeddingShare</a><br/> DockerHub - <a href="https://hub.docker.com/r/cirx08/wedding_share">https://h

## Looking for a self hosted remote desktop tool that can be accessed from a web interface.
 - [https://www.reddit.com/r/selfhosted/comments/1hva0vz/looking_for_a_self_hosted_remote_desktop_tool](https://www.reddit.com/r/selfhosted/comments/1hva0vz/looking_for_a_self_hosted_remote_desktop_tool)
 - RSS feed: $source
 - date published: 2025-01-06T21:12:16+00:00

<!-- SC_OFF --><div class="md"><p>Existing tools I&#39;ve found don&#39;t fit my use case. I would like a remote desktop tool that can be accessed from a web interface so I can access it from my custom domain. It needs to stream my windows PC. Does anything like this exist?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Live-Client-425"> /u/Live-Client-425 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hva0vz/looking_for_a_self_hosted_remote_desktop_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hva0vz/looking_for_a_self_hosted_remote_desktop_tool/">[comments]</a></span>

## Looking for really cheap (<3 euro) VPS based in the Netherlands (due to ping)
 - [https://www.reddit.com/r/selfhosted/comments/1hv9k7h/looking_for_really_cheap_3_euro_vps_based_in_the](https://www.reddit.com/r/selfhosted/comments/1hv9k7h/looking_for_really_cheap_3_euro_vps_based_in_the)
 - RSS feed: $source
 - date published: 2025-01-06T20:53:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been looking around but the cheap servers are either not available in the Netherlands, or, they&#39;re not cheap.</p> <p>Preferably atleast 100 Mbps bandwidth speed and, idk, a 500GB+ bandwidth cap.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/sinterkaastosti23"> /u/sinterkaastosti23 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv9k7h/looking_for_really_cheap_3_euro_vps_based_in_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv9k7h/looking_for_really_cheap_3_euro_vps_based_in_the/">[comments]</a></span>

## Need help with NGINX Proxy manager and Nextcloud-AIO
 - [https://www.reddit.com/r/selfhosted/comments/1hv9fjg/need_help_with_nginx_proxy_manager_and](https://www.reddit.com/r/selfhosted/comments/1hv9fjg/need_help_with_nginx_proxy_manager_and)
 - RSS feed: $source
 - date published: 2025-01-06T20:48:42+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to get Nextcloud-AIO running behind my Nginx reverse proxy and running into an odd issue.</p> <p>Both my NPM and Nextcloud-AIO contains are running inside a Truenas Scale VM that&#39;s inside a DMZ subnet (IP <a href="http://192.168.20.2">192.168.20.2</a>; Truenas is in LAN subnet 192.168.1.2) </p> <p>After setting the NPM proxy to point to the 192.168.20.2:11000 (or the docker internal IP 172.19.0.3:11000), I&#39;m getting this error in the Nextcloud-AIO management screen running a domain check:</p> <p>&quot;The domain is not reachable on Port 443 from within this container. Have you opened port 443/tcp in your router/firewall? If yes is the problem most likely that the router or firewall forbids local access to your domain. You can work around that by setting up a local DNS-server&quot;</p> <p>My cloudflare DNS A records are set up (cloud.mydomain.com; proxy off), and my firewall is forwarding port 80/443. If I go to mydomain.com, it

## How to access services in a local LAN network from a mobile while having always-on VPN?
 - [https://www.reddit.com/r/selfhosted/comments/1hv9ey7/how_to_access_services_in_a_local_lan_network](https://www.reddit.com/r/selfhosted/comments/1hv9ey7/how_to_access_services_in_a_local_lan_network)
 - RSS feed: $source
 - date published: 2025-01-06T20:48:00+00:00

<!-- SC_OFF --><div class="md"><p>There&#39;s always-on VPN connection active on a mobile. As Android has a limitation on one VPN connection at the same time, adding tailscale won&#39;t help, or at least I don&#39;t know how to set up. Services are accessible while on a home network, but they need to be accessible while away as well.</p> <p>Home network is behind CGNAT, so I assume Tailscale/ZeroTier is the only way or there&#39;s something else? I have a VPS which I could use if necessary, for example to move some service from a local network to VPS, but I would rather have it the way it is right now, if possible.</p> <p>Is there any way to make this work i.e. not to touch the active VPN connection, while adding the ability to access local services?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aimp_right"> /u/aimp_right </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv9ey7/how_to_access_services_in_a_local_lan_networ

## Essential Docker Security Tips for Self-Hosting
 - [https://www.reddit.com/r/selfhosted/comments/1hv8jn6/essential_docker_security_tips_for_selfhosting](https://www.reddit.com/r/selfhosted/comments/1hv8jn6/essential_docker_security_tips_for_selfhosting)
 - RSS feed: $source
 - date published: 2025-01-06T20:13:18+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hv8jn6/essential_docker_security_tips_for_selfhosting/"> <img src="https://external-preview.redd.it/AQ9TP8DWaRm40jLBLKjZ7c0UMVGRGKA29XJ5-CwllsY.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=2b9ea3bbc92427d91977ed471566ce81af0a00e8" alt="Essential Docker Security Tips for Self-Hosting" title="Essential Docker Security Tips for Self-Hosting" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/justsml"> /u/justsml </a> <br/> <span><a href="https://danlevy.net/docker-security-tips-for-self-hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv8jn6/essential_docker_security_tips_for_selfhosting/">[comments]</a></span> </td></tr></table>

## How to reliably make a URL for a Desktop?
 - [https://www.reddit.com/r/selfhosted/comments/1hv87eo/how_to_reliably_make_a_url_for_a_desktop](https://www.reddit.com/r/selfhosted/comments/1hv87eo/how_to_reliably_make_a_url_for_a_desktop)
 - RSS feed: $source
 - date published: 2025-01-06T20:00:05+00:00

<!-- SC_OFF --><div class="md"><p>is there any good guide on setting up caddy or some other reverse proxy with a router? </p> <p>Ive used tailscale to make my desktops publicly discoverable, but i want a permanent URL to my desktops.</p> <p>i got caddy working with cloudflare a few months ago at my families house in texas, but when they switched the router, the IP no longer works :(</p> <p>is there a good guide on self hosted networking?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Next-Commercial3114"> /u/Next-Commercial3114 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv87eo/how_to_reliably_make_a_url_for_a_desktop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv87eo/how_to_reliably_make_a_url_for_a_desktop/">[comments]</a></span>

## Contract management tool
 - [https://www.reddit.com/r/selfhosted/comments/1hv84tf/contract_management_tool](https://www.reddit.com/r/selfhosted/comments/1hv84tf/contract_management_tool)
 - RSS feed: $source
 - date published: 2025-01-06T19:57:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello, Does anyone know of a free tool where I can create an account for customers where they can manage their contracts with me? Or be able to conclude a new one. It doesn&#39;t need any accounting functions such as invoices as I use Lexware Office for this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ezleon311"> /u/ezleon311 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv84tf/contract_management_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv84tf/contract_management_tool/">[comments]</a></span>

## SFTPGO self hosted
 - [https://www.reddit.com/r/selfhosted/comments/1hv7fx3/sftpgo_self_hosted](https://www.reddit.com/r/selfhosted/comments/1hv7fx3/sftpgo_self_hosted)
 - RSS feed: $source
 - date published: 2025-01-06T19:29:16+00:00

<!-- SC_OFF --><div class="md"><p>anybody self hosted SFTPGo?</p> <p>I want to use webdev feature?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Infamous-Mission-878"> /u/Infamous-Mission-878 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv7fx3/sftpgo_self_hosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv7fx3/sftpgo_self_hosted/">[comments]</a></span>

## build dashboards with AI- private beta for feedback before open source
 - [https://www.reddit.com/r/selfhosted/comments/1hv779a/build_dashboards_with_ai_private_beta_for](https://www.reddit.com/r/selfhosted/comments/1hv779a/build_dashboards_with_ai_private_beta_for)
 - RSS feed: $source
 - date published: 2025-01-06T19:19:21+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I built a new AI tool to help build data apps/dashboard from any data source with just prompts. it will be out as open source in a few weeks but would love to get some feedback before i do that (so no disaster when i launch)</p> <p>whoever is interested: <a href="https://bagofwords.com">https://bagofwords.com</a></p> <p>fyi- private beta is simply a docker container you can self host. product written in python/js</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hot_Dependent9514"> /u/Hot_Dependent9514 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv779a/build_dashboards_with_ai_private_beta_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv779a/build_dashboards_with_ai_private_beta_for/">[comments]</a></span>

## Docker-compose GUI editor now open source and self-hostable
 - [https://www.reddit.com/r/selfhosted/comments/1hv6ngi/dockercompose_gui_editor_now_open_source_and](https://www.reddit.com/r/selfhosted/comments/1hv6ngi/dockercompose_gui_editor_now_open_source_and)
 - RSS feed: $source
 - date published: 2025-01-06T18:57:06+00:00

<!-- SC_OFF --><div class="md"><p>Weeks ago I released a docker-compose GUI editor, where you can import your own docker-compose.yml files and view, edit and share them : <a href="https://composecraft.com">https://composecraft.com</a></p> <p>And it&#39;s now open source !<br/> And you can self host it easily with a docker-compose file 😉</p> <p>Github : <a href="https://github.com/composecraft/composecraft">https://github.com/composecraft/composecraft</a><br/> Dockler hub : <a href="https://hub.docker.com/repository/docker/composecraft/composecraft/general">https://hub.docker.com/repository/docker/composecraft/composecraft/general</a></p> <p>I would like to have some feedbacks !<br/> Thanks !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WesternPerspective53"> /u/WesternPerspective53 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv6ngi/dockercompose_gui_editor_now_open_source_and/">[link]</a></span> &#32; <span><a href

## ERPNext Deployment
 - [https://www.reddit.com/r/selfhosted/comments/1hv6i42/erpnext_deployment](https://www.reddit.com/r/selfhosted/comments/1hv6i42/erpnext_deployment)
 - RSS feed: $source
 - date published: 2025-01-06T18:50:58+00:00

<!-- SC_OFF --><div class="md"><p>I just discovered the ERPNext application and plan to give it a try for my small business. I’m looking to deploy this in a docker compose container within Proxmox. Is there an option to deploy this using an external database vs the db container spun up from the compose file?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CedCodgy1450"> /u/CedCodgy1450 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv6i42/erpnext_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv6i42/erpnext_deployment/">[comments]</a></span>

## New Home Setup (Im learning, need guidance)
 - [https://www.reddit.com/r/selfhosted/comments/1hv6cmn/new_home_setup_im_learning_need_guidance](https://www.reddit.com/r/selfhosted/comments/1hv6cmn/new_home_setup_im_learning_need_guidance)
 - RSS feed: $source
 - date published: 2025-01-06T18:44:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hv6cmn/new_home_setup_im_learning_need_guidance/"> <img src="https://b.thumbs.redditmedia.com/EjX8g-VDAwViNSDcKp7xQZH19JNsGeFgSSza5WPzqtI.jpg" alt="New Home Setup (Im learning, need guidance)" title="New Home Setup (Im learning, need guidance)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>So what i am trying to do is set up my home network, with 1 external ip address, to allow for my gaming PC, 2 Ubuntu servers (reachable from outside my home network), and a homelab setup on a ESXI 7. I am very new to this but i am trying to learn and just need guidance on what to research for each step in this set up. I have overwhelmed myself with too much research and now have no idea what to do first. Im not looking for someone to give me the answers, just for advice to help me reach my end goal.</p> <p>The end goal is to host a webserver on 1 unbuntu server and a game server (ex. minecraft) on the 2nd server.</p> <p><

## Simpler alternative to ActualServer?
 - [https://www.reddit.com/r/selfhosted/comments/1hv63dx/simpler_alternative_to_actualserver](https://www.reddit.com/r/selfhosted/comments/1hv63dx/simpler_alternative_to_actualserver)
 - RSS feed: $source
 - date published: 2025-01-06T18:34:43+00:00

<!-- SC_OFF --><div class="md"><p>I like it but to be honest I don&#39;t have the time to go back at it every month. I think I actually need something different which doesn&#39;t depend much on transactions. My bank isn&#39;t compatible with the way ActualServer import transactions. This mean it&#39;s much less appealing. Are there simpler/less time consuming budget apps out there?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/igmyeongui"> /u/igmyeongui </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv63dx/simpler_alternative_to_actualserver/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv63dx/simpler_alternative_to_actualserver/">[comments]</a></span>

## Is it possible to install windows programs on a linux server, and execute the program remotely on my local windows computer?
 - [https://www.reddit.com/r/selfhosted/comments/1hv62ry/is_it_possible_to_install_windows_programs_on_a](https://www.reddit.com/r/selfhosted/comments/1hv62ry/is_it_possible_to_install_windows_programs_on_a)
 - RSS feed: $source
 - date published: 2025-01-06T18:33:59+00:00

<!-- SC_OFF --><div class="md"><p>My computer is running out of storage, I want to install a program in my home server and run it directly on my local windows computer, is it possible?</p> <p>All the guides ive seen are pointing towards using portable apps, wine, VM etc. But what I want is to install my program somewhere else on a network as if im installing on a different drive.</p> <p>Thanks guys!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Desmondtheredx"> /u/Desmondtheredx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv62ry/is_it_possible_to_install_windows_programs_on_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv62ry/is_it_possible_to_install_windows_programs_on_a/">[comments]</a></span>

## Starting My First Homelab with a Beelink SER8 – Looking for Ideas to Learn Networking, Cloud, and Docker
 - [https://www.reddit.com/r/selfhosted/comments/1hv4ykp/starting_my_first_homelab_with_a_beelink_ser8](https://www.reddit.com/r/selfhosted/comments/1hv4ykp/starting_my_first_homelab_with_a_beelink_ser8)
 - RSS feed: $source
 - date published: 2025-01-06T17:48:24+00:00

<!-- SC_OFF --><div class="md"><p>I’m thrilled to share that I’ve just picked up a <strong>Beelink SER8 mini PC</strong> with some impressive specs:</p> <ul> <li><strong>AMD Ryzen™ 7 8745HS</strong></li> <li><strong>AMD Radeon 780M</strong></li> <li><strong>32GB RAM</strong></li> <li><strong>1TB SSD</strong></li> </ul> <p>With this setup, I’m diving into my very first <strong>homelab</strong>! I’ve already completed the groundwork for my home network, including a router, firewall, and access point, so the networking side of things is sorted.</p> <p>While I’m familiar with <strong>IT</strong>, including <strong>Linux</strong>, <strong>terminal commands</strong>, and <strong>programming</strong>, I’m by no means an expert. My goal with this homelab is to deepen my knowledge of <strong>networking</strong>, <strong>cloud technologies</strong>, <strong>Docker</strong>, and other IT concepts to prepare for an career in IT. I plan to install <strong>Proxmox</strong> and experiment with VMs 

## pfSense-docker-alias: Simplify pfSense-based Alias Management for Your Self-Hosted Docker Services
 - [https://www.reddit.com/r/selfhosted/comments/1hv4o3q/pfsensedockeralias_simplify_pfsensebased_alias](https://www.reddit.com/r/selfhosted/comments/1hv4o3q/pfsensedockeralias_simplify_pfsensebased_alias)
 - RSS feed: $source
 - date published: 2025-01-06T17:36:33+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a> community!</p> <p>I&#39;m excited to share a project I&#39;ve been working on: <a href="https://github.com/toddawhittaker/pfsense-docker-alias">pfSense-docker-alias</a> — a lightweight, Python-based Docker container that dynamically updates DNS aliases in pfSense based on Docker container events. If you&#39;re running a self-hosted environment with pfSense and Docker, this tool might be just what you need. It&#39;s in early release (and my first service), so feedback is welcome.</p> <p><strong>Why I built this</strong></p> <p>My typical (manual) workflow was to spin up a new docker service, make an entry in my Caddy-based reverse proxy, and then add an alias for the Caddy LXC host override in pfSense. It was irritating to do this manually, especially adding the alias. So I automated it with this project.</p> <p>With this project, you can:</p> <ul> <li>Automatically add DNS aliases to an existing host overr

## GameVault: How to download meta data?
 - [https://www.reddit.com/r/selfhosted/comments/1hv4jka/gamevault_how_to_download_meta_data](https://www.reddit.com/r/selfhosted/comments/1hv4jka/gamevault_how_to_download_meta_data)
 - RSS feed: $source
 - date published: 2025-01-06T17:31:33+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hv4jka/gamevault_how_to_download_meta_data/"> <img src="https://b.thumbs.redditmedia.com/pm2dUddO_9FEaBL5bPzV4cZFZ-f0en-XkUNZIiMxZxg.jpg" alt="GameVault: How to download meta data?" title="GameVault: How to download meta data?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/cz5aj0agsebe1.png?width=2719&amp;format=png&amp;auto=webp&amp;s=bc5595c2ddf826fbe153bbe9321578116dc1673e">https://preview.redd.it/cz5aj0agsebe1.png?width=2719&amp;format=png&amp;auto=webp&amp;s=bc5595c2ddf826fbe153bbe9321578116dc1673e</a></p> <p>I have set up GameVault with docker, things works nice exept that no games matches with meta data.<br/> Maybe the games are not on the meta data server but I can&#39;t search either.<br/> I read that i should set up settings in the .env file but I could not figure out what. Im running without an .env file now.<br/> (I added picture and meta for Tetris manually.)</p

## Host Your Own Local LLM / RAG Behind a Private VPN, Access It From Anywhere
 - [https://www.reddit.com/r/selfhosted/comments/1hv4bkq/host_your_own_local_llm_rag_behind_a_private_vpn](https://www.reddit.com/r/selfhosted/comments/1hv4bkq/host_your_own_local_llm_rag_behind_a_private_vpn)
 - RSS feed: $source
 - date published: 2025-01-06T17:22:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi! Over my break from work I deployed my own private LLM using Ollama and Tailscale, hosted on my Synology NAS with a reverse proxy on my raspberry Pi. </p> <p>I designed the system such that it can exist behind a DNS that only I have access to, and that I can access it from anywhere in the world (with an internet connection). I used Ollama in a Synology container because it&#39;s so easy to get setup.</p> <p>Figured I&#39;d also share how I built it, in case anyone else wanted to try to replicate the process. If you have any questions, please feel free to comment!</p> <p>Link to writeup here: <a href="https://benjaminlabaschin.com/host-your-own-private-llm-access-it-from-anywhere/">https://benjaminlabaschin.com/host-your-own-private-llm-access-it-from-anywhere/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/benJman247"> /u/benJman247 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1

## What's a recommend OS for an old Android (Samsung S20 FE)?
 - [https://www.reddit.com/r/selfhosted/comments/1hv3w3e/whats_a_recommend_os_for_an_old_android_samsung](https://www.reddit.com/r/selfhosted/comments/1hv3w3e/whats_a_recommend_os_for_an_old_android_samsung)
 - RSS feed: $source
 - date published: 2025-01-06T17:05:24+00:00

<!-- SC_OFF --><div class="md"><p>My personal phone is a Samsung S23+, however I have the one before it an S20 FE in storage. It still turns on and works, as I do it once a month.</p> <p>As far as my Homelab setups, I have three Proxmox VE OS Desktops each running seperate Docker LXCs with different containers each, plus a Synology NAS DS218, all on the same VLAN.</p> <p>I was thinking of doing some kind of OS install on the S20 FE and doing god knows what with it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JaegerBourne"> /u/JaegerBourne </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv3w3e/whats_a_recommend_os_for_an_old_android_samsung/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv3w3e/whats_a_recommend_os_for_an_old_android_samsung/">[comments]</a></span>

## cheapest persistent storage for A100/H100 GPU's?
 - [https://www.reddit.com/r/selfhosted/comments/1hv39p9/cheapest_persistent_storage_for_a100h100_gpus](https://www.reddit.com/r/selfhosted/comments/1hv39p9/cheapest_persistent_storage_for_a100h100_gpus)
 - RSS feed: $source
 - date published: 2025-01-06T16:40:12+00:00

<!-- SC_OFF --><div class="md"><p>hi. anyone know which company offers the lowest price for a 200GB persistent drive when renting a A100/H100 gpu?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RealAI22"> /u/RealAI22 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv39p9/cheapest_persistent_storage_for_a100h100_gpus/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv39p9/cheapest_persistent_storage_for_a100h100_gpus/">[comments]</a></span>

## Looking for a financial management tool (LXC), in addition with iOS App interface...
 - [https://www.reddit.com/r/selfhosted/comments/1hv33ns/looking_for_a_financial_management_tool_lxc_in](https://www.reddit.com/r/selfhosted/comments/1hv33ns/looking_for_a_financial_management_tool_lxc_in)
 - RSS feed: $source
 - date published: 2025-01-06T16:33:12+00:00

<!-- SC_OFF --><div class="md"><p>Prefered as a Promox LXC with a iOS App</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Effective-Ad-2448"> /u/Effective-Ad-2448 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv33ns/looking_for_a_financial_management_tool_lxc_in/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv33ns/looking_for_a_financial_management_tool_lxc_in/">[comments]</a></span>

## Cloudflare Tunnel + Docker Container- some work and some don't
 - [https://www.reddit.com/r/selfhosted/comments/1hv2vch/cloudflare_tunnel_docker_container_some_work_and](https://www.reddit.com/r/selfhosted/comments/1hv2vch/cloudflare_tunnel_docker_container_some_work_and)
 - RSS feed: $source
 - date published: 2025-01-06T16:23:27+00:00

<!-- SC_OFF --><div class="md"><p>Alrighty, time to tackle this one. Here is my setup:<br/> Linux machine running Ubuntu with the Cloudflare daemon installed. Docker installed with multiple containers. Some containers I can use with Cloudflare (that is, I can &quot;point&quot; Cloudflare to the container and it works with zero issues.) In other containers, I get a loading error when trying the Cloudflare URL. I&#39;ve verified ports and made sure they were HTTP, etc. <strong>Why are some containers working ok with Cloudflare tunnels and others are not?</strong> I am a novice with Docker networking so everything is setup on a bridge. Specifically, I am trying to get PSiTransfer to work so that I can share files with others and have them use the Cloudflare URL to access them. </p> <p>I can use Tailscale and the port number just fine to connect to my containers from outside my network, so I feel like Cloudflare Tunnels should not give me this much hassle, albeit I know they are very dif

## No fuss switching between local IP and external IP for hosted apps — finally figured it out
 - [https://www.reddit.com/r/selfhosted/comments/1hv2kv3/no_fuss_switching_between_local_ip_and_external](https://www.reddit.com/r/selfhosted/comments/1hv2kv3/no_fuss_switching_between_local_ip_and_external)
 - RSS feed: $source
 - date published: 2025-01-06T16:11:07+00:00

<!-- SC_OFF --><div class="md"><p>I recently achieved seamless switching between my local IP and external IP for self-hosted apps using my own DNS over TLS (DoT) resolver. I&#39;ve found that most people resort to using WireGuard tunnels or Tailscale, but these solutions can be complex and may not be the best fit for everyone.</p> <p><strong>Local DNS Resolver</strong></p> <p>On my local network, I set up a DNS resolver that rewrites DNS queries to point to my local IP address. This allows my devices to resolve internal DNS queries correctly when I&#39;m on the local network.</p> <p><strong>External DNS Resolver</strong></p> <p>On an external server, I set up a traditional DNS resolver that acts as a normal resolver. However, since it&#39;s a DoT resolver, I was able to use the same DNS address (<code>dns.dmain.com</code>) for both local and external queries.</p> <p><strong>Benefits</strong></p> <p>This setup is particularly useful for family member&#39;s mobile devices who I want to

## Endurain: A Self-Hosted Fitness Activity Tracker - v0.7.1 Update 🎉
 - [https://www.reddit.com/r/selfhosted/comments/1hv11q0/endurain_a_selfhosted_fitness_activity_tracker](https://www.reddit.com/r/selfhosted/comments/1hv11q0/endurain_a_selfhosted_fitness_activity_tracker)
 - RSS feed: $source
 - date published: 2025-01-06T15:05:11+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! It’s me again, sharing updates about <strong>Endurain</strong>, a fitness activity tracker you can self-host. Last December, Endurain celebrated its <strong>first anniversary</strong>, and it’s been an incredible journey learning and growing with this project. A big thank you to everyone who has supported and provided feedback so far!</p> <p>Since my last post here, I’ve worked on adding new features and improvements based on community requests. Here are some highlights:</p> <ul> <li><strong>Unified Docker image</strong> with both backend and frontend (a much-requested feature).</li> <li><strong>Timezone awareness</strong> for better activity tracking.</li> <li>Support for <strong>initial KMs for gear</strong>.</li> <li>Automatically retrieve <strong>BMI from Garmin Connect</strong>.</li> <li>A new <strong>health dashboard</strong> to visualize key metrics (BMI and last weight).</li> <li>Support for new activity types: <strong>alpine sk

## Immich AIO Alpine on CasaOS does not work
 - [https://www.reddit.com/r/selfhosted/comments/1hv0wsn/immich_aio_alpine_on_casaos_does_not_work](https://www.reddit.com/r/selfhosted/comments/1hv0wsn/immich_aio_alpine_on_casaos_does_not_work)
 - RSS feed: $source
 - date published: 2025-01-06T14:59:30+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to install and use Immich on my CasaOS home server and nothing I do is working. Even if I download a fresh install, Immich does not seem to start and opening the web app gives me a &quot;could not connect error&quot;</p> <p>I&#39;ve tried this with Immich from the stock store, Immich from BigBear, Immich without Machine Learning from BigBear, and now finally Immich AIO Alpine from BigBear. Is there something I&#39;m doing g wrong? Is there a setting within the container itself I have to configure?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gay-espresso-tiger"> /u/gay-espresso-tiger </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0wsn/immich_aio_alpine_on_casaos_does_not_work/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0wsn/immich_aio_alpine_on_casaos_does_not_work/">[comments]</a></span>

## How to monitor the self hosted signoz docker instance running inside the ec2.
 - [https://www.reddit.com/r/selfhosted/comments/1hv0nd6/how_to_monitor_the_self_hosted_signoz_docker](https://www.reddit.com/r/selfhosted/comments/1hv0nd6/how_to_monitor_the_self_hosted_signoz_docker)
 - RSS feed: $source
 - date published: 2025-01-06T14:47:32+00:00

<!-- SC_OFF --><div class="md"><p>I am running the signoz docker instance inside EC2. Can anyone please help me with the good approach for monitoring the signoz itslef. I want know if all the docker containers are healthy and get alert on unhealthy container.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/New_Public_3950"> /u/New_Public_3950 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0nd6/how_to_monitor_the_self_hosted_signoz_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0nd6/how_to_monitor_the_self_hosted_signoz_docker/">[comments]</a></span>

## PDF / SCAN post processing
 - [https://www.reddit.com/r/selfhosted/comments/1hv0mzd/pdf_scan_post_processing](https://www.reddit.com/r/selfhosted/comments/1hv0mzd/pdf_scan_post_processing)
 - RSS feed: $source
 - date published: 2025-01-06T14:47:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi Folks,<br/> I want to start to optimize my personal documents. Currently I use the scan2mail solution which gives me a pdf which I sent to adobe&#39;s free tier acrobat api to OCR it, remove empty pages, fix rotation, brightness etc., as I now want to change my mailsystem (Office365, + PowerAutomate for sending to Adobe) I would like to change this to something selfhosted. I already played with paperless-ngx, but somehow could not really get into it, I&#39;m preferring a more file/folder based approach and therefore only searching for some pdf optimization tool. Do you have any suggestions? It could be simple as an executable which I run regulary or even more complex.</p> <p>Thanks for your recommendations :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Historical-Lab8122"> /u/Historical-Lab8122 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0mzd/pdf_scan_post_processing/">[link]

## Server Security + AWS replica
 - [https://www.reddit.com/r/selfhosted/comments/1hv0hgm/server_security_aws_replica](https://www.reddit.com/r/selfhosted/comments/1hv0hgm/server_security_aws_replica)
 - RSS feed: $source
 - date published: 2025-01-06T14:39:39+00:00

<!-- SC_OFF --><div class="md"><p>Just started self hosting about a week ago. Had previous networking + systems design knowledge (projects + interview prep lol) but never really delved into linux except for using Ubuntu at university. </p> <p>Started by trying to host my own server using nginx. </p> <p>I had a couple questions:</p> <ol> <li><p>Any advise for someone just starting out? How do I navigate this self hosting hobby?</p></li> <li><p>What are security considerations when doing all this? Like how do I make this as secure as possible - i.e systems for better access restriction, logging/notifying of weird activity etc. specifically zero day exploits? </p></li> <li><p>I want to recreate AWS as a personal project, just so I can understand how it all works but obviously with very very limited functionality, I want to start by replicating ECS because I used docker in one of my last roles. How do I go about doing this? </p></li> <li><p>Any Linux Distros that are specialised for host

## Advice setting up Cloudflare tunnel with Nginx-Ingress for my web-app?
 - [https://www.reddit.com/r/selfhosted/comments/1hv0dga/advice_setting_up_cloudflare_tunnel_with](https://www.reddit.com/r/selfhosted/comments/1hv0dga/advice_setting_up_cloudflare_tunnel_with)
 - RSS feed: $source
 - date published: 2025-01-06T14:34:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I&#39;m new to using k8s, nginx-ingress, and Cloudflare tunnels in general, but I am hoping to securely host my web app for the purpose of testing and learning to use these tools for career advancement. Otherwise, I would imagine this setup is overkill.</p> <p>To break down the configuration I have:</p> <p>I have my gunicorn port binded to 0.0.0.0:5000 so it can internally expose ports to work in a docker container which I have in a k8s pod.</p> <p>I have the cloudflare tunnel setup with the tunnel-id and my domain along with a valid certificate for full strict ssl set.</p> <p>Nginx-ingress and k8s is all setup and running fine as well.</p> <p>This is all hosted on my local homeserver that I access with ssh.</p> <p>The problem seems to be the routing between the Cloudflare tunnel and the Nginx-controller from a couple of the tests I ran. I had a couple questions and would appreciate any help in getting this resolved.</p> <p>I&#39;m thinking

## Remote assistance self-hosted solutions tips?
 - [https://www.reddit.com/r/selfhosted/comments/1hv0cr7/remote_assistance_selfhosted_solutions_tips](https://www.reddit.com/r/selfhosted/comments/1hv0cr7/remote_assistance_selfhosted_solutions_tips)
 - RSS feed: $source
 - date published: 2025-01-06T14:33:14+00:00

<!-- SC_OFF --><div class="md"><p>I struggle to find anything other than RustDesk, which makes not great pool of candidates to select from.</p> <p>I am intrested in something that can be used as e.g. Google Remote Desktop, so not VNC, the other party needs to be able to watch and be in control.</p> <p>Last time I tried RustDesk, the app required extra (Accessiblity, if remember well) permissions on e.g. MacOS. It also appears to be leaning towards use of its own rustdesk.com.</p> <p>I would ideally want something completely self-contained. And most importantly, open source.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0cr7/remote_assistance_selfhosted_solutions_tips/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hv0cr7/remote_assistance_selfhosted_solutions_tips/">[comments]</a></span>

## BookStack in 2024: A review of funding, project evolution, maintenance, future plans, and a thanks to all those that have helped
 - [https://www.reddit.com/r/selfhosted/comments/1hv0bcx/bookstack_in_2024_a_review_of_funding_project](https://www.reddit.com/r/selfhosted/comments/1hv0bcx/bookstack_in_2024_a_review_of_funding_project)
 - RSS feed: $source
 - date published: 2025-01-06T14:31:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">/r/selfhosted</a>,</p> <p>I generally avoid posting here outside of comments since BookStack is already well known, and mentioned often in the sub, and I don&#39;t want to over-promote, but since it&#39;s been a while since my last post here I thought I&#39;d share this project update reviewing the project in 2024:</p> <p><a href="https://www.bookstackapp.com/blog/bookstack-in-2024/">https://www.bookstackapp.com/blog/bookstack-in-2024/</a></p> <p>TL;DR:</p> <ul> <li>I&#39;m now more than covering my living costs from project revenue (via donations, sponsors, support services).</li> <li>Thanks to that, I&#39;ve resumed growth in forwarded donations.</li> <li>Made good progress in 2024, but hindered by license change of our core editor.</li> <li>Looking forward to being a decade old in 2025, and thinking about getting other maintainers involved.</li> <li>A big thanks to those that have supported the project.</li> </ul> </div>

## CRM for sales manager
 - [https://www.reddit.com/r/selfhosted/comments/1huzwl5/crm_for_sales_manager](https://www.reddit.com/r/selfhosted/comments/1huzwl5/crm_for_sales_manager)
 - RSS feed: $source
 - date published: 2025-01-06T14:12:12+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I&#39;m looking for a CRM to handle sales agent. </p> <p>My sales agent do:</p> <ul> <li> add lead and client</li> <li>send proposal</li> <li>send automatic reminder by sms and email</li> <li>every month tell me how much I need to pay </li> </ul> <p>I prefer it&#39;s selfhosted. Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Elemis89"> /u/Elemis89 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huzwl5/crm_for_sales_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huzwl5/crm_for_sales_manager/">[comments]</a></span>

## Yet another notes app request - with encrypted sync
 - [https://www.reddit.com/r/selfhosted/comments/1huzt2w/yet_another_notes_app_request_with_encrypted_sync](https://www.reddit.com/r/selfhosted/comments/1huzt2w/yet_another_notes_app_request_with_encrypted_sync)
 - RSS feed: $source
 - date published: 2025-01-06T14:07:24+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m after a self-hosted notes application - of the gazillion available I can&#39;t quite find the right fit:</p> <ul> <li>Encrypted storage</li> <li>Web-based</li> <li>Preferably with table support</li> </ul> <p>The first point is the most important - I want to store sensitive information, but access it from anywhere - while hosted on a VPS.</p> <p>Currently I use a combination of:</p> <ul> <li>Nextcloud notes - works OK for non-sensitive stuff</li> <li>Joplin - encrypted sync works well but would much prefer web-based</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GuzziGuy"> /u/GuzziGuy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huzt2w/yet_another_notes_app_request_with_encrypted_sync/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huzt2w/yet_another_notes_app_request_with_encrypted_sync/">[comments]</a></span>

## Linkwarden (v2.9.0) - open-source collaborative bookmark manager to collect, organize, and preserve webpages, articles, and documents (tons of new features!) 🚀
 - [https://www.reddit.com/r/selfhosted/comments/1huzsjv/linkwarden_v290_opensource_collaborative_bookmark](https://www.reddit.com/r/selfhosted/comments/1huzsjv/linkwarden_v290_opensource_collaborative_bookmark)
 - RSS feed: $source
 - date published: 2025-01-06T14:06:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1huzsjv/linkwarden_v290_opensource_collaborative_bookmark/"> <img src="https://b.thumbs.redditmedia.com/Eo-kcq7W6pKfbVg37K1OcZHgo_TnfHjfngQ2fl8N-wo.jpg" alt="Linkwarden (v2.9.0) - open-source collaborative bookmark manager to collect, organize, and preserve webpages, articles, and documents (tons of new features!) 🚀" title="Linkwarden (v2.9.0) - open-source collaborative bookmark manager to collect, organize, and preserve webpages, articles, and documents (tons of new features!) 🚀" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Happy New Year! 🎉</p> <p>It&#39;s me, Daniel, and I&#39;m back with some huge updates for Linkwarden.</p> <p>For those who are new to Linkwarden, it&#39;s basically a tool for saving and organizing your bookmarks, articles, and documents in one place. You can also share your links with others, create public collections, and collaborate with your team. Linkwarden is available as a <a hr

## This is why I started buying (4K UHD) Blu-Rays again
 - [https://www.reddit.com/r/selfhosted/comments/1huzr9u/this_is_why_i_started_buying_4k_uhd_blurays_again](https://www.reddit.com/r/selfhosted/comments/1huzr9u/this_is_why_i_started_buying_4k_uhd_blurays_again)
 - RSS feed: $source
 - date published: 2025-01-06T14:04:58+00:00

<!-- SC_OFF --><div class="md"><p>Since my wife loved Arcane so much, I bought the 4K UHD Steelbook Season 1 Blu-Ray for her. Naturally, I put it on my Plex server since we don&#39;t actually own a 4K Blu-Ray player. Guess what the bitrate of these video files are...</p> <p><a href="https://imgur.com/aNTrPnB">94Mbps...</a></p> <p>Netflix with their most expensive &quot;4K&quot; subscriptions gets, I don&#39;t know, maybe 8-15Mbps if you&#39;re lucky on a good day?</p> <p>This show has never looked or sounded this good. And with a nice physical box to put in the shelf as an added bonus. It&#39;s nice to actually OWN something again rather than lease it from some big corporation.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Matvalicious"> /u/Matvalicious </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huzr9u/this_is_why_i_started_buying_4k_uhd_blurays_again/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/

## Batch Rename Feature on Synology NAS—Anyone Else Need This?
 - [https://www.reddit.com/r/selfhosted/comments/1huzpjn/batch_rename_feature_on_synology_nasanyone_else](https://www.reddit.com/r/selfhosted/comments/1huzpjn/batch_rename_feature_on_synology_nasanyone_else)
 - RSS feed: $source
 - date published: 2025-01-06T14:02:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1huzpjn/batch_rename_feature_on_synology_nasanyone_else/"> <img src="https://a.thumbs.redditmedia.com/vRoC3mtD1ejDwql3GFjwKT8TbP0RjM1EuG8hG-IT188.jpg" alt="Batch Rename Feature on Synology NAS—Anyone Else Need This?" title="Batch Rename Feature on Synology NAS—Anyone Else Need This?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Today, while organizing photo files on my Synology NAS, I just found out it doesn’t have a batch rename feature. That was kinda pain in the ass at that moment. My photo albums contain a huge number of pictures with messy filenames, manually renaming each file is a total nightmare. Especially when I need to standardize filenames based on criteria like date or location, editing them one by one is just too overwhelming.</p> <p>This made me think of another NAS I have on hand. I have a Synology for handling files and a Ugreen for media center and entertainment purposes. I remember the ug

## Receipt Wrangler January Update
 - [https://www.reddit.com/r/selfhosted/comments/1huz4hu/receipt_wrangler_january_update](https://www.reddit.com/r/selfhosted/comments/1huz4hu/receipt_wrangler_january_update)
 - RSS feed: $source
 - date published: 2025-01-06T13:35:29+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, and happy new year!</p> <p>For those of you that are new, welcome! Receipt Wrangler is a self-hosted, ai powered app that is meant to make managing receipts easy. Receipt Wrangler is capable of scanning your receipts from desktop uploads, mobile app scans, or via email, or entering manually. Users can itemize, categorize, and split them amongst users in the app. Check out <a href="https://receiptwrangler.io/">https://receiptwrangler.io/</a> for more information.</p> <p>A few weeks ago the 2025 roadmap for Receipt Wrangler was posted. Take a look <a href="https://www.reddit.com/r/selfhosted/comments/1hikbsy/receipt_wrangler_2025_roadmap/">https://www.reddit.com/r/selfhosted/comments/1hikbsy/receipt_wrangler_2025_roadmap/</a></p> <p>Otherwise lets jump into the development highlights of last month.</p> <p><strong>Development Highlights:</strong></p> <p><strong>Receipt Share Quick Actions (mobile):</strong> Users can now split receipts on mob

## Looking for a really simple contract lifecycle management app
 - [https://www.reddit.com/r/selfhosted/comments/1huyhwz/looking_for_a_really_simple_contract_lifecycle](https://www.reddit.com/r/selfhosted/comments/1huyhwz/looking_for_a_really_simple_contract_lifecycle)
 - RSS feed: $source
 - date published: 2025-01-06T13:02:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1huyhwz/looking_for_a_really_simple_contract_lifecycle/"> <img src="https://b.thumbs.redditmedia.com/WqWF2Ds7wDUc_tHnz1zqeC54Tq2JKt6IBJ1hopgc9JY.jpg" alt="Looking for a really simple contract lifecycle management app" title="Looking for a really simple contract lifecycle management app" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>Background:</strong></p> <p>I&#39;m running a small website and make money by offering my customers priority listing at the top of the page, just like many websites do.</p> <p>This is done manually, I want control over who I work with, so there can&#39;t be a self-checkout, so for this part there&#39;s little to no automation.</p> <p>It gets messy, e.g. with some customers I have a 1 month deal starting on the 5th, others book 2 months on the 9th, etc.</p> <p><strong>Now to the problem:</strong></p> <p>It turns out I&#39;m missing out on a significant share of income becau

## Local DNS issues
 - [https://www.reddit.com/r/selfhosted/comments/1huyho9/local_dns_issues](https://www.reddit.com/r/selfhosted/comments/1huyho9/local_dns_issues)
 - RSS feed: $source
 - date published: 2025-01-06T13:02:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to set up some local services to run through a reverse proxy so I can use subdomains rather than remembering port numbers. Thought it would be an easy job, I&#39;ve done it before; I got NGINX up and running, adguard home for DNS rewrites, and DHCP to advertise the server. </p> <p>Problem is, chrome (on both my phone and desktop) are ignoring it in favour secure DNS. I know I could delve onto the settings and disable that setting, but I&#39;d rather not need to on every single device ; somewhat defeats the point of broadcasting it with DHCP.</p> <p>Is there a solution? Can I set up a secure local DNS server that Chrome won&#39;t ignore? Issue there is presumably it then needs DNS to find the DNS server.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JustUseDuckTape"> /u/JustUseDuckTape </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huyho9/local_dns_issues/">[link]</a></sp

## In 2025, what plugins are you using for Jellyfin?
 - [https://www.reddit.com/r/selfhosted/comments/1huxlgq/in_2025_what_plugins_are_you_using_for_jellyfin](https://www.reddit.com/r/selfhosted/comments/1huxlgq/in_2025_what_plugins_are_you_using_for_jellyfin)
 - RSS feed: $source
 - date published: 2025-01-06T12:10:48+00:00

<!-- SC_OFF --><div class="md"><p>All Theme, Plugin or Customization suggestions are welcome..</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Zestyclose_Car1088"> /u/Zestyclose_Car1088 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huxlgq/in_2025_what_plugins_are_you_using_for_jellyfin/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huxlgq/in_2025_what_plugins_are_you_using_for_jellyfin/">[comments]</a></span>

## Synology DSM Authentik
 - [https://www.reddit.com/r/selfhosted/comments/1hux21h/synology_dsm_authentik](https://www.reddit.com/r/selfhosted/comments/1hux21h/synology_dsm_authentik)
 - RSS feed: $source
 - date published: 2025-01-06T11:36:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hux21h/synology_dsm_authentik/"> <img src="https://external-preview.redd.it/q5A9zVI8_D78q8aKZAi3GLy1BGFnawuUORSzBLisls0.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a64fd74da5707ca731f27c7a69f7d20fe8938923" alt="Synology DSM Authentik" title="Synology DSM Authentik" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hallo zusammen,</p> <p>ich versuche gerade Authentik als SSO-Server in meiner DSM zu integrieren und habe mit der Integration ins Synology DSM meine Probleme (andere Dienste funktionieren). Ich habe mich an dieser Anleitung orientiert:</p> <p><a href="https://docs.goauthentik.io/integrations/services/synology-dsm/">https://docs.goauthentik.io/integrations/services/synology-dsm/</a></p> <p>Leider bekomme ich nach einer erfolgreichen Anmeldung bei authentik diese Meldung:</p> <p><a href="https://preview.redd.it/98zz9g9j0dbe1.png?width=437&amp;format=png&amp;auto=webp&amp;s=622544d724ef20364624b9cc5

## WeTube:video, Music & Drama Player is now available on the Google Play Store!
 - [https://www.reddit.com/r/selfhosted/comments/1huwxb7/wetubevideo_music_drama_player_is_now_available](https://www.reddit.com/r/selfhosted/comments/1huwxb7/wetubevideo_music_drama_player_is_now_available)
 - RSS feed: $source
 - date published: 2025-01-06T11:27:26+00:00

<!-- SC_OFF --><div class="md"><p>Tired of ads ruining your entertainment? Meet <strong>WeTube</strong>, your ultimate solution for seamless and immersive experiences:</p> <p>💎 <strong>Ad-Free Play</strong>back: Watch videos, listen to music, and enjoy short dramas without interruptions.<br/> 🖼️ <strong>Picture-in-Picture</strong> Mode: Multitask effortlessly while keeping your content in view.<br/> 🎭 <strong>Short Dr</strong>amas: Perfect for quick entertainment on the go.<br/> 🎮 <strong>Interactive G</strong>ames: Play fan-favorites like Angry Birds Showdown and Trivia Crack.<br/> 📦 <strong>YouTube</strong> Sync: Log in to like, save, and subscribe to your favorite content creators.</p> <p>Say goodbye to interruptions and hello to endless entertainment. Best of all? It’s <strong>100% FREE</strong> and easy to use! 🚀</p> <p>🔗 Check it out here: <a href="https://play.google.com/store/apps/details?id=free.mor.mordo.do">WeTube: Video, Music&amp;Drama</a></p> <p>Let us know your thought

## People that run hoarer/linkwarden/ect - do you really use it and then, how?
 - [https://www.reddit.com/r/selfhosted/comments/1huwf9b/people_that_run_hoarerlinkwardenect_do_you_really](https://www.reddit.com/r/selfhosted/comments/1huwf9b/people_that_run_hoarerlinkwardenect_do_you_really)
 - RSS feed: $source
 - date published: 2025-01-06T10:53:44+00:00

<!-- SC_OFF --><div class="md"><p>I run hoarder for a few weeks and Its a very neet product I its easy to fill it up with things to save/read-later etc but I always got this feeling that is just put everything in very nice organized piles...that I will never again look in. </p> <p>So people that using this, how does your workflow look like, how much do you interact with your collection/pile of digital leftovers? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kranke"> /u/Kranke </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huwf9b/people_that_run_hoarerlinkwardenect_do_you_really/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huwf9b/people_that_run_hoarerlinkwardenect_do_you_really/">[comments]</a></span>

## Connect to wifi in different parts of the world
 - [https://www.reddit.com/r/selfhosted/comments/1huw5r6/connect_to_wifi_in_different_parts_of_the_world](https://www.reddit.com/r/selfhosted/comments/1huw5r6/connect_to_wifi_in_different_parts_of_the_world)
 - RSS feed: $source
 - date published: 2025-01-06T10:35:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi I&#39;m a complete noob and don&#39;t really understand all of this tech stuff but I thought that this is my best bet of getting my question answered. </p> <p>I&#39;m wondering if there&#39;s any way to connect to a wifi in a place I haven&#39;t been before. Me and my friend are trying to transfer some files but they can only be transfered on the same wifi. And we live on different continents so that&#39;s a bit difficult.</p> <p>Is there anything we can do or is this a lost caause? Could a VPN work?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Untamed-Catlady"> /u/Untamed-Catlady </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huw5r6/connect_to_wifi_in_different_parts_of_the_world/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huw5r6/connect_to_wifi_in_different_parts_of_the_world/">[comments]</a></span>

## No models installed in Whisper web-GUI
 - [https://www.reddit.com/r/selfhosted/comments/1huvvey/no_models_installed_in_whisper_webgui](https://www.reddit.com/r/selfhosted/comments/1huvvey/no_models_installed_in_whisper_webgui)
 - RSS feed: $source
 - date published: 2025-01-06T10:14:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I installed Whisper web-GUI a few days ago, from Pinokio. All seemed ok until i tried to transcribe an audio file, where nothing happened.</p> <p>After a long search, I saw that i don&#39;t have any model stored in the directory C:\pinokio\api\whisper-webui.git\app\models\Whisper\faster-whisper\models--Systran--faster-whisper-large-v2.</p> <p>I deleted whisper &amp; re-installed it but it&#39;s the same.</p> <p>I did it also on an other computer &amp; it&#39;s the same :-(</p> <p>How can i resolve this please ? is there an other way to install whisper web-gui ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/weyb06"> /u/weyb06 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huvvey/no_models_installed_in_whisper_webgui/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huvvey/no_models_installed_in_whisper_webgui/">[comments]</a></spa

## Power efficient way to keep Jellyfin running?
 - [https://www.reddit.com/r/selfhosted/comments/1huv3o4/power_efficient_way_to_keep_jellyfin_running](https://www.reddit.com/r/selfhosted/comments/1huv3o4/power_efficient_way_to_keep_jellyfin_running)
 - RSS feed: $source
 - date published: 2025-01-06T09:16:33+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I am new to setting up personal media server so just asking a question out there.</p> <p>I have a 5 year old MSI GF75 Thin laptop ( 9th Gen i7, Nvidia GTX 1650 ) lying around so I did setup jellyfin server on it, and I am planning to keep it running in a corner in my attic. But not sure if that&#39;s efficient way of doing it ( energy wise ). Does anyone knows how much power it will use and are there any optimizations I can do ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Competitive-Ad8846"> /u/Competitive-Ad8846 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huv3o4/power_efficient_way_to_keep_jellyfin_running/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huv3o4/power_efficient_way_to_keep_jellyfin_running/">[comments]</a></span>

## Kotaemon: Open source web-app to self-host your document collections and chat with them using LLM (Ollama & API-based)
 - [https://www.reddit.com/r/selfhosted/comments/1huuzuq/kotaemon_open_source_webapp_to_selfhost_your](https://www.reddit.com/r/selfhosted/comments/1huuzuq/kotaemon_open_source_webapp_to_selfhost_your)
 - RSS feed: $source
 - date published: 2025-01-06T09:09:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1huuzuq/kotaemon_open_source_webapp_to_selfhost_your/"> <img src="https://external-preview.redd.it/mO6PlkN8_avfoOMnW1crWBa8K98mgf-y5PPmcbrH0is.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=ef13292009723520509077becbc59cb0d02d141a" alt="Kotaemon: Open source web-app to self-host your document collections and chat with them using LLM (Ollama &amp; API-based)" title="Kotaemon: Open source web-app to self-host your document collections and chat with them using LLM (Ollama &amp; API-based)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi everyone, our team are happy to share our hobby project <code>Kotaemon</code> - an open-source web app to organize and chat with your document collections. </p> <p><a href="https://github.com/Cinnamon/kotaemon">https://github.com/Cinnamon/kotaemon</a></p> <p><a href="https://preview.redd.it/rlt0651l8cbe1.png?width=1080&amp;format=png&amp;auto=webp&amp;s=4cce8e5fb4619339c119cb

## VPS and reverse proxy.. whats your take?
 - [https://www.reddit.com/r/selfhosted/comments/1huuuf4/vps_and_reverse_proxy_whats_your_take](https://www.reddit.com/r/selfhosted/comments/1huuuf4/vps_and_reverse_proxy_whats_your_take)
 - RSS feed: $source
 - date published: 2025-01-06T08:57:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello community. Im curious on your thoghts on utilizing a VPS, wireguard and reverse proxy. Im about to redo the whole thing.</p> <p>Would you do swag on VPS directly, or would you do SWAG locally at home and just let the VPS tunnel the traffic?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GeggaBajt"> /u/GeggaBajt </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huuuf4/vps_and_reverse_proxy_whats_your_take/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huuuf4/vps_and_reverse_proxy_whats_your_take/">[comments]</a></span>

## jellyfin setup
 - [https://www.reddit.com/r/selfhosted/comments/1huutxy/jellyfin_setup](https://www.reddit.com/r/selfhosted/comments/1huutxy/jellyfin_setup)
 - RSS feed: $source
 - date published: 2025-01-06T08:56:42+00:00

<!-- SC_OFF --><div class="md"><p>i have jellyfin on a raspberrypi 4 that runs on a ubuntu server. i have no problem playing videos. but i&#39;ve noticed that Hardware acceleration is not enabled. should i enable it? can raspberrypi 4 support it? what do you think?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/saramon"> /u/saramon </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huutxy/jellyfin_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huutxy/jellyfin_setup/">[comments]</a></span>

## Running a mail server on VPS with Port 25/465 blocked
 - [https://www.reddit.com/r/selfhosted/comments/1huuhfq/running_a_mail_server_on_vps_with_port_25465](https://www.reddit.com/r/selfhosted/comments/1huuhfq/running_a_mail_server_on_vps_with_port_25465)
 - RSS feed: $source
 - date published: 2025-01-06T08:29:37+00:00

<!-- SC_OFF --><div class="md"><p>I want to run a mail server on a VPS with outgoing traffic to ports 25 and 465 blocked. Will this be a problem for outgoing email? Can I expect most mail servers to support port 587, or should I consider using an SMTP relay service to reliably deliver mail to servers that only support port 25?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/izmno"> /u/izmno </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huuhfq/running_a_mail_server_on_vps_with_port_25465/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huuhfq/running_a_mail_server_on_vps_with_port_25465/">[comments]</a></span>

## Need help to find hardware that supports and runs IA agents for personal use.
 - [https://www.reddit.com/r/selfhosted/comments/1huuadp/need_help_to_find_hardware_that_supports_and_runs](https://www.reddit.com/r/selfhosted/comments/1huuadp/need_help_to_find_hardware_that_supports_and_runs)
 - RSS feed: $source
 - date published: 2025-01-06T08:14:29+00:00

<!-- SC_OFF --><div class="md"><p>TIdr; Med student who wants to try this new tech in a device for personal use, with a 2000USD budget and at a loss for which requirements are best to run this programs with a reasonable futureproof.</p> <p>To begin with, I am not native in English, but I can use any software in this language; and also have intermediate knowledge on computers. I study medicine and have support from my institutions to use Al agents with research purposes and daily administrative tasks such as medical records. I really don&#39;t have a good idea on which hardware to pick (Tower or Laptop) and which specs are more favorable to run this type of program.</p> <p>I have a budget of 2000USD (before taxes and fees) for the complete set up. Optional specs can be bought later, and I have the means to get the components shipped to my country. I really need help regarding RAM, storage, processor, graphic card, operating system (that can run open source) and if I need any specifics

## Ideas for selfhosted software
 - [https://www.reddit.com/r/selfhosted/comments/1hutt8e/ideas_for_selfhosted_software](https://www.reddit.com/r/selfhosted/comments/1hutt8e/ideas_for_selfhosted_software)
 - RSS feed: $source
 - date published: 2025-01-06T07:39:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to find ideas for a selfhostable program to develop in my free time, but I just can&#39;t find anything. Is there anything that is underrepresented in the selfhosting space, that I could work on?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fusion63"> /u/Fusion63 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hutt8e/ideas_for_selfhosted_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hutt8e/ideas_for_selfhosted_software/">[comments]</a></span>

## Bind mount permissions in unprivileged LXC
 - [https://www.reddit.com/r/selfhosted/comments/1hurvq1/bind_mount_permissions_in_unprivileged_lxc](https://www.reddit.com/r/selfhosted/comments/1hurvq1/bind_mount_permissions_in_unprivileged_lxc)
 - RSS feed: $source
 - date published: 2025-01-06T05:30:23+00:00

<!-- SC_OFF --><div class="md"><p>Hi all! Over the past couple of weeks I’ve been slowly setting up my first ‘real’ Proxmox homelab. I&#39;ve been having an issue around storage permissions that has become a mountain from what I assume is a molehill, and am hoping for a little help. My apologies for the rambling long-windedness below!</p> <p><strong>Basic details:</strong> Lenovo P520, Xeon W-2135, 48GB, 256GB boot SSD, 1TB media SSD, 1080Ti + P1000, onboard GbE (eno1/vmbr0 assigned to management), dual Intel 10GbE (enp2s0f0/vmbr1 WAN, enp2s0f1/vmbr2 LAN).</p> <p>This setup is pretty temporary, and the storage configuration probably even less so. I’m waiting for 4x 2X18 SATA drives to provide the main media storage in a Z1 array, with some smaller capacity arrangement of redundant SSDs for critical documents, etc, and a redundant pair of boot drives. Then stage 2 is moving routing over to its own system (probably an N305 or its N355 successor) and replacing the P520 with something ne

## Docker
 - [https://www.reddit.com/r/selfhosted/comments/1hurltl/docker](https://www.reddit.com/r/selfhosted/comments/1hurltl/docker)
 - RSS feed: $source
 - date published: 2025-01-06T05:14:32+00:00

<!-- SC_OFF --><div class="md"><p>Just wondering what the best way to run docker containers through a vpn? I have nordvpn and am wanting multiple containers to to run through it. Would I be best just having a virtual machine connected to nord with docker installed with all the containers I want to run through the vpn on? Or is there a better way?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Formal_Regret8002"> /u/Formal_Regret8002 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hurltl/docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hurltl/docker/">[comments]</a></span>

## Best Way To Share Geotiff
 - [https://www.reddit.com/r/selfhosted/comments/1hurkzi/best_way_to_share_geotiff](https://www.reddit.com/r/selfhosted/comments/1hurkzi/best_way_to_share_geotiff)
 - RSS feed: $source
 - date published: 2025-01-06T05:13:13+00:00

<!-- SC_OFF --><div class="md"><p>So around this time last year I had gotten myself lost on a hiking trail thanks to outdated maps along with an outdated Google earth image (from 2016)</p> <p>Thankfully I was able to navigate myself to safety using my drone as sort of an overhead spotter</p> <p>But that gave me the idea of generating my own maps of all the trails. I&#39;m using WebODM to generate Geotiff images and I&#39;ve got quite a library now</p> <p>I&#39;d really like to share them with everyone at the trail head. At the main trail head we have a bulletin board where people can post fliers and stuff so I&#39;d like to post a QR code to a repository of my Geotiff maps. </p> <p>Ideally it will overlay their GPS location with the Geotiff overlaid on something like Google maps so they can use it while hiking</p> <p>Does anyone have a good idea on how I could get that done? Is there any software out there like that already? Maybe even an Android app so I don&#39;t have to actually h

## Securing Public-facing Jellyfin while keeping Apps usable
 - [https://www.reddit.com/r/selfhosted/comments/1hup6te/securing_publicfacing_jellyfin_while_keeping_apps](https://www.reddit.com/r/selfhosted/comments/1hup6te/securing_publicfacing_jellyfin_while_keeping_apps)
 - RSS feed: $source
 - date published: 2025-01-06T03:03:59+00:00

<!-- SC_OFF --><div class="md"><p>I’ve finally setup a VPS running Nginx Proxy Manager, and connected it to a VM on my home machine running docker, but before actually keeping it running, I’d rather lock the service itself down.</p> <p>What are y’all’s recommended ways to setup 2fa or authentication while still being able to use a Jellyfin app, like on iOS?</p> <p>I’ve never used authentik previously, but would that be an option, or would that stop me from using an app to access my media away from home?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/24-7Games"> /u/24-7Games </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hup6te/securing_publicfacing_jellyfin_while_keeping_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hup6te/securing_publicfacing_jellyfin_while_keeping_apps/">[comments]</a></span>

## How to safely share access publicly?
 - [https://www.reddit.com/r/selfhosted/comments/1huomnq/how_to_safely_share_access_publicly](https://www.reddit.com/r/selfhosted/comments/1huomnq/how_to_safely_share_access_publicly)
 - RSS feed: $source
 - date published: 2025-01-06T02:36:03+00:00

<!-- SC_OFF --><div class="md"><p>Hey there, I’m running a small app that I would like to share publicly just for a few people. I’ve a public IP address, so I can just set port forwarding on my Asus-Merlin router and it’s done. But I’m wondering is it safe enough to leave it like this. </p> <p>I usually use WireGuard to access my network but I cannot use it for this app. In perfect world I would use Cloudflare as a proxy an add their IP addresses to allowlist on the router. But it’s not possible, as I cannot set IP ranges on it. :(</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kubelke"> /u/kubelke </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huomnq/how_to_safely_share_access_publicly/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huomnq/how_to_safely_share_access_publicly/">[comments]</a></span>

## Is there a self-hosted image personalization service like NiftyImages?
 - [https://www.reddit.com/r/selfhosted/comments/1huolup/is_there_a_selfhosted_image_personalization](https://www.reddit.com/r/selfhosted/comments/1huolup/is_there_a_selfhosted_image_personalization)
 - RSS feed: $source
 - date published: 2025-01-06T02:34:54+00:00

<!-- SC_OFF --><div class="md"><p>Is there a self-hosted image personalization service like NiftyImages that I may download and use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yogigee"> /u/yogigee </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1huolup/is_there_a_selfhosted_image_personalization/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1huolup/is_there_a_selfhosted_image_personalization/">[comments]</a></span>

## Syncing folders like AppData on my NextCloud
 - [https://www.reddit.com/r/selfhosted/comments/1humevk/syncing_folders_like_appdata_on_my_nextcloud](https://www.reddit.com/r/selfhosted/comments/1humevk/syncing_folders_like_appdata_on_my_nextcloud)
 - RSS feed: $source
 - date published: 2025-01-06T00:48:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I was wondering how could I sync my AppData folder, or a folder that is not created in the Nextcloud folder. I want to like, when I connect my second pc to the nextcloud, it&#39;s AppData gets updated you know what I mean? Do you think it&#39;s possible? How?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hadesk1"> /u/Hadesk1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1humevk/syncing_folders_like_appdata_on_my_nextcloud/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1humevk/syncing_folders_like_appdata_on_my_nextcloud/">[comments]</a></span>

## Nextcloud Died... Time for a New Solution
 - [https://www.reddit.com/r/selfhosted/comments/1hume4w/nextcloud_died_time_for_a_new_solution](https://www.reddit.com/r/selfhosted/comments/1hume4w/nextcloud_died_time_for_a_new_solution)
 - RSS feed: $source
 - date published: 2025-01-06T00:47:32+00:00

<!-- SC_OFF --><div class="md"><p>Looking for some feedback on a filesyncing solution for users with Linux desktops and Android phones.</p> <p>Background: I&#39;ve had Nextcloud running on a RPi from a 64GB USB (OS disk) for a couple of years now. That OS drive finally died recently. So I needed to rebuild my Nextcloud installation. However, after I built it I had a ton of issues trying to get it to sync nicely with my desktop. I&#39;m tired of messing with it and I just need a file syncing solution.</p> <p>Context: I have four users who rely on Nextcloud as a backup to their desktop/laptop files. They do share files ocassionally but that is not a required featured. Primarily they need their files to sync across the network between their primary machine, their mobile device, and a central server for safe keeping.</p> <p>Technical Details: The entire home is a Linux Mint shop. Servers are all Ubuntu. I do have a RPi NAS with hmdirs that we&#39;ve not used in a while and I could go bac

## Cloudflare Tunnel with domain, Tailspin, or Dynamic DNS?
 - [https://www.reddit.com/r/selfhosted/comments/1hultfx/cloudflare_tunnel_with_domain_tailspin_or_dynamic](https://www.reddit.com/r/selfhosted/comments/1hultfx/cloudflare_tunnel_with_domain_tailspin_or_dynamic)
 - RSS feed: $source
 - date published: 2025-01-06T00:20:26+00:00

<!-- SC_OFF --><div class="md"><p>I am setting up a Raspberry Pi with Wireguard, Docker, Adguard Home, and a few other services but I need to decide how to remotely access via Wireguard.</p> <p>I think all my options are:</p> <ol> <li>Cloudflare Tunnel and custom domain</li> <li>Tailspin VPN</li> <li>Dynamic DNS service like DuckDNS or desec.io</li> </ol> <p>But I am not sure which to choose. Are one of these recommended over the others?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dungeon_Crawler_Carl"> /u/Dungeon_Crawler_Carl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hultfx/cloudflare_tunnel_with_domain_tailspin_or_dynamic/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hultfx/cloudflare_tunnel_with_domain_tailspin_or_dynamic/">[comments]</a></span>

## Migrate from Docker Compose + Traefik + Port Forward to Cloudflare Tunnels
 - [https://www.reddit.com/r/selfhosted/comments/1hulsk5/migrate_from_docker_compose_traefik_port_forward](https://www.reddit.com/r/selfhosted/comments/1hulsk5/migrate_from_docker_compose_traefik_port_forward)
 - RSS feed: $source
 - date published: 2025-01-06T00:19:20+00:00

<!-- SC_OFF --><div class="md"><p>I setup my homelab according to this: <a href="https://www.smarthomebeginner.com/docker-media-server-2024/">https://www.smarthomebeginner.com/docker-media-server-2024/</a></p> <p>It&#39;s working great, and I have three containers published via Traefik and subdomain secured by oAuth. I would like to switch to Cloudflared and block access based on geolocation, while also keeping Traefik and oAuth.</p> <p>Is this possible?</p> <p>I tried to follow a blog recommending the cloudflare companion app, but it looks to only work with Traefik2 and I have three. After getting everything setup I couldn&#39;t get it to resolve publically, nor could I see Cloudflare making DNS pointer for me.</p> <p>Any advise to add CF Tunnels to a stack already setup with Traefik3 and using a wildcard ACME and DNS setup for hostnames of containers?</p> <p>I do have the tunnel connected and healthy, just not being used currently.</p> </div><!-- SC_ON --> &#32; submitted by &#32; 

## Do you have a single reverse proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1hull0l/do_you_have_a_single_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1hull0l/do_you_have_a_single_reverse_proxy)
 - RSS feed: $source
 - date published: 2025-01-06T00:09:41+00:00

<!-- SC_OFF --><div class="md"><p>Do you use a front-end proxy that handles all connections? If so, what is your configuration?</p> <p>I figured it would be easiest to have a single proxy that gets a wildcard cert from LetsEncrypt and forwards connections to the right internal VM/Container accordingly. Thoughts on this?</p> <p>I am having trouble configuring NextCloud (apache2 running the code) being aware that it is receiving a secure connection, not insecure. I still get a warning saying my connection is insecure and the Grants process breaks with an insecure &quot;Grant access&quot; link.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FarhanYusufzai"> /u/FarhanYusufzai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hull0l/do_you_have_a_single_reverse_proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hull0l/do_you_have_a_single_reverse_proxy/">[comments]</a></s

## WAF + Reverse Proxy recommendation for some websites
 - [https://www.reddit.com/r/selfhosted/comments/1hulkj7/waf_reverse_proxy_recommendation_for_some_websites](https://www.reddit.com/r/selfhosted/comments/1hulkj7/waf_reverse_proxy_recommendation_for_some_websites)
 - RSS feed: $source
 - date published: 2025-01-06T00:09:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi all selfhosters.</p> <p>I&#39;m currently hosting some websites to the public with this current setup:</p> <p>- Cloudflare in front of everything</p> <p>- Nginx Proxy Manager</p> <p>- PHP-FPM + Apache Containers</p> <p>- 8G Firewall rules on .htaccess</p> <p>BIG PREMISE: I&#39;m often target of web attacks.</p> <p>Said so, I tried with many tools out there (e.g. Nessus, Nikto and ZAPROXY) to check for vulnerabilities and I must say websites I&#39;m hosting seem fine with it.</p> <p>However I feel Nginx Proxy Manager is bottlenecking me. Don&#39;t get me wrong, even under DDoS attacks before Cloudflare mitigation kicks in, it performs really well.</p> <p>Said so, I believe it is missing many important features, like inbuilt bot protection, malicious patterns, rate limiting, geo blocking etc etc.</p> <p>Some time ago I tried openappsec with NPM integration. Everything worked fine, except that when under DDoS attack it was draining all the resources 
