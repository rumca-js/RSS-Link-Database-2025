# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## dhcpcd Memory leak with SSH connection open
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvud6t/dhcpcd_memory_leak_with_ssh_connection_open](https://www.reddit.com/r/raspberry_pi/comments/1hvud6t/dhcpcd_memory_leak_with_ssh_connection_open)
 - RSS feed: $source
 - date published: 2025-01-07T15:49:36+00:00

<!-- SC_OFF --><div class="md"><p>I have an issue where dhcpcd memory keeps increasing with an ssh connection open until it runs out of memory and then the kernal shuts it down.</p> <p>Not sure why. I increrased swap memory, but that just made it go from 1 day to a week or so before it crashes.</p> <pre><code>[1443083.606896] lowmem_reserve[]: 0 0 0 0 [1443083.606928] DMA: 641*4kB (UMEHC) 360*8kB (UMEHC) 251*16kB (UMEH) 117*32kB (UMEH) 56*64kB (UMEH) 20*128kB (UMEH) 6*256kB (UH) 1*512kB (M) 0*1024kB 0*2048kB 0*4096kB = 21396kB [1443083.607052] HighMem: 260*4kB (UM) 40*8kB (UM) 11*16kB (U) 4*32kB (U) 6*64kB (U) 0*128kB 0*256kB 0*512kB 0*1024kB 0*2048kB 0*4096kB = 2048kB [1443083.607150] 1558 total pagecache pages [1443083.607158] 106 pages in swap cache [1443083.607165] Swap cache stats: add 267649, delete 267542, find 1206769768/1206772230 [1443083.607171] Free swap = 0kB [1443083.607177] Total swap = 1048572kB [1443083.607183] 242688 pages RAM [1443083.607189] 46080 pages HighMem/Mo

## Issue with using ILI9488 with RPi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvrxzs/issue_with_using_ili9488_with_rpi_5](https://www.reddit.com/r/raspberry_pi/comments/1hvrxzs/issue_with_using_ili9488_with_rpi_5)
 - RSS feed: $source
 - date published: 2025-01-07T13:55:54+00:00

<!-- SC_OFF --><div class="md"><p>I have been trying to connect an ILI9488 touchscreen module to my RPi 5 so that I can use it for a project. This is the exact one I&#39;m using <a href="https://www.amazon.ae/dp/B0CGH9SBRP?social_share=cm_sw_r_cp_ud_dp_D58NWG0XT5CX0KTPRSMN&amp;_encoding=UTF8&amp;psc=1&amp;newOGT=1">https://www.amazon.ae/dp/B0CGH9SBRP?social_share=cm_sw_r_cp_ud_dp_D58NWG0XT5CX0KTPRSMN&amp;_encoding=UTF8&amp;psc=1&amp;newOGT=1</a> . I followed this script <a href="https://github.com/adamomd/ILI9488RPIScript">https://github.com/adamomd/ILI9488RPIScript</a> and executed all the commands on here to install the drivers. However, now my RPi 5 still won&#39;t use the display as it only shows a blank white screen. When I connect it via HDMI to a monitor, the Raspberry Pi OS welcome screen shows up and lingers for about a minute and then the screen just goes black. The RPi 5 still receives power and isn&#39;t broken so I am confused about what is happening. How do I fix this?<

## Car ignition triggered graceful shutdown
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvqjtp/car_ignition_triggered_graceful_shutdown](https://www.reddit.com/r/raspberry_pi/comments/1hvqjtp/car_ignition_triggered_graceful_shutdown)
 - RSS feed: $source
 - date published: 2025-01-07T12:40:25+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hvqjtp/car_ignition_triggered_graceful_shutdown/"> <img src="https://b.thumbs.redditmedia.com/_L4IEEdtiBuIE8fmjwrRaLtau5NXoMTLPPh4gzh0YMc.jpg" alt="Car ignition triggered graceful shutdown" title="Car ignition triggered graceful shutdown" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey guys,</p> <p>I&#39;m trying to achieve a graceful shutdown of my PiDash triggered by cutting off ignition (IGN) power.</p> <p>The plan is to use a timer relais which gets 12V continuous power and 12V switched power as a signal. It outputs power to a buck converter powering the Pi. The switched power also triggers a relais pulling a GPIO low when the ignition is turned off.</p> <p>With the help of a skript running on the Pi I&#39;d like to monitor the pinstate and when it goes low trigger a delayed graceful shutdown while the timer relais keeps the power up.</p> <p>Would following schematic work for that? Can I keep the GP

## Ethernet not working on custom RPI CM4 carrier
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvpnyu/ethernet_not_working_on_custom_rpi_cm4_carrier](https://www.reddit.com/r/raspberry_pi/comments/1hvpnyu/ethernet_not_working_on_custom_rpi_cm4_carrier)
 - RSS feed: $source
 - date published: 2025-01-07T11:46:46+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hvpnyu/ethernet_not_working_on_custom_rpi_cm4_carrier/"> <img src="https://b.thumbs.redditmedia.com/ZdhmF6BCjkBLu6lFQpQ5zUkcgUMczfPA-DJoI19VbQI.jpg" alt="Ethernet not working on custom RPI CM4 carrier" title="Ethernet not working on custom RPI CM4 carrier" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Designed a custom carrier for the RPI CM4. Need DSI, Ethernet and some GPIO. DSI display and GPIO are all working well. Ethernet is not even showing up in the OS. The same CM4 module works as expected on the official CM4 IO board. Parts of the schematics and PCB layout are attached below. I would appreciate any help to debug the issue. Posted on the RPI forum a couple of weeks ago with no response so far. </p> <p><a href="https://preview.redd.it/gosv7xxz6kbe1.png?width=1317&amp;format=png&amp;auto=webp&amp;s=0562f993e448dc4f784b69b0d2675030c5935491">PoE is not conected right now. Just want the ethernet to be

## Snapd failed snapd.socket issue on a Raspberry Pi movel B Rev 2
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvlmjt/snapd_failed_snapdsocket_issue_on_a_raspberry_pi](https://www.reddit.com/r/raspberry_pi/comments/1hvlmjt/snapd_failed_snapdsocket_issue_on_a_raspberry_pi)
 - RSS feed: $source
 - date published: 2025-01-07T06:47:22+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hvlmjt/snapd_failed_snapdsocket_issue_on_a_raspberry_pi/"> <img src="https://b.thumbs.redditmedia.com/NrSjktjyyG3ItmJMN0eOVlk-usI7iE8Vgjcq6rHBcWo.jpg" alt="Snapd failed snapd.socket issue on a Raspberry Pi movel B Rev 2" title="Snapd failed snapd.socket issue on a Raspberry Pi movel B Rev 2" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/n1soqoxtpibe1.png?width=924&amp;format=png&amp;auto=webp&amp;s=9bd81162195faa3fc5205cfac1b5e231a43d9f01">https://preview.redd.it/n1soqoxtpibe1.png?width=924&amp;format=png&amp;auto=webp&amp;s=9bd81162195faa3fc5205cfac1b5e231a43d9f01</a></p> <p>As the heading says, I am getting a snapd error. I have an old Raspberry Pi which I wanted to setup as a headless server for my in home stuff. I was able to install the Pi OS and enabled ssh to the Pi. However, snapd is not working. </p> <p>I have tried purging and installing snapd - that did not work

## Have I damaged my Pi?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvlhef/have_i_damaged_my_pi](https://www.reddit.com/r/raspberry_pi/comments/1hvlhef/have_i_damaged_my_pi)
 - RSS feed: $source
 - date published: 2025-01-07T06:37:16+00:00

<!-- SC_OFF --><div class="md"><p>When I SSH into my Pi Zero 2 W (retropie), I get a message with a bunch of info about the Pi&#39;s status, such as temperature, number of running processes, etc. Among these I get &quot;Memory.............: 62740kB (Free) / 243560kB (Total)&quot; — the total memory is almost half the 512MB that the Pi should have. Have I damaged the device&#39;s memory or is there a more plausible explanation?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Site8330"> /u/No-Site8330 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hvlhef/have_i_damaged_my_pi/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hvlhef/have_i_damaged_my_pi/">[comments]</a></span>

## Fresh OS install on RPi 3B giving input/output error?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hvkugk/fresh_os_install_on_rpi_3b_giving_inputoutput](https://www.reddit.com/r/raspberry_pi/comments/1hvkugk/fresh_os_install_on_rpi_3b_giving_inputoutput)
 - RSS feed: $source
 - date published: 2025-01-07T05:56:05+00:00

<!-- SC_OFF --><div class="md"><p>I got a fresh OS install using Raspberry Pi Imager onto a SD card. Chose 64-bit Lite version, and after booting up. I login and run</p> <p><code>sudo apt update</code></p> <p>followed by</p> <p><code>sudo apt full-upgrade</code></p> <p>and get the following error:</p> <p><code>Preparing to unpack .../19-raspberrypi-sys-mods_20241202_arm64.deb ...</code></p> <p><code>Unpacking raspberrypi-sys-mods (20241202) over (20241111) ...</code></p> <p><code>dpkg: error processing archive /tmp/apt-dpkg-install-ZrdXPm/19-raspberrypi-sys-mods_20241202_arm64.deb (--unpack):</code></p> <p><code>unable to stat &#39;./var/lib/polkit-1/localauthority/10-vendor.d/55-storage.pkla&#39; (which was about to be installed): Input</code></p> <p><code>/output error</code></p> <p><code>dpkg: error while cleaning up:</code></p> <p><code>unable to remove backup copy of &#39;/usr/share/initramfs-tools/scripts/local-premount/firstboot&#39;: Read-only file system</code></p> <p><code>

## 2025 Jan 6 Stickied -FAQ- & -HELPDESK- thread - Boot problems? Power supply problems? Display problems? Networking problems? Need ideas? Get help with these and other questions!
 - [https://www.reddit.com/r/raspberry_pi/comments/1hved4c/2025_jan_6_stickied_faq_helpdesk_thread_boot](https://www.reddit.com/r/raspberry_pi/comments/1hved4c/2025_jan_6_stickied_faq_helpdesk_thread_boot)
 - RSS feed: $source
 - date published: 2025-01-07T00:19:28+00:00

<!-- SC_OFF --><div class="md"><h3><a href="http://f2z.net/RPi-Helpdesk-FAQ.png">Welcome to the r/raspberry_pi Helpdesk and Frequently Asked Questions!</a></h3> <p><a href="https://www.reddit.com/r/raspberry_pi/comments/1hq03ii/2024_dec_30_stickied_faq_helpdesk_thread_boot/">Link to last week&#39;s thread</a></p> <p>Having a hard time searching for answers to your Raspberry Pi questions? Let the <a href="/r/raspberry_pi">r/raspberry_pi</a> community members search for answers <em>for you</em>!<sup>†</sup> Looking for help getting started with a project? Have a question that you need answered? Was it not answered last week? Did not get a satisfying answer? A question that you&#39;ve only done basic research for? Maybe something you think everyone but you knows? <strong>Ask your question in the comments on this page,</strong> operators are standing by!</p> <p>This helpdesk and idea thread is here so that the front page won&#39;t be filled with these same questions day in and day out:</

