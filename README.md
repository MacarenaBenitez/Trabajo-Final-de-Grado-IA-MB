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

## CAPÍTULO V: GEMELO DIGITAL PARA EVALUAR EL IMPACTO DE LA SEQUÍA EN EL VALOR UNITARIO DE TIERRA RURAL

## 5.1 Descripción de la zona de estudio: Departamento Unión, Córdoba

Unión es el cuarto departamento en la provincia de Córdoba en cuanto a su superficie con su ciudad cabecera en Bell Ville, una de las principales ciudades de la región. Este departamento está compuesto por cinco pedanías: Ascasubi, Ballesteros, Bell Ville, Litín y Loboy. El departamento limita con el norte con el departamento San Justo; al este, con el departamento Marcos Juárez; al sur, con el departamento Presidente Roque Sáenz Peña; al oeste, con los departamentos Juárez Celman y General San Martín; y al noroeste, con el departamento Río Segundo.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1-5hY030JC0Gp1d2sLnKoHrtxUdyoBTrZ" width="600">
</p>

<p align="center">
  <em>Figura 57: Ubicación de la zona de estudio. Fuente: Elaboración propia.</em>
</p>

A nivel organizativo, el departamento Unión está compuesto por 23 municipios y 4 comunas, lo que refleja su distribución administrativa y la diversidad de localidades que lo conforman.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1yZYuF-iHAZvhVkORdW96EXd8DDqangki" width="600">
</p>

<p align="center">
  <em>Figura 58: Demarcación, Hidrográfica y Red Vial. Fuente: Elaboración propia.</em>
</p>

En relación a la geografía, el departamento forma parte de la llanura pampeana y su sector norte tiene una red de drenaje no integrada, en forma de cañadas interrumpidas con dirección nordeste, que llevan sus aguas hacia la depresión de San Antonio (Arroyo Tortugas). El Río Tercero (Ctalamochita), es el más importante debido a su caudal y forma numerosos meandros y lagunas a lo largo de su curso. El Río Cuarto (Cochancaragua), tiene un nivel de base temporal en los Bañados del Saladillo.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1aIPZ04gCBUWxfjs-grj6zbDtK0NbBHdW" width="600">
</p>

<p align="center">
  <em>Figura 59: Red Hidrográfica y cuenca interprovincial. Fuente: Elaboración propia.</em>
</p>

## 5.2 Justificación del estudio en esta zona

La elección del Departamento Unión, Provincia de Córdoba, como zona de estudio para analizar el impacto de la sequía en el valor de la tierra rural se fundamenta en su elevada exposición a periodos prolongados de falta de lluvias, siendo una de las áreas más vulnerables de la provincia. Los registros meteorológicos evidencian una variabilidad climática significativa, con episodios que afectan la calidad del suelo y la rentabilidad de las actividades agropecuarias.
Asimismo, el Departamento Unión constituye un polo productivo relevante dentro del sector agrícola, destacándose por la producción extensiva de cultivos como soja, maíz y trigo los cuales dependen de las precipitaciones. Por este motivo, la escasez de agua tiene un impacto significativo en la región, no sólo en términos económicos sino también a través de procesos de degradación ambiental. Los periodos prolongados de falta de lluvias intensifican la erosión, reducen la cobertura vegetal y afectan a la biodiversidad, impactando tanto en la flora como la fauna silvestre. Del mismo modo, los cuerpos de agua temporales y permanentes sufren retracciones o desapariciones estacionales prolongadas, provocando un impacto significativo en los equilibrios ecológicos regionales.
Teniendo en cuenta las variables mencionadas, el presente estudio tiene por evaluar objeto el impacto histórico de las sequías en la valoración de la tierra rural del departamento elegido e indagar en la existencia de otras variables predecibles que posibilitan mitigar los efectos de este fenómeno.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1B3YEjUStzYh2Hkto6ygBfaByRpFhg6tc" width="600">
</p>

<p align="center">
  <em>Figura 60: La laguna La Brava, se quedó sin agua y perdió su flora y fauna. 22 de enero de 2023. Fuente: La Voz y La Posta Digital.</em>
</p>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1PGRDCtI6V5N0Z3CPe_Xku1QpFzNX5Fo1" width="600">
</p>

<p align="center">
  <em>Figura 61: Ubicación de La Laguna Brava, Dpto Unión, Pedanía Loboy. Fuente: Elaboración propia.</em>
</p>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1aXR7nYjBMRnmS7sRbJGhkWG1aDHPiVWS" width="600">
</p>

<p align="center">
  <em>Figura 62: Distribución anual de cuerpos de agua (2020–2024). Fuente: Elaboración propia a partir de imágenes Sentinel-2 en Google Earth Engine mediante scripts ejecutados en Google Colab.</em>
</p>

## 5.3 Sobre el estudio y la comprensión del fenómeno de la sequía 

El estudio de la sequía se ha abordado de diferentes formas y con diversas metodologías, dependiendo de quién la analiza y del objetivo de la investigación, así como de la conceptualización. En el contexto institucional, la Organización Meteorológica Mundial (1922, citado en Sistema de Información sobre Sequías para el Sur de Sudamérica, s.f.) define la sequía como “un período de tiempo con condiciones meteorológicas anormalmente secas, suficientemente prolongado como para que la falta de precipitación cause un grave desequilibrio hidrológico” (párr. 1).
 Por su parte, la Convención de las Naciones Unidas de Lucha contra la Desertificación (UNCCD, 1994)  la define como el “fenómeno que se produce naturalmente cuando las lluvias han sido considerablemente inferiores a los niveles normales registrados, causando un agudo desequilibrio hídrico que perjudica los sistemas productivos de la tierra” (art. 1, p. 1).
