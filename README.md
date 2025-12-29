# Инструкция по запуску StylishAlarmClock.jar

## Требования
1. Установлен Java Runtime Environment (JRE) или Java Development Kit (JDK) версии 8 или выше.
   - Проверить установку Java можно командой:
     java -version
   - Если Java не установлена, скачайте и установите с официального сайта:
     https://www.java.com/ru/download/

2. Скачать файл `StylishAlarmClock.jar` с GitHub:
   https://github.com/ovruch0909-hub/StylishAlarmClock.jar

## Запуск на Windows / Linux / Mac
1. Откройте терминал (Command Prompt на Windows или Terminal на Linux/Mac).
2. Перейдите в папку, где находится `StylishAlarmClock.jar`. Например:
   cd C:\Users\ВашеИмя\Загрузки
   или
   cd /home/username/Downloads
3. Запустите программу командой:
   java -jar StylishAlarmClock.jar

## Запуск на Android через Termux
1. Установите Termux и убедитесь, что есть Java:
   pkg install openjdk-17
2. Скачайте `StylishAlarmClock.jar` в Termux.
3. Перейдите в папку с файлом:
   cd /data/data/com.termux/files/home/Downloads
4. Запустите командой:
   java -jar StylishAlarmClock.jar

## Возможные проблемы
- Ошибка "java not found" → Java не установлена или не добавлена в PATH.
- Ошибка "unsupported major.minor version" → версия JRE ниже, чем требуется. Установите более новую версию Java.

## Примечания
- Программа должна запускаться как обычное Java GUI-приложение.
- Для закрытия программы используйте крестик окна или сочетание Alt+F4 (Windows) / Cmd+Q (Mac).
