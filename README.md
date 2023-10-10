# UA-Space-Station-14
Українська версія Space Station 14
- - -
### Про українську версію SS14 (Space Station 14)
Це не офіційний переклад SS14 з видаленням контенту країни-агрессора та деякими поліпшеннями.
- - -
# Використання
Якщо ви не розробник та хочете створити сервер для гри з друзями/для глобальної гри, то просто завантажте потрібну версію серверу з релізів, розпакуйте та запустіть потрібний файл ( Windows: /Content.Server.exe , Linux: Content.Server )

Якщо ви розробник, хочете завантажити та скомпілювати сервер, виконайте ці команди в консолі:
### Linux:
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
### Windows:
```
git clone https://github.com/Lines115/UA-Space-Station-14.git
cd UA-Space-Station-14
py RUN_THIS.py
dotnet build --os linux
cd bin/Content.Server
```
Далі, для запуску серверу, в папці UA-Space-Station-14/bin/Content.Server, запустіть Content.Server.exe

P.s. Також для Windows потрібно завантажити [git](https://git-scm.com/downloads), [python](https://python.org/downloads), [dotnet7](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
- - -
# Допомога
Якщо ви розробник та хочете допомогти в розробці не офіційного перекладу, пишіть мені на пошту: lines115@duck.com
Якщо ви не розробник та хочете допомогти в розрозбці не офіційного перекладу, можете стати моїм спонсором на github
- - -
### Changelog
06.10.2023 19:00 - Створення репозиторію

07.10.23 17:10 - Перший білд: v0.1: Back & Ears перекладені

10.10.23 20:33 - Другий білд:

Велике оновлення:
1. Перекладено практично все, що пов'язано з головою.
2. Перекладено: Пояси, Все що пов'язано з очима, Все що пов'язано з руками.
3. Додано поки не робоче худі. Його робота в процесі
4. Додано робочу збірку на github. Якщо щось не працює, спробуйте ще раз.
Дякую за підтримку (Якої немає), допомогу (Якої також не має) та використання цього білда (Цього теж немає...) !

### Подяки
**Yastoch** за спрайти до худі та деякі коректування перекладу (Discord: yastoch)

### Слава Україні!
