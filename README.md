## Тестовое задание «Автомобильный каталог»

Нужно развернуть Yii framework (первой версии), сверстать по приложенному макету простой адаптивный сайт на Bootstrap(обязательно использование сетки), создать схему БД(будет плюсом использование миграций), сгенерировать админку на стандартных CRUD'ах, наполнить БД тестовыми данными (марка, модель, комплектация, изображение, текстовое описание).

### Описание страниц:
 

__«Главная» (/)__
 
Статичная страница с рандомным содежанием (lorem ipsum) [Макет](https://ibuycar.github.io/tests/static/tt_7.png)

__«О сайте» (/about)__

Статичная страница с рандомным содежанием (lorem ipsum) [Макет](https://ibuycar.github.io/tests/static/tt_6.png)

__«Каталог» (/catalog)__

Каталог состоит из нескольких шагов

1. Выбираем марку автомобиля в select [Макет](https://ibuycar.github.io/tests/static/tt_1.png)

2. После выбора марки на странице должен появиться второй select с моделями соответствующей марки [Макет](https://ibuycar.github.io/tests/static/tt_2.png)

3. Аналогичным образом подгружаются комплектации [Макет](https://ibuycar.github.io/tests/static/tt_3.png)

4. После выбора комплектации появляется кнопка перехода и по клику нас перекидывает на детальную страницу комплектации [Макет](https://ibuycar.github.io/tests/static/tt_4.png)

5. Детальная страница комплектации содержит изображение, название и вывод текстового описания [Макет](https://ibuycar.github.io/tests/static/tt_5.png) 

Шаги 1-4 проходятся без перезагрузки страницы посредством AJAX.

Пример адреса страницы http://test.ru/catalog/audi/a3/1.4_ambition. 

### Примечания:

По цветовой гамме и оформлению макета нет ограничений, главное чтобы он выглядел хорошо.
Всячески приветствуется использование системы контроля версий, автоматизированных средств для разворачивания проекта, тестирования и сборки верстки.
Также приветствуется различные дополнения, такие как например реализация прямого доступа к промежуточным страницам выбора (например /catalog/audi/, /catalog/audi/a3/)

*Тестовый сайт должен быть размещен на хостинг-платформе и доступен для просмотра. При необходимости можем выделить доступ к тестовому серверу.*
