# 123
https://github.com/yaromkaaaaa
https://github.com/Seten01/demca/wiki
1.	Первым необходимым делом, при запуске виртуальных машин, необходимо настроить их переферию. Ниже приведена таблица (Таблица 1) по которой необходимо настроить подключение сетевых интерфейсов, так же не стоит забывать о дисках с ПО VipNeta и лицензиями для данного ПО.
	Таблица 1.
	
![image](https://github.com/SMYT911/123/assets/167532389/7261cf11-2ed1-4719-958f-c394deb91a6f)

2. После того как настроите интерфейсы, начинайте установку ПО, некоторое в свою особенность грузится долго, пытайтесь не терять время и не сидеть ждать, настраивайте другие машины(Отключайте файрволы, меняйте настройки сетевого обнаружения, это необходимо сделать на каждом узле). Далее (Таблица 2) приведен список ПО которое необходимо установить на каждую машину. Так же не стоит забывать о том, что клиент VIPNETa необходимо устанавливать в последнюю очередь на узел, после установки последнего можно перезагрузить машину/ы и установить дату соответствующую лицензии.
Таблица 2.
![image](https://github.com/SMYT911/123/assets/167532389/e294f219-0745-4432-8e9e-e994111df359)

3. Теперь переходим к работе в ЦУС. Здесь как и в настройках координатора, стоит быть очень аккуратным. При создании координатора в ЦУСе необходимо назначить ему роль как показано далее (рисунок 1).
![image](https://github.com/SMYT911/123/assets/167532389/65dbfca9-5280-42c8-b468-890dced75a7a)

Рисунок 1.

	Здесь показана настройка только первого координатора, но то же самое мы делаем и на втором. Далее у нас очень важный шаг при создании второго координатора. Нам необходимо прописать ему адрес во внешних сетях, делается это так же в ЦУСе(рисунок 2).
 ![image](https://github.com/SMYT911/123/assets/167532389/30cbc3ca-b25f-4b51-8c5c-bb45967fb77d)

Рисунок 2.
Здесь необходимо указать адрес его ВТОРОГО СЕТЕВОГО ИНТЕРФЕЙСА а именно 2.3.4.1

4. После можно переходить к созданию узлов и пользователей а так же настроить связи пользователей (!!!не путать связи с узлами!!!)между собой как показано в таблице далее(Таблица 3).

Таблица 3.
![image](https://github.com/SMYT911/123/assets/167532389/a5c8b638-af21-4762-8c47-ab81095b4ced)

“*” - есть связь.
“ ” - связи нет.
5. Далее после создания связей, необходимо создать справочники(ЦУС) и дистрибутивы ключей(УКЦ) для всех пользователей.

6. Далее идёт важная последовательность: Сперва мы настраиваем узлы, то есть разносим ключи по машинам у которых ест VipNet Client и устанавливаем эти ключи НО КЛИЕНТ НЕ ЗАПУСКАЕМ. ПОСЛЕ ПЕРЕХОДИМ К ИНИЦИАЛИЗАЦИИ КООРДИНАТОРОВ. При переносе ключа на клиент, можно кликнуть по нему два раза ЛКМ и клиент в миг инициализирует юзера.
7. При настройке координаторов следует быть так же аккуратным как и говорилось ранее. При установке ключа нужно настроить правильное время. А далее по аналогии таблице выше(Таблица 1).
1
![image](https://github.com/SMYT911/123/assets/167532389/cab957d7-a12f-4b5e-b280-20221bf41754)


















2 – 1.2.3.1 / 255.255.255.240
3 – 8.9.10.1 / 255.255.255.0
![image](https://github.com/SMYT911/123/assets/167532389/ff12d161-7195-46cb-9303-f323cb42acc0)



4 – 8.9.10.2(Шлюз)
![image](https://github.com/SMYT911/123/assets/167532389/9c4b777c-af06-46c6-9377-a685afdfa563)

5 -  No
![image](https://github.com/SMYT911/123/assets/167532389/ef655e0e-282f-4e44-a6fb-36d7cfc429cd)

![image](https://github.com/SMYT911/123/assets/167532389/c94c2e84-de15-492b-a69a-6ac8427ee3c9)


![image](https://github.com/SMYT911/123/assets/167532389/511ed367-dc35-4552-8888-97dc99a4d94b)


![image](https://github.com/SMYT911/123/assets/167532389/08cc1b0d-8b48-4e67-813b-919a0c2c07e2)


















6 - No
7 -  Yes

И на это всё)
Здесь показана настройка координатора 1. Настройка второго координатора аналогична, просто следуйте таблице выше(Таблица 1).
Для первой части этого в полне достаточно, ориентируйтесь на задание, делайте скриншоты.
Думаю как отправить сообщение и почту вы разберётесь сами, следуя по этим шагам можно спокойно получить 5.
Всех поцеловал <3
С любовью Иван(одногруппник).
Ориентировался на данный ресурс :
https://www.youtube.com/watch?v=DMlAWjtqhwY
