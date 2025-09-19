---
title: "Custom Configuration: Advanced"
slug: "en/rb3pc/customconfig/advanced"
description: "What to change for Rock Band 3 under the Advanced tab in RPCS3's Custom Configuration."
tableOfContents: false
sidebar:
  hidden: true
---

![A screenshot of Rock Band 3's Advanced custom settings, highlighting "Driver Wake-Up Delay" (20µ) in green with a dashed outline, "Exclusive Fullscreen Mode, and "Maximum Number of SPURS Threads" highlighted in blue with a dotted outline, and "Debug Console Mode" highlighted in tan with a solid outline.](https://rb3pc.milohax.org/images/cust/advanced.png "Advanced")

* ![A green square with a dashed outline.](https://rb3pc.milohax.org/images/cust/smallgreen.png "Green Square") **REQUIRED**: 
	* **Change "`Driver Wake-up Delay`" to "20µ"** to avoid crashing after a few songs. Increase it to "40µ" if the issue persists. If it keeps happening, keep increasing it by increments of 20.

* ![A blue square with a dotted outline.](https://rb3pc.milohax.org/images/cust/smallblue.png "Tan Square") **Depending on your computer**: 
	* **Change "`Maximum Number of SPURS Threads`"** - May improve performance on older systems with less cores and threads [[like 4th gen Intel i5 CPUs with 4 cores and 4 threads]](https://github.com/hmxmilohax/rb3-pc/issues/12#issue-1955946005).

* ![A tan square with a solid outline.](https://rb3pc.milohax.org/images/cust/smalltan.png "Tan Square") **Strongly Suggested**: 
	* **Enable "`Debug Console Mode`"** - Enabling this and "Large Heap" in Rock Band 3 Deluxe will allow Rock Band 3  to have more memory. This means more songs (up to 16000) and increased stability. Everyone should enable this! [[Click here for more information.]](https://rb3pc.milohax.org/memory)
	* **Change "`Exclusive Fullscreen Mode`" to "`Prefer borderless fullscreen`"** to prevent potential crashes and audio desync when changing from Rock Band 3 to another program while in fullscreen.

<br/>