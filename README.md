# 📌 Proyecto: Galería Filtrada

## 🚀 Descripción
Este proyecto es una galería de imágenes filtrada, desarrollada con **HTML, CSS y JavaScript**, utilizando **Parcel** como bundler para facilitar el desarrollo y la optimización.

## 📂 Estructura del Proyecto
```
/galeria-filtrada
├── src/
│   ├── index.html      # Archivo HTML principal
│   ├── css/
│   │   └── styles.css  # Archivo CSS
│   ├── js/
│   │   └── script.js   # Archivo JavaScript
│   ├── img/            # Carpeta de imágenes
├── dist/               # Archivos optimizados (se genera con `npm run build`)
├── node_modules/       # Dependencias (NO modificar)
├── .parcel-cache/      # Caché de Parcel (se puede eliminar)
├── package.json        # Configuración del proyecto
├── .gitignore          # Archivos y carpetas a ignorar en Git
└── README.md           # Documentación del proyecto
```

## 📦 Instalación
1. Clona el repositorio:
   ```sh
   git clone https://github.com/tu-usuario/galeria-filtrada.git
   cd galeria-filtrada
   ```
2. Instala las dependencias:
   ```sh
   npm install
   ```

## 🚀 Uso
### Modo Desarrollo
Ejecuta el siguiente comando para iniciar el servidor en modo desarrollo con recarga en vivo:
```sh
npm start
```
El proyecto se abrirá automáticamente en `http://localhost:3000`.

### Generar versión optimizada para producción
```sh
npm run build
```
Los archivos optimizados se guardarán en la carpeta `dist/`.

### Limpiar archivos generados
```sh
npm run clean
```
Elimina la carpeta `dist/` y la caché de Parcel.

### Formatear código
```sh
npm run format
```
Aplica **Prettier** a los archivos HTML, SCSS y JS dentro de `src/`.

## 🛠 Tecnologías Utilizadas
- **Parcel** (bundler moderno)
- **HTML5, CSS3, JavaScript**
- **Prettier** (formateador de código)

## 📜 Licencia
Este proyecto está bajo la licencia MIT. ¡Siéntete libre de usarlo y modificarlo! 🚀

