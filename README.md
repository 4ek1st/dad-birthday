# Birthday Quest

Спокойная версия сайта-квеста на день рождения.

Эта версия специально сделана без фальшивого сверхтёплого текста:
- без "лучший папа на свете";
- без "семейная легенда";
- без слишком личных фраз через силу.

Тон: честный, спокойный, уважительный.

## Как опубликовать на GitHub Pages

1. Загрузи `index.html` и `README.md` в корень репозитория.
2. Открой `Settings` → `Pages`.
3. Выбери:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Подожди пару минут.
5. Ссылка появится сверху на странице GitHub Pages.

## Где менять текст

В `index.html`:

- вопросы: `const QUESTIONS = [...]`
- нижний список: `const SIMPLE_ITEMS = [...]`
- фото: `const PHOTOS = [...]`
- главное поздравление: блок `<div class="big-message">`

## Как добавить фото

Создай папку `assets` рядом с `index.html`.

Пример:

```text
assets/photo1.jpg
assets/photo2.jpg
assets/photo3.jpg
```

Потом в `const PHOTOS` замени:

```js
src: ""
```

на:

```js
src: "assets/photo1.jpg"
```
