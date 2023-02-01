По условиям данного учебного проекта продакт-менеджер Василий попросил меня проанализировать совершенные покупки и ответить на следующие вопросы:

1. Сколько у нас пользователей, которые совершили покупку только один раз?

2. Сколько заказов в месяц в среднем не доставляется по разным причинам?

4. По каждому товару определяю, в какой день недели товар чаще всего покупается.

4. Сколько у каждого из пользователей в среднем покупок в неделю (по месяцам)?

5. Используя pandas, провести когортный анализ пользователей. В период с января по декабрь выявить когорту с самым высоким retention на 3й месяц. Описание подхода я взял тут (https://vc.ru/s/productstar/134090-chto-takoe-kogortnyy-analiz).

6. Используя python, построить RFM-сегментацию пользователей, чтобы качественно оценить свою аудиторию. В кластеризации выбрать следующие метрики: R - время от последней покупки пользователя до текущей даты, F - суммарное количество покупок у пользователя за всё время, M - сумма покупок за всё время. Для каждого RFM-сегмента построить границы метрик recency, frequency и monetary для интерпретации этих кластеров. Пример такого описания: RFM-сегмент 132 (recency=1, frequency=3, monetary=2) имеет границы метрик recency от 130 до 500 дней, frequency от 2 до 5 заказов в неделю, monetary от 1780 до 3560 рублей в неделю. Описание подхода нашел тут (https://guillaume-martin.github.io/rfm-segmentation-with-python.html).

