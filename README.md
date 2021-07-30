# GarticPicture
GarticPicture - программа для читерной загрузки картинок в браузерной игре [Gartic Phone](https://garticphone.com).
# Подключение
Для подключения бота к лобби нужно узнать адрес WebSocket'а. Для этого нужно:
* Подключиться лобби перейдя по ссылке (кнопку "ВОЙТИ" нажимать не надо). Как пример - https://garticphone.com/ru/?c=27092f137
* Нажать f12, перейти во вкладку сеть и отфильтровать по WS.![step1](https://user-images.githubusercontent.com/88092386/127359675-6d04c93e-a45b-46eb-a921-b8db60c93a41.jpg)
* Нажать кнопку "ВОЙТИ" и в сети появится подключение. Две цифры после "sv-" вписываем в программу в поле "Socket". Затем можно закрыть консоль.![step2](https://user-images.githubusercontent.com/88092386/127360025-a8dd4bf4-4069-4467-b454-f3b700c6e4d8.jpg)
* В поле Room code вписываем цифры в приглашении после "=". В нашем случае - 27092f137.![step3](https://user-images.githubusercontent.com/88092386/127362093-b74f528c-fbe2-4a29-9e89-eab04cb13e30.jpg)
* Нажимаем "Connect" и бот подключен к лобби.
# Использование
Все картинки кидать в папку "Img". Не рекомендуеться хранить в Img больше 30 картинок (обновляются в программе динамически).  
Кнопка "Start" - отправляет выбранную картинку.  
Кнопка "Send" - отправляет текст введеный в поле выше.  
Кнопка "Done" - подтверждает готовность (нажимать не обязательно, после каждого действия она жмется автоматически).  
Animation mode - переключает на режим рисования кистью для режима анимации (требует немного больше времени на отправку и увеличивает нагрузку на устройства игроков)  

[Скачать](https://github.com/Megum13/GarticPicture/releases/download/v1.2/GarticPicture.rar)
