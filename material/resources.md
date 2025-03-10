# Resource
> TODO: добавить описания, унифицировать оформление

- Онлайн компилятор, если прям очень срочно нужно: https://dotnetfiddle.net/
- Онлайн конвертор C#->JIT->IL, на случай, если вы начали читать Рихтера: https://sharplab.io/

## Courses

- Сайт с курсами от Контура, uLearn: https://ulearn.me/
- Вводные курсы от MS (а на сайте есть очень много разного увроня!):
  - https://docs.microsoft.com/ru-ru/learn/paths/csharp-first-steps/
  - https://docs.microsoft.com/ru-ru/learn/paths/csharp-logic/
  - https://docs.microsoft.com/ru-ru/learn/paths/csharp-data/
- Метанит, где есть все: https://metanit.com/
- Доки от MS: https://docs.microsoft.com/en-us/

## Books

Собрал список книг, которые могу предложить прочитать. Я либо их читал/знакомился, либо планирую этого сделать.

### CSharp

- "М. Прайс - CSharp 7 и Net Core. Кроссплатформенная разработка" - книга с которой можно начать, получить представление о всей платформе .NET, узнать про Core и Standard, основные элементы языка и поверхностно ознакомиться с технологиями ASP, UWP и Xamarin.
- "Э. Троелсен - Язык программирования C# 7 (8-е издание)" - одна из самых известных книг по языку C#. В ней довольно детально рассказывают про многие базовые аспекты C#/.NET. И это как хорошо, так и плохо. С одной стороны - после прочтения сложится общее понимание как все устроено и таких знаний хватит довольно надолго. Но детально в этой книге рассказывают также таки вещи как CLR, и читатель впервые начинает читать про синтаксис языка C# где-то спустя 100 страниц. К этому времени уже можно решить, что C# не твое. Так что советую очень правильно выбирать с какой главы начинать знакомство.
- "Д. Албахари - C# 7.0. Справочник. Полное описание языка". Книга где есть вся нужная информация, чтобы начать понимать C#. Но даже из названия можно понять, что это не книга для прочтения, а справочник. К ней рекомендуется обращаться, когда нужно подробно рассмотреть определенную тему.

### CSharp advanced

- "Дж. Скит - C# для профессионалов. Тонкости программирования" - Отличная книга, в которой рассказываются о истории языка, о том как реализованы различные механизмы и почему именно так. Отличный способ пересмотреть свой взгляд на привычные вещи в C#.
- "Дж. Рихтер - CLR via C#". Та самая классика, где рассказывают все (но это не точно), что нужно знать разработчику, чтобы C# не был для него магией. Книга приоткрывает занавес, пытаясь показать читателю как .NET понимает код, которые он пишет. 
- "C# Notes for Professionals". Это даже не книга, а скорее подборка примеров кода на C# на совершенно различные случаи начиная от синтаксиса операторов и заканчивая сериализацией, кодогенирацией и криптографией. Знакомиться в таком формате с языком можно только при условии, что есть полное понимание того, как работает какой-то схожий язык и хочется быстро сменить синтаксис с Java на C#.
- "А. Фримен - LINQ для профессионалов". Все что нужно знать про LINQ и много больше. Эта книга не только расскажет как правильно использовать LINQ, но и также может вдохновить вам на использование Fluent-интерфейсов в проектировании своей архитектуры.

### SQL и работа с базами данных

- "SQL cheat sheet (sqltutorial)" - лучшее решение для тех, кто уже разобрался с SQL, но не работает постоянно и забывает синтаксис языка.
- "Р. Виейра - Программирование баз данных Microsoft SQL Server". Книга полностью посвящена работе с SQL Server, она не связана с C# и .NET, но знания из этой книги помогут находить правильный подход к работе с базами данных.
- "А. Фримен - Entity Framework Core 2 для ASP" - книга, которая раскроет все аспекты при работе с Entity Framework.

### Паттрены, Clean code etc

