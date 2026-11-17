# Лабораторная работа 2 — кофейня «Зерно»

Лендинг из 7 логических секций (header, hero, about, menu, gallery, reviews, footer),
свёрстан по методологии БЭМ (блок `card`, элемент `card__title`, модификатор `card--hit`).

## Структура
```
index.html
css/reset.css   — сброс стилей
css/style.css   — стили страницы (БЭМ)
img/            — изображения (SVG — векторная графика: логотип, иконки, иллюстрации)
fonts/          — инструкции по шрифтам (Montserrat + Inter из Google Fonts)
```

## Публикация на GitHub Pages
1. Создайте пустой репозиторий на github.com (например `lab2-zerno`).
2. В папке проекта:
   ```
   git init
   git add .
   git commit -m "Лабораторная работа 2"
   git branch -M main
   git remote add origin https://github.com/<ваш-логин>/lab2-zerno.git
   git push -u origin main
   ```
3. На GitHub: Settings → Pages → Source: «Deploy from a branch», Branch: `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты сайт будет доступен по адресу `https://<ваш-логин>.github.io/lab2-zerno/`.
