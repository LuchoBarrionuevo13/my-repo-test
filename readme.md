# Landing Base

Proyecto de landing page responsivo y optimizado para SEO.

## Requisitos

- Un navegador web moderno (Chrome, Firefox, Safari, Edge)
- Editor de código (VS Code, Sublime Text, etc.)
- Git para control de versiones

## Pasos de Instalación

1. Clonar el repositorio:
```bash
git clone <url-del-repositorio>
cd CarpetaCopetti
```

2. Navegar a la rama develop:
```bash
git checkout develop
```

3. Instalar dependencias (si las hay):
```bash
npm install
```

## Cómo Ejecutar

1. Abre el archivo `index.html` en tu navegador:
   - Haz doble clic en el archivo `index.html`, o
   - Usa una extensión como Live Server en VS Code

2. Si usas Live Server en VS Code:
   - Haz clic derecho en `index.html`
   - Selecciona "Open with Live Server"

## Convenciones de Ramas

Este proyecto sigue una estructura de ramificación clara para mantener el código organizado y facilitar la colaboración:

### Rama `develop`
- Rama principal de desarrollo
- Contiene las características completas y testadas
- Punto de partida para nuevas características
- Base para crear ramas de features

### Rama `feature/<nombre>`
- Se crean a partir de `develop`
- Utilizadas para desarrollar nuevas características o funcionalidades
- Ejemplo: `feature/landing-base`, `feature/contacto`, `feature/galeria`
- Una vez completadas, se fusionan de vuelta a `develop` mediante pull request

### Creando una rama feature
```bash
git checkout develop
git checkout -b feature/tu-caracteristica
```

### Fusionando a develop
```bash
git checkout develop
git merge feature/tu-caracteristica
```

## Desarrolladores

- Luciano Copetti

---

Proyecto desarrollado con dedicación y pasión. ¡Gracias por tu interés!
