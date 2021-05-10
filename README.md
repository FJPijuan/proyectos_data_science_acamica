# proyectos_data_science_acamica
Este es un repositorio en el que se encuentran los proyectos realizados durante el curso de ciencias de datos en acamica.

---
---
---

## Proyecto 1 - Primer modelo de Machine Learning

Este proyecto te desafía a seleccionar una problemática entre un conjunto de opciones, indagar qué datos podrían ayudarte a abordarla, realizar un análisis exploratorio y entrenar un modelo sencillo de Machine Learning para resolverla. ¡Esperamos que puedas llevar adelante un primer ?ujo de trabajo tal como lo hacemos los/as Cientí?cos/as de Datos!


### Resumen del proyecto

Este proyecto te desafía a seleccionar una problemática entre un conjunto de opciones, indagar qué datos podrían ayudarte a abordarla, realizar un análisis exploratorio y entrenar un modelo sencillo de Machine Learning para resolverla. ¡Esperamos que puedas llevar adelante un primer flujo de trabajo tal como lo hacemos los/as Data Scientists!

La realización y entrega del Proyecto es individual.

### Entregable

Un Notebook de Jupyter con la resolución de la consigna. El Notebook debe poder ejecutarse sin errores.

### Referencias

Para realizar el proyecto debes usar como referencia el contenido de las bitácoras, de los notebooks trabajados y las presentaciones vistas en clase. También te será de mucha utilidad consultar la documentación de las librerías de Python que trabajamos en clase, consultar comunidades online como Stack Overflow y, por supuesto, buscar en la web (googlear).

### Recursos

Utiliza los siguientes recursos para realizar el proyecto:

    Dataset Properati (DSProyecto01DatosProperati.csv)

### Consigna

#### PARTE 1 - Pensando como un/a Data Scientist

En esta sección, te planteamos una problemática y deberás responder la siguiente pregunta:

¿Qué datos crees que te ayudarían a trabajar en el problema? ¿Por qué?

Importante: NO deberás buscar esos datos, solamente justificar qué información crees que te ayudaría a resolver la problemática planteada.

#### PARTE 2 - Análisis Exploratorio de Datos

En esta sección, te proveeremos de un Dataset relacionado con la problemática planteada para que realices un Análisis Exploratorio de Datos. Deberás responder las preguntas típicamente asociadas a este análisis para obtener una primera descripción del Dataset.

#### PARTE 3 - Primer Modelo de Machine Learning

Una vez explorado el dataset, deberás utilizar herramientas de Machine Learning para predecir la variable de interés. Para ello, tendrás que:

    1. Elegir la métrica que utilizarás para evaluar las predicciones.
    2. Generar tres modelos: un modelo Benchmark, un modelo basado en Vecino más Cercanos (Modelo 1) y otro basado en Árboles de Decisión (Modelo 2). Cada uno de estos modelos deberá ser correctamente entrenado y evaluado siguiendo un flujo de trabajo típico de Machine Learning (train/test split).
    3. Optimizar el desempeño de los Modelos 1 y 2 optimizando el número de vecinos y la profundidad del árbol, respectivamente.
    4. Comparar la performance de los Modelos 1 y 2 frente al modelo Benchmark y entre sí para decidir cuál modelo tiene mejor desempeño.

### Checklist de evaluación

Sugerencias para desarrollar el proyecto:

    * Debes resolver los mínimos entregables indicados en la consigna, pero te invitamos a que siempre profundices más.
    * La resolución del proyecto te puede enfrentar a pequeños desafíos que no trabajamos durante los encuentros. Es importante que desarrolles la capacidad de resolverlos. Para ello, consulta las bitácoras, las referencias, los notebooks vistos en clase, la documentación de la librería y, sobre todo, googlea.
    * Recuerda que un notebook es un informe, por lo que debes ir explicando lo que haces a medida que resuelves las consignas. Es importante que quien que lo lea entienda el flujo de trabajo, qué quisiste hacer. Recuerda, simple y conciso es una combinación ganadora.

