# Portfolio — Pablo Jiménez Bertolet

**Portfolio personal** para mostrar proyectos, tecnologías y mi trayectoria de aprendizaje como estudiante de Ingeniería Informática.

---

## Descripción

Este repositorio contiene el código y los recursos para mi sitio web personal (portfolio). El objetivo es recoger proyectos relevantes, enlaces a GitHub y demos, y servir como tarjeta de presentación técnica para LinkedIn y el CV.

---

## Estado

* ✅ Estructura del repositorio y documentación inicial
* 🚧 Desarrollo del frontend (React + Vite) pendiente → se trabajará en la rama `main` (o en `develop` si se activa GitFlow)
* 📦 Deploy: se publicará en Vercel / GitHub Pages (cuando la web esté lista)

---

## Tecnologías (planeadas)

* Frontend: React (Vite) / HTML / CSS
* Deploy: Vercel o GitHub Pages
* Backend (proyectos): Django / Django REST Framework (APIs que desarrollo por separado)
* Control de versiones: Git / GitHub

---

## Estructura propuesta del proyecto

```
portfolio/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── data/
│   └── App.jsx
├── .gitignore
├── README.md
└── package.json
```

---

## Contenido del portfolio

Cada proyecto tendrá:

* Descripción corta
* Tecnologías usadas
* Enlace al repositorio
* Demo/enlace a la aplicación (si aplica)
* Imágenes o GIF de la app (cuando sea posible)

---

## Cómo comenzar (cuando desarrolles localmente)

```bash
# clonar (si ya existe el repo remoto)
git clone https://github.com/PablitoKresh/portfolio.git
cd portfolio

# (cuando decidas usar Vite + React)
npm create vite@latest . --template react
npm install
npm run dev
```

---

## Buenas prácticas (recomendadas)

* Mantener la rama `main` como versión desplegada/estable.
* Trabajar en ramas `feature/...` para cada mejora (nombres claros).
* Documentar cada proyecto en su propia sección del README o en archivos separados dentro de `src/data/`.

---

## Licencia

Este proyecto está bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

---

## Contacto

* LinkedIn: [https://www.linkedin.com/in/pablo-jim%C3%A9nez-berthollet-40902a280/](https://www.linkedin.com/in/pablo-jim%C3%A9nez-berthollet-40902a280/)
* GitHub: [https://github.com/PablitoKresh](https://github.com/PablitoKresh)
* Email: [pablopan13@gmail.com](mailto:pablopan13@gmail.com)

---

## Próximos pasos (sugeridos)

1. Crear la estructura base con Vite + React.
2. Diseñar la página principal y la sección de proyectos.
3. Añadir mínimo 2 proyectos con capturas y enlaces a repos (tu API de películas y otro proyecto).
4. Publicar en Vercel y añadir el enlace público a LinkedIn.
