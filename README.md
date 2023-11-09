# Simulación de Dopaje de Nitruro de Indio (InN) con Galio (Ga)

## Descripción

Este proyecto contiene un programa de simulación en Python que modela la distribución de Fermi-Dirac para nitruro de indio (InN) intrínseco y dopado con galio (Ga). El InN es un semiconductor del grupo III-V con una amplia gama de aplicaciones en dispositivos optoelectrónicos y electrónicos de potencia. La dopación con galio permite modificar las propiedades eléctricas del InN, transformándolo de un semiconductor tipo n a tipo p, lo cual es crucial para la fabricación de dispositivos semiconductores como diodos y transistores.

## Características del Programa

- Simula la ocupación de los estados de energía según la distribución de Fermi-Dirac.
- Compara gráficamente el InN intrínseco (sin dopar) y el dopado con Ga.
- Asume valores típicos para las masas efectivas de electrones y huecos en el InN.
- Utiliza una aproximación de los niveles de energía de ionización para el Ga en InN.

## Dependencias

Este programa está escrito en Python y requiere las siguientes bibliotecas:

- NumPy: para cálculos numéricos y manejo de arrays.
- Matplotlib: para la generación de gráficos.

## Instalación

Asegúrate de tener Python instalado en tu sistema. Puedes instalar las dependencias necesarias con pip:

```bash
pip install numpy matplotlib
