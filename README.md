# Social Media 10x Faster with AI

Este proyecto es una página web que muestra cómo una herramienta de gestión de redes sociales impulsada por IA puede ayudar a los usuarios a crear, programar y optimizar contenido de manera más eficiente. La página está diseñada con un enfoque en la usabilidad y la presentación visual de las características clave de la herramienta.

## Vista previa

![Vista previa del proyecto](./assets/images/preview.jpg)

## Características

- **Diseño en cuadrícula**: Utiliza un diseño de cuadrícula (`grid`) para organizar los elementos de manera visualmente atractiva.
- **Responsive**: El diseño se adapta a diferentes tamaños de pantalla, desde dispositivos móviles hasta escritorios.
- **Colores y tipografía**: Uso de colores vibrantes y tipografía moderna para resaltar las características principales.
- **Imágenes ilustrativas**: Cada sección incluye imágenes que representan las funcionalidades de la herramienta.

## Estructura del proyecto

- `index.html`: Contiene la estructura HTML de la página.
- `styles.css`: Contiene los estilos CSS para el diseño y la disposición de los elementos.
- `assets/images/`: Carpeta que contiene las imágenes utilizadas en el proyecto.

## Cómo usar

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador para ver la página en acción.

## Estilos

Los estilos están diseñados para ser modernos y atractivos, utilizando una combinación de colores vibrantes y tipografía clara. Se utiliza CSS Grid para la disposición de los elementos, lo que permite un diseño flexible y responsive.

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(7, 1fr);
  gap: 10px;
  padding: 30px;
  max-width: 850px;
  max-height: 700px;
  margin: 0 auto;
}

.grid-item {
  background-color: hsl(0, 0%, 100%);
  padding: 10px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  text-align: center;
}
