# Building-Shell-in-C
The programming language selected is "C" because C itself was developed to serve as the system implementation language for the Unix operating system which helps us with functions that can work directly with Operating System.

# Situation before C:
In the late 1960s and early 1970s, programmers mainly had two choices:
```text
1. Assembly language
  	•	Very fast
  	•	Very close to hardware
  	•	But extremely hard to write, read, and maintain
  	•	Code written for one machine would not run on another
2. High-level languages (like FORTRAN, COBOL)
  	•	Easier to write
  	•	Portable
  	•	But too slow and not flexible enough for system-level work
      (like operating systems, compilers, device drivers)

There was no language that balanced both worlds.
```
At Bell Labs, engineers were building an operating system called UNIX.
```
Initially:
	•	UNIX was written in assembly
	  This made it:
    	•	Hard to maintain
    	•	Hard to move to new hardware      (As this was all Assembly)
    	•	Painful to extend

They wanted:
	•	The performance of assembly
	•	The readability and portability of high-level languages
```
## The core idea behind C
```
“Give programmers direct control over memory and hardware without forcing them to write assembly.”
```
## What C was designed to do (intentionally)
```text
1. Be good for systems programming
    C was made to:
    	•	Write operating systems
    	•	Build compilers
    	•	Talk directly to memory and hardware
    
    That’s why C gives you:
    	•	Pointers
    	•	Manual memory management
    	•	Bit-level operations
2. Be portable
    This was revolutionary.
    
    UNIX was rewritten in C, and suddenly:
    	•	UNIX could be moved to different machines
    	•	Only a small part needed rewriting
    	•	The rest stayed the same
     This proved that operating systems could be written in a high-level language.
3. Be minimal and efficient
    C intentionally:
    	•	Has very few keywords
    	•	Avoids heavy abstractions
    	•	Maps almost directly to machine instructions
    
    That’s why:
    	•	C code is fast
    	•	Compilers are simple and powerful
```
	•	Almost every OS is written in C or C++
	•	Most languages (Java, Python, Go, Rust) are influenced by C
	•	Understanding C helps you understand:
  	•	Memory
  	•	Processes
  	•	System calls
  	•	How computers actually work
