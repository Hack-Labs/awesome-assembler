# Awesome Assembler

A curated list of awesome ⚙️Assembler for x86_64/x86/aarch64/aarch/risc-v/etc


## Table of content
<details>
<summary>Click to expand</summary>

- [Awesome Assembler](#awesome-assembler)
  - [Table of content](#table-of-content)
  - [Books](#books)
  - [Assemblers](#assemblers)
    - [Self-hosted hex assemblers](#self-hosted-hex-assemblers)
  - [Disasembler](#disasembler)
  - [Debuger](#debuger)
  - [Soft](#soft)
    - [Shells](#shells)
    - [Social Media](#social-media)
    - [WebServer](#webserver)
    - [Webapp](#webapp)
  - [External links](#external-links)
</details>

## Books

<img height="50px" width="36px" hspace="10px" src="https://m.media-amazon.com/images/I/41fIax7nupL._SX404_BO1,204,203,200_.jpg"> [Professional Assembly Language](https://www.amazon.com/Professional-Assembly-Language-Richard-Blum/) **by Richard Blum**

<img height="50px" width="36px" hspace="10px" src="https://media.springernature.com/full/springer-static/cover-hires/book/978-1-4842-0064-3?as=webp">[Modern X86 Assembly Language Programming](http://www.apress.com/9781484200650) 32-bit, 64-bit, SSE, and AVX by **Daniel Kusswurm**

<img height="50px" width="36px" hspace="10px" src="https://m.media-amazon.com/images/I/41+MUyWhvHL._SX258_BO1,204,203,200_.jpg">[Assembly Language for x86 Processors, 7th edition](https://www.amazon.com/Assembly-Language-x86-Processors-7th/dp/0133769402) by **Kip Irvine** 

<img height="50px" width="36px" hspace="10px" src="https://nostarch.com/sites/default/files/styles/uc_product_full/public/assembly2_big.png?itok=wSMa6PaB">[The Art of Assembly Language, 2nd Edition](http://www.nostarch.com/assembly2.htm) by **Randall Hyde**

## Assemblers
> [Gnu Assembler (GAS)](http://www.gnu.org/software/binutils/)
is a fast assembly language compiler for the x86/x86_64/aarch/aarch64/mips/mips64/etc architectures. Is a basic assembler that is included in a large number of unix like systems, it supports [AT&T](https://ru.wikipedia.org/wiki/AT%26T-%D1%81%D0%B8%D0%BD%D1%82%D0%B0%D0%BA%D1%81%D0%B8%D1%81) and Intel notation

> [Flat Assembler (FASM)](http://flatassembler.net/)
is a fast assembly language compiler for the x86 architecture processors, which does multiple passes to optimize the size of generated machine code

> [Microsoft Macro Assembler (MASM)](https://www.microsoft.com/en-us/download/details.aspx?id=12654)
is an x86 assembler that uses the Intel syntax for MS-DOS and Microsoft Windows

> [Netwide Assembler (NASM)](http://www.nasm.us/)
is an assembler and disassembler for the Intel x86 architecture

> [YASM](http://yasm.tortall.net/)
is an assembler and disassembler for the Intel x86 architecture. Yasm is a full rewrite of Netwide Assembler (NASM).


> [PeachPy](https://github.com/Maratyszcza/PeachPy)
is an x86-64 assembler embedded in Python which targets high-performance computing audience. PeachPy can generate object files or assembly listings for Windows, Linux, Mac OS X, Native Client, and Go from the same source

### Self-hosted hex assemblers

> [Richard's compiler bootstrap experiment](https://github.com/ras52/bootstrap) — This is an experiment in developing from scratch a working compiler, assembler, linker and library for a language similar to C. Contain: a tiny program for packing hexadecimal octets into binary and self-hosted assembler.


> [bcompiler](https://github.com/certik/bcompiler) — Another experiment in creating a compiler from nothing, via a self-hosted assembler

## Disasembler
* [IDA PRO](https://www.hex-rays.com/ida-pro) — 32/64-bit proprietary software. [wiki](http://en.wikipedia.org/wiki/Interactive_Disassembler)
* [IDA Free](https://www.hex-rays.com/ida-free) — The free version of IDA
## Debuger
* [Syser Kernel Debugger](https://github.com/marakew/syser) is designed for Windows NT Family based on X86 platform. It is a kernel debugger with full-graphical interfaces and supports assembly debugging and source code debugging.
* [Radare2](http://rada.re) — An open-source complete framework for reverse-engineering and analyzing binaries; composed of a set of small utilities that can be used together or independently from the command line.
* [Plasma](https://github.com/plasma-disassembler/plasma) — Plasma is an interactive disassembler for x86/ARM/MIPS. It can generates indented pseudo-code with colored syntax.

## Soft
### Shells
* [x86-asm-sysh](https://github.com/StefanoBelli/sysh) — A weird assembly coded shell
### Social Media
* [x86_64-asm-tgbot](https://github.com/StefanoBelli/x86_64-asm-tgbot) — Attempting to build an x86_64 assembly telegram bot with a bit of C
### WebServer
* [RWASA]() — is our full-featured, high performance, scalable web server designed to compete with the likes of nginx. It has been built from the ground-up with no external library dependencies entirely in <b>x86_64</b> assembly language, and is the result of many years' experience with high volume web environments.
* [asmttpd](https://github.com/nemasu/asmttpd) — Web server for Linux written in amd64 assembly
### Webapp
* [AsmBB](https://asmbb.org/what-is-asmbb.1/) — is ultrafast web forum, written entirely in assembly language.


## External links
* [Unix Assembly Language Programming](http://www.int80h.org)
* [Linux Assembly](http://asm.sourceforge.net/)
* [PPR: Learning Assembly Language](http://c2.com/cgi/wiki?LearningAssemblyLanguage)
* [Assembly Language Programming Examples](http://www.azillionmonkeys.com/qed/asmexample.html)	
* [Authoring Windows Applications In Assembly Language](http://www.grc.com/smgassembly.htm)
* [Assembly Optimization Tips by Mark Larson](http://mark.masmcode.com/)
* [Introduction to programming using Linux assembly language](http://www.programminggroundup.blogspot.fi/)
* [x86 Assembly Guide](http://www.cs.virginia.edu/~evans/cs216/guides/x86.html)
* [x86 Assembly Wikibook](https://en.wikibooks.org/wiki/X86_Assembly)
* [x86 Disassembly Wikibook](https://en.wikibooks.org/wiki/X86_Disassembly)
* [Software written primarily in assembly language](https://en.wikipedia.org/wiki/Category:Software_written_primarily_in_assembly_language)
* [Novice and Advanced Assembly resources for x86 Platform](http://www.intel-assembler.it/portale/indice.asp)
* [GCC-Inline-Assembly-HOWTO](http://www.ibiblio.org/gferg/ldp/GCC-Inline-Assembly-HOWTO.html)
* [Introductory Intel x86: Architecture, Assembly, Applications & Alliteration](http://opensecuritytraining.info/IntroX86.html)
* [PC Assembly Language](http://pacman128.github.io/pcasm/)

----------


[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)