- "OReilly - Паттерны проектирования". Если вы знакомы с одной из книг OReilly, то знаете, что они отличаются высоким уровнем доступности, в них очень хорошо и просто расписывают тему книги. И эта - не исключение. Данная книга отлично подходит для тех, кто не знаком с паттернами вообще. В нем будут дается описание каждого из, а также примеры, чтобы появилось понимание что и когда лучше применять.
- "Тепляков - Паттерны проектирования на платформе NET". СКорее всего, самая популярная книга про паттерны в мире .NET. Хорошо изложенная теория, которая подкрепляется практикой. Что еще нужно? Но не стоит накидываться и читать от корки до корки. Все же, паттерны - это ситуативная вещь. К этой книге стоит прибегать только когда вы точно решили, что нужно использовать определенный подходи и хотите узнать больше о нем.
- "M. Fauler - Refactoring". В этой книге собраны идеи и подходы к написанию кода, поднимается вопрос "А хороший ли этот код?".
- "S. McConnell - Code Complete". Совершенный код - это первая книга, в которой я увидел мысль, что "Программирование - это не только про написание кода". И правда, одна из первых глав - это рассказ о том, как важны в разработке метафоры и как их правильно использовать. Данная книга поможет изменить подход к инструментам, которые вы используете (например, ваш язык программирования - это тоже инструмент), но стоит брать во внимание, что выгода от прочтения прям пропорциональная вашему уровню знаний на момент начала чтения.

### Bonus

Тут будут книги, которые не сильно связаны с изучением C#, но они дадут вам второстепенные навыки или альтернативные взгляды.

- "М. Фаулер - UML. Основы". Язык UML - это де-факто стандарт графического описания систем. Он очень удобен для визуализации вашей архитектуры и поможет сократить часы на объяснения другому человеку логики работы вашего кода.
- "Теория категорий для программистов (перевод глав книги Б. Милевски)". Больно, непонятно и очень больно - это те чувства, которые я испытывал первые N раз, когда открывал эту книгу. Но с этим нужно смириться и принять. Взамен вы получаете совершенно другой подход к проблемам - математические абстракции. И если все правильно воспринимать, то у вас начнет время от времени проскакивать мысль "о, похожую формулировку я встречал в той книге, можно попробовать написать такое решение".и вы начнете понемногу внедрять в свой код те самые абстракции, которыми и должен оперировать разработчик во время работы. 
- "В. Вернон - Domain Driven Design". Если вы уже ознакомились с ООП, то знаете общие подходы. Но так уж сложилось, что они у большинства разработчиков ООП связано с наследованием, полиморфизмом, инкапсуляцией. Другими словами - с правилами как использовать разработанный концепт. Но абсолютно никто не говорит о том, как это правильно описывать, как выделять те классы, которые потом будут наследоваться. На таки вопросы можно найти ответы в этой книге. Если попытаться ее описать кратко - она про то, как научиться правильно описывать то с чем вы работаете на формальном языке.

<!-- То, что я не включил:
- Dependency Injection. Книжка хай-левела. Она не сколько о шарпах, больше о проектировании и подобном. Я ее сам еще не читал, но на нее очень хорошие рецензии. Читать уже после Рихтера, разве что.
- A. Davies - Async in CSharp 5.0 - В этой книге описывают важные аспекты новой фичи (асинхронности) в шарпе. Читать есть смысл когда уже будут знания общие и нужно будет именно с асинхронностью познакомится.
- The Task-based Asynchronous Pattern - полное погружение в асинхронщину.
- under-the-hood-of-net-memory-management - все про память в C#.
- Боуэн, Крейн, Резник - Основы Windows Communication Foundation для .NET Framework 3.5
- Мак-Дональд Мэтью - Windows Presentation Foundation в .NET 4
- Петцольд Ч. - Windows Presentation Foundation (WPF)
- ASP.NET Core MVC 2, Фримен
- NET-Microservices-Architecture-for-Containerized-NET-Applications-(Microsoft-eBook)
- Architecting Modern Web Applications with ASP.NET Core and Azure
- Скот Чакон - Pro Git
- Фаулер - Архитектура корпоративных программных приложений
- Крис Смит - Программирование_на_FSharp
-->