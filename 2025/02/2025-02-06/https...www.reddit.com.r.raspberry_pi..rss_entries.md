# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Bluetooth keeps failing. Need to reboot.
 - [https://www.reddit.com/r/raspberry_pi/comments/1ijfog8/bluetooth_keeps_failing_need_to_reboot](https://www.reddit.com/r/raspberry_pi/comments/1ijfog8/bluetooth_keeps_failing_need_to_reboot)
 - RSS feed: $source
 - date published: 2025-02-06T22:39:08+00:00

<!-- SC_OFF --><div class="md"><p>I am running raspian 21 Bookworm</p> <p>Every few days my bluetooth LE devices stop being found. Turns out I am getting bluetooth errors. I have to reboot the Pi to get everything working again.</p> <pre><code># systemctl status bluetooth.service ● bluetooth.service - Bluetooth service Loaded: loaded (]8;;file://pi/lib/systemd/system/bluetooth.service/lib/systemd/system/bluetooth.service]8;;; enabled; preset: enabled) Active: active (running) since Thu 2025-02-06 22:14:39 GMT; 3min 35s ago Docs: ]8;;man:bluetoothd(8)man:bluetoothd(8)]8;; Main PID: 17834 (bluetoothd) Status: &quot;Running&quot; Tasks: 1 (limit: 762) CPU: 266ms CGroup: /system.slice/bluetooth.service └─17834 /usr/libexec/bluetooth/bluetoothd Feb 06 22:14:39 pi bluetoothd[17834]: profiles/audio/vcp.c:vcp_init() D-Bus experimental not enabled Feb 06 22:14:39 pi bluetoothd[17834]: src/plugin.c:plugin_init() Failed to init vcp plugin Feb 06 22:14:39 pi bluetoothd[17834]: profiles/audio/mcp

## Problem with the Raspberry Pi AI Camera focus IMX500
 - [https://www.reddit.com/r/raspberry_pi/comments/1ijadsc/problem_with_the_raspberry_pi_ai_camera_focus](https://www.reddit.com/r/raspberry_pi/comments/1ijadsc/problem_with_the_raspberry_pi_ai_camera_focus)
 - RSS feed: $source
 - date published: 2025-02-06T19:02:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I&#39;m having problems focusing the Raspberry Pi Ai camera, I&#39;m using the tool that comes in the box to be able to do the manual focus, but it&#39;s too hard, I&#39;ve already tried in a thousand ways and the lens doesn&#39;t turn, is there anything I&#39;m missing for it to work? I appreciate your help and comments</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/motionl24"> /u/motionl24 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ijadsc/problem_with_the_raspberry_pi_ai_camera_focus/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ijadsc/problem_with_the_raspberry_pi_ai_camera_focus/">[comments]</a></span>

## What's your experience with Raspberry Pi Bluetooth? Any recommendations or tips?
 - [https://www.reddit.com/r/raspberry_pi/comments/1ij9rjo/whats_your_experience_with_raspberry_pi_bluetooth](https://www.reddit.com/r/raspberry_pi/comments/1ij9rjo/whats_your_experience_with_raspberry_pi_bluetooth)
 - RSS feed: $source
 - date published: 2025-02-06T18:37:10+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone!</p> <p>I&#39;ve been working with my Raspberry Pi recently and decided to dive into using Bluetooth for wireless car control using Raspberry Pi 4 and Pico. However, I&#39;m finding the Bluetooth setup a bit tricky and the connection isn&#39;t stable.</p> <p>I wanted to ask the community: What has been your experience with Bluetooth on the Raspberry Pi? Any advice on getting it to work smoothly, or things to watch out for?</p> <p>Also, do you have any Bluetooth adapters or specific configurations you&#39;d recommend to make the process easier? I’d love to hear your recommendations for troubleshooting common issues or improving performance.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Vile_Freq"> /u/Vile_Freq </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ij9rjo/whats_your_experience_with_raspberry_pi_bluetooth/">[link]</a></span> &#32; <span><a href="https://www.reddit.

## Using Raspberry PI as a Link Runner
 - [https://www.reddit.com/r/raspberry_pi/comments/1ij51g2/using_raspberry_pi_as_a_link_runner](https://www.reddit.com/r/raspberry_pi/comments/1ij51g2/using_raspberry_pi_as_a_link_runner)
 - RSS feed: $source
 - date published: 2025-02-06T15:24:13+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m working on a Senior Project and also a proof of concept for my job, where I’m trying to program a Raspberry Pi to function similarly to a Fluke Link Runner. My main goal is to get it to provide <strong>CDP/LLDP discovery</strong> and perform <strong>basic cable testing</strong>.</p> <p>I know there are tools like <code>lldpd</code> for LLDP/CDP, but I’d love to hear if anyone has experience implementing this on a Raspberry Pi in a way that mimics a Link Runner. Specifically:</p> <ul> <li>What software/tools would you recommend for CDP/LLDP packet capture and analysis?</li> <li>Are there any open-source utilities or scripts for cable testing?</li> <li>Any tips on interfacing with an Ethernet PHY for advanced diagnostics?</li> <li>If you’ve built something similar, what challenges did you face?</li> </ul> <p>I appreciate any insights, recommendations, or resources you can share!</p> <p>Thanks!</p> </div><!-- SC_ON --> &#32; sub

