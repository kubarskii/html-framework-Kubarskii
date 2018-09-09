# html-framework-Kubarskii
Layout with flot and flex
////////////////////////////////////////////////////////////////////////////////////

1.
Релизована адаптивная разметка, основанная на float, по аналогии с BS 3. Релизованы следующие классы:
Контейнеры:
.container - фиксированной ширины, которая меняется в завимсимости от размера экрана, расположен по центру экрана
.container-fluid - 100% экрана

Строка:
.row - строка, вложена в контейнер, не обтекается (clear: both)

Колонки: 
.col-sm-1,.col-sm-2,.col-sm-3,.col-sm-4,.col-sm-5,.col-sm-6,.col-sm-7,.col-sm-8,.col-sm-9,.col-sm-10,.col-sm-11,.col-sm-12,
.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12,
.col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12

sm - меняет размер при экране 768px
md - меняет размер при экране 992px
lg - - меняет размер при экране 1200px

1 - 1/12 ширины row
2 - 2/12 ширины row
3 - 3/12 ширины row
4 - 4/12 ширины row
5 - 5/12 ширины row
6 - 6/12 ширины row
7 - 7/12 ширины row
8 - 8/12 ширины row
9 - 9/12 ширины row
10 - 10/12 ширины row
11 - 11/12 ширины row
12 - 100% ширины row

.clearfix - фикс для float

Классы для добавления float:
.pull-left - float left 
.pull-right - float right

Классы для выравнивания текста:
.text-left
.text-center
.text-right
////////////////////////////////////////////////////////////////////////////////////

2.
Реализована адаптивная разметка, основанная на flex, по принципу BS 4.0. Релизованы следующие классы:
.row-flex строка (контейнер для flex-item)

Классы для flex-item:
.col-sm-1-flex,.col-sm-2-flex,.col-sm-3-flex,.col-sm-4-flex,.col-sm-5-flex,.col-sm-6-flex,
.col-sm-7-flex,.col-sm-8-flex,.col-sm-9-flex,.col-sm-10-flex,.col-sm-11-flex,.col-sm-12-flex
(аналогично с col-sm-n для float)

Классы для сортировки:
.order-1,.order-2,.order-3,.order-4.order-5.order-6,.order-7,.order-8,.order-9,.order-10,.order-11,.order-12
указывают на порядок размещения элемента .order-n в row-flex, где n - порядковый номер. 

Классы для выравнивания элементов (flex-item) в row-flex:
.x-start flex-item выравниваются по левой стороне flex-row
.x-end flex-item выравниваются по правой стороне flex-row
.x-center flex-item выравниваются по центру стороне flex-row

.y-end выравние по вертикали притянуть к нижней части flex-row
.y-start выравние по вертикали по центру flex-row
.y-center выравние по вертикали притянуть к верхней части flex-row

.space-between - равные расстояния между flex-item
.space-around - равные расстояния вокруг flex-item

.column - располагает flex-item по-вертикали

////////////////////////////////////////////////////////////////////////////////////

3.
Дополнительные классы:
.outer-space-0, .outer-space-8, .outer-space-16, .outer-space-32, .outer-space-40
.inner-space-0,.inner-space-8,.inner-space-16,.inner-space-32,.inner-space-40

inner-space - добавление padding
outer-space - добавление margin
0, 8, 16, 32, 40 - значения margin/padding в px

.box-sizing-box - Расчет ширины блока с учетом padding.
