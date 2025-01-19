# Source:Self-Hosted Alternatives to Popular Services, URL:https://www.reddit.com/r/selfhosted/.rss, language:en

## What security measures should I use?
 - [https://www.reddit.com/r/selfhosted/comments/1i4jf8x/what_security_measures_should_i_use](https://www.reddit.com/r/selfhosted/comments/1i4jf8x/what_security_measures_should_i_use)
 - RSS feed: $source
 - date published: 2025-01-18T22:39:13+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m new to this and just setup a Raspberry Pi. What security measures should I implement? </p> <p>This is what services I&#39;m currently running:</p> <ul> <li>Docker / Portainer</li> <li>Heimdall</li> <li>Nginx Proxy Manager - default settings, still learning how to use it.</li> <li>Adguard Home</li> <li>Wireguard</li> <li>Paperless-ngx</li> </ul> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dungeon_Crawler_Carl"> /u/Dungeon_Crawler_Carl </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4jf8x/what_security_measures_should_i_use/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4jf8x/what_security_measures_should_i_use/">[comments]</a></span>

## Keep media server up while maintaining the server
 - [https://www.reddit.com/r/selfhosted/comments/1i4jarx/keep_media_server_up_while_maintaining_the_server](https://www.reddit.com/r/selfhosted/comments/1i4jarx/keep_media_server_up_while_maintaining_the_server)
 - RSS feed: $source
 - date published: 2025-01-18T22:33:18+00:00

<!-- SC_OFF --><div class="md"><p>I have a Jellyfin instance with about 20 users. On weekends or in the evenings, I usually have 6 or 7 users using the server at the same time. These are also the times when I have free time to tinker with it. I now have plans to upgrade my server, which will take me at least 1 or 2 days (including 3D printing parts, trying them out, and optimizing said parts). The Jellyfin instance is running in Docker, with the media stored on my NAS.</p> <p>My question is: is there any easy and straightforward way to keep the Jellyfin instance running without dealing with high availability, Kubernetes, etc., while maintaining the main server? I have my main PC and a couple of laptops I can use.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/golbaf"> /u/golbaf </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4jarx/keep_media_server_up_while_maintaining_the_server/">[link]</a></span> &#32; <span><a href=

## Looking for a fully free/open source web control panel for my home server
 - [https://www.reddit.com/r/selfhosted/comments/1i4iway/looking_for_a_fully_freeopen_source_web_control](https://www.reddit.com/r/selfhosted/comments/1i4iway/looking_for_a_fully_freeopen_source_web_control)
 - RSS feed: $source
 - date published: 2025-01-18T22:14:26+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I&#39;ve been running a home server with multiple web services on Apache with a static IP and domain name. </p> <p>My current setup includes: </p> <p>- Nextcloud for file storage/sync<br/> - Matomo for analytics<br/> - IRC server<br/> - Cockpit for system monitoring </p> <p>Everything is working great, and I&#39;ve spent quite some time setting it all up through SSH (headless Ubuntu on bare metal). While SSH management is fine, as the number of services grows, I&#39;m looking for a good web-based control panel to make things easier. For example, I&#39;d like to host a WordPress website and perhaps some React.js webapps in the future. </p> <p>The important part is that I&#39;d rather not have to reinstall everything from scratch - these services are running well and have lots of data/config I&#39;d like to preserve. I&#39;ve looked into options like Cloudron, Plesk, and Webmin, but I&#39;m specifically interested in completely fre

## Photo library that supports HDR
 - [https://www.reddit.com/r/selfhosted/comments/1i4ilnk/photo_library_that_supports_hdr](https://www.reddit.com/r/selfhosted/comments/1i4ilnk/photo_library_that_supports_hdr)
 - RSS feed: $source
 - date published: 2025-01-18T22:00:50+00:00

<!-- SC_OFF --><div class="md"><p>I’m looking for a way to share all fotos from my camera to my friends. The only features that I really need is indexing based on date of all my files that I already have in folders on my computer. All other features like AI indexing, search and the like are gravy but not essential.</p> <p>Lately I have been getting into HDR photography since Lightroom supports exporting HDR files. However, I’ve found that neither Immich nor PhotoPrism support viewing HDR files, either saved in AVIF or JPEGXL. Does anybody know if there is a self hosted foto library that does support HDR viewing at the moment?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fenjen"> /u/Fenjen </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ilnk/photo_library_that_supports_hdr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ilnk/photo_library_that_supports_hdr/">[comments]</a></spa

## Help excluding subdirectories in rclone
 - [https://www.reddit.com/r/selfhosted/comments/1i4hkcu/help_excluding_subdirectories_in_rclone](https://www.reddit.com/r/selfhosted/comments/1i4hkcu/help_excluding_subdirectories_in_rclone)
 - RSS feed: $source
 - date published: 2025-01-18T21:13:30+00:00

<!-- SC_OFF --><div class="md"><p>My experience in Ubuntu Server is fairly remedial as I&#39;m only on about week three with it. In that time I&#39;ve learnt the importance of backups so I&#39;m trying to create a script to run rclone nightly to backup to cloud storage.</p> <p>Folders being backed up: /home/user_name/docker /home/user_name/documents</p> <p>Issue: I&#39;d like to ideally keep the folder structure starting inside /home/user_name There are subdirectories inside docker that I do not want or need backed up.</p> <p>So far I&#39;ve modified a script I found online and tried two things. First I&#39;ve tried this to see if I could exclude everything except /documents, but the result was a backup the entirety of /user_name/</p> <p>``` rclone.sh &#39;NOW=$(date +&quot;%Y-%m-%dT%H%M%S%z&quot;) SOURCE=/home/user_name DEST=idrive:user_name</p> <p>rclone sync $SOURCE ${DEST} \ --fast-list \ --exclude=&quot;/downloads/** --exclude=&quot;/docker/** --progress -v \ --backup-dir ${DEST

## Uptime kuma notification email lower
 - [https://www.reddit.com/r/selfhosted/comments/1i4hb97/uptime_kuma_notification_email_lower](https://www.reddit.com/r/selfhosted/comments/1i4hb97/uptime_kuma_notification_email_lower)
 - RSS feed: $source
 - date published: 2025-01-18T21:02:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i4hb97/uptime_kuma_notification_email_lower/"> <img src="https://preview.redd.it/xlmp3d3zgtde1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=8f3ce4849aa5294d4ef4442284c5946736fa6099" alt="Uptime kuma notification email lower" title="Uptime kuma notification email lower" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Is there a way to send an email for just the group being down not every single monitor? I am going to look at the settings now and see if I can tie the notification to just the group. Any input is appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Squanchy2112"> /u/Squanchy2112 </a> <br/> <span><a href="https://i.redd.it/xlmp3d3zgtde1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4hb97/uptime_kuma_notification_email_lower/">[comments]</a></span> </td></tr></table>

## Anyway to restart/clear SWAG dashboard logs?
 - [https://www.reddit.com/r/selfhosted/comments/1i4h85y/anyway_to_restartclear_swag_dashboard_logs](https://www.reddit.com/r/selfhosted/comments/1i4h85y/anyway_to_restartclear_swag_dashboard_logs)
 - RSS feed: $source
 - date published: 2025-01-18T20:58:21+00:00

<!-- SC_OFF --><div class="md"><p>I cannot for the life of me find out where the dashboard is logging the history for the connection. I just need some help identifying where they could be so i can reset the stats. </p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Insulated_"> /u/Insulated_ </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4h85y/anyway_to_restartclear_swag_dashboard_logs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4h85y/anyway_to_restartclear_swag_dashboard_logs/">[comments]</a></span>

## Need to back up my digital life ASAP. Any reliable solutions?
 - [https://www.reddit.com/r/selfhosted/comments/1i4h50g/need_to_back_up_my_digital_life_asap_any_reliable](https://www.reddit.com/r/selfhosted/comments/1i4h50g/need_to_back_up_my_digital_life_asap_any_reliable)
 - RSS feed: $source
 - date published: 2025-01-18T20:54:21+00:00

<!-- SC_OFF --><div class="md"><p>So, I&#39;ve been following the news about the recent LA wildfires, and it really got me thinking: What if I suddenly lost all my important files—like family photos, work documents, or personal projects? Nowadays, my cellphone and laptop hold pretty much everything important to me. I gotta start backing everything up ASAP, but I’m not quiet sure which method / strategy to go with. There&#39;s so many options out there—cloud services, external hard drives, nas storage, backup software and services, etc.</p> <p>What do you recommend for a reliable and easy backup solution? I’d love to hear about what’s worked (or hasn’t worked) for you, and any tips for keeping data safe in general!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DependentEast4454"> /u/DependentEast4454 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4h50g/need_to_back_up_my_digital_life_asap_any_reliable/">[link]</a></spa

## Bought a domain now what?
 - [https://www.reddit.com/r/selfhosted/comments/1i4h4ss/bought_a_domain_now_what](https://www.reddit.com/r/selfhosted/comments/1i4h4ss/bought_a_domain_now_what)
 - RSS feed: $source
 - date published: 2025-01-18T20:54:04+00:00

<!-- SC_OFF --><div class="md"><p>I am novice, looking for some simple advice or some simple guide, I bought a domain for three years for $30 through Cloudflare, and I don’t want to host a website, but I want to be able to access some servers I have setup at home with out port forwarding as I understand that’s not a very good idea.</p> <p>Below are the services I want to use, am I on the right path to setup just a reverse proxy? And is this correct for each server I just a random address example (133383test.123456789.xyz) ? And then learn how to setup fail ban to ensure timeout, I just trying to ensure to lessen of my chance of being hacked or brute forceattacked, and the keeping exposer down while being able to access out side of the house. I understand once I open to the internet auto increase possibility, I cant do WireGuard as I want to share with my kids, a few select family members certain service and since I wont control each device. Running behind Pfsense.</p> <p>• Bedrock Mi

## Nginx routing issue: Blog subpaths get stripped when accessing Astro.js blog from Next.js main site (/blog/posts → /posts)
 - [https://www.reddit.com/r/selfhosted/comments/1i4gtoy/nginx_routing_issue_blog_subpaths_get_stripped](https://www.reddit.com/r/selfhosted/comments/1i4gtoy/nginx_routing_issue_blog_subpaths_get_stripped)
 - RSS feed: $source
 - date published: 2025-01-18T20:39:44+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m experiencing a frustrating routing issue with my dockerized setup running a Next.js main site alongside an Astro.js blog, both behind Nginx reverse proxy. While the base blog path works perfectly, any subpaths are inexplicably losing their <code>/blog</code> prefix during navigation.</p> <p><strong>Current Setup:</strong></p> <ul> <li>Main site: Next.js (dockerized, running on localhost:3000)</li> <li>Blog: Astro.js (dockerized, running on localhost:7000)</li> <li>Nginx as reverse proxy</li> <li>SSL enabled (managed by Certbot)</li> </ul> <p><strong>The Issue:</strong> The base blog path works flawlessly - <a href="http://domain.com/blog"><code>domain.com/blog</code></a> serves content correctly. However, when accessing any subpath, the URL gets rewritten to drop the <code>/blog</code> prefix. For example:</p> <ul> <li><a href="http://domain.com/blog/posts"><code>domain.com/blog/posts</code></a> gets rewritten to <a href="http://domain.com/po

## TubeArchivist alternatives?
 - [https://www.reddit.com/r/selfhosted/comments/1i4gii0/tubearchivist_alternatives](https://www.reddit.com/r/selfhosted/comments/1i4gii0/tubearchivist_alternatives)
 - RSS feed: $source
 - date published: 2025-01-18T20:25:16+00:00

<!-- SC_OFF --><div class="md"><p>I have been using TubeArchivist for a long, long time - but I think I finally hit it&#39;s breaking point ... or rather, my kernel&#39;s.</p> <p>To make a long story short, I needed this:</p> <p>```</p> <h1>cat /etc/sysctl.conf</h1> <p>(...)</p> <h1>Custom</h1> <p>kernel.pid_max = 4194303 fs.inotify.max_user_watches=1048576 fs.inotify.max_user_instances=1024 ```</p> <p>to stop my node from crashing in the first place. But the crashes return - and, the ElasticSearch database it uses eats a solid 3GB of my memory now, which is /actually/ insane. My total archive comes in at 1.9T (<code>du -h -d 0 $ta_path</code>). It is, genuenly, big. Likely too big for TA.</p> <p>What other tools are out there that serve TA&#39;s purpose? The features I used a lot:</p> <ul> <li>Subscribing to a channel and dumping it down to disk. (Useful for very volatile channels that host content that is bound to disappear soon.)</li> <li>Download videos in the background to later

## Recommend any self-hosted blogging platforms? (Switching from Blogger)
 - [https://www.reddit.com/r/selfhosted/comments/1i4g7kd/recommend_any_selfhosted_blogging_platforms](https://www.reddit.com/r/selfhosted/comments/1i4g7kd/recommend_any_selfhosted_blogging_platforms)
 - RSS feed: $source
 - date published: 2025-01-18T20:11:26+00:00

<!-- SC_OFF --><div class="md"><p>I run a personal art blog on blogger/blogspot that I share to just myself and my friends. I&#39;d like to create a locally hosted copy of it to transition away from google owned services. Ideally, I&#39;d like to be able to simply export my blog&#39;s HTML and XML and import it into the new self hosted blog. I&#39;m still a relative novice when it comes to this sort of stuff. I know a little about the linux terminal. I looked through this github for recommendations:<br/> <a href="https://github.com/awesome-selfhosted/awesome-selfhosted?tab=readme-ov-file#blogging-platforms">https://github.com/awesome-selfhosted/awesome-selfhosted?tab=readme-ov-file#blogging-platforms</a></p> <p>I looked at Ghost, but if I&#39;m correct, even if you self host it, it&#39;s hosted as a subdomain and you have to pay to keep it active. Ideally I&#39;d like to just port forward my raspberry pi and send a link to my friends.</p> <p>I&#39;d like for whatever self hosted plat

## Looking for a free Self Hosted Data Collection System
 - [https://www.reddit.com/r/selfhosted/comments/1i4fsjk/looking_for_a_free_self_hosted_data_collection](https://www.reddit.com/r/selfhosted/comments/1i4fsjk/looking_for_a_free_self_hosted_data_collection)
 - RSS feed: $source
 - date published: 2025-01-18T19:52:34+00:00

<!-- SC_OFF --><div class="md"><p>Good People, i am looking for a free self hosted data collection system . The system should provide some sort of a form for the users to input their details which can be displayed in a database and would like the database to be exported to excell or anything similar as well as import excell data from other sources..Also another thing the form should have a feature where it duplicate entries will be rejected</p> <p>TIA</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/soccer-geek"> /u/soccer-geek </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4fsjk/looking_for_a_free_self_hosted_data_collection/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4fsjk/looking_for_a_free_self_hosted_data_collection/">[comments]</a></span>

## High RAM Usage
 - [https://www.reddit.com/r/selfhosted/comments/1i4fmzj/high_ram_usage](https://www.reddit.com/r/selfhosted/comments/1i4fmzj/high_ram_usage)
 - RSS feed: $source
 - date published: 2025-01-18T19:45:44+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i4fmzj/high_ram_usage/"> <img src="https://b.thumbs.redditmedia.com/yOwZplGJRll6UUYUNDsALO029vJyXnSrOzj10_Ky7gU.jpg" alt="High RAM Usage" title="High RAM Usage" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I am an absolute noob and bought a pi to set up a Pi-hole. Started getting carried away and have expanded to a few other containers. I have a pi 3b+ running the following containers (see picture).</p> <p>Is the RAM usage normal or did I do something wrong.</p> <p>In many occasions the pi will kill the network and need a power cycle to begin functioning again. During these times the RAM usually spikes.</p> <p>Any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/frnchpaper"> /u/frnchpaper </a> <br/> <span><a href="https://www.reddit.com/gallery/1i4fmzj">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4fmzj/high_ram_usage/">[c

## Mounting case fans on gpu for quiet home server.
 - [https://www.reddit.com/r/selfhosted/comments/1i4fl95/mounting_case_fans_on_gpu_for_quiet_home_server](https://www.reddit.com/r/selfhosted/comments/1i4fl95/mounting_case_fans_on_gpu_for_quiet_home_server)
 - RSS feed: $source
 - date published: 2025-01-18T19:43:36+00:00

<!-- SC_OFF --><div class="md"><p>I have really old mobo and processor that doesnt support a lot of codecs, I also use my gpu for some upscaling work but the issue is that my nvidia 1660 super fans are really loud. They also spin all the time because this card version doesn&#39;t have zero rpm mode or anything like this. I sleep in the same room so noise level is issue for me.</p> <p>Do any of you know if its safe to connect two 120mm fans to gpu header with this connector? <a href="https://www.amazon.pl/gp/product/B075LKL5DH?smid=A2R2221NX79QZP&amp;psc=1">https://www.amazon.pl/gp/product/B075LKL5DH?smid=A2R2221NX79QZP&amp;psc=1</a><br/> the fans I wanted to use are arctic p12 slim pwm pst</p> <p>I&#39;m still not sure how can I mount them because tape is probably not good option (the card gets to hot for tape) and if the fan would be to close on the heatsink it would create turbulance and noise. Do any of you know what can I do about this? And whether I need some type of resistor co

## GitHub - mikebgrep/fork.recipes: Web application that manage food recipes with simplicity. New version just dropped out AI generation of recipe by a given ingredient + scrape the recipe with the help of ai.
 - [https://www.reddit.com/r/selfhosted/comments/1i4fiu2/github_mikebgrepforkrecipes_web_application_that](https://www.reddit.com/r/selfhosted/comments/1i4fiu2/github_mikebgrepforkrecipes_web_application_that)
 - RSS feed: $source
 - date published: 2025-01-18T19:40:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i4fiu2/github_mikebgrepforkrecipes_web_application_that/"> <img src="https://external-preview.redd.it/c1jnC4tmq1o2LxidjPQ5YHizTXNsd_4EdIdDQxRoHlA.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=197b6076d5f9d5aa2cde76306a3d0ea796478285" alt="GitHub - mikebgrep/fork.recipes: Web application that manage food recipes with simplicity. New version just dropped out AI generation of recipe by a given ingredient + scrape the recipe with the help of ai." title="GitHub - mikebgrep/fork.recipes: Web application that manage food recipes with simplicity. New version just dropped out AI generation of recipe by a given ingredient + scrape the recipe with the help of ai." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Affectionate-Dog-715"> /u/Affectionate-Dog-715 </a> <br/> <span><a href="https://github.com/mikebgrep/fork.recipes">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/s

## Seeking backup solution
 - [https://www.reddit.com/r/selfhosted/comments/1i4ffz4/seeking_backup_solution](https://www.reddit.com/r/selfhosted/comments/1i4ffz4/seeking_backup_solution)
 - RSS feed: $source
 - date published: 2025-01-18T19:37:06+00:00

<!-- SC_OFF --><div class="md"><p>Hey All, </p> <p>My homelab consists of a dell r730XD &amp; a synology nas. i always backuped our phone pictures to the nas without thinking about it. always nice to have your phone back up this way. Currenly i came across a lot of posts that raid isn&#39;t a backup, and this made me think &amp; its actually true. &amp; since i have the infrastructure, i could easily backup this aswell. </p> <p>NAS has always been used for backup up purposes. </p> <p>Dell Server is running multiple vms &amp; services, &amp; the import ones i back up using veeam &amp; smb share on the nas. </p> <p>the thing which bothers me now is, as the nas the being used for backup only, it doesn&#39;t seem right to backup my nas (only the pictures) to my dell server. So i am looking to host something on my server the same way synology has (free app, let the backup run &amp; have a nice gui incase you wanna see the pics that way). so i can backup that service to my nas, so my nas s

## Looking for something to do regulair phonecalls through my desktop
 - [https://www.reddit.com/r/selfhosted/comments/1i4erq5/looking_for_something_to_do_regulair_phonecalls](https://www.reddit.com/r/selfhosted/comments/1i4erq5/looking_for_something_to_do_regulair_phonecalls)
 - RSS feed: $source
 - date published: 2025-01-18T19:06:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone!</p> <p>This idea probably makes no sense or won&#39;t work because i have a normal phone number and not a business/company.</p> <p>But i would love to host something so i can do my normal phone calls through my computer, so i can use my headset instead of using my phone to make calls/pickup calls.</p> <p>Would love to hear your opinion on this, sorry if this sounds silly/unachievable</p> <p>Also, i should&#39;ve mention that i am using an iPhone sadly.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Macley6969"> /u/Macley6969 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4erq5/looking_for_something_to_do_regulair_phonecalls/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4erq5/looking_for_something_to_do_regulair_phonecalls/">[comments]</a></span>

## Help with TP-Link LS1005G switch
 - [https://www.reddit.com/r/selfhosted/comments/1i4enhj/help_with_tplink_ls1005g_switch](https://www.reddit.com/r/selfhosted/comments/1i4enhj/help_with_tplink_ls1005g_switch)
 - RSS feed: $source
 - date published: 2025-01-18T19:01:33+00:00

<!-- SC_OFF --><div class="md"><p>So I have a simple small TP-Link LS1005G gigabit switch for almost 2 years. In the last days I bought a new mini pc, and suddenly it is acting weird. It has 5 ports, but when I use all 5, it simply doesn’t work.</p> <p>The setup is:</p> <ul> <li>1 port is where internet comes in from my router to the first port of the switch.</li> <li>1 port goes to main pc</li> <li>1 port goes to security cameras</li> <li>1 port goes to a raspberry pi</li> <li>1 should go to my new mini pc.</li> </ul> <p>What happen is:</p> <ul> <li>1 port light goes on</li> <li>all port lights go on (for this brief period of time, I can ping my mini pc)</li> <li>all port lights go off</li> </ul> <p>This repeats over and over, but when I remove one RJ45 cable (doesn’t matter which) it works. For some reason, I can only use 4 of them. Is there any solution? Is anything broken somehow?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NorthBat2171"

## Best self-hosted AI UI?
 - [https://www.reddit.com/r/selfhosted/comments/1i4ef8g/best_selfhosted_ai_ui](https://www.reddit.com/r/selfhosted/comments/1i4ef8g/best_selfhosted_ai_ui)
 - RSS feed: $source
 - date published: 2025-01-18T18:51:24+00:00

<!-- SC_OFF --><div class="md"><p>Hey!</p> <p>What AI UI are you using? I tried anything llm but using the web ui on mobile isn&#39;t as good as Poe&#39;s mobile app.</p> <p>I would like something where I host the backend and connect mobile/desktop apps to it. Is there anything like that?</p> <p>Cheers </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Dizzy-Revolution-300"> /u/Dizzy-Revolution-300 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ef8g/best_selfhosted_ai_ui/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ef8g/best_selfhosted_ai_ui/">[comments]</a></span>

## Securing Self-Hosted Apps with Pocket ID / OAuth2-Proxy
 - [https://www.reddit.com/r/selfhosted/comments/1i4ecbx/securing_selfhosted_apps_with_pocket_id](https://www.reddit.com/r/selfhosted/comments/1i4ecbx/securing_selfhosted_apps_with_pocket_id)
 - RSS feed: $source
 - date published: 2025-01-18T18:47:46+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Overall4981"> /u/Overall4981 </a> <br/> <span><a href="https://thesynack.com/posts/securing-with-oauth2-proxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ecbx/securing_selfhosted_apps_with_pocket_id/">[comments]</a></span>

## Leantime alternative?
 - [https://www.reddit.com/r/selfhosted/comments/1i4e5ae/leantime_alternative](https://www.reddit.com/r/selfhosted/comments/1i4e5ae/leantime_alternative)
 - RSS feed: $source
 - date published: 2025-01-18T18:38:56+00:00

<!-- SC_OFF --><div class="md"><p>I really wanted to like Leantime, and I do like the look and feel, but it&#39;s just too naggy. They seem to go out of their way to litter the interface with premium links that take you to their store page, and if I&#39;m going to the trouble of self hosting a service, I don&#39;t really like that service constantly telling me I&#39;m a peasant. Admittedly what really pissed me off is that you can remove these links and just hide the premium features... for a fee. A subscription fee. I think I&#39;d be willing to pay $3-$5 as a one time thing, but there&#39;s no way I&#39;m paying a subscription fee just to hide features I&#39;m not paying for. That crossed the line, so unfortunately Leantime has gotta go.</p> <p>My use case is simple organization of various personal projects, some software and some not. I like being able to jot down a list of requirements into tasks and tackle them one at a time. I use Gitea as my code repo and Bookstack as a wiki, 

## Best Ways to Find Test Users for a SaaS?
 - [https://www.reddit.com/r/selfhosted/comments/1i4dgts/best_ways_to_find_test_users_for_a_saas](https://www.reddit.com/r/selfhosted/comments/1i4dgts/best_ways_to_find_test_users_for_a_saas)
 - RSS feed: $source
 - date published: 2025-01-18T18:08:41+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I’m looking for tips on getting test users for a new <a href="http://zetreport.com">SaaS</a>.</p> <p>How do you find people willing to test and give honest feedback? Any platforms or strategies that worked well for you?</p> <p>Appreciate any advice!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Competitive_Ad_408"> /u/Competitive_Ad_408 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4dgts/best_ways_to_find_test_users_for_a_saas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4dgts/best_ways_to_find_test_users_for_a_saas/">[comments]</a></span>

## Cockpit samba - can't add/edit files via win
 - [https://www.reddit.com/r/selfhosted/comments/1i4d9i5/cockpit_samba_cant_addedit_files_via_win](https://www.reddit.com/r/selfhosted/comments/1i4d9i5/cockpit_samba_cant_addedit_files_via_win)
 - RSS feed: $source
 - date published: 2025-01-18T18:00:04+00:00

<!-- SC_OFF --><div class="md"><p>Sorry not sure if this is the appropriate sub for this tool but hopefully it is. Got this running on a lxc container, installed the filesharing addon and identities addon. Made a user and gave a samba password (different than main pass). I can access everything however I can&#39;t seem to add new files to the sub directories.</p> <p>What&#39;s odd is this was working a week ago. I did change the file sharing settings for my samba mount path to include windows acl so perhaps that broke it. Anyways just unsure where to set the permissions </p> <p>I see a button marked edit permissions and it already has 777 and I assigned it to my new user. </p> <p>Any help is greatly appreciated </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RoachForLife"> /u/RoachForLife </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4d9i5/cockpit_samba_cant_addedit_files_via_win/">[link]</a></span> &#32; <span><a hre

## Built a simple self-hosted Linktree replacement. Still kinda basic!
 - [https://www.reddit.com/r/selfhosted/comments/1i4ck8x/built_a_simple_selfhosted_linktree_replacement](https://www.reddit.com/r/selfhosted/comments/1i4ck8x/built_a_simple_selfhosted_linktree_replacement)
 - RSS feed: $source
 - date published: 2025-01-18T17:29:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ExistentialEnso"> /u/ExistentialEnso </a> <br/> <span><a href="https://www.smoltree.xyz/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ck8x/built_a_simple_selfhosted_linktree_replacement/">[comments]</a></span>

## Storing/organizing business- and customer data
 - [https://www.reddit.com/r/selfhosted/comments/1i4buh8/storingorganizing_business_and_customer_data](https://www.reddit.com/r/selfhosted/comments/1i4buh8/storingorganizing_business_and_customer_data)
 - RSS feed: $source
 - date published: 2025-01-18T16:57:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>I am looking for a self-hosting tool to store information. It is primarily about company and customer data. It can be anything from normal text, graphics, PDF files, ZIP files, archives in general, etc. So far I&#39;ve been using Obsidian, which I also like, but it&#39;s becoming too cluttered for my business data. I looked around a bit and installed Bookstack. There, each customer is a chapter, and then has corresponding subpages. I like that much better than Obsidian, especially because I can access it from anywhere without sync. I wonder if there is something that might be even better before I start migrating all the data from Obsidian to Bookstack. Has anyone been in a similar situation and have any ideas? </p> <p>Many thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CrissCross85"> /u/CrissCross85 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/

## File storage with Fixed Pricing (like uploadthing)
 - [https://www.reddit.com/r/selfhosted/comments/1i4bpaa/file_storage_with_fixed_pricing_like_uploadthing](https://www.reddit.com/r/selfhosted/comments/1i4bpaa/file_storage_with_fixed_pricing_like_uploadthing)
 - RSS feed: $source
 - date published: 2025-01-18T16:51:20+00:00

<!-- SC_OFF --><div class="md"><p>Looking for file storage options with fixed pricing and ideally S3 SDK compatibility. Any recommendations?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/new-oneechan"> /u/new-oneechan </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4bpaa/file_storage_with_fixed_pricing_like_uploadthing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4bpaa/file_storage_with_fixed_pricing_like_uploadthing/">[comments]</a></span>

## Please help with Cloudflare tunnel on Android - worked fine until update
 - [https://www.reddit.com/r/selfhosted/comments/1i4bfrn/please_help_with_cloudflare_tunnel_on_android](https://www.reddit.com/r/selfhosted/comments/1i4bfrn/please_help_with_cloudflare_tunnel_on_android)
 - RSS feed: $source
 - date published: 2025-01-18T16:39:37+00:00

<!-- SC_OFF --><div class="md"><p>I have had a cloudflare tunnel running on my network for about a year now and it&#39;s worked great up until a few months ago when I updated my Android phone. Now, I can&#39;t get to any internal IP addresses on my network. </p> <p>The Warp client on my iPad and computer still function exactly as before, it&#39;s just our Android phones. </p> <p>Going to <a href="http://help.teams.cloudflare.com">help.teams.cloudflare.com</a> shows that everything is configured correctly.</p> <p>Putting in routed internal IP addresses just sits there with an error that the connection was interrupted.</p> <p>Any help on how to troubleshoot this would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BBQ_Master"> /u/BBQ_Master </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4bfrn/please_help_with_cloudflare_tunnel_on_android/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## BUY a dedicated server
 - [https://www.reddit.com/r/selfhosted/comments/1i4az80/buy_a_dedicated_server](https://www.reddit.com/r/selfhosted/comments/1i4az80/buy_a_dedicated_server)
 - RSS feed: $source
 - date published: 2025-01-18T16:18:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am looking for a place where I could buy a computer and rent the place where it says, so it is not in my home.</p> <p>Likely something with a high setup cost and a much smaller monthly fee. Does something like this exists?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vbenevides"> /u/vbenevides </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4az80/buy_a_dedicated_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4az80/buy_a_dedicated_server/">[comments]</a></span>

## Looking for self hosted wordgames
 - [https://www.reddit.com/r/selfhosted/comments/1i4ajjv/looking_for_self_hosted_wordgames](https://www.reddit.com/r/selfhosted/comments/1i4ajjv/looking_for_self_hosted_wordgames)
 - RSS feed: $source
 - date published: 2025-01-18T15:58:57+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>I&#39;m running a few self hosted services - so I have a bit of space to spin up a few docker images etc.. I am looking for something to keep my mum amused = she likes crossword/wordsearch and similar games on her phone/tablet, but i am getting forever annoyed at the number of ads and so on, is there something that i can self host, so she can play on a safe site? (I have nginx etc all running fine)</p> <p>much appreciated, and thanks in advance to you amazing folk in here :)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/circuit_beard"> /u/circuit_beard </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ajjv/looking_for_self_hosted_wordgames/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4ajjv/looking_for_self_hosted_wordgames/">[comments]</a></span>

## Content Security Policies (CSP) and NGINX / SWAG
 - [https://www.reddit.com/r/selfhosted/comments/1i4a8zu/content_security_policies_csp_and_nginx_swag](https://www.reddit.com/r/selfhosted/comments/1i4a8zu/content_security_policies_csp_and_nginx_swag)
 - RSS feed: $source
 - date published: 2025-01-18T15:45:27+00:00

<!-- SC_OFF --><div class="md"><p>I trying tune up my CSP headers in my swag / nginx proxy.</p> <p>In the same way there are addons that can generate the CSP rules while you navigate <a href="https://csper.io/docs/generating-content-security-policy">https://csper.io/docs/generating-content-security-policy</a></p> <p>Is there any easy and open source way to use report-uri function of CSP to report all the logs to another app that will use that info to tune up the CSP policy?</p> <p>Basically this but for free, something that I could self host</p> <p><a href="https://csper.io/report-uri">https://csper.io/report-uri</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/l0rd_raiden"> /u/l0rd_raiden </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4a8zu/content_security_policies_csp_and_nginx_swag/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i4a8zu/content_security_policies_csp_and_nginx

## Looking for an MDM - Selfhost
 - [https://www.reddit.com/r/selfhosted/comments/1i49vqd/looking_for_an_mdm_selfhost](https://www.reddit.com/r/selfhosted/comments/1i49vqd/looking_for_an_mdm_selfhost)
 - RSS feed: $source
 - date published: 2025-01-18T15:28:02+00:00

<!-- SC_OFF --><div class="md"><p>So for context I do volunteer IT work for a volunteer ambulance service. The ambulances all have Android tablets for GPS and on board details and tracking. Also, all medics have an android phone that have specific medical apps for on the spot checking, communication, GPS tracking and emergency systems.</p> <p>I was talking to the boss man the other day, and he was on a call with an MDM provider who wanted $5000 a year plus $100 per device. As a small volunteer service, these prices are not feasible, so I said I would look into it, if they can set up something like just pay towards electricity fees of a server I will host it for free. </p> <p>I am open to any suggestions anyone has, I have found a couple that are beyond complicated to install for some reason spent 3 hours trying to install Headwind MDM only to not have it go anywhere in the installation refusing to see the database and such. The other option I have been told is Mesh Central, but don&#

## Alternatives to Authentik for basic homelab
 - [https://www.reddit.com/r/selfhosted/comments/1i496mi/alternatives_to_authentik_for_basic_homelab](https://www.reddit.com/r/selfhosted/comments/1i496mi/alternatives_to_authentik_for_basic_homelab)
 - RSS feed: $source
 - date published: 2025-01-18T14:54:02+00:00

<!-- SC_OFF --><div class="md"><p>As the title suggests, I tried it and spent an entire weekend failing to get Authentik and Portainer to Oauth2 (might be my traefik setup or something with Cloudflare tunnels not passing all the oauth info to portainer). After all that (not really complaining as it is part of the SH journey), I realized that I don’t need all the bells and whistles of Authentik. </p> <p>I saw a post a while back where someone mentioned an easy simple self hosted solution that could use facial recognition tools on devices for SSO (and it was very wife and kid friendly!). Of course, I can’t find the GitHub link now (I know I should use other SH solutions like Hoarder, eventually). Anyone got any recommendations for a basic homelabber who wants to add a little more security to access applications and simplify with a SSO experience (ideally with the security features already built into our phones and laptops)? Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hr

## d3ward toolz adblock test is archived. How can I self-host this?
 - [https://www.reddit.com/r/selfhosted/comments/1i48tc0/d3ward_toolz_adblock_test_is_archived_how_can_i](https://www.reddit.com/r/selfhosted/comments/1i48tc0/d3ward_toolz_adblock_test_is_archived_how_can_i)
 - RSS feed: $source
 - date published: 2025-01-18T14:35:48+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t see on his GitHub a straightforward way to install it. does anyone know how to create a docker container script for this? <a href="https://d3ward.github.io/toolz/">https://d3ward.github.io/toolz/</a></p> <p><a href="https://github.com/d3ward/toolz">https://github.com/d3ward/toolz</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Atvriders"> /u/Atvriders </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i48tc0/d3ward_toolz_adblock_test_is_archived_how_can_i/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i48tc0/d3ward_toolz_adblock_test_is_archived_how_can_i/">[comments]</a></span>

## SilverBullet: Sweet little app for markdown notes
 - [https://www.reddit.com/r/selfhosted/comments/1i48qma/silverbullet_sweet_little_app_for_markdown_notes](https://www.reddit.com/r/selfhosted/comments/1i48qma/silverbullet_sweet_little_app_for_markdown_notes)
 - RSS feed: $source
 - date published: 2025-01-18T14:32:08+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://silverbullet.md/">https://silverbullet.md/</a></p> <p>I&#39;ve tried a few note-taking apps over the years, but always fall back to plain text files (previously .txt files, but nowadays .md Markdown files). I like that I can grep them from the command line, view and edit them from a basic ssh connection, use Git for version control, etc.</p> <p>I recently came across SilverBullet. I love that it&#39;s based on .md files. I can continue to write/edit/use plain markdown files as usual, but on top of that get a sweet little web interface. If SilverBullet goes away, the .md files are just still there.</p> <p>I got it up and running in under a minute with a docker one-liner:</p> <p><code>sudo docker run -it -p 3000:3000 -v /path/to/my/notes:/space zefhemel/silverbullet</code></p> <p>Docker install Instructions: <a href="https://silverbullet.md/Install/Docker">https://silverbullet.md/Install/Docker</a></p> <p>There are also a lot of bells 

## Centrifugo v6 released – major update of scalable WebSocket server, self-hosted alternative to Ably and Pusher
 - [https://www.reddit.com/r/selfhosted/comments/1i47x97/centrifugo_v6_released_major_update_of_scalable](https://www.reddit.com/r/selfhosted/comments/1i47x97/centrifugo_v6_released_major_update_of_scalable)
 - RSS feed: $source
 - date published: 2025-01-18T13:50:10+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i47x97/centrifugo_v6_released_major_update_of_scalable/"> <img src="https://external-preview.redd.it/lhCuP0SikgLscRtBnnbzqkXLsEYZ5JnbEmrqJIw4oeQ.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=61d73a2a81a45ec4d7089245be184e5528f17774" alt="Centrifugo v6 released – major update of scalable WebSocket server, self-hosted alternative to Ably and Pusher" title="Centrifugo v6 released – major update of scalable WebSocket server, self-hosted alternative to Ably and Pusher" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FZambia"> /u/FZambia </a> <br/> <span><a href="https://centrifugal.dev/blog/2025/01/16/centrifugo-v6-released">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i47x97/centrifugo_v6_released_major_update_of_scalable/">[comments]</a></span> </td></tr></table>

## Need advice on first homelab OS to play
 - [https://www.reddit.com/r/selfhosted/comments/1i46nc3/need_advice_on_first_homelab_os_to_play](https://www.reddit.com/r/selfhosted/comments/1i46nc3/need_advice_on_first_homelab_os_to_play)
 - RSS feed: $source
 - date published: 2025-01-18T12:35:49+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I got a mini pc to play as a homelab. It&#39;s a N100 with:</p> <ul> <li>1x 8gb ddr4</li> <li>1x nvme 128gb</li> <li>1x 480gb ssd sata3</li> <li>1x sdcard reader slot</li> <li>4x 2.5gb lan ports</li> </ul> <p>Currently, I want to build a mini NAS server to store pictures and work as a google drive to transfer data between friends via internet, a photo backup service like google photos, and as a dedicated adblocker. Some suggest OMV so I was learning to use it and found out that the drive I installed the system on can&#39;t be mounted/shared (or may be I can but still not found out yet).</p> <p>Now some people suggest me trying Proxmox and then using it to install OMV, and may be PfSense if I want to learn about dedicated firewall.</p> <p>Now the question is, is the device strong enough to run proxmox with 2 VMs like this? Or a different OS might be better for me </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/us

## AI powered local file share indexing and search
 - [https://www.reddit.com/r/selfhosted/comments/1i45zsu/ai_powered_local_file_share_indexing_and_search](https://www.reddit.com/r/selfhosted/comments/1i45zsu/ai_powered_local_file_share_indexing_and_search)
 - RSS feed: $source
 - date published: 2025-01-18T11:53:22+00:00

<!-- SC_OFF --><div class="md"><p>Gents</p> <p>Looking for an AI powered search and indexing service </p> <p>I&#39;ve got a lot of research documents that I&#39;d like indexed and made available via a very simple Google type interface</p> <p>Any suggestions would be great</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ithakaa"> /u/ithakaa </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i45zsu/ai_powered_local_file_share_indexing_and_search/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i45zsu/ai_powered_local_file_share_indexing_and_search/">[comments]</a></span>

## Lidarr, what are best/easiest method to get missing albums?
 - [https://www.reddit.com/r/selfhosted/comments/1i45xa9/lidarr_what_are_besteasiest_method_to_get_missing](https://www.reddit.com/r/selfhosted/comments/1i45xa9/lidarr_what_are_besteasiest_method_to_get_missing)
 - RSS feed: $source
 - date published: 2025-01-18T11:48:27+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve a lot of missing albums that are not being picked up, what plugins do you recommend? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RathdrumRip"> /u/RathdrumRip </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i45xa9/lidarr_what_are_besteasiest_method_to_get_missing/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i45xa9/lidarr_what_are_besteasiest_method_to_get_missing/">[comments]</a></span>

## New to self hosting, could use some guidance
 - [https://www.reddit.com/r/selfhosted/comments/1i45mow/new_to_self_hosting_could_use_some_guidance](https://www.reddit.com/r/selfhosted/comments/1i45mow/new_to_self_hosting_could_use_some_guidance)
 - RSS feed: $source
 - date published: 2025-01-18T11:28:04+00:00

<!-- SC_OFF --><div class="md"><p>Hello all. I&#39;m completely new to self hosting, and my networking knowledge is very limited, but I wanted to learn more about it for a small project of mine.</p> <p>For this project I would need to contact a service I wrote via its APIs from n mobile devices.<br/> I still don&#39;t know whether I&#39;ll just keep the app running on my main PC or if I&#39;ll just get a raspberry and run a linux machine on it to keep it running (to be honest I&#39;m not very familiar with Linux).</p> <p>As you can guess my problem is exposing its APIs so that I can reach them while not on the same network.</p> <p>With a bit of research I&#39;ve found suggested to use either cloudflare or tailscale to obtain a domain (for free?) to use for this.</p> <p>My questions are:</p> <p>- Can/should I actually get a domain for free from these sources?</p> <p>- Once I get a domain, what other steps and how much effort are required for this? Is it plug&amp;play, something that I

## Possible back-up ?
 - [https://www.reddit.com/r/selfhosted/comments/1i450q9/possible_backup](https://www.reddit.com/r/selfhosted/comments/1i450q9/possible_backup)
 - RSS feed: $source
 - date published: 2025-01-18T10:45:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello peeps ! I’m looking for something to help me with my and my gf’s iPhone back-ups. Rn I’m still using iCloud but I’m looking to drop them since photos/videos are already backed-up using Immich, so I’m thinking of looking for a solution for phone data as well. Any advice ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrPanda011"> /u/MrPanda011 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i450q9/possible_backup/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i450q9/possible_backup/">[comments]</a></span>

## Actual-ai: Classify your actual-budget transaction using Ollama. Now supports prompt customisation
 - [https://www.reddit.com/r/selfhosted/comments/1i44vx2/actualai_classify_your_actualbudget_transaction](https://www.reddit.com/r/selfhosted/comments/1i44vx2/actualai_classify_your_actualbudget_transaction)
 - RSS feed: $source
 - date published: 2025-01-18T10:35:59+00:00

<!-- SC_OFF --><div class="md"><p>For those who don&#39;t know, you can categorise your <a href="https://actualbudget.org/">Actual Budget</a> transactions using LLM.</p> <p><a href="https://github.com/sakowicz/actual-ai">https://github.com/sakowicz/actual-ai</a></p> <p>Today, I&#39;ve added support for prompt customisation using the <a href="https://handlebarsjs.com/">Handlebars</a> template.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/giebeka"> /u/giebeka </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i44vx2/actualai_classify_your_actualbudget_transaction/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i44vx2/actualai_classify_your_actualbudget_transaction/">[comments]</a></span>

## Things working slowly after around 120 days of uptime (BPi + esp8266)
 - [https://www.reddit.com/r/selfhosted/comments/1i44uo9/things_working_slowly_after_around_120_days_of](https://www.reddit.com/r/selfhosted/comments/1i44uo9/things_working_slowly_after_around_120_days_of)
 - RSS feed: $source
 - date published: 2025-01-18T10:33:32+00:00

<!-- SC_OFF --><div class="md"><p>Hi,</p> <p>Recently my server (Banana Pi M2 Ultra) was getting really slow internet download of 1.3Mbps (350 from ISP, other PCs okay). <code>iperf3</code> also maxed out at ~90Mbps receive. <code>ethtool</code> showed 1G/Full. Curiously, uplink was around 600Mbps. Restart fixed the issue (350 internet, 900 local).</p> <p>Coincidentally, my ESP8266 applications seem to also grind to halt. First 10 pings dropped. Http getting entirely lost. Sometimes it wakes back up. No deauth in logs or similar. I&#39;m wondering if this is somehow connected to the above, counter overflowing or something.</p> <p>Tl;dr servers going haywire after ~120 days of uptime. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrJake2137"> /u/MrJake2137 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i44uo9/things_working_slowly_after_around_120_days_of/">[link]</a></span> &#32; <span><a href="https://www.r

## Dawarich: cannot login with SSL offloading enabled
 - [https://www.reddit.com/r/selfhosted/comments/1i44rfg/dawarich_cannot_login_with_ssl_offloading_enabled](https://www.reddit.com/r/selfhosted/comments/1i44rfg/dawarich_cannot_login_with_ssl_offloading_enabled)
 - RSS feed: $source
 - date published: 2025-01-18T10:26:43+00:00

<!-- SC_OFF --><div class="md"><p>I am not an expert in Networking and might not put in the right search terms, but I couldn&#39;t google myself out of this. Any help in how to debug my problems would be appreciated. I set up a dawarich server on my server at home. Since I am running multiple services on the same machine and I would like to use nginx as a reverse proxy. This is working well when running over http but before I would like to open this for outside connections I would like to set up https, and this is where i fails.</p> <p>I can still get a connection but as soon as I try to login I will return to the login page with no error message independent on whether I put in valid credentials or not. In the console I always find the message</p> <p><code>WebSocket connection to &#39;wss://&lt;.local mdns domain name&gt;/cable&#39; failed</code></p> <p>Which leads me to believe that the problem is related to Websocket. I looked into that, and I set up my nginx config as follows:</p>

## arr software with multi language?
 - [https://www.reddit.com/r/selfhosted/comments/1i44kc2/arr_software_with_multi_language](https://www.reddit.com/r/selfhosted/comments/1i44kc2/arr_software_with_multi_language)
 - RSS feed: $source
 - date published: 2025-01-18T10:12:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,<br/> At home, we have an Overseerr, Plex, Radarr, Sonarr, and Prowlarr setup for managing and watching media. The issue is that we’re used to watching content in English, which works perfectly for us, but now we’re trying to share our environment with our non-English-speaking/hearing family members.</p> <p>Sharing Plex itself isn’t a problem, but we’re trying to figure out the best way to handle this situation. It seems that in Radarr and Sonarr, you can create custom rules for MULTI-language releases, but I’m not sure how to set it up to download both English and another language simultaneously or if it’s possible to have control over that.</p> <p>Another idea is to run multiple instances of Radarr and Sonarr, ideally still using the same frontends (Overseerr and Plex) and organizing the content into separate libraries. However, that seems like it could get a bit tedious to manage.</p> <p>Does anyone have an elegant solution to this 

## Failover server
 - [https://www.reddit.com/r/selfhosted/comments/1i44jf1/failover_server](https://www.reddit.com/r/selfhosted/comments/1i44jf1/failover_server)
 - RSS feed: $source
 - date published: 2025-01-18T10:10:10+00:00

<!-- SC_OFF --><div class="md"><p>Hi!</p> <p>I&#39;ve been researching something for quite some time now, ,but i can&#39;t find a good answer. I want to setup a failover cluster, but on different locations, because of wonky internet connections. My parents are divorced, so i got my locations, but there seems to be no software witch can setup a cluster on different networks. I&#39;ve read you can setup a proxmox cluster via VPN, but that you need a sub 2ms latency witch i don&#39;t have. Wich software would you use, or how do i fix this? it would be a new server so OS doesn&#39;t realy matter.</p> <p>thx in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/lucasrrc"> /u/lucasrrc </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i44jf1/failover_server/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i44jf1/failover_server/">[comments]</a></span>

## OMV disks
 - [https://www.reddit.com/r/selfhosted/comments/1i43uzz/omv_disks](https://www.reddit.com/r/selfhosted/comments/1i43uzz/omv_disks)
 - RSS feed: $source
 - date published: 2025-01-18T09:19:37+00:00

<!-- SC_OFF --><div class="md"><p>Using OMV for the first time setup all the arrs on primary drive nvme. Secondary drive 1TB for all the tv/movies. Now I want to add 2 more drives 2TB + 2TB. </p> <p>Is there any way I can extend my 1TB and combine 2 new drives without losing data? How do I do that? Any suggestions.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ComplexTreat7390"> /u/ComplexTreat7390 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i43uzz/omv_disks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i43uzz/omv_disks/">[comments]</a></span>

## Going to expose my homelab. Comments?
 - [https://www.reddit.com/r/selfhosted/comments/1i43pmy/going_to_expose_my_homelab_comments](https://www.reddit.com/r/selfhosted/comments/1i43pmy/going_to_expose_my_homelab_comments)
 - RSS feed: $source
 - date published: 2025-01-18T09:08:40+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone,</p> <p>after using my homelab for about half a year with a VPN I decided to expose some services directly. I have read a good amount of stuff on the topic and want to double check I have not missed any major points.</p> <p>I know there will be a lots of comments saying I should not do this at all if I have to ask or just use a VPN or cloudflare tunnel but I do not want to do that. I am just looking for some friendly advice on best practice.</p> <p>So the plan is: Opening and redirecting port 443 in my router to my VM. The VM is running on proxmox in a isolated VLAN. It is a very minimal install which apart from docker, git and nfs is running only the bare minimum. Firewall is handled by proxmox, it is set to allow only port 443 and my SSH from internal IPs from my admin VLAN.</p> <p>The VM has docker running in rootless mode with a total of 4 services I want to expose + Traefik and Authentik. Traefik drops all traffic not pointing to 

## Archival image host
 - [https://www.reddit.com/r/selfhosted/comments/1i436wv/archival_image_host](https://www.reddit.com/r/selfhosted/comments/1i436wv/archival_image_host)
 - RSS feed: $source
 - date published: 2025-01-18T08:29:37+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I’m looking for suggestions for hosting archive images that can then be embedded in a public Wordpress website. Currently I’m using Flickr Pro but aside from the cost of this their API is very slow resulting in noticeable page load slowdown on posts where images are embedded, and it’s even slower for full albums. Otherwise Flickr has been pretty spot-on, feature wise. </p> <p>These are very old photos taken from a variety of sources, some digital, some analog that I am scanning in. Being able to edit the metadata is important, particularly dates and locations but also descriptions. As many of these photos are scanned the ability to do some light editing, mostly cropping and rotating, would be useful. </p> <p>Requirements: - As fast as my current Wordpress image library (which I have to use for featured images etc) - Decent security as this will be public - saml/oauth/oidc MFA is a must - Metadata management - API or some other means to embed 

## Zero 2 w as nas
 - [https://www.reddit.com/r/selfhosted/comments/1i41w5m/zero_2_w_as_nas](https://www.reddit.com/r/selfhosted/comments/1i41w5m/zero_2_w_as_nas)
 - RSS feed: $source
 - date published: 2025-01-18T06:54:28+00:00

<!-- SC_OFF --><div class="md"><p>How can I use it as nas to share to share pics and videos across the entire family ? I have a external sdd with it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spacetimeslayer"> /u/spacetimeslayer </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i41w5m/zero_2_w_as_nas/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i41w5m/zero_2_w_as_nas/">[comments]</a></span>

## is localtonet down?
 - [https://www.reddit.com/r/selfhosted/comments/1i41vxw/is_localtonet_down](https://www.reddit.com/r/selfhosted/comments/1i41vxw/is_localtonet_down)
 - RSS feed: $source
 - date published: 2025-01-18T06:54:01+00:00

<!-- SC_OFF --><div class="md"><p>i can&#39;t connect to the tcp server? is localtonet down? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Short_Ad_7549"> /u/Short_Ad_7549 </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i41vxw/is_localtonet_down/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i41vxw/is_localtonet_down/">[comments]</a></span>

## Enhance Your Contabo VPS Backup Strategy with Contabo Snapshot Manager
 - [https://www.reddit.com/r/selfhosted/comments/1i40t4l/enhance_your_contabo_vps_backup_strategy_with](https://www.reddit.com/r/selfhosted/comments/1i40t4l/enhance_your_contabo_vps_backup_strategy_with)
 - RSS feed: $source
 - date published: 2025-01-18T05:40:59+00:00

<!-- SC_OFF --><div class="md"><p>If you’re hosting important applications or websites on Contabo, you know how crucial reliable backups can be. Manual snapshot creation can be time-consuming, and if you forget to do it before a major change, you risk losing valuable data. That’s why I developed <a href="https://github.com/sirantho20/contabo_snapshot_manager"><strong>Contabo Snapshot Manager</strong></a>—a powerful open-source tool designed to bring ease and automation to your Contabo backup routine. By letting you schedule snapshots at regular intervals and automatically remove outdated ones, it ensures you always have recent snapshots on hand without lifting a finger.</p> <h1>Automating Snapshot Creation</h1> <p>At its heart, <a href="https://github.com/sirantho20/contabo_snapshot_manager"><strong>Contabo Snapshot Manager</strong></a> frees you from repetitive manual steps. Instead of logging into the Contabo portal every so often, you can let the tool handle snapshot creation at i

## Question about directory structure for books with both a dramatized and traditional books. (AudiobookShelf + LazyLibrarian)
 - [https://www.reddit.com/r/selfhosted/comments/1i3z7bt/question_about_directory_structure_for_books_with](https://www.reddit.com/r/selfhosted/comments/1i3z7bt/question_about_directory_structure_for_books_with)
 - RSS feed: $source
 - date published: 2025-01-18T04:02:42+00:00

<!-- SC_OFF --><div class="md"><p>Hey Selfhosters, I recently picked up LazyLibrarian to replace Readarr. I&#39;m working my way through the settings and didn&#39;t see a file/directory rename option for the narrator. </p> <p>I was hoping to differentiate between traditional audiobooks and dramatized audiobooks (BBC Radio, GraphicAudio, etc). </p> <p>How are ya&#39;ll saving multiple versions of the same audiobook (trad/drama/abridged)?</p> <p>My current setup is:<br/> Traditional: Author/Series/01 - Title/Title.m4b<br/> Dramatized: Author/Series (GraphicAudio)/01 - Title/Title.m4b<br/> This was done manually as I acquired new media.</p> <p>I&#39;ve created a backup, but I&#39;m still a little nervous to run a scan that renames the files. </p> <p>Thanks in advance. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tagmeh"> /u/Tagmeh </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3z7bt/question_about_directory_structure_f

## Dedicated Media server instead of Synology NAS
 - [https://www.reddit.com/r/selfhosted/comments/1i3ylt9/dedicated_media_server_instead_of_synology_nas](https://www.reddit.com/r/selfhosted/comments/1i3ylt9/dedicated_media_server_instead_of_synology_nas)
 - RSS feed: $source
 - date published: 2025-01-18T03:29:02+00:00

<!-- SC_OFF --><div class="md"><p>I have been happily using Emby (as a native installed Synology package) on my Synology DS918+ for quite a while. I also run Portainerwith the following docker installs: Sonarr, Radarr, gluetun, sabnzb, prowlarr, Tdarr, but use Fileflows more and a few others. </p> <p>Because of some occasional stuttering and concerns about processing power I decided to explore a separate media server box. Initially considered an N100. However, I have an old laptop sitting around with these specs:</p> <p>Processor Intel(R) Core(TM) i7-8750H CPU @ 2.20GHz 2.20 GHz</p> <p>Installed RAM 16.0 GB (15.8 GB usable</p> <p>This is a MSI StealthThin laptop with a TB SSD installed (Samsung SSD EVO)</p> <p>I have experimented with a VMWare Debian install and used CasaOS with Emby installed through CasaOS and Portainer with FileFlows. Works pretty well. </p> <p>So my questions for those of you with experience: 1) do you think I’m on the right track with getting Emby (or Plex or Je

## I might've fixed the indexer issue on sonarr and radarr
 - [https://www.reddit.com/r/selfhosted/comments/1i3yiip/i_mightve_fixed_the_indexer_issue_on_sonarr_and](https://www.reddit.com/r/selfhosted/comments/1i3yiip/i_mightve_fixed_the_indexer_issue_on_sonarr_and)
 - RSS feed: $source
 - date published: 2025-01-18T03:23:55+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, Since I set sonarr and radarr up to manage my media, It has been a breeze, but there have been a few problems, one of them being that my indexers keep showing as failed, after looking into this apparently if an indexer doesn&#39;t give results, it is assumed to be &quot;not working&quot; and marked as disabled, for which we see an error that indexer is disabled (sometimes for over 6 hours), and since sonarr and radarr doesn&#39;t make more frequent health checks on those, its possible all indexers are not being used and we may not get results that are as good, i figured a solution would be to make an api callout every few minutes to check those indexers health, which worked pretty great, but i still saw sometimes that even after that, sometimes indexers might not be available, my requirement was, that even if the indexer is not working, force sonarr and radarr to use them, to which I thought of checking the radarr.db/sonarr.db database 

## Question about moving game server saves from windows to linux
 - [https://www.reddit.com/r/selfhosted/comments/1i3ygab/question_about_moving_game_server_saves_from](https://www.reddit.com/r/selfhosted/comments/1i3ygab/question_about_moving_game_server_saves_from)
 - RSS feed: $source
 - date published: 2025-01-18T03:20:19+00:00

<!-- SC_OFF --><div class="md"><p>Ok so im familiar with and used several different distros of linux over the years, but ive mainly used windows since windows 10. I have an old pc I use for a home server, thats running windows 10, which of course is about to lose support, and also I have some spare parts from when i upgraded my main gaming pc (windows 11). So....put 2 and 2 together and yeah Im about to finally get around to upgrading my old &quot;server&quot; pc (old optiplex with an i7 6700) to my old ryzen 3600 cpu/mobo, and while im at it, im considering just installing ubuntu on it as well.</p> <p>Im currently using it to run my media server along with hosting several dedicated game servers so I figured linux would be a much better OS then worrying about getting another windows key and running windows 11. Of course, with that being said, the boot drive that also has all my server files and saves on it will be wiped. If these are backed up on the 2nd hard drive in this pc, thats 

## New Server, new to self hosting outside of a Plex machine on Windows I used a few years ago. Having some trouble grasping the best way to get remote access to hosted apps, LubeLogger specifically.
 - [https://www.reddit.com/r/selfhosted/comments/1i3ydj6/new_server_new_to_self_hosting_outside_of_a_plex](https://www.reddit.com/r/selfhosted/comments/1i3ydj6/new_server_new_to_self_hosting_outside_of_a_plex)
 - RSS feed: $source
 - date published: 2025-01-18T03:16:06+00:00

<!-- SC_OFF --><div class="md"><p>I’m building a home server with Ubuntu to run <a href="/r/lubelogger">/r/lubelogger</a> and eventually Plex/Jellyfin with *arr apps and probably other things but those are the ones that I&#39;m primarily looking to get going.</p> <pre><code>Recycled PC Parts CPU: AMD Ryzen 5600x RAM: 16GB GPU: Intel Arc A380 Storage: 1x 512GB NVMe SSD for Ubuntu 2x 10TB HDDs for media storage and backups eventually </code></pre> <p>I&#39;m sure there are a variety of reasons to use a different OS but I don&#39;t think I&#39;m doing anything wild that will cause major issues so unless there&#39;s a reason to switch to something else like &quot;all that stuff you want works out of the box&quot; I&#39;ll probably just stick to Ubuntu.</p> <p>Anyway, the plan is to install LubeLogger via docker which I can handle I think. Where I&#39;m struggling is figuring out the best/easiest method to access the LubeLogger web interface outside of my LAN as I plan to be using it at m

## How do I reinstall Calibre-Web without losing my settings?
 - [https://www.reddit.com/r/selfhosted/comments/1i3x2im/how_do_i_reinstall_calibreweb_without_losing_my](https://www.reddit.com/r/selfhosted/comments/1i3x2im/how_do_i_reinstall_calibreweb_without_losing_my)
 - RSS feed: $source
 - date published: 2025-01-18T02:04:59+00:00

<!-- SC_OFF --><div class="md"><p>I was cleaning up my cache and think part of calibre-web was sitting there. Only thing that would explain a whole page of python errors. How do i reinstall the app without losing my appdata and settings?</p> <p>edit: So i deleted it and reinstalled it and now Im getting the error below</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/greypic"> /u/greypic </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3x2im/how_do_i_reinstall_calibreweb_without_losing_my/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3x2im/how_do_i_reinstall_calibreweb_without_losing_my/">[comments]</a></span>

## Network share randomly drops
 - [https://www.reddit.com/r/selfhosted/comments/1i3wxib/network_share_randomly_drops](https://www.reddit.com/r/selfhosted/comments/1i3wxib/network_share_randomly_drops)
 - RSS feed: $source
 - date published: 2025-01-18T01:57:50+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Hoping for some help, really frustrating issue. I&#39;ll describe my setup (limited to the two devices having issues) and then the specific problem I am running to.</p> <p><strong>Setup</strong></p> <p>I&#39;m running OMV on an intel miniPC. Have two hard drives connected via USB, and a SMB\CIFS share setup for each of them. I can always access them via my PC without any issues.</p> <p>I have a separate miniPC running some other services (Debian lite OS I believe), I have mounted the shares using <code>/etc/fstab</code> with the following configuration (changed IPs\folder names)</p> <p><code>proc /proc proc defaults 0 0</code></p> <p><code>PARTUUID=2e125637-01 /boot/firmware vfat defaults 0 2</code></p> <p><code>PARTUUID=2e125637-02 / ext4 defaults,noatime 0 1</code></p> <p><code>//192.154.1.7/dir1 /networkmnts/dir1 cifs guest 0 0</code></p> <p><code>//192.154.1.7/dir2 /networkmnts/dir2 cifs guest 0 0</code></p> <p>This works, in the s

## Rotating incremental backup with rsync
 - [https://www.reddit.com/r/selfhosted/comments/1i3wo9q/rotating_incremental_backup_with_rsync](https://www.reddit.com/r/selfhosted/comments/1i3wo9q/rotating_incremental_backup_with_rsync)
 - RSS feed: $source
 - date published: 2025-01-18T01:44:30+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve seen a lot of misconceptions recently on this sub about what rsync can do as a backup solution. For instance, I have read things like it is unpractical to restore files from a given point in time because Rsync will also duplicate unchanged files when a specific folder is backed up, and that would, indeed, take a large amount of space.</p> <p>However, Rsync has the powerful <code>--link-dest=DIR</code> option to hardlink files in DIR when unchanged. In practice, it means that the file already existing are not copied, just hard linked to the initial file, although you will see it as a separate file in the hierarchy. It allows creating rotating incremental backups. If you search for those keywords on the web you will find various implementions.</p> <p>For example, I have coded <a href="https://github.com/cgrima/rsync_backup/tree/master">rsync_backup</a> , which is a very simple bash wrapper around an rsync command to do &quot;<em>incremental ba

## Any forward proxy web-app like croxyproxy?
 - [https://www.reddit.com/r/selfhosted/comments/1i3wb0s/any_forward_proxy_webapp_like_croxyproxy](https://www.reddit.com/r/selfhosted/comments/1i3wb0s/any_forward_proxy_webapp_like_croxyproxy)
 - RSS feed: $source
 - date published: 2025-01-18T01:25:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/FixOxiF"> /u/FixOxiF </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3wb0s/any_forward_proxy_webapp_like_croxyproxy/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3wb0s/any_forward_proxy_webapp_like_croxyproxy/">[comments]</a></span>

## How To Configure Dawarich to add the line so it follows the road?
 - [https://www.reddit.com/r/selfhosted/comments/1i3w4q6/how_to_configure_dawarich_to_add_the_line_so_it](https://www.reddit.com/r/selfhosted/comments/1i3w4q6/how_to_configure_dawarich_to_add_the_line_so_it)
 - RSS feed: $source
 - date published: 2025-01-18T01:16:59+00:00

<!-- SC_OFF --><div class="md"><p>HI all, I have Dawarich setup and was initially using the Home Assistant iOS app to track my movement. This was being plotted in Dawarich, but instead of the lines following the roads like in the website images, it just draws a straight line from journey start to journey end, which looks very &#39;meh&#39;. I then installed Overland thinking it would be more granular, but importing points from that doesnt seem to make any difference.</p> <p>Is there a setting in Dawarich or the tracking apps to get the granularity I am after? In Overland I have configured, under settings and trip settings:</p> <p>Desired accuracy: 10m</p> <p>Activity Type: car</p> <p>Logging mode: all data</p> <p>Locations per batch 1000</p> <p>Min time between points: 1s</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PsiCzar"> /u/PsiCzar </a> <br/> <span><a href="https://www.reddit.com/r/selfhosted/comments/1i3w4q6/how_to_configure_dawarich_to

## Nextcloud on Truenas Scale
 - [https://www.reddit.com/r/selfhosted/comments/1i3urgv/nextcloud_on_truenas_scale](https://www.reddit.com/r/selfhosted/comments/1i3urgv/nextcloud_on_truenas_scale)
 - RSS feed: $source
 - date published: 2025-01-18T00:09:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/selfhosted/comments/1i3urgv/nextcloud_on_truenas_scale/"> <img src="https://b.thumbs.redditmedia.com/0oehT8q_ZDO9ANs7RpVda2x-UGZlC3Hzz54MwQkV2us.jpg" alt="Nextcloud on Truenas Scale" title="Nextcloud on Truenas Scale" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/o9geog7h9nde1.png?width=1875&amp;format=png&amp;auto=webp&amp;s=82fef2ad0cd7df9cadc9eca912a3a720375293ac">https://preview.redd.it/o9geog7h9nde1.png?width=1875&amp;format=png&amp;auto=webp&amp;s=82fef2ad0cd7df9cadc9eca912a3a720375293ac</a></p> <p>Anyone figured out to get this working, since the app is running inside docker it has only a port with the host truenas ip attached to it. i tried adding the ip with port to trusted domains, and adding the domain without the port which redirects the nextcloud ui back to truenas login. Thanks guys, this is really giving me a headache right now.</p> <p><a href="https://preview.redd.it/isaz2avsdnde

