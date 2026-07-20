# 📡 2.4GHz Meshtastic PCBs Compilation / Recopilatorio de PCBs 2.4GHz

## 🇪🇸 Descripción

Este repositorio es un recopilatorio de hardware y proyectos de PCBs diseñados específicamente para ejecutar **Meshtastic en la banda de 2.4GHz**.

El objetivo de este espacio es centralizar la documentación, esquemas, enlaces a repositorios y la compatibilidad con diferentes módulos de RF (especialmente la serie Ebyte E28 y E80) para guiar a la comunidad en la elección y fabricación de sus nodos.

### 📊 Características principales de la banda 2.4GHz en Meshtastic:
- **Mayor ancho de banda y menor latencia** para mensajes y telemetría rápidos.
- **Antenas integradas o externas muy pequeñas**, ideales para nodos tácticos, portátiles o discretos.
- **Compatibilidad internacional** sin restricciones severas de ciclo de trabajo (Duty Cycle) en la mayoría de regiones.

---

## 🇬🇧 Description

This repository is a curated compilation of PCB designs and hardware projects explicitly tailored for running **Meshtastic on the 2.4GHz band**.

The purpose of this repository is to centralize documentation, schematics, repository links, and RF module compatibility matrices (specifically for the Ebyte E28 and E80 series) to guide the community in choosing and building their own nodes.

### 📊 Key features of the 2.4GHz band in Meshtastic:
- **Higher bandwidth and lower latency** for fast messaging and telemetry.
- **Extremely compact integrated or external antennas**, ideal for tactical, portable, or stealth nodes.
- **Global compatibility** without severe duty-cycle limitations in most regions.

---

# 📊 Comparative Table / Tabla Comparativa

| Proyecto / Project | Desarrollador / Dev | Ebyte E28 | Ebyte E80 | MCU | Enlace / Link | Notas de Diseño / Design Notes |
| :--- | :--- | :---: | :---: | :---: | :--- | :--- |
| **Albatastic Node** | EA5JSQ | ✔️ | \* | nRF52840 | [GitHub](https://github.com/sqtactical/Albatastic_Node) | Nodo compacto de propósito general / Compact multipurprose PCB |
| **Albatastic Scout** | EA5JSQ | ✔️ | ✔️ | nRF52840 | [GitHub](https://github.com/sqtactical/Albatastic-Scout) | Nodo solar sencillo para despliegues rápidos / Quick deploy simple solar node |
| **FakeTec 2.4G** | EA5JSQ | ✔️ | ❌ | nRF52840 | [GitHub](https://github.com/sqtactical/FakeTec_2.4G) | La famosa Faketec, ahora en versión 2.4G / The famous Faketec, now in 2.4GHz |
| **Albatastic PRO** | EmilioAL-Git | ✔️ | ✔️ | nRF52840/Seeed nRF52 | [GitHub](https://github.com/EmilioAL-Git/PCB-Albatastic-PRO) | Placa multiopción con gran versatilidad / Great flexibility PCB with plenty of options for hardware |
| **xiaoWa** | gargomoma | ❌ | ✔️ | nRF52840| [GitHub](https://github.com/gargomoma/xiaoWa_pcb) | Ultra-compacta, ideal para nodos ocultos o tubos de 32mm / Ultra-compact, ideal for stealth nodes or 32mm tubes |

> **\*** *Depende de la versión / Depending on the version.*

---


## ➕ ¿Quieres añadir tu PCB? / Want to add your PCB?

### 🇪🇸 ¡Contribuye al recopilatorio!
Si has diseñado una PCB para Meshtastic en 2.4GHz, siéntete libre de añadirlo. 
Para hacerlo:
1. Abre un **Pull Request** o una **Issue**.
2. Incluye el enlace al repositorio, el nombre del desarrollador y una breve descripción.
3. Especifica la compatibilidad con los módulos **Ebyte E28** y **Ebyte E80**.

---

### 🇬🇧 Contribute to the compilation!
If you have designed a 2.4GHz Meshtastic PCB, feel free to add it.
To do so:
1. Open a **Pull Request** or an **Issue**.
2. Include the repository link, developer name, and a brief description.
3. Specify its compatibility with the **Ebyte E28** and **Ebyte E80** modules.
