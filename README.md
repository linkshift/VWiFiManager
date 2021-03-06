# Virtual Wi-Fi Manager

## Информация

Простое приложение для создания Wi-Fi сети.

Основные функции:
* Управление виртуальной сетью.
* Настройка раздачи интернета в виртуальной сети.
* Автоматический запуск сети.
* Автоматический старт при включении системы.
* Сворачивание программы в системный трей.
* Предотвращение перехода в режим сна при бездействии системы.

## Установка

* Программой поддерживаются следующие системы: Windows 7, Windows 8, Windows 8.1, Windows 10.
* Требуется аппаратная поддержка Virtual Wi-Fi.

[Скачать установщик](https://github.com/rensatsu/VWiFiManager/raw/master/Setup/VWiFiManager_Setup.exe)


## Настройка
### Первоначальная настройка программы

1. Скачайте и установить программу.
2. Введите название сети и пароль сети в соответствующие поля.  
  (минимальная длина пароля - 8 символов)
3. Запустите сеть кнопкой "Старт".
4. Нажмите на кнопку "Настройка раздачи интернета".
5. В окне "Connection Sharing Manager" в поле "Shared connection" выберите адаптер, к которому подключен интернет.
6. В поле "Home connection" выберите адаптер виртуальной сети (обычно имеет название "Wireless Network Adapter 2" или "Беспроводная сеть 2".
7. Нажмите "Apply", а затем "Close".

### Запуск сети

1. Запустите программу.
2. Запустите сеть кнопкой "Старт".


### Остановка сети

1. Запустите программу.
2. Остановите сеть кнопкой "Стоп".


## Исходный код
Исходный код приложения распространяется на условиях [Unlicense](LICENSE.txt).

В программе так же используется [Internet Connection Sharing Manager](https://github.com/utapyngo/icsmanager) для управления раздачей интернета.
