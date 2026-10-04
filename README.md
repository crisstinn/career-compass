# career-compass

## Descripción

CareerCompass es una aplicación interactiva de apoyo a la toma de decisiones profesionales cuyo objetivo es ayudar a los usuarios a identificar qué países se adaptan mejor a su perfil profesional y a sus prioridades personales.

La aplicación combinará información laboral y socioeconómica de diferentes países para permitir su comparación teniendo en cuenta factores como el salario esperado, el coste de vida, las oportunidades laborales, las condiciones de trabajo y la calidad de vida.

El usuario podrá introducir información sobre su perfil profesional, como su experiencia y principales habilidades, y establecer qué factores considera más importantes a la hora de trabajar en otro país. A partir de esta información, CareerCompass ofrecerá recomendaciones personalizadas y permitirá comparar diferentes alternativas de forma interactiva.

## Objetivos

Los principales objetivos del proyecto son:

- Integrar información laboral y socioeconómica procedente de diferentes fuentes públicas.
- Relacionar las habilidades del usuario con posibles ocupaciones profesionales.
- Estimar mediante un modelo predictivo el salario esperado de un determinado perfil profesional en diferentes países.
- Permitir al usuario establecer sus propias prioridades a la hora de comparar países.
- Generar recomendaciones personalizadas a partir del perfil y las preferencias introducidas.

## Fuentes de datos

Inicialmente se prevé utilizar principalmente las siguientes fuentes:

- **Eurostat:** indicadores relacionados con coste de vida, vivienda, mercado laboral, horas de trabajo y calidad de vida.
- **OECD:** información económica y salarial comparable entre países.
- **Datasets públicos de salarios profesionales:** para el desarrollo y entrenamiento del modelo de predicción salarial.

Las distintas fuentes serán limpiadas, transformadas y homogeneizadas antes de su integración, prestando especial atención a la estandarización de países, periodos temporales y valores ausentes.

## Plan de trabajo inicial

1. Búsqueda, selección y adquisición de las fuentes de datos.
2. Exploración y limpieza de los datasets.
3. Homogeneización e integración de la información de los diferentes países.
4. Análisis exploratorio y desarrollo de las primeras visualizaciones.
5. Desarrollo y evaluación del modelo de predicción salarial.
6. Desarrollo del sistema de comparación y recomendación de países.
7. Diseño de la interfaz interactiva mediante Dash y Plotly.