En cuanto a los factores causantes de la sequía, estos se asocian a fases extremas de la variabilidad climática en diferentes escalas temporales. Así, se ha establecido que en la escala interanual las anomalías climáticas provocadas por el ciclo La Niña frecuentemente generan condiciones de sequía en algunas regiones. Sin embargo, no todas las sequías que ocurren en una región están relacionadas con este ciclo ( UNCCD, 1994).

**5.3.1 Clasificación de las sequías**

En la actualidad, las sequías siguen representando un desafío significativo, especialmente en regiones donde el cambio climático ha intensificado su frecuencia y severidad. A diferencia de otros eventos extremos, el inicio de una sequía suele ser poco perceptible, pero sus efectos pueden volverse críticos a medida que la escasez de agua se prolonga en el tiempo.
Dada la magnitud de los impactos, resulta fundamental comprender la sequía como un proceso que involucra tanto factores meteorológicos como hidrológicos y socioeconómicos.  Bobba y Minetti (2010) proponen una clasificación universal de la sequía en cuatro categorías:
- Meteorológica: Se basa en datos climáticos y refleja la reducción de la precipitación respecto al valor promedio en un período determinado.
- Agrícola: Se produce cuando la humedad en el suelo es insuficiente para el desarrollo adecuado de los cultivos en cualquier fase de su crecimiento.
- Hidrológica: Se refiere a una deficiencia en el caudal o volumen de agua superficial o subterránea, afectando ríos, lagos y vertientes.
- Socioeconómica: Se manifiesta cuando la escasez de agua genera daños económicos o impactos negativos en la población de la zona afectada.

El presente estudio se centra en las sequías meteorológicas , dado que representan uno de los mayores desafíos ambientales y socioeconómicos en la administración del territorio, especialmente en regiones propensas a cambios climáticos significativos. Este fenómeno, caracterizado por un déficit prolongado de precipitaciones, afecta no solo la disponibilidad de agua, sino también tiene consecuencias en los ecosistemas, la producción agrícola, el desarrollo y la calidad de vida de la población.

**5.3.2 Eventos de sequía y respuesta normativa en la provincia de Córdoba (2020–2024)**

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1_VRMijJqN5523fEDsdV7qaRihKWEVQy-" width="600">
</p>

<p align="center">
  <em>Figura 63: Línea de tiempo que sintetiza la evolución de la sequía en la provincia de Córdoba durante el período 2020–2024. Fuente: Elaboración propia.</em>
</p>

La Figura 63: presenta una línea de tiempo que sintetiza la evolución de la sequía en la provincia de Córdoba durante el período 2020-2024, integrando los distintos tipos de sequía y la respuesta asociada institucional. En el año 2020 se identifican condiciones de sequía meteorológica, caracterizadas por un déficit de precipitaciones a escala provincial. Durante 2021 y 2022, la persistencia de la escasez de lluvias deriva en una sequía meteorológica e hidrológica, evidenciada por la disminución progresiva de las reservas hídricas destinadas al consumo, riego y actividades productivas.
El período 2022–2023 representa la fase más crítica, correspondiente a una sequía meteorológica prolongada, con impactos hidrológicos, agrícolas y económicos generalizados. Esta situación motivó la declaración del estado de emergencia agropecuario en la provincia de Córdoba mediante el Decreto Provincial N.º 136/2023, posteriormente homologado a nivel nacional por la Resolución 290/2023, habilitando beneficios fiscales y financieros en el marco de la Ley Nacional 26.509, tales como prórrogas y exenciones impositivas, suspensión de ejecuciones fiscales y acceso a mecanismos de asistencia crediticia y refinanciación de deudas para los productores afectados. Finalmente, en el año 2024 se observa un cambio de tendencia, con la finalización del evento La Niña 2020–2023 y una recuperación parcial de las precipitaciones, las reservas hídricas y los suelos, configurando una etapa post-sequía.
La normativa analizada no establece modificaciones directas sobre la valoración fiscal ni sobre el valor de la tierra rural. No obstante, al habilitar beneficios fiscales y financieros, introduce un marco institucional que puede incidir indirectamente en el comportamiento del mercado de tierras y en los procesos de cambio valuatorio asociados a eventos de sequía.

**5.3.3 Impacto de las sequías en la producción agropecuaria y el en el valor de la tierra rural**

Uno de los aspectos en los que se manifiesta el impacto económico de las sequías se manifiesta en el aumento de los costos operativos. En este sentido, la adquisición de insumos como el agua se vuelve más onerosa lo que afecta la competitividad de los productores y puede generar endeudamiento en el sector agropecuario. Además, la pérdida de vegetación y la erosión acelerada del suelo contribuyen a la desertificación, disminuyendo la capacidad productiva de las tierras y comprometiendo la sostenibilidad de las actividades agropecuarias a largo plazo.
Por su parte, las condiciones climáticas extremas pueden incidir en el valor unitario de la tierra rural, el cual se define como la evaluación técnica por unidad de superficie que refleja la capacidad productiva y el potencial territorial de cada parcela. Dado que este valor se determina a partir de ciertas características como la aptitud del suelo, la ubicación y las condiciones ambientales predominantes, los eventos de sequía pueden alterar indirectamente los factores que sustentan dicha valoración.
Así mismo, la percepción de riesgo frente a eventos climáticos recurrentes puede influir en la demanda de tierras rurales y en las expectativas de rentabilidad de los inversores. En este escenario, la necesidad de contar con herramientas capaces de integrar múltiples variables (ambientales, económicas y territoriales) se vuelve fundamental para anticipar posibles escenarios y reducir la exposición al riesgo.
En este marco es que se plantea la creación del Gemelo Digital para representar, analizar y proyectar de manera dinámica la relación entre sequías y valor unitario de la tierra rural.
En este contexto, el Gemelo Digital constituye una construcción de información virtual dinámica del territorio rural que replica la estructura espacial, el comportamiento climático y la respuesta productiva real del suelo ante eventos de sequía. De este modo se actualiza con datos observados (clima, datos catastrales y valuatorios), imita la evolución real de la sequía y su efecto sobre la productividad y el valor unitario de la tierra, y permite predecir posibles escenarios para orientar decisiones estratégicas de gestión territorial y valoración rural.

