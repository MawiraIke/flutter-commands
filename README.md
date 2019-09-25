# flutter-commands

![Flutter image!](https://cdn.devdojo.com/posts/images/June2019/be-a-part-of-the-extensive-bootcamp-for-the-flutter1.jpg?auto=compress&w=960&dpr=2 "Flutter image")

Common flutter commands to install, run and build Flutter and Dart projects

## Install Flutter

### Step One
To install flutter follow the directions below as per the different OS.

#### Windows
1. Official link at [Docs](https://flutter.dev/docs/get-started/install/windows)
2. Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.9.1+hotfix.2-stable.zip)
3. Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, C:\src\flutter; do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges.
4. Append flutter/bin to environment variables.
5. Run flutter doctor.
```
flutter doctor
```

#### MacOS
1. Official link at [Docs](https://flutter.dev/docs/get-started/install/macos)
2. Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_v1.9.1+hotfix.2-stable.zip)
3. Extract the file in the desired location, i.e,
```
unzip ~/Downloads/flutter_macos_v1.9.1+hotfix.2-stable.zip
```
4. Add flutter tool to your path, i.e,
```        
export PATH="$PATH:`pwd`/flutter/bin"
```
5. Run flutter doctor.
```        
flutter doctor
```

#### Linux
1. Offical link at [Docs](https://flutter.dev/docs/get-started/install/linux)
2. Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/linux/flutter_linux_v1.9.1+hotfix.2-stable.tar.xz)
3. Extract the file to the desired location, i.e,
```        
tar xf ~/Downloads/flutter_linux_v1.9.1+hotfix.2-stable.tar.xz
```
4. Add flutter tool to your path, i.e,
```        
export PATH="$PATH:`pwd`/flutter/bin"
```
5. Run flutter doctor.
```
flutter doctor
```    
    
***
## Set up an editor

1. You can use the editor of your choice, but the most common are,
    1. [Android Studio](https://developer.android.com/studio)
    2. [IntelliJ IDEA Community](https://www.jetbrains.com/idea/download/)
    3. [IntelliJ IDEA Ultimate (Paid)](https://www.jetbrains.com/idea/download/)
    4. [Visual Studio Code](https://code.visualstudio.com/)
    
2. Install Flutter and Dart plugins.
3. Create your first flutter project.


