# Yağız

Computer/Electronics engineering student. I work on embedded systems and the
low-level software that sits between hardware and the operating system.
I care more about *why* a system behaves the way it does than just getting it to run —
so I tend to build things from scratch instead of reaching for a framework.

Lately I've been drawn to the **operating-system side** of embedded: schedulers,
context switching, drivers, and how an RTOS or a Linux kernel actually works underneath.

---

## What I'm working on

- **CAN bus intrusion detection (graduation project)** — an STM32 test rig that
  generates both normal ECU traffic and attacks (flooding, spoofing, fuzzing,
  masquerade), feeding an FPGA-based detector. I own the traffic/attack generator
  and the ECU-workload side.

- **Bare-metal FreeRTOS from scratch** — brought up FreeRTOS on an STM32L476 by hand,
  no CubeIDE: wired the vector table, wrote the startup and linker layout, a
  register-level UART driver, and got the scheduler running on real silicon.

- **Embedded Linux & kernel drivers** — moving up the stack from microcontrollers to
  application processors. Learning Linux device drivers (character devices, SPI/I2C)
  on a BeagleBone. *(repos coming soon)*

---

## Technologies

- **Languages:** C, Python, a bit of Verilog
- **Low-level:** ARM Cortex-M, bare-metal register programming, FreeRTOS
- **Linux:** GNU/Linux, SocketCAN, device drivers *(learning)*
- **Tools:** Git, arm-none-eabi toolchain, st-link, GDB

---

## Interests

- How operating systems work from the inside — scheduling, memory, context switches
- The low-level side of in-vehicle networks and their security
- Building things from first principles to really understand them
- Debugging hard problems by narrowing them down, not guessing

---

## 📌 How I use GitHub

- My repos are learning- and exploration-driven, not polished products
- I keep the experiments and the failed attempts, not just the wins
- I try to write READMEs and commit messages that actually explain things
