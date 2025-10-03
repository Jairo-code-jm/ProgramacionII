# Proyecto de Análisis Económico

Este proyecto analiza datos económicos (PIB) descargados desde la API del Banco Mundial y genera gráficas comparativas entre países para observar su crecimiento y estabilidad económica a lo largo del tiempo.

---

## 📂 Archivos del repositorio
- `main.ipynb` → Notebook principal con el código.
- `requirements.txt` → Dependencias necesarias para ejecutar el proyecto.

---

## 🚀 Ejecución en Google Colab
1. Abre este repositorio en GitHub.
2. Haz clic en el archivo `main.ipynb`.
3. En la parte superior, selecciona **"Open in Colab"**.
4. Una vez en Colab, instala las librerías necesarias ejecutando:

```python
!pip install -r requirements.txt
```

---

## 💻 Ejecución en local
1. Clona el repositorio:
   ```bash
   git clone https://github.com/USUARIO/REPO.git
   cd REPO
   ```
2. Crea un entorno virtual (opcional, recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/Mac
   venv\Scripts\activate     # En Windows
   ```
3. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Abre el notebook:
   ```bash
   jupyter notebook main.ipynb
   ```

---

## 📊 Librerías utilizadas
- **requests**: Para obtener datos desde APIs.
- **pandas**: Para manipular y limpiar datos en forma de tablas.
- **numpy**: Para cálculos numéricos (máximos, mínimos, medias, etc).
- **matplotlib**: Para generar gráficos del crecimiento económico.
- **IPython.display**: Para mostrar DataFrames de manera ordenada en el notebook.

---

## ✅ Requisitos
- Python 3.9 o superior.
- Conexión a internet (para acceder a la API del Banco Mundial).
