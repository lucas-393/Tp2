# 🤖 Electrónica Digital II - Grupo 09

![MCU](https://img.shields.io/badge/MCU-PIC16F887-orange) ![Language](https://img.shields.io/badge/Language-Assembly-blue) ![IDE](https://img.shields.io/badge/IDE-MPLAB_X-red)

Este es el repositorio del grupo 09, Comisión a cargo del profesor Blasco. Aquí se encuentra el código fuente y las simulaciones correspondientes al **Trabajo Práctico N° 2: Contador binario y juego de luces LED** de la materia **Electrónica Digital II**. El foco principal es la programación de bajo nivel utilizando el microcontrolador **PIC16F887** en lenguaje **Ensamblador (Assembly)**.

## 🛠️ Herramientas Utilizadas

Para compilar y simular los proyectos de este repositorio, se recomienda el uso de:

*   **IDE:** [MPLAB X IDE](https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide)
*   **Compilador:** MPASM 
*   **Simulador:** Proteus Design Suite (para validación de circuitos y flujo de programa)
*   **Hardware:** Microcontrolador PIC16F887, oscilador de cristal de 4MHz, LEDs y resistencias.

## 📁 Estructura del Repositorio

El repositorio está organizado de la siguiente manera para este Trabajo Práctico:

```text
├── Tp2-JuegoDeLuces/         # Directorio principal del TP2
│   ├── Tp2.X/                # Proyecto de MPLAB X
│   │   └──Tp2_Codigo.X.hex   # Código fuente en Assembly (Contador + Efecto)
│   └── simu_tp2.pdsprj       # Archivo de simulación de Proteus
└── docs/                     # Documentación general, esquemáticos o informes extras
