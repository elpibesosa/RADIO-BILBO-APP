# Radio Bilbo 91.5 FM – App para Android

App que solo sirve para escuchar la radio: se abre, se toca el botón y suena.
No abre páginas web ni enlaces. Funciona con Android 5.0 o más nuevo y sigue
sonando con la pantalla apagada.

## Cómo se obtiene el APK

Este proyecto se compila solo en GitHub (pestaña **Actions**). Cada vez que se sube
algo al repositorio, GitHub genera `RadioBilbo.apk` y lo deja en **Releases**.

## Si cambia el streaming

Abrir `app/src/main/java/ar/bilbofm/radio/RadioService.java` y cambiar la línea
`STREAM_URL` por la nueva dirección (tiene que empezar con `https`).

## Si hay que cambiar el nombre, el ícono o los textos

- Nombre de la app: `app/src/main/res/values/strings.xml`
- Textos de la pantalla: `app/src/main/res/layout/activity_main.xml`
- Logo: `app/src/main/res/drawable-nodpi/logo.png`
