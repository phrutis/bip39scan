## bip39scan - Brute Pool
![o1AJ9qDyyJNSpZLSMmjZp1oHDUkVhqVqHnDVdzwQYjHMFBpSr](https://github.com/phrutis/bip39scan/assets/140947743/5e506934-c615-4fa9-aa1a-d3a41e16ff5f)

This pool will be the fastest search pool in the world, using the latest GPU libraries and having a programmer stand by the project through testing.<br>

We managed to achieve a speed of 3090 = 5M/s (5000000 seed/s)<br>

We are currently looking ETH addresses from $1<br>
Random mnemonic 12 words, bip44, patch m/44'/60'/0'/0/0-9
<br>
Web statistics: http://bip39scan.com

If you are ready to search with us 24/7, join us.<br>

Telegram: https://t.me/+k1jKsx_fxTo1MzQx<br>
Launch, Connection and Questions will be posted in Group.<br>
## Performance

| GPUs card     | Speed   |
|---------------|---------|
| RTX 4090      | 11 M/s  |
| RTX 3090      | 5.5 M/s |
| RTX 3080 Ti   | 5.3 M/s |
| Tesla V100    | 3.7 M/s |
| CMP 50HX      | 3.6 M/s |
| RTX 3070      | 3.5 M/s |
| RTX 3050      | 1.5 M/s |
| RTX 2060      | 1.5 M/s |

*M (million seeds per second)

Miners to share 50% of find based on contribution.<br>
There are no finder rewards since this works on a group effort.<br>
Organizers 30%<br>
Pool 20%

## Run
### Ubuntu Client
Terminal<br>
wget http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip<br>
Extract<br>
cd Bip39Scan-Linux<br>
chmod +x ./bip39scan<br>
./bip39scan -s 96.56.157.172 -u "enter_name_here_no_quotes"<br>


### Vast 4090/3090/3080/3070
cuda:12.0.1-devel-ubuntu20.04<br>
Use Jupyter Lab interface<br>
Terminal<br>
wget http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip<br>
sudo apt-get install unzip<br>
unzip Bip39Scan-Linux.zip<br>
cd Bip39Scan-Linux<br>
chmod +x ./bip39scan<br>
./bip39scan -s 96.56.157.172 -u "enter_name_here_no_quotes"<br>


### Windows
http://www.bip39scan.com/downloads/Bip39Scan-Windows.zip<br>
unzip<br>
CMD prompt into folder Bip39Scan-Windows<br>
bip39scan.exe -s 96.56.157.172 -u "enter_name_here_no_quotes"<br>


### HIVEOS 
(This will be easier in the future)<br>
```sudo mkdir BIP39SCAN && cd BIP39SCAN && sudo apt install libboost-all-dev && sudo apt install aria2 && sudo apt install unzip && sudo aria2c http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip && unzip bip39scan_linux.zip && cd Bip39Scan-Linux && chmod +x bip39scan && ./bip39scan -s 96.56.157.172 -u YouNick```

## bip39scan - брут мнемонических фраз bip39.

🚀 Это самым быстрый пул в мире. 🚀<br>
В программе используются быстрые алгоритмы и библиотеки.<br>
Нам удалось достичь скорости RTX 3090 = 5М/с (5000000 seed/сек)<br>
Мы сейчас ищем ETH адреса от $1.<br>
Рандом BIP44 12 слов.<br>
Патч m/44'/60'/0'/0/0-9


### Условия выплат 💰
50% баланса от находки выплачиваются тому кто нашел мнемоническую фразу.<br>
30% баланса получают организаторы пула.<br>
20% от баланса делится на всех охотников, кроме победителя.

Если вы готовы искать вместе с нами 24/7, присоединяйтесь.<br>
Telegram: https://t.me/+k1jKsx_fxTo1MzQx

## Запуск программы
### Ubuntu Client
Terminal<br>
wget http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip<br>
Распаковать<br>
cd Bip39Scan-Linux<br>
chmod +x ./bip39scan<br>
./bip39scan -s 96.56.157.172 -u Vasya<br>


### Vast 4090/3090/3080/3070
cuda:12.0.1-devel-ubuntu20.04<br>
Use Jupyter Lab interface<br>
Terminal<br>
wget http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip<br>
sudo apt-get install unzip<br>
unzip Bip39Scan-Linux.zip<br>
cd Bip39Scan-Linux<br>
chmod +x ./bip39scan<br>
./bip39scan -s 96.56.157.172 -u Petya<br>


### Windows
http://www.bip39scan.com/downloads/Bip39Scan-Windows.zip<br>
unzip<br>
CMD prompt into folder Bip39Scan-Windows<br>
bip39scan.exe -s 96.56.157.172 -u Andrey255<br>


### HIVEOS 
(This will be easier in the future)<br>
```sudo mkdir BIP39SCAN && cd BIP39SCAN && sudo apt install libboost-all-dev && sudo apt install aria2 && sudo apt install unzip && sudo aria2c http://www.bip39scan.com/downloads/Bip39Scan-Linux.zip && unzip bip39scan_linux.zip && cd Bip39Scan-Linux && chmod +x bip39scan && ./bip39scan -s 96.56.157.172 -u Nickname```

### Часто задаваемые вопросы ❓

**Я подключился. Программа зависла Connected**
<br>
Ждите идет синхронизации адресов.<br>
Обычно это длится до 10 минут, и больше.<br>
Это зависит от вашего оборудования и скорости интернет. Может доходить до 20 мин.<br>
Дождитесь окончания синхронизации адресов, программа запустится автоматически.

**У меня не запускается программа, ошибка..**
<br>
Скачайте самые новые (почледние) драйвера для вашей видеокарты.<br>
Если проблема не исчезла напишите об этом в чате. Телепатов в группе нет, сделайте скриншот окна программы с ошибкой.

**Как сделать скриншот?**
<br>
Windows Нажмите Ctrl + PrtSc, откройте Point Ctrl + v обрезать и отправить в группу.

**Как узнать что я нашёл seed?**
<br>
На сайте bip39scan.com ⭐ будет мигать жёлтым цветом.<br>
В окне вашей программы будет написано Found: найденный вами адрес.<br>
Этот адрес является вашим подтверждением что находку нашли именно вы.<br>
Адрес не нужно офишировать (писать в чате группы)<br>
Вам нужно написать одному из админов в телеграм для получения выплаты.

**Как мне рассчитать свой % от пула? 
Как делится находка?**
<br>
Вот вам наглядный пример распределения находки:<br>
Vasya нашел адрес $150000<br>
Делается скриншот статистики и отправляется в чат для фиксации % от пула.

Vasya получает $75000 (50%)<br>
Админы получают $45000 (30%)<br>

20% от пула - это $30000 (100%)<br>
К примеру ваш % в таблице статистики составляет 4.73972%<br>
(% высчитывается на основе кол-ва пройденных комбинаций тотал от последнего сброса)<br>
Вы получите $1421, это покроет часть ваших расходов на электричество и другое<br>
Победитель Vasya не получает % от пула! Его % от пула идёт на оплату коммисий транзакций выплат.<br>
Если после всех выплат у него останутся монеты, они снова будет разделены между охотниками.

**Куда пропала статистика на сайте**
<br>
Каждые сутки (00:00 мск) статистика сервера сбрасывается

**Как указать определённые карты?**
<br>
Добавьте в строку запуска -d 0,5,6,7<br>
Список карт начинается от 0.<br>
Укажите нужные карты через запятую
