# 🧭 Puestos Sensibles a la Corrupción (PSC)

Repositorio para la construcción y documentación de un listado de **servidores públicos con vinculación activa en SIGEP** que ocupan **cargos de confianza, manejo presupuestal y funciones directivas**, especialmente bajo la modalidad de **libre nombramiento y remoción**.

Este README es **parcial** y describe el propósito del proyecto, su estructura y el estado actual de desarrollo.

---

## 🎯 Objetivo general

* Consolidar y preparar información estructurada sobre **puestos sensibles a la corrupción**.
* Documentar un proceso **ETL reproducible** basado en fuentes oficiales.
* Dejar habilitada la base para análisis posteriores (exploración, indicadores, visualización o modelos).

> El proyecto tiene un enfoque **estructural y preventivo**. No realiza valoraciones individuales.

---

## 📁 Estructura del repositorio

```bash
Puestos-Sensibles-Corrupcion/
├── Data/
│   ├── Raw/
│   │   └── PSC.csv
│   └── Processed/
│
├── Docs/
│   ├── context.md
│   └── methodology.md
│
├── Notebooks/
│   ├── 01_inspeccion_datosPSC.ipynb
│
├── SRC/
│   └── ETL/
│       ├── Utils/
│       └── que debe ir aquí.txt
│
├── Report/
│
├── Visuals/
│
├── LICENSE
└── README.md
```

---

## 📂 Descripción breve de carpetas

* **Data/Raw**: datos originales sin transformación.
* **Data/Processed**: salidas del proceso ETL.
* **Docs**: documentación de contexto y metodología.
* **Notebooks**: inspección y análisis exploratorio.
* **SRC/ETL**: scripts del pipeline de datos.
* **SRC/Utils**: funciones auxiliares reutilizables.
* **Report**: resultados consolidados.
* **Visuals**: gráficos y recursos visuales.

---

## 🚧 Estado del proyecto

* ✔️ Estructura definida
* ✔️ Dataset base identificado
* ✔️ Documentación inicial
* 🔄 ETL en desarrollo
* ⏳ Análisis y productos finales pendientes

---

## 🛠️ Requisitos (provisorios)

```bash
python >= 3.10
pandas
numpy
jupyter
matplotlib / seaborn
```
