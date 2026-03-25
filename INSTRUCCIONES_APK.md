# Compilar el APK Remote via API (GitHub Actions)

Como me pediste la opción de que quede compilada vía API y obtener tu APK, te preparé un proyecto nativo de Android super ligero.
Como no tenés el SDK de Android en tu PC, usaremos los servidores gratuitos de GitHub (GitHub Actions) para que te devuelvan el APK ya compilado en 2 minutos.

## Instrucciones:

1. Ingresá a tu cuenta de GitHub y creá un nuevo repositorio **privado** (o público, como prefieras).
2. Subí **todo el contenido** de esta carpeta (`AndroidRemoteApp`) a ese repositorio.
3. En tu repositorio, andá a la pestaña **Actions**.
4. Es posible que te pida habilitar los Workflows; dale a "I understand my workflows, go ahead and enable them".
5. En la lista de la izquierda, seleccioná **"Build Android APK"**.
6. A la derecha le das al botón gris que dice **"Run workflow"**.
7. Esperá aproximadamente 1 a 2 minutos que termine de ejecutarse. 
8. Cuando termine (aparece un tick verde ✅), hacé clic en la ejecución y abajo del todo verás un archivo llamado **`app-debug`**.
9. Descargalo! Es un `.zip` que adentro contiene tu flamante **`app-debug.apk`**.
10. Pasalo a tu celular, instalalo, ¡y listo! Tu remote ya nunca apagará la pantalla.

> **Nota para el futuro:** Si hacés cambios en `screen-assist-remote.html`, simplemente copiá y reemplazá el archivo en `AndroidRemoteApp/app/src/main/assets/index.html`, subí el cambio a GitHub y automáticamente se generará un nuevo APK.
