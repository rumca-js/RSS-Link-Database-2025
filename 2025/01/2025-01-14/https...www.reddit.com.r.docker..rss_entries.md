# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## How can I Deploy a Docker compose container in Google Cloud run?
 - [https://www.reddit.com/r/docker/comments/1i1ip7a/how_can_i_deploy_a_docker_compose_container_in](https://www.reddit.com/r/docker/comments/1i1ip7a/how_can_i_deploy_a_docker_compose_container_in)
 - RSS feed: $source
 - date published: 2025-01-14T22:42:42+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I would like to deploy a docker compose container in cloud run. </p> <p>Essentially, having this container up &amp; running locally on Docker desktop or using an online temporary service like Play With Docker is easy &amp; straightforward. All I have to do is; </p> <ol> <li>Clone the github repo in terminal</li> <li>Create a json file container container volume</li> <li>Use docker compose up to have this container running.</li> </ol> <p>Now, I would like to do the same thing with Cloud run and deploy a docker instance using docker compose. When I search for a solution online, I get conflicting info where some people say &#39;docker compose&#39; isn&#39;t available in cloud while a very other users mention that they&#39;ve been able to use docker compose in cloud run. And this is confusing me. The closest solution I have seen is this; <a href="https://stackoverflow.com/questions/67185073/how-to-run-docker-compose-on-google-cloud-run">https://stack

## Advice for Docker Swarm & traefik
 - [https://www.reddit.com/r/docker/comments/1i1dtl6/advice_for_docker_swarm_traefik](https://www.reddit.com/r/docker/comments/1i1dtl6/advice_for_docker_swarm_traefik)
 - RSS feed: $source
 - date published: 2025-01-14T19:11:55+00:00

<!-- SC_OFF --><div class="md"><p>Ive got just enough knowledge to be dangerous as im sure many others do :) After some advice of how best to achieve my latest goals for the homelab.</p> <p>I currently run NGINX Proxy Manager, i have my domain pointed at home ip and some subdomains. NPM is handling things so far but i know this is far from ideal way of doing things. Having wanted to get some HA for my home services, i decided to setup swarm with 3 nodes. 2 physical servers running 2 nodes and 1 node respectively. Prior to swarm of course each service would only exist once meaning the NPM setup was straightforward.</p> <p>NPM doesnt seem to support load balancing, or at least my attempts have been unsuccessful so thought about moving to Traefik as it seems to fit the job description and goes a bit further. </p> <p>NPM currently runs inside Home Assistant as an Add-On (docker under the hood). If i now look to replace this with Traefik, would i run this in the swarm? I presume il need t

## How to access microphone from docker container?
 - [https://www.reddit.com/r/docker/comments/1i1bmem/how_to_access_microphone_from_docker_container](https://www.reddit.com/r/docker/comments/1i1bmem/how_to_access_microphone_from_docker_container)
 - RSS feed: $source
 - date published: 2025-01-14T17:39:19+00:00

<!-- SC_OFF --><div class="md"><p>I am building real-time speech to text application using openai-whisper. Using PyAudio (in code? and portaudio-19 dev(docker image). When I run the the docker image for /dev/snd it is not working. I have read about pulseaudio. But don&#39;t know what to do. </p> <p>The same code is running locally on my windows machine. I am using WSL2 + Ubuntu-22.0</p> <p>Can anyone please help me out?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/kmeanskaran"> /u/kmeanskaran </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i1bmem/how_to_access_microphone_from_docker_container/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i1bmem/how_to_access_microphone_from_docker_container/">[comments]</a></span>

## can i connect my headless docker to the desktop app
 - [https://www.reddit.com/r/docker/comments/1i1b0wl/can_i_connect_my_headless_docker_to_the_desktop](https://www.reddit.com/r/docker/comments/1i1b0wl/can_i_connect_my_headless_docker_to_the_desktop)
 - RSS feed: $source
 - date published: 2025-01-14T17:14:03+00:00

<!-- SC_OFF --><div class="md"><p>i have tried downloading the docker desktop app on my ubuntu machine and it wont work is this because i already have it headless ? if not can i connect the two ?</p> <p>sorry im very new to this </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Better-Difference134"> /u/Better-Difference134 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i1b0wl/can_i_connect_my_headless_docker_to_the_desktop/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i1b0wl/can_i_connect_my_headless_docker_to_the_desktop/">[comments]</a></span>

## Error response from daemon: all predefined address pools have been fully subnetted
 - [https://www.reddit.com/r/docker/comments/1i1840y/error_response_from_daemon_all_predefined_address](https://www.reddit.com/r/docker/comments/1i1840y/error_response_from_daemon_all_predefined_address)
 - RSS feed: $source
 - date published: 2025-01-14T15:08:30+00:00

<!-- SC_OFF --><div class="md"><p>Soooo, I can only have 32 networks on my docker server before all the address ranges have been exhausted? I&#39;m specifying different stacks to reuse externally configured networks but I don&#39;t want unrelated stacks to be on the same network if I can help it.</p> <p>Is there a way to specify more? I can see that docker is using ranges with /20 and /16, this is way more than my needs. Can I configure docker to use /24 ranges instead? </p> <p>My IP Range at home is <a href="http://192.168.1.0/24">192.168.1.0/24</a> and it&#39;s not using anything in the <a href="http://10.0.0.0/8">10.0.0.0/8</a> range is this because it believes that most host networks will be configured in that range?</p> <p>I&#39;m assuming it&#39;s something to do with this default-address-pools but I&#39;m not sure what to do with it.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ghoarder"> /u/ghoarder </a> <br/> <span><a href="https://w

## Possible to add kernel modules to the VM host for Docker on Mac?
 - [https://www.reddit.com/r/docker/comments/1i17ioo/possible_to_add_kernel_modules_to_the_vm_host_for](https://www.reddit.com/r/docker/comments/1i17ioo/possible_to_add_kernel_modules_to_the_vm_host_for)
 - RSS feed: $source
 - date published: 2025-01-14T14:41:08+00:00

<!-- SC_OFF --><div class="md"><p>Just wanted to have some basic kernel modules in my Docker containers so it becomes a must to have them in the host first.</p> <p>In Docker on Mac, is it possible to add kernel modules, for example br_netfilter, to the underlying VM host?</p> <p>Some experiments to have a look at what modules we have now in the latest Docker Desktop, which is v4.37.2.</p> <p>``` $ docker run -it --rm --privileged --pid=host justincormack/nsenter1 Unable to find image &#39;justincormack/nsenter1:latest&#39; locally latest: Pulling from justincormack/nsenter1 726619a9fa8c: Download complete Digest: sha256:e876f694a4cb6ff9e6861197ea3680fe2e3c5ab773a1e37ca1f13171f7f5798e Status: Downloaded newer image for justincormack/nsenter1:latest</p> <p>~ # cat /etc/os-release PRETTY_NAME=&quot;Docker Desktop&quot;</p> <p>~ # ls /lib/modules 6.10.14-linuxkit fakeowner.ko grpcfuse.ko rosetta.ko selfowner.ko shiftfs.ko</p> <p>~ # ls /lib/modules/6.10.14-linuxkit/ build modules.builtin

## Docker for Mac & Windows
 - [https://www.reddit.com/r/docker/comments/1i175e2/docker_for_mac_windows](https://www.reddit.com/r/docker/comments/1i175e2/docker_for_mac_windows)
 - RSS feed: $source
 - date published: 2025-01-14T14:23:39+00:00

<!-- SC_OFF --><div class="md"><p>Apologies if this sounds naive.</p> <p>Here&#39;s the issue: I&#39;m attempting to run an R script followed by a Python script on a Mac. The challenge arises because R doesn&#39;t support iODBC compiled drivers, while MySQL provides only iODBC drivers for Mac downloads.</p> <p><strong>Scenario:</strong> One developer writes R scripts on Windows, and another wants to run them on a Mac.</p> <p>Would Docker be a suitable solution if both developers use it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/aronianm"> /u/aronianm </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i175e2/docker_for_mac_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i175e2/docker_for_mac_windows/">[comments]</a></span>

## Is it possible to work on a web app across two different devices?
 - [https://www.reddit.com/r/docker/comments/1i16j4a/is_it_possible_to_work_on_a_web_app_across_two](https://www.reddit.com/r/docker/comments/1i16j4a/is_it_possible_to_work_on_a_web_app_across_two)
 - RSS feed: $source
 - date published: 2025-01-14T13:53:31+00:00

<!-- SC_OFF --><div class="md"><p>I’m fairly new to using Docker so please bear with me! I would like to know if it’s possible to work on the same web application across two different devices. I’d like to have access to it on my laptop and on my PC and be able to pick up from where I left off on either of those devices. Is this possible with docker? And if so, could someone please direct me to somewhere that shows me how to do so? Thank you! </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AmyJX612"> /u/AmyJX612 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i16j4a/is_it_possible_to_work_on_a_web_app_across_two/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i16j4a/is_it_possible_to_work_on_a_web_app_across_two/">[comments]</a></span>

## Best practice for populating database
 - [https://www.reddit.com/r/docker/comments/1i107hd/best_practice_for_populating_database](https://www.reddit.com/r/docker/comments/1i107hd/best_practice_for_populating_database)
 - RSS feed: $source
 - date published: 2025-01-14T06:47:34+00:00

<!-- SC_OFF --><div class="md"><p>I have a Flask rest API and a Postgres database both running on separate docker containers, and I want there to be some initial data in the database for the API (not dummy data for testing). This data will come from a Python program.</p> <p>Would this be better to do this as a startup script in the database container and have the Flask container wait on it, or should I have the Python script insert using the Flask API?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/OkInflation5"> /u/OkInflation5 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i107hd/best_practice_for_populating_database/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i107hd/best_practice_for_populating_database/">[comments]</a></span>

## How is startup order handled in Swarm (depends_on)?
 - [https://www.reddit.com/r/docker/comments/1i0wd39/how_is_startup_order_handled_in_swarm_depends_on](https://www.reddit.com/r/docker/comments/1i0wd39/how_is_startup_order_handled_in_swarm_depends_on)
 - RSS feed: $source
 - date published: 2025-01-14T03:00:26+00:00

<!-- SC_OFF --><div class="md"><p>Compose uses <code>depends_on</code> to order stack startup and shutdown to make sure multi-service stacks have the services start in the correct order (for example, proxy, cache, and database all being up and healthy before starting the web service). <code>depends_on</code> was apparently never implemented for Swarm. Swarm just starts all services and makes sure they are replicated up to the replicated limit number. How are services that rely on multiple other services in a stack reliably started on Swarm when using <code>docker stack deploy --compose-file</code>?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pugglewugglez"> /u/pugglewugglez </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i0wd39/how_is_startup_order_handled_in_swarm_depends_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i0wd39/how_is_startup_order_handled_in_swarm_depends_on/">[commen

## Docker dañará tu computadora.
 - [https://www.reddit.com/r/docker/comments/1i0v0i3/docker_dañará_tu_computadora](https://www.reddit.com/r/docker/comments/1i0v0i3/docker_dañará_tu_computadora)
 - RSS feed: $source
 - date published: 2025-01-14T01:52:33+00:00

<!-- SC_OFF --><div class="md"><p>Hola! Hace tiempo instalé Docker en mi MacOS y de un tiempo para acá me apareció el siguiente error ¿alguien sabe cómo lo puedo solucionar?<br/> Aparece un mensaje con cabecera &quot;Docker dañará tu computadora. Deberías de moverlo al basurero&quot; y cuando le doy click a &quot;Mover al basurero&quot; vuelve a aparecer el mensaje</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/WitnessElectronic593"> /u/WitnessElectronic593 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1i0v0i3/docker_dañará_tu_computadora/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1i0v0i3/docker_dañará_tu_computadora/">[comments]</a></span>

## Plex on Docker Container (WSL) slower than Windows Plex Media Server
 - [https://www.reddit.com/r/docker/comments/1i0t9f8/plex_on_docker_container_wsl_slower_than_windows](https://www.reddit.com/r/docker/comments/1i0t9f8/plex_on_docker_container_wsl_slower_than_windows)
 - RSS feed: $source
 - date published: 2025-01-14T00:28:27+00:00

<!-- SC_OFF --><div class="md"><p>Hi All,</p> <p>I recently managed to set up a Docker Container instance for Plex (via WSL + Docker Desktop on Windows PC).</p> <p>When I attempt to stream videos from the Docker Container Plex instance over LAN to my LG smart TV, I get a pop up message on the screen:</p> <p><em>Checking connection speed to [server]</em></p> <p>The video just sits there loading and does not play.</p> <p>The Docker Container&#39;s network setup is in bridged mode.</p> <p>I&#39;ve noticed that when I run Plex on the same host hardware (Windows Desktop running Plex Media Server), the media playback is seamless.</p> <p>Note:</p> <p>I have passthrough to my NVidia GPU enabled on the docker container using these in the compose:<br/> - NVIDIA_VISIBLE_DEVICES=all - NVIDIA_DRIVER_CAPABILITIES=all</p> <p>So I don&#39;t think its an issue with transcoding (issue is also identical whether the video is 4k or 480p).</p> <p>My Plex Config is stored on the host hardware, not on an NF