## 5.4 Proceso de creación del Gemelo Digital

En este apartado se describe el proceso metodológico adoptado para la construcción del gemelo digital aplicado al análisis del territorio rural. Dicho proceso se estructura de manera sistemática e integra la selección de la herramienta, la recolección de datos provenientes de múltiples fuentes, su preprocesamiento estadístico y espacial, la aplicación de modelos predictivos y la generación de visualizaciones a lo largo de las distintas etapas del flujo de trabajo.
A través de esta secuencia, se busca representar de forma dinámica la interacción entre variables climáticas, productivas y territoriales, posibilitando no solo la comprensión del comportamiento histórico del sistema, sino también la simulación de escenarios y el soporte en la toma de decisiones en contextos de sequía.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1g3kXT0rMcRFPDpQQzIlMtPfVGaYUCju0" width="600">
</p>

<p align="center">
  <em>Figura 64: Esquema de creación del Gemelo Digital. Fuente: Elaboración propia.</em>
</p>

## 5.4.1 Primera etapa: selección de la herramienta y recolección de datos

La creación del gemelo digital se apoya en el uso de herramientas de ciencia de datos, con el objetivo de garantizar la trazabilidad, la reproducibilidad y la flexibilidad en el análisis.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1_9PifWL_V__8qWaDoRidYhpYXl7Fe9Qr" width="600">
</p>

<p align="center">
  <em>Figura 65: Elección de tecnología. Fuente: Elaboración propia.</em>
</p>

En particular, se emplea Google Colab, un entorno de programación en la nube basado en Python, que posibilita la integración de diferentes fuentes de datos, la aplicación de algoritmos de aprendizaje automático, la automatización de procesos de preprocesamiento y modelado.
La elección de esta herramienta responde a su carácter abierto en términos de acceso y escalable, cualidades que resultan fundamentales para el desarrollo metodológico, aunque con una capacidad límite de RAM (~12 GB) que puede alcanzar para tareas medianas.
Para el análisis de la sequía, se emplean diversos indicadores, que son variables utilizadas para caracterizar las condiciones de sequía. Estos incluyen la precipitación, la temperatura, los caudales fluviales, los niveles de aguas subterráneas, la capacidad de los embalses, la humedad del suelo y el manto de nieve. A partir de estos indicadores, se desarrollan índices que representan numéricamente la magnitud de la sequía en base a datos climáticos e hidrometeorológicos. Sin embargo, no existe un índice único que pueda cuantificar de manera integral la intensidad y severidad de la sequía ni evaluar con precisión su impacto potencial.
Entre los índices más utilizados a nivel global se encuentran el Índice de Palmer (PDSI), el Índice de Precipitación Estandarizado (SPI) y el Índice de Precipitación-Evapotranspiración Estandarizado (SPEI), entre otros.
Para el presente estudio, se utilizaron datos del Índice de Sequía de Palmer (PDSI) proporcionados por el Centro de Relevamiento y Evaluación de Recursos Agrícolas y Naturales (CREAN), el cual realiza el monitoreo de sequías en la región. En este sentido, cabe aclarar que las diferencias metodológicas en las fuentes de datos pueden dar lugar a discrepancias en la evaluación de la sequía, ya que cada una se basa en distintas escalas temporales y espaciales, así como también en criterios específicos para el cálculo del índice.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=11_TIzRSCNL5Q_ru0W5QWRL0Zucs2ktQd" width="600">
</p>

<p align="center">
  <em>Figura 66: Registro histórico de sequía mediante el índice de Palmer – Estación Meteorológica Marcos Juárez. Fuente: Datos CREAN.</em>
</p>

La Figura 66 muestra que las sequías no son fenómenos instantáneos, sino prolongados en el tiempo. Pueden durar varios años y tener distintas intensidades. Un valor de PDSI más negativo implica mayor severidad en la sequía, lo cual afecta directamente la disponibilidad de agua para cultivos, ecosistemas y actividades humanas.
Debido a la disponibilidad de información sobre el valor de la tierra rural y del PDSI se seleccionó el período de tiempo comprendido entre los años 2020 y 2024 para realizar el análisis y la construcción del gemelo digital.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1s2vy40CQigSKp9Sy71dVzqD0toVhQfvw" width="600">
</p>

<p align="center">
  <em>Figura 67: Periodo comprendido. Fuente: Elaboración propia con datos de Mapas Córdoba.</em>
</p>

**5.4.1.1 Dependencias y librerías**

Las dependencias y librerías en Google Colab son componentes que permiten ampliar las capacidades básicas de Python y ejecutar análisis avanzados sin necesidad de instalar software en la computadora del usuario. Las dependencias son los requisitos adicionales que estas librerías necesitan para funcionar correctamente. Muchas veces una librería no funciona sola, sino que depende de otras librerías más pequeñas, de compiladores, de controladores o de extensiones del sistema. Por ejemplo: Earthengine-api requiere autenticación y paquetes auxiliares para conectarse con Google Earth Engine.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Z3v1pHa4GxgM2Wo5xANdS9RmUaHpYBSM" width="600">
</p>

