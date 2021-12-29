# ботнетик

## Для Windows
### Установка

для установки скачиваем с официального сайта [Python](https://www.python.org/downloads/) самой новой версии (текущая 3.9.6)

качаем питон последний, ставим галочку add to path, качаем сурсы и запускаем батник


---

## Для Termux (Android)

### Установка
```
apt-get update -y ; apt-get install python -y ; apt-get install git -y ; curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py ; python3 get-pip.py ; rm get-pip.py ; git clone https://github.com/n3k0parad1se/botnet ; cd Botnet ; termux-wake-lock ; pip3 install -r requirements.txt ; python3 bot.py
```

### Запуск
```
termux-wake-lock && python bot.py
```
---

## Для Linux

### Установка
открываем терминал, устанавливаем Python и Git
```
apt install python3 git
```
```
(на арче-подобных)
sudo pacman -S python3 git
```


клонируем репозиторий
```
git clone https://github.com/n3k0parad1se/botnet.git
```

переходим в директорию с юзерботом
```
cd Botnet
```

устанавливаем зависимости
```
pip3 install -r requirements.txt
```

запускаем файл через питон
```
python3 bot.py
```



### Запуск

в терминале
```
cd Botnet && python3 bot.py
```
---
## [telegram](https://t.me/maidl1nks) 
