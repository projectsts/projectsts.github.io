---
title: Open Ports
date: 2023-07-20 12:00:00 -500
categories: [,]
tags: [,,,Ports, PS, Code]

---

> There is a wisdom of the head, and a wisdom of the heart.
> — <cite>Charles Dickens</cite>

---

## Open Ports

	Get-NetTCPConnection -State Listen | Select-Object -Property LocalPort

```Powershell
Get-NetTCPConnection -State Listen | Select-Object -Property LocalPort
```