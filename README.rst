|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Методика многокритериального оценивания моделей разметки текста по несогласованным экспертным разметкам
    :Тип научной работы: M1P
    :Автор: Александр Михайлович Левыкин
    :Научный руководитель: д.ф.-м.н., Воронцов Константин Вячеславович
    :Научный консультант(при наличии): степень, Фамилия Имя Отчество

Abstract
========

С использованием разметок решается широкий класс задач обработки естественного языка. Одна из таких задач - задача NER (named enitity recognition). На данный момент подавляющее большинство моделей и датасетов опираются на простую структуру разметки, содержащую лишь фрагменты и теги (метки). Более того, для оценки точности модели используются простые метрики классификации, такие как F1, Precision, Recall. Проблема таких метрик в том, что они не учитывают все аспекты структуры разметки, и в том, что они применимы лишь в предположении существования идеальной разметки. В данной работе описывается более общая  и универсальная структура разметки, позволяющая решать комплексные задачи, и строится методика многокритериального оценивания моделей разметки текста по несогласованным экспертным разметкам. После чего рассматривается применение построенного метода для оценки качества модели, полученной в рамках конкурса PROчтение.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
