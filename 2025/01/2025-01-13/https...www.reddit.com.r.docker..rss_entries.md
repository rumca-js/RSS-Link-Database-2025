# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## How to build and launch docker container for cross-compiled architecture(aarch64) on x86 Ubuntu?
 - [https://www.reddit.com/r/docker/comments/1i0p13y/how_to_build_and_launch_docker_container_for](https://www.reddit.com/r/docker/comments/1i0p13y/how_to_build_and_launch_docker_container_for)
 - RSS feed: $source
 - date published: 2025-01-13T21:22:18+00:00

<!-- SC_OFF --><div class="md"><p>Consider I am developing C++ Linux Application for Target hardware which is arrch64 (Embedded System running custom Ubuntu OS)</p> <p>Now for testing my Application into some simulated environment instead of directly testing on Hardware I want to build docker container which can run this Application so can test independently without depending on actual hardware access</p> <p>Task which I am looking to perform:</p> <ol> <li>build docker container for simulating target machine(aarch64) which can run Application which is compiled for target machine( aarch64) using Host Machine (Ubuntu x86): Do I have to use same Host Machine as Target machine to build and spin docker container (which is arrm64 architecture) so it can run application compiled for target machine which is arrm64</li> <li>spin up this container on this Host Machine(Ubuntu x86) to launch developed Application</li> </ol> <p><strong>Note:</strong><br/> -&gt; Already know how to build and spin 

## Docker Compose - Dashly - Additional Properties Not Allowed
 - [https://www.reddit.com/r/docker/comments/1i0olw9/docker_compose_dashly_additional_properties_not](https://www.reddit.com/r/docker/comments/1i0olw9/docker_compose_dashly_additional_properties_not)
 - RSS feed: $source
 - date published: 2025-01-13T21:04:41+00:00

<!-- SC_OFF --><div class="md"><p>Hello Docker Community:</p> <p>Here is the setup/scenario...</p> <p>The host server is running IP Address 172.16.10.5/25. It is running AlmaLinux 9 with Docker version 27.4.1 and Portainer version 2.21.4.</p> <p>I created a custom docker network (through CLI) for containers to run on the same subnet as the server host on my home network. The following is the custom network details showing on the Portainer WebGUI:</p> <p>Name: net-vlan10 </p> <p>Id: &lt;bunch of characters&gt; </p> <p>Driver: ipvlan </p> <p>Scope: local </p> <p>Attachable: false </p> <p>Internal: false </p> <p>IPV4 Subnet - <a href="http://172.16.10.0/25">172.16.10.0/25</a> IPV4 Gateway - <a href="http://172.16.10.1">172.16.10.1</a> </p> <p>IPV4 IP Range IPV4 Excluded IPs</p> <p>For testing purposes, I created three separate docker compose NGINX containers (through Portainer Stack WebGUI interface) with a different static IP Address for each container. I am successful in accessing all

## Stock on ¨starting the docker engine¨
 - [https://www.reddit.com/r/docker/comments/1i0o9s0/stock_on_starting_the_docker_engine](https://www.reddit.com/r/docker/comments/1i0o9s0/stock_on_starting_the_docker_engine)
 - RSS feed: $source
 - date published: 2025-01-13T20:51:02+00:00

<!-- SC_OFF --><div class="md"><p>please someone help me im going insane. </p> <p>after crashing a bunch of time, i uninstall it, verified that hyper-v and windows subsistem for windows are activated. wsl is version 2 and updated. dont know what to do.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/juancruzz32"> /u/juancruzz32 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i0o9s0/stock_on_starting_the_docker_engine/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i0o9s0/stock_on_starting_the_docker_engine/">[comments]</a></span>

## Overlay always Overlay2? Why?
 - [https://www.reddit.com/r/docker/comments/1i0l1v3/overlay_always_overlay2_why](https://www.reddit.com/r/docker/comments/1i0l1v3/overlay_always_overlay2_why)
 - RSS feed: $source
 - date published: 2025-01-13T18:38:43+00:00

<!-- SC_OFF --><div class="md"><p>Why&#39;s it called Overlay2 and not just Overlay?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tylerdurden4285"> /u/tylerdurden4285 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i0l1v3/overlay_always_overlay2_why/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i0l1v3/overlay_always_overlay2_why/">[comments]</a></span>

## "Docker.app" was not opened because it contains malware.
 - [https://www.reddit.com/r/docker/comments/1i0k5ig/dockerapp_was_not_opened_because_it_contains](https://www.reddit.com/r/docker/comments/1i0k5ig/dockerapp_was_not_opened_because_it_contains)
 - RSS feed: $source
 - date published: 2025-01-13T18:02:45+00:00

<!-- SC_OFF --><div class="md"><p>Mac mini M1, Sequoia 15.2</p> <p>I got this this morning, anyone else?</p> <p>Malware Blocked and Moved to Trash</p> <p>&quot;Docker.app&quot; was not opened because it contains malware. This action did not harm your Mac.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nice_Ad7740"> /u/Nice_Ad7740 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i0k5ig/dockerapp_was_not_opened_because_it_contains/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i0k5ig/dockerapp_was_not_opened_because_it_contains/">[comments]</a></span>

## Bind mount files
 - [https://www.reddit.com/r/docker/comments/1i0egbd/bind_mount_files](https://www.reddit.com/r/docker/comments/1i0egbd/bind_mount_files)
 - RSS feed: $source
 - date published: 2025-01-13T13:54:30+00:00

<!-- SC_OFF --><div class="md"><p>Can someone please, please add a small update to docker so that you can bind mount files easily? As far as I can tell:</p> <p>With short syntax in compose:</p> <ul> <li>if the file does not exist on the host, it will create a directory, which then means the container won&#39;t run</li> <li>if the file does exist on the host then it won&#39;t overwrite it with the initial contents when you first create the container</li> <li>if the file does not exist in the container at creation, it will continue as above</li> </ul> <p>With the long syntax in compose:</p> <ul> <li>If the file does not exist on the host (not sure yet)</li> <li>if the file does exist on the host then it won&#39;t overwrite it with the initial contents when you first create the container</li> <li>If the files does not exist in the container at creation, it won&#39;t allow you to create the container saying it doesn&#39;t exist</li> </ul> <p>If I am wrong and this is simple - please let 

## Why is Docker Swarm Operator inspecting a container at the end of the dag run?
 - [https://www.reddit.com/r/docker/comments/1i0bpfj/why_is_docker_swarm_operator_inspecting_a](https://www.reddit.com/r/docker/comments/1i0bpfj/why_is_docker_swarm_operator_inspecting_a)
 - RSS feed: $source
 - date published: 2025-01-13T11:13:45+00:00

<!-- SC_OFF --><div class="md"><p>My setup is so:</p> <p>I have a 3 node cluster with one manager and two workers. My manager is configured to expose the API on port 2375 which I pass to the docker_swarm_operator as a parameter. At the end of the dag run</p> <p>```python import datetime</p> <p>from airflow import DAG from airflow.providers.docker.operators.docker_swarm import DockerSwarmOperator from docker.types import Mount, NetworkAttachmentConfig</p> <p>with DAG( dag_id=&quot;movie_retriever_dag&quot;, start_date=datetime.datetime(2025, 1, 4), ): extraction_container = DockerSwarmOperator( task_id=&quot;movie-extract_transform_load&quot;, image=&quot;movie-extract_transform_load-image:latest&quot;, command=&quot;python ./extract_transform_load.py -t \&quot;{{ dag_run.conf[&#39;title&#39;] }}\&quot;&quot;, mount_tmp_dir=False, mounts=[ Mount( target=&quot;/app/temp_data&quot;, source=&quot;/mnt/storage-server0/sda3/airflow/tmp&quot;, type=&quot;bind&quot;, ), Mount( target=&quot;/

## overlay2 folder is massive. Prune did not help.
 - [https://www.reddit.com/r/docker/comments/1i05ne5/overlay2_folder_is_massive_prune_did_not_help](https://www.reddit.com/r/docker/comments/1i05ne5/overlay2_folder_is_massive_prune_did_not_help)
 - RSS feed: $source
 - date published: 2025-01-13T04:09:13+00:00

<!-- SC_OFF --><div class="md"><p>Can&#39;t seem to find a solution to this. Been googling for over an hour. Prune got me enough space so that I can use my system, but barely any space. How can I fix this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ShadowWizard1"> /u/ShadowWizard1 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i05ne5/overlay2_folder_is_massive_prune_did_not_help/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i05ne5/overlay2_folder_is_massive_prune_did_not_help/">[comments]</a></span>

## Can't connect to Web UI for Plex Docker Container
 - [https://www.reddit.com/r/docker/comments/1i05hx9/cant_connect_to_web_ui_for_plex_docker_container](https://www.reddit.com/r/docker/comments/1i05hx9/cant_connect_to_web_ui_for_plex_docker_container)
 - RSS feed: $source
 - date published: 2025-01-13T04:00:45+00:00

<!-- SC_OFF --><div class="md"><p>Hey all,</p> <p>I&#39;m completely new to Docker (using WSL / Docker Desktop), and I&#39;m trying to set up a Plex Docker Container and have been completely unable to access the web ui. I ran a netstat search for port 32400 on my machine and it doesn&#39;t show up at all. I&#39;m sure I&#39;m missing something really basic but have no idea what&#39;s going on :(</p> <p>This is the compose I&#39;m using:</p> <p>---</p> <p>services:</p> <p>plex:</p> <p>image: <a href="http://lscr.io/linuxserver/plex:latest">lscr.io/linuxserver/plex:latest</a></p> <p>container_name: plex</p> <p>network_mode: host</p> <p>environment:</p> <p>- PUID=1000</p> <p>- PGID=1000</p> <p>- TZ=Australia/Sydney</p> <p>- VERSION=docker</p> <p>- PLEX_CLAIM=</p> <p>volumes:</p> <p>- /docker/plex/config:/config</p> <p>- /mnt/d/media/anime:/anime</p> <p>- /mnt/d/media/animemovies:/animemovies</p> <p>- /mnt/d/media/cartoons:/cartoons</p> <p>- /mnt/d/media/movies:/movies</p> <p>- /mnt/d/me

## 🎉 𝐯𝐢𝐧𝐝 is now open-sourced 🎉
 - [https://www.reddit.com/r/docker/comments/1i037b6/𝐯𝐢𝐧𝐝_is_now_opensourced](https://www.reddit.com/r/docker/comments/1i037b6/𝐯𝐢𝐧𝐝_is_now_opensourced)
 - RSS feed: $source
 - date published: 2025-01-13T01:56:47+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m thrilled to open source a tool that I build and use on a daily basis: 𝐯𝐢𝐧𝐝, which stands for Vm IN Docker, is a tool to create containers that look and work like virtual machines, on Docker (well, and Podman).</p> <p>When learning and building things, having a few handy VMs is a common requirement for a techie like me, even the world has become hybrid. Can we spin up a set of &quot;VMs&quot; in just a few seconds on our laptop, with the bare minimum resources? This is something that we now can achieve by simply issuing &quot;𝘷𝘪𝘯𝘥 𝘤𝘰𝘯𝘧𝘪𝘨 𝘤𝘳𝘦𝘢𝘵𝘦 --𝘳𝘦𝘱𝘭𝘪𝘤𝘢𝘴 3&quot; followed by &quot;𝘷𝘪𝘯𝘥 𝘤𝘳𝘦𝘢𝘵𝘦&quot;, and then you can &quot;𝘷𝘪𝘯𝘥 𝘴𝘴𝘩&quot; into any of the VMs to enjoy VM-like experience.</p> <p>Check out my GitHub repo, where has an asciinema-powered demo for what vind can do for you: <a href="https://github.com/brightzheng100/vind">https://github.com/brightzheng100/vind</a>.</p> <p>Have fun and let me know if you spot any errors -- hey, this is 

## [HELP] Gpu not being used
 - [https://www.reddit.com/r/docker/comments/1i028yw/help_gpu_not_being_used](https://www.reddit.com/r/docker/comments/1i028yw/help_gpu_not_being_used)
 - RSS feed: $source
 - date published: 2025-01-13T01:07:51+00:00

<!-- SC_OFF --><div class="md"><p>So i have gpu driver version Driver Version: 566.36 and have CUDA Version: 12.7. if i do &quot;docker pull nvidia/cuda:12.7.0-runtime-ubuntu20.04&quot; it tell me &quot; Error response from daemon: failed to resolve reference &quot;docker.io/nvidia/cuda:12.7.0-runtime-ubuntu20.04&quot;: docker.io/nvidia/cuda:12.7.0-runtime-ubuntu20.04: not found&quot; Im on windows and docker itself is fine but its running on cpu instead of gpu. What do i do?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/watchdrstone"> /u/watchdrstone </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i028yw/help_gpu_not_being_used/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i028yw/help_gpu_not_being_used/">[comments]</a></span>

## Question about docker networking
 - [https://www.reddit.com/r/docker/comments/1i01z74/question_about_docker_networking](https://www.reddit.com/r/docker/comments/1i01z74/question_about_docker_networking)
 - RSS feed: $source
 - date published: 2025-01-13T00:54:35+00:00

<!-- SC_OFF --><div class="md"><p>Let&#39;s say I have containers A, B and C all on the bridge network. They refer to each other by the local IP address &amp; the port...</p> <ol> <li>If I create a custom user defined network and put those containers on it, my understanding is that they can now communicate to each other by either container name or the container IP... which means this shouldn&#39;t break my existing configs, where the containers are all referred to as the local-IP&amp;port right?</li> <li>If container A &amp; B are on the user defined network and container C is on bridge, is it still possible for container A&amp;B to refer to C (or vice versa) by the local IP &amp; port?</li> <li>Changing the network from Bridge to the user defined network will not change the containers current local IP address right?</li> </ol> <p>Basically, I have like 10+ containers all related to the *arr apps on bridge mode right now and I&#39;m wondering what could break if I change it to a cust

