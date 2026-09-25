# Gestión de Citas Médicas — Análisis de Stack

## Descripción

Este repositorio contiene el análisis técnico para seleccionar un stack de desarrollo para una aplicación móvil de **gestión de citas médicas** compatible con Android e iOS.

## Stack recomendado

- **Framework:** Flutter
- **Lenguaje:** Dart
- **IDE:** Android Studio Quail 4 (2026.1.4 Patch 1), versión estable consultada el 24/09/2026
- **Cámara:** escaneo de códigos QR
- **Notificaciones:** Firebase Cloud Messaging o servicio equivalente
- **Persistencia local:** base de datos/almacenamiento local para historial mínimo offline
- **Backend propuesto:** API REST + base de datos relacional

## Comparativa

| Criterio | Flutter | React Native + Expo | Kotlin Multiplatform |
|---|---|---|---|
| Lenguaje | Dart | JavaScript/TypeScript | Kotlin |
| Rendimiento | Alto | Alto en aplicaciones generales; depende de arquitectura y módulos | Cercano a nativo |
| Curva de aprendizaje | Media | Media si se conoce React/JS | Media-alta |
| Comunidad | Grande y consolidada | Muy grande por React/JS | En crecimiento |
| Ejemplos | Google Pay, BMW, Google Earth, eBay | Microsoft Office, Outlook, Teams, Amazon Shopping, Alexa | Google, Duolingo, Forbes, Philips, McDonald's, Bolt |

## Hardware y capacidades

### Cámara
Se utiliza para escanear códigos QR asociados a una clínica, consultorio, médico o confirmación de cita.

### Notificaciones push
Se necesitan para:
- Recordatorios de citas.
- Confirmaciones.
- Cambios de horario.
- Cancelaciones.
- Avisos del consultorio.

### Almacenamiento local
Debe permitir consultar un historial mínimo sin conexión. La aplicación debe sincronizar los cambios cuando vuelva la conectividad y evitar almacenar más información médica de la necesaria.

### Conectividad
Internet/Wi-Fi/datos móviles es necesaria para autenticación, consulta de horarios, reserva de citas y sincronización.

## Configuración del entorno

1. Instalar Android Studio Quail 4.
2. Instalar/configurar Android SDK, Platform Tools y Build Tools.
3. Instalar Flutter SDK.
4. Añadir Flutter al PATH.
5. Abrir Android Studio.
6. Instalar el plugin **Flutter** desde `Settings > Plugins`.
7. Reiniciar Android Studio.
8. Ejecutar `flutter doctor`.
9. Crear un dispositivo virtual desde `Device Manager`.
10. Crear y ejecutar un proyecto Flutter de prueba.

> Para compilar/publicar iOS se necesita un equipo macOS con Xcode.

## Evidencias

Agregar al repositorio una carpeta `capturas/` con:

- `01-flutter-plugin.png` — Flutter instalado en Android Studio.
- `02-sdk-manager.png` — Android SDK configurado.
- `03-device-manager.png` — emulador creado.
- `04-flutter-doctor.png` — resultado de `flutter doctor`.

Las capturas deben ser tomadas del equipo del alumno; no deben presentarse imágenes de Internet como configuración propia.

## Archivos de entrega

- `Reporte_Tecnico_Stack_Citas_Medicas.pdf`
- `README.md`
- `capturas/`

## Referencias

- Android Developers: https://developer.android.com/studio/releases
- Android Studio: https://developer.android.com/studio/install.html
- Flutter: https://docs.flutter.dev/
- Flutter Showcase: https://flutter.dev/showcase
- React Native Showcase: https://reactnative.dev/showcase.html
- Expo: https://docs.expo.dev/
- Kotlin Multiplatform: https://kotlinlang.org/docs/multiplatform/

## Fecha de consulta

24 de septiembre de 2026.
