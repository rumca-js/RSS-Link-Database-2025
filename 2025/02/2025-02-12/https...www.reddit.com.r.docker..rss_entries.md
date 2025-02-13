# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Issues installing Docker, unsure how to proceed.
 - [https://www.reddit.com/r/docker/comments/1inz3wg/issues_installing_docker_unsure_how_to_proceed](https://www.reddit.com/r/docker/comments/1inz3wg/issues_installing_docker_unsure_how_to_proceed)
 - RSS feed: $source
 - date published: 2025-02-12T19:16:53+00:00

<!-- SC_OFF --><div class="md"><p>TL;DR: User is working on a Virtual Machine, we installed Docker for her to do development but application is either failing to launch entirely if the user is launching under their own non admin credentials or, when I launch it under admin rights it errors out after inputting email address. Unsure how VM&#39;s are being hosted, not sure if hyper v, Citrix or another.</p> <p><a href="https://imgur.com/a/uzIYC2w">https://imgur.com/a/uzIYC2w</a></p> <p>I am working technical support for a company, tried installing Docker on user&#39;s VDI but am getting an error.</p> <p>&quot;running Hyper-V engine: starting Hyper-V VM: status code not OK but 500: Unhandled exception: job failed with message: &#39;DockerDesktopVM&#39; failed to start. (Virtual machine ID D0B578C9-8900-46BB-8EAF-886B17BDFB62) The Virtual Machine Management Service failed to start the virtual machine &#39;DockerDesktopVM&#39; because one of the Hyper-V components is not running (Virtual m

## Can't communicate container and local network subnet
 - [https://www.reddit.com/r/docker/comments/1iny9yp/cant_communicate_container_and_local_network](https://www.reddit.com/r/docker/comments/1iny9yp/cant_communicate_container_and_local_network)
 - RSS feed: $source
 - date published: 2025-02-12T18:43:41+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m hosting a vpn in docker compose and after all tries I cannot make it to connect to my local network (192.168.1.xx). What am I doing wrong? Network mode is set to host and internal gateway to localnet is made but still cannot access even to localhost</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yutontaku"> /u/yutontaku </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iny9yp/cant_communicate_container_and_local_network/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iny9yp/cant_communicate_container_and_local_network/">[comments]</a></span>

## Can't get a container to run, not sure why
 - [https://www.reddit.com/r/docker/comments/1inwtnz/cant_get_a_container_to_run_not_sure_why](https://www.reddit.com/r/docker/comments/1inwtnz/cant_get_a_container_to_run_not_sure_why)
 - RSS feed: $source
 - date published: 2025-02-12T17:45:49+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m getting a Raspberry Pi setup with DerbyNet for our Cub Scout group so they have a plug-and-play solution for operating their pinewood derby race. I got it running once, but now it won&#39;t start and I can&#39;t find any logs/info.</p> <p>I got my Pi setup, got docker on it, ran the container once — it loaded, I was able to access it via the web interface, but the UI had an error that said it didn&#39;t have permission to write to the data directory I had given it (/home/cubscouts/DerbyNet), which was weird since I thought docker containers ran as root.</p> <p>Anyway, I stopped the container and tried to switch it to run using the current user (cubscouts, which owns that directory) instead:</p> <pre><code>docker run -it -p 80:80 -p 443:443 --user $(id -u) -v /home/cubscouts/DerbyNet:/var/lib/derbynet -v /etc/localtime:/etc/localtime:ro jeffpiazza/derbynet_server </code></pre> <p>That gave me this error:</p> <pre><code>[12-Feb-2025 10:46:36] E

## Create file in Docker
 - [https://www.reddit.com/r/docker/comments/1inubud/create_file_in_docker](https://www.reddit.com/r/docker/comments/1inubud/create_file_in_docker)
 - RSS feed: $source
 - date published: 2025-02-12T16:05:10+00:00

<!-- SC_OFF --><div class="md"><p>Hello I&#39;m new to Docker and was trying to run an Docker image. I installed the imaged and ran into the step to create a config.yml file. How do create a file in Docker to update with my configuration settings. </p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Junior-Beyond-954"> /u/Junior-Beyond-954 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inubud/create_file_in_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inubud/create_file_in_docker/">[comments]</a></span>

## Hands-On Project for Microservice architecture - deployed with Docker compose
 - [https://www.reddit.com/r/docker/comments/1int7g5/handson_project_for_microservice_architecture](https://www.reddit.com/r/docker/comments/1int7g5/handson_project_for_microservice_architecture)
 - RSS feed: $source
 - date published: 2025-02-12T15:18:25+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I made a video about a real project for anyone who might be interested:<br/> - Microservice<br/> - Docker<br/> - Java Spring boot<br/> - MongoDB<br/> - Elasticsearch </p> <p><a href="https://www.youtube.com/watch?v=uCPkxA_BauA">https://www.youtube.com/watch?v=uCPkxA_BauA</a> </p> <p>Hope you will learn something new &lt;3 </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkAcanthocephala1450"> /u/OkAcanthocephala1450 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1int7g5/handson_project_for_microservice_architecture/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1int7g5/handson_project_for_microservice_architecture/">[comments]</a></span>

## Unit Testing using Testcontainers
 - [https://www.reddit.com/r/docker/comments/1inshbj/unit_testing_using_testcontainers](https://www.reddit.com/r/docker/comments/1inshbj/unit_testing_using_testcontainers)
 - RSS feed: $source
 - date published: 2025-02-12T14:47:40+00:00

<!-- SC_OFF --><div class="md"><p>Recently I published a YouTube video on running unit test cases using testcontainers.</p> <p>Do check it out: <a href="https://youtu.be/qvAlVY59Oxo">https://youtu.be/qvAlVY59Oxo</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/waye027"> /u/waye027 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inshbj/unit_testing_using_testcontainers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inshbj/unit_testing_using_testcontainers/">[comments]</a></span>

## Docker Container on Synology DS220+
 - [https://www.reddit.com/r/docker/comments/1inqkl1/docker_container_on_synology_ds220](https://www.reddit.com/r/docker/comments/1inqkl1/docker_container_on_synology_ds220)
 - RSS feed: $source
 - date published: 2025-02-12T13:18:08+00:00

<!-- SC_OFF --><div class="md"><p>I created an Ubuntu VM on my Synology NAS because I originally had PiHole and Ad-Guard Home in Docker containers. However, I couldn&#39;t figure out how to give PiHole and Ad-Guard Home a different IP address from the NAS to test both, so I created an Ubuntu VM. Could I have given the PiHole Docker container a different IP from the NAS and Ad-Guard Home?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/the_mhousman"> /u/the_mhousman </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inqkl1/docker_container_on_synology_ds220/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inqkl1/docker_container_on_synology_ds220/">[comments]</a></span>

## Gdb on docker
 - [https://www.reddit.com/r/docker/comments/1inqid2/gdb_on_docker](https://www.reddit.com/r/docker/comments/1inqid2/gdb_on_docker)
 - RSS feed: $source
 - date published: 2025-02-12T13:14:53+00:00

<!-- SC_OFF --><div class="md"><p>I am trying to install and run ubuntu x86_64 in docker on my m1 mac ,i want gdb in my docker container. x86 binary file runs ,but when I try to debug it using gdb,i get ptrace error, Can&#39;t find cs register Input/output error,anyone has a fix for this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Empty-Deer8759"> /u/Empty-Deer8759 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inqid2/gdb_on_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inqid2/gdb_on_docker/">[comments]</a></span>

## Maker user Read-only to docker
 - [https://www.reddit.com/r/docker/comments/1inn9vv/maker_user_readonly_to_docker](https://www.reddit.com/r/docker/comments/1inn9vv/maker_user_readonly_to_docker)
 - RSS feed: $source
 - date published: 2025-02-12T09:33:56+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to make the user who monitors my server and is in the docker group read-only for security reasons. </p> <p>I have tried it with <a href="https://www.openpolicyagent.org/">OpenPolicyAgent</a> and <a href="https://casbin.org">Casbin</a> but when I deploy it it destroys my environment. </p> <p>it&#39;s silly should I try other things ? or could you give me some tips to achieve it? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Admirable_Desk_7156"> /u/Admirable_Desk_7156 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inn9vv/maker_user_readonly_to_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inn9vv/maker_user_readonly_to_docker/">[comments]</a></span>

## qBittorrent not downloading “Operation not permitted”
 - [https://www.reddit.com/r/docker/comments/1inmfpf/qbittorrent_not_downloading_operation_not](https://www.reddit.com/r/docker/comments/1inmfpf/qbittorrent_not_downloading_operation_not)
 - RSS feed: $source
 - date published: 2025-02-12T08:29:43+00:00

<!-- SC_OFF --><div class="md"><p>I had docker create a separate subnet that I’m running a qBittorrent container through a NordVPN container. This is on Debian12 os. The containers run perfectly fine. When I try to install a torrent I get an error “Operation not permitted” for every seeding source listed under my logs in qBittorrent. If fixed this by allowing for the ports in my docker-compose.yml file that starts the containers. I was able to download a few torrents without issue before it broke again. Now I can’t figure out how to fix it. I have it saving to folder /mnt/hdd:/mnt/hdd in the yml configuration. The user has ownership of that pathway. Any ideas?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Efficient-Pilot-9815"> /u/Efficient-Pilot-9815 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inmfpf/qbittorrent_not_downloading_operation_not/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comme

## DockerDesktop not opening
 - [https://www.reddit.com/r/docker/comments/1inksgn/dockerdesktop_not_opening](https://www.reddit.com/r/docker/comments/1inksgn/dockerdesktop_not_opening)
 - RSS feed: $source
 - date published: 2025-02-12T06:32:15+00:00

<!-- SC_OFF --><div class="md"><p>so im new to the whole docker think and i just messing around with files and stuff but what has been happening is that ill turn on my laptop open docker then close it when im done by hitting the X on the top but later when i try to open it again it wouldn&#39;t even try to open. should i try to reinstall it? and if i do will it still save my files?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Temporary_State_8968"> /u/Temporary_State_8968 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1inksgn/dockerdesktop_not_opening/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1inksgn/dockerdesktop_not_opening/">[comments]</a></span>

