TODO *Поменять ссылки, чтобы они вели на статьи **этого** сайта.*

Ранее в этой главе, [вы узнали об Атрибутах](docs/logic/attributes), которые являются изменяемыми и настраиваемыми свойствами Поведений. Какие Атрибуты есть в вашем распоряжении?

## Типы - Ссылки

Stencyl включает в себя следующие типы ресурсов.

Тип | Статья в Документации?
--- | ---
Actor *(Актер)* | [Да](docs/actors/actors)
Actor Group *(Группа Актера)* | [Да](docs/actors/collisions_groups)
Actor Type *(Тип Актера)* | [Да](docs/actors/actors)
Animation *(Анимация)* | [Да](docs/actors/animations)
Anything *(Что-то)* | ---
Boolean *(Логика)* | ---
Color *(Цвет)* | ---
Control *(Контроллер)* | [Да](docs/actors/controls)
Font *(Шрифт)* | [Да](http://www.stencyl.com/help/view/font-editor/) FIXME
Image *(Изображение)* | [Да](http://www.stencyl.com/help/view/image-api) FIXME
Image Instance *(Экземпляр Изображения)* | [Да](http://www.stencyl.com/help/view/image-api) FIXME
List *(Список)* | [Да](http://www.stencyl.com/help/view/lists/) FIXME
Joint *(Соединение)* | ---
Map *(Карта)* | [Да](http://www.stencyl.com/help/view/maps/) FIXME
Number *(Число)* | ---
Region *(Регион)* | [Да](http://www.stencyl.com/help/view/regions/) FIXME
Scene *(Сцена)* | [Да](http://www.stencyl.com/help/view/scene-basics/) FIXME
Shader *(Шэйдер)* | [Да](http://www.stencyl.com/help/view/shaders/) FIXME
Sound *(Звук)* | [Да](http://www.stencyl.com/help/view/playing-sounds-and-music/) FIXME
Text *(Текст)* | ---

## Как Выглядят Настройки Атрибутов?

Вот некоторые примеры основных Типов Атрибутов и как они могли бы появиться на странице Behaviors *(Поведения)* Типа Актера.

Тип Атрибута | Отображение в Редакторе Типа Актера > Поведения
--- | ---
Actor Group *(Группа Актера)* | ![stencyl-design-mode-actor-group-attribute](http://static.stencyl.com/pedia2/ch2/types/image00.png)
Actor Type *(Тип Актера)* | ![stencyl-design-mode-actor-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image03.png)
Animation *(Анимация)* | ![stencyl-design-mode-animation-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image01.png)
Boolean *(Логика)* | ![stencyl-design-mode-boolean-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image04.png)
Color *(Цвет)* | ![stencyl-design-mode-color-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image07.png)
Control *(Контроллер)* | ![stencyl-design-mode-control-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image11.png)
Font *(Шрифт)* | ![stencyl-design-mode-font-type-attribute](http://static.stencyl.com/help/images/Font-Attribute-Pic.png)
Number *(Число)* | ![stencyl-design-mode-number-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image05.png)
Scene *(Сцена)* | ![stencyl-design-mode-scene-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image02.png)
Sound *(Звук)* | ![stencyl-design-mode-sound-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image10.png)
Text *(Текст)* | ![stencyl-design-mode-text-type-attribute](http://static.stencyl.com/pedia2/ch2/types/image06.png)

## Глюки

Возможно вы столкнетесь с этим довольно быстро.

![Cannot configure](http://static.stencyl.com/pedia2/ch4/customize/image05.png)

*Это поле доступно только для Актеров, размещенных в сцене.*

Почему некоторые атрибуты не настраиваемые?

* Нечего настраивать или настройки имеют ограниченные значения. (например Экземпляр Изображения, Шейдер)
* Это поведение Актера, пока Актер не находится внутри сцены, нет контекста, чтобы выбрать определенного Актера или Регион.

В последнем случаи, это можно решить путем [настройки Актера](http://www.stencyl.com/help/viewArticle/117/) FIXME , как только он окажется внутри сцены.
