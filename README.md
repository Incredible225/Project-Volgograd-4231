
Что было сделано?
в файле "Проект_BugrovTeam" были загружены файлы и создан единый датасет в формат сырых данных
дискретная сетка координат , кодирование в разных левелах
в файле "Проект_BugrovTeam" -Токенизирование текстовых полей и превращение их в "смысловые"
![image](https://user-images.githubusercontent.com/65441571/183564536-027cdd81-959b-43b0-9a72-7a9f3f4d12b9.png)
![image](https://user-images.githubusercontent.com/65441571/183577815-762fc5af-8f86-4acb-81a9-e4c09a9053df.png)
координаты проблемных районов с количеством случаев выявлены
Построение карт по всем типам событий с переходом по каждому типу, для дробления датасета на состовляющие
![Волгоград , проблематика](https://user-images.githubusercontent.com/65441571/183589029-0b742ef4-49ad-46dd-b15f-c7fc4b2d6489.jpg)


Таблица проблем го
Проект_BugrovTeam.ipynb  Файл для загрузки датасета и формирование единой таблици и
кодирования имеющегося датасета дискретной сеткой от Yandex 
анализа ГЕО данных с обратным геокодированием


Облако слов из чата Волгоград.Здоровье

Был проанализирован весь датасет в 2.5М данных.
Таким образом при  агрегации данных дискретными сетками удалось качественно обобщить данные.  
При помощи обратного геокодирования были выявлены адреса проблемных центров по всем!!! направлениям.Красный цвет, более насыщенная концентрация случаев, желтая слабее, зеленый есть случаи, но не так много.
При анализе обнаружилась странная тенденция, очень частые случаи замечены в гексагонах с координатами  (48.63005022668863, 44.43260132279729) и 48.82528837873723, 44.75489543424276) , что говорит либо о некорректных координатах, либо о концентрации негативных тенденций и трендов в этих районах.
Данные с картами по всем выявленным разделам находятся в папке Map


Полное описани находится в файле "Отчёт"




