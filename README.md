# Группа пользователей языка R   
<!---
**[Russian Speaking R Language Group]**  
<p align="center">
<img src = "./R_logo.png" width=270> 
</p>
--->
_Тематика группы - [язык R](https://www.r-project.org), статистика и статистический анализ данных, машинное обучение и data mining._   

- Адрес группы в Telegram: https://t.me/rlang_ru
- Подгруппа для вакансий: https://t.me/rlang_ru_jobs

## Ссылки на важные подсекции  

- [Как задать хороший вопрос](https://github.com/r-lang-group-ru/group-rules/blob/master/README.md#how-to-ask-a-good-question) 
- [Как прислать код](https://github.com/r-lang-group-ru/group-rules/blob/master/README.md#code-sharing) 

## В группе нельзя

- рассылать спам и рекламу, флудить (нетематические сообщения в большом количестве) -- такие действия приводят к бану
- просить помощь за деньги -- такие сообщения удаляются
- публикация вакансий -- по согласованию с админами
    - Подгруппа, куда можно постить вакансии без согласования с админами (вакансия будет рассмотрена после публикации): https://t.me/rlang_ru_jobs

## How to ask a good question

**[Как задать хороший вопрос]**  

Вопросы можно задавать в свободной форме, но чтобы увеличить шансы получения ответа 

1. Не задавайте вопросы, ответ на которые легко находится в первых строчках результатов поиска по ключевым словам в Интернете. Если не получается найти, то попробуйте задать вопрос по-английски: большинство поисковиков исправят или проигнорируют ошибки в языке. Кроме того, имеет смысл поискать в самом чате -- есть вероятность, что Вы не первый, у кого возникла такая проблема. Если беглый поиск не помогает и не получается ничего легко найти в течение нескольких минут -- то спрашивайте в чате!)

1. Внимательно читайте текст ошибки. Например, если у Вас не встает пакет и ошибка выглядит как `Error in install.packages : path[1]=...` посмотрите, что еще произошло во время установки. Очень часто R сообщает что пошло не так, и эти ошибки можно и нужно искать в Интернете.

1. Вопрос нужно сформулировать кратко и ясно, включив в него всю необходимую информацию, чтобы идентифицировать проблему и решить ее. Если вопрос будет нечеткий/неясный, то Вам скорее всего либо ничего не ответят, либо членам группы придется задавать вам дополнительные наводящие вопросы -- на что не всегда есть время. Вот примеры плохих вопросов: 

    - *Пакет my_package почему-то не ставится, что делать?* В этом вопрос ничего нет про ошибки, которые произошли во время установки, так что членам группы придется задавать дополнительные вопросы.
    - *Пакет `my_package` почему-то не ставится, выдает ошибку `Warning: cannot remove prior installation of package ‘my_package’`. Никто не сталкивался? У меня линукс и R версии 3.6.1...* Этот вопрос значительно лучше сформулирован, и даже оформлен код (это не обязательно), но он все равно плохой, так как ответ на него содержится [в первой же строке поисковика](https://stackoverflow.com/questions/19407092/r-not-finding-package-even-after-package-installation).

1. Вопрос не должен предполагать наличие "телепатических" способностей у участников чата. Расскажите как воспроизвести проблему. Мы ставим хэштег #wizard в ответ на такие вопросы, так что можно поискать примеры по чату.

1. Если присылаете код или данные, то тоже важно сделать это правильно -- [см. следующую секцию](#code-sharing)


## Code sharing  

**[Как прислать код]**  

1. Пример кода должен быть:
    
    - **минимальным** — максимально сократите код, сохранив все проблемные моменты;
    - **самодостаточным** — приведите все части кода, необходимые для воспроизведения проблемы;
    - **воспроизводимым** — проверьте, что используя приведенный пример кода, другие участники смогут воспроизвести проблему.

1. **НЕ** присылайте скрины кода. Их сложно читать и невозможно скопировать текст для быстрого воспроизведения проблемы.

1. Минимальный пример _данных_ присылайте в тех случаях, когда проблема возникает при обработке определённых структур/типов данных. Обычно достаточно 10-20 примеров или несколько аномальных примеров, на которых воспроизводится проблема.

1. Указывайте ОС, версию R и используемых пакетов. Поведение R в разных ОС может различаться при работе со строками не в UTF-8 кодировке или в кириллице в Windows. Поведение функций в пакетах также может различаться от версии к версии.

1. Если код небольшой, то код можно присылать прямо в чат простым текстом, либо используя теги ``.  Если код больше 8-10 строк или есть строки с длиной больше 60 символов, то желательно воспользоваться сервисами / R-пакетами для расшаривания кода:

    - https://gist.github.com/
    - https://pastebin.com
    - R-пакеты
        - [Tools to work with the pastebin API in R](https://github.com/hrbrmstr/pastebin) 
        - [Work with 'GitHub' 'gists' from 'R'](https://cran.r-project.org/web/packages/gistr/index.html)


## Ресурсы 

- ["Классификация, регрессия и другие алгоритмы Data Mining с использованием R"](https://ranalytics.github.io/data-mining/index.html), Шитиков В. К., Мастицкий С. Э.
- [Coursera: Просто о статистике (с использованием R)](https://www.coursera.org/specializations/prosto-o-statistike)
- [Coursera: Линейная регрессия](https://www.coursera.org/learn/lineynaya-regressiya/)
