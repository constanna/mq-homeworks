# Новостные карточки

## Описание
Во внутренней системе управления крупного СМИ есть страница с карточками свежих новостей из разных источников. Раньше с этой системой можно было работать только с компьютера или ноутбука. Но недавно всем журналистам были выданы служебные планшеты и телефоны, чтобы они могли следить за трендами находясь «в поле».

Вам была поставлена задача изменить верстку страницы таким образом, чтобы контейнер, в котором находятся карточки, и сами карточки тянулись в зависимости от того, на каком устройстве открывается страница. Пропорции страницы при этом должны сохраниться.

Также важно, чтобы внутренние и внешние отступы карточки, как и обводка тоже оставались неизменными. Это личная просьба дизайнера.

## Процесс реализации
Измените размеры блоков `.container` и `.card` таким образом, чтобы они подстраивались под разрешение экрана, на котором открыты. `.container` должен занимать в процентах то же пространство, которое приходится на `960px` на экране с разрешением `1280px`.

Карточки должны стоять по две в рад. Внутренние отступы должны быть равны `15px`. Обводка должна быть шириной в `1px`. Внешние отступы должны быть равны `15px` сниху и `10px` по бокам.

## Реализация
В ходе решения этой задачи не изменяйте HTML-разметку.

### Локально с использованием git

Внесите изменения в файл ./css/news.css. Файл уже подключен к документу, поэтому другие файлы изменять не требуется.

### В песочнице CodePen

Внесите изменения во вкладке CSS. Перед началом работы сделайте форк пена на [CODEPEN](https://codepen.io/solarrust/pen/QMwpxx?editors=1100)