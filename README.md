# Arduino-RFID-iButton-Duplicator_RUS
  Копировальщик ключей для домофона RFID с OLED дисплеем и хранением ключей в памяти EEPROM
  Авторы: 
  МЕХАТРОН DIY, AlexMalov, 2019 https://github.com/AlexMalov/EasyKeyDublicatorRFID_OLED/
  
  SibMan54, 2023 https://github.com/SibMan54/Arduino-RFID-iButton-Duplicator
  
  mystarwolf, 2026 https://github.com/mystarwolf/Arduino-RFID-iButton-Duplicator_RUS
  
  ---
  За основу взят код SibMan54:
  1. Для OLED-дисплея теперь используется библиотека GyverOLED;
  2. Выводимые на дисплей сообщения переведены на русский язык. Текст сообщений подогнан под разрешение 128x32.
  3. Улучшена логика определения некоторых китайских болванок типа Dallas, при чтении/записи которых раньше выводился пустой тип;
  4. Задержка запуска уменьшена до 1,5 сек.;
  5. Добавлена заставка при смене режима работы;
  6. В режиме очистки MIFARE-ключей вместо списка ключей из памяти показывается текстовая подсказка.
  ---
  
# Необходимые компоненты
  !Ардуину нужно брать на Atmega328P на 168-ю не влезит!  
  Arduino Nano https://alii.pub/6ms6vk   https://alii.pub/6ms6yv   https://alii.pub/6ms70f  
  Arduino ProMini https://alii.pub/6ms72y  
  RC522 модуль https://alii.pub/6ms75a   https://alii.pub/6ms7ac   https://alii.pub/6ms7bb  
  Повышающий модуль с ЗУ Li-ion https://alii.pub/6ms7f7   https://alii.pub/6ms7hc   https://alii.pub/6ms7ii  
  Плата зарядки Li-ion https://alii.pub/6ms7me   https://alii.pub/6ms7ox   https://alii.pub/6ms7r9   https://alii.pub/6ms7u6  
  Энкодер   https://alii.pub/6ms80l   https://alii.pub/6ms852   https://alii.pub/6ms89q лучше брать именно такие (прямоугольные как на схеме НЕ БРАТЬ - они плохо работают)  
  Брелки заготовки   13.5мГц https://alii.pub/6msc7a   https://alii.pub/6mscbd  125кГц  https://alii.pub/6msche  
  
  ![Схема подключения](Scheme.png)  
  
  Вид устройства в моем исполнении, корпус напечатан на 3D принтере, файл модели лежит в папке "BOX"  
  [![Видеообзор устройства](/BOX/Photo7.jpg)](https://youtu.be/deiOaTfzMO0)  
  ![alt text](/BOX/Photo1.jpg)  ![alt text](/BOX/Photo3.jpg)  ![alt text](/BOX/Photo4.jpg)  
