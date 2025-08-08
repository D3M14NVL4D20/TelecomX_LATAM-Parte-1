
# 📊 Análisis de Churn de Clientes - Proyecto de Ciencia de Datos

Este proyecto tiene como objetivo analizar los datos de una tienda con el fin de identificar el comportamiento de abandono (churn) por parte de los clientes. A través de la exploración, limpieza y visualización de datos, se busca obtener **insights valiosos** para tomar decisiones estratégicas que ayuden a retener clientes.

---

## 📁 Estructura del Proyecto

```
📦 churn_analysis_project/
├── 📊 churn_analysis.ipynb        # Notebook principal del análisis
├── 📄 README.md                   # Este archivo
├── 🧾 data/
│   └── customers.json            # Archivo original con los datos de clientes
├── 📈 images/
│   ├── churn_barplot.png         # Gráfica de distribución de churn
│   └── otras_graficas.png        # Otras visualizaciones generadas
└── requirements.txt              # (Opcional) Librerías necesarias
```

---

## 📌 Ejemplos de Gráficos e Insights Obtenidos

### 1. Distribución de Churn (Abandono de Clientes)

![Distribución de Churn](images/churn_barplot.png)

🔍 **Insight:** La mayoría de los clientes **no abandonaron** el servicio, pero existe una proporción significativa de abandono (churn) que requiere atención.

### 2. Análisis de correlación entre características

Se exploraron variables como:

- `gender`, `Partner`, `Dependents`, `SeniorCitizen`
- `tenure` (antigüedad), `Charges.Total` (costo total)

Esto permitió detectar **factores comunes entre los clientes que abandonan**.

---

## ⚙️ Instrucciones para Ejecutar el Notebook

1. **Clona este repositorio** o descarga los archivos manualmente.
   ```bash
   git clone https://github.com/tu_usuario/churn_analysis_project.git
   ```

2. **Instala las dependencias necesarias**:
   Puedes usar un entorno virtual o tu ambiente base de Python.
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Ejecuta el notebook**:
   ```bash
   jupyter notebook churn_analysis.ipynb
   ```

4. Explora paso a paso el análisis, visualizaciones y resultados.

---

## ✅ Requisitos

- Python 3.8 o superior
- Librerías:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `jupyter`

Puedes instalar todas las dependencias con:
```bash
pip install -r requirements.txt
```

---

## 📬 Contacto

Si tienes dudas o sugerencias, puedes contactarme a través de [tu_email@ejemplo.com] o en [tuGitHub].
