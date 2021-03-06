# Определение перспективного тарифа сотовой связи
### Задача:
- На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа
### Процесс:
Проведен предварительный анализ использования тарифов на выборке клиентов,
проанализировано поведение клиентов при использовании услуг оператора и
рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка
данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и
различии выручки абонентов из Москвы и других регионов.
### Результат
- Пользователи тарифа «Ультра» в среднем потребляют больше минут, СМС и гигабайт, чем пользователи тарифа «Смарт», однако делают это с гораздо большей вариацией;
- Выручка пользователей различных тарифов, скорее всего, отличается в пользу тарифа «Ультра». На самом деле, этот вывод интуитивно понятен, учитывая более чем в 3 раза различающуюся базовую стоимость рассматриваемых тарифов. Если использующий тариф «Смарт» пользователь значительно выбивается из лимитов, он непременно перейдет на «Ультра» в целях экономии денежных средств;
- Выручка, скорее всего, не зависит от нахождения пользователя в Москве. Большинство пользователей не выходят за пределы бесплатных лимитов тарифов, и, учитывая факт унификации стоимости тарифов для всех регионов, включая Москву, данный вывод так же интуитивно понятен;
- СМС-сообщения в традиционном виде начинают вымирать - коэффициент вариации слишком велик, что свидетельствует об усложнении точного прогнозирования использования данного вида коммуникационных услуг. Если поддержка инфраструктуры СМС-сообщений требует больших финансовых вложений, от неё стоит вообще отказаться, так как в будущем из-за развития мессенджеров ситуация будет только усугубляться;
- Минуты разговоров, хоть и обладают большой вариацией, остаются одним из важнейших видов коммуникационных услуг на данное время. Однако, когда интернет будет распространен повсеместно, и все больше людей привыкнет звонить друг-другу с помощью мессенджеров, ситуация может значительно усложниться;
- Относительно низкая вариация использованного трафика говорит о ключевой роли интернета в услугах мобильных операторов. Интернет постепенно поглощает функцию более традиционных телефонных разговоров и СМС-сообщений, и при этом обладает большим количеством прочих функций. Существует предположение, что в будущем это будет единственная услуга мобильных операторов.

Был сделан вывод, что тариф «Ультра» в среднем приносит больше выручки, и поэтому целесообразно направить маркетинговые мероприятия именно на этот тариф, в том числе предлагая пользователям «Смарт» «прокачать» свой тариф.
### Примененные навыки: 
- Предобработка данных, описательная статистика, проверка статистических гипотез.
### Примененные инструменты: 
- Python и библиотеки Pandas, Matplotlib, NumPy, Scipy.
### Статус проекта:
- Завершен