<p align="center">
  <em>Figura 68: Instalación de dependencias. Fuente: Elaboración propia.</em>
</p>

Una librería es un conjunto de funciones, clases y módulos ya desarrollados que resuelven tareas específicas, como procesamiento de datos, visualización de gráficos, manejo de imágenes satelitales, conexión a servicios web o ejecución de modelos de aprendizaje automático.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1Z3v1pHa4GxgM2Wo5xANdS9RmUaHpYBSM" width="600">
</p>

<p align="center">
  <em>Figura 69: Instalación de librerías. Fuente: Elaboración propia.</em>
</p>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1EW0OSfdTOkX7EJehydyqc3izcZqdzsED" width="600">
</p>

<p align="center">
  <em>Figura 70: descripción. Fuente: Elaboración propia.</em>
</p>

**5.4.1.2 Datos del CREAN**

Se creó una cuenta en GitHub y se alojó el conjunto de datos proporcionados por el CREAN en formato CSV dentro de un repositorio para su resguardo y control de versiones.
A partir de ese repositorio, el archivo se integró al entorno de Google Colab mediante su URL lo que permitió después importar directamente los datos provistos para garantizar su trazabilidad y reproducibilidad en el análisis. En la visualización inicial se obtuvo una tabla con registros correspondientes a las Estaciones Meteorológicas de Marcos Juárez y Laboulaye, que constituyen la base de información climática para este estudio dentro del periodo 2020-2024.

**URL RAW de archivos en GitHub**

url_laboulaye = "https://raw.githubusercontent.com/MacarenaBenitez/TESIS/main/Labulaye%20Aero%2087534.csv"
url_marcos="https://raw.githubusercontent.com/MacarenaBenitez/TESIS/main/Marcos%20Juarez%20Aero%2087467.csv"

**5.4.1.3 Datos de IDECOR**  

En este trabajo, se utilizó la API de IDECOR para vincular y acceder a la información del Departamento Unión, integrando como capas principales departamento, pedanías, parcelas rurales, los radios urbanos, el valor de la tierra rural, red vial, e hidrología.
Esta conexión posibilitó la obtención de datos actualizados en formato interoperable, condición fundamental para su posterior preprocesamiento y análisis. La API brinda acceso a un total de 455 capas disponibles, de las cuales en este estudio se seleccionarán únicamente aquellas consideradas más relevantes para los objetivos planteados.
Una vez construida la API en Python para la conexión con los servicios geoespaciales, y verificadas correctamente las capas disponibles mediante su visualización preliminar, se procedió a la descarga individual de cada una de ellas. En primer lugar, se obtuvo la capa correspondiente al Departamento Unión utilizando el servicio WFS, lo que permitió acceder a su geometría y atributos asociados en formato vectorial. Esta descarga constituyó la base territorial sobre la cual se integraron posteriormente las otras capas temáticas requeridas (pedanías,parcelas, radios urbanas, red vial e hidrología).
Luego procedió a la construcción de una representación de la zona de estudio. Para ello, se combinaron las geometrías del departamento Unión con las pedanías que lo conforman, asignando a cada una un estilo visual que facilite su identificación. La visualización resultante permitió delimitar espacialmente el área de análisis.
Además, se elaboró ​​una representación que integra la red vial, la hidrología y los radios urbanos del departamento Unión, empleando como base un mapa satelital para contextualizar visualmente la distribución espacial de estas infraestructuras. En esta visualización se combinaron las capas de red vial nacional, provincial y regional, junto con los cursos de agua, acueductos y cuerpos de agua naturales, permitiendo identificar la estructura territorial y la conectividad interna del departamento. La incorporación de las radios urbanas en conjunto con estas capas facilitó el entendimiento del vínculo entre las áreas pobladas y las redes de infraestructura.

**Mapa que integra la red vial, la hidrología y los radios urbanos del departamento Unión**

👉 https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/red%20vial.html

**5.4.1.4 Caracterización del área de análisis**

Cada pedanía que integra el departamento Unión presenta particularidades en cuanto a su infraestructura, la disponibilidad de recursos hídricos y la organización territorial. Estas diferencias permiten reconocer la heterogeneidad interna del departamento, la cual aporta elementos para interpretar cómo las condiciones ambientales y los factores de infraestructura inciden en el desarrollo socioeconómico y en la gestión del territorio.
A partir de las capas vectoriales descargadas, se construyó una tabla de síntesis de infraestructura e hidrografía por pedanía para el Departamento Unión. En primer lugar, todas las capas involucradas (pedanías, cuerpos de agua, cursos de agua, radios urbanos, acueductos y red vial nacional, provincial y regional) fueron reproyectadas a un sistema de referencia común (EPSG:5346), con el fin de garantizar la consistencia espacial de los análisis. Luego, se normalizaron los nombres de las pedanías y se filtraron aquellas correspondientes al departamento de interés (Ascasubi, Ballesteros, Bell Ville, Litín y Loboy). Sobre esta base, se aplican uniones espaciales entre cada capa temática y la capa de pedanías, utilizando la relación de intersección para asignar a cada elemento de infraestructura o hidrografía la pedanía en la que se encuentra. Posteriormente, se realizaron agregaciones por pedanía mediante operaciones de conteo, obteniendo el número de cuerpos de agua, cursos de agua, radios urbanos, acueductos y segmentos de red vial nacional, provincial y regional presentes en cada una. Finalmente estos conteos se integraron en una única tabla resumen, completando los valores faltantes con cero y destacando en cada columna los valores máximos, lo que permitió identificar de manera comparativa las pedanías con mayor concentración de elementos de infraestructura e hidrografía dentro del Departamento Unión.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1oP6ksqvhOWjHuScT-OjJKWsB4bOuUklB" width="600">
</p>

