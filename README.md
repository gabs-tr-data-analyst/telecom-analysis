# 📱 Análisis ConnectaTel

ConnectaTel es una empresa de telecomunicaciones con operaciones en México 
y Colombia. Este análisis busca entender cómo los clientes usan realmente 
los servicios móviles (llamadas y mensajes) a partir de datos registrados 
hasta el año 2024.

## 🎯 Objetivo
Identificar patrones de uso, detectar comportamientos atípicos y comprender 
qué segmentos de clientes muestran necesidades diferenciadas, con el fin de 
optimizar la oferta comercial y mejorar la experiencia del usuario.

## 📁 Estructura del proyecto
proyecto/
├── data/
│   ├── users.csv
│   ├── usage.csv
│   └── plans.csv
├── notebook.ipynb
└── README.md

## 📋 Descripción del dataset
| Dataset | Descripción |
|---|---|
| `users` | Información demográfica y fecha de registro a planes |
| `usage` | Registro de mensajes, llamadas y minutos |
| `plans` | Tipos de planes disponibles |

## 🔍 Análisis realizado
- Exploración y limpieza de datos
- Imputación de valores nulos y tratamiento de outliers
- Creación de variables nuevas (`grupo_uso`, `grupo_edad`)
- Análisis de distribuciones por tipo de plan y segmento

## 🛠️ Tecnologías usadas
- Python 3.x
- Pandas
- Seaborn / Matplotlib
- NumPy

## ▶️ Cómo ejecutar el proyecto
1. Abre el notebook directamente en Google Colab
2. Ve a `Archivo > Abrir notebook > GitHub`
3. Pega la URL del repositorio y selecciona `analisis_connectatel.ipynb`

## 📌 Conclusiones
La base de usuarios está dominada por adultos y adultos mayores, por ende 
el segmento joven representa una oportunidad de crecimiento sin explotar. 
El grueso de usuarios se concentra en uso medio con plan básico, lo que 
indica un potencial real de upselling hacia planes superiores. Se recomienda 
diseñar campañas con AB testing en redes sociales para captar al segmento 
joven, mientras que Facebook resulta el canal más efectivo para impulsar 
la migración a planes premium entre adultos mayores de alto uso.

> 📒 Para el análisis detallado por segmento, hallazgos y visualizaciones, 
> consulta el notebook completo.
