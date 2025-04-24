# goit-markup-hw-01

📌 Модуль 1: Основи HTML
🔹 1. Основи веб-розробки
Frontend та Backend – основні складові сайту
Супутні технології: HTML, CSS, JavaScript
🔹 2. Структура HTML
📌 Основні елементи:
Структура документа
Теги та атрибути:
Типи тегів: текстові, посилання, списки, таблиці, блоки
Семантичні теги та доступність: <header>, <main>, <footer>, <nav>, <aside>
Парні та одинокі теги
DOM: батьківські, дочірні, нащадки, предки, сестринські елементи
Атрибути тегів
🔹 3. Графіка
Растрова та векторна графіка
🔹 4. Структурні теги
Тег Опис

<html>	Кореневий тег документа
<head>	Метаінформація сторінки
<body>	Вміст сторінки
🔹 5. Заголовки та текст
Тег	Опис
<h1> – <h6>	Заголовки різних рівнів
<p>	Абзац тексту
<span>	Рядковий контейнер
<div>	Блочний контейнер
<strong>	Жирний текст
<em>	Курсивний текст
<br>	Перенесення рядка
<hr>	Горизонтальна лінія
🔹 6. Списки
Тег	Опис
<ul>	Ненумерований список
<ol>	Нумерований список
<li>	Пункт списку
🔹 7. Таблиці
Тег	Опис
<table>	Таблиця
<tr>	Рядок таблиці
<td>	Комірка таблиці
<th>	Заголовок комірки
🔹 8. Форми
Тег	Опис
<form>	Форма введення
<input>	Поле введення
<textarea>	Багаторядкове поле
<button>	Кнопка
<label>	Мітка для введення
<select>	Випадаючий список
<option>	Варіант у списку
🔹 9. Посилання та зображення
Тег	Опис
<a>	Гіперпосилання
<img>	Зображення
🔹 10. Семантичні теги
Тег	Опис
<header>	Заголовок секції
<nav>	Навігаційне меню
<section>	Розділ сторінки
<article>	Незалежний блок контенту
<aside>	Додаткова інформація
<footer>	Нижній колонтитул
🔹 11. Скрипти та стилі
Тег	Опис
<script>	JavaScript-код
<link>	Підключення стилів
<style>	CSS-стилі
🔹 Додаткові ресурси 📚
🖼 Remove.bg – сервіс для видалення фону із зображень
🛠 iLoveIMG – інструменти для обробки зображень
✅ W3C Validator – перевірка HTML-коду на помилки
📖 MDN HTML Docs – офіційна документація HTML

📌 Модуль 2.2: Основи CSS - Fonts
dev-tools
FontFascia - Figma Plugin для визначення шрифтів
🔹 1. Основи CSS
властивості оформлення тексту
сімейства шрифту serif та sans-serif
властивості оформлення шрифту
підключення зовнішніх шрифтів через GoogleFonts
🔹 2. Додаткові плагіни
FontFascia - Figma Plugin для визначення шрифтів
🔹 3. Властивості оформелння тексту
text-align

text-decoration

text-transform

text-indent

line-height

letter-spacing

word-spacing

text-shadow

Сімейства шрифту serif та sans-serif

Властивості оформлення шрифту:

font-size

font-weight

font-style

font-family

🔹 4. CSS змінні
Опис CSS код
Оголошення змінних у :root :root { --main-color: blue; --font-size: 16px; }
Використання змінних у стилях p { color: var(--main-color); font-size: var(--font-size); }

