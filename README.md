# Click-to-Call Web Component

Este repositorio contiene un Web Component para realizar llamadas SIP a través de un botón interactivo. El componente permite personalizar el color del botón, el texto, el radio del borde y el color del mensaje de estado.

## Instalación

Para usar este Web Component, puedes incluirlo directamente desde GitHub Pages en tu proyecto HTML.

### Pasos:

1. Clona el repositorio:

   ```sh
   git clone https://github.com/tu-usuario/click-to-call-component.git
   ```

2. Navega al directorio del repositorio:

   ```sh
   cd click-to-call-component
   ```

3. Sube los archivos al repositorio y empújalos a GitHub:

   ```sh
   git add .
   git commit -m "Add click-to-call Web Component"
   git push origin main
   ```

4. Configura GitHub Pages en la sección `Settings` de tu repositorio y obtén la URL generada.

## Uso

Para incluir el Web Component en tu página web, sigue estos pasos:

1. Incluye los siguientes scripts en tu archivo HTML:

   ```html
   <script src="https://code.jquery.com/jquery-2.1.4.min.js"></script>
   <script src="https://sipml5.org/downloads/sipml5.js"></script>
   <script src="https://tu-usuario.github.io/click-to-call-component/click-to-call.js"></script>
   ```

2. Usa el componente en tu HTML:
   ```html
   <click-to-call
     button-color="#4CAF50"
     button-text-color="#FFFFFF"
     status-text-color="#FF0000"
     button-border-radius="10px"
     button-text="Llamar Ahora">
   </click-to-call>
   ```

### Ejemplo completo:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Click to call</title>
    <link rel="stylesheet" href="https://code.jquery.com/jquery-2.1.4.min.js" />
    <script src="https://sipml5.org/downloads/sipml5.js"></script>
    <script src="https://tu-usuario.github.io/click-to-call-component/click-to-call.js"></script>
    <!-- URL del CDN -->
  </head>
  <body>
    <click-to-call
      button-color="#4CAF50"
      button-text-color="#FFFFFF"
      status-text-color="#FF0000"
      button-border-radius="10px"
      button-text="Llamar Ahora">
    </click-to-call>
  </body>
</html>
```

## Personalización

El componente permite varias opciones de personalización a través de atributos:

- `button-color`: Cambia el color de fondo del botón.
- `button-text-color`: Cambia el color del texto del botón.
- `status-text-color`: Cambia el color del texto del mensaje de estado.
- `button-border-radius`: Cambia el radio del borde del botón.
- `button-text`: Cambia el texto que aparece en el botón.

## Contribución

Si deseas contribuir a este proyecto, por favor haz un fork del repositorio y envía un pull request con tus mejoras.

## Licencia

Este proyecto está bajo la licencia MIT.

````

### Instrucciones adicionales

1. **Reemplaza `tu-usuario`**: Asegúrate de reemplazar `tu-usuario` con tu nombre de usuario de GitHub en la URL del repositorio y en el script de GitHub Pages.
2. **Sube el archivo `README.md`**: Añade el archivo `README.md` a tu repositorio, confírmalo y empújalo a GitHub:
   ```sh
   git add README.md
   git commit -m "Add README file"
   git push origin main
````

Con este archivo `README.md`, los usuarios podrán entender fácilmente cómo instalar y usar el Web Component en sus propios proyectos.
