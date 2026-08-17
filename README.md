# Fullstack from Cero 🚀

Repositorio personal donde documento mi paso por [JSCamp](https://www.jscamp.dev), el bootcamp gratuito de JavaScript Full-Stack de [midudev](https://midu.dev): apuntes y ejercicios resueltos módulo a módulo, desde frontend hasta DevOps.

## Sobre este repo

Es mi cuaderno de bitácora siguiendo el temario oficial de JSCamp. Cada carpeta corresponde a un módulo del curso, con el código y los ejercicios que voy resolviendo a medida que avanzo. No es una copia del [repo oficial del curso](https://github.com/midudev/jscamp), sino mi propia práctica sobre el mismo temario.

## Estructura

| # | Carpeta                      | Módulo (JSCamp)                    | Clases | Estado |
| - | ------------------------------ | ------------------------------------- | :----: | :----: |
| 01 | `01_intro`                     | Introducción al Bootcamp              |   8    |   ✅   |
| 02 | `02_html_css`                  | HTML y CSS                            |   22   |   🔄   |
| 03 | `03_javascript`                | JavaScript                            |   28   |   ⬜   |
| 04 | `04_react`                     | React                                 |   43   |   ⬜   |
| 05 | `05_react_router`              | Estado Global y React Router          |   23   |   ⬜   |
| 06 | `06_backend_node_express`      | Backend con Node.js y Express         |   32   |   ⬜   |
| 07 | `07_testing`                   | Testing                               |   9    |   ⬜   |
| 08 | `08_typescript`                | TypeScript                            |   18   |   ⬜   |
| 09 | `09_ai`                        | Inteligencia Artificial               |   24   |   ⬜   |
| 10 | `10_sql`                       | SQL                                   |   22   |   ⬜   |
| 11 | `11_code_agent`                | Agente de Código                      |   34   |   ⬜   |
| 12 | `12_cicd`                      | CI/CD                                 |   18   |   ⬜   |
| 13 | `13_docker_devops`             | DevOps y Docker                       |   24   |   ⬜   |

Leyenda: ✅ Terminado · 🔄 En progreso · ⬜ Pendiente

*(305+ clases en total. Voy marcando cada fila conforme completo el módulo.)*

## Organización de cada carpeta

Cada módulo mezcla teoría y práctica, así que el contenido interno varía según la naturaleza del tema (no todos son scripts sueltos como en `python-from-cero`):

```
0X_modulo/
├── notes.md          # apuntes breves del módulo
├── exercises/         # ejercicios resueltos, uno por lección o bloque
└── project/            # mini-proyecto o práctica final del módulo (si aplica)
```

Por ejemplo, `04_react` y `06_backend_node_express` tendrán su propio mini-proyecto dentro de `project/`, mientras que módulos más teóricos como `01_intro` probablemente solo lleven `notes.md`.

## Requisitos

- Node.js (LTS) y npm
- Editor de código (VS Code recomendado)
- Docker, para el módulo `13_docker_devops`
- Cuenta de GitHub, para el módulo `12_cicd` (GitHub Actions)

## Cómo usar el repo

```
git clone https://github.com/alvarocyber/fullstack-from-cero.git
cd fullstack-from-cero
cd 02_html_css
```

## Fuente

Todo el temario y las clases originales están en [jscamp.dev](https://www.jscamp.dev), impartido por [midudev](https://midu.dev). El repo oficial del curso (con el código base de referencia) está en [github.com/midudev/jscamp](https://github.com/midudev/jscamp).

## Contexto

Este repo complementa mi especialización en ESI-UCLM y mi roadmap hacia backend engineering: mientras JSCamp cubre el stack JavaScript completo (React, Node/Express, SQL, testing, Docker, CI/CD), en paralelo sigo profundizando en Python, agentes de IA y mi stack elegido (React + Django/FastAPI). La idea es salir con una base full-stack sólida y transferible entre ecosistemas, no atada a un único lenguaje.

## Objetivo

Completar los 13 módulos del bootcamp documentando cada paso, como preparación práctica para procesos de selección en desarrollo full-stack (Fever, Sopra Steria) y como base transversal para mi trabajo con agentes de IA.
