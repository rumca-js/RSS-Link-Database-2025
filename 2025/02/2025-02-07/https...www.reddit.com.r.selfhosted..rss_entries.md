# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## Looking for a howto for self hosting maps
 - [https://www.reddit.com/r/selfhosted/comments/1ik9e18/looking_for_a_howto_for_self_hosting_maps](https://www.reddit.com/r/selfhosted/comments/1ik9e18/looking_for_a_howto_for_self_hosting_maps)
 - RSS feed: $source
 - date published: 2025-02-07T23:46:17+00:00

<!-- SC_OFF --><div class="md"><p>I would like to self host open street maps, or some sort of tiled version of it (I think that is the term). It seems like natively hosting requires tons of resources. Is there a nice docker implementation or a howto for getting it running on bare metal Linux? Use case would be for myself and family. Hoping to get it running on a Pi 4 or similarly powered device.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AppointmentNearby161"> /u/AppointmentNearby161 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik9e18/looking_for_a_howto_for_self_hosting_maps/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik9e18/looking_for_a_howto_for_self_hosting_maps/">[comments]</a></span>

## How do you find new self-hosted software?
 - [https://www.reddit.com/r/selfhosted/comments/1ik955y/how_do_you_find_new_selfhosted_software](https://www.reddit.com/r/selfhosted/comments/1ik955y/how_do_you_find_new_selfhosted_software)
 - RSS feed: $source
 - date published: 2025-02-07T23:34:52+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I was wondering how do you usually find new self-hosted software? Are you just scrolling through github and this reddit community or do you use lists like awesome selfhosted, selfhst store or selfhst ?</p> <p>I&#39;m always on the lookout for interesting projects to self-host, and sometimes I feel like I&#39;m missing out on some hidden gems</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ApprehensivePass3726"> /u/ApprehensivePass3726 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik955y/how_do_you_find_new_selfhosted_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik955y/how_do_you_find_new_selfhosted_software/">[comments]</a></span>

## What to use for backups (replacing duplicati)
 - [https://www.reddit.com/r/selfhosted/comments/1ik9469/what_to_use_for_backups_replacing_duplicati](https://www.reddit.com/r/selfhosted/comments/1ik9469/what_to_use_for_backups_replacing_duplicati)
 - RSS feed: $source
 - date published: 2025-02-07T23:33:38+00:00

<!-- SC_OFF --><div class="md"><p>I have been using duplicati but I noticed today that it is completely broken in many ways, which I won&#39;t go into, but the fact that it broke does not give me a lot of confidence in relying in it for backups. I&#39;m looking for a replacement.</p> <p>My requirements are a free solution to compress, encrypt, and upload local files on my nas to google drive or similar. Duplicati was perfect for this as I could mount the relevant volumes into the duplicati container and back them up... until it stopped working. Preferably something that can be run in container with an easy GUI.</p> <p>The files are mostly my docker volumes, to make reconfiguring my nas easier if I ever have to. But there are some other important backups too. All files are about 12GB.</p> <p>Any suggestions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gazm2k5"> /u/gazm2k5 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/

## Office 365/PST to Mailcow/IMAP Server
 - [https://www.reddit.com/r/selfhosted/comments/1ik8hyf/office_365pst_to_mailcowimap_server](https://www.reddit.com/r/selfhosted/comments/1ik8hyf/office_365pst_to_mailcowimap_server)
 - RSS feed: $source
 - date published: 2025-02-07T23:05:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi,<br/> I&#39;m trying to switch about 10 Users from Office 365 (Business) to Mailcow.<br/> I have exported the Profiles to PST Files, as Office 365 doesn&#39;t allow usable IMAP Access any more.<br/> Can anyone recommend a tool for importing the Mailboxes to my mailcow IMAP Server?</p> <p>I have no problem with a paid solution, as long as it works.<br/> However, free is alway welcome ;-)</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Needleworker_6778"> /u/No_Needleworker_6778 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik8hyf/office_365pst_to_mailcowimap_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik8hyf/office_365pst_to_mailcowimap_server/">[comments]</a></span>

## Docker vs Host for Nginx as a Proxy/Load Balancer – Deployment Strategies & Challenges
 - [https://www.reddit.com/r/selfhosted/comments/1ik6u4z/docker_vs_host_for_nginx_as_a_proxyload_balancer](https://www.reddit.com/r/selfhosted/comments/1ik6u4z/docker_vs_host_for_nginx_as_a_proxyload_balancer)
 - RSS feed: $source
 - date published: 2025-02-07T21:53:50+00:00

<!-- SC_OFF --><div class="md"><p>So many of us here self-host various services behind a proxy, and I assume a good number of you work as system engineers managing application servers and proxies (mostly Nginx).</p> <p>I’m curious—how are you deploying your proxies/load balancers, especially Nginx? Are you running it on the host itself, or have you containerized it with Docker? What advantages do you find in running it in Docker vs directly on the host?</p> <p>Additionally, if you compile Nginx from source for specific module support, how do you maintain version consistency across different deployments, whether on the host or in a container?</p> <p>For those using <strong>Fail2Ban</strong> with Nginx, how do you handle it when Nginx is inside a Docker container, considering networking limitations?</p> <p>If you <strong>migrated</strong> from running Nginx on the host to a containerized setup, what challenges did you face during the transition?</p> <p>Finally, in terms of <strong>perf

## Is Self-Hosting Coolify Secure Enough for a Beginner?
 - [https://www.reddit.com/r/selfhosted/comments/1ik6rwo/is_selfhosting_coolify_secure_enough_for_a](https://www.reddit.com/r/selfhosted/comments/1ik6rwo/is_selfhosting_coolify_secure_enough_for_a)
 - RSS feed: $source
 - date published: 2025-02-07T21:51:10+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m getting ready for deploying saas apps. I want to selfhost Coolify as a Vercel alternative.</p> <p>I have very beginner knowledge about setting up vps. I am wondering if selfhosting Coolify is good choice for beginner in case of users data protection and other potential vps attacks. </p> <p>Is standard vps securing like ssh keys and other basic tips enough for securing vps for hosting apps or that&#39;s not good idea for beginner and it&#39;s better to stick with paas like Vercel/Heroku etc?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SpizganyTomek"> /u/SpizganyTomek </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik6rwo/is_selfhosting_coolify_secure_enough_for_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik6rwo/is_selfhosting_coolify_secure_enough_for_a/">[comments]</a></span>

## What is the proper/most efficient way to move all of my iCloud data to local storage?
 - [https://www.reddit.com/r/selfhosted/comments/1ik6gwi/what_is_the_propermost_efficient_way_to_move_all](https://www.reddit.com/r/selfhosted/comments/1ik6gwi/what_is_the_propermost_efficient_way_to_move_all)
 - RSS feed: $source
 - date published: 2025-02-07T21:38:19+00:00

<!-- SC_OFF --><div class="md"><p>The last time I had to do anything like this was trying to move 5TB of OneDrive data to local storage, and I never found a method that worked - so figured it&#39;s worth asking here what the best way of doing this with iCloud is?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/anonymooseantler"> /u/anonymooseantler </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik6gwi/what_is_the_propermost_efficient_way_to_move_all/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik6gwi/what_is_the_propermost_efficient_way_to_move_all/">[comments]</a></span>

## Docker problem
 - [https://www.reddit.com/r/selfhosted/comments/1ik5ng1/docker_problem](https://www.reddit.com/r/selfhosted/comments/1ik5ng1/docker_problem)
 - RSS feed: $source
 - date published: 2025-02-07T21:03:36+00:00

<!-- SC_OFF --><div class="md"><p>So I have decided to move all my self hosting into Proxmox. So far I have not had to much of an issue getting things up and running except for Papermerge 3.4.</p> <p>I have installed it and it &quot;works&quot; with the exception that it is storing the files in</p> <pre><code>/var/lib/docker/volumes/[username]_media_root/_data/docvers/29/4a/294a3bc6-360f-463a-892e-7a523d85b356/2024insurance.pdf </code></pre> <p>instead of the /share folder i have setup on the network.</p> <p>Is there anything wrong with my docker-compose to cause this...</p> <pre><code>services: webapp: image: papermerge/papermerge:3.3.1 environment: PAPERMERGE__SECURITY__SECRET_KEY: 12345 PAPERMERGE__AUTH__USERNAME: admin PAPERMERGE__AUTH__PASSWORD: admin PAPERMERGE__DATABASE__URL: postgresql://coco:jumbo@db:5432/pmgdb PAPERMERGE__MAIN__MEDIA_ROOT: /share/documents/pmg volumes: - media_root:/share/documents/pmg ports: - &quot;12000:80&quot; depends_on: - db db: image: postgres:16.1 

## {Shit post} Rate my professional homelab
 - [https://www.reddit.com/r/selfhosted/comments/1ik5hge/shit_post_rate_my_professional_homelab](https://www.reddit.com/r/selfhosted/comments/1ik5hge/shit_post_rate_my_professional_homelab)
 - RSS feed: $source
 - date published: 2025-02-07T20:56:49+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ik5hge/shit_post_rate_my_professional_homelab/"> <img src="https://preview.redd.it/et0aa0q96she1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=772a317790a27ff74164b012945a92ca55916f26" alt="{Shit post} Rate my professional homelab" title="{Shit post} Rate my professional homelab" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lanzo__"> /u/Lanzo__ </a> <br/> <span><a href="https://i.redd.it/et0aa0q96she1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik5hge/shit_post_rate_my_professional_homelab/">[comments]</a></span> </td></tr></table>

## jellyfin a good choice for music?
 - [https://www.reddit.com/r/selfhosted/comments/1ik5eev/jellyfin_a_good_choice_for_music](https://www.reddit.com/r/selfhosted/comments/1ik5eev/jellyfin_a_good_choice_for_music)
 - RSS feed: $source
 - date published: 2025-02-07T20:53:08+00:00

<!-- SC_OFF --><div class="md"><p>hi! i&#39;m sorta new to all this, and what prompted me to finally start hosting my own shit is that i really really do not want to support spotify anymore!</p> <p>my plan so far is to set up a server that should work both as a NAS (debian + samba i guess) and a jellyfin host, and then start curating my own digital music library again. is jellyfin even the best option if my main concern is to stream music? or should i possibly look at smth else?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/marin_g00"> /u/marin_g00 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik5eev/jellyfin_a_good_choice_for_music/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik5eev/jellyfin_a_good_choice_for_music/">[comments]</a></span>

## Self Hosted Email Setup
 - [https://www.reddit.com/r/selfhosted/comments/1ik4o4y/self_hosted_email_setup](https://www.reddit.com/r/selfhosted/comments/1ik4o4y/self_hosted_email_setup)
 - RSS feed: $source
 - date published: 2025-02-07T20:22:11+00:00

<!-- SC_OFF --><div class="md"><p>So I am looking into setting up a self-hosted email server. I had considered this in the past just so I could have my own private email to separate out important private stuff from things like subscription services, online shopping etc. I know there are non-self hosted options for using email like that but they never really appealed to be due to how they worked or the $ cost involved. </p> <p>Plus, I would like to use this email server for password resets and other administrative actions for some of my other hosted services which are used by my family. </p> <p>Right now I am looking at dockerized Mailcow but their documentation has lots of warning/caveats that I don&#39;t really get. Like about how bad it is to use a firewall (they link some other reading on this but its not really clear). </p> <p>Can anyone give me some pointers/recommendations on a self hosted email server? What you all use and an idea of how you configure it?</p> </div><!-- SC_ON 

## Apt problems
 - [https://www.reddit.com/r/selfhosted/comments/1ik3uq1/apt_problems](https://www.reddit.com/r/selfhosted/comments/1ik3uq1/apt_problems)
 - RSS feed: $source
 - date published: 2025-02-07T19:47:50+00:00

<!-- SC_OFF --><div class="md"><p>Sorry to post here, I’m not allowed to post to <a href="/r/ubuntuserver">r/ubuntuserver</a> for some reason.</p> <p>I have a server running 22.04. LTS Whenever I try to update anything I get an error about unavailable repos. </p> <p>If I reinstall from an ISO without reformatting, how much will be wiped out? I’ve backed up my home directory but this is my music server and I’ve got ≈ 350 GB that will take a long time to backup and restore if I end up having to do that.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/salliesdad"> /u/salliesdad </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik3uq1/apt_problems/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik3uq1/apt_problems/">[comments]</a></span>

## Trying to host a website behind NGINX Proxy Manager (cert errors)
 - [https://www.reddit.com/r/selfhosted/comments/1ik3myz/trying_to_host_a_website_behind_nginx_proxy](https://www.reddit.com/r/selfhosted/comments/1ik3myz/trying_to_host_a_website_behind_nginx_proxy)
 - RSS feed: $source
 - date published: 2025-02-07T19:38:42+00:00

<!-- SC_OFF --><div class="md"><p>First, I&#39;m a relative newbie to this. I&#39;ve gotten several things working by kind of &quot;script kiddie-ing&quot; my way through it.</p> <p>My first project was to expose some services to the internet using custom URLs through a reverse proxy, for personal use. So I got a NUC PC and installed Ubuntu (desktop) on it. Then I installed docker and Portainer and DuckDNS and NGINX Proxy Manager (I don&#39;t know if that&#39;s different from just NGINX &quot;core&quot;.</p> <p>I&#39;ve been successful in configuring NGINX Proxy Manager to proxy multiple subdomains to my internal systems. So for example &lt;ha.mydomain.com&gt; hits my external IP and then routes to my raspberry pi over port 8123 and I can access Home Assistant remotely. Similarly I&#39;ve routed &lt;nginx.mydomain.com&gt; to NGINX Proxy Manager and &lt;portainer.mydomain.com&gt; to NGINX and Portainer respectively.</p> <p>I&#39;m using Cloudflare DNS for &lt;mydomain.com&gt; and I ge

## Meeting Room Statis iPad Display Software
 - [https://www.reddit.com/r/selfhosted/comments/1ik2ilz/meeting_room_statis_ipad_display_software](https://www.reddit.com/r/selfhosted/comments/1ik2ilz/meeting_room_statis_ipad_display_software)
 - RSS feed: $source
 - date published: 2025-02-07T18:51:56+00:00

<!-- SC_OFF --><div class="md"><p>I have a first generation iPad and would like to use it as a display for a meeting room where you can see from outside whether the room is free or occupied. I would like to be able to change the room status via another computer (calendar sync is not important at the moment) and preferably if it costs nothing. Is there a possibility via an app, or via a self-hosted software where I can retrieve the image via an IP.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GamingBar"> /u/GamingBar </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik2ilz/meeting_room_statis_ipad_display_software/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik2ilz/meeting_room_statis_ipad_display_software/">[comments]</a></span>

## Rate My Home Lab
 - [https://www.reddit.com/r/selfhosted/comments/1ik2gb9/rate_my_home_lab](https://www.reddit.com/r/selfhosted/comments/1ik2gb9/rate_my_home_lab)
 - RSS feed: $source
 - date published: 2025-02-07T18:49:15+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ik2gb9/rate_my_home_lab/"> <img src="https://preview.redd.it/kuk8b84fjrhe1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=260a59a9ba4059d9b24c1a934de2fac09ef2d4f2" alt="Rate My Home Lab" title="Rate My Home Lab" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NeitherAdvertNorAd"> /u/NeitherAdvertNorAd </a> <br/> <span><a href="https://i.redd.it/kuk8b84fjrhe1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik2gb9/rate_my_home_lab/">[comments]</a></span> </td></tr></table>

## What is your preferred email client and why?
 - [https://www.reddit.com/r/selfhosted/comments/1ik275t/what_is_your_preferred_email_client_and_why](https://www.reddit.com/r/selfhosted/comments/1ik275t/what_is_your_preferred_email_client_and_why)
 - RSS feed: $source
 - date published: 2025-02-07T18:38:31+00:00

<!-- SC_OFF --><div class="md"><p>Maybe you self-host your email, maybe you don&#39;t self-host email but still don&#39;t use the provider&#39;s native email client, and maybe you don&#39;t self-host your email but and rely on your provider&#39;s email client.</p> <p>Regardless of your situation, what is your preferred email client, and why? Also, if you don&#39;t mind sharing, what is your email provider (self-hosted or otherwise) and why?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/-ThatGingerKid-"> /u/-ThatGingerKid- </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik275t/what_is_your_preferred_email_client_and_why/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik275t/what_is_your_preferred_email_client_and_why/">[comments]</a></span>

## Manga... How?
 - [https://www.reddit.com/r/selfhosted/comments/1ik23ci/manga_how](https://www.reddit.com/r/selfhosted/comments/1ik23ci/manga_how)
 - RSS feed: $source
 - date published: 2025-02-07T18:34:12+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ll keep it extremely short. Looking for Mangarr for the downloading part. I&#39;ll be using Kavita. What do you recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TomerHorowitz"> /u/TomerHorowitz </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik23ci/manga_how/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik23ci/manga_how/">[comments]</a></span>

## Cpu allocations proxmox
 - [https://www.reddit.com/r/selfhosted/comments/1ik200a/cpu_allocations_proxmox](https://www.reddit.com/r/selfhosted/comments/1ik200a/cpu_allocations_proxmox)
 - RSS feed: $source
 - date published: 2025-02-07T18:30:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I have a dell r720 with 24 cores (48 cpu in proxmox) and 256 Ram. I have 7-8 vm’s mostly idle but is set to use 2-4 cpu.</p> <p>I just installed ollama in a vm, and installed deepseek 14b. How much of the CPU can I allocate to this vm to speed up token generation? Is it ok to set 40 cpu, since most of the other vm’s is not very active?</p> <p>I only plan to use deepseek locally maybe 1-2 times a day.</p> <p>Cheers</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fungalsen"> /u/Fungalsen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik200a/cpu_allocations_proxmox/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik200a/cpu_allocations_proxmox/">[comments]</a></span>

## umami-alerts v0.1.0: A daily email report generator for Umami Analytics
 - [https://www.reddit.com/r/selfhosted/comments/1ik1soe/umamialerts_v010_a_daily_email_report_generator](https://www.reddit.com/r/selfhosted/comments/1ik1soe/umamialerts_v010_a_daily_email_report_generator)
 - RSS feed: $source
 - date published: 2025-02-07T18:22:23+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>!</p> <p>I wanted to share something I built that started as a work requirement but turned into a nice side project. At work, we&#39;ve started using Umami Analytics (since Matomo <em>really</em> started suffering at our scale) for our websites, but some team members wanted daily email summaries of the stats without having to log into the dashboard (our non-tech team misses GA). So I built a small tool that:</p> <ul> <li>Fetches stats from your Umami instance for multiple websites</li> <li>Generates Umami-styled HTML email reports with: <ul> <li>Pageviews &amp; unique visitor counts</li> <li>Average time spent per visit</li> <li>Bounce rates</li> <li>Top pages and referrers</li> <li>Geographic distribution</li> <li>Browser &amp; device breakdowns</li> </ul></li> <li>Sends them via SMTP (works great with Postfix/Haraka/etc)</li> </ul> <p>I couldn&#39;t find many tools that did what we wanted, so I did it mys

## Cloudflare tunnel
 - [https://www.reddit.com/r/selfhosted/comments/1ik1lrh/cloudflare_tunnel](https://www.reddit.com/r/selfhosted/comments/1ik1lrh/cloudflare_tunnel)
 - RSS feed: $source
 - date published: 2025-02-07T18:14:44+00:00

<!-- SC_OFF --><div class="md"><p>How can I use cloudflare tunnel to access 2 of my services outside of my home network. At the moment only 1 service can be access and the other one not. I am getting a http status code 502 from the one that is not working. Or is there a way to setup a route to access the whole inside network using cloudflare tunnel. </p> <p>I did setup a public hostname in cloudflare that points to the internal ip address,done the some setup as to the one that is working. Can I use any name in the public hostname or must I use the docker container name. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tremaine77"> /u/Tremaine77 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik1lrh/cloudflare_tunnel/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik1lrh/cloudflare_tunnel/">[comments]</a></span>

## lan-to-wg: Simple Way to WireGuard Gateway into Your Network! [Docker]
 - [https://www.reddit.com/r/selfhosted/comments/1ik1h1s/lantowg_simple_way_to_wireguard_gateway_into_your](https://www.reddit.com/r/selfhosted/comments/1ik1h1s/lantowg_simple_way_to_wireguard_gateway_into_your)
 - RSS feed: $source
 - date published: 2025-02-07T18:09:18+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>! 👋</p> <p>Excited to share <strong>lan-to-wg</strong> ( <a href="https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fgithub.com%2Fkitsune0n%2Flan-to-wg">https://github.com/kitsune0n/lan-to-wg</a> ), a project I think you&#39;ll find useful.</p> <p>So, I created lan-to-wg as a <strong>simple Docker Compose solution for an additional WireGuard gateway in your LAN.</strong> It routes traffic through WireGuard, deployable on your server <strong>in Docker using macvlan</strong>. This setup gives you a lightweight, controlled VPN gateway without the usual WireGuard hassle and <strong>sidesteps slow router VPN speeds.</strong></p> <p>lan-to-wg is built for simplicity. <strong>For detailed setup instructions and more in-depth information, please check out the README on GitHub.</strong> </p> <p><strong>GitHub:</strong> <a href="https://www.google.com/url?sa=E&amp;q=https%3A%2F%2Fgithub.com%2Fkitsune0n%2Flan-to-wg">

## Seeking for advice for Hetzner and WordPress
 - [https://www.reddit.com/r/selfhosted/comments/1ik12mw/seeking_for_advice_for_hetzner_and_wordpress](https://www.reddit.com/r/selfhosted/comments/1ik12mw/seeking_for_advice_for_hetzner_and_wordpress)
 - RSS feed: $source
 - date published: 2025-02-07T17:53:14+00:00

<!-- SC_OFF --><div class="md"><p>I have multiple websites on WordPress and some laravel websites are under construction. I want to keep them on Hetzner cloud server. So, I am looking for a suggestion for a control panel to make my job easier. cPanel is too expensive. I came across CloudPanel. How is it? Or, do you have any other suggestion?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thuliumInsideFrog"> /u/thuliumInsideFrog </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik12mw/seeking_for_advice_for_hetzner_and_wordpress/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik12mw/seeking_for_advice_for_hetzner_and_wordpress/">[comments]</a></span>

## Does Cloudflare CDN add extra cost over Cloudflare R2
 - [https://www.reddit.com/r/selfhosted/comments/1ik0wbv/does_cloudflare_cdn_add_extra_cost_over](https://www.reddit.com/r/selfhosted/comments/1ik0wbv/does_cloudflare_cdn_add_extra_cost_over)
 - RSS feed: $source
 - date published: 2025-02-07T17:46:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a video editing web application and considering a cloud storage provider. Initially, I thought of S3 and CloudFront (for CDN), but I realized the cost would be substantial due to high egress usage (my application would heavily consume egress over storage). After some research, I discovered Cloudflare R2, which offers free unlimited egress, and that was amazing for me!</p> <p>My question is, would I incur extra costs for having a CDN serve my videos, or does Cloudflare R2 already include a CDN by default? </p> <p>Also, while searching, I found other, even cheaper providers like Backblaze, Wasabi, Telnyx, and IDrive e2. Do you think Cloudflare R2 is the best choice for this use case, or are there better providers? Thanks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dependent-Sport-1128"> /u/Dependent-Sport-1128 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik0wbv/do

## Coral TPU for PC, what is the best solution?
 - [https://www.reddit.com/r/selfhosted/comments/1ik0p4r/coral_tpu_for_pc_what_is_the_best_solution](https://www.reddit.com/r/selfhosted/comments/1ik0p4r/coral_tpu_for_pc_what_is_the_best_solution)
 - RSS feed: $source
 - date published: 2025-02-07T17:37:45+00:00

<!-- SC_OFF --><div class="md"><p>I am looking for Coral AI Dual Edge TPU for my Home lab. I will be using Proxmox and passthrough PCIe to the Frigate LXC.</p> <p>What Dual TPU should I get? and what kind of adapter do I need to install it on a MSI Z790 motherboard that supports this:</p> <p><em>M.2_1 Source (From CPU) supports up to PCIe 4.0 x4 , supports 22110/2280/2260 devices</em><br/> <em>M.2_2 Source (From Chipset) supports up to PCIe 4.0 x4 , supports 2280/2260 devices</em><br/> <em>M.2_3 Source (From Chipset) supports up to PCIe 4.0 x4 / SATA mode, supports 2280/2260/2242 devices</em><br/> <em>M.2_4 Source (From Chipset) supports up to PCIe 4.0 x4 , supports 2280/2260/2242 devices</em></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/john_mamu"> /u/john_mamu </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ik0p4r/coral_tpu_for_pc_what_is_the_best_solution/">[link]</a></span> &#32; <span><a href="https://www.reddit.c

## Need Help picking a GPU for an AI stack
 - [https://www.reddit.com/r/selfhosted/comments/1ik02cp/need_help_picking_a_gpu_for_an_ai_stack](https://www.reddit.com/r/selfhosted/comments/1ik02cp/need_help_picking_a_gpu_for_an_ai_stack)
 - RSS feed: $source
 - date published: 2025-02-07T17:11:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m looking at several cards for Ai use in my server. I want to run a full AI stack and here are the services I&#39;m interesting in:</p> <ul> <li>Ollama (with openwebui)</li> <li>Stable Diffusion</li> <li>Frigate</li> <li>Immich (already running it but it does some ai recognition hoping the GPU would take over)</li> <li>Some AI video generator (Looking for recommendations)</li> </ul> <p>I&#39;m looking for a good card to use, I can just get a <strong>3090</strong> and call it a day but I&#39;m <strong>not sure that&#39;s the best choice</strong> and would love to hear your thoughts. </p> <p>* I only have room for a <strong>single</strong> card, no PCIE slot for more *</p> <p>Here are the cards I am considering:</p> <ul> <li>V100 32gb (~$2000 used)</li> <li>3090 24gb (~$1500 used)</li> <li>Tesla P40 24gb (~$500 used) - Read the 3060 is better</li> <li>3060 12gb (~$250-300 used/new)</li> <li>B580 12gb (~$300 new) </li> <li>A770 16gb (~300 new) </l

## Ghostboard v3.4.0 Released: New REST Server and iOS Shortcuts Integration!
 - [https://www.reddit.com/r/selfhosted/comments/1ik00ed/ghostboard_v340_released_new_rest_server_and_ios](https://www.reddit.com/r/selfhosted/comments/1ik00ed/ghostboard_v340_released_new_rest_server_and_ios)
 - RSS feed: $source
 - date published: 2025-02-07T17:09:35+00:00

<!-- SC_OFF --><div class="md"><p>Hey self-hosting enthusiasts!</p> <p>I&#39;m excited to announce the release of <strong>Ghostboard v3.4.0</strong>, featuring a <strong>REST server</strong> that opens up new ways to interact with and share text across your devices. This update simplifies how text can be updated and retrieved without needing the legacy client script.</p> <hr/> <h2>What&#39;s New in v3.4.0?</h2> <h3>REST API Support</h3> <p>Ghostboard now includes REST endpoints for text management. You can easily update and retrieve text on any board through standard HTTP requests.</p> <p><strong>Examples:</strong></p> <ul> <li><p><strong>POST request</strong> to update text: <code>bash curl -X POST &quot;http://ghostboard-server:port&quot; -d &quot;text=$(cat example.txt)&quot; </code> Or: <code>bash curl -X POST &quot;http://ghostboard-server:port&quot; -d &quot;text=example&quot; </code></p></li> <li><p><strong>GET request</strong> to retrieve text: <code>bash curl &quot;http://gh

## Looking for an overview of Docker containers with newer tags available 👀
 - [https://www.reddit.com/r/selfhosted/comments/1ijzqj5/looking_for_an_overview_of_docker_containers_with](https://www.reddit.com/r/selfhosted/comments/1ijzqj5/looking_for_an_overview_of_docker_containers_with)
 - RSS feed: $source
 - date published: 2025-02-07T16:59:04+00:00

<!-- SC_OFF --><div class="md"><p>Does anyone know of an app (web/console) that would connect to a Docker daemon, view running containers, check the associated image registry and display those that have newer version tags?</p> <p>I don’t need it to update the containers. It just needs to give me an overview of available updates based on the version tags e.g. my running container has a tag of <code>:v3.2.1</code> but there’s a <code>:v3.2.2</code> tag available. </p> <p>I’m currently using Diun which is great, but I don’t want to be notified, I just want to get an overview ad-hoc. </p> <p>Any recommendations would be appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/adullage"> /u/adullage </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijzqj5/looking_for_an_overview_of_docker_containers_with/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijzqj5/looking_for_an_overview_of_

## Homelab Documentation
 - [https://www.reddit.com/r/selfhosted/comments/1ijzcg1/homelab_documentation](https://www.reddit.com/r/selfhosted/comments/1ijzcg1/homelab_documentation)
 - RSS feed: $source
 - date published: 2025-02-07T16:42:37+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s talk about Homelab Documentation, just for a quick second.</p> <p>I&#39;ve <a href="https://www.reddit.com/r/selfhosted/comments/1ibmbxq/comment/m9jbcvn/?utm_source=share&amp;utm_medium=web3x&amp;utm_name=web3xcss&amp;utm_term=1&amp;utm_content=share_button">seen</a> that some of you would like better documentation for your Homelab/Services. Even at my workplace we find documentation challenging.</p> <p>I&#39;m curious to hear your thoughts on how we could make homelab documentation <em>amazing</em>.<br/> Which features would you like a documentation platform to have, how should it be structured and what are your personal pain points with the current solutions?</p> <p>I&#39;m genuinely interested in hearing your ideas. Share your thoughts and add anything to this discussion, so we can build an idea together.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nightslide1"> /u/Nightslide1 </a> <br/> <span><

## Large wall mounted touchscreen to allow kids to interact with self-hosted apps.
 - [https://www.reddit.com/r/selfhosted/comments/1ijz0vc/large_wall_mounted_touchscreen_to_allow_kids_to](https://www.reddit.com/r/selfhosted/comments/1ijz0vc/large_wall_mounted_touchscreen_to_allow_kids_to)
 - RSS feed: $source
 - date published: 2025-02-07T16:29:15+00:00

<!-- SC_OFF --><div class="md"><p>So I have a pretty big home network of apps for photo storage, task tracking, calendars, etc. Proud to say I have developed many of them, including calendaring; I get a kick out of front-end design as I am a backend developer at work. Me and my partner use these to run the household. She didn&#39;t get it at first and missed google, but has really gotten into it in the last few years.</p> <p>But now the kids are getting old enough that they need to interact with some of them - especially the calendar app. Eventually they&#39;ll be old enough to have computers or phones of their own, but that&#39;s a big leap that won&#39;t be appropriate for a couple of years.</p> <p>So my question - can anyone recommend any hardware that they have used and like to accomplish something like a <strong>wall mounted touchscreen</strong>? It could be an all-in-one unix computer, or just a screen peripheral that needs to be plugged into a separate unix box. I&#39;ve done 

## Sync youtube playlist with Navidrome
 - [https://www.reddit.com/r/selfhosted/comments/1ijyjnf/sync_youtube_playlist_with_navidrome](https://www.reddit.com/r/selfhosted/comments/1ijyjnf/sync_youtube_playlist_with_navidrome)
 - RSS feed: $source
 - date published: 2025-02-07T16:09:40+00:00

<!-- SC_OFF --><div class="md"><p>I have navidrom setup but it&#39;s difficult to keep playlists in sync with Navidrome. Is there any lightweight service which can keep running in background and download any newly added video as mp3 for Navidrome?<br/> Also, it should only add and not delete if any video from the playlist is removed or made private by the owner.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pakkedheeth"> /u/pakkedheeth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijyjnf/sync_youtube_playlist_with_navidrome/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijyjnf/sync_youtube_playlist_with_navidrome/">[comments]</a></span>

## Looking for an Open-Source Email Automation Platform with Easier Setup than Mautic
 - [https://www.reddit.com/r/selfhosted/comments/1ijyd4o/looking_for_an_opensource_email_automation](https://www.reddit.com/r/selfhosted/comments/1ijyd4o/looking_for_an_opensource_email_automation)
 - RSS feed: $source
 - date published: 2025-02-07T16:02:09+00:00

<!-- SC_OFF --><div class="md"><p>Mautic (5) is a widely used open-source solution for email automation, including email sequences. However, setting it up can be complex, and configuring the core email functionality requires additional steps beyond simply connecting an SMTP server, even when the server works with other email clients.</p> <p>Are there any other open-source email automation platforms that support email sequences and might offer a more straightforward setup?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kerkerby"> /u/kerkerby </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijyd4o/looking_for_an_opensource_email_automation/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijyd4o/looking_for_an_opensource_email_automation/">[comments]</a></span>

## My Simple Server Monitoring with a python script.
 - [https://www.reddit.com/r/selfhosted/comments/1ijy31h/my_simple_server_monitoring_with_a_python_script](https://www.reddit.com/r/selfhosted/comments/1ijy31h/my_simple_server_monitoring_with_a_python_script)
 - RSS feed: $source
 - date published: 2025-02-07T15:50:43+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijy31h/my_simple_server_monitoring_with_a_python_script/"> <img src="https://a.thumbs.redditmedia.com/IVfJT68pKQyvCS8UwNSyYYl8BHgj1obc5iupj40Mij4.jpg" alt="My Simple Server Monitoring with a python script." title="My Simple Server Monitoring with a python script." /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Everything I tried for monitoring would just show too much information and was too cluttered. I just wanted basic info displayed in an easily read format, so I made this script. The processes section just shows anything that goes over 10% CPU usage. I&#39;m going to add some docker monitoring next I think. </p> <p>Any ideas of what else I could add to it?</p> <p><a href="https://preview.redd.it/ntqcflsbnqhe1.png?width=461&amp;format=png&amp;auto=webp&amp;s=d7564eca371f98de2a4cc810c60a993d3ff93b17">https://preview.redd.it/ntqcflsbnqhe1.png?width=461&amp;format=png&amp;auto=webp&amp;s=d7564eca371f98de2a4

## Question with Ollama/Open-WebUI and remote access...
 - [https://www.reddit.com/r/selfhosted/comments/1ijxho6/question_with_ollamaopenwebui_and_remote_access](https://www.reddit.com/r/selfhosted/comments/1ijxho6/question_with_ollamaopenwebui_and_remote_access)
 - RSS feed: $source
 - date published: 2025-02-07T15:25:26+00:00

<!-- SC_OFF --><div class="md"><p>First off, everything works ...locally. Anywhere in my house I can get on any device, hit up my open-webui and go. </p> <p>I have a domain and running nginx. I made a subdomain, did the thing and boom! I can hit the open-webui and login. When I try to do anything though it sits for a minute and then I get a box that says &quot;Network Problem&quot;. Nothing more, nothing less.</p> <p>I&#39;m not sure what the problem would be or what else I would need to do to get it to work. Doesn&#39;t add because I assume that open-webui is communicating with me and with ollama so yea, I&#39;m just lost.</p> <p>Any ideas?</p> <p>Also, this is all running Ubuntu Server 22.04, ollama locally, and open-webui running in a docker container using Network: &quot;host&quot; flag as that was the only way I could get open-webui to talk to ollama for some reason.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thegreatcerebral"> /u/theg

## Can someone please help me set up sonarr, radarr, and bazarr?
 - [https://www.reddit.com/r/selfhosted/comments/1ijx7oc/can_someone_please_help_me_set_up_sonarr_radarr](https://www.reddit.com/r/selfhosted/comments/1ijx7oc/can_someone_please_help_me_set_up_sonarr_radarr)
 - RSS feed: $source
 - date published: 2025-02-07T15:13:03+00:00

<!-- SC_OFF --><div class="md"><p>I am in way over my head. I’ve looked up every guide I can find to try and get these services working with my jellyfin server on truenas, but I just can’t seem to get them to play nicely together or get any of the arr services working at all.</p> <p>I’m not <em>super</em> interested in the automation features of sonarr and radarr, though they are nice. I’m mostly interested in the automation for subtitles that bazarr provides, as a lot of my media either doesn’t have subtitles at all, or has .ass subtitles which gives my android tv an aneurism trying to play the media. I <em>really</em> don’t want to go around finding individual srt files for media that’s missing them, and I’ve reached my limit on srt files downloaded from opensubtitles.</p> <p>I feel like I lucked into getting my jellyfin server working in the first place. The more I learn about sysadmin, self-hosting, and this whole media server thing, the dumber I feel. I don’t know what sort of d

## Is there a software that collects and shows the changelog of other software I installed?
 - [https://www.reddit.com/r/selfhosted/comments/1ijx6ai/is_there_a_software_that_collects_and_shows_the](https://www.reddit.com/r/selfhosted/comments/1ijx6ai/is_there_a_software_that_collects_and_shows_the)
 - RSS feed: $source
 - date published: 2025-02-07T15:11:20+00:00

<!-- SC_OFF --><div class="md"><p>Most of the dockers I use don&#39;t show a changelog after updating them, so I usually have to go and search for it (if I&#39;m aware at all that the docker was updated during the automated night backup).</p> <p>I&#39;m searching for a software that collects the versions for all the dockers I&#39;m using and sends me a notification when an update occurs, with the changelog shown in the same context. It could also proactively look for new versions and provide an update button.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dreadino"> /u/Dreadino </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijx6ai/is_there_a_software_that_collects_and_shows_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijx6ai/is_there_a_software_that_collects_and_shows_the/">[comments]</a></span>

## Wireless Access Point Help
 - [https://www.reddit.com/r/selfhosted/comments/1ijwne0/wireless_access_point_help](https://www.reddit.com/r/selfhosted/comments/1ijwne0/wireless_access_point_help)
 - RSS feed: $source
 - date published: 2025-02-07T14:48:34+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am new to all of this, and I have a lot of questions. I am slowly getting through planning my steps out before I start, and I am running into a few things that I see as blockers. This biggest issue I have is getting an additional wap. </p> <p>My current network set up is fiber. I get an ethernet port from my ont, and that plugs into my google wifi. I have 2 more access points throughout my house, 1 of which is critical. It is in a room that has kind of far access from my main unit, and so having the ap with an ethernet ports essentially doubles (even triples) my speed on my pc compared to wifi.</p> <p>As far as I understand, I will need to get one wap for my main wifi needs (replacing my main google wifi puck). And then, I would want an additional wap for the ap on my desk. The problem is that I cannot get an ethernet port to this wap from the main switch I will install in main floor. </p> <p>Is there a wap that connects to my main wap wireless

## Rate My Home Lab
 - [https://www.reddit.com/r/selfhosted/comments/1ijw1y9/rate_my_home_lab](https://www.reddit.com/r/selfhosted/comments/1ijw1y9/rate_my_home_lab)
 - RSS feed: $source
 - date published: 2025-02-07T14:20:55+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijw1y9/rate_my_home_lab/"> <img src="https://preview.redd.it/yzlfyeum7qhe1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9cf5e6757f60442e034f09d45e58548592ed26f1" alt="Rate My Home Lab" title="Rate My Home Lab" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>How is my Home Lab Design My Fellow selfhosters</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/daredeviltzr"> /u/daredeviltzr </a> <br/> <span><a href="https://i.redd.it/yzlfyeum7qhe1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijw1y9/rate_my_home_lab/">[comments]</a></span> </td></tr></table>

## UK orders Apple to grant access to user' encrypted data, worldwide, and not disclose that it was ordered to.
 - [https://www.reddit.com/r/selfhosted/comments/1ijvgox/uk_orders_apple_to_grant_access_to_user_encrypted](https://www.reddit.com/r/selfhosted/comments/1ijvgox/uk_orders_apple_to_grant_access_to_user_encrypted)
 - RSS feed: $source
 - date published: 2025-02-07T13:52:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijvgox/uk_orders_apple_to_grant_access_to_user_encrypted/"> <img src="https://external-preview.redd.it/B91YmESvb0WYpY12uw6Zx-k25K2rNCAfTccXq4MdpCk.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=715521fa812fce7755bb11c4adede1f46a175c1e" alt="UK orders Apple to grant access to user' encrypted data, worldwide, and not disclose that it was ordered to." title="UK orders Apple to grant access to user' encrypted data, worldwide, and not disclose that it was ordered to." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PlannedObsolescence_"> /u/PlannedObsolescence_ </a> <br/> <span><a href="https://archive.is/3Pp0U">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijvgox/uk_orders_apple_to_grant_access_to_user_encrypted/">[comments]</a></span> </td></tr></table>

## Dokploy and Traefik - how to handle exposed ports ?
 - [https://www.reddit.com/r/selfhosted/comments/1ijuwjq/dokploy_and_traefik_how_to_handle_exposed_ports](https://www.reddit.com/r/selfhosted/comments/1ijuwjq/dokploy_and_traefik_how_to_handle_exposed_ports)
 - RSS feed: $source
 - date published: 2025-02-07T13:24:45+00:00

<!-- SC_OFF --><div class="md"><p>my application is running expoded on ports: - 8081:80&quot; and - 443:443&quot; , so access it on [<a href="http://app.mydomain.com:8081%5D(javascript:void(0);)">http://app.mydomain.com:8081](javascript:void(0);)</a>. Dokploy works good on that. When I remove the ports and add labels for Traefik listen to por 80 and let me access throught http:/app.mydomain.com, nothing works. What can I do ? I&#39;m follow the deploy of OJS from [<a href="https://github.com/pkp/docker-ojs%5D(javascript:void(0);)">https://github.com/pkp/docker-ojs](javascript:void(0);)</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Odd-Outside-141"> /u/Odd-Outside-141 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijuwjq/dokploy_and_traefik_how_to_handle_exposed_ports/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijuwjq/dokploy_and_traefik_how_to_handle_exposed_ports/">[comme

## Selfhostable app to centralize messages
 - [https://www.reddit.com/r/selfhosted/comments/1ijunml/selfhostable_app_to_centralize_messages](https://www.reddit.com/r/selfhosted/comments/1ijunml/selfhostable_app_to_centralize_messages)
 - RSS feed: $source
 - date published: 2025-02-07T13:12:01+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m a startup and I need to centralize leads and clients messages from multiple sources. From the most important to the least:</p> <ol> <li>Whatsapp</li> <li>Email</li> <li>Twitter/X</li> <li>Instagram</li> <li>Linkedin</li> </ol> <p>Is there any software out there where I can add my own credentials to these platforms and make them available to my co-founder responsible for this? It feels like a mess to manage all these potential leads on their own platform.<br/> I found some platforms that handles that, but they are extremely expensive to our company, we do not have any external funding yet, we are completely bootstrapped.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Pedg0"> /u/Pedg0 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijunml/selfhostable_app_to_centralize_messages/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijunml/selfhostabl

## Immich Power Tools v0.14.0 - Better location tagging, filters in geo map and people list and many more
 - [https://www.reddit.com/r/selfhosted/comments/1ijuisl/immich_power_tools_v0140_better_location_tagging](https://www.reddit.com/r/selfhosted/comments/1ijuisl/immich_power_tools_v0140_better_location_tagging)
 - RSS feed: $source
 - date published: 2025-02-07T13:05:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijuisl/immich_power_tools_v0140_better_location_tagging/"> <img src="https://external-preview.redd.it/uasAxUNZBPTkTGW2WZB046rr4f6ZbTOJnyTkwxLIkZI.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8cfdac252fffb3841280724ce9e98d983a22d371" alt="Immich Power Tools v0.14.0 - Better location tagging, filters in geo map and people list and many more" title="Immich Power Tools v0.14.0 - Better location tagging, filters in geo map and people list and many more" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>This is a very minimal and short release with a bunch of quality of life improvements in Power tools.</p> <p><strong>🗺️ Missing Locations: Improved Navigation &amp; Management</strong></p> <ul> <li>Scroll to Date on Refresh: Effortlessly navigate to your desired date after a page refresh – no more hunting through your timeline!</li> <li>Remove Asset from List When Tagged: Streamline your workflow by automatically 

## This Week in Self-Hosted (7 February 2025)
 - [https://www.reddit.com/r/selfhosted/comments/1ijucpw/this_week_in_selfhosted_7_february_2025](https://www.reddit.com/r/selfhosted/comments/1ijucpw/this_week_in_selfhosted_7_february_2025)
 - RSS feed: $source
 - date published: 2025-02-07T12:56:23+00:00

<!-- SC_OFF --><div class="md"><p>Happy Friday, <a href="/r/selfhosted">r/selfhosted</a>! Linked below is the latest edition of <em>This Week in Self-Hosted</em>, a weekly newsletter recap of the latest activity in self-hosted software and content.</p> <p>This week&#39;s features include:</p> <ul> <li>Automated toilet flash tracking via Home Assistant</li> <li>Software updates and launches</li> <li>A spotlight on <a href="https://github.com/jon6fingrs/ghostboard?ref=selfh.st">Ghostboard</a> - a self-hosted text synchronization tool (<a href="/u/thehelpfulidiot">u/thehelpfulidiot</a>)</li> <li>A ton of great guides and content from the community</li> </ul> <p>Thanks, and as usual, feel free to reach out with feedback!</p> <hr/> <p><a href="https://selfh.st/newsletter/2025-02-07/?ref=reddit">This Week in Self-Hosted (7 February 2025)</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/shol-ly"> /u/shol-ly </a> <br/> <span><a href="https://www.redd

## Self-hosting R1 / LLama / some future AI stuff - GPUs vs server CPU + RAM?
 - [https://www.reddit.com/r/selfhosted/comments/1ijtubm/selfhosting_r1_llama_some_future_ai_stuff_gpus_vs](https://www.reddit.com/r/selfhosted/comments/1ijtubm/selfhosting_r1_llama_some_future_ai_stuff_gpus_vs)
 - RSS feed: $source
 - date published: 2025-02-07T12:26:50+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>After being sceptical about stuff like Chat GPT/ R1 in general, recently I started to find real value in using it, however concerns about sending my private/business information to the cloud prevents me from utilizing it fully. So I&#39;ve decided to dive deeper into locally hosting it.</p> <p>My use case would be mostly aid in programming, ideally if I would be able to provide context of my project so the code would be more or less adjusted to my specific project. I have some ideas about using it also in more general manner, like some kind of personal assistant, but that&#39;s not the main reason now.</p> <p>I&#39;ve started reading some stuff and watching videos of guys explaining their builds, but some seem to be using mostly GPUs where CPU is just and addition and all the work is done on the GPUs(like 2-4x 3090 or some other 24GB cards) and some use more like regular server builds with Threadripper and ~200 GB of RAM.</p> <p>

## My current setup
 - [https://www.reddit.com/r/selfhosted/comments/1ijtu6j/my_current_setup](https://www.reddit.com/r/selfhosted/comments/1ijtu6j/my_current_setup)
 - RSS feed: $source
 - date published: 2025-02-07T12:26:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijtu6j/my_current_setup/"> <img src="https://preview.redd.it/in6sjzu4nphe1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=318c491ac191dface458d3a9dc9c67573dd6e899" alt="My current setup" title="My current setup" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/boby_025"> /u/boby_025 </a> <br/> <span><a href="https://i.redd.it/in6sjzu4nphe1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijtu6j/my_current_setup/">[comments]</a></span> </td></tr></table>

## How much power does your server draw, and how much does this cost you?
 - [https://www.reddit.com/r/selfhosted/comments/1ijttdz/how_much_power_does_your_server_draw_and_how_much](https://www.reddit.com/r/selfhosted/comments/1ijttdz/how_much_power_does_your_server_draw_and_how_much)
 - RSS feed: $source
 - date published: 2025-02-07T12:25:15+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to keep electricity costs as minimal as possible. I built my server last year with power efficiency in mind.</p> <p>It currently draws around 25W at idle, with the two 12tb drives spun down. Running 24/7 at idle would cost me about £4.50/month, which I consider reasonable.</p> <p>Specs: </p> <ul> <li>Intel 11400</li> <li>H570M motherboard</li> <li>2x8GB ram</li> <li>2x1TB nvme</li> <li>CoolerMaster 550W psu</li> <li>5x case fans</li> <li>2x12tb HDD</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Flat_Professional_55"> /u/Flat_Professional_55 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijttdz/how_much_power_does_your_server_draw_and_how_much/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijttdz/how_much_power_does_your_server_draw_and_how_much/">[comments]</a></span>

## unable to block ads with iCloud private relay
 - [https://www.reddit.com/r/selfhosted/comments/1ijt9qm/unable_to_block_ads_with_icloud_private_relay](https://www.reddit.com/r/selfhosted/comments/1ijt9qm/unable_to_block_ads_with_icloud_private_relay)
 - RSS feed: $source
 - date published: 2025-02-07T11:52:19+00:00

<!-- SC_OFF --><div class="md"><p>I am running a local blocky instance that blocks ads for me on 127.0.0.1 and I have set that as my dns on my Mac. It works even with the default firewall on, but recently has not been working with the iCloud private relay. I forward queries to 1.1.1.1 upstream if I can&#39;t resolve them locally. I have heard of DOH/DOT alternatives but I can&#39;t get them working with both private relay and blocky</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Hot-Kick5863"> /u/Hot-Kick5863 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijt9qm/unable_to_block_ads_with_icloud_private_relay/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijt9qm/unable_to_block_ads_with_icloud_private_relay/">[comments]</a></span>

## looking for a selfhosted exam portal option
 - [https://www.reddit.com/r/selfhosted/comments/1ijs5b6/looking_for_a_selfhosted_exam_portal_option](https://www.reddit.com/r/selfhosted/comments/1ijs5b6/looking_for_a_selfhosted_exam_portal_option)
 - RSS feed: $source
 - date published: 2025-02-07T10:37:27+00:00

<!-- SC_OFF --><div class="md"><p>Students should be able to register.</p> <p>By the end of the semester, they should be able to register for their exams.</p> <p>Once the exam registration deadline ends, they should be able to obtain their admit card.</p> <p>After the exams are over, students should be able to view and download their result card in PDF format.</p> <p>Teachers/faculty should be able to assess students and assign marks.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chimtu_Sharma"> /u/Chimtu_Sharma </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijs5b6/looking_for_a_selfhosted_exam_portal_option/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijs5b6/looking_for_a_selfhosted_exam_portal_option/">[comments]</a></span>

## DNS & Caddy to reverse proxy
 - [https://www.reddit.com/r/selfhosted/comments/1ijs1ac/dns_caddy_to_reverse_proxy](https://www.reddit.com/r/selfhosted/comments/1ijs1ac/dns_caddy_to_reverse_proxy)
 - RSS feed: $source
 - date published: 2025-02-07T10:29:37+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I am new to the hosting environment and even more to the self-hosting part of it.</p> <p>What I am trying to do is setup a subdomain by applications and use Caddy to reverse proxy everything to the correct port safely without having to specify the port in the url</p> <p>What I did:</p> <ul> <li>I recently bought a domain that I&#39;ll call example.com in this thread.</li> <li>I use an old laptop as the hardware and latest ubuntu as the software</li> <li>I setup a ssh server to acces it from my main computer</li> <li>I redirected some subdomains to my public IP</li> <li>I tested with a minecraft docker that my DNS is working</li> <li>I tested Caddy by setting up DMZ redirecting all to the server (but I don&#39;t want to do this except for testing purposes)</li> </ul> <p>I don&#39;t quite understand caddy at this point and how I can forward the correct port</p> <p>Here is my caddy file</p> <p><code>json subdomain.example.com { reverse_pro

## End of studies internship
 - [https://www.reddit.com/r/selfhosted/comments/1ijrxrr/end_of_studies_internship](https://www.reddit.com/r/selfhosted/comments/1ijrxrr/end_of_studies_internship)
 - RSS feed: $source
 - date published: 2025-02-07T10:22:41+00:00

<!-- SC_OFF --><div class="md"><p>i have a dark kitchen with two restaurants working , and i am working on adding more restaurants . i am running these restaurants by myself and i am willing to offer an end of studies internship to one of my friends who is specializing in IT ( development, BI ...). what could the subject be according to what i do ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Healthy_Pack4053"> /u/Healthy_Pack4053 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijrxrr/end_of_studies_internship/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijrxrr/end_of_studies_internship/">[comments]</a></span>

## ZimaOS security concerns
 - [https://www.reddit.com/r/selfhosted/comments/1ijrw3m/zimaos_security_concerns](https://www.reddit.com/r/selfhosted/comments/1ijrw3m/zimaos_security_concerns)
 - RSS feed: $source
 - date published: 2025-02-07T10:19:37+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m testing <a href="https://github.com/IceWhaleTech/ZimaOS">ZimaOS</a> Beta 1.3.2 Beta which works really fine so far on my own x86 hardware. Docker, a big App Store, Samba with Time Machine announcement... Everything works out of the box and it is completely free. Basically a CasaOS, but as full OS with one-shot updates.</p> <p>Compared to a normal distro with Docker it seems to have a slightly bigger footprint, but the devs claim it is due to AI search and Samba and DLNA activated by default.</p> <p>Now what I&#39;m concerned about is two things:</p> <ol> <li>The company is based in Shanghai. Even if the guys are nice, AFAIK Chinese companies are forced to grant access to their customer data if the government demands it. It is unclear, if there is even some kind of backdoor or other unwanted data export already going on at this point.</li> <li>When checking the filesystem over SSH, every single element has root:root permissions. OK, you still 

## Affordable Self-Hosted Platform for Assisted DevOps Training with an Integrated Playground
 - [https://www.reddit.com/r/selfhosted/comments/1ijrtds/affordable_selfhosted_platform_for_assisted](https://www.reddit.com/r/selfhosted/comments/1ijrtds/affordable_selfhosted_platform_for_assisted)
 - RSS feed: $source
 - date published: 2025-02-07T10:14:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey <a href="/r/selfhosted">r/selfhosted</a>,</p> <p>I’m looking for an <strong>affordable (preferably free or low-cost) self-hosted</strong> solution to run an <strong>assisted DevOps training program</strong>. I currently have only a few students but need a platform that can scale as I grow.</p> <p><strong>Key Requirements:</strong></p> <p>1: <strong>Integrated playground</strong> (in-browser terminals, containerized labs, or VM-based environments)</p> <p>2: <strong>User management</strong> (self-registration or admin-created accounts)</p> <p>3: <strong>Course content support</strong> (video, markdown, slides, etc.—optional, otherwise I’ll use Jitsi)</p> <p>4: <strong>Minimal development or tweaking required</strong> (I’d prefer an easy-to-set-up solution)</p> <p>5: <strong>Basic tracking &amp; assessments</strong> (nice to have but not mandatory)</p> <p><strong>Labs Will Cover:</strong></p> <p>• Linux Basics</p> <p>• Docker &amp; Kubernetes</p> <p

## Need advice on Proxmox configuration
 - [https://www.reddit.com/r/selfhosted/comments/1ijrkl4/need_advice_on_proxmox_configuration](https://www.reddit.com/r/selfhosted/comments/1ijrkl4/need_advice_on_proxmox_configuration)
 - RSS feed: $source
 - date published: 2025-02-07T09:57:18+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I recently built my home server and want to figure out how to configure it. I&#39;ve read a lot of threads on forms and reddit but haven&#39;t found any answers to my questions, so I&#39;m asking for your advice.</p> <p>I&#39;m wondering how I should configure the service interaction and what should be run as LXC and what should be run as VM.</p> <p>I am planning to host a TrueNAS VM (for storage), Debian VM (for Lampac, Vaultwarden, Immich, Nextcloud, Torrserve, Jackett, Plex/Jellyfin). I have wired the drives inside TrueNAS and plan to connect them to Immich and Nextcloud via NFS. Chatbots advise splitting the docker services into different LXCs for better security, but I&#39;m new to this and don&#39;t know how much I need to do this. I&#39;ve also seen people configuring pfsense as an LXC to increase security, I&#39;m not sure if I need to do that yet, but I think it can be done later anyway without harming the server.</p> <p>Also I&#39;ve se

## Potentially moving into an AirBnB temporarily, where I have no control over the broadband connection. What are my options?
 - [https://www.reddit.com/r/selfhosted/comments/1ijrjpl/potentially_moving_into_an_airbnb_temporarily](https://www.reddit.com/r/selfhosted/comments/1ijrjpl/potentially_moving_into_an_airbnb_temporarily)
 - RSS feed: $source
 - date published: 2025-02-07T09:55:38+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve also posted this over on <a href="/r/homelab">r/homelab</a> but I&#39;m more concerned about my Self-Hosted services than the &quot;lab&quot; part...</p> <p>I currently have my OPNsense firewall connected directly to my fibre modem (ONT), using the credentials entered for my connection.</p> <p>Within this I have various VLANs for guests etc, as well as port forwarding for some public-facing services.</p> <p>I also have Pi-Hole setup handling my DNS and filtering.</p> <p>In an AirBnB where the &quot;Wifi is available&quot; I&#39;ll have no control over the internet connection. I can&#39;t work out how to connect into this and still have internet access for my servers, as well as allowing external traffic and not clash with the DHCP server in the provider&#39;s router.</p> <p>There&#39;s no way they&#39;ll let me have access to their broadband credentials to use within OPNsense.</p> <p>What are my options here beyond something like a GL.iNet r

## Help with image tagging and hosting with cloudflare zero trust
 - [https://www.reddit.com/r/selfhosted/comments/1ijrggh/help_with_image_tagging_and_hosting_with](https://www.reddit.com/r/selfhosted/comments/1ijrggh/help_with_image_tagging_and_hosting_with)
 - RSS feed: $source
 - date published: 2025-02-07T09:49:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi guys, I need to tag and share my images and videos with my family members by using a service like immich or photoprism. I want it to be easily accessible by others so I&#39;m thinking about hosting it on a AWS instance maybe, because I don&#39;t get a public ipv4 address (CGNAT) although I do get an ipv6, I&#39;ve tried hosting with ipv6 only but that didn&#39;t work as expected.</p> <p>These are my requirements :- 1. Use google accounts to authenticate via cloudflare zero trust. 2. Easy to host on preferably low end hardware like pi4 or something less powerful. 3. Easily accessible from the public internet. 4. User access control - not everyone should be able to upload or delete the media.</p> <p>How should I go about it? I don&#39;t really wanna use service like tailscale or twingate for accessing the service.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/xicor2205"> /u/xicor2205 </a> <br/> <span><a href=

## What environment to use? NAS + Homelab
 - [https://www.reddit.com/r/selfhosted/comments/1ijrgao/what_environment_to_use_nas_homelab](https://www.reddit.com/r/selfhosted/comments/1ijrgao/what_environment_to_use_nas_homelab)
 - RSS feed: $source
 - date published: 2025-02-07T09:48:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello,<br/> I want to use 1 PC for NAS and Homelab. Currently I am using Lenovo M93p Mini PC and Asustor NAS. I bought HP Elitedesk 800 G3 and now the question is what environment to use? </p> <p>What I want:<br/> - RAID 1<br/> - Reliable NAS<br/> - Immich<br/> - Plex, Radarr, Sonarr, Prowlarr etc.<br/> - VPN (piVPN)<br/> - Adguard<br/> - Ollama - for experimenting</p> <p>I have used OMV and Ubuntu. I want to separate Ollama from the other services. What should I use? Do I need Proxmox or TrueNAS will be enough for me? Can I have Proxmox and RAID? </p> <p>Thank you! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/stefiliev123"> /u/stefiliev123 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijrgao/what_environment_to_use_nas_homelab/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijrgao/what_environment_to_use_nas_homelab/">[comments]</a></span>

## What self-hosted OS to upgrade to?
 - [https://www.reddit.com/r/selfhosted/comments/1ijrd3n/what_selfhosted_os_to_upgrade_to](https://www.reddit.com/r/selfhosted/comments/1ijrd3n/what_selfhosted_os_to_upgrade_to)
 - RSS feed: $source
 - date published: 2025-02-07T09:42:03+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR: Upgrading my boot disk -- what&#39;s the upside of using a special NAS/self-hosting OS instead of a plain Ubuntu LTS / Debian setup?</p> <p>Current setup: </p> <ul> <li>Decade old laptop repurposed as home server, data storage in a separate ZFS partition.</li> <li>Ubuntu LTS as base OS </li> <li>VM for HomeAssistant OS</li> <li>Docker Containers for NPM as reverse proxy, Nextcloud AIO, Immich, Portainer, Authentik.</li> <li>I&#39;m pretty comfortable with terminal and manage above setup on terminal + <a href="https://cockpit-project.org/">cockpit</a>, but cockpit is sorta clunky.</li> <li>Few things I lack right now -- any proactive monitoring (eg: disk age/errors, CPU temps, logs etc.), periodic snapshot/backups, as I&#39;ve not gotten around to learning all that yet. </li> </ul> <p>Now I&#39;m upgrading to new SSDs + redundancy to make it more reliable for important data. And as a part of that, I can potentially change my OS too. </p> <p>I&#

## Help! DNS A Records only ones getting filtered.
 - [https://www.reddit.com/r/selfhosted/comments/1ijq58s/help_dns_a_records_only_ones_getting_filtered](https://www.reddit.com/r/selfhosted/comments/1ijq58s/help_dns_a_records_only_ones_getting_filtered)
 - RSS feed: $source
 - date published: 2025-02-07T08:11:17+00:00

<!-- SC_OFF --><div class="md"><p>I’m pulling my hair out over this. I’ve got a proxmox homelab, an LXC running technitium installed from TTeck’s script.</p> <p>The DNS server is also doing DHCP for my network. I have an authoritative zone for ‘.lan’</p> <p>I can get NS, SOA, TXT records from the DNS server, but no A records! The DNS query logs show that it gives an answer, and if I am on the DNS server itself I get an answer, but no other machines on the network hear the reply.</p> <p>I think this means the DNS server is working properly. There are no FWs in the way as I can resolve other types. </p> <p>Where else can I look, or how can I diagnose this? I am completely at a loss.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/bluesheepUK"> /u/bluesheepUK </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijq58s/help_dns_a_records_only_ones_getting_filtered/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/s

## Timeshift
 - [https://www.reddit.com/r/selfhosted/comments/1ijq168/timeshift](https://www.reddit.com/r/selfhosted/comments/1ijq168/timeshift)
 - RSS feed: $source
 - date published: 2025-02-07T08:02:55+00:00

<!-- SC_OFF --><div class="md"><p>I bought an Apple. What is the best solution to host TimeMaschine on my own Debian 12 Bookworm with Docker?</p> <p>Ich habe mir einen Apple zugelegt. Welches ist die beste Lösung um TimeMaschine auf dem eigenen Debian 12 Bookworm mit Docker selbst zu hosten?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AssociationMean5078"> /u/AssociationMean5078 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijq168/timeshift/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijq168/timeshift/">[comments]</a></span>

## What happens to files larger than 4GB in google photos takeout?
 - [https://www.reddit.com/r/selfhosted/comments/1ijntgm/what_happens_to_files_larger_than_4gb_in_google](https://www.reddit.com/r/selfhosted/comments/1ijntgm/what_happens_to_files_larger_than_4gb_in_google)
 - RSS feed: $source
 - date published: 2025-02-07T05:30:38+00:00

<!-- SC_OFF --><div class="md"><p>I might have multiple files uploaded on Google Photos which are larger than 4GB and <strong>ente photos</strong> says we need to export it in zip format only which doesn&#39;t support takeout size more than 4GB of each file. I want to know and understand what happens to the files larger than 4GB and how do I ensure that files are intact?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pakkedheeth"> /u/pakkedheeth </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijntgm/what_happens_to_files_larger_than_4gb_in_google/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijntgm/what_happens_to_files_larger_than_4gb_in_google/">[comments]</a></span>

## Build a website that let you search youtube and Vimeo in one place
 - [https://www.reddit.com/r/selfhosted/comments/1ijno2g/build_a_website_that_let_you_search_youtube_and](https://www.reddit.com/r/selfhosted/comments/1ijno2g/build_a_website_that_let_you_search_youtube_and)
 - RSS feed: $source
 - date published: 2025-02-07T05:21:44+00:00

<!-- SC_OFF --><div class="md"><p><a href="http://www.tubesynopsis.com">www.tubesynopsis.com</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Used_Ad8743"> /u/Used_Ad8743 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijno2g/build_a_website_that_let_you_search_youtube_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijno2g/build_a_website_that_let_you_search_youtube_and/">[comments]</a></span>

## Backups p2p like Crashplan was 10 years ago?
 - [https://www.reddit.com/r/selfhosted/comments/1ijn8kh/backups_p2p_like_crashplan_was_10_years_ago](https://www.reddit.com/r/selfhosted/comments/1ijn8kh/backups_p2p_like_crashplan_was_10_years_ago)
 - RSS feed: $source
 - date published: 2025-02-07T04:56:30+00:00

<!-- SC_OFF --><div class="md"><p>Crashplan was a Java based peer-to-peer backup system. You could allocate space on your system to allow other people you know to store encrypted backups.</p> <p>Does anything like this exist now? The concept seems to have died.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TheBlargus"> /u/TheBlargus </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijn8kh/backups_p2p_like_crashplan_was_10_years_ago/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijn8kh/backups_p2p_like_crashplan_was_10_years_ago/">[comments]</a></span>

## What to do with Server in School
 - [https://www.reddit.com/r/selfhosted/comments/1ijn2a9/what_to_do_with_server_in_school](https://www.reddit.com/r/selfhosted/comments/1ijn2a9/what_to_do_with_server_in_school)
 - RSS feed: $source
 - date published: 2025-02-07T04:46:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello all! Bit of an odd question lol. Basically, I am a senior in high school and I and a few friends in our python programming class have found an old tower dell poweredge t330 server. It&#39;s not a super powerful server by any means but we have fully reset it and have it running Debian (all with permission of course from both the teacher and the lead of the program that originally used the server for a class like 5-10 years ago). The server has a 3.smth ghz intel xeon CPU that I can&#39;t remember by heart but it&#39;s only like 4 core 4 thread and then like 16GB ram and 1TB HDD in it with a bunch of hot-swappable bays but we don&#39;t have the attachment piece to put other HDD&#39;s into the hot swappable spots. Anyway, my real question here is what are some fun services I should host that the class could use? I was thinking about bringing in my old GTX 1070 and lending it to the teacher for the semester and attempting to run a self-hosted AI mo

## So many self hosted items need some LLM. Whats the best direction to start selfhosting an LLM without needing mega hardware
 - [https://www.reddit.com/r/selfhosted/comments/1ijlp7t/so_many_self_hosted_items_need_some_llm_whats_the](https://www.reddit.com/r/selfhosted/comments/1ijlp7t/so_many_self_hosted_items_need_some_llm_whats_the)
 - RSS feed: $source
 - date published: 2025-02-07T03:30:33+00:00

<!-- SC_OFF --><div class="md"><p>Evening all. Selfhosting nut, with a number of proxmox hosts all doing my stuff, very happy, and love this community.</p> <p>The one thing that I havnt touched is an LLM. Ive used chatgpt and other tools, but when I see tools like paperless-aI and home assistant now connecting with LLM&#39;s, I just cant bring myself to subscribe to chatGPT for API. </p> <p>While my proxmox hosts are not giant machines with dedicated video cards, they are ticking along just fine. Can I get into my own LLM with modest hardware and proxmox? If so, what is the best direction to look at going down?</p> <p>Just a bit of direction please.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jdlnewborn"> /u/jdlnewborn </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijlp7t/so_many_self_hosted_items_need_some_llm_whats_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijlp7t/so_

## HDD'S acting out
 - [https://www.reddit.com/r/selfhosted/comments/1ijl8lk/hdds_acting_out](https://www.reddit.com/r/selfhosted/comments/1ijl8lk/hdds_acting_out)
 - RSS feed: $source
 - date published: 2025-02-07T03:06:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>Yesterday I got a email-message from my OMV that a SMART test had failed on 1 of my SAS HDD&#39;s.</p> <p>When I got upstairs, there was a annoying sound coming from the HDD bay (attached link)</p> <p>I disconnected disk by disk (and rebooting each time) to try to identify the problem disk.</p> <p>I started manually SMART testing each one. Turns out there where actually two disks that didn&#39;t pass the test.</p> <p>Luckily I have a 2 partity Snapraid set up, so all was well.</p> <p>I replaced the two malfunctioning HDD&#39;s with other ones I had laying around (second hand).</p> <p>When I booted the sound just reappeared, making me think the problem is not with the HDD&#39;s. </p> <p>I know HDD&#39;s aren&#39;t supposed to make such a beeping sound, so this sound has to come from my mobo right?</p> <p>However I still baffled as to how a possibly malfunctioning mobo can lead to two failed SMART test of 2 different HDD&#39;s?</

## How to Create Another Project in Self Hosted Supabase?
 - [https://www.reddit.com/r/selfhosted/comments/1ijl4nh/how_to_create_another_project_in_self_hosted](https://www.reddit.com/r/selfhosted/comments/1ijl4nh/how_to_create_another_project_in_self_hosted)
 - RSS feed: $source
 - date published: 2025-02-07T03:00:47+00:00

<!-- SC_OFF --><div class="md"><p>So I have been working lot of projects &amp; have been using self host supabase for my database needs. However on self host there is no option for creating another project like in cloud version. </p> <p>I have to create another server runnning for each project. </p> <p>Is there any better way? </p> <p>I really love supabase however doing things seperately each causing extra work for me a lot. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DefiantScarcity3133"> /u/DefiantScarcity3133 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijl4nh/how_to_create_another_project_in_self_hosted/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1ijl4nh/how_to_create_another_project_in_self_hosted/">[comments]</a></span>

## I'm discouraged. Maybe self-hosting isn't for me
 - [https://www.reddit.com/r/selfhosted/comments/1ijl3zu/im_discouraged_maybe_selfhosting_isnt_for_me](https://www.reddit.com/r/selfhosted/comments/1ijl3zu/im_discouraged_maybe_selfhosting_isnt_for_me)
 - RSS feed: $source
 - date published: 2025-02-07T02:59:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve posted a couple of times here in recent weeks discussing the beginnings of my self-hosting journey. Every time I think I finally get it, I get lost again. I can&#39;t figure out how to expose my apps to the outside network, I know apparently need to open docker containers to each other for things to work. It&#39;s so complicated. Hope I find the patience to give this more of my time.</p> <p>Truenas is up and running. Dockge, FileBrowser and some other apps are running. It all works locally. I got a domain on porkbun and have the wildcard A record in porkbun&#39;s DNS set to my public IP. That seems to be figured out.</p> <p>That&#39;s where the good ends and the wtf begins. I&#39;m a tech-oriented person but really feeling dumb.</p> <ol> <li><p>Put in my public IP and 443:443 in port forwarding on my router settings and it refuses to save</p></li> <li><p>Trying to set up reverse proxy and getting confused what domain name is what domain name

## Marreta 2.0: Destroy paywalls! ⚒️ 🧱
 - [https://www.reddit.com/r/selfhosted/comments/1ijl2iz/marreta_20_destroy_paywalls](https://www.reddit.com/r/selfhosted/comments/1ijl2iz/marreta_20_destroy_paywalls)
 - RSS feed: $source
 - date published: 2025-02-07T02:57:55+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1ijl2iz/marreta_20_destroy_paywalls/"> <img src="https://external-preview.redd.it/2vzi6rjhdsG0Vpz8mfeRh1WkcASwlWTYO4RTlK-yh-Y.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=b3e8960e2c5641576a1710e7d63c37c2e2103fbc" alt="Marreta 2.0: Destroy paywalls! ⚒️ 🧱" title="Marreta 2.0: Destroy paywalls! ⚒️ 🧱" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><strong>We just launched</strong> <a href="https://github.com/manualdousuario/marreta"><strong>version 2</strong></a><strong>! 🎉</strong></p> <p>Nothing explains <strong>Marreta</strong> better than this image:</p> <p><a href="https://preview.redd.it/vafqnn86gmhe1.png?width=678&amp;format=png&amp;auto=webp&amp;s=d0cdcfce8d38120756dabb7b282373018d08ea19">https://preview.redd.it/vafqnn86gmhe1.png?width=678&amp;format=png&amp;auto=webp&amp;s=d0cdcfce8d38120756dabb7b282373018d08ea19</a></p> <p>Over 25,000 pages have already been processed on the main instance (<a href="

## Need Help with Securely Exposing Services Using CrowdSec
 - [https://www.reddit.com/r/selfhosted/comments/1ijk5tq/need_help_with_securely_exposing_services_using](https://www.reddit.com/r/selfhosted/comments/1ijk5tq/need_help_with_securely_exposing_services_using)
 - RSS feed: $source
 - date published: 2025-02-07T02:10:55+00:00

<!-- SC_OFF --><div class="md"><p>I usually run my services through an Nginx reverse proxy, but now I need to expose some services to the internet. My current plan looks like this:</p> <p>A reverse proxy with CrowdSec installed on a <strong>DMZ VLAN</strong> &lt;--- <strong>OPNsense</strong> (with IPS enabled) &lt;--- THE <strong>internet</strong></p> <p>So far, I’ve set up everything except the CrowdSec integration and reverse proxy configuration.</p> <p>For internal services, I usually use Nginx, but there&#39;s no official CrowdSec bouncer for it. That led me to <strong>NPM Plus</strong>, which includes CrowdSec integration. However, I don’t fully understand how to modify or monitor CrowdSec within this setup, and I haven’t found many resources to guide me.</p> <p>I also looked into <strong>Traefik</strong>, but it seems more complicated than what I need, and most of my services are running on separate VMs. From what I understand, Traefik is more tailored for Docker, so I’m not su

## I Built a Personal Finance Dashboard with Next.js, Plaid, and Prisma – Self-Hosted & Privacy-Focused 💰💻
 - [https://www.reddit.com/r/selfhosted/comments/1ijhncr/i_built_a_personal_finance_dashboard_with_nextjs](https://www.reddit.com/r/selfhosted/comments/1ijhncr/i_built_a_personal_finance_dashboard_with_nextjs)
 - RSS feed: $source
 - date published: 2025-02-07T00:07:08+00:00

<!-- SC_OFF --><div class="md"><p>I wanted a <strong>fully customizable</strong> dashboard to track all my finances without relying on third-party apps like Mint or Personal Capital. So, I built my own <strong>Personal Finance Dashboard</strong> using <strong>Next.js, Plaid, and Prisma</strong>—and it&#39;s completely <strong>self-hosted</strong> for privacy!</p> <h1>Features:</h1> <p>✅ <strong>Secure bank account integration</strong> via Plaid<br/> ✅ <strong>Daily email balance updates</strong><br/> ✅ <strong>Historical tracking &amp; data visualization</strong> (Chart.js)<br/> ✅ <strong>Full control over sensitive financial data</strong><br/> ✅ <strong>Runs locally</strong> (SQLite + Prisma)</p> <h1>Tech Stack:</h1> <ul> <li><strong>Next.js (App Router)</strong> – API routes &amp; SSR</li> <li><strong>Prisma + SQLite</strong> – Local database with type safety</li> <li><strong>Plaid API</strong> – Securely fetch banking data</li> <li><strong>TailwindCSS</strong> – Rapid UI developme

