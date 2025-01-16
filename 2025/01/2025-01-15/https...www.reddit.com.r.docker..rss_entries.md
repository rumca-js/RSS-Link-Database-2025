# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## MeTube: YTDL_OPTIONS is invalid
 - [https://www.reddit.com/r/docker/comments/1i28il5/metube_ytdl_options_is_invalid](https://www.reddit.com/r/docker/comments/1i28il5/metube_ytdl_options_is_invalid)
 - RSS feed: $source
 - date published: 2025-01-15T21:37:26+00:00

<!-- SC_OFF --><div class="md"><p>Trying to figure out why the alexta69-metube container fails to accept the YTDL_OPTIONS value (YTDL_OPTIONS is invalid). I&#39;ve tried every combination I can think of and it still won&#39;t start with the cookiefile option. What am I doing wrong?</p> <p>&nbsp;</p> <p>Settings picture of synology&#39;s docker knockoff I&#39;m using: <a href="https://imgur.com/a/HcDlo2L">https://imgur.com/a/HcDlo2L</a></p> <p>&nbsp;</p> <p>If I remove the YTDL_OPTIONS the container runs. I&#39;ve placed this in the first box </p> <p>&quot;YTDL_OPTIONS={&quot;cookiefile&quot;</p> <p>&nbsp;And this in the second box:</p> <p>&quot;/cookies/cookies.txt&quot;}</p> <p>&nbsp;</p> <p>I&#39;ve tried lots of variants of the second box searching for the correct syntax or whatever but can&#39;t seem to find it. Can someone point me in the right direction? The cookies file is currently sitting at root/docker/.metube/cookies/cookies.txt <a href="https://registry.hub.docker.com/r/a

## Bitwarden Secrets Manager
 - [https://www.reddit.com/r/docker/comments/1i276b8/bitwarden_secrets_manager](https://www.reddit.com/r/docker/comments/1i276b8/bitwarden_secrets_manager)
 - RSS feed: $source
 - date published: 2025-01-15T20:39:08+00:00

<!-- SC_OFF --><div class="md"><p>After looking into Bitwarden Secrets Manager, and reading some of the documentation regarding altering the Dockerfile to dynamically set environment variables, I am beginning to wonder if this is just a bunch of malarkey and if it&#39;s even possible. </p> <p>Per the documentation, in the <strong>Advanced Tutorial</strong>, you can install the Secrets Manager CLI and then construct RUN statements in your Dockerfile to retrieve the creds and then set your environment variables dynamically. </p> <p>Does anyone have more insight into this? I am no Docker expert by any means, but I don&#39;t see how it&#39;s possible to dynamically set variables in a .env file inside of the build layer. </p> <p>Referenced documentation:<br/> <a href="https://bitwarden.com/help/developer-quick-start/">https://bitwarden.com/help/developer-quick-start/</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/StevieOnRails"> /u/StevieOnRails

## Need help with this issue
 - [https://www.reddit.com/r/docker/comments/1i2613k/need_help_with_this_issue](https://www.reddit.com/r/docker/comments/1i2613k/need_help_with_this_issue)
 - RSS feed: $source
 - date published: 2025-01-15T19:49:20+00:00

<!-- SC_OFF --><div class="md"><p>Hello, im just trying to setup a test enviroment for GLPI but when i try to access it i get recieved with a message that says &quot;Application dependemcies are not up to date. Run php bin/console dependencies install in the glpi tree to fix this&quot; and when i try to run it in the container it says that can&#39;t open the file.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/vaquishaProdigy"> /u/vaquishaProdigy </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i2613k/need_help_with_this_issue/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i2613k/need_help_with_this_issue/">[comments]</a></span>

## Container either available from host or docker network, but not both
 - [https://www.reddit.com/r/docker/comments/1i25nlk/container_either_available_from_host_or_docker](https://www.reddit.com/r/docker/comments/1i25nlk/container_either_available_from_host_or_docker)
 - RSS feed: $source
 - date published: 2025-01-15T19:32:58+00:00

<!-- SC_OFF --><div class="md"><p>Hello everyone :)</p> <p>First off: The explanation of my problem includes a lot of setup specific information. But the core question is related to docker itself. I&#39;m not looking for help regarding my specific setup. Just to clarify :)</p> <p>I&#39;m not new to Docker, at least that&#39;s what I thought five minutes ago, but I&#39;m facing an issue I simply can&#39;t explain.</p> <p>I have a SELKS (Suricata, Elastic, Kibana etc.) Docker Stack up and running, and it works great.</p> <p>I now wanted to integrate ElasticSearch, or OpenSearch (fork of ElasticSearch) in my case, in my Grapfana instance which runs on a separate server.</p> <p>Because the stack doesn&#39;t forward 9200/tcp from OpenSearch to the Host by default, I added said rule. Grafana was abled to connect without a problem - Nice!</p> <p>However, all other services, such as Kibana, lost connection and cant connect to elasticsearch:9200 anymore.</p> <p>Here&#39;s my complete <code>do

## Can any one help me? DockerFine
 - [https://www.reddit.com/r/docker/comments/1i20x46/can_any_one_help_me_dockerfine](https://www.reddit.com/r/docker/comments/1i20x46/can_any_one_help_me_dockerfine)
 - RSS feed: $source
 - date published: 2025-01-15T16:13:29+00:00

<!-- SC_OFF --><div class="md"><p>My plan is to make a docker image called jellyseerr with cloudflare but idk how jellyseerr image is based on alpine linux with nodejs but how to add <code>cloudflared</code> in that and run cloudflare tunnel my command is <code>cloudflared tunnel --no-autoupdate run --token=&lt;token&gt;</code> to run tunnel any one pls help me I am n00b you got it 😁</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aman_mohammed"> /u/aman_mohammed </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i20x46/can_any_one_help_me_dockerfine/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i20x46/can_any_one_help_me_dockerfine/">[comments]</a></span>

## Senior engineers, here's a FREE workshop on release management!
 - [https://www.reddit.com/r/docker/comments/1i1z56y/senior_engineers_heres_a_free_workshop_on_release](https://www.reddit.com/r/docker/comments/1i1z56y/senior_engineers_heres_a_free_workshop_on_release)
 - RSS feed: $source
 - date published: 2025-01-15T14:55:33+00:00

<!-- SC_OFF --><div class="md"><h1>What it is not:</h1> <p>This isn’t another 101 session—You&#39;ll get advanced insights tailored to engineers operating at scale. Whether you’re managing large-scale production systems or refining your team’s delivery processes, this workshop will deliver actionable takeaways you can implement immediately.</p> <h1>What it is:</h1> <p>We’re hosting a free workshop for experienced engineers and engineering leaders managing complex systems and an AMA session focused on scaling release management processes.</p> <p>You will learn directly from leaders who’ve optimized software delivery in some of the most demanding</p> <h1>Meet the Experts:</h1> <p>Ankit Jain: CEO and co-founder of Aviator, a developer productivity startup. Ankit is a former Google engineer with extensive experience leading engineering teams and building efficient release pipelines.</p> <p>Vilas Veeraraghavan: Former Engineering Leader at Netflix, Walmart, Bill . com, and TruckStop. With

## What tools do you recommend for scanning Windows Container Images?
 - [https://www.reddit.com/r/docker/comments/1i1ysjw/what_tools_do_you_recommend_for_scanning_windows](https://www.reddit.com/r/docker/comments/1i1ysjw/what_tools_do_you_recommend_for_scanning_windows)
 - RSS feed: $source
 - date published: 2025-01-15T14:39:19+00:00

<!-- SC_OFF --><div class="md"><p>I just noticed most of the tooling for Image scanning/Image SCA is around linux based containers.<br/> What are some good options for scanning Windows based images?<br/> Is it too much to want vulnerability, misconfiguration and secrets reporting in a tool ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/coyoteugly2"> /u/coyoteugly2 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i1ysjw/what_tools_do_you_recommend_for_scanning_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i1ysjw/what_tools_do_you_recommend_for_scanning_windows/">[comments]</a></span>

## Dockerising an old game server
 - [https://www.reddit.com/r/docker/comments/1i1waz4/dockerising_an_old_game_server](https://www.reddit.com/r/docker/comments/1i1waz4/dockerising_an_old_game_server)
 - RSS feed: $source
 - date published: 2025-01-15T12:28:21+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, unsure if this is the place to post (or if there are better places to) but I&#39;m looking for someone who has experience in dockerising a Windows based server, for an old video game called Microsoft Freelancer. The game is no longer sold/supported but we have an active modding community for over 20 years which is still going.</p> <p>We&#39;d like to fashion a cheaper alternative than a Windows based VM with Cloud providers so would like to go Docker, distro-less if my research is accurate. To get it as small as possible. </p> <p>Here is what we have so far...<br/> [Github - FLServer Docker](<a href="https://github.com/darklab8/blog/tree/master/docs/inspiration%5C_flserver%5C_docker">https://github.com/darklab8/blog/tree/master/docs/inspiration\_flserver\_docker</a>)</p> <p>I believe we did manage to get the game server running but without our server plugin system called FLHook which we believe is just hanging. We suspected it was a matter 

## Docker app on HTTPS with nginx and certbot
 - [https://www.reddit.com/r/docker/comments/1i1v689/docker_app_on_https_with_nginx_and_certbot](https://www.reddit.com/r/docker/comments/1i1v689/docker_app_on_https_with_nginx_and_certbot)
 - RSS feed: $source
 - date published: 2025-01-15T11:13:06+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve scoured the internet for answers to this question and, embarrassingly, still haven&#39;t resolved my issue. Hoping someone here can punt me in the right direction.</p> <p><strong>tl;dr</strong> My Docker app exposed on port 8080 only has HTTP access, despite manual nginx/Certbot set up. HTTPS resolves to the &#39;Welcome to Nginx!&#39; homepage. I think it&#39;s probably a port issue, but I can&#39;t see what I need to do to resolve it.</p> <ul> <li>I have a web app (developed in Rust, if it matters) which is run using Docker on port 8080.</li> <li>I have a Ubuntu VPS, which is currently running the app on <a href="http://my-app.com:8080">http://my-app.com:8080</a> (only an example).</li> <li>To use HTTPS, I went to Let&#39;s Encrypt and got an SSL certificate set up by installing nginx, installing certbot and configuring the certificate. I followed the instructions here: <a href="https://certbot.eff.org/instructions?ws=nginx&amp;os=snap">ht

## Need Help with Creating a Chiseled Python Image for My Project
 - [https://www.reddit.com/r/docker/comments/1i1s7zh/need_help_with_creating_a_chiseled_python_image](https://www.reddit.com/r/docker/comments/1i1s7zh/need_help_with_creating_a_chiseled_python_image)
 - RSS feed: $source
 - date published: 2025-01-15T07:25:09+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I&#39;m working on a project and currently using Alpine image. But found many vulnerabilities with the packages. So I am looking for a chiseled Ubuntu Python image for it, along with installing a few required dependencies. However, I&#39;m not sure about the steps to properly set it up. Can anyone guide me on how to create the chiseled Python image and include the necessary installations? I&#39;d appreciate any tips or resources that can help!</p> <p>Thanks in advance!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Imaginary-Ad-4434"> /u/Imaginary-Ad-4434 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i1s7zh/need_help_with_creating_a_chiseled_python_image/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i1s7zh/need_help_with_creating_a_chiseled_python_image/">[comments]</a></span>

## question about docker networking...
 - [https://www.reddit.com/r/docker/comments/1i1r91g/question_about_docker_networking](https://www.reddit.com/r/docker/comments/1i1r91g/question_about_docker_networking)
 - RSS feed: $source
 - date published: 2025-01-15T06:15:17+00:00

<!-- SC_OFF --><div class="md"><p>My understanding is that containers on different docker networks cannot communicate to each other. In my case, I started with a bunch of *arr containers all on the default-bridge network. I created a custom bridge network, and added ONLY Sonarr to it. </p> <ul> <li>I ran Recycler (on default-bridge) which was still able to access Sonarr and update its quality profiles. </li> <li>I went to Prowlarr (on default-bridge) and tested the connection with Sonarr, which passed with no issues. </li> <li>I usedconsole to get Sonarr (custom-bridge) to ping Bazarr/Plex (default-bridge) by the IP&amp;port, and that works too</li> </ul> <p>Shouldn&#39;t I have gotten an error in all these cases because Sonarr is on a different network? At first I thought maybe it&#39;s because some of the apps are connected via API key access, but even then, how was I able to ping containers on different networks?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://w

## After Git Repo Rewrite History, Docker Refuses to Load *Some* Files... Why?
 - [https://www.reddit.com/r/docker/comments/1i1pltv/after_git_repo_rewrite_history_docker_refuses_to](https://www.reddit.com/r/docker/comments/1i1pltv/after_git_repo_rewrite_history_docker_refuses_to)
 - RSS feed: $source
 - date published: 2025-01-15T04:31:24+00:00

<!-- SC_OFF --><div class="md"><p>Hi there,</p> <p>Any answer / insights are greatly appreciated!</p> <p>Here’s the situation: I completely rewrote my Git repo history to remove some large files and free up space. The process went smoothly—I updated the remote master branch with the new lightweight history and deleted the old <code>.git</code>. Naturally, all Git commit hashes have changed.</p> <p>Now, when I try to rebuild my Docker images, I keep running into a weird issue. Despite clearing all images, containers, and even running <code>docker system prune --all --volumes --force</code>, some files seem to be missing from the build.</p> <p>The missing files feel almost randomly selected—some are from commits 5 years ago (while others from the same time period persist), and others are recent. I initially thought it might be branch-related, but the pattern of missing files doesn’t make sense.</p> <p>Has anyone encountered something similar or have ideas on how to troubleshoot this?</

## Docker pull fails with 401 inside of Docker container
 - [https://www.reddit.com/r/docker/comments/1i1njfr/docker_pull_fails_with_401_inside_of_docker](https://www.reddit.com/r/docker/comments/1i1njfr/docker_pull_fails_with_401_inside_of_docker)
 - RSS feed: $source
 - date published: 2025-01-15T02:37:49+00:00

<!-- SC_OFF --><div class="md"><p>In a CI pipeline, I have a script which runs a Docker container with the hosts docker.sock mounted to the container. The agent that runs this script logs in to our container registry automatically.</p> <p>This container pulls another docker container from a private registry. When doing so, the agent will fail to pull the image with a 401 error stating the credentials are expired. </p> <p>If I pull directly from the agent itself, and not within the container the pull works fine. I thought by having the docker.sock mounted, the container would have the ability to pull the image with no extra configuration.</p> <p>What additional configuration I need to set on the container pulling the image to ensure that it can access our registry?</p> <p>I have a quick workaround which is just preemptively pulling the image on the agent and then starting the container which performs the pull. But that seems hacky and less than elegant. </p> </div><!-- SC_ON --> &#32;

## How to backup and restore my containers
 - [https://www.reddit.com/r/docker/comments/1i1ljxl/how_to_backup_and_restore_my_containers](https://www.reddit.com/r/docker/comments/1i1ljxl/how_to_backup_and_restore_my_containers)
 - RSS feed: $source
 - date published: 2025-01-15T00:56:52+00:00

<!-- SC_OFF --><div class="md"><p>New to docker.<br/> I currently run , Immich, Nextcloud, Jellyfin, actual budget etc. </p> <p>I have volumes, and ports etc configured to them<br/> How can i backup these settings? i don&#39;t need volume data but volume path needs to be backup. </p> <p>I do not know if its docker file? or docker compose.<br/> docker compose i saved all configuration and it is storing everything in 1 nested container ish, working fine but i don&#39;t want that. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BlazingBane007"> /u/BlazingBane007 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i1ljxl/how_to_backup_and_restore_my_containers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i1ljxl/how_to_backup_and_restore_my_containers/">[comments]</a></span>

