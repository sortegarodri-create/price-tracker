#Smart Price Tracker (Proyecto de Fin de Semana)

Este proyecto tiene como objetivo aprender los fundamenteos de extracción de datos, automatización y control de versiones

## Objetivo
El objetivo es monitorear el precio de un producto específico en tiempo real y recibir una notificación automática via correo electrónico cuando baje de un umbral determinado.

## Tecnologías utilizadas
Lenguaje: Python 3.x
Librerías:
    * `Requests`: Para realizar peticiones HTTP a la web.
    * `BeautifulSoup4`: Para el web scraping y parseo del HTML.
    * `smtplib`: Para el envío de notificaciones por email.
    
Herramientas:** VS Code, Git, GitHub.

## 📋 Plan de Desarrollo (3 Días) (SOLO TEMPORAL, PARA SABER LO QUE TENGO QUE HACER CADA DÍA)

### Día 1: Extracción de Datos (Scraping)
- [ ] Configuración del entorno virtual (`venv`).
- [ ] Implementación de la petición HTTP con `User-Agent`.
- [ ] Localización de etiquetas HTML (ID/Class) para extraer precio y título.

### Día 2: Lógica y Notificaciones
- [ ] Limpieza de datos (conversión de texto a `float`).
- [ ] Configuración del servidor SMTP para el envío de correos.
- [ ] Lógica de comparación de precios.

### Día 3: Automatización y Refuerzo
- [ ] Implementación de un bucle de tiempo (`time.sleep`).
- [ ] Documentación final y subida del código a GitHub.

## ⚙️ Cómo ejecutarlo
1. Clona el repositorio: `git clone https://github.com/TU_USUARIO/nombre-repo.git`
2. Crea un entorno virtual e instala las dependencias:
   ```bash
   pip install requests beautifulsoup4
