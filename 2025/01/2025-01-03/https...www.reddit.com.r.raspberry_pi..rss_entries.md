# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## NTSC drive access for nextcloud manager
 - [https://www.reddit.com/r/raspberry_pi/comments/1hsymnm/ntsc_drive_access_for_nextcloud_manager](https://www.reddit.com/r/raspberry_pi/comments/1hsymnm/ntsc_drive_access_for_nextcloud_manager)
 - RSS feed: $source
 - date published: 2025-01-03T22:13:06+00:00

<!-- SC_OFF --><div class="md"><p>I am attempting to setup a nextcloud manager on my pi5. Nextcloud is installed but the www-data user cannot write to the ntsc drive. I have been trying to edit the permissions but I can’t. I have tried editing the jstab file. I have tried adding udev rules. I am trying to manually mount with ntsc-3g but it always gets over ridden by fuseblk and set to root access. I do not know what else to try. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/pensulpusher"> /u/pensulpusher </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hsymnm/ntsc_drive_access_for_nextcloud_manager/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hsymnm/ntsc_drive_access_for_nextcloud_manager/">[comments]</a></span>

## Is there a way to install Node.js on Raspberry PI Zero V1? (ARMV6)
 - [https://www.reddit.com/r/raspberry_pi/comments/1hsm5f9/is_there_a_way_to_install_nodejs_on_raspberry_pi](https://www.reddit.com/r/raspberry_pi/comments/1hsm5f9/is_there_a_way_to_install_nodejs_on_raspberry_pi)
 - RSS feed: $source
 - date published: 2025-01-03T13:11:41+00:00

<!-- SC_OFF --><div class="md"><p>I know how to install nodejs, and I was able to install it on the raspi, but got an <code>Illegal Instruction</code> error, most likely because the distribution is only for ARMV7. I am now trying to compile it directly on the raspi, but this has a few problems. First, I will also have to compile <code>npm</code>, but more importantly, just <code>git clone</code> on that repo took 30 minutes so far. The compilation could take many hours.</p> <p>So I was wondering if I missed something. Or if someone has an idea on compiling both node and npm on some other machine. Anything I found on the internet was either outdated or &quot;just do <code>apt-get install</code>&quot; which I already tried.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MXXIV666"> /u/MXXIV666 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hsm5f9/is_there_a_way_to_install_nodejs_on_raspberry_pi/">[link]</a></span> &#32; 

## Pi zero 2W and bluetooth dongle
 - [https://www.reddit.com/r/raspberry_pi/comments/1hslaqh/pi_zero_2w_and_bluetooth_dongle](https://www.reddit.com/r/raspberry_pi/comments/1hslaqh/pi_zero_2w_and_bluetooth_dongle)
 - RSS feed: $source
 - date published: 2025-01-03T12:22:14+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>Probably a stupid question, but...</p> <p>The Pi Zero 2 W only has one usb port, when connecting a bluetooth dongle, I have one question :</p> <p>For example, I connect a bluetooth dongle and start up the Pi Zero 2 W, with for example Batocera installed. How am I supposed to connect anything to it ? Because to be able to connect anything through bluetooth, you would have to go into the bluetooth menu. And with the bluetooth dongle connected, it overwrites/disables the internal bluetooth, so any controller working with the internal bluetooth before connecting the dongle wouldn&#39;t work anymore with the dongle connected.</p> <p>So how can this dongle be used ?</p> <p>Thanks in advance. Greetings, Soxbrother</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Soxbrother"> /u/Soxbrother </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hslaqh/pi_zero_2w_and_bluetooth_dongle/">[lin

## Issue With SSH Over USB On CM5
 - [https://www.reddit.com/r/raspberry_pi/comments/1hsjyod/issue_with_ssh_over_usb_on_cm5](https://www.reddit.com/r/raspberry_pi/comments/1hsjyod/issue_with_ssh_over_usb_on_cm5)
 - RSS feed: $source
 - date published: 2025-01-03T10:57:10+00:00

<!-- SC_OFF --><div class="md"><p>For context to this question, I am using the <a href="https://www.raspberrypi.com/products/compute-module-5/?variant=cm5-104032">CM5 Compute Module</a> and the <a href="https://www.raspberrypi.com/products/compute-module-5-io-board/">CM5 IO board</a> running the <a href="https://www.raspberrypi.com/software/operating-systems/">latest 64-bit version of Bookworm</a>.</p> <p>I have looked over a bunch of guides, and the common theme is that to enable SSH over USB, you need to update both the <em>config.txt</em> file, and the <em>cmdline.txt</em> file, as mentioned in the guide below:</p> <p><a href="https://artivis.github.io/post/2020/pi-zero/">https://artivis.github.io/post/2020/pi-zero/</a></p> <p>As such, I have updated both files, which can be found below for reference.</p> <p><strong>config.txt</strong></p> <pre><code># For more options and information see # http://rptl.io/configtxt # Some settings may impact device functionality. See link above fo

## Raspberry Pi Cluster
 - [https://www.reddit.com/r/raspberry_pi/comments/1hsd8f9/raspberry_pi_cluster](https://www.reddit.com/r/raspberry_pi/comments/1hsd8f9/raspberry_pi_cluster)
 - RSS feed: $source
 - date published: 2025-01-03T03:42:07+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I&#39;m about to build a raspberry pi cluster. As of right now, the plan is to have 2-3 Raspberry Pi Zero 2Ws and 1 Raspberry Pi 5. My main dilemma is whether or not I should get 4GB of RAM or 8GB. The cluster will be used for the following:</p> <ol> <li>Learning how to make a case for the cluster (I&#39;m super excited for this part)</li> <li>PiHole</li> <li>Discord bot(s)</li> <li>Self hosted webserver</li> <li>Linux VMs to mess around in (strong MAYBE)</li> <li>NAS (don&#39;t really need it, nice to have)</li> </ol> <p>As of right now, the plan is to have 1 of the Pi zeros acting as a master node. That will be running a web server of sorts that will routinely monitor the other PIs, making sure they&#39;re online, and will be managing things inside the case as well such as a fan and a status display. The remaining worker nodes (1-2 zeros and 1 pi 5) will be used to make sure the discord bot(s) don&#39;t go down (my friends like to spam a lot...

## My Pi Zero 2 W LCD Info-Center Frame
 - [https://www.reddit.com/r/raspberry_pi/comments/1hs98d7/my_pi_zero_2_w_lcd_infocenter_frame](https://www.reddit.com/r/raspberry_pi/comments/1hs98d7/my_pi_zero_2_w_lcd_infocenter_frame)
 - RSS feed: $source
 - date published: 2025-01-03T00:29:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hs98d7/my_pi_zero_2_w_lcd_infocenter_frame/"> <img src="https://b.thumbs.redditmedia.com/LKT5Z44NRGiHwnvHwl_2QDkpx-Zb5-1h6bEH3JrVPyU.jpg" alt="My Pi Zero 2 W LCD Info-Center Frame" title="My Pi Zero 2 W LCD Info-Center Frame" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Here is a good project with no barrier to entry. No special tools needed, don&#39;t need to be a modder or programmer. Only $30 to get a Zero 2, i2c LCD screen and a shadow box frame. IMO a great way to get into learning coding though. More details on my blog, as well as the python code used <a href="https://lostgeek.net/piframe.html">https://lostgeek.net/piframe.html</a></p> <p>What do you guys think?</p> <p><a href="https://preview.redd.it/z63xki1lboae1.jpg?width=1024&amp;format=pjpg&amp;auto=webp&amp;s=6db5f06a0671407f06b491219562fd7d4e1a98f4">https://preview.redd.it/z63xki1lboae1.jpg?width=1024&amp;format=pjpg&amp;auto=webp&amp;s=6db5

