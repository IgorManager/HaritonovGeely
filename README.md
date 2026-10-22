<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Харитонов Игорь Валентинович - Geely АвтоСпецЦентр Дубровка</title>
    <style>
        /* Полный сброс всех отступов */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            background-color: #ffffff;
            display: block;
            width: 100%;
        }

        /* Контейнер визитки */
        .card-container {
            position: relative;
            width: 100%;
            max-width: 720px; /* Ограничение ширины для ПК */
            margin: 0 auto;  /* Центрирование по горизонтали */
        }

        /* Картинка визитки */
        .card-container img {
            width: 100%;
            height: auto;
            display: block;
        }

        /* Стили кликабельных кнопок */
        .btn-link {
            position: absolute;
            display: block;
            cursor: pointer;
            z-index: 10;
            /* ВРЕМЕННАЯ ПОДСВЕТКА: удалите строчку ниже, когда всё проверите */
            background: rgba(255, 0, 0, 0.3); 
        }
    </style>
</head>
<body>

    <div class="card-container">
        <!-- Само изображение визитки -->
        <img src="https://allwebs.ru" alt="Визитная карточка">

        <!-- 1. Позвонить -->
        <a href="tel:+79096262358" class="btn-link" style="top: 57.0%; left: 5.5%; width: 51.5%; height: 6.0%;"></a>

        <!-- 2. Написать в Telegram -->
        <a href="https://t.me" target="_blank" class="btn-link" style="top: 64.0%; left: 5.5%; width: 51.5%; height: 6.0%;"></a>

        <!-- 3. Построить маршрут -->
        <a href="https://yandex.ru" target="_blank" class="btn-link" style="top: 71.0%; left: 5.5%; width: 51.5%; height: 6.0%;"></a>

        <!-- 4. Сохранить контакт -->
        <a href="tel:+79096262358" class="btn-link" style="top: 78.0%; left: 5.5%; width: 51.5%; height: 6.0%;"></a>

        <!-- 5. Нижний блок с адресом -->
        <a href="https://yandex.ru" target="_blank" class="btn-link" style="top: 86.5%; left: 5.5%; width: 55.0%; height: 7.0%;"></a>
    </div>

</body>
</html>
