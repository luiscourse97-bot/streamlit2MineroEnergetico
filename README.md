# ⚡ Dashboard Sector Minero Energético Colombia

> Panel de control interactivo para el análisis de proyectos energéticos y mineros en Colombia.

<p align="center">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
</p>

<p align="center">
  <strong>Desarrollado por 
    <a href="https://github.com/FeibertGuzman/streamlit2.git">Feibert Guzmán</a>
  </strong>
</p>

---


## 🌐 La app estará disponible en: http://localhost:8501
### 📊 Módulos del Dashboard
Módulo
Descripción
## 🏠 Inicio
KPIs generales, distribución energética y fuentes de inversión
## 🏗️ Proyectos
Listado y detalles de proyectos por ubicación y tipo de energía
## 📉 Eficiencia
Series temporales de generación, costos e indicadores económicos
## 💰 Inversiones
Análisis de montos y fuentes de financiamiento
## 🏢 Empresas
Actores del ecosistema y su participación por proyecto
## 🗄️ Esquema de Datos

### 📦 SectorMineroEnergeticoColombia.db
 ├── tipos_energia          # Catálogo: Solar, Eólica, H2, Biomasa, Geotérmica
 ├── proyectos              # 5 proyectos piloto con metadata geoespacial
 ├── eficiencia_energetica  # 50 registros diarios: kWh, costos, KPIs
 ├── inversiones            # Fuentes: Gobierno, Privado, ONG
 ├── empresas               # Operadores por proyecto
 ├── comunidades_energeticas # Beneficiarios locales
 ├── minerales              # Recursos estratégicos asociados
 ├── estu

## 🛠️ Stack Tecnológico
Frontend: Streamlit + Plotly (visualizaciones interactivas)
Backend: Python 3.8+ + SQLite3
Data Engineering: Pandas para ETL y análisis
Estilo: CSS personalizado para UI profesional y responsive

## 📁 Estructura del Proyecto

sector_minero_energy/
├── app.py                   # Dashboard principal
├── init_db.py               # Script de inicialización de datos
├── requirements.txt         # Dependencias Python
├── README.md                # Este archivo
└── SectorMineroEnergeticoColombia.sql  # Script SQL original

## ⚡ Notas Técnicas

-> Los datos en init_db.py están sanitizados para corregir inconsistencias del dump SQL original (espacios en números, fechas mal formadas).
La conexión a la BD usa @st.cache_data para optimizar rendimiento.
Diseño mobile-first: compatible con escritorio y dispositivos móviles.
<p align="center">
<sub>© 2024 • Dashboard Sector Minero Energético Colombia •
<a href="https://github.com/FeibertGuzman/streamlit2.git">GitHub Repo</a></sub>
</p>

