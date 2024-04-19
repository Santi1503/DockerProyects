# Usa una imagen base de Python
FROM python:3.9-slim

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia los archivos necesarios al contenedor
COPY connect4.py .

# Instala las dependencias si es que no has instalado los requirements.txt
RUN pip install numpy scipy

# Define el comando por defecto para ejecutar tu aplicación
CMD ["python", "connect4.py"]
