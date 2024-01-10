# ANDAN_DROM

Проект создан во время прохождения курса "Анализ данных". Он включает в себя парсинг объявлений с сайта <a href="drom.ru" target="_blank"> drom.ru </a>. В ходе парсинга выявлялись проблемы с неуниверсальностью объявлений: какие-то объявления не содержали той или иной информации. Эти проблемы были решены далее в разделе __обработки данных__. Этот раздел включает себя полное описание действий и причин данных действий, также учтен комментарий проверяющего после промежуточного чекпоинта. В раздел с __гипотезами__ было решено проверить гипотезу о том, что _среднее значение цен на западные автомобили равно среднему значению цен на восточные_, для этого была создана дополнительная переменная `страна производитель`

<a href="https://github.com/segor14/andan_drom/blob/main/merged.ipynb" target="_blank"> Весь проект </a> для удобства разделен на три части: <a href="https://github.com/segor14/andan_drom/blob/main/Парсинг.ipynb" target="_blank"> парсинг </a>, <a href="https://github.com/segor14/andan_drom/blob/main/Обработка_и_визуализация.ipynb" target="_blank"> обработка собранных данных и EDA </a>, <a href="https://github.com/segor14/andan_drom/blob/main/Гипотезы_и_МО.ipynb" target="_blank"> проверка гипотез и построение моделей машинного обучения </a>

## Собранные данные
В файлах <a href="https://github.com/segor14/andan_drom/blob/main/data_raw%20(1).csv" target="_blank">data_raw (1).csv</a> и <a href="https://github.com/segor14/andan_drom/blob/main/data_processed.csv" target="_blank">data_processed.csv</a> содержатся изначальные и обработанные данные соответственно. 

## Содержание проекта:
<ul>
  
###  <li> Парсинг</li>
###  <li>Обработка данных</li>
  
 <dl>
    <dd>Что за данные у нас вообще получились?</dd>
    <dd>Обработка пропусков + исправления после чекпоинта</dd>
    <dd>Все пропуски обработаны! Ура!</dd> 
 <dl>

###  <li>Визуализация</li>
###  <li>Создаем новый признак, проверяем гипотезы</li>
###  <li>Машинное обучение</li>
 <dl>
    <dd>Линейная регрессия</dd>
    <dd>Ближайшие соседи</dd>
    <dd>Случайный лес</dd>
    <dd>Градиентный бустинг</dd>
 </dl>
</ul>

## Планы
В дальнейшем хочется разбить датасет на некоторые категории автомобилей (премиум-сегмент, раритетное авто и т.д.), вероятнее всего, это будет сделано с помощью решающего дерева или ансамбля.

Работа с такими категорями должна кратно улучшить метрики за счет создания сразу нескольких моделей под каждую категорию.

Кроме этого в планах разработать полносвязную нейронную сеть для набора данных
