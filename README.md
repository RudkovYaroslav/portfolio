# Мое портфолио
___________
# Pet - проекты

## [Проект 1 - Spotify](https://github.com/RudkovYaroslav/spotify_project)

Во время перерыва в обучении я занялся первым собственным проектом. Стало интересно проанализировать данные по исполнителям и их произведениям на spotify. В ходе выполнения проекта:
- Использовал еще более продвинутый функционал pandas, включая знание python, для создания собственных алгоритмов для отбора определенных данных
- Провел исследовательский анализ с целью оценки общего состояния индустрии, а также установления зависимостей различных качеств музыкальных композиций(треков) от их популярности
- Отметил нарастающую тенденцию использования стриминговыми сервисами, а также малую наполненность рынка на данный момент
- Составил выводы по итогу проведенного анализа

## [Проект 2 - Selenium_Riot](https://github.com/RudkovYaroslav/Selenium_Riot)

Мой второй собственным проект. Основная цель - упрощение выполнения достижения в игре League of Legends. Для достижения этой цели спарсил сайт по сбору статистики, а затем собрал всю полученную информацию в excel файл. В ходе выполнения проекта:
- Столкнулся со многими проблемами парсинга сайтов, а конкретно [op.gg](https://op.gg)
- Использовав библиотеки Selenium, а затем BeautifulSoup, смог открыть нужные страницы для сбора информации
- Отсортировал и преобразил информацию в собранных датафреймах
- Перенес все результаты в excel файл
___________
# Учебные проекты

Проекты, выполненные в процессе обучения в Яндекс - Практикуме
____________

## [Проект 1 - Исследовательский анализ данных](https://github.com/RudkovYaroslav/research_analysis?tab=readme-ov-file)

Первый самостоятельный проект, который выполнен в Jupyter Notebook. Основная цель - показать базовые навыки предобработки данных и проведения исследовательского анализа. В ходе проекта:
- Используя бибилиотеку pandas рассмотрел DataFrame, который был предоставлен
- Сделал предобработку данных, так как приложенный DataFrame был очень "сырым"
- Провел исследовательский анализ с целью обнаружения зависимостей параметров квартир от их стоимости
- На основании полученных данных были составлены выводы и даны рекомендации

## [Проект 2 - Статистический анализ данных](https://github.com/RudkovYaroslav/project_2)

Второй проект, выполненный все также в Jupyter Notebook. В ходе проекта:
- Также, как и ранее, провел предобработку и исследовательский анализ
- В ходе анализа было продемонстрировано знание библиотеки matplotlib для построения графиков
- Были использованы понятия из теории вероятностей для проведения статистического анализа
- Рассмотрел некоторые, выдвинутые заранее, гипотезы. Используя функционал библиотеки scipy, а также понятие p value, сделал выводы в пользу опровержения или его невозможности для высказанных гипотез
- Составил выводы и рекомендации на основе проведенного анализа

## [Проект 3 - Сборный проект](https://github.com/RudkovYaroslav/project_gaming)

Третий проект, который отражает знание всего блока анализа данных на Python. В него вошли:
- Использование библиотеки pandas на продвинутом уровне
- Использование библиотеки seaborn и matplotlib для построения графиков
- Использование библиотек numpy и scipy для проведения статистического анализа
В ходе проекта:
- Провел исследовательский анализ прошлого состояния игровой индустрии
- На основании трендов в прошлом попытался предсказать наиболее возможные варианты развития данной области в ближайшем будущем
- Оценил прибыльные платформы, жанры видеоигр, для вложения средств в рекламу
- Сделал выводы и дал рекомендации для компании на основе проведенного анализа

## [Проект 4 - Анализ бизнес показателей](https://github.com/RudkovYaroslav/project_business)

Пятый проект направлен на изучение бизнес аспектов, а конкретно проведение анализа затрат на рекламу с целью поиска слабых мест. В ходе анализа:
- Были взяты "сырые" данные о пользователях, каналах их привлечения, а также стоимости этих каналов и, что немаловажно, прибыли от пользователей
- После предобработки составил портреты каждого конкретного пользователя
- Провел исследовательский анализ по этим портертам с целью поиска базовых корреляций
- Провел анализ бизнес показателей затрат на рекламу. В ходе него рассмотрел Retentinon Rate/ Churn Rate пользователей в общем, а также в разрезе по каналам.
- Также рассмотрел показатели LTV, CAC, ROI в разрезе по странам, каналам привлечения. В ходе анализа смог установить неэффективные каналы привлечения
- Составил выводы и дал рекомендации бизнесу по улучшению состояния рекламы для компании

## [Проект 5 - Углубленный анализ гипотез](https://github.com/RudkovYaroslav/Advanced_business_analysis)

Шестой проект более углубленно заставил погрузиться в саму суть проведения А/B тестов, где на учебном кейсе необходимо было рассмотреть две группы и составить вывод, продолжать тест или прекратить. В ходе выполнения проекта:
- На входе были получены данные о таблице с гипотезами, количеством пользователей из каждой группы в определенные даты, а также с заказами, которые эти пользователи составляли
- После предобработки провел приоритизацию гипотез по фреймворкам ICE, RICE
- Приступил к анализу А/В теста, а именно:
   - Графически показал разниуц групп по среднему чеку, количеству заказов, а также относительным показателям
   - Учел аномальные значения в этих группах
   - Провел тесты Манна-Уитни на "сырых" и "чистых" данных, сделал выводы по полученным результатам
- По итогу сделал общий вывод, в котором принял решение остановить тест в виду успешности одной из групп и на графиках, и в стат тестах
