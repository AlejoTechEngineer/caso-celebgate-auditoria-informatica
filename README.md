<div align="center">

# 🔐 Auditoría Informática: Caso Celebgate (iCloud 2014)

### *Análisis Crítico del Robo de Datos en iCloud desde la Perspectiva de la Auditoría de Sistemas de Información*

[![Asignatura](https://img.shields.io/badge/Asignatura-Calidad%20y%20Auditoría%20de%20SI-blueviolet.svg)]()
[![Institución](https://img.shields.io/badge/Institución-UNIR-blue.svg)](https://www.unir.net/)
[![Status](https://img.shields.io/badge/Status-Completado-success.svg)]()
[![Caso](https://img.shields.io/badge/Caso-iCloud%20Celebgate%202014-orange.svg)]()

**[Descripción](#-descripción-del-proyecto) • [Temas Abordados](#-temas-abordados) • [Arquitectura del Análisis](#-arquitectura-del-análisis) • [Contenido](#-contenido-del-repositorio) • [Metodología](#-metodología-aplicada) • [Autor](#-autor)**

<img src="https://img.shields.io/badge/Normativa-ISO%2FIEC%2027001-blue?style=flat-square" alt="Normativa"/>
<img src="https://img.shields.io/badge/Marco%20Legal-RGPD%20%7C%20Ley%201581-green?style=flat-square" alt="Marco Legal"/>
<img src="https://img.shields.io/badge/Formato-PDF-red?style=flat-square" alt="Formato"/>
<img src="https://img.shields.io/badge/Idioma-Español-lightgrey?style=flat-square" alt="Idioma"/>

</div>

---

## 📋 Tabla de Contenidos

- [🎯 Descripción del Proyecto](#-descripción-del-proyecto)
- [✨ Ejes del Análisis](#-ejes-del-análisis)
- [🧭 Temas Abordados](#-temas-abordados)
- [🏗️ Arquitectura del Análisis](#-arquitectura-del-análisis)
- [📁 Contenido del Repositorio](#-contenido-del-repositorio)
- [🔎 Metodología Aplicada](#-metodología-aplicada)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [👨‍💻 Autor](#-autor)

---

## 🎯 Descripción del Proyecto

Este repositorio contiene el desarrollo del **Laboratorio #1: Importancia de la Auditoría Informática**, elaborado para la asignatura **Calidad y Auditoría de Sistemas de Información** de la Fundación Universitaria Internacional de La Rioja (UNIR). El trabajo realiza un **análisis crítico del incidente de seguridad de iCloud ocurrido en 2014**, conocido públicamente como *"Celebgate"*, en el que cientos de cuentas de celebridades fueron comprometidas mediante ataques de fuerza bruta contra el servicio *Find My iPhone*.

### 🌟 ¿Por qué este análisis es relevante?

- 🔍 **Estudio de caso real**: analiza un incidente documentado con impacto mediático, legal y económico verificable.
- 🛡️ **Enfoque desde la auditoría**: no se limita a describir el ataque, sino que evalúa qué controles de auditoría informática habrían podido prevenirlo o mitigarlo.
- 📜 **Base normativa sólida**: contrasta el caso contra el estándar ISO/IEC 27001:2022 y su Anexo A.
- ⚖️ **Perspectiva legal**: incorpora el marco regulatorio de protección de datos aplicable (RGPD, LOPD, LSSICE, Ley 1581 de 2012).
- 🧩 **Análisis crítico propio**: evalúa la pérdida económica, la transparencia de Apple ante el incidente y el rol preventivo que debió tener la auditoría.

---

## ✨ Ejes del Análisis

<table align="center" width="100%">
  <tr>
    <td width="50%" valign="top">

<h3>📚 Marco Teórico</h3>

<ul>
  <li>✅ Sistema de Gestión de Seguridad de la Información (SGSI)</li>
  <li>✅ Tríada CID (Confidencialidad, Integridad, Disponibilidad)</li>
  <li>✅ Gestión de activos, amenazas, vulnerabilidades y riesgos</li>
  <li>✅ Estructura de la norma ISO/IEC 27001:2022</li>
  <li>✅ Tipos y funciones de la auditoría informática</li>
</ul>

<h3>🧪 Análisis Crítico</h3>

<ul>
  <li>📊 Reconstrucción cronológica del caso Celebgate</li>
  <li>📊 Vulnerabilidad explotada (Find My iPhone / iBrute)</li>
  <li>📊 Evaluación de la respuesta oficial de Apple</li>
  <li>📊 Impacto económico y reputacional del incidente</li>
  <li>📊 Recomendaciones desde la auditoría preventiva</li>
</ul>

  </tr>
</table>

---

## 🧭 Temas Abordados

<div align="center">

| 📚 **Marco Teórico y Normativo** | 🕵️ **Desarrollo del Caso** | ⚖️ **Análisis Crítico** |
|:----------------------------------:|:-----------------------------:|:---------------------------:|
| SGSI, tríada CID, no repudio | Vulnerabilidad Find My iPhone / iBrute | Pérdida económica del incidente |
| ISO/IEC 27001:2022 y Anexo A | Respuesta oficial de Apple | Transparencia como principio de seguridad |
| Auditoría vs. consultoría vs. asesoría | Marco legal (RGPD, LOPD, LSSICE, Ley 1581) | Rol preventivo de la auditoría informática |

</div>

El análisis desarrolla, entre otros puntos:
- Fundamentos de la seguridad de la información (SGSI, tríada CID, no repudio).
- Gestión de activos, amenazas, vulnerabilidades y riesgos.
- Estructura de la norma ISO/IEC 27001:2022 y su Anexo A.
- Auditoría informática: tipos, funciones y diferencias con consultoría y asesoría.
- Marco legal aplicable a la protección de datos (RGPD, LOPD, LSSICE, Ley 1581 de 2012).
- Análisis crítico del caso Celebgate: impacto económico, transparencia y el rol preventivo de la auditoría.

---

## 🏗️ Arquitectura del Análisis

```mermaid
flowchart TD
    A[Marco Teórico] --> B[SGSI, Tríada CID, ISO/IEC 27001]
    B --> C[Desarrollo del Caso iCloud 2014]
    C --> D[Vulnerabilidad Find My iPhone e iBrute]
    D --> E[Respuesta oficial de Apple]
    E --> F[Análisis Crítico]
    F --> G[Pérdida económica]
    F --> H[Transparencia como principio de seguridad]
    F --> I[Rol de la auditoría informática]
    G --> J[Recomendaciones y Conclusiones]
    H --> J
    I --> J
```

---

## 📁 Contenido del Repositorio

<table align="center">
  <tr>
    <th>Archivo</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td><code>Desarrollo_Proyecto_Alejandro_De_Mendoza_Tovar.pdf</code></td>
    <td>📄 Documento final con el desarrollo completo de la actividad: marco teórico, desarrollo del caso, análisis crítico, recomendaciones, glosario, conclusiones y bibliografía</td>
  </tr>
</table>

> ℹ️ El repositorio versiona **únicamente el PDF final**. Los documentos editables (`.docx`) y archivos temporales de trabajo quedan excluidos vía `.gitignore`.

---

## 🔎 Metodología Aplicada

1. 📚 Revisión del marco teórico de seguridad de la información y del estándar **ISO/IEC 27001:2022**.
2. 🕵️ Reconstrucción documentada del caso Celebgate: vector de ataque, alcance y cronología.
3. 🏢 Evaluación de la respuesta institucional de Apple ante el incidente.
4. ⚖️ Contraste del caso contra el marco legal de protección de datos vigente (RGPD, LOPD, LSSICE, Ley 1581 de 2012).
5. 🧩 Análisis crítico propio sobre el impacto económico, la transparencia y el rol que debió cumplir la auditoría informática preventiva.
6. ✅ Formulación de recomendaciones y conclusiones.

---

## 📂 Estructura del Proyecto

```
caso-celebgate-auditoria-informatica/
│
├── 📄 Desarrollo_Proyecto_Alejandro_De_Mendoza_Tovar.pdf   # Informe final
├── 📄 README.md
└── 📄 .gitignore
```

---

## 📜 Marco Normativo y Referencias

<div align="center">

![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-004c97?style=for-the-badge)
![RGPD](https://img.shields.io/badge/RGPD-UE-003399?style=for-the-badge)
![LOPD](https://img.shields.io/badge/LOPD-España-c60b1e?style=for-the-badge)
![LSSICE](https://img.shields.io/badge/LSSICE-España-c60b1e?style=for-the-badge)
![Ley 1581](https://img.shields.io/badge/Ley%201581%20de%202012-Colombia-fcd116?style=for-the-badge)

</div>

---

## 👨‍💻 Autor

<div align="center">

**Alejandro De Mendoza**

Laboratorio desarrollado en el marco de la asignatura **Calidad y Auditoría de Sistemas de Información**

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejoTechEngineer)

</div>

---

<div align="center">

### 🔐 *Auditoría informática como herramienta preventiva ante incidentes de seguridad de la información*

</div>
