# openalpr_ru
Собрал со всего что смог. Распознает номера. 
![image](https://github.com/billib0bs/openalpr_ru/assets/10768758/6b41b104-06ea-4038-9861-b9f1a6ab45f1)


Осталось разобраться с распознование из потока rtsp. Не могу понять почему не работает с камерой bosch dinion ner-l2


Для дебага необходимо включить опцию debug_show_images = 1 в файле openalpr.conf
Запускать alpr.exe -c ru --debug image.jpg
