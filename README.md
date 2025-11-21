# Micro-CPU-2Bits
Micro-CPU 2Bits 
Autores Josué Alejandro Velásquez Tepé-000151607 Lindsay Mijhal Alvarez Gaitan-000147408

Objetivo del Proyecto El objetivo de este proyecto es construir un modelo funcional y simplificado de una Unidad Central de Procesamiento (CPU) utilizando la placa RP2040 Zero, simulando conceptos fundamentales de arquitectura computacional. El proyecto Micro-CPU 2Bits implementa: El Ciclo de Instrucción: Fetch → Decode → Execute → Write-Back, visualizado mediante una secuencia de LEDs. Las Banderas de Estado: Zero, Negative y Overflow. Una calculadora básica de 2 bits, capaz de realizar operaciones con números del 0 al 3.

Descripción General Este proyecto simula cómo funciona internamente una CPU real, mostrando de manera interactiva: Cómo se procesa una instrucción Cómo se detectan banderas en operaciones aritméticas Cómo funcionan los estados y el flujo de ejecución Cómo manejar un display de 7 segmentos y botones físicos Está desarrollado en MicroPython y pensado para ser utilizado en cursos de Arquitectura del Computador.

Instrucciones de Uso

Cargar el código en la RP2040 Zero Conectar la placa a la computadora mediante USB-C. Abrir Thonny IDE. Seleccionar el intérprete: RP2040 — MicroPython Abrir el archivo main.py. Guardarlo en la placa (Grabar en la RP2040). Ejecutar.

Operar la Calculadora 2-Bits Presiona un botón numérico (0, 1, 2 o 3). Luego presiona una operación: ➕ para sumar ➖ para restar Presiona el segundo número. Finalmente presiona = para mostrar el resultado. El display mostrará la salida. Los LEDs indicarán las banderas: Zero → El resultado es 0

Negative → El resultado es negativo

Overflow → Resultado fuera del rango permitido
