# 🚀 TaskFlow

## ⚙️ Instrucciones de Instalación y Ejecución

**1. Clonar el repositorio**
Descarga el código fuente e ingresa a la carpeta del proyecto:
```bash
git clone [https://github.com/tu-usuario/proyecto_backend.git](https://github.com/tu-usuario/proyecto_backend.git)
cd proyecto_backend
```

**2. Crear el entorno virtual**
Genera un entorno aislado para manejar las dependencias sin afectar tu sistema:
```bash
python -m venv ambvirt
```

**3. Activar el entorno virtual**
Habilita el entorno recién creado:
```bash
ambvirt\Scripts\activate
```

**4. Instalar dependencias**
Instala Django y el resto de librerías exactas utilizadas en el desarrollo:
```bash
pip install -r requirements.txt
```

**5. Ejecutar el servidor local**
Ingresa a la carpeta principal de la aplicación y arranca el servidor de desarrollo:
```bash
cd ttrello
python manage.py runserver
```
*(El proyecto estará disponible en http://127.0.0.1:8000/)*