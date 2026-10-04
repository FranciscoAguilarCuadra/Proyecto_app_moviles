# Proyecto App Móviles

[![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=black)](https://www.android.com/)
[![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)](https://www.java.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)

Aplicación android nativa desarrollada como proyecto de la asignatura de Dispositivos Móviles.

<!--
## Capturas
Coloca las imágenes en `docs/screenshots/` y descomenta:
![Login](docs/screenshots/login.png)
-->

## 📱 Descripción

App móvil construida en Android con autenticación mediante Firebase y inicio de sesión con Google, diseñada para ofrecer una experiencia fluida al usuario.

## 🛠️ Tecnologías

- **Lenguaje:** Java
- **Plataforma:** Android (SDK 35)
- **SDK Mínimo:** 24 (Android 7.0)
- **Autenticación:** Firebase Auth
- **Login Social:** Google Sign-In
- **UI:** Material Design + ConstraintLayout

## ✨ Funcionalidades

- Inicio de sesión con Firebase Authentication
- Autenticación con cuenta de Google
- Interfaz basada en Material Design
- Compatibilidad con Android 7.0 en adelante

## 🚀 Cómo ejecutar

### Requisitos
- Android Studio (última versión recomendada)
- JDK 11 o superior
- Dispositivo o emulador con Android 7.0+

### Pasos
1. Clonar el repositorio
   ```bash
   git clone https://github.com/FranciscoAguilarCuadra/Proyecto_app_moviles.git
   ```

2. Abrir el proyecto en Android Studio

3. Configurar Firebase:
   - Crear un proyecto en [Firebase Console](https://console.firebase.google.com/)
   - Habilitar Firebase Authentication
   - Habilitar Google Sign-In
   - Descargar `google-services.json` y colocarlo en `app/`

4. Sincronizar y ejecutar

## 📂 Estructura del proyecto

```
Proyecto_app_moviles/
├── app/
│   ├── src/
│   ├── build.gradle
│   └── google-services.json  (no incluido)
├── gradle/
├── build.gradle
└── settings.gradle
```

## 📋 Configuración de Firebase

1. Ir a [Firebase Console](https://console.firebase.google.com/)
2. Crear un nuevo proyecto
3. Agregar una app Android con el package name: `cl.grupo6.proyecto_app_moviles`
4. Descargar `google-services.json`
5. Habilitar **Email/Password** y **Google** en Authentication > Sign-in method

## 👨‍💻 Autor

**Francisco Aguilar Cuadra**

---

*Proyecto académico - Asignatura de Dispositivos Móviles*
