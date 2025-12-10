# 🚀 Proyecto de Investigación: Modelos de Escenarios y Técnicas de Inteligencia Artificial  
**Universidad Nacional del Oeste (UNO)**  
**Área:** Ingeniería de Requisitos • Modelos de Escenarios • Procesamiento del Lenguaje Natural (NLP)

---

## 📌 Descripción General del Proyecto

Este proyecto forma parte de una investigación adscripta a la **Universidad Nacional del Oeste**, dirigida por la **Dra. Graciela D. S. Hadad** y el **Dr. Jorge H. Doorn**, con el acompañamiento de la **Mg. María Celia Elizalde**.  
Se enmarca dentro del campo de la **Ingeniería de Requisitos**, con especial foco en el estudio, evolución y mejor aprovechamiento de los **modelos de escenarios**: descripciones en lenguaje natural que representan situaciones reales, ideales o problemáticas en un determinado contexto de trabajo.

Si bien los escenarios son herramientas cruciales para comprender la interacción usuario–sistema y derivar requisitos de software, su principal desafío es su **ambigüedad**, producto del lenguaje natural. Esto genera dificultades en etapas posteriores como **validación, diseño e implementación**.

Este proyecto investiga **nuevas formas de reorganizar, reagrupar y transformar escenarios** para hacerlos más claros y útiles, incorporando **herramientas de Inteligencia Artificial**, especialmente técnicas de **Procesamiento del Lenguaje Natural (NLP)**.

---

## 🎯 Objetivos Principales (Objetivos trabajados por Abril y Santiago)

### **🔹 Objetivo 1 – Agrupamiento Inteligente de Escenarios**
Diseñar un procedimiento basado en IA para **agrupar escenarios** según distintos criterios, empleando:
- Glosarios del equipo de investigación  
- Conjuntos reales de escenarios  
- Herramientas y modelos de NLP  
- Evaluación comparativa de métodos de agrupamiento  
- Elaboración de un procedimiento replicable y documentado  

### **🔹 Objetivo 3 – Reorganización y Validación de Escenarios**
Definir un procedimiento para **reorganizar y reagrupar escenarios** considerando distintos **puntos de vista de usuarios**.  
Incluye:
- Estudio de técnicas de validación  
- Definición de criterios para seleccionar usuarios evaluadores  
- Pruebas sobre conjuntos reales de escenarios  
- Propuesta de un método que mejore la calidad del proceso de validación  

---

## 👥 Equipo y Roles

### **Investigadores Adscritos**
- **Abril** — Enfocada especialmente en IA y Procesamiento del Lenguaje Natural (Objetivo 1).  
- **Santiago** — Co-responsable de los Objetivos 1 y 3, aportando al estudio, análisis y diseño de procedimientos.

### **Dirección y Acompañamiento**
- **Dra. Graciela D. S. Hadad** – Directora  
- **Dr. Jorge H. Doorn** – Co-director  
- **Mg. María Celia Elizalde** – Acompañamiento académico  

---

## 🧩 Estructura del Repositorio (Vista General)
```
📁 / (raíz)
├── 📄 [README.md]()                    ← Documentación principal del proyecto
├── 📄 [CONTRIBUTING.md]()              ← Guía para contribuir y colaborar en el proyecto
├── 📄 [LICENSE]()                      ← Licencia del proyecto
├── 📄 [.gitignore]()                   ← Archivos y carpetas ignoradas por Git
├── 📄 [requirements.txt]()             ← Lista de dependencias para Python
├── 📄 [environment.yml]() (opcional)   ← Entorno Conda para reproducibilidad
├── 📄 [Makefile]()                     ← Comandos automatizados para tareas comunes
│
├── 📁 [.github/]()                  ← Configuraciones específicas de GitHub
│   ├── 📁 [workflows/]()            ← Definiciones de CI/CD (tests automáticos, etc.)
│   └── 📁 [ISSUE_TEMPLATE/]()       ← Plantillas para issues y pull requests
│
├── 📁 [docs/]()                           ← Documentación complementaria y formal
│   ├── 📁 [procedimientos/]()             ← Procedimientos específicos (objetivos 1 y 3)
│   │   ├── 📄 [procedimiento_objetivo1.md]()  
│   │   └── 📄 [procedimiento_objetivo3.md]()
│   ├── 📁 [validacion/]()                 ← Material relacionado con validación de escenarios
│   └── 📁 [lecturas/]()                   ← Resúmenes, papers y bibliografía relevante
│
├── 📁 [notebooks/]()                 ← Jupyter notebooks para experimentos y prototipos
│   ├── 📁 [prototipos/]()            ← Pruebas exploratorias y desarrollo rápido
│   └── 📁 [experiments_formales/]()  ← Experimentos documentados y reproducibles
│
├── 📁 [src/]()                         ← Código fuente organizado por objetivo
│   ├── 📁 [objetivo1_agrupamiento/]()  ← Código para agrupamiento basado en IA
│   │   ├── 📁 [preprocessing/]()       ← Limpieza y preparación de datos
│   │   ├── 📁 [embeddings/]()          ← Modelos y generación de vectores semánticos
│   │   ├── 📁 [modelos/]()             ← Modelos NLP implementados o usados
│   │   └── 📁 [clustering/]()          ← Algoritmos de agrupamiento
│   └── 📁 [objetivo3_validacion/]()    ← Código para reorganización y validación
│       ├── 📁 [reorganizacion/]()      ← Métodos para reestructurar escenarios
│       └── 📁 [seleccion_usuarios/]()  ← Algoritmos para selección de evaluadores
│
├── 📁 [datasets/]()                 ← Datos usados en el proyecto
│   ├── 📁 [raw/]()                  ← Datos originales, sin modificar
│   ├── 📁 [processed/]()            ← Datos transformados o limpios para análisis
│   └── 📄 [README_datasets.md]()    ← Explicación sobre los datasets y uso
│
├── 📁 [results/]()                ← Resultados generados por experimentos
│   ├── 📁 [figures/]()              ← Gráficos e imágenes
│   ├── 📁 [tables/]()               ← Tablas y resúmenes numéricos
│   └── 📁 [runs_log/]()             ← Logs y detalles de ejecuciones
│
├── 📁 [tests/]()                  ← Tests unitarios y de integración
├── 📁 [scripts/]()                ← Scripts auxiliares y utilitarios
└── 📄 [experiments_meta.md]()      ← Metadatos y resumen general de experimentos
```


