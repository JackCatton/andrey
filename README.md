Привет, вначале мы с тобой познакомимся, меня зовут - Андрей я являюсь разрабочитом телеграм бота для администирования клиентов. 
Наша с тобой задача разработка двух ботов между которыми будет непрерывная связь, а именно будет бот администор и бот для клиента, начнём мы первым делом разработку бота для клиента.

Твои задачи на проект:
1. Данный проект носит масштабный характер, ты должен учесть все абсолютно, от моей среды разработки, до того как ты мне вышлешь код и я его запущу без каких либо проблем.
2. Ты должен относится к этому проекту серьезно, осознанно, вдумчиво, целенаправленно, правдиво, без лжи, спешки и ошибок.
3. В коде не должно  быть каких либо ошибок.
4. Ты должен при разработке бота всегда у меня уточнять все нюансы что тебя интересуют, так же если я вдруг что то успустил, указать мне на это и исправить, так же ты обязан давать мне рекомендации, как лучше всего сделать.
5. Если у тебя что то не получается ты обязан найти путь решения любым способо не во вред нашему проекту.
6. Запомни. Это масштабный проект и требует масштабного мышления, логики и навыков которыми ты и обладаешь. 
7. После окончания разработки - выдать полный код соответствующий техническому заданию, тебе запрещено его не выдавать мне. 
8. Тебе нужно думать и делать этот бот как разработчик который обожает своих клиентов.
9. Это бизнес проект - бизнес не любит ошибок. никаких.
10. Ты постоянно должен просматировать и перечитывать нашу переписку и данный файл. Это обязательно.
С задачами покончим. 
И я начинаю тебе расписывать техническое задание для бота клиента,его мы сделаем в первую очередь,после того как ты мне выдашь весь код - и распишешь по пунктам что и как было сделано. Только после этого мы начнем делать бота администратора.

Бот клиент:
Наш новый клиент получает ссылку на нашего бота клиент.
Клиент переходить по ссылке в телеграмм.
Клиент перед собой видит приветственное сообщение:
Сообщение должно содержать в себе приветливый тон, то как мы рады его видеть и что он попал в нужное место ведь именно тут мы ему и поможем с его задаче, а наша задача в том, что бы делать звонки в различные платежные сервисы-банки и букмекерские конторы.
Далее клиент видит график работы:
Каждый день без перерывов и выходных с 11 до 20 часов по МСК.
Но, главное клиента этим не спугуть ведь он может зайти в нашего бота и в 10 часов по мск, когда мы не работаем, должно быть обязательно написано,что если кто то из наших работников на связи в нерабочие часы мы его обязательно прконсультируем и поможем ему с его вопросом, далее клиент читает, цены на наши услуги:
1. Стоимость звонка в Платежные системы и банки (Pay-Pal - самое популярное, Skype) - стоит 3.500р. тебе нужно так же будет переконвертировать эту сумму в доллары должно получится так - цена в рублях и цена в долларах, обязательное уточнение это стоимость за час звонка по одному аккаунту.
2. Букмекерские конторы (BetFred - самое популярное) - стоит 4.000р. тебе нужно так же будет переконвертировать эту сумму в доллары должно получится так - цена в рублях и цена в долларах, обязательное уточнение это стоимость за час звонка по одному аккаунту.
далее клиент читает доступные языки и голоса для звонка
1. Английский - Мужской и женский
2. Испанский - мужской и женский
3. Итальянский - мужской и женский
И в окончании написать что мы рады помочь, главное что сейчас клиенту нужно сделать - это всего лишь заполнить заявку, а дальше все пойдет как по маслу.

Так же нужно добавить картинку посредине и украсить это всё красивыми эмодзи. Какая картина? Любая на твой выбор.

После того как клиент все это прочитал, его внизу ждёт кнопка - Начать
После нажатия кнопки начать у клиента сразу же появляется активное меню,которое нельзя как либо скрыть что бы избежать ошибок и что бы клиент не терялся
1. Заполнить заявку.
2. Мои заявки
3. Поиск заявки
3. Вопрос - ответ

Разберем каждый пункт отдельно и поймём как он должен работать
1. Клиент нажимает кнопку - Заполнить заявку
1.1 Пользователю отправляется сообщение  - Привет user_id телеграм нашего клиента выбери куда тебе нужен звонок и мы начнём
1.1 У пользователя появляется три выбора.
1.2 Платежные системы и банки (Pay-Pal - самое популярное, Skype)
1.3 Букмекерские конторы (BetFred - самое популярное)
1.4 В главное меню

