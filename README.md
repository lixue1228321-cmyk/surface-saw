 AstraSaw-iOS27

 This is a local vulnerability research project targeting iOS 27.0.1 (on iPhone 15 Pro Max / A17 Pro).
The primary objective is to explore the feasibility of escalating privileges from a standard sandboxed app to the kernel, while documenting which attack paths are no longer viable.

A complete Xcode project featuring a multi-stage attack chain (Stages 0–5), incorporating various techniques such as sandbox escape, kernel address leakage, IOSurface Use-After-Free (UAF), and IPC UAF.

Standard App (sandboxed)

↓

Stage 0: Environment Reconnaissance

↓

Stage 1: Sandbox Escape Attempt

↓

Stage 2: Kernel Address Leak Attempt (KASLR bypass)

↓

Stage 3: Race Condition Exploitation

↓

Stage 4: Kernel Read/Write Primitives (kread / kwrite)

​​   ↓

Stage 5: Post-Exploitation (Privilege Escalation, Persistence, etc.)
