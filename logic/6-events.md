TODO _Поменять ссылки, чтобы они вели на страницы **этого** сайта._

Как напоминание перед началом, События являются строительными блоками Поведения. **Короче говоря, это вещи, которые происходят в вашей игре и могут вызвать какие-то действия или ответ.**

Для примера вернемся к нашей вертикальной Shoot 'Em Up игре, вспомним, что когда игрок нажимает пробел, корабль игрока стреляет лазером. В этом случае, **нажатие пробела** является **событием**, а **стрельба** из лазера является **ответом**. Событие и ответ связаны **причиной и следствием**.

![](http://blog.stencyl.com/wp-content/uploads/2012/01/iff.png)  
*если [^] сталкивается с [&], тогда уничтожается [&]*

Stencyl включает большое количество событий, которые разработчики могут использовать в своих интересах.

## Basics *(Основные)*

![](http://static.stencyl.com/pedia2/ch2/events/image37.png)

#### When Creating *(При Создании)*

![](http://static.stencyl.com/pedia2/ch2/events/image07.png)

Происходит один раз, когда Поведение инициировано.

#### When Drawing *(При Рисовании)*

![](http://static.stencyl.com/pedia2/ch2/events/image06.png)

Весь код для прорисовки идет сюда. Обычно происходит один раз фрейм. Различие между этим и "When Updating" *(При Обновлении)* состоит в том, что этот код происходит в разное время "игрового цикла". Также, лучше выполнять операции отображения только внутри When Drawing.

#### When Updating *(При Обновлении)*

![](http://static.stencyl.com/pedia2/ch2/events/image04.png)

Происходит каждый фрейм игры.

## Input (Ввод)

![](http://static.stencyl.com/pedia2/ch2/events/image25.png)

#### Keyboard *(Клавиатура)*

![](http://static.stencyl.com/pedia2/ch2/events/image17.png)

Клавиша pressed/released *(нажата/отжата)*.

#### Focus *(Фокус)*

![](http://static.stencyl.com/pedia2/ch2/events/image05.png)

Игра gains/loses *(получает/теряет)* фокус. Только для Web-игр.

#### Click *(Клик/Нажатие)*

![](http://static.stencyl.com/pedia2/ch2/events/image38.png)

Мышь pressed/released/moved/dragged *(нажала/отпустила/переместила/перетащила)*.

#### On Actor *(На Актера)*

![](http://static.stencyl.com/pedia2/ch2/events/image42.png)

Мышь enters/exits/presses/releases/drags *(наводит/отводит/нажимает/отпускает/тянет)* актера.

#### On Region *(На Регион)*

![](http://static.stencyl.com/pedia2/ch2/events/image31.png)

Мышь enters/exits/presses/releases/drags *(наводит/отводит/нажимает/отпускает/тянет)* регион.

## Time *(Время)*

![](http://static.stencyl.com/pedia2/ch2/events/image11.png)

#### After N seconds *(После N секунд)*

![](http://static.stencyl.com/pedia2/ch2/events/image29.png)

Выполняет код после данной задержки.

#### Every N seconds *(Каждые N секунд)*

![](http://static.stencyl.com/pedia2/ch2/events/image32.png)

Выполняет код каждые N секунд.

#### Pause/Unpause *(Пауза/Выход из паузы)*

![](http://static.stencyl.com/pedia2/ch2/events/image02.png)

Игра paused/unpaused *(На паузе/выходит из паузы)*. [Читайте нашу статью о Паузе.](http://www.stencyl.com/help/viewArticle/122/) FIXME

## Actors (Актеры)

![](http://static.stencyl.com/pedia2/ch2/events/image08.png)

#### Created or Dies: Specific Actor  *(Создается или Умирает: Определенный Актер)*

![](http://static.stencyl.com/pedia2/ch2/events/image39.png)

Актер Created/Killed *(Создается/Уничтожается)*.

#### Created or Dies: Actor of Type *(Создается или Умирает: Актер Типа)*

![](http://static.stencyl.com/pedia2/ch2/events/image22.png)

Актер Типа Created/Killed *(Создается/Уничтожается)*.

#### Created or Dies: Member of Group *(Создается или Умирает: Член Группы)*

![](http://static.stencyl.com/pedia2/ch2/events/image35.png)

Член группы Created/Killed *(Создается/Уничтожается)*.

#### Enters or Leaves the Scene or Screen: Specific Actor *(Входит или Покидает Сцену или Экран: Определенный Актер)*

![](http://static.stencyl.com/pedia2/ch2/events/image23.png)

Актер enters/leaves *(входит/покидает)* Screen/Scene *(Сцену/Экран)*.

#### Enters or Leaves the Scene or Screen: Actor of Type *(Входит или Покидает Сцену или Экран: Актер Типа)*

![](http://static.stencyl.com/pedia2/ch2/events/image16.png)

Актер Типа enters/leaves *(входит/покидает)* Screen/Scene *(Сцену/Экран)*.

#### Enters or Leaves the Scene or Screen: Member of Group *(Входит или Покидает Сцену или Экран: Член Группы)*

![](http://static.stencyl.com/pedia2/ch2/events/image24.png)

Член Группы enters/leaves *(входит/покидает)* Screen/Scene *(Сцену/Экран)*.

#### Enters or Leaves a Region: Specific Actor *(Входит или Покидает Регион: Определенный Актер)*

![](http://static.stencyl.com/pedia2/ch2/events/image01.png)

Актер enters/leaves *(входит/покидает)* Регион. [Читайте нашу статью о Регионах.](http://www.stencyl.com/help/viewArticle/113/) FIXME

#### Enters or Leaves a Region: Actor of Type *(Входит или Покидает Регион: Актер Типа)*

![](http://static.stencyl.com/pedia2/ch2/events/image34.png)

Актер Типа enters/leaves *(входит/покидает)* Регион. [Читайте нашу статью о Регионах.](http://www.stencyl.com/help/viewArticle/113/) FIXME

#### Enters or Leaves a Region: Member of Group *(Входит или Покидает Регион: Член Группы)*

![](http://static.stencyl.com/pedia2/ch2/events/image09.png)

Член Группы enters/leaves (входит/покидает) Регион. [Читайте нашу статью о Регионах.](http://www.stencyl.com/help/viewArticle/113/) FIXME

## Collisions *(Столкновения)*

![](http://static.stencyl.com/pedia2/ch2/events/image41.png)

#### This actor collides with: Something Else (Actor Type Behavior only) *(Этот актер сталкивается с: Чем-то Еще (Только Поведение Типа Актера))*

![](http://static.stencyl.com/pedia2/ch2/events/image36.png)

Происходит, когда этот актер сталкивается с другим актером.

#### Any actor collides with: Specific Actor *(Любой актер сталкивается с: Определенный Актер)*

![](http://static.stencyl.com/pedia2/ch2/events/image40.png)

Актер сталкивается с другим актером.

#### Any actor collides with: Actor of Type *(Любой актер сталкивается с: Тип Актера)*

![](http://static.stencyl.com/pedia2/ch2/events/image43.png)

Актер сталкивается с другим Типом Актера.

#### Any actor collides with: Member of Group *(Любой актер сталкивается с: Член Группы)*

![](http://static.stencyl.com/pedia2/ch2/events/image14.png)

Актер сталкивается с другим Членом Группы.

#### Collisions Between: Type & Type *(Столкновение Между: Тип и Тип)*

![](http://static.stencyl.com/pedia2/ch2/events/image18.png)

Актер типа сталкивается с актером другого типа.

#### Collisions Between: Group & Group *(Столкновение Между: Группа и Группа)*

![](http://static.stencyl.com/pedia2/ch2/events/image21.png)

Член группы сталкивается с членом другой группы.

## Sound *(Звук)*

![](http://static.stencyl.com/pedia2/ch2/events/image33.png)

#### Sound is done *(Звук закончился)*

![](http://static.stencyl.com/pedia2/ch2/events/image30.png)

Звук закончился. [Читайте о Воспроизведении Звука.](http://www.stencyl.com/help/viewArticle/115/)FIXME

#### Channel is done *(Канал закончился)*

![](http://static.stencyl.com/pedia2/ch2/events/image03.png)

Канал закончился. [Читайте о Каналах Звука.](http://www.stencyl.com/help/viewArticle/115/)FIXME

## Attributes *(Атрибуты)*

![](http://static.stencyl.com/pedia2/ch2/events/image19.png)

#### Number *(Число)*

![](http://static.stencyl.com/pedia2/ch2/events/image27.png)

Число становится greater/less *(больше/меньше)*, чем число.

#### Equality *(Равенство)*

![](http://static.stencyl.com/pedia2/ch2/events/image28.png)

Атрибут становится equal/not equal *(равным/неравным)* атрибуту.

#### Boolean *(Логика)*

![](http://static.stencyl.com/pedia2/ch2/events/image00.png)

Логика становится true/false *(истина/лож)*.

## Advanced *(Продвинутые)*

![](http://static.stencyl.com/pedia2/ch2/events/image10.png)

#### Custom Event *(Пользовательское Событие)*

![](http://static.stencyl.com/pedia2/ch2/events/image15.png)

Происходит, когда Поведение использует блок “триггера события” (такой как ‘onClick’ для нажатия кнопки). Подобно вызову функции, но без параметров. [Читайте нашу статью о пользовательских Событиях.](http://www.stencyl.com/help/viewArticle/148/)FIXME

#### Custom Block *(Пользовательский Блок)*

![](http://static.stencyl.com/pedia2/ch2/events/image12.png)

Настраиваемая форма ‘when [ ] happens’, которая позволяет создавать новые блоки. [Читайте нашу статью о пользовательских Блоках.](http://www.stencyl.com/help/viewArticle/106/)FIXME

#### Global Custom Block *(Глобальный Пользовательский Блок)*

![](http://static.stencyl.com/pedia2/ch2/events/image26.png)

Настраиваемая форма ‘when [ ] happens’, которая позволяет создавать новые блоки, не связанные с Актерами или Сценами. [Читайте нашу статью о пользовательских Блоках.](http://www.stencyl.com/help/viewArticle/106/)FIXME

#### Custom Code *(Пользовательский Код)*

![](http://static.stencyl.com/pedia2/ch2/events/image13.png)

Произвольный код, который живет за пределами регулярных событий. Вставьте многострочный блок кода (используя Flow > Advanced), чтобы использовать это.

#### Custom Import *(Пользовательский импорт)*

![](http://static.stencyl.com/pedia2/ch2/events/image20.png)

Операторы импорта для кодеров. Вставьте многострочный блок кода (используя Flow > Advanced), чтобы использовать это.
