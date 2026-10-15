# jukefa - Jülich Kernel Factory

jukefa, the Jülich Kernel Factory, develops sets of tools to generate, build,
benchmark and tune compute kernels for performance.

## Tools

| Tool                             | Purpose                                                      |
| -------------------------------- | ------------------------------------------------------------ |
| [asmgen][asmgen]                 | generate GAS-style inline assembly for C and C++             |
| [ukrgen][ukrgen]                 | generate microkernels on top of asmgen                       |
| [blis-ukr-bench][blis-ukr-bench] | benchmark a BLIS microkernel in isolation                    |
| [blistune][blistune]             | autotune BLIS block sizes and thread decomposition           |

[asmgen]: https://github.com/FZJ-JSC/jukefa-asmgen
[ukrgen]: https://github.com/FZJ-JSC/jukefa-ukrgen
[blis-ukr-bench]: https://github.com/FZJ-JSC/jukefa-blis-ukr-bench
[blistune]: https://github.com/FZJ-JSC/jukefa-blistune

