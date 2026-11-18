<div align="center">
  <h1>Furkan (<code>@lwrlock</code>)</h1>
  <p><b>18 y/o Computer Engineering Student &bull; Linux Kernel, eBPF, x86_64 Assembly &amp; AI Systems Developer</b></p>
  <p>Building bare-metal low-overhead Linux telemetry, hardware power/thermal optimization, eBPF tracers, and GTK4 desktop suites.</p>
</div>

---

### Flagship Showcase — FF Linux Kernel & Hardware Suite

<p align="center">
  <a href="https://github.com/lwrlock/ff-power-manager">
    <img src="https://raw.githubusercontent.com/lwrlock/ff-power-manager/main/docs/screenshots/showcase.gif" alt="FF Power Manager Cosmic Bento UI" width="880"/>
  </a>
</p>

| Repository | Stack | Core Purpose | Live Preview |
| :--- | :--- | :--- | :---: |
| [**`ff-power-manager`**](https://github.com/lwrlock/ff-power-manager) | `C` · `x86_64 ASM` · `GTK4` | Universal laptop power suite, per-process `~W` blame & Freeze, USB-C PD, dGPU zombie watch, Multi-DE 120Hz ARR, `s2idle` guard | [Pages](https://lwrlock.github.io/ff-power-manager/) |
| [**`ebpf-latency-guard`**](https://github.com/lwrlock/ebpf-latency-guard) | `eBPF CO-RE` · `C` · `GTK4` | Micro-stutter & scheduling latency detective (`sched_wakeup`/`sched_switch`, PSI, `schedstat`, IRQ storms) | [Preview](https://raw.githubusercontent.com/lwrlock/ebpf-latency-guard/main/docs/screenshots/overview.png) |
| [**`vram-atlas`**](https://github.com/lwrlock/vram-atlas) | `C` · `Intel Xe / NPU` · `GTK4` | Unified Intel Xe iGPU, Intel NPU (`intel_vpu`), UMA RAM & local LLM `Tokens/Watt` matrix | [Preview](https://raw.githubusercontent.com/lwrlock/vram-atlas/main/docs/screenshots/overview.png) |
| [**`waylens-privacy`**](https://github.com/lwrlock/waylens-privacy) | `C` · `HID ToF` · `GTK4` | Zero-Trust IR ToF perimeter radar, Anti-BadUSB HID guard, `ssh-add -D` vault & SHA-256 audit chain | [Preview](https://raw.githubusercontent.com/lwrlock/waylens-privacy/main/docs/screenshots/overview.png) |
| [**`mempulse`**](https://github.com/lwrlock/mempulse) | `C` · `MGLRU` · `GTK4` | Linux MGLRU (`lru_gen`), Memory PSI & `zstd` ZRAM headroom analytics HUD | [Preview](https://raw.githubusercontent.com/lwrlock/mempulse/main/docs/screenshots/overview.png) |
| [**`netpulse-bpf`**](https://github.com/lwrlock/netpulse-bpf) | `eBPF sock_ops` · `C` · `GTK4` | TCP BBR / `fq` congestion analyzer, SNMP retransmits & per-PID socket profiler | [Preview](https://raw.githubusercontent.com/lwrlock/netpulse-bpf/main/docs/screenshots/overview.png) |
| [**`nvme-sentinel`**](https://github.com/lwrlock/nvme-sentinel) | `C` · `PCIe Gen4 APST` · `GTK4` | NVMe controller thermal, PS4 sleep latency & live block queue IOPS monitor | [Preview](https://raw.githubusercontent.com/lwrlock/nvme-sentinel/main/docs/screenshots/overview.png) |
| [**`quant-wealth-terminal`**](https://github.com/lwrlock/quant-wealth-terminal) | `FastAPI` · `SQLite` · `JS` | Full-stack personal wealth, TEFAS fund analytics & walk-forward backtesting terminal | — |

---

### Core Technical Stack
- **Systems & Kernel:** `C` · `x86_64 Assembly` · `eBPF (clang -target bpf)` · `Linux sysfs / procfs / hwmon / RAPL / DRM / Accel`
- **Desktop & Graphics:** `GTK 4` · `Libadwaita` · `Cairo` · `Wayland D-Bus` · `Mutter IdleMonitor` · `GNOME Shell Extensions`
- **Security & Packaging:** `PolicyKit` · `AppStream` · `Debian (.deb)` · `Fedora (.rpm)` · `SHA-256 Audit Chains`
