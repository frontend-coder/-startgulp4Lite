# Start temptate Gulp4

Я зібрав новий стартовий шаблон для забеспечення швидкого старту верстки и продакш-складання інтернет проекту під замовлення, керуючись запропонованному Figma- или PSD-макету. В якості  таск-менеджер використовую Gulp 4.

До стартового шблону додав normalize та найпростішу сітку, що прийнята в Web-дізайні. Ширина макета за умовченням складає - 1140px. За необхідністью це значення можливо змінити у файлі grid.css

За умовченням додав:
jQuery v3.3.1
jquery.PageScroll2id v1.5.8
Magnific Popup v1.1.0
Owl Carousel v2.3.4
jquery.nicescroll v3.7.6
font-awesome-4.7.0

Щоб підключити/від'єднати потрібні/непотрібні плагіни, фрейворки, інше відкрийте файли:

```
scss/_libs.scss
gulpfile.js
```

Цей стартовый шаблон призначенний для збирання HTML5 шаблонів різної складності за допомогою Gulp4, за умовчанням готовий до адаптивності шаблона. Він нічим не перевантаженний, але його можливо разширити за вимогою. 

### Як установити стартовый шаблон

Встановіть nodejs з підтримкою npm [https://nodejs.org/en/](https://nodejs.org/en/)
Встановіть git bash, якщо не використовуете консоль, жоден термінал не встановлений на компьютері під керуванням Windows 10 [gitforwindows](https://gitforwindows.org/)

Встановіть gulp глобально. Ця операция здійснюється одноразово, для цього потрібно у консолі прописується команда

```
npm install gulp-cli -g
```
Щоб побачити версію Gulp, яка інстальована на компьютер, потрібно використовувати команду

```
gulp -v
```

На момент написання цієї інструкції отримав наступну відповідь

```
CLI version 2.0.1
Local version 4.0.0
```

Щоб побачити версію nodejs, яка інстальована на компьютер,  потрібно використовувати команду

```
node -v
```
Щоб побачити перелік пакетів та версії npm, які інстальовані на компьютер,  потрібно використовувати команду

```
npm list -g --depth=0
```

Щоб почати работу зі стартовим пакетом потрібно:
* утворити каталог, в якому буде виконувати збірку шаблону
* розархівувати отриманий архів до створенного каталогу
* відкрийте його в VSCode. Щоб швидше це робити я використувую плагін Project Manager
* в терміналі прописується команда

```
npm i
```

* через декілька хвилин всі пакети збірки будуть встановлені

### Як інсталювати збірку шаблону

Після завершеня інсталювання пропишить команду, щоб запустити сервер:

```
gulp
```

За хвилиту автоматично запускается сервер, після чого в браузері відкриється головна сторінка сайта. Необхідно відкрити всі рабочі файли збірки та почати верстку шаблона.

каталог sass - писати scss-код 
каталог libs/common.js - писати кастомний js-код
index.html - виконуется HTML-розмітка шаблона

* Якшо необхідно встановити додаткові плагіни jQuery, всі їх файли розміщуються у каталозі libs.
* Якщо необхідно підключити js-файли, необхідно прописати шлях до них в файлі gulpfile.js
* Якщо з'явилася необхідність підключити файли css до збірки, потрібно прописати шлях до них в файлі app/scss/_ libs.scss

### Фінальна збірка шаблона

В терміналі пропишіть команду

```
gulp build
```
## Усі точки зламу для адаптації під усі мобільні пристрої:

    1920 базова точка
    1680 додаткова точка
1.  1440 базова точка
2.  1336 базова точка
    1280 додаткова точка
3.  1200 базова точка
4.  1190 базова точка
5.  1080 базова точка
6.  1024 базова точка
7.   992 базова точка
8.   980 базова точка
     834 додаткова точка
     812 додаткова точка
9.   815 базова точка
10.  800 базова точка
11.  768 базова точка
12.  740 базова точка
13.  736 базова точка
     734 додаткова точка
     684 додаткова точка
14.  667 базова точка
     640 додаткова точка
15.  600 базова точка 
16.  568 базова точка
17.  480 базова точка
18.  425 додаткова точка
19.  414 додаткова точка
     412 додаткова точка
20.  387 базова точка
21.  384 додаткова точка
     375 додаткова точка
22.  360 додаткова точка
23.  320 базова точка

## Контроль за якістью кода

За умовчуванням виконане налаштування котролю  за якістью написанного коду в процессі роботи. До зборки додані такі інструменти:

* Eslint
* Prettier
* Stylelint
  
Для активації цих інструментів використовуйте IDE VSCode да встановіть слідуючі плагіны:

* Prettier - Code formatter
* ESLint | Dirk Baeumer
* vscode-stylelint

## Звязатися зі мною з питань розробки сайті під ключ:
<br>

[![facebook](https://img.shields.io/badge/-Facebook-1877F2?style=for-the-badge&logo=Figma&logoColor=eeffff)](https://www.facebook.com/frontendercode)
[![Telegram](https://img.shields.io/badge/-Telegram-26A5E4?style=for-the-badge&logo=Telegram&logoColor=eeffff)](https://t.me/frontendcoder)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=Instagram&logoColor=eeffff)](https://www.instagram.com/frontendercode/?hl=ru)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=eeffff)](https://github.com/frontend-coder)

[![Portfolio](https://img.shields.io/badge/-Портфолио-181717?style=for-the-badge&logo=Internet-Archive&logoColor=eeffff)](https://frontend-coder.github.io)
