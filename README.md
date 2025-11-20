# Proyecto Final - Programación y Decisiones  
Autores: Juan Pachecho, Mateo Morales, Juan Camacho
Tercer corte

## Objetivo  
Analizar la relación entre desempeño financiero de empresas, empleo regional y exportaciones no minero-energéticas en Colombia.  
Se construye un pipeline reproducible de datos públicos → limpieza → modelado → dashboard gerencial para obtener insights estratégicos.

## Fuentes de datos (100 % públicas)  
- Superintendencia de Sociedades – Reportes masivos de empresas.  
- DANE – Microdatos GEIH (empleo y características regionales).  
- Datos Abiertos Colombia – Exportaciones No Minero-Energéticas (NME).  

## Estructura del repositorio  
├── data/
│ └── clean/
│ ├── finanzas_clean.csv
│ ├── empleo_clean.csv
│ └── exportaciones_clean.csv
├── notebooks/
│ └── Taller_Final_Programacion_Python.ipynb
├── powerbi/
│ └── instrucciones_powerbi.txt
└── README.md


## Cómo reproducir  
1. Clonar el repositorio.  
2. Ejecutar el notebook 
   - Descarga los datos oficiales, aplica limpieza automática y guarda los CSV 
3. Abrir Power BI 
4. Importar los 3 CSV limpios 

## Resultados esperados  
- Notebook con limpieza documentada, comentarios justificativos y exportación de datasets listos para análisis.  
- Dashboard de 2 páginas:  
  - Página 1: KPIs, tendencias, visuales correlacionales.  
  - Página 2: Conclusiones



