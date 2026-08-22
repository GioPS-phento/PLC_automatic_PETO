<h3>Objetivo</h3>
Diseñar un programa PLC para servir un vaso de PETO con adiciones seleccionadas.

<h3>Objetivos especificos</h3>
-Diseñar una fase de comprobación que verifique la existencia de materia prima 
-Diseñar una fase de preparación que verifique la temperatura del preparado y funcionamiento del calentador y motor mezclador
-Diseñar la fase para servir verificando tamaño de vaso seleccionado y adición seleccionada
-Configurar alarmas para errores de motor y del calentador

<h3>Lista de entradas y Salidas</h3>

<h4>Entradas</h4>
Tablero selector de tamaño T1 T2 
Input dinero D
Sensor nivel de tanque peto P1 P2
Sensor temperatura peto H1
Sensor de nivel tanque leche L1 L2
Sensor presencia de vaso V
Sensor de peso panela A
Sensor de nivel queso Q1 Q2
Sensor motor de mezcla principal M1
Sensor motor de panela M2
Sensor motor de queso M3
<h4>Salidas</h4>
Calentador K1
Motor vaso MV1
Motor mezclador M0
Compuerta peto Pp
Compuerta queso Pq
Compuerta Panela Pa


Fase de comprobación de sensores
<img width="917" height="835" alt="image" src="https://github.com/user-attachments/assets/9489ec43-f0e6-4b03-bca6-71851f9a1e9b" />

Fase de preparación
<img width="873" height="802" alt="image" src="https://github.com/user-attachments/assets/1af404af-85dd-4791-9e02-b3afc59a7e3e" />

Fase para servir

<img width="837" height="836" alt="image" src="https://github.com/user-attachments/assets/f0346f93-ca1f-484c-8664-1d04a6ed4af5" />


