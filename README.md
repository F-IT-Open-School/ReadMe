# ReadMe

*Закладки из браузера за 2017 год в относительно хронологическом порядке по Python. Это всё, что нагулилось в процессе: никогда не программировал - относительно свободно изучаю учебные курсы сообщества ODS и пользуюсь Pandas и t-SNE. Если что  - то как программист Python я [справа]( http://coub.com/view/xjqkp), но всё это читал и вам советую, годный [саундтрек](http://coub.com/view/x7kw4) для чтения прилагается.* 

# Часть 1. До и после 4ого издания Лутца.

*Обычно, новичкам, которые "никогда не программировали" советуют читать Лутца, но сам Лутц считает, что его книжка не зайдёт тем, у кого нет "минимальной базы". Я пробовал читать Лутца без базы в языке - дядька прав, прежде чем открыть 1200 страничный артефакт, содержащий свет истины - необходимо получить минимальный минимум.*

Выдержкам из первых глав Лутца посвящен отдельный [репозиторий](https://github.com/HorusHeresyHeretic/Learning-Python-from-zero). Для начала стоит немного потренироваться. 

1. Учимся пользоваться голым интерпретатором Python, [учимся печатать код](http://informatics.mccme.ru/mod/book/view.php?id=2301&chapterid=351)
2. Самый первый полезный [учебник с задачами](http://younglinux.info/sites/default/files/python_structured_programming.pdf) которые можно и нужно решить.
3. Разбираемся с первыми *трудными* вопросами из учебника и переходим к Лутцу.

 * [Типы данных](http://pythonicway.com/python-data-types)  
  
 * [Инструкция if-elif-else](https://pythonworld.ru/osnovy/instrukciya-if-elif-else-proverka-istinnosti-trexmestnoe-vyrazhenie-ifelse.html)
  
 * [Встроенные функции языка](https://pythonz.net/references/named/vstroennye-fynktsii/)
  
 * [Определение функций, основы](https://habrahabr.ru/post/30633/)
  
 * [Алгоритмы вычисления чисел Фибоначчи](http://py-algorithm.blogspot.ru/2011/04/blog-post_04.html)
  
 * [Сборник решений задач по программированию](http://taskcode.ru)
  
 * [Использование регулярных выражений в Python](https://tproger.ru/translations/regular-expression-python/)
  
 * [Двумерные списки (массивы и матрицы) в Python](http://progras.ru/31-dvumernye-spiski-massivy-matricy-v-python/)
  
  Несколько полезных уроков про модули в Python [раз](https://pep8.ru/doc/tutorial-3.1/6.html), [два](http://pythonicway.com/python-modules), [три](http://younglinux.info/oopython/module.php).
  
*Каждая из ссылок ведёт на разные ресурсы одинаковой полезности, там вы сможете найти ответы практически на любые вопросы, которые могут возникнуть у вас при  выполнении задач из учебника или чтении Лутца.*

*В теории, достаточно один раз самостоятельно решить задачи из первого учебника и переходить к Лутцу, но, на практие есть один нюанс - меньшая половина того материала, который представлен выше, займёт в изложении Лутца страниц 300.*

*4-ое издание нужно читать (как минимум до 8-10 главы) поскольку Лутц позволяет сформировать восприятие о языке как о инструменте, которым вы собираетесь пользоваться. Но 1200 страниц без подготовки это долго*.

Поэтому, я рекомендую сразу ознакомиться со справочными материалами с этих ресурсов, прочитать Лутца и по готовности переходить к изучению учебных материалов [ODS](https://github.com/Yorko/mlcourse_open). 

# Часть 2. Учимся полезному - изучаем Pandas.

*Изучение учебных курсов ODS предполагает не только необходимый минимум в знании языка, но и ряд других требований. Владение библиотекой Pandas является обязательным. Поэтому, прежде чем задаваться вопросом - насколько я силен в математике, необходимо научиться пользоваться этим, во всех отношениях, отличным инструментом.*

1. Лучший  стартовый [tutorial](https://khashtamov.com/ru/pandas-introduction/) по Pandas.
2. Хорошее [продолжение](https://habrahabr.ru/post/196980/) первого знакомства с Pandas. 
3. Старт учебного курса ODS и отличный [пример](https://habrahabr.ru/company/ods/blog/322626/) работы с Pandas 
4. Первый [вызов](https://habrahabr.ru/company/ods/blog/323210/) для начинающего и прекрасная иллюстрация практики.

**Стоп** - *вот тут нужно остановиться и прежде чем переходить к следующему уроку из ODS - серьёзно подготовиться. Любой провал в знаниях на данном этапе сделает последующие усилия бесполезными.*  

*Прежде чем двигаться дальше в рамках учебного курса ODS, нужно разобраться как всё это работает.*


# Часть 3. Разбираемся как работает часть 2.

*Заглянем в оф.док по Pandas и познакомимся со средствами визуаллизации* 

1. [Визуализация](http://playittodeath.ru/анализ-данных-при-помощи-python-графики-в-pandas/) данных с помощью Pandas и matplotlib. 
2. Более подробно о [визуализации](http://pandas.pydata.org/pandas-docs/version/0.20/indexing.html) данных с помощью Pandas.  
3. Процедура логической индексации данных в Pandas - [кратко](http://pandas.pydata.org/pandas-docs/version/0.19.2/10min.html?highlight=bool#boolean-indexing). 
4. [Мануал](http://pandas.pydata.org/pandas-docs/stable/api.html#api-reference) Pandas, в которой рекомендуется хоть иногда заглядывать.
5. Хорошая иллюстрация возможностей [конструктора](http://pandas.pydata.org/pandas-docs/version/0.18.1/generated/pandas.pivot_table.html) сводных таблиц.   
6. Хороший и наглядный мануал по научной графике в исполнении [matplotlib](https://pythonworld.ru/novosti-mira-python/scientific-graphics-in-python.html). 
7. [Архив](https://tomaugspurger.github.io/modern-6-visualization.html), который описывает возможности других библиотек в отношении графики в Pandas. 
8. На случай, если происходящее как то будет связано с [Excel](https://habrahabr.ru/company/otus/blog/331998/) без участия Pandas, хотя Pandas умеет в Excel.

*Заглянем на оф.сайт [Анаконды](https://www.anaconda.com/download/) и найдём [мануал по ней](https://docs.anaconda.com/anaconda/user-guide/tasks/integration/)*

*Режим читов - тетрадка Юпитер*

1. Сайт проекта [Юпитер](http://jupyter.org).
2. [Введение](https://www.openfablab.org/play/default/showtask/196) в тетрадку Юпитер.
3. Второй полезный [tutorial](https://github.com/DonJayamanne/pythonVSCode/wiki/Jupyter:-Getting-Started) по тетрадке. 
4. Это не баг - а фича! [сборник](https://habrahabr.ru/company/wunderfund/blog/316826/) особенностей тетрадки.

**IPython**

1. [Исходник](https://pypi.python.org/pypi/ipython/6.0.0)
2. [Инструкция](http://ipython.org/ipython-doc/dev/interactive/tutorial.html) 

**Либы**

1. [Plotly](https://plot.ly/python/) - интерактивные HTML графики и красота.  
2. [Seaborn](http://seaborn.pydata.org/index.html) - основной инструмент визуального анализа.
3. [NumPy](https://docs.scipy.org/doc/numpy/reference/) -  инструкция к математическому аппарату происходящего.
4. [Scikit-learn](http://scikit-learn.org/stable/tutorial/basic/tutorial.html) - инструкция к библиотеки про machine learning, сложная. 

*Предпологаеться хотя бы иногда подглядывать в тот или иной мануала за вопросом "как сделать" прежде чем искать готовый ответ в google, кстати, достаточно часто его там нет. Его там нет не потому что его нет - нет няши, всё проще, его там нет потому, что ответ на вопрос будет звучать так:* **RTFM**. 

# Часть 4. Вспоминаем математику.

*Если часть 3 носит относительно обзорный характер материалов, которыми вы будете пользоваться несколько лет, то эта часть более важна. Богом математики быть не обязательность, но разруха в голове должны быть на уровне: мне известна разница между корреляцией по Пирсону и по Спирману и один из этих методов является для меня более предпочтительным. Лично я всегда любил ранговую корреляцию и все свои модели приводил именно к ней.*

1. Кратко про коэффициент корреляции [Пирсона](http://py-algorithm.blogspot.ru/2014/08/blog-post_10.html). 
2. Про [математику](https://nahlogin.blogspot.ru/2016/01/pandas.html)  как часть визуального анализа. 
3. Хорошая [шпаргалка](http://playittodeath.ru/shpargalka-po-statisticheskomy-analizu/) по статистическому анализу.  
4. [Серия](http://math-info.hse.ru/2014-15/Компьютерные_инструменты_обработки_данных) поучительный лекция про [инструменты](http://math-hse.info/a/2014-15/nes-stat/lectures/lecture15.html) анализа. 
5. [Отличный материал](http://playittodeath.ru/анализ-данных-при-помощи-python-основные-ст-2/) по анализу статистических данных в Pandas 

*В теории, нужно хотя бы запомнить что между 1 и 0 есть 0.25, 0.5 и 0.75.* 

# Часть 5. Пробуем читать про t-SNE.

*Второй урок учебного курса ODS наглядно демонстрирует один из методов построения t-SNE представления. Забегая вперёд могу сказать - что, эта штука такая же полезная как и весь остальной "machine learning" и такой вариант, как "потратить пару лет только на изучение t-SNE вполне уместен. Например, если овладеть одним из методов, можно сразу идти устраиваться работать с поисковыми системами*.

1. Сложное, но очень хорошее [intro](http://datareview.info/article/algoritm-t-sne-illyustrirovannyiy-vvodnyiy-kurs/).
2. [Инструкция](http://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html) к этому празднику жизни. 
3. [Причина](https://habrahabr.ru/post/165001/) - по которой нужно уметь в Pandas и t-SNE. 
4. Техника [визуализации представления слов](https://habrahabr.ru/post/267041/) с помощью t-SNE. 
5. [Сочетание возможностей t-SNE](https://habrahabr.ru/company/wunderfund/blog/326750/) в алгоритмами компьютерного зрения. 
6. После чтения статьи про алгоритм Джонкера-Волгенанта советую посмотреть [сюда](https://distill.pub/2016/misread-tsne/).
7. Пожалуй, самая важная ссылка раздела - [репозиторий](https://github.com/scikit-learn/scikit-learn/pull/4025) с кодом посвященный библиотеке scikit-learn.
8. [Multicore t-SNE modification](https://github.com/DmitryUlyanov/Multicore-TSNE) - акутально, когда массив данных большой и интерпретатор  возвращают memory error.

*Эксперименты с датафреймами из первого и второго запуска учебного курса ODS в части t-SNE могут легко и красиво познакомить вас с пределом вычислительных мощностей вашего компьютера, даже если вы работаете с маленькими массивами вроде telecom churn.csv. В теории Multicore-t-SNE лучше работает с большим выборками, на практике t-SNE прожорлив в следствии большой вычислительной сложности. Скажем так - если дома калькулятор, можете забыть.*

*Как минимум это 14(12) GB Ram и разлоченный 4170 quad-core*

# Часть 6. Возвращаемся к части 2 с новыми знаниями.

*Вот теперь, можно вернуться к началу учебного курса ODS и попробовать самостоятельно провести анализ данных из первой части курса прежде чем отправляться в дебри machine learning. Так или иначе вам потребуется способность формировать оценочное суждение о данных с которыми вы работаете прежде чем строить вокруг них лес решений.*

**Бонус для облегчения процесса.**

1. [Ранговая](https://docs.scipy.org/doc/scipy-0.19.0/reference/generated/scipy.stats.spearmanr.html) корреляция.
2. Полезная подборка [годноты](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks).
3. [Функция](https://pandas.pydata.org/pandas-docs/stable/generated/pandas.melt.html), которую нужно выучить. 
4. Это не баг - это [фича](https://habrahabr.ru/post/279665/) статистики. 
5. Если вы до сих пор читали по [диагонали](http://pandas.pydata.org/pandas-docs/stable/search.html?q=describe&check_keywords=yes&area=default). 
6. [Возможности](https://www.jetbrains.com/help/pycharm/viewing-as-array-or-dataframe.html) PyCharm в сочетании с Pandas.
7. Полезный [раздел](https://pandas.pydata.org/pandas-docs/stable/computation.html) мануала Pandas в области статистики.
8. Важно знать что Pandas [самостоятельно](https://pandas.pydata.org/pandas-docs/stable/timeseries.html) работает с датами.

# Часть 7. Знакомство с Machine Learning.

*Серия полезных материалов для ознакомления с предметной областью machine learning*. 

1. Обзорная [статья](https://habrahabr.ru/company/mlclass/blog/247751/).
2. Источник [годноты](https://habrahabr.ru/company/mailru/blog/334960/#stati) ODS.
3. Строим [первый](https://habrahabr.ru/company/ods/blog/322534/) лес решений.
4. Ломаем голову над [математикой](https://habrahabr.ru/company/ods/blog/322076/).
5. Поучительный пример [построения](https://habrahabr.ru/post/327072/) прогноза.
6. Ещё один [хороший пример](https://habrahabr.ru/post/266639/) и набор данных для тренировки.
7. [Лекция](http://blog.yhat.com/posts/predicting-customer-churn-with-sklearn.html) про то - что такое **Churn** и почему он именно такой.
8. Ну, типа [учебный курс udemy](https://www.udemy.com/python-for-data-science-and-machine-learning-bootcamp/)


# Часть 8. Хаппиенда не будет.

*Если вы смогли прочитать по-диагонали хотя-бы половину ссылок, значит:*

1. вам пришлось много кодить на Python в IDE и IPyhton в тетрадке.
2. вы смогли пару раз криво построить представление t-SNE.
3. вы получили кучу memory error и теперь у вас 14Gb MRam.
4. вас ненавидят в чатике https://t.me/ru_python_beginners
5. вы ненавидите богов математики из слака ODS.
6. по ночам пришлось спать.
7. а не смотреть аниме.
8. отлично!

*Поздравляю, вы испортили себе жизнь настолько, что теперь можете написать датафрейм самостоятельно, пришло время для следующей части учебного [курса](https://habrahabr.ru/company/ods/blog/323890/)*.

*Кроме этого, настоятельно рекомендуеться научиться логический индексации в Pandas, разобрать свалку тетрадок и хоть что нибудь залить на Гит.*

*Рори [одобряет](http://coub.com/view/cgkmg)* 

# Часть 9. Дисклеймер.

*Дорогие бегинеры! если вы, как и я любите аниме - не читайте ссылки на материалы представленные в этом файле, изучение Python имеет одну особенность, которую лучше всего можно описать [так](http://coub.com/view/v66rg). Поэтому, даже если у [вас](http://coub.com/view/xgbnx) - это не повод портить себе жизнь и прекращать смотреть мультики.*

*Когда год назад один лид продюсер дал мне совет "ну... с твоими скиллами и сколнностью к ранговой корреляции всего и вся в процессе танслирования той разрухи в голове, которую ты выдаешь за скилл и идеи в области проектирования EPR систем тебе надо выучить Питон"..*

*Я не распознал подвоха и повёлся на этот прикол из уст человека, который в тот момент занимался тем, что учился кодить в руби шахте с целью перезда в другой город подальше от своих карьерных достижений...*

*И в результате оказался занят чем угодно, кроме просмотра аниме*

*Это не вдохновляет, я хочу [обратно](http://coub.com/view/xiulz)! И хуже всего то, что я стал понимать о чём говорят другие программисты в чатике, хотя сначала чатик для меня выглядел примерно вот [так](http://coub.com/view/x8gk5):*
