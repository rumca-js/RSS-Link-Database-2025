# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Fastest RISC-V emulator around?
 - [https://www.reddit.com/r/RISCV/comments/1i7mxil/fastest_riscv_emulator_around](https://www.reddit.com/r/RISCV/comments/1i7mxil/fastest_riscv_emulator_around)
 - RSS feed: $source
 - date published: 2025-01-22T21:46:18+00:00

<!-- SC_OFF --><div class="md"><p>Greetings!</p> <p>What&#39;s the fastest system-level RISC-V emulator around right now? It should be able to emulate rv64g and ideally run FreeBSD (though if it doesn&#39;t, I can try to port it). The emulator should be capable of multi-core operation.</p> <p>The goal is to bulk-build software on and for RISC-V. We have about 32000 software packages (the FreeBSD ports collection) to build, which takes around two weeks natively on an amd64 box (Skylake microarchitecture), so fast emulation is crucial.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/FUZxxl"> /u/FUZxxl </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i7mxil/fastest_riscv_emulator_around/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i7mxil/fastest_riscv_emulator_around/">[comments]</a></span>

## Milk-V Duo running (ascii) DOOM
 - [https://www.reddit.com/r/RISCV/comments/1i7htix/milkv_duo_running_ascii_doom](https://www.reddit.com/r/RISCV/comments/1i7htix/milkv_duo_running_ascii_doom)
 - RSS feed: $source
 - date published: 2025-01-22T18:19:02+00:00

<!-- SC_OFF --><div class="md"><p><a href="https://www.youtube.com/watch?v=3mNefsLfNIk">https://www.youtube.com/watch?v=3mNefsLfNIk</a></p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/floppydoppy2"> /u/floppydoppy2 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i7htix/milkv_duo_running_ascii_doom/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i7htix/milkv_duo_running_ascii_doom/">[comments]</a></span>

## The Reserved Privilege Level
 - [https://www.reddit.com/r/RISCV/comments/1i79cn9/the_reserved_privilege_level](https://www.reddit.com/r/RISCV/comments/1i79cn9/the_reserved_privilege_level)
 - RSS feed: $source
 - date published: 2025-01-22T11:49:47+00:00

<!-- SC_OFF --><div class="md"><p>This is a little bit of a long post so please bear with me. </p> <p>I was going through the risc-v privileged specification and in section 1.2 (Privilege Levels) a table was defined which stated how the privilege levels were encoded in the various CSRs.</p> <p>The table also mentions a reserved encoding of 0b10 (decimal 2) which hasn&#39;t yet been given a name and purpose yet.</p> <p>My question is, has this privilege level been reserved in the sense that any current implementations should not use this level as it will be given a new role in a future revision of the specification? (If so is anyone aware of what role this privilege level might receive?) </p> <p>For anyone wondering why I am interested to know about this, it is because I feel it would be a great idea to run kernel modules and drivers in this privilege level such that malicious or buggy modules/drivers can&#39;t just read/write kernel memory (just the way userspace cannot modify or acc

## Where do i start with the milk v duo, or should i?
 - [https://www.reddit.com/r/RISCV/comments/1i772o8/where_do_i_start_with_the_milk_v_duo_or_should_i](https://www.reddit.com/r/RISCV/comments/1i772o8/where_do_i_start_with_the_milk_v_duo_or_should_i)
 - RSS feed: $source
 - date published: 2025-01-22T09:05:03+00:00

<!-- SC_OFF --><div class="md"><p>I have little experience using an arduino uno and not much knowledge about embedded electronics in general. I have tried linux minimally in the form of wsl. I have been thinking between the milk v duo s and the raspberry pi zero 2w. I want an sbc that can train extremely rudimentary ml models (eg. using tensorflow lite or pytorch). It would be nice if i could also use the boards as test dummies for malware, by running old os&#39;s like windows vista or windows xp and the like. I have a television that i can out put to ( i have herd that the milk v duo s dosent have hdmi). I see many ters flying around like eMMc, sram and such. So it would also be nice if any of you could familiarize myself with, or lead me to any resources for learning these terms. My priorities for a board are:</p> <ol> <li>Being able to run linux and do ai/ml tasks<br/></li> <li><p>Function like an arduino (communicate via i2c, spi, uart etc etc) and have okay-ish processing power 

