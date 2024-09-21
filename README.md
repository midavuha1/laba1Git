                    Лабораторная работа №1 по работе с git
                            Ход работы.
1) Выполнил подготовительный этап и пункты 1-8.
   Получилась такая история веток:
   
   ![image](https://github.com/user-attachments/assets/56c9b1bf-7dd6-4fd6-b6d4-2cd815f9f29f)
   
   История журнала для 4 пункта:
   
   ![image](https://github.com/user-attachments/assets/62a0012b-5bb1-4a2d-87af-6202134b83f1)
   
   Разница между 1 и 3 коммитами для 5 пункта:
   
   ![image](https://github.com/user-attachments/assets/d38aad7c-c4de-4d94-9e47-d7ab286d6fa1)
2) Выполнил пункты 9-10:
   Создал новый локальный репозиторий и воссоздал структуру показанную в пункте 9:

   ![image](https://github.com/user-attachments/assets/20310d6e-4354-45da-8ca5-bc52e55fcb5b)

   С помощью merge сделал пункт a(без конфликтов):

   ![image](https://github.com/user-attachments/assets/3dbe5889-4a9e-48f7-8c62-fcbaa6f323a8)

   C помощью rebase сделал пункт b(без конфликтов):

   ![image](https://github.com/user-attachments/assets/06cb83c4-d120-4596-b4a4-ac243b61ee5b)

   Допустим файл который мы создали в c1 и изменили в нём 1 строку в c3, а в ветке test в c5 изменили 1 строку этого же файла то получим конфликт:

   ![image](https://github.com/user-attachments/assets/9795a3f4-bc99-4c97-90b2-662b92253ce9)

   ![image](https://github.com/user-attachments/assets/a87408d7-966f-414e-b6da-fb5b1ae34946)

    Решаем конфликт, делаем коммит и слияние происходит:

   ![image](https://github.com/user-attachments/assets/a6af6686-2fc4-44ac-b72d-e2c3bacaa1e7)

   ![image](https://github.com/user-attachments/assets/79e19841-9960-49ea-b0f4-df13c2b6fc7d)

   ![image](https://github.com/user-attachments/assets/6575aee2-4c5b-4368-8446-1200ca9a058c)

   Для 10 пункта меняю два файла и фиксирую изменнения в одном коммите:
   
   ![image](https://github.com/user-attachments/assets/eb18cafc-94c7-4699-8967-1101ae1d852d)

4) Выполнил 11 пункт.
   Для этого создал новый локальный репозиторий и привёл его к состоянию на следующем скриншоте:
   
   ![image](https://github.com/user-attachments/assets/532b210f-c7ce-46d7-8905-fdc694938538)

   после с помощью rebase слил ветку мастер с client:

   ![image](https://github.com/user-attachments/assets/ba8b6348-ca2c-41f1-8702-fdd33a42a993)

   далее аналогично c server:

   ![image](https://github.com/user-attachments/assets/09215d8f-1a49-4cda-83bb-e58522c36b2e)






   
   



   

   

