FROM python:3.11-slim

# Instala las dependencias de Python
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copia tu código al contenedor
COPY . /app
WORKDIR /app

# Asegúrate de que el script sea ejecutable (si es necesario)
# RUN chmod +x tu_script.py

# Comando para ejecutar tu aplicación (ajusta según tu caso)
CMD ["python", "######.py"]