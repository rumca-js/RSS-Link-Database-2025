# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Advice for getting the ch32v003 running blinking from scratch...
 - [https://www.reddit.com/r/RISCV/comments/1icbyso/advice_for_getting_the_ch32v003_running_blinking](https://www.reddit.com/r/RISCV/comments/1icbyso/advice_for_getting_the_ch32v003_running_blinking)
 - RSS feed: $source
 - date published: 2025-01-28T20:51:32+00:00

<!-- SC_OFF --><div class="md"><p>I&#39;m at the brink of getting crazy because I&#39;m unable to get the ch32v003 to do what I want. So I need some help.</p> <p>I just coded this little example code:</p> <pre><code>#include &lt;stdint.h&gt; // Register definitions #define RCC_BASE 0x40021000UL #define RCC_APB2PCENR (*(volatile uint32_t *)(RCC_BASE + 0x18)) #define GPIOD_BASE 0x40011400UL #define GPIOD_CFGLR (*(volatile uint32_t *)(GPIOD_BASE + 0x00)) #define GPIOD_BSHR (*(volatile uint32_t *)(GPIOD_BASE + 0x18)) void delay(void) { for (volatile int i = 0; i &lt; 100000; i++); // Adjust delay as needed } int main(void) { // Enable GPIO Port D clock RCC_APB2PCENR |= (1 &lt;&lt; 5); // Enable IOPDEN (Port D clock) // Configure PD0 as push-pull output (10MHz) GPIOD_CFGLR &amp;= ~(0xF &lt;&lt; (0 * 4)); // Clear existing configuration GPIOD_CFGLR |= (0x1 &lt;&lt; (0 * 4)); // Set mode: 10MHz, push-pull while(1) { GPIOD_BSHR = (1 &lt;&lt; 0); // Set PD0 high delay(); GPIOD_BSHR = (1 &lt;&

## Geekbench 6.4 released with support for RISC-V RVV 1.0 vector
 - [https://www.reddit.com/r/RISCV/comments/1ic58jw/geekbench_64_released_with_support_for_riscv_rvv](https://www.reddit.com/r/RISCV/comments/1ic58jw/geekbench_64_released_with_support_for_riscv_rvv)
 - RSS feed: $source
 - date published: 2025-01-28T16:18:08+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.geekbench.com/download/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ic58jw/geekbench_64_released_with_support_for_riscv_rvv/">[comments]</a></span>

## Hex code in RiscV
 - [https://www.reddit.com/r/RISCV/comments/1ic2nv6/hex_code_in_riscv](https://www.reddit.com/r/RISCV/comments/1ic2nv6/hex_code_in_riscv)
 - RSS feed: $source
 - date published: 2025-01-28T14:23:58+00:00

<!-- SC_OFF --><div class="md"><p>How do you write &quot;digit 2&quot; in hex code for 8*8 led matrix? Can someone help? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/02dewtou"> /u/02dewtou </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1ic2nv6/hex_code_in_riscv/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ic2nv6/hex_code_in_riscv/">[comments]</a></span>

## FreedomStudio and Eclipse
 - [https://www.reddit.com/r/RISCV/comments/1ic0p58/freedomstudio_and_eclipse](https://www.reddit.com/r/RISCV/comments/1ic0p58/freedomstudio_and_eclipse)
 - RSS feed: $source
 - date published: 2025-01-28T12:43:29+00:00

<!-- SC_OFF --><div class="md"><p>Greetings everyone, </p> <p>As everyone knows that the FreedomStudio IDE uses Eclipse</p> <p>I&#39;m having a problem where the IDE is giving this error: (Symbol &#39;std&#39; couldn&#39;t be resolved), also for <code>cout</code> and <code>cin</code> it is the same problem.<br/> I would like to also mention that I&#39;ve included the header file <code>#include &lt;iostream&gt;</code>. The toolchain that I&#39;m using is SiFive RISC-V GNU GCC Newlib</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Alternative_Event155"> /u/Alternative_Event155 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1ic0p58/freedomstudio_and_eclipse/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ic0p58/freedomstudio_and_eclipse/">[comments]</a></span>

## ARM+RISC-V SBC
 - [https://www.reddit.com/r/RISCV/comments/1ic0aik/armriscv_sbc](https://www.reddit.com/r/RISCV/comments/1ic0aik/armriscv_sbc)
 - RSS feed: $source
 - date published: 2025-01-28T12:19:28+00:00

<!-- SC_OFF --><div class="md"><p>Are there custom SBC boards with ARM+RISC-V? Yes, I&#39;ve heard about Sophgo chips. But I&#39;m curious if there&#39;s anything, for instance, based on Rockchip+RISC-V. I couldn&#39;t find anything on the Internet. Or is it just my imagination, and such a thing is impossible to implement? :)</p> <p>Perhaps someone knows manufacturers anywhere in the world?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Cherry_LinxDeb"> /u/Cherry_LinxDeb </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1ic0aik/armriscv_sbc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1ic0aik/armriscv_sbc/">[comments]</a></span>

