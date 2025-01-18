# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Running Linux Software on RISC V (FPGA Softcore) ?
 - [https://www.reddit.com/r/RISCV/comments/1i3sfex/running_linux_software_on_risc_v_fpga_softcore](https://www.reddit.com/r/RISCV/comments/1i3sfex/running_linux_software_on_risc_v_fpga_softcore)
 - RSS feed: $source
 - date published: 2025-01-17T22:20:45+00:00

<!-- SC_OFF --><div class="md"><p>This is basically the title of my Bachelor&#39;s Thesis. I have some questions: 1. What is the best FPGA for this project? Meaning the one where I can find the most related resources and tutorials, is suitable for my project and has a large community. 2. What Linux applications should run on it considering it is a Bachelor&#39;s Thesis? 3. Where to start and how would you do it? I don&#39;t want to revolutionize this field, I want to do this as fast as possible. ( You can still give me your idea of what would you like to add to make this special if it&#39;s not extremely complex ) 4. How long would this take? 5. Would a Real Digital Blackboard (I already have it) be suitable? ChatGPT says it might introduce unnecessary complexity and it lacks support. 6. What else would you like to add to the conversation? </p> <p>Thank you!</p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Tricky-Luck6850"> /u/Tricky-Luck6850 </a

## New to assembly language & RISC-V, struggling with simple I/O instructions
 - [https://www.reddit.com/r/RISCV/comments/1i3nvir/new_to_assembly_language_riscv_struggling_with](https://www.reddit.com/r/RISCV/comments/1i3nvir/new_to_assembly_language_riscv_struggling_with)
 - RSS feed: $source
 - date published: 2025-01-17T19:00:54+00:00

<!-- SC_OFF --><div class="md"><p>Suppose I have to declare 3 variables a, b, c and do a = a+5, b = b*4, c = a+b, then print the variables on separate lines. I spent hours looking for sample codes/tutorials and fixing my code, but to no avail (resources needed too). Entering 1, 2, 3 would give 3, 3, 3 instead of 6, 8, 17. Also whenever I try to print a newline with this code, address becomes out of range.</p> <pre><code> li a7, 4 la a0, newline ecall </code></pre> <p>Here&#39;s the other part of my code below, would appreciate some help:</p> <pre><code>.globl _start .data newline: .string &quot;\n&quot; a: .word b: .word c: .word .text _start: li a7, 5 ecall la a0, a li a7, 5 ecall la a1, b li a7, 5 ecall la a2, c addi t0, a0, 5 slli t1, a1, 2 add t2, t0, t1 li a7, 1 addi t0, a0, 0 ecall li a7, 1 addi t1, a1, 0 ecall li a7, 1 addi t2, a2, 0 ecall </code></pre> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/HorrorCrazy8634"> /u/HorrorCrazy8634 </a> 

## Dual Core RISC V SoC
 - [https://www.reddit.com/r/RISCV/comments/1i3gazl/dual_core_risc_v_soc](https://www.reddit.com/r/RISCV/comments/1i3gazl/dual_core_risc_v_soc)
 - RSS feed: $source
 - date published: 2025-01-17T13:26:52+00:00

<!-- SC_OFF --><div class="md"><p>Can anyone please suggest any dual core risc v Soc around which one can build and atttach the peripherals? </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/Polarroute"> /u/Polarroute </a> <br/> <span><a href="https://www.reddit.com/r/RISCV/comments/1i3gazl/dual_core_risc_v_soc/">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i3gazl/dual_core_risc_v_soc/">[comments]</a></span>

## Guess the oasis won't arrive soon.
 - [https://www.reddit.com/r/RISCV/comments/1i3by9p/guess_the_oasis_wont_arrive_soon](https://www.reddit.com/r/RISCV/comments/1i3by9p/guess_the_oasis_wont_arrive_soon)
 - RSS feed: $source
 - date published: 2025-01-17T08:33:01+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1i3by9p/guess_the_oasis_wont_arrive_soon/"> <img src="https://preview.redd.it/7wep9u8fmide1.png?width=640&amp;crop=smart&amp;auto=webp&amp;s=8b081c2c606bdb7e7dd2e32e97c815ede7c99be3" alt="Guess the oasis won't arrive soon. " title="Guess the oasis won't arrive soon. " /> </a> </td><td> <!-- SC_OFF --><div class="md"><p>I didn&#39;t request the cancellation, according to arace the oasis will be on hold for now. </p> </div><!-- SC_ON --> &#32; submitted by &#32; <a href="https://www.reddit.com/user/ConductiveInsulation"> /u/ConductiveInsulation </a> <br/> <span><a href="https://i.redd.it/7wep9u8fmide1.png">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i3by9p/guess_the_oasis_wont_arrive_soon/">[comments]</a></span> </td></tr></table>

