# telecom-analysis-academic_project

# ConnectaTel Customer Usage Analysis – Sprint 7

Este repositorio contiene el análisis exploratorio y la limpieza de datos realizados para ConnectaTel, una empresa de telecomunicaciones que busca comprender los patrones de uso de sus clientes y optimizar su oferta de planes.

El dataset incluye información demográfica y de consumo de aproximadamente 4.000 usuarios, incluyendo edad, tipo de plan, llamadas realizadas, mensajes enviados y duración de llamadas. Durante el análisis se abordaron problemas de calidad de datos como valores faltantes, detección de outliers y construcción de segmentos de clientes.

## 📂 Contenido del repositorio

- `notebooks/connectatel_analysis.ipynb`
  → Notebook principal con limpieza de datos, análisis exploratorio (EDA), segmentación de clientes, detección de outliers y recomendaciones de negocio.

- `data/`
  → Archivos fuente utilizados para el análisis.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/github/danypd0996-pixel/telecom-analysis-academic_project/blob/main/Project-ConnectaTel.ipynb)](URL_DEL_NOTEBOOK_EN_GITHUB](https://colab.research.google.com/github/danypd0996-pixel/telecom-analysis-academic_project/blob/main/Project-ConnectaTel.ipynb#scrollTo=9fbb1a91))

O:

1. Abre el archivo `.ipynb` en GitHub.
2. Haz clic en **Open in Colab**.

---

## 📘 Cómo reproducir el análisis

1. Clona este repositorio:

```bash
git clone https://github.com/danypd0996-pixel/telecom-analysis-academic_project/blob/main/Project-ConnectaTel.ipynb
```

2. Instala las dependencias:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Abre el notebook:

```bash
jupyter notebook
```

4. Ejecuta las celdas en orden para reproducir el análisis completo.

---

## 🧠 Objetivo del análisis

- Evaluar la calidad de los datos.
- Identificar y tratar valores faltantes.
- Analizar patrones de uso de llamadas y mensajes.
- Detectar valores atípicos (outliers).
- Segmentar clientes según edad y nivel de uso.
- Generar recomendaciones para optimizar los planes ofrecidos por ConnectaTel.

---

## 🛠 Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab
