## Тестовое задание «Автомобильный каталог»

Нужно развернуть Yii framework (первой версии), сверстать по приложенному макету простой сайт на Bootstrap или Foundation, создать схему БД, сгенерировать админку на стандартных CRUD'ах, наполнить БД тестовыми данными (марка, модель, комплектация, изображение, текстовое описание).

### Описание страниц:
 

_ «Главная» (/)_
 
Статичная страница с рандомным содежанием (lorem ipsum) [Макет](https://ibuycar.github.io/tests/static/tt_7.png)

_«О сайте» (/about)_

Статичная страница с рандомным содежанием (lorem ipsum) [Макет](https://ibuycar.github.io/tests/static/tt_8.png)

_«Каталог» (/catalog)_

Каталог состоит из нескольких шагов

1. Выбираем марку автомобиля в select [Макет](https://ibuycar.github.io/tests/static/tt_1.png)

2. После выбора марки на странице должен появиться второй select с моделями соответствующей марки [Макет](https://ibuycar.github.io/tests/static/tt_2.png)

3. Аналогичным образом подгружаются комплектации [Макет](https://ibuycar.github.io/tests/static/tt_3.png)

4. После выбора комплектации появляется кнопка перехода и по клику нас перекидывает на детальную страницу комплектации [Макет](https://ibuycar.github.io/tests/static/tt_4.png)

5. Детальная страница комплектации содержит изображение, назване и вывод текстового описания [Макет](https://ibuycar.github.io/tests/static/tt_5.png) 

Пример адреса страницы http://test.ru/catalog/audi/a3/1.4_ambition

Шаги 1-4 проходятся без перезагрузки страницы посредством AJAX.

### Примечания:

По цветовой гамме и оформлению макета нет ограничений, главное чтобы он выглядел хорошо.
Всячески приветствуется использование системы контроля версий, автоматизированных средств для разворачивания проекта, тестирования и сборки верстки.
Также приветствуется различные дополнения, такие как например реализация прямого доступа к промежуточным страницам выбора (например /catalog/audi/, /catalog/audi/a3/)

*Тестовый сайт должен быть размещен на хостинг-платформе и доступен для просмотра. При необходимости можем выделить доступ к тестовому серверу.*
