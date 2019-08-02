
> **При переносе репозитория потерялись звезды GitHub. Давайте их вернем =) Пожалуйста, поставьте ★ сверху.**

# Современный учебник JavaScript

Всем привет!

Когда-то давно был только русский учебник https://learn.javascript.ru. Но несколько лет назад был полностью с нуля написан английский — https://javascript.info. И с тех пор все существенные изменения вносились только в него.

Сейчас учебники уже довольно сильно разошлись. Между статьями есть общие фрагменты, но и много различий.

Самое лучшее, что можно сделать – это перевести русский с английского. Для этого создан этот репозиторий.

**Пожалуйста, помогите нам с переводом!**

- Перейдите в ишью с [текущим состоянием перевода](https://github.com/javascript-tutorial/ru.javascript.info/issues/60).
- Выберите понравившуюся статью для перевода, у которой не отмечена галочка.
- Напишите комментарий, указав название выбранной статьи, чтобы мейнтейнер узнал об этом и отметил вас в чеклисте.
- Сделайте форк этого репозитория, начните переводить и когда закончите, откройте пулреквест.

**Если вы хорошо знаете JavaScript и можете делать ревью статей - напишите нам: ревью очень важны для качества переводов.**

🎉 Спасибо!

> **Обязательно ознакомьтесь с [рекомендациями по переводу](https://github.com/javascript-tutorial/ru.javascript.info/blob/master/TRANSLATION.md)!**

# Структура

Каждому разделу, статье или задаче соответствует директория.

Эта директория имеет вид `N-url`, где `N` - это номер для сортировки статей и разделов (они упорядочены), а `url` – URL-имя, по которому материал будет доступен.

В директории находится один из файлов:

  - `index.md` для раздела
  - `article.md` для статьи
  - `task.md` для условия задачи (+там же `solution.md` с решением)

Каждый из этих файлов начинается с `# Заголовка материала`, и дальше текст в формате а-ля Markdown. Его довольно просто понять. Для редактирования достаточно простого текстового редактора.

Ресурсы и примеры, необходимые для статьи, раздела или задачи, находятся в её директории. На них можно ссылаться из материала.

# Запуск локально

Для удобства редактирования учебник можно запустить локально.

Сервер для этого находится здесь: <https://github.com/javascript-tutorial/server>.
