---
layout: default
title: Timers
parent: Libraries
---

# Timers
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## BaseTimer

## Heartbeat
![Heartbeat](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/Heartbeat.jpg)
Sets an output bit TRUE and then FALSE in one period.

## Watchdog
![Watchdog](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/Watchdog.jpg)
Monitors a boolean input signal, if no state change is deteced in the preset time, output is set true. 

## TON
![TON](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TON.jpg)
Extension of the basic on delay timer with additional data - actively timing, remaining time. 

## TONRT
![TONRT](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TONRT.jpg)
Retentive on delay timer with reset

## TOF
![TOF](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TOF.jpg)
Extension of the basic off delay timer with additional data - actively timing, remaining time. 

## TOFRT
![TOFRT](https://github.com/TwinCAT-Libre/source/blob/master/TcL_Timers/imgs/TOFRT.jpg)
Retentive off delay timer with reset

