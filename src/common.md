# Common

Пусть у нас есть граф объектов. Граф ориентированный. Есть ребро из `A` в `B`, если у объекта `A` существует поле, указывающее в `B`.  

Есть такие понятия как Мутатор и Коллектор:  
- Мутатор - программа, изменяющая граф объектов. Имеет 3 операции: `New`, `Read`, `Write`.
- Коллектор - компонента системы, отвечающая за сборку мусора.
