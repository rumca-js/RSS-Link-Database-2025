# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Laser Turret / 3D print + Robotic + Rasberry PI 4
 - [https://www.reddit.com/r/raspberry_pi/comments/1htmpzz/laser_turret_3d_print_robotic_rasberry_pi_4](https://www.reddit.com/r/raspberry_pi/comments/1htmpzz/laser_turret_3d_print_robotic_rasberry_pi_4)
 - RSS feed: $source
 - date published: 2025-01-04T19:52:02+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1htmpzz/laser_turret_3d_print_robotic_rasberry_pi_4/"> <img src="https://external-preview.redd.it/c3E0Zmcwcmw3MWJlMRZDGioP_mMXV1IXOi3P_grxK70Dy23udry1o6fnkMHW.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=bfc43e3bb50a4a8bfbd50333a6808cb46c2f5f77" alt="Laser Turret / 3D print + Robotic + Rasberry PI 4" title="Laser Turret / 3D print + Robotic + Rasberry PI 4" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/6HERMIT9"> /u/6HERMIT9 </a> <br/> <span><a href="https://v.redd.it/tknqyynl71be1">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1htmpzz/laser_turret_3d_print_robotic_rasberry_pi_4/">[comments]</a></span> </td></tr></table>

## Install RPi Zero 2W from LINUX command line???
 - [https://www.reddit.com/r/raspberry_pi/comments/1hth5r2/install_rpi_zero_2w_from_linux_command_line](https://www.reddit.com/r/raspberry_pi/comments/1hth5r2/install_rpi_zero_2w_from_linux_command_line)
 - RSS feed: $source
 - date published: 2025-01-04T15:48:32+00:00

<!-- SC_OFF --><div class="md"><p>I don&#39;t want to install an imager when, as I understand it, installing is just imaging a file onto an sdcard (dd) and then creating a couple of configuration files (vi).</p> <p>This process seems semi-well documented</p> <p>I downloaded 2024-11-19-raspios-bookworm-arm64-lite.img.xz</p> <p>I then imaged this with xzcat | dd of=/dev/sdd</p> <p>I unplugged and replugged the sdcard, and dmesg/lsblk show the device now having an sdd1 and sdd2.</p> <p>I mount /dev/sdd1 at /rpi, as this seems to be the boot partition. I then create three files there:</p> <p>touch /rpi/ssh</p> <p>echo pi:encryptedpwd &gt; /rpi/userconf.txt &lt;&lt;EOM</p> <p>cat &gt; /rpi/wpa_supplicant.conf</p> <p>country=us</p> <p>ctrl_interface=/var/run/wpa_supplicant</p> <p>network={</p> <p>scan_ssid=1</p> <p>ssid=&quot;my-ssid&quot;</p> <p>psk=&quot;my-ssid-pwd&quot;</p> <p>}</p> <p>EOM </p> <p>But, it doesn&#39;t work. I umount /rpi, eject /dev/sdd, and then move the sdcard to the 

## Raspberry pi5 Ubuntu 24.04.1 Screen Cropped
 - [https://www.reddit.com/r/raspberry_pi/comments/1htedjk/raspberry_pi5_ubuntu_24041_screen_cropped](https://www.reddit.com/r/raspberry_pi/comments/1htedjk/raspberry_pi5_ubuntu_24041_screen_cropped)
 - RSS feed: $source
 - date published: 2025-01-04T13:28:30+00:00

<!-- SC_OFF --><div class="md"><p>Hello there,</p> <p>I&#39;m experiencing a problem with my Raspberry Pi5, running Ubuntu 24.04.1 LTS connected via HDMI to Panasonic TV where the display is cropped on the left hand side of the screen. I&#39;ve changed /boot/firmware/config.txt disable_overscan=0 &amp; it makes no difference. I&#39;ve disabled overscan on the TV &amp; it makes no difference. </p> <p>I&#39;ve searched the internet for solutions, tried them &amp; found no answers, can anybody help me</p> <p>Many many thanks</p> <p>David</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/dattydee"> /u/dattydee </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1htedjk/raspberry_pi5_ubuntu_24041_screen_cropped/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1htedjk/raspberry_pi5_ubuntu_24041_screen_cropped/">[comments]</a></span>

## C4 labs zebra case for rpi5
 - [https://www.reddit.com/r/raspberry_pi/comments/1ht7pvj/c4_labs_zebra_case_for_rpi5](https://www.reddit.com/r/raspberry_pi/comments/1ht7pvj/c4_labs_zebra_case_for_rpi5)
 - RSS feed: $source
 - date published: 2025-01-04T05:47:04+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ht7pvj/c4_labs_zebra_case_for_rpi5/"> <img src="https://preview.redd.it/ye2cnbsy0xae1.jpeg?width=640&amp;crop=smart&amp;auto=webp&amp;s=3cbcf16662acaed5551083749239826f0451af86" alt="C4 labs zebra case for rpi5" title="C4 labs zebra case for rpi5" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I couldn&#39;t find these on their website, so for anyone who needs them. Here you go!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nerdguy1138"> /u/nerdguy1138 </a> <br/> <span><a href="https://i.redd.it/ye2cnbsy0xae1.jpeg">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ht7pvj/c4_labs_zebra_case_for_rpi5/">[comments]</a></span> </td></tr></table>

## I can't start Jellyfin server on Windows ARM
 - [https://www.reddit.com/r/raspberry_pi/comments/1ht1xq6/i_cant_start_jellyfin_server_on_windows_arm](https://www.reddit.com/r/raspberry_pi/comments/1ht1xq6/i_cant_start_jellyfin_server_on_windows_arm)
 - RSS feed: $source
 - date published: 2025-01-04T00:40:32+00:00

<!-- SC_OFF --><div class="md"><p>As the title says. I use the 64 bit arm version but it just opens a console window which immediately closes and the first time it ask to unlock the firewall. I haven&#39;t found anything online. Do you know a solution or I have to wait for update?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UntoTheBreach95"> /u/UntoTheBreach95 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ht1xq6/i_cant_start_jellyfin_server_on_windows_arm/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ht1xq6/i_cant_start_jellyfin_server_on_windows_arm/">[comments]</a></span>

