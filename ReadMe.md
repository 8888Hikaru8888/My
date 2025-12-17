# MyCarWashing

## ТЗ
  _Мобильное (Андроид, Айфон) приложение для клиентов сети автомоек. + WEB для директора, бухгалтера, кассира, мойщика._
  
## Требования
+ Пользователи:
   1. Директор
   2. Бухгалтер
   3. Клиент
   4. Оператор (касса)
   5. Мойщик
- Для Клиентов:
  - Регистрация (Авторизация):
      - Номер
      - Логин
      - Пароль
      - Модель тс
  - Выбор точки на карте.
  - Выбор бокса, времени, услуги.
  - Оплата (Способ оплаты).
  - Возможность отмены услуги и возврата платежа за 30 минут до назначенной услуги.
  - Обратная связь по качеству услуги.\
  **_Дополнительно:_**
  - Оповещения.
  - Загруженность мойки.
- Для Директора:
  - Авторизация.
  - Возможность выбора точки.
  - Рейтинг посещаемости, окупаемости точек + Рейтинг/анти-рейтинг клиентов (кол-во отменённых услуг, негативные отзывы).
  - Статистика по работе мойщиков.
  - Просмотр и редактирование списка VIP-клиентов.
  - Просмотр доступных тарифов и акций.
  - Просмотр загруженности боксов + прогноз.
- Для бухгалтера:
  - Авторизация.
  - Возможность выбора точки на карте.
  - Рейтинг окупаемости точек.
  - Просмотр и редактирование списка VIP-клиентов.
  - Просмотр и редактирование доступных тарифов и акций.
- Для оператора:
  - Авторизация.
  - Список всех предоплат с возможностью выбора актуальных (на сегодняшний день или тех, где услуга ещё не выполнена).
  - Поиск по номеру предоплаты (на текущий день) и/или по номеру/логину клиента.
  - _Всё то же, что было без приложения (Возможность оплаты и назначения специально выделенного "оффлайн" бокса и услуги)._
- Для мойщика:
  - Табло с номером предоплаты, статуса оплаты и услугой.

## Расчёты
### Точки:
 - Корсаков (5 боксов)
 - Долинск (7 боксов)
 - ЮС (10 боксов)

```
Рабочий день: 12 часов.
Среднее время обслуживания тс: 12.5 минут.
Среднее количество машин на один бокс в течение дня: 12 * 60 / 12.5 ~ 58 машин/бокс.
```
### Итоги:
```
Максимальное количество машин: 580 (10 боксов * 58) машин/день.
```

## Ссылки:

| Артефакт | Файлы |  
|----------|-------|  
| Sequance_Diagram | [**Sequance_Diagram**](./SequanceDiagram/Sequance_Diagram) <br> ![**Sequance_Diagram**](https://github.com/8888Hikaru8888/My/blob/main/SequanceDiagram/Sequance_Diagram.png) |  
### OpenAPI
-[**OpenAPI**](./OpenAPI/api-docs.yaml)-OpenAPI спецификация  
 **OpenAPI спецификация**  [`Open API`](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/8888Hikaru8888/My/refs/heads/main/OpenAPI/api-docs.yaml) 
### Sequance_Diagram
|-------------|-------------|  
| [**Sequance_Diagram**](./SequanceDiagram/Sequance_Diagram) <br> ![**Sequance_Diagram**](https://github.com/8888Hikaru8888/My/blob/main/SequanceDiagram/Sequance_Diagram.png) |  
### ERD
|-------------|-------------|
| [**ERD**](./ERDCat/ERD)-ERD спецификация <br> ![**ERD**](https://github.com/8888Hikaru8888/My/blob/main/ERDCat/ERD2.png) |
### StatusModel
-[**StatusModel**](./StatusModel/Status_Model.uml)  
![**StatusModel**](https://github.com/8888Hikaru8888/My/blob/main/StatusModel/Status_Model.png)  
### StoryMapping
![**StoryMapping**](https://github.com/8888Hikaru8888/My/blob/main/StoryMapping/User%20Story%20Mapping1.png)
### Use_Case
-[**Use_Case(ТЗ)**](./UseCase/Use_Case(ТЗ).md)  
-[**Use_Case**](./UseCase/UseCasePlantUml)  
![**Use_Case**](https://github.com/8888Hikaru8888/My/blob/main/UseCase/UseCaseR.png) 
### UserStories_Director
-[**UserStories_Director**](./UserStory/UserStories_Director.md)   
### UС4Model CarWash
![**С4Model CarWash**](https://github.com/8888Hikaru8888/My/blob/main/%D0%A14Model%20CarWash.png)  
-[**Directors`s demands**](https://github.com/8888Hikaru8888/My/blob/main/Directors%60s%20demands.md)  
































