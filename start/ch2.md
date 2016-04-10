Из **Dashboard**, мы можем создавать новые, импортировать внешние или открывать существующие. В Crash Course мы включили все необходимые для начала ресурсы. Давайте перейдем к ним.

![Dashboard](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-5.png)

## Актер Игрока

Мы начнем с нахождения **Actor Type** *(Типа Актера)*, который будет служить нам играбельным персонажем.

<div class="note">
**Определение:** В Stencyl что либо, что может перемещаться или взаимодействовать, считается **Actor** *(Актером)*. Это включает в себя игровых персонажей, врагов, элементы пользовательского интерфейса и т.д. **Actor Type** *(Тип Актера)* - это шаблон для Актеров, в то время как Актер обычно означает конкретный экземпляр. В сообществе, эти два термина часто используются, как взаимозаменяемые.
</div>

1. Сперва нажмите на надпись **Actor Types** *(Типы Актеров)*, расположенной под RESOURCES *(РЕСУРСЫ)* в боковой панели Dashboard.

  ![RESOURCES](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-6.png)

  <div class="note">
  **Примечание:** Вы можете увидеть небольшое число "2" рядом с кнопкой. Это число показывает общее количество актеров в вашей игре. Точно такие же числа, рядом с другими ресурсами, показывает количество имеющихся у вас других типов ресурсов.
  </div>

2. Теперь появится список всех Типов Актеров в вашей игре. Как и ожидалось, вы увидите здесь два Типа Актеров, первый называется Noni *(Нони)*, дурой - Clown *(Клоун)*. Нони будет управляемым игроком Типом Актера.

  ![Actor Types](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-7.png)

3. Если вы дважды нажмете на **иконку Нони**, Stencyl откроет его внутри **Actor Type Editor** *(Редактор Типа Актера)*.

  ![Noni](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-8.png)

  <div class="note">
  **Определение:** Редактор Типа Актера является одним из нескольких редакторов ресурсов включенных в Stencyl. Он позволит вам настроить внешний вид, поведение и физические свойства Актера.
  </div>

В ближайшее время мы вернемся к этому редактору, но сейчас давайте проверим остальные ресурсы, которые будем использовать.

## Актер Врага

1. Вернемся в **Dashboard** нажав на эту вкладку.

  ![Tabs](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-9.png)

2. Теперь откроем **Clown**, этот Тип Актера мы будем использовать в качестве врага.

  ![Clown](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-10.png)

  <div class="note">
  **Совет:** Предпочитаете открывать ресурсы с помощью клавиатуры? Нажмите Ctrl-O (или Command-O на Mac). Это вызовет диалоговое окно, в котором вы можете ввести имя любого ресурса. Используйте клавиши со стрелками, чтобы выбрать нужное и нажмите Enter/Return, чтобы подтвердить свой выбор.
  </div>

## Tilesets *(Тайлсет)*

Теперь взглянем на наш Тайлсет.

<div class="note">
**Определение:** Тайлсет - это набор прямоугольных изображений (тайлов), которые могут быть использованы для создания игровых уровней (в Stencyl известны, как сцены).
</div>

1. Вернитесь обратно на **Вкладку Dashboard** и нажмите на категорию **Tilesets**.

  ![Tilesets](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-11.png)

2. Откройте **Grass Land Tileset**.

3. Как и следовало ожидать,  в новой вкладке открылся редактор. На этот раз, это **Tileset Editor** *(Редактор Тайлсета)*.

  ![Tileset Editor](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-12.png)

## Sounds *(Звуки)*

Дальше, давайте посмотрим на наши **Звуки**. Нажмите кнопку Sounds в Dashboard. Вы увидите, что у нас уже есть два Звука: Stomp и Jump.

![Sounds](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-13.png)

Не стесняйтесь открыть один из них, что бы проверить в **Sound Editor** *(Редактор Звука)*.

## Behaviors *(Поведения)*

Теперь, давайте посмотрим на ниши **Поведения**, а конкретно на **Actor Behaviors** *(Поведения Актеров)*, расположенные в Dashboard под LOGIC *(ЛОГИКА)*.

Ниже приведены пять поведений, которые мы будем использовать в этом курсе:

![Behaviors](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-14.png)

<div class="note">
**Примечание:** Поведения контролируют всю игровую логику и взаимодействия игрока; они делают это каждый игровой "тик".
</div>

Давайте быстро взглянем на одно из этих поведений. Дважды нажмите на **Walking** *(Ходьба)*, чтобы открыть его. Он откроется внутри **Design Mode** *(Режим Конструктора)*.

![Design Mode](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-15.png)

Здесь происходит очень много всего и в дальнейшем мы подробно поговорим про это. **Режим Конструктора** - это мощный инструмент, который делает разработку сложной логики довольно простой. У нас есть [отдельный урок](http://stencyl.pajamdev.ru/2-postroenie-logiki/rabota-s-povedeniyami/) посвященный тому, как работает этот редактор. Хотя сейчас вам просто достаточно знать, что он существует.

<div class="note">
**Примечание:** Предпочитаете печатать код, вместо этого? Мы предлагаем два способа добавить код в игру, специальный Code Editor *(Редактор Кода)* (или подключаемый, чтобы использовать ваш любимый текстовый редактор) и специальные Code Blocks *(Блоки Кода)*, которые позволяют вставлять код в Режиме Конструктора.
</div>

## Сохранение

Когда вы работаете над игрой, **сохраняться чаще** - это хорошая идея. Просто нажмите на **кнопку Save Game** *(Сохранить Игру)* на главной панели инструментов, или нажмите Ctrl-S (Command-S на Mac).

![Save Game](https://raw.githubusercontent.com/Stencyl/stencylpedia/master/crash-course-1/images/crash-course-16.png)
