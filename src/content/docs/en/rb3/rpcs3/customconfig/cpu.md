---
title: "Custom Configuration: CPU"
slug: "en/rb3pc/customconfig/cpu"
description: "What to change for Rock Band 3 under the CPU tab in RPCS3's Custom Configuration."
tableOfContents: false
sidebar:
  hidden: true
---

![A screenshot of Rock Band 3's CPU custom settings, showing SPU Block Size, Preferred SPU Threads, and Thread Scheduler highlighted in blue with a dotted outline.](https://rb3pc.milohax.org/images/cust/cpu.png "CPU")

* ![A blue square with a dotted outline.](https://rb3pc.milohax.org/images/cust/smallblue.png "Tan Square") **Improved performance, depending on machine**: 
	* **Change "`SPU Block Size`" to "`Mega`"** - Ties smaller SPU compiled together, which can help machines with fewer cores/threads. Drastically speeds up game startup time on certain machines.
	* **Change "`Preferred SPU Threads`" to "`1`", "`2`", "`3`", or "`4`"** - May help prevent stutter caused by CPU overloads on systems with fewer cores/threads. **Start at "`4`" and lower it one by one until it improves**.
	* **Change "`Thread Scheduler`" to "`RPCS3 Scheduler`", or "`RPCS3 Alternative Scheduler`"** - **FOR CPUs WITH 12+ THREADS ONLY!** May help with thread distribution to prevent microstutters.

<br/>