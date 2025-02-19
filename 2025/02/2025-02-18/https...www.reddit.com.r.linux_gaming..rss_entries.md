# Source:GNU/Linux Gaming on Reddit, URL:https://www.reddit.com/r/linux_gaming/.rss, language:

## I switched from Windows to Linux for gaming and it's been a wild ride!
 - [https://www.reddit.com/r/linux_gaming/comments/1isq46w/i_switched_from_windows_to_linux_for_gaming_and](https://www.reddit.com/r/linux_gaming/comments/1isq46w/i_switched_from_windows_to_linux_for_gaming_and)
 - RSS feed: $source
 - date published: 2025-02-18T23:07:21+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve been a dedicated PC gamer for over 10 years, but I recently decided to make the switch from Windows to Linux. The main reason was that I wanted a more secure and stable operating system, as well as the ability to customize and fine-tune my system to my liking.</p> <p>I chose Ubuntu as my distro of choice, mainly because it&#39;s user-friendly and has a large community of users who are willing to help out with any issues. The initial setup was relatively smooth, but I did encounter some bumps along the way.</p> <p>One of the biggest challenges was getting Steam to work properly. It took me a few days of troubleshooting to figure out that the issue was related to the Wine compatibility layer. Once I updated my Wine version and tweaked some settings, everything started working smoothly.</p> <p>Another challenge I faced was finding games that were compatible with Linux. I was pleasantly surprised to find that many popular titles had native Linux

## Can my laptop run Bazzite?
 - [https://www.reddit.com/r/linux_gaming/comments/1ispxz5/can_my_laptop_run_bazzite](https://www.reddit.com/r/linux_gaming/comments/1ispxz5/can_my_laptop_run_bazzite)
 - RSS feed: $source
 - date published: 2025-02-18T23:00:27+00:00

<!-- SC_OFF --><div class="md"><p>I have an old laptop with a core i3 6100u with Intel HD 520 graphics. Does anyone know if it will be supported by Bazzite? I know it&#39;s not gonna be a graphical power house, but I just want know if it&#39;s gonna be compatible enough to at least get whatever performance the laptop is still capable of. Using it to get a more console like experience for old computer games primarily.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Forward_Sell_4221"> /u/Forward_Sell_4221 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1ispxz5/can_my_laptop_run_bazzite/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1ispxz5/can_my_laptop_run_bazzite/">[comments]</a></span>

## Some Bash Tricks for steam wine prefixes
 - [https://www.reddit.com/r/linux_gaming/comments/1ispblz/some_bash_tricks_for_steam_wine_prefixes](https://www.reddit.com/r/linux_gaming/comments/1ispblz/some_bash_tricks_for_steam_wine_prefixes)
 - RSS feed: $source
 - date published: 2025-02-18T22:36:50+00:00

<!-- SC_OFF --><div class="md"><p>I have created some functions for .bashrc that override the standard behaviour of cd and ls if you are in the compatdata directory (where the wine prefixes of steam are located).</p> <p>it will show you which game&#39;s prefix is located in which id (with ls) and if you are in one of the prefix folders will modify PS1 to show that.</p> <p>Edit: you will need to have protontricks, as it uses it to find the steamids of installed games (even non-steam games) that have a wine prefix</p> <p>```bash list-steam() { for i in $(/usr/bin/ls); do out=$(protontricks -l | grep &quot;($i)&quot;) if [ -z &quot;$out&quot; ] ; then echo $i; else echo $out; fi done; }</p> <p>myls() { if [ ! -z $@ ]; then /usr/bin/ls $@ else if [ &quot;${PWD##*/}&quot; == &quot;compatdata&quot; ]; then list-steam else /usr/bin/ls fi fi }</p> <p>custom_cd() { builtin cd $@ if [ ! -z &quot;$OLD_PS1&quot; ]; then if [ -z $(pwd | grep &quot;$STEAMID&quot;) ]; then PS1=$OLD_PS1 unset $OLD_P

## Valve releases Team Fortress 2 game code
 - [https://www.reddit.com/r/linux_gaming/comments/1isp2ir/valve_releases_team_fortress_2_game_code](https://www.reddit.com/r/linux_gaming/comments/1isp2ir/valve_releases_team_fortress_2_game_code)
 - RSS feed: $source
 - date published: 2025-02-18T22:28:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1isp2ir/valve_releases_team_fortress_2_game_code/"> <img src="https://external-preview.redd.it/vMfufMQmoYP7lpAvnoVm5olsAfEmwWjzz0PY57FdipE.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=87d549525bf3a6d01ac53a01582280fdb956c68e" alt="Valve releases Team Fortress 2 game code" title="Valve releases Team Fortress 2 game code" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sol33t303"> /u/Sol33t303 </a> <br/> <span><a href="https://github.com/ValveSoftware/source-sdk-2013/commit/0759e2e8e179d5352d81d0d4aaded72c1704b7a9">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isp2ir/valve_releases_team_fortress_2_game_code/">[comments]</a></span> </td></tr></table>

## VRR deactivating when moving mouse in games [source of issue found]
 - [https://www.reddit.com/r/linux_gaming/comments/1isoj4i/vrr_deactivating_when_moving_mouse_in_games](https://www.reddit.com/r/linux_gaming/comments/1isoj4i/vrr_deactivating_when_moving_mouse_in_games)
 - RSS feed: $source
 - date published: 2025-02-18T21:39:15+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m on Arch + AMD + Plasma Wayland. This was a known issue with this configuration a while ago. See these relevant issues, among others linked in them:</p> <p><a href="https://invent.kde.org/plasma/kwin/-/issues/85">Handling cursor updates with VRR</a></p> <p><a href="https://gitlab.freedesktop.org/drm/amd/-/issues/2186">With vrr and atomic modesetting, some cursor plane updates are dropped</a></p> <p>From my understanding a solution was initially implemented about 11 months ago, but required a software cursor to work on AMD without strange cursor behaviour because of a bug in <code>amdgpu</code>. This bug was then fixed about 10 months ago, taking a bit to work its way into the kernel. The issue should be completely resolved with my current Linux 6.13.2 and plasma 6.3.0. However, with a default configuration moving my mouse in a game/application that is engaging VRR will still cause the VRR to deactivate, which is obvious now that I have an OLED

## Borderlands The Pre-Sequel! crashing at start [SOLUTION]
 - [https://www.reddit.com/r/linux_gaming/comments/1isnr65/borderlands_the_presequel_crashing_at_start](https://www.reddit.com/r/linux_gaming/comments/1isnr65/borderlands_the_presequel_crashing_at_start)
 - RSS feed: $source
 - date published: 2025-02-18T21:08:44+00:00

<!-- SC_OFF --><div class="md"><p>Months ago I was playing BTP on my Arch PC, then I changed my SSD to a NVMe and decided to reinstall all my stuff.</p> <p>All good, until I tried to play BTP (Steam), the game downloaded the C++ dependencies, the &quot;STOP&quot; button appeared on the Steam client (the game is running), and then suddenly crashes (PLAY button reappears), both on native and using Proton.</p> <p>I tried many fixes and possible solutions, but nothing worked.</p> <p>Then I decided to do this:</p> <ol> <li>Uninstall game</li> <li>Open game properties, force compatibility to any version of Proton</li> <li>Install game</li> </ol> <p>Then it finally worked!</p> <p>I read about a post saying that it could be due to Proton not updating correctly the game directory when switching from the native version, and I tried to fix the switching multiple times, but it didn&#39;t work.</p> <p>Then I tried the solution to this post.</p> <p>I hope that you found this useful. This is my con

## Mint 22 causing graphics card to crash
 - [https://www.reddit.com/r/linux_gaming/comments/1isn584/mint_22_causing_graphics_card_to_crash](https://www.reddit.com/r/linux_gaming/comments/1isn584/mint_22_causing_graphics_card_to_crash)
 - RSS feed: $source
 - date published: 2025-02-18T20:44:20+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone else run into this issue? I just upgraded to Linux mint 22 and now whenever I try to load up a game through steam my screens go black and the fans on my graphics card start to spin like crazy. Still can’t figure out why</p> <p>I’m on intel i5 and Nvidia-driver-550 Gigabyte 1060 and I’ve sudo apt update &amp;&amp; upgrade</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Soubdwave_Prime"> /u/Soubdwave_Prime </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isn584/mint_22_causing_graphics_card_to_crash/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isn584/mint_22_causing_graphics_card_to_crash/">[comments]</a></span>

## Switching to Linux
 - [https://www.reddit.com/r/linux_gaming/comments/1ism27u/switching_to_linux](https://www.reddit.com/r/linux_gaming/comments/1ism27u/switching_to_linux)
 - RSS feed: $source
 - date published: 2025-02-18T20:01:12+00:00

<!-- SC_OFF --><div class="md"><p>I use my computer for studying and gaming. As far as studying goes, I have no doubts about Linux&#39;s ability to facilitate my studying. In terms of gaming, I am a little concerned. I really love Linux as an operating system but I have not switched to it just because of the lack of gaming support. I heard Minecraft Bedrock Edition Realms doesn&#39;t work. Roblox doesn&#39;t work either. Also, I want to keep my personal files. I am thinking of installing Arch. I would appreciate any helpful tips!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mogger_rebel"> /u/mogger_rebel </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1ism27u/switching_to_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1ism27u/switching_to_linux/">[comments]</a></span>

## Plug & Play OS?
 - [https://www.reddit.com/r/linux_gaming/comments/1isl5o8/plug_play_os](https://www.reddit.com/r/linux_gaming/comments/1isl5o8/plug_play_os)
 - RSS feed: $source
 - date published: 2025-02-18T19:24:49+00:00

<!-- SC_OFF --><div class="md"><p>Hello guys, VERY new Linux user here, but very optimistic! Altho, I have been trying to do something lately because I have free will and really wanna see if it works. </p> <p>Basically, what I wish to do is to put a working Linux distro OS into a USB drive, not in a Rufus way, more in &quot;install as a drive&quot; way if I&#39;m making myself understandable. I have seen some videos and have been trying to research it, but every try I had has come to despair. </p> <p>My equipment: A computer (idk if specs are needed) 2 USB drives(16GB Rufus, 128GB destination)</p> <p>Im grateful for any help :D</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/StrangeEnergy3666"> /u/StrangeEnergy3666 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isl5o8/plug_play_os/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isl5o8/plug_play_os/">[comments]</a></span>

## 2k25 doesn't run on Windows because of EAC, but runs on Linux
 - [https://www.reddit.com/r/linux_gaming/comments/1iskmz9/2k25_doesnt_run_on_windows_because_of_eac_but](https://www.reddit.com/r/linux_gaming/comments/1iskmz9/2k25_doesnt_run_on_windows_because_of_eac_but)
 - RSS feed: $source
 - date published: 2025-02-18T19:04:22+00:00

<!-- SC_OFF --><div class="md"><p>This is a funny anecdotal experience I had during this past week. So I upgraded to the 9800x3d and X870E chipset, and for some reason there is a bug in the latest Windows 11 version where certain versions anti-cheats cause unexpected kernel mode trap and Windows crashes into a blue screen with Ryzen 9000 CPUs. So NBA 2K25 turned out to be one of those games, and its one of the games I play the most. </p> <p>Just for chuckles I decided to test it in EndeavourOS (Arch based distro) since protondb claimed it works and... drumroll.. it DOES!</p> <p>I actually lived to see the day where Eazy Anticheat games work better on Linux LOL, but seriously Windows, get your sh*t together.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thetanaz"> /u/thetanaz </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1iskmz9/2k25_doesnt_run_on_windows_because_of_eac_but/">[link]</a></span> &#32; <span><a href="htt

## Which distro will let me boot directly into steam big picture mode faster than windows 10 ltsc on a gtx 750ti?
 - [https://www.reddit.com/r/linux_gaming/comments/1isjvvm/which_distro_will_let_me_boot_directly_into_steam](https://www.reddit.com/r/linux_gaming/comments/1isjvvm/which_distro_will_let_me_boot_directly_into_steam)
 - RSS feed: $source
 - date published: 2025-02-18T18:35:16+00:00

<!-- SC_OFF --><div class="md"><p>Asked this before but got no answers, is there any gaming distro that boots straight into steam regardless of hardware? I know bazzite doesn&#39;t </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/latrina_demmerda"> /u/latrina_demmerda </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isjvvm/which_distro_will_let_me_boot_directly_into_steam/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isjvvm/which_distro_will_let_me_boot_directly_into_steam/">[comments]</a></span>

## I developed this social deduction game using Linux and FOSS tools! 🎃💀
 - [https://www.reddit.com/r/linux_gaming/comments/1isj0sh/i_developed_this_social_deduction_game_using](https://www.reddit.com/r/linux_gaming/comments/1isj0sh/i_developed_this_social_deduction_game_using)
 - RSS feed: $source
 - date published: 2025-02-18T18:01:25+00:00

<!-- SC_OFF --><div class="md"><p>Hey, fellow Linux gamers! I made <em>Spooky Night</em>, a social deduction game entirely using Linux and open-source tools. From coding to the drawn art.</p> <p>Check it out and let me know what you think</p> <p>The demo is coming soon on steam! WISHLISH the game to help me gain more visibility</p> <p>OS: Arch Linux</p> <p>Game Engine: Godot</p> <p>Editor: Emacs</p> <p>Art: Gimp &amp; Inkscape &amp; Krita</p> <p>Sound: Audacity</p> <p>Trailer &amp; Video content: Blender</p> <p><a href="https://reddit.com/link/1isj0sh/video/ghs5ax6zqxje1/player">https://reddit.com/link/1isj0sh/video/ghs5ax6zqxje1/player</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Mission-Essay6795"> /u/Mission-Essay6795 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isj0sh/i_developed_this_social_deduction_game_using/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isj0sh

## Dual Boot Distros
 - [https://www.reddit.com/r/linux_gaming/comments/1ish537/dual_boot_distros](https://www.reddit.com/r/linux_gaming/comments/1ish537/dual_boot_distros)
 - RSS feed: $source
 - date published: 2025-02-18T16:47:11+00:00

<!-- SC_OFF --><div class="md"><p>I currently have Zorin OS as my main OS with Windows 11 on a second drive for a few work related things. I&#39;ve been reading on on Bazzite OS and want to give it a try. While I doubt it will magically make Photoshop or Premiere work (I&#39;m 99.9% it won&#39;t), I am curious if some game related issues I have are resolved. So far games I&#39;ve thrown at Zorin works with the exception of several mods for City Skylines 2, which is the main reason I want to try Bazzite.</p> <p>Long story to the question: Since I&#39;m still relatively new to Linux, if I partition the Zorin drive and install Bazzite to it will it mess up my bootloader, or will I now be able to choose between Zorin, Bazzite, and Win11? If I decide Bazzite isn&#39;t for me and I remove the partition, will Zorin and Win11 continue to load without issue, or will I need to fix the bootloader somehow?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/thu

## Linux vs Windows Benchmark GTA 5 2025
 - [https://www.reddit.com/r/linux_gaming/comments/1isfvi4/linux_vs_windows_benchmark_gta_5_2025](https://www.reddit.com/r/linux_gaming/comments/1isfvi4/linux_vs_windows_benchmark_gta_5_2025)
 - RSS feed: $source
 - date published: 2025-02-18T15:55:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1isfvi4/linux_vs_windows_benchmark_gta_5_2025/"> <img src="https://external-preview.redd.it/3Ttsc-oyI_nJHtEZmoRN6qkLRpsvBI2YxZd0XsharSs.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=16585def902298589f183ae2942558387cab30cd" alt="Linux vs Windows Benchmark GTA 5 2025" title="Linux vs Windows Benchmark GTA 5 2025" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Linux performs much better in GTA5 than year ago. Identical flawless experience on both platforms. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/RoninNinjaTv"> /u/RoninNinjaTv </a> <br/> <span><a href="https://youtu.be/J-fezkcaQYo?si=gf4L9_KelppxV7CI">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isfvi4/linux_vs_windows_benchmark_gta_5_2025/">[comments]</a></span> </td></tr></table>

## Watchmen: End is Night Part 1 and 2 not launching
 - [https://www.reddit.com/r/linux_gaming/comments/1isfp37/watchmen_end_is_night_part_1_and_2_not_launching](https://www.reddit.com/r/linux_gaming/comments/1isfp37/watchmen_end_is_night_part_1_and_2_not_launching)
 - RSS feed: $source
 - date published: 2025-02-18T15:47:27+00:00

<!-- SC_OFF --><div class="md"><p>As per the title, I just bought and installed Watchmen and cant get it to even properly start. I click play and it acts like it&#39;s going to start up then just cycles back like I didn&#39;t even click on it.</p> <p>I&#39;m up to date with Linux Mint Cinnamon. Is there a certain Proton I need to use? any and all help/suggestions would be appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/GiantNerd96"> /u/GiantNerd96 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isfp37/watchmen_end_is_night_part_1_and_2_not_launching/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isfp37/watchmen_end_is_night_part_1_and_2_not_launching/">[comments]</a></span>

## I feel like my "Linux Gaming" information is out of date
 - [https://www.reddit.com/r/linux_gaming/comments/1isfio5/i_feel_like_my_linux_gaming_information_is_out_of](https://www.reddit.com/r/linux_gaming/comments/1isfio5/i_feel_like_my_linux_gaming_information_is_out_of)
 - RSS feed: $source
 - date published: 2025-02-18T15:39:58+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve dabbled in Linux off and on since I installed it on my old HP ZD8000 a Pentium 4 laptop with a dedicated GPU that had a whopping 512MB of VRAM. I&#39;ve thought that I&#39;ve general kept up to date on general Linux news since I use a lot of Raspberry Pi&#39;s. However my &quot;go-to&quot; Linux OS&#39;s for home use are all Debian based and either Ubuntu or Ubuntu off-shoots like Pop_OS! since my long term experience with them has been better stability in their LTS builds, better out-of-the hardware support, and the default GUI is more user friendly to me for day-to-day computer use.</p> <p>The general wisdom I&#39;ve known is that the bigger the team behind a Linux OS the more stable feature rich it was and also the more likely it was to have continued security and feature support down the line. I&#39;ve typically avoided Fedora because of how far upstream it is, and Arch based OS are generally not very user friendly but it seems weird to 

## Quest 3 PCVR on Fedora Linux
 - [https://www.reddit.com/r/linux_gaming/comments/1isdp46/quest_3_pcvr_on_fedora_linux](https://www.reddit.com/r/linux_gaming/comments/1isdp46/quest_3_pcvr_on_fedora_linux)
 - RSS feed: $source
 - date published: 2025-02-18T14:19:02+00:00

<!-- SC_OFF --><div class="md"><p>After weeks of researching and configurations Quest 3 with Fedora Linux I would like to share my experience to save somebody&#39;s time.</p> <p><em>OS: Fedora Workstation 41, Gnome 47, Wayland</em> </p> <p><em>CPU: 12th Gen Intel® Core™ i5-12500H with Iris Xe graphics (yea it will be fun)</em></p> <p>I&#39;ve tested a lot of apps in different configurations, even tried to launch Windows applications using Wine. So, here is the list of my recommendations:</p> <p><strong>Screen mirroring:</strong> <a href="https://immersed.com/">Immersed</a></p> <p>Allow you to mirror your pc screen to headset, create additional virtual monitors, resize and arrange them. Work both wireless and wired (require Dev Mode). Simple and free tool. <em>Note: install intel-media-driver for Hardware Acceleration</em></p> <p><strong>PCVR:</strong> <a href="https://github.com/WiVRn/WiVRn">WiVRn</a></p> <p>After weeks of fixing ALVR issues and getting errors in Steam Link, I finall

## Why skip to Linux?
 - [https://www.reddit.com/r/linux_gaming/comments/1isciv2/why_skip_to_linux](https://www.reddit.com/r/linux_gaming/comments/1isciv2/why_skip_to_linux)
 - RSS feed: $source
 - date published: 2025-02-18T13:21:28+00:00

<!-- SC_OFF --><div class="md"><p>Hello good morning. First time writing in the community. I would like to know how much of a difference there is between moving from Windows to Linux? Is the jump in performance in games so big? I have an Intel i3-9100f with an rx 570 4gb and the truth is that for more current games it begins to suffer. So that&#39;s why I look for new systems to see how efficient they can be. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Lauty_0611"> /u/Lauty_0611 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isciv2/why_skip_to_linux/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isciv2/why_skip_to_linux/">[comments]</a></span>

## Is it worth setting up a Windows KVM for VR gaming? How is the performance?
 - [https://www.reddit.com/r/linux_gaming/comments/1iscfdc/is_it_worth_setting_up_a_windows_kvm_for_vr](https://www.reddit.com/r/linux_gaming/comments/1iscfdc/is_it_worth_setting_up_a_windows_kvm_for_vr)
 - RSS feed: $source
 - date published: 2025-02-18T13:16:14+00:00

<!-- SC_OFF --><div class="md"><p>ALVR is a hit and miss especially with fast paced games like Beat Saber<br/> I currently dual boot Fedora and Windows 11 but I&#39;d much rather have it easier to access, question is how well it works and how much it affects hte performance.<br/> Bottom line - is it worth it?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/etay080"> /u/etay080 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1iscfdc/is_it_worth_setting_up_a_windows_kvm_for_vr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1iscfdc/is_it_worth_setting_up_a_windows_kvm_for_vr/">[comments]</a></span>

## State of VR
 - [https://www.reddit.com/r/linux_gaming/comments/1isbrx8/state_of_vr](https://www.reddit.com/r/linux_gaming/comments/1isbrx8/state_of_vr)
 - RSS feed: $source
 - date published: 2025-02-18T12:41:04+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;ve tried to jump ship so many times. My productivity, media, and media server devices are running Linux distros. The one thing that&#39;s holding me back- my gaming rig. </p> <p>I play a niche of a niche. I play driving sims with a ffb wheel in VR. Virtual Desktop just works, and works incredibly well. I&#39;m aware of ALVR but have never tried it. </p> <p>I hate windows. Any advice on VR and wheel support, specifically a Quest 2 with a link cable? I&#39;ve done tons of googling but it seems like most posts are from years ago. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Same-Traffic-285"> /u/Same-Traffic-285 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbrx8/state_of_vr/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbrx8/state_of_vr/">[comments]</a></span>

## Diablo 4 / Lutris / Battlenet - how to use discrete GPU?
 - [https://www.reddit.com/r/linux_gaming/comments/1isbogt/diablo_4_lutris_battlenet_how_to_use_discrete_gpu](https://www.reddit.com/r/linux_gaming/comments/1isbogt/diablo_4_lutris_battlenet_how_to_use_discrete_gpu)
 - RSS feed: $source
 - date published: 2025-02-18T12:35:29+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I have AMD 7600 CPU with integrated GPU + RX 6950XT, </p> <p>I&#39;ve installed Battlenet through Lutris and set it to use 6950XT, but Diablo has 5fps :/</p> <p>So I assume that it&#39;s not using 6950XT but the integrated GPU.</p> <p>(Nobara 41)</p> <p>Any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/amamoh"> /u/amamoh </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbogt/diablo_4_lutris_battlenet_how_to_use_discrete_gpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbogt/diablo_4_lutris_battlenet_how_to_use_discrete_gpu/">[comments]</a></span>

## Get a .macdat Steam Cloud save working with Proton
 - [https://www.reddit.com/r/linux_gaming/comments/1isbdtr/get_a_macdat_steam_cloud_save_working_with_proton](https://www.reddit.com/r/linux_gaming/comments/1isbdtr/get_a_macdat_steam_cloud_save_working_with_proton)
 - RSS feed: $source
 - date published: 2025-02-18T12:18:06+00:00

<!-- SC_OFF --><div class="md"><p>Hi everyone, I built a new PC with an AMD card for Arch linux and Hyprland. I started Tomb Raider on my mac, so on Steam Cloud I have .macdat saves. But proton saves in and reads the .dat ones, like Windows, I believe it’s because it has to emulate the Windows environment. Anyway, I don’t know why, but it doesn’t start natively, it only starts with Proton. I really don’t want to restart the game or download a save from the Internet. Do you have any solutions?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/semedilino073"> /u/semedilino073 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbdtr/get_a_macdat_steam_cloud_save_working_with_proton/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isbdtr/get_a_macdat_steam_cloud_save_working_with_proton/">[comments]</a></span>

## Font issue on EU4
 - [https://www.reddit.com/r/linux_gaming/comments/1isavma/font_issue_on_eu4](https://www.reddit.com/r/linux_gaming/comments/1isavma/font_issue_on_eu4)
 - RSS feed: $source
 - date published: 2025-02-18T11:47:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1isavma/font_issue_on_eu4/"> <img src="https://b.thumbs.redditmedia.com/s41t6QA5mFW4bPr8rniK5M4bRAHUQqqSqXOMg66tS1I.jpg" alt="Font issue on EU4" title="Font issue on EU4" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I wanted to start playing EU4 and it&#39;s my first time trying the game and I encountered this issue where some region names are displayed incorrectly with ¿ and 1/2 symbols for some reason. I think it happens because of special characters. I had similar issues on Lutris and fixed it with installing all the fonts winetricks allowed me to install but apparently EU4 works natively on Linux so I don&#39;t know how to go about it. I can see the fonts used in the game folders but do I need to install them to my system somehow? Can you help me figure out what to do?</p> <p><a href="https://preview.redd.it/5zojeosrxvje1.png?width=1920&amp;format=png&amp;auto=webp&amp;s=41d3002289aaff3598bdb13aaf608b

## Ext4 or btrfs
 - [https://www.reddit.com/r/linux_gaming/comments/1isasm4/ext4_or_btrfs](https://www.reddit.com/r/linux_gaming/comments/1isasm4/ext4_or_btrfs)
 - RSS feed: $source
 - date published: 2025-02-18T11:42:32+00:00

<!-- SC_OFF --><div class="md"><p>Which file system should I choose btrfs or ext4, what are the advantages or disadvantages of both. (I am using a dying hdd which has 3 bad sectors for testing things out) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AbyssalBytez_"> /u/AbyssalBytez_ </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isasm4/ext4_or_btrfs/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1isasm4/ext4_or_btrfs/">[comments]</a></span>

## Metro: Last Light (Steam Linux native version) crashes to desktop
 - [https://www.reddit.com/r/linux_gaming/comments/1is9zgh/metro_last_light_steam_linux_native_version](https://www.reddit.com/r/linux_gaming/comments/1is9zgh/metro_last_light_steam_linux_native_version)
 - RSS feed: $source
 - date published: 2025-02-18T10:49:38+00:00

<!-- SC_OFF --><div class="md"><p>Did anyone manage to get it running? When I click Play it just shows black screen for a split second and then closes.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ParticularAd4647"> /u/ParticularAd4647 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is9zgh/metro_last_light_steam_linux_native_version/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is9zgh/metro_last_light_steam_linux_native_version/">[comments]</a></span>

## My teenage sons windows computer aren't eligible to be updated to windows 11. He is a gamer, what type of Linux is the easiest to setup steam and start playing?
 - [https://www.reddit.com/r/linux_gaming/comments/1is9ol0/my_teenage_sons_windows_computer_arent_eligible](https://www.reddit.com/r/linux_gaming/comments/1is9ol0/my_teenage_sons_windows_computer_arent_eligible)
 - RSS feed: $source
 - date published: 2025-02-18T10:27:53+00:00

<!-- SC_OFF --><div class="md"><p>Hi. I&#39;m new to Linux. 10 years ago I experimented a little bit with Ubuntu on an older laptop. </p> <p>Now Microsoft forcing people to replace there hardware upgrade to windows 11. I&#39;m looking for an alternative, and maybe going into Linux again, and try learning together with my son. There are many different versions. </p> <p>My son only needs his computer for study and gaming. What type of Linux is the easiest to setup here in 2025, including nvidia drivers, and steam?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Chameleon2000"> /u/Chameleon2000 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is9ol0/my_teenage_sons_windows_computer_arent_eligible/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is9ol0/my_teenage_sons_windows_computer_arent_eligible/">[comments]</a></span>

## Wayland screensharing not working with native discord but works with browser and flatpak (canary)
 - [https://www.reddit.com/r/linux_gaming/comments/1is9nyx/wayland_screensharing_not_working_with_native](https://www.reddit.com/r/linux_gaming/comments/1is9nyx/wayland_screensharing_not_working_with_native)
 - RSS feed: $source
 - date published: 2025-02-18T10:26:36+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is9nyx/wayland_screensharing_not_working_with_native/"> <img src="https://external-preview.redd.it/KG4l1-3zJTvLNaFqFEI0sZpFckuzbP1eU-y7B_jpu2A.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=0895ca1ea9f4a3525144603627d86d20dd315994" alt="Wayland screensharing not working with native discord but works with browser and flatpak (canary)" title="Wayland screensharing not working with native discord but works with browser and flatpak (canary)" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>It shows me this:</p> <p><a href="https://preview.redd.it/dejijoxkhvje1.png?width=1353&amp;format=png&amp;auto=webp&amp;s=6c21da179f222ecf673be779b7fc4c5a45dcafe5">https://preview.redd.it/dejijoxkhvje1.png?width=1353&amp;format=png&amp;auto=webp&amp;s=6c21da179f222ecf673be779b7fc4c5a45dcafe5</a></p> <p>and ultimately only streams a blank image:</p> <p><a href="https://preview.redd.it/193jmwu2ivje1.png?width=1691&amp;format=p

## How the tables have turned.
 - [https://www.reddit.com/r/linux_gaming/comments/1is99tg/how_the_tables_have_turned](https://www.reddit.com/r/linux_gaming/comments/1is99tg/how_the_tables_have_turned)
 - RSS feed: $source
 - date published: 2025-02-18T09:58:44+00:00

<!-- SC_OFF --><div class="md"><p>Well I use my pc just for gaming. I dual boot bazzite and windows. As I was messing around with my HDD configuration I decided to do a clean install of both. Bazzite was up and running in no time then I turned to windows. First the install took about 100 times longer than bazzite. Then after just two days of running my windows got a rather annoying bug were all the fonts changed and for the life of me I can&#39;t change them back. We are talking the fonts under all my desktop icons and the header bar in my internet browsers. So this weekend I think I will have to do another clean install of windows. When did Linux become the stable one and windows be the one with issues.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/peter1970uk"> /u/peter1970uk </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is99tg/how_the_tables_have_turned/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## Arkham asylum have problem on ubuntu, intel
 - [https://www.reddit.com/r/linux_gaming/comments/1is8zlf/arkham_asylum_have_problem_on_ubuntu_intel](https://www.reddit.com/r/linux_gaming/comments/1is8zlf/arkham_asylum_have_problem_on_ubuntu_intel)
 - RSS feed: $source
 - date published: 2025-02-18T09:37:23+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is8zlf/arkham_asylum_have_problem_on_ubuntu_intel/"> <img src="https://b.thumbs.redditmedia.com/kpcC6bXOz1OOPU0mlu5ODVCnx-Wt708AR3hi0mnc9vk.jpg" alt="Arkham asylum have problem on ubuntu, intel" title="Arkham asylum have problem on ubuntu, intel" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/ftvp8pb1bvje1.png?width=1092&amp;format=png&amp;auto=webp&amp;s=c96f4619ab52c6ebbf6f559f77207390aef96518">https://preview.redd.it/ftvp8pb1bvje1.png?width=1092&amp;format=png&amp;auto=webp&amp;s=c96f4619ab52c6ebbf6f559f77207390aef96518</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Significant-Pin6416"> /u/Significant-Pin6416 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is8zlf/arkham_asylum_have_problem_on_ubuntu_intel/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is8zlf/a

## I found and made a video on a document Nvidia made about their upcoming and past developments (over 2024 and 2025)
 - [https://www.reddit.com/r/linux_gaming/comments/1is7yke/i_found_and_made_a_video_on_a_document_nvidia](https://www.reddit.com/r/linux_gaming/comments/1is7yke/i_found_and_made_a_video_on_a_document_nvidia)
 - RSS feed: $source
 - date published: 2025-02-18T08:21:21+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is7yke/i_found_and_made_a_video_on_a_document_nvidia/"> <img src="https://external-preview.redd.it/F_H4JkJEwQxfkV2I2x252Eu1XGzqzR1P-MJIpjddeqg.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=1b002531c3b0fe02ecce3ea03fa63338fb934de6" alt="I found and made a video on a document Nvidia made about their upcoming and past developments (over 2024 and 2025)" title="I found and made a video on a document Nvidia made about their upcoming and past developments (over 2024 and 2025)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/AAVVIronAlex"> /u/AAVVIronAlex </a> <br/> <span><a href="https://youtu.be/YX3qK_6x4ro">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7yke/i_found_and_made_a_video_on_a_document_nvidia/">[comments]</a></span> </td></tr></table>

## Getting this error when I do yay -S moosync on arch, help?
 - [https://www.reddit.com/r/linux_gaming/comments/1is7y8h/getting_this_error_when_i_do_yay_s_moosync_on](https://www.reddit.com/r/linux_gaming/comments/1is7y8h/getting_this_error_when_i_do_yay_s_moosync_on)
 - RSS feed: $source
 - date published: 2025-02-18T08:20:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is7y8h/getting_this_error_when_i_do_yay_s_moosync_on/"> <img src="https://b.thumbs.redditmedia.com/X5v4Fm31vFFUohQ9m_iEKXIO_SyMXWRKrr3nRW_a2dM.jpg" alt="Getting this error when I do yay -S moosync on arch, help?" title="Getting this error when I do yay -S moosync on arch, help?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p><a href="https://preview.redd.it/x715lla8xuje1.png?width=1741&amp;format=png&amp;auto=webp&amp;s=afec3c9aa06c9db2a5d364a6c83b9fb20b30946a">https://preview.redd.it/x715lla8xuje1.png?width=1741&amp;format=png&amp;auto=webp&amp;s=afec3c9aa06c9db2a5d364a6c83b9fb20b30946a</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NightmarSpiral"> /u/NightmarSpiral </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7y8h/getting_this_error_when_i_do_yay_s_moosync_on/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux

## Marvel rivals network diagnostics 5000ms and 100% packet lose in linux
 - [https://www.reddit.com/r/linux_gaming/comments/1is7gha/marvel_rivals_network_diagnostics_5000ms_and_100](https://www.reddit.com/r/linux_gaming/comments/1is7gha/marvel_rivals_network_diagnostics_5000ms_and_100)
 - RSS feed: $source
 - date published: 2025-02-18T07:44:57+00:00

<!-- SC_OFF --><div class="md"><p>I have 5000ms and 100% packet lose in network diagnostics in marvel rivals in debian everytime I run it. I have 60 ping to some servers in the game and not much lag but why is network diagnostics not working? Does debian have some firewall that blocks it or something?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fearless_Major_7456"> /u/Fearless_Major_7456 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7gha/marvel_rivals_network_diagnostics_5000ms_and_100/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7gha/marvel_rivals_network_diagnostics_5000ms_and_100/">[comments]</a></span>

## Dev snapshot: Godot 4.4 beta 4
 - [https://www.reddit.com/r/linux_gaming/comments/1is7cs2/dev_snapshot_godot_44_beta_4](https://www.reddit.com/r/linux_gaming/comments/1is7cs2/dev_snapshot_godot_44_beta_4)
 - RSS feed: $source
 - date published: 2025-02-18T07:37:42+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is7cs2/dev_snapshot_godot_44_beta_4/"> <img src="https://external-preview.redd.it/mhdeYCxnggYez-NyQBAU-CPGmAbZmOGKNXKtNakBMCo.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=9ed295d97615f06df01c858bf6dc6d82fa459774" alt="Dev snapshot: Godot 4.4 beta 4" title="Dev snapshot: Godot 4.4 beta 4" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beer120"> /u/beer120 </a> <br/> <span><a href="https://godotengine.org/article/dev-snapshot-godot-4-4-beta-4/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7cs2/dev_snapshot_godot_44_beta_4/">[comments]</a></span> </td></tr></table>

## Is DInput or XInput more supported/useful?
 - [https://www.reddit.com/r/linux_gaming/comments/1is7b5i/is_dinput_or_xinput_more_supporteduseful](https://www.reddit.com/r/linux_gaming/comments/1is7b5i/is_dinput_or_xinput_more_supporteduseful)
 - RSS feed: $source
 - date published: 2025-02-18T07:34:25+00:00

<!-- SC_OFF --><div class="md"><p>(this is probably using the wrong tag)</p> <p>I have been messing around with XInput and DInput configurations on my controller, and I am wondering if Linux prefers/is more optimized for one or the other. I am also wondering if using one would be more useful than the other, and whether rumble is actually supported with DInput on Linux (Steam doesn&#39;t let me test it).</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/No_Comparison4153"> /u/No_Comparison4153 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7b5i/is_dinput_or_xinput_more_supporteduseful/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is7b5i/is_dinput_or_xinput_more_supporteduseful/">[comments]</a></span>

## Modding
 - [https://www.reddit.com/r/linux_gaming/comments/1is6pxl/modding](https://www.reddit.com/r/linux_gaming/comments/1is6pxl/modding)
 - RSS feed: $source
 - date published: 2025-02-18T06:54:09+00:00

<!-- SC_OFF --><div class="md"><p>Gaming has improved in Linux but modding is still left behind, Are there any good alternatives for Vortex, TexMod, TFC installer or does they work in bottles ?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/BlueColorBanana_"> /u/BlueColorBanana_ </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is6pxl/modding/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is6pxl/modding/">[comments]</a></span>

## Save 60% on Total War: WARHAMMER III on Steam. Is it a great game?
 - [https://www.reddit.com/r/linux_gaming/comments/1is693g/save_60_on_total_war_warhammer_iii_on_steam_is_it](https://www.reddit.com/r/linux_gaming/comments/1is693g/save_60_on_total_war_warhammer_iii_on_steam_is_it)
 - RSS feed: $source
 - date published: 2025-02-18T06:23:16+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is693g/save_60_on_total_war_warhammer_iii_on_steam_is_it/"> <img src="https://external-preview.redd.it/mELZF6ax3N7fdDiB2eBzmd8cYy5KoVosC5NT6lO2q8A.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=bd8419f6ba2c4d354e2da3009bf1b056ec0015fe" alt="Save 60% on Total War: WARHAMMER III on Steam. Is it a great game?" title="Save 60% on Total War: WARHAMMER III on Steam. Is it a great game?" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/beer120"> /u/beer120 </a> <br/> <span><a href="https://store.steampowered.com/app/1142710/Total_War_WARHAMMER_III/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is693g/save_60_on_total_war_warhammer_iii_on_steam_is_it/">[comments]</a></span> </td></tr></table>

## Has anyone gotten a headless version of Ubuntu working for Moonlight streaming?
 - [https://www.reddit.com/r/linux_gaming/comments/1is4h9w/has_anyone_gotten_a_headless_version_of_ubuntu](https://www.reddit.com/r/linux_gaming/comments/1is4h9w/has_anyone_gotten_a_headless_version_of_ubuntu)
 - RSS feed: $source
 - date published: 2025-02-18T04:35:41+00:00

<!-- SC_OFF --><div class="md"><p>I can’t seem to figure it out but I’m new to Ubuntu and wanted to setup my machine with Sunshine and stream my games when my monitor is off/im toggled to my Mac on my KVM (which disconnects the DP signal from my desktop). </p> <p>I have Sunshine running just fine and I tried a dummy DP plug to fix the issue but it’s not taking. I have no idea what exactly is causing the issue or where to start. I haven’t been able to find any other tutorials or guides where people have been successful online either (or if I have they are really old). Any help is appreciated.</p> <p>FWIW I’m using a 13700k, 32GB RAM and 3080 running Ubuntu 24.10.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Spudly2319"> /u/Spudly2319 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is4h9w/has_anyone_gotten_a_headless_version_of_ubuntu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/commen

## Improving Performance - Linux Mint
 - [https://www.reddit.com/r/linux_gaming/comments/1is4b15/improving_performance_linux_mint](https://www.reddit.com/r/linux_gaming/comments/1is4b15/improving_performance_linux_mint)
 - RSS feed: $source
 - date published: 2025-02-18T04:25:50+00:00

<!-- SC_OFF --><div class="md"><p>okay, so i started on linux mint about a month ago but was bothered by the performance. games that were running at 144+ frames on windows were now struggling to reach 60. so, i switched to bazzite, which boosted my performance back to where it was on windows. i attributed this to the mesa drivers bazzite comes packaged with. so, after hating fedora, i went back to mint. i installed the mesa drivers, but i&#39;m still experiencing performance issues. any tips?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/signal_win_8398"> /u/signal_win_8398 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is4b15/improving_performance_linux_mint/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is4b15/improving_performance_linux_mint/">[comments]</a></span>

## OCCT Now Available on Linux, Steam and Steam Deck
 - [https://www.reddit.com/r/linux_gaming/comments/1is3ix8/occt_now_available_on_linux_steam_and_steam_deck](https://www.reddit.com/r/linux_gaming/comments/1is3ix8/occt_now_available_on_linux_steam_and_steam_deck)
 - RSS feed: $source
 - date published: 2025-02-18T03:44:21+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Alternative-Pie345"> /u/Alternative-Pie345 </a> <br/> <span><a href="https://ocbase.com/news/occt-linux-release">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is3ix8/occt_now_available_on_linux_steam_and_steam_deck/">[comments]</a></span>

## Batman Arkham City issue on PopOS NVIDIA
 - [https://www.reddit.com/r/linux_gaming/comments/1is2u9q/batman_arkham_city_issue_on_popos_nvidia](https://www.reddit.com/r/linux_gaming/comments/1is2u9q/batman_arkham_city_issue_on_popos_nvidia)
 - RSS feed: $source
 - date published: 2025-02-18T03:08:29+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is2u9q/batman_arkham_city_issue_on_popos_nvidia/"> <img src="https://b.thumbs.redditmedia.com/HotZoYeviSYDS1KkgpWgBFRDm7mHrMuthM1TLe3k8PE.jpg" alt="Batman Arkham City issue on PopOS NVIDIA" title="Batman Arkham City issue on PopOS NVIDIA" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Hey everyone, trying to get my first game going on Linux (Pop_OS 22.04 NVIDIA) Batman Arkham City.</p> <p>I have installed Steam and enabled proton. But I keep getting the below error</p> <p><a href="https://preview.redd.it/ih1tnlooctje1.png?width=333&amp;format=png&amp;auto=webp&amp;s=e64abf46225e58d9ac1da5052c1b4aa7e143b163">Error screen</a></p> <p>After this I installed experimental proton and proton 8.05 but still got same error.</p> <p>I then tried installing Wine from PopOS launcher but got the same error:</p> <p>So far I have not tried anything other than just installing proton (via Steam) and Wine (via Pop! shop)</p> 

## Ready to finally make a move from Windows
 - [https://www.reddit.com/r/linux_gaming/comments/1is2s7h/ready_to_finally_make_a_move_from_windows](https://www.reddit.com/r/linux_gaming/comments/1is2s7h/ready_to_finally_make_a_move_from_windows)
 - RSS feed: $source
 - date published: 2025-02-18T03:05:29+00:00

<!-- SC_OFF --><div class="md"><p>Hello there friends, I never felt the urge to finally ditch Windows and become Linux user before like I do now. I use my computer basically just for gaming and usual stuff like browsing the internet. I dont use my computer for work at all.</p> <p>My system is AMD build 7600 CPU paired with 7900XTX Nitro+ and HDR monitor from Alienware model 3423DWF.</p> <p>I watched few videos here and there about Linux distros and stuff but I really would like to know which OS would you guys recommend for my needs? Linux Mint, Bazzite or maybe some other? Let me know what you guys think.</p> <p>Thank you and have a great day guys! :) </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/cr1ticaL666"> /u/cr1ticaL666 </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is2s7h/ready_to_finally_make_a_move_from_windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is2s7h/re

## For anyone curious, the upcoming game "Duet Night Abyss" seems to run without any tweaks
 - [https://www.reddit.com/r/linux_gaming/comments/1is12ho/for_anyone_curious_the_upcoming_game_duet_night](https://www.reddit.com/r/linux_gaming/comments/1is12ho/for_anyone_curious_the_upcoming_game_duet_night)
 - RSS feed: $source
 - date published: 2025-02-18T01:39:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/linux_gaming/comments/1is12ho/for_anyone_curious_the_upcoming_game_duet_night/"> <img src="https://preview.redd.it/t6x4f57pxsje1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=30632a2dd5c6fe1747c911482cd587054b04b43f" alt="For anyone curious, the upcoming game &quot;Duet Night Abyss&quot; seems to run without any tweaks" title="For anyone curious, the upcoming game &quot;Duet Night Abyss&quot; seems to run without any tweaks" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/TopazismyWife"> /u/TopazismyWife </a> <br/> <span><a href="https://i.redd.it/t6x4f57pxsje1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1is12ho/for_anyone_curious_the_upcoming_game_duet_night/">[comments]</a></span> </td></tr></table>

## Best way to run Red Dead Redemption 2 (Epic)?
 - [https://www.reddit.com/r/linux_gaming/comments/1irziry/best_way_to_run_red_dead_redemption_2_epic](https://www.reddit.com/r/linux_gaming/comments/1irziry/best_way_to_run_red_dead_redemption_2_epic)
 - RSS feed: $source
 - date published: 2025-02-18T00:25:52+00:00

<!-- SC_OFF --><div class="md"><p>I have been putting off playing RDR2 for a while, I want to get back to it and I remember last time I tried to launch it, I was having problems with the Rockstar launcher. Before I download it all through Heroric, I want to check what is the best way to run it right now without problems?</p> <p>I am using Arch and mostly just use Steam/Heroic, this one is purchased on Epic so I&#39;d like to run it through Heroic if possible.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/SillyLilBear"> /u/SillyLilBear </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1irziry/best_way_to_run_red_dead_redemption_2_epic/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1irziry/best_way_to_run_red_dead_redemption_2_epic/">[comments]</a></span>

## How do I convert my existing video files to the ones supported on linux (fix audio?) (studio or normal resolve)
 - [https://www.reddit.com/r/linux_gaming/comments/1irzi8h/how_do_i_convert_my_existing_video_files_to_the](https://www.reddit.com/r/linux_gaming/comments/1irzi8h/how_do_i_convert_my_existing_video_files_to_the)
 - RSS feed: $source
 - date published: 2025-02-18T00:25:08+00:00

<!-- SC_OFF --><div class="md"><p>Hey there, I have a bunch of video footage for my videos and ever since switching to linux, I could not play any of my videos as the audio section is missing (i think because the audio codec is not compatible) Can you please explain to me very easily on what to do with dept? new to linux, thanks</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/NightmarSpiral"> /u/NightmarSpiral </a> <br/> <span><a href="https://www.reddit.com/r/linux_gaming/comments/1irzi8h/how_do_i_convert_my_existing_video_files_to_the/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/linux_gaming/comments/1irzi8h/how_do_i_convert_my_existing_video_files_to_the/">[comments]</a></span>

## RADV Launch options that dont help (and some hurt performance), and a few that do
 - [https://www.reddit.com/r/linux_gaming/comments/1irzhuy/radv_launch_options_that_dont_help_and_some_hurt](https://www.reddit.com/r/linux_gaming/comments/1irzhuy/radv_launch_options_that_dont_help_and_some_hurt)
 - RSS feed: $source
 - date published: 2025-02-18T00:24:40+00:00

<!-- SC_OFF --><div class="md"><p>I just wanted to create a post about some of the launch options available to AMD Mesa driver users that either are generally worthless, hurt, or help performance. Keep in mind that these should not be used universally in most cases and you should do A/B testing for any given game to make sure. Many of these are not the default for good reason.</p> <p>This is by no means a comprehensive list but these are some of the common ones i see around. Some are in 2 categories to emphasize that they shouldnt be used universally.</p> <p><strong>Good</strong> </p> <p>---------</p> <p>RADV_DEBUG :</p> <p><code>invariantgeom</code> ; can work around geometry flickering in some games</p> <p><code>novrsflatshading</code> (RDNA2+) : use with forced VRS can be a performance bump</p> <p><code>zerovram</code> : this is actually the default for most cases it would be useful but you can test it on a given game if it might not be the default</p> <p><code>syncshaders</code> 

