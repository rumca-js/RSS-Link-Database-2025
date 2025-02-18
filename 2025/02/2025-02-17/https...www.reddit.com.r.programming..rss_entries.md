# Source:programming, URL:https://www.reddit.com/r/programming/.rss, language:

## Has anybody have any idea on what I am facing? Max retries exceeded with url
 - [https://www.reddit.com/r/programming/comments/1iry28y/has_anybody_have_any_idea_on_what_i_am_facing_max](https://www.reddit.com/r/programming/comments/1iry28y/has_anybody_have_any_idea_on_what_i_am_facing_max)
 - RSS feed: $source
 - date published: 2025-02-17T23:18:29+00:00

<!-- SC_OFF --><div class="md"><p>This is my code:</p> <p>—</p> <p>import requests from requests.adapters import HTTPAdapter from urllib3.util.retry import Retry</p> <p>session = requests.Session() retry = Retry(connect=3, backoff_factor=0.5) adapter = HTTPAdapter(max_retries=retry) session.mount(&#39;http://&#39;, adapter) session.mount(&#39;https://&#39;, adapter)</p> <p>response = session.get(url, headers=myHeaders, data=myData, verify=False, timeout=3000)</p> <p>—</p> <p>A simple request but I am getting this error when requesting a ASP page that should return a xml:</p> <p>HTTPSConnectionPool(host=&#39;&#39;, port=443) - (Caused by ProxyError(&#39;Cannot connect to proxy.&#39;, RemoteDisconnected(&#39;Remote end closed connection w ithout response&#39;)))</p> <p>It lasts about 2 minutes, retries but does not return anything…</p> <p>If someone more experienced could help me I would appreciate.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/

## First Look at JetBrains Junie Autonomous AI Agent
 - [https://www.reddit.com/r/programming/comments/1iry1ct/first_look_at_jetbrains_junie_autonomous_ai_agent](https://www.reddit.com/r/programming/comments/1iry1ct/first_look_at_jetbrains_junie_autonomous_ai_agent)
 - RSS feed: $source
 - date published: 2025-02-17T23:17:25+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/dmcg"> /u/dmcg </a> <br/> <span><a href="https://youtu.be/Ti-JGNvRDo4">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1iry1ct/first_look_at_jetbrains_junie_autonomous_ai_agent/">[comments]</a></span>

## The C3 Programming Language - version 0.6.7 released
 - [https://www.reddit.com/r/programming/comments/1irxwio/the_c3_programming_language_version_067_released](https://www.reddit.com/r/programming/comments/1irxwio/the_c3_programming_language_version_067_released)
 - RSS feed: $source
 - date published: 2025-02-17T23:11:38+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Nuoji"> /u/Nuoji </a> <br/> <span><a href="https://c3.handmade.network/blog/p/8994-it%2527s_february_and_time_for_a_new_c3_release__0.6.7">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irxwio/the_c3_programming_language_version_067_released/">[comments]</a></span>

## Debugging An Undebuggable App
 - [https://www.reddit.com/r/programming/comments/1irxpv2/debugging_an_undebuggable_app](https://www.reddit.com/r/programming/comments/1irxpv2/debugging_an_undebuggable_app)
 - RSS feed: $source
 - date published: 2025-02-17T23:03:44+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/DreamyRustacean"> /u/DreamyRustacean </a> <br/> <span><a href="https://bryce.co/undebuggable/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irxpv2/debugging_an_undebuggable_app/">[comments]</a></span>

## Image to video api
 - [https://www.reddit.com/r/programming/comments/1irtrb0/image_to_video_api](https://www.reddit.com/r/programming/comments/1irtrb0/image_to_video_api)
 - RSS feed: $source
 - date published: 2025-02-17T20:21:51+00:00

<!-- SC_OFF --><div class="md"><p>How are you guys using the imageToVideo api provided by stability.ai? My results are bad, and the output exapmples they provide seems to be too good to be true? Tips/tricks and what other AI- api’s do you recommend?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Fit-History-6559"> /u/Fit-History-6559 </a> <br/> <span><a href="https://stability.ai">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irtrb0/image_to_video_api/">[comments]</a></span>

## How do you manage and organize reusable code snippets across projects? GitHU doesn't count
 - [https://www.reddit.com/r/programming/comments/1irt4zp/how_do_you_manage_and_organize_reusable_code](https://www.reddit.com/r/programming/comments/1irt4zp/how_do_you_manage_and_organize_reusable_code)
 - RSS feed: $source
 - date published: 2025-02-17T19:57:44+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Pack2831"> /u/No-Pack2831 </a> <br/> <span><a href="https://github.com/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irt4zp/how_do_you_manage_and_organize_reusable_code/">[comments]</a></span>

## How hash table works under the hood?
 - [https://www.reddit.com/r/programming/comments/1irrx09/how_hash_table_works_under_the_hood](https://www.reddit.com/r/programming/comments/1irrx09/how_hash_table_works_under_the_hood)
 - RSS feed: $source
 - date published: 2025-02-17T19:09:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/NoBarber9673"> /u/NoBarber9673 </a> <br/> <span><a href="https://medium.com/@volodymyrpotiichuk/why-hash-tables-65483b7dbf9c">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irrx09/how_hash_table_works_under_the_hood/">[comments]</a></span>

## AI Content Moderator - Why and how to build one with Gemini 1.5
 - [https://www.reddit.com/r/programming/comments/1irr0dj/ai_content_moderator_why_and_how_to_build_one](https://www.reddit.com/r/programming/comments/1irr0dj/ai_content_moderator_why_and_how_to_build_one)
 - RSS feed: $source
 - date published: 2025-02-17T18:33:51+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Permit_io"> /u/Permit_io </a> <br/> <span><a href="https://www.permit.io/blog/ai-powered-content-moderation-gemini-and-nextjs">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irr0dj/ai_content_moderator_why_and_how_to_build_one/">[comments]</a></span>

## Getting Buy-In: Overcoming Larman's Law • Allen Holub
 - [https://www.reddit.com/r/programming/comments/1irqz5r/getting_buyin_overcoming_larmans_law_allen_holub](https://www.reddit.com/r/programming/comments/1irqz5r/getting_buyin_overcoming_larmans_law_allen_holub)
 - RSS feed: $source
 - date published: 2025-02-17T18:32:32+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/goto-con"> /u/goto-con </a> <br/> <span><a href="https://youtu.be/XwhF_xbVpIQ">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irqz5r/getting_buyin_overcoming_larmans_law_allen_holub/">[comments]</a></span>

## How I Stole Your ChatGPT API Keys
 - [https://www.reddit.com/r/programming/comments/1irq0mw/how_i_stole_your_chatgpt_api_keys](https://www.reddit.com/r/programming/comments/1irq0mw/how_i_stole_your_chatgpt_api_keys)
 - RSS feed: $source
 - date published: 2025-02-17T17:55:52+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/jacobs-tech-tavern"> /u/jacobs-tech-tavern </a> <br/> <span><a href="https://blog.jacobstechtavern.com/p/how-i-stole-your-api-keys">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irq0mw/how_i_stole_your_chatgpt_api_keys/">[comments]</a></span>

## Engineering With Java: Digest #46
 - [https://www.reddit.com/r/programming/comments/1irp7cp/engineering_with_java_digest_46](https://www.reddit.com/r/programming/comments/1irp7cp/engineering_with_java_digest_46)
 - RSS feed: $source
 - date published: 2025-02-17T17:23:39+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Educational-Ad2036"> /u/Educational-Ad2036 </a> <br/> <span><a href="https://javabulletin.substack.com/p/engineering-with-java-digest-46">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irp7cp/engineering_with_java_digest_46/">[comments]</a></span>

## MacOS Targeted by New XCSSET Malware Variant That Infects Xcode Projects
 - [https://www.reddit.com/r/programming/comments/1irot80/macos_targeted_by_new_xcsset_malware_variant_that](https://www.reddit.com/r/programming/comments/1irot80/macos_targeted_by_new_xcsset_malware_variant_that)
 - RSS feed: $source
 - date published: 2025-02-17T17:08:15+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Dark-Marc"> /u/Dark-Marc </a> <br/> <span><a href="https://www.reddit.com/r/pwnhub/comments/1iropmo/microsoft_warns_of_new_xcsset_macos_malware/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irot80/macos_targeted_by_new_xcsset_malware_variant_that/">[comments]</a></span>

## Understanding Yoneda
 - [https://www.reddit.com/r/programming/comments/1irokr7/understanding_yoneda](https://www.reddit.com/r/programming/comments/1irokr7/understanding_yoneda)
 - RSS feed: $source
 - date published: 2025-02-17T16:59:05+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/andarmanik"> /u/andarmanik </a> <br/> <span><a href="https://bartoszmilewski.com/2013/05/15/understanding-yoneda/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irokr7/understanding_yoneda/">[comments]</a></span>

## I Built My Own AI Code Assistant with DeepSeek & LangChain!
 - [https://www.reddit.com/r/programming/comments/1iro8iz/i_built_my_own_ai_code_assistant_with_deepseek](https://www.reddit.com/r/programming/comments/1iro8iz/i_built_my_own_ai_code_assistant_with_deepseek)
 - RSS feed: $source
 - date published: 2025-02-17T16:45:00+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Special_Community179"> /u/Special_Community179 </a> <br/> <span><a href="https://www.youtube.com/watch?v=7GAKB21lxyg&amp;list=PLp01ObP3udmq2quR-RfrX4zNut_t_kNot">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1iro8iz/i_built_my_own_ai_code_assistant_with_deepseek/">[comments]</a></span>

## ASMR Programming - Calculator App Coding - No Talking
 - [https://www.reddit.com/r/programming/comments/1irnc7j/asmr_programming_calculator_app_coding_no_talking](https://www.reddit.com/r/programming/comments/1irnc7j/asmr_programming_calculator_app_coding_no_talking)
 - RSS feed: $source
 - date published: 2025-02-17T16:08:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/No-Bee3407"> /u/No-Bee3407 </a> <br/> <span><a href="https://youtu.be/CglvFDtfyS8">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irnc7j/asmr_programming_calculator_app_coding_no_talking/">[comments]</a></span>

## How to document Event-Driven Architecture
 - [https://www.reddit.com/r/programming/comments/1irn3d3/how_to_document_eventdriven_architecture](https://www.reddit.com/r/programming/comments/1irn3d3/how_to_document_eventdriven_architecture)
 - RSS feed: $source
 - date published: 2025-02-17T15:58:16+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Adventurous-Salt8514"> /u/Adventurous-Salt8514 </a> <br/> <span><a href="https://www.architecture-weekly.com/p/documenting-event-driven-architecture">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irn3d3/how_to_document_eventdriven_architecture/">[comments]</a></span>

## Free Online Book for ASP.NET Razor Pages + htmx
 - [https://www.reddit.com/r/programming/comments/1irm275/free_online_book_for_aspnet_razor_pages_htmx](https://www.reddit.com/r/programming/comments/1irm275/free_online_book_for_aspnet_razor_pages_htmx)
 - RSS feed: $source
 - date published: 2025-02-17T15:13:35+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/chriswoodruff"> /u/chriswoodruff </a> <br/> <span><a href="https://aspnet-htmx.com/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irm275/free_online_book_for_aspnet_razor_pages_htmx/">[comments]</a></span>

## Built a WhatsApp Dashboard with React, D3.js & Tailwind – Feedback appreciated
 - [https://www.reddit.com/r/programming/comments/1irlpd5/built_a_whatsapp_dashboard_with_react_d3js](https://www.reddit.com/r/programming/comments/1irlpd5/built_a_whatsapp_dashboard_with_react_d3js)
 - RSS feed: $source
 - date published: 2025-02-17T14:58:39+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/frieVoe"> /u/frieVoe </a> <br/> <span><a href="http://whatsapp-dashboard.friedrichvoelkers.de/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irlpd5/built_a_whatsapp_dashboard_with_react_d3js/">[comments]</a></span>

## Go 1.24: Game-Changing Updates Every Go Developer Should Know
 - [https://www.reddit.com/r/programming/comments/1irlmyx/go_124_gamechanging_updates_every_go_developer](https://www.reddit.com/r/programming/comments/1irlmyx/go_124_gamechanging_updates_every_go_developer)
 - RSS feed: $source
 - date published: 2025-02-17T14:55:34+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/toxic2soul"> /u/toxic2soul </a> <br/> <span><a href="https://medium.com/@linkwithjoydeep/go-1-24-game-changing-updates-every-go-developer-should-know-96a502699d5d">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irlmyx/go_124_gamechanging_updates_every_go_developer/">[comments]</a></span>

## Unevictable Kubernetes Nodes And Smart Pod Placement
 - [https://www.reddit.com/r/programming/comments/1irlgmb/unevictable_kubernetes_nodes_and_smart_pod](https://www.reddit.com/r/programming/comments/1irlgmb/unevictable_kubernetes_nodes_and_smart_pod)
 - RSS feed: $source
 - date published: 2025-02-17T14:47:37+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/codingdecently"> /u/codingdecently </a> <br/> <span><a href="https://overcast.blog/unevictable-kubernetes-nodes-and-smart-pod-placement-a47e53182fdb">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irlgmb/unevictable_kubernetes_nodes_and_smart_pod/">[comments]</a></span>

## How to segment X-Ray lungs using U-Net and Tensorflow
 - [https://www.reddit.com/r/programming/comments/1irlghm/how_to_segment_xray_lungs_using_unet_and](https://www.reddit.com/r/programming/comments/1irlghm/how_to_segment_xray_lungs_using_unet_and)
 - RSS feed: $source
 - date published: 2025-02-17T14:47:28+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Feitgemel"> /u/Feitgemel </a> <br/> <span><a href="https://eranfeit.net/how-to-segment-x-ray-lungs-using-u-net-and-tensorflow/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irlghm/how_to_segment_xray_lungs_using_unet_and/">[comments]</a></span>

## Coding Some Fractals (inspired by Sebastian Lague's Coding Adventures)
 - [https://www.reddit.com/r/programming/comments/1irl5zm/coding_some_fractals_inspired_by_sebastian_lagues](https://www.reddit.com/r/programming/comments/1irl5zm/coding_some_fractals_inspired_by_sebastian_lagues)
 - RSS feed: $source
 - date published: 2025-02-17T14:33:44+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/vvye"> /u/vvye </a> <br/> <span><a href="https://www.youtube.com/watch?v=hjhMh0R9T1Y">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irl5zm/coding_some_fractals_inspired_by_sebastian_lagues/">[comments]</a></span>

## I built a private workspace for calling API and inspecting data
 - [https://www.reddit.com/r/programming/comments/1irl5tk/i_built_a_private_workspace_for_calling_api_and](https://www.reddit.com/r/programming/comments/1irl5tk/i_built_a_private_workspace_for_calling_api_and)
 - RSS feed: $source
 - date published: 2025-02-17T14:33:29+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Lac-TranAn"> /u/Lac-TranAn </a> <br/> <span><a href="https://www.postpilot.dev/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irl5tk/i_built_a_private_workspace_for_calling_api_and/">[comments]</a></span>

## Procedures as State Machines
 - [https://www.reddit.com/r/programming/comments/1irkk33/procedures_as_state_machines](https://www.reddit.com/r/programming/comments/1irkk33/procedures_as_state_machines)
 - RSS feed: $source
 - date published: 2025-02-17T14:04:49+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Temdog007"> /u/Temdog007 </a> <br/> <span><a href="https://procasm.temware.site/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irkk33/procedures_as_state_machines/">[comments]</a></span>

## Microsoft to Deprecate Location History Feature in Windows
 - [https://www.reddit.com/r/programming/comments/1irjs19/microsoft_to_deprecate_location_history_feature](https://www.reddit.com/r/programming/comments/1irjs19/microsoft_to_deprecate_location_history_feature)
 - RSS feed: $source
 - date published: 2025-02-17T13:26:07+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/miso25"> /u/miso25 </a> <br/> <span><a href="https://cyberinsider.com/microsoft-to-deprecate-location-history-feature-in-windows/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irjs19/microsoft_to_deprecate_location_history_feature/">[comments]</a></span>

## 🚀 I Built a Free Dev Tools Hub – Would Love Your Feedback!
 - [https://www.reddit.com/r/programming/comments/1irjayd/i_built_a_free_dev_tools_hub_would_love_your](https://www.reddit.com/r/programming/comments/1irjayd/i_built_a_free_dev_tools_hub_would_love_your)
 - RSS feed: $source
 - date published: 2025-02-17T13:01:19+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Capital_Pick6672"> /u/Capital_Pick6672 </a> <br/> <span><a href="https://www.devtools24.com/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irjayd/i_built_a_free_dev_tools_hub_would_love_your/">[comments]</a></span>

## Death of a thousand nits: the gentle art of code review
 - [https://www.reddit.com/r/programming/comments/1iri0l4/death_of_a_thousand_nits_the_gentle_art_of_code](https://www.reddit.com/r/programming/comments/1iri0l4/death_of_a_thousand_nits_the_gentle_art_of_code)
 - RSS feed: $source
 - date published: 2025-02-17T11:44:30+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/AlexandraLinnea"> /u/AlexandraLinnea </a> <br/> <span><a href="https://bitfieldconsulting.com/posts/code-review">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1iri0l4/death_of_a_thousand_nits_the_gentle_art_of_code/">[comments]</a></span>

## 0+0 > 0: C++ thread-local storage performance
 - [https://www.reddit.com/r/programming/comments/1irhytj/00_0_c_threadlocal_storage_performance](https://www.reddit.com/r/programming/comments/1irhytj/00_0_c_threadlocal_storage_performance)
 - RSS feed: $source
 - date published: 2025-02-17T11:41:16+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/FoxInTheRedBox"> /u/FoxInTheRedBox </a> <br/> <span><a href="https://yosefk.com/blog/cxx-thread-local-storage-performance.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irhytj/00_0_c_threadlocal_storage_performance/">[comments]</a></span>

## Notemod: Note-Taking App Open Source | Only - JS HTML CSS
 - [https://www.reddit.com/r/programming/comments/1irhxu9/notemod_notetaking_app_open_source_only_js_html](https://www.reddit.com/r/programming/comments/1irhxu9/notemod_notetaking_app_open_source_only_js_html)
 - RSS feed: $source
 - date published: 2025-02-17T11:39:31+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/remodeus"> /u/remodeus </a> <br/> <span><a href="https://github.com/orayemre/Notemod">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irhxu9/notemod_notetaking_app_open_source_only_js_html/">[comments]</a></span>

## searchcode.com’s SQLite database is probably 6 terabytes bigger than yours
 - [https://www.reddit.com/r/programming/comments/1irhwil/searchcodecoms_sqlite_database_is_probably_6](https://www.reddit.com/r/programming/comments/1irhwil/searchcodecoms_sqlite_database_is_probably_6)
 - RSS feed: $source
 - date published: 2025-02-17T11:36:58+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/FoxInTheRedBox"> /u/FoxInTheRedBox </a> <br/> <span><a href="https://boyter.org/posts/searchcode-bigger-sqlite-than-you/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irhwil/searchcodecoms_sqlite_database_is_probably_6/">[comments]</a></span>

## searchcode.com’s SQLite database is probably 6 terabytes bigger than yours
 - [https://www.reddit.com/r/programming/comments/1irhw4d/searchcodecoms_sqlite_database_is_probably_6](https://www.reddit.com/r/programming/comments/1irhw4d/searchcodecoms_sqlite_database_is_probably_6)
 - RSS feed: $source
 - date published: 2025-02-17T11:36:13+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/FoxInTheRedBox"> /u/FoxInTheRedBox </a> <br/> <span><a href="https://boyter.org/posts/searchcode-bigger-sqlite-than-you/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irhw4d/searchcodecoms_sqlite_database_is_probably_6/">[comments]</a></span>

## Which API provider do you use for GIF integration? I came across this review of GIF API providers, including their endpoints and parameters. Have you tried any of them?
 - [https://www.reddit.com/r/programming/comments/1irhnis/which_api_provider_do_you_use_for_gif_integration](https://www.reddit.com/r/programming/comments/1irhnis/which_api_provider_do_you_use_for_gif_integration)
 - RSS feed: $source
 - date published: 2025-02-17T11:19:59+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/gkhachik"> /u/gkhachik </a> <br/> <span><a href="https://zuplo.com/blog/2025/02/10/klipy-api">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irhnis/which_api_provider_do_you_use_for_gif_integration/">[comments]</a></span>

## Learn How to Build a Plant Identification AI Tool with Next.js 14!
 - [https://www.reddit.com/r/programming/comments/1irh4le/learn_how_to_build_a_plant_identification_ai_tool](https://www.reddit.com/r/programming/comments/1irh4le/learn_how_to_build_a_plant_identification_ai_tool)
 - RSS feed: $source
 - date published: 2025-02-17T10:44:32+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Any-Maximum-595"> /u/Any-Maximum-595 </a> <br/> <span><a href="http://tsuman.com.np/step-by-step-tutorial-how-to-build-a-plant-identification-ai-tool-website-using-next-js-14/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irh4le/learn_how_to_build_a_plant_identification_ai_tool/">[comments]</a></span>

## Looking for help replicating this approach
 - [https://www.reddit.com/r/programming/comments/1irh1o7/looking_for_help_replicating_this_approach](https://www.reddit.com/r/programming/comments/1irh1o7/looking_for_help_replicating_this_approach)
 - RSS feed: $source
 - date published: 2025-02-17T10:38:44+00:00

<!-- SC_OFF --><div class="md"><p>Hello dear friends. I came across a great model and a website in my GIS/DT communities and I was very impressed. </p> <p><a href="https://rantuniitty.fi/">https://rantuniitty.fi/</a></p> <p>I am a developer working on building digital twins using Unreal Engine as a foundation. UE5 is great with META and image processing but server load and size is a bit high for GIS, so i am trying to add a seperate GIS layer similar to this site. </p> <p>Would you kindly suggest a framework and language for OSM support with zoom feature? How can i replicate or build something similar? Feel free to comment or DM me, thank you</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/atropostr"> /u/atropostr </a> <br/> <span><a href="https://rantuniitty.fi">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irh1o7/looking_for_help_replicating_this_approach/">[comments]</a></span>

## I'm building my own open-source service mesh in Rust. Looking for developers!
 - [https://www.reddit.com/r/programming/comments/1irgux4/im_building_my_own_opensource_service_mesh_in](https://www.reddit.com/r/programming/comments/1irgux4/im_building_my_own_opensource_service_mesh_in)
 - RSS feed: $source
 - date published: 2025-02-17T10:25:13+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/LorenzoTettamanti"> /u/LorenzoTettamanti </a> <br/> <span><a href="https://github.com/CortexFlow/CortexBrain">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irgux4/im_building_my_own_opensource_service_mesh_in/">[comments]</a></span>

## JavaScript Development: Unleashing Speed and Agility with the Semantic Concept Connection System
 - [https://www.reddit.com/r/programming/comments/1irgo9v/javascript_development_unleashing_speed_and](https://www.reddit.com/r/programming/comments/1irgo9v/javascript_development_unleashing_speed_and)
 - RSS feed: $source
 - date published: 2025-02-17T10:11:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/BoomConsole"> /u/BoomConsole </a> <br/> <span><a href="https://www.reddit.com/r/BoomConsole/comments/1irgnkl/javascript_development_unleashing_speed_and/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irgo9v/javascript_development_unleashing_speed_and/">[comments]</a></span>

## In need of some criticism/reactions
 - [https://www.reddit.com/r/programming/comments/1irgmnv/in_need_of_some_criticismreactions](https://www.reddit.com/r/programming/comments/1irgmnv/in_need_of_some_criticismreactions)
 - RSS feed: $source
 - date published: 2025-02-17T10:08:37+00:00

<!-- SC_OFF --><div class="md"><p>CE student here,trying to land first intenrship/job anything wrong/right with my repos? And projects themselves? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/UpperOpportunity1647"> /u/UpperOpportunity1647 </a> <br/> <span><a href="https://github.com/todi-mih">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irgmnv/in_need_of_some_criticismreactions/">[comments]</a></span>

## Harvard team built a CMOS chip to map 70,000 synaptic connections between 2,000 rat neurons
 - [https://www.reddit.com/r/programming/comments/1irg96i/harvard_team_built_a_cmos_chip_to_map_70000](https://www.reddit.com/r/programming/comments/1irg96i/harvard_team_built_a_cmos_chip_to_map_70000)
 - RSS feed: $source
 - date published: 2025-02-17T09:41:38+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Sheishofert"> /u/Sheishofert </a> <br/> <span><a href="https://www.tomshardware.com/tech-industry/harvard-team-built-a-cmos-chip-to-map-70-000-synaptic-connections-between-2-000-rat-neurons">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irg96i/harvard_team_built_a_cmos_chip_to_map_70000/">[comments]</a></span>

## Ideas for programming an array of 8192 Qubitrons?
 - [https://www.reddit.com/r/programming/comments/1irfrv6/ideas_for_programming_an_array_of_8192_qubitrons](https://www.reddit.com/r/programming/comments/1irfrv6/ideas_for_programming_an_array_of_8192_qubitrons)
 - RSS feed: $source
 - date published: 2025-02-17T09:06:43+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Euphoric-Wafer-4487"> /u/Euphoric-Wafer-4487 </a> <br/> <span><a href="https://github.com/bookofquantum/BOQ/blob/main/photons/Qubitron/Abstract-v2.md">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irfrv6/ideas_for_programming_an_array_of_8192_qubitrons/">[comments]</a></span>

## Why Kotlin’s Result Type Falls Short for Handling Failures
 - [https://www.reddit.com/r/programming/comments/1irfo1u/why_kotlins_result_type_falls_short_for_handling](https://www.reddit.com/r/programming/comments/1irfo1u/why_kotlins_result_type_falls_short_for_handling)
 - RSS feed: $source
 - date published: 2025-02-17T08:59:39+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/ablx0000"> /u/ablx0000 </a> <br/> <span><a href="https://verbosemode.dev/p/why-kotlins-result-type-falls-short">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irfo1u/why_kotlins_result_type_falls_short_for_handling/">[comments]</a></span>

## How I used Google's Gemini LLM to fix formatting issues in Project Gutenberg eBooks.
 - [https://www.reddit.com/r/programming/comments/1irdj8n/how_i_used_googles_gemini_llm_to_fix_formatting](https://www.reddit.com/r/programming/comments/1irdj8n/how_i_used_googles_gemini_llm_to_fix_formatting)
 - RSS feed: $source
 - date published: 2025-02-17T06:27:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/tycho_brahes_nose_"> /u/tycho_brahes_nose_ </a> <br/> <span><a href="https://amanvir.com/blog/gempress-formatting-ebooks-with-gemini">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irdj8n/how_i_used_googles_gemini_llm_to_fix_formatting/">[comments]</a></span>

## Implementing Prisma RBAC: Fine-Grained Prisma Permissions
 - [https://www.reddit.com/r/programming/comments/1irde5o/implementing_prisma_rbac_finegrained_prisma](https://www.reddit.com/r/programming/comments/1irde5o/implementing_prisma_rbac_finegrained_prisma)
 - RSS feed: $source
 - date published: 2025-02-17T06:18:10+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Permit_io"> /u/Permit_io </a> <br/> <span><a href="https://www.permit.io/blog/implementing-prisma-rbac-fine-grained-prisma-permissions">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irde5o/implementing_prisma_rbac_finegrained_prisma/">[comments]</a></span>

## Schemesh: Fusion between Unix shell and Lisp REPL
 - [https://www.reddit.com/r/programming/comments/1irctno/schemesh_fusion_between_unix_shell_and_lisp_repl](https://www.reddit.com/r/programming/comments/1irctno/schemesh_fusion_between_unix_shell_and_lisp_repl)
 - RSS feed: $source
 - date published: 2025-02-17T05:43:14+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/namanyayg"> /u/namanyayg </a> <br/> <span><a href="https://github.com/cosmos72/schemesh">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irctno/schemesh_fusion_between_unix_shell_and_lisp_repl/">[comments]</a></span>

## Gixy: Nginx Configuration Static Analyzer
 - [https://www.reddit.com/r/programming/comments/1ircpyw/gixy_nginx_configuration_static_analyzer](https://www.reddit.com/r/programming/comments/1ircpyw/gixy_nginx_configuration_static_analyzer)
 - RSS feed: $source
 - date published: 2025-02-17T05:36:49+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/namanyayg"> /u/namanyayg </a> <br/> <span><a href="https://github.com/dvershinin/gixy">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1ircpyw/gixy_nginx_configuration_static_analyzer/">[comments]</a></span>

## Project: What to buy during a Bitcoin bullrun? Suggesting coins and optimizing the portfolio
 - [https://www.reddit.com/r/programming/comments/1irc1ct/project_what_to_buy_during_a_bitcoin_bullrun](https://www.reddit.com/r/programming/comments/1irc1ct/project_what_to_buy_during_a_bitcoin_bullrun)
 - RSS feed: $source
 - date published: 2025-02-17T04:55:59+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/erfaniaa"> /u/erfaniaa </a> <br/> <span><a href="https://github.com/Erfaniaa/crypto-portfolio-optimizer">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irc1ct/project_what_to_buy_during_a_bitcoin_bullrun/">[comments]</a></span>

## Microblogging for motivation
 - [https://www.reddit.com/r/programming/comments/1irby6v/microblogging_for_motivation](https://www.reddit.com/r/programming/comments/1irby6v/microblogging_for_motivation)
 - RSS feed: $source
 - date published: 2025-02-17T04:50:41+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Lazy_Two_4908"> /u/Lazy_Two_4908 </a> <br/> <span><a href="http://logs.neilarora.in">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irby6v/microblogging_for_motivation/">[comments]</a></span>

## Lombok @Builder: Simplificando la Creación de Objetos en Java
 - [https://www.reddit.com/r/programming/comments/1irb5ni/lombok_builder_simplificando_la_creación_de](https://www.reddit.com/r/programming/comments/1irb5ni/lombok_builder_simplificando_la_creación_de)
 - RSS feed: $source
 - date published: 2025-02-17T04:05:04+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/emanuelpeg"> /u/emanuelpeg </a> <br/> <span><a href="https://emanuelpeg.blogspot.com/2025/02/lombok-builder-simplificando-la.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1irb5ni/lombok_builder_simplificando_la_creación_de/">[comments]</a></span>

## Concurrencia en Erlang parte 13
 - [https://www.reddit.com/r/programming/comments/1iray9l/concurrencia_en_erlang_parte_13](https://www.reddit.com/r/programming/comments/1iray9l/concurrencia_en_erlang_parte_13)
 - RSS feed: $source
 - date published: 2025-02-17T03:53:35+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/emanuelpeg"> /u/emanuelpeg </a> <br/> <span><a href="https://emanuelpeg.blogspot.com/2025/02/concurrencia-en-erlang-parte-13.html">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1iray9l/concurrencia_en_erlang_parte_13/">[comments]</a></span>

## Day 28: Can You Unlock the Power of JavaScript Proxy Objects?
 - [https://www.reddit.com/r/programming/comments/1ir8odd/day_28_can_you_unlock_the_power_of_javascript](https://www.reddit.com/r/programming/comments/1ir8odd/day_28_can_you_unlock_the_power_of_javascript)
 - RSS feed: $source
 - date published: 2025-02-17T01:50:09+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/MysteriousEye8494"> /u/MysteriousEye8494 </a> <br/> <span><a href="https://javascript.plainenglish.io/day-28-can-you-unlock-the-power-of-javascript-proxy-objects-e72762b0199a">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1ir8odd/day_28_can_you_unlock_the_power_of_javascript/">[comments]</a></span>

## Day 25 — Daily JavaScript Algorithm : Maximum Subarray Sum (Kadane’s Algorithm)
 - [https://www.reddit.com/r/programming/comments/1ir8ks0/day_25_daily_javascript_algorithm_maximum](https://www.reddit.com/r/programming/comments/1ir8ks0/day_25_daily_javascript_algorithm_maximum)
 - RSS feed: $source
 - date published: 2025-02-17T01:44:56+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/MysteriousEye8494"> /u/MysteriousEye8494 </a> <br/> <span><a href="https://javascript.plainenglish.io/day-25-daily-javascript-algorithm-20c99ce8e6b2">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1ir8ks0/day_25_daily_javascript_algorithm_maximum/">[comments]</a></span>

## My first external cheat for Assualtcube
 - [https://www.reddit.com/r/programming/comments/1ir7x9n/my_first_external_cheat_for_assualtcube](https://www.reddit.com/r/programming/comments/1ir7x9n/my_first_external_cheat_for_assualtcube)
 - RSS feed: $source
 - date published: 2025-02-17T01:11:36+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Wide-Tea8060"> /u/Wide-Tea8060 </a> <br/> <span><a href="https://github.com/x64-exploit0r/AssaultCubeAmmoHack">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1ir7x9n/my_first_external_cheat_for_assualtcube/">[comments]</a></span>

## How to add a directory to your PATH
 - [https://www.reddit.com/r/programming/comments/1ir7f2g/how_to_add_a_directory_to_your_path](https://www.reddit.com/r/programming/comments/1ir7f2g/how_to_add_a_directory_to_your_path)
 - RSS feed: $source
 - date published: 2025-02-17T00:46:26+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/stackoverflooooooow"> /u/stackoverflooooooow </a> <br/> <span><a href="https://jvns.ca/blog/2025/02/13/how-to-add-a-directory-to-your-path/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/programming/comments/1ir7f2g/how_to_add_a_directory_to_your_path/">[comments]</a></span>

