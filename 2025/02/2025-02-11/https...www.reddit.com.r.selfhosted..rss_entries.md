# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Is there an easier platform than postfix/dovecot for email?
 - [https://www.reddit.com/r/selfhosted/comments/1inczvz/is_there_an_easier_platform_than_postfixdovecot](https://www.reddit.com/r/selfhosted/comments/1inczvz/is_there_an_easier_platform_than_postfixdovecot)
 - RSS feed: $source
 - date published: 2025-02-11T23:38:05+00:00

<!-- SC_OFF --><div class="md"><p>Setting up email always pisses me off, it&#39;s so overly complicated for nothing and always have to fight it. For what should be a simple protocol it really shouldn&#39;t be this complicated. </p> <p>Is there something that is easier to setup with easier to understand config? Especially when it comes to mail routing, authentication for both IMAP/POP and SMTP etc. It&#39;s always a shit show trying to get all that to work properly. You get one mail box to work, then for whatever reason the next won&#39;t work despite it being setup the same. It&#39;s always a gamble. </p> <p>I&#39;m in process of setting up a new local mail server, for whatever reason it just refuses the password for 1 mailbox when it&#39;s exactly setup the same as all the others that work, and it&#39;s just driving me nuts. It shouldn&#39;t be this complicated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RedSquirrelFtw"> /u/RedSquirrelFtw 

## Traggo - Tags not "sticking" to time sheet entry
 - [https://www.reddit.com/r/selfhosted/comments/1inci99/traggo_tags_not_sticking_to_time_sheet_entry](https://www.reddit.com/r/selfhosted/comments/1inci99/traggo_tags_not_sticking_to_time_sheet_entry)
 - RSS feed: $source
 - date published: 2025-02-11T23:16:07+00:00

<!-- SC_OFF --><div class="md"><p>I installed Traggo and love it so far for its simplicity and not being bloated. Thank you <a href="/u/jmattheis">u/jmattheis</a> for this!</p> <p>I am encountering some weird behavior. Whenever I try to add a tag to my time sheet, either on the list view of the calendar view, it does not save the tag. When I browse to a different view and come back, all the tags are gone, making it really hard to keep track of my time.</p> <p>Tags have been created on the &quot;Tags&quot; page and are visible there.</p> <p>Anyone else encountered this situation and might have a solution?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RRabbit10"> /u/RRabbit10 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1inci99/traggo_tags_not_sticking_to_time_sheet_entry/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1inci99/traggo_tags_not_sticking_to_time_sheet_entry/">[comments

## Vaultwarden + certbot
 - [https://www.reddit.com/r/selfhosted/comments/1inbvlc/vaultwarden_certbot](https://www.reddit.com/r/selfhosted/comments/1inbvlc/vaultwarden_certbot)
 - RSS feed: $source
 - date published: 2025-02-11T22:48:04+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I have a Proxmox server with a LXC container with Vaultwarden running on it. It was installed via the script from Helper Scripts. Now I want to install nginx Reverse Proxy and certbot on that same LXC Container so I can get my SSL certificate for Vaultwarden. Nginx has been installed, site file has been created:</p> <pre><code>server { #listen 80; server_name domain.ltd; location /.well-known/acme-challenge/ { root /var/www/html; } location / { proxy_pass http://127.0.0.1:8000; proxy_set_header Host $host; proxy_set_header X-Real-IP $remote_addr; proxy_set_header X-Forwarded-For $proxy_add_x_forwarded_for; proxy_set_header X-Forwarded-Proto $scheme; } } </code></pre> <p>On my firewall I forwarded port 80 and 443 to the IP address of that LXC Container. When I go to <a href="http://domain.ltd">http://domain.ltd</a> I get the login page of Vaultwarden.</p> <p>But when I try to generate my SSL certificate with: certbot certonly --webroot -w /

## ToolJet.ai relaunched as a self-hosted IDE to build AI-powered internal apps & agents using prompts. New pricing - unlimited end users. Deploy using Docker, k8s, AWS AMI & more! AI-first alternative to Retool, Power Apps & OutSystems.
 - [https://www.reddit.com/r/selfhosted/comments/1inapz9/tooljetai_relaunched_as_a_selfhosted_ide_to_build](https://www.reddit.com/r/selfhosted/comments/1inapz9/tooljetai_relaunched_as_a_selfhosted_ide_to_build)
 - RSS feed: $source
 - date published: 2025-02-11T21:59:57+00:00

<!-- SC_OFF --><div class="md"><p>Founder here, We just launched a new version of ToolJet that lets you <strong>describe an app in plain English, and AI generates the UI, database, and logic for you.</strong> No dragging, no complex setup—just type what you need, and it’s built.</p> <p>TLDR; </p> <p>Demo: <a href="https://www.youtube.com/watch?v=EiqZJufcNl8">https://www.youtube.com/watch?v=EiqZJufcNl8</a></p> <p>Website: <a href="https://tooljet.ai">https://tooljet.ai</a> </p> <p>Setup docs: <a href="https://docs.tooljet.ai/docs/setup/">https://docs.tooljet.ai/docs/setup/</a></p> <h1>How it works</h1> <ul> <li><strong>Describe your app in plain English:</strong> <em>“I need a simple CRM that lets users add contacts, log calls, and see a dashboard of activity.”</em></li> <li><strong>AI generates a Product Requirements Document (PRD):</strong> It drafts a spec for your app’s features/screens to make sure we’re on the same page. This even includes data models.</li> <li><strong>It builds

## ToolJet - Self-hosted low-code framework relaunches as AI-native platform to build internal tools using natural language. Deploy using helm charts, Docker, Heroku, Google Cloud Run and AWS EC2 using AMI. Open-source low-code application builder. AI-first alternative to Retool & Power Apps.
 - [https://www.reddit.com/r/selfhosted/comments/1ina0rc/tooljet_selfhosted_lowcode_framework_relaunches](https://www.reddit.com/r/selfhosted/comments/1ina0rc/tooljet_selfhosted_lowcode_framework_relaunches)
 - RSS feed: $source
 - date published: 2025-02-11T21:30:33+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/navaneethpk"> /u/navaneethpk </a> <br/> <span><a href="https://tooljet.ai">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ina0rc/tooljet_selfhosted_lowcode_framework_relaunches/">[comments]</a></span>

## Endurain: A Self-Hosted Fitness Activity Tracker - v0.8.0 Update 🎉
 - [https://www.reddit.com/r/selfhosted/comments/1in9pz4/endurain_a_selfhosted_fitness_activity_tracker](https://www.reddit.com/r/selfhosted/comments/1in9pz4/endurain_a_selfhosted_fitness_activity_tracker)
 - RSS feed: $source
 - date published: 2025-02-11T21:18:16+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! Excited to share another update for <strong>Endurain</strong>, the self-hosted fitness activity tracker. Thanks to all of you for the feedback and support—it’s been amazing seeing the project grow!</p> <p>This update, <strong>v0.8.0</strong>, brings some much-requested features and improvements. Here are the highlights:</p> <h1>🚀 New Features</h1> <ul> <li><strong>Imperial units support</strong> – Now you can choose between metric and imperial units.</li> <li><strong>Dedicated search view</strong> – A streamlined way to search your activities, gear, and users.</li> <li><strong>Updated gear list view</strong> – Improved layout with easier management options.</li> <li><strong>Strava token handling improvements</strong> – Expired tokens should now be correctly managed, and you can relink Strava if needed.</li> <li><strong>Top 3 activities</strong> – See your top 3 activity types by distance.</li> <li><strong>Additional form validations</st

## Tandoor How do I add a custom filter? 'List is empty' need help 😢!
 - [https://www.reddit.com/r/selfhosted/comments/1in9cro/tandoor_how_do_i_add_a_custom_filter_list_is](https://www.reddit.com/r/selfhosted/comments/1in9cro/tandoor_how_do_i_add_a_custom_filter_list_is)
 - RSS feed: $source
 - date published: 2025-02-11T21:03:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1in9cro/tandoor_how_do_i_add_a_custom_filter_list_is/"> <img src="https://preview.redd.it/komm8h78qkie1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=4b8737456e7c582a30cf221cb88fffa3001407cf" alt="Tandoor How do I add a custom filter? 'List is empty' need help 😢!" title="Tandoor How do I add a custom filter? 'List is empty' need help 😢!" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Loewe_2020"> /u/Loewe_2020 </a> <br/> <span><a href="https://i.redd.it/komm8h78qkie1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in9cro/tandoor_how_do_i_add_a_custom_filter_list_is/">[comments]</a></span> </td></tr></table>

## beginner-friendly install of local AI?
 - [https://www.reddit.com/r/selfhosted/comments/1in8gr9/beginnerfriendly_install_of_local_ai](https://www.reddit.com/r/selfhosted/comments/1in8gr9/beginnerfriendly_install_of_local_ai)
 - RSS feed: $source
 - date published: 2025-02-11T20:27:01+00:00

<!-- SC_OFF --><div class="md"><p>Is there a way I can install a local ai on my Windows PC or Macbook Air and connect it to <a href="https://github.com/clusterzx/paperless-ai">paperless-ai</a> for paperless-ngx to get ai-generated titles and tags?</p> <p>I already have paperless-ai up and running on my Raspberry Pi 4. </p> <p>I want to keep it local because a lot of my documents have sensitive information like medical records.</p> <p>Was hoping if someone has any beginner-friendly guides they can recommend. Thank you.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dungeon_Crawler_Carl"> /u/Dungeon_Crawler_Carl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in8gr9/beginnerfriendly_install_of_local_ai/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in8gr9/beginnerfriendly_install_of_local_ai/">[comments]</a></span>

## rclone, gocryptfs with unison. Does my setup make sense?
 - [https://www.reddit.com/r/selfhosted/comments/1in8as6/rclone_gocryptfs_with_unison_does_my_setup_make](https://www.reddit.com/r/selfhosted/comments/1in8as6/rclone_gocryptfs_with_unison_does_my_setup_make)
 - RSS feed: $source
 - date published: 2025-02-11T20:20:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1in8as6/rclone_gocryptfs_with_unison_does_my_setup_make/"> <img src="https://b.thumbs.redditmedia.com/zHL7Akp5kSMjKJ4q5D-53ZW8bFUmDARhShmRLK68xxo.jpg" alt="rclone, gocryptfs with unison. Does my setup make sense?" title="rclone, gocryptfs with unison. Does my setup make sense?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>does this setup make sense?</p> <p><a href="https://preview.redd.it/icib8av6jkie1.png?width=1080&amp;format=png&amp;auto=webp&amp;s=4bf8f12c024e0ae11fb04c5bd8713a0c4d0defd9">https://preview.redd.it/icib8av6jkie1.png?width=1080&amp;format=png&amp;auto=webp&amp;s=4bf8f12c024e0ae11fb04c5bd8713a0c4d0defd9</a></p> <p>---<br/> Also, on startup, through systemd with dependencies, i&#39;m automating the following in this particular order:</p> <ol> <li>Mount the plain directory to ram.</li> <li>Mount the gocryptfs filesystem.</li> <li>Mount the remote gdrive.</li> <li>Activate unison to sync the go

## Guacamole vs. XRDP?
 - [https://www.reddit.com/r/selfhosted/comments/1in87qz/guacamole_vs_xrdp](https://www.reddit.com/r/selfhosted/comments/1in87qz/guacamole_vs_xrdp)
 - RSS feed: $source
 - date published: 2025-02-11T20:16:31+00:00

<!-- SC_OFF --><div class="md"><p>This may be a silly question, but is there any reason I should hassle with Guac over XRDP? Yeah, it’s slow and is by no means a replacement for physical access, however, I don’t see any added benefits UNLESS Guac is able to run 4k@60hz connection with almost no latency.</p> <p>Any insight would be appreciated. Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-ManWhat"> /u/-ManWhat </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in87qz/guacamole_vs_xrdp/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in87qz/guacamole_vs_xrdp/">[comments]</a></span>

## Running Docker containers unprivileged/rootless - am I doing something wrong or is it not feasible for most containers?
 - [https://www.reddit.com/r/selfhosted/comments/1in86fj/running_docker_containers_unprivilegedrootless_am](https://www.reddit.com/r/selfhosted/comments/1in86fj/running_docker_containers_unprivilegedrootless_am)
 - RSS feed: $source
 - date published: 2025-02-11T20:14:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>as a selfhosting beginner I checked the <a href="https://cheatsheetseries.owasp.org/cheatsheets/Docker_Security_Cheat_Sheet.html">Docker Security Cheat Sheet</a>. I heard that Docker runs all containers as root by default and it&#39;s better to run the container with an unprivileged user via the <code>-u</code> option (rule #2 of the cheat sheet). However when I checked installation guides of several Docker images that are popular around here (not talking about those that obviously need root privileges), the vast majority does not mention that you can use this option. I&#39;ve even tried running a couple of them as an unprivileged user but that usually resulted in various errors. The closest alternative I&#39;ve seen is being able to set a user via PUID/PGID env variables but if I understand it correctly the <code>-u</code> option is superior because with the env variables the container still starts as root and drops privileges later wher

## Self Hosted NVR Solution
 - [https://www.reddit.com/r/selfhosted/comments/1in5lyu/self_hosted_nvr_solution](https://www.reddit.com/r/selfhosted/comments/1in5lyu/self_hosted_nvr_solution)
 - RSS feed: $source
 - date published: 2025-02-11T18:31:38+00:00

<!-- SC_OFF --><div class="md"><p>Hey Everybody,</p> <p>I have been using Motioneye OS as my self hosted NVR at home, but as many of you may know MEOS is no longer supported by the developer. As such I have been looking into a replacement NVR solution for my home security cameras. Ideally I would like the solution to be open source, have notifications, and possibly have built in remote access support so that I can view the cameras from my phone when I am away from home. I have looked into mainly Shinobi and Frigate as possible options, but wanted to get the opinion of this subreddit.</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PrettyDumbITGuy_87"> /u/PrettyDumbITGuy_87 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5lyu/self_hosted_nvr_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5lyu/self_hosted_nvr_solution/">[comments]</a></span>

## Self hosted appreciation
 - [https://www.reddit.com/r/selfhosted/comments/1in5lfs/self_hosted_appreciation](https://www.reddit.com/r/selfhosted/comments/1in5lfs/self_hosted_appreciation)
 - RSS feed: $source
 - date published: 2025-02-11T18:31:01+00:00

<!-- SC_OFF --><div class="md"><p>I started my journey into self hosting out of fear. 6 months later and while that fear is not exactly gone. I am driven far more by my passion to learn, experiment, grow my skills and just have fun with silly projects. </p> <p>I&#39;m so grateful for communities like this and so many more I&#39;ve found while delving into the world of self hosting. </p> <p>That&#39;s it. That&#39;s the post. Thank you to everyone who is forever curious and happy to share their wealth of knowledge with others. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AyoJD0123"> /u/AyoJD0123 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5lfs/self_hosted_appreciation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5lfs/self_hosted_appreciation/">[comments]</a></span>

## What are my options if I don’t trust tailscale?
 - [https://www.reddit.com/r/selfhosted/comments/1in5e0p/what_are_my_options_if_i_dont_trust_tailscale](https://www.reddit.com/r/selfhosted/comments/1in5e0p/what_are_my_options_if_i_dont_trust_tailscale)
 - RSS feed: $source
 - date published: 2025-02-11T18:22:29+00:00

<!-- SC_OFF --><div class="md"><p>I know the first thing you will ask is why I don’t trust tailscale. I don’t have any more specific insights than you all do. Let’s just say that hypothetically I don’t trust them. Are there any reliable open source options? I have heard of headscale. If I want to selfhost something like that on a VPS, what are your most trusted and reliable VPS services?</p> <p>I am just trying to base my happiness on things I can control. Any advice is highly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Webfarer"> /u/Webfarer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5e0p/what_are_my_options_if_i_dont_trust_tailscale/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in5e0p/what_are_my_options_if_i_dont_trust_tailscale/">[comments]</a></span>

## Need help with VPN service
 - [https://www.reddit.com/r/selfhosted/comments/1in5d9n/need_help_with_vpn_service](https://www.reddit.com/r/selfhosted/comments/1in5d9n/need_help_with_vpn_service)
 - RSS feed: $source
 - date published: 2025-02-11T18:21:40+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, I have a computer I&#39;m building to be a server, I want it to run a couple game servers, jellyfin, and have it be a storage server.</p> <p>As of now I do not have access to my local network so I cannot port forward or set static ips. </p> <p>I was looking into VPN services like tailscale, zrok, and ngrok. </p> <p>My problem with tailscale is that from my understanding, you need to have an authentication app on each device you want to have the IP. I don&#39;t want to bother with this so I was looking at ngrok.</p> <p>I have used the free version of ngrok before but only running one service so I wanted to know if the personal paid plan allows for more than one service to be accessed. </p> <p>I do not know anything of zrok other than it is open source but I do not know if they allow multiple services.</p> <p>I am willing to try other services if they offer better pricing and/or services.</p> <p>Thank you for your time.</p> </div><!-- SC_ON --

## What OS and raid should I go with?
 - [https://www.reddit.com/r/selfhosted/comments/1in5bfd/what_os_and_raid_should_i_go_with](https://www.reddit.com/r/selfhosted/comments/1in5bfd/what_os_and_raid_should_i_go_with)
 - RSS feed: $source
 - date published: 2025-02-11T18:19:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Im sorry if this isn&#39;t the right place to ask this. I&#39;m running a server atm using proxmox as the OS. Im gonna be changing my use case for it and want to get some opinions on what OS and Raid to run. I&#39;m debating between continuing using proxmox, going with undraid or trunas. Open to other suggestions as well. Machine will be used for docker containers, including Plex with GPU passthru, a NAS for media storage and other things as well as maybe a VM or 2 for OS testing. What OS is recommended?</p> <p>As for the raid configuration, machine is running 4 18tb HDD&#39;s. Want the ability to expand in the future if possible but not necessarily important atm. Not using ECC ram. Running ddr5. Should also add, have 2 1tb nvme drives. 1 will be run as a cache and the other for Dockers and vm&#39;s.</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chaoseater423"> /u/Chaoseater423 </a>

## Audio-only livestreaming to Jellyfin, other places
 - [https://www.reddit.com/r/selfhosted/comments/1in4ja6/audioonly_livestreaming_to_jellyfin_other_places](https://www.reddit.com/r/selfhosted/comments/1in4ja6/audioonly_livestreaming_to_jellyfin_other_places)
 - RSS feed: $source
 - date published: 2025-02-11T17:48:27+00:00

<!-- SC_OFF --><div class="md"><p>There are nice paid options like <a href="https://mixlr.com/">https://mixlr.com/</a>, spreaker, podbean that can do live podcasting. Anything free and self-hostable? </p> <p>Not for podcasting but for setting up long audio-only livestream sessions that save bandwidth (Jellyfin for example for our audio recordings processes them like videos I believe and probably is using more bandwidth than it should for just audio).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Losconquistadores"> /u/Losconquistadores </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in4ja6/audioonly_livestreaming_to_jellyfin_other_places/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in4ja6/audioonly_livestreaming_to_jellyfin_other_places/">[comments]</a></span>

## DCTS Update v4.9.9 (Discord Alternative)
 - [https://www.reddit.com/r/selfhosted/comments/1in4glr/dcts_update_v499_discord_alternative](https://www.reddit.com/r/selfhosted/comments/1in4glr/dcts_update_v499_discord_alternative)
 - RSS feed: $source
 - date published: 2025-02-11T17:45:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey! This is a follow up post from my old post <a href="https://www.reddit.com/r/selfhosted/comments/1efd0et/discord_alternative_dcts_new_update_3/">here</a>.</p> <p>Basically, DCTS is a chat application i&#39;ve been making for about one year actively now. Its supposed to become a better alternative to discord, guilded, revolt, matrix, etc. When i started my work on it my goal was to make it as easy to use and setup as possible. </p> <ul> <li>For newbies <strong>matrix</strong> can be overwhelming</li> <li><strong>Guilded</strong> was kinda dead and &quot;recently&quot; made it a requirement to use a roblox account, making it even worse. the official staff is as bad as discord from personal experience. It had cool features tho.</li> <li><strong>Discord</strong> can be very restrictive when you think about nitro. Given their business it makes kinda sense, but its still annoying. Lets not get started with their support...</li> <li><strong>Revolt</stro

## Best way to backup docker containers?
 - [https://www.reddit.com/r/selfhosted/comments/1in41k3/best_way_to_backup_docker_containers](https://www.reddit.com/r/selfhosted/comments/1in41k3/best_way_to_backup_docker_containers)
 - RSS feed: $source
 - date published: 2025-02-11T17:28:29+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m not stupid - I backup my docker, but at the moment I&#39;m running dockge in an LXC and backing the whole thing up regularly.</p> <p>I&#39;d like to backup each container individually so that I can restore an individual one incase of a failure.</p> <p>Lots of difference views on the internet so would like to hear yours</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tcoysh"> /u/tcoysh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in41k3/best_way_to_backup_docker_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in41k3/best_way_to_backup_docker_containers/">[comments]</a></span>

## [Question] Discord push notifications?
 - [https://www.reddit.com/r/selfhosted/comments/1in3xlx/question_discord_push_notifications](https://www.reddit.com/r/selfhosted/comments/1in3xlx/question_discord_push_notifications)
 - RSS feed: $source
 - date published: 2025-02-11T17:24:01+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, I am just dipping my toes into the self hosting world. I&#39;d love to be able to set up push notifications (discord for now, but eventually more?) to my device without the need for google play services. Are there any beginner friendly options out there for discord push notifications or any guides you all may be aware of?</p> <p>(Apologies if this has been discussed elsewhere, I tried doing some basic searches beforehand).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Crazywombat8"> /u/Crazywombat8 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in3xlx/question_discord_push_notifications/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in3xlx/question_discord_push_notifications/">[comments]</a></span>

## Does anybody know about self hosted valentines?
 - [https://www.reddit.com/r/selfhosted/comments/1in303n/does_anybody_know_about_self_hosted_valentines](https://www.reddit.com/r/selfhosted/comments/1in303n/does_anybody_know_about_self_hosted_valentines)
 - RSS feed: $source
 - date published: 2025-02-11T16:45:57+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;d like to be able to send a URL to somebody I love. For example I could imagine something where they follow the link and see animated shower of sparks &amp; hearts, maybe a tune, and a love message of some kind. Ideally the path on the URL would point to a message for <strong>them</strong>. I&#39;m thinking something with HTTP that I put a reverse proxy in front of.</p> <p>Or other ideas for a self hosted valentines day?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/purepersistence"> /u/purepersistence </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in303n/does_anybody_know_about_self_hosted_valentines/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in303n/does_anybody_know_about_self_hosted_valentines/">[comments]</a></span>

## Looking for a note+bookmark app
 - [https://www.reddit.com/r/selfhosted/comments/1in2uwf/looking_for_a_notebookmark_app](https://www.reddit.com/r/selfhosted/comments/1in2uwf/looking_for_a_notebookmark_app)
 - RSS feed: $source
 - date published: 2025-02-11T16:39:54+00:00

<!-- SC_OFF --><div class="md"><p>I am desperately looking for a self hosted solution for a note and bookmark app in one. Like a mix between Hoarder and Joplin with all the nice Hoarder features like AI analysis and tagging and the note features like Joplin with the nice organization and text editing options. I tried several systems like Standard Notes (no AI and &quot;Share to&quot; features on Android), AppFlowy (really complicated to setup and was not really able to set it up) and some others. </p> <p>The solution should have an app to be able to use &quot;Share to&quot; on Android like with Hoarder and I need a docket compose setup which is able to be deployed with Portainer. </p> <p>Do you guys have any solution in mind I didn&#39;t find yet?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkAdvertising2801"> /u/OkAdvertising2801 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in2uwf/looking_for_a_notebookmark_app/">

## Help with actual server ssl?
 - [https://www.reddit.com/r/selfhosted/comments/1in2s51/help_with_actual_server_ssl](https://www.reddit.com/r/selfhosted/comments/1in2s51/help_with_actual_server_ssl)
 - RSS feed: $source
 - date published: 2025-02-11T16:36:44+00:00

<!-- SC_OFF --><div class="md"><p>Hey all, hobbyist trying very hard</p> <p>I&#39;m trying to setup an actual server (actual budget) container. What I&#39;m reading is it absolutely need https. I&#39;m accessing all my services with tailscale, but actual server is &quot;initializing connetion to local database&quot; forever, can&#39;t get it to work...</p> <p>I&#39;ve setup ssl with tailscale and am trying to access my container through the domain provided by tailscale (<a href="https://mydomain.xxxx.ts.net:port">https://mydomain.xxxx.ts.net:port</a>), but I get &quot;SSL_ERROR_RX_RECORD_TOO_LONG&quot;, but if I just go to the domain without the port I land on unraid login, which tells me ssl is working properly?</p> <p>I&#39;m at a loss, I don&#39;t even want https to work at this point as I&#39;m only going to acces it through tailscale and never expose anything to the world... </p> <p>Any help please? Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://ww

## How do I get started with a Homeserver?
 - [https://www.reddit.com/r/selfhosted/comments/1in2izp/how_do_i_get_started_with_a_homeserver](https://www.reddit.com/r/selfhosted/comments/1in2izp/how_do_i_get_started_with_a_homeserver)
 - RSS feed: $source
 - date published: 2025-02-11T16:25:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, I bought a used Fujitsu Esprimo D757 with an i5 6500, 8GB DDR4 Ram and 1.5TB of Storage. I&#39;m planing to use this as my first homeserver as a NAS, Mediaserver, maybe Plex Server and to run a Minecraft server my friends can join anytime.</p> <p>I&#39;ve never done this before so I need some help regarding which OS, Software and programs I should use. If possible I would like to control everything from my main PC after the initial setup.</p> <p>Any help would be appreaciated</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AcNicooo"> /u/AcNicooo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in2izp/how_do_i_get_started_with_a_homeserver/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in2izp/how_do_i_get_started_with_a_homeserver/">[comments]</a></span>

## Yet another note taking app
 - [https://www.reddit.com/r/selfhosted/comments/1in2gw3/yet_another_note_taking_app](https://www.reddit.com/r/selfhosted/comments/1in2gw3/yet_another_note_taking_app)
 - RSS feed: $source
 - date published: 2025-02-11T16:23:24+00:00

<!-- SC_OFF --><div class="md"><p>I was having a hard time finding a note taking app. I wanted one that had:</p> <ol> <li>Fast - I want it to feel smooth &amp; fast. Both search and editing/viewing. Just need it to be quick. For example, i use os specific (e.g. grep in linux) to search for notes and their content.</li> <li>Portability - I don&#39;t want to save my notes to a database - just markdown files I can search from terminal and edit via SSH when I want.</li> <li>No client / server sync - Just save it directly to my homelab! It has all the bells and whistles to backup etc.</li> <li>Mobile friendly - I take notes from my phone often - it needs to work.</li> <li>Simple - I just wanna take some notes, I don&#39;t want a knowledge management system</li> <li>Basic notebooks/folders</li> <li>FOSS - Always a bonus.</li> </ol> <p>I tried Joplin, memos, loqsec, flatnotes and a few others. All fantastic apps but just didn&#39;t meet what I wanted. I think Flatnotes came the closest. I w

## I'm thinking of hosting Vaultwarden
 - [https://www.reddit.com/r/selfhosted/comments/1in2474/im_thinking_of_hosting_vaultwarden](https://www.reddit.com/r/selfhosted/comments/1in2474/im_thinking_of_hosting_vaultwarden)
 - RSS feed: $source
 - date published: 2025-02-11T16:08:35+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m have some technical skills and I think I can do it. However I want to know the security implications. Some people strongly advised me against it. They said I should just use Bitwarden.</p> <p>So I want to ask if someone here with a cybersecurity background (or has any idea) can give me his/her opinion.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/wkup-wolf"> /u/wkup-wolf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in2474/im_thinking_of_hosting_vaultwarden/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in2474/im_thinking_of_hosting_vaultwarden/">[comments]</a></span>

## imap vs imaps
 - [https://www.reddit.com/r/selfhosted/comments/1in1mw5/imap_vs_imaps](https://www.reddit.com/r/selfhosted/comments/1in1mw5/imap_vs_imaps)
 - RSS feed: $source
 - date published: 2025-02-11T15:48:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1in1mw5/imap_vs_imaps/"> <img src="https://a.thumbs.redditmedia.com/R1gUavJLy4v1hQBFEOFCAoQmIfR0Md0k96TKPgO56i0.jpg" alt="imap vs imaps" title="imap vs imaps" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;ve been exploring tightening up my VPS-based dovecot (and postfix) installation, mostly for fun.</p> <p>When I changed this line in dovecot.conf:</p> <pre><code>protocols = imap lmtp </code></pre> <p>to</p> <pre><code>protocols = imaps lmtp </code></pre> <p>I was suddenly unable to connect to the server (remotely). Yet I thought the (Outlook) account was set up correctly:</p> <p><a href="https://preview.redd.it/9mfq88tt6jie1.png?width=592&amp;format=png&amp;auto=webp&amp;s=e54ed3111b0e15e9778a038c49e8a633b4952f27">https://preview.redd.it/9mfq88tt6jie1.png?width=592&amp;format=png&amp;auto=webp&amp;s=e54ed3111b0e15e9778a038c49e8a633b4952f27</a></p> <p>What did I do wrong?</p> </div><!-- SC_ON --> &#32;

## home hosting - DNS record update
 - [https://www.reddit.com/r/selfhosted/comments/1in1mkd/home_hosting_dns_record_update](https://www.reddit.com/r/selfhosted/comments/1in1mkd/home_hosting_dns_record_update)
 - RSS feed: $source
 - date published: 2025-02-11T15:48:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am about to build my first (simple -ish) home lab setup, the setup is going to run home assistant but also a small LAMP setup and Adguard. I have a domainname that I would like to point to to the LAMP server but am unsure what service I can use to update the DNS records should my external IP change (router resets or ISP changes my IP etc.)?</p> <p>I am using duckdns on my current home assistant setup but that only updates .duckdns.org domains (i think) - so my question is what do I need to install or run to update the DNS records for my domain to point to my lamp setup?</p> <p>Thank you - I am new/learning this after years of hacking away with half setups it is time for me to setup properly at home (planning on using Proxmox to manage the instances for info). </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/geeky-hawkes"> /u/geeky-hawkes </a> <br/> <span><a href="https://www.reddit.com/r/selfhost

## Must-Have Self-Hosted Apps – What Makes Your Life Easier?
 - [https://www.reddit.com/r/selfhosted/comments/1in0wud/musthave_selfhosted_apps_what_makes_your_life](https://www.reddit.com/r/selfhosted/comments/1in0wud/musthave_selfhosted_apps_what_makes_your_life)
 - RSS feed: $source
 - date published: 2025-02-11T15:17:43+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I&#39;m currently looking for <strong>must-have self-hosted apps</strong> that make your daily life easier. I love diving into new projects and constantly improving my homelab.</p> <p>I&#39;ve only been into self-hosting for about <strong>14 days</strong>, so I&#39;m still struggling with some things, but I&#39;m eager to learn and improve.</p> <p>Here are the services I’m currently running:</p> <ul> <li><strong>AdGuard Home</strong></li> <li><strong>Nginx Proxy Manager</strong></li> <li><strong>PDF Stirling</strong></li> <li><strong>Portier (2x)</strong></li> <li><strong>Smokeping</strong></li> <li><strong>Uptime Kuma</strong></li> <li><strong>Watchtower</strong></li> <li><strong>Paperless NGX</strong></li> </ul> <p>Which self-hosted apps do you consider <strong>essential</strong>? What makes your life easier or is just plain fun?</p> <p>Looking forward to your recommendations and insights!</p> </div><!-- SC_ON --> &#32; submitt

## Using individual "tools" on proxmox - Whisper in this case?
 - [https://www.reddit.com/r/selfhosted/comments/1in0jm4/using_individual_tools_on_proxmox_whisper_in_this](https://www.reddit.com/r/selfhosted/comments/1in0jm4/using_individual_tools_on_proxmox_whisper_in_this)
 - RSS feed: $source
 - date published: 2025-02-11T15:02:03+00:00

<!-- SC_OFF --><div class="md"><p>I had Whisper, Home Assistant Core, etc etc running on baremetal.</p> <p>I&#39;ve migrated to proxmox with a HAOS VM and various LXCs. </p> <p>I am missing various tools (often installed via pip) like Whisper. Some of those have setup scripts, some don&#39;t.</p> <p>I want to start by installing either whisper or faster-whisper.</p> <p>Am I better trying to get this done via an LXC, or &quot;inside&quot; my HAOS VM?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thephatmaster"> /u/thephatmaster </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in0jm4/using_individual_tools_on_proxmox_whisper_in_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in0jm4/using_individual_tools_on_proxmox_whisper_in_this/">[comments]</a></span>

## Open source requisition software recommendations
 - [https://www.reddit.com/r/selfhosted/comments/1in079d/open_source_requisition_software_recommendations](https://www.reddit.com/r/selfhosted/comments/1in079d/open_source_requisition_software_recommendations)
 - RSS feed: $source
 - date published: 2025-02-11T14:46:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Anyone got recommendations for a requisition software that is open source and comes with approval module for petty cash transactions or purchases?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Express_Steak"> /u/Express_Steak </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1in079d/open_source_requisition_software_recommendations/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1in079d/open_source_requisition_software_recommendations/">[comments]</a></span>

## 🌐 Cloudflare DNS Manager for Docker - Automatically manage DNS records for your self-hosted services
 - [https://www.reddit.com/r/selfhosted/comments/1imzt9u/cloudflare_dns_manager_for_docker_automatically](https://www.reddit.com/r/selfhosted/comments/1imzt9u/cloudflare_dns_manager_for_docker_automatically)
 - RSS feed: $source
 - date published: 2025-02-11T14:29:30+00:00

<!-- SC_OFF --><div class="md"><p>Hey fellow self-hosters! I wanted to share a tool I created to simplify DNS management when running Docker services.</p> <p><strong>What it does:</strong> Simply add labels to your Docker containers/services, and it automatically creates/updates the corresponding DNS records in Cloudflare. No more manual DNS management!</p> <p><strong>Key features:</strong></p> <ul> <li>Works with both standalone Docker and Swarm mode</li> <li>Supports A, AAAA, CNAME, MX, and TXT records</li> <li>Automatic public IP detection</li> <li>Smart defaults (just specify the hostname, it handles the rest)</li> <li>Cloudflare proxy support</li> <li>Multiple domains/subdomains per container</li> </ul> <p><strong>Quick example:</strong></p> <pre><code>version: &quot;3.8&quot; services: nextcloud: image: nextcloud labels: - &quot;dns.cloudflare.hostname=cloud.yourdomain.com&quot; # That&#39;s it! It will automatically create an A record </code></pre> <p><strong>More complex exam

## Use traefik certificate resolver without routing requests to service
 - [https://www.reddit.com/r/selfhosted/comments/1imzkok/use_traefik_certificate_resolver_without_routing](https://www.reddit.com/r/selfhosted/comments/1imzkok/use_traefik_certificate_resolver_without_routing)
 - RSS feed: $source
 - date published: 2025-02-11T14:18:09+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I have done some searching and have not found any answer pertaining to this scenario, so I hope it&#39;s not a duplicate.</p> <p>I have recently been doing a bunch of learning with docker and traefik after getting a proper server set up and it has been awesome! I experimented with exposing some services to the internet and then got paranoid so removed them from the traefik routers. I am however enjoying the automated letsencrypt SSL certs and am wondering how to keep them around and renewed whilst not having the service itself exposed.</p> <p>In order for the cert renewal to work I assume that the hostname in question (let&#39;s say <code>picoshare.mydomain.com</code>) needs to resolve to my public IP, however if I remove the traefik labels from the service container, specifically this one:</p> <pre><code>&quot;traefik.http.routers.picoshare.rule=Host(`picoshare.mydomain.com`)&quot; </code></pre> <p>then (I think) traefik will not know which d

## How can i make my domain show up in the address bar?
 - [https://www.reddit.com/r/selfhosted/comments/1imz798/how_can_i_make_my_domain_show_up_in_the_address](https://www.reddit.com/r/selfhosted/comments/1imz798/how_can_i_make_my_domain_show_up_in_the_address)
 - RSS feed: $source
 - date published: 2025-02-11T14:00:45+00:00

<!-- SC_OFF --><div class="md"><p>So i have a server running ubuntu with apache2 that is port forwarded to my ips 45279 port. I have a domain at porkbun. I want to make the website thats on my server to show up on the domain i bought. I tried DNS records, it says i can only include an ipv4 address so i cant specify a port and when i try glue records, it says &quot;Could not create or update host.&quot;. What should i do? Any help would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Detryx-"> /u/Detryx- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imz798/how_can_i_make_my_domain_show_up_in_the_address/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imz798/how_can_i_make_my_domain_show_up_in_the_address/">[comments]</a></span>

## New 2025 Docker/-Swarm Beginners-Guide for Traefik Reverse Proxy!
 - [https://www.reddit.com/r/selfhosted/comments/1imz1a3/new_2025_dockerswarm_beginnersguide_for_traefik](https://www.reddit.com/r/selfhosted/comments/1imz1a3/new_2025_dockerswarm_beginnersguide_for_traefik)
 - RSS feed: $source
 - date published: 2025-02-11T13:52:27+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1imz1a3/new_2025_dockerswarm_beginnersguide_for_traefik/"> <img src="https://external-preview.redd.it/9jOK_iNDtfaIRNHovxwOKYj7wV-MVEyEe1v-5mbeDwk.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b3b000dc39d16005b96a1ab340ae8e04a43fcb65" alt="New 2025 Docker/-Swarm Beginners-Guide for Traefik Reverse Proxy!" title="New 2025 Docker/-Swarm Beginners-Guide for Traefik Reverse Proxy!" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey Selfhosters,</p> <p>I wrote a Big Traefik Reverse Proxy Guide for Docker &amp; DockerSwarm!</p> <p><strong>Disclaimer:</strong><br/> <strong>The Guide/Wiki-Post is not always Perfect... If you got Recommendations or Feedback please be Constructive in the Commentsection.</strong></p> <p><a href="https://preview.redd.it/gm9fcd0hmiie1.png?width=2640&amp;format=png&amp;auto=webp&amp;s=0bc4def641afcf60c894de0a9037d5f695fc6371">Traefik 3.3.3</a></p> <h1>Link-List</h1> <table><thead> <tr> <

## When your bell router randomly blocks an IP for no apparent reason
 - [https://www.reddit.com/r/selfhosted/comments/1imyr4j/when_your_bell_router_randomly_blocks_an_ip_for](https://www.reddit.com/r/selfhosted/comments/1imyr4j/when_your_bell_router_randomly_blocks_an_ip_for)
 - RSS feed: $source
 - date published: 2025-02-11T13:38:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>Yesterday, I ran into a bizarre networking issue that I initially thought was caused by <strong>AdGuard Home</strong> breaking my server. After hours of troubleshooting, it turned out to be something completely different.</p> <p>I have a <strong>self-hosted Debian server</strong> running multiple services, and my network is managed by a <strong>Bell Router</strong> (which I plan to replace soon with an <strong>ASUS RT-AX88U PRO</strong>, already ordered) (i also plan to kick Bell out of my life lol, just learn how to do IPV6, guys). Everything was working fine—until it suddenly wasn’t.</p> <h1>The Issue</h1> <p>At some point, my server <strong>completely lost connectivity</strong>. It couldn&#39;t:</p> <ul> <li>Reach the <strong>internet</strong></li> <li>Ping the <strong>gateway</strong> (192.168.2.1)</li> <li>Communicate with <strong>any other devices</strong> on the network</li> </ul> <p><strong>However</strong></p> <ul> <li>T

## My way to deploy K3S home cluster
 - [https://www.reddit.com/r/selfhosted/comments/1imyhzn/my_way_to_deploy_k3s_home_cluster](https://www.reddit.com/r/selfhosted/comments/1imyhzn/my_way_to_deploy_k3s_home_cluster)
 - RSS feed: $source
 - date published: 2025-02-11T13:25:31+00:00

<!-- SC_OFF --><div class="md"><p>This was written initially more to help me in the future to easily rebuild my k3s lab, or to have where to check how I configured everything in case I forget, isn’t something really new and it’s based a lot on technotim k3s-ansible project, jimsgarage and some guides found here on selfhosted/kubernetes communities, maybe it will help someone of you, and I’m also open to complete the blog post if you have any idea, the main content of the blog is:</p> <ul> <li>Simple best practices on your network before starting the k3s deployment</li> <li>A bash script to easily deploy ubuntu VMs in proxmox Based on cloud-init</li> <li>K3s-ansible technotim - how to configure and deploy for your needs</li> <li>Infrastructure k3s apps deployment like rancher, traefik, cert-manager and longhorn</li> </ul> <p>If it helps someone I’m really thankful</p> <p>Here is the link: <a href="https://merox.dev/blog/k3s-cluster-in-2025/">https://merox.dev/blog/k3s-cluster-in-2025/

## Any good free whatsapp http api?
 - [https://www.reddit.com/r/selfhosted/comments/1imy3n6/any_good_free_whatsapp_http_api](https://www.reddit.com/r/selfhosted/comments/1imy3n6/any_good_free_whatsapp_http_api)
 - RSS feed: $source
 - date published: 2025-02-11T13:04:39+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, Recently my office is forcing all people to update their WhatsApp status daily using some provided text or video. While i can do it manualy, but its too much of hassle for me who never put anything on story/status.</p> <p>So now im try to find a good apps that can be self hosted with capability to change status (text or video would be great) using api or some other method.</p> <p>i found waha, but 19$ per month is too much for me. is there any other selfhoster have experience and recommendation in this kind of apps? thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/alveox"> /u/alveox </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imy3n6/any_good_free_whatsapp_http_api/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imy3n6/any_good_free_whatsapp_http_api/">[comments]</a></span>

## Making installation of self-hosted apps easier.
 - [https://www.reddit.com/r/selfhosted/comments/1imxfkw/making_installation_of_selfhosted_apps_easier](https://www.reddit.com/r/selfhosted/comments/1imxfkw/making_installation_of_selfhosted_apps_easier)
 - RSS feed: $source
 - date published: 2025-02-11T12:27:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi <a href="/r/selfhosted">r/selfhosted</a> ,</p> <p>My goal is to make the installation process of self-hosted apps easier, ideally in one click. This is what I did my pet project for - <a href="https://github.com/frierun/frierun">https://github.com/frierun/frierun</a> </p> <p>It can install/uninstall such packages as Jellyfin, Immich, Plex and some others in one click.</p> <p>Many packages are supplied as a single docker container but require other stuff for a full setup: a domain, databases, volumes, ssl certificates. Each and every thing needs to be configured according to your existing infrastructure. Provided docs and hints are far from being unified. Some of the packages require docker, some docker compose. Some packages will install their own db, some request your existing db credentials. Some require an ssl certificate, some want to install traefik which will request the cert on its own.</p> <p>Long story short, the idea to unify package req

## Interest in Setting up own Mail server (Mail in a Box)
 - [https://www.reddit.com/r/selfhosted/comments/1imx51n/interest_in_setting_up_own_mail_server_mail_in_a](https://www.reddit.com/r/selfhosted/comments/1imx51n/interest_in_setting_up_own_mail_server_mail_in_a)
 - RSS feed: $source
 - date published: 2025-02-11T12:10:13+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, I would like to ask if anybody is interested for a paid project which is an open source mail server (Mail in A Box) setup with the Server managed by us, and making it a Hidden Service (accessible only through TOR Network). Users are at least 20. </p> <p>Please let me know if you are interested.</p> <p>Please don&#39;t ban me :(((</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glum_Teaching_9426"> /u/Glum_Teaching_9426 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imx51n/interest_in_setting_up_own_mail_server_mail_in_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imx51n/interest_in_setting_up_own_mail_server_mail_in_a/">[comments]</a></span>

## Tunnel immich using EC2 instance
 - [https://www.reddit.com/r/selfhosted/comments/1imx1a5/tunnel_immich_using_ec2_instance](https://www.reddit.com/r/selfhosted/comments/1imx1a5/tunnel_immich_using_ec2_instance)
 - RSS feed: $source
 - date published: 2025-02-11T12:03:59+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to access my immich server from the public internet but my ipv4 address is behind a CGNAT so can really use that for hosting and not everyone with whom I&#39;m trying to share access to my server gets ipv6 address like me, so I was trying to use wireguard to tunnel only my ipv4 traffic from my server to EC2 instance and then to the user. I was thinking of settting A name record to the EC2 instace public ip and AAAA name record to my server ip.</p> <p>I&#39;ve been trying to setup wireguard tunnel for the past few hours and nothing has worked so far.</p> <p>Server Config:</p> <pre><code>[Interface] Address = 10.0.0.1/24 DNS = 1.1.1.1 PrivateKey = &lt;private_key&gt; ListenPort = 51820 PostUp = iptables -A FORWARD -i %i -j ACCEPT; iptables -A FORWARD -o %i -j ACCEPT; iptables -t nat -A POSTROUTING -o enX0 -j MASQUERADE PostDown = iptables -D FORWARD -i %i -j ACCEPT; iptables -D FORWARD -o %i -j ACCEPT; iptables -t nat -D POSTROUTING -o e

## Mini PC as Docker server for Ticketing sys
 - [https://www.reddit.com/r/selfhosted/comments/1imvygv/mini_pc_as_docker_server_for_ticketing_sys](https://www.reddit.com/r/selfhosted/comments/1imvygv/mini_pc_as_docker_server_for_ticketing_sys)
 - RSS feed: $source
 - date published: 2025-02-11T10:54:51+00:00

<!-- SC_OFF --><div class="md"><p>Hi all!</p> <p>I&#39;m a self-employed web developer and have been investigating open source ticketing solutions to help improve my processes and some stuff falling down the cracks in my email.</p> <p>Also, I have a couple of other freelancers who I need to give access to individual inboxes occasionally.</p> <p>My needs are fairly simple:</p> <ul> <li><strong>Monitor email account(s) -</strong> Most support comes through email, so I&#39;d have the helpdesk monitor an inbox and create tickets from any emails that come in.</li> <li><strong>Multiple inboxes</strong>, or ability to segment and grant access to only some tickets by the company they came from. I&#39;d have maybe 3 or 4 inboxes for Support, On-boarding, Company A, Company B etc. So freelancer A might only have access to Company A. Although 96% of the time it&#39;s just me.</li> <li><strong>Segmentation by Company,</strong> I&#39;d want to auto-route all emails from certain domains to specifi

## Database you use to store MQTT data?
 - [https://www.reddit.com/r/selfhosted/comments/1imvy3p/database_you_use_to_store_mqtt_data](https://www.reddit.com/r/selfhosted/comments/1imvy3p/database_you_use_to_store_mqtt_data)
 - RSS feed: $source
 - date published: 2025-02-11T10:54:08+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve used influxdb and now preferring timescaledb (Postgres extension). In any case, wha&#39;dt you (recommend to) use?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/edgeflare"> /u/edgeflare </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imvy3p/database_you_use_to_store_mqtt_data/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imvy3p/database_you_use_to_store_mqtt_data/">[comments]</a></span>

## An AI agent for e-commerce
 - [https://www.reddit.com/r/selfhosted/comments/1imvxpn/an_ai_agent_for_ecommerce](https://www.reddit.com/r/selfhosted/comments/1imvxpn/an_ai_agent_for_ecommerce)
 - RSS feed: $source
 - date published: 2025-02-11T10:53:24+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m the creator of a an AI agent for e-commerce that can be self-hosted, called Enthusiast. You can think of it as a huge knowledge base supporting sales, customer support or marketing teams. It&#39;s also open-source. </p> <p>Enthusiast was created as an answer for businesses that want to run LLMs, but only on their own infrastructure. You can fully customize it, and create your own integrations. For now we have ready integration with Shopify, and more are on the way. </p> <p>Here&#39;s the GitHub repo: <a href="https://github.com/upsidelab/enthusiast">https://github.com/upsidelab/enthusiast</a></p> <p>You can get started in few minutes by following this getting started guide: <a href="https://upsidelab.io/tools/enthusiast/docs/category/getting-started">https://upsidelab.io/tools/enthusiast/docs/category/getting-started</a></p> <p>Thanks for checking it out, waiting for feedback and happy to answer any questions :)</p> </div><!-- SC_ON --> &#32;

## We've created a Self-hosting analytics tool! (+890 stars on github)
 - [https://www.reddit.com/r/selfhosted/comments/1imv077/weve_created_a_selfhosting_analytics_tool_890](https://www.reddit.com/r/selfhosted/comments/1imv077/weve_created_a_selfhosting_analytics_tool_890)
 - RSS feed: $source
 - date published: 2025-02-11T09:44:28+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks at <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I wanted to introduce you to our self-hosted analytics tool called Litlyx. I&#39;ve already made some posts here, but I would love the support of this amazing community of builders to share this with people who might be interested.</p> <p>We didn’t invent anything new... this isn’t some groundbreaking discovery... but we realized that &quot;modern&quot; analytics solutions are bad. Really bad.</p> <p>No good UI/UX. They claim to be open-source but impose too many limitations. They say they replace Google Analytics but still import its tracking script... (Yes, we allow users to log in with Google and email, but only because Google has 10B+ accounts.)</p> <p>So the idea is: we want to bring some fresh air and genuinely try to replace Google Analytics (even if it’s an impossible task). We want to be a modern alternative to Plausible, Matomo, Umami that are old solution that most of the time co

## Is Self-Hosted Mail more private? (For my use case)
 - [https://www.reddit.com/r/selfhosted/comments/1imuzlt/is_selfhosted_mail_more_private_for_my_use_case](https://www.reddit.com/r/selfhosted/comments/1imuzlt/is_selfhosted_mail_more_private_for_my_use_case)
 - RSS feed: $source
 - date published: 2025-02-11T09:43:08+00:00

<!-- SC_OFF --><div class="md"><p>Hello Self-Hosters,</p> <p>I&#39;ve been interested in self-hosting my Email stack as its one of the last services for which I rely on cloud solutions like Gmail. I know that self-hosting mail is kinda tricky cause its a lot of work to mantain and it can cause issues like being flaged as spam.</p> <p>My main use case was to have unlimited number of email addresses which I can use to create accounts in other services, sending mails would not be a requirement. This seems like a perfect use case as I dont have to deal with many of the drawbacks as the main problem AFAIK is with sending mails, not receiving.</p> <p>However I&#39;ve been reluctant to setting this up cause I feel like it would not be better for privacy. Let me explain.</p> <p>Option 1: Use random Gmail accounts, and use this account to register to some other site. Google has my emails, but my account is not related to my real identity, Google doesnt know who I am, nor does the site I regis

## Duplicate request to local addresses
 - [https://www.reddit.com/r/selfhosted/comments/1imuc8f/duplicate_request_to_local_addresses](https://www.reddit.com/r/selfhosted/comments/1imuc8f/duplicate_request_to_local_addresses)
 - RSS feed: $source
 - date published: 2025-02-11T08:52:35+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I don’t have much experience with networking, but my friend and I are facing an issue.</p> <p>How can we duplicate incoming requests and forward them to two different machines?</p> <p>We&#39;re building an app that relies on various integrations. To integrate successfully via OAuth, we need to provide a redirect URL that supports HTTPS, meaning <code>localhost</code> isn&#39;t an option. Right now, we have a Cloudflare Tunnel set up on our main redirect URL, which forwards requests to our local machines. However, this only works about 50% of the time and only for one person at a time.</p> <p>Does anyone have suggestions on how to properly forward or duplicate these requests to multiple machines?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Glittering_Candle814"> /u/Glittering_Candle814 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imuc8f/duplicate_request_to_loca

## Announcing Reddit-Fetch: Save & Organize Your Reddit Saved Posts Effortlessly!
 - [https://www.reddit.com/r/selfhosted/comments/1imu7p1/announcing_redditfetch_save_organize_your_reddit](https://www.reddit.com/r/selfhosted/comments/1imu7p1/announcing_redditfetch_save_organize_your_reddit)
 - RSS feed: $source
 - date published: 2025-02-11T08:42:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a> and fellow Redditors! 👋</p> <p>I’m excited to introduce Reddit-Fetch, a Python-based tool I built to fetch, organize, and back up saved posts and comments from Reddit. If you’ve ever wanted a structured way to store and analyze your saved content, this is for you!</p> <p>🔹 Key Features: ✅ Fetch &amp; Backup: Automatically downloads saved posts and comments. ✅ Delta Fetching: Only retrieves new saved posts, avoiding duplicates. ✅ Token Refreshing: Handles Reddit API authentication seamlessly. ✅ Headless Mode Support: Works on Raspberry Pi, servers, and cloud environments. ✅ Automated Execution: Can be scheduled via cron jobs or task schedulers.</p> <p>🔧 Setup is simple, and all you need is a Reddit API key! Full installation and usage instructions are available in the GitHub repo: 🔗 GitHub Link: <a href="https://github.com/akashpandey/Reddit-Fetch">https://github.com/akashpandey/Reddit-Fetch</a></p> <p>Woul

## How do I run database migrations using Coolify
 - [https://www.reddit.com/r/selfhosted/comments/1imtwtl/how_do_i_run_database_migrations_using_coolify](https://www.reddit.com/r/selfhosted/comments/1imtwtl/how_do_i_run_database_migrations_using_coolify)
 - RSS feed: $source
 - date published: 2025-02-11T08:18:55+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m just switching from <code>Vercel</code> to <code>Coolify</code>, and have managed to set up a Postgres database, Redis instance and my app. (NextJS using Docker).</p> <p>Previously in Vercel, my build command was this <code>npx prisma generate &amp;&amp; npx prisma migrate deploy &amp;&amp; next build</code>. Essentially running a prisma migration, generating the prisma types and building my app.</p> <p>However, because I&#39;m using Docker now, I obviously can&#39;t make <code>prisma migrate</code> part of my Dockerfile. So where&#39;s the best place to run this now? Ideally I want to just run it when I deploy.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Quick-Balance-9257"> /u/Quick-Balance-9257 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imtwtl/how_do_i_run_database_migrations_using_coolify/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/com

## Self hosted tool that can email on a schedule.
 - [https://www.reddit.com/r/selfhosted/comments/1imtixm/self_hosted_tool_that_can_email_on_a_schedule](https://www.reddit.com/r/selfhosted/comments/1imtixm/self_hosted_tool_that_can_email_on_a_schedule)
 - RSS feed: $source
 - date published: 2025-02-11T07:49:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I&#39;m looking for a self hosted tool that can send different emails to different emails address,s on a schedule I setup.</p> <p>Would be awesome if it has a calendar and multiple accounts attached to it.</p> <p>So essentially configure the email accounts on the tool and then schedule it to send from the separate accounts.</p> <p>Hope that makes sense </p> <p>Rob</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IT-Rob"> /u/IT-Rob </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imtixm/self_hosted_tool_that_can_email_on_a_schedule/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imtixm/self_hosted_tool_that_can_email_on_a_schedule/">[comments]</a></span>

## Cannot play some movies with HW decoding
 - [https://www.reddit.com/r/selfhosted/comments/1imtbc5/cannot_play_some_movies_with_hw_decoding](https://www.reddit.com/r/selfhosted/comments/1imtbc5/cannot_play_some_movies_with_hw_decoding)
 - RSS feed: $source
 - date published: 2025-02-11T07:34:18+00:00

<!-- SC_OFF --><div class="md"><p>-- My HW specs: </p> <p>-- OS: Unraid 6.12</p> <p>-- AMD Ryzen 7 5700G with Radeon Graphics (so APU must be 5000 series). No GPU here.</p> <p>-- I&#39;m using last Linuxserver docker version of Jellyfin.</p> <p>If I play movies with HW disabled everything is fine. All CPUs goes to 75% but ok, the movie is playing. Instead, if I enable HW encoding options with AMD AMF or VAAPI drivers, some movies give a playback fatal error. For instance, this is the info I get from Jellyfin:</p> <p>101 dalmatians, 1080p, h264, SDR (HW acceleration gives an error here)</p> <p>102 dalmatians, 1080p, h264, SDR (no errors here)</p> <p>WTF is going on here? Here goes the log (FfmpegException: FFmpeg exited with code 187? Is that the problem?):</p> <pre><code> at Jellyfin.Api.Middleware.RobotsRedirectionMiddleware.Invoke(HttpContext httpContext) at Jellyfin.Api.Middleware.LegacyEmbyRouteRewriteMiddleware.Invoke(HttpContext httpContext) at Microsoft.AspNetCore.ResponseComp

## Would website be useful?
 - [https://www.reddit.com/r/selfhosted/comments/1imt54h/would_website_be_useful](https://www.reddit.com/r/selfhosted/comments/1imt54h/would_website_be_useful)
 - RSS feed: $source
 - date published: 2025-02-11T07:21:55+00:00

<!-- SC_OFF --><div class="md"><p>I have been on my self-hosting journey for last year or so. I have many apps currently running on my server via docker... e.g. Nextcloud Arr Gitlab Jellyfin Traefik Grafana Metabase Etc...</p> <p>I was wondering if a free website, with a guide like structure, showing how to build your own Opensource self-hosted setup would be appreciated by the community?</p> <p>Intention is to let someone start from basics of linux to all the way to proxmox and docker.</p> <p><a href="https://www.reddit.com/poll/1imt54h">View Poll</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/StudentWithNoMaster"> /u/StudentWithNoMaster </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imt54h/would_website_be_useful/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imt54h/would_website_be_useful/">[comments]</a></span>

## Can I Use a Tablet as a Personal VPS
 - [https://www.reddit.com/r/selfhosted/comments/1imt040/can_i_use_a_tablet_as_a_personal_vps](https://www.reddit.com/r/selfhosted/comments/1imt040/can_i_use_a_tablet_as_a_personal_vps)
 - RSS feed: $source
 - date published: 2025-02-11T07:12:09+00:00

<!-- SC_OFF --><div class="md"><p>I have an old tablet and I&#39;m curious if I can use it as a personal VPS. I understand that tablets aren&#39;t intended for this purpose, but I’d like to know if there’s a way to make it functional for basic tasks.</p> <p>Previously, I was using <a href="https://electrohaxz.host/">ElectroHaxz Hosting</a>, which provides free VPS options through its VCO (Virtual Colocation) plan or via daily voting (the latter was my approach, but I don&#39;t want to deal with it anymore). In the VCO plan, users contribute resources from their devices (like tablets, laptops, or desktops) for services such as mirror file hosting, in return for access to a free VPS powered by x86-based enterprise-grade servers. The VPS operates independently from your device, yet utilizes the device&#39;s resources for various functions.</p> <p>They don’t host the VPS directly on your device; instead, they use your device&#39;s resources to support their infrastructure, providing you 

## First-Time Builder: Can I Use SAS Drives For A Multi-Media Server
 - [https://www.reddit.com/r/selfhosted/comments/1imslic/firsttime_builder_can_i_use_sas_drives_for_a](https://www.reddit.com/r/selfhosted/comments/1imslic/firsttime_builder_can_i_use_sas_drives_for_a)
 - RSS feed: $source
 - date published: 2025-02-11T06:44:06+00:00

<!-- SC_OFF --><div class="md"><p>Hello, all! So like the title says, I&#39;m a first time builder looking to create a multi-media (TV, Movies, Books, etc.) server locally at home, instead of perpetually paying for a seedbox. However, I&#39;m currently facing a decent-sized hurdle. So, I purchased some drives (for a great price), but overlooked the fact that the drives are SAS, not SATA. After doing some research, I seen that it&#39;s <em>technically</em> possible to connect the drives to the motherboard by way of a PCI controller? I just wanted to know how futureproof this is? Like, for example if I wanted to then add SATA drives down the road, would it create an imbalance in any way? Do I need any other parts to make this happen? Also, just for some added clarification, here are some of the parts I am/were eyeing for my server/pc build prior to knowing my drives were SAS:</p> <ul> <li><a href="https://www.newegg.com/black-fractal-design-define-7-xl-atx-full-tower/p/N82E16811352118?

## This sub has sparked a lifelong passion of mine. Just wanted to say thanks.
 - [https://www.reddit.com/r/selfhosted/comments/1imqwpx/this_sub_has_sparked_a_lifelong_passion_of_mine](https://www.reddit.com/r/selfhosted/comments/1imqwpx/this_sub_has_sparked_a_lifelong_passion_of_mine)
 - RSS feed: $source
 - date published: 2025-02-11T04:59:06+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1imqwpx/this_sub_has_sparked_a_lifelong_passion_of_mine/"> <img src="https://b.thumbs.redditmedia.com/3I_IdBq0Xbgvqv6wRfzFVxSwLP4Q8S6oSUja-kJqdpQ.jpg" alt="This sub has sparked a lifelong passion of mine. Just wanted to say thanks." title="This sub has sparked a lifelong passion of mine. Just wanted to say thanks." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Self hosting has brought a new level of joy to my life that I haven’t felt since I was a kid. It all started with using PFsense to block ads, then Plex, then Docker, and the rabbit hole goes so far I don’t even know where it’d stop. Today I just setup my first Ubuntu server where I am currently hosting Plex, Homeassistant, Kuma, and a few others. I successfully completed the migration over from Windows with no hiccups. Even managed to transfer 50TB of media with no losses. I have big plans for the future, and wouldn’t be able to do any of it without th

## Upgist - Web UI to upload files to GitHub Gists
 - [https://www.reddit.com/r/selfhosted/comments/1imqg00/upgist_web_ui_to_upload_files_to_github_gists](https://www.reddit.com/r/selfhosted/comments/1imqg00/upgist_web_ui_to_upload_files_to_github_gists)
 - RSS feed: $source
 - date published: 2025-02-11T04:32:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1imqg00/upgist_web_ui_to_upload_files_to_github_gists/"> <img src="https://external-preview.redd.it/880aE71oB-Rul23FdYKLYjPA9V2bg6kKEI-eYqy5pYw.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=44a016da18341b8f9d362a26efb372f6c15c3e65" alt="Upgist - Web UI to upload files to GitHub Gists" title="Upgist - Web UI to upload files to GitHub Gists" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I needed a simple Web app to upload images/files to public GitHub Gists. Didn&#39;t see any out there so I just made one.</p> <p>I like to use Gists to store images that I need public for one reason or another, such as hosting images for GitHub readme when I don&#39;t want to commit the image to the code.</p> <p><a href="https://github.com/zachatrocity/upgist">Screenshot in readme</a></p> <p>Anyways, was a fun little web app using go + htmx. It&#39;s useful for me, perhaps it will be useful to you!</p> </div><!-- SC_ON --> &

## Why Is It So Hard to Automate Certain Types of Content?
 - [https://www.reddit.com/r/selfhosted/comments/1imqc8o/why_is_it_so_hard_to_automate_certain_types_of](https://www.reddit.com/r/selfhosted/comments/1imqc8o/why_is_it_so_hard_to_automate_certain_types_of)
 - RSS feed: $source
 - date published: 2025-02-11T04:26:39+00:00

<!-- SC_OFF --><div class="md"><p>I have a <strong>100TB server</strong> (first-world problems, I know), but I&#39;m struggling to find content to fill it. I already have a decent-sized <strong>movie and TV show collection</strong>, thanks to how easily available they are on <strong>Usenet indexers and torrent sites</strong>. Now, I’m working on <strong>building a music library</strong>, but beyond that, things get <strong>way more difficult</strong>.</p> <p>When it comes to <strong>audiobooks, eBooks, websites, or video games</strong>, automated options seem to <strong>fall off a cliff</strong>. Finding this content manually is already tough, but setting up an <em>arr-style automation system? Forget it.</em>*</p> <p>I’ve heard that <strong>video games are hard to automate</strong> because of <strong>inconsistent naming schemes</strong>, making it difficult to develop a reliable *arr app. But that excuse doesn’t really apply to <strong>audiobooks, right?</strong> There’s clearly a de

## Looking for recommendations for HRMS
 - [https://www.reddit.com/r/selfhosted/comments/1imp0hz/looking_for_recommendations_for_hrms](https://www.reddit.com/r/selfhosted/comments/1imp0hz/looking_for_recommendations_for_hrms)
 - RSS feed: $source
 - date published: 2025-02-11T03:16:15+00:00

<!-- SC_OFF --><div class="md"><p>Hello! First time posting in this sub, I&#39;m currently looking for self hosted hrms. Maybe similar to WorkSuite by AJAY (it&#39;s paid and my broke ass can&#39;t afford it) any recommendations will be greatly appreciated!</p> <p>Frappe is too complicated on end user so I&#39;m looking for other alternatives</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/markapii"> /u/markapii </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imp0hz/looking_for_recommendations_for_hrms/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imp0hz/looking_for_recommendations_for_hrms/">[comments]</a></span>

## Self hosting DeepSeek
 - [https://www.reddit.com/r/selfhosted/comments/1imoi66/self_hosting_deepseek](https://www.reddit.com/r/selfhosted/comments/1imoi66/self_hosting_deepseek)
 - RSS feed: $source
 - date published: 2025-02-11T02:51:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m totally new to AI, and have tried using DeepSeek online to help me write a Python program. I have just copied and pasted the code back and forth from my IDE to DeepSeek, but now I am getting server busy messages. How can I self host DeepSeek in a way that allow me to paste the code back and forth to my IDE, and prompt for features I want DeepSeek to write, and prompt error messages for DeepSeek to solve. Especially, how can I get the AI to remember the 5 Python files that make up my program? Or is there a way to prompt the AI from within an IDE?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Window-1000"> /u/No-Window-1000 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imoi66/self_hosting_deepseek/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imoi66/self_hosting_deepseek/">[comments]</a></span>

## Authentik seems to be eating my server (I know this sounds silly, there is context)
 - [https://www.reddit.com/r/selfhosted/comments/1imobt8/authentik_seems_to_be_eating_my_server_i_know](https://www.reddit.com/r/selfhosted/comments/1imobt8/authentik_seems_to_be_eating_my_server_i_know)
 - RSS feed: $source
 - date published: 2025-02-11T02:42:21+00:00

<!-- SC_OFF --><div class="md"><p>I really can&#39;t think of a good title for this on virtue of it being such a weird situation. </p> <p>Context:</p> <ul> <li>Many services using Authentik as an OIDC backend</li> <li>Authentik started running slower and slower over time - no new users had been added during this</li> <li>Other services also got slow</li> <li>All web services are now just timing out</li> <li>&quot;Hm. I wonder if it&#39;s Authentik, that&#39;s always been a little slow&quot;</li> <li><code>cd authentik &amp;&amp; docker compose down</code></li> <li>Suddenly everything else is perfectly fine, no more timeouts, no more slowness</li> </ul> <p>So there&#39;s the situation. Now for the questions:</p> <ol> <li>What on earth might be going on here? This is unlike anything I&#39;ve had to troubleshoot in the past and searching the web and Authentik&#39;s issue tracker has not turned up anything useful</li> <li>Should I just switch to Authelia/Keycloak/anything else? Is this w

## Am I relying too much on tailscale?
 - [https://www.reddit.com/r/selfhosted/comments/1imobmz/am_i_relying_too_much_on_tailscale](https://www.reddit.com/r/selfhosted/comments/1imobmz/am_i_relying_too_much_on_tailscale)
 - RSS feed: $source
 - date published: 2025-02-11T02:42:07+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1imobmz/am_i_relying_too_much_on_tailscale/"> <img src="https://preview.redd.it/rqaqy5sfafie1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=b035ba9872d6a43b5f2ca1b3c7dd0907a53e255c" alt="Am I relying too much on tailscale?" title="Am I relying too much on tailscale?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GiveMeARedditUsernam"> /u/GiveMeARedditUsernam </a> <br/> <span><a href="https://i.redd.it/rqaqy5sfafie1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imobmz/am_i_relying_too_much_on_tailscale/">[comments]</a></span> </td></tr></table>

## -arr Stack file orgnization w/ Offsite seedbox
 - [https://www.reddit.com/r/selfhosted/comments/1imncoi/arr_stack_file_orgnization_w_offsite_seedbox](https://www.reddit.com/r/selfhosted/comments/1imncoi/arr_stack_file_orgnization_w_offsite_seedbox)
 - RSS feed: $source
 - date published: 2025-02-11T01:56:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey All -</p> <p>Question for the self-hosted hivemind. I&#39;m currently running an Arr-stack locally with my Plex server but the Arr-stack is pointed at an external Seedbox that will do a daily SFTP pull to a folder on my NAS.</p> <p>Here is the issue: That folder is a large, single pile that is now an absolute mess. The server is a truenas, so I&#39;m flexible to deploy any additional tools to help the media orgnization.</p> <p>Anyone have a similar sitaution?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/LetTheRiotsDrop"> /u/LetTheRiotsDrop </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1imncoi/arr_stack_file_orgnization_w_offsite_seedbox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1imncoi/arr_stack_file_orgnization_w_offsite_seedbox/">[comments]</a></span>

## Self-Hosting Deepseek AI Model on K3s with Cloudflared Tunnel — Full Control, Privacy, and Custom AI at Home! 🚀
 - [https://www.reddit.com/r/selfhosted/comments/1immd6n/selfhosting_deepseek_ai_model_on_k3s_with](https://www.reddit.com/r/selfhosted/comments/1immd6n/selfhosting_deepseek_ai_model_on_k3s_with)
 - RSS feed: $source
 - date published: 2025-02-11T00:58:42+00:00

<!-- SC_OFF --><div class="md"><p>I just deployed Deepseek 1.5b on my home server using K3s, Ollama for model hosting, and Cloudflared tunnel to securely expose it externally. Here’s how I set it up:</p> <ul> <li><strong>K3s</strong> for lightweight Kubernetes management</li> <li><strong>Ollama</strong> to pull and serve the Deepseek 1.5b model</li> <li><strong>Cloudflared</strong> to securely tunnel the app for external access</li> </ul> <p>Now, I’ve got a fully private AI model running locally, giving me complete control. Whether you’re a startup founder, CTO, or a tech enthusiast looking to experiment with AI, this setup is ideal for exploring secure, personal AI without depending on third-party providers.</p> <p><strong>Why it’s great for startups:</strong></p> <ul> <li>Full <strong>data privacy</strong></li> <li><strong>Cost-effective</strong> for custom models</li> <li><strong>Scalable</strong> as your needs grow</li> </ul> <p>Check out the full deployment guide here: <a href="

## Looking for a self hosted “TeamLinkt” - “TeamSnap” type app that has general chat but also event check-in
 - [https://www.reddit.com/r/selfhosted/comments/1immcsd/looking_for_a_self_hosted_teamlinkt_teamsnap_type](https://www.reddit.com/r/selfhosted/comments/1immcsd/looking_for_a_self_hosted_teamlinkt_teamsnap_type)
 - RSS feed: $source
 - date published: 2025-02-11T00:58:09+00:00

<!-- SC_OFF --><div class="md"><p>We’re a volunteer fire station and we have our regular communication app for calls but we use TeamLinkt to schedule our training night with what’s planned and who is or is not coming. </p> <p>With that it has a messenger for general group chat. </p> <p>Would be nice to have an app I can self host for the station and one that could share general documents etc. </p> <p>But of a big ask but figured I’d ask. </p> <p>Thank you </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/carterx"> /u/carterx </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1immcsd/looking_for_a_self_hosted_teamlinkt_teamsnap_type/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1immcsd/looking_for_a_self_hosted_teamlinkt_teamsnap_type/">[comments]</a></span>

## Upvote RSS - Generate RSS feeds from social aggregation websites like Reddit, Lemmy, and Hacker News
 - [https://www.reddit.com/r/selfhosted/comments/1imlhv8/upvote_rss_generate_rss_feeds_from_social](https://www.reddit.com/r/selfhosted/comments/1imlhv8/upvote_rss_generate_rss_feeds_from_social)
 - RSS feed: $source
 - date published: 2025-02-11T00:16:43+00:00

<!-- SC_OFF --><div class="md"><p>Upvote RSS is a self-hosted project I&#39;ve been working on that generates RSS feeds from social aggregation websites like Reddit, Lemmy, and Hacker News. You can subscribe to subreddits, Lemmy communities, and Hacker News while filtering to only the top posts. It will embed Reddit post media (videos, images, galleries), and you can optionally include parsed article content, AI-generated summaries, top comments, and more. Here are some of the features:</p> <ul> <li>Supports subreddits, Hacker News, Lemmy communities, and more to come</li> <li>Configurable filtering to dial in the right number of posts per day in your feed reader</li> <li>Embedded post media: videos, galleries, images</li> <li>Parsers to extract clean content and add featured images</li> <li>AI article summaries</li> <li>Estimated reading time, score, and permalinks to the original post</li> <li>Top comments</li> <li>NSFW filtering/blurring (Reddit only)</li> <li>Custom Reddit domain

## DNS Redirecting all Twitter/X links to Nitter - privacy friendly Twitter frontend that doesn't require logging in
 - [https://www.reddit.com/r/selfhosted/comments/1imlb35/dns_redirecting_all_twitterx_links_to_nitter](https://www.reddit.com/r/selfhosted/comments/1imlb35/dns_redirecting_all_twitterx_links_to_nitter)
 - RSS feed: $source
 - date published: 2025-02-11T00:08:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1imlb35/dns_redirecting_all_twitterx_links_to_nitter/"> <img src="https://external-preview.redd.it/XdLW0IGJGo-Rz1j76-dlX_QLyY7R6sAUxQiIjxS9H70.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=20679b4cda8ea4a3c235c9e7a499c3dfb9385e51" alt="DNS Redirecting all Twitter/X links to Nitter - privacy friendly Twitter frontend that doesn't require logging in" title="DNS Redirecting all Twitter/X links to Nitter - privacy friendly Twitter frontend that doesn't require logging in" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I&#39;m writing this guide/testimony because I deleted my twitter account back in November, sadly though some content is still only available through it and often requires an account to properly browse it. There is an alternative though called Nitter that proxies the requests and displays tweets in proper, clean and non bloated form. This however would require me to replace the domain in the URL 

## free, open source self hosted digital signage - multiscreen?
 - [https://www.reddit.com/r/selfhosted/comments/1iml6k7/free_open_source_self_hosted_digital_signage](https://www.reddit.com/r/selfhosted/comments/1iml6k7/free_open_source_self_hosted_digital_signage)
 - RSS feed: $source
 - date published: 2025-02-11T00:02:10+00:00

<!-- SC_OFF --><div class="md"><p>hi! </p> <p>Has anyone come across a digital signage solution thats free + open source that can be used across multiple screens? </p> <p>I have found a few options, one being Anthias (<a href="https://github.com/Screenly/Anthias/">https://github.com/Screenly/Anthias/</a>)</p> <p>but, as soon as multiscreen is in play it becomes their commercial offering.</p> <p>id be open to some out of the box thinking, could be repurpose of another software? </p> <p>Just trying to help a not-for-profit club - hence the cost sensitivity</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rudeone_99"> /u/rudeone_99 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1iml6k7/free_open_source_self_hosted_digital_signage/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1iml6k7/free_open_source_self_hosted_digital_signage/">[comments]</a></span>

