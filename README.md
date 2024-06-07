# Бизнес империя

## Общая информация

**Бизнес империя** – игра экономического и стратегического жанра, основанная на игре «Монополия», но со своими фишками. Главной фишкой игры является наличие «Банд». С помощью «Банд» возможно нападать на имущество другого игрока, с целью присвоения его себе. Также есть возможность ставить охрану на свои объекты и набирать людей в банду. Игра написана на фреймворке MonoGame.

## Правила

1. Выберите количество игроков, определите очерёдность и нажмите “Играть”
2. Для броска кубиков нажмите “Бросить кубики”, после этого фишка вашего цвета передвинется автоматически.
3. В зависимости от того, на какую ячейку вы попали, у вас появятся возможности: покупать или продавать объекты, нанимать людей в банду, ставить охрану на объект, нападать на чужое имущество
4. Если вы попадёте на ячейку с объектом, у которого указана цена и нет владельца, то вы сможете купить его, либо набрать людей в банду
5. Если вы попадёте на ячейку с объектом, который принадлежит вам, то вы сможете продать её, набрать людей в банду, поставить охрану на данный объект
6. Если вы попадёте на ячейку с объектом, который принадлежит другому игроку, то вы заплатите ренту, и сможете напасть на данный объект. Если рейд окажется успешным, то объект будет принадлежать вам и уровень ренты объекта будет понижен до 1. Количество людей в банде, бывшего владельца, будет уменьшено на количество людей, охраняющих объект, и цена для рекрутирования новых людей будет понижена на (кол-во убитых / 10) \* 100. Если рейд окажется неуспешным, атакующий потеряет всех людей, которые участвовали в рейде, а защищающийся не понесёт потерь
7. Если вы попадёте на ячейки “Чёрный ящик”, “Звонок с незнакомого номера”, “Конец года”, “У вас день рождения”, “Ремонт дороги”, “Суперприз”, то вы получите описание карты, что произошло с вами
8. При прохождении через поле “Старт”, вы получите 400$, при попадании на поле “Вас взяли в заложники”, вы заплатите 200$
9. Продажа имущества происходит по той же цене, что и покупка
10. Рекрутирование людей в банду изначально стоит 500$. Цена последующего рекрутирования будет повышена на 100$ и так каждый раз. Цена рекрутирования индивидуальна для каждого игрока
11. С помощью людей, которых вы рекрутировали в банду, можно нападать на объекты принадлежащие другим игрокам, при условии, что есть люди, которые не стоят на охране ваших объектов. При наведении на кнопку “Напасть на имущество”, вы увидите шанс, на захват имущества. Также если у вас есть свободные люди, то вы можете поставить их на охрану, при условии, что ваша фишка стоит на карточке объекта, который принадлежит вам. Людей, которые стоят на охране, будут сняты тогда, когда вы продадите объект
12. Игра заканчивается по истечении ходов, либо когда появился первый банкрот. Победителем считается игрок, у которого суммарная стоимость всех его объектов больше, оставшиеся деньги и количество людей в банде в зачёт не идут
13. Банкротом считается игрок, у которого не хватает средств для закрытия задолженности. Долг можно погасить продажей своего имущества. Для продажи необходимо навести курсор мыши над вашим имуществом и нажать левую кнопку мыши
14. Все финансовые операции производятся автоматически, также не забывайте завершать ход
