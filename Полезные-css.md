# Полезные-css для голого HTML
Да, существуют библиотеки, которые автоматически стилизуют чистый HTML без необходимости вручную прописывать классы. Они применяют стили непосредственно к тегам (`<h1>`, `<p>`, `<table>` и т.д.), делая страницу визуально приятной "из коробки". Вот несколько популярных решений:

---

### 1. **Water.css**  
**Особенности**:  
- Просто подключите CSS-файл — библиотека стилизует стандартные HTML-теги.  
- Поддерживает светлую и тёмную тему (автоподстройка под систему).  
- Нет зависимостей от JS, только CSS.  

**Пример подключения**:  
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/water.css@2/out/water.css">
```

**Демо**: [https://watercss.kognise.dev/](https://watercss.kognise.dev/)  

---

### 2. **MVP.css**  
**Особенности**:  
- Стилизует тексты, формы, таблицы и даже `<code>` без классов.  
- Адаптивный дизайн для мобильных.  
- Минимум кода (всего ~10 КБ).  

**Пример подключения**:  
```html
<link rel="stylesheet" href="https://unpkg.com/mvp.css">
```

**Демо**: [https://andybrewer.github.io/mvp/](https://andybrewer.github.io/mvp/)  

---

### 3. **Pico.css**  
**Особенности**:  
- Семантический дизайн (стили для `<header>`, `<nav>`, `<section>`).  
- Встроенная сетка на CSS Grid.  
- Поддержка темной/светлой темы.  

**Пример подключения**:  
```html
<link rel="stylesheet" href="https://unpkg.com/@picocss/pico@latest/css/pico.min.css">
```

**Демо**: [https://picocss.com/examples/preview/](https://picocss.com/examples/preview/)  

---

### 4. **Sakura** (для минималистов)  
**Особенности**:  
- Очень легкий (~7 КБ).  
- Стилизует базовые теги в нежных тонах.  

**Пример подключения**:  
```html
<link rel="stylesheet" href="https://unpkg.com/sakura.css/css/sakura.css">
```

**Демо**: [https://oxal.org/projects/sakura/](https://oxal.org/projects/sakura/)  

---

### 5. **Tacit** (для графиков и данных)  
**Особенности**:  
- Фокус на контенте (хорошо стилизует `<table>`, `<pre>`).  
- Подходит для технической документации.  

**Пример подключения**:  
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yegor256/tacit@gh-pages/tacit-css.min.css">
```

**Демо**: [https://yegor256.github.io/tacit/](https://yegor256.github.io/tacit/)  

---

### Как выбрать?  
- Для **блога/документации**: Water.css или MVP.css.  
- Для **сложных лэндингов**: Pico.css.  
- Для **минимализма**: Sakura.  

Все они работают без JavaScript и не требуют добавления классов — просто пишите чистый HTML, и стили применятся автоматически! 🎨
