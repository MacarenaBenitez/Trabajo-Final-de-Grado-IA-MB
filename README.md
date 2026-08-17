<div align="justify">

<h2 align="center">FACULTAD DE CIENCIAS EXACTAS, FÍSICAS Y NATURALES</h2>
<h3 align="center">UNIVERSIDAD NACIONAL DE CÓRDOBA</h3>
<h3 align="center">Departamento de Agrimensura</h3>
<h3 align="center">Ingeniería en Agrimensura</h3>
<h3 align="center">Cátedra de TRABAJO FINAL</h3>

<h2 align="center">“Gemelo Digital para evaluar el impacto de la sequía meteorológica en el valor de la tierra rural”</h2>

<p align="center">
Autora: Macarena Benítez<br>
Profesores: Luis Antonio Bosch – Mario Andrés Piumetto – Santiago Masquijo
</p>

<h3 align="center">RESUMEN</h3>

El presente Trabajo Final tiene como propósito estudiar el uso de gemelos digitales para la administración del territorio, con un enfoque en el impacto de la sequía meteorológica en el valor de la tierra rural. Además, busca brindar información sobre la utilización de esta tecnología y su implementación efectiva. Esta tecnología, aunque ya empleada en diversas industrias, ha comenzado a ganar protagonismo en el ámbito técnico y académico, sin embargo, su comprensión sigue siendo limitada. Aún persisten dudas sobre su concepto, los métodos de aplicación, el uso de software especializado y los costos asociados. En el contexto de la administración del territorio, el uso de gemelos digitales se encuentra en una fase inicial lo que plantea la necesidad de más estudios y evaluaciones sobre su potencial y limitaciones.
Este trabajo analizará el impacto de la sequía meteorológica en el valor unitario de la tierra rural, y el rol del gemelo digital para modelar, predecir, simular y gestionar estas variaciones valorativas de manera eficiente. Para ello, se emplearán para el procesamiento y la experimentación, Google Colab como entorno computacional, utilizando Python para la limpieza, el modelado, simulación y predicción. Además, se explorará la interrelación entre los aspectos ambientales y tecnológicos con el campo de la administración territorial, destacando su importancia en la gestión y planificación del territorio.

**📑 ÍNDICE**

OBJETIVOS DEL TRABAJO ...................................................... 7  
Objetivo general ............................................................ 7  
Objetivos específicos ....................................................... 7  
Metodología ................................................................ 7  

---

**CAPÍTULO I: INTRODUCCIÓN** 

1.1 Administración del territorio ........................................... 9  
1.2 Modelo conceptual de la gestión de la tierra ............................ 10  
1.3 Administración del territorio en contextos de desastres naturales ...... 11  
1.4 Desafíos actuales en la administración del territorio .................. 12  
1.5 Implementación de tecnologías emergentes ............................... 15  
1.6 Los gemelos digitales como herramienta para la administración del territorio ............................................................ 15  
1.7 Caso de uso: gemelo digital para la gestión de desastres ............... 16  
1.8 Preguntas orientadoras ................................................. 18  

---

**CAPÍTULO II: HISTORIA, CONCEPTOS Y MODELOS DE GEMELOS DIGITALES** 

2.1 Historia y origen de los gemelos digitales ............................. 20  
2.2 Revisión del estado del arte ........................................... 23  
2.3 Diferenciación por propósitos y escalas ............................... 24  
2.4 Definiciones de gemelo digital ......................................... 27  
2.5 Clasificación de los gemelos digitales ................................ 30  
2.5.1 Gemelos digitales clásicos ........................................... 32  
2.5.2 Gemelos digitales avanzados .......................................... 32  
2.5.3 Gemelos digitales híbridos ........................................... 33  
2.5.4 Gemelos digitales sociales ........................................... 33  
2.5.6 Gemelo digital geoespacial .......................................... 34  
2.6 Valor temporal del gemelo digital ..................................... 36  
2.7 Niveles de desarrollo ................................................ 37  
2.8 Integración físico-virtual ............................................ 39  
2.9 Elementos del gemelo digital .......................................... 41  
2.10 Funciones ............................................................ 42  
2.11 Enfoques de modelado ................................................. 46  
2.12 Desafíos ............................................................. 47  
2.13 Evolución ............................................................ 48  

---

**CAPÍTULO III: TECNOLOGÍAS** 

3.1 Tecnologías tradicionales ............................................. 54  
3.1.1 Tecnologías geoespaciales ........................................... 57  
3.1.2 BIM y modelado 3D ................................................... 57  
3.1.3 Ciencia de datos .................................................... 58  
3.1.4 Inteligencia artificial ............................................. 59  
3.1.5 Realidad extendida .................................................. 59  
3.1.6 Metaversos .......................................................... 60  
3.1.7 Plataformas digitales ............................................... 61  
3.1.8 Software técnico .................................................... 61  
3.1.9 Modelado 3D ......................................................... 62  

3.2 Instrumentos .......................................................... 63  
3.2.2 Sensores LiDAR ...................................................... 66  
3.2.3 Equipos sin LiDAR ................................................... 67  
3.2.4 Escáner láser ....................................................... 69  
3.2.5 Mapeo móvil ......................................................... 71  

3.3 Marcos normativos ..................................................... 76  
3.4 Situación en Argentina ................................................ 77  

---

**CAPÍTULO IV: PROYECTOS** 

4.1 Acapulco .............................................................. 83  
4.2 Japón ................................................................. 89  
4.3 China ................................................................. 92  

---

**CAPÍTULO V: GEMELO DIGITAL** 

