# 📊 Dashboard Inventario Rotativo - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a SQL Server, orientado al análisis de indicadores y herramientas enfocadas a la Distribución y Almacen en entornos industriales.


---

## 📌 Objetivo

Clarificar y establecer las directrices para el uso adecuado del tablero de PowerBI “Inventario Rotativo” con el fin de garantizar una visualización clara, oportuna y confiable de los datos para contribuir a una toma de decisiones basada en información precisa y actualizada que contribuya a la mejora continua de los procesos logísticos.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- SQL Server (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
PowerBI-OEE-Coflex/
├── pbix/                                   → Archivo PBIX del tablero
├── docs/
│   ├── README.md                                           → Descripción general del repositorio
│   ├── Medidas.md                                          → Medidas DAX documentadas
│   ├── Columnas_Calculadas.md                              → DAX documentadas
│   ├── Tablas_Catalogo.md                                  → DAX documentadas
│   ├── Instructivo Dashboard Inventario Rotativo.docx      → Guía de uso del dashboard
├── sql/ 
│   └── consulta_fuente_OEE.sql             → Consulta SQL base
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   └── modelo_datos.png                    → Relación entre tablas
└── LICENSE                                 → MIT (u otra que se defina)
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/Inventario Rotativo.pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server y Excel.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

---

## 📄 Licencia

MIT – Libre uso con atribución.

