---
title: "07 Proyectos de Power Bi"
output:
  md_document:
    variant: gfm+footnotes
    preserve_yaml: TRUE
knit: (function(inputFile, encoding) {
  rmarkdown::render(inputFile, encoding = encoding, output_dir = "../_posts") })
date: 2027-07-26
permalink: /portfolio/Portfolio-07-Proyectos-en-Power-Bi
excerpt_separator: <!--more-->
toc: true
header:
 og_image: "posts/Portfolio-07-Proyectos-en-Power-Bi/shared_legend_right-1.png" 
tags:
  - GIS
  - visualization
  - peacekeeping
---

Colección de dashboards desarrollados en Power BI para proyectos de educación, programas sociales y análisis de negocios. Incluye indicadores de gestión, monitoreo de resultados, análisis geoespacial y reportes interactivos para apoyar la toma de decisiones

<!--more-->

# Contenido
1. [**Tablero de Servicios Educativos**](#1)
2. [**Proyecto Observatorio Nacional de la Discapacidad**](#2)
3. [**Otros Proyectos**](#3)

# 1. Proyecto Plataforma VISIBLE <a id='1'></a>

**Institución:** Ministerio de Educación - MINEDU  
**Rol:** Consultor (Data Scientist)  
**Año:** 2026 
**Herramienta principal:** SQL, Power BI, Python, STATA, Git/GitHub  
**Estado:** En producción

## 1.1. Objetivo del Proyecto 🎯

Construir/estimar indicadores y desarrollar **dashboards** estadísticos para la sección de indicadores de la nueva [**Plataforma VISIBLE**](https://visible.dansantivanezdev.space/) (un espacio implementado por el MIMP para integrar, estandarizar y organizar los observatorios del sector), orientados a consolidar información oficial y facilitar la toma de decisiones, la planificación de políticas públicas y la transparencia institucional.

### 📈 Dashboard (Servicios Educativos) [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiYWUyNmU5YzEtM2QxMC00NDg0LTg0MTktMTllOTdkNTMwMjM1IiwidCI6IjE3OWJkZGE4LWQ5NjQtNDNmZi1hZDNiLTY3NDE4NmEyZmEyOCIsImMiOjR9)

## 1.2. Estructura del proyecto 🧮

Organización del proyecto orientada a reproducibilidad, control de versiones y carga en Power BI:

```cmd
├───01_data/
│   ├───01_raw/
│   └───02_processed/
├───02_code/
├───03_doc/
├───04_results/
│   ├───01_wide/
│   ├───02_long/
│   └───03_carga_bi/
├───05_report/
│   
├───.gitignore
├───overview-noshare.tex
├───README-noshare.md
└───requirements.txt
```

## 1.3. Indicadores Clave (KPIs) por Temática 📌

Indicadores organizados por temáticas poblacionales:  
- Niñas, Niños y Adolescentes (NNA)  
- Personas con Discapacidad (PCD)  
- Personas Adultas Mayores (PAM)  
- Violencia  
- Familias  

Dimensiones de análisis:  
- Salud
- Educación
- Empleo
- Ingresos
- Relaciones familiares

Principales desagregaciones:
- Periodo: 2019 – 2024
- Área de residencia: Urbano / Rural
- Región: 26 departamentos (incluye Lima metropolitana)

### 📈 Dashboard (Programas Presupuestales) [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiYjdiYzAwZDItZWZjNi00ZDY4LTkzNmQtMDdjZmMxOWRiYzdkIiwidCI6IjY4MTljNDYzLTVkZWItNDA3MC1hY2I2LTlmZGQzY2FhZTk4NCJ9&pageName=5a7dac000b9e16b97ac8)
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/PP0117_N.gif)

### 📈 Dashboard (Políticas Multisectoriales) [🔗ver](https://visible.dansantivanezdev.space/observatorios/discapacidad/estadisticas)
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/EN.gif)

### **Portada del Tablero de Padrón de Servicios Educativos** 
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/Tablero_01_Portada.png)
### **Inicio 1**
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/Tablero_02_Inicio_1.png)
### **Inicio 2**
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/Tablero_03_Inicio_2.png)
### **Estadísticas Generales**
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/Tablero_04_General.png)
### **Estadísticas por I.E.**
![VISIBLE](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/01-Power-BI/Tablero_05_Estadisticas.png)

> Los dashboards permiten filtros dinámicos por periodo, región, área de residencia y características poblacionales.

{% comment %}  

# 2. Proyecto Observatorio Nacional de la Discapacidad <a id='2'></a>

**Institución:** Consejo Nacional para la Integración de la Persona con Discapacidad - CONADIS  
**Rol:** Consultor (Data Scientist)  
**Año:** 2024 | 2025  
**Herramienta principal:** Power BI, Python, STATA, Git/GitHub, VSCode  
**Estado:** En producción

## 2.1. Objetivo del Proyecto 🎯

