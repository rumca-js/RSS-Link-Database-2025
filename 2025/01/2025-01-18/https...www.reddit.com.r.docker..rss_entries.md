# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Setup + Access Docker + Containers from other (local) machines
 - [https://www.reddit.com/r/docker/comments/1i4k5a5/setup_access_docker_containers_from_other_local](https://www.reddit.com/r/docker/comments/1i4k5a5/setup_access_docker_containers_from_other_local)
 - RSS feed: $source
 - date published: 2025-01-18T23:14:07+00:00

<!-- SC_OFF --><div class="md"><p>Hello! Definitely a newbie here trying to dive in but having some roadblocks. Currently I have a Rasp Pi 5 with Docker installed and set up. However, I intend on having the Pi be headless, and remote in with my main Windows machine. Is there an easy way to access the Docker Engine running on the Pi from my Windows machine, without using either VNC or SSH on the command line? Both are doable, but VNC is clunky and ideally I don&#39;t want to have to use it on a regular basis, and currently I don&#39;t have the confidence with CLI to do EVERYthing while at the same time I&#39;m learning how to set up containers, opening them to LAN, etc.</p> <p>Google has been failing me on trying to find a guide or other post regarding this specific issue. Does anyone here have advice, or can point me to an appropriate guide? Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/deltaflip"> /u/deltaflip </a> <br/> <span><a href

## Static IP address for pi-hole - use pi-hole for Docker host DNS?
 - [https://www.reddit.com/r/docker/comments/1i4j5ce/static_ip_address_for_pihole_use_pihole_for](https://www.reddit.com/r/docker/comments/1i4j5ce/static_ip_address_for_pihole_use_pihole_for)
 - RSS feed: $source
 - date published: 2025-01-18T22:26:12+00:00

<!-- SC_OFF --><div class="md"><p>I used macvlan and have it working with a static IP on my LAN, but due to host-container isolation, my docker host cannot use pi-hole for DNS resolution when the container is running on the docker host. Is there a method where pi-hole can have a static IP address on my normal LAN address space and the docker host can contact it for DNS resolution at the same time since neither macvlan nor ipvlan allow for this?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pugglewugglez"> /u/pugglewugglez </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i4j5ce/static_ip_address_for_pihole_use_pihole_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i4j5ce/static_ip_address_for_pihole_use_pihole_for/">[comments]</a></span>

## Dial TCP error on running with Docker on WSL
 - [https://www.reddit.com/r/docker/comments/1i4gfxe/dial_tcp_error_on_running_with_docker_on_wsl](https://www.reddit.com/r/docker/comments/1i4gfxe/dial_tcp_error_on_running_with_docker_on_wsl)
 - RSS feed: $source
 - date published: 2025-01-18T20:21:56+00:00

<!-- SC_OFF --><div class="md"><p>I have Docker Desktop &amp; Debian WSL installed and I am trying to run zimit and get the following error:</p> <pre><code>aggam@DESKTOP-QJ6804O:/mnt/c/Users/Aggam/Desktop$ docker run docker run zimit zimit -u [https://ranchermanager.docs.rancher.com](https://ranchermanager.docs.rancher.com) \--name rancher\_docs docker: error during connect: Head &quot;http://docker:2375/\_ping&quot;: dial tcp: lookup docker on 192.168.65.7:53: no such host. See &#39;docker run --help&#39;. aggam@DESKTOP-QJ6804O:/mnt/c/Users/Aggam/Desktop$ docker run docker run zimit zimit -u [https://ranchermanager.docs.rancher.com](https://ranchermanager.docs.rancher.com) \--name rancher\_docs docker: error during connect: Head &quot;http://docker:2375/\_ping&quot;: dial tcp: lookup docker on 192.168.65.7:53: no such host. See &#39;docker run --help&#39;. </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Prize-Big2335"> /u/Prize-Big233

## Trouble with docker socket/ Immich install
 - [https://www.reddit.com/r/docker/comments/1i4fo0n/trouble_with_docker_socket_immich_install](https://www.reddit.com/r/docker/comments/1i4fo0n/trouble_with_docker_socket_immich_install)
 - RSS feed: $source
 - date published: 2025-01-18T19:46:59+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>Hope this is an easy fix, as I am a total noob to docker. However, a couple of hours of searching previous threads has gotten me nowhere.</p> <p>When trying to start my immich container, I am met with the following:</p> <p>PS Microsoft.PowerShell.Core\FileSystem::\\wsl.localhost\docker-desktop\home\george\immich-app\docker&gt; docker-compose up -d</p> <p>[+] Running 2/0</p> <p>- Container immich_postgres Creating 0.0s</p> <p>✔ Container immich_redis Running 0.0s</p> <p>✔ Container immich_machine_learning Running 0.0s</p> <p>Error response from daemon: can&#39;t access specified distro mount service: stat /run/guest-services/distro-services/docker-desktop.sock: no such file or directory</p> <p>This is with the latest versions of docker and immich.</p> <p>Any advice appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/spagbolthebest"> /u/spagbolthebest </a> <br/> <span><a href="https://www.r

## docker desktop hyperlink issue ubuntu server 24.04
 - [https://www.reddit.com/r/docker/comments/1i4eyju/docker_desktop_hyperlink_issue_ubuntu_server_2404](https://www.reddit.com/r/docker/comments/1i4eyju/docker_desktop_hyperlink_issue_ubuntu_server_2404)
 - RSS feed: $source
 - date published: 2025-01-18T19:15:17+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys, this is going to sound crazy but every time i click a link in Docker Desktop GUI, it tries/fails to open in LibreOffice. I have double checked my default app selection and even verified that i can click links in other applications that properly resolve to my browser. About to flip the desk. Any help would be greatly appreciated.</p> <p>ubuntu server 24.04</p> <p>docker.desktop verson 4.37.1</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Comprehensive_Ad7587"> /u/Comprehensive_Ad7587 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i4eyju/docker_desktop_hyperlink_issue_ubuntu_server_2404/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i4eyju/docker_desktop_hyperlink_issue_ubuntu_server_2404/">[comments]</a></span>

## Mount a USB drive in a Docker container
 - [https://www.reddit.com/r/docker/comments/1i49yvl/mount_a_usb_drive_in_a_docker_container](https://www.reddit.com/r/docker/comments/1i49yvl/mount_a_usb_drive_in_a_docker_container)
 - RSS feed: $source
 - date published: 2025-01-18T15:32:12+00:00

<!-- SC_OFF --><div class="md"><p>Hi all, I am trying to follow this tutorial for OSX <a href="https://docs.sevenbridges.com/docs/mount-a-usb-drive-in-a-docker-container">https://docs.sevenbridges.com/docs/mount-a-usb-drive-in-a-docker-container</a> , but in step 4 I have this problem: Mountpoint /mnt/usb does not exist</p> <p>can anyone help me? thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cecca84_2"> /u/cecca84_2 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i49yvl/mount_a_usb_drive_in_a_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i49yvl/mount_a_usb_drive_in_a_docker_container/">[comments]</a></span>

## Symbolic link loop from mounts, am I missing something obvious?
 - [https://www.reddit.com/r/docker/comments/1i489q4/symbolic_link_loop_from_mounts_am_i_missing](https://www.reddit.com/r/docker/comments/1i489q4/symbolic_link_loop_from_mounts_am_i_missing)
 - RSS feed: $source
 - date published: 2025-01-18T14:08:31+00:00

<!-- SC_OFF --><div class="md"><p>Hi folks, </p> <p>I have a VM running services from the *arr stack, recently I modified the docker compose so that only a single path was mounted instead of multiple. I did this to facilitate atomic moves/copies. </p> <p>The previous compose looked like, notice the last two mounts in the volume section</p> <pre><code> radarr: image: lscr.io/linuxserver/radarr:develop network_mode: host container_name: radarr logging: driver: json-file environment: - PUID=1000 - PGID=1000 - TZ=America/New_York volumes: - /etc/localtime:/etc/localtime:ro - /opt/servarr/config/radarr:/config - /opt/servarr/config/radarr/scripts:/app/radarr/bin/scripts - ./config/radarr/custom-services:/custom-services.d - ./config/radarr/custom-cont-init:/custom-cont-init.d - /mnt/smb/downloads:/mnt/downloads - /mnt/smb/movies:/mnt/movies restart: unless-stopped labels: - &quot;com.centurylinklabs.watchtower.enable=true&quot; </code></pre> <p>The updated compos looks like below, notice 

## Optimize .vhdx WSL2 Distro File for Docker Desktop v4.37.1 on Windows 10
 - [https://www.reddit.com/r/docker/comments/1i47rlk/optimize_vhdx_wsl2_distro_file_for_docker_desktop](https://www.reddit.com/r/docker/comments/1i47rlk/optimize_vhdx_wsl2_distro_file_for_docker_desktop)
 - RSS feed: $source
 - date published: 2025-01-18T13:41:32+00:00

<!-- SC_OFF --><div class="md"><p>How to disable sparse mode specifically for <code>C:\Users\&lt;user&gt;\AppData\Local\Docker\wsl\disk\docker_data.vhdx</code>? This is the file that is growing. But it no longer has a dedicated separate distro - since one of the latest versions <code>docker-desktop-data</code> doesn&#39;t exist any more so I can no longer run the command <code>wsl --manage docker-desktop-data --set-sparse false</code>.</p> <p>It appears that <code>wsl --manage docker-desktop --set-sparse false</code> is applied only to <code>C:\Users\&lt;user&gt;\AppData\Local\Docker\wsl\main\ext4.vhdx</code>.</p> <p>The ultimate goal is to be able to run: <code>optimize-vhd -Path C:\Users\&lt;user&gt;\AppData\Local\Docker\wsl\disk\docker_data.vhdx -Mode full</code> so I can reclaim space back.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dat_bunneh"> /u/dat_bunneh </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i47rlk/opt

## Synology -> Docker -> qBittorrent "errored"
 - [https://www.reddit.com/r/docker/comments/1i46mav/synology_docker_qbittorrent_errored](https://www.reddit.com/r/docker/comments/1i46mav/synology_docker_qbittorrent_errored)
 - RSS feed: $source
 - date published: 2025-01-18T12:33:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi all,</p> <p>I&#39;m having trouble getting my qbittorrent to work on my NAS, using docker. All is set up and installed, but when I test qbittorrent by loading a link to a .torrent file, it downloads the .torrent, but then immediately stops, and posts &quot;errored&quot; as status.</p> <p>When I look in the docker/qbittorrent log, it says:</p> <p>(W) 2025-01-18T11:59:33 - File error alert. Torrent: &quot;ubuntu-unity-24.10-desktop-amd64.iso&quot;. File: &quot;/incomplete/ubuntu-unity-24.10-desktop-amd64.iso&quot;. Reason: &quot;ubuntu-unity-24.10-desktop-amd64.iso file_stat (/incomplete/ubuntu-unity-24.10-desktop-amd64.iso) error: Permission denied&quot;</p> <p>I interpret this as a permission issue, so I did two things:</p> <p>1: Went into the DSM and turned full read/write permissions on for all users and user groups.</p> <p>2: Went into the Docker containerpermissions, and ensured that all volume/file/folder/mount paths had &quot;rw&quot; as &qu

## Opinions on creating a school container
 - [https://www.reddit.com/r/docker/comments/1i42b9j/opinions_on_creating_a_school_container](https://www.reddit.com/r/docker/comments/1i42b9j/opinions_on_creating_a_school_container)
 - RSS feed: $source
 - date published: 2025-01-18T07:24:19+00:00

<!-- SC_OFF --><div class="md"><p>I really hate downloading software for school on my pc or macbook pro. I’ve been looking into a few options like: - a VM on each machine w/ file syncing - a remote VM with remote access</p> <p>those have a few downsides and i thought about using a docker container. it seems like a good middle ground but i dont know how to go about it.</p> <p>My main concern is if I need some software for school how would i make it only exist within the container? Where would I start? Would I create the same image for my windows pc and my macbook?</p> <p>All of my experience with docker so far has been running simple game servers so the idea of using it more as a “VM” is confusing me.</p> <p>I appreciate any help or opinions. Thanks!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/matlireddit"> /u/matlireddit </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i42b9j/opinions_on_creating_a_school_container/">[link

## Docker won't run after latest Wondows 10 update
 - [https://www.reddit.com/r/docker/comments/1i3x4cl/docker_wont_run_after_latest_wondows_10_update](https://www.reddit.com/r/docker/comments/1i3x4cl/docker_wont_run_after_latest_wondows_10_update)
 - RSS feed: $source
 - date published: 2025-01-18T02:07:40+00:00

<!-- SC_OFF --><div class="md"><p>This is the message I get:</p> <p>deploying WSL2 distributions ensuring main distro is deployed: deploying &quot;docker-desktop&quot;: importing WSL distro &quot;The service cannot be started, either because it is disabled or because it has no enabled devices associated with it. \r\nError code: Wsl/0x80070422\r\n&quot; output=&quot;docker-desktop&quot;: exit code: 4294967295: running WSL command wsl.exe C:\Windows\System32\wsl.exe --import docker-desktop &lt;HOME&gt;\AppData\Local\Docker\wsl\main C:\Program Files\Docker\Docker\resources\wsl\wsl-bootstrap.tar --version 2: The service cannot be started, either because it is disabled or because it has no enabled devices associated with it. Error code: Wsl/0x80070422 : exit status 0xffffffff checking if isocache exists: CreateFile \wsl$\docker-desktop-data\isocache: The network name cannot be found.</p> <p>Restarting the computer doesn&#39;t fix it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hr
