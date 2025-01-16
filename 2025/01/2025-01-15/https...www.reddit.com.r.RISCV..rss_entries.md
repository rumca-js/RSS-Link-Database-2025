# Source:The RISC-V Instruction Set Architecture, URL:https://www.reddit.com/r/RISCV/.rss, language:en

## Spike riscv32 program failed - Access exception occurred while loading payload test: Memory address 0x48 is invalid
 - [https://www.reddit.com/r/RISCV/comments/1i26nwj/spike_riscv32_program_failed_access_exception](https://www.reddit.com/r/RISCV/comments/1i26nwj/spike_riscv32_program_failed_access_exception)
 - RSS feed: $source
 - date published: 2025-01-15T20:16:33+00:00

<!-- SC_OFF --><div class="md"><p>Hi, I am trying to run a simple C code compiled for rv32e platform on spike and it&#39;s been very hard. Please guide me, here&#39;s the steps and code I used</p> <p><code> My Code int main() { int a = 4; int b = 3; int c = a - b; return c; } </code></p> <p>My Linker ``` /* * link.ld : Linker script */</p> <p>OUTPUT_ARCH( &quot;riscv&quot; ) /* ENTRY(_start) */ MEMORY { INSTR_MEM (rx) : ORIGIN = 0x00000000, LENGTH = 256 DATA_MEM (rwx) : ORIGIN = 0x00000100, LENGTH = 64 }</p> <p>SECTIONS { .text : { . = ALIGN(4); start.o (.text) *(.text) } &gt; INSTR_MEM .data : { *(.data) } &gt; DATA_MEM .bss : { *(.bss) } &gt; DATA_MEM </p> <p>/* <em>start: li sp, 0x140 _start: li sp, 0x140 // Load stack pointer (arbitrary address) linker_stack_start = .; _stack_start = 0X140; _stack_top = 0x00000180; _stack_start = ORIGIN(DATA_MEM) + LENGTH(DATA_MEM); PROVIDE(</em>_stack_pointer = _stack_start); */ } <code> Stack pointer initialization code </code> .section .text .

## Genshin Impact running on RISC-V (SG2044 EVB) with Box64
 - [https://www.reddit.com/r/RISCV/comments/1i1v7mo/genshin_impact_running_on_riscv_sg2044_evb_with](https://www.reddit.com/r/RISCV/comments/1i1v7mo/genshin_impact_running_on_riscv_sg2044_evb_with)
 - RSS feed: $source
 - date published: 2025-01-15T11:15:59+00:00

<table> <tr><td> <a href="https://www.reddit.com/r/RISCV/comments/1i1v7mo/genshin_impact_running_on_riscv_sg2044_evb_with/"> <img src="https://external-preview.redd.it/uq7Pny586O382UOreI_MmLd7uDpP9lW4-dHJqZUTfN8.jpg?width=320&amp;crop=smart&amp;auto=webp&amp;s=f107abc77810ecb4f8371813ab86b3544a04e159" alt="Genshin Impact running on RISC-V (SG2044 EVB) with Box64" title="Genshin Impact running on RISC-V (SG2044 EVB) with Box64" /> </a> </td><td> &#32; submitted by &#32; <a href="https://www.reddit.com/user/mrksco"> /u/mrksco </a> <br/> <span><a href="https://www.youtube.com/watch?v=P_fApiLERLI">[link]</a></span> &#32; <span><a href="https://www.reddit.com/r/RISCV/comments/1i1v7mo/genshin_impact_running_on_riscv_sg2044_evb_with/">[comments]</a></span> </td></tr></table>

