# Source:Linux, GNU/Linux, free software..., URL:https://www.reddit.com/r/linux/.rss, language:en

## Nvidia 565 / KDE Neon / Optimus laptop - Finally working with Wayland.
 - [https://www.reddit.com/r/linux/comments/1hs6595/nvidia_565_kde_neon_optimus_laptop_finally](https://www.reddit.com/r/linux/comments/1hs6595/nvidia_565_kde_neon_optimus_laptop_finally)
 - RSS feed: $source
 - date published: 2025-01-02T22:15:52+00:00

<!-- SC_OFF --><div class="md"><ul> <li>KDE neon 6.2</li> <li>Dell Precision 5550</li> <li>Kernel 6.8.0-51-generic</li> <li>Plasma 6.2.4</li> <li>Intel CometLake-H GT2 UHD Graphics</li> <li>Nvidia Quadro T1000 Mobile</li> <li>Ubuntu PPA nvidia-driver-565</li> <li>Grub: GRUB_CMDLINE_LINUX_DEFAULT=&quot;loglevel=3 i915.modeset=1 nvidia-drm.modeset=1 nvidia-drm.fbdev=1 nvidia.NVreg_EnableGpuFirm ware=0&quot; </li> <li>/etc/modprobe.d/nvidia-graphics-drivers-kms.conf: options nvidia-drm modeset=1</li> </ul> <p>- SDDM without tweaks to /etc/sddm.conf finally working<br/> - Wayland session finally working - Just moments ago, no ideas what issues I may find yet.<br/> - X11 session broke - Plasma loads, black screens, but can generate some artifacts using meta key to pop up the menu, or alt-f2 and starting a shell. I&#39;ll tackle this next sometime, probably when something forces me to x11 for some reason.<br/> - No HDMI audio showing up, but had this issue before the nvidia driver attempt 

## feasibility of running your main desktop OS off of an external SSD?
 - [https://www.reddit.com/r/linux/comments/1hs5auc/feasibility_of_running_your_main_desktop_os_off](https://www.reddit.com/r/linux/comments/1hs5auc/feasibility_of_running_your_main_desktop_os_off)
 - RSS feed: $source
 - date published: 2025-01-02T21:40:57+00:00

<!-- SC_OFF --><div class="md"><p>So, I&#39;m in a situation where I kind of want to have two different machines.</p> <p>One stable and more minimal machine which I can use for uni, and one more experimental machine, potentially running a less stable OS which I use for my home situation.</p> <p>This, both due to the storage requirements of both my home usage and my uni usage (I can certainly manage, but it would be a nice bonus), but more importantly to separate the two spaces digitally, which would hopefully make it easier to keep the two separated for me.</p> <p>Now I do not currently have the money to spend on a second machine, but I do have enough money to spend on an external SSD, so I was wondering as to the feasibility of running a main OS (on which I would like to be able to, for example, game and such) off of an external SSD.<br/> I don&#39;t think that total read write speeds would be an issue, lowest ones I&#39;m currently looking at is 800 MB/s up and down, though I am af

## My first month of daily driving linux
 - [https://www.reddit.com/r/linux/comments/1hs4xp5/my_first_month_of_daily_driving_linux](https://www.reddit.com/r/linux/comments/1hs4xp5/my_first_month_of_daily_driving_linux)
 - RSS feed: $source
 - date published: 2025-01-02T21:25:56+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone. I have been a big linux enthusiast for about a year. I installed it on a few old laptops to save it from the trash and had a lot of fun to play around with. My daily driver is PC and I installed linux on there after I bought a new ssd for it. First I used linux mint but had problems with vr and stuff so I later went to arch btw. My experience is better than Windows. In games especially. People say Nvidia is shit on linux but I&#39;ve never had screen tearing compared to windows (where it was a huge problem) vr also has been no problem using ALVR on my quest 2. I have a few problems like davinci resolve not working but I am keeping linux so far and am not thinking about going back. This has been the most fun using my pc in years. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/CodeEgg08"> /u/CodeEgg08 </a> <br/> <span><a href="https://i.redd.it/wh077sanenae1.png">[link]</a></span> &#32; <span><a hre

## Self-hosted IRC Network with AI Bot, built on headless Ubuntu server in the living room
 - [https://www.reddit.com/r/linux/comments/1hs2qrv/selfhosted_irc_network_with_ai_bot_built_on](https://www.reddit.com/r/linux/comments/1hs2qrv/selfhosted_irc_network_with_ai_bot_built_on)
 - RSS feed: $source
 - date published: 2025-01-02T19:56:19+00:00

<!-- SC_OFF --><div class="md"><p>Wanted to share a project that brings together the classic IRC protocol with modern AI capabilities, all running on headless Ubuntu server in my living room :)</p> <p>It&#39;s based on:</p> <p>- UnrealIRCd 6 server with Anope Services</p> <p>- Python-based AI bots using modern libraries</p> <p>- Full SSL/TLS support with Let&#39;s Encrypt</p> <p>- Privacy-focused design</p> <p>The Bot Stack:</p> <p>- MistralBot: AI assistant using the Mistral API</p> <p>- WeatherBot: Weather info via Open-Meteo</p> <p>- SearchBot: Private web search using Hearch API</p> <p>Everything is FOSS and runs beautifully on Linux. All bots are written in Python 3 with standard libraries plus requests/ssl. The entire stack is lightweight and can run on modest hardware.</p> <p>Check out the source, I still have to add the SearchBot : <a href="https://github.com/MansionNET">https://github.com/MansionNET</a></p> <p>If any Linux users want to try it out, DM me for server details. 

## DE setup for laypeople serving home media (host) and as a game server (client)
 - [https://www.reddit.com/r/linux/comments/1hs288u/de_setup_for_laypeople_serving_home_media_host](https://www.reddit.com/r/linux/comments/1hs288u/de_setup_for_laypeople_serving_home_media_host)
 - RSS feed: $source
 - date published: 2025-01-02T19:35:19+00:00

<!-- SC_OFF --><div class="md"><p>Hello All!</p> <p>I am currently running a headless debian server, however the need to use a desktop environment has arisen!</p> <p>I am looking for recommendations for a desktop environment similar to that found on a smart tv. </p> <p>- The main use case will be to access local services and specific websites e.g. netflix/jellyfin/youtube but also bare metal software such as steam as I&#39;m planning on using this to do steam link with my gaming desktop (The gpu in the server is just there for transcoding and very small llm applications).</p> <p>- It needs to be controllable by a remote, ideally designed with remote use in mind e.g. PS/xbox remote</p> <p>- User access/control needs to be extremely limited, I don&#39;t want anyone capable of accessing system level settings, files etc... The only access should be through my portainer instance, sftp containers, and ssh. The people using this are not capable of using anything more complex than an apple o

## Marvel Rivals is Banning Mac OS Users
 - [https://www.reddit.com/r/linux/comments/1hs1gk2/marvel_rivals_is_banning_mac_os_users](https://www.reddit.com/r/linux/comments/1hs1gk2/marvel_rivals_is_banning_mac_os_users)
 - RSS feed: $source
 - date published: 2025-01-02T19:04:22+00:00

<!-- SC_OFF --><div class="md"><p>Hello <a href="/r/Linux">r/Linux</a> reaching out to hopefully spread some information regarding Marvel Rivals. </p> <p>Currently a huge ban wave has affected the <a href="/r/macgaming">r/macgaming</a> community and I am reaching out to spread/share the situation. </p> <p>Players who use Crossover Preview to play the game are being affected with a 100 year ban. Even if the player never played a single online game (happened to myself).</p> <p>You can preview how to emulate the game on Mac here: <a href="https://www.youtube.com/watch?v=IMR31cFbyj4">https://www.youtube.com/watch?v=IMR31cFbyj4</a></p> <p>You can follow the thread here: <a href="https://www.reddit.com/r/macgaming/comments/1hrsitf/marvel_rivals_banning_mac_os_users/">https://www.reddit.com/r/macgaming/comments/1hrsitf/marvel_rivals_banning_mac_os_users/</a></p> <p>I hope just sharing this and spreading some awareness can help Marvel Rivals revert this automated ban. Especially with the sev

## Do we consider desktop UI at a good point? I'm not talking about underlying tech like compositing but the UI itself.
 - [https://www.reddit.com/r/linux/comments/1hs19yo/do_we_consider_desktop_ui_at_a_good_point_im_not](https://www.reddit.com/r/linux/comments/1hs19yo/do_we_consider_desktop_ui_at_a_good_point_im_not)
 - RSS feed: $source
 - date published: 2025-01-02T18:57:02+00:00

<!-- SC_OFF --><div class="md"><p>Myself, I use KDE and pleased, so I hope it doesn&#39;t change much any time soon like Windows did to make me move away from it. Windows 11 UI tried to over-simplify so much that it made things harder. For instance, just to extract a file it went from just right-click---&gt;extract to requiring two menus for such a simple thing. And the taskbar, it went from being able to be moved anywhere to being stuck on bottom. I know, there&#39;s mods you can do but I was already doing enough to change Windows 11 to my liking. Please tell me KDE won&#39;t be doing such a thing because I&#39;ve grown to love it and hope it stays that way. </p> <p>And before you recommend Gnome, last time I used it, it was so &quot;simplified&quot; that to just create a text file I had to create another file in some folder somewhere to allow me to create text files. I&#39;ve been in tech 20 years and I had to google how to create a text file, fsmh.</p> </div><!-- SC_ON --> &#32; s

## Why is this necessary
 - [https://www.reddit.com/r/linux/comments/1hrzfch/why_is_this_necessary](https://www.reddit.com/r/linux/comments/1hrzfch/why_is_this_necessary)
 - RSS feed: $source
 - date published: 2025-01-02T17:42:02+00:00

<!-- SC_OFF --><div class="md"><p>I never understood the need for ai social media and other gimmicks to be integrated into an os, especially a linux distro. This gives a strong windows vibe. Also wtf is an anti woke ai</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/fishcat404"> /u/fishcat404 </a> <br/> <span><a href="https://i.redd.it/lp5hc87pamae1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrzfch/why_is_this_necessary/">[comments]</a></span>

## Ubuntu Server with ZFS – 'Failed to import pool 'rpool'' after installation
 - [https://www.reddit.com/r/linux/comments/1hrsy1d/ubuntu_server_with_zfs_failed_to_import_pool](https://www.reddit.com/r/linux/comments/1hrsy1d/ubuntu_server_with_zfs_failed_to_import_pool)
 - RSS feed: $source
 - date published: 2025-01-02T12:48:26+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone,</p> <p>I’m trying to create an automated Ubuntu Server installation with ZFS on a fresh disk using <code>autoinstall.yaml</code>, but I’m encountering a problem I can’t solve. Here’s my current <code>autoinstall.yaml</code> file, with passwords, late commands, and hostname removed:</p> <pre><code>#cloud-config autoinstall: version: 1 locale: en_US.UTF-8 identity: username: ubuntu realname: ubuntu storage: config: - grub_device: true id: disk1 name: main_disk ptable: gpt type: disk device: sda wipe: zero preserve: false - device: disk1 id: disk1p1 number: 1 size: 9G type: partition - device: disk1 flag: bios_grub id: bios_boot number: 2 size: 1M type: partition - id: disk1_rootpool mountpoint: none pool: rpool type: zpool vdevs: - disk1p1 - id: disk1_rootpool_container pool: disk1_rootpool properties: canmount: &#39;off&#39; mountpoint: &#39;none&#39; type: zfs volume: /ROOT - id: disk1_rootpool_rootfs pool: disk1_rootpool properties: can

## Generic configuration GUI
 - [https://www.reddit.com/r/linux/comments/1hrspgv/generic_configuration_gui](https://www.reddit.com/r/linux/comments/1hrspgv/generic_configuration_gui)
 - RSS feed: $source
 - date published: 2025-01-02T12:34:17+00:00

<!-- SC_OFF --><div class="md"><p>Hi friends, I have a FOSS project idea and want to ask if it already exists.</p> <p>Like probably many of you, I&#39;m comfortable editing text-based configuration files. However, other people would prefer a GUI. The reason many programs use text-based configuration (in my opinion) is because its easier to implement and developers generally tend to be more comfortable with it anyway. FOSS developers are less motivated to spend more of their free time implementing a configuration method they don&#39;t even prefer themselves.</p> <p>My idea is this: We now have things like <a href="https://json-schema.org/">JSON schema</a>. These schemas can often even be generated from source code, so there is very little effort for developers to provide JSON schemas for their app configuration. A generic configuration GUI would then take 2 inputs: the location of the config file and the JSON schema. From that, it would render a GUI that allows editing the configurati

## Linux stats on Steam
 - [https://www.reddit.com/r/linux/comments/1hrrp9w/linux_stats_on_steam](https://www.reddit.com/r/linux/comments/1hrrp9w/linux_stats_on_steam)
 - RSS feed: $source
 - date published: 2025-01-02T11:29:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gurugabrielpradipaka"> /u/gurugabrielpradipaka </a> <br/> <span><a href="https://www.phoronix.com/news/Steam-Survey-December-2024">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrrp9w/linux_stats_on_steam/">[comments]</a></span>

## EWW (Need Help)
 - [https://www.reddit.com/r/linux/comments/1hrrbgd/eww_need_help](https://www.reddit.com/r/linux/comments/1hrrbgd/eww_need_help)
 - RSS feed: $source
 - date published: 2025-01-02T11:03:35+00:00

<!-- SC_OFF --><div class="md"><p>Below Contains in Order:<br/> - Widget<br/> - Window (Widget and Window are together)<br/> - Bashscript<br/> - Output of the bashscript which you can copy and paste into the widget section and pass it into window<br/> - Variable that contains the bashscript output </p> <p>I can&#39;t figure this out for the life of me. It&#39;s supposed to dynamically make buttons based on how many bluetooth devices available. </p> <p>```<br/> (defwidget test []</p> <p>(box :class &quot;container_bluetooth&quot; :orientation &quot;v&quot; :space-evenly &quot;true&quot;</p> <p>;; Labels Box</p> <p>(box :class &quot;container_labels&quot; :orientation &quot;h&quot; :space-evenly &quot;false&quot;</p> <p>(button :class &quot;label_devices&quot; :style &quot;font-size: 15px; padding-left: 0px&quot; :onclick &quot;&quot; &quot;Devices&quot;)</p> <p>(button :class &quot;label_options&quot; :style &quot;font-size: 15px; padding-left: 0px&quot; :onclick &quot;&quot; &quot;Op

## Another "Linux-y" tale of "Micro-soft" madness...
 - [https://www.reddit.com/r/linux/comments/1hrqqg3/another_linuxy_tale_of_microsoft_madness](https://www.reddit.com/r/linux/comments/1hrqqg3/another_linuxy_tale_of_microsoft_madness)
 - RSS feed: $source
 - date published: 2025-01-02T10:21:01+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/BulkyMix6581"> /u/BulkyMix6581 </a> <br/> <span><a href="/r/linuxmint/comments/1hrpw6s/another_linuxy_tale_of_microsoft_madness/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrqqg3/another_linuxy_tale_of_microsoft_madness/">[comments]</a></span>

## Numpad auto repeat key in Linux
 - [https://www.reddit.com/r/linux/comments/1hrqqby/numpad_auto_repeat_key_in_linux](https://www.reddit.com/r/linux/comments/1hrqqby/numpad_auto_repeat_key_in_linux)
 - RSS feed: $source
 - date published: 2025-01-02T10:20:46+00:00

<!-- SC_OFF --><div class="md"><p>Happy holidays everyone. I wondering if there is a way to mimic/replicate, in Linux, the numpad auto repeat key feature of Windows. This is quite useful in gaming. It reduces the chance of repeative stress injury such as carpel tunnel, reduces wear and tear on keyboards, and cuts down on the amount of noise generated by heavy click keyboards.</p> <p>Here is how it works. In a video game&#39;s settings, the user maps the 0 to 9 keys on the numpad to match the same keybinds of the numerical keys above the standard finger positions on the keyboard. Once the user is playing the actual game, the following is done: * turn off numlock * hold down one or more numpad keys (ex: numpad 2 and 4) * while still holding the numpad keys, tap numlock to turn it on * release the held numpad keys</p> <p>The matching numerical keys will fire and be interpreted by the game as the user pressing those numerical keys above &quot;q,w,e,r,t,y,u,i,o,p&quot;. The keyboard repea

## mcfetch - ufetch with custom color options
 - [https://www.reddit.com/r/linux/comments/1hrqj50/mcfetch_ufetch_with_custom_color_options](https://www.reddit.com/r/linux/comments/1hrqj50/mcfetch_ufetch_with_custom_color_options)
 - RSS feed: $source
 - date published: 2025-01-02T10:06:06+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/forvirringssirkel"> /u/forvirringssirkel </a> <br/> <span><a href="https://github.com/dybdeskarphet/mcfetch">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrqj50/mcfetch_ufetch_with_custom_color_options/">[comments]</a></span>

## KDE Plasma 6.2.5, Bugfix Release for December
 - [https://www.reddit.com/r/linux/comments/1hrpjwb/kde_plasma_625_bugfix_release_for_december](https://www.reddit.com/r/linux/comments/1hrpjwb/kde_plasma_625_bugfix_release_for_december)
 - RSS feed: $source
 - date published: 2025-01-02T08:52:19+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gabriel_3"> /u/gabriel_3 </a> <br/> <span><a href="https://kde.org/announcements/plasma/6/6.2.5/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrpjwb/kde_plasma_625_bugfix_release_for_december/">[comments]</a></span>

## Want to move on from Garuda linux, and try new distro
 - [https://www.reddit.com/r/linux/comments/1hro414/want_to_move_on_from_garuda_linux_and_try_new](https://www.reddit.com/r/linux/comments/1hro414/want_to_move_on_from_garuda_linux_and_try_new)
 - RSS feed: $source
 - date published: 2025-01-02T07:06:41+00:00

<!-- SC_OFF --><div class="md"><p>I have been using Garuda linux from past 2 years, after one of my seniors installed it for me, I love the aesthetics and features it offers, mainly</p> <ul> <li>Snapper tools for snapshots</li> <li>KDE tools mainly KDE Connect</li> <li>The various animations and customization</li> </ul> <p>It is built on top of arch, and its mainly for beginners, but now I want to try out different distros just so that I am sure that I am not missing any other better distro (ofcourse there are better ones which exists)</p> <p>Also I want to get down into the rabbit hole of linux, learn and experiment more and more things, as I love to try things and learn by breaking things (again a reason why I love the snapshots)</p> <p>I need suggestions from this subreddit on what distro should I switch to and give a try.</p> <p>P.S. I am a software developer, working on the web mainly and sometimes mobile.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.re

## dos to linux
 - [https://www.reddit.com/r/linux/comments/1hrnnpb/dos_to_linux](https://www.reddit.com/r/linux/comments/1hrnnpb/dos_to_linux)
 - RSS feed: $source
 - date published: 2025-01-02T06:35:54+00:00

<!-- SC_OFF --><div class="md"><p>My journey from DOS to Linux!</p> <p>Yes I am that young :D</p> <p>And today is my Birthday! </p> <p>I wrote my master’s thesis on my university’s brand new DOS computer with a green screen and a printer that made more noise than a truck.</p> <p>Went through all of Windows, from 3. to win10, except vista off coarse.</p> <p>My favorites were 7 and XP. Then everything went downhill.</p> <p>A week into win11 I realized how much I am fed up with this s**t. f**k w*d*s.</p> <p>I will miss photoshop and lightroom though.</p> <p>The big switch was to Linux Mint, on a dual boot, because I was scared to death from the terminal.</p> <p>After exploring tty I realized that I can fix things as much as I can f**k up other things (never did rm -rf / though haha!). </p> <p>So I started my new journey in installing and fixing things (especially nvidia) with the terminal and very basic bash scripting.</p> <p>From mint went on to Ubuntu for 2 months (didn’t like it, rem

## running a distro virtualized with native performance including audio and video?
 - [https://www.reddit.com/r/linux/comments/1hrlsxz/running_a_distro_virtualized_with_native](https://www.reddit.com/r/linux/comments/1hrlsxz/running_a_distro_virtualized_with_native)
 - RSS feed: $source
 - date published: 2025-01-02T04:40:50+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m wanting to try out a few different distros on my current linux (tumbleweed) install as the host. Instead of dealing with dual booting I was going to run them as some sort of virtualized guest. I&#39;ve done this from time to time years ago but I was never able to get video and or sound as if it was native. For example, watching a video or playing music was choppy at best. I used virtualbox and kvm for reference. And, I tried lots of different ways to connect to the guest such as nomachine which had the best quality with compression. </p> <p>I&#39;d like to try arch out but run it as a guest. Is there any newer ways to achieve this that&#39;s comparable to running it natively? Distrobox maybe? I&#39;ve not played around with the newer virt tech in linux these days. </p> <p>I think running tumbleweed and cachyOS both with btrfs and snapshots would be messy on one drive and one bootloader. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a hr

## Is ZapZap messenger secure and encrypted? is that safe to use?
 - [https://www.reddit.com/r/linux/comments/1hrlmni/is_zapzap_messenger_secure_and_encrypted_is_that](https://www.reddit.com/r/linux/comments/1hrlmni/is_zapzap_messenger_secure_and_encrypted_is_that)
 - RSS feed: $source
 - date published: 2025-01-02T04:30:41+00:00

<!-- SC_OFF --><div class="md"><p>Flatpak have Telegram and Signal desktop versions. But WhatsApp official desktop isn&#39;t available for linux.</p> <p>But I found a whatsapp web frontend client ZAPZAP messenger.</p> <p>Is that end-to-end encrypted and safe to use? Can developer view all our data?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MrLoton"> /u/MrLoton </a> <br/> <span><a href="https://www.reddit.com/r/linux/comments/1hrlmni/is_zapzap_messenger_secure_and_encrypted_is_that/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrlmni/is_zapzap_messenger_secure_and_encrypted_is_that/">[comments]</a></span>

## Initial Release of heretek: Yet Another GDB TUI Frontend
 - [https://www.reddit.com/r/linux/comments/1hrknqp/initial_release_of_heretek_yet_another_gdb_tui](https://www.reddit.com/r/linux/comments/1hrknqp/initial_release_of_heretek_yet_another_gdb_tui)
 - RSS feed: $source
 - date published: 2025-01-02T03:36:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/arch_rust"> /u/arch_rust </a> <br/> <span><a href="https://github.com/wcampbell0x2a/heretek">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hrknqp/initial_release_of_heretek_yet_another_gdb_tui/">[comments]</a></span>

## The perfect install
 - [https://www.reddit.com/r/linux/comments/1hri81m/the_perfect_install](https://www.reddit.com/r/linux/comments/1hri81m/the_perfect_install)
 - RSS feed: $source
 - date published: 2025-01-02T01:31:35+00:00

<!-- SC_OFF --><div class="md"><p>Time for a fresh WSL2 install, the reason is a classic. I&#39;ve had Linux for 12 months and I access it so often I almost forgot my password, so basically a WSL2 veteran. Nay, expert. I decide I&#39;m sick of the CLI and as gods gift to computing (and using google to find stack exchange posts) I&#39;m going to get this windowed penguin all wrapped up in a sexy gnome outfit. Fast forward twenty minutes, I&#39;ve sucessfully installed VcXsrc and broken my distro beyond convenient repair. Who knew a guide from 2021 coupled with a tenuous grasp of linux in general would end up like this. No matter, the only casualties here are a 60% completion of the TOP tutorial and a half complete CTF challenge (I told you i was a WSL2 savant).</p> <p>&gt; wsl --unregister Ubuntu 24.04.1<br/> &gt;wsl.exe --uninstall</p> <p>Time to redo, this time i&#39;ll use the opportunity to do a perfect install</p> <p>&gt;wsl --install</p> <p>$sudo apt install firefox</p> <p>$sudo

## Ubuntu is more searched than every other distro combined (google trends)
 - [https://www.reddit.com/r/linux/comments/1hri7cr/ubuntu_is_more_searched_than_every_other_distro](https://www.reddit.com/r/linux/comments/1hri7cr/ubuntu_is_more_searched_than_every_other_distro)
 - RSS feed: $source
 - date published: 2025-01-02T01:30:39+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Zery12"> /u/Zery12 </a> <br/> <span><a href="https://i.redd.it/9pccqwn5hhae1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux/comments/1hri7cr/ubuntu_is_more_searched_than_every_other_distro/">[comments]</a></span>

