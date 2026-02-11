# Prompts para Construir el Sitio Web "Zapatos Urbanos"

Este documento contiene todos los prompts necesarios para reconstruir este sitio web desde cero.

---

## 1. Crear la Estructura Inicial

### Prompt:
```
Crea una página web HTML básica con la siguiente estructura:
- Encabezado (header) con el título "Zapatos Urbanos"
- Sección principal (main) con un título "Hola mundo" y un párrafo descriptivo
- Pie de página (footer) con copyright "© 2026 - Mi sitio web"
- Meta charset UTF-8
- Idioma en español (lang="es")
```

---

## 2. Crear Hoja de Estilos

### Prompt:
```
Crea una hoja de estilos CSS y vincula la al index.html
```

---

## 3. Mejorar Estilos con Bootstrap

### Prompt:
```
Mejora los estilos para que usen bootstrap y sea responsive y adaptativo y deja los estilos en una carpeta separada
```

**Resultado esperado:**
- Carpeta `css/` creada
- Archivo `css/styles.css` con estilos mejorados
- Bootstrap CDN integrado en el HTML
- Meta viewport agregado para responsividad

---

## 4. Agregar Imagen

### Prompt:
```
Agrega una imagen de un zapato acorde a la página web, agrega la imagen a una carpeta nueva y conectala al index
```

**Resultado esperado:**
- Carpeta `images/` creada
- Imagen de zapato en formato SVG
- Imagen conectada en el index.html de forma responsive

---

## 5. Agregar Múltiples Secciones (Opcional)

### Prompt:
```
Agrega una segunda sección al main con un título "Catálogo" y descripción "Ideales para el día a día", incluyendo una imagen de zapatos adicional. Mantén el diseño responsive con Bootstrap.
```

---

## Comandos Git

### Crear rama develop:
```bash
git checkout -b develop
git push origin develop
```

### Subir cambios a develop:
```bash
git add .
git commit -m "Descripción del cambio"
git push origin develop
```

### Subir cambios a main:
```bash
git add .
git commit -m "Descripción del cambio"
git push origin main
```

---

## Estructura de Carpetas Final

```
pagina_web/
├── index.html
├── README.md
├── PROMPTS_CONSTRUCCION.md
├── css/
│   └── styles.css
└── images/
    ├── zapatos.jpg
    └── zapatos 2.jpg
```

---

## Características Implementadas

✅ HTML semántico en español
✅ Bootstrap 5 para responsividad
✅ Estilos personalizados en carpeta separada
✅ Imágenes en carpeta dedicada
✅ Diseño responsive (mobile, tablet, desktop)
✅ Gradientes y efectos visuales
✅ Sombras y transiciones
✅ Meta viewport para dispositivos móviles
✅ Control de versiones con Git

---

## Notas Importantes

- El sitio está optimizado para ser responsive en dispositivos de todos los tamaños
- Se utiliza Bootstrap 5 desde CDN
- Los estilos personalizados se encuentran en `css/styles.css`
- Las imágenes deben colocarse en la carpeta `images/`
- El proyecto está versionado en Git con ramas main y develop
