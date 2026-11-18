### Furkan (`@lwrlock`)

Computer Engineering student working on Linux hardware telemetry, power management utilities, eBPF experiments, and GTK4 desktop tools in C and Python.

### Repositories

| Project | Stack | Summary | Preview |
| :--- | :--- | :--- | :--- |
| [ff-power-manager](https://github.com/lwrlock/ff-power-manager) | `C`, `x86_64 ASM`, `Python`, `GTK4` | Laptop power profiles, `ffctl` CLI, `s2idle` standby drain reports, per-PID blame, adaptive refresh (`60↔120Hz`), and optional ISH ToF presence lock | [Pages](https://lwrlock.github.io/ff-power-manager/) |
| [ebpf-latency-guard](https://github.com/lwrlock/ebpf-latency-guard) | `C`, `eBPF`, `Python`, `GTK4` | Unprivileged PSI, `schedstat`, and `/proc/interrupts` latency sampler paired with a compiled `sched_wakeup`/`sched_switch` eBPF tracepoint object | [Screenshot](https://raw.githubusercontent.com/lwrlock/ebpf-latency-guard/main/docs/screenshots/overview.png) |
| [vram-atlas](https://github.com/lwrlock/vram-atlas) | `C`, `Python`, `GTK4` | Reads DRM GPU sysfs (`xe`/`amdgpu`), Intel NPU (`intel_vpu`), `/proc/meminfo` shared pool, and `llama.cpp` `/metrics` throughput | [Screenshot](https://raw.githubusercontent.com/lwrlock/vram-atlas/main/docs/screenshots/overview.png) |
| [waylens-privacy](https://github.com/lwrlock/waylens-privacy) | `C`, `Python`, `GTK4` | USB HID/storage device baseline checker, ST VL53L1 presence lock reader, `ssh-add -D` trigger, and SHA-256 hash-chained `audit.jsonl` logger | [Screenshot](https://raw.githubusercontent.com/lwrlock/waylens-privacy/main/docs/screenshots/overview.png) |
| [mempulse](https://github.com/lwrlock/mempulse) | `C`, `Python`, `GTK4` | Inspects Linux MGLRU (`lru_gen`), `zram0/mm_stat`, memory PSI, and per-process RSS/swap usage | [Screenshot](https://raw.githubusercontent.com/lwrlock/mempulse/main/docs/screenshots/overview.png) |
| [netpulse-bpf](https://github.com/lwrlock/netpulse-bpf) | `C`, `eBPF`, `Python`, `GTK4` | Reads NIC counters, `tcp_congestion_control`, `default_qdisc`, `/proc/net/snmp` retransmits, and process sockets, plus a `sock_ops` eBPF hook | [Screenshot](https://raw.githubusercontent.com/lwrlock/netpulse-bpf/main/docs/screenshots/overview.png) |
| [nvme-sentinel](https://github.com/lwrlock/nvme-sentinel) | `C`, `Python`, `GTK4` | Displays NVMe `hwmon` temperature, PCIe link speed/width, `default_ps_max_latency_us` (APST), and `/sys/block/nvme*` IOPS | [Screenshot](https://raw.githubusercontent.com/lwrlock/nvme-sentinel/main/docs/screenshots/overview.png) |
| [quant-wealth-terminal](https://github.com/lwrlock/quant-wealth-terminal) | `FastAPI`, `SQLite`, `JS` | Portfolio tracker, TEFAS fund data viewer, and simple strategy backtester | — |

### Stack
- **Languages:** C, Python, x86_64 Assembly, restricted C (eBPF)
- **Linux Interfaces:** `sysfs`, `procfs`, `hwmon`, `powercap`/RAPL, DRM/`accel`, PolicyKit, Wayland D-Bus
- **UI:** GTK 4, Libadwaita, Cairo
