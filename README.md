# Hermes Reisner

I'm a computer science student in Basel. I build tools for image and video
restoration, ML training, GPU kernels, music and embedded systems, mostly with
Python, C, C++, Java and ESP32 boards.

My portfolio and CV can be found here:
**[hermesreisner.com](https://hermesreisner.com/)**.

## LocalSR

A free, open-source desktop app for upscaling, denoising and restoring images
and video on your own computer. It runs on macOS (Metal), Windows and Linux;
Tauri and Svelte host, PyTorch engine. In beta. Its Quick and Best Quality
presets use my own small photo models, which run on Apple's Neural Engine.

[Try it in your browser](https://herrei.github.io/localsr/demo/) ·
[Showcase and downloads](https://herrei.github.io/localsr/) ·
[Source](https://github.com/HerRei/local-upscale) ·
[Write-up](https://hermesreisner.com/work/localsr/) ·
[Models](https://github.com/HerRei/localsr-models) ·
[Models write-up](https://hermesreisner.com/work/localsr-models/)

On a Mac: `brew install --cask herrei/tap/localsr`

## All projects

| Project | What it does | Links |
| --- | --- | --- |
| **LocalSR** | A free, open-source desktop app for upscaling, denoising and restoring images and video on your own computer. It runs on macOS, Windows and Linux. | [Code](https://github.com/HerRei/local-upscale) · [Demo](https://herrei.github.io/localsr/demo/) · [Showcase](https://herrei.github.io/localsr/) · [Write-up](https://hermesreisner.com/work/localsr/) |
| **LocalSR Photo models** | Two small 4x photo upscalers for LocalSR, trained only on CC0 photos. They run entirely on Apple's Neural Engine and stay fast on old computers without one. | [Code](https://github.com/HerRei/localsr-models) · [Download](https://github.com/HerRei/localsr-models/releases/tag/v1) · [Report (PDF)](https://github.com/HerRei/localsr-models/blob/master/report/localsr-models.pdf) · [Write-up](https://hermesreisner.com/work/localsr-models/) |
| **gfx906 decode kernels** | Two llama.cpp HIP kernels that make single-token decode faster on AMD gfx906 cards (Radeon VII, MI50, MI60). Written with an AI agent, then checked against llama.cpp's CPU reference and measured on the card. | [Code](https://github.com/HerRei/gfx906-decode-kernels) · [Write-up (PDF)](https://github.com/HerRei/gfx906-decode-kernels/blob/main/writeup/gfx906-decode-kernels.pdf) |
| **FlashVSR for Apple Silicon** | An unofficial MLX port of FlashVSR v1.1, a one-step diffusion model that upscales video 4x. The sparse attention runs in its own Metal kernel. | [Code](https://github.com/HerRei/flashvsr-mlx) |
| **SEC filing forecasts** | A small Transformer that forecasts how far a stock can move after a 10-Q or 10-K filing. The final test rules were written down and hashed before any outcome existed, then run once on 3,329 real filings. | [Code](https://github.com/HerRei/sec-filing-forecasts) · [Demo](https://herrei.github.io/sec-filing-forecasts/) · [Findings (PDF)](https://github.com/HerRei/sec-filing-forecasts/blob/main/findings/findings.pdf) · [Write-up](https://hermesreisner.com/work/finance-forecasting/) |
| **Piano models** | Two small models that write piano music as MIDI: a GPT-2 trained on MAESTRO that continues a passage, and an RWKV-7 whose density and loudness a game can steer live, running on the Neural Engine. | [Code](https://github.com/HerRei/gpt2-piano-mps-12k) · [Showcase](https://herrei.github.io/gpt2-piano-mps-12k/) · [Write-up](https://hermesreisner.com/work/gpt2-piano/) |
| **train-tui** | A dependency-free C terminal dashboard for ML training runs, with AMD and NVIDIA GPU monitoring. | [Code](https://github.com/HerRei/train-tui) · [Demo](https://herrei.github.io/train-tui/) · [Write-up](https://hermesreisner.com/work/train-tui/) |
| **SBB departure board** | An ESP32 display for Swiss public transport departures, updated live from the OpenData API. | [Code](https://github.com/HerRei/Sbb_Tracker_Sissach) · [Showcase](https://herrei.github.io/Sbb_Tracker_Sissach/) · [Write-up](https://hermesreisner.com/work/departure-board/) |
| **Flying wing** | My Matura project: a 95 cm balsa flying wing with its own flight computer and sensors. | [Write-up](https://hermesreisner.com/work/flying-wing/) |
| **Nature Inventory Delta** | Local tools for querying and visualising changes in the Basel-Stadt nature inventory. Early stage, paused for now. | [Code](https://github.com/HerRei/nature-inventory-delta-ai) · [Showcase](https://herrei.github.io/nature-inventory-delta-ai/) · [Write-up](https://hermesreisner.com/work/nature-inventory-delta/) |
| **PhantomHunt** | An asymmetric 3-vs-1 Java/JavaFX multiplayer game from a University of Basel team project, with client-server networking, lobbies, chat, spectators and scoring. | [Code](https://github.com/HerRei/PhantomHunt) · [Showcase](https://herrei.github.io/PhantomHunt/) · [Browser prototype](https://herrei.github.io/mockup/) · [Write-up](https://hermesreisner.com/work/phantomhunt/) |
| **TSP / ant colony** | A Java Swing visualiser for ant colony optimisation on the travelling salesman problem. | [Code](https://github.com/HerRei/tsp_aco_gui) · [Demo](https://herrei.github.io/tsp_aco_gui/) · [Write-up](https://hermesreisner.com/work/tsp-ant-colony/) |
| **Google Sheets automation** | A small Python tool that turns repetitive bookkeeping entries into a few clicks through the Sheets API. | [Code](https://github.com/HerRei/google_sheets_automation) · [Showcase](https://herrei.github.io/google_sheets_automation/) · [Write-up](https://hermesreisner.com/work/google-sheets-automation/) |
| **Telegram YouTube player** | Telegram-controlled fullscreen YouTube playback on a chosen monitor of my home server. | [Code](https://github.com/HerRei/telegram-youtube-player) · [Write-up](https://hermesreisner.com/work/telegram-youtube-player/) |
| **HAT (fork)** | My fork of the CVPR 2023 / TPAMI image-restoration transformer, extended with face-restoration fine-tuning experiments and recovery reports. | [Code](https://github.com/HerRei/HAT) |
| **Quantum Blender AO** | A self-directed experiment comparing exact, Monte Carlo, and simulated quantum amplitude estimation for ambient visibility in Blender renders. | [Code](https://github.com/HerRei/quantum-blender-ao) |

## Contact

[hermes.reisner@gmail.com](mailto:hermes.reisner@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/hermes-reisner-171143353/) ·
[hermesreisner.com](https://hermesreisner.com/)
