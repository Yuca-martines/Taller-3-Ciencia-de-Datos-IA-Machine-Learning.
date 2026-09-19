# 🌲 Random Forest - Sistema de Diagnóstico de Enfermedades

Este proyecto implementa un modelo de **Random Forest** para predecir y diagnosticar enfermedades basándose en síntomas del paciente. Incluye la creación del dataset, entrenamiento del modelo y una interfaz web interactiva desplegada en Streamlit.

---

## 🚀 Demo en Producción

> 🔗 **Aplicación en vivo:**  
> [![Streamlit App](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit&logoColor=white)](https://sistemadiagnostico-rd2acca5hlkm5cogxae85f.streamlit.app/)  
> **https://sistemadiagnostico-rd2acca5hlkm5cogxae85f.streamlit.app/**

---

## 🛠️ Tech Stack

- **Lenguaje:** Python 3.x
- **Modelo:** Scikit-learn (RandomForestClassifier)
- **Interfaz:** Streamlit
- **Datos:** Dataset generado sintéticamente con síntomas y enfermedades

---

## 📁 Estructura del Proyecto

```plaintext
RandomForest/
│
├── 1.Crear_dataset.py       # Genera el dataset de síntomas y enfermedades
├── 2.Entrenar_modelo.py     # Entrena el modelo Random Forest
├── 3.Predecir_enfermedad.py # App Streamlit para predicción interactiva
├── data/                    # Carpeta con los datasets generados
├── models/                  # Carpeta donde se guarda el modelo entrenado
└── requirements.txt         # Dependencias del proyecto
```

---

## ⚙️ Pasos para Ejecutar el Proyecto Localmente

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/Yuca-martines/Taller-3-Ciencia-de-Datos-IA-Machine-Learning..git
cd RandomForest
```

### 2️⃣ Crear entorno virtual

```bash
python -m venv venv
```

### 3️⃣ Activar el entorno virtual

**Windows:**
```bash
venv\Scripts\activate
```

**Linux / Mac:**
```bash
source venv/bin/activate
```

### 4️⃣ Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 5️⃣ Crear el dataset

```bash
python 1.Crear_dataset.py
```

### 6️⃣ Entrenar el modelo

```bash
python 2.Entrenar_modelo.py
```

### 7️⃣ Ejecutar la aplicación en local

```bash
streamlit run 3.Predecir_enfermedad.py
```

La aplicación estará disponible en: **http://localhost:8501**

---

## 🌐 Enlace de Despliegue

| Plataforma | URL |
|:----------:|:---:|
| 🟢 Streamlit Cloud | [https://sistemadiagnostico-rd2acca5hlkm5cogxae85f.streamlit.app/](https://sistemadiagnostico-rd2acca5hlkm5cogxae85f.streamlit.app/) |

---

## 📦 Dependencias

```
scikit-learn
pandas
numpy
streamlit
joblib
```

---

<p align="center">
  <strong>🌲 Random Forest · Taller 3 - Ciencia de Datos, IA y Machine Learning</strong>
</p>