# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## One large compose file?
 - [https://www.reddit.com/r/docker/comments/1i32i3z/one_large_compose_file](https://www.reddit.com/r/docker/comments/1i32i3z/one_large_compose_file)
 - RSS feed: $source
 - date published: 2025-01-16T23:26:40+00:00

<!-- SC_OFF --><div class="md"><p>very new still to docker, compose etc. but been looking around for quite a bit and trying things out, but unable to find a sollution/answer.</p> <p>I&#39;m trying to make a single compose file for a handful of images/containers I want to run and play around with, like nginx and searxng for now. but trying to put it all in a single compose file.</p> <p>So trying to have it automatically make the folders on my host etc. but doesn&#39;t seem to work, and can&#39;t figure out how to do it.</p> <p>getting &quot;errors&quot; like:</p> <pre><code>yaml: unmarshal errors: line 121: mapping key &quot;volumes&quot; already defined at line 89 </code></pre> <p>as an example^</p> <p>some guidance or pointers would be great!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DemonicXz"> /u/DemonicXz </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i32i3z/one_large_compose_file/">[link]</a></span> &#32; <span><a

## Strange behavior with docker compose restart
 - [https://www.reddit.com/r/docker/comments/1i2zhgw/strange_behavior_with_docker_compose_restart](https://www.reddit.com/r/docker/comments/1i2zhgw/strange_behavior_with_docker_compose_restart)
 - RSS feed: $source
 - date published: 2025-01-16T21:11:25+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I ran into a strange behavior with docker compose that I can&#39;t find an answer online and maybe some of you can help me figuring it out!</p> <p>I&#39;ve setup a compose file with some services in it. Two of them are: - Redis, used as a cache for data I fetch from a remote server - A service I&#39;ve write in Go that fetch and cache the data</p> <p>The service in Go starts some routine based on the data fetched from the remote server periodically and store some information about that in redis so in the next iteration no routine is started for the same data. When a routine started from this process ends, it removes the data from the cache. At startup, this process asks Redis if some values are stored, and if so, starts the routines. This is done because if it crashes, this way it can easily return in the correct state.</p> <p>Back to docker: if I restart the container with &quot;docker compose restart my-service&quot;, no logs of the code tha

## Updated DDEV and now I'm getting mac issues with ._
 - [https://www.reddit.com/r/docker/comments/1i2x11w/updated_ddev_and_now_im_getting_mac_issues_with](https://www.reddit.com/r/docker/comments/1i2x11w/updated_ddev_and_now_im_getting_mac_issues_with)
 - RSS feed: $source
 - date published: 2025-01-16T19:26:27+00:00

<!-- SC_OFF --><div class="md"><p>Today I updated ddev on my mac. Docker desktop was previously running fine. But now I&#39;m getting an error thatcontains ._ names </p> <p>Starting marketplace-commerce... </p> <p>unable to clean up directory .webimageBuild, you may want to delete it manually: stat /Volumes/Azul/IT/marketplace-commerce/.ddev/.webimageBuild/._Dockerfile.example: no such file or directory </p> <p>unable to clean up directory .dbimageBuild, you may want to delete it manually: stat /Volumes/Azul/IT/marketplace-commerce/.ddev/.dbimageBuild/._Dockerfile.example: no such file or directory.</p> <p>I&#39;ve tried changing permissions I made sure the terminal I&#39;m using has full disk write permissions. I&#39;ve been using ddev just fine until I made the update today. </p> <p>Someone, please help me get this resolved. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/smiths16"> /u/smiths16 </a> <br/> <span><a href="https://www.reddit.com

## Docker is confusing me. I'm trying to setup multiple sites on my remote server
 - [https://www.reddit.com/r/docker/comments/1i2w27l/docker_is_confusing_me_im_trying_to_setup](https://www.reddit.com/r/docker/comments/1i2w27l/docker_is_confusing_me_im_trying_to_setup)
 - RSS feed: $source
 - date published: 2025-01-16T18:45:44+00:00

<!-- SC_OFF --><div class="md"><p>Hi all</p> <p>I&#39;m really trying not to give up on Docker as I hear its the must tool to use but I think it&#39;s laughing at me.</p> <p>I am trying to create multiple sites locally and then push to my remote server once done. Docker seems like the best tool to help with this but I am finding it hard at the moment. I plan on using Nuxt as the frontend for the sites and Directus as the backend which will be on a sub-domain.</p> <p>I&#39;m unable to get Nuxt working at the moment without some kind of unhealthy error so I have skipped this for now. I have a container for mysql and a container for nginx which I intend on using with multiple sites. I then plan to have a container for each site which will hold the directory for /frontend (nuxt) and backend (directus).</p> <p>I thought I had this all sorted after days and days or playing about but as soon as I try to add a second website to my domain, it&#39;s broken. I thought I just needed to duplicate

## Trying to isolate /dev from the host instead of using a VM like a sane person would.
 - [https://www.reddit.com/r/docker/comments/1i2ub06/trying_to_isolate_dev_from_the_host_instead_of](https://www.reddit.com/r/docker/comments/1i2ub06/trying_to_isolate_dev_from_the_host_instead_of)
 - RSS feed: $source
 - date published: 2025-01-16T17:31:49+00:00

<!-- SC_OFF --><div class="md"><p>I know what I am trying to do isn&#39;t what Docker is for and that a VM is the way to go but I&#39;ve been playing around with Docker, experimenting, and pushing the limits so hopefully you&#39;ll humor me.</p> <p>I am trying to containerize a live boot distro that uses syslinux to boot from USB and then runs `/sbin/init`. I&#39;ve gotten it to boot the file system and am trying to get a virtual block device working so it can continue booting the live/virtual USB. I can partially get that working making a loop device in the host and running as privileged. But then I run into other issues with other devices in `/dev` when the init script runs and allowing the guest access, if that&#39;s even possible, will probably screw up the host (yes, I know, use a VM). I am currently exploring the possibility of making a tmpfs of /dev for this or something similar to trick the guest into using an isolated virtual `/dev`. Does anyone have any pointers or other cr

## IPvlan to put a container in another subnet?
 - [https://www.reddit.com/r/docker/comments/1i2qiat/ipvlan_to_put_a_container_in_another_subnet](https://www.reddit.com/r/docker/comments/1i2qiat/ipvlan_to_put_a_container_in_another_subnet)
 - RSS feed: $source
 - date published: 2025-01-16T14:47:34+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://imgur.com/a/b1zaRk9">https://imgur.com/a/b1zaRk9</a></p> <p>As the title says, I&#39;m trying to put a Home Assistant container into my smarthome subnet while also having the host box on my private subnet to act as a NAS, but I&#39;m entirely new to Docker and networking in general so I don&#39;t know if this is the right way to achieve network isolation or if these are the right tools to achieve this.</p> <p>I&#39;ve been following along with these guides from Crosstalk <a href="https://www.youtube.com/watch?v=UBtPme0RQ2U">https://www.youtube.com/watch?v=UBtPme0RQ2U</a> and NetworkChuck <a href="https://www.youtube.com/watch?v=bKFMS5C4CG0">https://www.youtube.com/watch?v=bKFMS5C4CG0</a></p> <p>The relevant commands:</p> <p><code>sudo docker network create -d ipvlan --subnet 192.168.107.0/24 --gateway 192.168.107.1 -o parent=eth0 107_ipvlan</code></p> <p><code>sudo docker run -itd --rm --network 107_ipvlan --ip 192.168.107.251 --name

## Minecraft server GUI??
 - [https://www.reddit.com/r/docker/comments/1i2laka/minecraft_server_gui](https://www.reddit.com/r/docker/comments/1i2laka/minecraft_server_gui)
 - RSS feed: $source
 - date published: 2025-01-16T09:34:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>This is just a question to see if such a thing exists.</p> <p>Atm I am running modded Minecraft server in docker containers on debian12, I also use portainer. I’m wondering if such a thing exists that’s like portainer but instead it will be like, I go to an ip on a brower and it gives me a gui and it will show me all my containers and asks me what containers are Minecraft ones, then after I select them it will give me like a dashboard of all my Minecraft servers and it will show how much ram/cpu it’s using and show me like health and also the users that are on that Minecraft world.</p> <p>Does such a thing exist?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/JKAF3"> /u/JKAF3 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i2laka/minecraft_server_gui/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i2laka/minecraft_server_gui/">[comments]</a><

## Alpine Docker: Unable to modify env YARN version unless on debug mode
 - [https://www.reddit.com/r/docker/comments/1i2kwb7/alpine_docker_unable_to_modify_env_yarn_version](https://www.reddit.com/r/docker/comments/1i2kwb7/alpine_docker_unable_to_modify_env_yarn_version)
 - RSS feed: $source
 - date published: 2025-01-16T09:03:34+00:00

<!-- SC_OFF --><div class="md"><p>I am currently studying typescript and react and simultaneously learning containers. I ran into an issue with some containers that the base image of the container uses ENV YARN_VERSION 1.22.22. However, I am using a higher version. If I try RUN env YARN_VERSION=4.5.3 corepack enable &amp;&amp; corepack prepare <a href="mailto:yarn@4.5.3">yarn@4.5.3</a> --activate on my docker file it doesn&#39;t do anything and I still have to manually change this via debug mode.</p> <p>What I found interesting is that running ENV within the container gives me sh: ENV: not found however &quot;env&quot; in lowercase works.</p> <p>Has anyone had this issue before?</p> <p>I was able to find the root cause of the problem however I am after a long term solution.</p> <p>Dockerfile below:</p> <p><sup>FROM node:20 AS build</sup></p> <p><sup>RUN env YARN\</sup>VERSION=4.5.3 corepack enable &amp;&amp; corepack prepare <a href="mailto:yarn@4.5.3">yarn@4.5.3</a> --activate)</p> 

## docker is amazing.. but is there something deeply missed/missing in the roadmap ?
 - [https://www.reddit.com/r/docker/comments/1i2k7pj/docker_is_amazing_but_is_there_something_deeply](https://www.reddit.com/r/docker/comments/1i2k7pj/docker_is_amazing_but_is_there_something_deeply)
 - RSS feed: $source
 - date published: 2025-01-16T08:10:05+00:00

<!-- SC_OFF --><div class="md"><p>hello.</p> <p>the title says it all.. i m an old guy from the mainframe era. i ve seen the beginning of linux and all kind of hypervisor passed (and faded) and i&#39;m now deploying amazing stuff build on docker/swarm.</p> <p>i m pretty sure some of you are full of wishes of what&#39;s the next killer feature of docker ecosystem should be or some 5 years old bug that&#39;s still not fixed upstream ... can you share ?</p> <p>have a good day !</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nul0op"> /u/Nul0op </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i2k7pj/docker_is_amazing_but_is_there_something_deeply/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i2k7pj/docker_is_amazing_but_is_there_something_deeply/">[comments]</a></span>

## Best Practices for Managing and Securing Container Images
 - [https://www.reddit.com/r/docker/comments/1i2it13/best_practices_for_managing_and_securing](https://www.reddit.com/r/docker/comments/1i2it13/best_practices_for_managing_and_securing)
 - RSS feed: $source
 - date published: 2025-01-16T06:26:55+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m looking to deepen my understanding of container image management and security. Specifically, I’d like to know:</p> <p>What are some effective strategies or tools you use to manage container images at scale?</p> <p>How do you ensure the images you’re using (or creating) are secure and free from vulnerabilities?</p> <p>Are there any best practices for maintaining image integrity throughout the CI/CD pipeline?</p> <p>Additionally, I’m curious about your approach to monitoring container images post-deployment. How do you keep up with vulnerability updates or other potential issues that might arise after an image is already in production?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Anjalikumarsonkar"> /u/Anjalikumarsonkar </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i2it13/best_practices_for_managing_and_securing/">[link]</a></span> &#32; <span><a href="https://www.r

## Docker noob here, can someone help me with this?
 - [https://www.reddit.com/r/docker/comments/1i2ik4s/docker_noob_here_can_someone_help_me_with_this](https://www.reddit.com/r/docker/comments/1i2ik4s/docker_noob_here_can_someone_help_me_with_this)
 - RSS feed: $source
 - date published: 2025-01-16T06:10:14+00:00

<!-- SC_OFF --><div class="md"><p>I am new to docker and was watching a tutorial and trying to do it through this, but I had an issue that wasn&#39;t appearing in the video, at 23:16</p> <p><a href="https://www.youtube.com/watch?v=GFgJkfScVNU">https://www.youtube.com/watch?v=GFgJkfScVNU</a></p> <p>The creator showed himself able to access the files of the container while it wasn&#39;t running, and when I run it, it shows me a message saying &quot;The container is no longer running. Unable to show the container’s files.&quot; Can someone help me understand why that is, and if there is any way to fix it? </p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Wooden_Neat1280"> /u/Wooden_Neat1280 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i2ik4s/docker_noob_here_can_someone_help_me_with_this/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i2ik4s/docker_noob_here_can_some

