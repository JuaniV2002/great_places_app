# Great Places App
The attached files **DO NOT** work as a standalone project, they are just the code I wrote (lib folder) and pubspecs (dependencies).  

To give the app a try:
-  [Download the Flutter SDK and Android Studio](https://docs.flutter.dev/get-started/install).
-  Run "flutter create" on the terminal, or open up the Command Palette (Ctrl + Shift + 'P') in VS Code and type "Flutter: New Project".
-  Once it's done creating the new project, replace the lib folder and the pubspecs (pubspec.yaml and pubspec.lock) with the ones I provide in this repo.
-  Once you have done that, run `flutter pub get`, so you get all the dependencies needed in the project.
-  Run the app **without debugging** on an Android Virtual Device (first of all you need to have an AVD up and running before running the app).
-  A little sidenote for this specific project: since I used some external packages and APIs to correctly implement the location and camera features, you will need to make some tweaks to the `ios` and `android` folders in the project. 
-  That's it!

---

# Great Places App
Los archivos adjuntados **NO** funcionan como un proyecto por si mismos, son solo el codigo que escribi (carpeta lib) y pubspecs (dependencias).

Para probar la aplicacion:
-  [Descarga el SDK de Flutter y Android Studio](https://docs.flutter.dev/get-started/install).
-  Corre "flutter create" en la terminal, o abre la Command Palette (Ctrl + Shift + 'P') en VS Code y escribe "Flutter: New Project".
-  Una vez que finalizo la creacion del nuevo proyecto, reemplaza la carpeta lib y pubspecs (pubspec.yaml y pubspec.lock) con las que yo proveo en este repositorio.
-  Una vez hecho eso, corre `flutter pub get`, para que obtengas todas las dependencias necesarias para el proyecto.
-  Corre la aplicacion **sin depurar** en un Dispositivo Virtual de Android (primero que todo necesitas tener un DVA abierto y en funcionamiento antes de correr la app).
-  Un pequeño detalle para este proyecto en especifico: como use algunos paquetes y APIs externas para implementar correctamente las caracteristicas de localizacion y camara, necesitaras hacer algunos ajustes en las carpetas `ios` y `android` del proyecto.
-  Eso es todo!
