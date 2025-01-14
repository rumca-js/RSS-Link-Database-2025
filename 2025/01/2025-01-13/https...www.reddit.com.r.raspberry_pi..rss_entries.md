# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Play Games on the Meshtastic with a Pi
 - [https://www.reddit.com/r/raspberry_pi/comments/1i0s75y/play_games_on_the_meshtastic_with_a_pi](https://www.reddit.com/r/raspberry_pi/comments/1i0s75y/play_games_on_the_meshtastic_with_a_pi)
 - RSS feed: $source
 - date published: 2025-01-13T23:39:43+00:00

<!-- SC_OFF --><div class="md"><p>Check out my modular BBS built on Meshtastic and Pi! This project lets you navigate menus and play games like Tic Tac Toe and an Escape Room, all live on a mesh network with no internet required. It’s powered by Raspberry Pi and designed to showcase how games and modular systems can run seamlessly over decentralized networks. Perfect for fans of mesh networking, retro BBS vibes, and creative tech projects. Would love to hear your thoughts or ideas for more games to add! <a href="https://www.tiktok.com/@veggievampire/video/7459528609775144238">https://www.tiktok.com/@veggievampire/video/7459528609775144238</a> <a href="https://github.com/VeggieVampire/MeshBoard">https://github.com/VeggieVampire/MeshBoard</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/VeggieVampire"> /u/VeggieVampire </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1i0s75y/play_games_on_the_meshtastic_with_a_pi/">[link

## Is there something better than McWhorter to learn about RPi
 - [https://www.reddit.com/r/raspberry_pi/comments/1i0cjkj/is_there_something_better_than_mcwhorter_to_learn](https://www.reddit.com/r/raspberry_pi/comments/1i0cjkj/is_there_something_better_than_mcwhorter_to_learn)
 - RSS feed: $source
 - date published: 2025-01-13T12:10:11+00:00

<!-- SC_OFF --><div class="md"><p>I really liked his tutorials on Arduino, but in his tutorials on RPi Im feeling lost.</p> <p>He seems to be assuming that people know a LOT more than i do.</p> <p>I have 2 questions:</p> <ol> <li><p>Is there a better resource for learning RPi?</p></li> <li><p>Am i an idiot, or does he just not explain anything about how to actually accomplish the &quot;homework&quot;?</p></li> </ol> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/feraljohn"> /u/feraljohn </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1i0cjkj/is_there_something_better_than_mcwhorter_to_learn/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1i0cjkj/is_there_something_better_than_mcwhorter_to_learn/">[comments]</a></span>

## Pi Zero 2W Wifi Issues
 - [https://www.reddit.com/r/raspberry_pi/comments/1i081w4/pi_zero_2w_wifi_issues](https://www.reddit.com/r/raspberry_pi/comments/1i081w4/pi_zero_2w_wifi_issues)
 - RSS feed: $source
 - date published: 2025-01-13T06:38:26+00:00

<!-- SC_OFF --><div class="md"><p>Hello,</p> <p>I&#39;m facing an issue where my Zero 2W does not connect to Wifi, every time my router reboots. The only way to fix it is to power cycle the Pi, after the router is rebooted. Please note that it works fine if I reboot the Pi itself. </p> <p>I have another Pi 3B which doesn&#39;t have this issue at all. I&#39;ve tried every possible fix found on Google, as well as tried the suggestions from ChatGPT (wpa_supplicant updates, cron job to check wifi connectivity and restart interface, etc.), but nothing seems to work so far.</p> <p>I&#39;m running the Pi headless, and don&#39;t have a mini HDMI cable at the moment, so can&#39;t see what&#39;s going on in the Pi during router reboot.</p> <p>I&#39;ve installed the recommended 64-bit Raspbian OS, and everything is upto-date.</p> <p>Appreciate any help!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/retrogamer_gj"> /u/retrogamer_gj </a> <br/> <span><a hre

## Raspberry Pi 5 & Adafruit Ultimate GPS
 - [https://www.reddit.com/r/raspberry_pi/comments/1i069d3/raspberry_pi_5_adafruit_ultimate_gps](https://www.reddit.com/r/raspberry_pi/comments/1i069d3/raspberry_pi_5_adafruit_ultimate_gps)
 - RSS feed: $source
 - date published: 2025-01-13T04:44:12+00:00

<!-- SC_OFF --><div class="md"><p>Im using a raspberry pi 5 (bookworm OS) and when running my code to send back latitude and longitude information it only returns &quot;Latitude: 0.0, Longitude: 0.0&quot;. What do I need to do to fix this?</p> <p>Heres my code:</p> <p>import serial</p> <p>import pynmea2</p> <p>try:</p> <p># Configure the serial connection</p> <p>gps_serial = serial.Serial(</p> <p>port=&#39;/dev/serial0&#39;, # Replace with your UART port</p> <p>baudrate=9600, # GPS baud rate</p> <p>timeout=1 # Timeout in seconds</p> <p>)</p> <p>print(&quot;Reading GPS data...&quot;)</p> <p>while True:</p> <p># Read a line of data from the GPS</p> <p>gps_data = gps_serial.readline().decode(&#39;ascii&#39;, errors=&#39;replace&#39;).strip()</p> <p>if gps_data.startswith(&#39;$GPGGA&#39;) or gps_data.startswith(&#39;$GPRMC&#39;):</p> <p>try:</p> <p>nmea_sentence = pynmea2.parse(gps_data)</p> <p>print(f&quot;Latitude: {nmea_sentence.latitude}, Longitude: {nmea_sentence.longitude}&quot;)<

## Enabling More SDA/SCL Ports
 - [https://www.reddit.com/r/raspberry_pi/comments/1i03ol2/enabling_more_sdascl_ports](https://www.reddit.com/r/raspberry_pi/comments/1i03ol2/enabling_more_sdascl_ports)
 - RSS feed: $source
 - date published: 2025-01-13T02:22:26+00:00

<!-- SC_OFF --><div class="md"><p>I’m trying to use 2 SDA &amp; SCL devices at once on my raspberry pi 5 (bookworm OS) but there’s only a single spot for one of my devices, is there anyway to enable more of the GPIO pins to be SDA &amp; SCL compatible? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/MudFront1456"> /u/MudFront1456 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1i03ol2/enabling_more_sdascl_ports/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1i03ol2/enabling_more_sdascl_ports/">[comments]</a></span>

