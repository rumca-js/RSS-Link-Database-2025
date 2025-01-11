# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Wifi problems on my Zero 2 W
 - [https://www.reddit.com/r/raspberry_pi/comments/1hyi6jg/wifi_problems_on_my_zero_2_w](https://www.reddit.com/r/raspberry_pi/comments/1hyi6jg/wifi_problems_on_my_zero_2_w)
 - RSS feed: $source
 - date published: 2025-01-10T23:28:05+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hyi6jg/wifi_problems_on_my_zero_2_w/"> <img src="https://b.thumbs.redditmedia.com/p-NMHWl9KIP82EgQXONqtT4KCVCNs55g6fjLTXi48_o.jpg" alt="Wifi problems on my Zero 2 W" title="Wifi problems on my Zero 2 W" /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>Dear people,</p> <p>I recently had a wifi problem with my Rpi Zero 2W.</p> <p>Previously my Rpi connected to a powerline adapter and everything worked perfectly!</p> <p>Since this powerline adapter was a bit rickety and slow I wanted to be a new and faster (you know it, the whole house has to be able to watch movies on all floors).</p> <p>All I had to do was, in my opinion, via Putty SSH-s and in the Rpi and via sudo nano /etc/wpa-supplicant/w-supplicant.conf the SSID and change the password to the new one. I noticed that the password entered from my old network was much longer than I normally had to enter to be able to that network but that did not seem import

## Cant connect to my pi3, but it responses to ping
 - [https://www.reddit.com/r/raspberry_pi/comments/1hyhlkc/cant_connect_to_my_pi3_but_it_responses_to_ping](https://www.reddit.com/r/raspberry_pi/comments/1hyhlkc/cant_connect_to_my_pi3_but_it_responses_to_ping)
 - RSS feed: $source
 - date published: 2025-01-10T23:01:13+00:00

<!-- SC_OFF --><div class="md"><p>First I tried to install Home Assistant OS on my pi,, It was succesfull, I was using HDMI to see when its ready and I tried to connect to Home Assistant through my browser on my PC, I tried homeassistant.local:8123 and also with an IP address, none of them work, it couldnt connect, only timed out, but if I ping the Pi through cmd, it gives instant response, like 2ms.</p> <p>After that I thought if docker version would work, I installed Raspberry Pi OS Lite and I tried to connect to it through SSH but it would only give &quot;connection timedout&quot; message, everytime. I tried both, IP and hostname, none of them work, but again if I ping the Pi&#39;s IP address, it gives instant response.</p> <p>I tried to turn off my firewall, tried to add firewall rules for ports, tried to enable UPnP on router, Switched my network to Private instead of Public, changed private network settings on my windows to allow fileshare through lan.</p> <p>I have Windows 11 

## Improving Touchscreen Usability
 - [https://www.reddit.com/r/raspberry_pi/comments/1hy9wme/improving_touchscreen_usability](https://www.reddit.com/r/raspberry_pi/comments/1hy9wme/improving_touchscreen_usability)
 - RSS feed: $source
 - date published: 2025-01-10T17:35:33+00:00

<!-- SC_OFF --><div class="md"><p>I have a Pi4 connected to an external touchscreen, HP E24t G5 FHD Touch Monitor connected via HDMI and USB. Software wise, the machine is only running chromium.</p> <p>The touchscreen behavior is very mouse-like. Clicking works via the screen but dragging does not, and scrolling is done by clicking on the scroll-bar.</p> <p>Can anyone point me to tips on how to configure the interface for a more touch-like experience.</p> <p>- Drag to scroll</p> <p>- Pinch to zoom</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/chicagoandy"> /u/chicagoandy </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hy9wme/improving_touchscreen_usability/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hy9wme/improving_touchscreen_usability/">[comments]</a></span>

## PiVPN port forwarding hell
 - [https://www.reddit.com/r/raspberry_pi/comments/1hy8go5/pivpn_port_forwarding_hell](https://www.reddit.com/r/raspberry_pi/comments/1hy8go5/pivpn_port_forwarding_hell)
 - RSS feed: $source
 - date published: 2025-01-10T16:35:27+00:00

<!-- SC_OFF --><div class="md"><p>I’m fairly sure this is a router port forwarding issue, but want to make sure my PiVPN isn’t the culprit:</p> <p>I have a TP-Link X60 mesh system that’s just old enough to not work as a VPN server. I’ve set up a Raspberry Pi Zero 2 W running PiHole (works great, would highly recommend), NoIp DUC (also works great, I can see my router’s IP when I put in the DDNS address), and PiVPN (why I’m here).</p> <p>I’ve tried both OpenVPN and Wireguard. In both cases, I’m unable to get any clients to connect to VPN. I think I’ve narrowed it down to a port forwarding issue. I’ve selected “custom” as the forwarding type on the router, the Pi as the client, put in the UDP port that I’ve selected for VPN and…nothing. When I use the TP-Link app to scan open ports, they still show closed. My ISP and cable modem do not block any ports. Any idea what I’m doing wrong?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/capn_davey"> /u/c

## Raspberry Pi Connect: "Your device and browser chose to use a mix of Connect’s relay and a peer-to-peer connection." How can I customize this?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hy6i6u/raspberry_pi_connect_your_device_and_browser](https://www.reddit.com/r/raspberry_pi/comments/1hy6i6u/raspberry_pi_connect_your_device_and_browser)
 - RSS feed: $source
 - date published: 2025-01-10T15:10:34+00:00

<!-- SC_OFF --><div class="md"><p>So I just picked up a Pi5-8GB and tossed Raspberry Pi OS on there to tinker with.</p> <p>I found Raspberry Pi Connect to be fairly slow, compared to a Windows desktop with RDP right next to it - nothing to do with processing power, this is just at idle. I tried installing Weston to use RDP, but so far I can&#39;t connect via RDP and all I have is a scrambled terminal window to show for running Weston. Very strange.</p> <p>So anyway, I noticed &quot;Your device and browser chose to use a mix of Connect’s relay and a peer-to-peer connection.&quot; Which I believe is what I want (direct connection, rather than all of my data being relayed through raspberrypi.com&#39;s servers before it gets to me). Running <strong><em>rpi-connect doctor</em></strong> <a href="https://www.raspberrypi.com/documentation/services/connect.html">per the documentation</a>, I see all 4 check marks, so I assume that&#39;s &quot;as good as it gets.&quot; Is there anything else I 

## Help! Menu bar is gone after I tried to add "btm" to menu bar
 - [https://www.reddit.com/r/raspberry_pi/comments/1hy2lpo/help_menu_bar_is_gone_after_i_tried_to_add_btm_to](https://www.reddit.com/r/raspberry_pi/comments/1hy2lpo/help_menu_bar_is_gone_after_i_tried_to_add_btm_to)
 - RSS feed: $source
 - date published: 2025-01-10T11:43:32+00:00

<!-- SC_OFF --><div class="md"><p>I added Chrome and vscode to the menu bar, and everything is good, but then when I add btm to the menu bar, the menu bar is gone, and I cannot bring it back; any clue?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ender-Wang"> /u/Ender-Wang </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hy2lpo/help_menu_bar_is_gone_after_i_tried_to_add_btm_to/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hy2lpo/help_menu_bar_is_gone_after_i_tried_to_add_btm_to/">[comments]</a></span>

## What uses would the 16 gb pi have?
 - [https://www.reddit.com/r/raspberry_pi/comments/1hxuhaz/what_uses_would_the_16_gb_pi_have](https://www.reddit.com/r/raspberry_pi/comments/1hxuhaz/what_uses_would_the_16_gb_pi_have)
 - RSS feed: $source
 - date published: 2025-01-10T02:45:33+00:00

<!-- SC_OFF --><div class="md"><p>I’m actually curious because even if you need the amount of ram, couldn’t you just get a cheap mini-desktop or nvidia jetson? I get power consumption, but what other uses would there be?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/hotmanj0sh28"> /u/hotmanj0sh28 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hxuhaz/what_uses_would_the_16_gb_pi_have/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hxuhaz/what_uses_would_the_16_gb_pi_have/">[comments]</a></span>

