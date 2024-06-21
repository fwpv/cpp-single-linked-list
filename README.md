#Single Linked List

Реализует класс контейнера - односвязный список. Его также называют линейным однонаправленным списком. Аналог std::forward_list из стандартной библиотеки.

Односвязный список — это базовая структура данных, которая представляет собой соединённые узлы с однотипными данными. В каждом узле хранится элемент данных списка и ссылка на следующий узел.

Самый первый элемент списка называют головой (head), а последний — хвостом (tail). Последний элемент односвязного списка в качестве ссылки содержит null-значение.

Передвигаться по элементам можно только в одном направлении.

Поддерживаются следующий операции:

- вставка элемента в начало или конец.
- вставка элемента после некоторого элемента.
- удаление элемента, следующего за данным элементом.
- проверка на пустоту.
- получение количества элементов.

## Инструменты разработки

Проект написан в Visual Studio Code. Язык программирования - C++17. Для сборки использовался плагин C/C++ Runner и компилятор gcc (MinGW-W64) версии 13.2.0.
