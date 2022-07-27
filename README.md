# Markdown
**Markdown** (произносится маркда́ун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций
## Content
### Heading
### Text attributes
### Lists
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
