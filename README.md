
## МОДУЛЬ


- Активируем модуль!
	![](/img/module_on.jpg "active module")
- вводим предложенные данные ( Аккаунт нужен с правами администратора )






## Создание продукта\редактирование


- ДЛЯ НАЧАЛА НУЖНО ДОБАВИТЬ ПРОИЗВОДИТЕЛЕЙ ЧТОБЫ ПОТОМ ИХ ВЫБИРАТЬ В КАРТОЧКЕ СОЗДАНИЯ ТОВАРА
ТАКЖЕ НУЖНО БУДЕТ ДОБАВИТЬ ПРОДУКТ НА СКЛАД, ЕСЛИ КОЛ-ВО ПРОДУКТОВ БУДЕТ <= 0 В РОЗЕТКЕ ВАШ ТОВАР БУДЕТ ОТОБРАЖАТЬСЯ КАК НЕТ В НАЛИЧИИ

#### Вкладка НАСТРОЙКИ CRM:
В название товара обязательно вписать производителя (требование розетки)
обязательные поля: Название, Производитель, Цена продажи
Если указали цена акционная в прайсе эта цена будет основной, а та что в поле Цена товара будет зачернутой
Описание товара ( пока что можно писать только текст без тегов!! )

#### Вкладка НАСТРОЙКИ РОЗЕТКИ:
Поля с лева Обязательные для заполнения + название категории
сами атрибуты не обязательны
атрибуты можно добавлять свои НО!! НЕ РЕКОМЕНДУЕТСЯ! МОЖНО вписывать свои заначения в полях где нет выбора





## ПРАЙС

- что бы получить прайс лист нужно хотя бы 1н продукт Добавить в прайс лист
- Для того что бы отключить продукт ( он будет присутствовать в прайс листе но не отображаться для покупателей ) заходим в карточку товара -> Настройки розетка -> отображать товар на розетке-> нет
- так же можно массово включать , отключать, добавлять, удалять продукты




## Заказы

- Заказы синхронизируются с розеткой каждые 5 минут
- ЧТОБЫ СТАТУСЫ МЕНЯЛИСЬ АВТОМАТИЧЕСКИ НУЖНО СОЗДАТЬ И ИСПОЛЬЗОВАТЬ ТАКИЕ ЖЕ КАК И В РОЗЕТКЕ!
- При изменении, кол-ва продуктов, добавления новых( новые должны быть добавлены в прайс! ) Данные синхронизируются с розеткой при сохранении заказа
- ИЗМЕНЯТЬ ПРОДУКТЫ МОЖНО ТОЛЬКО ПРИ СТАТУСЕ Обрабатывается менеджером
- Основные статусы для работы с розеткой и их последовательность: 
	- Обрабатывается менеджером -> 
	- Данные подтверждены. Ожидает отправки -> 
	- Передан в службу доставки ( только при изменении на этот статус ттн добавиться )