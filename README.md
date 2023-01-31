# Marketing_analysis
Здесь представлены задачи, связанные с маркетинговой аналитикой.

<h3><a href="https://github.com/KristinaBataeva/Marketing_analysis/blob/main/k_factor_ols.ipynb">k_factor_ols</a></h3>
С помощью линейной регрессии была проведена оценка k-фактора для денег(gross) и для пользователей(count), чтобы верно оценить маркетинговую кампанию. Я решила действовать с помощью линейной регрессии в обоих случаях, так как они линейно связаны, хоть и не распределены нормально. Предиктор - UA, ЗП - ORG. За k-фактор принимаю коэффициент уравнения линейной регрессии при предикторе.

И для count, и для gross, я решила создать по две модели: одну с полным набором данных, другую без выбросов. Как и ожидалось, модели без выбросов были более надёжными по ряду критериев, но в обоих случаях их MSE превышала MSE первых моделей, в которых учитывались выбросы. Так как в задачи входит более полно учесть k-фактор периода, чем просто спрогнозировать, я считаю, что имеет смысл взять именно их коэффициенты.

Перерасчёт прибыли с учётом k-фактора дал стат значимые результаты в пользу маркетинговой компании, хотя до перерасчёта такого вывода сделать было нельзя. Отчёт-презентация есть внутри работы.

  ---
<h3><a href="https://github.com/KristinaBataeva/Marketing_analysis/blob/main/metrics_and_acquisition_channels.ipynb">metrics_and_acquisition_channels</a></h3>
Эта работа по оценке метрик и качества трафика с различных каналов.
