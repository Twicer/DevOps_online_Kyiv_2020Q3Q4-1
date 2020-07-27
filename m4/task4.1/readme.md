<b>Топологія 1</b> <br />
Концентратор та 4 ПК <br />
![alt text](/m4/task4.1/1.PNG) <br />

Пакети передалися успішно <br />
![alt text](/m4/task4.1/2_PDU.PNG) <br />

Перегляд інформації про пакети <br />
![alt text](/m4/task4.1/3_PDUinfo.PNG) <br />

Без прописаних ІР-адрес, пакети в мережі не передаються <br />
![alt text](/m4/task4.1/4_PDU.PNG) <br />

<b>Топологія 2</b> <br />
Пакети передаються усіпшно проходячи шлях через 2 концентратори <br />
![alt text](/m4/task4.1/5.PNG) <br />

<b>Топологія 3</b> <br />
Комутатор та 4 ПК <br />
![alt text](/m4/task4.1/6.PNG) <br />

Перегляд інформації про пакети <br />
![alt text](/m4/task4.1/7.PNG) <br />

Відмінності роботи Топології 1 та Топології 3 полягають у алгоритмі роботи таких пристроїв як концетнратор та комутатор. Концентратор прцює на першому(фізичному) рівні моделі OSI; передає пакети з одного порту на всі інші доступні порти. Комутатор працює на другому(канальному) рівні моделі OSI, використовуючи МАС-адреси та зберігає їх у таблиці комутації. Завдяки цьому пакети передаються від комутатора не на всі доступні порти. а лише на той, який вказаний як отримувач. <br />

<b>Топологія 4</b> <br />
Два комутатори та 8 ПК <br />

Для під'єднання 4 ПК до одного комутатора використовуємо додатковий порт Ethernet <br />
![alt text](/m4/task4.1/8.PNG) <br />

Паекти передіються успішно в одній підмережі, проходячи шлях через 2 комутатори <br />
![alt text](/m4/task4.1/9.PNG) <br />

<b>Топологія 5</b> <br />
Маршрутизатор, 2 комутатори та 8 пк з двома підмережами (192.168.0.5 та 192.168.1.5) <br />

Прописуємо ІР-адреси для ще однієї підмережі <br />
![alt text](/m4/task4.1/10.PNG) <br />

Прописуємо шлюз для кожного ПК з відповідною підмережею <br />
![alt text](/m4/task4.1/11_Gateway.PNG) <br />

Оцінюємо роботу побудованої мережі - пакети передаються успішно <br />
![alt text](/m4/task4.1/12.PNG) <br />

Отже, маршрутизатор працює на 3(мережевому) рівні моделі OSI та використовує ІР-адреси для передачі даних в мережі. Цей пристрій дозволяє поєднувати підмережі в одну мережу, чого не можна зробити за допомогою концетратора або комутатора.