# Extracción de Datos de Jurisprudencia con Selenium

Este proyecto utiliza Selenium para automatizar la extracción de datos de la página web de jurisprudencia del Poder Judicial de Perú. Los datos extraídos se guardan en un archivo CSV.

## Requisitos

### 1. Python y pip

Asegúrate de tener Python 3 y `pip` instalados en tu sistema.

### 2. Google Chrome y ChromeDriver

#### Linux:
1. Instala Google Chrome:

   ```bash
   wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
   sudo apt install ./google-chrome-stable_current_amd64.deb

2. **Instala las dependencias adicionales:**

   En Linux, es posible que necesites instalar algunos paquetes adicionales para que Google Chrome funcione correctamente en un entorno sin interfaz gráfica. Puedes hacerlo con los siguientes comandos:

   ```bash
   sudo apt-get update
   sudo apt-get install -y xvfb libnss3 libgconf-2-4
