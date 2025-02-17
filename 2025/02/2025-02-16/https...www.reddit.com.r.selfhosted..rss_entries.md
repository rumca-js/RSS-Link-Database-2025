# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Raspberry Pi Zero 2W going offline after few hours/days (DietPi)
 - [https://www.reddit.com/r/selfhosted/comments/1ir4kti/raspberry_pi_zero_2w_going_offline_after_few](https://www.reddit.com/r/selfhosted/comments/1ir4kti/raspberry_pi_zero_2w_going_offline_after_few)
 - RSS feed: $source
 - date published: 2025-02-16T22:32:03+00:00

<!-- SC_OFF --><div class="md"><p>So I got a raspberry pi zero 2w to act as a tailscale exit node, it runs at around 5mbps continuous as it&#39;s routing some camera rtsp feed to a remote frigate server. I noticed lately that it used to go offline randomly (not sure if it&#39;s shutting down or going offline because I&#39;m not on premises). I thought it was the ethernet adapter that I connected to it as it was quite cheap and it seems the interface used to go up and down. After that I switched to the wifi interface however the same issue is happening, when checking the logs i see this (<a href="https://pastebin.com/B9Epg86b">https://pastebin.com/B9Epg86b</a>), could someone please point me into the right direction as to what could be happening? I tried changing the governor and under clocking the cpu with dietpi-config in case it was temps however the temps were always staying around 50 degrees so it seemed alright, I&#39;m honestly at my wits end as I tried so much to troubleshoot 

## Best iOS App for Polaris Music Server?
 - [https://www.reddit.com/r/selfhosted/comments/1ir3o6p/best_ios_app_for_polaris_music_server](https://www.reddit.com/r/selfhosted/comments/1ir3o6p/best_ios_app_for_polaris_music_server)
 - RSS feed: $source
 - date published: 2025-02-16T21:52:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m currently using <a href="https://github.com/agersant/polaris"><strong>Polaris</strong></a> for my music management and loving the experience so far. However, I&#39;m struggling to find a good iOS app to use with it.</p> <p>I came across <strong>Polarios</strong>, but I keep running into SSL certificate and other security errors that prevent it from working properly.</p> <p>Does anyone know of an iOS app that works well with Polaris for streaming music—preferably something that doesn’t require using Safari?</p> <p>Any recommendations or workarounds would be greatly appreciated!</p> <p>Thanks in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Brilliant_Still_9605"> /u/Brilliant_Still_9605 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir3o6p/best_ios_app_for_polaris_music_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## Docker PHP Permissions problem? FileRun Docker
 - [https://www.reddit.com/r/selfhosted/comments/1ir3236/docker_php_permissions_problem_filerun_docker](https://www.reddit.com/r/selfhosted/comments/1ir3236/docker_php_permissions_problem_filerun_docker)
 - RSS feed: $source
 - date published: 2025-02-16T21:25:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey :)</p> <p>Maybe someone here can help me out. Everything is on Unraid btw. </p> <p>I&#39;ve been trying for two weeks to get my FileRun Docker back up and running. It worked flawlessly for a year, but then NGINX stopped working, and I started getting a 502 error.</p> <p>So I thought I&#39;d reinstall FileRun. Now I can access the interface, but I can&#39;t set a home folder.</p> <p>Whenever I try, I get the following error:<br/> <strong>(createPath error: mkdir(): Permission denied).</strong><br/> Neither files nor folders are readable, and I can&#39;t create any either.</p> <p>Here’s what I’ve tried so far:</p> <ul> <li>Set <code>chmod 777</code> for the files folder and appdata folder</li> <li><code>x</code> permission is set for all parent directories</li> <li>Volumes are, of course, set with <code>rw</code></li> <li>Inside the Docker container shell, I <em>can</em> create a folder using <code>mkdir</code></li> </ul> <p>The owner is set to <co

## Sharing Jellyfin routed through Gluetun with family and friends
 - [https://www.reddit.com/r/selfhosted/comments/1ir2amu/sharing_jellyfin_routed_through_gluetun_with](https://www.reddit.com/r/selfhosted/comments/1ir2amu/sharing_jellyfin_routed_through_gluetun_with)
 - RSS feed: $source
 - date published: 2025-02-16T20:53:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m new to self hosting and just got a basic server set up last month. I used Portainer to set up Docker containers and got Jellyfin and a few other containers routed through Gluetun, which is also in another container, on an Ubuntu 24.04 LTS PC. Gluetun is using ProtonVPN and I have port forwarding enabled.</p> <p>Now I want to share my Jellyfin server with some family and friends, preferably for free. I&#39;ve searched through this and other subs but I haven&#39;t seen a way to do it when Jellyfin is routed through Gluetun. Has anyone done this before? If so, how did you do it?</p> <p>Thank you for your help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ComicCruiser"> /u/ComicCruiser </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir2amu/sharing_jellyfin_routed_through_gluetun_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted

## Easy, secure and private file sharing
 - [https://www.reddit.com/r/selfhosted/comments/1ir28na/easy_secure_and_private_file_sharing](https://www.reddit.com/r/selfhosted/comments/1ir28na/easy_secure_and_private_file_sharing)
 - RSS feed: $source
 - date published: 2025-02-16T20:51:04+00:00

<!-- SC_OFF --><div class="md"><p>I still haven’t found a good solution to easy , secure and private file sharing with people who are not technical (probably 90% of the population). </p> <p>Let’s say I want to share medical records with my doctor. Public cloud is not a good idea, as documents are probably indexed and linked to me, and permanently stored. </p> <p>One could run a webserver like Nextcloud at home, but exposing it to the public is risky and frowned upon.</p> <p>The vast majority of people won’t install and configure a VPN to access my webserver. </p> <p>I could put Cloudflare Access in front of my webserver, but Cloudflare says I need your data. Nextcloud has an app for end to end encryption to keep Cloudflare out, but it doesn’t work with web. </p> <p>I could do a Bitwarden Send, which works for small files, but doesn’t work with larger files or folders. </p> <p>Obviously the vast majority of people are not going to install a command line utility like magic-wormhole or 

## Monitoring docker-containers with grafana, prometheus & fluent-bit
 - [https://www.reddit.com/r/selfhosted/comments/1ir27et/monitoring_dockercontainers_with_grafana](https://www.reddit.com/r/selfhosted/comments/1ir27et/monitoring_dockercontainers_with_grafana)
 - RSS feed: $source
 - date published: 2025-02-16T20:49:38+00:00

<!-- SC_OFF --><div class="md"><h1>goal with problem-description</h1> <p>I&#39;m trying to monitor my docker containers with grafana. The goal is to see things like CPU, RAM &amp; disk usage per container. Some network stats would be nice too. Currently I&#39;m trying to get metrics for my containers from fluent-bit &amp; collect them with prometheus. I&#39;m using the docker input plugin: <a href="https://docs.fluentbit.io/manual/pipeline/inputs/docker-metrics">https://docs.fluentbit.io/manual/pipeline/inputs/docker-metrics</a> which seems to be doing exactly what I want. When running this with default stdout output, I can see docker metrics from my containers in fluent-bit logs. The problem I&#39;m currently facing is actually delivering these metrics to grafana with prometheus. I tried this with several fluent-bit outputs - prometheus_remote_write, prometheus_exporter &amp; http which can all be found under: <a href="https://docs.fluentbit.io/manual/pipeline/outputs">https://docs.

## MediaWiki and Raspberry PI - self hosted wiki website (like Wikipedia)
 - [https://www.reddit.com/r/selfhosted/comments/1ir26hg/mediawiki_and_raspberry_pi_self_hosted_wiki](https://www.reddit.com/r/selfhosted/comments/1ir26hg/mediawiki_and_raspberry_pi_self_hosted_wiki)
 - RSS feed: $source
 - date published: 2025-02-16T20:48:31+00:00

<!-- SC_OFF --><div class="md"><p>For those people interested, here&#39;s a detailed tutorial for beginners to get your personal wiki page up in minutes: install and setup MediaWiki in a Raspberry PI computer board with docker: <a href="https://peppe8o.com/personal-mediawiki-with-raspberry-pi-and-docker/">https://peppe8o.com/personal-mediawiki-with-raspberry-pi-and-docker/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peppe8o_"> /u/peppe8o_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir26hg/mediawiki_and_raspberry_pi_self_hosted_wiki/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir26hg/mediawiki_and_raspberry_pi_self_hosted_wiki/">[comments]</a></span>

## YunoHost + Hugo?
 - [https://www.reddit.com/r/selfhosted/comments/1ir26an/yunohost_hugo](https://www.reddit.com/r/selfhosted/comments/1ir26an/yunohost_hugo)
 - RSS feed: $source
 - date published: 2025-02-16T20:48:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I&#39;m new to selfhosting and IT in general (only 7 months of exp) and I want to start self hosting a website using Hugo.</p> <p>I&#39;ve got a YunoHost install on the PC Im using for my selfhosting which already has some stuff like nextcloud. But Hugo isn&#39;t an existing app and although I have installed another app that YunuHost doesn&#39;t provide. Im find it a hard time to get someone whos done this before and have shared how they&#39;ve done it? </p> <p>Some Context if you wanna know:</p> <p>I have tried to use Proxmox with nextcloud and a hugo VM but I needed a reverse proxy (I tried using caddy and a nginx VM for this) which I just couldn&#39;t A) really understand what I was doing such as what each config file did and stuff and B) get it work... It was a pain and I wasn&#39;t learning anything. I gave up and went for YunoHost which does SSL certificate for you and it also does the reverse proxy for you aswell (I beleive lmk if

## Hardware recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1ir1tyc/hardware_recommendations](https://www.reddit.com/r/selfhosted/comments/1ir1tyc/hardware_recommendations)
 - RSS feed: $source
 - date published: 2025-02-16T20:33:35+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to figure out what hardware I should get....</p> <p>I keep flipping from Pi 5&#39;s, to mini PC&#39;s, to a more complete home server build, and basically now am a bit confused on what way to go.</p> <p>Here&#39;s what I know I want to run:</p> <ul> <li>Immich (or similar) server for photos/short videos. <strong>347GB of data</strong></li> <li>Jellyfin server for movies/tv <strong>2.7TB of data</strong> (probably occasional max of 2 people)</li> <li>Home Assistant </li> <li>A music server to replace Spotify.</li> <li>Potentially some networking servers...DNS or VPN...though I&#39;m not too knowledgeable in this area yet.</li> </ul> <p>And probably some other things I&#39;ve not thought about yet.</p> <ul> <li>I&#39;ve had a good play with Proxmox on a spare laptop and like it, so I think I&#39;d like to use that. I think I&#39;d like to have multiple drives for resilience, so I can lose a drive with zero data loss.</li> <li>I&#39;ve re

## Comcast keeps changing my public IP, so I made a tool to keep my DNS records up to date with my current public IP.
 - [https://www.reddit.com/r/selfhosted/comments/1ir1c8y/comcast_keeps_changing_my_public_ip_so_i_made_a](https://www.reddit.com/r/selfhosted/comments/1ir1c8y/comcast_keeps_changing_my_public_ip_so_i_made_a)
 - RSS feed: $source
 - date published: 2025-02-16T20:12:45+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been struggling with an annoying problem where my ISP keeps changing my public IP, which breaks my homelab setup since my Cloudflare domains stop pointing to the right place. My mom will text me that that the media server is down :(.</p> <p>Worth noting that Cloudflare actually <a href="https://developers.cloudflare.com/dns/manage-dns-records/how-to/managing-dynamic-ip-addresses/">offers documentation about this problem</a>, but none of the solutions offer this in a simple docker image I can just drop next to my reverse proxy. The closest I was able to find was <a href="https://github.com/TheWicklowWolf/pyNameCheap">TheWicklowWolf/pyNameCheap</a> but that only works for NameCheap and I use Cloudflare.</p> <p>So, I decided to solve this once and for all. I created a dockerized tool that:</p> <ol> <li>Checks my current public IP every minute</li> <li>Compares it to the A record set in Cloudflare</li> <li>If they&#39;re different, it updates th

## Creating a homemade server?
 - [https://www.reddit.com/r/selfhosted/comments/1ir16b5/creating_a_homemade_server](https://www.reddit.com/r/selfhosted/comments/1ir16b5/creating_a_homemade_server)
 - RSS feed: $source
 - date published: 2025-02-16T20:05:45+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone, I am new here. I created a Telegram bot that I want to run 24/7, and since I can&#39;t keep my pc on all the time, I&#39;ve been looking around a bit on how to do it. Gosh what prices.</p> <p>At this point the question arose for me whether it would be convenient to make a homemade server. Besides running python scripts, I would also use it as my personal cloud. I really don&#39;t know much about it, but would it be worth doing? Is it feasible to do this? If yes, where should I start from? How much would it cost me? Has anyone done this and what do you think? How do you go about building a homemade server? I&#39;m 17 yrs old and I haven&#39;t so much cash.</p> <p>Thank you in advance for your answers.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UzzInReddit"> /u/UzzInReddit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir16b5/creating_a_homemade_server/">[link]</a></sp

## Screenless phone server
 - [https://www.reddit.com/r/selfhosted/comments/1ir062f/screenless_phone_server](https://www.reddit.com/r/selfhosted/comments/1ir062f/screenless_phone_server)
 - RSS feed: $source
 - date published: 2025-02-16T19:23:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve got a OnePlus 7 Pro, a decent Android phone; the only problem is that the screen is broken. Screen mirroring via USB-C dongle works though.</p> <p>I&#39;m thinking of turning it into a Linux server of some kind, any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SlowStopper"> /u/SlowStopper </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir062f/screenless_phone_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir062f/screenless_phone_server/">[comments]</a></span>

## iCal „Manager“
 - [https://www.reddit.com/r/selfhosted/comments/1ir03c6/ical_manager](https://www.reddit.com/r/selfhosted/comments/1ir03c6/ical_manager)
 - RSS feed: $source
 - date published: 2025-02-16T19:20:43+00:00

<!-- SC_OFF --><div class="md"><p>I have a problem with one of my iCal subscription where I’d like to be able to hide certain events depending on event name, uid or category. The most sane way I can think of handling something like this is a iCal Server acting as a middle man. It would handle pulling the iCal subscription and filtering events based of the above mentioned and then host this filtered iCal itself. Since I would need to update what needs to be filtered quite frequently it would also be nice to have some sort of web interface since there is no way I know of to have a iCal Subscription with write access. I have done some searches into iCal solutions but wasn’t able to finde something that would work… I was especially surprised to learn that the Nextcloud iCal App could do something like this? I have encountered problems like this a lot in the last years and would have thought of it to be somewhat common. I have also a working python script as a prove of concept, so somethi

## Looking to start a public self hosted Minecraft server
 - [https://www.reddit.com/r/selfhosted/comments/1ir024b/looking_to_start_a_public_self_hosted_minecraft](https://www.reddit.com/r/selfhosted/comments/1ir024b/looking_to_start_a_public_self_hosted_minecraft)
 - RSS feed: $source
 - date published: 2025-02-16T19:19:22+00:00

<!-- SC_OFF --><div class="md"><p>I got a new computer and I&#39;m looking to use my old computer to host it here are the spec&#39;s Gpu: GTX 1050 cpu: AMD FX-6300, 6-Core @ ~3.5GHz ram 16 gigs I assume I&#39;d need to update the cpu once I got more then 10 players consistently playing let me know if there&#39;s anything I need to know or if I need to upgrade anything right away</p> <p>Edit: also wondering how much this will impact my wifi </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SloppyCloth7601"> /u/SloppyCloth7601 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir024b/looking_to_start_a_public_self_hosted_minecraft/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ir024b/looking_to_start_a_public_self_hosted_minecraft/">[comments]</a></span>

## dead-simple photo viewer with customizable views?
 - [https://www.reddit.com/r/selfhosted/comments/1iqzoft/deadsimple_photo_viewer_with_customizable_views](https://www.reddit.com/r/selfhosted/comments/1iqzoft/deadsimple_photo_viewer_with_customizable_views)
 - RSS feed: $source
 - date published: 2025-02-16T19:03:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi all </p> <p>So after abandoning Immich for photoprism, I am starting to grow tired of this too. It offers so many features I do not need, and yet lacks the few that I actually care for. Before I go about building my own, maybe as a last effort my question here: is there a very simple self hosted photo app that meets these requirements:</p> <ul> <li>Read only (I do my own folders and don&#39;t want other other app touching them. While photoprism is a bit better than immich in this regard, it does create it&#39;s own folders which I very much don&#39;t like) </li> <li>Simple web view (thumbnails arranged by custom sort, large image display when clicked)</li> <li>custom timeline views: This is the big one. I have 3 types of images. Mobile (unorganized), DSLR (grouped into collections/events), and memes (unorganized). I want the memes to be viewable, but I do not want them part of the main timeline (many apps use &quot;albums&quot; to offer this, but 

## Help Reviewing My Server Setup
 - [https://www.reddit.com/r/selfhosted/comments/1iqz6zg/help_reviewing_my_server_setup](https://www.reddit.com/r/selfhosted/comments/1iqz6zg/help_reviewing_my_server_setup)
 - RSS feed: $source
 - date published: 2025-02-16T18:44:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m running three servers: one for home automation/NVR, one for NAS/media services, and one for network/firewall services.</p> <p><a href="https://imgur.com/iUtQCTd">Does this breakdown look doable based on the hardware?</a> Should the services be ditributed differently for better efficiency?</p> <p>Server 1 and 3 are already up and running. I just received my NAS, and am trying to decide where to run each service to best take advantage of my hardware.</p> <p>I&#39;m also considering UnRaid instead of Proxmox for a NAS OS. I just chose Proxmox because I&#39;m familiar with it, and I like the ability to snapshot. I also intend to run Proxmox Backup Server offsite at some point, and I like the PVE/PBS integration.</p> <p>Any advice would be much appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BostonDrivingIsWorse"> /u/BostonDrivingIsWorse </a> <br/> <span><a href="https://www.reddit.com/r/selfhost

## Exposing certain selfhosted services publicly, is a VPS and wireguard the right choice?
 - [https://www.reddit.com/r/selfhosted/comments/1iqxvdh/exposing_certain_selfhosted_services_publicly_is](https://www.reddit.com/r/selfhosted/comments/1iqxvdh/exposing_certain_selfhosted_services_publicly_is)
 - RSS feed: $source
 - date published: 2025-02-16T17:48:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi.</p> <p>I want to expose certain things that I host on my LAN to the public internet for family members. Generally Immich, Jellyfin and Nextcloud. Because of this, I&#39;m under the impression Cloudflare Tunnels is not an option.</p> <p>A quick diagram of my network looks like this: <a href="https://i.imgur.com/RKY3wSZ.png">https://i.imgur.com/RKY3wSZ.png</a></p> <p>My initial thoughts are to add something in front of my Opnsense firewall to protect my home IP address from being exposed. Is it ideal to just set up a wireguard tunnel between a VPS and the Opnsense firewall? That&#39;s how I would assume I had to do it, but do I also need a reverse proxy in the mix on the VPS as well if I went that route?</p> <p>I do have a 2nd proxmox server available to me for this as well where I could place the VMs that I want exposed publicly.</p> <p>Thanks for any input folks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/us

## [Fluid Calendar] – An Open-Source Alternative to Motion for Smart Task Scheduling
 - [https://www.reddit.com/r/selfhosted/comments/1iqxmzg/fluid_calendar_an_opensource_alternative_to](https://www.reddit.com/r/selfhosted/comments/1iqxmzg/fluid_calendar_an_opensource_alternative_to)
 - RSS feed: $source
 - date published: 2025-02-16T17:39:51+00:00

<!-- SC_OFF --><div class="md"><h1>For over a year, I used Motion as my go-to task scheduling and calendar automation tool. It was great, but I wanted more control, flexibility, and an open-source alternative. So, I decided to build my own:</h1> <p>🚀 <strong>Introducing Fluid Calendar</strong> – an open-source, intelligent scheduling tool that integrates with Google Calendar and automates task management.</p> <h1>Why Build Another Calendar App?</h1> <p>Motion is great, but I wanted:<br/> ✅ More customization &amp; control over scheduling<br/> ✅ A <strong>free &amp; open-source</strong> alternative for the community<br/> ✅ A way to experiment with new <strong>web technologies</strong><br/> ✅ (And let’s be honest—saving on subscription costs is a bonus! 😆)</p> <h1>Tech Stack</h1> <p>I built Fluid Calendar using:<br/> 🔹 <strong>Next.js</strong> – for frontend and API routes<br/> 🔹 <strong>TypeScript</strong> – for type safety &amp; maintainability<br/> 🔹 <strong>Prisma</strong> – for da

## What are your biggest challenges in keeping your knowledge hub accurate, up to date, and secure?
 - [https://www.reddit.com/r/selfhosted/comments/1iqx8un/what_are_your_biggest_challenges_in_keeping_your](https://www.reddit.com/r/selfhosted/comments/1iqx8un/what_are_your_biggest_challenges_in_keeping_your)
 - RSS feed: $source
 - date published: 2025-02-16T17:23:18+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Maximum_Function_665"> /u/Maximum_Function_665 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqx8un/what_are_your_biggest_challenges_in_keeping_your/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqx8un/what_are_your_biggest_challenges_in_keeping_your/">[comments]</a></span>

## Is there an Android app that works with a self-hosted yt-dlp/youtube-dl instance?
 - [https://www.reddit.com/r/selfhosted/comments/1iqx7ob/is_there_an_android_app_that_works_with_a](https://www.reddit.com/r/selfhosted/comments/1iqx7ob/is_there_an_android_app_that_works_with_a)
 - RSS feed: $source
 - date published: 2025-02-16T17:22:03+00:00

<!-- SC_OFF --><div class="md"><p>I come across videos on my phone that I want to download and keep a LOT. The vast majority of the time, the platform doesn&#39;t let you download the video directly (Facebook, Instagram, Reddit, whatever.) or even if it does, I don&#39;t necessarily want it to be on my phone, I&#39;d rather it be on my server. </p> <p>So the current workflow to do this is to copy the URL to the video, go to my bookmark to my &#39;YouTubeDL-Material&#39; instance that I host, log in, then paste the url into the download field and click the download button. </p> <p>I would much rather have a &#39;share&#39; option that hooked into this somehow. Now ideally there is already something out there that directly works the way I&#39;m explaining. But second choice would be something that could potentially get there but uses a remote API or something that maybe I could enable or setup which is a bit more legwork.</p> <p>Last scenario is I build it completely myself (which I mi

## Backup Amazon EBooks
 - [https://www.reddit.com/r/selfhosted/comments/1iqx6em/backup_amazon_ebooks](https://www.reddit.com/r/selfhosted/comments/1iqx6em/backup_amazon_ebooks)
 - RSS feed: $source
 - date published: 2025-02-16T17:20:38+00:00

<!-- SC_OFF --><div class="md"><blockquote> <p><a href="https://www.reddit.com/r/books/comments/1iqi07k/amazon_removing_the_ability_to_download_your/">Amazon removing the ability to download your purchased books</a><br/> by<a href="https://www.reddit.com/user/EchoesInTheAbyss/">u/EchoesInTheAbyss</a> in<a href="https://www.reddit.com/r/books/">booksAmazon removing the ability to download your purchased books</a></p> </blockquote> <p>Saw this in another Reddit and made me immediately wonder if there was a SH alternative. I know that we have had threads about self hosted libraries that we can push ebooks to our kindles (e.g. Calibre) but is there something that y&#39;all use to back up your Kindle libraries that we can host ourselves?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/two-wheel"> /u/two-wheel </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqx6em/backup_amazon_ebooks/">[link]</a></span> &#32; <span><a href="ht

## Domain for $0.18
 - [https://www.reddit.com/r/selfhosted/comments/1iqx4q0/domain_for_018](https://www.reddit.com/r/selfhosted/comments/1iqx4q0/domain_for_018)
 - RSS feed: $source
 - date published: 2025-02-16T17:18:45+00:00

<!-- SC_OFF --><div class="md"><p>I just found this namecheap promo code <code>&quot;WINTWINBACK&quot;</code> and it gives any .site domain for free basically (for the 1st year), you just pay $0.18 for ICANN fees</p> <p>Note: idk how long this will last </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Homelanderr420"> /u/Homelanderr420 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqx4q0/domain_for_018/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqx4q0/domain_for_018/">[comments]</a></span>

## Minisforum MS-01 homelab for self hosting
 - [https://www.reddit.com/r/selfhosted/comments/1iqx3zr/minisforum_ms01_homelab_for_self_hosting](https://www.reddit.com/r/selfhosted/comments/1iqx3zr/minisforum_ms01_homelab_for_self_hosting)
 - RSS feed: $source
 - date published: 2025-02-16T17:17:53+00:00

<!-- SC_OFF --><div class="md"><p>I’m seriously considering building a homelab with this mini pc, which has some serious specs. This is the first time I dive into self hosting on a physical server (I’ve always used VPSs for very small services), I’m just a dev that treats hardware as a tool, I’m not following the pc hardware market really, so any piece of advice is welcome.</p> <p>I want to have a NAS (this is where my biggest hesitation is), most likely using trueNAS in a proxmox vm.</p> <p>For the rest, I’ll most likely run everything in proxmox as needed, although I will primarily run Jellyfin, immich, Nextcloud, paperless ngx and a few more services that I would develop myself in Go.</p> <p>I’m gonna have a Fedora server VM for sure, although for now I don’t know whether I will run my services in podman containers in the vm itself, or directly in proxmox with lxc containers.</p> <p>I might even consider installing TrueNAS on bare metal and use its hypervisor, I’m really open to a

## Advice: recommendations for a self-hosted community server with associated mobile app
 - [https://www.reddit.com/r/selfhosted/comments/1iqwizt/advice_recommendations_for_a_selfhosted_community](https://www.reddit.com/r/selfhosted/comments/1iqwizt/advice_recommendations_for_a_selfhosted_community)
 - RSS feed: $source
 - date published: 2025-02-16T16:53:30+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m the founder of a (non-profit) men&#39;s suicide prevention &amp; mental health support group. I&#39;m looking to self-host a community on a Linux server.</p> <p>Requirements:</p> <ul> <li>Member registration can be enabled / disabled.</li> <li>Member applications are approved before admission.</li> <li>Should have an associated mobile app in the respective app store for members to access the community.</li> <li>Runs natively on Debian 12 <code>aarch64</code>, either as a package, a binary, or compile from source.</li> <li>ETA: Has instant messaging.</li> <li>Does not require a container.</li> <li>No or minimal licensing costs.</li> </ul> <p>So far, <a href="https://element.io">Element</a> + <a href="https://matrix.org/ecosystem/clients/element/">Matrix</a> seems to be a pretty good fit.</p> <p>Are there additional self-hosted community apps that have associated mobile apps that could be considered?</p> <p>I am grateful for your advice and oth

## Travel Location manager
 - [https://www.reddit.com/r/selfhosted/comments/1iqvxa8/travel_location_manager](https://www.reddit.com/r/selfhosted/comments/1iqvxa8/travel_location_manager)
 - RSS feed: $source
 - date published: 2025-02-16T16:27:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey there,</p> <p>does anyone here know of a solution where I can compile travel location from different sites. It doesn&#39;t need to pull data automatically, it can be fed manually. So a glorified database with nice front-end presentation.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/basementkid128"> /u/basementkid128 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqvxa8/travel_location_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqvxa8/travel_location_manager/">[comments]</a></span>

## My neighbor just left the country and gave me 2 Dell poweredge T350. What cool stuff can I do with that? I have an engineering background but not really familiar with using this kind of equipment as I use usually cloud solutions.
 - [https://www.reddit.com/r/selfhosted/comments/1iqvw55/my_neighbor_just_left_the_country_and_gave_me_2](https://www.reddit.com/r/selfhosted/comments/1iqvw55/my_neighbor_just_left_the_country_and_gave_me_2)
 - RSS feed: $source
 - date published: 2025-02-16T16:26:25+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/pacmanpill"> /u/pacmanpill </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqvw55/my_neighbor_just_left_the_country_and_gave_me_2/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqvw55/my_neighbor_just_left_the_country_and_gave_me_2/">[comments]</a></span>

## How to make WordPress site more interactive?
 - [https://www.reddit.com/r/selfhosted/comments/1iqurk5/how_to_make_wordpress_site_more_interactive](https://www.reddit.com/r/selfhosted/comments/1iqurk5/how_to_make_wordpress_site_more_interactive)
 - RSS feed: $source
 - date published: 2025-02-16T15:36:16+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>So, I just made a WordPress website with a custom domain on an old potato computer I got from a thrift store. I was wondering if anyone here has any ideas on how I could make the site more interactive, like sending an email per user&#39;s request, etc. Mind you, I don&#39;t know HTML/CSS/JS, just Python and Bash.</p> <p>I&#39;m saying this because a good chunk of people who visit my site think it&#39;s a <a href="http://wordpress.com">wordpress.com</a> blog.</p> <p>I appreciate any input in advance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Skilled-Potato"> /u/Skilled-Potato </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqurk5/how_to_make_wordpress_site_more_interactive/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqurk5/how_to_make_wordpress_site_more_interactive/">[comments]</a></span>

## Pangolin TCP Stream
 - [https://www.reddit.com/r/selfhosted/comments/1iqum1u/pangolin_tcp_stream](https://www.reddit.com/r/selfhosted/comments/1iqum1u/pangolin_tcp_stream)
 - RSS feed: $source
 - date published: 2025-02-16T15:29:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I use <a href="https://github.com/fosrl/pangolin">Pangolin</a> as my reverse proxy and im currently trying to have my friends join my Minecraft server, but Pangloin only has the option for http or https. Does somebody know how I can get my MC server public?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Space_v2"> /u/Space_v2 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqum1u/pangolin_tcp_stream/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqum1u/pangolin_tcp_stream/">[comments]</a></span>

## Jellyfin, Immich, and NAS OS
 - [https://www.reddit.com/r/selfhosted/comments/1iqtwbf/jellyfin_immich_and_nas_os](https://www.reddit.com/r/selfhosted/comments/1iqtwbf/jellyfin_immich_and_nas_os)
 - RSS feed: $source
 - date published: 2025-02-16T14:56:14+00:00

<!-- SC_OFF --><div class="md"><p>I currently have a PC lying around (still fairly powerful with an i5 8600) and am looking to turn it into a server that runs Jellyfin, a NAS software, and Immich. Which OS and NAS software should I use as I have found that installing them can be quite frustrating and difficult.</p> <p>Thanks so much! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SpaceAce256"> /u/SpaceAce256 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtwbf/jellyfin_immich_and_nas_os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtwbf/jellyfin_immich_and_nas_os/">[comments]</a></span>

## Starting a Weekly Rancher Series – From Zero to Hero!
 - [https://www.reddit.com/r/selfhosted/comments/1iqtqq9/starting_a_weekly_rancher_series_from_zero_to_hero](https://www.reddit.com/r/selfhosted/comments/1iqtqq9/starting_a_weekly_rancher_series_from_zero_to_hero)
 - RSS feed: $source
 - date published: 2025-02-16T14:48:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m kicking off a weekly YouTube series on Rancher, covering everything from getting started to advanced use cases. Whether you&#39;re new to Rancher or looking to level up your Kubernetes management skills, this series will walk you through step-by-step tutorials, hands-on demos, and real-world troubleshooting.</p> <p>I&#39;ve just uploaded the introductory video where I break down what Rancher is and why it matters: 📺 <a href="https://youtu.be/_CRjSf8i7Vo?si=ZR6IcXaNOCCppFiG">https://youtu.be/_CRjSf8i7Vo?si=ZR6IcXaNOCCppFiG</a></p> <p>I&#39;ll be posting new videos every week, so if you&#39;re interested in mastering Rancher, make sure to follow along. Would love to hear your feedback and any specific topics you&#39;d like to see covered!</p> <p>Let’s build and learn together! 🚀</p> <h1>Kubernetes #Rancher #DevOps #Containers #SelfHosting #Homelab</h1> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddi

## Local Audio Enhancer Model
 - [https://www.reddit.com/r/selfhosted/comments/1iqtq1f/local_audio_enhancer_model](https://www.reddit.com/r/selfhosted/comments/1iqtq1f/local_audio_enhancer_model)
 - RSS feed: $source
 - date published: 2025-02-16T14:47:46+00:00

<!-- SC_OFF --><div class="md"><p>Im looking for a local model I can use to enhance audio, such as what <a href="https://podcast.adobe.com/enhance">adobe</a> offers. Even if it is not a propper software tool but the raw thing I am still interested. Thanks in advance! I dont have a specific application, Im tinkering around with audio for the first time for both music and speech.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gas_patxo"> /u/gas_patxo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtq1f/local_audio_enhancer_model/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtq1f/local_audio_enhancer_model/">[comments]</a></span>

## Would Windows 11 LTSC or some other debloat tool help for using Windows 11 as a server OS?
 - [https://www.reddit.com/r/selfhosted/comments/1iqtjab/would_windows_11_ltsc_or_some_other_debloat_tool](https://www.reddit.com/r/selfhosted/comments/1iqtjab/would_windows_11_ltsc_or_some_other_debloat_tool)
 - RSS feed: $source
 - date published: 2025-02-16T14:38:39+00:00

<!-- SC_OFF --><div class="md"><p>First off, yes I know Linux would be better, I&#39;m using Linux for one of my servers. But I am a noob and I have some game servers and media server where I just want the functionality, familiarity, and ease of use that windows has. So I&#39;m wondering if Windows 11 LTSC or some debloat tool would at least help a bit in making it a more viable OS to run my servers on?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Diefuku"> /u/Diefuku </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtjab/would_windows_11_ltsc_or_some_other_debloat_tool/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqtjab/would_windows_11_ltsc_or_some_other_debloat_tool/">[comments]</a></span>

## Need help repurposing an old Inspiron 3847 into a NAS
 - [https://www.reddit.com/r/selfhosted/comments/1iqt127/need_help_repurposing_an_old_inspiron_3847_into_a](https://www.reddit.com/r/selfhosted/comments/1iqt127/need_help_repurposing_an_old_inspiron_3847_into_a)
 - RSS feed: $source
 - date published: 2025-02-16T14:12:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to repurpose an old computer as a NAS for storing pictures but I&#39;m not sure about its limitations. I&#39;m probably going to use TrueNAS with Immich.</p> <p>I haven&#39;t powered it on yet so I&#39;m not sure about the CPU, but here are the other specs I know:</p> <p>RAM: 2x4GB DDR3</p> <p>PSU: 300W</p> <p>1 PCIe x16 port</p> <p>2 PCIe x1 ports</p> <p>1 M.2 E-key (WiFi card currently installed)</p> <p>2 HDD ports (1 TB HDD in one port)</p> <p>2 ODD ports</p> <p>I&#39;ve tried researching on my own but got a bit lost, so any tips or advice are appreciated. However, I do have several questions of my own:</p> <p>RAM upgrade: I think the motherboard supports up to 16GB of RAM. Is it worth it to upgrade if I&#39;m only storing pictures?</p> <p>Boot drive: Since the system will be connected via Ethernet, should I remove the wifi cards and use a M.2 storage card for the boot drive? Or should I just boot from a USB flash drive?</p> <p>Stor

## How should I licence a selfhostable app from being commercialized by someone else?
 - [https://www.reddit.com/r/selfhosted/comments/1iqsmur/how_should_i_licence_a_selfhostable_app_from](https://www.reddit.com/r/selfhosted/comments/1iqsmur/how_should_i_licence_a_selfhostable_app_from)
 - RSS feed: $source
 - date published: 2025-02-16T13:52:25+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say I build a selfhostable application that serves solely end users (aka B2C). So, it&#39;s something like Immich, rather Redis. </p> <p>Is there a well-known licence that I can use for my project that serves my needs described below?</p> <p>I know, if I choose something like AGPLv3 (like Immich did, btw), I can make sure that any derivatives of my code will be also FOSS. And while it can turn away some of potential companies that aren&#39;t willing to share the code of their commercialized fork, it does not save me from companies that can just take my code AS IS and build a paid SaaS based on it. </p> <p>My wish is to build an application that will be always free and open source (or, to be precise &quot;Source-available&quot; since what I&#39;m trying to achieve seems to be against FOSS commuty) for users who selfhost it for private and non-commercial use, but no one except myself is allowed to provide paid SaaS version of it.</p> <p>I lov

## SSL certifacate for LAN server
 - [https://www.reddit.com/r/selfhosted/comments/1iqs3bf/ssl_certifacate_for_lan_server](https://www.reddit.com/r/selfhosted/comments/1iqs3bf/ssl_certifacate_for_lan_server)
 - RSS feed: $source
 - date published: 2025-02-16T13:22:26+00:00

<!-- SC_OFF --><div class="md"><p>I have a home server with many self-hosted services. Some services are exposed to the internet through a VPS. On the VPS i have Nginx Proxy Manager (NPM) as reverse proxy for these services. Since i got this server up, i always used to set a wildcard Let&#39;s Encrypt certificate for my NPM instance on VPS for SSL from external clients and HTTP over Wireguard for routing requests from the VPS to my home server. This is working pretty well for years.</p> <p>Now, i want access my services with the same url &quot;https://*.mydns:port&quot;, regardless i&#39;m accessing them from external or internal of my LAN. For this i set up a pi-hole instance for solving DNS in my LAN. But i also need an SSL certificate in order to use the same protocol that I use from external clients.</p> <p>My idea is to set up a new Nginx Proxy Manager (NPM) instance on my home server where i should register all sub-domains of my services, as i&#39;ve done on the VPS until now. 

## Server down - Emergency plan for next time
 - [https://www.reddit.com/r/selfhosted/comments/1iqrtac/server_down_emergency_plan_for_next_time](https://www.reddit.com/r/selfhosted/comments/1iqrtac/server_down_emergency_plan_for_next_time)
 - RSS feed: $source
 - date published: 2025-02-16T13:06:38+00:00

<!-- SC_OFF --><div class="md"><p>At the moment my server is kinda down (looks like it has high load and therefore doesn‘t respond). I can‘t do anything, because I‘m not at home.</p> <p>I get to the password prompt with ssh, but nothing happens after that.</p> <p>So I thought about two things:</p> <ul> <li><p>Can I prioritize ssh? With nicevalues or reserve resources?</p></li> <li><p>I had already connected the server in the past with serial to another PC, exactly for such cases. But it didn&#39;t work well (it was as if someone was pressing something in the boot menu, for example (does anyone know what the cause of this could be?)). Does anyone know of a project with an ESP that can be connected serially to the server and then accessed via ssh?</p></li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tone866"> /u/Tone866 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqrtac/server_down_emergency_plan_for_next_time/">[

## [TESTING] Developing a Web App for Monitoring & Storing NUT Data – Need UPS Data for Testing
 - [https://www.reddit.com/r/selfhosted/comments/1iqrr4o/testing_developing_a_web_app_for_monitoring](https://www.reddit.com/r/selfhosted/comments/1iqrr4o/testing_developing_a_web_app_for_monitoring)
 - RSS feed: $source
 - date published: 2025-02-16T13:03:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m working on a web app using Python, JavaScript, and other technologies to monitor and store data from <strong>NUT (Network UPS Tools)</strong>. My goal is to create a platform that not only logs UPS data but also provides real-time cost analysis based on power consumption.</p> <p>To improve testing and refine my implementation, I’d like to compare data from different <strong>UPS brands and models</strong>. If you have a UPS connected to NUT, I’d really appreciate it if you could share some sample output <strong>(without the serial number, as I don’t need it)</strong>.</p> <p>Please <strong>send it to me via private message</strong> so I can analyze real-world variations in UPS data and make the system more adaptable. Thanks in advance! 🚀</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DartSteven"> /u/DartSteven </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqrr4o

## For the recipes enthusiasts of self hosted solution
 - [https://www.reddit.com/r/selfhosted/comments/1iqrp41/for_the_recipes_enthusiasts_of_self_hosted](https://www.reddit.com/r/selfhosted/comments/1iqrp41/for_the_recipes_enthusiasts_of_self_hosted)
 - RSS feed: $source
 - date published: 2025-02-16T13:00:05+00:00

<!-- SC_OFF --><div class="md"><p>Hi, Selfhosted users I just want to grab your attention and present you with this selfhosted recipe managment application that just got a update and with the help of chatgpt you can translate recipe to languages you want.(Languge addition on demand can happen). The app has scraping functionality also and is work pretty great with most recipes.You even can generate a recipe by ingredients and scrape it afterwards. Meal planner , categories, favorites and more functionality in the app.</p> <p>Take a look of the repository and leave a star 🌟. Stay cool and keep selfhosted. <a href="https://github.com/mikebgrep/fork.recipes">https://github.com/mikebgrep/fork.recipes</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Dog-715"> /u/Affectionate-Dog-715 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqrp41/for_the_recipes_enthusiasts_of_self_hosted/">[link]</a></span> &#32; <span><

## voip solution
 - [https://www.reddit.com/r/selfhosted/comments/1iqrg5u/voip_solution](https://www.reddit.com/r/selfhosted/comments/1iqrg5u/voip_solution)
 - RSS feed: $source
 - date published: 2025-02-16T12:44:43+00:00

<!-- SC_OFF --><div class="md"><p>I have a physical SIM that does not support Wi-Fi calling (UAE). How can I convert my physical SIM to VoIP so that I can use it globally to make calls and receive SMS with an application on my phone?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kingssm3n"> /u/kingssm3n </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqrg5u/voip_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqrg5u/voip_solution/">[comments]</a></span>

## Containers connecting to Gluetun network leaking IP
 - [https://www.reddit.com/r/selfhosted/comments/1iqrfll/containers_connecting_to_gluetun_network_leaking](https://www.reddit.com/r/selfhosted/comments/1iqrfll/containers_connecting_to_gluetun_network_leaking)
 - RSS feed: $source
 - date published: 2025-02-16T12:43:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey team, I&#39;m trying to setup a VPN container, and seperate Sabnzbd and Sonarr containers, which will use the VPN container for it&#39;s network. </p> <p>It seems I can setup the Gluetun container using the Private Internet Access VPN no problem. The logs spit out the public IP which is different to my real IP. </p> <p>However when I configure Sonarr to use the Gluetun network, it seems to attach to the network with no issue. However when testing via console with `curl ip.me` it&#39;s exposing my real IP. </p> <p>This happens when the Gluetun container is running fine, or if it&#39;s in a restart loop if I give it bogus credentials. I&#39;d expect Sonarr to have no access to the internet if the network container is not healthy. I&#39;d also expect it to use the VPN IP. </p> <p>Here are my 2 docker compose files. The Gluetun stack will create the `gluetun_default` network, which I add to the `VPN_NETWORK` env var for the Sonarr stack. What am I do

## Nginxproxymanager not accessible randomly
 - [https://www.reddit.com/r/selfhosted/comments/1iqra2c/nginxproxymanager_not_accessible_randomly](https://www.reddit.com/r/selfhosted/comments/1iqra2c/nginxproxymanager_not_accessible_randomly)
 - RSS feed: $source
 - date published: 2025-02-16T12:34:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello all, </p> <p>So I have installed proxmox and nginxproxymanager as lxc on my machine. There Ive added some hosts that points on some of my local machines.</p> <p>The NPM is also exposed to the internet. Not actually it works, but from time to time, NPM is randomly that accessable neither from the internet nor from the local network, hence all my services are randomly sometimes not accesible.</p> <p>Does someone know why or had similar experiences?</p> <p>I would really appreciate any help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ill_Anybody_1860"> /u/Ill_Anybody_1860 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqra2c/nginxproxymanager_not_accessible_randomly/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqra2c/nginxproxymanager_not_accessible_randomly/">[comments]</a></span>

## Docmost - can I make the docs public? I really like it and I really wanna make it public.
 - [https://www.reddit.com/r/selfhosted/comments/1iqr6ld/docmost_can_i_make_the_docs_public_i_really_like](https://www.reddit.com/r/selfhosted/comments/1iqr6ld/docmost_can_i_make_the_docs_public_i_really_like)
 - RSS feed: $source
 - date published: 2025-02-16T12:28:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>Is there any way to make the docmost site visible to public? It would be a huge huge time saving approach for me if it&#39;s possible. </p> <p>I&#39;m happy to customize the code if needed but I need a method to serve a public doc site. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dizzy_Pizza3997"> /u/Dizzy_Pizza3997 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqr6ld/docmost_can_i_make_the_docs_public_i_really_like/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqr6ld/docmost_can_i_make_the_docs_public_i_really_like/">[comments]</a></span>

## What Portable Live GPS Tracker can you recommend?
 - [https://www.reddit.com/r/selfhosted/comments/1iqql58/what_portable_live_gps_tracker_can_you_recommend](https://www.reddit.com/r/selfhosted/comments/1iqql58/what_portable_live_gps_tracker_can_you_recommend)
 - RSS feed: $source
 - date published: 2025-02-16T11:48:13+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,<br/> I’m working on a project that requires live tracking of multiple people (via devices in their backpacks) with updates at intervals of &lt;10 seconds. I’ve looked into smartwatches, but they aren’t advanced enough for my needs. Here are the key requirements:</p> <ul> <li><strong>Portable:</strong> Battery-powered with 24h+ capability under constant usage</li> <li><strong>Live GPS updates:</strong> Less than 10-second intervals</li> <li><strong>eSIM/nano-SIM support:</strong> So I can use my own SIM, no subscription services</li> <li><strong>Customizable:</strong> Must connect to custom APIs or allow setting up my own server architecture</li> </ul> <p>The issue I’ve found is that most GPS trackers seem subscription-based, with vague technical details and questionable reliability. If anyone has experience with hardware that fits these needs or can recommend open-source-friendly devices, I’d greatly appreciate your help!</p> </div><!-- SC_ON

## Just Started a Business – Looking for Open Source Solutions Advice (Firewall, SIEM, NAS, etc.)
 - [https://www.reddit.com/r/selfhosted/comments/1iqq6kr/just_started_a_business_looking_for_open_source](https://www.reddit.com/r/selfhosted/comments/1iqq6kr/just_started_a_business_looking_for_open_source)
 - RSS feed: $source
 - date published: 2025-02-16T11:18:40+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I’ve recently started a small business, and I’m setting up the IT infrastructure myself. I have around 4 PCs and want to implement the best possible security and storage solutions without breaking the bank. I’m looking for recommendations on free and open-source tools for the following:</p> <ul> <li><strong>Firewall:</strong> Something reliable that can help with network security and control traffic.</li> <li><strong>SIEM:</strong> I’d like to monitor logs and detect potential threats. Lightweight but effective would be ideal.</li> <li><strong>Network Attached Storage (NAS):</strong> A secure and easy-to-manage solution for local file sharing and backups.</li> </ul> <p>If anyone has experience with setting up a similar environment or has general advice on securing a small business network, I’d love to hear it!</p> <p>Thanks in advance for your help and recommendations!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="ht

## Struggling for Using Headscale, Tailscale, and Caddy for Remote Access
 - [https://www.reddit.com/r/selfhosted/comments/1iqq1o1/struggling_for_using_headscale_tailscale_and](https://www.reddit.com/r/selfhosted/comments/1iqq1o1/struggling_for_using_headscale_tailscale_and)
 - RSS feed: $source
 - date published: 2025-02-16T11:08:52+00:00

<!-- SC_OFF --><div class="md"><p>I am running a Proxmox server, and i tried to set up Headscale + Tailscale along with Caddy as a reverse proxy. I&#39;ve got Two LXC container, One for headscale with this config.yaml :</p> <pre><code>server_url: &quot;https://headscale.example.com&quot; # Configured to listen on port 8080 (HTTP) so that it can be reached internally. Originally it was bound to localhost (127.0.0.1), but changed it to 0.0.0.0:8080 so other containers can connect. listen_addr: &quot;0.0.0.0:8080&quot; metrics_listen_addr: &quot;0.0.0.0:9090&quot; tls_cert_path: &quot;&quot; tls_key_path: &quot;&quot; </code></pre> <p>And Caddy/Tailscale in another container, listen on port 443 <strong>and</strong> 80, with this caddyfile :</p> <pre><code>headscale.cloud.ermont.com { reverse_proxy 192.168.1.89:8080 } #etc/hosts # --- BEGIN PVE --- 127.0.1.1 caddy.tom.local caddy # --- END PVE --- 127.0.0.1 headscale.example.com </code></pre> <p>Originally, this hostname pointing directl

## NAS like docker container
 - [https://www.reddit.com/r/selfhosted/comments/1iqq073/nas_like_docker_container](https://www.reddit.com/r/selfhosted/comments/1iqq073/nas_like_docker_container)
 - RSS feed: $source
 - date published: 2025-02-16T11:05:54+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am currently looking for a NAS like docker container to access files which are on docker volumes. The most common answer I get is FileBrowser, which ticks a lot of boxes, but I would also love to host the files as smb shares. The common way would probably be to host an VM with TrueNAS or OMV, but in my case I´m on a hosted VM, which acts as a docker host.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Anatu_spb"> /u/Anatu_spb </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqq073/nas_like_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqq073/nas_like_docker_container/">[comments]</a></span>

## Video editing software
 - [https://www.reddit.com/r/selfhosted/comments/1iqpqdr/video_editing_software](https://www.reddit.com/r/selfhosted/comments/1iqpqdr/video_editing_software)
 - RSS feed: $source
 - date published: 2025-02-16T10:46:45+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I would like to know if there is some video editing software, free, that I can self host on my home lab.</p> <p>Something like Apple iMovie but that I can self host and then use with a web interface.</p> <p>I don’t know if this even make sense, just asking. The goals is to have the software that I need on the central server instead of spread between different client at home.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Old_Rock_9457"> /u/Old_Rock_9457 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqpqdr/video_editing_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqpqdr/video_editing_software/">[comments]</a></span>

## Guacamole with Authentik OIDC Error 502 on redirect
 - [https://www.reddit.com/r/selfhosted/comments/1iqpmb8/guacamole_with_authentik_oidc_error_502_on](https://www.reddit.com/r/selfhosted/comments/1iqpmb8/guacamole_with_authentik_oidc_error_502_on)
 - RSS feed: $source
 - date published: 2025-02-16T10:38:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have a working Apache Guacamole instance selfhosted with the official docker containers. I also have an Authentik instance. They&#39;re both working fine for themselves. Authentik provides working OpenID authentication for several other services I selfhost. Now of course I wanted to add OpenID to Guacamole as well. As far as I can tell I set up everything correctly. I even had it working before, but something borked that setup and I had to redo it from scratch since my backups didn&#39;t work either.</p> <p>When I try to login using oidc I get redirected to Authentik, login there just fine and get redirected back. Except I end up on a page telling me there was a 502 Error instead of the guacamole dashboard.</p> <p>The logs give no indication on what goes wrong. The only log entry that get&#39;s created when I try to login using oidc is in the tomcat logs (localhost_access_log) is:</p> <pre><code>192.168.2.128 - - [16/Feb/2025:10

## Reverse proxying Application control
 - [https://www.reddit.com/r/selfhosted/comments/1iqpjtn/reverse_proxying_application_control](https://www.reddit.com/r/selfhosted/comments/1iqpjtn/reverse_proxying_application_control)
 - RSS feed: $source
 - date published: 2025-02-16T10:33:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys!</p> <p>I have a setup where I have multiple VMs with Nginx Proxy Manager reverse proxying several containerized apps. This is easy and allows me all the goodies of SSL, custom DNS (I also have Pihole).</p> <p>But I am looking for a good solution to implement access control to the apps.</p> <p>I use netbird and can manage access to the NPM host.<br/> But to further control the application access I need another way because if I allow access to the NPM host, it will automatically have access to all the apps running on that host.<br/> I know I can add access lists on NPM but i&#39;d like a better solution, ideally with groups.</p> <p>I am thinking of simply having multiple NPM on different host ports and each one serves different apps<br/> That way I could filter access to each specific NPM instance.</p> <p>Anyone has an idea of what could help?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user

## Flame project dead?
 - [https://www.reddit.com/r/selfhosted/comments/1iqoti3/flame_project_dead](https://www.reddit.com/r/selfhosted/comments/1iqoti3/flame_project_dead)
 - RSS feed: $source
 - date published: 2025-02-16T09:41:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi! </p> <p>I assume that the Flame <a href="https://github.com/pawelmalak/flame/tree/master">https://github.com/pawelmalak/flame/tree/master</a> project is dead, is there any alternative, similar easy to use and which can be hosted in a docker container?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MickyGER"> /u/MickyGER </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqoti3/flame_project_dead/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqoti3/flame_project_dead/">[comments]</a></span>

## Anyone know why metube will not download?
 - [https://www.reddit.com/r/selfhosted/comments/1iqoo8b/anyone_know_why_metube_will_not_download](https://www.reddit.com/r/selfhosted/comments/1iqoo8b/anyone_know_why_metube_will_not_download)
 - RSS feed: $source
 - date published: 2025-02-16T09:29:57+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1iqoo8b/anyone_know_why_metube_will_not_download/"> <img src="https://preview.redd.it/hbj9lwexzgje1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=7ec7e66d2bf4b0f5e896ff4cce695a2522c9181e" alt="Anyone know why metube will not download?" title="Anyone know why metube will not download?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>The display just shows what you can see in the picture for about 5 minutes and then cancels the download saying it failed with no other details or error codes. Any idea what could be causing this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NIDNHU"> /u/NIDNHU </a> <br/> <span><a href="https://i.redd.it/hbj9lwexzgje1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqoo8b/anyone_know_why_metube_will_not_download/">[comments]</a></span> </td></tr></table>

## Should I Open Source My Project If a Better Alternative Exists?
 - [https://www.reddit.com/r/selfhosted/comments/1iqnnnj/should_i_open_source_my_project_if_a_better](https://www.reddit.com/r/selfhosted/comments/1iqnnnj/should_i_open_source_my_project_if_a_better)
 - RSS feed: $source
 - date published: 2025-02-16T08:15:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I’d love to hear your thoughts on something I’ve been debating.</p> <p>For the past three months, I’ve been building my own <strong>social media scheduler</strong>, and recently, I started considering making it open source. My thinking was that the code itself isn’t that valuable to keep private, and open-sourcing would allow developers who don’t want to pay for a tool like this to self-host it instead.</p> <p>But here’s the dilemma:<br/> I just discovered Postiz—an open-source project that does exactly what my tool does, but better. It’s already well-developed, has extensive documentation, and was built by a more experienced developer using NestJS and a more modularized architecture.</p> <p>So now I’m wondering:<br/> Does it still make sense for me to go open source? Would anyone actually want to contribute or use my project when there’s already a superior alternative?</p> <p>That said, I still want to keep working on my project

## Hardware Questions - Synology vs Mac Mini
 - [https://www.reddit.com/r/selfhosted/comments/1iqni36/hardware_questions_synology_vs_mac_mini](https://www.reddit.com/r/selfhosted/comments/1iqni36/hardware_questions_synology_vs_mac_mini)
 - RSS feed: $source
 - date published: 2025-02-16T08:04:16+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I&#39;m trying to work out if I&#39;m better off running my docker apps through an old Mac Mini (Late 2012) or my Synology DS920+. Currently I&#39;m running the *arrs, Immich and Plex and they&#39;re all on the Synology. Not sure if I&#39;m best relocating them to the Mac Mini now I have replaced it with a newer Mac Mini</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/girdles"> /u/girdles </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqni36/hardware_questions_synology_vs_mac_mini/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqni36/hardware_questions_synology_vs_mac_mini/">[comments]</a></span>

## Piwigo Video and PDF Support
 - [https://www.reddit.com/r/selfhosted/comments/1iqnco6/piwigo_video_and_pdf_support](https://www.reddit.com/r/selfhosted/comments/1iqnco6/piwigo_video_and_pdf_support)
 - RSS feed: $source
 - date published: 2025-02-16T07:53:48+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know how to add pdf files and mp4 (videos) to a piwigo album, I downloaded a plugin for that but it still marks each file as &quot;error&quot; would there be a way to fix this, is anyone else having the same issue? </p> <p>Thanks. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gfdsatg"> /u/gfdsatg </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqnco6/piwigo_video_and_pdf_support/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqnco6/piwigo_video_and_pdf_support/">[comments]</a></span>

## Where do I start? Homeserver
 - [https://www.reddit.com/r/selfhosted/comments/1iqnbau/where_do_i_start_homeserver](https://www.reddit.com/r/selfhosted/comments/1iqnbau/where_do_i_start_homeserver)
 - RSS feed: $source
 - date published: 2025-02-16T07:51:01+00:00

<!-- SC_OFF --><div class="md"><p>Hi I’ve just now had my mind blown by the world of home servers and realized it’s just what me and my family needs. But I don’t know where to start there are alot of YouTubers making videos in the topic and seemingly doing overkill setups. </p> <p>My question is provably rather large i suppose - where do I start? What do I actually need for me and my family.</p> <p>I just want to run a media setup like plex and/or jellyfin, while maybe also running the occasional Minecraft server. Plus maybe have some storage to access from most places, or to backup photos.</p> <p>Could i do this from an old laptop or would a raspberryPi suffice. What am I looking at here? I don’t want to break the bank but I also want to invest in this.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RepresentativeWin278"> /u/RepresentativeWin278 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqnbau/where_do_i_start_hom

## Docker swarm (or K3S) with something better than NFS for config storage?
 - [https://www.reddit.com/r/selfhosted/comments/1iqmuca/docker_swarm_or_k3s_with_something_better_than](https://www.reddit.com/r/selfhosted/comments/1iqmuca/docker_swarm_or_k3s_with_something_better_than)
 - RSS feed: $source
 - date published: 2025-02-16T07:16:48+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently running 5–6 Docker containers (Home Assistant, Caddy, Homebridge, Omada Controller etc.) on a low-power x86 box. I also have a NAS set up (just an SMB/NFS share) running on a slightly more powerful x86 box. I&#39;ll probably be adding another one or two machines to my local network (perhaps only a Raspberry pi)</p> <p>I&#39;m happy using Portainer on my single node, and I&#39;d love to keep using it with Docker Swarm (or K3s if necessary).</p> <p>I&#39;m trying to figure out the simplest way to add some redundancy for these containers (and others) in terms of configuration. Ideally, I&#39;d like to semi-persistently sync key config volumes (e.g., Home Assistant configs) across 2–3 nodes so that my network isn&#39;t entirely reliant on the NAS. I don&#39;t care about maintaining perfect state or keeping logs continuity etc., I just want Omada controller and Home Assistant to come back up on a different node with a roughly up to date 

## Adding Jumper to make miniPC autostart on power failure
 - [https://www.reddit.com/r/selfhosted/comments/1iqmix7/adding_jumper_to_make_minipc_autostart_on_power](https://www.reddit.com/r/selfhosted/comments/1iqmix7/adding_jumper_to_make_minipc_autostart_on_power)
 - RSS feed: $source
 - date published: 2025-02-16T06:54:53+00:00

<!-- SC_OFF --><div class="md"><p>Model &amp; physical images: <a href="https://4pda.to/forum/index.php?showtopic=699603">https://4pda.to/forum/index.php?showtopic=699603</a></p> <p>Machine to be used as personal server.</p> <p>My objective is to add a jumper such that I don&#39;t have to switch PC on (via touch sensor) after power failure (<strong>BIOS do not have this feature</strong>).</p> <p>All online pictures indicate a 2x4 array of front panel connectors (Intel NUC) but my connector also has total x8 pins but are in a single row?</p> <p><a href="https://preview.redd.it/cb4ft3d9oeje1.png?width=208&amp;format=png&amp;auto=webp&amp;s=bf77f94188b612856276b6aa0070ab541874e668">If I find equivalent pin to 6-8 I will add jumper to make it auto power on</a></p> <p>Will upload detailed images for proper discussion</p> <p><a href="https://preview.redd.it/39s4sbx5ieje1.jpg?width=500&amp;format=pjpg&amp;auto=webp&amp;s=010cc6f66f1ec800677f48cd21980690629dda0a">Power button is a touch sens

## Best mini device to host a small Minecraft server?
 - [https://www.reddit.com/r/selfhosted/comments/1iqjv8y/best_mini_device_to_host_a_small_minecraft_server](https://www.reddit.com/r/selfhosted/comments/1iqjv8y/best_mini_device_to_host_a_small_minecraft_server)
 - RSS feed: $source
 - date published: 2025-02-16T04:08:57+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;m going to self host a very small Minecraft server (vanilla with 2-3 mods) with like 5 players and i&#39;m looking for a small AND cheap device</p> <p>I&#39;m already looking for used mini-pc&#39;s to buy but if you have some exact models to recommend let me know please ! Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CancerousGTFO"> /u/CancerousGTFO </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqjv8y/best_mini_device_to_host_a_small_minecraft_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqjv8y/best_mini_device_to_host_a_small_minecraft_server/">[comments]</a></span>

## Tips on c-stats/aspm?
 - [https://www.reddit.com/r/selfhosted/comments/1iqineb/tips_on_cstatsaspm](https://www.reddit.com/r/selfhosted/comments/1iqineb/tips_on_cstatsaspm)
 - RSS feed: $source
 - date published: 2025-02-16T02:58:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1iqineb/tips_on_cstatsaspm/"> <img src="https://preview.redd.it/6tsn4va42fje1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=68e69d6aa295846d06f3811deaf7fc266a4aaad7" alt="Tips on c-stats/aspm?" title="Tips on c-stats/aspm?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I have an unRAID server I run, and if I use powertop I get the following output</p> <p>```</p> <blockquote> <blockquote> <p>Bad Enable SATA link power management for host6 Bad Enable SATA link power management for host7 Bad Enable SATA link power management for host5 Bad Enable SATA link power management for host3 Bad Enable SATA link power management for host1 Bad Enable SATA link power management for host8 Bad Enable SATA link power management for host4 Bad Enable SATA link power management for host2 Bad VM writeback timeout Bad Autosuspend for USB device USB Flash Drive [Lexar] Bad Autosuspend for USB device MYSTIC LIGHT [MSI] Bad Runti

## Serious Question for the SelfHosted Community: Why aren't we on a selfhosted social platform?
 - [https://www.reddit.com/r/selfhosted/comments/1iqik23/serious_question_for_the_selfhosted_community_why](https://www.reddit.com/r/selfhosted/comments/1iqik23/serious_question_for_the_selfhosted_community_why)
 - RSS feed: $source
 - date published: 2025-02-16T02:53:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll start out with the TLDR: With the way large social media companies are acting these days, including reddit, why are we not all on Lemmy or something similar (if there is something similar)? </p> <p>We all talk about open source and owning our own data. We all talk about leaving google, Facebook, this paid platform, that commercial software, etc. Yet here we are.</p> <p>I love this community. It has taught me a lot. I have had private discussions with fellow selfhosters both getting help and giving. I have had conversations with developers of software I use which is so cool. That said, with the way &quot;big social media&quot; acts these days I find myself wondering why we aren&#39;t all on a selfhosted platform like Lemmy or something like it. I mean if there is a subreddit that should be at the forefront of going to an alternative platform isnt it us? </p> <p>Since this is sort of a controversial question I just want to say that I am not tr

## Rack mountable power strip that also doubles as a UPS?
 - [https://www.reddit.com/r/selfhosted/comments/1iqhqzk/rack_mountable_power_strip_that_also_doubles_as_a](https://www.reddit.com/r/selfhosted/comments/1iqhqzk/rack_mountable_power_strip_that_also_doubles_as_a)
 - RSS feed: $source
 - date published: 2025-02-16T02:09:21+00:00

<!-- SC_OFF --><div class="md"><p>Is there such a thing as a 6 outlet power strip UPS? At most, I don&#39;t mind if it takes up 2U of space and it has to fit in a deskpi. A standard power strip fits just fine. A battery type of LifePo4.</p> <p>Edit: Oh and a fuse or a breaker that pops, instead of any device down the line?</p> <p>Kinda want to do this myself with a bunch of UGreen power banks for that PD deliver and smart charging, but I don&#39;t know where to even start. If I were to wire up all the positive and negative leads together that are coming out of the USB ports and feeding those wires through the wires of the power strip, would that be a problem?</p> <p>Does a service exist where they custom make power strip UPSs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkAngle2353"> /u/OkAngle2353 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqhqzk/rack_mountable_power_strip_that_also_doubles_as_a/">[link]</a></sp

## ePub to Audiobook
 - [https://www.reddit.com/r/selfhosted/comments/1iqhge8/epub_to_audiobook](https://www.reddit.com/r/selfhosted/comments/1iqhge8/epub_to_audiobook)
 - RSS feed: $source
 - date published: 2025-02-16T01:54:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Valos12"> /u/Valos12 </a> <br/> <span><a href="https://audio.visuai.io/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqhge8/epub_to_audiobook/">[comments]</a></span>

## cleanuperr v1.5.0 🚀 - Dry run, Notifiarr support and a seeding download cleaner added
 - [https://www.reddit.com/r/selfhosted/comments/1iqh9qk/cleanuperr_v150_dry_run_notifiarr_support_and_a](https://www.reddit.com/r/selfhosted/comments/1iqh9qk/cleanuperr_v150_dry_run_notifiarr_support_and_a)
 - RSS feed: $source
 - date published: 2025-02-16T01:44:19+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I hope everyone had a great weekend so far!</p> <p>✨ I&#39;m happy to announce that cleanuperr v1.5.0 has been released.</p> <p>Quick recap from <a href="https://www.reddit.com/r/selfhosted/comments/1i28zik/cleanuperr_v140_added_lidarr_support_private/">last time</a>:</p> <p>cleanuperr is a tool for automating the cleanup of unwanted files, stalled downloads and failed imports for Sonarr, Radarr and Lidarr.</p> <p>Supported download clients:</p> <ul> <li>none (useful for, but not limited to, Usenet protocol)</li> <li>qBittorrent</li> <li>Deluge</li> <li>Transmission</li> </ul> <p>What changed since v1.4.0:</p> <p>- Added a `DRY_RUN` option to help with testing your setup before committing to deleting stuff.<br/> - Added Notifiarr support to get notified on certain actions.<br/> - Added a download cleaner to remove seeding downloads when a certain ratio or seed time has been reached.<br/> - Added option to reset stalled strikes on download progres

## SMB inventory management options?
 - [https://www.reddit.com/r/selfhosted/comments/1iqh342/smb_inventory_management_options](https://www.reddit.com/r/selfhosted/comments/1iqh342/smb_inventory_management_options)
 - RSS feed: $source
 - date published: 2025-02-16T01:34:19+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for an inventory management solution for my business. I have raw materials and blank items that I need to track. I also want to be able to write POs so that I can keep track of incoming and have it added to inventory upon receipt. </p> <p>I spent some time trying to get inventree running in docker but kept pulling errors. The most frustrating was the pgdump file is in v15 but my pg database server is running v17 so it is apparently not compatible. I tried with the docker pg image but that has the same problem. The bare metal install is based on old versions of debian (11) and ubuntu (20) so don&#39;t really want to load up a new app that runs on an os that is going out of support. </p> <p>I need something that is good with actual materials. I&#39;ve seem systems for IT or electronics but not sure how well those will work for my needs. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Witty_Leopard

## NetAlertX: Lessons learned from renaming a project
 - [https://www.reddit.com/r/selfhosted/comments/1iqgpkt/netalertx_lessons_learned_from_renaming_a_project](https://www.reddit.com/r/selfhosted/comments/1iqgpkt/netalertx_lessons_learned_from_renaming_a_project)
 - RSS feed: $source
 - date published: 2025-02-16T01:14:23+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://imgur.com/JshKE2a">Pulls over time</a></p> <p>Thinking about renaming your project? Here’s what I learned when I rebranded PiAlert to <a href="https://netalertx.com/">NetAlertX</a>.</p> <ol> <li><p>Make it as painless as possible for existing users</p> <p>Seeing how many projects have breaking changes between versions, I wanted to give existing users a pretty seamless upgrade path. So the migration was mostly automated, with minimal user interaction needed. </p></li> <li><p>Secure domains and social handles </p> <p>The rename is giving you an opportunity to grab some good social and domain names. Do some research what&#39;s available before deciding on a name. </p></li> <li><p>Track the user transition</p> <p>Track the user transition between your old and new app, if needed. This will allow you to make informed decisions when you think it&#39;s ok to completely retire the old application. I did this with a simple Google spreadsheet. 

## Help with Caddy on Local Network *Updated*
 - [https://www.reddit.com/r/selfhosted/comments/1iqgg38/help_with_caddy_on_local_network_updated](https://www.reddit.com/r/selfhosted/comments/1iqgg38/help_with_caddy_on_local_network_updated)
 - RSS feed: $source
 - date published: 2025-02-16T01:00:43+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>Thank you to everyone who helped last time. I&#39;m trying to setup caddy with cloudflare DNS-01 challenge. I re-set my docker instance back up with a new caddyfile. </p> <p>I changed the DNS records on cloudflare&#39;s website about 30 mins ago but I&#39;m still unable to navigate to adguard.example.my and view my adguard instance. I get this failure <a href="https://imgur.com/M3M31M8">error</a></p> <p><a href="https://imgur.com/cbwrvLY">container details</a></p> <p><a href="https://imgur.com/RXaB8kK">container list</a></p> <p><a href="https://imgur.com/RFld8tJ">DNS records</a></p> <p><a href="https://imgur.com/49kv2d1">manually navigated</a></p> <p><a href="https://imgur.com/ww2mCyh">caddyfile</a></p> <p><a href="https://imgur.com/pmF74Js">cloudflare DNS analytics</a></p> <p><a href="https://imgur.com/ucvnXah">log</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PesteringKitty"> /u/PesteringKi

## Guide on SSH certificates (signed by a CA, i.e. not plain keys) setup - client and host side alike
 - [https://www.reddit.com/r/selfhosted/comments/1iqgaz1/guide_on_ssh_certificates_signed_by_a_ca_ie_not](https://www.reddit.com/r/selfhosted/comments/1iqgaz1/guide_on_ssh_certificates_signed_by_a_ca_ie_not)
 - RSS feed: $source
 - date published: 2025-02-16T00:53:31+00:00

<!-- SC_OFF --><div class="md"><p>Whilst originally written for Proxmox VE users, this can be easily followed by anyone for standard Linux deployment - hosts, guests, virtual instances - when adjusted appropriately.</p> <p>The linked OP of mine below is free of any tracking, but other than the limiting formatting options of Reddit, full content follows as well.</p> <hr/> <h1>SSH certificates setup</h1> <p><strong>TL;DR</strong> PKI SSH setups for complex clusters or virtual guests should be a norm, one which improves security, but also manageability. With a scripted setup, automated key rotations come as a bonus.</p> <hr/> <p><strong>ORIGINAL POST</strong> <a href="https://free-pmx.pages.dev/guides/ssh-certs/"><strong>SSH certificates setup</strong></a></p> <hr/> <p>Following an explanatory post on <a href="https://free-pmx.pages.dev/insights/ssh-pki/">how to use SSH within Public-key Infrastructure (PKI)</a>, the following is an <em>example</em> how to deploy it within almost any en

## Ive tried everything. I cant get Bookstack to work on portainer. Please help before I go insane
 - [https://www.reddit.com/r/selfhosted/comments/1iqg7d3/ive_tried_everything_i_cant_get_bookstack_to_work](https://www.reddit.com/r/selfhosted/comments/1iqg7d3/ive_tried_everything_i_cant_get_bookstack_to_work)
 - RSS feed: $source
 - date published: 2025-02-16T00:48:16+00:00

<!-- SC_OFF --><div class="md"><p>I want to run bookstack in portainer but I cant get it to work. I have tried damn near everything to diagnose it, and just get it to work and I simply cant. It is basically the same error every time.</p> <pre><code>To support LSIO projects visit: ─────────────────────────────────────── GID/UID ─────────────────────────────────────── User UID: 1000 User GID: 100 ─────────────────────────────────────── version: v24.12.1-ls192Build-date: 2025-02-10T18:28:10+00:00 ─────────────────────────────────────── using keys found in /config/keys Waiting for DB to be available Illuminate\Database\QueryException SQLSTATE[HY000] [1045] Access denied for user &#39;database_username&#39;@&#39;bookstack.bookstack_default&#39; (using password: YES) (Connection: mysql, SQL: select table_name as `name`, (data_length + index_length) as `size`, table_comment as `comment`, engine as `engine`, table_collation as `collation` from information_schema.tables where table_schema = &

## Web Based Replacement for MS Access Lookup Wizard Capability
 - [https://www.reddit.com/r/selfhosted/comments/1iqfrv0/web_based_replacement_for_ms_access_lookup_wizard](https://www.reddit.com/r/selfhosted/comments/1iqfrv0/web_based_replacement_for_ms_access_lookup_wizard)
 - RSS feed: $source
 - date published: 2025-02-16T00:26:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>For a (long) while now, I&#39;ve been looking for something that, via a web UI (or app that&#39;s available for Windows, Mac, Android, IOS) will emulate the functionality of Microsoft Access&#39; lookup field. This lookup functionality, as you may be aware, allows the population of a field from a dependent table (that whole foreign key thing). The beauty of it is that you can set it up to make the key field invisible and, when entering the value for this dependent field, you can just start typing the corresponding readable value for that field. Access will show a drop down box of available values depending on what&#39;s been typed so far. All throughout this process the actual key field is invisible. Once you&#39;ve narrowed it down to one value and tab out of that field, it is the key field value that gets written as the actual field value.</p> <p>This basic functionality allows for the population of Access table without defining anyth

## Any free Vps recomendation?
 - [https://www.reddit.com/r/selfhosted/comments/1iqfou2/any_free_vps_recomendation](https://www.reddit.com/r/selfhosted/comments/1iqfou2/any_free_vps_recomendation)
 - RSS feed: $source
 - date published: 2025-02-16T00:22:28+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m searching for a free vps service that has 60gb of storage or more for hosting a gameserver and a backend </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lubieyyyyyy"> /u/lubieyyyyyy </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqfou2/any_free_vps_recomendation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iqfou2/any_free_vps_recomendation/">[comments]</a></span>

## How to set up automated plex server with Debrid service
 - [https://www.reddit.com/r/selfhosted/comments/1iqfn0o/how_to_set_up_automated_plex_server_with_debrid](https://www.reddit.com/r/selfhosted/comments/1iqfn0o/how_to_set_up_automated_plex_server_with_debrid)
 - RSS feed: $source
 - date published: 2025-02-16T00:20:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone.</p> <p>I&#39;ve been scratching my head for the past few days trying to find some sort of answer to this question online, but I can&#39;t seem to find what I&#39;m looking for. It&#39;s probably just a lack of knowledge but I figured I&#39;d ask her and see if anyone had any ideas.</p> <p>Basically, I have a plex home server running on a spare Linux machine I build out of old parts, and right now it&#39;s pretty much all manual. I find a movie I want, I send the link to realdebrid, then remote into the ubuntu desktop and download the file into the appropriate directory for plex to pick it up.</p> <p>My question is if there is some way to automate this process? Like maybe instead of RDP I could ssh into the machine and run a script to download what I want from realdebrid and automatically place the file in the appropriate drive, or some sort of app that handles all of that from my main desktop.</p> <p>I&#39;ve looked into the arr apps a l