📌 Модуль 1.1: Основи CSS
🔹 1. Основи CSS
синтаксис CSS: правила / селектор / властивості / значення
підключення стилей
CSS селектори: тега / класу / ідентифікатора / атрибута /нащадка / дитини
псевдокласи стану
колір тексту
каскад / пріоритетність / спадкування
CSS змінні
🔹 2. Підключення стилів
Вбудований (inline styles)
Внутрішній (internal styles)
Зовнішній (external styles)
🔹 3. Селектори CSS
Селектор Приклад Опис
Тега p {} Застосовує стилі до всіх <p>
Тега h1 { color: blue; } Застосовує стилі до всіх <h1>
Класу .title {} Застосовує стилі до елементів з class="title"
Класу .red-text { color: red; } Застосовує стилі до всіх елементів з class="red-text"
Ідентифікатора #main {} Застосовує стилі до елемента з id="main"
Ідентифікатора #header { color: green; } Застосовує стилі до елемента з id="header"
Атрибута [type="text"] {} Стилізує всі <input type="text">
Атрибута a[target="_blank"] { color: purple; } Стилізує всі посилання, що відкриваються в новому вікні
Нащадка div p {} Стилізує <p>, які знаходяться в <div>
Дитини div > p {} Стилізує <p>, які є тільки першими дітьми <div>
🔹 4. Псевдокласи стану
Псевдоклас Опис
:hover Застосовується при наведенні миші
:focus Коли елемент у фокусі (наприклад, у полі вводу)
:first-child Перший дочірній елемент
:last-child Останній дочірній елемент
:nth-child(odd/even/n) Вибирає елементи за номером (парні, непарні або за індексом)
🔹 5. Колір тексту
Назва кольору Формат Значення
🔹 Червоний CSS color color: red;
🎨 HEX-код HEX color: #ff0000;
🎭 RGB RGB color: rgb(255, 0, 0);
🌈 RGBA (з прозорістю) RGBA color: rgba(255, 0, 0, 0.5);
🔥 HSL HSL color: hsl(0, 100%, 50%);
🔹 6. Каскад, пріоритетність, спадкування
Каскад
Опис CSS правила
Правила для кольору тексту p { color: red; }
Перезапис правил, останнє спрацює p { color: blue; } /_ Спрацює останнє правило → текст буде синім _/
Пріоритетність
Порядок застосування Тип селектора Опис

