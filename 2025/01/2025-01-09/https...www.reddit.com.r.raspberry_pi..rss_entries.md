# Source:Raspberry Pi - More than just magic mirrors and kodi!, URL:https://www.reddit.com/r/raspberry_pi/.rss, language:en

## Help with CM5 custom devicetree overlay for audio codec featuring i2s and i2c
 - [https://www.reddit.com/r/raspberry_pi/comments/1hxal5n/help_with_cm5_custom_devicetree_overlay_for_audio](https://www.reddit.com/r/raspberry_pi/comments/1hxal5n/help_with_cm5_custom_devicetree_overlay_for_audio)
 - RSS feed: $source
 - date published: 2025-01-09T11:15:31+00:00

<!-- SC_OFF --><div class="md"><p>I have an audio codec breakout board featuring a Texas Instruments TLV320ADC5140 connected to 4 microphones. I&#39;m hoping to connect this to my CM5 via the CM4 IO board however, the main issue I have is that I have never worked with devicetree overlays before and therefore have no idea where to begin.</p> <p>So far, I&#39;ve deduced that I need to wire the breakout board to the CM5 as follows:</p> <table><thead> <tr> <th align="left">TLV320ADC5140</th> <th align="left">CM5</th> </tr> </thead><tbody> <tr> <td align="left">SDOUT</td> <td align="left">GPIO20 (I2S0_SDI)</td> </tr> <tr> <td align="left">BCLK</td> <td align="left">GPIO18 (I2S0_SCLK)</td> </tr> <tr> <td align="left">FSYNC</td> <td align="left">GPIO19 (I2S0_WS)</td> </tr> <tr> <td align="left">SCL_MOSI</td> <td align="left">GPIO9 (I2C0_SCL)</td> </tr> <tr> <td align="left">SDA_SSZ</td> <td align="left">GPIO8 (I2C0_SDA)</td> </tr> </tbody></table> <p>I&#39;ve pulled the relevant branch of t

## I finally made a NAS with my raspberry pi 4b 8gb
 - [https://www.reddit.com/r/raspberry_pi/comments/1hx97oa/i_finally_made_a_nas_with_my_raspberry_pi_4b_8gb](https://www.reddit.com/r/raspberry_pi/comments/1hx97oa/i_finally_made_a_nas_with_my_raspberry_pi_4b_8gb)
 - RSS feed: $source
 - date published: 2025-01-09T09:35:03+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/raspberry_pi/comments/1hx97oa/i_finally_made_a_nas_with_my_raspberry_pi_4b_8gb/"> <img src="https://preview.redd.it/w50tzbdcixbe1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=110709b6ec6f19be425e86bb5ed3ebaf23d6b20a" alt="I finally made a NAS with my raspberry pi 4b 8gb" title="I finally made a NAS with my raspberry pi 4b 8gb" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/nosamsti"> /u/nosamsti </a> <br/> <span><a href="https://i.redd.it/w50tzbdcixbe1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx97oa/i_finally_made_a_nas_with_my_raspberry_pi_4b_8gb/">[comments]</a></span> </td></tr></table>

## 16GB Raspberry Pi 5 on sale now at $120 (USD)
 - [https://www.reddit.com/r/raspberry_pi/comments/1hx869c/16gb_raspberry_pi_5_on_sale_now_at_120_usd](https://www.reddit.com/r/raspberry_pi/comments/1hx869c/16gb_raspberry_pi_5_on_sale_now_at_120_usd)
 - RSS feed: $source
 - date published: 2025-01-09T08:14:03+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/KindOne"> /u/KindOne </a> <br/> <span><a href="https://www.raspberrypi.com/news/16gb-raspberry-pi-5-on-sale-now-at-120/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx869c/16gb_raspberry_pi_5_on_sale_now_at_120_usd/">[comments]</a></span>

## Not enough Voltage with 3.5 inch TFT display
 - [https://www.reddit.com/r/raspberry_pi/comments/1hx71v5/not_enough_voltage_with_35_inch_tft_display](https://www.reddit.com/r/raspberry_pi/comments/1hx71v5/not_enough_voltage_with_35_inch_tft_display)
 - RSS feed: $source
 - date published: 2025-01-09T06:51:18+00:00

<!-- SC_OFF --><div class="md"><p>So I have a rpi 3b+ and i just got a 3.5 inch tft display and plugged it with the gpio pins. I installed the driver for the display and I am using a raspberry pi 15V cable which works fine without the display. But once i use the 3.5 inch display and not the hdmi, the lightning bolt comes. What do I do? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Biomathematician"> /u/Biomathematician </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx71v5/not_enough_voltage_with_35_inch_tft_display/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx71v5/not_enough_voltage_with_35_inch_tft_display/">[comments]</a></span>

## For anyone who want active any fan with the Pi 5
 - [https://www.reddit.com/r/raspberry_pi/comments/1hx25mo/for_anyone_who_want_active_any_fan_with_the_pi_5](https://www.reddit.com/r/raspberry_pi/comments/1hx25mo/for_anyone_who_want_active_any_fan_with_the_pi_5)
 - RSS feed: $source
 - date published: 2025-01-09T02:22:40+00:00

<!-- SC_OFF --><div class="md"><p>from enum import Enum import time</p> <p>TEMP_PATH = &quot;/sys/class/thermal/thermal_zone0/temp&quot; FAN_PATH = &quot;/sys/class/thermal/cooling_device0/cur_state&quot;</p> <p>class FanSpeed(Enum): OFF = 0 LOW = 1 MEDIUM = 2 HIGH = 3 FULL = 4</p> <p>def main(): start = time.time() while time.time() - start &lt; 59: temp = get_temp() temp -= 25 # Reduce the temperature by 25 degrees print(f&quot;Current temperature: {temp}°C&quot;) # Display current temperature if temp &gt;= 10 and temp &lt; 15: speed = FanSpeed.LOW elif temp &gt;= 15 and temp &lt; 20: speed = FanSpeed.MEDIUM elif temp &gt;= 20 and temp &lt; 25: speed = FanSpeed.HIGH elif temp &gt;= 25: speed = FanSpeed.FULL else: speed = FanSpeed.OFF set_fan_speed(speed) time.sleep(2)</p> <p>def get_temp() -&gt; int: with open(TEMP_PATH, &quot;r&quot;) as f: data = f.read() return int(data) // 1000</p> <p>def set_fan_speed(speed: FanSpeed): with open(FAN_PATH, &quot;w&quot;) as f: f.write(str(speed

## shairport-sync working but only through audio jack how do I get my pip to share audio through HDMI
 - [https://www.reddit.com/r/raspberry_pi/comments/1hx19u9/shairportsync_working_but_only_through_audio_jack](https://www.reddit.com/r/raspberry_pi/comments/1hx19u9/shairportsync_working_but_only_through_audio_jack)
 - RSS feed: $source
 - date published: 2025-01-09T01:42:01+00:00

<!-- SC_OFF --><div class="md"><p>Among a few other things I am using my Pi for I am giving my old sound system the ability to be airplay audio to from my appletv. Right now I can only get the audio jack to work which is on the front of my stereo which means I can&#39;t close the closet door. Perhaps if there is not a way to share audio via HDMI maybe there is a way to share my wifi connection to the yahama receivers ethernet port. Let me know what I should try.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Cultural_Stuffin"> /u/Cultural_Stuffin </a> <br/> <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx19u9/shairportsync_working_but_only_through_audio_jack/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/raspberry_pi/comments/1hx19u9/shairportsync_working_but_only_through_audio_jack/">[comments]</a></span>
