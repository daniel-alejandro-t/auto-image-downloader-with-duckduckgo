# Web Scraping de Imágenes con DuckDuckGo 📸🗺️

Este repositorio contiene un script de Python para hacer web scraping de imágenes turísticas de cantones desde DuckDuckGo utilizando Selenium y almacenarlas en su sistema local.

## Tabla de Contenidos 📋

- [Requisitos](#requisitos-)
- [Instalación](#instalación-)
- [Uso](#uso-)
- [Cómo Contribuir](#cómo-contribuir-)
- [Licencia](#licencia-)

## Requisitos 🛠️

- Python 3.x
- Selenium WebDriver
- Firefox
- Geckodriver
- Otros paquetes Python (`requests`, `bs4`, `unidecode`)

## Instalación 📥

1. **Clonar el repositorio**

    ```bash
    git clone https://github.com/daniel-alejandro-t/auto-image-downloader-with-duckduckgo.git
    ```

2. **Instalar Python**

    - Descargar e instalar Python desde el [sitio oficial](https://www.python.org/).

3. **Instalar paquetes necesarios**

    ```bash
    pip install selenium requests beautifulsoup4 unidecode
    ```

4. **Instalar Firefox**

    - Descargar e instalar desde el [sitio oficial](https://www.mozilla.org/en-US/firefox/new/).

5. **Instalar Geckodriver**

    Para Linux, descarga el ejecutable y muevalo:

    ```bash
    sudo mv geckodriver /usr/local/bin/
    ```

    Para otras sistemas operativos, consulte la [documentación oficial](https://github.com/mozilla/geckodriver).

## Uso 🚀

1. **Configurar el CSV**

    Asegúrese de tener un archivo CSV (`cantones.csv`) con las provincias y cantones que desea buscar.

2. **Ejecutar el Jupyter-Notebook**

3. **Verificar las imágenes**

    Las imágenes descargadas se guardarán en el directorio `tmp/images`.

## Cómo Contribuir 🤝

1. Haga un Fork del proyecto.
2. Cree una nueva rama con `git checkout -b feature/AmazingFeature`.
3. Haga Commit de sus cambios con `git commit -m 'Add some AmazingFeature'`.
4. Suba la rama con `git push origin feature/AmazingFeature`.
5. Abra un Pull Request.

## Licencia 📝

Haz lo que quieras con el.

---

Gracias por usar o contribuir a este proyecto! 😊