<p align="center">
  <em>Figura 71: descripción. Fuente: Elaboración propia.</em>
</p>

La Figura 71: muestra la distribución de infraestructura e hidrografía en las pedanías del departamento Unión. En cuanto a cuerpos de agua naturales, Ascasubi se destaca con la mayor cantidad registrada (133), seguida por Loboy con 76, mientras que Ballesteros, Litin y Bell Ville presentan valores más bajos. Respecto a los cursos de agua, Ballesteros presenta 7, mientras que Bell Ville registra 6, superando ambas a las demás pedanías, las cuales se mantienen en valores cercanos a 4. En radios urbanos, Bell Ville y Ascasubi lideran con 7, en tanto que Loboy alcanza 6, Litín y Ballesteros 5. En relación con la infraestructura de acueductos, Ascasubi sobresale con 9, mientras que Loboy cuenta con 8 y Litín con 4, evidenciando una mayor cobertura en el sur del departamento. La red vial nacional se concentra en Bell Ville con 232 tramos, siendo la pedanía más conectada en términos de rutas de jerarquía nacional. La red vial provincial muestra su máxima extensión en Ascasubi con 989 registros, seguida de Bell Ville con 760 y Litín con 693, lo que refleja una fuerte presencia de rutas provinciales en estas pedanías. Por último, en red vial regional, tanto Litín como Ascasubi alcanzan el valor máximo con 4, indicando un desarrollo equilibrado en este tipo de infraestructura.
En conjunto, los datos permiten identificar a Ascasubi y Bell Ville como los principales nodos de concentración de infraestructura y recursos hídricos en el departamento Unión, mientras que Loboy se destaca por su número de acueductos.

**Mapa de infraestructura e hidrografía**

👉 [Ver mapa interactivo](https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/mapa_maximos_pedanias.html)

## 5.4.2. Segunda etapa: pre procesamiento de datos

El procedimiento incluyó limpieza de datos (detección y tratamiento de valores atípicos, ausentes o inconsistentes), así como comparaciones y análisis exploratorios que permitieron identificar relaciones entre variables y posibles redundancias. Asimismo, se realizaron elecciones metodológicas en torno a la transformación de variables y a la definición de los conjuntos de datos más adecuados para el modelado posterior.

En este trabajo se exploraron dos alternativas para asignar la influencia espacial de las estaciones meteorológicas de Laboulaye y Marcos Juárez sobre el territorio del Departamento Unión. La primera consistió en la asignación directa por pedanía, en la cual a cada unidad administrativa se le asoció la estación más cercana a su centroide. Este enfoque, aunque más simplificado en términos geométricos, resulta más coherente con la escala de análisis, ya que los valores de la tierra rural están disponibles y se gestionan a nivel de pedanía. La segunda alternativa fue la construcción de polígonos de Voronoi recortados al límite departamental, lo que permitió delimitar zonas contiguas según la proximidad geométrica a cada estación. Por este motivo, en el desarrollo se adopta la asignación por pedanía como método principal, manteniendo el enfoque Voronoi como referencia exploratoria que permite validar la consistencia espacial de los resultados. De esta manera, se asegura que el indicador departamental de sequía refleje tanto la dimensión climática como la lógica territorial utilizada en la valuación de tierras.

**5.4.2.4 Resultado del análisis**

**Mapa de PDSI**

👉 [Ver mapa interactivo](https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/mapa_pdsi_union.html)

El mapa presenta la evolución temporal del Índice de Severidad de Sequía de Palmer (PDSI) en el Departamento Unión para el período 2020–2024, utilizando la asignación por pedanía como método principal de referencia climática. En este enfoque, cada pedanía hereda el valor del PDSI de la estación meteorológica más cercana, lo que asegura la coherencia con la escala administrativa. Los resultados muestran una dinámica temporal marcada: en 2020 y 2021 predominan condiciones cercanas a la normalidad, con leves déficits en algunos sectores y episodios aislados de humedad. En 2022 y, especialmente, 2023, se observa un agravamiento de la sequía en prácticamente todo el departamento, alcanzando valores negativos más intensos y generalizados. Finalmente, en 2024 se registra un cambio de tendencia, con la recuperación de condiciones húmedas en la mayor parte del territorio, aunque persisten déficits puntuales en el sur.
Posteriormente, se procedió a la exploración de los datos de IDECOR, analizando en particular el contenido de las columnas de las capas correspondientes al departamento, parcela y  radios urbanos con el fin de caracterizar su estructura y preparar la información.
Al analizar la estructura de los datos de valor de tierra rural del Departamento Unión entre 2020 y 2024, se observa una evolución hacia una mayor completitud y estandarización: en 2020 y 2021 los campos de valor están denominados como vur_2020 y vur_2021, respectivamente, lo cual requiere tratamiento específico para su homogeneización.
A partir de 2022 se unifica el campo de valor en vur_pesos y se incorpora el valor en dólares (vur_dolar), agregando una nueva dimensión de análisis económico. Desde 2020, los datos contienen metadatos adicionales como código, nombre y etiqueta, lo que permite vincular espacialmente los valores con unidades territoriales específicas.
Esta variabilidad inicial en la estructura de atributos justifica la aplicación de un proceso de normalización, que permite unificar criterios y preparar los datos para el análisis temporal y espacial comparativo.

