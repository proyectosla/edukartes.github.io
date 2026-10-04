# EdukArtes - Página Web Oficial

Página web profesional para EdukArtes, programa de bienestar integral de la Fundación Manitas Unidas.

## Estructura del Proyecto

```
.
├── index.html          # Página principal
├── assets/
│   └── logo.png       # Logo de EdukArtes
├── .gitignore         # Archivos a ignorar en Git
└── README.md          # Este archivo
```

## Características

✅ Responsive (funciona en móvil, tablet y desktop)
✅ Navegación fija y fluida
✅ Secciones: Inicio, Quiénes Somos, Servicios, Contacto
✅ Botones funcionales directos a WhatsApp, Instagram y Tienda Virtual
✅ Colores basados en el branding de EdukArtes
✅ Optimizado para SEO básico
✅ Sin dependencias externas (HTML + CSS puro)

## Instrucciones para GitHub Pages

### 1. Crear un repositorio en GitHub

1. Abre https://github.com/new
2. Nombre del repositorio: `edukartes.github.io`
3. Descripción: "Página web oficial de EdukArtes"
4. Selecciona "Public"
5. Haz clic en "Create repository"

### 2. Preparar los archivos locales

Descarga esta carpeta a tu computadora o cópiala a una ubicación segura.

### 3. Inicializar Git (si no lo has hecho)

Abre terminal/CMD en la carpeta del proyecto y ejecuta:

```bash
git init
git add .
git commit -m "Versión inicial de la página EdukArtes"
git branch -M main
git remote add origin https://github.com/[tu-usuario]/edukartes.github.io.git
git push -u origin main
```

Reemplaza `[tu-usuario]` con tu usuario de GitHub.

### 4. Acceder a tu sitio

En 2-3 minutos, tu sitio estará disponible en:
```
https://edukartes.github.io
```

## Actualizar la página

Para hacer cambios en el futuro:

1. Edita `index.html` o los archivos que necesites
2. En terminal:
```bash
git add .
git commit -m "Descripción del cambio"
git push
```

## Cambios frecuentes

### Cambiar el WhatsApp
En `index.html`, busca la línea con el número `3219242244` y reemplazalo.

### Cambiar Instagram
Busca `eduk_artes` en el archivo y actualiza.

### Cambiar Tienda Virtual
Busca la URL `https://fundacion-manitas-unidas.cercia.co/` y actualiza.

### Cambiar ubicación
Busca "Montería, Córdoba, Colombia" y actualiza.

## Colores del Branding

- Verde oscuro: #2d5016
- Verde claro: #7ab649
- Naranja: #f39c12
- Gris claro: #f5f5f5

Estos están definidos en las variables CSS del archivo `index.html`.

## Soporte

Si necesitas ayuda con Git o GitHub, consulta:
- GitHub Docs: https://docs.github.com
- Git Handbook: https://guides.github.com

---

**Última actualización:** Octubre 2026
**Desarrollado por:** Orbita Integración de Servicios Gerenciales
