# Source:Emulation, URL:https://www.reddit.com/r/emulation/.rss, language:

## Play! PS2 emulator 2025 progress report! - more playable games, new "game config" system
 - [https://www.reddit.com/r/emulation/comments/1ig1yr5/play_ps2_emulator_2025_progress_report_more](https://www.reddit.com/r/emulation/comments/1ig1yr5/play_ps2_emulator_2025_progress_report_more)
 - RSS feed: $source
 - date published: 2025-02-02T17:09:09+00:00

<!-- SC_OFF --><div class="md"><ul> <li><a href="https://www.patreon.com/posts/121336482">January Report</a></li> <li><a href="https://purei.org/">Website</a></li> </ul> <h1>Game Config System;</h1> <p><strong>The tl;dr is:</strong> it&#39;s a per game patch system loading specific patches from an external file. This replaces the older &quot;patches.xml&quot; file in play!&#39;s directory with a new &quot;GameConfig.xml&quot;, but in general the file itself isn&#39;t that special. What&#39;s special is the new changes on the emulator itself to support changing the &quot;rounding mode&quot; and finding the correct memory block where idle skips happen, as well as some specific addresses where &quot;something weird&quot; can happen to make a game hang or behave incorrectly. The rounding mode changes allow us to change the results of some calculations to get a closer result to what the game expects and needs to work in some points (due to how the PS2 CPU works, you won&#39;t always get t

