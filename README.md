# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут Михаил, я начинающий аналитик данных. 

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``


## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Проанализировать исторические данные и собрать ряд сводных таблиц  
  <li>Провести расчет сложных композитных показателей(LT, LTR, CAC)
  <li>Свести воедино полученную информацию по юнит-экономике и рассчитать доли статей
    
</ol>

<p>Как решал:
С помощью математических форммул рассчитал сколько мы тратим просто на привлечение, сколько идет на конверсию в оплату, какой процент привлеченных пользователей совершает оплату, сколько стоит урок с учетом всех скидок и промо, как долго привлеченный пользователь остается с нами (в часах и в уроках), какова интенсивность занятий. Добавил поле с изменяемыми параметрами, чтобы рассчитать планые показатели. И построил прогноз отталкиваясь от целей на следующий год.  
<p>


> <a href="https://docs.google.com/spreadsheets/d/1vJzxpHr6NQy4aRs2sPQhfV36tADNi5L_/edit#gid=1896091894">Ссылка на проект</a>
 
<p>Выводы (итоги):<p>
<ol>
  <li>Проанализировав исторические данные мы поняли, что узким местом нашей юнит-экономики остается CAC, самый эффективный канал привлечения — parents, за счет увеличения доли маркетинговых расходов на этот канал мы, вероятнее всего, сможем снизить общий CAC. Также исторические данные показали что маржинальность находится на низком уровне, но если посмотреть основыные доли статей по месяцам, то можем заметить что мы вышли на положительную маржу( в апреле 2021 года она составляла почти 14%)  </li>
 <li>Изменив такие параметры, как средний CPA уменьшив его на 10%, конверсию в покупку увеличив на 10,5%, retention увеличив на 3%, интенсивность подняв на 13% и долю скидок уменьшив на 30%, то на пересчитанных данных мы можем увидеть, что следующий год мы пройдем с маржинальность более чем 15%, к концу года выйдем более чем на 4тыс. студентов , помимо этого при текущих настройках мы выйдем на выручку около 34 млн. руб., что свидетельствует о перевыполнении годовых целей.     </li>
</ol>
<br> 

<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Необходимо посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность</li>
  <li>Собрать хорошую наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на нашей платформе.</li>
</ol>

<p>Как решал: Определил, что является юнитом в нашей экономике. Посчитал юнит-экономику продукта и предложил сценарий по настройке параметров для выхода на 25%-ную маржинальность.Выбрал оптимальный вариант расчета Retention. Собрал визуализации основных бизнес-показателей. Исследовал данные о пользователях и их поведении.<p>

> <a href="https://docs.google.com/spreadsheets/d/16D44TyVgSe4N1rMZ91_JO0gBMXPH2hLu/edit#gid=1223403638">Ссылка на проект</a>
 
<p>Выводы (итоги):<p>
<ol>
  <li>Действительно можем сделать вывод, что с пт-вс активность выше чем в будние дни	</li>
  <li>Динамика роста новых пользователей заметно начала падать в апреле 2021 года		</li>
</ol>
<br> 

<p>Проект 3: Построение витрины для модели машинного обучения в банке </p> 
<p>Что нужно было сделать: На основе таблицы skybank.late_collection_clients сделать витрину с новыми полями и переменными <p>
  
<p>Как решал: При помощи case when добавил поле, которое принимает значение 1 для мужчин и 0 для женщин — новое поле nflag_gender на основании поля gender. При помощи агрегирующих оконных функций добавил поля, которые показывают суммарный объем кредитов, выданных в этом городе, в рамках указанного типа кредита и в рамках указанного типа кредита и города. Также отразил доли данного кредита среди всех кредитов, выданных в этом городе, в рамках указанного типа кредита и в рамках указанного типа кредита и города.<p>

> <a href="https://metabase.sky.pro/question/81930">Ссылка на проект</a>

 <p>Выводы (итоги):<p>
<ol>
  <li>Код успешно отработал</li>
  <li>В новой витрине стало больше полезных данных</li>
</ol>
<br> 


<p>Проект 4: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Написать запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день.</li>
  <li>Создать визуализацию (линейную диаграмму) итогового результата и написать выводы из получившейся визуализации</li>
</ol>

<p>Как решал: Узнал когда была первая транзакция,чтобы понять с какой даты мы будем собирать баланс уроков. Собрал таблицу с датами за каждый календарный день 2016 года. При помощи join объединил 2 таблицы чтобы узнать за какие даты имеет смысл собирать баланс для каждого студента. Нашёл все изменения балансов, связанные с успешными транзакциями. Нашёл баланс студентов, который сформирован только транзакциями. Нашёл изменения балансов из-за прохождения уроков. По аналогии с уже проделанным шагом для оплат создадал CTE для хранения кумулятивной суммы количества пройденных уроков. И создал CTE balances с вычисленными балансами каждого студента. <p>

> <a href="https://docs.google.com/spreadsheets/d/1DWubVJfGtNHRod4sZWx6WxuzUw7aVgVL/edit#gid=1613423631">Ссылка на проект</a>
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Общий баланс студентов имеет растущую тенденцию, особенно это можно увидеть с сентября месяца, начала учебного периода</li>
  <li>По графикам видно что кривая покупки уроков и кривая списывания с баланса этих уроков почти четко накладываются друг на друга, что говорит нам о том, что студенты не откладывают уроки в долгую копилку, а своевременно их просматривают</li>
  <li>К концу 2016 года общее количестов уроков выросло с 8 до 3.5 тыс</li>
  <li>Еще один инсайт можно увидеть на сером и темно синем графике , в промежутке с сентября месяца по конец декабря  видно что синий график налазит на серый, это говорит нам о том что в этот промежуток студенты чаще приобретали уроки</li>
</ol>

## Контактная информация
- Email: mechanic.1990@inbox.ru
