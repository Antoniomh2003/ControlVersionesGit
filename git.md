# 2. Sistemas de control de versiones: Git

## ¿Qué es el control de versiones (VCS)?
Un sistema de control de versiones (VCS) registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo para poder recuperar versiones específicas más adelante.

### Beneficios principales:
- Revertir archivos o el proyecto completo a un estado anterior.
- Comparar cambios a lo largo del tiempo.
- Identificar quién realizó modificaciones y cuándo se introdujo un error.
- Facilitar la recuperación de archivos en caso de pérdida o problemas accidentales.

---

## Tipos de sistemas de control de versiones

1. **Locales:**
   - Utilizan una base de datos local simple donde se registran todos los cambios sobre los archivos en el propio equipo.

2. **Centralizados:**
   - Emplean un servidor único que contiene todos los archivos versionados. Los colaboradores descargan las versiones desde ese punto central.

3. **Distribuidos:**
   - Los colaboradores no solo descargan la última instantánea de los archivos, sino que replican por completo el repositorio en local.
   - Si el servidor central falla, cualquier copia de los colaboradores puede restaurarlo íntegramente.

---

## Git
Git es una herramienta rápida, eficiente y moderna de control de versiones para archivos digitales (código fuente o cualquier otro tipo de documento).

- **Autor:** Creado por Linus Torvalds para el desarrollo del kernel de Linux.
- **Flujo distribuido:** Permite trabajar sin depender obligatoriamente de un repositorio central.
```[cite: 4, 5, 6, 7]