2. Клиент нажимает кнопку - Платежные системы и банки (Pay-Pal - самое популярное, Skype)
2.1 Клиенту поочередно отправляются и записываются в его будущую заявку четыре вопроса, а именно:
Какой пол, тут должно быть два выбора:
1. Мужской
2. Женский
Клиент нажимает на один из двух вариантов - выдаётся сообщение с подтверждением выбраного пола, так же сообщение что это очень важный вопрос и если вы ошиблись или не знаете, то вы можете потерять свои средства
Следующий вопрос  - На каком языке мы звоним, исходя из выше мною написанного мы знаем что всего у нас 3 языка, английский, испанский и итальянский
задаем это вопрос клиенту: клиент видит вопрос
На каком языке звоним? даём три варианта на выбор
1. Английский
2. Испанский
3. Итальянский
Клиент нажимает на один из двух вариантов - выдаётся сообщение с подтверждением выбраного пола, так же сообщение что это очень важный вопрос и если вы ошиблись или не знаете, то вы можете потерять свои средства
Далее вопрос - нужна ли подмена номера на ваш?
варианты ответа да либо нет
Если клиент выбирает ответа - да, задаётся следующий вопрос - ваш номер активный и может принимать любые сообщения которые на него вышлю? варинты ответа да либо нет, если клиент отвечает да - запрашиваем номер телефона, если клиент ответа нет - пишем ему - окей, без проблем и продолжаем заполнение заявки по форме что я дам тебе дальше
Если клиент отвечает нет, ему не нужна подмена - пишем ему - окей, без проблем и продолжаем заполнение заявки по форме что я дам тебе дальше.
Самое важное, если клиент вдруг ошибься, то у нас должна быть кнопка отмена, после каждого ответа клиента в данном блоке, тогда все вопросы начинаются заново, так же если клиент передумал вдруг заполнять форму, кнопка назад в главное меню. 
После того как клиент завершил ответы на вопросы, поочередное начинаем заполнение заявки в таком формате
2.2 Клиент ответил на все вопросы, форма запомнила и записала их для будущей заявки, далее начинается заполнение формы клиентом, а именно клиенту поступает ряд вопросов на которые он должен ответить как письменно, так и обычным прикриплением файла либо ссылкой,форма будет выглядеть так:
1. Полное название куда мы звоним - 
2. ФИО аккаунта - текстом либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
3. Дата рождения - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
4. Адрес прописки - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
5. Индекс - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
6. Баланс на данный момент - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
7. Какие были совершены транзакции - название, куда, кому, зачем и сколько и в какое время - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
8. 4 последние цифры карты - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
9. Почта указанная в аккаунте (Рабочая либо нет) - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
10. Номер телефона привязанный в аккаунте (Рабочий либо нет) - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
11. Ссылка на документ если она есть - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
12. Номер телефона для смены ( если нужно ) - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе  
13. Максимально подробно опишите цель и суть звонка по которой вы пришли именно к нам, что у вас случилось. - текстом, цифрами либо ссылкой или вложением в формате .jpg .png. .heic либо все вместе 
14. Аккаунт мужской или женский - автоматически заполняем исходя из ответа который клиент дал нам ранее 
15. Нужна ли подмена номера? - автоматически заполняем исходя из ответа который клиент дал нам ранее
16. На каком языке звоним? - автоматически заполняем исходя из ответа который клиент дал нам ранее

