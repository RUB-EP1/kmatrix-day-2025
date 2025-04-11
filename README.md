# International K-Matrix Day 2025

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Pixi Badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/prefix-dev/pixi/main/assets/badge/v0.json)](https://pixi.sh)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![Spelling checked](https://img.shields.io/badge/cspell-checked-brightgreen.svg)](https://github.com/streetsidesoftware/cspell/tree/master/packages/cspell)

This is the source code for the **[rub-ep1.github.io/kmatrix-day-2025](https://rub-ep1.github.io/kmatrix-day-2025)** website. <!-- cspell:ignore kmatrix -->

To help developing this repository, all you need is [Git](https://git-scm.com), a [GitHub account](https://github.com/signup), and an installation of **[Pixi](https://pixi.sh)**.

1. Install Pixi[^pixi-install] and restart your terminal:
   ```bash
   curl -fsSL https://pixi.sh/install.sh | sh
   ```
2. Clone this repository and navigate into it:
   ```bash
   git clone https://github.com/RUB-EP1/kmatrix-day-2025
   ```
3. All dependencies, such as Julia and Python, are installed through Pixi. Simply run:
   ```bash
   pixi install
   ```

[^pixi-install]: This only works on Linux and MacOS. See [these installation instructions](https://pixi.sh) for other operating systems.

The local Pixi config defines a few aliases for the main commands that are relevant for this repository.

- Start Jupyter Lab for Python notebooks:
  ```bash
  pixi run lab
  ```
- Start a Pluto server for Julia notebooks:
  ```bash
  pixi run pluto
  ```
- Run the Julia notebooks:
  ```bash
  pixi run pluto-server
  ```
- Start a live preview for the website:
  ```bash
  pixi run doclive
  ```
- Execute all notebooks and build a static version of the website:
  ```bash
  pixi run docnb
  ```
  <!-- cspell:ignore docnb -->
