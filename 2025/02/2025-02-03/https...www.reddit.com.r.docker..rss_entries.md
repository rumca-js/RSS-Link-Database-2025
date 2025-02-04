# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Docker building multiarch image randomly fails in gitlab CI
 - [https://www.reddit.com/r/docker/comments/1ih2ruh/docker_building_multiarch_image_randomly_fails_in](https://www.reddit.com/r/docker/comments/1ih2ruh/docker_building_multiarch_image_randomly_fails_in)
 - RSS feed: $source
 - date published: 2025-02-03T22:59:27+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;ve been trying to debug the issue of my CI build failing randomly ( sometimes job succeeds, other times it does not ) when using docker buildx to also build for arm64. I get the error, <code>usr/bin/gcc&#39; failed with exit code -11</code> randomly on different packages, hiredis, psutils, and some other ones.<br/> My Dockerfile runs a script that uses poetry to install the python dependencies.</p> <p><code>set -e</code></p> <p><code>python3 -m pip install --upgrade pip</code></p> <p><code>python3 -m pip install --upgrade setuptools==72.1.0</code></p> <p><code>python3 -m pip install poetry==1.8.2 gunicorn==22.0.0</code></p> <p><code>poetry config virtualenvs.create false</code></p> <p><code>poetry install --no-dev</code></p> <p>For example the following CI failed on the &quot;psutils&quot; package:</p> <blockquote> <p>ChefBuildError<br/> #24 111.0<br/> #24 111.0 Backend subprocess exited when trying to invoke build_wheel<br/> #24 

## Step-by-Step Guide to Installing Docker on Windows
 - [https://www.reddit.com/r/docker/comments/1igyabl/stepbystep_guide_to_installing_docker_on_windows](https://www.reddit.com/r/docker/comments/1igyabl/stepbystep_guide_to_installing_docker_on_windows)
 - RSS feed: $source
 - date published: 2025-02-03T19:57:09+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://gustavosantosio.com/step-by-step-guide-to-installing-docker-on-windows?showSharer=true#heading-download-and-install-docker">https://gustavosantosio.com/step-by-step-guide-to-installing-docker-on-windows?showSharer=true#heading-download-and-install-docker</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/gustavribeiro"> /u/gustavribeiro </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1igyabl/stepbystep_guide_to_installing_docker_on_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1igyabl/stepbystep_guide_to_installing_docker_on_windows/">[comments]</a></span>

## Should I Use Docker for Game Servers?
 - [https://www.reddit.com/r/docker/comments/1igroy5/should_i_use_docker_for_game_servers](https://www.reddit.com/r/docker/comments/1igroy5/should_i_use_docker_for_game_servers)
 - RSS feed: $source
 - date published: 2025-02-03T15:31:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone, I’m setting up a few game servers and trying to decide the best way to manage them.</p> <p>Here’s my setup:</p> <ul> <li><strong>3x CS 1.6 servers</strong></li> <li><strong>1x CS2 server</strong></li> <li><strong>1x Minecraft server</strong></li> </ul> <p>I’m thinking about using <strong>Docker</strong> to keep things organized, but I’m not sure if it’s the best approach. Would it make things easier, or is it just unnecessary complexity for game servers?</p> <p>Would love to hear from anyone who has tried this. Is Docker the way to go, or should I just run everything directly on the machine with <code>screen</code> / <code>tmux</code>?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FortiByte"> /u/FortiByte </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1igroy5/should_i_use_docker_for_game_servers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/

## Msc research project idea
 - [https://www.reddit.com/r/docker/comments/1igrbz4/msc_research_project_idea](https://www.reddit.com/r/docker/comments/1igrbz4/msc_research_project_idea)
 - RSS feed: $source
 - date published: 2025-02-03T15:15:29+00:00

<!-- SC_OFF --><div class="md"><p>Hi there…</p> <p>I am looking for a research idea for my MSc I would love to have your opinion also, if so please drop a comment Thanks in advance 🤩🤗</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Upstairs-Ad-5581"> /u/Upstairs-Ad-5581 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1igrbz4/msc_research_project_idea/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1igrbz4/msc_research_project_idea/">[comments]</a></span>

## GPG error: http://deb.debian.org/debian-security bookworm-security InRelease: At least one invalid signature was encountered.
 - [https://www.reddit.com/r/docker/comments/1igm1uk/gpg_error_httpdebdebianorgdebiansecurity](https://www.reddit.com/r/docker/comments/1igm1uk/gpg_error_httpdebdebianorgdebiansecurity)
 - RSS feed: $source
 - date published: 2025-02-03T10:22:36+00:00

<!-- SC_OFF --><div class="md"><p>Hi Guys, I using docker to buil image, It&#39;s very simple dockerfile. but It show error</p> <p>GPG error: <a href="http://deb.debian.org/debian-security">http://deb.debian.org/debian-security</a> bookworm-security InRelease: At least one invalid signature was encountered.</p> <p>can anyone tell me how to fix it?</p> <p>my dockerfile: </p> <p>FROM python:3.12-slim</p> <p>RUN apt-get update &amp;&amp; apt-get install -y git &amp;&amp; rm -rf /var/lib/apt/lists/*</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/asc686f61"> /u/asc686f61 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1igm1uk/gpg_error_httpdebdebianorgdebiansecurity/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1igm1uk/gpg_error_httpdebdebianorgdebiansecurity/">[comments]</a></span>

## Edit a file in Docker on Synology DSM
 - [https://www.reddit.com/r/docker/comments/1igj1xs/edit_a_file_in_docker_on_synology_dsm](https://www.reddit.com/r/docker/comments/1igj1xs/edit_a_file_in_docker_on_synology_dsm)
 - RSS feed: $source
 - date published: 2025-02-03T06:40:16+00:00

<!-- SC_OFF --><div class="md"><p>I have installed a MySql via Docker on Synology. My question is how can I edit the mysql configuration file my.cnf?</p> <p>Somehow I cannot find my.cnf on Synology&#39;s file system. When I open a terminal/bash into the docker/mysql package, I am able to find this file my.cnf. But I cannot find any useful editor such as vi etc for me to edit this my.cnf. </p> <p>Any help will be appreciated. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/runasfastasucan"> /u/runasfastasucan </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1igj1xs/edit_a_file_in_docker_on_synology_dsm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1igj1xs/edit_a_file_in_docker_on_synology_dsm/">[comments]</a></span>

## Correct setup for mounting network storage when accessing from containers
 - [https://www.reddit.com/r/docker/comments/1igi1dl/correct_setup_for_mounting_network_storage_when](https://www.reddit.com/r/docker/comments/1igi1dl/correct_setup_for_mounting_network_storage_when)
 - RSS feed: $source
 - date published: 2025-02-03T05:34:23+00:00

<!-- SC_OFF --><div class="md"><p>I am in the process of moving all the programs i have running on a windows VM in to their own docker containers on a different VM and want to know what the best practice is for setting up the file shares i require. </p> <p>I will have multiple containers that i need to blind mount network shares to. </p> <ol> <li><p>Right now the share is mounted in using /etc/fstab and is mounted as root. Is there an issue with doing this or should it be mounted so that it is owned as the default user. the reason i ask is because i ran in to a permission issue where the puid and guid were set to 1000 and had to change to 0 so it would work correctly. </p></li> <li><p>Should mount the network share once to the root of the share and then path out each blind mount as required for the containers or should i mount each folder that i require for the container and then blind mount each from its own /mnt location. </p></li> </ol> <p>The share location is on the local networ

## |Weekly Thread| Ask for help here in the comments or anything you want to post
 - [https://www.reddit.com/r/docker/comments/1ighhrz/weekly_thread_ask_for_help_here_in_the_comments](https://www.reddit.com/r/docker/comments/1ighhrz/weekly_thread_ask_for_help_here_in_the_comments)
 - RSS feed: $source
 - date published: 2025-02-03T05:02:22+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/TJOcraft8"> /u/TJOcraft8 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ighhrz/weekly_thread_ask_for_help_here_in_the_comments/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ighhrz/weekly_thread_ask_for_help_here_in_the_comments/">[comments]</a></span>

## NFS mounts FSTAB
 - [https://www.reddit.com/r/docker/comments/1igcyx9/nfs_mounts_fstab](https://www.reddit.com/r/docker/comments/1igcyx9/nfs_mounts_fstab)
 - RSS feed: $source
 - date published: 2025-02-03T01:04:11+00:00

<!-- SC_OFF --><div class="md"><p>I currently mount an NFS share to /mnt/storage0 I then use /mnt/storage0/Docker/xyz as a bind mount for every config type of mount location for my containers. This really handnt been a problem, i migrated everything to a new server, and everything works, but....It seems like anything with a db (sqlite, etc) is pretty slow to run now. I tried moving some of them to non NFS bind mounts and it seemed to improve. I&#39;m using the default options for mounting from /etc/fstab. Could it be I just need to use some options like nolock, etc?</p> <p>I did try CIFS mounts, but the whole permissions not changing thing with items like acme.json and some db&#39;s made it a no go.</p> <p>Thoughts on what I might be doing wrong? /etc/fstab</p> <pre><code>10.23.0.10:/zfs0 /mnt/storage0 nfs defaults 0 0 </code></pre> <p>NFS Export</p> <pre><code>/zfs0 -fsid=20a733cc-5ece-4ff2-b1fe-faa89578ccb8 *(rw,sync,no_subtree_check,no_root_squash) </code></pre> </div><!-- SC_ON -

