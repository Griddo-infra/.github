# 🧩 Plantillas de Griddo-infra #

Plantillas comunes de **pull requests** e **issues** para todos los repos de la
organización `Griddo-infra`.

GitHub las aplica solas a cualquier repo de la organización que no tenga las
suyas. Este repo tiene que ser público para que eso funcione; por eso solo
contiene plantillas.

---

## 📦 Qué es ##

- `.github/PULL_REQUEST_TEMPLATE.md` → lo que aparece escrito al abrir un PR.
- `.github/ISSUE_TEMPLATE/` → los formularios que se ofrecen al abrir una issue.

---

## 🚀 Uso ##

No hay que hacer nada: al abrir un PR o una issue en cualquier repo de la
organización, la plantilla ya está ahí.

Convenciones que acompañan a las plantillas:

| Qué | Cómo |
| --- | --- |
| Título del PR | `tipo(ámbito): descripción`, en español. Tipos: `feat`, `fix`, `chore`, `docs`, `refactor`, `test` |
| Rama | `tipo/descripción-corta` |
| Fusión | Siempre con squash: el título del PR pasa a ser el del commit |
| Etiquetas | El mismo juego en todos los repos (`tipo: mejora`, `tipo: corrección`, `dependencias`, `seguridad`…) |

---

## 🔧 Configuración ##

Un repo que necesite una plantilla distinta puede tener la suya en su propia
carpeta `.github/`. En cuanto la tiene, deja de usar la común: para los PR, el
fichero `PULL_REQUEST_TEMPLATE.md`; para las issues, cualquier fichero dentro
de `ISSUE_TEMPLATE/`.

---

## 🗂️ Estructura del repositorio ##

- `.github/PULL_REQUEST_TEMPLATE.md` → plantilla de PR.
- `.github/ISSUE_TEMPLATE/incidencia.yml` → formulario de incidencia.
- `.github/ISSUE_TEMPLATE/cambio.yml` → formulario de cambio o mejora.
- `.github/ISSUE_TEMPLATE/config.yml` → opciones del selector de issues.

---

## 🔒 Seguridad ##

- Un cambio aquí se ve en todos los repos de la organización: `main` solo
  admite cambios por PR.
- No añadir una carpeta `profile/`: su `README.md` pasaría a ser la portada
  pública de la organización.
- No escribir aquí nombres de clientes, cuentas ni direcciones internas.

---

## 👤 Autor ##

- ✍️ Equipo de Infra Griddo (OJRR) - Con asistencia de Claude
- 📅 Última actualización: Noviembre 2026
