# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Built an AI Photo Frame with Raspberry Pi Zero 2 W and an E-ink Display (Github link in comments)
 - [https://www.reddit.com/r/raspberry_pi/comments/1ipgpxp/built_an_ai_photo_frame_with_raspberry_pi_zero_2](https://www.reddit.com/r/raspberry_pi/comments/1ipgpxp/built_an_ai_photo_frame_with_raspberry_pi_zero_2)
 - RSS feed: $source
 - date published: 2025-02-14T18:03:18+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ipgpxp/built_an_ai_photo_frame_with_raspberry_pi_zero_2/"> <img src="https://external-preview.redd.it/anhkcHA5dG45NWplMVPs3gXVth-uRRyYfClQIHrZn4tt23a_OhfTn1SPq1bT.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=a7dd5f61079e2f64d703e42507302ada527c4d68" alt="Built an AI Photo Frame with Raspberry Pi Zero 2 W and an E-ink Display (Github link in comments)" title="Built an AI Photo Frame with Raspberry Pi Zero 2 W and an E-ink Display (Github link in comments)" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Usteri"> /u/Usteri </a> <br/> <span><a href="https://v.redd.it/ixoi26tn95je1">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ipgpxp/built_an_ai_photo_frame_with_raspberry_pi_zero_2/">[comments]</a></span> </td></tr></table>

## DMX: RS485 Hat vs Enttec USB device
 - [https://www.reddit.com/r/raspberry_pi/comments/1ipbp76/dmx_rs485_hat_vs_enttec_usb_device](https://www.reddit.com/r/raspberry_pi/comments/1ipbp76/dmx_rs485_hat_vs_enttec_usb_device)
 - RSS feed: $source
 - date published: 2025-02-14T14:25:35+00:00

<!-- SC_OFF --><div class="md"><p>I want to send DMX from a Raspberry Pi, and traditionally I&#39;ve just used one of Enttec&#39;s DMX USB Pro devices and that has worked fine. But for a new project, space is at a premium and I was thinking of using one of the RS485 hats (specifically, I have the <a href="https://www.waveshare.com/rs485-can-hat.htm">Waveshare one</a>). I&#39;ve tested it with a Python script and it works fine for simple tests. The relevant code </p> <pre><code>dmx_packet = bytearray([0] + dmx_data) # Start Code (0) + 512 values # DMX BREAK (low for 88µs) ser.break_condition = True time.sleep(0.000088) # 88µs ser.break_condition = False # Mark After Break (MAB) (high for 8µs) time.sleep(0.000008) # 8µs # Send DMX data ser.write(dmx_packet) ser.flush() </code></pre> <p>Is this a bad idea? What pitfalls might I face here? </p> <p>I&#39;d like to use a Zero 2 W, but I&#39;m open to using a 5 if performance would be a cause for concern.</p> <p>The other options is to use 

## HyperHDR not working
 - [https://www.reddit.com/r/raspberry_pi/comments/1ip85b2/hyperhdr_not_working](https://www.reddit.com/r/raspberry_pi/comments/1ip85b2/hyperhdr_not_working)
 - RSS feed: $source
 - date published: 2025-02-14T11:01:59+00:00

<!-- SC_OFF --><div class="md"><p>Hey everyone,</p> <p>I’m trying to set up an ambilight set up for my tv but can’t get things to work properly.</p> <p>I have hyperhdr downloaded and running on a raspberry pi zero 2w and I can see the capture card input online but I don’t have any sing of life from my led strips.</p> <p>I’m using ws2815’s (input 12v) with a step down converter (output 5v) so my ground is all common. I’m going out of gpio 18 on the pi but see nothing on the lights. </p> <p>Any insight would be greatly appreciated!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Horror_Skill6576"> /u/Horror_Skill6576 </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip85b2/hyperhdr_not_working/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip85b2/hyperhdr_not_working/">[comments]</a></span>

## Unable to sync time with timesyncd
 - [https://www.reddit.com/r/raspberry_pi/comments/1ip7qml/unable_to_sync_time_with_timesyncd](https://www.reddit.com/r/raspberry_pi/comments/1ip7qml/unable_to_sync_time_with_timesyncd)
 - RSS feed: $source
 - date published: 2025-02-14T10:32:17+00:00

<!-- SC_OFF --><div class="md"><p>Hello, I encounter some problem with my raspberry pi 4.<br/> It is completely unable to get a response from an ntp server even though they are pingable.<br/> I try a lot of thing found online like changing the default ntp server, restarting the daemon, uncommenting the FallbackNTP in the config file etc... nothing worked.</p> <p>When I look to <code>systemctl status systemd-timesyncd.service</code>, it tries to connect to all fallback server but it always display messages like <code>Time out waiting for reply from</code> <a href="http://192.33.214.57:123"><code>192.33.214.57:123</code></a> <code>(1.debian.pool.ntp.org)</code></p> <p>If someone have any advice or clue about this it will be very nice </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/_Voxanimus_"> /u/_Voxanimus_ </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip7qml/unable_to_sync_time_with_timesyncd/">[link]</a></span> &#3

## On screen keyboard on raspbian lite
 - [https://www.reddit.com/r/raspberry_pi/comments/1ip4p7l/on_screen_keyboard_on_raspbian_lite](https://www.reddit.com/r/raspberry_pi/comments/1ip4p7l/on_screen_keyboard_on_raspbian_lite)
 - RSS feed: $source
 - date published: 2025-02-14T06:46:22+00:00

<!-- SC_OFF --><div class="md"><p>Im trying to make an ipod but only for spotify thing and im gonna use spotify-tui <a href="https://github.com/Rigellute/spotify-tui">https://github.com/Rigellute/spotify-tui</a> And in trying to make a on screen keyboard overlay so could yall help me? </p> <p>(I cant code 😭)</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/yogoplay"> /u/yogoplay </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip4p7l/on_screen_keyboard_on_raspbian_lite/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip4p7l/on_screen_keyboard_on_raspbian_lite/">[comments]</a></span>

## A clock that tells the time using book quotes.
 - [https://www.reddit.com/r/raspberry_pi/comments/1ip2oms/a_clock_that_tells_the_time_using_book_quotes](https://www.reddit.com/r/raspberry_pi/comments/1ip2oms/a_clock_that_tells_the_time_using_book_quotes)
 - RSS feed: $source
 - date published: 2025-02-14T04:38:52+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1ip2oms/a_clock_that_tells_the_time_using_book_quotes/"> <img src="https://b.thumbs.redditmedia.com/w2aUdq0pKC4WGT_GuZSn6RXtPHviewtZfIJ4vFTOAss.jpg" alt="A clock that tells the time using book quotes." title="A clock that tells the time using book quotes." /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Head-Community7540"> /u/Head-Community7540 </a> <br/> <span><a href="https://www.reddit.com/gallery/1ip2oms">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1ip2oms/a_clock_that_tells_the_time_using_book_quotes/">[comments]</a></span> </td></tr></table>

