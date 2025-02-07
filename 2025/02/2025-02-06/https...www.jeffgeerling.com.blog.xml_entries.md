# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## How to build Ollama to run LLMs on RISC-V Linux
 - [https://www.jeffgeerling.com/blog/2025/how-build-ollama-run-llms-on-risc-v-linux](https://www.jeffgeerling.com/blog/2025/how-build-ollama-run-llms-on-risc-v-linux)
 - RSS feed: $source
 - date published: 2025-02-06T03:13:13+00:00

<span class="field field--name-title field--type-string field--label-hidden">How to build Ollama to run LLMs on RISC-V Linux</span>

            <p>RISC-V is the new entrant into the SBC/low-end desktop space, and as I'm in possession of a HiFive Premier P550 motherboard, I am running it through my usual gauntlet of benchmarks—partly to see how fast it is, and partly to gauge how far along RISC-V support is in general across a wide swath of Linux software.</p>

<p>From my first tests on the <a href="https://www.jeffgeerling.com/blog/2023/risc-v-business-testing-starfives-visionfive-2-sbc">VisionFive 2 back in 2023</a> to today, RISC-V has seen quite a bit of growth, fueled by economics, geopolitical wrangling, and developer interest.</p>

<p>The P550 uses the ESWIN EIC7700X SoC, and while it doesn't have a <em>fast</em> CPU, by modern standards, it is fast enough—and the system has enough RAM and IO—to run most modern Linux-y things. Including llama.cpp and Ollama!</p>

<h2>Compiling

