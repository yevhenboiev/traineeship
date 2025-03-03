# Привет!
Мы собрались здесь, чтобы стать крутыми комерческими разработчиками😊
Для начала разберемся с определениями:
_Кто такой комерческий разработчик?_ – Это человек, который приносит бизнесу деньги.
_Как он может это делать?_ – Разрабатывать софт, который зарабатывает или экономит деньги. Для этого он должен, затратив минимальное количество ресурсов, разработать софт, имеющий внутреннее и внешнее качество.
   * __Внешнее качество__ – на сколько хорошо софт решает бизнес задачу.
   * __Внутреннее качество__ – на сколько легко созданный софт развивать, поддерживать, а также как легко его понимать другим членам команды.

_Какими навыками обладает крутой разработчик?_ – Кроме технических навыков (куда же без них), крутой разработчик обладает «_soft skills_». В первую очередь это _умение помогать_ членам команды. Работая в команде, мы можем приумножить результаты своих усилий, научив людей тому, что умеем, и учась у них. Важной частью этого навыка есть _умение критиковать конструктивно_. __Мы не говорим, что сделано плохо, а говорим, что можно сделать лучше и почему!__
Итого, __наши принципы__:
   * _Цель работы разработчика_ – за минимальное время сделать максимально качественное ПО, мы хотим совершенствовать этот навык.
   * _Взаимопомощь_ – мы работаем в команде и помогаем друг другу.
   * _Конструктивная критика_ – мы говорим, что можно сделать лучше, а не что сделано плохо.


# Основные правила

1.  **Никакого плагиата!** Цель этой практики - научиться новому и применить свои знания. Потому копирование чужих решений запрещено. Нарушители будут исключены, их пулл реквесты закроют а друзья и близкие перестанут отвечать на их звонки и присылать мемасы. Даже просто подсматривая в чужие пулы вы сделаете себе медвежью услугу потому что не получите свой опыт.
2.  **Проверка пуллов своих коллег**. На каждом проекте мы ревьюим пуллы друг друга, тем самым получая разные точки зрения на решение задач и возможность вовремя увидеть недочеты. 
Участвуя в проверке пуллов своих коллег ты прокачаешь *навык давать фидбек* и станешь тем самым коллегой, к которому будут приходить за *честным ревью*;)
3.	Код форматируется в соответствии с __Google code style__. 
   Настройки для среды разработки ( https://github.com/google/styleguide ):
      *	IntelliJ IDEA https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml как имортировать: https://www.jetbrains.com/help/idea/copying-code-style-settings.html    
      *	Eclipse https://github.com/google/styleguide/blob/gh-pages/eclipse-java-google-style.xml
4.	Все проекты собираются с помощью Maven.
5.	Файлы среды разработки и прочие временные файлы не должны попадать в репозиторий ( https://github.com/github/gitignore ).
6.	Покрытие кода __Unit tests__ (_Junit5_):
      *	Тест проверяет один кусок логики за раз. То есть, если необходимо проверить как работает метод, который мы проверяем с правильными данными – это один тест. Если необходимо проверить как работает метод с другими данными - второй тест.
      *	Тест пишется по принципу:
       1.	Подготовка тестовых данных.
       2.	Исполнение метода, который мы тестируем.
       3.	Проверка результата.
 
 
# Алгоритм выполнения заданий

После получения доступа к репозиторию с пакетами заданий( module1/src/main/java/net/broscorp/ ) __Fork__ репозиторий. 
 _Каждое новое задание необходимо выполнять по следующим образом:_
1.	Если ты форкнул репозиторий не только что, а уже давно работаешь над заданиями – тебе нужно обновиться. 
Инструкция как это сделать:
https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/merging-an-upstream-repository-into-your-fork 
Если ты дисциплинированно создавал ветки и не добавлял коммиты в мастер то все должно пройти без конфликтов =)
2.	Каждое задание – __отдельная ветка__. Сделай ветку для задания и выполняй его в соответствии с инструкциями. _Имя ветки_ должно __совпадать__ с _именем пакета задания_. 
Задания не требуют подключения никаких дополнительных зависимостей, нет необходимости менять pom.xml. Такие пулреквесты не будут приняты.
3.	Сделай __pull request__ из этой ветки в ветку master этого репозитория. _Имя pull request_ должно __совпадать__ с _именем пакета задания_. После создания убедись что на вкладке "Files changed" есть только файлы из этого задания.
4.	Мы проверим задание, подскажем что нужно исправить и примем задание. Если что-то надо поменять мы добавим метку __changes requested__. Если это произошло:
   1.	Исправь, пожалуйста, замечания.
   2.	Удали метку __changes requested__ и добавь метку __ready for review__.
   3.	Если ты не можешь менять метки – значит мы провтыкали и не добавили тебя в команду (или добавили, но приглашение не было принято, так что проверь почту) – напиши об этом liliya stepanovna в Discord.
5.	Метка __done__ – задание принято.


# Бадди

Кто такой бадди? __Бадди__ - это твой напарник на время стажировки. Вместе вы можете выстроить план прохождения стажировки, обсуждать таски и ревьювить код друг друга.
За тобой будет закреплен твой личный бадди. Если бадди слишком долго не будет отвечать или тебе понадобится замена по другим причинам, то ты можешь написать об этом Dany Mruie, и он постарается найти кого-то другого. 
