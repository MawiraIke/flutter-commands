# flutter-commands
Common flutter commands to install, run and build Flutter and Dart projects


***
## Install Flutter

### Step One
To install flutter follow the directions below as per the different OS.

#### Windows
- Official link at [Docs](https://flutter.dev/docs/get-started/install/windows)
- Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.9.1+hotfix.2-stable.zip)
- Extract the zip file and place the contained flutter in the desired installation location for the Flutter SDK (for example, C:\src\flutter; do not install Flutter in a directory like C:\Program Files\ that requires elevated privileges.
- Append flutter/bin to environment variables.
- Run flutter doctor.
        flutter doctor

#### MacOS
- Official link at [Docs](https://flutter.dev/docs/get-started/install/macos)
- Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_v1.9.1+hotfix.2-stable.zip)
- Extract the file in the desired location, i.e,
        unzip ~/Downloads/flutter_macos_v1.9.1+hotfix.2-stable.zip
- Add flutter tool to your path, i.e,
        export PATH="$PATH:`pwd`/flutter/bin"
- Run flutter doctor.
        flutter doctor
    
#### Linux
- Offical link at [Docs](https://flutter.dev/docs/get-started/install/linux)
- Download [Bundle](https://storage.googleapis.com/flutter_infra/releases/stable/linux/flutter_linux_v1.9.1+hotfix.2-stable.tar.xz)
- Extract the file to the desired location, i.e,
        tar xf ~/Downloads/flutter_linux_v1.9.1+hotfix.2-stable.tar.xz
- Add flutter tool to your path, i.e,
        export PATH="$PATH:`pwd`/flutter/bin"
- Run flutter doctor.
        flutter doctor
    
    
***
## Set up an editor

