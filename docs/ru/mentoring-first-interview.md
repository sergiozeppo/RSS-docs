# Первое собеседование со студентами (Technical screening)

## 1. Перед собеседованием

### 1.1 Прочитать информацию о собеседовании из учебного плана студентов
https://github.com/rolling-scopes-school/tasks/tree/master/stage2/modules/technical-screening

### 1.2. Выбрать форму проведения собеседования
- 1to1 со студентом или в паре c вторым ментором. 
- В случае оффлайн интервью можно собеседовать сразу группу студентов. 

### 1.3. Выбрать место
- Онлайн (MS Teams, Google Meet, Skype) или оффлайн (офис, кафе, коворкинг и т.д.)
- Для онлайн собеседований могут быть полезны следующие инструменты:
    - https://codepen.io/
    - https://codeshare.io/
    - https://www.skype.com/en/interviews/
    - https://codepad.remoteinterview.io
    - https://repl.it/

### 1.4. Согласовать время и место проведения  
Студенты сами должны связаться с вами, у них есть контакты, которые вы оставили в RS App.
Если вы не хотите ждать, вам необходимо:
1. Посмотреть список студентов назначенных вам для собеседования: RS APP  > Interviews > Technical Screening
2. Использовать контактные данные студентов из его профиля в RSAPP или найти студента в Discord по гитхаб аккаунту

### 1.5. Посмотреть инфорацию о студенте
- Информацию из профайла студента в RS APP.
- Рейтинг студента в RS APP > Score.
- Прочитать CV, которое студенты делали в рамках одно из заданий. Он лежит в **личном** github репозитории студента `rsschool-cv`. (Внимание! там могут быть фейковые данные) 
- Посмотреть видеозапись самопрезентации студента. Ссылка на запись находится в приватном репозитории студента на аккаунте RS School в бранче "self-introduction". 
- Просмотреть работы студента по верстке. Можно и нужно задать доп. вопросы во время интервью. Ссылки на таски есть в score.
- Посмотреть работы студента по алгоритмическим таскам. Можно и нужно задать доп. вопросы во время интервью. Ссылки на таски есть в score.

## 2. Во время собеседования
**Важно во время собеседования быть вежливыми и понимать, что студенты обычно сильно нервничают.** 

### 2.1 ПРИМЕРНАЯ структура интервью
1) Ментор рассказывает о себе. Достаточно в 5+ предложений
2) Просим студента рассказать о себе
  - Опыт работы в любой сфере
  - Где учился
  - Мотивация изучать фронтенд
  - что угодно по вашему желанию:)
3) Легкая теория и простая задача, чтобы студент мог привыкнуть к атмосфере интервью.
  - примеры вопросов по html
    * отличие блочных от инлайн элементов
    * Значения атрибута display
    * Веса селекторов
    * Псевдоклассы
    * Box model
    * em vs rem, относительные и абсолютные величины
    * обязательные аттрибуты
    * data-attribute
  - Примеры задач
    * палиндром
    * удаление дубликатов из массива
4) Остальная теория и практика. Ментор заполняет фидбек форму - RS APP > Interviews > Technical Screening
5) Проверяем уровень английского (на глаз :))
6) Ментор рассказывает фидбек студенту 
	- Какие темы студент ответил хорошо
	- Над чем необходимо работать. Рекомендации.
	- Ваше решение (если оно уже есть)

### 2.2 Возможные варианты вопросов в ходе собеседования
Если вы собеседуете одновременно несколько человек, можно написать вопросы на доске, на которые студенты пишут ответы в любом порядке:
- Array vs List. Написать основные отличия. Нарисовать представление. 
- Нарисовать схему бинарного дерева или хэш-таблицы на доске или листе бумаги.
- Реализовать Stack.
- Convert decimal to binary. Выдавать несколько чисел. Написать (нарисовать) алгоритм перевода.
- Реализовать функцию сортировки массива. Написать какие еще алгоритмы существуют.  Указать Big O
- Можно попросить реализовать какую-нибудь задачу: 
```
a.
	“aabbbcccc” - >  “2a3b4c”
	“aaaaaaa” -> “7a”
b. 
	“((a))” -> true
	“((vvv()” -> false
c. Вычислить количество единиц в бинарном представлении:
	31 -> 5
	1 -> 1
	15 -> 4
d. Любая другая (например проверка палиндрома и т.д.)
```

- Почему вы решили стать фронтендером? Что нового узнали за последний год и из каких источников?
- Любые другие вопросы
- Вопросы по заданиям stage#1. Список заданий тут - https://github.com/rolling-scopes-school/tasks/tree/master/stage1

## 3. После собеседования
Результаты собеседования необходимо занести в форму - RS APP > Interviews > Technical Screening.
- Студенты не увидят ваш отзыв по интервью.
- После проведения всех интервью в вашей подгруппе, вы сообщаете студентам результат. Вы можете отложить окончательное решение на пару недель, и посмотреть, как будут выполняться первые задания второго этапа.   
- Если вы не берете студента дальше, вам необходимо указать какие у него были проблемы и над чем ему надо работать.

Внимание! Результаты должны быть сабмитнуты по всем интервью, иначе реджектнутые студенты не попадают в waitlist! 

## FAQ
#### Question: Что делать, если студент не вышел на связь?
Отчислить студента в RS APP > Expel/Unassign Student, указав “Не вышел на связь”. 

#### Question: Где можно добрать еще студентов?
Вариант #1. Если вы хотите взять себе еще одного студента для интервью:
- Открываете RS APP > Interviews > Available students
- Нажимаете "Want To Interview"

Вариант #2. Cпросить в телеграм канале вашего города - кто из студентов остался без ментора. [Список каналов](https://docs.rs.school/#/rs-school-chats?id=telegram). Далее действовать по варианту №1.

В обоих вариантах ментор сам связывается со студентом

#### Question: Как обменяться студентами с другим ментором?
После обоюдного согласия менторов, открываете RS APP > Interviews > Technical Screening и нажимаете "Transfer".

#### Question: Необходимо ли собеседовать знакомых/друзей/коллег, которых я менторю?
Да, необходимо. Можете попросить другого ментора вам помочь.
Фидбек оставить в RS APP > Interviews > Technical Screening

#### Question: Сколько времени обычно отводится на интервью? 
45-90 минут

