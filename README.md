<h1 align="center">
  <img src=".github/banner.png" alt=".github · Infraestructura de Griddo" width="100%">
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/tipo-plantillas-5057ff?labelColor=001b3c" alt="Tipo: plantillas">
  <img src="https://img.shields.io/badge/entorno-todos-199ab3?labelColor=001b3c" alt="Entorno: todos">
  <img src="https://img.shields.io/badge/equipo-infra-5057ff?labelColor=001b3c" alt="Equipo: infra">
</p>

Plantillas comunes de **pull requests** e **issues** para todos los repos de la
organización `Griddo-infra`.

---

## 🎯 Qué es y para qué sirve ##

GitHub aplica estas plantillas, sin hacer nada más, a cualquier repo de la
organización que no tenga las suyas. Así todos los PR y todas las issues tienen
la misma forma.

- **Plantilla de PR** (`.github/PULL_REQUEST_TEMPLATE.md`): lo que aparece escrito al abrir un PR. Tres apartados: «Qué cambia», «Por qué» y «Cómo se ha probado».
- **Formularios de issues** (`.github/ISSUE_TEMPLATE/`): los que se ofrecen al abrir una issue.

| Formulario | Para qué | Título que propone | Etiqueta que pone |
| --- | --- | --- | --- |
| Incidencia | Algo falla o no se comporta como debería | `fix: ` | `tipo: corrección` |
| Cambio o mejora | Pedir un cambio en la infraestructura, en un workflow o en la documentación | `feat: ` | `tipo: mejora` |

También se puede abrir una issue en blanco, sin formulario.

---

## 📋 Requisitos ##

- **Este repo tiene que ser público.** Si no lo es, GitHub no aplica las plantillas al resto de la organización. Por eso solo contiene plantillas.
- **El repo que las usa no puede tener las suyas** (ver «Usar una plantilla distinta en un repo»).
- **Las etiquetas tienen que existir en el repo.** Un formulario solo pone una etiqueta que ya exista en el repo donde se abre la issue.

---

## 🚀 Uso ##

No hay que hacer nada: al abrir un PR o una issue en cualquier repo de la
organización, la plantilla ya está ahí.

### Convenciones que acompañan a las plantillas ###

| Qué | Cómo |
| --- | --- |
| Título del PR | `tipo(ámbito): descripción`, en español, en minúscula y en presente. Tipos: `feat`, `fix`, `chore`, `docs`, `refactor`, `test` |
| Rama | `tipo/descripción-corta` |
| Fusión | Siempre con squash: el título del PR pasa a ser el del commit |
| Etiquetas | El mismo juego en todos los repos: `tipo: mejora`, `tipo: corrección`, `dependencias`, `seguridad`, `documentación`, `infraestructura`, `cambio incompatible` y `no fusionar` |

### Usar una plantilla distinta en un repo ###

Un repo que necesite una plantilla distinta puede tener la suya en su propia
carpeta `.github/`. En cuanto la tiene, deja de usar la común:

- para los PR, el fichero `PULL_REQUEST_TEMPLATE.md`;
- para las issues, cualquier fichero dentro de `ISSUE_TEMPLATE/`.

---

## 🚢 Despliegue ##

No hay nada que desplegar: GitHub lee las plantillas de la rama `main` de este
repo. Un cambio se aplica en toda la organización en cuanto se fusiona su PR.

---

## 🗂️ Estructura del repositorio ##

- `.github/PULL_REQUEST_TEMPLATE.md` → plantilla de PR.
- `.github/ISSUE_TEMPLATE/incidencia.yml` → formulario de incidencia.
- `.github/ISSUE_TEMPLATE/cambio.yml` → formulario de cambio o mejora.
- `.github/ISSUE_TEMPLATE/config.yml` → opciones del selector de issues.
- `.github/CODEOWNERS` → quién revisa los cambios de este repo.
- `.github/banner.png` → cabecera de este documento.

---

## 🔒 Consideraciones de seguridad ##

- Un cambio aquí se ve en todos los repos de la organización: `main` solo
  admite cambios por PR, y `CODEOWNERS` asigna la revisión al equipo de
  infraestructura.
- No añadir una carpeta `profile/`: su `README.md` pasaría a ser la portada
  pública de la organización.

> [!WARNING]
> Este repo es público. No escribas aquí nombres de clientes, cuentas ni
> direcciones internas.

> [!IMPORTANT]
> En una issue no se pegan contraseñas, tokens ni claves. Si el problema es de
> seguridad, no abras una issue: avisa al equipo de infraestructura.

---

## 📬 Contacto y responsables ##

- **Responsable:** Equipo de Infra de Griddo.
- **Dudas o propuestas sobre las plantillas:** abre una issue en este repo.

---

## 📝 Historial de cambios ##

Este repo no lleva un `CHANGELOG.md`: cada cambio entra por un PR con el título
en el formato `tipo(ámbito): descripción` y se fusiona como un solo commit.

- [PR fusionados](https://github.com/Griddo-infra/.github/pulls?q=is%3Apr+is%3Amerged)
- [Commits de `main`](https://github.com/Griddo-infra/.github/commits/main)

---

## 👤 Autor ##

- ✍️ Equipo de Infra Griddo (OJRR) - Con asistencia de Claude
- 📅 Última actualización: Noviembre 2026
