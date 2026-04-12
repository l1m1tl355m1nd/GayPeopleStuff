<p align="center">
  <img src=".github/header.png" alt="L1M1TL355 CPU" width="600"/>
</p>

<h1 align="center">L1M1TL355-CPU</h1>

<p align="center">
  A custom 32-bit CPU designed and implemented from scratch using Logisim-Evolution.
</p>

<p align="center">
  <a href="https://l1m1tl355m1nd.github.io/L1M1TL355-CPU/">Documentation</a>
  &nbsp;·&nbsp;
  <a href="https://discord.gg/pyssXESdPr">Discord</a>
  &nbsp;·&nbsp;
  <a href="LICENSE">License</a>
</p>

---

## Overview

L1M1TL355-CPU is a personal project to design and build a functional 32-bit CPU architecture from first principles. The project covers digital logic design, custom instruction set architecture, and lays groundwork toward a future bootloader and minimal operating system.

This repository serves as both a working implementation and a public record of the design process.

---

## Repository Structure

cpu_ver_1
  contains customasm code, logisim project and images
cpu_ver_2
  contains logisim project and images
images
  contains image for html
---

## Features

- Full ISAs reference available at the [documentation site](https://l1m1tl355m1nd.github.io/L1M1TL355-CPU/)
- CPUs made in logisim-evolution

---

## Project Roadmap

- [x] Define and document instruction set architectures
- [ ] Create a pipelined cpu (in progress)
.
.
.
(more steps in between as I'm learning)
- [ ] Create a cpu good enough for fpga usage
- [ ] Create operating system for cpu
---

## Getting Started

1. Install [Logisim-Evolution](https://github.com/logisim-evolution/logisim-evolution/releases)
2. Clone this repository:
   ```sh
   git clone https://github.com/l1M1TL355M1ND/L1M1TL355-CPU.git
   ```
3. Open chosen project in Logisim-Evolution

Refer to the [ISA documentation](https://l1m1tl355m1nd.github.io/L1M1TL355-CPU/) for instruction encoding details.

---

## Tools

| Tool | Purpose |
|------|---------|
| [Logisim-Evolution](https://github.com/logisim-evolution/logisim-evolution) | Digital logic simulation and circuit design |
| [customasm](https://github.com/hlorenzi/customasm) | Custom assembler using `#ruledef` syntax |

---

## Contributing

Contributions, feedback, and suggestions are welcome. You can:

- **Star or watch** the repository to follow progress
- **Open an issue** with advice, resources, or design feedback
- **Join the [Discord](https://discord.gg/pyssXESdPr)** to discuss the project

This is currently a solo learning project. Large pull requests may take time to review.

---

## License

See the [LICENSE](LICENSE) file for details.

---

## Author

**l1M1TL355M1ND**