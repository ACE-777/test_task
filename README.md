# test_task
Рассмотрим силы действия на движущийся обьект:

>![Диаграмма без названия drawio](https://user-images.githubusercontent.com/55112338/193457381-d098293c-e568-46c4-9134-94f9a689a750.svg)
```
Fd-силы сопротивления воздуха; Fm-сила Магнуса;G-сила гравитации.
```
Теперь же представим трехмерную систему координат с началом координат в точке стояния камеры:

>![Диаграмма без названия drawio (1)](https://user-images.githubusercontent.com/55112338/193457586-74219f74-d5ae-4751-8e04-91339dad9682.svg)

#
Запишем систему дифференциальных уравнений:
>![image](https://user-images.githubusercontent.com/55112338/193460768-92d9e515-b4c7-4a4e-a290-15147ec630a5.png)
#
Решим каждый из диффуров:
>![image](https://user-images.githubusercontent.com/55112338/193461454-d1249dba-ab06-4bbe-806e-3b9e70b7c4d0.png)
#
В итоге получаем 8 неизвесетных:
>![image](https://user-images.githubusercontent.com/55112338/193461069-567e61d8-0e93-42cb-971a-676e535da77a.png)
#
Мы имеем уравнения переводящие трехмерную систему координат в двухмерную систему камеры:
>![image](https://user-images.githubusercontent.com/55112338/193461383-1b2b4ee8-087b-4342-8dd5-152f95118d1b.png)
#
Мы имеем координаты в системе камеры соотвествующие времени:
>![image](https://user-images.githubusercontent.com/55112338/193462134-8da1b18f-6f78-4535-b38d-a89dd538a94e.png)
#
тогда получается с начальными даннами координат в системе камеры и времени, требуется разрешить систему:
>![image](https://user-images.githubusercontent.com/55112338/193461671-37eb171f-0e0e-4b98-9b41-47118ea0a059.png)

