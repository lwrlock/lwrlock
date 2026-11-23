### Furkan (`@lwrlock`)

Computer Engineering student building Linux kernel/hardware telemetry tools, deterministic distributed orchestrators, quantitative financial simulators, audio DSP instruments, and reverse-engineering utilities in C, Python, x86_64/eBPF, and modern vanilla Web UIs.

<p align="center">
  <a href="https://github.com/lwrlock/ff-power-manager">
    <img src="https://raw.githubusercontent.com/lwrlock/ff-power-manager/main/docs/screenshots/showcase.gif" alt="FF Power Manager Showcase" width="860"/>
  </a>
</p>

### Featured Interactive Studios & Distributed Systems

| Project | Stack | Theme & Architecture | Repository |
| :--- | :--- | :--- | :--- |
| [flowforge](https://github.com/lwrlock/flowforge) | `FastAPI`, `Asyncio`, `SQLite WAL`, `Canvas` | Deterministic DAG Workflow Engine, CPM Critical Path, Saga Compensation, Time-Travel Replay & Linear-inspired Left-Rail Observatory | [Repo](https://github.com/lwrlock/flowforge) |
| [cortexscope](https://github.com/lwrlock/cortexscope) | `FastAPI`, `Ollama Proxy`, `Intel RAPL`, `SVG` | Streaming Local LLM Telemetry Proxy (`TTFT`/`ITL` + `Joules/100tok`), A/B Arena & Charcoal Analog VU Mastering Console | [Repo](https://github.com/lwrlock/cortexscope) |
| [sonatarack](https://github.com/lwrlock/sonatarack) | `FastAPI`, `NumPy/SciPy`, `Web Audio API` | Polyphonic FM Synth, Bjorklund Euclidean Sequencer, 48-Band FFT, WAV Export & Walnut/Vinyl Hardware Rack | [Repo](https://github.com/lwrlock/sonatarack) |
| [hexward](https://github.com/lwrlock/hexward) | `FastAPI`, `PE64/ELF64`, `Pillow`, `NumPy` | Game Modding VFS Load-Order Solver (Kahn DAG), 3-Way Config Merger, Shannon Entropy/AOB Dissector & Outrun Synthwave UI | [Repo](https://github.com/lwrlock/hexward) |
| [quantpress](https://github.com/lwrlock/quantpress) | `FastAPI`, `NumPy`, `SciPy`, `Canvas` | FIFO Limit Order Book Simulator, Zero-Lookahead Walk-Forward Backtester, VaR/CVaR Risk & Swiss Editorial Broadsheet | [Repo](https://github.com/lwrlock/quantpress) |
| [echoroom](https://github.com/lwrlock/echoroom) | `FastAPI`, `NumPy`, `Acoustics Physics` | 2D Specular Acoustic Ray-Tracer, Room Standing-Wave Eigenmode Field, Eyring/Sabine RT60 & Nordic Aurora Observatory | [Repo](https://github.com/lwrlock/echoroom) |

### Linux Systems, Kernel, eBPF & Hardware Utilities

| Project | Stack | Summary | Preview |
| :--- | :--- | :--- | :--- |
| [ff-power-manager](https://github.com/lwrlock/ff-power-manager) | `C`, `x86_64 ASM`, `Python`, `GTK4` | Laptop power profiles, `ffctl` CLI, `s2idle` standby drain reports, per-PID blame, adaptive refresh (`60↔120Hz`), and ISH ToF presence lock | [Pages](https://lwrlock.github.io/ff-power-manager/) |
| [ebpf-latency-guard](https://github.com/lwrlock/ebpf-latency-guard) | `C`, `eBPF`, `Python`, `GTK4` | Unprivileged PSI, `schedstat`, and `/proc/interrupts` latency sampler paired with a compiled `sched_wakeup`/`sched_switch` eBPF tracepoint object | [GIF](https://raw.githubusercontent.com/lwrlock/ebpf-latency-guard/main/docs/screenshots/showcase.gif) |
| [vram-atlas](https://github.com/lwrlock/vram-atlas) | `C`, `Python`, `GTK4` | Reads DRM GPU sysfs (`xe`/`amdgpu`), Intel NPU (`intel_vpu`), `/proc/meminfo` shared pool, and `llama.cpp` `/metrics` throughput | [GIF](https://raw.githubusercontent.com/lwrlock/vram-atlas/main/docs/screenshots/showcase.gif) |
| [waylens-privacy](https://github.com/lwrlock/waylens-privacy) | `C`, `Python`, `GTK4` | USB HID/storage device baseline checker, ST VL53L1 presence lock reader, `ssh-add -D` trigger, and SHA-256 hash-chained `audit.jsonl` logger | [GIF](https://raw.githubusercontent.com/lwrlock/waylens-privacy/main/docs/screenshots/showcase.gif) |
| [mempulse](https://github.com/lwrlock/mempulse) | `C`, `Python`, `GTK4` | Inspects Linux MGLRU (`lru_gen`), `zram0/mm_stat`, memory PSI, and per-process RSS/swap usage | [GIF](https://raw.githubusercontent.com/lwrlock/mempulse/main/docs/screenshots/showcase.gif) |
| [netpulse-bpf](https://github.com/lwrlock/netpulse-bpf) | `C`, `eBPF`, `Python`, `GTK4` | Reads NIC counters, `tcp_congestion_control`, `default_qdisc`, `/proc/net/snmp` retransmits, and process sockets, plus a `sock_ops` eBPF hook | [GIF](https://raw.githubusercontent.com/lwrlock/netpulse-bpf/main/docs/screenshots/showcase.gif) |
| [nvme-sentinel](https://github.com/lwrlock/nvme-sentinel) | `C`, `Python`, `GTK4` | Displays NVMe `hwmon` temperature, PCIe link speed/width, `default_ps_max_latency_us` (APST), and `/sys/block/nvme*` IOPS | [GIF](https://raw.githubusercontent.com/lwrlock/nvme-sentinel/main/docs/screenshots/showcase.gif) |
| [quant-wealth-terminal](https://github.com/lwrlock/quant-wealth-terminal) | `FastAPI`, `SQLite`, `JS` | Portfolio tracker, TEFAS fund data viewer, and simple strategy backtester | — |

### Stack & Development
- **Languages:** C, Python, x86_64 Assembly, restricted C (eBPF), Modern ES Modules
- **Linux Interfaces:** `sysfs`, `procfs`, `hwmon`, `powercap`/RAPL, DRM/`accel`, PolicyKit, Wayland D-Bus
- **UI:** GTK 4, Libadwaita, Cairo, Custom Architectural HTML5 Canvas / SVG
- **Workflow:** Built test-first (`pytest`, `node:test`), verified end-to-end in Chromium, and cross-documented in Obsidian.
