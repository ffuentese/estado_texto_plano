---
section: issue
title: Reinicio del proveedor
date: 2026-07-23T06:30:36.545Z
resolved: true
draft: false
informational: false
pin: true
resolvedWhen: 2026-07-23T07:30:36.573Z
affected:
  - servidor-principal
severity: disrupted
---
Admin:

Se reviso el evento y el sistema funciona sin problemas nuevamente. 

Vultr:

*A critical Linux KVM vulnerability affecting virtualized environments has been disclosed. To protect your workloads, our security team is applying patches across our infrastructure, which requires a one-time reboot of your virtual machine. Please note that this reboot must be conducted by our team. Rebooting yourself will not avoid our scheduled reboot.*

*Because of the severity, this window cannot be rescheduled, and affected VMs cannot be migrated to avoid the reboot.*

**Maintenance window**
Miami
Start: 2026-07-23 06:30:00 UTC
End: 2026-07-23 07:30:00 UTC

**What to expect**
Each VM will reboot once during this window. Actual interruption should be brief (~2–5 minutes) while the VM restarts — not the full hour.