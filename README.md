# 🎬 Desafío React + TypeScript + Vite + Tailwind

Proyecto frontend desarrollado con tecnologías modernas para consumir la API pública de [TMDB](https://www.themoviedb.org/).

> Este proyecto forma parte de un challenge técnico con foco en buenas prácticas, componentes reutilizables y documentación profesional.

---
Para ver el deploy de prueba:
👉 https://react-tsoft.netlify.app/

## 🚀 Tecnologías principales

- ⚛️ **React 19** — UI moderna con hooks
- 🧠 **TypeScript** — Tipado estático robusto
- ⚡ **Vite** — Build tool ultra rápido
- 🎨 **Tailwind CSS** — Estilos con utilidades listas
- ✨ **Storybook 9** — Catálogo visual de componentes
- 🧪 Vitest — Framework de testing moderno (compatible con Vite)

---

## 🌐 API utilizada

Se consume la API pública de **TMDB (The Movie Database)** para mostrar:

- Detalles de películas
- Popularidad
- Géneros
- Imágenes, fechas de estreno, sinopsis, etc.

> Requiere clave pública de TMDB configurada en el archivo `.env`

---

## 📦 Instalación local

```bash
git clone https://github.com/LucasFernandez11/desafio-react-tsoft.git
cd desafio-react-tsoft
npm install
```


## ▶️ Correr la app en modo desarrollo
```bash

npm run dev
```
Abre tu navegador en:
👉 http://localhost:5173


## 📚 Storybook: Catálogo de Componentes
Este proyecto cuenta con documentación visual de los componentes usando Storybook.

Para ver el deploy de Storybook:
👉 https://react-tsoft-storybook.netlify.app/ 


🔧 Para correr Storybook en local:
```bash

npm run storybook
```
Abre tu navegador en:
👉 http://localhost:6006


Desde ahí podés visualizar y testear componentes como:
Card, MovieDetailView y Chip


## ✨ Componentes documentados hasta ahora
Componente	Descripción
Card	Tarjeta reutilizable con 5 layouts distintos (hero, popular, etc.)
MovieDetailView	Vista detallada de película (versión presentacional)
Chip	Etiqueta dinámica con color por id

🛠 Scripts útiles
```bash

npm run dev              # Corre la app
npm run storybook        # Inicia Storybook
npm run build            # Compila el proyecto
npm run build-storybook  # Compila Storybook para deploy
npm run test             # Ejecuta todos los archivos de testing
npm run test:coverage    # Generará una carpeta coverage/ con el porcentaje de líneas y archivos testeados.    
```

## 🧪 Testing: Validación de componentes y lógica
Este proyecto cuenta con pruebas unitarias e integración utilizando:

Vitest — Framework de testing moderno (compatible con Vite)

@testing-library/react — Interacción con componentes como un usuario real

msw — Simulación de API en tests

▶️ Ejecutar todos los tests

```bash
npm run test
```

🔁 Modo watch (se vuelve a ejecutar al guardar cambios)

```bash
npm run test:watch #Ver reporte de cobertura
```

```bash
npm run test:coverage #Esto generará una carpeta coverage/ con el porcentaje de líneas y archivos testeados.
```

## 📄 Licencia
Este proyecto es de uso educativo y demostrativo.

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=LucasFernandez11&repo=desafio-react-tsoft)](https://github.com/LucasFernandez11/desafio-react-tsoft)

## Desarrollado por Lucas Fernández

