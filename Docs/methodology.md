## 1. Enfoque Metodológico

El proyecto adopta un **enfoque cuantitativo, exploratorio y descriptivo**, con extensiones comparativas y predictivas según la calidad y cobertura de la información disponible. El análisis se basa en el uso de datos administrativos transformados en insumos analíticos para la gestión del riesgo institucional.

El enfoque es preventivo y sistémico, alineado con los principios del MIPG. No se asume causalidad directa ni se realizan juicios individuales; el interés se centra en identificar **patrones estructurales** asociados a los puestos sensibles.

## 2. Fuente de Datos

La fuente principal es el dataset de **Puestos Sensibles a la Corrupción** publicado por el Departamento Administrativo de la Función Pública (DAFP). Este dataset contiene información relacionada con:

* Características del cargo.
* Información general de la entidad.
* Variables laborales y contractuales asociadas a la persona que ocupa el puesto.

Previo al análisis, se realizará un proceso de depuración, validación y estandarización de variables.

## 3. Estrategia de Análisis

### 3.1 Análisis Descriptivo

Se realizará una caracterización general del dataset, incluyendo:

* Distribución de puestos sensibles por entidad, sector y nivel administrativo.
* Características generales de los cargos (jerarquía, tipo de función).
* Perfil agregado de las personas vinculadas a estos puestos.

El objetivo es identificar concentraciones, patrones frecuentes y posibles asimetrías institucionales.

### 3.2 Análisis Comparativo

Se explorarán diferencias entre grupos de entidades o cargos mediante:

* Comparaciones entre entidades con alta y baja concentración de puestos sensibles.
* Análisis territorial cuando la información lo permita.
* Uso de estadísticos descriptivos y pruebas de significancia apropiadas.

Este nivel busca identificar desigualdades estructurales y priorizar focos de atención.

### 3.3 Análisis Exploratorio Avanzado

Cuando la estructura del dataset lo permita, se aplicarán técnicas exploratorias como:

* Análisis de correlación entre variables relevantes.
* Agrupamiento (clustering) para identificar perfiles típicos de puestos sensibles.
* Reducción de dimensionalidad para detectar estructuras latentes.

### 3.4 Modelos Predictivos (Opcional)

De manera exploratoria, se podrán construir modelos de clasificación orientados a identificar patrones asociados a mayor riesgo estructural. Estos modelos no tendrán fines predictivos individuales, sino analíticos.

## 4. Preguntas Analíticas Guía

El análisis se orienta por preguntas como:

* ¿Cómo se distribuyen los puestos sensibles a la corrupción entre entidades y niveles administrativos?
* ¿Existen perfiles recurrentes asociados a estos cargos?
* ¿Se observa concentración institucional del riesgo?
* ¿Qué variables parecen estar más asociadas a la sensibilidad del puesto?

## 5. Métricas de Evaluación

* **Análisis descriptivo:** claridad, coherencia y capacidad de identificar patrones relevantes.
* **Análisis comparativo:** significancia estadística y robustez de los resultados.
* **Modelos predictivos:** accuracy, precision, recall, F1-score y AUC-ROC, comparados con modelos base.

## 6. Criterio de Éxito

El estudio será considerado exitoso si los resultados:

* Aportan evidencia útil para la gestión preventiva del riesgo de corrupción.
* Son interpretables por actores institucionales.
* Permiten priorizar acciones dentro del marco del MIPG.

El énfasis estará en la **utilidad práctica** y la **coherencia metodológica**, más que en la complejidad técnica.