**5.4.2.5  A. Normalización**

Aunque el campo vur_pesos (valor unitario rural)  aparece formalmente a partir de 2022, los datos de valor monetario en pesos están disponibles desde 2020 bajo diferentes nombres. Por lo tanto, mediante un proceso de normalización de campos, es posible integrar los datos de 2020 a 2024 de forma homogénea para el análisis multitemporal en moneda local.
Se realizó un resumen estadístico descriptivo del valor de tierra de todas las parcelas del Departamento Unión, con el fin de analizar la evolución de los valores de la tierra en el período 2020–2024. 
Para cada año se calcularon medidas de tendencia central (media y mediana) y de dispersión (mínimo y máximo), junto con el número total de registros disponibles (N = 44.378).
Los resultados muestran una marcada variabilidad temporal: en 2020 la media del valor de la tierra era de aproximadamente $710.117, mientras que en 2024 ascendió a $9.723.645. Asimismo, el valor máximo pasó de $10.675.000 en 2020 a $148.800.000 en 2024. La mediana también refleja este crecimiento, al aumentar de $740.000 en 2020 a $9.920.000 en 2024.

**5.4.2.6  B. Limpieza de Datos**

La limpieza de datos es una etapa fundamental dentro del preprocesamiento, cuyo objetivo principal es detectar, corregir o eliminar errores, inconsistencias y valores no válidos presentes en los conjuntos de datos. Este procedimiento incluye tareas como la identificación de valores faltantes, la corrección de registros duplicados, el tratamiento de outliers, la unificación de formatos y la verificación de la coherencia interna de las variables.
En el caso particular de la base de datos de IDECOR,  se identificó que los registros con valores 1 suelen indicar anomalías y no reflejan un precio real de mercado. Al filtrarlos y mapearlos, se observa que muchos caen dentro de cuerpos de agua como lagunas, bañados o zonas anegadas. Esto se debe a que corresponden a parcelas sin uso productivo directo, que no se transaccionan en el mercado como tierra agrícola, por lo que se les asigna  un valor igual a 1. La identificación de estas parcelas permite depurar las series históricas y evitar sesgos en el cálculo de medianas, cuartiles o modelos predictivos. Si no se eliminan para el cálculo, tienden a aplanar la distribución hacia valores bajos y a aumentar artificialmente la heterogeneidad en el análisis de los valores de la tierra.
Para esto, se implementó un flujo de trabajo para conectarse a la API WFS de IDECOR, descargar las capas del Departamento Unión como parcelas y radios urbanos y luego filtrarlas espacialmente. A partir de esas capas se normalizaron y unificaron los datos de valor de tierra rural para los años 2020–2024. El objetivo fue identificar y aislar las parcelas rurales con valor igual a 1, excluyendo las áreas urbanas, y generar un dataset depurado en formatos interoperables (GeoJSON y GPKG). Finalmente, se construyó un mapa interactivo con buscador por número de cuenta o nomenclatura, lo que facilita la consulta y análisis del territorio de forma dinámica.

**Mapa de valores 1**

👉 [Ver mapa interactivo](https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/mapa_parcelas_valor1%20(2)%20(1).html)

Como parte del proceso de depuración de datos, se aplicó un filtro a los registros con valor_pesos ≤ 100 en el período 2020–2024 con el fin de depurar valores atípicos o inconsistentes que no representen el comportamiento real del mercado de tierras rurales. Este umbral permite concentrar el análisis en las parcelas con valores más razonables, garantizando una base de datos más confiable para evaluar la evolución del valor de la tierra y su relación con la sequía en el Departamento Unión.
El conjunto de datos contaba inicialmente con 221.890 registros. Tras aplicar el filtro, se conservaron 219.374 registros válidos, eliminando 2.516 registros con valor_pesos ≤ 100 por considerarse atípicos o no representativos.

**5.4.2.6.2 Distribución espacial del valor medio de la tierra rural** 

Se tomaron las parcelas del Departamento Unión con sus valores unitarios rurales y se calcularon únicamente los valores conservados (mayores o iguales a 100). Luego se detectó, para cada año y cada pedanía, qué parcelas tenían valores típicos y cuáles eran atípicas aplicando estadística de 1.5 veces el rango intercuartílico. Con esa clasificación se generó un punto por parcela usando el centroide de cada polígono y se lo proyectó al sistema geográfico. Finalmente se realizó un mapa por año mostrando la distribución espacial donde los puntos de color  azul representan valores normales y los rojos destacan las parcelas con valores fuera del rango esperado, permitiendo visualizar cómo se distribuyen en el territorio los valores extremos y los patrones anuales de variación del mercado rural.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=17kzyh1lCQ6nnrAqi0qALEugdf_FB9TBe" width="600">
</p>

<p align="center">
  <em>Figura 72: Gráfico de distribución del valor de tierra rural por año del Departamento. Fuente: Elaboración propia.</em>
</p>

Las Figura 72: muestra la distribución espacial del valor unitario rural en el Departamento Unión mantiene un patrón territorial relativamente estable, donde la mayor parte de las parcelas presentan valores típicos dentro de cada año y pedanía, mientras que los valores atípicos se concentran siempre en zonas muy específicas. Los outliers se ubican preferentemente en la franja central-oriental y en el sector suroeste del departamento. La persistencia de focos de valores atípicos a lo largo de los distintos años evidencia que no se trata de fluctuaciones aleatorias, sino de patrones estructurales asociados al territorio. Si bien el número total de outliers presenta variaciones menores entre períodos, su ubicación general y la tendencia a agruparse en clústeres espaciales se mantiene de manera consistente. 
Para profundizar este análisis, se generó y descargó un mapa en formato HTML que permite visualizar con precisión la distribución geográfica de estos casos y explorar su comportamiento espacial dentro del Departamento Unión.

