# Справка (Туториал) по основам системы контроля версий GIT

## Как инициализировать GIT

1)
**Чтобы инициализировать репозиторий необходимо прописать в терминале следующую команду:**
```
git init
```
2)**Чтобы добавить файл для отслеживания необходимо ввести команду**

```
git add .
```
3)**Так же можно проверить журнал изменений и действий**
для этого введите команду
~~~
git log
~~~
или 
~~~
git reflog
~~~
4)**Так же можно переключатся на интересующую нас точку фиксации
команда для перехода
~~~
git checkout <имя фиксации>
~~~
для возврата на главную ветку мастер
вводим команду
```
git checkout master
```

5)**для того чтобы перейти и сброситься до интересующей нас точки фиксации надо ввести команду 
```
git reset <имя фиксации>
```
по умолчанию используется сброс --soft
есть еще вариант ключа --hard

# Туториал (справка) для работы с языком разметки MarkDown


## Заголовки





## Цитаты
Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");




## Исходный код




## Таблицы