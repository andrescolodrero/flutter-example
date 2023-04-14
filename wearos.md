## Comenzar con Wear-Os
1. Installar plugin para flutter
flutter pub add wear
2. Vamos a necesitar algun dispositivo para la emulacion, lo instalamos con sdkmanager
3. C:\tools\cmdline-tools\sdkmanager "system-images;android-27;google_apis_playstore;x86" --sdk_root=../
4. PAra instalar un dispositivo "Wear OS":  sdkmanager "system-images;android-30;android-wear;x86" --sdk_root=../

Si no encontramos la imagen a descargar:
sdkmanager --list --verbose | grep 'wear_'

 sdkmanager "system-images;android-30;android-wear;x86" --sdk_root=../
