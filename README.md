# BybitFutures
trading bot for exchange Bybit

Бот для торговли на криптобирже Bybit фьючерсами USDT Perpetual (аналог BinFutures-19).   
Можно выбирать реальную или тестовую биржу (https://testnet.bybit.com/).    

Запуск бота на VPS с ubuntu
1. Подключаемся к серверу и по умолчанию находимся в корневом каталоге.
2. Создаем новую папку (например, с именем BybitFutures) командой:  
mkdir BybitFutures
3. Создаём новую screen-сессию (назовем, например, тоже BybitFutures) для  бота командой:  
screen -S BybitFutures
4. Заходим в папку BybitFutures командой:  
cd BybitFutures
5. Скачиваем бота в папку BybitFutures командой:  
wget https://github.com/ebot732/BybitFutures/releases/download/BybitFutures-19/BybitFutures-19
6. Даём права на запуск бота командой:  
chmod 755 BybitFutures-19
7. Запускаем  бота командой:  
./BybitFutures-19  
и следуем подсказкам.
8. Выходим из работающего screen, не прерывая его работу, командой:  
ctrl+a, d (при нажатой ctrl жмем а, отпускаем их, и затем жмем d)

Далее, чтобы зайти в screen работающего бота, введите команду:  
screen -x BybitFutures  
То есть, второй раз вводить  
screen -S BybitFutures   
не нужно, а то создастся еще одна screen-сессия.
