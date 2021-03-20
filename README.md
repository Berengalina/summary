# План автоматизации 
## 1. Перечень автоматизируемых сценариев 

### 1.1 Отправка анкеты через меню "Частным лицам" вариант 1 - успешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Анна Иванова"
- мобильный телефон +79850739905
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные успешно отправлены на сервер
Выполнен переход на страницу с текстом "Спасибо, скоро мы вам перезвоним!"

### 1.2 Отправка анкеты через меню "Частным лицам" вариант 2 - успешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" в разделе "Как открыть счет и услугу Копилка для сдачи?"  нажать "Заполнить заявку" 
В открывшейся форме заполнить: 
- имя и фамилию кириллицей, например "Алексей Смирнов"
- мобильный телефон +79850739906
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные успешно отправлены на сервер
Выполнен переход на страницу с текстом "Спасибо, скоро мы вам перезвоним!"

### 1.3 Отправка анкеты через меню "Вклады" - успешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать раздел "Вклады"
На открывшейся странице "Вклады" перейти в раздел "Накопительные счета"
В разделе "Накопительные счета" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Ирина Петрова"
- мобильный телефон +79850739907
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные успешно отправлены на сервер
Выполнен переход на страницу с текстом "Спасибо, скоро мы вам перезвоним!"


### 1.4 Ввод невалидного имени вариант 1 - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя кириллицей, например "Анна"
- мобильный телефон +79850709905
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные не отправлены на сервер.
На странице ввода данных под окном ввода имени появилось сообщение "Введите имя и фамилию русскими буквами"

### 1.5 Ввод невалидного имени вариант 2 - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию латиницей, например "Anna Belousova"
- мобильный телефон +79850739560
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные не отправлены на сервер.
На странице ввода данных под окном ввода имени появилось сообщение "Введите имя и фамилию русскими буквами"

### 1.6 Ввод невалидного имени вариант 3 - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- оставить пустым поле "Имя"
- мобильный телефон +79850739098
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные не отправлены на сервер.
На странице ввода данных под окном ввода имени появилось сообщение "Введите имя и фамилию русскими буквами"

### 1.7 Ввод невалидного номера телефона вариант 1 - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Анна Белоусова"
- мобильный телефон 798507
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**:  Данные не отправлены на сервер.
На странице ввода данных под окном ввода мобильного телефона появилось сообщение "Введите номер телефона в формате +7-xxx-xxxxxxx"


### 1.8 Ввод невалидного номера телефона вариант 2 - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Анна Белоусова"
- оставить пустым поле мобильный телефон
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные не отправлены на сервер.
На странице ввода данных под окном ввода мобильного телефона появилось сообщение "Введите номер телефона в формате +7-xxx-xxxxxxx"


### 1.9 Отсутствие чек-бокса согласия - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Анна Белоусова"
- мобильный телефон +79850739905
- не нажимать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные не отправлены на сервер.
На странице ввода данных под окном чек-бокса появилось сообщение "Необходимо согласие на обработку персональных данных"


### 1.10 Повторный ввод данных при отправке анкеты  - неуспешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей, например "Елена Крылова"
- мобильный телефон +79850009905
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"
Вернуться на страницу "Накопилки", под описанием условий повторно нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- те же имя и фамилию "Елена Крылова"
- тот же мобильный телефон +79850009905
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные отправлены на сервер
Выполнен переход на страницу с текстом "Заявка с персональными данными уже в рассмотрении"


### 1.11 Ввод валидного имени со спецсимволами при отправке анкеты - успешная операция
**Шаги**
Открыть главную страницу Альфа-банка https://alfabank.ru/
На открывшемся по умолчанию разделе "Частные лица" выбрать опцию "Накопилка"
На открывшейся странице "Накопилки" под описанием условий нажать "Заполнить заявку" 
В открывшейся форме заполнить:
- имя и фамилию кириллицей с дефисом, буквами "ё" и "й", например "Подъёмова Майя-Мария"
- мобильный телефон +79266845100
- нажать чек-бокс "Я согласен(а) на обработку персональных данных"

После заполнения данных нажать "Мы перезвоним"

**Ожидаемый результат**: Данные успешно отправлены на сервер
Выполнен переход на страницу с текстом "Спасибо, скоро мы вам перезвоним!"


## 2. Перечень используемых инструментов с обоснованием выбора

**Java 11**
Преимущества:
* кросс-платформенная совместимость (независимость от ОС)
* поддержка ООП
* безопасность и производительность

**JUnit 5**
Преимущества:
* независимость тестов от основного кода
* большой выбор аннотаций для удобства написания и запуска автотестов
* возможность создавать параметризованные тесты

**библиотека Faker**
Преимущества:
* возможность генерации случайных данных с заданными параметрами

**Selenide**
Преимущества:
* простая конфигурация
* лаконичный синтаксис, по сравнению с selenuim
* автоматическое управление браузером

**REST-assured**
Преимущества:
* удобный синтаксис для проведения проверки каждой составляющей HTTP-ответа
* использование спецификаций для избежания дублирования кода

**Allure**
Преимущества:
* легкость настройки и подключения
* прозрачность информации - понятно, насколько автотесты соответствуют ручным тестам, какие именно проверки покрыты автотестами
* наглядные отчеты со скриншотами выполняемых действий


## 3. Перечень необходимых разрешений/данных/доступов от банка
Для тестирования необходимы разрешения на вставку большого объема тестовых данных в БД (ФИО + телефон для регистрации заявок на открытия вклада). Возможно следует развернуть тестовую БД, куда буду уходить все запросы при тестировании.


## 4. Перечень и описание возможных рисков при автоматизации
- неполное описание функциональности (отсутствует скриншот страницы вкладов, на которой было бы видно, как можно перейти на "Накопилку") создает риск создания некорректных тестов, возможно потребуется дополнительная отладка после запуска.
- отсутствие доступа к БД не позволит дополнительно проверить корректность записи полученных данных с веб-сайта
- в требованиях отсутствует перечисление браузеров и их версий, в которых необходимо выполнить проверку, выбор браузеров остается за командой тестирования
- в требованиях отсутствует указание на максимальную производительность - число одновременных попыток отправки заявок, которую выдержит сайт. Необходимо запланировать нагрузочное тестирование
- инфраструктурные проблемы - недоступность веб-сайта, проблемы с тестовой БД, другие форс-мажорные обстоятельства из-за которых возможны простои (энергосеть, провайдер, железо)


## 5. Перечень необходимых специалистов для автоматизации
- специалист по созданию тестовой модели и анализу требований
- специалист по созданию и отладке автотестов 
- специалист по запуску автотестов и составлению отчетов

## 6. Интервальная оценка с учётом рисков (в часах)
без рисков: 21 час
- 4 часа на анализ
- 12 часов на создание и отладку тестов
- 3 часа на настройку инфраструктуры 
- 2 часа на отчетность

с рисками: 33 часа
- 6 часов на анализ
- 18 часов на создание и отладку тестов
- 6 часа на настройку инфраструктуры 
- 3 часа на отчетность
