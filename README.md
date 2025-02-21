# $\color{lightgray}\textsf{Kropp Fitness}$

$\color{limegreen}\text{Учебная работа}$

## $\color{mediumblue}\text{Описание работы }$:

Внешняя страницы тренажёрного залла.

Работа на основе видеоуроков .

**Цели и задачи работы :**

❗Отслеживание потерь производительности ( _проверка на [PageSpeed Insights](https://pagespeed.web.dev/)_) .

❗Знакомство с ранее не используемыми способами стилизации и формирования HTML-структуры элементов страницы.

🎯 <span style="color:mediumblue">Основная задача</span> - Практика и улучшение навыков вёрстки .

---

Макет -> [**Figma**](<https://www.figma.com/design/m3lT3GF4mUgEBaU3qysyeu/10%2B-Free-Web-UI-designs-(Community)?node-id=0-1&p=f&t=mcusH9lsNWI7Jc1D-0>)

Вёрстка -> [**Git pages**](https://artiom-work.github.io/kropp-crossfit/)

<img src="images/website/preview-readme-image.jpg" width="400" alt="Изображение макета страницы">

---

## $\color{mediumblue}\text{Технологии, инструменты и способы вёрстки }$:

✅ SASS
✅ Flex
✅ Grid
✅ Адаптивная вёрстка
✅ Git
✅ Figma

---

## $\color{mediumblue}\text{Поблочные изменения производительности}$:

1.  Adding a header

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

2.  Adding a section banner ( not slider )

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

3.  Adding a section motivation

        	Performance:
        	Mobile version - 88%
        	Computer version - 100%

        Convert images to webp format and compression

            Performance:
        	Mobile version - 100%
        	Computer version - 100%

4.  Adding a section training-types

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

5.  Adding a section join-us

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

6.  Adding a section location

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

7.  Adding a section family

        	Performance:
        	Mobile version - 100%
        	Computer version - 100%

8.  Adding a section calculate

        	Performance:
        	Mobile version - 98%
        	Computer version - 100%

    _Using tables slows down page loading_

## $\color{mediumblue}\text{Новые (для меня) способы вёрстки:}$

💡Переработанный файл обнуления стилей: [Normalize.css](https://raw.githubusercontent.com/aleksanderlamkov/css-normalize/main/index.css)

💡CSS-свойство **scrollbar-gutter** для стабилизации скролла на странице ( _исправляет баг с модальными окнами_)

💡Зачем **атрибут title** у элементов **button**

💡Свойство **aspect-ratio** ( _для элементов с одинаковой высотой и шириной_ )

💡Способ **визуального сокрытия** ( _для элементов button_ )

💡Правильная **компоновка заголовков** , и их сокрытие (_если нужно_) .

💡Зачем **элементам button обязательно** нужно задавать **атрибут type**

💡Как перевести размер из **px в vw** при адаптиве. И функции** clamp и min** (_как ими пользоваться_) .

💡**data-атрибут** для псевдоэлемента

💡Использование CSS-функции **clamp()** для **gap**

💡CSS-cвойство **margin-block** для позиционирования

💡Способ **центрирования** нестандартно позиционируемых элементов свойствами **position и translate**

💡Нестандартный способ изменение цвета фонового SVG-изобажения . Свойством **filter**

💡Создание **"placeholder"** для элемента **select**. Только HTML и CSS

💡Свойство **padding-block** для отступов у блока только сверху и снизу

💡Псевдокласс **:is**

💡Как **закрашивать inline SVG** на всей странице, пользуясь наследованием цвета
