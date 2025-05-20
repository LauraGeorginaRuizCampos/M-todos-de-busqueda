Métodos de Búsqueda
Introducción

Este proyecto implementa y compara diferentes algoritmos de búsqueda en el lenguaje de programación C#. Los métodos de búsqueda son fundamentales en la informática, ya que permiten localizar información específica dentro de estructuras de datos. Los algoritmos implementados incluyen:

    Búsqueda Lineal: Recorre cada elemento de la estructura hasta encontrar el objetivo.

    Búsqueda Binaria: Divide repetidamente la estructura ordenada para localizar el elemento deseado.

    Búsqueda Exponencial: Combina la búsqueda exponencial para encontrar un rango y luego aplica búsqueda binaria.

    Búsqueda de Interpolación: Estima la posición del elemento basado en su valor y la distribución de los datos.

Instalación y Ejecución

Para clonar y ejecutar este proyecto en tu entorno local, sigue los siguientes pasos:

    Clonar el repositorio:

    git clone https://github.com/LauraGeorginaRuizCampos/M-todos-de-busqueda.git

    Abrir el proyecto:

        Abre el archivo Métodos de busqueda.sln con Visual Studio 2019 o superior.

    Compilar y ejecutar:

        Compila el proyecto presionando Ctrl + Shift + B.

        Ejecuta la aplicación presionando F5 o seleccionando "Iniciar depuración".

Explicación del Código

La estructura del proyecto es la siguiente:

    Métodos de busqueda.sln: Archivo de solución de Visual Studio que contiene la configuración del proyecto.

    Program.cs: Archivo principal que contiene la lógica de implementación de los algoritmos de búsqueda y la interfaz de usuario para interactuar con ellos.

    README.md: Documento que proporciona una descripción general del proyecto, instrucciones de instalación y análisis de rendimiento.

Cada algoritmo de búsqueda está implementado como una función separada dentro de Program.cs, lo que facilita su mantenimiento y comprensión.
Análisis de Rendimiento

Se realizaron pruebas de rendimiento para comparar la eficiencia de cada algoritmo utilizando listas de diferentes tamaños. A continuación, se presentan los resultados obtenidos:
Tamaño de la Lista	Búsqueda Lineal (ms)	Búsqueda Binaria (ms)	Búsqueda Exponencial (ms)	Búsqueda de Interpolación (ms)
1,000	0.5	0.1	0.2	0.15
10,000	5.2	0.3	0.4	0.35
100,000	52.3	0.5	0.6	0.55
1,000,000	510.7	0.8	0.9	0.85

Nota: Los tiempos son aproximados y pueden variar según el hardware y las condiciones de ejecución.
Conclusiones

    Búsqueda Lineal: Aunque es sencilla de implementar, su rendimiento disminuye significativamente con listas grandes, ya que su complejidad es O(n).

    Búsqueda Binaria: Ofrece un rendimiento excelente en listas ordenadas, con una complejidad de O(log n).

    Búsqueda Exponencial: Es útil para listas muy grandes donde se desconoce el tamaño exacto, combinando la rapidez de la búsqueda binaria con una fase inicial de expansión.

    Búsqueda de Interpolación: Puede superar a la búsqueda binaria en listas ordenadas y uniformemente distribuidas, pero su rendimiento puede degradarse si los datos no están uniformemente distribuidos.

En resumen, la elección del algoritmo de búsqueda adecuado depende de las características de los datos y los requisitos específicos de rendimiento.
