# UA-Space-Station-14
Українська версія Space Station 14
- - -
### Про українську версію SS14 (Space Station 14)
Це не офіційний переклад SS14 з видаленням контенту країни-агрессора та деякими поліпшеннями.
- - -
### Використання
Якщо ви не розробник та хочете створити сервер для гри з друзями/для глобальної гри, то просто завантажте потрібну версію серверу з релізів
Якщо ви розробник, хочете завантажити та скомпілювати сервер, виконайте ці команди в консолі:
# Linux:
```
apt update && apt upgrade
apt install git dotnet7 python3
git clone https://github.com/Lines115/UA-Space-Station-14.git
cd UA-Space-Station-14
python3 RUN_THIS.py
dotnet7 build --os linux
cd bin/Content.Server
```
Далі, для запуску серверу, в папці UA-Space-Station-14/bin/Content.Server, напишіть: ./Content.Server
# Windows:
```
git clone https://github.com/Lines115/UA-Space-Station-14.git
cd UA-Space-Station-14
py RUN_THIS.py
dotnet build --os linux
cd bin/Content.Server
```
Далі, для запуску серверу, в папці UA-Space-Station-14/bin/Content.Server, запустіть Content.Server.exe
P.s. Також для Windows потрібно завантажити [git](https://git-scm.com/downloads), [python](https://python.org), [dotnet7](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- - -
### Changelog
06.10.2023 19:00 - Створення репозиторію
