# Source:Docker: An open source project to pack, ship and run any application as a lightweight container, URL:https://www.reddit.com/r/docker/.rss, language:en

## Understanding Users, Permissions, and Namespaces in Rootful vs. Rootless Docker
 - [https://www.reddit.com/r/docker/comments/1iijk0t/understanding_users_permissions_and_namespaces_in](https://www.reddit.com/r/docker/comments/1iijk0t/understanding_users_permissions_and_namespaces_in)
 - RSS feed: $source
 - date published: 2025-02-05T20:12:23+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m working on a problem where a rootful Docker setup with a bind-mounted directory causes permission issues for a non-root user in the container. I think I understand why—since the user in the container simply doesn’t have the right permissions to modify files in the mounted path.</p> <p>However, when using a named volume instead of a bind mount, the non-root user <em>does</em> have permission. I assume this is because the volume is created with permissions that allow access, but I’d love a clearer explanation.</p> <p>Beyond this, I want to fully understand the different configurations:</p> <ul> <li>Rootful Docker with a root vs. non-root user</li> <li>Rootless Docker</li> <li>User namespaces: I’ve read that you need to enable them, but this confuses me because I thought Docker already relies on namespaces for user isolation. If they need to be explicitly enabled, what changes? Are there different configurations I need to understand depending on

## Something is causing my one HDD to constantly be busy and can't format it, "Error unmounting /dev/sdb1: target is busy (udisks-error-quark 14)" (Ubuntu/Docker)
 - [https://www.reddit.com/r/docker/comments/1iiga6m/something_is_causing_my_one_hdd_to_constantly_be](https://www.reddit.com/r/docker/comments/1iiga6m/something_is_causing_my_one_hdd_to_constantly_be)
 - RSS feed: $source
 - date published: 2025-02-05T18:00:51+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/TopdeckTom"> /u/TopdeckTom </a> <br/> <span><a href="/r/linux4noobs/comments/1iifosm/something_is_causing_my_one_hdd_to_constantly_be/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iiga6m/something_is_causing_my_one_hdd_to_constantly_be/">[comments]</a></span>

## Best IPTV Services of 2024: Top Trusted Providers: Reddit
 - [https://www.reddit.com/r/docker/comments/1iidn80/best_iptv_services_of_2024_top_trusted_providers](https://www.reddit.com/r/docker/comments/1iidn80/best_iptv_services_of_2024_top_trusted_providers)
 - RSS feed: $source
 - date published: 2025-02-05T16:13:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/docker/comments/1iidn80/best_iptv_services_of_2024_top_trusted_providers/"> <img src="https://external-preview.redd.it/cO4V034GhyAs9HV0ncuafvn3yzkaSJDiPrJ5Dq6HRV8.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d54687e53d792f3f62fe278db8568a795b72c869" alt="Best IPTV Services of 2024: Top Trusted Providers: Reddit" title="Best IPTV Services of 2024: Top Trusted Providers: Reddit" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/DeviceAfectionate"> /u/DeviceAfectionate </a> <br/> <span><a href="/r/IPTVPlay/comments/1gkaxo1/best_iptv_services_of_2024_top_trusted_providers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1iidn80/best_iptv_services_of_2024_top_trusted_providers/">[comments]</a></span> </td></tr></table>

## Rust web server does not work
 - [https://www.reddit.com/r/docker/comments/1ii7i2i/rust_web_server_does_not_work](https://www.reddit.com/r/docker/comments/1ii7i2i/rust_web_server_does_not_work)
 - RSS feed: $source
 - date published: 2025-02-05T10:59:22+00:00

<!-- SC_OFF --><div class="md"><p>So I am following the last chapter in the <a href="https://doc.rust-lang.org/book/ch20-01-single-threaded.html">Rust Programming Language tutorial</a> and i wanted to try out using Docker. But when trying to connect to the server it says &quot;127.0.0.1 refused to connect&quot;. My code can be found here: <a href="https://github.com/ViktorPopp/RustWebServer/tree/docker">ViktorPopp/RustWebServer - Docker</a>.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ViktorPoppDev"> /u/ViktorPoppDev </a> <br/> <span><a href="https://www.reddit.com/r/docker/comments/1ii7i2i/rust_web_server_does_not_work/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ii7i2i/rust_web_server_does_not_work/">[comments]</a></span>

## Squirrel Servers Manager, the solution to manage your containers & servers, now agentless!
 - [https://www.reddit.com/r/docker/comments/1ii6zot/squirrel_servers_manager_the_solution_to_manage](https://www.reddit.com/r/docker/comments/1ii6zot/squirrel_servers_manager_the_solution_to_manage)
 - RSS feed: $source
 - date published: 2025-02-05T10:20:20+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m thrilled to announce a major milestone for the next version of <a href="https://squirrelserversmanager.io/">Squirrel Server Manager </a><strong>(SSM)</strong>: it will be <strong>100% agentless</strong>!</p> <h1>What’s Changing?</h1> <p>Since day one, SSM has relied on installing an agent on each of your devices to retrieve statistics and information. That’s about to change. With the upcoming version, everything will work seamlessly over <strong>SSH</strong>—no need for agents anymore! This means setup will be <em>simpler</em>, <em>cleaner</em>, and <em>less resource-intensive</em>, all while remaining completely transparent.</p> <p>And that’s not all...</p> <h1>Key Enhancements</h1> <ol> <li><strong>Prometheus Integration</strong> The internal database for statistics has been replaced with <strong>Prometheus</strong>, the standard for storing and processing metrics. This will bring <strong>reliability, scalability, and advanc

## How to use Burpsuite with a docker container?
 - [https://www.reddit.com/r/docker/comments/1ii6ovg/how_to_use_burpsuite_with_a_docker_container](https://www.reddit.com/r/docker/comments/1ii6ovg/how_to_use_burpsuite_with_a_docker_container)
 - RSS feed: $source
 - date published: 2025-02-05T09:57:55+00:00

<!-- SC_OFF --><div class="md"><p>I have a docker container, and I need to use burpsuite proxy as the address for my docker containers proxy. </p> <p>I have tried setting the container to port 8080 and burp to 8081, and I set the container to use the proxy address `-e HTTP_PROXY=<a href="http://127.0.0.7:8081%5C%60">http://127.0.0.7:8081\`</a>. </p> <p>My browser uses the burpsuite proxy, so to my understanding the issue is either how burpsuite connects to the container, or how the container is connecting to burpsuite? </p> <p>I can connect to the container in my browser at localhost:8080, but no traffic is intercepted by the proxy (the container uses http). Not sure what the error is in the configuration. </p> <p>Any help is appreciated. What steps can I take to troubleshoot? Not sure if I am missing something super basic or not. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/IndividualSyllabub52"> /u/IndividualSyllabub52 </a> <br/> <span><a 

## nginx-proxy or vps network problem setting up webserver
 - [https://www.reddit.com/r/docker/comments/1ii30cl/nginxproxy_or_vps_network_problem_setting_up](https://www.reddit.com/r/docker/comments/1ii30cl/nginxproxy_or_vps_network_problem_setting_up)
 - RSS feed: $source
 - date published: 2025-02-05T05:31:18+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m way over my head. I have a VPS running on IONOS. I am trying to setup mysql-apache2-wordpress server using docker compose yaml file examples I found online. This works perfectly until I try to add https support through nginx-proxy. The working yaml lets me setup wordpress just fine. Here&#39;s the working yaml without nginx-proxy</p> <pre><code>services: db: image: mysql:9.1.0 restart: always environment: MYSQL_ROOT_PASSWORD: ${MYSQL_ROOT_PASSWORD} MYSQL_DATABASE: ${MYSQL_DATABASE} MYSQL_USER: ${MYSQL_USER} MYSQL_PASSWORD: ${MYSQL_PASSWORD} volumes: - mysql:/var/lib/mysql wordpress: depends_on: - db image: wordpress:6-php8.1-apache restart: always ports: - &quot;80:80&quot; environment: WORDPRESS_DB_HOST: db:3306 WORDPRESS_DB_USER: ${MYSQL_USER} WORDPRESS_DB_PASSWORD: ${MYSQL_PASSWORD} WORDPRESS_DB_NAME: ${MYSQL_DATABASE} volumes: - &quot;./:/var/www/html&quot; phpmyadmin: image: phpmyadmin/phpmyadmin:5 restart: always ports: - &quot;8080:80&

## Best IPTV Services of 2024: Top Trusted Providers: Reddit
 - [https://www.reddit.com/r/docker/comments/1ii1ihm/best_iptv_services_of_2024_top_trusted_providers](https://www.reddit.com/r/docker/comments/1ii1ihm/best_iptv_services_of_2024_top_trusted_providers)
 - RSS feed: $source
 - date published: 2025-02-05T04:04:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/docker/comments/1ii1ihm/best_iptv_services_of_2024_top_trusted_providers/"> <img src="https://external-preview.redd.it/cO4V034GhyAs9HV0ncuafvn3yzkaSJDiPrJ5Dq6HRV8.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=d54687e53d792f3f62fe278db8568a795b72c869" alt="Best IPTV Services of 2024: Top Trusted Providers: Reddit" title="Best IPTV Services of 2024: Top Trusted Providers: Reddit" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/meow_meow_meow2024"> /u/meow_meow_meow2024 </a> <br/> <span><a href="/r/IPTVPlay/comments/1gkaxo1/best_iptv_services_of_2024_top_trusted_providers/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ii1ihm/best_iptv_services_of_2024_top_trusted_providers/">[comments]</a></span> </td></tr></table>

## How can I initialize lower-case-table-names in the docker version of mysql?
 - [https://www.reddit.com/r/docker/comments/1ii18df/how_can_i_initialize_lowercasetablenames_in_the](https://www.reddit.com/r/docker/comments/1ii18df/how_can_i_initialize_lowercasetablenames_in_the)
 - RSS feed: $source
 - date published: 2025-02-05T03:49:31+00:00

<!-- SC_OFF --><div class="md"><p>I would like to initialize the lower-case-table-names to 1 when using mysql:8.4. Any help will be much appreciated.</p> <p>This is not an issue when using the non-docker version. I can just set the parameter in my.cnf and everything works.</p> <p>However, in the docker version, if I add the line &#39;lower-case-table-names=1&#39; in the /etc/my.cnf and restart the mysql server, the process will fail due to the following error.</p> <pre><code>Different lower_case_table_names settings for server (&#39;1&#39;) and data dictionary (&#39;0&#39;). </code></pre> <p>Then, I created a new folder /temp/docker and execute: </p> <p>docker run -v /temp/docker:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=MyPswd mysql:8.4 --initialize --lower_case_table_names=1</p> <p>The process also failed after complaining (the full output is attached at the end of this post):</p> <pre><code>--initialize specified but the data directory has files in it. Aborting. </code></pre> <p>What 

## The Best IPTV Providers Services | IPTVSMARTECH.COM - reddit
 - [https://www.reddit.com/r/docker/comments/1ii0dn5/the_best_iptv_providers_services_iptvsmartechcom](https://www.reddit.com/r/docker/comments/1ii0dn5/the_best_iptv_providers_services_iptvsmartechcom)
 - RSS feed: $source
 - date published: 2025-02-05T03:04:40+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/docker/comments/1ii0dn5/the_best_iptv_providers_services_iptvsmartechcom/"> <img src="https://b.thumbs.redditmedia.com/ky42WU2kpLwCHuAI92V1BZ68fBEeqrQbRVgV_T-n1vc.jpg" alt="The Best IPTV Providers Services | IPTVSMARTECH.COM - reddit" title="The Best IPTV Providers Services | IPTVSMARTECH.COM - reddit" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Least-Prompt-2199"> /u/Least-Prompt-2199 </a> <br/> <span><a href="/r/TvUserEnthusiasm/comments/1i3ms99/the_best_iptv_providers_services_iptvsmartechcom/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/docker/comments/1ii0dn5/the_best_iptv_providers_services_iptvsmartechcom/">[comments]</a></span> </td></tr></table>

