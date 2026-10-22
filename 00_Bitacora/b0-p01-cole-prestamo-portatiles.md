Fase 0.8 · Práctica 01 · Cole: préstamo de portátiles
- **Alumno:** Javier Agulló
- **Bloque:** B0 — Prerrequisitos
- **Fase / ejercicio:** Fase 0.8
- **Fecha de inicio:** 22/10/2026
- **Fecha de entrega:** 22/10/2026

---

## 🎯 Qué se pedía

He creado un proyecto HTML y 
su propio repositorio Git, también otro repositorio vacío en GitHub y lo he conectado por SSH.

## ⌨️ Comandos y pasos importantes

- `cd` — acceder a una carpeta
-  ls -l — hacer el listado de archivos
- git init — para colocar el master
- git branch -M main — cambiar de master a main
- git status — para comprobar
- git commit — colocar el nombre
- git push — subirlo a github

## 🛠️ Qué he hecho

He creado una estructura de archivos, he hecho los commits y los push correspondientes y comprobado cada fichero

## 🚩 Qué me ha fallado y cómo lo he resuelto

me ha fallado a la hora de seleccionar los archivos para hacer el commit, pero era un error mio ya que estaba eliminando el .md pensando que no iba ahi, pero si

## 🤔 Respuestas a las preguntas

1. ¿Por qué git init se hizo en 01_Proyecto y no en la raíz de la bóveda?
- Para controlar solo los archivos del proyecto, no toda la bóveda.
2. ¿Qué mostró git status antes de add , después de add y después de commit ?
- Antes de add, archivos sin seguimiento, después archivos preparados, después de commit, árbol de trabajo limpio.
3. ¿Por qué creaste un repositorio de GitHub propio y lo conectaste con git remote add origin ?
- Para guardar una copia remota y conectar el proyecto con git remote.
4. ¿Por qué las páginas nuevas aparecen en git status pero no en git diff -- web/
index.html ?
- git status muestra archivos nuevos, pero git diff -- web/index.html no enseña su contenido porque Git aún no sigue esos archivos.
5. ¿Cómo has comprobado que los vídeos existen pero no se van a subir?
- Metiendome en github y tambien comprobando que no he puesto el comando de los videos
6. ¿Qué muestra git diff --cached --stat después de preparar los cuatro archivos?
- Enseña los archivos preparados y el resumen de cambios: inserciones y eliminaciones.
7. ¿Qué cambia al visitar el primer commit y qué recuperas al volver a main ?
- Al visitarlo con git checkout, ves la versión antigua; al volver con git switch main, recuperas la versión actual.
8. ¿Por qué esta web necesita historial? ¿Qué aportaría GitHub si otro técnico trabajase contigo?
- Permite registrar cambios, comparar versiones y recuperar errores. GitHub facilita compartir código, colaborar y revisar cambios.
9. Si mañana corriges una errata en normas.html , ¿qué pasos repites y cuáles no?
- Repetir git status, git add normas.html y git commit -m y no repetir git init ni configurar origin


## 🔗 Enlaces

- **Vídeo de esta fase:** https://youtu.be/y_dFQOxBgEQ
- **Playlist:** B0.P01 · Cole · Préstamo de portátiles con Git y GitHub

## 💭 Dudas / a repasar

-  nada
- **Playlist:** B0.P01 · Cole · Préstamo de portátiles con Git y GitHub

## 💭 Dudas / a repasar

-  nada