Antes de subir tu proyecto a la plataforma Acámica para que sea evaluado, verifica que el Notebook se ejecute sin errores. Además, asegúrate de cumplir con las siguientes condiciones (son las que los/as evaluadores/as tendrán en consideración al momento de corregir tu trabajo).

#### PARTE 1 - Pensando como un/a Data Scientist

    Debes justificar por qué creés que los datos que elegiste ayudan a resolver la problemática planteada.

#### PARTE 2 - Análisis Exploratorio de Datos

    1. Debes responder las preguntas típicas de un Análisis Exploratorio de Datos.
    2. Debes utilizar histogramas para representar la distribución de variables numéricas, gráficos de barras para variables categóricas y diagramas de dispersión para visualizar la relación entre dos variables numéricas. Si no exploras alguna variable (columna), deberás justificar por qué.
    3. Los gráficos deben estar correctamente presentados, con título y etiquetas en cada eje. Cada gráfico debe ir acompañado de una breve descripción. Si existen valores atípicos que distorsionan la visualización de un gráfico, el límite de cada eje debe estar ajustado para que esto no suceda o el dataset debe ser filtrado.

#### PARTE 3 - Primer Modelo de Machine Learning

    1. La elección de la métrica de evaluación debe estar correctamente justificada.
    2. Debes elegir correctamente las variables predictoras y la variable a predecir.
    3. Realiza un train/test split de los datos.
    4. El modelo benchmark debe estar justificado y evaluado de forma similar a los modelos generados.
    5. Debes justificar cuál modelo elegirías para utilizar.
    6. Debes ser crítico/a con la metodología utilizada. ¿Qué mejorarías?
	
---
---
---

## Proyecto 2 - Ingeniería de features, Modelos avanzados e Interpretación de modelos

Aplica ingeniería de Features y Modelos Avanzados para desarrollar con mayor profundidad tu modelo de Machine Learning. ¿Qué puedes aprender del problema que estás abordando mediante el estudio de tu propio modelo?

### Resumen del proyecto

Aplica transformación de datos y entrena Modelos Avanzados para desarrollar con mayor profundidad tu modelo de Machine Learning. ¿Qué puedes aprender del problema que estás abordando mediante el estudio de tu propio modelo?

### Entregable

Un Notebook de Jupyter con la resolución de la consigna. El Notebook debe poder ejecutarse sin errores.

### Referencias

Apóyate en las bitácoras, los notebooks trabajados y las presentaciones vistas en clase para resolver tu proyecto. También será de mucha utilidad la documentación de las librerías de Python. No dudes en consultar comunidades online como Stack Overflow y, por supuesto, buscar en la web (googlear).

### Recursos

Para realizar el proyecto:

    * Utiliza el siguiente dataset (es el mismo que en el Proyecto 01): Dataset Properati (DSProyecto01DatosProperati.csv)
    * Retoma el notebook desarrollado para el Proyecto 01 y considera la devolución que recibiste de tu evaluador/a.

### Consigna

En este proyecto profundizarás lo desarrollado en el proyecto 01 (“Primer modelo de Machine Learning”). El objetivo es aplicar las técnicas incorporadas (Transformación de Datos, Optimización de Hiperparámetros, Modelos Avanzados, etc.) para generar un modelo que tenga un mejor desempeño que el modelo generado en el proyecto anterior. Luego, interpreta ese modelo para responder la siguiente pregunta: ¿qué podemos aprender de nuestro problema estudiando el modelo que generamos?

El trabajo se organiza en tres partes:

#### PARTE A - Transformación de Datos

Elige cuáles de las siguientes tareas son apropiadas para su dataset. Implementa las transformaciones que elegiste. Es importante que justifiques por qué las haces:

    * Detección y eliminación de Outliers
    * Encoding
    * Imputación de valores faltantes
    * Escalado de datos
    * Generación de nuevas variables predictoras/reducción de dimensionalidad (SVD/PCA).

