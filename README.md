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
| [dev-atelier](https://github.com/lwrlock/dev-atelier) | `FastAPI`, `Asyncio`, `SQLite WAL`, `Intel RAPL`, `PE64/ELF64`, `Canvas/SVG` | Unified 3-studio developer workbench (`dev-atelier` CLI): **FlowForge** (DAG orchestrator, CPM critical path, saga & replay), **CortexScope** (Ollama proxy, TTFT/ITL + RAPL energy console), and **HexWard** (modding VFS solver, 3-way merge & binary/texture dissector) | [Repo](https://github.com/lwrlock/dev-atelier) |
| [sonatarack](https://github.com/lwrlock/sonatarack) | `FastAPI`, `NumPy/SciPy`, `Web Audio API`, `Acoustics Physics` | Unified Audio DSP & Spatial Acoustics Suite: Polyphonic FM Synth, Bjorklund Euclidean Sequencer, 48-Band FFT & Walnut Hardware Rack + 2D Specular Acoustic Ray-Tracer, Standing-Wave Eigenmodes & Eyring/Sabine RT60 Observatory (`/acoustics`) | [Repo](https://github.com/lwrlock/sonatarack) |

> *Standalone prototypes (`flowforge`, `cortexscope`, `hexward` -> `dev-atelier`; `echoroom` -> `sonatarack`) are consolidated into the two flagship suites above.*

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