5.1 Descripción de la zona de estudio ..................................... 100  
5.2 Justificación ......................................................... 103  
5.3 Comprensión del fenómeno de la sequía ................................. 104  
5.3.1 Clasificación ....................................................... 105  
5.3.2 Eventos de sequía ................................................... 107  
5.3.3 Impacto en la producción ............................................ 108  

5.4 Proceso de creación .................................................. 110  

*Primera etapa*
5.4.1 Selección de herramientas ........................................... 111  
5.4.1.1 Librerías ......................................................... 114  
5.4.1.2 Datos CREAN ...................................................... 116  
5.4.1.3 Datos IDECOR ..................................................... 117  
5.4.1.4 Área de análisis .................................................. 119  
5.4.1.5 Intersección ..................................................... 124  

*Segunda etapa*
5.4.2 Preprocesamiento ................................................... 125  
5.4.2.1 Evolución del PDSI ............................................... 126  
5.4.2.2 Estación más seca ................................................ 126  
5.4.2.3 Indicador departamental .......................................... 128  
5.4.2.3.1 Promedio simple ................................................ 129  
5.4.2.3.2 Promedio ponderado ............................................. 130  
5.4.2.4 Resultados ....................................................... 133  
5.4.2.5 Normalización .................................................... 136  
5.4.2.6 Limpieza de datos ................................................ 138  
5.4.2.6.1 Valor de la tierra rural ........................................ 140  
5.4.2.6.2 Distribución espacial .......................................... 141  
5.4.2.6.3 Relación sequía-valor ........................................... 151  
5.4.2.6.4 Dataset final ................................................... 153  
5.4.2.7 Ingeniería de datos .............................................. 154  
5.4.4.7.1 Matriz de correlación ........................................... 154  
5.4.4.7.2 Correlación por pedanía ........................................ 156  

*Tercera etapa*
5.4.3 Modelo predictivo .................................................. 158  
5.4.3.1 Imputación ....................................................... 160  
5.4.3.2 Random Forest .................................................... 161  
5.4.3.3 XGBoost ......................................................... 165  
5.4.3.4 Comparación ...................................................... 168  

*Cuarta etapa*
5.4.4 Uso operativo ...................................................... 169  
5.4.4.1 Mapas interactivos ............................................... 172  
5.4.4.2 Nivel alcanzado ................................................. 176  

---

**CAPÍTULO VI: CONCLUSIÓN** ............................................... 178

Futuras investigaciones ................................................... 181  

**REFERENCIAS** .............................................................. 183

--- 

**OBJETIVOS DEL TRABAJO**

**Objetivo general**

Sistematizar el conocimiento existente sobre el uso de gemelos digitales en la administración del territorio con el fin de proponer recomendaciones que promuevan su implementación efectiva en el campo de aplicación.

**Objetivos específicos**

Identificar definiciones, usos, tecnologías y evolución de los gemelos digitales en el ámbito del territorio.
Analizar las aplicaciones prácticas y la capacidad de representación, simulación, predicción y optimización de los gemelos digitales en el ámbito territorial a partir del estudio de casos internacionales.
Desarrollar un prototipo de gemelo digital para analizar el impacto de la sequía en el valor de la tierra rural.
Elaborar recomendaciones para ampliar el uso de gemelos digitales en los desafíos de la gestión territorial, a partir del estudio bibliográfico y el prototipo desarrollado.

**Metodología**

La metodología adoptada en este estudio es mixta y de diseño exploratorio-descriptivo. En primer término, se realizó una revisión exhaustiva de la literatura que abarca estudios previos sobre los gemelos digitales como artículos académicos, libros, conferencias, entrevistas, proyectos relevantes que hayan utilizado esta tecnología en diferentes contextos, noticias, entrevistas y trabajos finales de otros países. De esta manera, se realizó un análisis documental y de contenido de fuentes secundarias para la elaboración del problema de estudio, estado del arte y marco teórico. En segunda instancia, se realizaron entrevistas dirigidas a profesionales de diferentes rubros, abarcando tanto el ámbito provincial como nacional. Estas entrevistas fueron individuales y semiestructuradas, constando de 10 preguntas del tipo abierto, de seguimiento y de clarificación.
Asimismo, se adoptó la técnica de la encuesta dirigida a estudiantes, profesionales vinculados a la administración del territorio como así también a profesionales de diferentes rubros de alcance provincial y nacional con el objetivo de revelar niveles de conocimiento, capacidades técnicas y limitaciones de los gemelos digitales para la administración del territorio. El cuestionario fue autoadministrado, con preguntas cerradas y abiertas, de carácter anónimo respaldando la confidencialidad de los resultados. Estos fueron procesados ​​con el sistema Power Bi Desktop que permite una visualización interactiva y la integración de datos. En algunas respuestas abiertas se aplicó Voyant Tools, que es una plataforma más avanzada de análisis de texto que admite múltiples archivos de texto de gran tamaño o largos bloques de contenido.
Finalmente, fue seleccionada la zona de estudio departamento Unión, específica donde se desarrolló un gemelo digital para la administración del territorio enfocado a un área específica de sequía meteorológica. El mismo fue elaborado a partir de Google Colab que es una herramienta gratuita de Google que permite programar y ejecutar código en la nube. Se realizaron simulaciones y predicciones para evaluar diferentes escenarios actuales y/o futuros. Los resultados obtenidos se sistematizaron para identificar y señalar las mejores prácticas para la gestión y planificación territorial.

El presente repositorio expone una **síntesis del Trabajo Final de Grado**, con el objetivo de mostrar el enfoque metodológico, las herramientas utilizadas y los principales resultados obtenidos en el desarrollo de un gemelo digital aplicado a la administración del territorio.


📩 El contenido teórico completo del trabajo no se incluye en este repositorio.  
Para su consulta, se solicita contactar a la autora .
MAIL: macarenabenitez2012@gmail.com 
