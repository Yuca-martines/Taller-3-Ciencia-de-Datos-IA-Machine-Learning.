# 👁️ Visión Artificial - Detección de Rostros en Tiempo Real

Este proyecto implementa un sistema de **detección de rostros en tiempo real** usando Python, Flask y OpenCV. Permite subir imágenes o usar la cámara web para detectar rostros con recuadros delimitadores.

---

## 🚀 Demo en Producción

> 🔗 **Aplicación en vivo:**  
> [![Railway](https://img.shields.io/badge/Railway-App-0B0D0E?logo=railway&logoColor=white)](https://taller-3-ciencia-de-datos-ia-machine-learning-production.up.railway.app/)  
> **https://taller-3-ciencia-de-datos-ia-machine-learning-production.up.railway.app/**

---

## 🛠️ Tech Stack

| Capa | Tecnologías |
|:----:|:-----------:|
| **Backend** | Python, Flask |
| **Visión Computacional** | OpenCV (`opencv-python-headless`) |
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Dependencias** | NumPy |
| **Despliegue** | Railway |

---

## ✨ Características

- 📤 **Subida de imágenes**: Arrastra y suelta o selecciona una imagen para detectar rostros
- 🎥 **Detección en tiempo real**: Usa tu cámara web para detectar rostros en vivo
- 🟩 **Recuadros delimitadores**: Dibuja cajas verdes alrededor de los rostros detectados
- 🔢 **Contador de rostros**: Muestra la cantidad de rostros detectados
- 📱 **Diseño responsivo**: Interfaz adaptable con Bootstrap

---

## 📁 Estructura del Proyecto

```plaintext
Visionartificial/
│
├── python_img_ss/                          # Aplicación Flask principal
│   ├── api/
│   │   └── index.py                       # Servidor Backend (Flask)
│   ├── public/
│   │   ├── index.html                     # Interfaz Frontend
│   │   ├── style.css                      # Estilos responsivos
│   │   └── script.js                      # Lógica del cliente
│   ├── haarcascade_frontalface_default.xml # Clasificador de OpenCV
│   ├── requirements.txt                   # Dependencias Python
│   └── vercel.json                        # Configuración de despliegue
│
├── haarcascade_frontalface_default.xml     # Clasificador de OpenCV
├── images.jpg                             # Imagen de ejemplo
├── index.ipynb                            # Notebook de experimentación
├── py_img.zip                             # Paquete comprimido
└── .gitignore                             # Archivos ignorados por Git
```

---

## ⚙️ Pasos para Ejecutar el Proyecto Localmente

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/Yuca-martines/Taller-3-Ciencia-de-Datos-IA-Machine-Learning..git
cd Visionartificial/python_img_ss
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

Las dependencias incluyen:
- `Flask==3.0.2`
- `opencv-python-headless==4.9.0.80`
- `numpy==1.26.4`

### 5️⃣ Navegar a la carpeta de la API y ejecutar

```bash
cd api
python index.py
```

La aplicación estará disponible en: **http://localhost:5000**

---

## 🐳 Ejecutar con Docker

```bash
cd Visionartificial/python_img_ss
docker build -t visionartificial .
docker run -p 5000:5000 visionartificial
```

---

## 🖥️ Cómo Usar la Aplicación

1. **Inicia el servidor** siguiendo los pasos anteriores
2. **Abre el navegador** y ve a `http://localhost:5000`
3. **Elige tu método de entrada:**
   - 📷 **Subir imagen**: Arrastra una imagen al área de carga o haz clic para buscar
   - 🎥 **Cámara web**: Activa la cámara para detección en tiempo real
4. **Visualiza los resultados** con los rostros marcados y el conteo total

---

## 🌐 Enlace de Despliegue

| Plataforma | URL |
|:----------:|:---:|
| 🚂 Railway | [https://taller-3-ciencia-de-datos-ia-machine-learning-production.up.railway.app/](https://taller-3-ciencia-de-datos-ia-machine-learning-production.up.railway.app/) |

---

<p align="center">
  <strong>👁️ Visión Artificial · Taller 3 - Ciencia de Datos, IA y Machine Learning</strong>
</p>