Vuelve a entrenar el modelo implementado en la Entrega 01 - en particular, el árbol de decisión - con este nuevo dataset transformado. Evalúa su desempeño a partir del dataset obtenido luego de transformar los datos. ¿Hay una mejora en su desempeño? Compara con el desempeño obtenido en el proyecto 01. Sea cual sea la respuesta, intenta explicar a qué se debe.

#### PARTE B - Modelos Avanzados

    * Elige dos de los modelos avanzados vistos Compara con el desempeño obtenido en el proyecto 01 (en el caso de regresión, considera una regresión lineal con atributos polinómicos y regularización). Entrénalos y evalúalos con sus argumentos por defecto. No te olvides de hacer un train/test split y usar Validación Cruzada.
    * Optimiza sus hiperparámetros mediante Validación Cruzada y Grid Search o Random Search.
    * Compara el desempeño de los nuevos modelos entre sí y con el modelo de la Parte A. ¿Cuál elegirías? Justifica.

#### PARTE C - Interpretación de modelos

De acuerdo a lo que el modelo permite, responde algunas o todas las siguientes preguntas:

    * ¿Qué variables fueron relevantes para el modelo para hacer una predicción? ¿Cuáles no? Si usaste una regresión lineal con regularización, presta atención a los parámetros (pendientes) obtenidas. Si usaste un modelo de ensamble en árboles, además de ver la importancia de cada atributo, también elige algunos árboles al azar y observa qué atributos considera importantes. ¿En qué se diferencian esos árboles? ¿Por qué? Finalmente, responde, ¿coincide con lo que esperabas a partir de tu experiencia con este dataset?

    * ¿Cómo es la distribución de errores (regresión) o qué clases se confunden entre sí (clasificación)? ¿Dónde falla? ¿A qué se debe?

#### DESAFÍO OPCIONAL

Aplica una técnica de Clustering sobre el dataset. Puedes combinar con técnicas de reducción de dimensionalidad para facilitar la visualización. ¿Qué clusters encuentras? ¿A qué pueden corresponder? Te dejamos preguntas que pueden servir como disparadoras: ¿qué barrios se parecen más entre sí?¿qué tipos de propiedades se parecen más entre sí?

### Checklist de evaluación

Sugerencias para desarrollar el proyecto:

    * Este proyecto no cuenta con mínimos entregables indicados en la consigna, pero ten en cuenta lo siguiente:
        1. en la Parte A debes implementar al menos tres de las transformaciones de datos propuestas.
        2. en la Parte B, al menos un modelo debe ser optimizado por Grid Search o Random Search; el otro puede ser optimizado por búsqueda manual (es decir, puedes dejar los mejores parámetros que encontraste probando).
        3. en la Parte C, debes responder al menos una pregunta. Obviamente, ¡cuanto más hagas, más aprenderás y mejor será tu proyecto!
    * La resolución del proyecto te puede enfrentar a pequeños desafíos que no trabajamos durante los encuentros. Es importante que desarrolles la capacidad de resolverlos. Para ello, consulta las bitácoras, las referencias, los notebooks vistos en clase, la documentación de la librería y, sobre todo, googlea.

Antes de subir tu proyecto a la plataforma Acámica para que sea evaluado, verifica que el Notebook se ejecute sin errores. Además, asegúrate de cumplir con las siguientes condiciones (son las que los/as evaluadores/as tendrán en consideración al momento de corregir tu trabajo):

