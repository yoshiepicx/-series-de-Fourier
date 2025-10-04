# -series-de-Fourier
Señales con Transformada de Fourier  (TF)
Análisis de Señales con Transformada de Fourier
by Yoshua Solano UC 2025
Objetivo del proyecto
El objetivo de esta actividad es analizar señales en el dominio del tiempo y frecuencia utilizando MATLAB o Python. Aplicarás la Transformada de Fourier para visualizar cómo las señales se representan en ambos dominios y compararás los resultados obtenidos. Finalmente, compartirás tu código en un repositorio en línea (GitHub) y presentarán sus hallazgos en una sesión en línea con una presentación de apoyo.
Conceptos clave a aplicar:

Representación de señales en el dominio del tiempo.
Transformada de Fourier: definición y aplicación.
Propiedades de la transformada de Fourier.
Interpretación del espectro de frecuencia de una señal.
Para desarrollar la actividad sigue estos pasos:

1. Instalar las herramientas de desarrollo necesarias
MATLAB: Puede utilizarse su versión de escritorio o MATLAB Online.
Python: Usando librerías como NumPy, SciPy, y Matplotlib para manipulación y visualización de señales.
Crear una cuenta en GitHub y un repositorio para subir el código desarrollado.
2. Implementar la simulación en MATLAB o Python
Crear señales elementales como el pulso rectangular, la función escalón y la función senoidal.
Representar las señales de manera gráfica en MATLAB o Python.
Calcular la Transformada de Fourier de las señales generadas usando: 
fft() en MATLAB
np.fft.fft() en Python
Graficar la magnitud y fase del espectro de frecuencia de cada señal.
Verificar la propiedad de linealidad, desplazamiento en el tiempo y escalamiento en frecuencia.
Comparar cómo cambia la señal al analizarla en el dominio de la frecuencia.
3. Documentar el código y cxplicaciones
Es importante incluir comentarios explicativos en el código para que otros puedan entender el análisis realizado. Ejemplo de estructura recomendada: 
Definición de la señal en el dominio del tiempo
Cálculo de la Transformada de Fourier
Visualización de los resultados
Análisis de propiedades y transformaciones
4. Subir el código a GitHub
Crear un repositorio en GitHub.
Subir el código utilizando Git (git commit y git push).
Asegurarse de incluir un README.md explicando el propósito del código.
5.  Preparar una presentación para la sesión en línea
Herramientas sugeridas: PowerPoint, Canva o Sway de Microsoft.
6.  Presentar el proyecto en una sesión en línea
Compartir pantalla para mostrar el código y los gráficos obtenidos.
Explicar paso a paso la transformación de la señal y su espectro de frecuencia.
Analizar el efecto de las propiedades de la transformada de Fourier en las señales.
Responder preguntas de los compañeros o el profesor.
Señales simuladas
Se trabajó con tres señales elementales:

Pulso rectangular: Señal con valores constantes en un intervalo y cero en el resto. Es útil para analizar la dispersión espectral.
Función escalón (Heaviside): Señal que cambia de 0 a 1 en un punto determinado. Representa un cambio abrupto y es común en sistemas de control.
Señal senoidal: Señal periódica que representa una sola frecuencia pura. Es clave para comprender cómo se comportan señales armónicas.
Para cada señal se generó:

Su representación en el dominio del tiempo.
Su espectro de frecuencia: magnitud y fase, usando np.fft.fft().
Herramientas usadas
Python 3.8+
NumPy para manejo de vectores y FFT.
Matplotlib para graficar las señales y espectros.
Git y GitHub para control de versiones y publicación del proyecto.
Fourier-Signal-Analysis
