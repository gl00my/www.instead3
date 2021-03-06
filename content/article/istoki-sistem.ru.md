---
title: Истоки систем интерактивного повествования
date: 2017-03-22 00:01:00
disqus: y
author: true-grue
---

Речь пойдет о разработках далекого прошлого, которые несут в себе существенные элементы систем интерактивного повествования (ИП).

<!-- pagebreak -->

## Морфология сказки (1928)

Советский ученый, филолог-фольклорист В.Я. Пропп одним из первых начал анализировать морфологию текстов, их формальную сторону. Изучив структуру волшебных сказок, он выявил схему с 31 обобщенной функцией действующих лиц и однотипной последовательностью этих функций. С помощью соответствующей модели (иными словами — с помощью порождающей грамматики) получаются разнообразные варианты сказочных сюжетов.

## SAGA II (1960)

26 октября 1960 года в передаче «Thinking Machine» (см. раздел «Источники») канала CBS были показаны несколько сценок из жанра вестерн. Эти сюжеты созданы программой SAGA II (авторы Douglas Ross и Harrison Morse из MIT) на компьютере TX-O. Пользователь запускал программу командой «run» с параметром — затравкой для генератора псевдослучайных чисел. В процессе работы использовалось 16 переменных состояния (в духе: «шериф видит грабителя» или «дверь открыта»), а также множество «переключателей», которые производили вероятностный выбор между различными сюжетными ветвями. Примеры работы SAGA II можно обнаружить во втором томе «Искусства программирования» Д.Э. Кнута. 

## ELIZA (1966)

Виртуальный психотерапевт ELIZA Дж. Вейценбаума в особенном представлении не нуждается. Программа реагирует на ключевые слова в сообщениях пользователя и отвечает, используя подходящие правила преобразования.

## SHRDLU (1968)

Удивительная программа SHRDLU Терри Винограда, как и ELIZA, представляет собой диалог с компьютером на естественном языке. Главная особенность SHRDLU в том, что эта программа действительно пытается понять пользователя, а не просто «притворяется», как в случае с детищем Вейценбаума. Секрет в том, что разговор с компьютером ведется в терминах «мира блоков», достаточно простых для восприятия машиной.

## Automatic Novel Writing (1973)

Программа Automated Novel Writer Шелдона Клейна выдавала «рассказы об убийствах на 2100 слов, глубоко проработанные, менее чем за 19 секунд». Герои могли иметь различные характеристики, а конкретные убийца и жертва варьировались. «Вселенная» рассказа представлялась в виде семантической сети, моделирующей объекты и отношения между ними. Изменения состояния «вселенной» порождали очередные порции текста.

В 1974 году у Клейна вышла работа, где было описано применение той же системы к синтезу волшебных сказок по Проппу.

## TALE-SPIN (1976)

В программе TALE-SPIN (автор James Meehan) используется подход на основе постановки целей перед персонажами и последующего автоматического процесса движения по подзадачам к окончательным решениям. В базу знаний первоначально заносятся характеристики героев и окружающего мира, а также процедуры для решения различных частных задач. В этой системе нет предварительно подготовленных сюжетных фрагментов, и персонажи-агенты творят историю самостоятельно.

## Порождение структур волшебных сказок (1980)

Советский специалист по искусственному интеллекту М.Г. Гаазе-Рапопорт предложил свой алгоритм сочинения волшебных сказок на основе идей Проппа. Он основан на генерировании по нисходящему многоуровневому принципу: начиная с самых общих шаблонов (вариант экспозиции, основные константы сказки) и заканчивая конкретной глагольной структурой.

## AUTHOR (1981)

В своей статье Natalie Dehn противопоставляет подходу TALE-SPIN, основанному на моделировании мира и движении персонажей к своим целям, автороцентричный подход. Основу разработанной ей системы AUTHOR составляет моделирование поведения сочинителя: итеративное переформулирование целей, которые он перед собой ставит, а также вариантов их достижения.

## Hobbit (1982)

Знаменитая текстовая игра для ZX Spectrum с непревзойденным даже сегодня уровнем моделирования мира.

## UNIVERSE (1983)

Программа Universe (автор Michael Lebowitz) предназначена для сочинения сценариев бесконечных ТВ-сериалов. Сюжет генерируется на основе отдельных фрагментов, в которых описываются задачи и методы их достижения как со стороны персонажей, так и с точки зрения моделируемого сочинителя. Подход Universe имеет много достоинств и заслуживает самого внимательного изучения.

