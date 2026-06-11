# Luciano Balladares
### Healthcare Data Analyst · Tecnólogo Médico (BACIMET)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Luciano%20Balladares-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/luciano-balladares/)
[![Email](https://img.shields.io/badge/Email-l.garridoballadares%40uandresbello.edu-D14836?style=flat&logo=gmail)](mailto:l.garridoballadares@uandresbello.edu)
[![Johns Hopkins](https://img.shields.io/badge/Health%20Informatics-Johns%20Hopkins%20University-002D62?style=flat)](https://www.coursera.org/specializations/health-informatics)
[![English](https://img.shields.io/badge/English-C2%20Proficient%20(EF%20SET%2080%2F100)-brightgreen?style=flat)](https://www.efset.org/)

Construyo puentes entre el dominio clínico y la analítica de datos en el sistema público de salud.

Mi formación como Tecnólogo Médico me da algo que un data scientist sin historia clínica no tiene: sé **qué** significan los datos antes de procesarlos. Sé por qué una lista de espera NO GES tiene esa estructura, qué incentivos genera la Glosa 06, y qué decisiones de gestión se esconden detrás de cada delta de mediana.

---

## 🔬 Proyecto principal

### [Análisis Longitudinal de Listas de Espera NO GES en Chile (2021–2025)](https://github.com/LucianoBalladares/Analisis-de-Listas-de-Espera-No-GES)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20635195.svg)](https://doi.org/10.5281/zenodo.20635195)
[![CI](https://github.com/LucianoBalladares/Analisis-de-Listas-de-Espera-No-GES/actions/workflows/ci.yml/badge.svg)](https://github.com/LucianoBalladares/Analisis-de-Listas-de-Espera-No-GES/actions/workflows/ci.yml)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat&logo=python)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-12%2B-336791?style=flat&logo=postgresql)](https://www.postgresql.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat)](https://app.powerbi.com/view?r=eyJrIjoiNDFhZDFlMWYtYzhkMC00NjRjLWIzNzItMGY1MWEyNDUwZmE5IiwidCI6IjZmZDQ4ZjQxLWFmODEtNDVhNS05YzFlLWUzOTkwYmMyN2U3YyIsImMiOjR9)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat)](LICENSE)

Pipeline ETL end-to-end + base de datos PostgreSQL + dashboard Power BI 7 páginas para el análisis de heterogeneidad territorial en listas de espera del sistema público chileno.

**¿Qué construí?**

```
Glosa 06 (PDF/imágenes MINSAL)
        │
        ▼  OCR + validación manual
        ▼  Python: limpieza, normalización, tests, UPSERT idempotente
        ▼  PostgreSQL: 4 tablas · 5 vistas analíticas · triggers · CI/CD
        ▼
   Power BI — 7 páginas · DAX · segmentación operacional
```

**Escala del proyecto:**

| Dimensión | Valor |
|-----------|-------|
| Período cubierto | 17 trimestres (2021–2025) |
| Servicios de Salud | 29 SS del sistema público |
| Tipos de prestación | CNE + IQ (Intervención Quirúrgica) |
| Registros CNE | ~2,46 millones |
| Tests automatizados | 80+ unitarios + integración |
| Versiones Python en CI | 3.10, 3.11, 3.12 |

**Hallazgo central:** La crisis post-pandemia fue inicialmente homogénea (R²=0,88 en IQ, 2022 T3) y se fragmentó en cuatro perfiles operacionales durante la recuperación. Los SS que lideraban la lista en 2022 la lideran en 2025, aunque a valores absolutos menores.

🔗 [Dashboard Power BI](https://app.powerbi.com/view?r=eyJrIjoiNDFhZDFlMWYtYzhkMC00NjRjLWIzNzItMGY1MWEyNDUwZmE5IiwidCI6IjZmZDQ4ZjQxLWFmODEtNDVhNS05YzFlLWUzOTkwYmMyN2U3YyIsImMiOjR9) · 📄 [Informe PDF](Reporte_Mayo_2026.pdf) · 📊 [Repositorio](https://github.com/LucianoBalladares/Analisis-de-Listas-de-Espera-No-GES)

---

## 🛠️ Stack técnico

**Data & Analytics**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/-Excel%20Avanzado-217346?style=flat&logo=microsoftexcel&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat)
![pandas](https://img.shields.io/badge/-pandas-150458?style=flat&logo=pandas)

**DevOps & Tooling**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

**Dominio en salud digital**

![LOINC](https://img.shields.io/badge/-LOINC-00539B?style=flat)
![HL7 FHIR](https://img.shields.io/badge/-HL7%20FHIR-E84E40?style=flat)
![SNOMED CT](https://img.shields.io/badge/-SNOMED%20CT-5B9BD5?style=flat)

---

## 🏥 Por qué Health Data Analytics

No llegué a los datos desde la programación. Llegué desde el laboratorio clínico.

Trabajé en UMT y Banco de Sangre en el Hospital El Carmen (Maipú) y en BACIMET en el Hospital Adriana Cousiño (Quintero). Ahí aprendí que los datos clínicos no son filas en una tabla — son decisiones de triage, protocolos, tiempos de reporte, flujos de trabajo que cambian con cada turno.

Eso es lo que me diferencia: cuando analizo que SS Metropolitano Norte tiene 378 días de mediana en CNE, no solo calculo el número. Sé lo que significa para el paciente, para el gestor del servicio, y para el sistema que tiene que responder.

---

## 📚 Formación

| Institución | Título / Programa |
|-------------|-------------------|
| Universidad Andrés Bello | Tecnólogo Médico — Mención BACIMET |
| Johns Hopkins University | Health Informatics Specialization |
| Academia 4HC | Diplomado en Gestión de Calidad en Salud |
| Harvard University | CS50 — Introduction to Computer Science |
| Microsoft & LinkedIn | Career Essentials in Data Analysis |
| Stanford University | COVID-19 Training for Healthcare Workers |
| FreeCodeCamp | Data Analysis with Python |

---

## 💼 Buscando oportunidades

Busco mi **primer rol formal en analítica de datos en salud**, en cualquier sector (público, privado, consultora).

Roles de interés: Analista de Datos en Salud · Business Intelligence Analyst · Health Data Analyst · Analista de Gestión Sanitaria

📧 l.garridoballadares@uandresbello.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/luciano-balladares/)

---

<div align="center">
  <i>Santiago de Chile · Disponible para trabajo presencial, híbrido o remoto</i>
</div>
