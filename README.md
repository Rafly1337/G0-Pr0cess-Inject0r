# G0-Pr0cess-Inject0r
Proof of concept for single/multiple shellcode process injection malware in Go language.

Contains two programs:

Multi: multi-threaded malware to recursively scan and inject multiple processes' space with little cpu and memory usage

Single: malware to scan for target processes once a target process id is found the program will inject shellcode into target process space and exit
