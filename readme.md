# Ролевая игра «Century Zero» на движке Unreal Engine 5

## RPG "Century Zero" on Unreal Engine 5

Состав команды:
* **Архаров Дмитрий** - Представитель, геймдизайнер, програмист механник, програмист искусственного интеллекта
* **Шпоть Валерий** - Програмист механник, програмист окружения
* **Шалаева Марина** - Геймдизайнер, програмист механник, програмист UI

-----

Core проекта, реализуемый за три недели:

Обязательно:

* Реализовать телекинез (3 способа применения), (протюнить чтобы было приятно)
* Реализовать объекты, которые можно кидать во врагов, 
* Реализовать начальный огнестрел, (посмотреть успеем ли протюнить до состояния чтобы было приятно)
* Реализовать врагов на начальном уровне, которые будут пытаться атаковать героя.

Дополнительно по мере успевания:

* Реализовать управление гравитацией.

-----

Примечание: после последней встречи мы придумали 3 пути внедрения комбинаторики в геймплейный цикл, 
для Core проекта решили остановиться на внедрении двух систем:
1) Управления гравитацией (переключение гравитации между двумя режимами — пониженной и повышенной), 
которая будет влиять на все остальные способности, так, например, при повышенной гравитации все объекты будут становиться тяжелее и медленнее.
2) Наличие у телекинеза трёх способов применения в зависимости от выбранной цели.
Так, при применении к предмету игрок сможет поднять этот объект в воздух и метать его в противников.
При применении к противнику игрок сможет толкнуть NPC, а при режиме низкой гравитации даже оторвать его от поверхности.
При примении же телекинеза к поверхности, игрок сможет оттолкнуться от поверхности в противоположном направлении.
3) Наша идея заключалась в добавлении системы энергетических эллементов (например — электричество и огонь), энергию которых игрок может поглощать с трупов поверженных противников, чтобы потом, комбинируя до 3-ёх поглощённых, эллементов таким образом создавать особую, привязанную к такой связке способность, однако пока что для Core проекта мы подумали оставить эту систему за скобками.