1. Найвищий пріоритет Inline-стилі (style="") Стилі, задані безпосередньо в HTML-елементі
2. Вищий пріоритет ID-селектор (#id) Стилі, задані за допомогою унікальних ідентифікаторів
3. Середній пріоритет Клас (.class) Стилі, задані через класи елементів
4. Найнижчий пріоритет Тег (h1, p, div тощо) Стилі, задані через HTML теги
   🔹 7. Спадкування
   Деякі властивості (наприклад, color, font-family) успадковуються від батьківських елементів, інші (border, margin, padding) — ні.
   🔹 8. CSS змінні
   Опис CSS код
   Оголошення змінних у :root :root { --main-color: blue; --font-size: 16px; }
   Використання змінних у стилях p { color: var(--main-color); font-size: var(--font-size); }

📌 Модуль 3.1: Блокова модель
🔹 1. План заняття
Блокова модель елемента
Властивості width та height
Модель візуального форматування: box-sizing
Геометрія елемента
Рамки та заокруглені рамки
"Схлопування" і випадіння вертикальних маржинів
Горизонтальне центрування блокових елементів
Типи боксів: блокові, рядкові та рядково-блокові елементи. Властивість display
🔹 2. Box-model
Основні компоненти блокової моделі:
content — вміст елемента
padding — відступи всередині елемента
border — межа елемента
margin — відступи зовні елемента
Властивості для управління розмірами та відступами:
top, right, bottom, left — для позиціювання елемента
width, height — ширина та висота елемента (з максимальними та мінімальними значеннями)
box-sizing: content-box | border-box | inherit — управління розмірами елемента з урахуванням рамок і відступів
Стилізація рамок:
border: solid, dotted, dashed, double — типи рамок
border-radius - заокруглення кутів рамки
Оформлення переповнення:
overflow: visible | hidden | scroll | auto
Значення Опис
visible 🔹 За замовчуванням. Вміст виходить за межі контейнера і видимий.
hidden 🔒 Вміст, що виходить за межі, обрізається і не видно.
scroll 📜 Завжди додає прокрутку, навіть якщо вона не потрібна.
auto ⚙️ Додає прокрутку лише при потребі, якщо вміст не вміщується.
Типи елементів:
display: block, inline, inline-block, none — управління відображенням елементів
Центрування елементів на сторінці:
margin: margin: 0 auto; || margin-right: auto; margin-left: auto;
Налаштування "Гумові картинки":
display: block;
max-width: 100%;
height: auto;
Альтернативний спосіб:
display: block;
max-width: 100%;
height: 100%;
object-fit: cover;
Приховування заголовків (visually-hidden):
position: absolute;
white-space: nowrap;
width: 1px;
height: 1px;
overflow: hidden;
border: 0;
padding: 0;
clip: rect(0 0 0 0);
clip-path: inset(50%);
margin: -1px;

📌 Модуль 3.1: Блокова модель
🔹 1. План заняття
Блокова модель елемента
Властивості width та height
Модель візуального форматування: box-sizing
Геометрія елемента
Рамки та заокруглені рамки
"Схлопування" і випадіння вертикальних маржинів
Горизонтальне центрування блокових елементів
Типи боксів: блокові, рядкові та рядково-блокові елементи. Властивість display
🔹 2. Flexbox
Властивість display:
display: — flex | inline-flex
Властивості flex контейнера:
gap: — відступ між flex елементами

flex-direction: — row | row-reverse | column | column-reverse

justify-content: — flex-start | flex-end | center | space-between | space-around | space-evenly

align-items: — stretch | flex-start | flex-end | center | baseline

flex-wrap: — nowrap | wrap | wrap-reverse

align-content: — flex-start | flex-end | center | space-between | space-around | space-evenly | stretch

CSS-функція calc(): — calc((100% - 20px \* 2) / 3);

Властивості flex елементів:
flex-basis: — auto | значення
flex-grow: — значення
flex-shrink: — значення
align-self: — auto | flex-start | flex-end | center | baseline | stretch
order: — позиція
🔹 3. Структурні псевдокласи
Стани елементів (інтерактивні):

:hover — коли курсор на елементі
:focus — коли елемент у фокусі (наприклад, інпут)
:active — під час кліку
:visited — для відвіданих посилань
Положення в DOM:

:first-child — перший елемент у батьківському
:last-child — останній
:nth-child(n) — n-ий за рахунком (number | odd | even)
** Фільтрація**:

:not(selector) — все, крім вказаного
:empty — елемент без дітей
:is() — групування селекторів (новіший синтаксис)
Оформлення переповнення:
overflow: visible | hidden | scroll | auto
Значення Опис
visible 🔹 За замовчуванням. Вміст виходить за межі контейнера і видимий.
hidden 🔒 Вміст, що виходить за межі, обрізається і не видно.
scroll 📜 Завжди додає прокрутку, навіть якщо вона не потрібна.
auto ⚙️ Додає прокрутку лише при потребі, якщо вміст не вміщується.
Типи елементів:
display: block, inline, inline-block, none — управління відображенням елементів
Налаштування "Гумові картинки":
display: block;
max-width: 100%;
height: auto;
Альтернативний спосіб:
display: block;
max-width: 100%;
height: 100%;
object-fit: cover;

📘 Модуль 4.1: Декоративні елементи
🗂 План заняття
🖼 Контентні та декоративні зображення
🎨 Властивості: background-color, background-image, background-repeat, background-position, background-size
🧅 Багатошаровий фон
🌈 Градієнти: лінійний, радіальний
🕶 CSS-тіні та властивість box-shadow
📐 Векторна графіка (SVG)
✏️ Основи SVG-фігур
🧩 Способи використання SVG
🧰 Створення та робота з SVG-спрайтом
🧙‍♀️ Псевдоелементи ::before та ::after
🖼 Властивість background-image
🔁 background-repeat
repeat — повторювати X і Y. Значення за замовчуванням.
repeat-x — повторювати тільки X (горизонтально).
repeat-y — повторювати тільки Y (вертикально).
no-repeat — не повторювати.
📍 background-position
x y
50% 50%
100px 200px
right bottom
left top
📏 background-size
auto auto
200px
200px 300px
cover — масштабувати, щоб покрити весь елемент
contain — масштабувати, щоб вмістити зображення всередину елемента
🧅 Багатошаровий фон
Приклад:
background-image: url(шлях до зображення 1), url(шлях до зображення 2);

🌈 Градієнти
🔄 Лінійний градієнт
Синтаксис:
background-image: linear-gradient(<напрямок>, <колір-1>, <колір-2>, ...)

Приклад з фоном:
background-image: linear-gradient(to top, rgba(17, 17, 17, 0.4), rgba(17, 17, 17, 0.4)), url("path_to_image");

🎯 Радіальний градієнт
Приклад:
background-image: radial-gradient(rgba(17, 17, 17, 0.3), rgba(17, 17, 17, 1)), url("path_to_image");

🧰 background (скорочена форма)
Приклад:
background: url(шлях до зображення) repeat-x;

🕶 Властивість box-shadow
Синтаксис:
box-shadow: <x-offset> <y-offset> <blur> <spread> <color>;

Можна додати inset для внутрішньої тіні:
box-shadow: inset <x-offset> <y-offset> <blur> <spread> <color>;

🔳 Багатошарова тінь
Приклад:
box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1), 0px 6px 20px rgba(0, 0, 0, 0.1);

