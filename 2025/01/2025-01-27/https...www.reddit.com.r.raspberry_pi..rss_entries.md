# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## [RPI5] flickering hdmi output with vc4-kms-v3d
 - [https://www.reddit.com/r/raspberry_pi/comments/1ibd427/rpi5_flickering_hdmi_output_with_vc4kmsv3d](https://www.reddit.com/r/raspberry_pi/comments/1ibd427/rpi5_flickering_hdmi_output_with_vc4kmsv3d)
 - RSS feed: $source
 - date published: 2025-01-27T16:26:14+00:00

<!-- SC_OFF --><div class="md"><p>I had photo wall project based on a RPI3 driving a 4K display (30hz). Unfortunately the RPI3 itself recently got broken after a voltage spike :( </p> <p>I now received a PI5 and am reconfiguring the setup.</p> <p>I installed a new version of headless armbian (12.9) on the sd card.</p> <p>My software starts using <code>/usr/bin/startx &quot;myapp&quot;</code>. There&#39;s no window manager present, just X11. All this works fine, except there&#39;s an hdmi issue:</p> <p>* when <code>dtoverlay=vc4-kms-v3d</code> is present in <code>/boot/firmware/config.txt</code> I get no image over hdmi at all. My monitor recognizes signal, turns on the screens and then the signal is gone. This process keeps on repeating itself</p> <p>raspinfo shows:</p> <pre><code>Connector 0 (32) HDMI-A-1 (connected) Encoder 0 (31) TMDS Crtc 2 (93) 3840x2160@60.00 594.000 3840/176/88/296/+ 2160/8/10/72/+ 60 (60.00) Plane 2 (82) fb-id: 681 (crtcs: 2) 0,0 3840x2160 -&gt; 0,0 3840x2160

## I build an RGB Matrix with a Web Interface
 - [https://www.reddit.com/r/raspberry_pi/comments/1ibacon/i_build_an_rgb_matrix_with_a_web_interface](https://www.reddit.com/r/raspberry_pi/comments/1ibacon/i_build_an_rgb_matrix_with_a_web_interface)
 - RSS feed: $source
 - date published: 2025-01-27T14:29:50+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ibacon/i_build_an_rgb_matrix_with_a_web_interface/"> <img src="https://b.thumbs.redditmedia.com/_bbUQA9SfguyQ86vtoQovUr49vfqe-ZvX2H_WCI_qUw.jpg" alt="I build an RGB Matrix with a Web Interface" title="I build an RGB Matrix with a Web Interface" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>raspberry pi zero wh</p> <p>rzeller library</p> <p>and a python script with a flask. which shows the gifs on the raspberry pie. the web interface lets you delete gifs, upload new gifs with automatic downscaling to 64x64 pixel(otherwise its very slow). starting and stopping the gif.<br/> basically the python script uses the already given led-image-viewer.</p> <p><a href="https://preview.redd.it/4e4w7g0dsjfe1.png?width=1934&amp;format=png&amp;auto=webp&amp;s=2282f53a070973c9f0017f7189c3f4c3863c4154">https://preview.redd.it/4e4w7g0dsjfe1.png?width=1934&amp;format=png&amp;auto=webp&amp;s=2282f53a070973c9f0017f7189c3f4c3863c

## Is my micro SD corrupted?
 - [https://www.reddit.com/r/raspberry_pi/comments/1ib9ebs/is_my_micro_sd_corrupted](https://www.reddit.com/r/raspberry_pi/comments/1ib9ebs/is_my_micro_sd_corrupted)
 - RSS feed: $source
 - date published: 2025-01-27T13:44:37+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ib9ebs/is_my_micro_sd_corrupted/"> <img src="https://b.thumbs.redditmedia.com/x-bwjUVrs8hjU8RiwTVaG9NAe0-9FiQ0BIqq1GY7pEE.jpg" alt="Is my micro SD corrupted?" title="Is my micro SD corrupted?" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>A few days ago I noticed that I couldn&#39;t connect to my Raspberry Pi 3B, so I plugged a HDMI to my monitor and saw this.</p> <p><a href="https://preview.redd.it/i1xa2f0yijfe1.jpg?width=1280&amp;format=pjpg&amp;auto=webp&amp;s=839cc4fdd8e899577b1344fef20dd9ec16a0579e">https://preview.redd.it/i1xa2f0yijfe1.jpg?width=1280&amp;format=pjpg&amp;auto=webp&amp;s=839cc4fdd8e899577b1344fef20dd9ec16a0579e</a></p> <p>Is it corrupted? I tried to fix it with Microsoft cmd, but it didn&#39;t work.</p> <p>I don&#39;t want to format it because that will require to install and setup everything again.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user

## Dependencies Failing on Boot
 - [https://www.reddit.com/r/raspberry_pi/comments/1ib7uva/dependencies_failing_on_boot](https://www.reddit.com/r/raspberry_pi/comments/1ib7uva/dependencies_failing_on_boot)
 - RSS feed: $source
 - date published: 2025-01-27T12:36:42+00:00

<!-- SC_OFF --><div class="md"><p><strong>First time using a PI , and I don&#39;t know what I did wrong</strong></p> <p><strong>Formatted USB and used pi imager. Using the proper power supply for the PI</strong></p> <p><strong>I am using raspberry pi 4b (2GB)</strong> </p> <p><strong>But when I boot the PI, it reboots twice and on the second boot it shows this</strong></p> <p>FAILED] Failed to start lightdm.service Light Display Manager.</p> <p>[FAILED] Failed to start dbus.service D-Bus System Message Bus.</p> <p>[FAILED] Failed to start cups.service CUPS Scheduler.</p> <p>[FAILED] Failed to start NetworkManager.service Network Manager. [FAILED] Failed to start ssh.service OpenBSD Secure Shell server.</p> <p>[FAILED] Failed to start cups.service CUPS Scheduler.</p> <p>[FAILED] Failed to start dbus.service D-Bus System Message Bus.</p> <p>[FAILED] Failed to start ssh.service OpenBSD Secure Shell server.</p> <p>[FAILED] Failed to start lightdm.service Light Display Manager.</p> <p>[FA

## No Android OS is working for me at all
 - [https://www.reddit.com/r/raspberry_pi/comments/1iawlec/no_android_os_is_working_for_me_at_all](https://www.reddit.com/r/raspberry_pi/comments/1iawlec/no_android_os_is_working_for_me_at_all)
 - RSS feed: $source
 - date published: 2025-01-27T01:45:14+00:00

<!-- SC_OFF --><div class="md"><p>How do <a href="https://www.amazon.com/s?k=android+14+tablet&amp;rh=p_36%3A-5200">these things</a> exist? These no name tablets running android 14 and they can use google apps under $50?</p> <p>Trying to install android OS on anything thats not a phone or tablet is almost impossible. Devices like PC need something stupid like blissOS and raspberryPis need bassOS. Lineage OS is another and Emteria to name a few.</p> <p>Why do you need these gimmik Android ports that almost never work yet these tablets run a genuine Android that has 0 issues? To be fair these gimmik OS run fine on actual phones and tablets, but what are you to do for a raspberryPI or PC that you want to run Android on? Everything i try is all janky and never works properly, and if it does work, it has no google play store.</p> <p>For my Pi4 2gb the following i have tried:</p> <p><strong>BassOS Tablet UI (blissOS):</strong></p> <ul> <li>Doesn&#39;t render google maps graphics</li> <li>W

