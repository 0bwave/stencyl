В нашей игре уже есть несколько Типов Актеров, но они не особо интересные. Без Поведений, Типы Актеров вообще не могут ничего делать.

## Создание Группы “Враги”

Прежде чем мы прыгнем в настройку наших актеров, давайте быстро создадим **Группу**, в которую поместим врагов.

<div class="note">
**Определение:** **Groups** *(Группы)* используются, чтобы определить какие виды Типов Актеров сталкиваются друг с другом. Группы так же могут позволить вам рассматривать различные классы Типов Актеров по разному. Мы посвятили [отдельную статью](http://www.stencyl.com/help/view/collisions-and-groups/) Группам и тому, как они влияют на столкновения.
</div>

1) Нажмите на кнопку **Settings** *(Настройки)* на панели инструментов. Должно появиться окно **Game Settings** *(Настройки Игры)*. Здесь собраны почти все параметры настройки вашей игры.

![Game Settings](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-28.png)

2) Переключитесь на раздел **Groups** нажав соответствующую кнопку в боковой панели Settings.

![Collision Groups](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-29.png)

3) Нажмите зеленую кнопку **Create New** *(Создать Новую)* в верхней части окна.

![Create New](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-30.png)

4) Введите **Enemies** *(Враги)* в поле Name *(Имя)* и нажмите **Create** *(Создать)*.

![Create a New Group...](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-31.png)

5) Под **Collides With** *(Сталкивается С)*, нажмите на **Players** *(Игроки)* и **Tiles** *(Тайлы)*. Кнопки, которые вы нажали, должны стать зелеными. Это значит, что Враги будут сталкиваться с Игроками и Тайлами.

![Collides With](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-32.png)

6) Нажмите внизу-справа кнопку **OK** чтобы закрыть окно.

![OK](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-33.png)

## Настройка Нони

Чтобы вдохнуть немного жизни в основного персонажа (Нони) и его врага (Клоун), давайте более подробно рассмотрим Редактор Типа Актера и добавим Поведения включенные в Crash Course Kit.

Если вы еще не закрыли Тип Актера **Noni**, нажмите по его вкладке. Иначе, перейдите в Dashboard и дважды нажмите на Noni из раздела Actor Types в Dashboard.

![Actor Types](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-7.png)

1) По умолчанию появиться страница Appearance *(Внешний Вид)* Редактора Актера. Перейдите на страницу **Properties** *(Свойства)*, нажав на его кнопку вверху редактора.

![Properties](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-17.png)

2) Проверьте, что Нони состоит в Группу **Players** *(Игроки)*. Это обеспечит то, что Stencyl будет обрабатывать столкновения так, как мы задумали.

![Choose Group](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-18.png)

3) Зайдите на страницу **Physics** *(Физика)*, нажав кнопку **Physics** вверху редактора.

![Physics Button](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-19.png)

4) Под **General** *(Общее)*, переключите настройку **Can Rotate?** *(Может Вращаться?)* на **"No"** *(Нет)*. Это гарантирует, что актер всегда будет обращен ногами к земле и никак иначе.

![Can Rotate?](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-20.png)

5) Теперь давайте перейдем к разделу **Behaviors** *(Поведения)*, где начнутся реально трудные настройки. Для этого нажмите кнопку **Behaviors** (следующая справа от кнопки Appearance). Должен появиться следующий экран:

![Behaviors](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-21.png)

6) Нажмите на кнопу **Add Behavior** *(Добавить Поведение)* в левом-нижнем углу.

7) Когда появиться диалоговое окно, дважды нажмите на **Walking Behavior** *(Поведение Ходьбы)*.

![Choose a Behavior](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-22.png)

8) Мы вернемся на страницу Behaviors Нони. Заметьте, что в списке справа добавилось Поведение Walking, а также все его настраиваемые **Attributes** *(Атрибуты)* в основной области.

