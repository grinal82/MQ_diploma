# Дипломный проект курса «Адаптивная и мобильная верстка»
![GitHub last commit](https://img.shields.io/github/last-commit/Alnipet/mq-diploma)
![GitHub top language](https://img.shields.io/github/languages/top/Alnipet/mq-diploma)
![GitHub language](https://img.shields.io/github/languages/count/Alnipet/mq-diploma)

**Диплом должен быть реализован локально и опубликован на сервисе [GitHub Pages](https://pages.github.com/). 
Перед началом работы, пожалуйста, посмотрите видео-инструкцию по [ссылке](https://embed.new.video/cxEqtfQzkYST15TtikEAWF?sig=eyJhbGciOiJIUzI1NiJ9.eyJ1c2VyX2lwIjoiMTA5LjI1Mi40MS45OCIsInZpZGVvX3Rva2VuIjoiY3hFcXRmUXprWVNUMTVUdGlrRUFXRiJ9.fqxDLhpUA1gcTj6mnjqO0q9r5Wvqk8by1jdkCzz6FMY).**
Если при выборе ветки для публикации у вас нет ветки `master` в выпадающем списке, то выбирайте `main`. 

*В процессе реализации дипломного проекта, вам предстоит работать с локальными файлами и папками. Для того чтобы вам было легче разобраться как работают относительные пути, мы подготовили для вас [инструкцию](https://github.com/netology-code/guides/tree/master/relative-link).*

В рамках дипломного проекта вам необходимо сверстать макет сайта для трех групп устройств: десктопные экраны, планшеты и смартфоны.

Макеты сайта для различных экранов выглядят так:

![Layout](img/layouts.jpg)

Исходные файлы макетов хранятся в директории [sources](./sources/) репозитория:

- `NOEMI_mq_desktop.psd` – макет для экрана шириной 1200px и более,
- `NOEMI_mq_tablet.psd` – макет для экрана шириной 768px,
- `NOEMI_mq_mobile.psd` – макет для экрана шириной 360px.

О верстке промежуточных состояний подробнее читайте в разделе [Промежуточные состояния между макетами](#Промежуточные-состояния-между-макетами).

Также папка [sources](./sources/) содержит jpg-изображения – превью макетов для быстрого просмотра. **Не верстайте сайт с превью, используйте для верстки psd-макеты.**

В поддиректории [fonts](./sources/fonts/) вы можете найти использующиеся в макете шрифты, а в поддиректории [svg](./sources/svg/) — иконки в формате `svg`.
