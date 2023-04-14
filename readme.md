# Requisitos
1. Instalar VS Code
2. Instalar Flutter Extensio
3. Si no queremos instalar Android Studio =>Command line tools only
4. Extraer command line tools a, por ejemplo c:\tools
5. Añadir path: C:\tools\cmdline-tools\bin a Variables de entorno
6. INstalar Java: https://www.oracle.com/java/technologies/downloads/#jdk17-windows 
7. Instalar Flutter SDK

## Instalar build-tools y plataforma
1. Abrir Powershell en C:\tools\cmdline-tools
2. Ejecutar: sdkmanager "build-tools;30.0.0" --sdk_root=../
3. Ejecutar: sdkmanager "platforms;android-30" --sdk_root=../
4. sdkmanager "cmdline-tools;latest" --sdk_root=../
5. Añadir el path a variables de entorno:
  C:\tools\platforms
  C:\tools\platform-tools

6. Cerrar VS Code y Powershell
  
  
## Preparar VS COde
1. en View -> Command Pallete: Ejecutar "RUn Flutter Doctor"
2. Mirar el informe y solucionar los problemas:
"!] Flutter (Channel stable, 3.7.11, on Microsoft Windows [Version 10.0.19045.2846], locale en-US)
    • Flutter version 3.7.11 on channel stable at C:\tools\flutter
    ! The flutter binary is not on your path. Consider adding C:\tools\flutter\bin to your path.
    ! The dart binary is not on your path. Consider adding C:\tools\flutter\bin to your path."
    
  ----> Pues poner el path como dice :) 
  
      ! Some Android licenses not accepted. To resolve this, run: flutter doctor --android-licenses
  
  ----> Lo dice claro: (puedes ejecutar este commando desde powershell o VS Code terminal:flutter doctor --android-licenses )
  
  [!] Android Studio (not installed) ---> NO HACE FALTA
  
 3. Reinicio VS COde y pruebo de nuevo
 
 # CREAR PROJECTO
 1. en VS Code -> View -> Command Pallete "New Flutter Project"
 2. Configurar VS Code para que Ejecute la aplicacion en Chrome 
 3. Start Debugging.
 
  