Construir/estimar indicadores y desarrollar **dashboards** estadísticos para la sección [**Discapacidad en cifras**](https://observatorio.conadisperu.gob.pe/discapacidad-en-cifras/) del **Observatorio Nacional de la Discapacidad** una plataforma orientada a brindar información relevante, confiable, oportuna, amigable y accesible en materia de
discapacidad para las entidades públicas, centros de investigación, entre otros.

🔗 [Observatorio Nacional de la Discapacidad](https://observatorio.conadisperu.gob.pe/)

## 2.2. Estructura del proyecto 🧮

Organización del proyecto orientada a reproducibilidad, control de versiones y carga en Power BI:

🔗 [Documentación técnica](documentacion.pdf)

```cmd
/DISCAPACIDAD EN CIFRAS 2025/
│ 
├───1 - ENAHO
│   ├───1 - DATA
│   │   ├───1 - DATA RAW
│   │   └───2 - DATA CLEAN
│   ├───2 - CODIGO
│   ├───3 - TABULADOS
│   ├───4 - CARGA BI
│   └───5 - REPORTE BI
├───2 - FISCALIZACION
│   ├───1 - DATA
│   │   ├───1 - DATA RAW
│   │   └───2 - DATA CLEAN
│   ├───2 - CODIGO
│   ├───3 - TABULADOS
│   ├───4 - CARGA BI
│   └───5 - REPORTE BI
├───3 - REGISTRO
│   ├───1 - DATA
│   │   ├───1 - DATA RAW
│   │   └───2 - DATA CLEAN
│   ├───2 - CODIGO
│   ├───3 - TABULADOS
│   ├───4 - CARGA BI
│   └───5 - REPORTE BI
├───4 - SECTORES
│   ├───1 - DATA
│   │   ├───1 - DATA RAW
│   │   └───2 - DATA CLEAN
│   ├───2 - CODIGO
│   ├───3 - TABULADOS
│   ├───4 - CARGA BI
│   └───5 - REPORTE BI
├───.gitignore
├───overview-noshare.tex
├───requirements.txt        # Dependencias del proyecto
├───README.md               # Documentación
└───.venvCONADIS            # Entorno virtual
```

## 2.3. Indicadores (KPIs) 📌

Dashboards organizados por temáticas:
- Situación de las personas con discapacidad: ¿Cómo vamos?  
- Infracciones bajo la lupa: ¿Qué estamos fiscalizando?  
- Explora el Registro del CONADIS: ¿Cuántas personas con discapacidad están registradas en el RNPCD?   

Dimensiones de análisis:  
- Sociodemográfico  
- Participación política y social  
- Empleo e ingresos  
- Salud  
- Educación  
- Pobreza  

Principales desagregaciones:
- Periodo: 2014 – 2024
- Área de residencia: Urbano / Rural
- Región: 26 departamentos (incluye Lima metropolitana)
- Características demográficas.

### 📈 Dashboard (Power BI)
#### **Situación de las personas con discapacidad: ¿Cómo vamos?**  [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiYmRmM2UyMzAtMzkzMy00MWE2LTlmYmQtMjZjMDI0OGZlYzAzIiwidCI6IjA5OTJkMDkyLTIyZDktNDVhOC05M2EwLTY3NTY4ZGMzMDY4MiIsImMiOjR9)
![Cómo vamos](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/02-Power-BI/DEC.gif)

#### **Infracciones bajo la lupa: ¿Qué estamos fiscalizando?**   [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiNDU3ZDBjYWEtODBiMi00OGZiLWIzNGQtZmNlZjA1ZGZmMWIxIiwidCI6IjA5OTJkMDkyLTIyZDktNDVhOC05M2EwLTY3NTY4ZGMzMDY4MiIsImMiOjR9)
![Qué estamos fiscalizando](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/02-Power-BI/FIS.gif)

#### **Explora el Registro del CONADIS: ¿Cuántas personas con discapacidad están registradas en el RNPCD?**   [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiNmJjYTIyMTQtOTY4Mi00YTYxLTg1MzgtYWFjODk4ZmQwZWI3IiwidCI6IjA5OTJkMDkyLTIyZDktNDVhOC05M2EwLTY3NTY4ZGMzMDY4MiIsImMiOjR9)
![Registro](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/02-Power-BI/REG.gif)

> Los dashboards permiten filtros dinámicos por periodo, región, área de residencia y características poblacionales.

# 3. Otros Proyectos <a id='3'></a>

**Proyecto:** Estadisticas MIMP  
**Rol:** Data Analyst 
**Año:** 2021 | 2022  
**Herramienta principal:** Power BI  
**Estado:** En producción

## 3.1. Objetivo del Proyecto 🎯

Implementar **dashboards** estadísticos para la sección [**Estadísticas MIMP**](https://www.mimp.gob.pe/omep/estadisticas-tablero-desempenio-NNA.php) para el seguimiento de indicadores y rendición de cuentas sobre los Programas Presupuestales.

🔗 [Estadísticas MIMP](https://www.mimp.gob.pe/omep/estadisticas-mimp.php)

## 3.2. Dashboard (Power BI) 📈
### **Programa Presupuestale 117:** Niñas, Niños y Adolescentes (NNA)  [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiODA0YmY2OTEtYTE2ZC00NjM0LWFkYWItOWQ1NWQwMmUwN2RjIiwidCI6IjY4MTljNDYzLTVkZWItNDA3MC1hY2I2LTlmZGQzY2FhZTk4NCJ9)
![117](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/03-Power-BI/PP117.gif)

### **Programa Presupuestale 142:** Personas Adultas Mayores (PAM)   [🔗ver](https://app.powerbi.com/view?r=eyJrIjoiMjI1NzJiZGYtMGYzYi00MDAwLTg3ODgtMDk4ZTJhOTU2MDNlIiwidCI6IjY4MTljNDYzLTVkZWItNDA3MC1hY2I2LTlmZGQzY2FhZTk4NCJ9)
![142](/images/posts/Portfolio-07-Proyectos-en-Power-Bi/03-Power-BI/PP142.gif)
{% endcomment %}

## Licencia <a id="7"></a>
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](/LICENSE) para más detalles.

[**⬆ Volver al inicio**](#top)