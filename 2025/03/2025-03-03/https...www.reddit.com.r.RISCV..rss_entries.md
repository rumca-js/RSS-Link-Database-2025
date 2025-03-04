# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Alibaba launches RISC-V-based XuanTie C930 server CPU — AI/HPC chip ships this month, more designs to follow
 - [https://www.reddit.com/r/RISCV/comments/1j2v3og/alibaba_launches_riscvbased_xuantie_c930_server](https://www.reddit.com/r/RISCV/comments/1j2v3og/alibaba_launches_riscvbased_xuantie_c930_server)
 - RSS feed: $source
 - date published: 2025-03-03T22:15:56+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1j2v3og/alibaba_launches_riscvbased_xuantie_c930_server/"> <img src="https://external-preview.redd.it/J13VcC4Fmn42mYBUjTXA-59Bkuyh0cD878CLrS84A-Q.jpg?width=640&amp;crop=smart&amp;auto=webp&amp;s=f8d30e0a6d4759e50f1e7048459557b2dade1c6c" alt="Alibaba launches RISC-V-based XuanTie C930 server CPU — AI/HPC chip ships this month, more designs to follow" title="Alibaba launches RISC-V-based XuanTie C930 server CPU — AI/HPC chip ships this month, more designs to follow" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/brucehoult"> /u/brucehoult </a> <br/> <span><a href="https://www.tomshardware.com/pc-components/cpus/alibaba-launches-risc-v-based-xuantie-c930-server-cpu-ai-hpc-chip-ships-this-month-more-designs-to-follow">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1j2v3og/alibaba_launches_riscvbased_xuantie_c930_server/">[comments]</a></span> </td></tr></tabl

## Can VLE64 be faster than VLE8 for loading 128 bits from memory?
 - [https://www.reddit.com/r/RISCV/comments/1j2nt1b/can_vle64_be_faster_than_vle8_for_loading_128](https://www.reddit.com/r/RISCV/comments/1j2nt1b/can_vle64_be_faster_than_vle8_for_loading_128)
 - RSS feed: $source
 - date published: 2025-03-03T17:16:29+00:00

<!-- SC_OFF --><div class="md"><p>I am making an emulator that targets RISC-V. As much as I&#39;d like every memory access to be aligned, it&#39;s not always the case. Sometimes I need to emit RISC-V instructions that load 128 bits from memory. I do not know ahead of time if the address is going to be aligned or not.</p> <p>I know that with VLE8 + vl of 16 I can load from that address whether or not it is aligned to 128-bit boundary. I can also do the same with a VLE64 + vl of 2, but it needs to be aligned to 64-bit.</p> <p>Is VLE64 faster? Is it a good optimization to assume every address is going to be aligned properly, and only patch VLE64 to VLE8 if an unaligned address exception (SIGBUS) is triggered? Or is there no performance benefit to using VLE64 and I should use VLE8 everywhere?</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ProductAccurate9702"> /u/ProductAccurate9702 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/

## Created RVV Python Library.
 - [https://www.reddit.com/r/RISCV/comments/1j2m178/created_rvv_python_library](https://www.reddit.com/r/RISCV/comments/1j2m178/created_rvv_python_library)
 - RSS feed: $source
 - date published: 2025-03-03T16:03:53+00:00

<!-- SC_OFF --><div class="md"><p>Hey guys! So, it&#39;s been a few months since I have started coding C and ASM using RISCV RVV, I felt the need for a python library that could replicate the vector operations of RISCV so I can verify and debug issues with my algorithm before implementing them in C.<br/> So here is the link to the repo:<br/> <a href="https://github.com/OM3R-Nazir/rvv">OM3R-Nazir/rvv</a><br/> Kind of new in this programming space of writing libraries. Constructive criticism of the code base would be highly appreciated.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Omer_Nazir_EE"> /u/Omer_Nazir_EE </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1j2m178/created_rvv_python_library/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1j2m178/created_rvv_python_library/">[comments]</a></span>

## Kendryte K230 RISC-V Development Board – CanMV-K230 Default App
 - [https://www.reddit.com/r/RISCV/comments/1j2ib6j/kendryte_k230_riscv_development_board_canmvk230](https://www.reddit.com/r/RISCV/comments/1j2ib6j/kendryte_k230_riscv_development_board_canmvk230)
 - RSS feed: $source
 - date published: 2025-03-03T13:10:08+00:00

<!-- SC_OFF --><div class="md"><p>Has anyone tried to change the default app in an image file compiled with the SDK on this board before? By default, the <strong>face_detection</strong> app starts. I tried <strong>sample_vicap</strong> with <strong>dewarp correction</strong>, but I couldn’t get the <strong>fisheye correction</strong> example to work.</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Sorry_Stable_5541"> /u/Sorry_Stable_5541 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1j2ib6j/kendryte_k230_riscv_development_board_canmvk230/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1j2ib6j/kendryte_k230_riscv_development_board_canmvk230/">[comments]</a></span>

## Where is exception handler code from?
 - [https://www.reddit.com/r/RISCV/comments/1j2buf0/where_is_exception_handler_code_from](https://www.reddit.com/r/RISCV/comments/1j2buf0/where_is_exception_handler_code_from)
 - RSS feed: $source
 - date published: 2025-03-03T05:48:36+00:00

<!-- SC_OFF --><div class="md"><p>I know when an exception/interrupt occurs, PC will be set to the address stored in mtvec. So the exception handling code is somehow loaded into memory, right? I know in some cases these codes is in OS&#39; kernel code. But does this apply to all cases? What if I don&#39;t hava an OS at all? Like on an embedded system that runs a single application. I still have to offer some kind of kernel which has exception handling logic in it in this case? Is all exception handling code offerred by software, if so, can I say when I have buy a CPU, it actually has no exception handling ability before I load a kernel? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Ok-Performer-9014"> /u/Ok-Performer-9014 </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1j2buf0/where_is_exception_handler_code_from/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1j2buf0/where_is_exception_handl

