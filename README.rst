
Mango interpreter
===============================

Mango is a statically typed programming language that is designed to be compiled to WebAssembly.

So why an interpreter? There are a few reasons:

* It is faster to implement features in the interpreter, for prototyping.
* To support platforms that are not (yet) targeted by the compiler.
* Possibly to one day support an interactive console (REPL).

This project does not directly interpret Mango source code. Instead `the compiler`_ 'frontend' converts the code to an intermediary format, which is interpreted. Code is still fully checked in the same way as the compiler does, but wasm generation (and optimization) are skipped.

Note that, for the time being, the intermediary format has no stability guarantees.

Status
-------------------------------

This project is still in early development stage. It is not ready to use, not even experimentally.

Links
-------------------------------

* `Official website`_
* `Documentation`_
* `Code of conduct and contributing`_


.. _`Official website`: https://mangocode.org/
.. _`Documentation`: https://docs.mangocode.org/
.. _`Code of conduct and contributing`: https://github.com/mangolang/mango
.. _`the compiler`: https://github.com/mangolang/compiler

