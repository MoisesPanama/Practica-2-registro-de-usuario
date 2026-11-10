# Práctica 2 – Registro de Usuarios

Aplicación Android desarrollada en Kotlin para la práctica de **diseño responsivo de interfaces de usuario** con `ConstraintLayout` y Material Components.

## Descripción

La aplicación presenta un formulario de registro de usuarios en una sola pantalla. El contenido se encuentra dentro de un `ScrollView` para que pueda desplazarse en dispositivos pequeños y utiliza campos Material con bordes outline.

### Campos del formulario

- Nombres y apellidos.
- Tipo de documento: cédula, pasaporte o RUC.
- Número de identificación.
- Género: hombre, mujer u otro.
- Fecha de nacimiento mediante menús desplegables de día, mes y año.
- Teléfono.
- Botón **Grabar**.

El botón forma parte únicamente del diseño de la interfaz, ya que la práctica está enfocada en la construcción y adaptación visual de la pantalla.

## Estructura del proyecto

- `app/src/main/java/com/example/practica2/MainActivity.kt`: carga la pantalla y aplica los márgenes del sistema.
- `app/src/main/res/layout/activity_main.xml`: diseño responsivo con `ScrollView`, `ConstraintLayout` y componentes Material.
- `app/src/main/res/values/strings.xml`: textos de la interfaz.
- `app/src/main/res/values/arrays.xml`: opciones de los menús desplegables.
- `app/src/main/res/drawable/`: iconos utilizados en el formulario.

## Tecnologías

- Kotlin.
- Android Studio.
- `ConstraintLayout`.
- Material Components (`TextInputLayout`, menús desplegables y botones).
- `ScrollView` para adaptar el formulario a distintas alturas de pantalla.

## Evidencias

Las capturas de la aplicación se agregarán en la carpeta `evidencias/` al finalizar la práctica.

## Ejecución

1. Abrir el proyecto en Android Studio.
2. Sincronizar Gradle.
3. Ejecutar la aplicación en un emulador o dispositivo Android.
