Nessus CSV Unifier

This Python script, called Nessus CSV Unifier, aims to consolidate multiple .CSV files generated by the Nessus vulnerability scanning tool into a single unified file.

Description: In the context of a pentesting process, it is common to generate multiple vulnerability reports in .CSV format using Nessus. Managing these multiple files can be tedious and error-prone, especially when you want to have a unified view of all vulnerabilities detected in different segments of the network or during different periods of time.

Nessus CSV Unifier automates this consolidation process, allowing security analysts to save time and reduce the risk of human error. The script performs the following actions:

 Reading CSV Files: Searches and reads all CSV files in the specified directory.
 Error Handling: Captures and logs any errors that occur while reading files.
 Data Consolidation: Combine data from all CSV files into a single DataFrame.
 Activity Log: Maintains a detailed log of the actions performed and errors found.
 Data Export: Saves the consolidated DataFrame into a new CSV file ready for analysis.

To use this script, follow these steps:

 Place all the CSV files you want to consolidate in the same directory as the script.

 Run the script in your Python environment.

Execution Example:

python csv_unifier.py

![imagen](https://github.com/user-attachments/assets/62781143-d240-4b6b-9292-7070b6299071)


Requirements:

 Python 3.x
 pandas library

Installing Pandas: You can install the pandas library using pip: pip install pandas

Script created by Arturo Correa 'P4nth4_R31'

========================================================================================================================================

Nessus CSV Unifier

Este script de Python, denominado Nessus CSV Unifier, tiene como objetivo consolidar múltiples archivos .CSV generados por la herramienta de análisis de vulnerabilidades Nessus en un solo archivo unificado.

Descripción: En el contexto de un proceso de pentesting, es común generar múltiples reportes de vulnerabilidades en formato .CSV utilizando Nessus. La gestión de estos múltiples archivos puede ser tediosa y propensa a errores, especialmente cuando se desea tener una vista unificada de todas las vulnerabilidades detectadas en diferentes segmentos de la red o durante diferentes periodos de tiempo.

Nessus CSV Unifier automatiza este proceso de consolidación, permitiendo a los analistas de seguridad ahorrar tiempo y reducir el riesgo de errores humanos. El script realiza las siguientes acciones:

    Lectura de Archivos CSV: Busca y lee todos los archivos CSV en el directorio especificado.
    Manejo de Errores: Captura y registra cualquier error que ocurra durante la lectura de los archivos.
    Consolidación de Datos: Combina los datos de todos los archivos CSV en un único DataFrame.
    Registro de Actividades: Mantiene un log detallado de las acciones realizadas y errores encontrados.
    Exportación de Datos: Guarda el DataFrame consolidado en un nuevo archivo CSV listo para su análisis.

Para utilizar este script, sigue estos pasos:

    Coloca todos los archivos CSV que deseas consolidar en el mismo directorio que el script.

    Ejecuta el script en tu entorno de Python.

Ejemplo de Ejecución: 

python csv_unifier.py

![imagen](https://github.com/user-attachments/assets/62781143-d240-4b6b-9292-7070b6299071)

Requisitos:

    Python 3.x
    Biblioteca pandas

Instalación de Pandas: Puedes instalar la biblioteca pandas utilizando pip: pip install pandas

Script created by Arturo Correa 'P4nth4_R31'
