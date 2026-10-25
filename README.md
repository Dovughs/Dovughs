![Doruk | Systems and security research](assets/profile-header.svg)

I develop low-level systems software and specialize in Windows internals,
kernel development and endpoint security research. I work across C, C++ and x64
assembly, with a focus on execution flow, architectural state and the mechanisms
behind kernel instrumentation and detection.

My work combines hands-on implementation with ongoing analysis of Windows
internals and processor architecture. I also investigate emerging EDR architectures
and develop new evasion and bypass techniques.

### Technical focus

| Area | Focus |
| --- | --- |
| **Windows internals** | Native system-call paths, kernel callback mechanisms, exception and interrupt delivery, kernel memory management, and CET shadow-stack semantics |
| **Systems programming** | Kernel-mode C/C++, x64 assembly, ABI and calling-convention details, concurrent state management, synchronization, and resource lifetime across execution boundaries |
| **Virtualization** | Intel VT-x, VMCS guest/host state, per-CPU EPT, instruction replay and MTF, event reinjection, translation invalidation, and native return |
| **EDR research & evasion** | Indirect syscalls, advanced call stack spoofing, kernel callback unlinking, ETW-TI unregistration, and analysis of endpoint instrumentation |

### Featured project

**[Velum-VMM](https://github.com/Dovughs/velum-vmm)**

A Windows x64 research hypervisor with EPT entry hooks, live kernel telemetry,
scoped request policies and an interactive console. Its C runtime and x64
assembly layer handle per-CPU VMX state, CET transfer and native shutdown.

[Source code](https://github.com/Dovughs/velum-vmm) | [Technical write-up](https://github.com/Dovughs/velum-vmm/blob/main/readmes/technical-writeup/README.md) | [Release](https://github.com/Dovughs/velum-vmm/releases/latest)

### Beyond systems

I also study advanced mathematics and history. I enjoy working through
mathematical ideas in depth and understanding historical events through their
sources and wider context.
