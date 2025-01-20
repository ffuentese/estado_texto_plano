---
section: issue
title: Problemas con espacio en disco provocan caídas de sistema
date: 2025-01-20T13:01:30.287Z
resolved: true
draft: false
informational: false
pin: false
resolvedWhen: 2025-01-20T13:01:30.292Z
affected:
  - servidor-principal
severity: disrupted
---
*Investigando* - A raíz de caída temporal de SMTPD, notamos que el espacio usado en disco aumentó drásticamente poniendo en peligro el funcionamiento de todo el servidor por lo que estamos buscando la raíz del problema para restaurar usos razonables del medio de almacenamiento.

R﻿esuelto - Configuración nginx revela ataque masivo a subdominio dado de baja, generando log de error masivo.