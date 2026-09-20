graduated undergrad computer science '26 @ Williams College (MA, USA). 

looking for work in traditional compilers, ML compilers, kernels, systems, c++

experienced in C++, Python, F#, C#

super super interested in compiler/programming language development and tools

email: ryunosukeyanashita@gmail.com

linkedin: [https://www.linkedin.com/in/ryunosuke-rick-yanashita](https://www.linkedin.com/in/ryunosuke-rick-yanashita)

## Open Source contributions for LLVM
- **[llvm/llvm-project PR #219598](https://github.com/llvm/llvm-project/pull/219598)**
  - Added an optimization in InstCombine for combining adjacent extracted bit fields, which restored an optimization regression which started in Clang 14
  - Involves separate truncation + logical right shift, and bitfield extraction.
  - The fold combines: ``` (trunc (lshr X, S) & M0) | (lshr (trunc X), S & M1) --> (trunc (lshr X, S) & (C0 | C1)) ```
  - Added an alive2 proof, and implemented positive, negative, multi-use, commuted, and vector tests

## Projects

2ptx Compiler: Compiler custom DSL to PTX for execution on Nvidia GPU

Lambda Calculus Solver in F#

Plus-Lang-Extended Compiler in F#: My own programming language, with lexer, parser, and code generation. 

"Text Classification Accuracy of Politically-Biased Language Models": NLP Project comparing LLM performance using Python, PyTorch, NumPy, and HuggingFace Transformers. 

Simple LLVM Passes and Code Optimizations. 

Running Training Plan LP/MIP

Python-Keylogger

Artificial Life Simulators
