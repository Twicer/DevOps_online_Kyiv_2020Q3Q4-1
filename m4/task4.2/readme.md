<b>Завдання 1</b> <br/>
Необхідно змоделювати корпоративну мережу організації, яка містить 2 будинки по 2 поверхи в кожному. Горизонтальна підсистема поверху складається з однієї робочої групи по 5 комп'ютерів. Провести аналіз працездатності мережі і її трафіку.<br/>

Для моделювання мережі із чотирьма підмережами було обрано один маршрутизатор із 4 портами для оптоволокна та 4 комутатори, які з'єднані через FastEthernet  із 5 ПК кожен відповідно <br/>
![alt text](/m4/task4.2/Network.PNG) <br />

Маршрутизатор було доповнено двома додатковими оптичними модулями для можливості підключення 4 комутаторів <br />
![alt text](/m4/task4.2/OpticModule.PNG) <br />

Також було доповнено кожен з комутаторів одним FastEthernet портом для можливості підключення 5 ПК до кожного комутатора <br />
![alt text](/m4/task4.2/FaModule.PNG) <br />

Для кожного ПК було прописано унікальну ІР-адресу та відповідний шлюз <br />
![alt text](/m4/task4.2/Gateway.PNG) <br />

Для перевірки працездатності мережі було відправлено пакети даних. Спостерігаємо, що пакети передаються в мережі  <br />
![alt text](/m4/task4.2/Run.PNG) <br />

Також я побудувала інший варіант мережі, використовуючи 2 маршрутизатори. Перший варіант мережі можна використовувати, вважаючи, що будівлі знаходяться поруч. Другий - при їхньому розміщенні у різних частинах міста. <br />
![alt text](/m4/task4.2/Routers.PNG) <br />

<b>Посилання на файли проекту:</b> <br />
https://github.com/remaieva/DevOps_online_Kyiv_2020Q3Q4/blob/master/m4/task4.2/task4.2_1.pkt <br />
https://github.com/remaieva/DevOps_online_Kyiv_2020Q3Q4/blob/master/m4/task4.2/task4.2_1(2).pkt <br />

<b>Завдання 2</b> <br/>
Необхідно змоделювати корпоративну мережу організації, яка містить 1 будинок з чотирма поверхами. Горизонтальна підсистема поверху складається з двох робочих груп по 3 і 5 комп'ютерів відповідно. Провести логічну структуризацію мережі на 8 підмереж (відповідно до кількості робочих груп). Провести аналіз працездатності мережі і її трафіку. <br/>

Змодельовано мережу, яка містить 8 підмереж за допомогою комутаторів  <br />
![alt text](/m4/task4.2/Network(2).PNG) <br />

Прописуємо влани на відповідних портах комутаторів switch 0, 1, 2, 3.  <br />
![alt text](/m4/task4.2/Vlan_conf.PNG) <br />

Проводимо конфігурацію вланів на відповідних портах для всіх 8 підмереж <br />
![alt text](/m4/task4.2/Vlan_fa.PNG) <br />

Перевіряємо правильність налаштування вланів <br />
![alt text](/m4/task4.2/Vlan_brief.PNG) <br />

Налаштовуємо центральний комутатор, а саме транк порти для відповідних вланів <br />
![alt text](/m4/task4.2/Central.PNG) <br />

Кінцева конфігурація для портів центрального комутатора <br />
![alt text](/m4/task4.2/Central_conf.PNG) <br />

Проводимо аналіз працездатності мережі <br />
![alt text](/m4/task4.2/Ping.PNG) <br />
Як бачимо пінг проходить на пк в одній підмережі та не проходить в різних <br />

<b>Посилання на файл проекту:</b> <br />
https://github.com/remaieva/DevOps_online_Kyiv_2020Q3Q4/blob/master/m4/task4.2/task4.2_2.pkt<br />

<b>Завдання 3</b> <br/>
Необхідно змоделювати локальну мережу комплексу з 5 одноповерхових будівель. Одна будівля - 1 робоча група по 6 комп'ютерів. Мережа будується на основі маршрутизатора з одним портом. <br/>

Було змодельовано мережу, яка містить 5 підмереж та 5 вланів відповідно 10, 20, 30, 40 та 50 <br />
![alt text](/m4/task4.2/net.PNG) <br />

Налаштовуємо комутатори 0, 1, 2, 3, 4. Назначаємо влани інтерфейсам
![alt text](/m4/task4.2/vlan.PNG) <br />

Призначаємо пк ІР-адреси згідно назначених вланів <br />
![alt text](/m4/task4.2/comp.PNG) <br />

Налаштовуємо центральний комутатор, а саме транк порт <br />
![alt text](/m4/task4.2/switch-trunk.PNG) <br />

Налаштовуємо сабінтерфейси на маршрутизаторі <br />
![alt text](/m4/task4.2/sub.PNG) <br />

Перевіряємо доступність мережі <br />
![alt text](/m4/task4.2/ping_m.PNG) <br />
Спостерігаємо, що на пк з відповідним вланом пінгується відповідний сабінтерфейс на маршрутизаторі <br />


<b>Посилання на файл проекту:</b> <br />
https://github.com/remaieva/DevOps_online_Kyiv_2020Q3Q4/blob/master/m4/task4.2/task4.2_3.1.pkt<br />
