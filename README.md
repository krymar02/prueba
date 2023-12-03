

# Laboratorio 7 - Python Scripting

**Universidad de Costa Rica  
Curso: Principios de Informática  
Código del Curso: IE-0117 Programación Bajo Plataformas Abiertas  
Profesora: Carolina Trejos  
Fecha: 3 de diciembre de 2023  
Estudiante: Kryssia Martínez, Carne: B84636**

## Descripción

Este laboratorio tiene como objetivo evaluar los conocimientos adquiridos en Python, convirtiendo el desarrollo previo en Bash scripting a Python scripting.

## Archivos

- `process_info.py`: Obtiene información relevante de un proceso.
- `process_monitor.py`: Automatiza el monitoreo de un proceso.
- `resource_monitor.py`: Monitorea el consumo de CPU y memoria de un proceso y grafica los resultados.

## Instrucciones de Instalación de Librerías

Instala las siguientes librerías antes de ejecutar los scripts:

```bash
pip install psutil matplotlib
psutil: Acceso a información sobre procesos y sistema.
matplotlib: Creación de gráficos y visualización de datos.
Ejecución y Resultados
Ejercicio 1: Obtener Información de un Proceso
bash
Copy code
python process_info.py 5072
Resultado:


Nombre del proceso: code
ID del proceso: 5072
Parent process ID: 83148
Usuario propietario: kryssia martinez0
Porcentaje de uso de CPU: 14.42%
Consumo de memoria: 219 MB
Estado: Running
Path del ejecutable: C:\Windows\visual studio code\process_info.py
Ejercicio 2: Monitorear un Proceso


python process_monitor.py firefox "Brave"
Resultado:


Process 'Brave' restarted.
Process 'Brave' restarted.
Process 'Brave' restarted.
...
Monitoring stopped.
Ejercicio 3: Monitorear Consumo de CPU y Memoria

python resource_monitor.py "C:\Program Files\BraveSoftware\Brave-Browser\Application\brave.exe"
Resultado:


Graficando resultados...
(Se muestra una gráfica con el tiempo y el uso de CPU y memoria)
Branches
main: Contiene el código principal.
ejercicio1: Branch para el desarrollo del Ejercicio 1.
ejercicio2: Branch para el desarrollo del Ejercicio 2.
ejercicio3: Branch para el desarrollo del Ejercicio 3.
Comandos Utilizados
Algunos comandos utilizados durante el desarrollo:

git checkout -b ejercicio1
git checkout -b ejercicio2
git checkout -b ejercicio3
git checkout main
git branch

