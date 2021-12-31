# interruptor

The [future] home for Interruptor, a human-friendly interrupts hook library based on Frida's Stalker

Interruptor is the interrupts/systemcall hooking system from Dexcalibur.

## Requirements

* frida
* frida-compile

## Supported architectures / call conventions

* ARM (32 & 64bits) : SVC, HVC, SMC

## Supported syscalls API 

* Linux kernel API

## Documentation

There are mainly two way to hook interrupts depending of yours needs.

### A. Agent Tracer

When you want to use only a Frida agent script (and not host script).

*Limitation:*

Cannot follow children/multiples processes.

### B. Remote Trace

When you need to follow children processes, or external processes.
It works even if there is not link between traces processes.



