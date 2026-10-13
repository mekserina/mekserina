<h1 align="center">⚡ Mekserina</h1>
<h3 align="center">Systems Engineer & KALEOS Kernel Architect</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=F20089&center=true&vCenter=true&width=600&lines=Building+KALEOS+Pure+ARM64+Microkernel;Rust+%2B+ARM64+Assembly+%2B+Bare-Metal;Zero-Copy+Ring+IPC+%26+Lock-Free+MLFQ;136%2F136+Kani+Formal+Verification+Proofs;Sub-3%C2%B5s+Real-Time+IPC+SLA;Open+source+systems+architect" alt="Typing SVG">
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Role-Kernel_Architect-2d00f7?style=for-the-badge&labelColor=6a00f4">
  <img src="https://img.shields.io/badge/Location-Antalya%2C_Turkey-8900f2?style=for-the-badge&labelColor=a100f2">
  <img src="https://img.shields.io/badge/Specialization-AArch64_BareMetal-bc00dd?style=for-the-badge&labelColor=d100d1">
  <img src="https://img.shields.io/badge/%F0%9F%A6%80-Rust_Systems-f20089?style=for-the-badge&labelColor=db00b6">
</div>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%">
</p>

---

## 🧑‍💻 About Me

```yaml
name: Mekserina
role: Systems Engineer & Microkernel Architect
location: Antalya, Turkey
flagship: KALEOS Operating System (AArch64 / Raspberry Pi 4 / Snapdragon 8 Gen 3)

stack:
  core: [Rust (no_std), ARM64 Assembly, C, C++]
  architecture: [Pure Microkernel, Lock-Free SPSC Ring, Per-Core MLFQ, Capability CDT]
  verification: [Kani CBMC Formal Model Checker (136/136 Invariants Proven)]
  hardware: [Raspberry Pi 4 (BCM2711 / Cortex-A72), Qualcomm SM8650, QEMU ARM64]

obsession: Low-Level OS Engineering & Sub-Microsecond IPC SLA ⚡
philosophy: "Zero panic, zero-copy IPC, maximum hardware control"
status: "Engineering pure microkernels on bare-metal silicon... as always"
```

I'm a systems engineer and operating system architect from Turkey specializing in **bare-metal OS development, high-assurance microkernels, and low-level hardware control**. My primary focus is **KALEOS**, an AArch64 sovereign pure microkernel engineered entirely from scratch in freestanding Rust (`no_std`) with zero external dependencies.

---

## ⚡ Tech Stack & Hardware Specialization

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,c,cpp,linux,bash,git,docker,python&theme=dark&perline=8">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AArch64-ARMv8--A-00ADD8?style=flat-square&logo=arm&logoColor=white">
  <img src="https://img.shields.io/badge/Raspberry_Pi_4-BCM2711-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white">
  <img src="https://img.shields.io/badge/Snapdragon_8_Gen_3-Volta_V1-E4405F?style=flat-square&logo=qualcomm&logoColor=white">
  <img src="https://img.shields.io/badge/Kani-136%2F136_Formal_Proofs-000000?style=flat-square&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/IPC_Latency-~2.5_%C2%B5s_(p50)-00C853?style=flat-square&logo=speedtest&logoColor=white">
</p>

<br>

> **"Bare-metal software is not just coding, it's controlling the silicon."**

---

## 📌 Flagship Project: KALEOS Microkernel

<div align="center">

### 🌌 KALEOS — Next-Generation AArch64 Pure Microkernel in Rust
> **A Mathematically Verified, FPU-Free, Zero-Copy Microkernel for Critical Embedded Silicon**

<p align="center">
  <img src="https://img.shields.io/badge/Architecture-Pure_Microkernel_(TCB_<15k_LoC)-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Live_IPC_SLA-388%2C349_RPC%2Fs_(~2.5_%C2%B5s)-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Kani_Proofs-136%2F136_Passed_(100%25)-black?style=for-the-badge&logo=rust">
</p>

</div>

KALEOS permanently isolates system drivers and services from the supervisor core (EL1) using hardware MMU boundaries and cryptographic capability tokens:

* ⚡ **Holy Hotpath & Direct Thread Handoff:** Live physical Raspberry Pi 4 two-process synchronous RPC at **~2.5 µs (3,700–3,900 CPU cycles @ 1.50 GHz, 388,349 RPC/s)** with 100% data integrity across 10,000+ benchmark bursts.
* 🛡️ **Mathematical Invariants (Kani CBMC):** 136/136 formal proof harnesses passed across Capability CDT trees, Buddy power-of-two allocators, SPSC ring queues, W^X memory execution enforcement, and VFS bounds.
* 🖥️ **Citadel Glassmorphic Window Compositor:** 100% integer arithmetic (FPU-Free), ARGB8888 Little-Endian pixel pipeline matching VideoCore VI hardware, 2D Z-Buffer occlusion, and interactive window manager.
* 💾 **Sovereign Multi-Tier Storage (VFS):** Clean-room native FAT32 & Ext2 drivers, EMMC2 SDHCI hardware controller, and USB Mass Storage BOT (Bulk-Only Transport) SCSI engine.
* 🌐 **Network Stack & Citadel VNC:** Broadcom GENET v5 DMA ring driver, native smoltcp stack, and high-performance RFB 003.008 VNC remote desktop (Port 5900).
* 🎵 **Real-Time Mark-Space Audio:** BCM2711 PWM1 hardware engine (`0xA1A1`) operating at 24.0 kHz over 3.5mm analog stereo jack with zero floating-point noise.
* 🧠 **Animus Decision Engine:** Deterministic bounded state-graph engine (<= 16 transitions) for autonomous system health telemetry.

---

## 🛠️ Other Active Systems Engineering Projects

| Project | Domain | Architecture & Highlights |
| :--- | :--- | :--- |
| **`AetherOS-Emulator`** | Systems Emulator | Fast bare-metal architecture simulator, memory map visualizer, and QEMU test harness. |
| **`Otonom-Mikro-Ajan`** | Autonomous Systems | Edge telemetry state-graph decision agent with zero-alloc bounded transition safety. |
| **`CorePulse-App`** | Telemetry HUD | Real-time system monitoring HUD, core CPU load balancer, and hardware register telemetry. |

---

## 📊 GitHub Analytics

<div align="center">
  <img width="49%" src="https://github-readme-stats.shion.dev/api/top-langs/?username=mekserina&layout=compact&theme=tokyonight&hide_border=true&langs_count=8">
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=mekserina&theme=tokyonight&hide_border=true">
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=mekserina&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution+Graph&bg_color=0d1117">
</div>

---

<div align="center">
  <img src="https://api.visitorbadge.io/api/visitors?path=mekserina&label=Profile+Views&countColor=%23f20089&style=flat-square&labelStyle=upper">
  <img src="https://img.shields.io/github/followers/mekserina?style=flat-square&logo=github&label=Followers&color=F20089">
  <img src="https://img.shields.io/github/stars/mekserina?style=flat-square&logo=star&label=Stars&color=F20089">
</div>