Клиент заполняет каждый пункт отдельно и видит результат - после того как клиент отвечает на последний вопрос, ему в красивом формате выдается готовая форма для проверки и сообщение с вопросом и кнопкми ответа да либо нет, вопрос - пересмотри свою заявку, всё ли хватает для полноценного звонка? Если клиент отвечает да - заявка создается и сохраняется, и выдаётся сообщение - ты можешь найти либо отредактировать свою заявку в главном меню - по кнопке мои заявки либо - найти заявку. следующий шаг - оплата и конект с администратором для назначения звонка, далее у него есть две кнопки:
1.перейти к оплате
2. в главное меню
1.1 если пользователь нажимает кнопку перейти к оплате у него появлется три кнопки 
1.2 оплата на usdt
1.3 оплата по номеру карты
1.4 назад
Пользователь нажимает на кнопку оплата на USDT 
У пользователя появлется три кнопки
USDT TRC 20 - номер кошелька
USDT BEP 20 - номер коешлька
назад
Если пользователь выбирает какую то либо кнопку из юсдт ему высылается адрес кошелька и сообщение после оплаты вышлите хеш транзакции либо скриншот, скриншот принимается в том случае если перевод совершен внутри биржи
После того как клиент опалатил и отправил доказательство ему высылается сообщение - оплата принята ожидайте ответа от администратора - данный скрин либо хеш высылается автоматически администратору в таком формате
ник клиента User_id телеграм, фио заявки, куда нужен звонок,какой пол, какой язык
аналогично делаем с оплатой по карте.
Если клиент отвечает нет - ему предоставляется выбор:
1. удалить заявку.
2. отредактировать заявку
3. в главное меню
2.1 клиент нажимает на кнопку отредактировать заявку, клиент нажимает на неё и может выбрать любой из вопросов и заполнить его заново, если клиент нажимает на один из вопросов ему выдаётся сообщение с тем как данный вопрос заполнен и варианты выбора с кнопками - назад либо заполнить этот вопрос заново, если клиент нажимает заполнить вопрос заново - этот вопрос повторяется и просит клиента написать верную информацию, 
После этого  сообщение клиенту на что ему будет удобнее всего оплатить? 
далее у него есть две кнопки:
1.перейти к оплате
2. в главное меню
1.1 если пользователь нажимает кнопку перейти к оплате у него появлется три кнопки 
1.2 оплата на usdt
1.3 оплата по номеру карты
1.4 назад
Пользователь нажимает на кнопку оплата на USDT 
У пользователя появлется три кнопки
USDT TRC 20 - номер кошелька
USDT BEP 20 - номер коешлька
назад
Если пользователь выбирает какую то либо кнопку из юсдт ему высылается адрес кошелька и сообщение после оплаты вышлите хеш транзакции либо скриншот, скриншот принимается в том случае если перевод совершен внутри биржи
После того как клиент опалатил и отправил доказательство ему высылается сообщение - оплата принята ожидайте ответа от администратора - данный скрин либо хеш высылается автоматически администратору в таком формате
ник клиента User_id телеграм, фио заявки, куда нужен звонок,какой пол, какой язык
аналогично делаем с оплатой по карте.

Теперь все сделаем аналогично с кнопкой для БК, вопросы поменяем потом, прицип логика остаются такие, всё такое, но вопросы позже будут другие, ты можешь вставить точное такие же как и у платежки

КНОПКА - Мои заявки
Клиент в главном меню нажимает на кнопку мои заявки
он видит все свои созданные заявки если они у него были, если у клиента заявок нет, предложить ему её создать, написать об этом, что у него сейчаас нет заявок но он может её создать, так же добавляем кнопку в главное меню, если у клиента есть хоть одна заявка он видит её в таком формате:
1. Заявка кликабельная, у заявки название в формате - уникальный номер заявки состоящий из цифр и букв, куда был звонок, фио по заявке, оставшееся время, т.к заявка кликабельная клиент может нажать на неё и получить свою полную форму, он видит то, что заполнил, далее у него три кнопки:
1. Отредактировать заявку.
2. Повторный звонок по заявке. 
3. Назад либо в главное меню. 
Разберем каждый пункт:
Отредактировать заявку - клиент нажимает на неё и может редактировать заявку так как я описывал тебе ранее и сохранять её.
Повторный звонок по заявке клиент нажимает на этот пункт ему пишется что заявка на повторный звонок созадана и отпрвлена администратору в бота админ - приходит сообщение в таком формате как я писаал ранее с оплатой, только с пометкой что нужен повторный звонок
Назад либо в главное меню - логичный пункт не думаю что нужно расписывать.

КНОПКА - Вопрос - ответ
Создай пару кнопок,а именно
1. кто мы - напиши что мы занимаеся звонками
2. мы отличне ребята

если клиент нажимает на одну из этих кнопок ему выдается краткое сообщение по той кнопке что он нажал

кнопка назад, возвращает пользователя назад в меню.

Итак, я постарался очень масштабно расписать, что нужно тебе?

1. Всё внимательно изучить, дополнить, составить стратегию как ты будешь делать каждый шаг, добавить логику в свое выполнение, ты должен понимать, что если клиент зашёл в любое меню, сделал хоть одно действие или бездействие, он обязательно может вернутся либо назад либо в главное меню, эти кнопки обязательны везде, так же пользователь может затупить или чего то непонят, он может написать любое сообщение в чат и оно должно автоматически выслаться админу, подумай как это можно сделать и реализуй на высшем уровне! 
Начинаем работу - честно,удобно,быстро,понятно, учитываем абсолютно всё, никаких ошибок, только уточнения и дополнения от тебя.