<div class="note">
**Определение:** **Атрибуты** - это настраиваемые значения, которые делают возможным повторное использование и легкое изменение Поведений. Чтобы больше узнать о Атрибутах, посмотрите нашу [вводную статью](http://www.stencyl.com/help/view/attributes/) о них.
</div>

![Walking](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-23.png)

9) Давайте начнем настраивать эти **Атрибуты**. Некоторые Атрибуты имеют значения по умолчанию, которые мы сможем использовать (например Speed *(Скорость)*), а другие нам нужно будет настроить самим.

Сначала, настройте **Move Right Key** *(Клавиша Движения Вправо)* и **Move Left Key** *(Клавиша Движения Влево)* на Контроллеры _**right**_ и _**left**_ соответственно.

![Control Attributes](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-24.png)

<div class="note">
**Определение:** **Controls** *(Контроллеры)* карта физических клавиш клавиатуры или кнопок геймпада, привязанных к именам, к которым вы можете обращаться в ваших поведениях. Если вы решите изменить текущую клавишу, вы сможете сделать это в одном месте. Посмотрите нашу статью о Контроллерах для получения дополнительной информации.
</div>

10) Теперь выберите желаемые анимации, нажав на кнопку **Choose an Animation** *(Выбрать Анимацию)* и выбрав последовательности анимаций,  которые вы хотите.

![Animation Attributes](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-25.png)

Это для первого Поведения!

11) Давайте таким же способом добавим и настроим остальные. Чтобы добавить больше Поведений, нажмите кнопку **Add Behavior** в левом-нижнем углу редактора.

![Add Behavior](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-26.png)

**Добавьте и настройте следующие Поведения: **

* **Jumping** *(Прыжки)* : Сделайте следующие изменения стандартных значений: Выберите _**action1**_ для **Jump Key**. Добавьте **Jump Sound** *(Звук Прыжка)*, таким образом Stencyl будет воспроизводить звуковой эффект, когда Нони будет прыгать. В конце, выберите _**Jump Right**_ и _**Jump Left**_ для анимаций **Jump Right** и **Jump Left**, соответственно.

 ![Jumping](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-27.png)

* **Stomp on Enemies** *(Раздавить Врагов)* : Установите **Stompable Group** на _**Enemies**_ (мы создали эту группу в начале этой части) и **Jump Key** на _**action1**_.

  <div class="note">  
  **Примечание:** Возможно вам придется перезагрузить документ для того, чтобы группа Enemies появилась в качестве опции. Сделайте это с помощью горячих клавиш Ctrl-R (Command-R на Mac), или нажмите File > Reload Document.
  </div>

 ![Stomp on Enemies](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-34.png)

* **Die in Pit and Reload** *(Смерть в Яме и Перезагрузка)* : Здесь нечего настраивать. Просто убедитесь, что добавили его.

Вот все Поведения, которые вы должны были добавить к Нони:

![All Behaviors for Noni](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-59.png)

## Настройка Клоуна

Настроить **Клоуна** будет проще, чем Нони. Переключитесь на его вкладку (или откройте ее из Dashboard, если это необходимо).

![Actor Types](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-10.png)

1) Нажмите на кнопку **Properties**, как мы делали с Нони.

2) Дальше измените группу Клоуна на **Enemies**.

![Choose Group: Enemies](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-35.png)

3) Все, что нам осталось сделать с Клоуном, это добавить одно Поведение. Нажмите кнопку **Behaviors** и добавьте Поведение **Stompable**. Настройте следующие Атрибуты также, как здесь:

![Stompable Behavior](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-36.png)

<div class="note">
**Примечание:** Можно сказать, что это Поведение делает Клоуна похожим на Гумбу из Super Mario Bros. Клоун "умрет" и воспроизведет соответствующий звук, когда на него упадут сверху. Если вы нажмете кнопку Edit Behavior *(Изменить Поведение)*, вы сможете увидеть "код" стоящий за этим Поведением.
</div>
