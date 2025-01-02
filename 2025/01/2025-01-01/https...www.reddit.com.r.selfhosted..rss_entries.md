# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Built a cozy IRC network from spare PC parts - come hang out if you'd like :)
 - [https://www.reddit.com/r/selfhosted/comments/1hrf90g/built_a_cozy_irc_network_from_spare_pc_parts_come](https://www.reddit.com/r/selfhosted/comments/1hrf90g/built_a_cozy_irc_network_from_spare_pc_parts_come)
 - RSS feed: $source
 - date published: 2025-01-01T23:08:23+00:00

<!-- SC_OFF --><div class="md"><p>I wanted to share a fun project I&#39;ve been working on. Remember the golden days of IRC? Well, I&#39;ve built my own IRC network using a frankenstein PC made from spare parts sitting in my living room 😄.</p> <p>Running UnrealIRCd 6 with full services suite, and I&#39;ve even created some cool custom bots:</p> <ul> <li>An AI assistant bot powered by Mistral (great for quick coding help!)</li> <li>A weather bot for checking conditions worldwide</li> <li>And more coming soon...</li> </ul> <p>It&#39;s been pretty stable so far, and we&#39;ve got a small but growing community of tech enthusiasts, music lovers and developers.</p> <p>Channels include spaces for:</p> <ul> <li>Tech discussions &amp; troubleshooting</li> <li>Music sharing &amp; discovery</li> <li>Creative projects</li> <li>Gaming meetups</li> <li>General chat &amp; community</li> </ul> <p>If you&#39;re interested in connecting to my living room and chatting with people all over the world, dr

## Surmai: Personal/family travel organizer
 - [https://www.reddit.com/r/selfhosted/comments/1hrf8he/surmai_personalfamily_travel_organizer](https://www.reddit.com/r/selfhosted/comments/1hrf8he/surmai_personalfamily_travel_organizer)
 - RSS feed: $source
 - date published: 2025-01-01T23:07:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello Community!</p> <p>I&#39;ve been working on a travel organization application for the past few months. I had tried a few subscription based services for personal travel but found their approach rather pushy and sometimes rather hostile. So I decided to make one myself. It&#39;s designed/intended to be self-hosted and at a point where I&#39;m happy using it myself. </p> <p>Alright, so the spiel:</p> <p>Surmai is a personal/family travel organizer. The app is built to solve 3 particular challenges while planning a trip:</p> <ol> <li>Allow collaborative planning between multiple people.</li> <li>Allow easy access to all the necessary artifacts during the course of the trip.</li> <li>Keep the data private.</li> </ol> <p>NOTE: This is a very very alpha stage project and under active development. Please report any issues using Github Issues.</p> <p>Github: <a href="https://github.com/rohitkumbhar/surmai">https://github.com/rohitkumbhar/surmai</a></p> 

## Adguardhome - Storing Logs in a log file
 - [https://www.reddit.com/r/selfhosted/comments/1hrf1oz/adguardhome_storing_logs_in_a_log_file](https://www.reddit.com/r/selfhosted/comments/1hrf1oz/adguardhome_storing_logs_in_a_log_file)
 - RSS feed: $source
 - date published: 2025-01-01T22:59:27+00:00

<!-- SC_OFF --><div class="md"><p>Help me to update this compose to write log under /home/sparky/SparkyApps/adguard/confdir/log/adguard.log</p> <p>I noticed it seems to be saving under a json file. But I need it to be a log text file format to add to the parser of Crowdsec. Anyway to achieve it? I tried following command given github. But I couldn&#39;t get the correct sytnaxt to make it work. </p> <blockquote> <p>services:</p> <p>adguardhome:</p> <p>image: adguard/adguardhome</p> <p>container_name: adguardhome</p> <p>restart: unless-stopped</p> <p>volumes:</p> <p>- /home/sparky/SparkyApps/adguard/workdir:/opt/adguardhome/work</p> <p>- /home/sparky/SparkyApps/adguard/confdir:/opt/adguardhome/conf</p> <p>ports:</p> <p>- &quot;192.168.1.111:53:53/tcp&quot; # DNS TCP</p> <p>- &quot;192.168.1.111:53:53/udp&quot; # DNS UDP</p> <p>- &quot;192.168.1.111:8443:443/tcp&quot; # Web interface (HTTPS)</p> <p>- &quot;192.168.1.111:8080:80/tcp&quot; # Web interface (HTTPS)</p> <p>- &quot;192.168.1.

## Network traffic monitoring + PiHole: options and tips
 - [https://www.reddit.com/r/selfhosted/comments/1hreea7/network_traffic_monitoring_pihole_options_and_tips](https://www.reddit.com/r/selfhosted/comments/1hreea7/network_traffic_monitoring_pihole_options_and_tips)
 - RSS feed: $source
 - date published: 2025-01-01T22:29:54+00:00

<!-- SC_OFF --><div class="md"><p>Hey there. So I have a homelab set up on raspberry pi 4 with pihole, currently filtering DNS requests. For some time I wanted to check what requests various devices on my network are making. I looked into possible options, but tbh my networking knowledge is lacking.</p> <p>Initial plan was to accept DNS requests on the rpi (as already is), route them to the monitoring container, collect data and then reroute to pihole for filtering. First I tried Zabbix, but struggled enormously with the set up. Out of frustration I put that on hold and switched to ntopng. While I did start it up successfully, it didn&#39;t seem to accept the incoming traffic nor to collect data.</p> <p>So my question is: is it even a viable plan to have two containers on the same host machine with one accepting traffic, collecting some data (currently I&#39;m only interested in what requests a device is making, size of traffic would be a &#39;nice to have&#39;) and then rerouting it

## Need Help with creating my own Minecraft Server to play with friends
 - [https://www.reddit.com/r/selfhosted/comments/1hredvf/need_help_with_creating_my_own_minecraft_server](https://www.reddit.com/r/selfhosted/comments/1hredvf/need_help_with_creating_my_own_minecraft_server)
 - RSS feed: $source
 - date published: 2025-01-01T22:29:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello there!<br/> I am an absolute beginner/noob, when it comes to hosting my own stuff, I&#39;ve never done this before. My plan is to create my own Minecraft Vanilla Server, so me and Friends can play together without getting scammed by all these hosting sites.<br/> Can someone give me Guidance (that I will be able to understand and follow) on how to make this thing/ where I can find some good and easy Tutorials for this?</p> <p>I got 16 GB of Ram<br/> CPU: AMD Ryzen 5 5500<br/> GPU: AMD Radeon RX 6650 XT</p> <p>I hope my specs are enough to run a 4-8 Player Server while I&#39;m playing on it without too much lagginess.<br/> Cheers!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ItisiYeet"> /u/ItisiYeet </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hredvf/need_help_with_creating_my_own_minecraft_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comme

## NGINX proxy hosts + large file download
 - [https://www.reddit.com/r/selfhosted/comments/1hrdy16/nginx_proxy_hosts_large_file_download](https://www.reddit.com/r/selfhosted/comments/1hrdy16/nginx_proxy_hosts_large_file_download)
 - RSS feed: $source
 - date published: 2025-01-01T22:09:17+00:00

<!-- SC_OFF --><div class="md"><p>I am bashing my head against the wall on this one. </p> <p>For the last couple of years, I have experimented off and on with file hosting as a way to share files with family(Photo&#39;s in a zip, 3d printed files, ISO&#39;s, etc.) across a number of service(Plik, GoKapi, and now Pingvin-share. Every time, I try to host the site behind my Nginx proxy, and every time, a file download will start and fail(think like 60 seconds in, connection time out, and then the download fails). I am currently using NPM but its always just been a basic Nginx proxy so I can get SSL termination at my network gateway.</p> <p>Here is my question: Is there something I am missing? Is Nginx trying to proxy my file stream in memory and running into OOM? Am I supposed to pass something to Nginx to tell it NOT to proxy a file stream? Is it a chunk size mismatch? When I directly expose these services to the internet, it works just fine. But every time the proxy chokes.</p> <p>Wha

## I want to create my own local MTV
 - [https://www.reddit.com/r/selfhosted/comments/1hrdumq/i_want_to_create_my_own_local_mtv](https://www.reddit.com/r/selfhosted/comments/1hrdumq/i_want_to_create_my_own_local_mtv)
 - RSS feed: $source
 - date published: 2025-01-01T22:05:14+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I&#39;d like to create a local music video streaming service for my personal entertainment.</p> <p>Here&#39;s my idea:</p> <ul> <li>I want to define a spotify playlist of my liked songs.</li> <li>This playlist should be compared to youtube, to see if there is a music video (e.g. artist + song name + official) for each song.</li> <li>I want to see a list of results to for &quot;quality assurance&quot;. I want to check/uncheck videos and send them to youtube-dl</li> </ul> <p>The next steps are already in place:</p> <ul> <li>from youtube-dl the videos will be sent into my trash-folder-structure and are picked up by Jellyfin and ersatzTV or dizquetv.</li> </ul> <p>Has someone done something like this? Or do you have ideas/hints how I can achieve this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zykooo"> /u/zykooo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hrdumq/i_want_to_create

## Using Authelia with internal 'home.arpa' domain
 - [https://www.reddit.com/r/selfhosted/comments/1hrdcdp/using_authelia_with_internal_homearpa_domain](https://www.reddit.com/r/selfhosted/comments/1hrdcdp/using_authelia_with_internal_homearpa_domain)
 - RSS feed: $source
 - date published: 2025-01-01T21:42:43+00:00

<!-- SC_OFF --><div class="md"><p>Anyone else here using Authelia for internal domains? I&#39;ve got authelia on &#39;auth.home.arpa&#39; and multiple services running on service1.home.arpa, service2.home.arpa, etc. My configuration seems to be broken with the latest version of Authelia (<a href="https://github.com/authelia/authelia/releases/tag/v4.38.18">v4.38.18</a>).</p> <p>On investigation, it seems that the reason is &#39;home.arpa&#39; is on the Public Suffix List as described here:</p> <p><a href="https://www.authelia.com/configuration/session/introduction/#domain">https://www.authelia.com/configuration/session/introduction/#domain</a></p> <p>I don&#39;t know why my configuration worked with the previous version, but rolling back seems to have temporarily resolved the issue.</p> <p>My configuration.yml looks like this:</p> <pre><code>session: cookies: - domain: &#39;home.arpa&#39; authelia_url: &#39;https://auth.home.arpa&#39; name: authelia_session #secret: provided by file e

## Should I use GitHub, instead of self-hosting Gitea? See, I only need Issues (not Git) and reliability is crucial to me.
 - [https://www.reddit.com/r/selfhosted/comments/1hrcy6v/should_i_use_github_instead_of_selfhosting_gitea](https://www.reddit.com/r/selfhosted/comments/1hrcy6v/should_i_use_github_instead_of_selfhosting_gitea)
 - RSS feed: $source
 - date published: 2025-01-01T21:25:24+00:00

<!-- SC_OFF --><div class="md"><h4>TL;DR</h4> <p>I need a reliable project management application so that ten non-technical people can collaborate effectively. Both GitHub Issues (on GitHub&#39;s free tier) and Gitea Issues would meet my needs.</p> <p>I’m planning to teach everyone Markdown. As a result, I’m not concerned about the common belief that non-technical people won&#39;t use Markdown.</p> <h4>My Experience</h4> <p>I’ve trialed around two dozen project management tools, including Vikunja, Plane, Leantime, Redmine, YouTrack, Trello, RT, and Mantis. Surprisingly, the ones I preferred most were GitHub Issues, Gitea Issues, and GitLab Issues.</p> <p>I successfully cloned my Issues from GitHub into a demo instance of Gitea, and I also downloaded my Issues from GitHub using a Python script. Although I ran the script manually, I could easily automate it to run, say, once or twice a day.</p> <p>Therefore, I am confident that if Microsoft (er, uh, I meant GitHub) were to shut down my

## Looking for a file sharing with a client portal.
 - [https://www.reddit.com/r/selfhosted/comments/1hrcwq2/looking_for_a_file_sharing_with_a_client_portal](https://www.reddit.com/r/selfhosted/comments/1hrcwq2/looking_for_a_file_sharing_with_a_client_portal)
 - RSS feed: $source
 - date published: 2025-01-01T21:23:42+00:00

<!-- SC_OFF --><div class="md"><p>I have been looking for a good file sharing with a client portal to share document to clients to see/download files.</p> <p>I have looked at projectsend but I haven&#39;t been able to make it work. For some reason it doesn&#39;t let me create a folders. For the people that use it, what version are you on and can you share a folder to a client?</p> <p>I have also tested nextcloud but the user experience has been confusing for clients.</p> <p>EDIT: what are other options?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ZeroNoPro"> /u/ZeroNoPro </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hrcwq2/looking_for_a_file_sharing_with_a_client_portal/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hrcwq2/looking_for_a_file_sharing_with_a_client_portal/">[comments]</a></span>

## Hosting behind CGNAT
 - [https://www.reddit.com/r/selfhosted/comments/1hrcp6t/hosting_behind_cgnat](https://www.reddit.com/r/selfhosted/comments/1hrcp6t/hosting_behind_cgnat)
 - RSS feed: $source
 - date published: 2025-01-01T21:14:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, Ive been racking my brain on how I could possibly host my services behind tmobiles cgnat. Used to do it fine when I had another ISP and a public IP to use but now im at a loss.</p> <p>My old ISP raised my cost from $50 to $175 without warning so we swapped to tmobiles. Saw no point in paying almost $200 for only 500Mbps when the avrage was ~350. Its looking like my only options are to try and make this work some how or take what id have to pay for a cloud server that would host my reverse proxy and just put it toward a different ISP.</p> <p>The goal: use a wildcard DNS entry on cloudflare so that I can specify whatever subdomain I want and have it direct over to my internal reverse proxy and thus to my internal services. I cant use any vpns or zerotrust solutions like twingate as they require something to be installed on the client.</p> <p>Whats been tried: Using cloudflare tunnels. While this works I would need to make a seperate DNS entry f

## Self Hosted VPN or Reverse SSH
 - [https://www.reddit.com/r/selfhosted/comments/1hrcl4g/self_hosted_vpn_or_reverse_ssh](https://www.reddit.com/r/selfhosted/comments/1hrcl4g/self_hosted_vpn_or_reverse_ssh)
 - RSS feed: $source
 - date published: 2025-01-01T21:09:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I have a few computers that I need to access specific ports on them, they are basically home PCs and connected to the internet which means they don&#39;t have dedicated IPs and also port forwarding isn&#39;t allowed.</p> <p>The computers are either Windows or Linux.</p> <p>I wanted a way to be able to access them or at least access a service running on a specific port.</p> <p>I own a VPS running Ubuntu with a dedicated IP.</p> <p>I read about reverse ssh which I didn&#39;t exactly understand how it works but it should allow me to access the service I want, however an issue is that the PC which is running windows is hard to setup reverse ssh on, it needs to be stable and also start on boot.</p> <p>Another solution came up to my mind is to setup a self hosted VPN and connect all the PCs, which should allow me to access them.</p> <p>Any guidance is appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/u

## What to run on new setup
 - [https://www.reddit.com/r/selfhosted/comments/1hrb1tq/what_to_run_on_new_setup](https://www.reddit.com/r/selfhosted/comments/1hrb1tq/what_to_run_on_new_setup)
 - RSS feed: $source
 - date published: 2025-01-01T19:59:50+00:00

<!-- SC_OFF --><div class="md"><p>Buying a new mini PC to get my main docker containers running on. Currently have a DS423 with plenty of storage so will be looking to integrate with it. Already running docker from the Synology but has an AMD CPU so image compatibility is an issue. </p> <p>Am thinking either Unraid or Proxmox (running a Linux host with docked and possibly a Windows VM). </p> <p>Happy with either, would just be good to hear pros and cons. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shoddy-Addendum1069"> /u/Shoddy-Addendum1069 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hrb1tq/what_to_run_on_new_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hrb1tq/what_to_run_on_new_setup/">[comments]</a></span>

## Looking to replace iCloud with self hosting - seeking input on cross-platform options
 - [https://www.reddit.com/r/selfhosted/comments/1hrav2c/looking_to_replace_icloud_with_self_hosting](https://www.reddit.com/r/selfhosted/comments/1hrav2c/looking_to_replace_icloud_with_self_hosting)
 - RSS feed: $source
 - date published: 2025-01-01T19:51:14+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR - Can I use NextCloud to host files and notes via an M4 Mac Mini and access them on Linux and Android?</p> <p>I&#39;m an Apple user looking to switch to Linux and Android. The main thing in my current Apple workflow that I would like to replace is iCloud for notes and file syncing+access on all devices.</p> <p>What I&#39;m looking for is a self-hosted solution that I can run from a base M4 Mac Mini with an external SSD and access my data on iOS, Linux, Android, and maybe Windows.</p> <p>Why do I want a Mac Mini? I do still need a Mac for occasional audio engineering in Logic, and M4 Minis are insanely power efficient. The base models are actually good value, so I&#39;d ideally just use it to host my cloud storage with a connected USB-C SSD. It&#39;d serve that occasional software need while running my cloud services with minimal power consumption and easy battery backup.</p> <p>I also will be transitioning in steps. First will be my main comput

## Sama Deploy - Self Hosted One-Click Docker Deployments on Hetzner with Automatic SSL
 - [https://www.reddit.com/r/selfhosted/comments/1hrav0k/sama_deploy_self_hosted_oneclick_docker](https://www.reddit.com/r/selfhosted/comments/1hrav0k/sama_deploy_self_hosted_oneclick_docker)
 - RSS feed: $source
 - date published: 2025-01-01T19:51:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>I&#39;m the founder of <a href="https://samadeploy.com">Samadeploy.com.</a></p> <p>In the last year, I launched multiple side projects and kept facing the same challenge: repeatedly setting up VPS servers on Hetzner from scratch. Each time, I had to look up my bookmarks and configs, which significantly slowed down my process.</p> <p>That&#39;s why I built Sama Deploy - an intuitive app with which you can:</p> <p>- Instantly provision Hetzner servers</p> <p>- Deploy any containerized app with a single click</p> <p>- Get SSL certificates automatically</p> <p>- Protect your sites from the public by easily adding basic auth</p> <p>- Edit the Docker Compose file directly in your browser</p> <p>Under the hood, I built on top of Docker and Caddy. So if you ever want to do something which you cannot yet do with my app, you could always just SSH into your server and adjust it yourself.</p> <p>I built this solution to solve my own deploymen

## Making sense of Proxmox bootloaders
 - [https://www.reddit.com/r/selfhosted/comments/1hrar1i/making_sense_of_proxmox_bootloaders](https://www.reddit.com/r/selfhosted/comments/1hrar1i/making_sense_of_proxmox_bootloaders)
 - RSS feed: $source
 - date published: 2025-01-01T19:46:25+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p>Better formatted at <a href="https://free-pmx.github.io/insights/bootloaders/">GitHub Pages</a> - <em>NO</em> referral / ads / tracking</p> </blockquote> <hr/> <p>Proxmox installer can be quite mysterious, it will try to support all kinds of systems, be it UEFI <a href="https://uefi.org/sites/default/files/resources/UEFI_Spec_2_9_2021_03_18.pdf"><sup>1</sup></a> or BIOS <a href="https://www.scs.stanford.edu/nyu/04fa/lab/specsbbs101.pdf"><sup>2</sup></a> and let you choose several very different filesystems on which the host system will reside. But on one popular setup - <em>UEFI system without SecureBoot on ZFS</em> - it will set you up, out of blue, with a different bootloader than all the others - and it is NOT blue - as GRUB <a href="https://www.gnu.org/software/grub/"><sup>3</sup></a> would have been. This is, nowadays, completely unnecessary and confusing.</p> <h2>UEFI or BIOS</h2> <p>There are two widely known types of starting up 

## Thoughts on which NAS OS for a UGREEN DXP2800
 - [https://www.reddit.com/r/selfhosted/comments/1hrac9n/thoughts_on_which_nas_os_for_a_ugreen_dxp2800](https://www.reddit.com/r/selfhosted/comments/1hrac9n/thoughts_on_which_nas_os_for_a_ugreen_dxp2800)
 - RSS feed: $source
 - date published: 2025-01-01T19:28:10+00:00

<!-- SC_OFF --><div class="md"><p>Looks like a great community here. Thanks for listening in advance.</p> <p>I&#39;ve been a Synology user (first NAS) for a few years. Purchased their low-end DS220J with two 2TB Iron Wolf HDDs. Have them raided (RAID 1) and an external 300MB external USB SSD attached (which I just use as a second backup of my media folders). So I have 1.8TB of usable storage, which is fine for the below that I&#39;ve listed.</p> <p>Need to move on since that NAS comes with only 512MB of RAM and not upgradeable. Tried installing Home Assistant, but no go. Simple movement within the DSM software drags, etc.</p> <p>So I purchased a UGREEN 2-bay DXP2800 and a 16GB RAM card (which will replace the 8MB card that comes installed (only one RAM slot unfortunately)).</p> <p>What I have and want going forward, in order of importance:</p> <ol> <li>Raid 1 for the two drives</li> <li>Backup of critical local device folders - I have 3 PCs running Linux (Synology uses the desktop ap

## Best TinyPC for multiple services.
 - [https://www.reddit.com/r/selfhosted/comments/1hr9zul/best_tinypc_for_multiple_services](https://www.reddit.com/r/selfhosted/comments/1hr9zul/best_tinypc_for_multiple_services)
 - RSS feed: $source
 - date published: 2025-01-01T19:13:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! This is my first post here but i have been lurking for a while and started loving the idea of self hosting some services!</p> <p>More precisely i am thinking of hosting 2-3 MC servers possibly one of them modded. (Only one of them will see real usage at a time. Also i would like to set up a VPN and a little time machine setup to back up my macs.</p> <p>The thing doesn&#39;t have to be blazingly fast for me but i would like the Minecraft servers to run smoothly at least.</p> <p>So now i want to ask those with experience which TinyPCs and specs they would recommend and think would work for my use cases.</p> <p>Kind regards, a (hopefully) future server operator ;)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MacRedditorXD"> /u/MacRedditorXD </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr9zul/best_tinypc_for_multiple_services/">[link]</a></span> &#32; <span><a href="https:

## Proxmox and Synology?
 - [https://www.reddit.com/r/selfhosted/comments/1hr9wrx/proxmox_and_synology](https://www.reddit.com/r/selfhosted/comments/1hr9wrx/proxmox_and_synology)
 - RSS feed: $source
 - date published: 2025-01-01T19:09:32+00:00

<!-- SC_OFF --><div class="md"><p>I run a pretty powerful Proxmox machine that handles all my services and vms as well as an offsite Proxmox backup server. However for Christmas I was gifted a DiskStation DS214+ that was never used by a friend. Do I have any reason to keep this? Does anybody run both Proxmox and Synology in their homes? If so, why?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PhaseDirect4273"> /u/PhaseDirect4273 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr9wrx/proxmox_and_synology/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr9wrx/proxmox_and_synology/">[comments]</a></span>

## Odin - a self-hosted FOSS streaming service.
 - [https://www.reddit.com/r/selfhosted/comments/1hr9v3i/odin_a_selfhosted_foss_streaming_service](https://www.reddit.com/r/selfhosted/comments/1hr9v3i/odin_a_selfhosted_foss_streaming_service)
 - RSS feed: $source
 - date published: 2025-01-01T19:07:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey, I just published a self-hosted streaming service, it&#39;s called Odin. Odin comes in two parts, a server and an Android app. Both can be found on GitHub, with their install instructions.</p> <p>Odin Server <a href="https://github.com/ad-on-is/odin-server">https://github.com/ad-on-is/odin-server</a></p> <p>Odin TV App <a href="https://github.com/ad-on-is/odin-tv">https://github.com/ad-on-is/odin-tv</a></p> <h2>Motivation:</h2> <p>I&#39;ve used many of the readily available apps in the past, and they all came with their pros and cons. I was mostly annoyed by the fact, that most of them use their own server-backend, somewhere. So each time, the app stops working, I didn&#39;t know whether their server just crashed, or the developer abandoned the app and I had to look for something else. I also started becoming paranoid, whether someone was collecting my data and offering them to &quot;the highest bidder&quot;. Oh, and I also disliked the UI of the

## Why does self-hosted VPN runs slow for me?
 - [https://www.reddit.com/r/selfhosted/comments/1hr8ms1/why_does_selfhosted_vpn_runs_slow_for_me](https://www.reddit.com/r/selfhosted/comments/1hr8ms1/why_does_selfhosted_vpn_runs_slow_for_me)
 - RSS feed: $source
 - date published: 2025-01-01T18:14:03+00:00

<!-- SC_OFF --><div class="md"><p>I have switched to multiple cloud providers(Digital Ocean, Racknerd, Local)always with basic/essential plans like 2GB ram 2 core or similar.<br/> Not something demanding assuming it doesn&#39;t take that much resources to deliver maximum bandwidth</p> <p>My internet speed is 250mbps<br/> I have deployed VPN thrice using OpenVPN and Wireguard.<br/> I barely get 40-60mbps.<br/> When I run speedtest on VPS instance it comes out good, around 800-1500mbps</p> <p>What could be the reason?</p> <p>Also from your experience does provider ban you if you utilise a lot of bandwidth?<br/> I consume 3-5TB data per month</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Natural_Home_769"> /u/Natural_Home_769 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr8ms1/why_does_selfhosted_vpn_runs_slow_for_me/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr8ms1/why_does_s

## Audio and Video out of sync in jellyfin on firestick
 - [https://www.reddit.com/r/selfhosted/comments/1hr8mnu/audio_and_video_out_of_sync_in_jellyfin_on](https://www.reddit.com/r/selfhosted/comments/1hr8mnu/audio_and_video_out_of_sync_in_jellyfin_on)
 - RSS feed: $source
 - date published: 2025-01-01T18:13:53+00:00

<!-- SC_OFF --><div class="md"><p>I have recently experienced intermittent issues with the audio and video being out of sync on a firestick 4k. I read up on this issue and it seems like people recommend switching the player to exoplayer from libvlc or something, but I can’t seem to find this option in the jellyfin settings on firestick. All I see is a checkbox to use an external player. Was this player option removed, and if not can someone point me to it? And does anyone have any advice on how to fix the audio/video sync issue? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OverThinkingTinkerer"> /u/OverThinkingTinkerer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr8mnu/audio_and_video_out_of_sync_in_jellyfin_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr8mnu/audio_and_video_out_of_sync_in_jellyfin_on/">[comments]</a></span>

## Caddy + Docker Networks break me
 - [https://www.reddit.com/r/selfhosted/comments/1hr8daz/caddy_docker_networks_break_me](https://www.reddit.com/r/selfhosted/comments/1hr8daz/caddy_docker_networks_break_me)
 - RSS feed: $source
 - date published: 2025-01-01T18:02:18+00:00

<!-- SC_OFF --><div class="md"><p>Hello you wonderful people :&gt;</p> <p>recently after some minor fiddling i was able to successfully setup caddy as a reverse proxy for authentik and other apps.</p> <p>Quick background information, i am using docker and a separate docker network between caddy and authentik + etc.</p> <p>The first &quot;problem&quot; i encountered was that Authentik and another app (Netbox) could not check for version upgrades, which means they cannot access my LAN directly.</p> <p>Is there a way i can allow Authentik (or any other docker stack) to communicate to the hosts network without exposing its services that way?</p> <p>The Second problem, when i was trying to setup Kitchenowl with Authentik as OIDC provider, the Kitchenowl stack cannot reach my Authentik instance.</p> <p>Authentik sits behind caddy on authentik.dom.tld.</p> <p>I am sure these problem have the same root cause but i cannot get my head around it.<br/> After multiple sessions with hours of resea

## Looking for a Media Server that can do this
 - [https://www.reddit.com/r/selfhosted/comments/1hr7fc7/looking_for_a_media_server_that_can_do_this](https://www.reddit.com/r/selfhosted/comments/1hr7fc7/looking_for_a_media_server_that_can_do_this)
 - RSS feed: $source
 - date published: 2025-01-01T17:20:33+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve recently started exploring self-hosting and want to set up a media server. Currently, I use Stremio with Torrentio, but it&#39;s not ideal because 4K HDR movies often buffer. I want to download movies in advance and store them on my server for smooth playback on any device in my network, like a TV, phone, or PC. </p> <p>I&#39;m looking for a media server that lets me browse and queue movie torrents for downloading directly to the server, and then stream them to my devices once downloaded. I&#39;ve heard good things about Jellyfin, but it seems to only manage an existing media library that you manually create.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CarlosLockward"> /u/CarlosLockward </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr7fc7/looking_for_a_media_server_that_can_do_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr7fc7

## Looking for a wiki with PDF embedding and linking
 - [https://www.reddit.com/r/selfhosted/comments/1hr7dl5/looking_for_a_wiki_with_pdf_embedding_and_linking](https://www.reddit.com/r/selfhosted/comments/1hr7dl5/looking_for_a_wiki_with_pdf_embedding_and_linking)
 - RSS feed: $source
 - date published: 2025-01-01T17:18:18+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for a wiki that can support a very specific use. I need it to have the ability to embed a master PDF. The other pages in the wiki will reference the PDF and be able to hyperlink directly to the referenced section. I tried BookStack but ran into two issues:</p> <p>1) This is running in docker on Synology, finding the .env for BookStack to raise the max upload size to accommodate the PDF proved to be impossible for me. </p> <p>2) Embedding PDFs is not native, so even when testing a different PDF by embedding through a Head Content customization, I don&#39;t see how you could link to a specific portion of the PDF.</p> <p>It feels like I&#39;m trying to fit a square peg into a round hole with BookStack. Does anyone know of a wiki that might better suit my needs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bamfcoco1"> /u/bamfcoco1 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments

## SMTP2GO Free Plan - Spam Score?
 - [https://www.reddit.com/r/selfhosted/comments/1hr7bi5/smtp2go_free_plan_spam_score](https://www.reddit.com/r/selfhosted/comments/1hr7bi5/smtp2go_free_plan_spam_score)
 - RSS feed: $source
 - date published: 2025-01-01T17:15:35+00:00

<!-- SC_OFF --><div class="md"><p>I spotted this in another thread here at selfhosted:</p> <p><a href="https://www.smtp2go.com/pricing/">https://www.smtp2go.com/pricing/</a></p> <p>1000 outgoing emails per month is free.</p> <p>It makes me worry that spammers will use that service and give a bad reputation to their IPs so that a lot of emails will end up in spam folders. But from what I can see so far, it seems like they actually have a good score?</p> <p>Anyone else here using their free plan and can say whether they are good? I&#39;m just interested in sending like 5 outgoing emails a month for personal use.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pilkyton"> /u/pilkyton </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr7bi5/smtp2go_free_plan_spam_score/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr7bi5/smtp2go_free_plan_spam_score/">[comments]</a></span>

## Synology NAS Bootstrapper ✴
 - [https://www.reddit.com/r/selfhosted/comments/1hr6lfm/synology_nas_bootstrapper](https://www.reddit.com/r/selfhosted/comments/1hr6lfm/synology_nas_bootstrapper)
 - RSS feed: $source
 - date published: 2025-01-01T16:42:26+00:00

<!-- SC_OFF --><div class="md"><p>Bootstrap your Synology NAS setup with automatic provisioning for: filesystem structure, shares, docker user, docker group, permissions, network, container orchestration and `.env` variables.</p> <p><a href="https://github.com/erwinkramer/synology-nas-bootstrapper?tab=readme-ov-file#synology-nas-bootstrapper-">erwinkramer/synology-nas-bootstrapper: Bootstrap your Synology NAS setup with automatic provisioning for: filesystem structure, shares, docker user, docker group, permissions, network, container orchestration and `.env` variables.</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JumpLegitimate8762"> /u/JumpLegitimate8762 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr6lfm/synology_nas_bootstrapper/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr6lfm/synology_nas_bootstrapper/">[comments]</a></span>

## Do you recommend hosting plex away from home
 - [https://www.reddit.com/r/selfhosted/comments/1hr6bn7/do_you_recommend_hosting_plex_away_from_home](https://www.reddit.com/r/selfhosted/comments/1hr6bn7/do_you_recommend_hosting_plex_away_from_home)
 - RSS feed: $source
 - date published: 2025-01-01T16:29:45+00:00

<!-- SC_OFF --><div class="md"><p>I will be a college student soon, but i also want to self host and I obviously can&#39;t do it in my college. Is it recommended to host a plex media server in my house to be mainly accessed outside, with typical household internet speeds, with my own paid domain, or should i wait another 4 years</p> <p>Plex would definitely be helpful for my mom, but i don&#39;t think she understands that a server running 24x7 is still cheaper than Amazon + Netflix combined (ive tried)</p> <p>Edit- 30mpbs upgradeable to 100</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PSSGAMER"> /u/PSSGAMER </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr6bn7/do_you_recommend_hosting_plex_away_from_home/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr6bn7/do_you_recommend_hosting_plex_away_from_home/">[comments]</a></span>

## How can I create actual urls for my self hosted apps?
 - [https://www.reddit.com/r/selfhosted/comments/1hr5s1p/how_can_i_create_actual_urls_for_my_self_hosted](https://www.reddit.com/r/selfhosted/comments/1hr5s1p/how_can_i_create_actual_urls_for_my_self_hosted)
 - RSS feed: $source
 - date published: 2025-01-01T16:04:07+00:00

<!-- SC_OFF --><div class="md"><p>Using the format of &lt;ip address/hostname&gt;:&lt;app port&gt; is fine and all, but I&#39;d like to route them to slightly more descriptive urls, especially since I currently have my home lab split between two servers</p> <p>Like for Jellyfin, instead of doing &quot;host-name:8096&quot;, I&#39;d like to do something like &quot;jellyfin.host.name&quot; </p> <p>Is this something I have to do on my router? I&#39;d like to add that I intend to keep this only on my local network and both hosts on my server run CasaOS</p> <p>It&#39;s not imperative that I do this, but I do think it&#39;d be nice</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/avi-the-tiger-rawr"> /u/avi-the-tiger-rawr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr5s1p/how_can_i_create_actual_urls_for_my_self_hosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr5s1p/how_can_i_crea

## Self hostes streamflix?
 - [https://www.reddit.com/r/selfhosted/comments/1hr59g0/self_hostes_streamflix](https://www.reddit.com/r/selfhosted/comments/1hr59g0/self_hostes_streamflix)
 - RSS feed: $source
 - date published: 2025-01-01T15:38:44+00:00

<!-- SC_OFF --><div class="md"><p>I want an app i can use to pirate movies and such.i saw streamflix but idk if its self hostable. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AndrexOnTop"> /u/AndrexOnTop </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr59g0/self_hostes_streamflix/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr59g0/self_hostes_streamflix/">[comments]</a></span>

## Is there a way to backup and restore Docker Containers and Volumes?
 - [https://www.reddit.com/r/selfhosted/comments/1hr4v3g/is_there_a_way_to_backup_and_restore_docker](https://www.reddit.com/r/selfhosted/comments/1hr4v3g/is_there_a_way_to_backup_and_restore_docker)
 - RSS feed: $source
 - date published: 2025-01-01T15:18:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I’ve had a home server setup for awhile now using.. MacOS Mojave and it’s been giving me reliability issues recently, hence why I want to switch to Debian. </p> <p>The issue is I’ve built up many containers with their own configurations and files that I can’t afford to lose. It’s one thing to backup the containers, but if there’s a way to backup all of my data in docker, that would be a great help, thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Kthor426"> /u/Kthor426 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr4v3g/is_there_a_way_to_backup_and_restore_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr4v3g/is_there_a_way_to_backup_and_restore_docker/">[comments]</a></span>

## Seeking advice to isolate docker container
 - [https://www.reddit.com/r/selfhosted/comments/1hr4r23/seeking_advice_to_isolate_docker_container](https://www.reddit.com/r/selfhosted/comments/1hr4r23/seeking_advice_to_isolate_docker_container)
 - RSS feed: $source
 - date published: 2025-01-01T15:12:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello colleagues,</p> <p>I have a WireGuard Easy Docker instance that allows me to connect to all my home services from anywhere.</p> <p>This instance is behind Traefik and shares a Docker network with all the other containers.</p> <p>Recently, I need to deploy a new Docker image that is isolated from all the others, allowing people to connect to it without being able to access any other containers.</p> <p>I’ve been trying to come up with solutions but haven’t been able to formulate a solid one yet. Lately, I’ve been considering whether I could create multiple subnets with WireGuard Easy and separate clients into those, but I’m not sure if that would be the best solution either.</p> <p>Could you please help me or recommend how to proceed? (I don’t think Cloudflared would work, as this image exposes more than just HTTP services.)</p> <p>Thank you very much!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/saek13">

## Looking for a Self Hosted Scaper/Archiver/Search Engine
 - [https://www.reddit.com/r/selfhosted/comments/1hr4cy5/looking_for_a_self_hosted_scaperarchiversearch](https://www.reddit.com/r/selfhosted/comments/1hr4cy5/looking_for_a_self_hosted_scaperarchiversearch)
 - RSS feed: $source
 - date published: 2025-01-01T14:51:42+00:00

<!-- SC_OFF --><div class="md"><p>Howdy folks, I&#39;m looking for a tool to accomplish a few goals that I&#39;ve had in mind for a while:<br/> 1. Archive every site I visit (including media, I already have the list of urls captured daily)<br/> 2. Create a full text search (engine) of all of the archived / crawled content<br/> 3. Be able to detect / visualize connected sites (maps) and link rot </p> <p>I&#39;m trying to determine if there is something that already does all of this (or could with minor modification) or if I&#39;m going to need to put a few pieces together myself. I presently have an ELK stack that I could probably coax into doing all of that but I don&#39;t want to reinvent the wheel if possible.<br/> Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CaptianCrypto"> /u/CaptianCrypto </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr4cy5/looking_for_a_self_hosted_scaperarchiversearch/">[link]</a></spa

## Host ARK: Survival Ascended Servers on Linux – A Self-Hosted Docker-Free Solution
 - [https://www.reddit.com/r/selfhosted/comments/1hr3ubx/host_ark_survival_ascended_servers_on_linux_a](https://www.reddit.com/r/selfhosted/comments/1hr3ubx/host_ark_survival_ascended_servers_on_linux_a)
 - RSS feed: $source
 - date published: 2025-01-01T14:22:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m the developer of the <strong>ARK: Survival Ascended Linux Server Manager</strong>, a script designed for self-hosting <strong>ARK: Survival Ascended servers</strong> on Linux. Since the game doesn’t provide a native Linux server, I created this tool to fill the gap, avoiding Docker and making server management straightforward.</p> <h3>Why is it relevant for self-hosters?</h3> <ul> <li><strong>Open Source</strong>: Available on GitHub, so you can inspect, modify, or contribute.</li> <li><strong>Full Control</strong>: Ideal for managing multiple instances with isolated configurations and automated clustering.</li> <li><strong>Interactive and Beginner-Friendly</strong>: Includes a menu-driven interface for easy setup and management.</li> <li><strong>CLI for Advanced Users</strong>: Supports automation with cron jobs for tasks like restarts, updates, and backups.</li> </ul> <h3>Key Features:</h3> <ul> <li><strong>No Docker Require

## Reverse proxy for ssh?
 - [https://www.reddit.com/r/selfhosted/comments/1hr3u2w/reverse_proxy_for_ssh](https://www.reddit.com/r/selfhosted/comments/1hr3u2w/reverse_proxy_for_ssh)
 - RSS feed: $source
 - date published: 2025-01-01T14:22:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been looking for options to host some kind of reverse proxy for ssh, I need some way to unify the access of all my servers on a single port and IP.</p> <p>When I was searching, I found sshpiper, which seemed to be exactly what I was looking for, although I couldn&#39;t get it to work with Docker, apart from its poor documentation, does anyone know of a similar option?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LeonardoIz"> /u/LeonardoIz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr3u2w/reverse_proxy_for_ssh/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr3u2w/reverse_proxy_for_ssh/">[comments]</a></span>

## Using a TV box as a server
 - [https://www.reddit.com/r/selfhosted/comments/1hr3rpg/using_a_tv_box_as_a_server](https://www.reddit.com/r/selfhosted/comments/1hr3rpg/using_a_tv_box_as_a_server)
 - RSS feed: $source
 - date published: 2025-01-01T14:18:31+00:00

<!-- SC_OFF --><div class="md"><p>Sold my old PC last year before I knew the bliss of self hosting. The only extra device i have rn is an androidT V box advertised to be capable of 4k output.</p> <p>Can i use it as a home server connected to 2 or 3 harddrives with a appropriate RAID 2 config??</p> <p>For context some services i hope to run are Jellyfin (with natively supported files, so hopefully no video encoding), Radarr, Sonarr, other similar services, Vaultwarden, SimpleLogin (i own a domain), bookmarking, code snippets, Immich, NextCloud, and maybe a communcation app for my significant other, but that&#39;s optional</p> <p>CPU: Cortex-A53 Quad-core 64bit, 1.5Ghz</p> <p>GPU: Mali-450 750MHz</p> <p>RAM: 2GB DDR3</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PSSGAMER"> /u/PSSGAMER </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr3rpg/using_a_tv_box_as_a_server/">[link]</a></span> &#32; <span><a href="https://www.redd

## Tailscale and N8N webhook problem
 - [https://www.reddit.com/r/selfhosted/comments/1hr33vk/tailscale_and_n8n_webhook_problem](https://www.reddit.com/r/selfhosted/comments/1hr33vk/tailscale_and_n8n_webhook_problem)
 - RSS feed: $source
 - date published: 2025-01-01T13:39:15+00:00

<!-- SC_OFF --><div class="md"><p>I am using Coolify on my home server as a deployment platform. I use Tailscale for secure access to my server.</p> <p>Currently, I have deployed n8n, and I can only use it if I have the Tailscale client installed. I need to configure a webhook for n8n and make it public. I&#39;m trying to use Tailscale Funnel. I open port 5678 (using tailscale funnel 5678), and while the webhook works when this port is open, all other services, including Coolify, become inaccessible from my domain (coolify.domen.dev).</p> <p>I moved Traefik to port 8443 and forwarded Tailscale Funnel 5678 to port 8443, but it didn&#39;t work. Now, when I enable tailscale funnel 8443, all services on the server work, but the webhook does not.</p> <p>I am new to configurations, and these are my first attempts at setting up a home server. I would appreciate any advice, and I can also provide logs if needed.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.co

## Calibre-Web Cover Image Dark
 - [https://www.reddit.com/r/selfhosted/comments/1hr2eix/calibreweb_cover_image_dark](https://www.reddit.com/r/selfhosted/comments/1hr2eix/calibreweb_cover_image_dark)
 - RSS feed: $source
 - date published: 2025-01-01T12:54:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hr2eix/calibreweb_cover_image_dark/"> <img src="https://b.thumbs.redditmedia.com/2y0nrfBY94mnrzIldwuZBSFb8_-qoxEb096cn2biXWI.jpg" alt="Calibre-Web Cover Image Dark" title="Calibre-Web Cover Image Dark" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey guys</p> <p>I have this weird image problem. When I import a book and fetch the metadata from an online source, the cover image goes dark if I use the link that is populated. If I don&#39;t use the link and use the one from the book itself, it displays fine. But some books don&#39;t have the cover image as their first page.</p> <p>Does anyone know why this happens? I am using the Docker-Compose file from LinuxServer .io and I am running it in Linux Mint.</p> <p><a href="https://preview.redd.it/alsi38j8qdae1.png?width=3840&amp;format=png&amp;auto=webp&amp;s=0f35b999ec61114c0719beec9bde29e8699eb68c">Importing Book and Fetching Metadata</a></p> <p><a href="https:

## Calibre-Web COver Image Dark
 - [https://www.reddit.com/r/selfhosted/comments/1hr2czq/calibreweb_cover_image_dark](https://www.reddit.com/r/selfhosted/comments/1hr2czq/calibreweb_cover_image_dark)
 - RSS feed: $source
 - date published: 2025-01-01T12:51:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys</p> <p>I have this weird image problem. When I import a book and fetch the metadata from an online source, the cover image goes dark if I use the link that is populated. If I don&#39;t use the link and use the one from the book itself, it displays fine. But some books don&#39;t have the cover image as their first page.</p> <p>Does anyone know why this happens? I am using the Docker-Compose file from LinuxServer .io and I am running it in Linux Mint.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AlphaWeasel123"> /u/AlphaWeasel123 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr2czq/calibreweb_cover_image_dark/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr2czq/calibreweb_cover_image_dark/">[comments]</a></span>

## Refer to NAS Shared folder in container in another VM
 - [https://www.reddit.com/r/selfhosted/comments/1hr2502/refer_to_nas_shared_folder_in_container_in](https://www.reddit.com/r/selfhosted/comments/1hr2502/refer_to_nas_shared_folder_in_container_in)
 - RSS feed: $source
 - date published: 2025-01-01T12:35:57+00:00

<!-- SC_OFF --><div class="md"><p><em>I posted this before in another Subreddit but without response, I did some search online and I made a POC on my enviroment without luck, looks like my basic linux/Networking knowhow are the problem:</em></p> <p>Now I have all may containers and my shared folders inside OpenMediaVault which is on VM on Proxmox</p> <p><strong>The current setup : Proxmox —&gt; OMV VM —&gt; Containers &amp; Shared Folders</strong></p> <p>Now I decided to move all my containers to a separate Debian Instance, to make NAS only as NAS and Containers to be separate for more segregation / control /backup/..</p> <p><strong>The new setup:</strong><br/> <strong>My Files. : Proxmox —&gt; OMV VM —&gt; my shared folders</strong><br/> <strong>My Containers: Proxmox —&gt; Debian VM—&gt; Container</strong></p> <p>As you see my containers now on separate VM than my files and I need to refer to my shared folders inside my containers, Example of that my plex, below is the existing com

## Recommendations for Self-Hosted Open Source Software for Real-Time Delphi Studies?
 - [https://www.reddit.com/r/selfhosted/comments/1hr1q35/recommendations_for_selfhosted_open_source](https://www.reddit.com/r/selfhosted/comments/1hr1q35/recommendations_for_selfhosted_open_source)
 - RSS feed: $source
 - date published: 2025-01-01T12:06:48+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m looking to conduct a Real-Time Delphi study and would prefer to use a self-hosted, open-source software solution. Ideally, it should support features like iterative feedback, data visualization, and participant anonymity.</p> <p>Does anyone have recommendations for platforms or tools that fit this use case?</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Astrianz"> /u/Astrianz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr1q35/recommendations_for_selfhosted_open_source/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr1q35/recommendations_for_selfhosted_open_source/">[comments]</a></span>

## [Looking for help / suggestions] How to sync google photos bidirectionally to PC ?
 - [https://www.reddit.com/r/selfhosted/comments/1hr1f40/looking_for_help_suggestions_how_to_sync_google](https://www.reddit.com/r/selfhosted/comments/1hr1f40/looking_for_help_suggestions_how_to_sync_google)
 - RSS feed: $source
 - date published: 2025-01-01T11:44:55+00:00

<!-- SC_OFF --><div class="md"><p>Happy new year, selfhosters!</p> <p>After looking here and there for a solution for my case, I come to this mighty community for help...</p> <p>Here is the case:</p> <p><strong>[Context]</strong> My wife and I share photos with each other, having enabled each other&#39;s google account to access our own google photos library.</p> <p><strong>The cause:</strong> Some time ago, my wife enabled an option within her google photos account to get a copy of every new photo I took to her own account (effectively having duplicates, one &quot;original&quot; in my account, and the copy on hers). I found about that later on, but &quot;the damage was already done&quot;</p> <p><strong>The problem:</strong> Now we are running low on space on our google storage, and I know there are several gigas we can free up by removing those unnecessary duplicates.</p> <p><strong>The challenge:</strong> As the sync option was enabled for a long time, there are MANY pictures dupli

## Twingate / Tailscale Free Plan
 - [https://www.reddit.com/r/selfhosted/comments/1hr0na6/twingate_tailscale_free_plan](https://www.reddit.com/r/selfhosted/comments/1hr0na6/twingate_tailscale_free_plan)
 - RSS feed: $source
 - date published: 2025-01-01T10:46:44+00:00

<!-- SC_OFF --><div class="md"><p>I was wondering, if I use Twinsgate or Tailscale free plan, does that mean I can ditch my VPN?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/InformationNo9581"> /u/InformationNo9581 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr0na6/twingate_tailscale_free_plan/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hr0na6/twingate_tailscale_free_plan/">[comments]</a></span>

## Public demo - Self-hosted tool to analyze IP / domain / hash
 - [https://www.reddit.com/r/selfhosted/comments/1hr02c8/public_demo_selfhosted_tool_to_analyze_ip_domain](https://www.reddit.com/r/selfhosted/comments/1hr02c8/public_demo_selfhosted_tool_to_analyze_ip_domain)
 - RSS feed: $source
 - date published: 2025-01-01T10:00:27+00:00

<!-- SC_OFF --><div class="md"><p>Hello there,</p> <p>not so long ago I published a post about Cyberbro, a FOSS tool I am developing. It has now 75+ stars (I&#39;m so happy, I didn&#39;t expect it).</p> <p>I made a public demo (careful, all info is public, do not put anything sensitive).</p> <p>Here is the demo if you want to try it: </p> <p><a href="https://demo.cyberbro.net/">https://demo.cyberbro.net/</a></p> <p>This tool can be easily deployed with docker compose up (after editing secrets or copying the sample). </p> <p>Original project: <a href="https://github.com/stanfrbd/cyberbro/">https://github.com/stanfrbd/cyberbro/</a></p> <p>Features:</p> <pre><code>Effortless Input Handling: Paste raw logs, IoCs, or fanged IoCs, and let our regex parser do the rest. Multi-Service Reputation Checks: Verify observables (IP, hash, domain, URL) across multiple services like VirusTotal, AbuseIPDB, IPInfo, Spur.us, MDE, Google Safe Browsing, Shodan, Abusix, Phishtank, ThreatFox, Github, Google

## Postiz (v1.19.1) - open source social media scheduling tool (tons of new featrures)
 - [https://www.reddit.com/r/selfhosted/comments/1hr00zc/postiz_v1191_open_source_social_media_scheduling](https://www.reddit.com/r/selfhosted/comments/1hr00zc/postiz_v1191_open_source_social_media_scheduling)
 - RSS feed: $source
 - date published: 2025-01-01T09:57:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>Happy New Year 🥳</p> <p>I had so much time during this month; it was pretty quiet, so I dug crazy into coding.</p> <p>My wife also had much free time, so we started polishing and adding new features!</p> <p><strong>Just a recap:</strong> Postiz is a social media scheduling tool supporting 14 social media channels:</p> <p>Instagram, Facebook, TikTok, Reddit, LinkedIn, X, Threads, BlueSky, Mastodon, YouTube, Pinterest, Dribbble, Slack, and Discord.</p> <p><a href="https://github.com/gitroomhq/postiz-app/">https://github.com/gitroomhq/postiz-app/</a></p> <p>Here are some of the new stuff!</p> <ul> <li><strong>Public API</strong> is now available for open-source use!</li> <li><strong>Better uploading</strong> - Decreases the quality of the pictures on the client side to save storage.</li> <li><strong>Internal Plugs</strong> - Now, when you post a post for LinkedIn or X, you can choose other connected accounts to repost it!</li> <li><s

## BunkerWeb WAF - Is there any use in the community ?
 - [https://www.reddit.com/r/selfhosted/comments/1hqzuj6/bunkerweb_waf_is_there_any_use_in_the_community](https://www.reddit.com/r/selfhosted/comments/1hqzuj6/bunkerweb_waf_is_there_any_use_in_the_community)
 - RSS feed: $source
 - date published: 2025-01-01T09:43:03+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Just discovered BunkerWeb. It had features I was looking for for quite a while (country filtering in my case) but never heard about it until few days ago </p> <p>I’m wondering : are many people in the community using it ? Is there some advantages/disadvantages from using it ?</p> <p>Trying to gather some feedbacks around it before adopting it in prod. </p> <p>Thanks</p> <p>PS : One big downside is the lets encrypt DNS challenge behind a paywall that seems like a hard to justify choice. But http challenge works well enough so I guess that’s acceptable </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bright_Mobile_7400"> /u/Bright_Mobile_7400 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzuj6/bunkerweb_waf_is_there_any_use_in_the_community/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzuj6/bunkerweb_waf_is_there_any_use_in_the_co

## Linux server best practices? Tips and tricks?
 - [https://www.reddit.com/r/selfhosted/comments/1hqzmwz/linux_server_best_practices_tips_and_tricks](https://www.reddit.com/r/selfhosted/comments/1hqzmwz/linux_server_best_practices_tips_and_tricks)
 - RSS feed: $source
 - date published: 2025-01-01T09:25:43+00:00

<!-- SC_OFF --><div class="md"><p>Linux server best practices? Tips and tricks?</p> <p>What are some best practices for a home Linux server server when it comes down to running programs?</p> <p>Like install everything as much as possible in containers?</p> <p>Or just install everything in flatpaks </p> <p>Or all just native </p> <p>.....</p> <p>And what are some other tips and tricks that you found out because of experience ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UinguZero"> /u/UinguZero </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzmwz/linux_server_best_practices_tips_and_tricks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzmwz/linux_server_best_practices_tips_and_tricks/">[comments]</a></span>

## 2024 Conclusion For Self Hosting & More
 - [https://www.reddit.com/r/selfhosted/comments/1hqzlm7/2024_conclusion_for_self_hosting_more](https://www.reddit.com/r/selfhosted/comments/1hqzlm7/2024_conclusion_for_self_hosting_more)
 - RSS feed: $source
 - date published: 2025-01-01T09:22:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, you may have seen my monthly-ish article called <em>Now Self Hosted</em>. Like last year I have put out a conclusion of the year including my experience with self hosting and more.</p> <p>This article goes through what I have been developing, home assistant experiences and an update on how my servers are performing with a few issues I have encountered.</p> <p>Come over and read the 2024 conclusion at: <a href="https://enchantedcode.co.uk/blog/year-2024-conclusion/">enchantedcode.co.uk/blog/year-2024-conclusion/</a>.</p> <p>Hope you enjoy reading! Feel free to comment any suggestions/feedback for the 2025 issue, next new year.</p> <p>Also happy new year to you all!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/enchant97"> /u/enchant97 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzlm7/2024_conclusion_for_self_hosting_more/">[link]</a></span> &#32; <span><a href="https://www.r

## Vaultwarden on Bitwarden Android app Not Connecting
 - [https://www.reddit.com/r/selfhosted/comments/1hqzaqj/vaultwarden_on_bitwarden_android_app_not](https://www.reddit.com/r/selfhosted/comments/1hqzaqj/vaultwarden_on_bitwarden_android_app_not)
 - RSS feed: $source
 - date published: 2025-01-01T08:58:26+00:00

<!-- SC_OFF --><div class="md"><p>I have a nginx reverse proxy and I added the certificate to my android device yet I cant connect to my self hosted Vaultwarden instance on the Android Bitwarden app (for local access only). Yet signing in the browser extension works.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SideSelect1Four"> /u/SideSelect1Four </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzaqj/vaultwarden_on_bitwarden_android_app_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqzaqj/vaultwarden_on_bitwarden_android_app_not/">[comments]</a></span>

## [noob] My wishlist for a local server in 2025
 - [https://www.reddit.com/r/selfhosted/comments/1hqza75/noob_my_wishlist_for_a_local_server_in_2025](https://www.reddit.com/r/selfhosted/comments/1hqza75/noob_my_wishlist_for_a_local_server_in_2025)
 - RSS feed: $source
 - date published: 2025-01-01T08:57:12+00:00

<!-- SC_OFF --><div class="md"><p>**edited linked to first remarks --&gt; lack of knowledge makes me being doubtful of port forwarding but bear in mind I&#39;m primarily focused on local network and www will come later.</p> <p>Hello everyone, Have a safe 2025. My first Reddit post ever is here to ask for advice for my project. For 1-2 month I&#39;ve been scrolling around the concept of self-hosted server (homelab no vps). This world is vertiginous for me. I think I don&#39;t want yet to invest in a router and a switch. All I want to test is having some (immich, nextcloud, *arr through vpn, jellyfin and adguard home) self hosted software. Most of them local with occasional external access without port forwarding because I&#39;m scared about hacks with port forwarding. I got an old (10y) gaming desktop reconverted into fedora server. But I&#39;m ahead of my capabilities. Meddling with DNS and accessing everything easily is hard. I&#39;ve investigated easy solution such as yunohost or s

## Pi-hole
 - [https://www.reddit.com/r/selfhosted/comments/1hqz3qh/pihole](https://www.reddit.com/r/selfhosted/comments/1hqz3qh/pihole)
 - RSS feed: $source
 - date published: 2025-01-01T08:42:38+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I would like to get into pi-hole again. I had it working once (long time ago), but these days I seem to struggle with it, especially getting it running if I am not at home. I have a domain name and use cloudflare tunnels, so I can set up something like pi-hole.mydomain.com Is there some sort of guide I could follow to set it up correctly and have it working?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Late_Republic_1805"> /u/Late_Republic_1805 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqz3qh/pihole/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqz3qh/pihole/">[comments]</a></span>

## Self-built NAS
 - [https://www.reddit.com/r/selfhosted/comments/1hqynoi/selfbuilt_nas](https://www.reddit.com/r/selfhosted/comments/1hqynoi/selfbuilt_nas)
 - RSS feed: $source
 - date published: 2025-01-01T08:08:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>I wanted to get your opinion. I have a self-built NAS with a 6th generation i5, 40 GB RAM, 4x 6 TB HDDs and a 512 GB M.2 SSD. It&#39;s currently running Xpenology and I&#39;m largely happy with it, having tried TrueNAS and Unraid - neither of which I was happy with.</p> <p>Now I&#39;m toying with the idea of installing Proxmox VE and running Xpenology via a container. However, I am still unsure.</p> <p>I mainly use the NAS for Paperless, a Minecraft server for me and my son, and Plex for in-home streaming.</p> <p>In the future, I would also like to run an LLM and a teddycloud container on it.</p> <p>What do you think? Have you had any experience with alternatives to xpenology what would you recommend? As a sample CasaOS, Omv etc.</p> <p>Thanks and best wishes, and happy new</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spiritual_Onion_6805"> /u/Spiritual_Onion_6805 </a> <br/> <span><a href="ht

## New year, new dashboard! From Homer to Homepage
 - [https://www.reddit.com/r/selfhosted/comments/1hqy61b/new_year_new_dashboard_from_homer_to_homepage](https://www.reddit.com/r/selfhosted/comments/1hqy61b/new_year_new_dashboard_from_homer_to_homepage)
 - RSS feed: $source
 - date published: 2025-01-01T07:30:31+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://imgur.com/a/HCoZTlo">https://imgur.com/a/HCoZTlo</a></p> <p>Decided to gift myself a new dashboard for the new year. Homer was cool. Simple. But Homepage seems to be more feature rich with its integrations.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PaperFloater"> /u/PaperFloater </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqy61b/new_year_new_dashboard_from_homer_to_homepage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqy61b/new_year_new_dashboard_from_homer_to_homepage/">[comments]</a></span>

## Opinion about Lenovo ThinkCentre M720s Intel i5-8500 with 8GB RAM
 - [https://www.reddit.com/r/selfhosted/comments/1hqx4wu/opinion_about_lenovo_thinkcentre_m720s_intel](https://www.reddit.com/r/selfhosted/comments/1hqx4wu/opinion_about_lenovo_thinkcentre_m720s_intel)
 - RSS feed: $source
 - date published: 2025-01-01T06:14:02+00:00

<!-- SC_OFF --><div class="md"><p>Cross-posted from <a href="/r/homelab">r/homelab</a></p> <p>I currently have a Raspberry Pi 4 with 8 GB RAM on which I am running some small hobby projects. However, I am thinking of building a self-hosting Plex stack and running a couple of containers on it. I tried to start those containers on the Pi, but at some point, the Pi started to be very slow to respond, and I am afraid that I am pushing its limits.</p> <p>I found this ThinkCentre SFF second-hand relatively cheap. I thought it would be a good and more powerful replacement for the Pi, and I should be able to use it for HEVC HW transcoding on the Plex as well. I guess I won&#39;t have any problems running all the containers I want on it as well, and I would be able to attach a couple of HDDs. My main concerns are:</p> <ul> <li>power consumption. Since this would run mostly idle, naturally I would like to lower the power consumption to the bare minimum.</li> <li>The CPU doesn&#39;t support ECC

## Code snippet or gist app?
 - [https://www.reddit.com/r/selfhosted/comments/1hqwa3m/code_snippet_or_gist_app](https://www.reddit.com/r/selfhosted/comments/1hqwa3m/code_snippet_or_gist_app)
 - RSS feed: $source
 - date published: 2025-01-01T05:14:05+00:00

<!-- SC_OFF --><div class="md"><p>Is there a selfhosted app for organizing snippets for easy access and remembering?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Payment8612"> /u/Ok-Payment8612 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqwa3m/code_snippet_or_gist_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqwa3m/code_snippet_or_gist_app/">[comments]</a></span>

## nvidia-smi & nvtop does not show power for Quardro P600 ?
 - [https://www.reddit.com/r/selfhosted/comments/1hqw2ym/nvidiasmi_nvtop_does_not_show_power_for_quardro](https://www.reddit.com/r/selfhosted/comments/1hqw2ym/nvidiasmi_nvtop_does_not_show_power_for_quardro)
 - RSS feed: $source
 - date published: 2025-01-01T05:01:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hqw2ym/nvidiasmi_nvtop_does_not_show_power_for_quardro/"> <img src="https://b.thumbs.redditmedia.com/-uq5WRSEsvwVDcFHfD5TB5-okWL-d_Qj0XohplArwbg.jpg" alt="nvidia-smi &amp; nvtop does not show power for Quardro P600 ?" title="nvidia-smi &amp; nvtop does not show power for Quardro P600 ?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>AS the title, its ubuntu 22.04 vm on proxmox v8.3, my GPU pass through is working, but I can&#39;t see power consumption inside the vm</p> <p><a href="https://preview.redd.it/s7nwsp1ddbae1.png?width=581&amp;format=png&amp;auto=webp&amp;s=e2d5660290d80c79c90860f66ed2a36bb6450736">https://preview.redd.it/s7nwsp1ddbae1.png?width=581&amp;format=png&amp;auto=webp&amp;s=e2d5660290d80c79c90860f66ed2a36bb6450736</a></p> <p><a href="https://preview.redd.it/rqez0e0fdbae1.png?width=737&amp;format=png&amp;auto=webp&amp;s=84da187fde5aabc3038adc926bfc2aadce8ad3e9">https://preview.redd.it/rqez0

## Docker Swarm - Redundancy
 - [https://www.reddit.com/r/selfhosted/comments/1hquwot/docker_swarm_redundancy](https://www.reddit.com/r/selfhosted/comments/1hquwot/docker_swarm_redundancy)
 - RSS feed: $source
 - date published: 2025-01-01T03:42:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys</p> <p>I&#39;m relatively new to Docker &amp; Docker Swarm. I&#39;ve always run everything in VM&#39;s.</p> <p>I&#39;ve been experimenting with migrating some workloads to Docker Swarm.</p> <p>I&#39;ve setup a 3 node docker swarm cluster, each node is a Manager &amp; Worker for redundancy.</p> <p>I&#39;ve setup a pihole stack and have replicas=1 &amp; max replicas per node=1. </p> <p>DHCP sets DNS to the swarm IP for all clients on my network.</p> <p>My thinking was that if one of the worker nodes dies then the stack/task would automatically get started on a new worker node so that I have HA for my DNS/pihole (I bind mount storage to a shared NFS cluster)</p> <p>What I&#39;ve observed is that when I just unexpectedly kill the worker node running pihole then the swarm correctly starts up another instance on a new worker node, however, the original task on the dead node is still in the running state. </p> <p>This then seems to confuse the swarm

## Any self hosted Project Management software?
 - [https://www.reddit.com/r/selfhosted/comments/1hqu8mj/any_self_hosted_project_management_software](https://www.reddit.com/r/selfhosted/comments/1hqu8mj/any_self_hosted_project_management_software)
 - RSS feed: $source
 - date published: 2025-01-01T02:58:49+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/sushikingdom"> /u/sushikingdom </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqu8mj/any_self_hosted_project_management_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqu8mj/any_self_hosted_project_management_software/">[comments]</a></span>

## What is the best OS for Jellyfin + *arr server?
 - [https://www.reddit.com/r/selfhosted/comments/1hqsxsl/what_is_the_best_os_for_jellyfin_arr_server](https://www.reddit.com/r/selfhosted/comments/1hqsxsl/what_is_the_best_os_for_jellyfin_arr_server)
 - RSS feed: $source
 - date published: 2025-01-01T01:37:23+00:00

<!-- SC_OFF --><div class="md"><p>So I’ve never done anything like this and I want to set up a media server with Jellyfin, Sonarr, Radarr, etc. on my spare laptop.</p> <p>Some options I know about are Ubuntu Server (with Portainer maybe?), TrueNAS Scale and Proxmox.</p> <p>What’s the best choice with the best performance/stability/reliability/ease of use considering my use case?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dramatic_Mastodon_93"> /u/Dramatic_Mastodon_93 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqsxsl/what_is_the_best_os_for_jellyfin_arr_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1hqsxsl/what_is_the_best_os_for_jellyfin_arr_server/">[comments]</a></span>

## HTTPS secured n8n in your preferred Cloud. The easy way with Docker Compose YML and Nginx Proxy Manager.
 - [https://www.reddit.com/r/selfhosted/comments/1hqs5xl/https_secured_n8n_in_your_preferred_cloud_the](https://www.reddit.com/r/selfhosted/comments/1hqs5xl/https_secured_n8n_in_your_preferred_cloud_the)
 - RSS feed: $source
 - date published: 2025-01-01T00:51:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1hqs5xl/https_secured_n8n_in_your_preferred_cloud_the/"> <img src="https://external-preview.redd.it/fTAu9cPzfCi4y5PkoeKBdX59nlACZ35lZ2yOThkuoJw.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=d9768387820c3618770b6c001566a2a560c27c71" alt="HTTPS secured n8n in your preferred Cloud. The easy way with Docker Compose YML and Nginx Proxy Manager." title="HTTPS secured n8n in your preferred Cloud. The easy way with Docker Compose YML and Nginx Proxy Manager." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Simply Deploy instances of n8n in your preferred cloud provider using Portainer, docker compose YML and Nginx Proxy Manager. This step by step guide will take you from zero to hero in Nginx deployments. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/f2ka07"> /u/f2ka07 </a> <br/> <span><a href="https://youtu.be/Paedqn7EyBw">[link]</a></span> &#32; <span><a href="https://www

