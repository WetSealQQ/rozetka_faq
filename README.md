
## МОДУЛЬ

- Заходим по ссылке (http://Ваш.домен/plugins)
- Активируем модуль!
	![](/img/module_on.jpg "active module")
- Заходим в модуль, вводим предложенные данные ( Аккаунт нужен с правами администратора )


---


## ДОБАВЛЕНИЕ ПРОДУКТА/РЕДАКТИРОВАНИЕ

![](/img/edit_product.jpg "edit product")

- ДЛЯ НАЧАЛА НУЖНО ДОБАВИТЬ ПРОИЗВОДИТЕЛЕЙ ЧТОБЫ ПОТОМ ИХ ВЫБИРАТЬ В КАРТОЧКЕ СОЗДАНИЯ ТОВАРА

- ТАКЖЕ НУЖНО БУДЕТ ДОБАВИТЬ ПРОДУКТ НА СКЛАД, ЕСЛИ КОЛ-ВО ПРОДУКТОВ БУДЕТ <= 0 В РОЗЕТКЕ ВАШ ТОВАР БУДЕТ ОТОБРАЖАТЬСЯ КАК НЕТ В НАЛИЧИИ

- #### При открытии окна добавления товара или при редактировании товара появляються 2 вкладки
	
	- ##### Вкладка НАСТРОЙКИ CRM:
		- Обязательные поля: Название, Производитель, Цена продажи
		- Если указали цена акционная в прайсе эта цена будет основной, а та что в поле Цена товара будет зачернутой
		- Описание товара - при переключении ползунка появлятеться возможность в описании товара писать html код
		- В прайс будет добавляться описание с html, если его нет - обычное описание

	- ##### Вкладка НАСТРОЙКИ РОЗЕТКИ:
		- Поля слева и название категории обязательные для заполнения
		- При выборе категрии из предложеного списка ( работает автозаполнение ) отображаются атрибуты
		- Все атрибуты заполнять не обязательно
		- Атрибуты можно добавлять свои НО!! НЕ РЕКОМЕНДУЕТСЯ! МОЖНО вписывать свои заначения в полях где нет выбора

	- ![](/img/attr_edit.jpg "edit attr")
		

---



## ПРАЙС

![](/img/price_list.jpg "price-list")
- Чтобы получить прайс-лист нужно хотя бы 1н продукт Добавить в прайс лист: **выделяем продукт-> жмем кнопку ROZETKA -> Добавить в прайс**

- При успешном создании прайс листа Вы получите ссылку на xml прайс, которую нужно отправить в розетку

- Для того что бы отключить продукт ( он будет присутствовать в прайс листе но не отображаться для покупателей ) заходим в карточку товара -> Настройки розетка -> отображать товар на розетке-> нет

- так же можно массово включать , отключать, добавлять, удалять продукты, **выделяя несколько продуктов -> жмем кнопку ROZETKA -> Выбираем нужное действие**



---

## ЗАКАЗЫ

- Заказы синхронизируются с розеткой каждые 5 минут

- ЧТОБЫ СТАТУСЫ МЕНЯЛИСЬ АВТОМАТИЧЕСКИ НУЖНО СОЗДАТЬ И ИСПОЛЬЗОВАТЬ ТАКИЕ ЖЕ КАК И В РОЗЕТКЕ!

- Основные статусы для работы с розеткой и их последовательность: 
	- Обрабатывается менеджером -> 
	- Данные подтверждены. Ожидает отправки -> 
	- Передан в службу доставки ( только при изменении на этот статус ттн добавиться )

- При изменении, кол-ва продуктов, добавления новых( новые должны быть добавлены в прайс! ) Данные синхронизируются с розеткой при сохранении заказа

- ИЗМЕНЯТЬ ПРОДУКТЫ МОЖНО ТОЛЬКО ПРИ СТАТУСЕ Обрабатывается менеджером
