# CupCarbon - Entrega 3

## Integrantes

- **Natalia Arandio**
- **Miguel Gomez**

## Descripción

Proyecto de **capa de comunicación de sensores para IoT** (Internet of Things). Consiste en una simulación de red de sensores inalámbricos que monitorean eventos (por ejemplo, alarma de incendio) y envían la información hacia una estación base mediante distintos protocolos de comunicación.

El trabajo se centra en la capa de comunicación: configuración de nodos sensores y nodo base, enrutamiento multi-salto hacia el sink, límite de transmisiones, manejo de batería y comparación de tecnologías (Zigbee, WiFi, LoRa).

## Software

Este proyecto está desarrollado para **[CupCarbon](http://www.cupcarbon.com)**, un simulador de redes de sensores inalámbricos (WSN) e IoT. Los nodos se programan en **SenScript** y la simulación permite evaluar consumo energético, cobertura y comportamiento de la red.

## Estructura del repositorio

- `scripts/` — Scripts SenScript del nodo base (`base.csc`) y de los nodos sensores (`nodoSensor.csc`).
- `natevents/` — Archivos de eventos naturales (.evt) para la simulación.
- `config/` — Configuración de nodos y parámetros de simulación.
- `results/` — Resultados y gráficas de las simulaciones.
