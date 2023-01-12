# Profile page Pinguine
Ссылка на пример на сайте [MDBootstrap](https://mdbootstrap.com/docs/standard/extended/profiles/)

>Верстка страницы выполнена с помощью фреймворка Bootstrap 5
### Структура страницы

>Страница состоит из навигационной панели и 5ти карточек.

* Навигационная панель `navbar`
* Карточка 1 name `card`
* Карточка 2 links `card`
* Карточка 3 about `card`
* Карточка 4 progress bar `card`
* Карточка 5 progress bar `card`

### Детали

1. `list-group` функция позволяят делать карточку с разными ссылками
```css
<ul class="list-group list-group-flush rounded-3">
    <li class="list-group-item d-flex justify-content-between align-items-center">
    <i class="bi bi-globe text-warning fs-3"></i>
    <p class="mb-0">https://mdbootstrap.com</p>
    </li>
```
2. `text-primary fs-3` данный клас воздействует на иконочный шрифт bootstrap

```css
<i class="bi bi-globe text-warning fs-3"></i>
```
3. Прогресс-бар  (индикатор выполнения задачи) имеет класс `progress`
```css
<div class="progress rounded" style="height: 5px;">
    <div class="progress-bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="80" style="width: 80%;"></div>
</div>
```


