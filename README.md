# Markdown
**Markdown** (произносится маркда́ун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций
## Content
### Heading
Заголовки в Markdown выделяются с помощью знаков решетки (#). Можно просто поставить нужное количество решеток в начале строки, чтобы указать уровень. Или заключить строку с двух сторон по аналогии с HTML-тегами, кому как удобно.

Другой вариант: написать текст первого заголовка, затем нажать Enter и на следующей строке указать любое количество знаков «равно» (===). Аналогичным образом можно выделить заголовок 2го уровня, только использовать уже нужно дефисы (---). Заголовки других уровней таким методом оформить нельзя.

### Text attributes
Форматирование курсивом и жирным точно есть во всех инструментах, где другие функции Markdown могут быть ограничены. Синтаксис выделения текста и расставления акцентов:

__Жирный__ (выделяем с двух сторон двойным нижним дефисом __)

**Тоже жирный** (выделяем с двух сторон **)

*Курсив* (выделяем с двух сторон *)

_Тоже курсив_ (выделяем с двух знаком нижнего подчеркивания _)

~~Зачеркнутый~~ (выделяем с двух сторон ~~)

Перечисленные способы выделения можно комбинировать. Например: __*Пример*__ 

### Lists
Чтобы оформить строку в элемент маркированного списка, в начале нужно поставить плюс, минус или звездочку. Звездочка не приведет к курсивному выделению, потому что отделяется от слова пробелом.

- Пример (со знаком -)
+ Пример (со знаком +)
* Пример ( со *)

Если необходимо создать нумерованный список, используйте в начале строки цифру с точкой. Удобно, что нумерация автоматическая: можно вставить любые цифры, и ошибки не будет.
1. Пример
4. Пример
5. Пример

### Links and images

Чтобы поставить **гиперссылку** без анкора, нужно взять URL в угловые скобки. С e-mail – аналогично.

Если вставлять с анкором, то тогда текст ссылки заключается в квадратные скобки, а адрес страницы – в круглые. Рядом с URL можно прописать тайтл, его объявляют в кавычках (он тоже остается внутри круглых скобок).

[Эта ссылка](http://SecondLessonInProgress.ru/) без заголовка.


<https://SecondLessonInProgress.ru/> – а это безанкорная ссылка.

Основной способ, как отобразить **локальное изображение** в markdown документе, это использовать следующий код:

1![Текст с описанием картинки](/images/picture.jpg)
Часть в квадратных скобках - это так называемый альтернативный текст, который важен по следующим причинам:

Для доступности. Программы чтения с экрана читают именно его. Например, для тех, кто плохо видит.

Этот текст будет отображаться вместо изображения, если файл изображения не может быть загружен.

Он обеспечивает контекст и описание изображения для поисковых систем, помогая им с поиском.

Часть в круглых скобках - это путь к файлу. Обрати внимание, что перед images стоит /. Без этого символа твой документ может отображаться нормально на твоем компьютере, но после загрузки на сервер в интернете она отображаться перестанет. Это одна из основных причин, почему так случается.

## Implementations
Implementations of Markdown are available for over a dozen programming languages; in addition, many platforms and frameworks support Markdown. For example, Markdown plugins exist for every major blogging platform.
