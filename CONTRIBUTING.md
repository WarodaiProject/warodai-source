Об участии в проекте WARODAI
=================================

<!-- TOC depthfrom:1 orderedlist:true -->

- [1. ФОРМЫ УЧАСТИЯ](#1-формы-участия)
- [2. КОНТРОЛЬ КАЧЕСТВА](#2-контроль-качества)
- [3. РЕКОМЕНДАЦИИ ПО РАБОТЕ](#3-рекомендации-по-работе)
    - [3.1. Работа с тикетами](#31-работа-с-тикетами)
    - [3.2. Работа над словарными карточками в репозитории](#32-работа-над-словарными-карточками-в-репозитории)
- [4. ТРЕБОВАНИЯ К УЧАСТНИКАМ](#4-требования-к-участникам)
- [5. ОГОВОРКА ДЛЯ ОПЫТНЫХ ПОЛЬЗОВАТЕЛЕЙ GIT И GITHUB](#5-оговорка-для-опытных-пользователей-git-и-github)

<!-- /TOC -->

# 1. ФОРМЫ УЧАСТИЯ

Работа над словарём ведётся в специальном репозитории на платформе [Github](https://github.com/WarodaiProject/warodai-source).

Участие в проекте возможно в следующих двух формах:

- работа над тикетами (issue) в репозитории [warodai-source](https://github.com/WarodaiProject/warodai-source/issues);
- работа над словарными карточками с помощью [специального редактора](https://www.warodai.ru/editor).

Если вы только начинаете работать в проекте, мы рекомендуем попробовать свои силы в обработке тикетов. Для этого лучше всего завести учётную запись на Github. Если после определённой тренировки в работе над тикетами вы почувствовали, что готовы взять на себя ответственность за правки в словарных карточках, вы можете претендовать на получение статуса составителя (роль «Collaborator» в репозитории).

Статус составителя будет предоставлен вам в том случае, если другие составители по результатам анализа ваших тикетов твердо удостоверятся в том, что с их стороны не потребуется постоянно контролировать корректность ваших действий. Иными словами, будет установлено, что:

а) вы демонстрируете достаточно глубокое понимание понятий *современный японский язык*, *язык массовой коммуникации*, *толкование*, *перевод*, *производное*, *выражение* как они раскрыты в [разделе 2 README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#2-%D0%BE-%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%B5);

б) вы строго следуете правилам оформления, изложенным [в разделе 3 README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#3-%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D0%BD%D0%B0%D1%8F-%D1%81%D1%82%D0%B0%D1%82%D1%8C%D1%8F);

в) вы надежно обосновываете ваши решения по правкам и добавлениям.

# 2. КОНТРОЛЬ КАЧЕСТВА
В работе над словарем WARODAI составители всемерно стараются поддерживать уровень качества, характерный для академических справочных изданий, к числу которых относится Большой японско-русский словарь под редакцией академика Н.И. Конрада. С оцифровки словника именно этого словаря в 2006 году был начат настоящий проект. Конечной целью составителей является достижение уровня качества, при котором пользователи словаря могут быть уверены в приведённых в нем сведениях настолько, чтобы не обращаться к другим справочным изданиям для их проверки.

В связи с этим каждое исправление или дополнение в словаре должно быть тщательно выверено и соответствовать принципам и правилам, изложенным в файле [README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md). Независимо от того, вносите ли вы свой вклад через работу над тикетами или редактирование репозитория, залогом поддержания заявленного уровня качества является следование следующим двум основным правилам:

> Строгим критерием включения *слова* или *значения* в настоящий словарь является фиксация такового не менее чем в двух авторитетных толковых или переводных японских словарях (см. список в [п. 2.5 файла README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#25-источники)).

> Строгим критерием включения в словарь *выражения* является его нахождение хотя бы в одном авторитетном толковом или двуязычном японском словаре или не менее чем в двух разнородных источниках, относящихся к сферам бытования языка массовой коммуникации, перечисленных в [п. 2.2 файла README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#22-лексический-состав-словаря). Под разнородными в данном случае понимаются источники, как можно более различающиеся по характеру информационного носителя и по признаку устности-письменности.

# 3. РЕКОМЕНДАЦИИ ПО РАБОТЕ

## 3.1. Работа с тикетами
Добавлять тикеты вы можете как в [соответствующем разделе репозитория](https://github.com/WarodaiProject/warodai-source/issues), так и на сайте [www.warodai.ru](https://www.warodai.ru). При этом все тикеты, добавленные через сайт warodai.ru, автоматически поступают в репозиторий. При отправке тикета вам необходимо обосновать предлагаему в нём правку или новую карточку. В качестве обоснований можно привести ссылки на авторитетные словари из [п. 2.5 файла README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#25-источники) или другие источники, соответствующие списку в [п. 2.2 файла README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md#22-лексический-состав-словаря). 

Тикеты могут иметь следующие ярлыки (label):

а) «Комментарий из warodai.ru» — тикеты, автоматически заведённые для комментариев, присланных с сайта warodai.ru; если тикет был добавлен как редакция уже имеющейся в словаре карточки, то он будет также иметь дополнительный ярлык «редакция», если как новая карточка — дополнительный ярлык «новая».

б) «Комментарии к eБЯРС» — тикеты, содержащие комментарии редакторов, внесенные во время обработки электронной версии БЯРС.

Тикеты с этими ярлыками имеют приоритет в обработке. В подавляющем числе случаев информация, представленная в тикете, требует проверки и обоснования соответствующих правок. Вы можете провести такую проверку и обосновать или отклонить необходимость изменения. Всю соответствующую информацию можно давать в комментариях под тикетом. Такая информация должна включать ссылки и выписки из авторитетных словарей и надежных источников. Выписки должны быть как можно более краткими, однако достаточными для того, чтобы другой участник, знакомящийся с ними, не был вынужден перепроверять приведённые сведения или уточнять их. 

Допускается в некоторых случаях ссылаться при обосновании на личные консультации, полученные у эксперта в той или иной области. При этом с согласия эксперта следует указать его инициалы, фамилию, степень, звание или иную информацию, подтверждающую его экспертный статус. В конце каждого обоснования рекомендуется давать *вывод* или *резолюцию*, в которых среди прочего чётко сформулировать, какие действия вы предлагаете предпринять (например, «добавить такой-то вариант написания» или «добавить новую карточку» или «отклонить»). Пример обработки тикета можно посмотреть <a href="https://github.com/warodai/warodai-source/issues/2259">здесь</a>.

Вы можете участвовать в работе над уже имеющимися тикетами, добавляя комментарии к ним. Такая форма работы возможна только внутри [репозитория](https://github.com/WarodaiProject/warodai-source/issues), поскольку на сайте warodai.ru средств просмотра тикетов и их комментирования нет.

Закрыть тикет может только составитель после рассмотрения всех обоснований и внесения соответствующих изменений в словарные карточки.

## 3.2. Работа над словарными карточками в репозитории
Если вы являетесь составителем словаря, вы можете редактировать словарные карточки с помощью [специального редактора](https://warodai.ru/editor/). При работе над карточками необходимо строго следовать принципам и правилам, изложенным в файле [README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md). Авторизация в редакторе осуществляется с помощью вашей учётной записи Github. При авторизации производится проверка того, что вы имеете права на запись в репозитории warodai-source.

При сохранении изменений в редакторе следует указывать ссылку на соответствующий тикет в форме `#номер_тикета`. Это позволяет системе Github автоматически показывать ваши правки в этом тикете. В подавляющем числе случаев изменения в словаре должны ссылаться на тикеты. Исключение составляют лишь такие очевидные правки, как исправление явных орфографических ошибок и опечаток в переводах, а также мелкие ошибки в оформлении статьи.

Из этого следует, что если вы не вносите изменений, обоснованных уже имеющимся тикетом, то вы должны завести такой тикет самостоятельно. В нём необходимо провести всю работу по обоснованию правки, и только после этого вносить ее в словарь.

Словарная карточка не должна содержать никаких редакторских комментариев, заметок, пояснений и т.п. Все они выносятся в тикеты.

Не следует сохранять в словаре карточки с нарушениями правил оформления. При сохранении следует исходить из понимания, что в любой момент может быть запущена автоматизированная процедура сборки очередной версии словаря, которая заберёт недоделанную карточку и опубликует её. Поэтому нажимать кнопку «Сохранить» в редакторе следует только в моменты, когда карточка имеет правильное оформление. В карточке могут иметься не все значения и примеры, но всё, что в ней уже есть, должно быть оформлено правильно.

# 4. ТРЕБОВАНИЯ К УЧАСТНИКАМ

Никаких специальных требований к языковой подготовке участников не предъявляется. Если вы не владеете японским языком или только начинаете его учить, вы можете принять участие в проекте, помогая с корректурой переводов, проверкой оформления, поиском статей в словарях и т.п.

К участникам предъявляются строгие требования по соблюдению принципов и правил, изложенных в файле [README](https://github.com/WarodaiProject/warodai-source/blob/master/README.md).

При работе над обоснованием исправлений и дополнений участники проекта обязуются соблюдать принципы научной добросовестности. В первую очередь, это относится к точности указания источников.

При обсуждении тикетов участникам рекомендуется придерживаться общих принципов ведения научной дискуссии. К текстам внутри тикетов предъявляются менее строгие требования, чем к тексту словарных статей. Здесь допустимо наличие несущественных орфографических, пунктуационных и стилистических ошибок, не мешающих, однако, точной передаче важных для состовителей сведений.

В текстах тикетов и обсуждений к ним запрещены любые рекламные объявления — скрытые или явные. Участникам рекомендуется придерживаться тем, непосредственно связанных с содержанием словарных статей.

# 5. ОГОВОРКА ДЛЯ ОПЫТНЫХ ПОЛЬЗОВАТЕЛЕЙ GIT И GITHUB
Вы можете предлагать свою редакцию карточек словаря по модели «Fork + Pull». При этом рекомендуется в рамках одного pull request предлагать редакцию не более одной карточки.
Большая часть участников этого проекта, обладающих правами приема pull request, являются специалистами в отраслях знаний, не предполагающих уверенного владения системами контроля версий. Поэтому наберитесь терпения — ваш pull request может быть рассмотрен с некоторой задержкой.