#### PARTE A - Transformación de Datos

    * Debes justificar por qué creés que las transformaciones elegidas aplican en este dataset. Ten en cuenta que, en el manejo de valores atípicos o en la imputación de valores faltantes, los valores obtenidos deben tener sentido. Por ejemplo, valores mayores que cero para superficies, número de baños, etc.
    * Debes re entrenar un modelo del Proyecto 01 y comparar su desempeño con el modelo obtenido en el Proyecto 01. Una aclaración: con reentrenar nos referimos a usar el mismo proceso de entrenamiento junto con sus hiperparámetros. Pero puede ocurrir - y, de hecho, se espera - que el dataset contenga más atributos que los utilizados en el Proyecto 01.

#### PARTE B - Modelos Avanzados

    * En la optimización de hiperparámetros, debes justificar los parámetros que elegiste para optimizar y el rango de cada uno.

#### PARTE C - Interpretación de modelos

    * Debes estudiar qué variables utiliza el modelo para predecir y responder la pregunta: ¿coincide con lo que esperabas a partir de tu experiencia con este dataset?
    * Es muy importante que analices los errores del modelo. ¿Dónde es mayor el error? ¿dónde acierta?
    * Debes ser crítico/a con la metodología utilizada. ¿Qué mejorarías? Ten en cuenta siempre terminar con una discusión sobre lo realizado y conclusiones obtenidas.
	
---
---
---

## Proyecto 3 -	Aplicaciones actuales

¡Aplica Procesamiento del Lenguaje Natural, Sistemas de Recomendación, Series de Tiempo y Análisis de Imágenes para resolver problemas de relevancia contemporánea!

### Resumen del proyecto

¡Aplica Procesamiento del Lenguaje Natural, Sistemas de Recomendación y Series de Tiempo para resolver problemas de relevancia contemporánea!

### Entregables

Un Notebook de Jupyter con la resolución de la consigna. El Notebook debe poder ejecutarse sin errores. En el notebook debe estar el link al repositorio (por ejemplo, de GitHub) donde se pueda encontrar el proyecto entregado.

### Referencias

Apóyate en las bitácoras, los notebooks trabajados y las presentaciones vistas en clase para resolver tu proyecto. También será de mucha utilidad la documentación de las librerías de Python. No dudes en consultar comunidades online como Stack Overflow y, por supuesto, buscar en la web (googlear).

### Consigna

Elige una de las tres opciones de aplicación para elaborar tu proyecto. El objetivo es que apliques las herramientas aprendidas en el dominio que hayas seleccionado. Verás que para cualquiera de las opciones, el trabajo se organiza en tres partes:

    * Parte A - Exploración de Datos. Todo proyecto de Ciencia de Datos empieza con un Análisis Exploratorio de Datos. Y todo Análisis Exploratorio de Datos debe responder preguntas.
    * Parte B - Modelo de Machine Learning. En esta sección deberás aplicar las técnicas de Machine Learning aprendidas para crear un modelo predictivo a partir del dataset provisto.
    * Parte C - Investigación. Las preguntas y cosas para probar nunca se agotan. El objetivo de esta sección es que sugieras cómo continuarías el proyecto, con el fin de mejorar el modelo o responder una pregunta que consideres interesante. En todos los notebooks dejamos algunas sugerencias, pero puedes proponer otras.

Aquí debajo encontrarás el notebook con las consignas y el dataset para cada caso. Ten en cuenta que este proyecto se monta sobre los proyectos anteriores, y que ya esperamos cierto grado de independencia de parte tuya. Por eso, las consignas y recomendaciones de los notebooks no son exhaustivas. Es decir, si hay un paso en el flujo de trabajo que no está mencionado en el notebook que te dejamos, no implica que no haya que hacerlo. Recuerda que para ver lo que sí tiene que estar sin falta en tu entregable debes consultar el Checklist.

#### Opción 1: Sistemas de recomendación

Implementa un Sistema de Recomendación para videojuegos de la plataforma Steam.

    * Dataset. En este repositorio puedes encontrar el dataset, junto con información sobre sus creadores (¡a quienes les agradecemos fuertemente!). Descarga los dos archivos (reviews y game_info) con anticipación. ¡Ten en cuenta que el primero ocupa bastante lugar!
    * Notebook. Aquí te dejamos un notebook con algunas recomendaciones y líneas de código para que empieces a explorar los datos.

