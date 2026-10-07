<p align="center">
  <img src="./banner.svg?v=3" width="900" alt="Boyi Dai — Computer Engineering student at UVA. Interested in systems, infrastructure, and compilers." />
</p>

## Languages and tools

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![VHDL](https://img.shields.io/badge/VHDL-543978)

![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![WebGPU](https://img.shields.io/badge/WGSL-WebGPU-005A9C)
![Pyodide](https://img.shields.io/badge/Pyodide-WebAssembly-654FF0)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-Cyclone%20V-0071C5?logo=intel&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?logo=kicad&logoColor=white)

## Projects

### Systems and ML infrastructure

- **[nanoinfer](https://github.com/SpookyJumpyBeans/nanoinfer)**: an LLM inference engine written from scratch in Python and Rust SIMD. Its int8 path decodes Qwen2.5-0.5B 1.4 to 1.6× faster than llama.cpp's Q8_0 on the same laptop, at a sixth of the quality loss.

### Data systems

- **[tinyquery](https://github.com/SpookyJumpyBeans/tinyquery)**: a single-node SQL engine with a parser, iterator plans, hash join and hash aggregate. [Live demo](https://spookyjumpybeans.github.io/tinyquery/), running in the browser under Pyodide.
- **[tinydelta](https://github.com/SpookyJumpyBeans/tinydelta)**: a single-node table format with an atomic JSON commit log, time travel and optimistic concurrency.

### Computer architecture

- **[toy-cpu](https://github.com/SpookyJumpyBeans/toy-cpu)**: an 8-bit multi-cycle CPU in structural VHDL with hardwired control and a 14-instruction ISA, synthesized for a Cyclone V FPGA in 73 ALMs. [Browser simulator](https://spookyjumpybeans.github.io/toy-cpu/).

### Signals and analog hardware

- **[RAPTOR](https://github.com/SpookyJumpyBeans/RAPTOR)**: Autotune from scratch in NumPy, with STFT pitch tracking, equal-temperament note quantization and pitch correction.
- **[audio-analyzer](https://github.com/SpookyJumpyBeans/audio-analyzer)**: a two-band analog audio analyzer built on Sallen-Key active filters, simulated in KiCad and measured on hardware within 3.7% of theory.

### Algorithms

- **[leetcode-submissions](https://github.com/SpookyJumpyBeans/leetcode-submissions)**: my accepted LeetCode and NeetCode solutions in Java and C++, grouped by topic and synced automatically by a tool I wrote.
