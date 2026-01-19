# Plantilla de Enlaces de Redes Sociales

Una plantilla simple y personalizable para crear tu propia página de enlaces de redes sociales. Perfecta para compartir todos tus perfiles en un solo lugar.

## Características

- ✨ Diseño moderno y responsivo
- 🎨 Fácil de personalizar
- 📱 Compatible con móviles
- 🎯 Botones interactivos con descripciones
- ⚡ Sin dependencias externas
- 🌙 Tema oscuro predeterminado

## Estructura del proyecto

```
demo-template/
├── src/
│   ├── index.html        # Página principal
│   └── index.css         # Estilos CSS
└── README.md             # Este archivo
```

## Cómo usar

1. **Clona o descarga este repositorio**:
   ```bash
   git clone <url-del-repositorio>
   cd demo-template
   ```

2. **Personaliza el contenido**:
   - Abre `src/index.html` en tu editor de texto
   - Reemplaza "Tu nombre" con tu nombre real
   - Añade la URL de tu foto de perfil en el atributo `src` de la imagen
   - Actualiza cada "Sample Button X" con el nombre de tu red social
   - Cambia los enlaces `href="#"` por tus URLs reales
   - Escribe descripciones personalizadas para cada red

3. **Personaliza los estilos (opcional)**:
   - Abre `src/index.css`
   - Modifica colores, tamaños de fuente, etc. según tus preferencias
   - Los botones tienen un gradiente por defecto que puedes cambiar

4. **Abre en tu navegador**:
   - Haz doble clic en `src/index.html` o abre el archivo en tu navegador

## Personalización de colores

En `index.css` puedes cambiar:
- `background-color: #261436` - Color de fondo de la página
- `color: #e6eef8` - Color del texto
- `background: linear-gradient(...)` - Gradiente de los botones

## Ejemplo de personalización

```html
<!-- Cambiar esto: -->
<a class="social-media-link" href="#" target="_blank" rel="noopener">
    Sample Button 1
</a>

<!-- Por esto: -->
<a class="social-media-link twitter" href="https://twitter.com/tuusuario" target="_blank" rel="noopener">
    Twitter
</a>
```

Y en CSS:
```css
.twitter {
    background-color: #1da1f2; /* Azul de Twitter */
}
```

## Requisitos

Ninguno. Solo necesitas:
- Un navegador web moderno
- Un editor de texto
- Una conexión a internet (para acceder a Google Fonts)

## Licencia

Libre para usar y modificar como desees.

## ¿Necesitas ayuda?

Si encuentras problemas, verifica:
1. Que los enlaces sean correctos (comenzar con `https://`)
2. Que la ruta de la imagen sea válida
3. Que el archivo `index.css` esté en la misma carpeta que `index.html`

¡Diviértete personalizando tu página! 🎉

