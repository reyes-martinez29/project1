# Guía Visual de Git y GitHub (HTML + CSS)

Guía visual, práctica y progresiva para aprender Git y GitHub desde cero hasta un flujo de trabajo real, construida como una página web estática usando únicamente HTML y CSS.

Este proyecto no solo explica Git: utiliza Git correctamente durante todo su desarrollo, aplicando ramas, Pull Requests, merges y commits claros.

## Objetivo del proyecto

El objetivo de este proyecto es aprender Git y GitHub de forma práctica, no solo teórica, construyendo una guía de referencia real mientras se aplica un flujo profesional de trabajo.  
Durante el desarrollo se generó un historial realista con más de 50 commits bien justificados.

## Qué aprenderás con esta guía

- Qué es Git y qué es GitHub (y por qué no son lo mismo)
- Flujo básico: init → status → add → commit
- Cómo leer el historial: log, diff y show
- Trabajo con ramas (branch y switch)
- Merge y resolución de conflictos
- Uso de repositorios remotos (GitHub)
- Pull Requests y revisión de cambios
- Buenas prácticas y recuperación de errores
- Cheatsheet final con los comandos esenciales

## Tecnologías usadas

- HTML5 – estructura del contenido
- CSS3 – diseño, layout y responsive
- Git – control de versiones
- GitHub – repositorio remoto y Pull Requests

No se utilizan frameworks ni JavaScript. El enfoque del proyecto es claridad, simplicidad y aprendizaje.

## Estructura del proyecto

git-guia-web/
├── index.html
├── styles.css
├── README.md
└── .gitignore

## Cómo ver la guía

No requiere instalación ni dependencias.

1. Clona el repositorio:
   git clone https://github.com/usuario/git-guia-web.git
2. Abre el archivo index.html en tu navegador.

## Flujo de trabajo usado en el proyecto

Este proyecto se desarrolló siguiendo un flujo realista y profesional de Git y GitHub:

1. Crear una rama para cada sección o mejora
2. Realizar commits pequeños y con intención clara
3. Subir la rama al repositorio remoto
4. Abrir un Pull Request hacia la rama main
5. Corregir detalles antes del merge (incluidos problemas visuales)
6. Realizar el merge en GitHub
7. Sincronizar el repositorio local con git pull
8. Eliminar la rama una vez integrada

Este mismo flujo está documentado y explicado dentro de la guía.

## Convención de commits

Se utilizaron prefijos claros para mantener un historial legible:

- feat: contenido o funcionalidad nueva
- style: cambios visuales o de diseño
- fix: correcciones
- docs: documentación
- chore: mantenimiento o configuración

Ejemplos reales de commits usados en el proyecto:

feat: add workflow section  
style: fix responsive layout for grids and navbar  
fix: improve anchor navigation  
docs: finalize README  

## Responsive y calidad visual

- Layout adaptable usando CSS Grid con minmax
- Navbar desplazable horizontalmente en pantallas pequeñas
- Bloques de código legibles en desktop y mobile
- Correcciones visuales realizadas antes de integrar cambios a main

## Estado del proyecto

Estado: completo y estable  
Propósito: educativo y de referencia  
Uso: académico, personal y de portafolio

Posibles mejoras futuras:
- Publicar la guía con GitHub Pages
- Agregar capturas al README
- Añadir archivos CONTRIBUTING.md y templates de Pull Request

## Aprendizaje clave

Git no se aprende memorizando comandos.  
Git se aprende usándolo correctamente dentro de un flujo real de trabajo.

Este proyecto refleja ese enfoque.
