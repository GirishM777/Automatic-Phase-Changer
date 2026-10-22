# Automatic Phase Changer

A microcontroller-based system that monitors a 3-phase AC supply and automatically switches the load to a healthy phase during under-voltage, over-voltage or phase failure. It keeps single-phase loads running without manual switching.

> Diploma in Electrical Engineering project, TKIET (Polytechnic), Warananagar (MSBTE), Academic Year 2022-23

---

## Problem

In many places, 3-phase supply is unstable. When one phase fails or its voltage drops, the phase is changed manually. This interrupts the supply and can damage appliances and sensitive equipment.

## Solution

The Automatic Phase Changer senses the voltage of the R, Y and B phases continuously. If the phase feeding the load goes outside the safe range, relays switch the load to a phase with normal voltage. No operator is needed.

## How It Works

1. A step-down transformer, rectifier and filter capacitor bring each phase voltage down to a measurable level.
2. The ADC0808 converts each phase voltage into digital data.
3. The AT89S52
