# Глушилка WiFi на базе Arduino

Компоненты моей глушилки: 
- плата Nodemcu Lua Wi-Fi (Esp8266)
- модуль зарядки литиевых аккумуляторов с type C
- 3 светодиода
- внешняя антена
- кнопка
- аккумулятор со старого телефона samsung

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/components.jpg)

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/case.jpg)

Процесс изготовления платы: 

1) На первом этапе необходимо сформировать макет печатной платы. Для этого берем листик, карандаш и рисуем предполагаемое расположение дорожек, затем фотографируем результат и скидываем полученную фотографию на компьютер. С помощью Microsoft Word обводим полученное изображение примитивными фигурами с целью получить более качественный макет. Полученный макет распечатываем на глянцевой бумаге лазерным принтером.

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/model.jpg)

2) Распечатанный макет обрезаем до нужного размера и прикладываем к чистой печатной плате. Используя утюг переводим краску с бумаги на плату, для этого прогреваем лист с макетом лежащий на плате. Места, где краска плохо перенеслась можно подкрасить, например с помощью лака для ногтей.

3) На третьем этапе необходимо подготовить раствор для травления. У нас он будет состоять из двух ингридиентов - лимонная кислота и перекись водорода. 

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/ingredients.jpg)

Окунаем нашу плату в полученный раствор.

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/board1.jpg)

Спустя недолгое время пойдет химическая реакция с обильным выделением пузырьков.

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/board2.jpg)

4) После того как раствор растворил покрытие платы в ненужных местах вынимаем плату и удаляем краску с дорожек при помощи спирта или растворителя. Чтобы убедиться что все ненужное растворилось можно прозвонить дорожки с помощью мультиметра. Далее необходимо просверлить отверстия под крепление электронных компонентов. 
Я изготавливал плату таким способом впервые, поэтому не судите строго, свою функцию плата выполняет.

![Image alt](https://github.com/ArtemAvanesov/Arduino-WIFI-Jammer/raw/master/Изображения/board3.jpg)
