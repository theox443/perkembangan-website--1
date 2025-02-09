sudo apt update
sudo apt install python3 python3-pip golang clang dotnet-sdk-8.0
- **Python 3** dan **pip**: Untuk skrip Python dan manajemen paket.
- **Go**: Untuk kode yang ditulis dalam Go.
- **Clang**: Sebagai compiler untuk kode C/C++.
- **.NET 8 SDK**: Untuk proyek yang menggunakan .NET.
- **Android SDK** dan **NDK**: Jika Anda ingin membangun APK.
- #### Instalasi di Ubuntu/Debian:
```bash
sudo apt update
sudo apt install python3 python3-pip golang clang dotnet-sdk-8.0
```
#### Instalasi di Windows:
- Unduh dan instal Python 3 dari [python.org](https://www.python.org/).
- Unduh dan instal Go dari [golang.org](https://golang.org/).
- Unduh dan instal Clang dari [LLVM](https://llvm.org/).
- Unduh dan instal .NET 8 SDK dari [dotnet.microsoft.com](https://dotnet.microsoft.com/).
- pip install -r requirements.txt
python3 your_script.py
go build -o your_binary_name main.go
clang -o your_binary_name your_source_code.c
dotnet build
dotnet run
pip install buildozer
buildozer init
buildozer -v android debug
go install golang.org/x/mobile/cmd/gomobile@latest
gomobile init
gomobile build -target=android -o your_app.apk
#!/bin/bash

# Build Python project
pip install -r requirements.txt
python3 your_script.py

# Build Go project
go build -o your_binary_name main.go

# Build C/C++ project
clang -o your_binary_name your_source_code.c

# Build .NET project
dotnet build
dotnet run

# Build APK (if applicable)
buildozer -v android debug
chmod +x build.sh
./build.sh
