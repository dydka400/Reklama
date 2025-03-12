# Reklama
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Рекламное агентство</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Эффективная реклама для вашего бизнеса</h1>
        <p>Привлекайте клиентов с помощью профессионального маркетинга</p>
        <button onclick="openForm()">Оставить заявку</button>
    </header>

    <section class="advantages">
        <h2>Почему выбирают нас?</h2>
        <div class="advantage">
            <h3>Целевая аудитория</h3>
            <p>Мы привлекаем только заинтересованных клиентов.</p>
        </div>
        <div class="advantage">
            <h3>Современные технологии</h3>
            <p>Используем передовые рекламные инструменты.</p>
        </div>
        <div class="advantage">
            <h3>Гарантия результата</h3>
            <p>Мы настраиваем кампании так, чтобы они приносили прибыль.</p>
        </div>
    </section>

    <div class="form-popup" id="formPopup">
        <div class="form-container">
            <h2>Оставьте заявку</h2>
            <form id="contactForm">
                <input type="text" id="name" placeholder="Ваше имя" required>
                <input type="email" id="email" placeholder="Ваш Email" required>
                <button type="submit">Отправить</button>
                <button type="button" onclick="closeForm()">Закрыть</button>
            </form>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
