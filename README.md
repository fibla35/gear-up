# Gear Up! Garage Racing

Juego de conducción 2D para Android (Capacitor 6).

- El juego está en `www/` (se genera desde el proyecto del juego).
- Cada subida a `main` compila la APK sola (GitHub Actions) y la publica en **Releases** como `GearUp.apk`.
- Paquete `com.fibla.gearup`, horizontal, pantalla completa. Firmado siempre con `android/app/gearup.keystore` para que cada APK se instale encima de la anterior. Para Google Play hará falta una clave de publicación nueva y privada.