#### Opción 2: Procesamiento de Lenguaje Natural

Implementa un modelo para reconocer el puntaje asignado a un ítem de Amazon a partir de la crítica que hace un/a usuario/a.

    * Dataset. Aquí puedes encontrar la descarga del dataset e información sobre el mismo aquí. Es importante que tengas en cuenta la licencia de este dataset.
    * Notebook. Aquí te dejamos un notebook con algunas recomendaciones para tu trabajo.

#### Opción 3: Series de Tiempo

Implementa un modelo para predecir el flujo vehicular en una autopista de la Ciudad de Buenos Aires, Argentina.

    * Dataset. Aquí puedes descargar el dataset. Deberás descargar - al menos para comenzar - los años 2017, 2018 y 2019. ¡Agradecemos a todos/as los que hacen Datos Abiertos!
    * Notebook. Aquí te dejamos un notebook con algunas recomendaciones y líneas de código para que empieces a explorar los datos.

### Checklist de evaluación

Sugerencias para desarrollar el proyecto:

    * La resolución del proyecto te puede enfrentar a desafíos que no trabajamos durante los encuentros. Es importante que desarrolles la capacidad de resolverlos. Para ello, consulta las bitácoras, las referencias, los notebooks vistos en clase, la documentación de la librería y, sobre todo, googlea.
    * Los pasos deben estar correctamente justificados.
    * Las preguntas que se respondan deben estar correctamente explicitadas.
    * Imagina que este proyecto lo usarías para presentar en una entrevista de trabajo, o que lo debes presentar en tu trabajo. Presta mucha atención a la redacción, presentación de gráficos, etc.

Antes de subir tu proyecto a la plataforma Acámica para que sea evaluado, verifica que el Notebook se ejecute sin errores. Además, asegúrate de cumplir con las siguientes condiciones (son las que los/as evaluadores/as tendrán en consideración al momento de corregir tu trabajo):

#### Parte A - Exploración de Datos

    * El Análisis Exploratorio de Datos debe servir para comprender el dataset y todo el flujo de trabajo que le siga.
    * Debes responder al menos una pregunta original con este dataset. La pregunta debe estar correctamente explicitada.

#### Parte B - Modelo de Machine Learning

    * Debes evaluar correctamente el modelo que realices. Esto implica un correcto manejo de datos de Train y Test, elegir una métrica apropiada y justificar su elección, y comparar los resultados contra un modelo benchmark.
    * Puedes aplicar más de una de las técnicas vistas para crear tus modelos. Pero ten en cuenta que es preferible un modelo bien hecho (apropiada transformación de datos, optimización de hiperparámetros y análisis de sus resultados) que muchos modelos a medias. En caso de entrenar más de un modelo, debes comparar sus resultados y justificar cuál elegirías.
    * Si el modelo lo permite, debes explorar qué información utiliza para predecir e interpretar ese resultado. ¿Coincide con lo que esperabas a partir de tu experiencia con el dataset?

#### Parte C - Investigación

    * Debes explicar qué te gustaría probar, por qué y cómo lo harías. Si tienes referencias (por ejemplo, un artículo que hayas encontrado, capítulo de libro, etc.), debes mencionarlas.
    * Debes comentar también qué resultados esperas encontrar. Por ejemplo, puedes implementar una prueba rápida y mostrar resultados preliminares, para ver si estás correctamente orientado.
	
---
---
---

## Proyecto 4 -Informe Final Carrera

Profundiza y ajusta la resolución de tus proyectos: agrega al menos una fuente de datos o prueba un modelo que hasta el momento no hayas aplicado. Elabora un informe ?nal que describa el proceso de toma de decisiones. Sustenta la razón por la cual usaste las librerías y aplicaste los métodos al dataset. Todos tus hallazgos deberán ser comunicados en función de la problemática y las preguntas que buscabas responder.

