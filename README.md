# Trabajo Práctico: Organización Empresarial - UTN 2026

## 👥 Integrantes del Equipo
* **Hugo (P1)** - Líder de Proyecto / Gestión de Configuración
* **Paco (P2)** - Desarrollar / Analista de Datos
* **Luis (P3)** - Aseguramiento de la Calidad (QA) / Documentación

---

## 📋 Descripción del Proyecto
Este repositorio contiene el desarrollo del **Escenario B – Análisis de Ventas de una Pequeña Empresa**. El objetivo principal es procesar un conjunto de datos comerciales estructurados para extraer indicadores financieros clave y automatizar la generación de gráficos analíticos que faciliten la toma de decisiones estratégicas.

### 📊 Indicadores Calculados
1. **Ventas Totales**: Cálculo del volumen bruto de ingresos mediante la sumatoria del producto entre cantidades y precios unitarios.
2. **Producto Líder**: Identificación del artículo con mayor demanda volumétrica en el mercado.
3. **Evolución Mensual**: Agrupación cronológica de la facturación para detectar tendencias comerciales.

---

## 📂 Estructura del Repositorio
Para garantizar el cumplimiento de las buenas prácticas de desarrollo y arquitectura de software, el proyecto se organiza de la siguiente manera:

```text
TP-II-PEREZ/
│
├── datos/
│   └── ventas_originales.csv    # Dataset estructurado (Open Data)
│
├── scripts/
│   └── analisis_datos.py        # Algoritmo en Python con rutas relativas
│
├── resultados/
│   └── evolucion_ventas.png     # Gráfico de tendencias exportado en alta resolución
│
├── .gitignore                   # Exclusión de archivos temporales del sistema
└── README.md                    # Manual técnico del proyecto (Este archivo)
```

---

## 🛠️ Tecnologías y Librerías Utilizadas
El entorno de ejecución requiere **Python** y las siguientes herramientas de análisis de datos:
* **`os`**: Gestión de rutas relativas e interoperabilidad del sistema operativo.
* **`pandas`**: Procesamiento matricial, limpieza y agrupación de datos estructurados.
* **`matplotlib`**: Automatización y diseño del componente gráfico analítico.

---

## 🚀 Instrucciones de Ejecución (Reproducibilidad)

Siga estos pasos para ejecutar el entorno de forma local en su terminal:

1. **Clonar el repositorio** (Reemplace con su credencial segura si es necesario):
   ```bash
   git clone https://github.com
   ```

2. **Acceder al directorio del proyecto**:
   ```bash
   cd TP-II-PEREZ
   ```

3. **Instalar las dependencias obligatorias**:
   ```bash
   pip install pandas matplotlib
   ```

4. **Ejecutar el script analítico**:
   ```bash
   python scripts/analisis_datos.py
   ```