🔗 Приклади: getcssscan.com/css-box-shadow-examples

📐 Векторна графіка
Вбудований SVG (inline)
Властивість fill — визначає колір заливки
Властивість stroke — визначає колір рамок
🧰 SVG-спрайт
Генерація через: icomoon.io/app

Оптимізація SVG: svgomg.net

<svg class="class-name" width="24" height="24"> <use href="./sprite.svg#icon-instagram"></use> </svg>

🧙‍♀️ Псевдоелементи
Використання:
.box::before, .box::after, .box:hover::before

📘 Модуль 4.2: Декоративні елементи
📍 Позиціонування
position: static | relative | absolute | fixed | sticky
z-index
🎬 CSS-переходи
transition-property: <властивість> | color, background-color

transition-duration: <час> | 2s | 0.5s | 2000ms | 500ms

transition-timing-function: <функція розподілу часу> | ease, linear, ease-in, ease-out, ease-in-out

transition-delay: <затримка>

transition: [property] [duration] [timing-function] [delay]

transition: background-color 500ms linear, transform 500ms ease-in-out;

Властивість transition-timing-function
ease — перехід починається повільно, швидко прискорюється, а потім знову сповільнюється в кінці.
linear — перехід має рівномірну швидкість.
ease-in — починається повільно, швидкість переходу збільшується до повного завершення переходу.
ease-out — починається швидко, уповільнюється протягом переходу.
ease-in-out — починається повільно, прискорюється, а потім знову сповільнюється.
🌀 2D-трансформації
transform: none | <тип трансформації> <тип трансформації> ...
transform: scale(1.15) — маштабування
transform: rotate(45deg) — прокручування
transform: translate(100px, 200px) — зміщення
transform: translate(-50%, -50%) — центрування елемента
transform: skew(30deg) — викривлення
🧙‍♀️ Псевдоелементи
Використання:
.box::before, .box::after, .box:hover::before

👩‍🏫 Заняття 9: Форми і таблиці
🎯 Ціль заняття
Ознайомитись з основними HTML-тегами для створення форм
Розібрати атрибути форм та їх поведінку
Навчитись працювати з валідацією та псевдокласами
Продовжити роботу над проєктом, додавши форми
📌 1. Вступ
Що розглянемо:

