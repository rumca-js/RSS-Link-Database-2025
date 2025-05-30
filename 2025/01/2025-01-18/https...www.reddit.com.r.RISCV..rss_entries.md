# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Has anyone implemented RISC-V V vector extension on a softcore? I am looking into extending MI-V microchip's risc-v softcore
 - [https://www.reddit.com/r/RISCV/comments/1i4gzuy/has_anyone_implemented_riscv_v_vector_extension](https://www.reddit.com/r/RISCV/comments/1i4gzuy/has_anyone_implemented_riscv_v_vector_extension)
 - RSS feed: $source
 - date published: 2025-01-18T20:47:47+00:00

&#32; submitted by &#32; <a href="https://www.reddit.com/user/Matcha_341"> /u/Matcha_341 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i4gzuy/has_anyone_implemented_riscv_v_vector_extension/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i4gzuy/has_anyone_implemented_riscv_v_vector_extension/">[comments]</a></span>

## What is the purpose of Instruction Uncache unit in Xiangshan Processor ?
 - [https://www.reddit.com/r/RISCV/comments/1i4alsy/what_is_the_purpose_of_instruction_uncache_unit](https://www.reddit.com/r/RISCV/comments/1i4alsy/what_is_the_purpose_of_instruction_uncache_unit)
 - RSS feed: $source
 - date published: 2025-01-18T16:01:31+00:00

<!-- SC_OFF --><div class="md"><p>I was just going through the Xiangshan core docs when I came across this Instruction Uncache unit. Does anybody have any idea what its purpose is and how it works? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/PlentyAd9374"> /u/PlentyAd9374 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i4alsy/what_is_the_purpose_of_instruction_uncache_unit/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i4alsy/what_is_the_purpose_of_instruction_uncache_unit/">[comments]</a></span>

## Chatassembler is a RISC-V assembler that's over 10 times faster than GCC
 - [https://www.reddit.com/r/RISCV/comments/1i4aepi/chatassembler_is_a_riscv_assembler_thats_over_10](https://www.reddit.com/r/RISCV/comments/1i4aepi/chatassembler_is_a_riscv_assembler_thats_over_10)
 - RSS feed: $source
 - date published: 2025-01-18T15:52:48+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1i4aepi/chatassembler_is_a_riscv_assembler_thats_over_10/"> <img src="https://external-preview.redd.it/v4CNXv2OaEXo8ORShDInq1XhAa9uqfEDZnK16CH_62g.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=280c9c04a4892c491b23fd1cf140ca09789d9e8c" alt="Chatassembler is a RISC-V assembler that's over 10 times faster than GCC" title="Chatassembler is a RISC-V assembler that's over 10 times faster than GCC" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Slammernanners"> /u/Slammernanners </a> <br/> <span><a href="https://github.com/Slackadays/Chata/tree/main/libchata#welcome-to-chatassembler">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i4aepi/chatassembler_is_a_riscv_assembler_thats_over_10/">[comments]</a></span> </td></tr></table>

## crt0.o don't linking to 0x1000
 - [https://www.reddit.com/r/RISCV/comments/1i47utf/crt0o_dont_linking_to_0x1000](https://www.reddit.com/r/RISCV/comments/1i47utf/crt0o_dont_linking_to_0x1000)
 - RSS feed: $source
 - date published: 2025-01-18T13:46:30+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I intend to use a custom newlib, but the linker is not linking crt0.o to the 0x10000 (I made an error in the post title) location. Instead, it&#39;s linking _start to:</p> <pre><code>000000000001037c &lt;_start&gt;: </code></pre> <p>The first .text executable section is:</p> <pre><code>0000000000010120 &lt;__do_global_dtors_aux&gt;: </code></pre> <p>I&#39;m using the internal link script of riscv64-unknown-ld. Here&#39;s my compilation command:</p> <pre><code>riscv64-unknown-elf-gcc -march=rv64imafdc_zicsr -mcmodel=medany -mabi=lp64d -Wall -fno-builtin --save-temps -nostartfiles -nostdlib -nodefaultlibs -g gcc/rv64imafdc/lp64d/crti.o gcc/rv64imafdc/lp64d/crtbegin.o -o output.elf msetteste.o platform.o memset.o syscall.o build-gcc-newlib-stage2/gcc/rv64imafdc/lp64d/crtend.o build-gcc-newlib-stage2/gcc/rv64imafdc/lp64d/crtn.o build-newlib/riscv64-unknown-elf/rv64imafdc/lp64d/libgloss/riscv/crt0.o build-newlib-nano/riscv64-unknown-elf/newlib/libc.a 

## FemtoRV32 - Minimalistic CPU
 - [https://www.reddit.com/r/RISCV/comments/1i3wbfw/femtorv32_minimalistic_cpu](https://www.reddit.com/r/RISCV/comments/1i3wbfw/femtorv32_minimalistic_cpu)
 - RSS feed: $source
 - date published: 2025-01-18T01:26:21+00:00

<!-- SC_OFF --><div class="md"><p>Hello Everyone, Can this FemtoRV32 perform fetch and write back operation? Say I am receiving data from SPI peripheral (MISO operation) and transfer the received data into UART peripheral (Tx) ? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Polarroute"> /u/Polarroute </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i3wbfw/femtorv32_minimalistic_cpu/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i3wbfw/femtorv32_minimalistic_cpu/">[comments]</a></span>