**Mapa de outliers**  

👉 https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/mapa_outliers_union_satellite%20(1)%20(1).html  

Desde una perspectiva inicial, la capa analizada (valor_tierra_rural) se interpreta como representativa del valor de la tierra rural. Sin embargo, al tratarse de una grilla que cubre de manera continua todo el espacio territorial, esta incluye sectores con diferentes usos del suelo. En el mapa generado, cada polígono resaltado en color rojo corresponde a una celda de la grilla identificada como valor atípico (outlier) para su respectivo año, lo que permite visualizar su distribución espacial. Además, se observa que algunos de estos valores se localizan en áreas urbanas o periurbanas, a pesar de que la capa de origen se encuentra definida como correspondiente al valor rural.
A partir de esta primera visualización, se realizó una depuración espacial para conservar únicamente los valores rurales. Primero se definieron los parámetros y se  normalizaron textos para evitar problemas con nombres. Luego se trajo la capa de radios urbanos, asegurando que su sistema de referencia sea el correcto y reparando geometrías. Posteriormente, se tomó el dataset de valores conservados, se lo convirtió en un GeoDataFrame válido y se lo proyectó al mismo sistema de coordenadas. A través de una intersección espacial, se identificaron todas las grillas cuyos polígonos se superponían con áreas urbanas, eliminándose del dataset original, a partir de sus identificadores, aquellas ubicadas dentro de radios urbanos. 
Del total inicial de 219.374 registros, se identificaron 5.085 valores  ubicados dentro de radios urbanos, los cuales fueron excluidos del análisis. Como resultado, el conjunto de datos final quedó conformado por 214.289 parcelas correspondientes exclusivamente a suelo rural. Posteriormente, se generó una tabla y un nuevo gráfico de dispersión para visualizar el modo en que se distribuyeron los valores rurales a lo largo de los años y para evaluar nuevamente la presencia, magnitud y estabilidad de los valores atípicos dentro del conjunto depurado.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=19taa3bdczx73w-wmpZ1EVGEoxmIQCIXn" width="600">
</p>

<p align="center">
  <em>Figura 73: Tabla de distribución después de la depuración.. Fuente: Elaboración propia.</em>
</p>

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1cHDgd4YIshW25wkxwp66L0bV_wVsyjYh" width="600">
</p>

<p align="center">
  <em>Figura 74: Gráfico de distribución del valor de tierra rural por año del Departamento. Fuente: Elaboración propia.</em>
</p>

La distribución presenta una dispersión en todos los años analizados, con aumentos progresivos en los niveles generales de valuación hacia 2024. Los valores atípicos se mantienen presentes en cada período y tienden a ubicarse tanto por encima como por debajo del rango intercuartílico. Para verificar la distribución correcta de los datos atípicos se generó y descargó el un mapa HTML.

**Mapa de verificación de la  distribución de los datos atípicos**

