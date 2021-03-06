# Анализ маркетинговых затрат для мобильной игры

[Просмотреть проект](https://nbviewer.jupyter.org/github/Boris-1coder/Yandex.Praktikum/blob/main/Analysis_of_marketing_costs/Analysis_of_marketing_costs.ipynb)

## Данные

В наличии были следующие данные о клиентах в мобильной игре:

**game_actions.csv**
- event_datetime — время события
- event — одно из трёх событий (building — объект построен, finished_stage_1 — первый уровень завершён, project — проект завершён)
- building_type — один из трёх типов здания (assembly_shop — сборочный цех, spaceport — космопорт, research_center — исследовательский центр)
- user_id — идентификатор пользователя
- project_type — тип реализованного проекта

**ad_cost.csv**
- day - день, в который был совершен клик по объявлению
- source - источник трафика
- cost - стоимость кликов

**user_source.csv**
- user_id - идентификатор пользователя
- source - идентификатор источников, с которого пришёл пользователь, установивший приложение

## Задача

Нужно разобраться, в какую рекламу лучше всего вкладываться, а также какая стратегия монетизации игры лучше всего подойдет для повышения доходов от рекламы. Для этого будет необходимо разобраться, какие типы клиентов играют в наше приложение, как это влияет на прохождение и вовлеченность в игру.  

## Используемые библиотеки
<li>pandas <li>matplotlib.pyplot  <li>numpy <li>math <li>seaborn <li>datetime <li>plotly.express <li>stats <li>graph_objects <li>display

