# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Need advice regarding a private cloud solution I have created
 - [https://www.reddit.com/r/selfhosted/comments/1j4hlqh/need_advice_regarding_a_private_cloud_solution_i](https://www.reddit.com/r/selfhosted/comments/1j4hlqh/need_advice_regarding_a_private_cloud_solution_i)
 - RSS feed: $source
 - date published: 2025-03-05T23:34:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I’m seeking some advice regarding a private cloud solution I’ve created. It runs on users&#39; personal hardware (Android phones and computers), but I’m wondering how to address concerns from non-technical users who might be wary of using a solution that accesses their data between devices—especially coming from a solo indie developer (me).</p> <p>Since many people won’t be able to use tools like WireShark to monitor data access, how can I help ease their concerns and build trust in my solution? What steps can I take to reassure them about privacy and security?</p> <p>Any insights or advice would be greatly appreciated.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OffByNull"> /u/OffByNull </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4hlqh/need_advice_regarding_a_private_cloud_solution_i/">[link]</a></span> &#32; <span><a href="https:

## Just starting my Tailscale roll out but wait, should I do Headscale instead?
 - [https://www.reddit.com/r/selfhosted/comments/1j4hd15/just_starting_my_tailscale_roll_out_but_wait](https://www.reddit.com/r/selfhosted/comments/1j4hd15/just_starting_my_tailscale_roll_out_but_wait)
 - RSS feed: $source
 - date published: 2025-03-05T23:24:24+00:00

<!-- SC_OFF --><div class="md"><p>Have two proxmox servers running with a dozen apps between them. One is only VMs running single dockerized apps, and the other is one single VM with only dockerized apps inside. Starting to add tailscale to some - like audiobookshelf and calibre-web, so I can access them when away from home. (I am truly floored at how easy this was and how well it worked).</p> <p>I&#39;m still very new to self-hosting, Linux, and running all these &quot;servers,&quot; but before I go too deep into this, should I just set everything up using Headscale instead? The two proxmox servers run 24/7, so they are ideal for this. Someone posted a very detailed write-up about a year ago in this sub on how to set up Headscale, which seems doable, even for a newbie like me.</p> <p>A second question is on server load. When streaming an audiobook, the proxmox server load barely moves. I thought it would take a bigger hit, but it did not. Is that because it is simply streaming a fil

## Found this interesting - Hetzner - The Making of a Data Center #timelapse
 - [https://www.reddit.com/r/selfhosted/comments/1j4gkem/found_this_interesting_hetzner_the_making_of_a](https://www.reddit.com/r/selfhosted/comments/1j4gkem/found_this_interesting_hetzner_the_making_of_a)
 - RSS feed: $source
 - date published: 2025-03-05T22:50:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j4gkem/found_this_interesting_hetzner_the_making_of_a/"> <img src="https://external-preview.redd.it/VWBuXVO7UZJK8UTZkrQSb7wdxmIqp7J_Egk6F9sh4uc.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=0379e1d54946041c5c557f3a355223ffb1ac8bcd" alt="Found this interesting - Hetzner - The Making of a Data Center #timelapse" title="Found this interesting - Hetzner - The Making of a Data Center #timelapse" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anturk"> /u/anturk </a> <br/> <span><a href="https://youtu.be/bzs2Gisptm0">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4gkem/found_this_interesting_hetzner_the_making_of_a/">[comments]</a></span> </td></tr></table>

## How I set up Immich and got rid of Google Photos & iCloud
 - [https://www.reddit.com/r/selfhosted/comments/1j4gigq/how_i_set_up_immich_and_got_rid_of_google_photos](https://www.reddit.com/r/selfhosted/comments/1j4gigq/how_i_set_up_immich_and_got_rid_of_google_photos)
 - RSS feed: $source
 - date published: 2025-03-05T22:48:22+00:00

<!-- SC_OFF --><div class="md"><p>With my ever-growing videos and photos, I really got fed up with cloud storages like <strong>Google Photos</strong> or <strong>iCloud</strong>. Also, didn&#39;t want my naked pictures to be leaked from iCloud 😆, so I switched to self hosting the <strong>Immich</strong> .</p> <p>Here is my setup:</p> <h1>🖥 Server: Beelink Mini PC N100</h1> <p>Initially, I tested everything on a Raspberry Pi 4, which worked fine, but since I needed to host other services, I opted for a more powerful machine. If you&#39;re running only Immich, a Raspberry Pi 4 ($60) should be sufficient.</p> <h1>⚙️ OS: Proxmox</h1> <p>Everything runs on Proxmox. I set up an Ubuntu Server VM with Docker to host Immich and other small services. I also enabled <strong>iGPU passthrough</strong> to improve video encoding and machine learning (ML) tasks.</p> <p>For the initial bulk upload, I used my MacBook instead of running ML on the server, but I enabled it afterward.</p> <h1>💾 Storage: 2T

## Frigate HW Acceleration causing high GPU Idle?
 - [https://www.reddit.com/r/selfhosted/comments/1j4ghue/frigate_hw_acceleration_causing_high_gpu_idle](https://www.reddit.com/r/selfhosted/comments/1j4ghue/frigate_hw_acceleration_causing_high_gpu_idle)
 - RSS feed: $source
 - date published: 2025-03-05T22:47:38+00:00

<!-- SC_OFF --><div class="md"><p>I followed <a href="https://docs.frigate.video/configuration/hardware_acceleration/#nvidia-gpus">official doc to get HW acc on my Turing GPU</a> , it has H264 and H265 support</p> <p>Currently only 4x 4k camera feed, and I find idle draw of GPU along went from 10W to 40W. Then a closer look at the Frigate Docs nvidia-smi, their example is drawing 36W with a few FFmpeg process.</p> <p>This kind of wattage is as much as the whole system of a mini PC running a few VMs.</p> <p>I did came across a similar post here before but can&#39;t find it now. Vaguely OP did find a solution, can&#39;t remember it was config tweak or going to iGPU,</p> <p>How are you guys handling it? Disable HW Acc? Leave as is? Or mini PC iGPU?</p> <p>Or is there something like Coral that&#39;s dedicated and only draws a few watt?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Rxunique"> /u/Rxunique </a> <br/> <span><a href="https://www.reddit

## Pangolin + Plex + Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1j4g7ab/pangolin_plex_jellyfin](https://www.reddit.com/r/selfhosted/comments/1j4g7ab/pangolin_plex_jellyfin)
 - RSS feed: $source
 - date published: 2025-03-05T22:35:46+00:00

<!-- SC_OFF --><div class="md"><p>With pangolin now going into production I&#39;m giving it another go. I&#39;ve currently got a free tier VPS from Oracle which has 10 TB per month of network traffic as well as symmetrical gigabit speed. Everything seems to be working just fine. The VPS is that they recommend on their own site. All have either slower speeds and lower data caps.</p> <p>Now all of my self-hosted services with the exception of jellyfin and Plex wouldn&#39;t even come close to 10 TB a month. </p> <p>With Plex, from what I understand since I&#39;m using my own domain name but I&#39;m also port forwarding Port 32400. The fqdn is only used to establish the initial connection and then a direct connection is established over Port 32400. Is that correct? Or is all of this being sent over the pangolin network thus eating into that 10 tbs of data? </p> <p>With jellyfin considering I&#39;m not port forwarding any ports, I&#39;m just going to go ahead and assume that it&#39;s all 

## Just finished migrating my media stack to Linux - now to find a good dashboard???
 - [https://www.reddit.com/r/selfhosted/comments/1j4fq0p/just_finished_migrating_my_media_stack_to_linux](https://www.reddit.com/r/selfhosted/comments/1j4fq0p/just_finished_migrating_my_media_stack_to_linux)
 - RSS feed: $source
 - date published: 2025-03-05T22:16:17+00:00

<!-- SC_OFF --><div class="md"><p>Been running Plex and a stack of Arr apps for several years on a Win10 machine. With it&#39;s coming exit of support, I wanted to move to a new machine. So for the past while I&#39;ve been working on migrating everything to a new machine. Eventually settled on Linux Mint 22.1 for the OS, and all the apps run in containers under docker. </p> <p>Now I need some sort of dashboard or status screen that will bring all the info together from the various apps and put it in one place. Currently I have Radarr, Sonarr, Prowlarr, SABnzbd, and qBittorrent. I will probably add a few more down the road. I&#39;ve looked at a number of YT videos discussing things like dashy, homarr, and homepage were the ones I saw most often. </p> <p>I would appreciate your recommendations! Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lone_Wolf"> /u/Lone_Wolf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4

## For those of you that (in some way) expose your servers to the wider internet (be it through a reverse proxy like Nginx Proxy Manager, or just a VPN), what do you think about adding captchas to lower the risk of bots trying to access your services? I've linked a FOSS captcha framework for reference!
 - [https://www.reddit.com/r/selfhosted/comments/1j4flor/for_those_of_you_that_in_some_way_expose_your](https://www.reddit.com/r/selfhosted/comments/1j4flor/for_those_of_you_that_in_some_way_expose_your)
 - RSS feed: $source
 - date published: 2025-03-05T22:11:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j4flor/for_those_of_you_that_in_some_way_expose_your/"> <img src="https://external-preview.redd.it/ZKSh2yFbh_GjK_Xg-XZx7J30iIhBWujq1yAqtvj2rtg.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=99c496a3b06889f33ec1206f3c520e398cc700a1" alt="For those of you that (in some way) expose your servers to the wider internet (be it through a reverse proxy like Nginx Proxy Manager, or just a VPN), what do you think about adding captchas to lower the risk of bots trying to access your services? I've linked a FOSS captcha framework for reference!" title="For those of you that (in some way) expose your servers to the wider internet (be it through a reverse proxy like Nginx Proxy Manager, or just a VPN), what do you think about adding captchas to lower the risk of bots trying to access your services? I've linked a FOSS captcha framework for reference!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/u

## Looking for feedback on my project: open source, developer-first Typeform alternative
 - [https://www.reddit.com/r/selfhosted/comments/1j4elyx/looking_for_feedback_on_my_project_open_source](https://www.reddit.com/r/selfhosted/comments/1j4elyx/looking_for_feedback_on_my_project_open_source)
 - RSS feed: $source
 - date published: 2025-03-05T21:31:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I&#39;m building <a href="http://Forms.md">Forms.md</a>, which is an open source, developer-first Typeform alternative. Basically, it&#39;s a JS library that lets you build multi-step forms and surveys with very little code. The forms themselves are exactly like Typeform&#39;s. Right now, it does not have a backend, but you can obviously just POST the data directly in your database or wherever else.</p> <p>The big advantage (in my head at least) is that it integrates natively into your codebase. The forms themselves live inside your product, so no iframes, no monthly response cap, etc. You have full control of everything.</p> <p>I&#39;m looking for some genuine feedback on this? Can I potentially grow this into a company? Do you think what I have is useful already? Some obvious ideas are building out a backend and integrations, etc. I&#39;m also more than happy to help anyone with integration and support if you decide to use the libra

## My beloved HP Microserver Gen 8 has died. 10 or 11 years after I bought it.
 - [https://www.reddit.com/r/selfhosted/comments/1j4elg2/my_beloved_hp_microserver_gen_8_has_died_10_or_11](https://www.reddit.com/r/selfhosted/comments/1j4elg2/my_beloved_hp_microserver_gen_8_has_died_10_or_11)
 - RSS feed: $source
 - date published: 2025-03-05T21:30:56+00:00

<!-- SC_OFF --><div class="md"><p>I run TrueNAS on it. Disks started chucking errors. I replaced them with new, shiny 6TB WD NAS Reds. </p> <p>Now they too chucking chksum errors. So..... Assuming it&#39;s the SATA controller which is duff. </p> <p>I don&#39;t run anything else on it, I have another cluster for that so it&#39;s just storage. </p> <p>My question:<br/> 1. Do I get another HP (newer one) or<br/> 2. Do I get a standard NAS like &lt;your brand here&gt; </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrappyTan69"> /u/CrappyTan69 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4elg2/my_beloved_hp_microserver_gen_8_has_died_10_or_11/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4elg2/my_beloved_hp_microserver_gen_8_has_died_10_or_11/">[comments]</a></span>

## TrailBase 0.7: Open, sub-millisecond, single-executable FireBase alternative built with Rust, SQLite & V8 🚀
 - [https://www.reddit.com/r/selfhosted/comments/1j4eg9n/trailbase_07_open_submillisecond_singleexecutable](https://www.reddit.com/r/selfhosted/comments/1j4eg9n/trailbase_07_open_submillisecond_singleexecutable)
 - RSS feed: $source
 - date published: 2025-03-05T21:25:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j4eg9n/trailbase_07_open_submillisecond_singleexecutable/"> <img src="https://external-preview.redd.it/jV6_gtHi03qNnIqF-2v39naAXZDe3cY0XuuLQlX7x5U.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=7c50209fb1c4ac2e4d81212c7e13610ce6a0bd42" alt="TrailBase 0.7: Open, sub-millisecond, single-executable FireBase alternative built with Rust, SQLite &amp; V8 🚀" title="TrailBase 0.7: Open, sub-millisecond, single-executable FireBase alternative built with Rust, SQLite &amp; V8 🚀" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/zl395n0xtxme1.png?width=1665&amp;format=png&amp;auto=webp&amp;s=ffee373bae37415ac59e921fb7e3a2e49613ad9f">Admin UI: Table Browser &amp; Logs</a></p> <p><a href="https://github.com/trailbaseio/trailbase">TrailBase</a> is an easy to self-host, sub-millisecond, single-executable FireBase alternative. It provides type-safe REST and realtime APIs, a built-in JS/ES6/TS

## mDash with Docker
 - [https://www.reddit.com/r/selfhosted/comments/1j4ec8f/mdash_with_docker](https://www.reddit.com/r/selfhosted/comments/1j4ec8f/mdash_with_docker)
 - RSS feed: $source
 - date published: 2025-03-05T21:20:53+00:00

<!-- SC_OFF --><div class="md"><p>Multiple people asked for an install with Docker, so here it is!</p> <p><a href="https://github.com/beans-are-gross/mdash">https://github.com/beans-are-gross/mdash</a></p> <p>If you have any questions, please let me know! The original post is below:</p> <p><a href="https://www.reddit.com/r/selfhosted/comments/1j1cxdx/mdash/">https://www.reddit.com/r/selfhosted/comments/1j1cxdx/mdash/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lowercase-raging"> /u/lowercase-raging </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4ec8f/mdash_with_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4ec8f/mdash_with_docker/">[comments]</a></span>

## How to secure server with npm
 - [https://www.reddit.com/r/selfhosted/comments/1j4e66x/how_to_secure_server_with_npm](https://www.reddit.com/r/selfhosted/comments/1j4e66x/how_to_secure_server_with_npm)
 - RSS feed: $source
 - date published: 2025-03-05T21:14:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone! I am pretty new in self host. I have a computer with Ubuntu and I would like to expose Jellyfin, nextcloud and home assistant to share with family and friend. For the moment I use NPM (really easy to setup) but I am afraid that this is not secure at all. Do you have any (easy) guide or recommendations to secure my server ? Thanks a lots Cheers!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/althife"> /u/althife </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4e66x/how_to_secure_server_with_npm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4e66x/how_to_secure_server_with_npm/">[comments]</a></span>

## Questions regarding network safety on my server
 - [https://www.reddit.com/r/selfhosted/comments/1j4e181/questions_regarding_network_safety_on_my_server](https://www.reddit.com/r/selfhosted/comments/1j4e181/questions_regarding_network_safety_on_my_server)
 - RSS feed: $source
 - date published: 2025-03-05T21:08:34+00:00

<!-- SC_OFF --><div class="md"><p>Alright, long time lurker and been building my server for a few months now and I have some security questions I need help with. </p> <p>I recently moved my server from local only to the outside network. Currently running the following:</p> <p><strong>Setup</strong></p> <ul> <li>Currently only media server, soon to integrate family stuff (photos, videos, documents etc.)</li> <li>Router with OpenWRT.</li> </ul> <p><strong>Jellyfin/Jellyseerr</strong></p> <ul> <li>Exposed to my family member through my domain + cloudflare tunnel. I have limited the access to IPs from my country only. </li> <li>Admin account on Jellyfin is hidden, rest are visible for them to log in.</li> <li>Jellyfin and Jellyseerr are the only ones exposed this way through my domain.</li> </ul> <p><strong>Reaching server from outside</strong></p> <ul> <li>Currently have Tailscale installed on server and my phone. No ports open on my router. I have set up a ACL where my Tailscale IP on 

## manually blocking ip ranges in sshguard
 - [https://www.reddit.com/r/selfhosted/comments/1j4e0b7/manually_blocking_ip_ranges_in_sshguard](https://www.reddit.com/r/selfhosted/comments/1j4e0b7/manually_blocking_ip_ranges_in_sshguard)
 - RSS feed: $source
 - date published: 2025-03-05T21:07:37+00:00

<!-- SC_OFF --><div class="md"><p>Is there a possibility to manually block ip ranges in sshguard?</p> <p>Blocked IPs are added to blacklist.db but only one by one. And I&#39;d really like to add a whole /24 net to it. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_anno_"> /u/_anno_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4e0b7/manually_blocking_ip_ranges_in_sshguard/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4e0b7/manually_blocking_ip_ranges_in_sshguard/">[comments]</a></span>

## Ente vs PhotoPrism
 - [https://www.reddit.com/r/selfhosted/comments/1j4dytn/ente_vs_photoprism](https://www.reddit.com/r/selfhosted/comments/1j4dytn/ente_vs_photoprism)
 - RSS feed: $source
 - date published: 2025-03-05T21:05:52+00:00

<!-- SC_OFF --><div class="md"><p>Ive been running Photo Prism self hosted for a year on my rancher k8s stack. I would love to find an alternative where I can push originals (photos) to secure s3 buckets (s3/complaint) and keep high res thumbs for app browsing locally. OOB photo prism does not have cloud awareness. What about Ente?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Shadowbq_"> /u/Shadowbq_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4dytn/ente_vs_photoprism/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4dytn/ente_vs_photoprism/">[comments]</a></span>

## Double reverse proxy setup -- more secure?
 - [https://www.reddit.com/r/selfhosted/comments/1j4cggf/double_reverse_proxy_setup_more_secure](https://www.reddit.com/r/selfhosted/comments/1j4cggf/double_reverse_proxy_setup_more_secure)
 - RSS feed: $source
 - date published: 2025-03-05T20:04:45+00:00

<!-- SC_OFF --><div class="md"><p>Thinking through security here and wanted communities thoughts:</p> <p>Lets say I have two VMs in home network: </p> <ul> <li>a &quot;DMZ&quot; subnet, with 80/443 open to the world, that can&#39;t speak to anything else in network</li> <li>a &quot;LAB&quot; subnet with my critical services/data</li> </ul> <p>Lets say I wanted to run n8n.io, Bitwarden, Immich and minimize surface area for probing.</p> <ul> <li>n8n has a <code>subdomain.example.com/webhooks/</code> endpoint that (ideally) I can expose to the world for automation</li> <li>Immich has a <code>subdomain.example.com/share/</code> endpoint that (ideally) I can expose to selectively share stuff with people <ul> <li>Bitwarden structures Send links as <code>subdomain.example.com/#/send/</code>, also (ideally) I can expose to share with people.</li> </ul></li> </ul> <p>I just realized a potential way to expose these specific URL endpoints, without hosting the full service on the exposed DMZ, wo

## Help With New Proxy/VM Design
 - [https://www.reddit.com/r/selfhosted/comments/1j4cbeh/help_with_new_proxyvm_design](https://www.reddit.com/r/selfhosted/comments/1j4cbeh/help_with_new_proxyvm_design)
 - RSS feed: $source
 - date published: 2025-03-05T19:59:24+00:00

<!-- SC_OFF --><div class="md"><p>I am currently running ~65 containers on a DS718+. It&#39;s started struggling so I bought a new NUC and put Proxmox on it.</p> <p>My plan was to run 3 VMs each with standalone docker on separate VLANs. One is for home things (home assistant, immich), one for media things (*arr, etc) and one for external services (just calibre-web and overseerr). I also have a DS920+ running plex.</p> <p>My issue is that I am not sure how to handle the reverse proxy setup. I stupidly thought I could just put separate Traefik instances on the DS920 and 3 VMs, but that is not supported. As everything is on one host now, traefik currently provides certs for all of the containers from my domain with cloudflare and handles plex through an external entry in the config. I&#39;d like to keep having all services use certs from my domain, so this is where I&#39;m stuck.</p> <p>I like the idea of the 3 standalone docker VMs as it seems more secure as they are all firewalled on 

## Jellyfin GPU recommendations for a newbie
 - [https://www.reddit.com/r/selfhosted/comments/1j4bzc0/jellyfin_gpu_recommendations_for_a_newbie](https://www.reddit.com/r/selfhosted/comments/1j4bzc0/jellyfin_gpu_recommendations_for_a_newbie)
 - RSS feed: $source
 - date published: 2025-03-05T19:45:46+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys!</p> <p>I started to set up my Jellyfin server on a Windows machine a few days ago, and I&#39;ve been enjoying it, but I&#39;m a complete newbie on this field. I use an old i7-3770 and a GT 1030, and if I recall correctly the 1030 can&#39;t do any transcoding. When I access my server from my phone on cellular network and start a playback, my CPU usage skyrockets to 100% immediately, so I&#39;m thinking getting a &quot;new&quot; dedicated GPU. I wouldn&#39;t have more than 3-4 concurrent streams (at 1080p), mostly HEVC and H264.</p> <p>I&#39;m looking at buying a used GTX 1050Ti 4Gb (no power cable, 40-55$ in my country) or a GTX 1060 6Gb (65-90$), but I&#39;m not sure if the price difference worth the extra 2 Gbs of VRAM. Is the 1050Ti more than enough for me, or the stronger the better? If I want to have two 4k streams concurrently in the future, are these cards sufficient? Or alternatively, should I wait and hunt for a good deal on a P10

## Cloudflared cannot access devices on the LAN
 - [https://www.reddit.com/r/selfhosted/comments/1j4bfp1/cloudflared_cannot_access_devices_on_the_lan](https://www.reddit.com/r/selfhosted/comments/1j4bfp1/cloudflared_cannot_access_devices_on_the_lan)
 - RSS feed: $source
 - date published: 2025-03-05T19:23:46+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I have cloudflared installed in a Docker Container on my OMV NAS and while it works connecting to the various other Containers, I cannot get access to devices on the host subnet. Mainly due to the default network mode being bridge.</p> <p>What do I need to do so cloudflared can access both containers and devices on the host subnet?</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheDeathPit"> /u/TheDeathPit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4bfp1/cloudflared_cannot_access_devices_on_the_lan/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4bfp1/cloudflared_cannot_access_devices_on_the_lan/">[comments]</a></span>

## Self-hosted open source project management tools?
 - [https://www.reddit.com/r/selfhosted/comments/1j49yg4/selfhosted_open_source_project_management_tools](https://www.reddit.com/r/selfhosted/comments/1j49yg4/selfhosted_open_source_project_management_tools)
 - RSS feed: $source
 - date published: 2025-03-05T18:25:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone.</p> <p>Wasn&#39;t sure how to flair this.</p> <p>I&#39;m looking for a general project management tool that:</p> <ul> <li>Has a semi-minimalist, low friction interface</li> <li>Can track task dependencies easily</li> <li>Is open source</li> <li>Is self-hostable</li> <li>Is not specifically geared towards software dev or agile (or not so much that it&#39;s challenging to use it for other things)</li> <li>Is actively maintained, supported, and semi-frequently updated</li> <li>Is not Kanban-focused (or has multiple views)</li> <li>Is not hard to manage/back up/restore on the backend</li> </ul> <p>Something like Todoist but with the ability to see task dependencies and visualize those dependencies on a timeline-type visualization would be literal perfection. Todoist does have Ganttify integration, but alas both are closed source and privately hosted.</p> <p>Vikunja is a good start but it needs a bit of work in entering tasks/subtasks and de

## I Just Launched RestoPOS – A Free, Open-Source Multi-Tenancy Restaurant POS System
 - [https://www.reddit.com/r/selfhosted/comments/1j49uoi/i_just_launched_restopos_a_free_opensource](https://www.reddit.com/r/selfhosted/comments/1j49uoi/i_just_launched_restopos_a_free_opensource)
 - RSS feed: $source
 - date published: 2025-03-05T18:21:02+00:00

<!-- SC_OFF --><div class="md"><h1>🚀 I Just Launched RestoPOS – A Free, Open-Source Multi-Tenancy Restaurant POS System (Laravel + Vue) 🍽️</h1> <p>Hey everyone,</p> <p>I’ve been working on <strong>RestoPOS</strong>, a <strong>SaaS-based restaurant billing and management system</strong>, and I just launched it as an <strong>open-source project</strong> on GitHub! 🎉</p> <p>🔗 <strong>GitHub Repo:</strong> <a href="https://github.com/faizaldevs/restopos">https://github.com/faizaldevs/restopos</a></p> <h1>What is RestoPOS?</h1> <p>RestoPOS is a <strong>multi-tenancy</strong> restaurant management system built with <strong>Laravel, Vue.js, and AdminLTE</strong>. It’s perfect for restaurants, cafés, and cloud kitchens that need a <strong>scalable</strong> and <strong>self-hosted</strong> POS solution.</p> <h1>🔥 Features</h1> <p>✅ Multi-Tenancy (Powered by <strong>Stancl Tenancy</strong>)<br/> ✅ <strong>Multiple Print Formats</strong> – Thermal print support, KOT printing<br/> ✅ <strong>Bill

## [Celeron N3550] Minimalist
 - [https://www.reddit.com/r/selfhosted/comments/1j49riv/celeron_n3550_minimalist](https://www.reddit.com/r/selfhosted/comments/1j49riv/celeron_n3550_minimalist)
 - RSS feed: $source
 - date published: 2025-03-05T18:17:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j49riv/celeron_n3550_minimalist/"> <img src="https://b.thumbs.redditmedia.com/lqT1jNVRrlTFXnOyxteKYl8Hl3pbjFIH4nAduKfC6Vk.jpg" alt="[Celeron N3550] Minimalist" title="[Celeron N3550] Minimalist" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>i just carved out the inside of this cheap laptop that i got and just bootstrap the whole thing using double-sided foam tape. </p> <p>it came with, Cpu : Intel Celeron N3550 Ram : 4gb emmc Storage : 64gb emmc + 500gb sata hdd using usb 3.0 enclosure OS : NixOS It&#39;s completely headless but since the board didn&#39;t have network port i just use the hdmi port to my monitor so i could setup the wifi. i know there are some usb hub that had the network port but i just kinda lazy and just stick with what i have.</p> <p>My use-case : - Samba - Cups - Sane - Jellyfin - Qbittorrent</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Casppy">

## home automation setup?
 - [https://www.reddit.com/r/selfhosted/comments/1j49l2l/home_automation_setup](https://www.reddit.com/r/selfhosted/comments/1j49l2l/home_automation_setup)
 - RSS feed: $source
 - date published: 2025-03-05T18:10:17+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j49l2l/home_automation_setup/"> <img src="https://b.thumbs.redditmedia.com/K8A7-TPDVnjdqOrpunvBFNsLC946zDXPm0rqn1OGzKg.jpg" alt="home automation setup?" title="home automation setup?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>i know nothing about home automation but my brother asked for help setting up his home and i said i&#39;d take care of it. </p> <p>basically what he wanted to do is remotely turn off the lights (for the whole house) when he&#39;s not at home and close all the shutters at once (also programming this so that they open up in the morning would be nice)</p> <p>i have seen many people use home assistant for this and that&#39;s what i was planning to use too but i don&#39;t wanna use smart bulbs or relays (and possibly i don&#39;t wanna rely on wifi at all)</p> <p>i don&#39;t need to control lights individually, not even for each room, just to turn them off (and maybe check if they are on

## CI app deployment
 - [https://www.reddit.com/r/selfhosted/comments/1j497q3/ci_app_deployment](https://www.reddit.com/r/selfhosted/comments/1j497q3/ci_app_deployment)
 - RSS feed: $source
 - date published: 2025-03-05T17:56:04+00:00

<!-- SC_OFF --><div class="md"><p>Hey, so I&#39;m looking to find a tool that will let me automate app deployments for a test environment.</p> <p>Essentially I have a CI that builds a docker image. I want to deploy this image with a domain name from a CI pipeline. It&#39;s important I can deploy this via CI.</p> <p>Zero downtime deployments aren&#39;t 100% necessary but would be nice. </p> <p>Maybe I&#39;m over complicating and could set this up with some scripts. But any recommendations would be great. Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Munch1498"> /u/Munch1498 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j497q3/ci_app_deployment/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j497q3/ci_app_deployment/">[comments]</a></span>

## Intermittant HTTPS certificate errors on random websites since using Adguard Home
 - [https://www.reddit.com/r/selfhosted/comments/1j492xs/intermittant_https_certificate_errors_on_random](https://www.reddit.com/r/selfhosted/comments/1j492xs/intermittant_https_certificate_errors_on_random)
 - RSS feed: $source
 - date published: 2025-03-05T17:50:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j492xs/intermittant_https_certificate_errors_on_random/"> <img src="https://b.thumbs.redditmedia.com/i5zB3xopsOtG1q2itfNs7-4_bfwbV8vEb69DRAcBm8Y.jpg" alt="Intermittant HTTPS certificate errors on random websites since using Adguard Home" title="Intermittant HTTPS certificate errors on random websites since using Adguard Home" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This is an odd one, where I&#39;m not really sure how to get started investigating this. Since setting up Adguard Home on my local network, I&#39;ve been intermittently getting HTTPs certificate errors from Firefox and both my PC (windows) and laptop (macOS).</p> <p>It&#39;s just happened to me now trying to load job-boards.greenhouse.io, I was returned an HTTPS certificate issued for *.rvshare.com. </p> <p><a href="https://preview.redd.it/axgb9ufrqwme1.png?width=1182&amp;format=png&amp;auto=webp&amp;s=705db6c5eaf74f3b39398620c0ac3e87165a07

## Slow speeds while using VPN? Jellyfin
 - [https://www.reddit.com/r/selfhosted/comments/1j48wxd/slow_speeds_while_using_vpn_jellyfin](https://www.reddit.com/r/selfhosted/comments/1j48wxd/slow_speeds_while_using_vpn_jellyfin)
 - RSS feed: $source
 - date published: 2025-03-05T17:44:07+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I recently have been learning / getting into setting up a NAS (Synology with hardware capable of transcoding). After doing a lot of reading I figured the best and most secure way for me to access the server outside of my home was with using a VPN. I was able to get Wireguard setup using WG_easy. </p> <p>My home internet speed is about 300mbps upload. When connected via Wireguard on a client device I’m getting like 170-180mbps download (via speed test) which should be fast enough. However, I have noticed a problem with streaming high bit rate media (4k, 40 MBPS or higher). It seems like my connection isn’t fast enough and it keeps buffering. I’m not sure why this is happening.</p> <p>To troubleshoot, I set up plex with port forwarding, and when my VPN is off I have no issues with playing media in original quality using the same internet connection. When I turn on the VPN I get the error on plex “your connection to the server is no

## docker alternatives for windows?
 - [https://www.reddit.com/r/selfhosted/comments/1j48f7m/docker_alternatives_for_windows](https://www.reddit.com/r/selfhosted/comments/1j48f7m/docker_alternatives_for_windows)
 - RSS feed: $source
 - date published: 2025-03-05T17:24:34+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>I wanted to use docker in my self hosted system which is windows but when i went to setting i was not able to find a way to mount a hard drive to docker. so i wonder if there is a docker alternatives that works well in windows with GUI and allow hard drive mount? </p> <p>Thanks </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheLastAirbender2025"> /u/TheLastAirbender2025 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j48f7m/docker_alternatives_for_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j48f7m/docker_alternatives_for_windows/">[comments]</a></span>

## Dollar Dollar Bill Y'all v3.0 : With Muti currency support now and more !
 - [https://www.reddit.com/r/selfhosted/comments/1j4847m/dollar_dollar_bill_yall_v30_with_muti_currency](https://www.reddit.com/r/selfhosted/comments/1j4847m/dollar_dollar_bill_yall_v30_with_muti_currency)
 - RSS feed: $source
 - date published: 2025-03-05T17:12:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j4847m/dollar_dollar_bill_yall_v30_with_muti_currency/"> <img src="https://external-preview.redd.it/HrRPHa-VE083IpomXWHJXdfYCPEcQARiT1u8U4Hmx00.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=304fa495265584acd241885b2eaf68347dc60ecb" alt="Dollar Dollar Bill Y'all v3.0 : With Muti currency support now and more !" title="Dollar Dollar Bill Y'all v3.0 : With Muti currency support now and more !" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I wanted to share the latest update to &quot;Dollar Dollar Bill Y&#39;all&quot; that I&#39;ve been developing over the past few months. Version 3.0 just dropped with some significant improvements that make tracking shared expenses with roommates, friends, or partners much easier.</p> <h1>What&#39;s New in v3.0</h1> <h1>💱 Multi-Currency Support</h1> <ul> <li>Added support for 30+ currencies with automatic conversion</li> <li>Real-time exchange rates pulled from a free API</

## odd Swiftfin stuttering when watching movies
 - [https://www.reddit.com/r/selfhosted/comments/1j47hrv/odd_swiftfin_stuttering_when_watching_movies](https://www.reddit.com/r/selfhosted/comments/1j47hrv/odd_swiftfin_stuttering_when_watching_movies)
 - RSS feed: $source
 - date published: 2025-03-05T16:47:01+00:00

<!-- SC_OFF --><div class="md"><p>hey folks! very new to selfhosting in general so forgive me if i miss some stuff, but i&#39;ve noticed that, when watching movies specifically on swiftfin on my apple tv (older model), it is basically unwatchably laggy. i get about 1 frame every 2 seconds lol</p> <p>i don&#39;t notice this when watching tv shows (yet, at least), but it does happen pretty consistently with movies. i haven&#39;t altered any settings in jellyfin and i have tried messing with settings in SF, but to no avail. is there any particular setting in jellyfin or swiftfin that i should modify? FWIW, it plays perfectly on infuse, but want to get swiftfin to work if possible</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YeetMcManus"> /u/YeetMcManus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j47hrv/odd_swiftfin_stuttering_when_watching_movies/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfho

## so what are the limits of Firebin.net?
 - [https://www.reddit.com/r/selfhosted/comments/1j46zaj/so_what_are_the_limits_of_firebinnet](https://www.reddit.com/r/selfhosted/comments/1j46zaj/so_what_are_the_limits_of_firebinnet)
 - RSS feed: $source
 - date published: 2025-03-05T16:25:47+00:00

<!-- SC_OFF --><div class="md"><p>I cant seem to find the limits anywhere such as maximum size allowed, frequency of uploads using the api, etc.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Seek4Seek"> /u/Seek4Seek </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j46zaj/so_what_are_the_limits_of_firebinnet/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j46zaj/so_what_are_the_limits_of_firebinnet/">[comments]</a></span>

## Looking for a self-hosted course management solution (CRM, enrollments, contracts, etc.)
 - [https://www.reddit.com/r/selfhosted/comments/1j46yri/looking_for_a_selfhosted_course_management](https://www.reddit.com/r/selfhosted/comments/1j46yri/looking_for_a_selfhosted_course_management)
 - RSS feed: $source
 - date published: 2025-03-05T16:25:11+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m looking for a <strong>self-hosted</strong> solution to manage my course business. My requirements include:</p> <ul> <li><strong>Course management</strong> (creating courses, schedules, pricing, etc.)</li> <li><strong>User enrollments</strong> (sign-ups, participant tracking, automated confirmations)</li> <li><strong>CRM features</strong> (keeping track of customers, communication history, follow-ups)</li> <li><strong>Contract management</strong> (digital signatures, agreements)</li> <li><strong>Payment handling</strong> (optional, but would be great)</li> </ul> <p>I’d prefer something <strong>FOSS</strong> (open-source) or at least a <strong>one-time license</strong> rather than SaaS. If necessary, I could set up multiple tools and integrate them.</p> <p>What tools do you recommend? Any personal experiences?</p> <p>Thanks in advance! 😊</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/

## Debian Setup helper script
 - [https://www.reddit.com/r/selfhosted/comments/1j45rnr/debian_setup_helper_script](https://www.reddit.com/r/selfhosted/comments/1j45rnr/debian_setup_helper_script)
 - RSS feed: $source
 - date published: 2025-03-05T15:34:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, while I&#39;m switching servers every year or so I created a quick setup bash script to save some minutes in the begninning. Here is the link: </p> <p><a href="https://github.com/Snake16547/debian-setup-script">https://github.com/Snake16547/debian-setup-script</a></p> <p>Feedback and thoughts are appreciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Snake16547"> /u/Snake16547 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j45rnr/debian_setup_helper_script/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j45rnr/debian_setup_helper_script/">[comments]</a></span>

## Kasm in docker compose using yml file
 - [https://www.reddit.com/r/selfhosted/comments/1j45j3w/kasm_in_docker_compose_using_yml_file](https://www.reddit.com/r/selfhosted/comments/1j45j3w/kasm_in_docker_compose_using_yml_file)
 - RSS feed: $source
 - date published: 2025-03-05T15:24:11+00:00

<!-- SC_OFF --><div class="md"><p>has anyone had any luck installing kasm in docker compose using a YML file? for the life of me I cannot figure it out... I dont really know what i am doing wrong. any guide that exist would be much appreciated. </p> <pre><code>YML: kasm_server: image: lscr.io/linuxserver/kasm:latest container_name: kasm privileged: true security_opt: - apparmor:rootlesskit #optional environment: - KASM_PORT=443 - DOCKER_HUB_USERNAME=USER #optional - DOCKER_HUB_PASSWORD=PASS #optional - DOCKER_MTU=1500 #optional volumes: - /home/ivan/public/kasm/kasm_data:/data - /home/ivan/public/kasm/profiles:/profiles - /dev/input:/dev/input #optional - /run/udev/data:/run/udev/data #optional ports: - 3000:3000 - 443:443 restart: unless-stopped networks: shared_network: ipv4_address: 172.18.1.21 log file: [migrations] started [migrations] no migrations found usermod: no changes ─────────────────────────────────────── ██╗ ███████╗██╗ ██████╗ ██║ ██╔════╝██║██╔═══██╗ ██║ ███████╗██║█

## Self-hosted RSS/ATOM reader with LLM-generated tags, scoring, filtering, and sorting
 - [https://www.reddit.com/r/selfhosted/comments/1j45f9x/selfhosted_rssatom_reader_with_llmgenerated_tags](https://www.reddit.com/r/selfhosted/comments/1j45f9x/selfhosted_rssatom_reader_with_llmgenerated_tags)
 - RSS feed: $source
 - date published: 2025-03-05T15:19:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>For a long time I&#39;m looking for a news reader that help me filter out the noise and read only the most interesting news. I&#39;ve not found any, so I created it myself.</p> <p>You can find the reader here: <a href="https://github.com/Tiendil/feeds.fun">https://github.com/Tiendil/feeds.fun</a></p> <p>It is open sourced, self-hosted, and can work without access to proprietary LLM APIs (you can replace the API entry point with your self-hosted OpenAI-compatible API or fully disable them).</p> <p>How it works:</p> <ul> <li>For each news entry, the reader automatically assigns a lot of tags.</li> <li>You can create rules like <code>books + sci-fi -&gt; +5 score</code>, <code>politics + new-york -&gt; -10 score</code>.</li> <li>News are sorted by score, so you always see the most interesting news first.</li> </ul> <p>Here are some links if you want to follow development:</p> <ul> <li><a href="https://www.reddit.com/r/feedsfun/">r/fe

## Looking for: self-hosted Budget finance app with bank connections (US)
 - [https://www.reddit.com/r/selfhosted/comments/1j44uq1/looking_for_selfhosted_budget_finance_app_with](https://www.reddit.com/r/selfhosted/comments/1j44uq1/looking_for_selfhosted_budget_finance_app_with)
 - RSS feed: $source
 - date published: 2025-03-05T14:54:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey! I’ve been using Actual Budget for a little while and really, it has been less than intuitive. I’m always facing syncing or logging issues between devices. Sometimes I’ll see some transactions on my mobile device sometimes not, same on desktop. It’s been a struggle.</p> <p>Do you all have any other recommendations for a finance budgeting self hosted app that is relatively simple, and can automatically import bank transactions? Firefly III doesn’t seem to have automatic bank import.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fit_Increase2967"> /u/Fit_Increase2967 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j44uq1/looking_for_selfhosted_budget_finance_app_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j44uq1/looking_for_selfhosted_budget_finance_app_with/">[comments]</a></span>

## URL to Service
 - [https://www.reddit.com/r/selfhosted/comments/1j44uiw/url_to_service](https://www.reddit.com/r/selfhosted/comments/1j44uiw/url_to_service)
 - RSS feed: $source
 - date published: 2025-03-05T14:53:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to the world of self hosting, and I&#39;m trying to set up a few game servers for my friends. What i eventually want to do is have things working like &lt;domain&gt;/minecraft and &lt;domain&gt;/valheim for connections instead of having to do domain:port. Is there a way to configure that with truenas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/zIronKlad"> /u/zIronKlad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j44uiw/url_to_service/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j44uiw/url_to_service/">[comments]</a></span>

## Unsure what self-hosted solution best fits my needs
 - [https://www.reddit.com/r/selfhosted/comments/1j446jf/unsure_what_selfhosted_solution_best_fits_my_needs](https://www.reddit.com/r/selfhosted/comments/1j446jf/unsure_what_selfhosted_solution_best_fits_my_needs)
 - RSS feed: $source
 - date published: 2025-03-05T14:22:42+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been interested in setting up a self-hosted solution for all my various hobby projects. This might<br/> include websites, games, backends and tiny databases. I also want to be able to self-host git repos.</p> <p>I need an inexpensive mix of performance and storage, but using it as a remote storage device is not my intention. I want to be able to configure multiple small linux vms with various distros in order to ssh in and program using various dependencies (ubuntu, arch, etc). Preferably I&#39;d like to setup a single block storage that I can mount on any of them in order to access the same data regardless of what VM I&#39;m using. I&#39;d also love being able to host lightweight servers, some for games like minecraft and some<br/> for my own networking applications.</p> <p>I&#39;m not sure how to go about setting up a solution for this. Is there a single solution that would be a good fit? Do I need to combine multiple providers? Would it b

## Audiobookshelf + CalibreWebAutomated together?
 - [https://www.reddit.com/r/selfhosted/comments/1j43uza/audiobookshelf_calibrewebautomated_together](https://www.reddit.com/r/selfhosted/comments/1j43uza/audiobookshelf_calibrewebautomated_together)
 - RSS feed: $source
 - date published: 2025-03-05T14:07:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m currently running audiobookshelf with a library bound to a folder &quot;Books&quot;. The directory structure is as follows -&gt; Books/{Author Name}/{Book Name}/(EPUB + Audio Files + Audiobookshelf metadata file).</p> <p>I want to run Calibre Web Automated bound to the same library. Can I do this without losing data and not having one interfere with the other?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/seriouslyfun95"> /u/seriouslyfun95 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j43uza/audiobookshelf_calibrewebautomated_together/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j43uza/audiobookshelf_calibrewebautomated_together/">[comments]</a></span>

## Why so many selfhosted app does not support path prefix reverse proxy?
 - [https://www.reddit.com/r/selfhosted/comments/1j43ql2/why_so_many_selfhosted_app_does_not_support_path](https://www.reddit.com/r/selfhosted/comments/1j43ql2/why_so_many_selfhosted_app_does_not_support_path)
 - RSS feed: $source
 - date published: 2025-03-05T14:01:50+00:00

<!-- SC_OFF --><div class="md"><p>I just gotten started on the selfhost treadmill and I found many apps I want to run but does not support path prefix reverse proxy. This seems to me to be the easiest way to go about self hosting and clearly I&#39;m wrong here since it&#39;s pretty low on the support list.</p> <p>Advantage of path prefix: </p> <ul> <li>Ease of access: I can go to <code>192.168.1.2:3456/my-service</code> at home, or <code>my.dynamic.dns/my-service</code> when I&#39;m not at home.</li> <li>Home page linking: I have a list of bookmarks at the root path, the link href just need to say <code>my-service</code> and it&#39;s usable in both scenarios. As far as I know this is not possible for subdomain links.</li> <li>Only 1 cert is needed for <code>my.dynamic.dns</code>.</li> <li>No need to set up a private dns server. With subdomain linking I need <code>my-service.my.dynamic.dns</code> to resolve to a different IP, so either that needs to be on the public DNS or I need to r

## Strange Networking Issues.. What's the permanent fix?
 - [https://www.reddit.com/r/selfhosted/comments/1j43gss/strange_networking_issues_whats_the_permanent_fix](https://www.reddit.com/r/selfhosted/comments/1j43gss/strange_networking_issues_whats_the_permanent_fix)
 - RSS feed: $source
 - date published: 2025-03-05T13:48:55+00:00

<!-- SC_OFF --><div class="md"><p>I will admit before summarizing this issue that networking is my biggest weakness with self-hosting.<br/> Here&#39;s the summary:<br/> I have 2 ProxMox nodes (PCs) connected to an unmanaged switch which runs to my ISPs all-in-one fibre box. The ISP box does the DHCP, DNS, WIFI, everything. All traffic from both nodes runs to the 10gig port on the back of this box.</p> <p>A while back now I started having this issue where some of my LXC&#39;s (which all have their own MAC and IP) would lose internet for roughly 5-10 minutes. They can still ping each other, and some of them still have connection it would only be 1 or 2 failing to resolve at a time while everything else using the same wirepath continues to work.</p> <p>I noticed if I reboot the nodes, the first LXCs to get a connection are the ones that are up first. Once it gets to the 10th(ish) one, they take longer to connect to the internet. Kinda seems like theres maybe a limit to how many IP addre

## PdfDing - Version 1 released and major UI revamp
 - [https://www.reddit.com/r/selfhosted/comments/1j43233/pdfding_version_1_released_and_major_ui_revamp](https://www.reddit.com/r/selfhosted/comments/1j43233/pdfding_version_1_released_and_major_ui_revamp)
 - RSS feed: $source
 - date published: 2025-03-05T13:28:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>PdfDing is a selfhosted PDF manager, viewer and editor offering a seamless user experience on multiple devices. You can find the repo <a href="https://github.com/mrmn2/PdfDing">here</a>. After around 9 months of work the app is finally where I wanted it to be and can be considered stable. Last week version v1.0.0 was finally released. Leading up to this I did a major UI revamp which now supports different layouts. </p> <p>Let me know what you think of the new UI. If you like PdfDing consider starring the repo on <a href="https://github.com/mrmn2/PdfDing">github</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mindless-View-3071"> /u/Mindless-View-3071 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j43233/pdfding_version_1_released_and_major_ui_revamp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/commen

## Why my ngrok is not able to respond to GET requests ?
 - [https://www.reddit.com/r/selfhosted/comments/1j42qyo/why_my_ngrok_is_not_able_to_respond_to_get](https://www.reddit.com/r/selfhosted/comments/1j42qyo/why_my_ngrok_is_not_able_to_respond_to_get)
 - RSS feed: $source
 - date published: 2025-03-05T13:12:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I&#39;m developing a flask backend app . I run the app ( on PORT 3005 ) , then I do</p> <p>ngrok http <a href="http://localhost:3005">http://localhost:3005</a></p> <p>anyone should now be able to interact with my backend using the ngrok link .</p> <p>In my case , when I try to call my ngrok api from my ReactJS app , POST apis are working perfectly fine but not GET apis .</p> <p>In case of GET apis , I get this :</p> <p>You are about to visit jkvsfdvvvjdvjkfdkjvfjkfdjvj.ngrok-free.app, served by 104.104.104.34. This website is served for free through ngrok.com. You should only visit this website if you trust whoever sent the link to you. (ERR_NGROK_6024)</p> <p>I came across one documentation from ngrok</p> <p><a href="https://ngrok.com/docs/errors/err_ngrok_6024/">https://ngrok.com/docs/errors/err_ngrok_6024/</a></p> <h1>To remove this page:<a href="https://ngrok.com/docs/errors/err_ngrok_6024/#to-remove-this-page">To remove th

## Recommended alternatives to Firefox Sync?
 - [https://www.reddit.com/r/selfhosted/comments/1j4242b/recommended_alternatives_to_firefox_sync](https://www.reddit.com/r/selfhosted/comments/1j4242b/recommended_alternatives_to_firefox_sync)
 - RSS feed: $source
 - date published: 2025-03-05T12:38:20+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m currently looking for an alternative to Firefox sync, preferably self-hosted.</p> <ul> <li>I&#39;m already using Nextcloud, so something that uses it would be preferable</li> <li>I&#39;ve switched to Zen, &amp; I&#39;m hoping for one that also works with Brave. </li> <li>prefer one that&#39;s integrated to the browser&#39;s bookmarks system &amp; not just tied to the addon</li> </ul> <p>What are your thoughts about <a href="https://github.com/floccusaddon/floccus?tab=readme-ov-file">Floccus</a>? Are there alternatives I can explore?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/YamiYukiSenpai"> /u/YamiYukiSenpai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4242b/recommended_alternatives_to_firefox_sync/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j4242b/recommended_alternatives_to_firefox_sync/">[comments]</a></span>

## Cannot SSH into GPON-ONU-34-20BI connected to UDM Pro - Password issue
 - [https://www.reddit.com/r/selfhosted/comments/1j423z3/cannot_ssh_into_gpononu3420bi_connected_to_udm](https://www.reddit.com/r/selfhosted/comments/1j423z3/cannot_ssh_into_gpononu3420bi_connected_to_udm)
 - RSS feed: $source
 - date published: 2025-03-05T12:38:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I’m having an issue accessing my GPON-ONU-34-20BI module installed in my UniFi Dream Machine Pro. I’m trying to SSH into the module to retrieve the modem ID, but I’m facing authentication problems.</p> <p>My setup: • UniFi Dream Machine Pro with a GPON-ONU-34-20BI SFP module • UDM Pro has IP 192.168.1.1 • GPON module has IP 192.168.2.10 (different subnet due to network constraints) • Using Termius SSH client on iOS What I’ve tried: • The documentation mentions the username “ONTUSER” and password “7sp!lwUBz1” • I can successfully ping the module and establish an SSH connection • I’ve modified the SSH command to enable legacy algorithms: <code>ssh -o HostkeyAlgorithms=+ssh-rsa -o PubkeyAcceptedKeyTypes=+ssh-rsa -o KexAlgorithms=+diffie-hellman-group1-sha1 ONTUSER@192.168.2.10</code> • Using copy &amp; paste to ensure the password is entered correctly • The connection works but the password is consistently rejected</p> <p>Questions: 1. Has 

## Which graphics card should I get for my Jellyfin server?
 - [https://www.reddit.com/r/selfhosted/comments/1j422nl/which_graphics_card_should_i_get_for_my_jellyfin](https://www.reddit.com/r/selfhosted/comments/1j422nl/which_graphics_card_should_i_get_for_my_jellyfin)
 - RSS feed: $source
 - date published: 2025-03-05T12:36:05+00:00

<!-- SC_OFF --><div class="md"><p>Just as the title above asks, I’m deciding between an Intel A770 16GB or a 3060 12GB for multiple 4K streams? Has Intel’s graphics drivers been well updated now? Or should I just go with the tried-and-true method of choosing Nvidia?</p> <p>If so, what are the benefits of having either of them and what are the pros and cons?</p> <p>My NAS will be running true NAS as its main software with the Jellyfin plugin. Although this is still my first time building a NAS, I’m still wanting to make sure I’m doing things the right way.</p> <p>I’m also aware that my current setup is unnecessary, and I could easily run this entire setup on an Intel IGPU. I’ve already acquired all the other components from my previous PC, so all I need is a GPU recommendation.</p> <p>Thank you once again for all the invaluable advice you, the amazing people out there, have provided. <sup>^</sup></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aL

## Self hosting gpt-sovits with API
 - [https://www.reddit.com/r/selfhosted/comments/1j416z3/self_hosting_gptsovits_with_api](https://www.reddit.com/r/selfhosted/comments/1j416z3/self_hosting_gptsovits_with_api)
 - RSS feed: $source
 - date published: 2025-03-05T11:43:58+00:00

<!-- SC_OFF --><div class="md"><p>Not sure if this is the right place to ask; I&#39;m using windows and I managed to run the web UI for GPT SoVITS and get it working fine. Now I want to connect one of my python apps to it, but I couldn&#39;t find a direct API or endpoint to which I can send my request and receive the generated audio.</p> <p>There was an API.py file, but it required me to downgrade my Numpy and I didn&#39;t since it&#39;ll break a lot of my other stuff. Is there an easily accessible endpoint that I don&#39;t know of? What about creating a virtual environment for it? (I used the pre-bundled windows installer they had) I&#39;m open for suggestions, thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/annann7"> /u/annann7 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j416z3/self_hosting_gptsovits_with_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j416z3/self_h

## Guacamole : ssh with key+password ?
 - [https://www.reddit.com/r/selfhosted/comments/1j40nbs/guacamole_ssh_with_keypassword](https://www.reddit.com/r/selfhosted/comments/1j40nbs/guacamole_ssh_with_keypassword)
 - RSS feed: $source
 - date published: 2025-03-05T11:07:14+00:00

<!-- SC_OFF --><div class="md"><p>Hi ! </p> <p>Does anyone knows if Guacmaole can handle SSH with key+password authentication ? </p> <p>I got the error : &quot;Public key authentication failed, invalid signature for supplied public key or bad username/public key combination&quot;</p> <p>It works fine with only the same pubkey, also with password only. But as soon as i set &quot;AuthenticationMethods publickey,password&quot; on the remote server, Guacamole can&#39;t connect (it works fine from another ssh client)</p> <p>I tried to clean all known_hosts, set host key... </p> <p>Thanks for the help :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Far_Fig1798"> /u/Far_Fig1798 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j40nbs/guacamole_ssh_with_keypassword/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j40nbs/guacamole_ssh_with_keypassword/">[comments]</a></span>

## Self-Host Noob. Seeking opinions and guidance
 - [https://www.reddit.com/r/selfhosted/comments/1j40m8k/selfhost_noob_seeking_opinions_and_guidance](https://www.reddit.com/r/selfhosted/comments/1j40m8k/selfhost_noob_seeking_opinions_and_guidance)
 - RSS feed: $source
 - date published: 2025-03-05T11:05:09+00:00

<!-- SC_OFF --><div class="md"><p>Hey self-hosting community,</p> <p>I’m currently running a VPS where I’ve set up Portainer, Umami, and Miniflux. I’ve configured my domain with Cloudflare and am working on securing everything with HTTPS using Caddy. So far, it&#39;s been a fun learning experience, but now I’m thinking of expanding my setup.</p> <p>I’m considering hosting Vaultwarden, a personal blog, and a CMS on the same VPS. I wanted to reach out to the community for some best practices and tips, especially around the following topics:</p> <h1>1. Monitoring:</h1> <ul> <li>What do you all use for monitoring uptime, version updates, and server load?</li> <li>How do you ensure that everything is running smoothly?</li> </ul> <h1>2. Security:</h1> <ul> <li>Should I be configuring firewalls for my VPS? If so, which ones are recommended for self-hosted environments?</li> <li>What should I expose on my Docker containers, and how do you approach securing your containers and services?</li> 

## Best way to use self-hosted LocalAI models in VSCode?
 - [https://www.reddit.com/r/selfhosted/comments/1j401j4/best_way_to_use_selfhosted_localai_models_in](https://www.reddit.com/r/selfhosted/comments/1j401j4/best_way_to_use_selfhosted_localai_models_in)
 - RSS feed: $source
 - date published: 2025-03-05T10:23:48+00:00

<!-- SC_OFF --><div class="md"><p>I’m using <strong>LocalAI</strong> to run models like <code>phi-2</code> on my local machine, but I can’t find a VSCode extension that lets me <strong>easily</strong> connect to a <strong>self-hosted OpenAI-compatible API</strong> (e.g., <code>http://localhost:8080/v1</code>).</p> <p>Most extensions force OpenAI usage, and I don’t want to deal with complex workarounds. I even built my own plugin: <a href="https://github.com/miloskec/vscode-custom-ai-suggestions-extension"><strong>VSCode Custom AI Suggestions</strong></a>, but I was hoping there was already a solid alternative.</p> <p>Has anyone found an <strong>AI extension that works seamlessly with a self-hosted LocalAI API?</strong> If not, maybe I should build a full-featured one.</p> <p>Would love to hear what others are using!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TransitionRemote208"> /u/TransitionRemote208 </a> <br/> <span><a href="https://www.

## European based Cloudflare alternative
 - [https://www.reddit.com/r/selfhosted/comments/1j3zj8e/european_based_cloudflare_alternative](https://www.reddit.com/r/selfhosted/comments/1j3zj8e/european_based_cloudflare_alternative)
 - RSS feed: $source
 - date published: 2025-03-05T09:47:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>For reasons I won&#39;t detail here, I&#39;m looking to stop using USA based corporations on my homelab. That&#39;s why I&#39;m looking for an alternative to Cloudflare, preferably from Europe. I&#39;m not speaking about the CDN part, lots of alternatives exists. I&#39;m thinking more about the proxy, filtering, bot fighting,etc... I am also using tunnel on one of my services.</p> <p>I don&#39;t mind hosting everything at home without Cloudflare proxy but I got to say that was useful to &quot;hide&quot; behind this thing !</p> <p>Thanks</p> <p>EDIT: Willing to pay a small or reasonable fee</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/saintjimmy12"> /u/saintjimmy12 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3zj8e/european_based_cloudflare_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3zj8e/european_based_cloudflar

## Small business : looking for reliable email, calendar, document storage & web editing tools
 - [https://www.reddit.com/r/selfhosted/comments/1j3zecr/small_business_looking_for_reliable_email](https://www.reddit.com/r/selfhosted/comments/1j3zecr/small_business_looking_for_reliable_email)
 - RSS feed: $source
 - date published: 2025-03-05T09:36:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I run a 10-people business that&#39;s sending a lot of money to Google every month, which I dislike.</p> <p>The key features that make us use Google are as follows :</p> <p>- Reliable Email &amp; Calendar tools</p> <p>- Reliable document storage &amp; web editing (sheets, slides, docs) =&gt; does such a thing exist outside google ?</p> <p>We need to stay productive and not spend ungodly amounts of time tinkering, and I&#39;m the only technically inclined power user in this company. Tools need to be easy to use and &quot;just work&quot;.</p> <p>Can nextcloud do the trick ? Is the document editing suite reliable or will there be endless frustration ? Are there other good solutions ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Brachamul"> /u/Brachamul </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3zecr/small_business_looking_for_reliable_email/">[link]</a></span> &#32; <

## 19 Open Source Tools You Can Self-Host
 - [https://www.reddit.com/r/selfhosted/comments/1j3yzgs/19_open_source_tools_you_can_selfhost](https://www.reddit.com/r/selfhosted/comments/1j3yzgs/19_open_source_tools_you_can_selfhost)
 - RSS feed: $source
 - date published: 2025-03-05T09:04:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a big believer in open source, but recently I&#39;ve been exploring the self-hosting space and found great tools such as Plausible, Umami for analytics and others like PayloadCMS, Ghost &amp; much more.</p> <p>Below, you’ll find <strong>19</strong> open-source projects you can self-host and some data including GitHub stats and repo link.</p> <h1>Analytics</h1> <p><strong>Umami</strong> - 25,001 Github Stars - <a href="https://github.com/umami-software/umami">github.com/umami-software/umami</a><br/> <strong>Plausible</strong> - 21,615 Github Stars - <a href="https://github.com/plausible/analytics">github.com/plausible/analytics</a><br/> <strong>PostHog</strong> - 24,625 Github Stars - <a href="https://github.com/PostHog/posthog">github.com/PostHog/posthog</a><br/> <strong>OpenPanel</strong> - 3,707 Github Stars - <a href="https://github.com/Openpanel-dev/openpanel">github.com/Openpanel-dev/openpanel</a></p> <h1>CMS, Wiki &amp; Publishing</h1> 

## Netbird setup Behind Cloudflare proxy (Origin Cert)
 - [https://www.reddit.com/r/selfhosted/comments/1j3yz24/netbird_setup_behind_cloudflare_proxy_origin_cert](https://www.reddit.com/r/selfhosted/comments/1j3yz24/netbird_setup_behind_cloudflare_proxy_origin_cert)
 - RSS feed: $source
 - date published: 2025-03-05T09:03:40+00:00

<!-- SC_OFF --><div class="md"><p>HI Everyone.</p> <p>I recently setup netbird on a VM. Setup was the standard setup where i ran the QuickStart script. I Added my domain (A record domain) that points to that vm. From there Netbird was setup up.</p> <p>I was able to add peers and get all my servers connected with no issues, but after a day i started receiving certificate issues when visiting Netbird via my A Record. I assume this is because I use Cloudflare with Proxy enabled and nowhere did I assign the origin Cert.</p> <p>Now I am new to caddy, and Zitadel so I assume I need to add this origin cert somewhere. Any advice or guide? Google hasn&#39;t been very helpful with any guides or info.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WebIntelligent9433"> /u/WebIntelligent9433 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3yz24/netbird_setup_behind_cloudflare_proxy_origin_cert/">[link]</a></span> &#32; <span><a href

## Why my Grafana isn't showing data?
 - [https://www.reddit.com/r/selfhosted/comments/1j3xjrt/why_my_grafana_isnt_showing_data](https://www.reddit.com/r/selfhosted/comments/1j3xjrt/why_my_grafana_isnt_showing_data)
 - RSS feed: $source
 - date published: 2025-03-05T07:14:30+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j3xjrt/why_my_grafana_isnt_showing_data/"> <img src="https://b.thumbs.redditmedia.com/8h1Q87LWZcFm8JLDPfjdWlljkeedHLWxuW1LDXFz7Ec.jpg" alt="Why my Grafana isn't showing data?" title="Why my Grafana isn't showing data?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hello! I setted up grafana yesterday and I gave it a while to refresh but after a night it still doesn&#39;t show anything. I tried restarting Prometheus, Grafana and Server. I tried different dashboards (this one works on a different server for me). </p> <p>If anyone encountered the same problem please help! I can ensure that Prometheus and Grafana have connection between since I tested it with grafana data integration I&#39;m using &quot;GET&quot; as request idk if that will change anything but I tried with &quot;POST&quot; and nothing. </p> <p>Anyways here&#39;s my docker compose file for grafana and the problem. Any help would be appreciated. 

## Help me harden my webserver
 - [https://www.reddit.com/r/selfhosted/comments/1j3x8cs/help_me_harden_my_webserver](https://www.reddit.com/r/selfhosted/comments/1j3x8cs/help_me_harden_my_webserver)
 - RSS feed: $source
 - date published: 2025-03-05T06:52:07+00:00

<!-- SC_OFF --><div class="md"><p>I want to expose port 80/443 to the public internet. Yup i already am using cloudflare but what do you usually do about bots and scanners who scan your origin IP anyways for open ports ?</p> <p>Do we have anything to block all countries except one ? My server uses caddy as a reverse proxy but im a bit worried about the scanners and bots. How do you harden this ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cum_cum_sex"> /u/cum_cum_sex </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3x8cs/help_me_harden_my_webserver/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3x8cs/help_me_harden_my_webserver/">[comments]</a></span>

## Is a Raspberry Pi a Viable Option for Running a 24/7 qBittorrent Seeding Server?
 - [https://www.reddit.com/r/selfhosted/comments/1j3wne5/is_a_raspberry_pi_a_viable_option_for_running_a](https://www.reddit.com/r/selfhosted/comments/1j3wne5/is_a_raspberry_pi_a_viable_option_for_running_a)
 - RSS feed: $source
 - date published: 2025-03-05T06:12:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for advice on building a low-power device that will connect to my NAS NFS share for seeding media and files 24/7, 365 days a year, without significantly increasing my power bill. My plan is to use Docker for running the qBittorrent client and Gluetun for the VPN (with port forwarding enabled, of course). I&#39;ve asked in other subreddits before but kept having my posts removed, so I&#39;m hoping to get some helpful insights here.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConfusedHomelabber"> /u/ConfusedHomelabber </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3wne5/is_a_raspberry_pi_a_viable_option_for_running_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3wne5/is_a_raspberry_pi_a_viable_option_for_running_a/">[comments]</a></span>

## Caddy not issuing ssl
 - [https://www.reddit.com/r/selfhosted/comments/1j3vfbj/caddy_not_issuing_ssl](https://www.reddit.com/r/selfhosted/comments/1j3vfbj/caddy_not_issuing_ssl)
 - RSS feed: $source
 - date published: 2025-03-05T04:58:39+00:00

<!-- SC_OFF --><div class="md"><p>So i finally installed all the arr app, set up caddy however when I am going to run caddy it&#39;s giving me a bunch of errors for my site. I configured the config file properly so should be working. thoughts?</p> <p><a href="https://pastebin.com/EtANYtga">https://pastebin.com/EtANYtga</a></p> <p>I believe the issue is the timezone that is different, but unsure how to change it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juzt4me"> /u/juzt4me </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3vfbj/caddy_not_issuing_ssl/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3vfbj/caddy_not_issuing_ssl/">[comments]</a></span>

## VPS Hit 100% CPU & Became Unresponsive – How to Prevent This?
 - [https://www.reddit.com/r/selfhosted/comments/1j3uf5w/vps_hit_100_cpu_became_unresponsive_how_to](https://www.reddit.com/r/selfhosted/comments/1j3uf5w/vps_hit_100_cpu_became_unresponsive_how_to)
 - RSS feed: $source
 - date published: 2025-03-05T04:01:22+00:00

<!-- SC_OFF --><div class="md"><p>set up a VPS with Coolify to manage my projects and connected it with Cloudflare Tunnels. Everything was running fine for a few days, but tonight, while deploying a new feature, my VPS completely locked up. I couldn’t access Coolify, my Next.js app was down, SSH stopped working, and the CPU was stuck at 100%.</p> <p>I had to force reboot the server, and now everything is back up, but I want to make sure this doesn’t happen again, especially since it’s for a client.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Noor_Slimane_9999"> /u/Noor_Slimane_9999 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3uf5w/vps_hit_100_cpu_became_unresponsive_how_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3uf5w/vps_hit_100_cpu_became_unresponsive_how_to/">[comments]</a></span>

## Self-Hosted Internet Radio Collection Portal/App?
 - [https://www.reddit.com/r/selfhosted/comments/1j3u3f7/selfhosted_internet_radio_collection_portalapp](https://www.reddit.com/r/selfhosted/comments/1j3u3f7/selfhosted_internet_radio_collection_portalapp)
 - RSS feed: $source
 - date published: 2025-03-05T03:43:06+00:00

<!-- SC_OFF --><div class="md"><p>What I&#39;m looking for seems so simple, I must just not be using the right search terms.</p> <p>I started using Navidrome a while back to stream my own music collection, and it&#39;s quite useful. One feature I took some time to investigate was its &quot;Radio&quot; section, where you can specify a collection of URLs for streaming radio services and listen to them. Most client apps on phones allow access to this, making it a good alternative if you want something more &quot;live&quot; than your own music collection. I&#39;ve even found integrations between Sonos and Navidrome (Bonob) work with these radio channels too. However, the feature is buggy and very bare-bones. From some reading, it seems the team maintaining Navidrome view the radio feature as of minimal value, and they simply don&#39;t do much with it any more. There are a number of stream compatibility issues. I&#39;ve noticed streams that work just fine in a browser that simply won&#39;

## any selfhosted meta search engines?
 - [https://www.reddit.com/r/selfhosted/comments/1j3s5ia/any_selfhosted_meta_search_engines](https://www.reddit.com/r/selfhosted/comments/1j3s5ia/any_selfhosted_meta_search_engines)
 - RSS feed: $source
 - date published: 2025-03-05T02:03:17+00:00

<!-- SC_OFF --><div class="md"><p>was looking for a selfhosted duck duck go for example. can anyone think of anything that already exsists?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dry_Pay_1137"> /u/Dry_Pay_1137 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3s5ia/any_selfhosted_meta_search_engines/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3s5ia/any_selfhosted_meta_search_engines/">[comments]</a></span>

## file upload page
 - [https://www.reddit.com/r/selfhosted/comments/1j3rtqm/file_upload_page](https://www.reddit.com/r/selfhosted/comments/1j3rtqm/file_upload_page)
 - RSS feed: $source
 - date published: 2025-03-05T01:46:58+00:00

<!-- SC_OFF --><div class="md"><p>Whats everyones favorite self hosted uploads page? Something I can setup on my end for people with the link to send me files. I would like to set the max size and if it has some sort of login page that&#39;s a bonus. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/larsen8989"> /u/larsen8989 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3rtqm/file_upload_page/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3rtqm/file_upload_page/">[comments]</a></span>

## owned domains used locally?
 - [https://www.reddit.com/r/selfhosted/comments/1j3qlcr/owned_domains_used_locally](https://www.reddit.com/r/selfhosted/comments/1j3qlcr/owned_domains_used_locally)
 - RSS feed: $source
 - date published: 2025-03-05T00:47:06+00:00

<!-- SC_OFF --><div class="md"><p>Can someone explain how bought domains work when using locally. For example if I own <a href="http://boogerdomain.com">boogerdomain.com</a> proxmox says hey whats your fqdn, i think it defaults to pve.local, opnsense has a local domain I use <a href="http://home.arpa">home.arpa</a>, but since I own my own fqdn how would i utilize it here? Would it be like <a href="http://pve.server.boogerdomain.com">pve.server.boogerdomain.com</a> or something like that? I dont quite follow this but I would love to not use .local .arpa etc, I already use dns rewrites to hit things internally by their fqdn wan counterparts.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3qlcr/owned_domains_used_locally/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3qlcr/owned_domains_used_locally/">[co

## PSA : Earlier I mentioned nip.io for DNS. Do not use it, the owner of the company passed away
 - [https://www.reddit.com/r/selfhosted/comments/1j3q9kp/psa_earlier_i_mentioned_nipio_for_dns_do_not_use](https://www.reddit.com/r/selfhosted/comments/1j3q9kp/psa_earlier_i_mentioned_nipio_for_dns_do_not_use)
 - RSS feed: $source
 - date published: 2025-03-05T00:31:08+00:00

<!-- SC_OFF --><div class="md"><p>I did a little reading up on this company and noticed that all of their products have down gateways or expired, so I emailed out of curiosity and received the above response. Expect this domain to disappear in the near term. </p> <p><a href="https://xp-dev-recovery.boards.net/thread/3/status-update">https://xp-dev-recovery.boards.net/thread/3/status-update</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/doolittledoolate"> /u/doolittledoolate </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3q9kp/psa_earlier_i_mentioned_nipio_for_dns_do_not_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3q9kp/psa_earlier_i_mentioned_nipio_for_dns_do_not_use/">[comments]</a></span>

## {Showcase} Network Chronicles - WIP
 - [https://www.reddit.com/r/selfhosted/comments/1j3pug9/showcase_network_chronicles_wip](https://www.reddit.com/r/selfhosted/comments/1j3pug9/showcase_network_chronicles_wip)
 - RSS feed: $source
 - date published: 2025-03-05T00:11:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1j3pug9/showcase_network_chronicles_wip/"> <img src="https://b.thumbs.redditmedia.com/-y5rA9PicX2jbAhymbvErS4zZ_6v39KLH4ZhqVBb9HA.jpg" alt="{Showcase} Network Chronicles - WIP" title="{Showcase} Network Chronicles - WIP" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fimeg"> /u/Fimeg </a> <br/> <span><a href="https://www.reddit.com/gallery/1j3pug9">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1j3pug9/showcase_network_chronicles_wip/">[comments]</a></span> </td></tr></table>

