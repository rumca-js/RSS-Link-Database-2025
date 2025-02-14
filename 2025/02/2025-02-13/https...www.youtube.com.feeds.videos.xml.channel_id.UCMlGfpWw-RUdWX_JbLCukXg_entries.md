# Source:CppCon, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCMlGfpWw-RUdWX_JbLCukXg, language:en

## Rollback System in C++ for Online Multiplayer Games - Elias Farhan - CppCon 2024
 - [https://www.youtube.com/watch?v=xkcGa-Xw154](https://www.youtube.com/watch?v=xkcGa-Xw154)
 - RSS feed: $source
 - date published: 2025-02-13T15:07:08+00:00

https://cppcon.org​
---

Rollback System in C++ for Online Multiplayer Games - Elias Farhan - CppCon 2024
---

It is common knowledge that online multiplayer games are some of the hardest kinds of software to develop. Game developers have to deal with data packets coming with a substancial delay, in fact working with data from the past. The rollback technique allows to give the illusion of real-time by extrapolating input with a game simulation from the confirm frame to the current one. However, for the implemention to work there are several key factors that need to be taken into account. The game simulation update needs to be deterministic, the game state should be easily copyable, and the game state should be clearly separated from the graphics side of the game.
---

Slides: https://github.com/CppCon/CppCon2024/blob/main/Presentations/A_Simple_Rollback_System_In_Cpp.pdf

Sponsored by JetBrains: https://www.jetbrains.com/clion/
---

Elias Farhan

Elias Farhan is the head of the Game