### Resumen del proyecto

Profundiza y ajusta la resolución de tus proyectos. Agrega una fuente de datos, prueba un modelo nuevo o responde una pregunta nueva. Elabora un informe final que describa el proceso de toma de decisiones. Sustenta la razón por la cual usaste las librerías y aplicaste los métodos al dataset. Todos tus hallazgos deberán ser comunicados en función de la problemática y las preguntas que buscabas responder.

### Entregables

Un Notebook de Jupyter con la resolución de la consigna. El Notebook debe poder ejecutarse sin errores. En el notebook debe estar el link al repositorio (por ejemplo, de GitHub) donde se pueda encontrar el proyecto entregado y todo los materiales necesarios.
Referencias

Apóyate en las bitácoras, los notebooks trabajados y las presentaciones vistas en clase para resolver tu proyecto. También será de mucha utilidad la documentación de las librerías de Python. No dudes en consultar comunidades online como Stack Overflow y, por supuesto, buscar en la web (googlear).

### Consigna

Te presentamos los pasos a seguir para realizar el proyecto 04.

    * Elige tu punto de partida entre dos opciones:
        1. Tus Proyectos 01 y 02
        2.. Tu Proyecto 03

Si corresponde, emprolija lo hecho hasta el momento, incorporando las correcciones y/o sugerencias que hayas recibido de tu(s) evaluador/a (es/as).

    * Formula una nueva pregunta, problema o desafío para explorar. Aquí hay una lista no exhaustiva de opciones que puedes elegir:
    * Prueba un modelo de Machine Learning nuevo que no hayas visto en la carrera. En ese caso, debes explicar su funcionamiento y por qué consideras apropiado aplicarlo. La ganancia no necesariamente tiene que ser en desempeño, también puede ser en interpretabilidad o aplicabilidad.
    * Agrega al proyecto información de otra fuente. ¡Es sumamente válido! En ese caso, debe estar claramente explicado cómo conseguiste esos datos y qué usos esperas darles. Los datos deben ser accesibles por tu evaluador/a (por ejemplo, puedes subirlos al repositorio). Presta atención a la sensibilidad y privacidad de los datos antes de compartirlos.
    * Continúa el Análisis Exploratorio de Datos. Recuerda que es tan importante como entrenar un modelo de Machine Learning.
    * Sigue las sugerencias que te propusimos en los notebooks para continuar el Proyecto 03.

Plantea un objetivo alcanzable. En esta etapa de tu formación, es preferible un problema sencillo bien abordado que uno ambicioso que no sabes cómo abordar. El objetivo debe estar correctamente explicitado. Debes explicar qué quieres hacer y qué esperas encontrar. Imagina que es una tarea en tu trabajo y tienes que explicarle a un/a jefe/a qué vas a hacer y por qué.

### Checklist de evaluación

    * Se evaluará la claridad con la que está expuesto el objetivo a alcanzar y su relevancia.
    * Los pasos deben estar correctamente justificados. No deben haber grandes grupos de celdas de código sin explicar su función. Lo mismo aplica para los gráficos. Recuerda que el notebook es un informe.
    * Las preguntas que se respondan deben estar correctamente explicitadas.
    * Imagina que este proyecto lo usarías para presentar en una entrevista de trabajo, o que lo debes presentar en tu trabajo. Presta mucha atención a la redacción, presentación de gráficos, etc.
    * Debes entregar el proyecto anterior correspondiente (Proyecto 2 si eliges continuar con el dataset de Properati, Proyecto 3 si eliges continuar con alguna aplicación), el cual debe estar subido al repositorio.
    * Incorpora las correcciones y/o sugerencias que tu evaluador/a te haya dado en la devolución del proyecto correspondiente anterior.

Antes de subir tu proyecto a la plataforma Acámica para que sea evaluado, verifica que el Notebook se ejecute sin errores.