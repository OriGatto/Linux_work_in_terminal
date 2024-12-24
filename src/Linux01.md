<h2>Part 1. Установка ОС</h2>
<p>Узнайте версию Ubuntu, выполнив команду cat etc/issue</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_1().png">

<h2>Part 2. Создание пользователя</h2>
<p>Вставьте скриншот вызова комманды для создания пользователя</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_2(0).png">

<p>Добавление в группу adm</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_2(1).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_2(2).png">

<p>новый пользователь должен быть в выводе комманды cat /etc/passwd</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_2(3).png">

<h2>Part 3. Настройка сети ОС</h2>
<p>Задать название машины вида user-1</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(0).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(1).png">

<p>Установить временную зону, соответствующуюю вашему текущему местоположению.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(2).png">

<p>Вывести название сетевых интерфейсов с помощью консольной команды.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(3).png">

<p>Один из самых основных виртуальных интерфейсов - lo. Это локальный интерфейс, который позволяет программам обращаться к  этому компьютеру. Используя консольную команду получить ip адрес устройства, на котором вы работаете, от DHCP сервера.</p>
<p>Установка</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(4).png">

<p>Используя консольную команду получитьь ip адрес устройства, на котором вы работаете, от DHCP сервера.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(5).png">

<p>DHCP - это клиент-серверный протокол динамической конфигурации хоста(Dynamic Host Configuration Protocol), с помощью которого в IT-инфраструктуре сетевые параметры каждого нового устройства прописываются автоматически.</p>
<p>Определить и вывести на экран внешний ip-адрес шлюза (ip) и внутренний IP-адрес шлюза, он же ip-адрес по умолчанию (gw)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(6).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(7).png">

<p>Задать статичные (заданные вручную, а не полученные от DHCP сервера) настройки ip, gw, dns (использовать публичный DNS серверы, например 1.1.1.1 или 8.8.8.8)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(8).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(9).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(10).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(11).png">

<p>после ребута</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(12).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_3(13).png">

<h2>Part 4. Обновление ОС</h2>
<p>Обновить системные пакеты до последней на момент выполнения задания версии.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_4(0).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_4(1).png">

<h2>Part 5. Использование команды sudo</h2>
<p>Разрешить пользователю Part 2 выпольнять команду, sudo.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_5(0).png">

<p>Поменять hostname OC от имени пользователя, созданного в пункте Part 2 (используя sudo)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_5(1).png">

<p>sudo - это утилита, она позволяет временно поднимать привелегии и выполнять задачи администрирования системы</p>

<h2>Part 6. Установка и настройка службы времени</h2>
<p>Настроить службу автоматической синхронизации времени</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_6(0).png">

<p>Вывод следующей команды должен содержать NTPSynchronized=yes: timedatectl show</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_6(1).png">

<h2>Part 7. Установка и использование текстовых редакторов</h2>
<p>Установить текстовые редакторы VIM (+ любые два по желанию NANO, MCEDIT, JOE и т.д.)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(0).png">

<p>Используя каждый из трех выбранных редакторов, создайте файл test_X.txt, где Х - название редактора, в котором создани файл. Напишите в нем свой никнейм, закройте файл с сохранением изменений.</p>
<p>vim</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(1).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(2).png">
<p>выход: esc + :wq</p>

<p>nano</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(3).png">
<p>выход: control+o+x</p>

<p>mcedit</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(4).png">
<p>выход: f2+f10</p>

<p>Используя каждый из трех выбранных редакторов, откройте файл на редактирование, отредактируйте файл, заменив никнейм на строку "21 School 21", закройте файл без сохранения изменений. vim</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(5).png">
<p>выход:q!</p>

<p>nano</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(6).png">
<p>выход: control+x</p>

<p>mcedit</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(7).png">
<p>выход: f10</p>

<p>Используя каждый из трех выбранных редакторов, отредактируйте файл ещё раз (по аналогии с предыдущим пунктом), а затем освойте функции поиска по содержимому файла (слово) и замены слова на любое другое.</p>
<p>vim поиск</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(8).png">

<p>замена</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(9).png">
<p>/- поиск</p>

<p>nano поиск</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(10).png">

<p>замена - control /</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(11).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(12).png">
<p>поиск - control w</p>

<p>mcedit</p>

<p>поиск -f7</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(13).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(14).png">

<p>замена - f4</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(15).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_7(16).png">

<h2>Part 8. Установка и базовая настройка сервиа SSHD</h2>
<p>Установить службу SSHd.</p>
<p>обновление репозитория</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(0).png">

<p>установление ssh</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(1).png">

<p>установление OpenSSH</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(2).png">

<p>Добавить автостарт службы при загрузке системы.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(3).png">

