# vetaprueba

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


-para cambiar el nameId : flutter pub run change_app_package_name:main com.kiyasaa0523proyect.push-language
para llevar a cabo este cambio se tendra que instalar la dependencia en pubspec.yaml 

Primero, abre el archivo `pubspec.yaml` y agrega `change_app_package_name` a las dependencias de desarrollo:

```yaml
dev_dependencies:
  change_app_package_name: ^1.0.0
  
-para construir la apk: flutter buil apk --name



-para cambiar icono de la app en ¨pupspec.yaml
    ´´dev_dependencies:
        ´´flutter_test:
            ´´sdk: flutter
        ´´flutter_launcher_icons:
        
    ´´flutter_icons:
        ´´android: 'launcher_icon'
        ´´ios: true
        ´´image_path: './icon/name-image.png'
        ´´adaptive_icon_background: './icon/name-image.png'
        
* y ejecutamos en la terminal 
    ´´flutter packages pub run flutter_launcher_icons:main
    ANDROID
-para cambiar el nombre de la aplicacion nos vamos a la carpeta:
    ´´android/app/src/main/AndroidManifest.xml
    
-buscamos el nombre que esta definidido por la etiqueta 
    ´´android: label= 'new name'
    
    
        IOS
- nos dirigimos a la carpeta     
    ´´ios/Runner/Info.plist
- buscamos y cambiamos el valor de la etiqueta:
    ´´<key>CFBundleDisplayName</key>
    ´´<string>New Name</string>



