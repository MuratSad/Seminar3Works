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





## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```

Самое приятное, что в коде не нужно заменять угловые скобки `< >` и амперсанд `&` на их html-сущности.



## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Можно управлять выравниванием столбцов при помощи двоеточия.

| Left-Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |     **$1600** |
| col 2 is      | centered        |         $12   |
| zebra stripes | are neat        |        ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.