<p>статус ssh</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(4).png">

<p>Перенастроить службу SSHd на порт 2022.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(9).png">

<p>ssh перезапуск для сохранения изменений</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(6).png">

<p>Используя команду ps, показать наличие процесса sshd. Для этого к команде нужно подобрать ключи.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(7).png">

<p>-tan:</p>
<p>t-по протоколу TCP</p>
<p>a-Отображение всех подключений и ожидающих портов.</p>
<p>n- Отображение адресов и номеров портов в числовом формате.</p>
<p>Cтолбцы:</p>
<p>Recv-Q -количество запросов в очередях на приём на данном узле/компьютере</p>
<p>Send-Q -количество запросов в очередях на отправку на данном узле/компьютере</p>
<p>Local Address - адрес и номер локального конца сокета</p>
<p>Foreign Address - адрес и номер порта удаленного порта сокета</p>
<p>State - состояние сокета</p>
<p>Если в качестве адреса отображается 0.0.0.0 , то это означает - "любой адрес", т. е в соединении могут использоваться все IP-адреса существующие на данном компьютере.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_8(8).png">

<p>ps -aux | grep sshd output:</p>
<p>ps-выводит список текущих процессов на вашем сервере в виде таблицы</p>
<p>a-выбрать все процессы, кроме фоновых;</p>
<p>u-выбрать процессы пользователя.</p>
<p>x-заставляет ps перечислить все процессы, принадлежащие вам</p>
<h2>Part 9. Установка и использование утилит top, htop</h2>
<p>Установить и запустить утилиты top и htop.</p>
<p>top</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(0).png">

<p>uptime</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(1).png">

<p>количество авторизованных пользователей</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(6).png">

<p>общую загрузку системы</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(2).png">

<p>общее количество процессов</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(3).png">

<p>загрузку cpu</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(3).png">

<p>загрузку памяти</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(4).png">

<p>pid процесса занимающего больше всего памяти</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(5).png">

<p>pid процесса, занимающего больше всего процессорного времени</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(5).png">

<p>htop отсортированному по PID</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(8).png">

<p>PERCENT_CPU</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(7).png">

<p>PERCENT_MEM</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(9).png">

<p>TIME</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(10).png">

<p>отфильтрованному для процесса sshd</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(11).png">

<p>с процессом syslog, найденным, используя поиск</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(12).png">

<p>с добавленным выводом hostname, clock и uptime</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_9(13).png">

<h2>Part 10. Использование утилиты fdisk</h2>
<p>Запустить команду fdisk -l.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_10(0).png">

<p>имя</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_10(1).png">
<p>размер 8.25Gb</p>

<p>количество секторов</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_10(2).png">
<h2>Part 11. Использование утилиты df</h2>
<p>df</p>
<p>Для корневого раздела (/):</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_11(0).png">

<p>размер раздела-8408452</p>
<p>размер занятого пространства - 2753880</p>
<p>размер свободного пространства-5205856</p>
<p>процент использования-35</p>
<p>Единица измерения в выводе-килобайты</p>
<p>df -Th для корневого раздела (/):</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_11(1).png">

<p>размер раздела-8.1Gb</p>
<p>размер занятого пространства-2.7Gb</p>
<p>размер свободного пространства-5.0Gb</p>
<p>процент использования-35</p>
<p>Tип файловой системы для раздела-ext4</p>
<h2>Part 12. Использование утилиты du</h2>
<p>Вывести размер папок /home, /var, /var/log (в байтах)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_12(1).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_12(0).png">

<p>Вывести размер всего содержимого в /var/log (не общее, а каждого вложенного элемента, используя *)</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_12(6).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_12(57).png">

<h2>Part 13. Установка и использование утилиты ncdu</h2>
<p>Установить утилиту ncdu.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_13(0).png">

<p>Вывести размер папок /home, /var, /var/log.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_13(1).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_13(2).png">
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_13(3).png">
<h2>Part 14. Работа с системными журналами</h2>
<p>dmesg</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_14(0).png">

<p>syslog</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_14(1).png">

<p>auth</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_14(2).png">

<p>время последней успешной авторизации- Dec 21 00:35:01</p>
<p>имя пользователя-user-1</p>
<p>метод входа в систему-sudo</p>
<p>Перезапустить службу SSHd.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_14(3).png">

<h2>Part 15. Использовиние планировщика заданий CRON</h2>
<p>uptime</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_15(0).png">

<p>Найти в системных журналах строчки (минимум две в заданном временном диапазоне) о выполнении.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_15(1).png">

<p>список текущих задач</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_15(2).png">
<p>Удалите все задания из планировщика заданий.</p>
<img src="C:\Users\пк\Desktop\D01_Linux\src\screens\Part_15(3).png">