Теги form, label, input, textarea, select, fieldset, optgroup, datalist
Атрибути: type, name, placeholder, checked, required, disabled, autofocus, minLength, maxLength, step, value, min, max
Псевдокласи: :focus-within, :placeholder-shown, :checked
Стилизування textarea — властивість resize
🙋‍♂️ 2. Відповіді на питання студентів
(з файлу питань — буде заповнюватись на уроці)

🧩 3. Продовження проєкта
📄 Базові теги форм:
Тег Призначення

<form>	Контейнер для форми
<label>	Підпис до елемента форми
<input>	Поле вводу (вказується тип через type)
<textarea>	Багаторядкове текстове поле
<select>	Випадаючий список
<optgroup>	Група опцій у <select>
<datalist>	Варіанти підказок до <input>
<fieldset>	Групування пов’язаних елементів форми
⚙️ Важливі атрибути input:
Атрибут	Пояснення
type	Тип поля (див. нижче)
name	Ім’я поля (важливо для обробки даних)
placeholder	Підказка у полі
checked	Встановлює обране значення (для checkbox, radio)
required	Поле обов’язкове для заповнення
disabled	Поле вимкнене
autofocus	Фокус при завантаженні сторінки
min, max, step, value	Для числових полів
minLength, maxLength	Для текстових/парольних полів
⌨️ Типи input:
<input type="text">
<input type="email">
<input type="checkbox" checked>
<input type="radio" name="choice">
<input type="number" value="0" min="18" max="120" step="0.5">
<input type="date">
<input type="time">
<input type="datetime-local">
<input type="tel">
<input type="password" minLength="6" maxLength="20">
🔹 Додаткові ресурси 📚
🖼 dashly-theme – приклад використання форм
🖼 ant.design – одна з популярних js бібліотек з різними компонентами

👩‍🏫 Заняття 9: Форми і таблиці
🎯 Ціль заняття
Ознайомитись з основними HTML-тегами для створення форм
Розібрати атрибути форм та їх поведінку
Навчитись працювати з валідацією та псевдокласами
Продовжити роботу над проєктом, додавши форми
📌 1. Вступ
Що розглянемо:

Теги form, label, input, textarea, select, fieldset, optgroup, datalist
Атрибути: type, name, placeholder, checked, required, disabled, autofocus, minLength, maxLength, step, value, min, max
Псевдокласи: :focus-within, :placeholder-shown, :checked
Стилизування textarea — властивість resize
🙋‍♂️ 2. Відповіді на питання студентів
(з файлу питань — буде заповнюватись на уроці)

🧩 3. Продовження проєкта
📄 Базові теги форм:
Тег Призначення

<form>	Контейнер для форми
<label>	Підпис до елемента форми
<input>	Поле вводу (вказується тип через type)
<textarea>	Багаторядкове текстове поле
<select>	Випадаючий список
<optgroup>	Група опцій у <select>
<datalist>	Варіанти підказок до <input>
<fieldset>	Групування пов’язаних елементів форми
⚙️ Важливі атрибути input:
Атрибут	Пояснення
type	Тип поля (див. нижче)
name	Ім’я поля (важливо для обробки даних)
placeholder	Підказка у полі
checked	Встановлює обране значення (для checkbox, radio)
required	Поле обов’язкове для заповнення
disabled	Поле вимкнене
autofocus	Фокус при завантаженні сторінки
min, max, step, value	Для числових полів
minLength, maxLength	Для текстових/парольних полів
⌨️ Типи input:
<input type="text">
<input type="email">
<input type="checkbox" checked>
<input type="radio" name="choice">
<input type="number" value="0" min="18" max="120" step="0.5">
<input type="date">
<input type="time">
<input type="datetime-local">
<input type="tel">
<input type="password" minLength="6" maxLength="20">
🔹 Додаткові ресурси 📚
🖼 dashly-theme – приклад використання форм
🖼 ant.design – одна з популярних js бібліотек з різними компонентами
