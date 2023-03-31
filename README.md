# Описание
Если количество ингредиентов не кратно количеству людей, то образуется остаток, который не отображается в результате расчета программы.

# Локализация дефекта
https://github.com/Kanger79/HW_7.1_1/blob/5d808861d711ef78a9c46ea865aba82166e5e891/src/Main.java#L8

# Шаги воспроизведения

1. Открыть [код программы](https://github.com/Kanger79/HW_7.1_1/blob/main/src/Main.java) в IntelliJ IDEA
2. Установить значение переменной 'eaters' (количество людей) равным 5
3. Установить значение переменной 'chicken' (куриное бедро) равным 6
4. Запустить программу
5. Посмотреть на вывод результата в консоли

***
***Ожидаемый результат:*** Вывод 1,2 куриных(ое) бёдер(ро)

***Фактический результат:*** Вывод 1 куриных(ое) бёдер(ро)
***
# Скриншот
![image](https://user-images.githubusercontent.com/127352228/229197336-ed344993-e6d9-42ed-b6a2-f6799f59eeca.png)

***
# Окружение
***Операционная система:*** Windows 10

***IDE:*** IntelliJ IDEA 2023.1 (Community Edition)

***Java:*** OpenJDK 11