## Домашнее задание № 1 «Представление графа»

Дан базовый интерфейс для представления ориентированного взвешенного графа (тип объекта, который является значением весовой функции, передаётся в качестве шаблонного параметра)

Необходимо написать несколько реализаций интерфейса:

+ **ListGraph**, хранящий граф в виде массива списков смежности,

+ **MatrixGraph**, хранящий граф в виде матрицы смежности,

+ **ArcGraph**, хранящий граф в виде одного массива пар {from, to},

+ **PtrsGraph**, хранящий граф в виде вершин -- Node, хранящих указатели на другие вершины и вес рёбер

**Node** для этого класса тоже необходимо реализовать

Также необходимо реализовать конструктор, принимающий const IGraph*. Такой конструктор должен скопировать переданный граф в создаваемый объект
 (обратите внимание, что иногда в одну реализацию графа копируется другая)
Реализуйте в том числе все конструкторы копий/перемещения и операторы присваивания, если необходимо.

Интерфейс графов и строение директории можно менять, если вам покажется более удобным другое представление. В таком случае необходимо заменить вызовы методов в тестовом файле.