## Trust & Betrayal: The Legacy of Siboot (1987)

Крис Кроуфорд — один из самых незаурядных ветеранов-разработчиков компьютерных игр. Еще в 1983 году он создал небольшую и очень оригинальную игру Gossip на тему социальных взаимоотношений. Trust & Betrayal: The Legacy of Siboot можно считать развитием идей из Gossip. Кроуфорд называет героев своей игры «искусственными личностями», поскольку они обладают различными характерами, настроением, находятся в разнообразных взаимоотношениях. Для общения с персонажами игрок использует так называемый обратный парсер на основе пиктограмм.

## Заключение

Выскажу несколько замечаний по поводу систем интерактивного повествования в целом. Современную ИП-систему и «мир блоков» древней SHRDLU роднит общая «камерность» виртуальной обстановки. Это неудивительно, ведь в подобных системах слишком легко возникает комбинаторный взрыв сюжетных вариантов. Также имеется существенная разница между автоматическим генерированием лабиринтов, планет, имен персонажей в обычных играх и тем, что происходит в ИП-системах. В последнем случае алгоритмы опираются на «литературность», а не на «реализм». Важна не «процедурная генерация» ландшафтов и «искусственной жизни», а то, как эта «жизнь» драматургически взаимодействует с игроком и другими компьютерными персонажами.

Завершить этот текст мне бы хотелось парой слов об ИП-системах будущего. Вспомните, как бабушки рассказывают сказки своим внукам. Исходный сюжет часто меняется до неузнаваемости, слушатель и рассказчик воздействуют друг на друга. Теперь представьте себе игровой мир, игрока, а также рассказчика, роль которого выполняет компьютер. Рассказчик анализирует поведение игрока и в дело вступает обратная связь — сюжет становится более драматичным, захватывающим. Конечно же, пока совершенно неясно, как строить подобные вещи. Но поиграть в одну из таких систем будущего я бы не отказался. А вы?

## Источники

1. Морфология сказки
feb-web.ru/feb/classics/critics/propp/pms/pms-001-.htm

1. «Memorandum 8436-M-29: Preliminary Operating Notes for SAGA II»
bitsavers.trailing-edge.com/pdf/mit/tx-0/memos/Morse_SAGAII_Oct60.pdf
«An Account of Randomness in Literary Computing»
www.samplereality.com/2013/01/08/an-account-of-randomness-in-literary-computing/
«The Thinking Machine» (1961) — MIT Centennial Film
techtv.mit.edu/videos/10268-the-thinking-machine-1961---mit-centennial-film

1. «ELIZA--A Computer Program For the Study of Natural Language Communication Between Man and Machine»
www.csee.umbc.edu/courses/331/papers/eliza.html

1. SHRDLU hci.stanford.edu/winograd/shrdlu/

1. «Automatic Novel Writing: A Status Report»
minds.wisconsin.edu/bitstream/handle/1793/57816/TR186.pdf?sequence=1
«Modelling Propp and Levi-Strauss in a meta-symbolic simulation system»
ftp://ftp.cs.wisc.edu/pub/techreports/1974/TR226.pdf

1. «TALE-SPIN, An Interactive Program that Writes Stories»
gel.msu.edu/classes/tc848/papers/Meehan.Tale-Spin.pdf
“The Story of Meehan’s Tale-Spin”
grandtextauto.soe.ucsc.edu/2006/09/13/the-story-of-meehans-tale-spin/

1. Гаазе-Рапопорт М.Г. Поиск вариантов в сочинении сказок. В кн. Зарипов Р.Х. Машинный поиск вариантов при моделировании творческого процесса. – М.: Наука, 1983. – 232 с.
www.piano.ru/scores/books/zaripov.pdf

1. "Об автоматизации нетворческих литературных процессов", Карпов В.Э., Мещерякова Т.В.
www.interface.ru/home.asp?artId=36317

1. «Story Generation After TALE-SPIN»
nil.cs.uno.edu/publications/papers/dehn1981story.pdf

1. «Story Telling as Planning and Learning»
classes.soe.ucsc.edu/cmps148/Winter10/readings/LebowitzUniversePoetics14.pdf
«Lebowitz’s Universe, part 1»
grandtextauto.soe.ucsc.edu/2006/03/04/lebowitzs-universe-part-1/

1. Trust & Betrayal: The Legacy of Siboot
«Blowing my Siboot-Horn»
www.erasmatazz.com/library/the-journal-of-computer/jcgd-volume-1/blowing-my-siboot-horn.html