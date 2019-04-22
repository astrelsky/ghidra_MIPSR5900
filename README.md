MIPSR5900le Ghidra Processor Specifications
=======================

The following has been created using publicly available information.
As such it may contain errors.

LICENSE
=======

All files taken or modified from the Ghidra MIPS processor fall under
the Apache 2.0 license. The corresponding LICENSE file has been placed
in the folders containing these files. All subfolders with the corresponding
LICENSE file fall under said license.

Instruction Sources
===================

The following are the primary sources for the instruction information.

* [EE Instruction Reference](http://lukasz.dk/files/tx79architecture.pdf)
* [VU Instruction Reference](http://lukasz.dk/files/vu-instruction-manual.pdf)

Missing Instructions
====================

If a missing instruction is encountered, please verify the instruction
mnemonic and byte string using ps2dis. If it is not a VU instruction
please open an issue.

Known Bugs
==========

'Unaffected' Registers appear as a variable after decompilation.
Running 'No Return' analysis causes returning functions to be marked
as no return. This causes control flow to break. Please ensure that
no return analysis is disabled.

TODO
====

* VU Support
* DWARF information for new/special registers
* Memory Map
* Fix DWARF File Reading
