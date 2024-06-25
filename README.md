### Descripción del Proyecto

Este proyecto aplica la metodología CRISP-DM para el análisis descriptivo de bases de datos provenientes de encuestas sobre estancias profesionales y desempeño profesional de egresados. La información ha sido recopilada a través de encuestas y cuestionarios físicos realizados por alumnos y egresados, coordinados por la unidad de estancias profesionales y vinculación con egresados. Posteriormente, se realiza el análisis de datos utilizando técnicas de clustering K-Modes y K-Prototypes, identificando las características relevantes de cada clúster.

### Metodología CRISP-DM

CRISP-DM (Cross Industry Standard Process for Data Mining) es una metodología ampliamente utilizada en minería de datos que proporciona un proceso estructurado para abordar proyectos de análisis de datos. Se compone de seis fases:

1. **Comprensión del Negocio**:
   - **Objetivo**: Entender los objetivos y requerimientos del negocio.
   - **Actividades**: Definir los problemas del negocio, objetivos del proyecto, y criterios de éxito.
   
2. **Comprensión de los Datos**:
   - **Objetivo**: Familiarizarse con los datos disponibles.
   - **Actividades**: Recolectar datos iniciales, describir los datos, explorar los datos, y verificar la calidad de los datos.

3. **Preparación de los Datos**:
   - **Objetivo**: Preparar los datos en un formato adecuado para el análisis.
   - **Actividades**: Seleccionar datos, limpiar datos, construir datos derivados, integrar datos, y formatear datos.

4. **Modelado**:
   - **Objetivo**: Aplicar técnicas de modelado para el análisis de datos.
   - **Actividades**: Seleccionar técnica de modelado, generar diseño de prueba, construir modelos, y evaluar modelos.

5. **Evaluación**:
   - **Objetivo**: Evaluar el modelo para asegurar que cumple con los objetivos del negocio.
   - **Actividades**: Evaluar resultados, revisar proceso, y determinar próximos pasos.

6. **Despliegue**:
   - **Objetivo**: Implementar los resultados del proyecto de minería de datos.
   - **Actividades**: Planificar despliegue, monitorear y mantener modelo, y documentar y reportar resultados.

### Algoritmos de Clustering

#### K-Modes

K-Modes es una extensión del algoritmo K-Means diseñado para clústeres de datos categóricos. En lugar de utilizar la media para actualizar los centros de clústeres, K-Modes utiliza la moda (el valor más frecuente) para actualizar los centros. Este enfoque es ideal para datos categóricos, ya que minimiza la disimilitud entre los puntos de datos y los centros de los clústeres. Las principales características de K-Modes son:

- **Moda**: En lugar de promedios, se usan modas para definir centros de clústeres.
- **Disimilitud**: Se mide por la cantidad de atributos diferentes.
- **Eficiencia**: Es eficiente y escalable para grandes conjuntos de datos.

#### K-Prototypes

K-Prototypes es un algoritmo híbrido que combina K-Means y K-Modes para manejar conjuntos de datos mixtos (categóricos y numéricos). Este algoritmo permite agrupar datos que contienen tanto tipos de variables categóricas como numéricas. Las características clave de K-Prototypes son:

- **Actualización de Prototipos**: Utiliza medias para variables numéricas y modas para variables categóricas.
- **Medición de Disimilitud**: Combina la distancia euclidiana para variables numéricas y la disimilitud simple para variables categóricas.
- **Versatilidad**: Es adecuado para datos mixtos, proporcionando una solución unificada para variables heterogéneas.

### Resultados

Los resultados del proyecto incluyen:

- **Análisis de las Modas**: Identificación de las características más frecuentes en cada clúster.
- **Interpretación de Clústeres**: Análisis detallado de los clústeres formados y las tendencias observadas.
- **Visualización de Datos**: Gráficas y tablas que presentan las tendencias y características clave de los clústeres identificados.

Este proyecto demuestra cómo las técnicas avanzadas de clustering y la metodología CRISP-DM pueden aplicarse eficazmente para obtener insights valiosos a partir de datos de encuestas, proporcionando una comprensión más profunda del desempeño profesional de los egresados.

Organización del Código y Base de Datos
El código del proyecto está organizado en carpetas, cada una con comentarios y encabezados para facilitar la comprensión del funcionamiento de cada bloque de código. Aunque la base de datos no se puede proporcionar, se incluye una imagen que muestra cómo son los datos utilizados.

Colaboradores
Este trabajo fue realizado en colaboración con:

Ferra García Eduardo
Palma Nicolás Pavel
Pérez Medina Julio Josafat
