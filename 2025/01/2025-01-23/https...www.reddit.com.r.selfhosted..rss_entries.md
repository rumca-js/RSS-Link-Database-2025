# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Help with remote access and dns
 - [https://www.reddit.com/r/selfhosted/comments/1i8ggjd/help_with_remote_access_and_dns](https://www.reddit.com/r/selfhosted/comments/1i8ggjd/help_with_remote_access_and_dns)
 - RSS feed: $source
 - date published: 2025-01-23T22:49:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, sorry if this has been asked answered million times here bit of a noob here.</p> <p>How do I share my jellyfin and immich docker ports running on my server with family/ friends. I just want to expose these very SECURELY on a domain. I already have domain name. Will everyone on the internet have access to my services ?</p> <p>Tailscale is working but will be too much setup for them and heard cloudflare has ToS/ privacy issues.</p> <p>Also whats the deal with https/ ssl, will i need it ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Appropriate-Play-208"> /u/Appropriate-Play-208 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8ggjd/help_with_remote_access_and_dns/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8ggjd/help_with_remote_access_and_dns/">[comments]</a></span>

## Simple Homepage custom.js script
 - [https://www.reddit.com/r/selfhosted/comments/1i8fzal/simple_homepage_customjs_script](https://www.reddit.com/r/selfhosted/comments/1i8fzal/simple_homepage_customjs_script)
 - RSS feed: $source
 - date published: 2025-01-23T22:28:17+00:00

<!-- SC_OFF --><div class="md"><p>I have my Homepage set up with links to service.domain.tld as I am using a cloudflare tunnel. I click on Immich, it takes me to immich.mydomain.tld. I would prefer to go to ip:port when I&#39;m on my home network though. I&#39;ve tried WatchYourPorts, bookmarking ip:port and more, but I&#39;ve realized I can do it with Homepages customjs script. I was lucky enough that for each service you have on your homepage, there are 2 links: one on the icon and one on the card itself. This scripts changes the icon link to the local service url and leaves the card&#39;s link intact to whatever url you have set in services.yaml. Maybe it helps someone, i made it for me tbh, also share any other scripts if you use this feature.</p> <pre><code>const ip = &#39;192.168.X.XXX&#39; // http://ip:port const changeToLocal = () =&gt; { document.querySelectorAll(&#39;li.service&#39;).forEach(service =&gt; { const port = service.id?.slice(1) || null if (port) { const link = 

## Introducing Caddy-Defender: A Reddit-Inspired Caddy Module to Block Bots, Cloud Providers, and AI Scrapers!
 - [https://www.reddit.com/r/selfhosted/comments/1i8f9a2/introducing_caddydefender_a_redditinspired_caddy](https://www.reddit.com/r/selfhosted/comments/1i8f9a2/introducing_caddydefender_a_redditinspired_caddy)
 - RSS feed: $source
 - date published: 2025-01-23T21:57:37+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>!</p> <p>I’m thrilled to share <a href="https://github.com/JasonLovesDoggo/caddy-defender"><strong>Caddy-Defender</strong></a>, a new <a href="https://caddyserver.com/">Caddy</a> module inspired by a discussion right <a href="https://www.reddit.com/r/selfhosted/comments/1i154h7/openai_not_respecting_robotstxt_and_being_sneaky/">here</a> on this sub! A few days ago, I saw <a href="https://www.reddit.com/r/selfhosted/comments/1i154h7/comment/m73pj9t/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">this comment</a> about defending against unwanted traffic, and I thought, <em>“Hey, I can build that!”</em></p> <h1>What is it?</h1> <p>Caddy-Defender is a <strong>lightweight module</strong> to help protect your self-hosted services from:</p> <ul> <li>🤖 <strong>Bots</strong></li> <li>🕵️ <strong>Malicious traffic</strong></li> <li>☁️ <strong>Entire cloud provi

## Supermicro 825 file server
 - [https://www.reddit.com/r/selfhosted/comments/1i8f19o/supermicro_825_file_server](https://www.reddit.com/r/selfhosted/comments/1i8f19o/supermicro_825_file_server)
 - RSS feed: $source
 - date published: 2025-01-23T21:47:56+00:00

<!-- SC_OFF --><div class="md"><p>I recently found a 825 supermicro server in our recycle area and I took it home to find out it has no ram but I was wondering with a DDR3 mobo would this still be good to use in a media environment for jellyfin? My worry is the data transfer speeds being slow. The motherboard is a X8ST3-F. </p> <p>Currently i just have an old desktop that i can barely fit any more than 5 drives in because the GPU is massive plus it&#39;s the same case my proxmox is in so I wanted to separate them out. </p> <p>Thanks for any responses. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Roguediculous"> /u/Roguediculous </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8f19o/supermicro_825_file_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8f19o/supermicro_825_file_server/">[comments]</a></span>

## Looking for a music server that'll run on an OLD browser
 - [https://www.reddit.com/r/selfhosted/comments/1i8e7xg/looking_for_a_music_server_thatll_run_on_an_old](https://www.reddit.com/r/selfhosted/comments/1i8e7xg/looking_for_a_music_server_thatll_run_on_an_old)
 - RSS feed: $source
 - date published: 2025-01-23T21:13:38+00:00

<!-- SC_OFF --><div class="md"><p>So I have an ewaste piece of garbage iPad 2 running iOS 9 in my kitchen. It&#39;s good enough to read recipes, but basically no music streaming website I have tried will load on Safari; just a blank or loading screen on Plex, Navidrome Obviously I can&#39;t download any apps on this thing.</p> <p>Any ideas? Have any of these projects been doing so long that an old version might work?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ratbum"> /u/ratbum </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8e7xg/looking_for_a_music_server_thatll_run_on_an_old/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8e7xg/looking_for_a_music_server_thatll_run_on_an_old/">[comments]</a></span>

## Hosting OpenDesk Yourself?
 - [https://www.reddit.com/r/selfhosted/comments/1i8dzwy/hosting_opendesk_yourself](https://www.reddit.com/r/selfhosted/comments/1i8dzwy/hosting_opendesk_yourself)
 - RSS feed: $source
 - date published: 2025-01-23T21:04:35+00:00

<!-- SC_OFF --><div class="md"><p>I recently stumbled across OpenDesk, and it looks super interesting! However, I couldn&#39;t find an easy Docker installation for it.</p> <p>Has anyone here tried self-hosting OpenDesk? Any tips or guides you can share? I&#39;d love to hear your experiences or if there&#39;s a simple way to get it running.</p> <p>Thanks in advance!&quot;</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/National_Worker_9504"> /u/National_Worker_9504 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dzwy/hosting_opendesk_yourself/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dzwy/hosting_opendesk_yourself/">[comments]</a></span>

## Constant intrusion attempts killing my system
 - [https://www.reddit.com/r/selfhosted/comments/1i8dqfi/constant_intrusion_attempts_killing_my_system](https://www.reddit.com/r/selfhosted/comments/1i8dqfi/constant_intrusion_attempts_killing_my_system)
 - RSS feed: $source
 - date published: 2025-01-23T20:53:54+00:00

<!-- SC_OFF --><div class="md"><p>I have a little raspberry pi 3 running a few IoT services in a remote location. It’s open for a ssh, https, mqtt and a few other things. It’s very secure but it’s constantly being probed by, for example attempt to ssh, or search for directories in the web server. I’m using ufw and fail2ban, I only allow ssh by public/private key. But still constant attempts are consuming compute resources and my limited bandwidth. </p> <p>How do others cope with this? I don’t imagine there’s anything specially attractive about my setup! Can I push the work off screening to another device ?</p> <p>Thanks for your help. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mwanafunzi255"> /u/mwanafunzi255 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dqfi/constant_intrusion_attempts_killing_my_system/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dqfi/constant_intrus

## Looking for advice for a VPS with multiple IP adresses
 - [https://www.reddit.com/r/selfhosted/comments/1i8dkl1/looking_for_advice_for_a_vps_with_multiple_ip](https://www.reddit.com/r/selfhosted/comments/1i8dkl1/looking_for_advice_for_a_vps_with_multiple_ip)
 - RSS feed: $source
 - date published: 2025-01-23T20:46:49+00:00

<!-- SC_OFF --><div class="md"><p>I own multiple blogwebsites, up to 150. I’m looking for a VPS which could support around the same number of unique IP-adresses.</p> <p>I’m situated in the Netherlands, but looking for all kinds of advice for different IP-adresses.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Swartgoed"> /u/Swartgoed </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dkl1/looking_for_advice_for_a_vps_with_multiple_ip/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8dkl1/looking_for_advice_for_a_vps_with_multiple_ip/">[comments]</a></span>

## PHP based light blog?
 - [https://www.reddit.com/r/selfhosted/comments/1i8bwf6/php_based_light_blog](https://www.reddit.com/r/selfhosted/comments/1i8bwf6/php_based_light_blog)
 - RSS feed: $source
 - date published: 2025-01-23T19:37:06+00:00

<!-- SC_OFF --><div class="md"><p>Clearly I&#39;m not using the right reach terms but I&#39;m after a PHP powered blogging system that is very lightweight and allows different post types. I think I&#39;m after a Tumblr style blog (image post, link post, YT post, long form text post etc.). Ideally it would be light enough that it uses a flat file store system but I know I&#39;m pushing that. A selection of themes to get me started would be grand but that&#39;s just the cherry on top. </p> <p>Looking for it for a single user. I&#39;ve ran WP for a number of years but looking to move to something lighter. </p> <p>Any ideas on the best one to go with? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nickweb"> /u/nickweb </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8bwf6/php_based_light_blog/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8bwf6/php_based_light_blog/">[comments]</a></

## Good use for old laptop?
 - [https://www.reddit.com/r/selfhosted/comments/1i8buof/good_use_for_old_laptop](https://www.reddit.com/r/selfhosted/comments/1i8buof/good_use_for_old_laptop)
 - RSS feed: $source
 - date published: 2025-01-23T19:35:04+00:00

<!-- SC_OFF --><div class="md"><p>I have a really old (09) laptop given by my work.</p> <p>I already have a server running basically everything I want. Jellyfin, arr stack, immich, syncthing, audiobookshelf, qbittorrent.</p> <p>My biggest problem right now is actually my performance. I upgraded my RAM, but my server is still sorta bogged down.</p> <p>Could I reasonably run anything, even qBittorrent, on a Core 2 Duo and between 1 and 8gb RAM? Could I run HomeAssistant on this laptop, since that&#39;s the only thing I don&#39;t have for performance reasons?</p> <p>Edit: 2Gb RAM</p> <p>Also, I have two of these laptops</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bill_Buttersr"> /u/Bill_Buttersr </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8buof/good_use_for_old_laptop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i8buof/good_use_for_old_laptop/">[comments]</a></span>

## KitOps v1.0.0 is now available, featuring Hugging Face to ModelKit import
 - [https://www.reddit.com/r/selfhosted/comments/1i89zfy/kitops_v100_is_now_available_featuring_hugging](https://www.reddit.com/r/selfhosted/comments/1i89zfy/kitops_v100_is_now_available_featuring_hugging)
 - RSS feed: $source
 - date published: 2025-01-23T18:19:04+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, my name is Jesse, I&#39;m a project lead for open source KitOps (kitops.ml)</p> <p>Yesterday we cut our 1.0 release(!) which at some points has felt like an impossible milestone.</p> <p><strong>Project Background</strong><br/> KitOps was inspired by the idea that we could define a <em>better</em> was inspired by the idea that we could define a <em>better</em> way of storing, sharing, and deploying AI/ML models. By using a structure related to the ubiquitous Docker container format, we gain many of the useful features of containers (such as immutability and simple distribution) while tailoring our implementation to be simple and easy to use. With a few commands, you can take a locally stored model, package it into the ModelKit format, and push it to most image registries currently used for sharing containers.</p> <p>We&#39;ve been working on the project for the past year and are proud to announce the release of KitOps v1.0.0. Here are so

## Looking for a self-hosted OperaTurbo alternative / caching server for low bandwidth connections
 - [https://www.reddit.com/r/selfhosted/comments/1i89wry/looking_for_a_selfhosted_operaturbo_alternative](https://www.reddit.com/r/selfhosted/comments/1i89wry/looking_for_a_selfhosted_operaturbo_alternative)
 - RSS feed: $source
 - date published: 2025-01-23T18:15:58+00:00

<!-- SC_OFF --><div class="md"><p>We have a situation where one of our sites has an EVDO/G3 speed connection that is unusable for anything other than basic messaging. I would like to host a proxy server that will compress websites down as much as possible so they can be viewed on this potato connection. Any insight woudl be appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cainram"> /u/cainram </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i89wry/looking_for_a_selfhosted_operaturbo_alternative/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i89wry/looking_for_a_selfhosted_operaturbo_alternative/">[comments]</a></span>

## Confused on why switch gives no internet
 - [https://www.reddit.com/r/selfhosted/comments/1i89sh7/confused_on_why_switch_gives_no_internet](https://www.reddit.com/r/selfhosted/comments/1i89sh7/confused_on_why_switch_gives_no_internet)
 - RSS feed: $source
 - date published: 2025-01-23T18:11:12+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i89sh7/confused_on_why_switch_gives_no_internet/"> <img src="https://preview.redd.it/jn4cxrq1bsee1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=c6f10ecab54b390be8390dd53cdd4b7ce099a7bf" alt="Confused on why switch gives no internet" title="Confused on why switch gives no internet" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Networking newb. Need help please :)</p> <p>Via wired laptop, I can neither ping nor browse 192.168.1.1 to access switch</p> <p>Nor access 10.0.0.50:5000 to access NAS</p> <p>When directly connected to modem router, can access admin 10.0.0.1</p> <p>My laptop should be able to get internet when I connect via cat5 to switch. Right now, I can only get WiFi via Google WiFi. </p> <p>I should be able to browse NAS when either connected via WiFi or wired.</p> <p>How do I fix my issue? Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/azimuth

## QuickDrop 1.3.0 is here! 🎉
 - [https://www.reddit.com/r/selfhosted/comments/1i88bfo/quickdrop_130_is_here](https://www.reddit.com/r/selfhosted/comments/1i88bfo/quickdrop_130_is_here)
 - RSS feed: $source
 - date published: 2025-01-23T17:10:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i88bfo/quickdrop_130_is_here/"> <img src="https://b.thumbs.redditmedia.com/fRgBKt8R_C57gRNoQmQFXa_qMkBsRxcexEcSxn72VYA.jpg" alt="QuickDrop 1.3.0 is here! 🎉" title="QuickDrop 1.3.0 is here! 🎉" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>For anyone that doesn&#39;t know the project, <strong>QuickDrop</strong> is a simple self-hosted app to upload and share files with no user accounts required. You can protect files with passwords, generate one-time download links, and now a <strong>whole lot more</strong>. Here’s what’s new in <strong>1.3.0</strong>:</p> <ul> <li><strong>Chunked Uploads</strong> Upload huge files reliably, even on slow or spotty connections.</li> <li><strong>Disable “View Files”</strong> Prefer privacy? Turn off the built-in file listing page entirely.</li> <li><strong>All-in-One Share Modal</strong> Generate links, set custom days for the link to be valid, or create fully unrestricted link

## Open Source contribution in the era of AI Agents
 - [https://www.reddit.com/r/selfhosted/comments/1i87xh7/open_source_contribution_in_the_era_of_ai_agents](https://www.reddit.com/r/selfhosted/comments/1i87xh7/open_source_contribution_in_the_era_of_ai_agents)
 - RSS feed: $source
 - date published: 2025-01-23T16:54:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been a long-time open-source contributor, having worked on projects like Reactplay, Tembo, Julep, and more. I&#39;ve not only contributed code, but I&#39;ve also been a maintainer, managing multiple GitHub repositories. So, I&#39;ve seen things from both sides.</p> <p>With the rise of AI assistants like ChatGPT, Cursor, and Gemini, there&#39;s a growing trend of contributors using these tools to churn out solutions to issues and calling it open-source contribution. As a maintainer, I come across these baseless contributions all the time, where the code is AI-generated and doesn&#39;t actually solve the problem.</p> <p>While working as a Reactplay maintainer, reviewing PRs and comments was part of my daily routine. Contributors would often try to game the system by using AI Agents to generate solutions to issues. I&#39;d end up pulling my hair out because most of these &#39;contributions&#39; were just AI-generated code that didn&#39;t actual

## Help with fail2ban
 - [https://www.reddit.com/r/selfhosted/comments/1i87vhy/help_with_fail2ban](https://www.reddit.com/r/selfhosted/comments/1i87vhy/help_with_fail2ban)
 - RSS feed: $source
 - date published: 2025-01-23T16:52:39+00:00

<!-- SC_OFF --><div class="md"><p>I have the following jail.local file, I can&#39;t figure out whats wrong here.</p> <pre><code>[DEFAULT] [jellyfin] enabled = true maxretry = 3 logpath = /remotelogs/jellyfin/log_*.log chain = DOCKER-USER action = %(known/action)s [jellyseerr] enabled = true maxretry = 3 logpath = /remotelogs/jellyseer/overseerr.log chain = DOCKER-USER action = %(known/action)s discord-notifications[bantime=10] [npm-general-forceful-browsing] enabled = true filter = npm-general-forceful-browsing chain = DOCKER-USER logpath = /remotelogs/nginx/proxy-host-*_access.log maxretry = 10 action = %(known/action)s discord-notifications[bantime=10] </code></pre> <p>When I ban an IP in the jellyseerr jail it works, the others just notifiy in discord but the ban doesn&#39;t work, it doesn&#39;t stop the connections. For reference all services are in docker containers, and the incoming traffic is through an nginx proxy manager docker container.</p> </div><!-- SC_ON --> &#32; submi

## IntellAgnet: An open-source framework to evaluate and optimize conversational agents
 - [https://www.reddit.com/r/selfhosted/comments/1i85pny/intellagnet_an_opensource_framework_to_evaluate](https://www.reddit.com/r/selfhosted/comments/1i85pny/intellagnet_an_opensource_framework_to_evaluate)
 - RSS feed: $source
 - date published: 2025-01-23T15:20:35+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://github.com/plurai-ai/intellagent">IntellAgnet</a> is a novel multi-agent framework to evaluate conversational agents. The system takes the prompt as an input and generates thousands of <strong>realistic</strong> challenging interactions with the tested agent. It then simulates the interactions and provides fine-grained analysis. The <a href="https://arxiv.org/abs/2501.11067">research paper</a> provides many non-trivial insights that are produced by the system.</p> <p>The system is open source: <a href="https://github.com/plurai-ai/intellagent">https://github.com/plurai-ai/intellagent</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/e2lv"> /u/e2lv </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i85pny/intellagnet_an_opensource_framework_to_evaluate/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i85pny/intellagnet_an_opensource_fra

## android box as htpc?
 - [https://www.reddit.com/r/selfhosted/comments/1i85lp6/android_box_as_htpc](https://www.reddit.com/r/selfhosted/comments/1i85lp6/android_box_as_htpc)
 - RSS feed: $source
 - date published: 2025-01-23T15:15:56+00:00

<!-- SC_OFF --><div class="md"><p>i found an old MXQ android box collecting dust and i thought i could use it as a htpc. </p> <p>the specs aren&#39;t incredible and it&#39;s running android 6 but i thought with another OS it could make a decent htpc since it&#39;s also very power efficient (i&#39;m using an old windows pc with plexHTPC at the moment)</p> <p>i&#39;m not sure if it supports h265 deconding (if it doesn&#39;t it&#39;s pretty much useless to me cause my server can&#39;t do transcoding) cause i couldn&#39;t find out what hardware it&#39;s exactly running (but it was a cheap box from 2016 so i&#39;m not expecting much) but afaik it can&#39;t be much worse than a firestick. </p> <p>has anybody successfully done this? should i just throw it in the trash? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iCujoDeSotta"> /u/iCujoDeSotta </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i85lp6/android_box_as_htpc/">[link

## Suggestions for Outlook-like app
 - [https://www.reddit.com/r/selfhosted/comments/1i858ki/suggestions_for_outlooklike_app](https://www.reddit.com/r/selfhosted/comments/1i858ki/suggestions_for_outlooklike_app)
 - RSS feed: $source
 - date published: 2025-01-23T15:00:02+00:00

<!-- SC_OFF --><div class="md"><p>Are you aware of any web app that could be locally hosted which can manage multiple email accounts in a single place? Like Outlook but can be hosted as Docker container and be accessed from a web browser within the local network.</p> <p>So far I tested several apps but they only manage a single account at a time</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/iu2frl"> /u/iu2frl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i858ki/suggestions_for_outlooklike_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i858ki/suggestions_for_outlooklike_app/">[comments]</a></span>

## Anyone built a good ERPNext based system at a small company?
 - [https://www.reddit.com/r/selfhosted/comments/1i84tq8/anyone_built_a_good_erpnext_based_system_at_a](https://www.reddit.com/r/selfhosted/comments/1i84tq8/anyone_built_a_good_erpnext_based_system_at_a)
 - RSS feed: $source
 - date published: 2025-01-23T14:40:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys</p> <p>Currently looking for an ERP system to integrate in the company. We&#39;re a small team of 10-15 people designing, manufacturing in China, and selling permanent point of sale in-store displays for all kinds of brands. I&#39;m fairly new in the company and these guys are super old school. To sketch an image, Some of them still have paper agendas, almost no laptops, no Teams/Slack, internal landline, and they do their project management in decades old accounting software.</p> <p>It works to a large extent, but I&#39;m hearing a lot of complaints about difficulty of juggling 10 projects per team and tracking everything. We manage shipping and distribution sometimes too.</p> <p>---</p> <p>Now I find myself scouring the internet for tools - my god there&#39;s so many now - that can help us. Currently the best contender seems Odoo. But I tried hosting ERPNext too. It looks good but seems complicate to set up and customize to our needs. I&#39

## Recipe Management
 - [https://www.reddit.com/r/selfhosted/comments/1i84q9a/recipe_management](https://www.reddit.com/r/selfhosted/comments/1i84q9a/recipe_management)
 - RSS feed: $source
 - date published: 2025-01-23T14:36:07+00:00

<!-- SC_OFF --><div class="md"><p>Looking for a self-hosted recipe manager that will work with Alexa shopping lists on my echo dot. Can Tandoor do this? Any suggestions would be appreciated! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Due-Net5655"> /u/Due-Net5655 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i84q9a/recipe_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i84q9a/recipe_management/">[comments]</a></span>

## Noob question: Pihole + nginx -or- caddy?
 - [https://www.reddit.com/r/selfhosted/comments/1i84g4r/noob_question_pihole_nginx_or_caddy](https://www.reddit.com/r/selfhosted/comments/1i84g4r/noob_question_pihole_nginx_or_caddy)
 - RSS feed: $source
 - date published: 2025-01-23T14:22:41+00:00

<!-- SC_OFF --><div class="md"><p>What are you picking and why? I&#39;m a bit of a noob when it comes to self hosting, but I have done some research and the general consensus I see is: People love nginx because UIs make life easy, people love caddy because just throw your stuff in a file in a easy to understand way.</p> <p>What are you guys running and what do you recommend? Any weird stumbling blocks I need to look out for?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IAmMoonie"> /u/IAmMoonie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i84g4r/noob_question_pihole_nginx_or_caddy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i84g4r/noob_question_pihole_nginx_or_caddy/">[comments]</a></span>

## Help Configuring OrpheusDL for SoundCloud HQ Downloads (192kbps+)
 - [https://www.reddit.com/r/selfhosted/comments/1i83vyg/help_configuring_orpheusdl_for_soundcloud_hq](https://www.reddit.com/r/selfhosted/comments/1i83vyg/help_configuring_orpheusdl_for_soundcloud_hq)
 - RSS feed: $source
 - date published: 2025-01-23T13:56:10+00:00

<!-- SC_OFF --><div class="md"><p>I’ve been trying to configure OrpheusDL to rip <strong>high-quality audio from SoundCloud</strong>, but I’m running into issues and could use some help. My goal is to streamline the process of downloading tracks from SoundCloud using command-line tools like OrpheusDL.</p> <p>I’ve used other rippers, such as <strong>Lucida</strong>, which does a fantastic job of ripping HQ audio (256kbps or 320kbps when available) with all the metadata intact. However, I want to transition to a more <strong>streamlined and customizable solution</strong> like OrpheusDL for better control and efficiency.</p> <p>Here’s what I need:</p> <ul> <li>I don’t want to download anything below <strong>192kbps</strong>, and ideally, I’d like <strong>320kbps</strong> when available.</li> <li>I need as much metadata as possible (artist, title, album art, etc.) since I use the files in <strong>Rekordbox</strong> for DJing.</li> <li>If possible, I’d love guidance on automating the proc

## Home server hardware - miniPC or NAS?
 - [https://www.reddit.com/r/selfhosted/comments/1i839ps/home_server_hardware_minipc_or_nas](https://www.reddit.com/r/selfhosted/comments/1i839ps/home_server_hardware_minipc_or_nas)
 - RSS feed: $source
 - date published: 2025-01-23T13:24:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi, sorry for asking if thats very stupid question but i really tried to find an anwser but couldnt and feel stupid..</p> <p>I&#39;m currently running my home server on an old lenovo laptop with Proxmox. As it only has 256GB storage im running low on it. My main purpose of home server are Immich, some kind of file &quot;cloud&quot; (maybe Seafile), Paperless ngx, Home assistant and some lightweight stuff for food recipes and home budget tracking. MAYBE in the future id like to tinker with *arr for movies and series. It will be used only by me, my wife and maybe kids in the future so 4 users maximum. (two right now)</p> <p>I want to upgrade to hardware that will be sufficient for this purpose for as long as possible.</p> <p>My first idea was to get a 16GB RAM, N100 miniPC with 256/500GB storage and attach usb external hard drive or whole external hard drive enclosure with 3,5&quot; SATA disks but i saw a lot of people saying that storage connected wit

## AI for digital Library
 - [https://www.reddit.com/r/selfhosted/comments/1i82sau/ai_for_digital_library](https://www.reddit.com/r/selfhosted/comments/1i82sau/ai_for_digital_library)
 - RSS feed: $source
 - date published: 2025-01-23T12:59:36+00:00

<!-- SC_OFF --><div class="md"><p>Dear Reddit, assuming I have a collection of ebooks (pdf, epub, jpg...) of &gt; 3tb and consisting of thousands of files. Is there a way to host an AI which screens my library folder for the task I will give the AI? What are the hardware requirements for such a task? Kind regards</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Jazzlike_Iron_2275"> /u/Jazzlike_Iron_2275 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i82sau/ai_for_digital_library/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i82sau/ai_for_digital_library/">[comments]</a></span>

## I like this idea, anyone know of any self hosted alternatives?
 - [https://www.reddit.com/r/selfhosted/comments/1i82q2y/i_like_this_idea_anyone_know_of_any_self_hosted](https://www.reddit.com/r/selfhosted/comments/1i82q2y/i_like_this_idea_anyone_know_of_any_self_hosted)
 - RSS feed: $source
 - date published: 2025-01-23T12:56:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i82q2y/i_like_this_idea_anyone_know_of_any_self_hosted/"> <img src="https://external-preview.redd.it/9sQumFHj1x7oa9eqSPE1wm_xRbuExlsAJhNu1FhLtK0.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=29e1f674e4f3a08f8c23dddb3feba12aa9c23ab3" alt="I like this idea, anyone know of any self hosted alternatives?" title="I like this idea, anyone know of any self hosted alternatives?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Troyking2"> /u/Troyking2 </a> <br/> <span><a href="https://hiddenspectrum.io/people">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i82q2y/i_like_this_idea_anyone_know_of_any_self_hosted/">[comments]</a></span> </td></tr></table>

## How do you use open-source Ai models like Llama or Deepseek
 - [https://www.reddit.com/r/selfhosted/comments/1i822oe/how_do_you_use_opensource_ai_models_like_llama_or](https://www.reddit.com/r/selfhosted/comments/1i822oe/how_do_you_use_opensource_ai_models_like_llama_or)
 - RSS feed: $source
 - date published: 2025-01-23T12:19:36+00:00

<!-- SC_OFF --><div class="md"><p>I am kinda new to this whole ecosystem of selfhost and with the recent news of the open source model deepseek Ai <a href="https://huggingface.co/deepseek-ai/DeepSeek-R1">here</a> I was thinking, there are ways to run it on the system but how do you deploy and use it like how we use the models of open ai or claude with api keys.</p> <p>have any of you tried and whats your experience do you have any blogs which explains all the process, I find it facinating.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jethiya007"> /u/jethiya007 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i822oe/how_do_you_use_opensource_ai_models_like_llama_or/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i822oe/how_do_you_use_opensource_ai_models_like_llama_or/">[comments]</a></span>

## Media Files from Starr-Apps (RPi 5) to a NAS
 - [https://www.reddit.com/r/selfhosted/comments/1i820pd/media_files_from_starrapps_rpi_5_to_a_nas](https://www.reddit.com/r/selfhosted/comments/1i820pd/media_files_from_starrapps_rpi_5_to_a_nas)
 - RSS feed: $source
 - date published: 2025-01-23T12:16:11+00:00

<!-- SC_OFF --><div class="md"><p>Hello everybody,</p> <p>I have a Rasbberry PI 5 with 8GB RAM where all my Services are running (most of the time really smooth). </p> <p>I also have an old HP MicroServer N40L mit 8TB of storage. I would like to use this storage for the media files from the Starr-Apps. These Apps are running on my RPi. On the NAS is unraid running. But it&#39;s too slow to run docker on it. </p> <p>Is there a useful way to to this? Or would it better to buy a new NUC? I tried to install the apps on the HP, but it was too slow.</p> <p>Regards,<br/> Florian</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Pop_2602"> /u/Ok_Pop_2602 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i820pd/media_files_from_starrapps_rpi_5_to_a_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i820pd/media_files_from_starrapps_rpi_5_to_a_nas/">[comments]</a></span>

## Recommendations for selfhosted URL shorter?
 - [https://www.reddit.com/r/selfhosted/comments/1i81hz0/recommendations_for_selfhosted_url_shorter](https://www.reddit.com/r/selfhosted/comments/1i81hz0/recommendations_for_selfhosted_url_shorter)
 - RSS feed: $source
 - date published: 2025-01-23T11:42:34+00:00

<!-- SC_OFF --><div class="md"><p>Title says it all. What do people use? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/devra11"> /u/devra11 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i81hz0/recommendations_for_selfhosted_url_shorter/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i81hz0/recommendations_for_selfhosted_url_shorter/">[comments]</a></span>

## PSA: Keep it simple
 - [https://www.reddit.com/r/selfhosted/comments/1i818o2/psa_keep_it_simple](https://www.reddit.com/r/selfhosted/comments/1i818o2/psa_keep_it_simple)
 - RSS feed: $source
 - date published: 2025-01-23T11:25:20+00:00

<!-- SC_OFF --><div class="md"><p>This is a reminder to really think about whoch problem you exactly want to solve and what the easiest way to do so is before sinking hours into a project that eventually runs mediocre at best. </p> <p>When I was looking into a NVR that can be somewhat securely accessed from the outside (for one singular indoor Camera), I read tons of posts and eventually tried a few solutions such as Frigate, Shinobi, AgentDVR etc in combination with Home Assistant. I settled with Frigate, Home Assistant and quickly realized that I needed Mosquitto as a mqtt broker. Integrating all of that on my existing VM and making it work (looking at you, HACS) took some time and a lot of research, just to eventually run mediocre at best. PTZ controls were lagging and viewing saved footage via HA would have likely cost me another hour of my time at best. I decided to let it sit for a while and after a few weeks looked into a different approach. After a bit of research and thought

## My minecraft bedrock dedicated server ping is high
 - [https://www.reddit.com/r/selfhosted/comments/1i817mq/my_minecraft_bedrock_dedicated_server_ping_is_high](https://www.reddit.com/r/selfhosted/comments/1i817mq/my_minecraft_bedrock_dedicated_server_ping_is_high)
 - RSS feed: $source
 - date published: 2025-01-23T11:23:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i817mq/my_minecraft_bedrock_dedicated_server_ping_is_high/"> <img src="https://a.thumbs.redditmedia.com/_iTLXxn2CVxRSBzagrqpyTBBjTh1iF7a5KX22vkN3i8.jpg" alt="My minecraft bedrock dedicated server ping is high" title="My minecraft bedrock dedicated server ping is high" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>It switches from 50ms to 8000ms or even more. I will be thankful if someone could help.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Aggravating_Dream768"> /u/Aggravating_Dream768 </a> <br/> <span><a href="https://www.reddit.com/gallery/1i817mq">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i817mq/my_minecraft_bedrock_dedicated_server_ping_is_high/">[comments]</a></span> </td></tr></table>

## What is the best way to run Nextcloud in MacOS on my Mac Mini from 2012?
 - [https://www.reddit.com/r/selfhosted/comments/1i80xf9/what_is_the_best_way_to_run_nextcloud_in_macos_on](https://www.reddit.com/r/selfhosted/comments/1i80xf9/what_is_the_best_way_to_run_nextcloud_in_macos_on)
 - RSS feed: $source
 - date published: 2025-01-23T11:03:22+00:00

<!-- SC_OFF --><div class="md"><ul> <li>Hi everyone 👋</li> </ul> <p>I’m wondering where to start to get Nextcloud on my Mac Mini. I see people are running Nextcloud on their Macs with Ubuntu through a VM and I want to do the same thing as them. So, I’m wondering what are the steps or a great tutorial to get everything configured right step by step. </p> <ul> <li>Relevant Specs</li> </ul> <p>MODEL: LATE 2012 MAC MINI OS: Monterey (Patched with Open Core Legacy Patcher) RAM: 16GB PROCESSOR: Processor: Intel Core i7 (3615QM, 3720QM) (&quot;Ivy Bridge&quot;) STORAGE: SAMSUNG 4TB 860 PRO SSD</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/keyonholman4"> /u/keyonholman4 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i80xf9/what_is_the_best_way_to_run_nextcloud_in_macos_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i80xf9/what_is_the_best_way_to_run_nextcloud_in_macos_on/">[comments]<

## Complete newbie, small image hosting server?
 - [https://www.reddit.com/r/selfhosted/comments/1i80lut/complete_newbie_small_image_hosting_server](https://www.reddit.com/r/selfhosted/comments/1i80lut/complete_newbie_small_image_hosting_server)
 - RSS feed: $source
 - date published: 2025-01-23T10:41:00+00:00

<!-- SC_OFF --><div class="md"><p>Hello there everyone, sorry if this comes across kind of dumb, but as someone who doesn&#39;t really trust any cloud service at all nowadays I&#39;d very much like to learn how I could set up a small server to host my own images to share online (for ex.: on my personal site) and maybe even share with a limited amount of people in the future.</p> <p>Please talk to me like I&#39;m stupid, I am an absolute beginner with these things.<br/> What should I learn first? What hardware do I need?</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Moist_Row9986"> /u/Moist_Row9986 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i80lut/complete_newbie_small_image_hosting_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i80lut/complete_newbie_small_image_hosting_server/">[comments]</a></span>

## Open-Source (and free) CLI for Stacked PRs and Developer Workflow Automation
 - [https://www.reddit.com/r/selfhosted/comments/1i80j6g/opensource_and_free_cli_for_stacked_prs_and](https://www.reddit.com/r/selfhosted/comments/1i80j6g/opensource_and_free_cli_for_stacked_prs_and)
 - RSS feed: $source
 - date published: 2025-01-23T10:35:33+00:00

<!-- SC_OFF --><div class="md"><p>Hey folks, I just wanted to come back to this community that has given us so much love in the past and reintroduce y&#39;all to Aviator and our FOSS CLI utility~</p> <h1>What is Aviator?</h1> <p>Aviator is an open-source developer productivity tool designed to solve some of the most frustrating challenges in modern software development workflows. At its core, Aviator provides a comprehensive set of tools to manage pull requests, continuous integration, and collaborative coding processes.</p> <h1>Key Components of Aviator</h1> <ul> <li>1. Stacked PRs CLI <ul> <li>Automate management of interdependent pull requests</li> <li>Create, sync, and merge stacked branches with </li> <li>Reduce manual rebasing and conflict </li> <li>Seamless integration with GitHub </li> </ul></li> <li>2. MergeQueue <ul> <li>Automated PR merging system</li> <li>Protects main branches from broken </li> <li>Validates CI checks automatically</li> <li>Handles semantic conflicts int

## Proxmox not getting IP DHCP or Static
 - [https://www.reddit.com/r/selfhosted/comments/1i80agk/proxmox_not_getting_ip_dhcp_or_static](https://www.reddit.com/r/selfhosted/comments/1i80agk/proxmox_not_getting_ip_dhcp_or_static)
 - RSS feed: $source
 - date published: 2025-01-23T10:17:56+00:00

<!-- SC_OFF --><div class="md"><p>So, I had in the GUI eno1 and vmbr0, the setting of eno1 where emty but vmbr0 had ip of <a href="http://192.168.1.200">192.168.1.200</a> and gateway of <a href="http://192.168.1.1">192.168.1.1</a> (in the gui), I deleted <a href="http://192.168.1.200">192.168.1.200</a> and <a href="http://192.168.1.1">192.168.1.1</a> thinking it will switch to DHCP.</p> <p>And since then I can no longer acces proxmox because is not getting an IP.</p> <p>My proxmox console is not loading, I get &quot;EFI stub: Loaded initrd from Li.....&quot; but it was like that before , I got acces to rpool storage with proxmox iso in debug mode, and the interface file right now is :</p> <p>auto lo </p> <p>iface lo inet loopback </p> <p>iface eno1 inet manual </p> <p>iface vmbr0 inet static </p> <p>address <a href="http://192.168.1.200">192.168.1.200</a> </p> <p>netmask <a href="http://255.255.255.0">255.255.255.0</a> </p> <p>gateway <a href="http://192.168.1.1">192.168.1.1</a> </p>

## SSD + HDD partitioning advise needed
 - [https://www.reddit.com/r/selfhosted/comments/1i80712/ssd_hdd_partitioning_advise_needed](https://www.reddit.com/r/selfhosted/comments/1i80712/ssd_hdd_partitioning_advise_needed)
 - RSS feed: $source
 - date published: 2025-01-23T10:10:44+00:00

<!-- SC_OFF --><div class="md"><p>Recently I&#39;ve got my hands on a very sweet deal for a HP Prodesk 400 G5 with i3-8100 and 16GB of RAM. I&#39;ve upgraded it with 256GB SSD and 3TB Toshiba NAS HDD to make my first &quot;real&quot; home server/NAS (because HDD connected to a router with samba doesn&#39;t count).</p> <p>In planning to use it for Jellyfin server, Nextcloud, some torrent+Radarr and maybe a game server (like Terraria or maybe ARK) on top of it. Which seems pretty common.</p> <p>And while there are lots of videos about making a budget home server, somehow most of them show you how to install Ubuntu and SSH, yet never focus on the damn partitioning.</p> <p>So with my casual Linux desctop experience I&#39;ve initially partitioned SSD to have EFI, / and swap, while whole 3TB HDD is /home partition. Because that&#39;s where I have all my data like movies, pictures and games on desktop Linux.</p> <p>But as soon as I&#39;ve installed CasaOS and Jellyfin server, I&#39;ve found

## Thrifty - A simple monthly income and expanses tracker
 - [https://www.reddit.com/r/selfhosted/comments/1i804pp/thrifty_a_simple_monthly_income_and_expanses](https://www.reddit.com/r/selfhosted/comments/1i804pp/thrifty_a_simple_monthly_income_and_expanses)
 - RSS feed: $source
 - date published: 2025-01-23T10:05:59+00:00

<!-- SC_OFF --><div class="md"><p>I created my first ever app 😅. It&#39;s a simple income and expanses tracker. I don&#39;t wanted to track every single penny or create buckets and saving plans.</p> <p>The app should give a simple overview over the monthly occurring cash flows to give a rough feeling about what&#39;s left in the pocket.</p> <p>I hope some of you may like it or give me a little feedback 😊</p> <p><a href="https://github.com/tiehfood/thrifty">https://github.com/tiehfood/thrifty</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/testheit"> /u/testheit </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i804pp/thrifty_a_simple_monthly_income_and_expanses/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i804pp/thrifty_a_simple_monthly_income_and_expanses/">[comments]</a></span>

## Help with accessing devices in the home network with WireGuard
 - [https://www.reddit.com/r/selfhosted/comments/1i7z2bc/help_with_accessing_devices_in_the_home_network](https://www.reddit.com/r/selfhosted/comments/1i7z2bc/help_with_accessing_devices_in_the_home_network)
 - RSS feed: $source
 - date published: 2025-01-23T08:41:59+00:00

<!-- SC_OFF --><div class="md"><p>Hello community. I’m trying to dip my toes into self hosting with the goal of eventually running immich and paperless ngx. I’m new to this and wrapping my head around the networking basics first and am encountering an issue I can’t fully understand. </p> <p>I have the following setup:</p> <p>Router (FRITZ!Box) &gt; GLinet Flint2 connected via DHCP &gt; all local devices</p> <p>I’m running a WireGuard Server on the Flint 2 router, which actually works well. I can connect to it from other devices (using mobile data for testing) and once I’ve done that I can also reach the FRITZ!Box Web interface. I can not, however, access the Flint Router or any device that is connected to it. I can’t even ping the Flint 2 or the connected local devices. This seems counter intuitive since the WireGuard server runs on the Flint and not on the FRITZ!Box. I could run WireGuard on the FRITZ!Box, but I‘d like to keep Adguard on the Flint filtering my traffic. </p> <p>Any i

## RepoFlow Update: New Features and Improvements Since Launch
 - [https://www.reddit.com/r/selfhosted/comments/1i7yl7l/repoflow_update_new_features_and_improvements](https://www.reddit.com/r/selfhosted/comments/1i7yl7l/repoflow_update_new_features_and_improvements)
 - RSS feed: $source
 - date published: 2025-01-23T08:05:20+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i7yl7l/repoflow_update_new_features_and_improvements/"> <img src="https://a.thumbs.redditmedia.com/7Jseb_hyc2RfSyqG9O06SwFP90T-qXp5Ofc6SNZDJs8.jpg" alt="RepoFlow Update: New Features and Improvements Since Launch" title="RepoFlow Update: New Features and Improvements Since Launch" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>Website</strong>: <a href="https://www.repoflow.io">RepoFlow</a><br/> Docs: <a href="https://docs.repoflow.io">RepoFlow Docs</a></p> <p>Hello everyone </p> <p>I hope it’s okay to share updates from time to time. if not, please let me know!<br/> First, I want to thank everyone who has supported RepoFlow so far. Over 20 of you have requested and received personal-use licenses, and I’m thrilled to see so many people self-hosting it. Your feedback and encouragement have been invaluable! 😊 </p> <p>If you haven’t come across RepoFlow yet, it’s a self-hosted package management platfor

## Music SelfHost
 - [https://www.reddit.com/r/selfhosted/comments/1i7yahp/music_selfhost](https://www.reddit.com/r/selfhosted/comments/1i7yahp/music_selfhost)
 - RSS feed: $source
 - date published: 2025-01-23T07:42:36+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking for a music self-hosting service with an Android app. I&#39;m trying to escape the navidrome. Jellyfin, emby or plex don&#39;t interest me. I wanted one that I could edit the artist&#39;s image or that would automatically download from a service (lastfm).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DorgasDoIndaia"> /u/DorgasDoIndaia </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7yahp/music_selfhost/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7yahp/music_selfhost/">[comments]</a></span>

## Ryot v8: Now with Youtube Music integration and much more!
 - [https://www.reddit.com/r/selfhosted/comments/1i7y7t3/ryot_v8_now_with_youtube_music_integration_and](https://www.reddit.com/r/selfhosted/comments/1i7y7t3/ryot_v8_now_with_youtube_music_integration_and)
 - RSS feed: $source
 - date published: 2025-01-23T07:36:37+00:00

<!-- SC_OFF --><div class="md"><p>New year came a bit late for Ryot since I was stuck with a few upstream dependencies. Nevertheless, Happy New Year everyone!</p> <p>Ryot v8 is now live with a lot of cool updates!</p> <ul> <li>Import data from Anilist.</li> <li>Integration with Youtube Music [PRO].</li> <li>Workouts can now be paused and have a new stopwatch feature.</li> <li>You can create workout templates with empty exercises.</li> <li>You will now get frontend notifications when an item has been in progress for too long [PRO].</li> <li>The import logic has been rewritten to prevent rate limiting bugs. Also an &quot;Estimated Time to Finish&quot; an import will be displayed.</li> <li>New <a href="https://hardcover.app">Hardcover</a> integration for book tracking.</li> <li>Media list pages now have a date filter [PRO].</li> <li>ISBN matching has been improved, so integrations/imports from Goodreads, Audiobookshelf etc should be much more accurate.</li> <li>A lot of bugfixes...</li>

## [Help needed] I'm struggling go containerize NextCloud and need help.
 - [https://www.reddit.com/r/selfhosted/comments/1i7xt0b/help_needed_im_struggling_go_containerize](https://www.reddit.com/r/selfhosted/comments/1i7xt0b/help_needed_im_struggling_go_containerize)
 - RSS feed: $source
 - date published: 2025-01-23T07:05:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to get NextCloud to run on my Synology NAS for the past few days, and I&#39;m at my wit&#39;s end. I really need help, and everywhere else I&#39;ve asked yet has either given no response or advice that didn&#39;t prove useful.</p> <p>All I want is to run NextCloud so I can run NextPush in it. I don&#39;t even know what else NextCloud is good for — I&#39;m just trying to self-host a UnifiedPush distributor.</p> <p>I&#39;ve tried both MariusHosting guides, and installing via an image in Container Manager, and trying to build NextCloud AIO via the task scheduler. I&#39;ve had varying levels of success with each, but never enough.</p> <p>I will expose it via Nginx Proxy Manager being run on another device. I just need NextCloud to be exposed at &lt;My NAS IP&gt;:&lt;Some Port&gt;</p> <p>My NAS is a Synology DS423. It&#39;s ARMv8 with 2GB of RAM.</p> <p>Help would be much appreciated. I&#39;m making this post right before going to bed

## UPS battery packs
 - [https://www.reddit.com/r/selfhosted/comments/1i7xoln/ups_battery_packs](https://www.reddit.com/r/selfhosted/comments/1i7xoln/ups_battery_packs)
 - RSS feed: $source
 - date published: 2025-01-23T06:56:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i7xoln/ups_battery_packs/"> <img src="https://preview.redd.it/kuxam4fpyoee1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=2289fef8ac8e52ff29c73bcf50646157bc6a0cbd" alt="UPS battery packs" title="UPS battery packs" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Has anyone successfully replaced the generic lead-acid batteries that are inside the sealed battery packs certain UPSs use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rarely_late56"> /u/rarely_late56 </a> <br/> <span><a href="https://i.redd.it/kuxam4fpyoee1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7xoln/ups_battery_packs/">[comments]</a></span> </td></tr></table>

## 6 bay NAS with an i7 5675c
 - [https://www.reddit.com/r/selfhosted/comments/1i7xo8f/6_bay_nas_with_an_i7_5675c](https://www.reddit.com/r/selfhosted/comments/1i7xo8f/6_bay_nas_with_an_i7_5675c)
 - RSS feed: $source
 - date published: 2025-01-23T06:56:01+00:00

<!-- SC_OFF --><div class="md"><p>Will a $65 second hand 6 bay DIY NAS with an i7 5675c, 16gb ramh, h97n-wifi with windows server 2019 ok for a main low power home file server and 1080p streaming? The 3.3-3.7ghz 5675c has 65w TDP with a configurable 37w TDP</p> <p>I have also almost decade old QNAP and noisy Asus NAS&#39; with slow 1.8-2.5ghz dual celeron n3060 processors and I plan these to be the backups or sell them.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/djtron99"> /u/djtron99 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7xo8f/6_bay_nas_with_an_i7_5675c/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7xo8f/6_bay_nas_with_an_i7_5675c/">[comments]</a></span>

## I open sourced my project to analyze your YEARS of Apple Health data with A.I.
 - [https://www.reddit.com/r/selfhosted/comments/1i7wgqo/i_open_sourced_my_project_to_analyze_your_years](https://www.reddit.com/r/selfhosted/comments/1i7wgqo/i_open_sourced_my_project_to_analyze_your_years)
 - RSS feed: $source
 - date published: 2025-01-23T05:34:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i7wgqo/i_open_sourced_my_project_to_analyze_your_years/"> <img src="https://external-preview.redd.it/o6O0KpWd7hdMkRjkzCi7Q4jRhO9FUgWICfZgm8yZPGI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d7af43b6be18adb2719fc5fd9f18ccefb172364d" alt="I open sourced my project to analyze your YEARS of Apple Health data with A.I." title="I open sourced my project to analyze your YEARS of Apple Health data with A.I." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;ve been a lurker and self host homebox, actualbudget and n8n. So I wanted to give back. Not a full blown docker app yet but here it is.</p> <p>I was playing around and found out that you can export all your Apple health data. I&#39;ve been wearing an Apple watch for 8 years and whoop for 3 years. I always check my day to day and week to week stats but I never looked at the data over the years.</p> <p>I exported my data and there was 989MB of data! So I nee

## Trakt.tv just became useless without a subscription. Any self-hosted solutions out there?
 - [https://www.reddit.com/r/selfhosted/comments/1i7vssl/trakttv_just_became_useless_without_a](https://www.reddit.com/r/selfhosted/comments/1i7vssl/trakttv_just_became_useless_without_a)
 - RSS feed: $source
 - date published: 2025-01-23T04:53:45+00:00

<!-- SC_OFF --><div class="md"><p>Trakt.tv has long been my favorite place for tracking TV and movies that I have on Plex, and more importantly, what I don&#39;t have. Recently, they just put limits of 100 on all types of lists and even your own collection. What&#39;s more, you can&#39;t create new lists to just have like 20 lists be your collection. This makes the core functionality basically useless. Of course you could subscribe, but that is basically the price of a streaming service and who wants another subscription?</p> <p>So, I&#39;m asking, does anyone have a good solution that is self hosted? It would also be a high priority feature if it would help me find things that I&#39;m missing. That means if I want to get all top 250 IMDB movies, I can see which ones I already have. Or if I&#39;m trying to get every Tom Hanks movie, it will show me the ones I&#39;m missing.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Unsungghost"> /u/Unsungg

## Brand new to self hosting, where to start?
 - [https://www.reddit.com/r/selfhosted/comments/1i7v1v5/brand_new_to_self_hosting_where_to_start](https://www.reddit.com/r/selfhosted/comments/1i7v1v5/brand_new_to_self_hosting_where_to_start)
 - RSS feed: $source
 - date published: 2025-01-23T04:10:31+00:00

<!-- SC_OFF --><div class="md"><p>I am a complete newbie when it comes to self hosting, but have been doing some research over the last couple days. I am planning on building a home server and NAS for the house. I would like some help on recommendations for guides and hardware.</p> <p>I have built all of my own PC&#39;s but have only ever used windows. For work I deal with an enterprise scheduler, and am very familiar with powershell, and somewhat familiar with writing UNIX code for our unix servers, though have never directly worked in the command line.</p> <p>The general outline I have so far is to use proxmox to split the NAS and the Servers. I am planning on TrueNAS Scale in one VM, for a NAS everyone in the house can access.</p> <p>Not sure what OS to run the dockerized server stuff on (never used docker either) but I am pretty sure that VM will be using Debian from my research? I am planning on running *Arr&#39;s (have these running my PC, but that rig was not made with UP in m

## Building first Server and parts not compatible.
 - [https://www.reddit.com/r/selfhosted/comments/1i7twzj/building_first_server_and_parts_not_compatible](https://www.reddit.com/r/selfhosted/comments/1i7twzj/building_first_server_and_parts_not_compatible)
 - RSS feed: $source
 - date published: 2025-01-23T03:09:45+00:00

<!-- SC_OFF --><div class="md"><p>I finally bought all the parts to build my own server, but despite noctus saying that their fan was compatible, it turns out that it is not. I’m trying to figure out where exactly I can find a fan that is compatible, but I am having trouble.</p> <p>Motherboard: BKHD 2011-mATX Motherboard - 4x2.5GE 6xDDR4 Up to 384G 10xSATA</p> <p>Chip: E5 2698V4 Original Intel Xeon</p> <p>The chip and motherboard are great but I need a cooler for the CPU and cannot find anything that says it’s compatible. Any thoughts? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jessetechno"> /u/jessetechno </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7twzj/building_first_server_and_parts_not_compatible/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7twzj/building_first_server_and_parts_not_compatible/">[comments]</a></span>

## What kinds of self hosted services would be unsuitable for a Synology NAS?
 - [https://www.reddit.com/r/selfhosted/comments/1i7t8aa/what_kinds_of_self_hosted_services_would_be](https://www.reddit.com/r/selfhosted/comments/1i7t8aa/what_kinds_of_self_hosted_services_would_be)
 - RSS feed: $source
 - date published: 2025-01-23T02:34:51+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m in the market for a Synology NAS, but I&#39;m wondering if anyone knows the extent of its utility as a home server. What kinds of things make sense to run directly on it, connected directly to the storage? What types of services would bog it down or use too many resources?</p> <p>Apologies if the question is vague, I&#39;m just interested in learning how people distribute self hosted services across their servers, and if some things are more efficient to run directly on the NAS itself.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sorry-Attitude4154"> /u/Sorry-Attitude4154 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7t8aa/what_kinds_of_self_hosted_services_would_be/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7t8aa/what_kinds_of_self_hosted_services_would_be/">[comments]</a></span>

## Confession time, what's the jankiest workaround you've implemented because you are lazy (or don't have time right now)?
 - [https://www.reddit.com/r/selfhosted/comments/1i7suwe/confession_time_whats_the_jankiest_workaround](https://www.reddit.com/r/selfhosted/comments/1i7suwe/confession_time_whats_the_jankiest_workaround)
 - RSS feed: $source
 - date published: 2025-01-23T02:15:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll go first, so with my <code>*arr</code>, <code>qbit</code> and <code>jellyfin</code> setup I have a problem with media duplication, apparently it is some issue with hardlinks and my current configuration. I have not had the time to sit down and reconfigure everything, so instead, I wrote a small script to do a near match dedupe, it&#39;s been running for a good 6 months or so without any issues.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Master-Variety3841"> /u/Master-Variety3841 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7suwe/confession_time_whats_the_jankiest_workaround/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7suwe/confession_time_whats_the_jankiest_workaround/">[comments]</a></span>

## Suggestions for limited or tunneled public access to existing private services.
 - [https://www.reddit.com/r/selfhosted/comments/1i7sp42/suggestions_for_limited_or_tunneled_public_access](https://www.reddit.com/r/selfhosted/comments/1i7sp42/suggestions_for_limited_or_tunneled_public_access)
 - RSS feed: $source
 - date published: 2025-01-23T02:07:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not really sure what to title this, but here is my situation and my goals. I am reasonably technical and fluent in terms of hosting, but not with third-party proxies.</p> <p>Situation:</p> <ul> <li>I have a number of HTTP services I selfhost across several hosts.</li> <li>All of these are currently available via HTTP via their local addresses and nonstandard ports</li> <li>All of these are also available via HTTPS through single NGINX proxy service keeping all proxy config in one place.</li> <li>HTTPS is provided by a single Lets Encrypt wildcard certificate. As nothing is currently publicly accessible, this makes it easy to obtain and renew that cert at a single point, but use it across the entire network.</li> <li>I have both an internal and external DNS service that is &quot;authoritative&quot; for a custom subdomain. This allows me to split-horizon the DNS and provide different addresses internally and externally.</li> </ul> <p>Goal:</p> 

## Advice for setting up a family photo server
 - [https://www.reddit.com/r/selfhosted/comments/1i7s7f4/advice_for_setting_up_a_family_photo_server](https://www.reddit.com/r/selfhosted/comments/1i7s7f4/advice_for_setting_up_a_family_photo_server)
 - RSS feed: $source
 - date published: 2025-01-23T01:43:43+00:00

<!-- SC_OFF --><div class="md"><p>Sorry in advance for the long post! I’m planning to set up a family server for storing and viewing all our photos, but I’m pretty new to home servers and feeling a bit lost after doing some research. My primary goals are:</p> <ol> <li>Allow all family members to upload their photos to a shared server</li> <li>Organize photos and remove duplicates</li> <li>Make photos searchable by categories</li> <li>Automate sorting newly uploaded photos</li> </ol> <p>For the first two steps, my idea is to create a NAS server with folders for each family member based on who took the photos. I&#39;d have two subfolders within their folders: &quot;unorganized&quot; where they&#39;d upload their photos, and &quot;organized.&quot; I would then remove all duplicates between our photos, rename old or apple photos to the android name structure based on date, and then sort them in subfolders based on year.</p> <p>Based on my research, Czkawka seems to be best for finding du

## Need Guidance for Self Hosting Mini PC
 - [https://www.reddit.com/r/selfhosted/comments/1i7rwm0/need_guidance_for_self_hosting_mini_pc](https://www.reddit.com/r/selfhosted/comments/1i7rwm0/need_guidance_for_self_hosting_mini_pc)
 - RSS feed: $source
 - date published: 2025-01-23T01:29:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello Community of Self Hosting,</p> <p>I have a linux server that I host at home however I want to make it so I can access it externally outside of my network without doing port forwarding. I have looked into VPN / other documentation regarding the idea of using another ip but I have found myself lost and been needing more information regarding what I am doing.</p> <p>If possible, please give me guidance through these confusing times. </p> <p>Thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Viewer23"> /u/Viewer23 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7rwm0/need_guidance_for_self_hosting_mini_pc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7rwm0/need_guidance_for_self_hosting_mini_pc/">[comments]</a></span>

## Light Weight Fediverse Server?
 - [https://www.reddit.com/r/selfhosted/comments/1i7r2sh/light_weight_fediverse_server](https://www.reddit.com/r/selfhosted/comments/1i7r2sh/light_weight_fediverse_server)
 - RSS feed: $source
 - date published: 2025-01-23T00:49:10+00:00

<!-- SC_OFF --><div class="md"><p>As the title suggests, what&#39;s the lightest weight Fediverse server that has an android App?</p> <p>I used Pleroma for years, even wrote the FreeBSD installation guide, but wanted to see what other options there were.</p> <p>Mastodon is out due to its heavy footprint...</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FarhanYusufzai"> /u/FarhanYusufzai </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7r2sh/light_weight_fediverse_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7r2sh/light_weight_fediverse_server/">[comments]</a></span>

## Tandoor keeps exiting with code 3 exit error after booting up the containers. Any ideas what could be the cause?
 - [https://www.reddit.com/r/selfhosted/comments/1i7qvnf/tandoor_keeps_exiting_with_code_3_exit_error](https://www.reddit.com/r/selfhosted/comments/1i7qvnf/tandoor_keeps_exiting_with_code_3_exit_error)
 - RSS feed: $source
 - date published: 2025-01-23T00:39:51+00:00

<!-- SC_OFF --><div class="md"><p>This is the log on portainer.</p> <p>ImportError: Error loading shared library libssl.so.1.1: No such file or directory (needed by /opt/recipes/venv/lib/python3.12/site-packages/cryptography/hazmat/bindings/_rust.abi3.so)</p> <p>[2025-01-23 01:33:53 +0100] [15] [INFO] Worker exiting (pid: 15)</p> <p>[2025-01-23 00:33:53 +0000] [1] [ERROR] Worker (pid:13) exited with code 3</p> <p>[2025-01-23 00:33:53 +0000] [1] [ERROR] Worker (pid:14) was sent SIGTERM!</p> <p>[2025-01-23 00:33:53 +0000] [1] [ERROR] Worker (pid:15) was sent SIGTERM!</p> <p>[2025-01-23 00:33:53 +0000] [1] [ERROR] Shutting down: Master</p> <p>[2025-01-23 00:33:53 +0000] [1] [ERROR] Reason: Worker failed to boot.</p> <p>I&#39;m not too versed in self hosting. Tandoor was working for a long time but stopped importing lately for some reason so I recreated the containers and it stopped working completely. Then I deleted them completely and remade the containers and it&#39;s getting the same

## Help! My mom is pissed at me because she forgot her Vaultwarden password
 - [https://www.reddit.com/r/selfhosted/comments/1i7qdaz/help_my_mom_is_pissed_at_me_because_she_forgot](https://www.reddit.com/r/selfhosted/comments/1i7qdaz/help_my_mom_is_pissed_at_me_because_she_forgot)
 - RSS feed: $source
 - date published: 2025-01-23T00:16:12+00:00

<!-- SC_OFF --><div class="md"><p>I setup emergency access for her because I knew this would probably happen. But in the emergency access section, I am unable to send an email to her to start the recovery. I think she might not have confirmed it on the web portal even though I confirmed becoming an emergency contact from my account.</p> <p>Is there anyway I can update the sqlite database <code>emergency_access</code> table to fully enable emergency access?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Bubba8291"> /u/Bubba8291 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7qdaz/help_my_mom_is_pissed_at_me_because_she_forgot/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7qdaz/help_my_mom_is_pissed_at_me_because_she_forgot/">[comments]</a></span>

## ArchiveBox - Open source self-hosted web archiving
 - [https://www.reddit.com/r/selfhosted/comments/1i7q3wv/archivebox_open_source_selfhosted_web_archiving](https://www.reddit.com/r/selfhosted/comments/1i7q3wv/archivebox_open_source_selfhosted_web_archiving)
 - RSS feed: $source
 - date published: 2025-01-23T00:04:24+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Spaduf"> /u/Spaduf </a> <br/> <span><a href="https://archivebox.io/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i7q3wv/archivebox_open_source_selfhosted_web_archiving/">[comments]</a></span>

