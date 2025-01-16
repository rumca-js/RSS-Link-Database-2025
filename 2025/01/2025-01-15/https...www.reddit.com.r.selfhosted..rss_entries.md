# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Can you self host an LLM using only CPU?
 - [https://www.reddit.com/r/selfhosted/comments/1i29q5r/can_you_self_host_an_llm_using_only_cpu](https://www.reddit.com/r/selfhosted/comments/1i29q5r/can_you_self_host_an_llm_using_only_cpu)
 - RSS feed: $source
 - date published: 2025-01-15T22:29:56+00:00

<!-- SC_OFF --><div class="md"><p>I currently have two Lenovo m900&#39;s I&#39;m trying to find a use for as I currently have a main proxmox server running everything I need. I had an idea to use K8&#39;s to run an LLM across both m900&#39;s, but both only have an i5. One has 16gb of ram and one has 8. Is this a reasonable idea? Or should I try a different project. The goal is learning, but I&#39;d like it to also be usable. </p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alternative_Leg_3111"> /u/Alternative_Leg_3111 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i29q5r/can_you_self_host_an_llm_using_only_cpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i29q5r/can_you_self_host_an_llm_using_only_cpu/">[comments]</a></span>

## Hoarder (the name) is being stolen from me
 - [https://www.reddit.com/r/selfhosted/comments/1i29pi1/hoarder_the_name_is_being_stolen_from_me](https://www.reddit.com/r/selfhosted/comments/1i29pi1/hoarder_the_name_is_being_stolen_from_me)
 - RSS feed: $source
 - date published: 2025-01-15T22:29:08+00:00

<!-- SC_OFF --><div class="md"><p>This post could have been about how hoarder reached <a href="https://github.com/hoarder-app/hoarder/releases/tag/v0.21.0">10k stars on Github</a>, or about how we spent a day in the front page of hackernews. But unfortunately, it&#39;s about neither of those. Today, I received a cease and desist from someone holding the &quot;Hordr&quot; trademark claiming that &quot;Hoarder&quot; infringes their trademark. Quoting the content of the letter:</p> <blockquote> <p>In these circumstances, our client is concerned, and justifiably so, that your use of a near identical name in connection with software having very similar (if not identical) functionality gives the impression that your software originates from, is somehow sponsored by, or is otherwise affiliated with our client.</p> </blockquote> <p>They&#39;re asking to cease and desist from using the &quot;Hoarder&quot; name, remove all content of websites/app store/github/etc that uses the name &quot;Hoard

## How to load local images into homepage (no docker)
 - [https://www.reddit.com/r/selfhosted/comments/1i29esk/how_to_load_local_images_into_homepage_no_docker](https://www.reddit.com/r/selfhosted/comments/1i29esk/how_to_load_local_images_into_homepage_no_docker)
 - RSS feed: $source
 - date published: 2025-01-15T22:15:55+00:00

<!-- SC_OFF --><div class="md"><p>I am setting up <a href="https://gethomepage.dev/">homepage</a> directly in a lxc, building from sources. Most of it works fine but I am having trouble loading in local images (for the background as well as for icons). The default icons and any image that is loaded remotely (via https) works fine but when I try to use a local image only a placeholder is displayed.<br/> I have tried both absolute and relative paths to the images. I have also tried storing them in the &quot;public&quot; folder and in an &quot;icons&quot; folder underneath that. All of the tips that I found on the website and elsewhere were talking about the docker image so I am kind of lost.</p> <p>I am very thankful for any advice or idea!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JanJanSax"> /u/JanJanSax </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i29esk/how_to_load_local_images_into_homepage_no_docker/">[link]<

## How should you setup and manage data storage for different proxmox containers?
 - [https://www.reddit.com/r/selfhosted/comments/1i2997w/how_should_you_setup_and_manage_data_storage_for](https://www.reddit.com/r/selfhosted/comments/1i2997w/how_should_you_setup_and_manage_data_storage_for)
 - RSS feed: $source
 - date published: 2025-01-15T22:09:23+00:00

<!-- SC_OFF --><div class="md"><p>EDIT: I incorrectly mentioned containers (also in the title), but I meant proxmox VMs.</p> <p>I am trying to get into self hosting. I have an old desktop pc which I want to use for this purpose. I have installed proxmox and now I am unsure how to proceed; especially how to handle data storage.</p> <p>I want to host the usual stuff: jellyfin, immich, paperless, etc. I am not exactly sure how I want to split these services into containers etc. For now I am thinking of:</p> <ul> <li>A VM running portainer and the different apps <ul> <li>can you have a single portainer instance manage apps spread over mutliple VMs?</li> </ul></li> <li>And a VM running a reverse proxy for the apps I want to access remotely.</li> </ul> <p>For now I have just made a single VM for experimenting.</p> <p>My only storage is an 8TB internal disk in the pc. Proxmox didn&#39;t automatically mount the disk, but I was able to mount it manually via the fstab file. I then tried to mou

## Ring camera replacement with local storage and mobile app viewer
 - [https://www.reddit.com/r/selfhosted/comments/1i297af/ring_camera_replacement_with_local_storage_and](https://www.reddit.com/r/selfhosted/comments/1i297af/ring_camera_replacement_with_local_storage_and)
 - RSS feed: $source
 - date published: 2025-01-15T22:07:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m looking into replacing my Ring cameras and their subscription.</p> <p>My current setup is:</p> <p>A network connected raspberrypi (for pihole) with large attached HDD. I&#39;m using it as a NAS as well.</p> <p>I&#39;m looking for indoor cameras, 2K resolution, ideally with motion/people tracking and night vision to install around the house. Plenty of them on Amazon that take SD card for storage.</p> <p>Wondering if there is any brand that would use the NAS as its backing storage. Knowing that I&#39;ve a full raspbian powering the NAS if additional processing is needed.</p> <p>In a way, if it works, it should mimic Ubiquity at a fraction of the cost and no monthly subscription.</p> <p>Any recommendations? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AgileHelicopter5673"> /u/AgileHelicopter5673 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i297af/ring_camera_replacement_wi

## cleanuperr v1.4.0 🚀 - Added Lidarr support, private downloads options and breaking changes
 - [https://www.reddit.com/r/selfhosted/comments/1i28zik/cleanuperr_v140_added_lidarr_support_private](https://www.reddit.com/r/selfhosted/comments/1i28zik/cleanuperr_v140_added_lidarr_support_private)
 - RSS feed: $source
 - date published: 2025-01-15T21:58:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I hope you week is going well!</p> <p>✨ I&#39;m excited to announce that cleanuperr v1.4.0 is now out, which includes the much requested support for Lidarr.</p> <p>cleanuperr is a tool for automating the cleanup of unwanted files and downloads for Sonarr, Radarr, and now Lidarr.</p> <ul> <li>Weird file extensions? Cleaned! 📄🧹</li> <li>Failed imports? Cleaned! 🚫🧹</li> <li>Stalled downloads? Cleaned! 🕒🧹</li> <li>Ignore private torrents? Not cleaned! 🔒</li> </ul> <p>Supported download clients:</p> <ul> <li>none</li> <li>qBittorrent</li> <li>Deluge</li> <li>Transmission</li> </ul> <p>What changed since v1.3.0:</p> <ul> <li>Created an official Unraid template. 🗄️</li> <li>Added Lidarr support. 🎵</li> <li>Changed the way blocklists work (breaking change), due to new Lidarr support. ⚠️</li> <li>Added option to not use a download client. This is useful if you want to use cleanuperr to remove failed imports, even if you&#39;re using Usenet.</li> 

## Is this config good enough for plex media server?
 - [https://www.reddit.com/r/selfhosted/comments/1i28w3t/is_this_config_good_enough_for_plex_media_server](https://www.reddit.com/r/selfhosted/comments/1i28w3t/is_this_config_good_enough_for_plex_media_server)
 - RSS feed: $source
 - date published: 2025-01-15T21:53:49+00:00

<!-- SC_OFF --><div class="md"><p>Just getting started in this world. I have only run Plex on my MacBook before thinking about getting an old PC to run a dedicated server. Would this config be enough?</p> <p>Intel j1900 4gb ddr3 ram 1tb hdd storage Windows 10 Wifi included </p> <p>Looking for guidance </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Top-Winner-5535"> /u/Top-Winner-5535 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i28w3t/is_this_config_good_enough_for_plex_media_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i28w3t/is_this_config_good_enough_for_plex_media_server/">[comments]</a></span>

## RX 6650 XT for local ai and gaming server?
 - [https://www.reddit.com/r/selfhosted/comments/1i28c1l/rx_6650_xt_for_local_ai_and_gaming_server](https://www.reddit.com/r/selfhosted/comments/1i28c1l/rx_6650_xt_for_local_ai_and_gaming_server)
 - RSS feed: $source
 - date published: 2025-01-15T21:29:17+00:00

<!-- SC_OFF --><div class="md"><p>Is there anyone who has some expirience with this card for genertive ai? Any help, or advice will help</p> <p>I&#39;d also like to integrate it with immich, for more functionality, also I would like to have something like local copilot while coding. Also I heard I can give access to searxng to models, and I find this really usefull. </p> <p>It has a single problem, ollama will must run through wsl, because I want to make this pc also as my &quot;gaming server&quot;. I am core Arch linux user, but I also miss games like Valorant, lol, and even fortnite. No nesecerly because of me, but I miss out on some time with my friends and it is slightly anoying. So it sadly has to be windows machine for this reason. </p> <p>I would use my laptop as client for this server, I have a lot of things selfhosted on my two other servers (old laptop and 12th gen intel pc with 3tb drive both running proxmox) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="http

## Share Your Setup!
 - [https://www.reddit.com/r/selfhosted/comments/1i287e3/share_your_setup](https://www.reddit.com/r/selfhosted/comments/1i287e3/share_your_setup)
 - RSS feed: $source
 - date published: 2025-01-15T21:23:47+00:00

<!-- SC_OFF --><div class="md"><p>Share Your Themes Selfhosted Stuff And Even Stuff U Think helps u on a daily basis!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mudw"> /u/mudw </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i287e3/share_your_setup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i287e3/share_your_setup/">[comments]</a></span>

## Habit, mood, and task tracker
 - [https://www.reddit.com/r/selfhosted/comments/1i28461/habit_mood_and_task_tracker](https://www.reddit.com/r/selfhosted/comments/1i28461/habit_mood_and_task_tracker)
 - RSS feed: $source
 - date published: 2025-01-15T21:20:00+00:00

<!-- SC_OFF --><div class="md"><p>So I know elements of this come up frequently, but I haven&#39;t seen any projects that really fit what I&#39;m looking for, hoping I&#39;ve missed some</p> <p>So here&#39;s the deal, I was recently diagnosed with ADHD and am starting meds to try and manage it</p> <p>I was hoping to find a decent app for tracking mood/overall feeling and energy level to assist with figuring out a good dosage for the meds</p> <p>I am already starting to use a basic android habit app (Habits) in parallel as part of my management plan, it&#39;s been quite useful BUT I would love to have the habit tracking in the same app as the mood tracking so that I can easily correlate habit performance with mood</p> <p>Finally less important but I am using planka for kanban and tasks but it would be equally useful if task completion/creating/progress could be tracked against mood etc as well</p> <p>So really what I&#39;m looking for is I guess a personal CRM type app that has the fo

## Hi, looking for email solution
 - [https://www.reddit.com/r/selfhosted/comments/1i280i5/hi_looking_for_email_solution](https://www.reddit.com/r/selfhosted/comments/1i280i5/hi_looking_for_email_solution)
 - RSS feed: $source
 - date published: 2025-01-15T21:15:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi, </p> <p>I&#39;m trying to have a self hosted email that&#39;s only online when i want it to be, for use as a recovery email address that does not depend on purchasing a domain for example. Looking at Exim. </p> <p>I have some basic tech skills but this stuff is the deepest ive gone and i dont know what im doing.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mastercolombo"> /u/mastercolombo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i280i5/hi_looking_for_email_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i280i5/hi_looking_for_email_solution/">[comments]</a></span>

## Scrutiny - Task Scheduler
 - [https://www.reddit.com/r/selfhosted/comments/1i272vr/scrutiny_task_scheduler](https://www.reddit.com/r/selfhosted/comments/1i272vr/scrutiny_task_scheduler)
 - RSS feed: $source
 - date published: 2025-01-15T20:34:54+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve just got Scrutiny up and running.</p> <p>Having a bit of an issue running the .exe using task scheduler on Windows 10. The task just keeps &quot;running&quot; and never sends any data but if I were to run the .exe directly from Powershell, it runs and completes.</p> <p>Using a user that is within the &quot;Administrators&quot; user group. I&#39;ve setup an identical task on another machine and it appears to run fine there.</p> <p>Anyone have any ideas to what I should check?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alternative_Cry9520"> /u/Alternative_Cry9520 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i272vr/scrutiny_task_scheduler/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i272vr/scrutiny_task_scheduler/">[comments]</a></span>

## Developing: self-hosted period tracking
 - [https://www.reddit.com/r/selfhosted/comments/1i26vii/developing_selfhosted_period_tracking](https://www.reddit.com/r/selfhosted/comments/1i26vii/developing_selfhosted_period_tracking)
 - RSS feed: $source
 - date published: 2025-01-15T20:26:06+00:00

<!-- SC_OFF --><div class="md"><h1>TLDR</h1> <p>Developing a open source self-hostable period tracker with e2e encrypted device syncing and cycle sharing. Any suggestions or input will be huge help!</p> <h1>Why?</h1> <p>Currently most period trackers out there are entirely proprietary. While many make promises that they encrypt your data or wont share it with law enforcement we all know that those promises are often empty. I wont get political but we can agree that privacy especially biological privacy is sacred.</p> <p>My solution, both server and client, will be open source, transparent and verifiablely end-to-end encrypted. There are already pen source trackers out there (such as Drip) but these also have their own issues.</p> <p>1) Many are not very feature rich, not as easy to use or unattractive.</p> <p>2) None that I have seen support device syncing or cycle sharing with friends and partners.</p> <h1>1.0 features</h1> <p>Features that I want stable and ready for the 1.0 releas

## self-hosting: “updates gone wild” – a true story of frustration and annoyance
 - [https://www.reddit.com/r/selfhosted/comments/1i26edw/selfhosting_updates_gone_wild_a_true_story_of](https://www.reddit.com/r/selfhosted/comments/1i26edw/selfhosting_updates_gone_wild_a_true_story_of)
 - RSS feed: $source
 - date published: 2025-01-15T20:04:58+00:00

<!-- SC_OFF --><div class="md"><p>Have you ever found yourself in a situation where you wanted to try out a new web app or tool, only to discover that it required an update or dependency that seemed too trivial to justify? But once you started down the rabbit hole, one minor issue led to another, and before you knew it, you were stuck in a never-ending cycle of updates and troubleshooting.</p> <p>I recently fell prey to this trap when I wanted to install the gh CLI tool on my Docker VM running Ubuntu 22.04. However, I soon realized that the version was no longer supported, making installation impossible. Feeling frustrated, I decided to test it as an LXC container in Proxmox instead. But lo and behold, Proxmox 7 had already reached its End of Life, and I couldn&#39;t find a suitable Ubuntu 24.04 template.</p> <p>In a moment of sanity (or desperation), I decided to upgrade Proxmox to version 8, something I had been putting off for too long. And wouldn&#39;t you know it? The template w

## self-hosted email storage
 - [https://www.reddit.com/r/selfhosted/comments/1i2691n/selfhosted_email_storage](https://www.reddit.com/r/selfhosted/comments/1i2691n/selfhosted_email_storage)
 - RSS feed: $source
 - date published: 2025-01-15T19:58:53+00:00

<!-- SC_OFF --><div class="md"><p>Every now and then there&#39;s a post about hosting or not hosting email per se. For sending out or delivering. This is <em>NOT</em> such one.</p> <p>I am wondering what people use for storing emails, whether they got pulled or delivered or otherwise reached their system.</p> <p>Suppose you have downloaded entire mailbox content off a service like Gmail, it comes as mbox. You can make it a Maildir. You can e.g. put Dovecot over it and have it available via IMAP to whichever clients, but it also makes it horrible to search within or organise.</p> <p>You could perhaps forward it to something like Matrix (or Mattermost, etc.) via a bridge and get some of the database benefits, but then it&#39;s not actionable, as an email and what about exports back to e.g. that mbox if need be one day.</p> <p>So, how do you store your mailboxes, long-term?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/esiy0676"> /u/esiy0676 </a>

## Favorite CalDev task list android client?
 - [https://www.reddit.com/r/selfhosted/comments/1i25hp7/favorite_caldev_task_list_android_client](https://www.reddit.com/r/selfhosted/comments/1i25hp7/favorite_caldev_task_list_android_client)
 - RSS feed: $source
 - date published: 2025-01-15T19:26:07+00:00

<!-- SC_OFF --><div class="md"><p>Just got Vikunja up and hooked into my email to collect all the reminders from my other apps. Anyone have a task/todo client they love that supports CalDev?</p> <p>Trying out the tasks.org app but I&#39;m not liking the interface so much.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SomeBeerDrinker"> /u/SomeBeerDrinker </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i25hp7/favorite_caldev_task_list_android_client/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i25hp7/favorite_caldev_task_list_android_client/">[comments]</a></span>

## Self hosted option for iPhone pictures
 - [https://www.reddit.com/r/selfhosted/comments/1i25aop/self_hosted_option_for_iphone_pictures](https://www.reddit.com/r/selfhosted/comments/1i25aop/self_hosted_option_for_iphone_pictures)
 - RSS feed: $source
 - date published: 2025-01-15T19:17:58+00:00

<!-- SC_OFF --><div class="md"><p>I am new to the self hosted community. Recently did a proxmox setup and looking to replace iCloud photo backups. What are my options or are there any guides for it to work automatically?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/15feet"> /u/15feet </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i25aop/self_hosted_option_for_iphone_pictures/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i25aop/self_hosted_option_for_iphone_pictures/">[comments]</a></span>

## NFS vs SMB for Mounting Storage in My PVE Setup—Which One’s Better?
 - [https://www.reddit.com/r/selfhosted/comments/1i24rls/nfs_vs_smb_for_mounting_storage_in_my_pve](https://www.reddit.com/r/selfhosted/comments/1i24rls/nfs_vs_smb_for_mounting_storage_in_my_pve)
 - RSS feed: $source
 - date published: 2025-01-15T18:56:34+00:00

<!-- SC_OFF --><div class="md"><p>I’m in the process of separating my storage and services. Right now, I’m running PVE for my virtualization platform and using a Ugreen DXP4800Plus NAS for storage. Both are connected via 10Gbps network, and I plan to store my VM templates, images, and LXC containers on the NAS.</p> <p>Now, I’m trying to figure out whether NFS or SMB is the better option for mounting storage. I’m leaning toward NFS but wanted to check if anyone else has experience with this kind of setup. How stable is NFS in a high-performance setup like this? Are there any pitfalls or issues I should be aware of? Thx a lot.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cuzmylegsareshort"> /u/cuzmylegsareshort </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i24rls/nfs_vs_smb_for_mounting_storage_in_my_pve/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i24rls/nfs_vs_smb_for_mountin

## kitshn: App for Tandoor recipes - now on Apple App Store
 - [https://www.reddit.com/r/selfhosted/comments/1i24k0b/kitshn_app_for_tandoor_recipes_now_on_apple_app](https://www.reddit.com/r/selfhosted/comments/1i24k0b/kitshn_app_for_tandoor_recipes_now_on_apple_app)
 - RSS feed: $source
 - date published: 2025-01-15T18:47:36+00:00

<!-- SC_OFF --><div class="md"><p>Hey!</p> <p>I just want to announce that I decided to publish kitshn (mobile client for Tandoor recipes) to the <a href="https://apps.apple.com/us/app/kitshn-for-tandoor/id6740168361">Apple App Store</a>. After some back and forth with the Support Team, I was now able to publish it. 🥳 Please feel free to report any issues or ideas if you&#39;d like :)</p> <p><a href="https://github.com/aimok04/kitshn/">kitshn on GitHub</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aimo_dg18"> /u/aimo_dg18 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i24k0b/kitshn_app_for_tandoor_recipes_now_on_apple_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i24k0b/kitshn_app_for_tandoor_recipes_now_on_apple_app/">[comments]</a></span>

## Do I need multiple instances of Authentik if I want to use a VPS to expose a locally hosted instance?
 - [https://www.reddit.com/r/selfhosted/comments/1i244ik/do_i_need_multiple_instances_of_authentik_if_i](https://www.reddit.com/r/selfhosted/comments/1i244ik/do_i_need_multiple_instances_of_authentik_if_i)
 - RSS feed: $source
 - date published: 2025-01-15T18:29:07+00:00

<!-- SC_OFF --><div class="md"><p>I plan to have two reverse proxies. One on my VPS, and one on my home server.</p> <p>VPS reverse proxy will be for the services I expose externally to the internet, and my home server reverse proxy will be for internal services with local DNS records.</p> <p>The two servers would be connected via Wireguard connection.</p> <p>My question is, I want to use Authentik. I understand how Authentik would work on one server... but not multiple.</p> <p>Say I want to expose my Jellyfin instance within the VPS. I&#39;d use my reverse proxy to expose it. How would I ensure Authentik is also involved? Do I install Authentik also on my VPS? </p> <p><strong>I&#39;m assuming by default that with Wireguard, the VPS will have access to every single container I run on Proxmox. Which means, I&#39;d have to limit access with firewall protocols to only be the intentional service to be exposed, and I assume access to Authentik as well in order for it to work?</strong><br/>

## I have built a tool to manage my docker compose deployments via git. Are you intersted?
 - [https://www.reddit.com/r/selfhosted/comments/1i23av5/i_have_built_a_tool_to_manage_my_docker_compose](https://www.reddit.com/r/selfhosted/comments/1i23av5/i_have_built_a_tool_to_manage_my_docker_compose)
 - RSS feed: $source
 - date published: 2025-01-15T17:54:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey,</p> <p>the tool allows you to configure multiple git repositories containing docker compose files. The tool will pull the repositories and run the composes.</p> <p>Should I open source it or am I the only one who wanted to store and manage his compose files in git repositories?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/davud_bohl"> /u/davud_bohl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i23av5/i_have_built_a_tool_to_manage_my_docker_compose/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i23av5/i_have_built_a_tool_to_manage_my_docker_compose/">[comments]</a></span>

## How to securely operate a plex server (with remote connections)?
 - [https://www.reddit.com/r/selfhosted/comments/1i22nw0/how_to_securely_operate_a_plex_server_with_remote](https://www.reddit.com/r/selfhosted/comments/1i22nw0/how_to_securely_operate_a_plex_server_with_remote)
 - RSS feed: $source
 - date published: 2025-01-15T17:27:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello all,</p> <p>For a number of years now I’ve been running a local plex server for various shows and movies as well as home videos. Setup using trash guides and notifiarr, and accessible remotely via Cloudflare Tunnel and Plex Remote Access (for the app, more on this later).</p> <p>It’s primarily used locally by me and my family but I’ve invited one additional account (my ex) and am looking to invite a few more close friends. “Semi public” is definitely not the best term, as it would be whitelisted and locked down to trusted contacts, but it’s a step beyond just one account and local access only. </p> <p>So I’m trying to figure out what the best practices are to achieve my goals without compromising my network speed or security. </p> <p>Here’s what I feel like I need to know or do already:</p> <p>1.) implement overseerr or similar and get requests working properly. I’ve tried in the past but when episodes are unavailable or a movie doesn’t appear 

## Nas, vps, or other? Looking for direction to get started.
 - [https://www.reddit.com/r/selfhosted/comments/1i22b7q/nas_vps_or_other_looking_for_direction_to_get](https://www.reddit.com/r/selfhosted/comments/1i22b7q/nas_vps_or_other_looking_for_direction_to_get)
 - RSS feed: $source
 - date published: 2025-01-15T17:12:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve got a 4 year old laptop I want to do something with. 16gb of ram and ssd storage, I don&#39;t remember the other specs off the top of my head... I have a much better desktop I use for everything so the laptop has been collecting dust for about a year... </p> <p>I want a storage device I can access over the internet. I&#39;m also interested in hosting game servers for stuff like Minecraft or 7 days to die for my friend group. (not multiple game servers simultaneously just to clarify...) I want to be able to remote access for uploads and downloads from it for personal files and projects. I&#39;m also interested in hosting discord bots I made from it. I do have a buddy I co developed a discord bot with so I would like to give him access to modify it but not access to my other files.</p> <p>What would be the best way to do this? Any help is appreciated as I&#39;ve never tried to do anything like this...</p> </div><!-- SC_ON --> &#32; submitted b

## best option for certs managed with terraform?
 - [https://www.reddit.com/r/selfhosted/comments/1i21npd/best_option_for_certs_managed_with_terraform](https://www.reddit.com/r/selfhosted/comments/1i21npd/best_option_for_certs_managed_with_terraform)
 - RSS feed: $source
 - date published: 2025-01-15T16:45:19+00:00

<!-- SC_OFF --><div class="md"><p>my current setup is a collection of proxmox servers, and I&#39;m in the beginning stages of getting a k3s cluster running on some coreos instances, which is going well. I&#39;m decent at terraform/terragrunt and am very committed to having everything be fully captured in IaC and fully destructible + recreateable from scratch, and am a little lost on how to proceed regarding certs. while most of my stuff is self-hosted, I do have an AWS account, and am not particularly bothered by the idea of running stuff that I consider impractical to self-host (like DNS) in AWS rather than my home network, and have done so for my domain name + a couple other things. I am looking for a service or collection of services that can be easily managed with terraform, either in AWS or in my self-hosted kubernetes cluster, that will automate cert creation + renewal and can be interacted with from terraform so I can consume the created certs in other places in my infrastruct

## Feeling stuck searching for a self-hosted file sharing solution that doesn't force compromises.
 - [https://www.reddit.com/r/selfhosted/comments/1i21iwl/feeling_stuck_searching_for_a_selfhosted_file](https://www.reddit.com/r/selfhosted/comments/1i21iwl/feeling_stuck_searching_for_a_selfhosted_file)
 - RSS feed: $source
 - date published: 2025-01-15T16:39:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been trying to move away from my Synology NAS setup, specifically looking to replace Synology Drive. While Synology isn&#39;t perfect, Drive really nailed something important: it provides a solid collaboration and file sharing platform while still maintaining direct filesystem access through SMB, NFS, SFTP, etc.</p> <p>I&#39;ve given Nextcloud another shot (probably my 10th attempt by now) but I keep running into the same old issues - it just feels sluggish and somewhat unstable in daily use. After some work, I finally figured out how to enable external filesystem access without sending Nextcloud into a conniption fit or having to have all my files owned by `www-data`. While that is at least a step in the right direction it doesn&#39;t change the fact that all the files still need to be owned by the same user, but at-least that user is part of the actual `users` group so I can share the files via SMB and with other apps without breaking thin

## Zerotier with CasaOS?
 - [https://www.reddit.com/r/selfhosted/comments/1i21azi/zerotier_with_casaos](https://www.reddit.com/r/selfhosted/comments/1i21azi/zerotier_with_casaos)
 - RSS feed: $source
 - date published: 2025-01-15T16:30:13+00:00

<!-- SC_OFF --><div class="md"><p>I have Casa in a Prodmox LXC and want to access it using ZT, anyone know how to do this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kraze2341"> /u/kraze2341 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i21azi/zerotier_with_casaos/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i21azi/zerotier_with_casaos/">[comments]</a></span>

## Moving HAOS from an Unraid VM to a secondary server (maybe proxmox?)
 - [https://www.reddit.com/r/selfhosted/comments/1i210fm/moving_haos_from_an_unraid_vm_to_a_secondary](https://www.reddit.com/r/selfhosted/comments/1i210fm/moving_haos_from_an_unraid_vm_to_a_secondary)
 - RSS feed: $source
 - date published: 2025-01-15T16:17:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone! So I currently am running unraid with a 48tb array. Run around 20 various docker containers plus HAOS in a VM. Its running on a N100 mini PC with 12gb ram. Works great for the most part, but I upgraded to this from a previous mini PC with only 8GB ram as I needed more (and the ram isn&#39;t upgradable). </p> <p>The VM does eat a lot of my limited memory, and running Emby and some other things it can get bogged down.</p> <p>I was thinking of just moving the VM to my old mini PC, after doing some reading, proxmox seems like the best os for that? Unless anyone can recommend anything simpler or better. Since that might be overkill for just HAOS, I might want to also move Emby over to it in a Docker container (and point the directories to the unraid share). Freeing up a lot more resources for any file management and various tasks.</p> <p>I read I can easily clone the VM to Proxmox as well. Just want some advice from people who have some expe

## cfex: A Self-Hosted CLI Tool to Share and Test Applications with HTTPS and HTTP/3 Using Cloudflared
 - [https://www.reddit.com/r/selfhosted/comments/1i1zx4m/cfex_a_selfhosted_cli_tool_to_share_and_test](https://www.reddit.com/r/selfhosted/comments/1i1zx4m/cfex_a_selfhosted_cli_tool_to_share_and_test)
 - RSS feed: $source
 - date published: 2025-01-15T15:29:50+00:00

<!-- SC_OFF --><div class="md"><p>I built cfex, a self-hosted CLI tool for quickly sharing web applications for testing, feedback, or demos. It’s built on top of cloudflared and works similarly to ngrok, but with the flexibility of using your own infrastructure.</p> <p>With one command:</p> <p>cfex api.yourdomain.com:8080</p> <p>You can make your app live at <a href="https://api.yourdomain.com">https://api.yourdomain.com</a> with HTTPS and HTTP/3 enabled by default. Perfect for those who prefer self-hosted solutions for secure and fast sharing.</p> <p>Code: <a href="https://github.com/muthuishere/cfex-cli">https://github.com/muthuishere/cfex-cli</a> Article: <a href="https://muthuishere.medium.com/one-command-to-go-live-with-cfex-135d74d81b45">https://muthuishere.medium.com/one-command-to-go-live-with-cfex-135d74d81b45</a></p> <p>Feel free to check it out and share your thoughts!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/muthuishere2101"> 

## I'm releasing my Self-Hosted App: Project Management w/ Boards, Time Tracking, Focus Tools
 - [https://www.reddit.com/r/selfhosted/comments/1i1zu5x/im_releasing_my_selfhosted_app_project_management](https://www.reddit.com/r/selfhosted/comments/1i1zu5x/im_releasing_my_selfhosted_app_project_management)
 - RSS feed: $source
 - date published: 2025-01-15T15:26:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I&#39;m launching my Self-Hosted App for an <strong>All-In-One solution to manage projects, track time and focus</strong>. My goal is to make it <strong>simple yet effective</strong>.</p> <p>I’ve always believed it’s not the tool that makes a project successful but I’ve always wanted one that aligned with <em>my</em> vision: a mix of <strong>Trello, ClickUp, Toggl and Focus-Oriented Tools</strong>.</p> <p>So I&#39;m really happy to have started this project!</p> <p>I hope you like it. Any Idea or Feedbacks are welcome.</p> <p><a href="https://github.com/Eigenfocus/eigenfocus/">https://github.com/Eigenfocus/eigenfocus/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vinioyama"> /u/vinioyama </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zu5x/im_releasing_my_selfhosted_app_project_management/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1

## Dawarich Records.json import failing
 - [https://www.reddit.com/r/selfhosted/comments/1i1zgoe/dawarich_recordsjson_import_failing](https://www.reddit.com/r/selfhosted/comments/1i1zgoe/dawarich_recordsjson_import_failing)
 - RSS feed: $source
 - date published: 2025-01-15T15:09:20+00:00

<!-- SC_OFF --><div class="md"><p>Posted this on Dawarich&#39;s github issue site too but thought maybe someone here would have an answer for me... Basically I am trying to get my Google Takeout timeline history to import through the Dawarich rake task, but it&#39;s failing with errors that seem like it doesn&#39;t know how to handle the json format</p> <p>See the full description here: <a href="https://github.com/Freika/dawarich/issues/663#issue-2787738834">https://github.com/Freika/dawarich/issues/663#issue-2787738834</a></p> <p>Any ideas what I might be doing wrong? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/rswafford"> /u/rswafford </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zgoe/dawarich_recordsjson_import_failing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zgoe/dawarich_recordsjson_import_failing/">[comments]</a></span>

## Daily Time Management app suggestions
 - [https://www.reddit.com/r/selfhosted/comments/1i1zchj/daily_time_management_app_suggestions](https://www.reddit.com/r/selfhosted/comments/1i1zchj/daily_time_management_app_suggestions)
 - RSS feed: $source
 - date published: 2025-01-15T15:04:19+00:00

<!-- SC_OFF --><div class="md"><p>I want to attempt to get better at time management.</p> <p>I have been looking for software that will allow me to create a quick daily schedule.</p> <p>Currently I have an excel workbook with the working hours in 30 min increments. I fill out the blocks of time I want to dedicate to things.</p> <p>What I would like is something where I can create template blocks and then drag them on to a schedule each day.</p> <p>Things like:</p> <ol> <li>Work Meeting</li> <li>Project Time</li> <li>Piano Practice</li> <li>Lunch</li> <li>Work Tasks</li> <li>Home Tasks</li> <li>Study Time</li> </ol> <p>Then I can just open up a daily board and drag my squares and make then the correct length. Anyone know of something like that?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/--Tinman--"> /u/--Tinman-- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zchj/daily_time_management_app_suggestions/">[link]</a><

## Pi-hole and NGX Proxy manager
 - [https://www.reddit.com/r/selfhosted/comments/1i1zalz/pihole_and_ngx_proxy_manager](https://www.reddit.com/r/selfhosted/comments/1i1zalz/pihole_and_ngx_proxy_manager)
 - RSS feed: $source
 - date published: 2025-01-15T15:02:10+00:00

<!-- SC_OFF --><div class="md"><p>I am currently trying to add Pi-hole to the Proxymanager but nothing is working</p> <p>On pi-hole I have added the dns entry.</p> <p>On NGX I have added:<br/> <a href="http://pihole.domain.com">pihole.domain.com</a><br/> http<br/> <a href="http://192.168.1.23">192.168.1.23</a><br/> 9090<br/> Block Common exploits<br/> Websocket support<br/> Added the ssl cert with<br/> Force SSL<br/> HHTP/2 Support<br/> HSTS Enabled</p> <p>And it stays loading forever, any suggestions why is doing that?</p> <p>Same with portainer the only difference is that is https but does the same stay loading the page forever.</p> <p>Any help please</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dc_stuff"> /u/dc_stuff </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zalz/pihole_and_ngx_proxy_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1zalz/pihole_and_ngx_proxy_man

## Unstable Code-Server / Openvscode-server
 - [https://www.reddit.com/r/selfhosted/comments/1i1z770/unstable_codeserver_openvscodeserver](https://www.reddit.com/r/selfhosted/comments/1i1z770/unstable_codeserver_openvscodeserver)
 - RSS feed: $source
 - date published: 2025-01-15T14:58:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have recently been having problems with my self-hosted instance of VS Code. I&#39;ve used both code-server and openvscode-server from the LinuxServer team. I have a Cloudflare Zero Trust tunnel and use my instance of VS Code as an installed Chrome app on a Windows laptop.</p> <p>Recently, I have been facing some problems like freezing or disconnecting and getting &quot;Aw, Snap!&quot; messages. I have checked the logs, and both images have problems with missing files such as:</p> <ul> <li>File not found: /app/openvscode-server/node_modules/vsda/rust/web/vsda_bg.wasm</li> <li>File not found: /app/openvscode-server/node_modules/vsda/rust/web/vsda.js</li> </ul> <p>And that&#39;s it! I am wondering what the problem could be.<br/> Could it be that my Zero Trust tunnel is unstable? If so, how can I diagnose it? I have three connectors for my tunnel on two different devices.</p> <p>My docker-compose looks like this: </p> <pre><code>ser

## How to connect to a VPN ? It's so difficult
 - [https://www.reddit.com/r/selfhosted/comments/1i1yjmm/how_to_connect_to_a_vpn_its_so_difficult](https://www.reddit.com/r/selfhosted/comments/1i1yjmm/how_to_connect_to_a_vpn_its_so_difficult)
 - RSS feed: $source
 - date published: 2025-01-15T14:27:32+00:00

<!-- SC_OFF --><div class="md"><p>Never done that in my life</p> <p>I have a Raspberry Pi 5 (OS : Raspberry Pi OS Lite so i only have commands), installed docker and Portainer and many other things.</p> <p>I have a Proton VPN subscription, how to connect to it and that qbittorrent/ stops downloads if the vpn connection stops ?</p> <p>I watch youtube videos etc but i don&#39;t find anything.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Frnandred"> /u/Frnandred </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1yjmm/how_to_connect_to_a_vpn_its_so_difficult/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1yjmm/how_to_connect_to_a_vpn_its_so_difficult/">[comments]</a></span>

## Best router for self hosting.
 - [https://www.reddit.com/r/selfhosted/comments/1i1ygh7/best_router_for_self_hosting](https://www.reddit.com/r/selfhosted/comments/1i1ygh7/best_router_for_self_hosting)
 - RSS feed: $source
 - date published: 2025-01-15T14:23:20+00:00

<!-- SC_OFF --><div class="md"><p>I just talked a bit with some people I know and I came to the conclusion that a FritzBox is very likely the thing I want. But just in case there is something better I am asking here.</p> <p>I need a router/modem thingy for self hosting my internet. I want to be able to configure everything the way I want with support for: Port Forwarding, IPv4 and 6, 2.5GHz and 5GHz under one SSID, 4+ LAN Ports, an DS Card slot and WPA3. I would also like to setup a VPN at some point but I have no idea if that influences my choice here.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DocEyss"> /u/DocEyss </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ygh7/best_router_for_self_hosting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ygh7/best_router_for_self_hosting/">[comments]</a></span>

## Guest WiFi QR Code Cross-stitch
 - [https://www.reddit.com/r/selfhosted/comments/1i1yd7j/guest_wifi_qr_code_crossstitch](https://www.reddit.com/r/selfhosted/comments/1i1yd7j/guest_wifi_qr_code_crossstitch)
 - RSS feed: $source
 - date published: 2025-01-15T14:18:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1yd7j/guest_wifi_qr_code_crossstitch/"> <img src="https://preview.redd.it/zqbdjwjy16de1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=d3c2e3dd081b547e41f17dd9b53672f634549f93" alt="Guest WiFi QR Code Cross-stitch" title="Guest WiFi QR Code Cross-stitch" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrSlaw"> /u/MrSlaw </a> <br/> <span><a href="https://i.redd.it/zqbdjwjy16de1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1yd7j/guest_wifi_qr_code_crossstitch/">[comments]</a></span> </td></tr></table>

## Feedback welcome - Plex, Audiobooksapp Timeline - Legasea
 - [https://www.reddit.com/r/selfhosted/comments/1i1y8qc/feedback_welcome_plex_audiobooksapp_timeline](https://www.reddit.com/r/selfhosted/comments/1i1y8qc/feedback_welcome_plex_audiobooksapp_timeline)
 - RSS feed: $source
 - date published: 2025-01-15T14:12:38+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1y8qc/feedback_welcome_plex_audiobooksapp_timeline/"> <img src="https://b.thumbs.redditmedia.com/Z1nhndqOouVH9cEQbCK-PEob0vfA6wM7uhSFdaZkHRc.jpg" alt="Feedback welcome - Plex, Audiobooksapp Timeline - Legasea" title="Feedback welcome - Plex, Audiobooksapp Timeline - Legasea" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fimeg"> /u/Fimeg </a> <br/> <span><a href="https://www.reddit.com/gallery/1i1y8qc">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1y8qc/feedback_welcome_plex_audiobooksapp_timeline/">[comments]</a></span> </td></tr></table>

## FOSS IT Helpdesk & FOSS backups solutions
 - [https://www.reddit.com/r/selfhosted/comments/1i1xw6x/foss_it_helpdesk_foss_backups_solutions](https://www.reddit.com/r/selfhosted/comments/1i1xw6x/foss_it_helpdesk_foss_backups_solutions)
 - RSS feed: $source
 - date published: 2025-01-15T13:55:35+00:00

<!-- SC_OFF --><div class="md"><p>As the name implies, reaching out to the community for suggestions on Opensource Helpdesk solutions and Backups </p> <p>for current backups i have <strong>syncthing</strong> going to another server, but just open to migrating to other services and for the helpdesk just inquiring whats good out there. besides forms and excel</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok_Award_2793"> /u/Ok_Award_2793 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1xw6x/foss_it_helpdesk_foss_backups_solutions/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1xw6x/foss_it_helpdesk_foss_backups_solutions/">[comments]</a></span>

## Looking for advice on building a dashboard using WhatsApp Business API: Attendance and Daily Reports
 - [https://www.reddit.com/r/selfhosted/comments/1i1xi8i/looking_for_advice_on_building_a_dashboard_using](https://www.reddit.com/r/selfhosted/comments/1i1xi8i/looking_for_advice_on_building_a_dashboard_using)
 - RSS feed: $source
 - date published: 2025-01-15T13:35:22+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I manage 15 teams (essentially groups) where employees submit daily check-in/check-out messages and brief reports via WhatsApp. I have a WhatsApp Business account and I want to use the API to get real-time access to the messages I receive.</p> <p>My goal is to create a dashboard using Cloudflare Workers and D1 database, where I can easily track attendance and view daily summaries for each group. I’m planning to use a lightweight LLM (maybe Workers AI - BERT?) to analyze and summarize the reports daily for each group.</p> <p>From my research, it seems like WhatsApp does not charge for receiving messages via their API. Has anyone implemented something similar? Any advice or suggestions would be greatly appreciated!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yeeeeeeaaaboi"> /u/yeeeeeeaaaboi </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1x

## Feedback for OneUptime: Open Source Monitoring and Observability Platform
 - [https://www.reddit.com/r/selfhosted/comments/1i1xa72/feedback_for_oneuptime_open_source_monitoring_and](https://www.reddit.com/r/selfhosted/comments/1i1xa72/feedback_for_oneuptime_open_source_monitoring_and)
 - RSS feed: $source
 - date published: 2025-01-15T13:23:44+00:00

<!-- SC_OFF --><div class="md"><p>We&#39;re building an open source observability platform - OneUptime (<a href="https://oneuptime.com">https://oneuptime.com</a>). Think of it as your open-source alternative to Datadog, NewRelic, PagerDuty, and Incident.io—100% FOSS and Apache Licensed.</p> <p>Already using OneUptime? Huge thanks! We’d love to hear your feedback.</p> <p>Not on board yet? We’re curious why and eager to know how we can better serve your needs. What features would you like to see implemented? We listen to this community very closely and will ship updates for you all.</p> <p>Looking forward to hearing your thoughts and feedback!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OuPeaNut"> /u/OuPeaNut </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1xa72/feedback_for_oneuptime_open_source_monitoring_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1xa72/feedback_for_on

## ownCloud + Syncthing to sync Obsidian?
 - [https://www.reddit.com/r/selfhosted/comments/1i1x03x/owncloud_syncthing_to_sync_obsidian](https://www.reddit.com/r/selfhosted/comments/1i1x03x/owncloud_syncthing_to_sync_obsidian)
 - RSS feed: $source
 - date published: 2025-01-15T13:08:41+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I was wandering if anyone had tested this approach to handle sync across multiple devices (of which, for my use case, one is an Android phone and another is a linux server/NAS):</p> <ul> <li>So on the NAS I host ownCloud and Syncthing</li> <li>On my ownCloud files I create a &quot;Notes&quot; folder</li> <li>To use Osbidian on desktop clients I simply install the ownCloud client or mount the webdav and the sync should be handled by the client or the system</li> <li>To sync with the Android phone, my idea was to let Syncthing have access to the files managed by ownCloud and share the Notes folder through Syncthing</li> </ul> <p>My questions are:</p> <p>1) Would this work? 2) Would there be problems with ownCloud and its indexing? 3) Would this be much simpler if I used FolderSync? 4) Is FolderSync enough or should I go with the PRO version? 5) Are there FOSS alternatives to this? 6) Why the hell did Google decide it was a good idea to not l

## Searching for WebDAV Client with VFS support
 - [https://www.reddit.com/r/selfhosted/comments/1i1w0hj/searching_for_webdav_client_with_vfs_support](https://www.reddit.com/r/selfhosted/comments/1i1w0hj/searching_for_webdav_client_with_vfs_support)
 - RSS feed: $source
 - date published: 2025-01-15T12:09:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello everybody ^^<br/> I want to replace my nextcloud instance with something more lightweight, since I don&#39;t need all the added features that nextcloud offers. I already found a pretty solid webdav solution (also with a good and simple UI) by abusing <a href="https://sftpgo.com/">SFTPgo</a> and only using it for it&#39;s webdav functionality.</p> <p>So now for my question: I&#39;ve been searching for a webdav client that does the same as the nextcloud client. Create a virtual filesystem on my device and downloading files on demand (if not specified to keep them on the device all the time), uploading files in that folder if a connection to the server is possible and handle file collisions gracefully.<br/> Dos anybody know a good client for this usecase? I haven&#39;t found anything in my three day search quest until now :/</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CryoAT"> /u/CryoAT </a> <br/> <span><

## GoIP 8-Channel VoIP Gateway – Ideal for Call Centers & SIM Management
 - [https://www.reddit.com/r/selfhosted/comments/1i1vwfz/goip_8channel_voip_gateway_ideal_for_call_centers](https://www.reddit.com/r/selfhosted/comments/1i1vwfz/goip_8channel_voip_gateway_ideal_for_call_centers)
 - RSS feed: $source
 - date published: 2025-01-15T12:02:26+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1vwfz/goip_8channel_voip_gateway_ideal_for_call_centers/"> <img src="https://external-preview.redd.it/9EnWCfEJ9FE7QAlRuOQZ_mkPUbyggHPtLixst1D41sk.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=350dcc3a5e0be7059816e88016613ccf6ae961d1" alt="GoIP 8-Channel VoIP Gateway – Ideal for Call Centers &amp; SIM Management" title="GoIP 8-Channel VoIP Gateway – Ideal for Call Centers &amp; SIM Management" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Equivalent_Tea3633"> /u/Equivalent_Tea3633 </a> <br/> <span><a href="https://www.ebay.com/itm/396125507826?mkcid=16&amp;mkevt=1&amp;mkrid=711-127632-2357-0&amp;ssspo=30_0upp1qm6&amp;sssrc=2524149&amp;ssuid=30_0upp1qm6&amp;widget_ver=artemis&amp;media=REDDIT">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1vwfz/goip_8channel_voip_gateway_ideal_for_call_centers/">[comments]</a></span> </td></tr></table>

## Best Passive Income App - Biggest Airdrop in DePIN Incoming Join Early ( $112m Funding )
 - [https://www.reddit.com/r/selfhosted/comments/1i1v5x5/best_passive_income_app_biggest_airdrop_in_depin](https://www.reddit.com/r/selfhosted/comments/1i1v5x5/best_passive_income_app_biggest_airdrop_in_depin)
 - RSS feed: $source
 - date published: 2025-01-15T11:12:32+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1v5x5/best_passive_income_app_biggest_airdrop_in_depin/"> <img src="https://preview.redd.it/1x3hpbz155de1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=608fe2b1c779c637de869fad8d1cf88c27f068e7" alt="Best Passive Income App - Biggest Airdrop in DePIN Incoming Join Early ( $112m Funding )" title="Best Passive Income App - Biggest Airdrop in DePIN Incoming Join Early ( $112m Funding )" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Use invite code - damonsalvate - to instantly receive 200 coins </p> <p>Welcome to the Silencio community! Silencio is a unique project designed to help people reconnect with the power of silence and mindfulness in a fast-paced, noisy world. But it’s more than just a philosophy—it’s also a growing ecosystem that blends technology and tranquility.</p> <p>How Does Silencio Work? At its core, Silencio promotes practices and tools that encourage mindfulness, meditation, and digital 

## Text to Speech for eBook to Audio books
 - [https://www.reddit.com/r/selfhosted/comments/1i1uy33/text_to_speech_for_ebook_to_audio_books](https://www.reddit.com/r/selfhosted/comments/1i1uy33/text_to_speech_for_ebook_to_audio_books)
 - RSS feed: $source
 - date published: 2025-01-15T10:57:34+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://claudio.uk/posts/epub-to-audiobook.html">https://claudio.uk/posts/epub-to-audiobook.html</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/psychiatric_hippo"> /u/psychiatric_hippo </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1uy33/text_to_speech_for_ebook_to_audio_books/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1uy33/text_to_speech_for_ebook_to_audio_books/">[comments]</a></span>

## Help with self-hosting Pixelfed – not a developer!
 - [https://www.reddit.com/r/selfhosted/comments/1i1ujo7/help_with_selfhosting_pixelfed_not_a_developer](https://www.reddit.com/r/selfhosted/comments/1i1ujo7/help_with_selfhosting_pixelfed_not_a_developer)
 - RSS feed: $source
 - date published: 2025-01-15T10:27:05+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to self-host Pixelfed, but I’m a tech enthusiast, not a developer. </p> <p>I’ve followed the official documentation and set up a virtual machine on Google Cloud, installed Docker, and completed the installation steps, but I’m running into issues – particularly with database privileges – even though I’ve followed the instructions carefully.</p> <p>I may have missed something along the way and I&#39;m having trouble troubleshooting it. I’ve already posted on GitHub, but I’m wondering if anyone here has set up Pixelfed before and can point me in the right direction, or knows of a more detailed step-by-step guide.</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beatrootbird"> /u/beatrootbird </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ujo7/help_with_selfhosting_pixelfed_not_a_developer/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r

## self-hosted NetBird: force use regional relay for clients and routing traffic via ISP private network
 - [https://www.reddit.com/r/selfhosted/comments/1i1uivl/selfhosted_netbird_force_use_regional_relay_for](https://www.reddit.com/r/selfhosted/comments/1i1uivl/selfhosted_netbird_force_use_regional_relay_for)
 - RSS feed: $source
 - date published: 2025-01-15T10:25:23+00:00

<!-- SC_OFF --><div class="md"><p>Is it possible to set it up so that clients are forced to use a relay in certain regions, and the relay itself uses the ISP&#39;s private network to communicate with other peers for self-hosted NetBird, OVH vRack in my case?<br/> What I mean is this:<br/> I have clients(my friends are gamers) in Asia on the Internet, but they have very high latency to the EU game servers, I want to put a relay and/or peer on servers in Asia and do the following setup: clients should be forced to connect to the relay/peer in Asia and the servers should route traffic through the ISP&#39;s private network to my exit node in Europe so that the latency is acceptable (I don&#39;t know how OVH does it, but it works), and it would be great if I could cut out the ip addresses of these countries so that clients do not try to send traffic to their regional game servers through netbird.<br/> Sorry, I tried to find the information myself but without success, was going to post in 

## Campsite - A team communication app open-sourced their entire code-base
 - [https://www.reddit.com/r/selfhosted/comments/1i1uaex/campsite_a_team_communication_app_opensourced](https://www.reddit.com/r/selfhosted/comments/1i1uaex/campsite_a_team_communication_app_opensourced)
 - RSS feed: $source
 - date published: 2025-01-15T10:07:34+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1uaex/campsite_a_team_communication_app_opensourced/"> <img src="https://external-preview.redd.it/PypCoDCjwGdEsLBv6Pxi7IC72bj_1p6rbiPmJ8xH4SM.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=a1643753d559589bfb3669d1ccb7d4fe136b40b2" alt="Campsite - A team communication app open-sourced their entire code-base" title="Campsite - A team communication app open-sourced their entire code-base" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vihar_kurama3"> /u/vihar_kurama3 </a> <br/> <span><a href="https://github.com/campsite/campsite">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1uaex/campsite_a_team_communication_app_opensourced/">[comments]</a></span> </td></tr></table>

## Adding random self-hosted wallpaper to your dashboards
 - [https://www.reddit.com/r/selfhosted/comments/1i1u9i2/adding_random_selfhosted_wallpaper_to_your](https://www.reddit.com/r/selfhosted/comments/1i1u9i2/adding_random_selfhosted_wallpaper_to_your)
 - RSS feed: $source
 - date published: 2025-01-15T10:05:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1u9i2/adding_random_selfhosted_wallpaper_to_your/"> <img src="https://preview.redd.it/mtg4yne0t4de1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=36157bb4f2084272aaa21c1131d3c0c767ccab5e" alt=" Adding random self-hosted wallpaper to your dashboards " title=" Adding random self-hosted wallpaper to your dashboards " /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hakunin_Fallout"> /u/Hakunin_Fallout </a> <br/> <span><a href="https://i.redd.it/mtg4yne0t4de1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1u9i2/adding_random_selfhosted_wallpaper_to_your/">[comments]</a></span> </td></tr></table>

## Player like Navidrome etc - but that has extra fields like Record Label?
 - [https://www.reddit.com/r/selfhosted/comments/1i1u0t8/player_like_navidrome_etc_but_that_has_extra](https://www.reddit.com/r/selfhosted/comments/1i1u0t8/player_like_navidrome_etc_but_that_has_extra)
 - RSS feed: $source
 - date published: 2025-01-15T09:47:30+00:00

<!-- SC_OFF --><div class="md"><p>is there such a thing as a music library / player that would enable me to group / filter / sort by Record Label, where it exists in the track&#39;s metadata? I have a collection that is much more geared around labels than artists and would like to be able to view, for example, the &#39;Crispy Recordings&#39; catalogue much more than album or artist or genre or whatever</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrispyBegs"> /u/CrispyBegs </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1u0t8/player_like_navidrome_etc_but_that_has_extra/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1u0t8/player_like_navidrome_etc_but_that_has_extra/">[comments]</a></span>

## I built icloudpd-web for those who enjoy web interface
 - [https://www.reddit.com/r/selfhosted/comments/1i1sznp/i_built_icloudpdweb_for_those_who_enjoy_web](https://www.reddit.com/r/selfhosted/comments/1i1sznp/i_built_icloudpdweb_for_those_who_enjoy_web)
 - RSS feed: $source
 - date published: 2025-01-15T08:25:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1sznp/i_built_icloudpdweb_for_those_who_enjoy_web/"> <img src="https://external-preview.redd.it/iGjBMKPhEyNCKP7gHM_sHaJGqA5rdLST8GvmW_m99ps.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=5587b1944e54e556e9c7b4a6cc71e9dfd4467494" alt="I built icloudpd-web for those who enjoy web interface" title="I built icloudpd-web for those who enjoy web interface" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Long story short, I rely heavily on icloud photos to store data for my family (and my photography work since its support for RAW files) but I do not want to keep all my data just with Apple. Here comes <a href="https://github.com/icloud-photos-downloader/icloud_photos_downloader">icloudpd</a>, a great CLI tool written in python to download your photos. I have been using it but I never enjoyed having to work in a terminal environment to deal with daily life stuff while others might do. That made me build this app 

## Multiple services on same domain - how to?
 - [https://www.reddit.com/r/selfhosted/comments/1i1s9yk/multiple_services_on_same_domain_how_to](https://www.reddit.com/r/selfhosted/comments/1i1s9yk/multiple_services_on_same_domain_how_to)
 - RSS feed: $source
 - date published: 2025-01-15T07:29:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, another noob here, First off, any recommendations on books/learning material which starts with basics and slowly goes into secure hosting? I tend to grasp a lot, make 20 steps forward and then fall into a canyon...</p> <p>I&#39;ve got a website (domain with company A, hosted by company B) and all works fine on <a href="http://www.mydomainexample.com.au">www.mydomainexample.com.au</a>, but was wondering what the process would be to add a self hosted service pointed at (for example) backoffice.mydomain.com.au etc etc (i.e. my ERP accessible via public)</p> <p>Would this involve the purchase of another domain?</p> <p>Thanks guys AtR</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AndyTheRanga"> /u/AndyTheRanga </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1s9yk/multiple_services_on_same_domain_how_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/com

## Open WebUI
 - [https://www.reddit.com/r/selfhosted/comments/1i1s0dq/open_webui](https://www.reddit.com/r/selfhosted/comments/1i1s0dq/open_webui)
 - RSS feed: $source
 - date published: 2025-01-15T07:09:09+00:00

<!-- SC_OFF --><div class="md"><p>I <em>finally</em> got Open WebUI working on AWS t2-micro with custom domain and HTTPS. Won’t be running LLMs on it, just using OpenRouter API. This is meant to replace ChatGPT and Claude (apps/subscriptions) and economise by using the same API credits I purchase for Cline/Aider.</p> <p>Honestly, this took a lot out of me because I’m not an expert at Python or AWS by any stretch of the imagination. Now I’m just exhausted and wondering whether the new tools OpenAI and Anthropic are putting in their apps are in fact worth the subscriptions. Is there such a thing as self-hosting fatigue? Ugh!</p> <p>Still, I can now use <a href="https://ai.mydomain.com">https://ai.mydomain.com</a> anywhere now with any/multiple LLMs.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/clericrobe"> /u/clericrobe </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1s0dq/open_webui/">[link]</a></span> &#32; <span><a h

## Most complete and robust tasks solution?
 - [https://www.reddit.com/r/selfhosted/comments/1i1rm07/most_complete_and_robust_tasks_solution](https://www.reddit.com/r/selfhosted/comments/1i1rm07/most_complete_and_robust_tasks_solution)
 - RSS feed: $source
 - date published: 2025-01-15T06:40:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been struggling with this since I started my self-hosting journey years ago.</p> <p>How do you all keep track of your tasks? The three main capabilities that I take into account when evaluating task solutions are</p> <ul> <li>Flexebility</li> <li>Portability</li> <li>Extensibility</li> </ul> <p>By flexibility, I mean, how advanced can the tasks become? I ran into seemingly random limitations with solutions like Google Tasks, ie. you can create subtasks and recurring tasks, but subtasks <strong>cannot</strong> be recurring tasks...</p> <p>By portability, I mean, how easy would it be to export or migrate my tasks from this system to another? This is to avoid walled-garden ecosystems where my tasks would be trapped in some proprietary format</p> <p>By extensibility, I mean, is there any ecosystem and array of plugins/applications to support it? ie. ability to sync tasks across devices and modify tasks from a mobile app</p> <p>I&#39;ve seen a fe

## What is the best way to go about networking my home server?
 - [https://www.reddit.com/r/selfhosted/comments/1i1q7cn/what_is_the_best_way_to_go_about_networking_my](https://www.reddit.com/r/selfhosted/comments/1i1q7cn/what_is_the_best_way_to_go_about_networking_my)
 - RSS feed: $source
 - date published: 2025-01-15T05:07:05+00:00

<!-- SC_OFF --><div class="md"><p>I know this kind of question gets asked a lot but I keep finding conflicting answers everywhere I look. I&#39;ll start this off by telling you what I&#39;m running. I currently have some decent parts thrown in a case with 3 18TB drives in a RAIDz1 running truenas. I currently have setup a full *ARR stack using dockge with Jellyfin, and QBittorrent, attached by gluetun, to protonVPN. Everything is working and I have things torrenting and besides some config tweaking left, everything is how I want it. I have been doing research on my last step which is accessing everything outside my home network. I currently am running cloudflared to use cloudflare tunnels with my domain name to prevent port forwarding my server, toggling it on and off when I want to work on some stuff outside my house, mainly keeping it off for now until I find a better solution. I also can&#39;t use this to access Jellyfin as it&#39;s against cloudflares TOS, and also heard other pe

## Preventing IP Access to LAN Services, Only Allow Domain Name
 - [https://www.reddit.com/r/selfhosted/comments/1i1pv5q/preventing_ip_access_to_lan_services_only_allow](https://www.reddit.com/r/selfhosted/comments/1i1pv5q/preventing_ip_access_to_lan_services_only_allow)
 - RSS feed: $source
 - date published: 2025-01-15T04:47:00+00:00

<!-- SC_OFF --><div class="md"><p>I currently have Nginx Proxy Manager (NPM) running with DNS &amp; SSL through Cloudflare. I recently decided to begin to implement SSO for my services using Authentik. However, I&#39;m realizing that on services without built-in Authentication or where it has to be disabled to avoid double-logins, the authentication can be completely bypassed by just typing in the IP &amp; Port over LAN (e.g. <a href="http://192.168.100.100:5001">http://192.168.100.100:5001</a>). </p> <p>How can I prevent access over direct IP over LAN? I couldn&#39;t find any resources online and ChatGPT configurations weren&#39;t working. It would have to either be an advanced configuration in NPM or a custom .conf file added manually to NPM. My goal is to (a) not allow users to bypass auth and (b) avoid people using insecure HTTP connections. I do not currently have a local DNS server - would I need one in order to make this happen? </p> </div><!-- SC_ON --> &#32; submitted by &#3

## Huge color diference between my downloaded movies and online version
 - [https://www.reddit.com/r/selfhosted/comments/1i1pkn6/huge_color_diference_between_my_downloaded_movies](https://www.reddit.com/r/selfhosted/comments/1i1pkn6/huge_color_diference_between_my_downloaded_movies)
 - RSS feed: $source
 - date published: 2025-01-15T04:29:28+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1pkn6/huge_color_diference_between_my_downloaded_movies/"> <img src="https://b.thumbs.redditmedia.com/kFnAb1qilU4lwuWNzDr3RwU-3E0X2Xi88Vb5_wCagnI.jpg" alt="Huge color diference between my downloaded movies and online version" title="Huge color diference between my downloaded movies and online version" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/0pcsvv4v43de1.png?width=997&amp;format=png&amp;auto=webp&amp;s=dd5bee10846fb16d689e5906cd22f2a5f2cd2ece">https://preview.redd.it/0pcsvv4v43de1.png?width=997&amp;format=png&amp;auto=webp&amp;s=dd5bee10846fb16d689e5906cd22f2a5f2cd2ece</a></p> <p>left my home server / right streamio</p> <p>also happens with dune 1 and 2 and all of the lord of the ring movies so i dont think its because is a different cut.maybe some codec issue? everything looks bland and it lacks contrast</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="http

## Solutions for public & private services?
 - [https://www.reddit.com/r/selfhosted/comments/1i1o87q/solutions_for_public_private_services](https://www.reddit.com/r/selfhosted/comments/1i1o87q/solutions_for_public_private_services)
 - RSS feed: $source
 - date published: 2025-01-15T03:14:08+00:00

<!-- SC_OFF --><div class="md"><p>Have been playing around with self-hosting some services on a pretty simple Linux machine - currently running everything out of docker / compose.</p> <p>Initially these were all &quot;private&quot; services, had the machine sitting in my router&#39;s DMZ running wg-easy (an out of the box wireguard solution), traefik and home assistant. This worked pretty good and did exactly what I needed it to, but then I had the thought of taking some of my websites off of cloud hosting and shoving them onto this box.</p> <p>I&#39;m by no means a network wizard, and looking into iptables did my head in. Has anyone else done something similar in this space? Is using a VPN not viable for what I want here? Keen to hear thoughts.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dr_Oatmeal"> /u/Dr_Oatmeal </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1o87q/solutions_for_public_private_services/">[link]</a

## Backing up docker container persistent data for local bind mounts
 - [https://www.reddit.com/r/selfhosted/comments/1i1o3s4/backing_up_docker_container_persistent_data_for](https://www.reddit.com/r/selfhosted/comments/1i1o3s4/backing_up_docker_container_persistent_data_for)
 - RSS feed: $source
 - date published: 2025-01-15T03:07:33+00:00

<!-- SC_OFF --><div class="md"><p>If you are like me and you use a single directory for all docker containers in your home server and have a docker compose for each container with local folders mapped as volumes to those containers for persistent data like databases and config files, how do you manage the file permissions and ownership of the files created by the containers in those folders.</p> <p>There are many containers that will generate the persistent files as root, this creates an issue for me as I have default user <code>cron</code> backup script that runs <code>rclone</code> and I have had to change ownership of container volume files manually multiple time to have this script run correctly. Every other week my healthcheck says my cron is down due to some file permission issue for some file/folder or the other.</p> <p>Each time i add a new container to my stack, i have to do these shenanigans again. A good fallback that has worked for me was having the rclone script being ex

## I build 2 demo repos — one for provisioning Digital Ocean server with Terraform, another to deploy frontend/backend with Kamal 2
 - [https://www.reddit.com/r/selfhosted/comments/1i1o2j0/i_build_2_demo_repos_one_for_provisioning_digital](https://www.reddit.com/r/selfhosted/comments/1i1o2j0/i_build_2_demo_repos_one_for_provisioning_digital)
 - RSS feed: $source
 - date published: 2025-01-15T03:05:44+00:00

<!-- SC_OFF --><div class="md"><p>I normally use Render, but looked into self-hosting some stuff a few weeks ago. Took a few days to figure out so I clean my repos up and pushed to GitHub. While I wrote them for hosting my services, they ought to be useful for hosting your own apps/data. Let me know if you find it useful.</p> <p>Wrote them up at <a href="https://hboon.com/terraform-and-kamal-for-digital-ocean-demo-repositories/">https://hboon.com/terraform-and-kamal-for-digital-ocean-demo-repositories/</a>. Contains links to the the GitHub repos.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/h____"> /u/h____ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1o2j0/i_build_2_demo_repos_one_for_provisioning_digital/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1o2j0/i_build_2_demo_repos_one_for_provisioning_digital/">[comments]</a></span>

## Nginx Mobile Dashboard: App made with AI available for download
 - [https://www.reddit.com/r/selfhosted/comments/1i1nx38/nginx_mobile_dashboard_app_made_with_ai_available](https://www.reddit.com/r/selfhosted/comments/1i1nx38/nginx_mobile_dashboard_app_made_with_ai_available)
 - RSS feed: $source
 - date published: 2025-01-15T02:58:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i1nx38/nginx_mobile_dashboard_app_made_with_ai_available/"> <img src="https://external-preview.redd.it/rb_z94Xw5YPgU21R_AKNkROUVKb7PsktU7vjQr6B8GE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f7835cffe98da6e3e7ffa3e0e6bb8d35d03cf770" alt="Nginx Mobile Dashboard: App made with AI available for download" title="Nginx Mobile Dashboard: App made with AI available for download" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hi, like a lot of folks, over the Christmas break I tried if * anyone * could make apps using AI. I am not a developer. I&#39;ve always used NPM as a dashboard to see which of my internal IPs map to my domains (homelab), always hated the web UI + credentials part -- wished there was an iPhone app... so I decided to make one.</p> <p><strong>iPhone:</strong> The result is now available for download on the <a href="https://apps.apple.com/us/app/nginix-mobile-dashboard/id6740245899">Apple App 

## handling media requests
 - [https://www.reddit.com/r/selfhosted/comments/1i1nky9/handling_media_requests](https://www.reddit.com/r/selfhosted/comments/1i1nky9/handling_media_requests)
 - RSS feed: $source
 - date published: 2025-01-15T02:40:05+00:00

<!-- SC_OFF --><div class="md"><p>i know that everyone recommends/mentions overseer, but i dont run an arr stack, and get a lot of requests that aren&#39;t necessarily for plex anyway (trying to get away from plex anyway)</p> <p>currently using google keep notes with checkboxes shared between me and the end-user as a collaborator. they add what they want to the note, and i check it off when its up.</p> <p>it <em>works</em>, but was wondering how users here are handling requests, and if there was something a little more elegant out there that isnt built around automation.</p> <p>anything that supports OIDC is a huge plus</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xrichNJ"> /u/xrichNJ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1nky9/handling_media_requests/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1nky9/handling_media_requests/">[comments]</a></span>

## Question on Music Self-hosting Apps
 - [https://www.reddit.com/r/selfhosted/comments/1i1nfsf/question_on_music_selfhosting_apps](https://www.reddit.com/r/selfhosted/comments/1i1nfsf/question_on_music_selfhosting_apps)
 - RSS feed: $source
 - date published: 2025-01-15T02:32:29+00:00

<!-- SC_OFF --><div class="md"><p>Basically, I am very content with my directory organization for my massive music collection, zero brag, it ruins the &#39;album&#39; or &#39;artist&#39; organization as scrolling through thousands of artists or albums is ridiculous.</p> <p>Anyway, I&#39;m new to this and amazed by Jellyfin and how great it is to stream from home. I&#39;m using finamp and I&#39;m wondering if there is a way to just browse my directories, or if there is a better app, or if Jellyfin is not the right service for my usecase.</p> <p>Thanks a lot for letting me know about this in the first place, appreciate it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/metricspace-"> /u/metricspace- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1nfsf/question_on_music_selfhosting_apps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1nfsf/question_on_music_selfhosting_apps/">[comme

## Better tool for logs?
 - [https://www.reddit.com/r/selfhosted/comments/1i1n368/better_tool_for_logs](https://www.reddit.com/r/selfhosted/comments/1i1n368/better_tool_for_logs)
 - RSS feed: $source
 - date published: 2025-01-15T02:14:11+00:00

<!-- SC_OFF --><div class="md"><p>I usually check logs when something goes wrong. Most of the time, I will click on the logs icon for a docker container using the portainer ui. As I have built out my services, this seems more and more burdensome to do. I think what I need is a central location to look at all the logs I have, whether they are running as containers or otherwise.</p> <p>The amount of different tools for logs seems insane to me. Something like granfana seems more like a tool to visualize metrics than for being able to quickly go through logs (though I believe it can also do that). I guess I am mainly looking for a lightweight tool that can help quickly and easily access logs?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ottovonbizmarkie"> /u/ottovonbizmarkie </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1n368/better_tool_for_logs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhost

## I don't get proxmox and LXC
 - [https://www.reddit.com/r/selfhosted/comments/1i1lwxc/i_dont_get_proxmox_and_lxc](https://www.reddit.com/r/selfhosted/comments/1i1lwxc/i_dont_get_proxmox_and_lxc)
 - RSS feed: $source
 - date published: 2025-01-15T01:14:37+00:00

<!-- SC_OFF --><div class="md"><p>Im terribly sorry this is a stupid question but I&#39;ve started out with my homelab journey with a bare metal linux install and docker containers running a media server, *arr stack, a dashboard, paperless-ngx, etc and now that i finally got something more powerful for my homelab upgrading from my raspberry pi I assumed a proxmox install would be my next step because that&#39;s what i see everywhere but i just don&#39;t understand the use case, why would you want to manage so many different vms? Why even use different vms, how are LXC containers better? Ive never seen an option to get them on the GitHub page of a project, why hoolahoop and map so many things to get your config files in one place when you can just map the config directory from a docker container</p> <p>I just don&#39;t understand the use case, if you use it please chime in and help me understand why you do over just a single debian or fedora server install and run everything in docker

## Physical Movies/TV shows Cataloging App
 - [https://www.reddit.com/r/selfhosted/comments/1i1ltpp/physical_moviestv_shows_cataloging_app](https://www.reddit.com/r/selfhosted/comments/1i1ltpp/physical_moviestv_shows_cataloging_app)
 - RSS feed: $source
 - date published: 2025-01-15T01:10:12+00:00

<!-- SC_OFF --><div class="md"><p>I am currently running Tellico locally on my computer to track all my physical movies and tv shows that i own. I would like to have something that can run as selfhosted app on my NAS. Does anyone know of a good piece of software like Tellico or Collectorz Movie Collector that I can run a NAS web app? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thejollylolly"> /u/thejollylolly </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ltpp/physical_moviestv_shows_cataloging_app/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ltpp/physical_moviestv_shows_cataloging_app/">[comments]</a></span>

## Homelab as Code
 - [https://www.reddit.com/r/selfhosted/comments/1i1kl19/homelab_as_code](https://www.reddit.com/r/selfhosted/comments/1i1kl19/homelab_as_code)
 - RSS feed: $source
 - date published: 2025-01-15T00:10:07+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve kept my Homelab config (docker compose files, Ansible playbooks, OpenTofu, Packer, etc) in a Git repo and this has been the source of truth for my Homelab for a few years now. </p> <p>I have a bunch of workflows to automate alot of the repetitive tasks (Docker stack redeploy, Tofu deployments, yamllint)</p> <p>It started out as just a way to keep things updated, without having to use Watchtower and potentially break something, now it has morphed into almost everything that can make up a Homelab and is now treated as Infrastructure as Code</p> <p>This has been entirely custom as I have not yet seen any other Git repos that do the same thing, with that I&#39;m sort of running out of ideas to keep expanding on this. (Can keep adding stuff like authentik config to OpenTofu)</p> <p>All that being said, if you have a similar setup to mine and post your Homelab to VCS, I would love to see your repo so I can steal some of your ideas. Or if you just 

## Can I host a Netbird controller if my ISP blocks ports 80 and 443?
 - [https://www.reddit.com/r/selfhosted/comments/1i1ki0u/can_i_host_a_netbird_controller_if_my_isp_blocks](https://www.reddit.com/r/selfhosted/comments/1i1ki0u/can_i_host_a_netbird_controller_if_my_isp_blocks)
 - RSS feed: $source
 - date published: 2025-01-15T00:06:14+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to set up Netbird to create a VPN between different services in various locations. I&#39;ve decided to self-host the controller, and my plan is to use a Proxmox container for this purpose. I also have a Cloudflare domain that I can leverage for either a tunnel or DDNS to expose the server.</p> <p>However, my ISP blocks ports 80 and 443, which raises a concern since the documentation specifies:</p> <blockquote> </blockquote> <p>Is it still possible to set up the Netbird controller under these circumstances? If so, what would be the best approach to bypass this limitation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brunomoreirab"> /u/brunomoreirab </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ki0u/can_i_host_a_netbird_controller_if_my_isp_blocks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i1ki0u/can_i_host_a_netbird_controll

