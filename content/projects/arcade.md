---
title: "Integrated Arcade System"
date: 2024-12-31T00:00:00+00:00
draft: false
slug: arcade
description: "The Integrated Arcade System is a dual-microcontroller system for the popular \"Connect 4\" and \"Whack-a-Mole\" games."
summary: "The Integrated Arcade System is a dual-microcontroller system for the popular \"Connect 4\" and \"Whack-a-Mole\" games."
featured: true
tags:
  - C
  - C++
  - UART/SPI
  - AVR
categories:
  - projects
# cover: "images/01.avif"
# link: ""
status: "completed"
---

{{< button text="View GitHub (\"Connect 4\" Game)" url="https://github.com/michaeltin001/EE120B_FinalProject" icon="github" target="_blank" />}}{{< button text="View Documentation (\"Connect 4\" Game)" url="/connect-4.pdf" icon="external-link" target="_blank" />}}
{{< button text="View GitHub (\"Whack-a-Mole\" Game)" url="https://github.com/michaeltin001/EE128_FinalProject" icon="github" target="_blank" />}}{{< button text="View Documentation (\"Whack-a-Mole\" Game)" url="/whack-a-mole.pdf" icon="external-link" target="_blank" />}}

**The Integrated Arcade System is a dual-microcontroller system for the popular "Connect 4" and "Whack-a-Mole" games.**

It utilizes the ATmega328P and FRDM-K64F microcontrollers, synchronizing logic via UART/SPI to drive score displays, sound effects, and background music. I developed low-level drivers for an ST7735 TFT display, 74HC595 shift registers, and ULN2003 stepper motors, optimizing ISRs to handle asynchronous player inputs while managing game states with physical feedback.

{{< youtube SnLw6SEYBBg >}}
{{< embed-pdf url="/connect-4.pdf" >}}

{{< youtube 3Lc4pzt0jEU >}}
{{< embed-pdf url="/whack-a-mole.pdf" >}}
