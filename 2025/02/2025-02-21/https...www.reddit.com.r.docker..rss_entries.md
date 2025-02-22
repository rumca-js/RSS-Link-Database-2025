# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Good Image for Java/Node?
 - [https://www.reddit.com/r/docker/comments/1iv3gws/good_image_for_javanode](https://www.reddit.com/r/docker/comments/1iv3gws/good_image_for_javanode)
 - RSS feed: $source
 - date published: 2025-02-21T22:20:19+00:00

<!-- SC_OFF --><div class="md"><p>So i&#39;ll preface by saying im newish to docker in general but understand the basics. Essentially I&#39;m wanting to create my own image to allow me to run Allure (It&#39;s a reporting library: <a href="https://allurereport.org/docs/install-for-nodejs/">https://allurereport.org/docs/install-for-nodejs/</a>) on a container and transfer my test results to this image. Right now i&#39;m using a 3rd party one that does way more than necessary.</p> <p>From my understanding i&#39;ll need to (for my dockerfile):</p> <ol> <li>Use some base image (Maybe Alpine?/Ubuntu?)</li> <li>Install Node</li> <li>Install Java (JDK/JRE unsure)</li> <li>Set Java env variable</li> <li>Install the Allure commandline tool above (via npm)</li> <li>copy my &quot;allure-results&quot; test results file in</li> <li>I think that&#39;s it?</li> </ol> <p>Then i&#39;ll just need to set the &quot;script&quot; parameter in my CI file to run the generate thing.</p> <p>Am I missing anythi

## Existing Container Adding USB Access Issue
 - [https://www.reddit.com/r/docker/comments/1iv2ebe/existing_container_adding_usb_access_issue](https://www.reddit.com/r/docker/comments/1iv2ebe/existing_container_adding_usb_access_issue)
 - RSS feed: $source
 - date published: 2025-02-21T21:35:02+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I&#39;ll apologize ahead of time for being a docker beginner. So far though, it has worked great for me in what I need it to do. But now I have slammed into a brick wall and I am humbly asking for help.</p> <p>I created a docker container in WSL2 (WIndows 11) and installed some support in it for coding for the RPI Pico using the Pico-SDK. This approach solved ALL my previous issues and (knock on wood) everything I have thrown at the container setup has built UF2&#39;s as expected. I make frequent experimental updates to my code however and the process of updating my devices is cumbersome. So now that I have a docker container doing what I wanted, FINALLY, I am setting out to automate some of the human interaction needed with the process.</p> <p>I have a little bit of a better understanding on how it all works, starting my container, using EXEC to start an interactive shell into it. It works great, with both via the command line in wind

## How install docker compose on Linux server?
 - [https://www.reddit.com/r/docker/comments/1iv03ec/how_install_docker_compose_on_linux_server](https://www.reddit.com/r/docker/comments/1iv03ec/how_install_docker_compose_on_linux_server)
 - RSS feed: $source
 - date published: 2025-02-21T19:58:59+00:00

<!-- SC_OFF --><div class="md"><p>Let’s look at documentation </p> <p><a href="https://docs.docker.com/compose/install/">https://docs.docker.com/compose/install/</a></p> <p>The recommended option is to install docker desktop. But I’m installing it on server, and do not need gui. I’m not sure if this will not cause problems on servers, particularly with regard to publishing ports and networking. </p> <p>The second option is to install docker compose plugin. But this is for when one has other pieces installed, which I don’t. It’s not even an installation option. </p> <p>The last option is manual. It’s legacy and not recommended. </p> <p>So how do you install docker compose on Linux servers, which is like 95% of cases? </p> <p>Why desktop installation is the recommended option, when the vast majority of containers are server applications? Docker opens ports and bypasses ufw firewall, on servers. Does it behave like this in desktop too? That would be a disaster. </p> </div><!-- SC_ON -->

## Is anyone here able to help create an egg for a Game? (pterodactyl server Hosting)
 - [https://www.reddit.com/r/docker/comments/1iuzfg5/is_anyone_here_able_to_help_create_an_egg_for_a](https://www.reddit.com/r/docker/comments/1iuzfg5/is_anyone_here_able_to_help_create_an_egg_for_a)
 - RSS feed: $source
 - date published: 2025-02-21T19:30:44+00:00

<!-- SC_OFF --><div class="md"><p>The game in question is called DCS (Dynamic Combat Simulator), it&#39;s an awesome flight simulator and I would love to play with my friends but the game only supports server-based multiplayer and I&#39;m not skilled nor smart enough to create an egg for this game so do you think someone could help me out? Thanks! I know this Reddit place thing is probably not the best place to ask but I can&#39;t find any help on either the official Pteradactyl GitHub or Reddit and even the discord and you lot seem very smart </p> <p>Sorry for the trouble</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Constant_Dog_429"> /u/Constant_Dog_429 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iuzfg5/is_anyone_here_able_to_help_create_an_egg_for_a/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iuzfg5/is_anyone_here_able_to_help_create_an_egg_for_a/">[comments]</a></span>

## Docker minimal image sizes for different programming languages
 - [https://www.reddit.com/r/docker/comments/1iuwotd/docker_minimal_image_sizes_for_different](https://www.reddit.com/r/docker/comments/1iuwotd/docker_minimal_image_sizes_for_different)
 - RSS feed: $source
 - date published: 2025-02-21T17:39:27+00:00

<!-- SC_OFF --><div class="md"><p>I implemented a simple JSON API in multiple programming languages. It is interesting to compare the sizes of the resulting Docker images.</p> <p>Optimizing the images can really reduce the sizes, especially for interpreted languages: while you would expect Go and Rust to be small (and they are: 9 MB &amp; 5 MB respectively), Python and PHP are also surprisingly good: 60 MB and 51 MB.</p> <p>Deno, Bun, NodeJS, .Net and Ruby are between 100 and 200 MB.</p> <p>Ruby using bitami:ruby was over 500 MB. Switching to chainguard:ruby brought it down to 124 MB.</p> <p>I haven&#39;t optimized the Swift, Perl, Java &amp; Tcl images which are between 200 and 300 MB.</p> <p><a href="https://andrew.marcuse.info/blog/2025/2025-02-01-docker-image-sizes.html">Detailed results</a></p> <p><a href="https://www.regexplanet.com/status.html">Proof</a> that they actually run and work.</p> <p>Description of <a href="https://github.com/regexplanet/regexplanet-next/blob/main/CO

## Docker not working without sudo
 - [https://www.reddit.com/r/docker/comments/1iuvhux/docker_not_working_without_sudo](https://www.reddit.com/r/docker/comments/1iuvhux/docker_not_working_without_sudo)
 - RSS feed: $source
 - date published: 2025-02-21T16:51:45+00:00

<!-- SC_OFF --><div class="md"><p>I have recently installed docker on my Linux machine. But when I try to run it like <code>docker images</code> it is showing <code>Cannot connect to the Docker daemon. But if run with sudo it is working. Can anyone explain why this is happening. Any solution to this</code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spiritual-Sea-4190"> /u/Spiritual-Sea-4190 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iuvhux/docker_not_working_without_sudo/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iuvhux/docker_not_working_without_sudo/">[comments]</a></span>

## The Best IPTV Services in 2025: Top 5 Ranked
 - [https://www.reddit.com/r/docker/comments/1iusgun/the_best_iptv_services_in_2025_top_5_ranked](https://www.reddit.com/r/docker/comments/1iusgun/the_best_iptv_services_in_2025_top_5_ranked)
 - RSS feed: $source
 - date published: 2025-02-21T14:42:31+00:00

<!-- SC_OFF --><div class="md"><p>With the rise of digital streaming, IPTV services have revolutionized home entertainment, offering thousands of live channels, sports, and movies at unbeatable prices. If you&#39;re looking for the best IPTV provider in 2025, here’s our expert ranking of the <strong>top 5 IPTV services</strong> based on quality, reliability, and affordability.</p> <h1>1. <a href="https://tvworldwide.shop/"><strong>TVWorldwide IPTV</strong></a> – The Ultimate IPTV Experience</h1> <p>TVWorldwide IPTV takes the <strong>#1 spot</strong> as the most reliable and feature-packed IPTV service in 2025. Here’s why:<br/> ✅ <strong>Over 20,000 live channels</strong> from around the world<br/> ✅ <strong>4K and Full HD quality</strong> for a crystal-clear viewing experience<br/> ✅ <strong>Catch-up TV</strong> and a vast VOD library for movies &amp; series<br/> ✅ <strong>Compatible with IBO Player Pro, Shamel TV, Smart TVs, Firestick, and Android devices</strong><br/> ✅ <strong>One

## Help with Failed Portainer Update
 - [https://www.reddit.com/r/docker/comments/1iurtr7/help_with_failed_portainer_update](https://www.reddit.com/r/docker/comments/1iurtr7/help_with_failed_portainer_update)
 - RSS feed: $source
 - date published: 2025-02-21T14:13:17+00:00

<!-- SC_OFF --><div class="md"><p>I tried following the directions to update my Portainer container but messed something up. Everything contained (Channels DVR stacks) in Portainer still works, but I think I accidentally changed the port #. The ports now show up as 8000:8000 and 9443:9443. Its port used to be 9000. While all of my containers in Portainer still work I cannot access the local host anymore. I already had a container on port 8000. It still works but cannot work concurrently with Portainer. I also now have a portainer agent which I did not have before. I&#39;ve followed the instructions on how to change the port # in the terminal, but that does not work. I&#39;m running Docker on an M2 mac mini. Does anyone know a solution? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/jtrippe77"> /u/jtrippe77 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iurtr7/help_with_failed_portainer_update/">[link]</a></span> &#32; <spa

## Docker install commands changed?
 - [https://www.reddit.com/r/docker/comments/1iurrmk/docker_install_commands_changed](https://www.reddit.com/r/docker/comments/1iurrmk/docker_install_commands_changed)
 - RSS feed: $source
 - date published: 2025-02-21T14:10:39+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Just wondering are the old Docker, and Docker-Compose commands still relevant? I see the documentation has been updated, or was this always the case? In terms of installation methods, will the old commands still work?</p> <p>Would appreciate any experienced guidance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/inialation247"> /u/inialation247 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iurrmk/docker_install_commands_changed/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iurrmk/docker_install_commands_changed/">[comments]</a></span>

## Docker containers are bloated. We built a tool for debloating them.
 - [https://www.reddit.com/r/docker/comments/1iumles/docker_containers_are_bloated_we_built_a_tool_for](https://www.reddit.com/r/docker/comments/1iumles/docker_containers_are_bloated_we_built_a_tool_for)
 - RSS feed: $source
 - date published: 2025-02-21T08:59:35+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>We got fedup with the current state of debloating tool (there are multiple academic papers on why they suck), so we build an open-source docker debloating tool. Please try it and give us feedback!</p> <p><a href="https://github.com/negativa-ai/BLAFS">https://github.com/negativa-ai/BLAFS</a> </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Specialist_Square818"> /u/Specialist_Square818 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iumles/docker_containers_are_bloated_we_built_a_tool_for/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iumles/docker_containers_are_bloated_we_built_a_tool_for/">[comments]</a></span>

## can i make a 1.16 minecraft server on papermc?
 - [https://www.reddit.com/r/docker/comments/1iukhfw/can_i_make_a_116_minecraft_server_on_papermc](https://www.reddit.com/r/docker/comments/1iukhfw/can_i_make_a_116_minecraft_server_on_papermc)
 - RSS feed: $source
 - date published: 2025-02-21T06:29:03+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I am trying to make a 1.16 Minecraft server with docker papermc</p> <p>every time i make a server on 1.16, the server crashes and i get.</p> <p>YOU ARE RUNNING AN OUTDATED VERSION OF JAVA. PAPER WILL STOP BEING COMPATIBLE WITH THIS VERSION OF JAVA WHEN MINECRAFT 1.17 IS RELEASED. Please update the version of java you use to run Paper to atleast java 16.</p> <p>since minecaft 1.16 runs on java version 11, does that mean it is impossible to make a server for minecraft 1.16 now?</p> <p>is there any other alternatives i can use other than paperMC?</p> <p>Thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pauleydsweettea"> /u/pauleydsweettea </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iukhfw/can_i_make_a_116_minecraft_server_on_papermc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iukhfw/can_i_make_a_116_minecraft_server_on_papermc/">[comments]</

## Hosting docker
 - [https://www.reddit.com/r/docker/comments/1iui0jn/hosting_docker](https://www.reddit.com/r/docker/comments/1iui0jn/hosting_docker)
 - RSS feed: $source
 - date published: 2025-02-21T04:04:29+00:00

<!-- SC_OFF --><div class="md"><p>Hey, so I do some self hosting however I was wondering is there a platform (similar to Vercel or Render) but that can be used to host and run a docker container for free? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mo_with_the_floof"> /u/mo_with_the_floof </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iui0jn/hosting_docker/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iui0jn/hosting_docker/">[comments]</a></span>