👉 [Ver mapa interactivo](https://macarenabenitez.github.io/Trabajo-Final-de-Grado-IA-MB/mapa_outliers_rurales_union_satellite%201%20(1)%20(1).html)

Posteriormente, se implementó un procedimiento específico debido a que la grilla no posee una pedanía asignada de origen, dado que constituye una malla regular y no un conjunto de polígonos administrativos. 
Para resolver esta ausencia de referencia territorial, primero se aplicó el método de asignación por intersección del centroide, que consiste en ubicar el centro geométrico de cada celda y determinar dentro de qué pedanía se encuentra. Este enfoque resulta el más adecuado para unidades regulares y garantiza una asignación directa y consistente. No obstante, algunas celdas permanecieron sin asignar debido a su localización en bordes, solapes mínimos o situaciones en las que el centroide no intersecta ningún polígono. 
Para asegurar la clasificación completa de la grilla, se incorporó un método complementario de asignación por distancia mínima, que vincula cada celda con la pedanía cuyo polígono se encuentra más próximo. De este modo, la pedanía asignada se integra al GeoDataFrame principal, verificando posteriormente que todas las filas cuenten con una asignación válida.
Para analizar la distribución espacial de los valores rurales, por pedanía en el Departamento Unión a lo largo del período 2020–2024 se construyó un mapa comparativo a partir del dataset final realizado previamente. 

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1mHAUW5JAgjeKNwyLbfQzqCM9zay80p6V" width="600">
</p>

<p align="center">
  <em>Figura 75: Gráfico de distribución del valor de tierra rural por año del Departamento. Fuente: Elaboración propia.</em>
</p>

La Figura 75 constituye la expresión gráfica directa del proceso de construcción del dataset final, evidenciando que los datos han sido limpiados, correctamente georreferenciados y vinculados a su pedanía correspondiente. 
Durante este proceso, se partió el conjunto de datos final y se aseguró que el valor de la tierra estuviera definido como variable numérica. Luego, para cada combinación de año y pedanía, se calcularon dos cuantiles del valor de la tierra, que corresponden  aproximadamente a los tercios inferior y superior de la distribución. A partir de estos umbrales, cada parcela fue clasificada en una categoría relativa de valor —mínimo, medio o máximo— según su posición dentro de la distribución anual de su pedanía. De este modo, la categorización reflejó la posición relativa de cada parcela dentro de su contexto territorial y temporal, reduciendo sesgos espaciales y permitiendo análisis comparables en el tiempo.

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1dlMqNhoKn4g_kp6RXpgoNaIAmsb9MnPj" width="600">
</p>

<p align="center">
  <em>Figura 76: Distribución espacial de los valores máximos, mínimos y medio del Departamento Unión para el período 2020–2024. Fuente: Elaboración propia.</em>
</p>

En la comparación temporal se observa que la clasificación relativa de los valores de la tierra rural mantiene patrones espaciales persistentes dentro del Departamento Unión, pero con variaciones interanuales en la intensidad y extensión de cada categoría. Entre 2020 y 2024 se aprecian cambios en la proporción y distribución de las categorías, especialmente en el pasaje entre años, indicando que ciertas áreas migran de valores medios a máximos o mínimos según el contexto anual. 
Para complementar este análisis, se realizó un mapa con mayor nivel de detalle para analizar la variabilidad espacial intra-pedanía de los valores unitarios rurales, permitiendo observar cómo se distribuyen las categorías de valor mínimo, medio y máximo a escala de parcela y año. Este nivel de desagregación posibilita identificar patrones locales, zonas de concentración de valores extremos y cambios sutiles. 

**5.4.2.6.3  Relación sequía, valor de tierra e índice de productividad**

Para determinar la relación entre la sequía, el valor de la tierra y el índice de productividad se integró y depuró la información territorial, productiva y climática con el objetivo de construir un conjunto de datos consistente. En primer lugar, se realizaron copias de los datos originales y se normalizaron los nombres de las pedanías y los tipos de las variables temporales, con el fin de asegurar coherencia en los procesos de unión. Posteriormente, se estandarizaron los identificadores parcelarios y se incorporó el Índice de Productividad del suelo, priorizando la vinculación mediante el número de cuenta y utilizando la nomenclatura catastral como alternativa cuando resultó necesario.
A continuación, se integró la información climática a través del índice de sequía de Palmer (PDSI), asignando a cada parcela el valor correspondiente según el año y la pedanía. Finalmente, se depuró el conjunto de datos mediante la eliminación de registros incompletos, obteniéndose un dataset integrado y consistente, preparado para análisis posteriores sin aplicar procesos de entrenamiento o modelado.

**5.4.2.7  C. Ingeniería de Datos** 

El objetivo de la etapa de ingeniería de datos dentro del desarrollo del gemelo digital consiste en estructurar y transformar el conjunto de datos depurado con el fin de identificar las variables explicativas que presentan mayor asociación con la variable objetivo (el valor unitario rural) y preparar la información para su posterior modelización predictiva. 
Con este propósito, se realizó un análisis de correlación entre el valor unitario rural y las variables consideradas, a fin de evaluar la intensidad y dirección de las relaciones estadísticas y orientar la selección de variables para el modelo predictivo. 

**5.4.4.7.1 Matriz de correlación de variables**

La matriz de correlación cuantifica la relación lineal entre las variables del dataset y permite interpretar la magnitud y el sentido de cada asociación. La intensidad del color indica la fuerza de la relación lineal. Los valores cercanos a 1 tienen una correlación positiva fuerte, los valores cercanos a –1 poseen una correlación negativa fuerte y los valores cercanos a 0 tienen correlación débil o inexistente. 

<p align="center">
  <img src="https://drive.google.com/thumbnail?id=16A9LHCYEP-SO6A8BN3DC5Ywtwiywy26l&sz=w1000" width="600">
</p>

<p align="center">
  <em>Figura 77: Matriz de correlacion. Fuente: Elaboración propia.</em>
</p>

La matriz de correlación muestra que el valor unitario rural en pesos presenta una correlación positiva fuerte con el año, lo que indica una tendencia creciente del valor de la tierra a lo largo del período analizado. La relación entre el valor de la tierra y el índice de productividad del suelo es positiva pero débil, lo que sugiere que, a escala global del conjunto de datos, la productividad edáfica explica solo una parte limitada de la variabilidad del valor rural. En cuanto a la sequía meteorológica, medida mediante el PDSI, se observa una correlación positiva baja con el valor de la tierra, indicando que las condiciones de sequía presentan una influencia moderada cuando se analizan de manera agregada. Asimismo, los dos indicadores de productividad del suelo muestran una correlación prácticamente perfecta entre sí, lo que confirma que representan información equivalente, y que la elección del criterio de agregación no introduce diferencias significativas en la estructura de correlación del conjunto de datos. 
Por su parte, el PDSI exhibe una relación negativa leve con el año, lo que sugiere una posible tendencia hacia condiciones relativamente más secas en los años recientes del período estudiado. 

## 🔎 Alcance del contenido presentado

El presente repositorio expone una **síntesis del Trabajo Final de Grado**, con el objetivo de mostrar el enfoque metodológico, las herramientas utilizadas y los principales resultados obtenidos en el desarrollo de un gemelo digital aplicado a la administración del territorio.

En particular, el contenido aquí publicado abarca hasta la etapa de **análisis exploratorio de datos**, incluyendo la construcción del dataset integrado y el estudio de relaciones entre variables mediante herramientas como la `matriz de correlación`.

A partir de este punto, el trabajo continúa con etapas más avanzadas...

No obstante, dichas instancias se incluyen en este repositorio en su totalidad lo practico en tf_mb_2025_p1(1).py y tf_mb_2025_p2(3).py. 

📩 El contenido teórico completo del trabajo no se incluye en este repositorio.  
Para su consulta, se solicita contactar a la autora .
MAIL: macarenabenitez2012@gmail.com 
