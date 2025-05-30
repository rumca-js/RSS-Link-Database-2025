# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## AdGuard Home in Docker Compose keeps resetting to First-Time Setup after Restart – Losing Settings
 - [https://www.reddit.com/r/docker/comments/1iowaah/adguard_home_in_docker_compose_keeps_resetting_to](https://www.reddit.com/r/docker/comments/1iowaah/adguard_home_in_docker_compose_keeps_resetting_to)
 - RSS feed: $source
 - date published: 2025-02-13T23:05:16+00:00

<!-- SC_OFF --><div class="md"><p><strong>My Setup:</strong></p> <p>• <strong>Platform:</strong> Raspberry Pi 4, Debian (aarch64)</p> <p>• <strong>AdGuard Home Image:</strong> adguard/adguardhome:latest</p> <p><strong>• Docker Compose Config:</strong></p> <pre><code>adguardhome: image: adguard/adguardhome:latest container_name: adguardhome restart: unless-stopped network_mode: &quot;host&quot; volumes: - ./config/adguard/conf:/opt/adguardhome/conf - ./config/adguard/work:/opt/adguardhome/work environment: - TZ=Australia/Sydney cap_add: - NET_ADMIN command: [&quot;--web-addr&quot;, &quot;0.0.0.0:8083&quot;] </code></pre> <p><strong>Directory Structure:</strong></p> <pre><code>docker-compose/ └── config/ └── adguard/ ├── conf/ │ └── AdGuardHome.yaml └── work/ └── data/ └── sessions.db </code></pre> <p><strong>Permissions Set:</strong></p> <pre><code>sudo chown -R 1000:1000 ~/docker-compose/config/adguard sudo chmod -R 700 ~/docker-compose/config/adguard </code></pre> <p>Also set 700 in

## Docker takes up 1.1 TB of storage on Mac
 - [https://www.reddit.com/r/docker/comments/1iotce4/docker_takes_up_11_tb_of_storage_on_mac](https://www.reddit.com/r/docker/comments/1iotce4/docker_takes_up_11_tb_of_storage_on_mac)
 - RSS feed: $source
 - date published: 2025-02-13T20:56:34+00:00

<!-- SC_OFF --><div class="md"><p>has any one ever faced this issue before? i&#39;m only using docker for work.<br/> can&#39;t upload an image for some reason otherwise i would have included it.<br/> thanks in advance</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Nourrrrrrr"> /u/Nourrrrrrr </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iotce4/docker_takes_up_11_tb_of_storage_on_mac/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iotce4/docker_takes_up_11_tb_of_storage_on_mac/">[comments]</a></span>

## Docker uid gid user is failing to execute py file
 - [https://www.reddit.com/r/docker/comments/1ios8dw/docker_uid_gid_user_is_failing_to_execute_py_file](https://www.reddit.com/r/docker/comments/1ios8dw/docker_uid_gid_user_is_failing_to_execute_py_file)
 - RSS feed: $source
 - date published: 2025-02-13T20:08:37+00:00

<!-- SC_OFF --><div class="md"><p>I am running a docker container and it is only executing the python file if I am root. I have changed permissions for my RUNID user. Which is the id from user data and the id from group data_sync. I set rwx on data and data_sync</p> <p>My docker-compose.yml file</p> <pre><code>services: find_file ...... user: ${RUNID} </code></pre> <p>Dockerfile</p> <pre><code>.... COPY app_data/ /app-data/src/ CMD python3 /app-data/src/file.py .... USER root </code></pre> <p>Run. sh file</p> <pre><code>start container.sh setfacl -m u:data:rw /path to file setfacl -m g:data_sync:r /path to file export RUNID=$(id -u data):$(id -g data_sync) </code></pre> <p>I have given the user and group rwx but I am still getting permission denied</p> <p><code>python3 can&#39;t open file /app-data/src/file.py</code></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pythondev1"> /u/pythondev1 </a> <br/> <span><a href="https://www.reddit.com/r/dock

## [BUG] docker-entrypoint.sh: Permission denied
 - [https://www.reddit.com/r/docker/comments/1iortox/bug_dockerentrypointsh_permission_denied](https://www.reddit.com/r/docker/comments/1iortox/bug_dockerentrypointsh_permission_denied)
 - RSS feed: $source
 - date published: 2025-02-13T19:51:22+00:00

<!-- SC_OFF --><div class="md"><p>Newbie here! I have some problems with mounting the code in a volume. I&#39;m trying to do this to avoid rebuilding the image whenever I change something in the code.</p> <p>The structure of the project (with Django backend) is like this: </p> <p>todo<br/> - backend:<br/> -- backend (essential project files):<br/> -- tasks (tasks app):<br/> -- (Other apps)<br/> -- docker-entrypoint.sh<br/> -- Dockerfile<br/> -- wait-for-it.sh (script for waiting the db to be ready before the backend service starts)<br/> -- manage.py (essential file for django commands)<br/> -- requirements.txt<br/> - frontend:<br/> -- (Empty for now)<br/> - docker-compose.yml</p> <p>I have this Dockerfile: ```</p> <h1>Use a valid Python version</h1> <p>FROM python:3.11-slim</p> <h1>Set environment variables</h1> <p>ENV PYTHONDONTWRITEBYTECODE=1 \ PYTHONUNBUFFERED=1</p> <h1>Set working directory</h1> <p>WORKDIR /app</p> <h1>Install system dependencies</h1> <p>RUN apt-get update &amp;&

## Best IPTV Providers for 2024 – Top IPTV Services You Should Try! 4KIPTVSpot Best IPTV Provider
 - [https://www.reddit.com/r/docker/comments/1ioqeyh/best_iptv_providers_for_2024_top_iptv_services](https://www.reddit.com/r/docker/comments/1ioqeyh/best_iptv_providers_for_2024_top_iptv_services)
 - RSS feed: $source
 - date published: 2025-02-13T18:52:34+00:00

<!-- SC_OFF --><div class="md"><h1>Best IPTV Providers for 2024 – Top IPTV Services You Should Try!</h1> <p>Finding a <strong>reliable IPTV provider</strong> can be challenging with so many options out there. If you&#39;re looking for <strong>high-quality HD &amp; 4K streaming, global channels, and affordable plans</strong>, I highly recommend these three top-tier IPTV services:</p> <p>🔥 <strong>4KIPTVSpot</strong> – One of the best IPTV providers for sports lovers and entertainment fans, offering premium sports channels, movies, and international content.<br/> 🔥 <strong>Xtreme HD IPT</strong>V – A high-performance IPTV service with a vast selection of channels from the USA, Canada, UK, Europe, Asia, and the Arab world.<br/> 🔥 <strong>4K Live IPTV</strong> – A top IPTV provider known for its ultra-fast servers, massive VOD library, and 24/7 stable streaming with no buffering.</p> <p>These <strong>IPTV services</strong> deliver a seamless viewing experience, covering a wide range of l

## Cheap place to host docker container API with GPU?
 - [https://www.reddit.com/r/docker/comments/1ioq2m2/cheap_place_to_host_docker_container_api_with_gpu](https://www.reddit.com/r/docker/comments/1ioq2m2/cheap_place_to_host_docker_container_api_with_gpu)
 - RSS feed: $source
 - date published: 2025-02-13T18:38:08+00:00

<!-- SC_OFF --><div class="md"><p>Hi! I have an API setup in python with uvicorn and an AI RAG pipeline, and it&#39;s currently hosted on Oracle with the free tier of 4 vCPU&#39;s and 24 GB RAM. I use Mistral-7B and save embeddings inside of a pkl file hosted within the container, and it works but it&#39;s incredibly slow. I was considering building a GPU-based server, but I&#39;m not sure if that would need a lot of VRAM vs. RAM and whether it would support multiple requests at the same time. Are there any inexpensive places that offer GPU-supported cloud hosting? It takes about 3-4 minutes to generate a response for one request in my current application, and I hopefully want to cut it down to sub-30 sec. Thank you!</p> <p>Here&#39;s the code if anyone wants to view:</p> <p>Dockerfile: <a href="https://pastebin.com/70948Dem">https://pastebin.com/70948Dem</a></p> <p>Main.py: <a href="https://pastebin.com/GdEN5aRe">https://pastebin.com/GdEN5aRe</a></p> </div><!-- SC_ON --> &#32; submi

## Connect to GPT agent using Docker
 - [https://www.reddit.com/r/docker/comments/1ion05b/connect_to_gpt_agent_using_docker](https://www.reddit.com/r/docker/comments/1ion05b/connect_to_gpt_agent_using_docker)
 - RSS feed: $source
 - date published: 2025-02-13T16:29:41+00:00

<!-- SC_OFF --><div class="md"><p>Due to the sensitivity of information, my company&#39;s policy prohibits the use of LLMs (Large Language Models), and they are all blocked on my work network. However, I would like to use them for my hobbies. I am allowed to use my work laptop for personal use.</p> <p>How can I connect to GPT chat agents, like Claude, via my home server? I am not interested in running a local model and prefer not to use a full-fledged OS like Windows or Linux. I want the solution to be as lightweight as possible. Additionally, it is important that I can use the agents for free, so many APIs are not an option. My home server runs on Proxmox with Docker installed.</p> <p>I am looking for methods that allow me to bypass the company restrictions while keeping the setup minimal and efficient. Any suggestions on how to achieve this would be greatly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/blu3sh4rk"> /u/blu3sh4rk <

## Career Switch from Finance to DevOps – Need Advice on Certs & Job Strategy
 - [https://www.reddit.com/r/docker/comments/1ioilej/career_switch_from_finance_to_devops_need_advice](https://www.reddit.com/r/docker/comments/1ioilej/career_switch_from_finance_to_devops_need_advice)
 - RSS feed: $source
 - date published: 2025-02-13T13:04:40+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I have 10 years of experience in Finance and currently work as a Country CFO, but I don’t like my job. I’ve decided to switch to DevOps because I see huge potential in cloud technology, and I want the flexibility to work from anywhere—or even start my own consulting business in a few years.</p> <p>I completed a 6-month DevOps bootcamp and then started working on certifications to prove my skills to recruiters and ensure I’m ready for the career switch. My plan was:</p> <p>• DCA (Docker Certified Associate) → To validate containerization knowledge • CKA (Certified Kubernetes Administrator) → To demonstrate orchestration expertise • Terraform Associate → To showcase provisioning and automation skills</p> <p>However, after extensively studying for the DCA, I failed it. The exam was nothing like I expected—80% was about Kubernetes (which I wasn’t ready for), and the rest focused on Docker’s enterprise products rather than practical Do

## Configure Prestashop with Docker and Git
 - [https://www.reddit.com/r/docker/comments/1iof88n/configure_prestashop_with_docker_and_git](https://www.reddit.com/r/docker/comments/1iof88n/configure_prestashop_with_docker_and_git)
 - RSS feed: $source
 - date published: 2025-02-13T09:17:55+00:00

<!-- SC_OFF --><div class="md"><p>Hello!</p> <p>I&#39;m trying to create a local environment to work with Prestashop + Docker + Git, since I usually create and modify modules, themes and override files. I followed the steps in the official documentation <a href="https://devdocs.prestashop-project.org/8/basics/installation/environments/docker/">https://devdocs.prestashop-project.org/8/basics/installation/environments/docker/</a> and I&#39;m using Windows with WSL2.</p> <p>The steps I followed are the following:</p> <ol> <li>I created the docker-compose.yml, using the most recent version of Prestashop as an image, as indicated in the Presta documentation, creating a file like this:version:</li> </ol> <p><code>yml version: &#39;3&#39; services: mysql: container_name: some-mysql image: mysql:5.7 restart: unless-stopped environment: MYSQL_ROOT_PASSWORD: admin MYSQL_DATABASE: prestashop networks: - prestashop_network prestashop: container_name: prestashop image: prestashop/prestashop:lates

## Here's the Fastest Way to Get an IPTV Free Trial (Just 20 Seconds!)"
 - [https://www.reddit.com/r/docker/comments/1iodoge/heres_the_fastest_way_to_get_an_iptv_free_trial](https://www.reddit.com/r/docker/comments/1iodoge/heres_the_fastest_way_to_get_an_iptv_free_trial)
 - RSS feed: $source
 - date published: 2025-02-13T07:19:10+00:00

<!-- SC_OFF --><div class="md"><p>Been searching for a <strong>free IPTV trial</strong> with no strings attached? I found one that delivers <strong>instant access—no credit card, no delays</strong>. Just enter your email, and in <strong>20 seconds</strong>, you’ll have your trial in your inbox!</p> <p>I tested it myself, and the <strong>streaming quality is excellent</strong>—crystal-clear, no buffering, and super smooth. Setup was effortless, and I was watching in minutes.</p> <p>If you’ve been thinking about trying IPTV or just want to test a solid service before committing, now’s your chance!</p> <p>✅ <strong>Enter your email address</strong><br/> ✅ <strong>Check your inbox (SPAM Sometimes)</strong> —your free trial arrives in <strong>20 seconds!</strong></p> <p>🔥 <strong>Claim your free trial now:</strong> MetaIPTVPro .com</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Standard_Salary_5197"> /u/Standard_Salary_5197 </a> <br/> <span><a href=

## Best practice for background tasks
 - [https://www.reddit.com/r/docker/comments/1iod1gd/best_practice_for_background_tasks](https://www.reddit.com/r/docker/comments/1iod1gd/best_practice_for_background_tasks)
 - RSS feed: $source
 - date published: 2025-02-13T06:33:42+00:00

<!-- SC_OFF --><div class="md"><p>Hello I am relatively new to docker in production and am having a hard time wrapping my head around this architectural decision. I am dockerizing a large legacy Django app that has a number of background Django commands it runs. One such command is a “data binning” service that creates rolling bins. It’s currently a well constructed Django command but it runs as a supervisor subtask in our current monolith deployment. How do I correctly dockerize something like this that needs access to both the main Django container and a DB? It needs the models from Django and writes to my DB. Just wondering what best practice here would be? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/tking13"> /u/tking13 </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1iod1gd/best_practice_for_background_tasks/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iod1gd/best_practice_for_ba

## Docker Desktop fills up my drive while starting for the first time
 - [https://www.reddit.com/r/docker/comments/1io9way/docker_desktop_fills_up_my_drive_while_starting](https://www.reddit.com/r/docker/comments/1io9way/docker_desktop_fills_up_my_drive_while_starting)
 - RSS feed: $source
 - date published: 2025-02-13T03:25:07+00:00

<!-- SC_OFF --><div class="md"><p>Docker newbie here, running Linux Mint 22.1. I went through the tutorials and got Docker installed. When I launch Docker Desktop it churns and churns until I get an error &quot;Cannot resize &quot;/home/david/.docker/desktop/vms/0/data/Docker.raw&quot; to 218000MiB: truncate /home/david/.docker/desktop/vms/0/data/Docker.raw: no space left on device&quot;. The OS will also tell me that the drive is now full. I have been searching online for a fix, but I am not finding anything that fits my situation. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/davidsinnergeek"> /u/davidsinnergeek </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1io9way/docker_desktop_fills_up_my_drive_while_starting/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1io9way/docker_desktop_fills_up_my_drive_while_starting/">[comments]</a></span>

## For God's Sake, I can't seem to configure VSCode Dev Container
 - [https://www.reddit.com/r/docker/comments/1io7ixh/for_gods_sake_i_cant_seem_to_configure_vscode_dev](https://www.reddit.com/r/docker/comments/1io7ixh/for_gods_sake_i_cant_seem_to_configure_vscode_dev)
 - RSS feed: $source
 - date published: 2025-02-13T01:23:46+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying to configure VS Code Dev Container for the past 5 hours but it just doesn&#39;t work.</p> <p>I want to run a multi service container, Node and Postgre for now and install over node_modules in the container.</p> <p>It fails because npm install cannot find a package.json file. The error logs are in the comments</p> <p>Here is my implementation:</p> <p>devcontainer.json</p> <pre><code>{ &quot;dockerComposeFile&quot;: &quot;docker-compose.yml&quot;, &quot;service&quot;: &quot;devcontainer&quot;, &quot;workspaceFolder&quot;: &quot;/workspace&quot;, &quot;forwardPorts&quot;: [3000, 5432] } </code></pre> <p>docker-compose.yml</p> <pre><code>version: &#39;3.8&#39; services: devcontainer: build: context: . dockerfile: Dockerfile volumes: - ..:/workspace command: sleep infinity network_mode: service:db db: image: postgres:latest restart: unless-stopped volumes: - postgres-data:/var/lib/postgresql/data environment: POSTGRES_PASSWORD: postgres

## I'm trying to run a docker container (gabotechs/musicgpt) but in the end it gives me this error "ERROR No space left on device (os error 28)"
 - [https://www.reddit.com/r/docker/comments/1io7gpn/im_trying_to_run_a_docker_container](https://www.reddit.com/r/docker/comments/1io7gpn/im_trying_to_run_a_docker_container)
 - RSS feed: $source
 - date published: 2025-02-13T01:20:43+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m trying to download a github repository (docker pull gabotechs/musicgpt) and running it (docker run -it --gpus all -p 8642:8642 -v ~/.musicgpt:/root/.local/share/musicgpt gabotechs/musicgpt --gpu --ui-expose), but in the process it downloads some libraries, it does it with ease, but then when It tries to download the AI models it needs, the terminal throws this error at me and I don&#39;t know what to do: ERROR No space left on device (os error 28)</p> <p>FULL LOG: <a href="https://pastebin.com/x8q9zcZ8">https://pastebin.com/x8q9zcZ8</a></p> <p>And sorry if I don&#39;t use correct terminology, I don&#39;t know what I&#39;m doing and I want to use this as a personal project</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/G1erBvn"> /u/G1erBvn </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1io7gpn/im_trying_to_run_a_docker_container/">[link]</a></span> &#32; <span><a href="https://www.red

