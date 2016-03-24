Google Experimental Language #2 (GEL2) is an experimental general-purpose object-oriented programming language.  GEL2 is essentially a subset of C#, extended with an ownership-based type system which allows GEL2 to free memory safely and deterministically without using a garbage collector.

This implementation of GEL2 includes an interpreter and a compiler which generates C++ code.  The implementation is mostly intended as an experimental prototype intended to demonstrate the viability of a type system based on ownership.  The language is large enough to write useful programs, such as the GEL2 interpreter/compiler itself.

GEL2 originated as a research project I developed while working at Google.  I'd like to thank Google for allowing me to release GEL2 as open source.