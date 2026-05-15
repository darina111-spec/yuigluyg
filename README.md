<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Электронная Библиотека</title>
    <!-- Подключение внешнего файла стилей -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Mansion Library</h1>
        <p>Электронный каталог и заказ книг</p>
    </header>

    <main>
        <section class="category-section">
            <div class="category-title">Фантастика и Фэнтези</div>
            <div class="books-grid">
                
                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Интерстеллар</div>
                    <div class="book-author">Кристофер Нолан</div>
                    <div class="book-price">2 500 ₸</div>
                </div>

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Дюна</div>
                    <div class="book-author">Фрэнк Герберт</div>
                    <div class="book-price">3 200 ₸</div>
                </div>

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Властелин Колец</div>
                    <div class="book-author">Дж. Р. Р. Толкин</div>
                    <div class="book-price">4 500 ₸</div>
                </div>

            </div>
        </section>

        <section class="category-section">
            <div class="category-title">Детективы</div>
            <div class="books-grid">

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Шерлок Холмс</div>
                    <div class="book-author">Артур Конан Дойл</div>
                    <div class="book-price">2 800 ₸</div>
                </div>

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Убийство в Восточном экспрессе</div>
                    <div class="book-author">Агата Кристи</div>
                    <div class="book-price">2 900 ₸</div>
                </div>

            </div>
        </section>

        <section class="category-section">
            <div class="category-title">Психология и Саморазвитие</div>
            <div class="books-grid">

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Атомные привычки</div>
                    <div class="book-author">Джеймс CLIр</div>
                    <div class="book-price">3 800 ₸</div>
                </div>

                <div class="book-card">
                    <div class="book-cover">Обложка книги</div>
                    <div class="book-title">Думай медленно... Решай быстро</div>
                    <div class="book-author">Даниэль Канеман</div>
                    <div class="book-price">4 100 ₸</div>
                </div>

            </div>
        </section>
    </main>

</body>
</html>

  /* Общие настройки страницы (Коричневая палитра) */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #2D1A12; /* Глубокий темно-коричневый фон */
    color: #F5EBE6; /* Очень светлый бежевый текст */
    line-height: 1.6;
    margin: 0;
    padding: 10px;
}

/* Главный контейнер по центру */
.container {
    max-width: 800px;
    margin: 20px auto;
    background-color: #3D251E; /* Кофейный фон для карточки */
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.3);
}

/* Заголовки */
h1 {
    color: #E6C5B3; /* Нежный древесно-бежевый оттенок */
    font-size: 2rem;
    margin-bottom: 20px;
    border-bottom: 2px solid #5A3A31;
    padding-bottom: 10px;
}

h2 {
    color: #D4A373; /* Теплый карамельный цвет */
    font-size: 1.4rem;
    margin-top: 30px;
}

/* Стилизация строгого блока документов */
.document-block {
    background-color: #261610; /* Более темный фон для контраста документа */
    border: 1px solid #5A3A31;
    padding: 20px;
    margin: 25px 0;
    border-radius: 6px;
}

.doc-header {
    font-family: 'Courier New', Courier, monospace; /* Шрифт печатной машинки */
    font-weight: bold;
    text-align: center;
    color: #D4A373;
    margin-bottom: 15px;
    letter-spacing: 1px;
    font-size: 0.95rem;
}

.doc-table {
    width: 100%;
    border-collapse: collapse;
    font-family: 'Courier New', Courier, monospace;
    font-size: 0.9rem;
}

.doc-table th, .doc-table td {
    border: 1px solid #5A3A31;
    padding: 10px;
    text-align: left;
}

.doc-table th {
    background-color: #341E16;
    color: #E6C5B3;
}

/* Списки кейсов */
ul {
    list-style: none;
    padding: 0;
}

li {
    background-color: #4A312A;
    margin-bottom: 12px;
    padding: 15px;
    border-radius: 8px;
    border-left: 5px solid #D4A373;
    transition: all 0.3s ease;
}

li:hover {
    transform: translateX(5px);
    background-color: #543830;
    border-left-color: #E6C5B3;
}

strong {
    color: #FFF;
}

.placeholder {
    color: #FFB703;
    font-style: italic;
}

/* Адаптивная верстка */
@media (max-width: 600px) {
    body { padding: 5px; }
    .container { padding: 20px; margin: 10px auto; }
    h1 { font-size: 1.6rem; }
    h2 { font-size: 1.2rem; }
    .doc-table { font-size: 0.8rem; }
}
s
