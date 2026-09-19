# 📈 Regresión Lineal - Predicción de Precios de Vivienda

Este proyecto implementa un modelo de **Regresión Lineal** para predecir precios de vivienda. Cuenta con una arquitectura completa de **Frontend** (interfaz web) y **Backend** (API REST), ambos desplegados en Railway.

---

## 🚀 Demo en Producción

| Componente | URL |
|:----------:|:---:|
| 🎨 **Frontend** | [![Railway](https://img.shields.io/badge/Railway-Frontend-0B0D0E?logo=railway&logoColor=white)](https://precious-peace-a.up.railway.app/) [https://precious-peace-a.up.railway.app/](https://precious-peace-a.up.railway.app/) |
| ⚙️ **Backend (API)** | [![Railway](https://img.shields.io/badge/Railway-Backend-0B0D0E?logo=railway&logoColor=white)](https://prediccionvivienda-a.up.railway.app/) [https://prediccionvivienda-a.up.railway.app/](https://prediccionvivienda-a.up.railway.app/) |

---

## 🛠️ Tech Stack

| Capa | Tecnologías |
|:----:|:-----------:|
| **Backend** | Python, Django, scikit-learn |
| **Frontend** | HTML, CSS, JavaScript |
| **Modelo ML** | LinearRegression (scikit-learn) |
| **Despliegue** | Railway |

---

## 📁 Estructura del Proyecto

```plaintext
RegresionLineal/
│
├── back/                    # Backend (API Django)
│   ├── Dockerfile           # Contenedor Docker del backend
│   ├── main.py              # Punto de entrada principal
│   ├── train.py             # Entrenamiento del modelo
│   ├── models/              # Modelos entrenados guardados
│   └── requirements.txt     # Dependencias Python
│
└── front/                   # Frontend (Django App)
    ├── Dockerfile           # Contenedor Docker del frontend
    ├── manage.py            # Gestor de Django
    ├── db.sqlite3           # Base de datos SQLite
    ├── app_prediccion/      # Aplicación principal Django
    ├── config/              # Configuración del proyecto
    └── requirements.txt     # Dependencias Python
```

---

## ⚙️ Pasos para Ejecutar el Backend Localmente

### 1️⃣ Navegar a la carpeta del Backend

```bash
cd RegresionLineal/back
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

### 5️⃣ Entrenar el modelo

```bash
python train.py
```

### 6️⃣ Iniciar el servidor Backend

```bash
python main.py
```

API disponible en: **http://localhost:8000**

---

## ⚙️ Pasos para Ejecutar el Frontend Localmente

### 1️⃣ Navegar a la carpeta del Frontend

```bash
cd RegresionLineal/front
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

### 5️⃣ Aplicar migraciones de base de datos

```bash
python manage.py migrate
```

### 6️⃣ Ejecutar el servidor de desarrollo

```bash
python manage.py runserver
```

Frontend disponible en: **http://localhost:8000**

---

## 🐳 Ejecutar con Docker

### Backend

```bash
cd RegresionLineal/back
docker build -t prediccion-back .
docker run -p 8000:8000 prediccion-back
```

### Frontend

```bash
cd RegresionLineal/front
docker build -t prediccion-front .
docker run -p 8001:8000 prediccion-front
```

---

## 🌐 Enlaces de Despliegue

| Servicio | URL |
|:--------:|:---:|
| 🎨 Frontend | [https://precious-peace-a.up.railway.app/](https://precious-peace-a.up.railway.app/) |
| ⚙️ Backend | [https://prediccionvivienda-a.up.railway.app/](https://prediccionvivienda-a.up.railway.app/) |

---

<p align="center">
  <strong>📈 Regresión Lineal · Taller 3 - Ciencia de Datos, IA y Machine Learning</strong>
</p>
