<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Харитонов Игорь Валентинович - Geely АвтоСпецЦентр Дубровка</title>
    <style>
        /* Сброс базовых отступов */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            background-color: #0d0f12; /* Темный фон под стиль визитки */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: sans-serif;
        }

        /* Главный контейнер визитки */
        .card-container {
            position: relative;
            width: 100%;
            max-width: 720px; /* Ограничение максимальной ширины на ПК */
            margin: 0 auto;
        }

        /* Адаптивная картинка визитки */
        .card-container img {
            width: 100%;
            height: auto;
            display: block;
        }

        /* Общие правила для кликабельных кнопок */
        .btn-link {
            position: absolute;
            display: block;
            cursor: pointer;
            /* Чтобы увидеть точные границы кнопок при отладке, раскомментируйте строчку ниже: */
            /* background: rgba(255, 0, 0, 0.3); */
        }
    </style>
</head>
<body>

    <div class="card-container">
        <!-- Ваша картинка-визитка -->
        <img src="https://allwebs.ru/images/2026/10/23/c7f66b0ff4bf99a77de49277d6f5a5f7.png" alt="Визитная карточка">

        <!-- Кнопка 1: Позвонить (Основная кнопка) -->
        <a href="tel:+79096262358" class="btn-link" style="top: 57.2%; left: 5.5%; width: 90%; height: 6.8%;"></a>

        <!-- Кнопка 2: Написать в Telegram -->
        <a href="https://t.me/IVkharitonov" target="_blank" class="btn-link" style="top: 64.1%; left: 5.5%; width: 90%; height: 6.8%;"></a>

        <!-- Кнопка 3: Построить маршрут в Яндекс Навигаторе -->
        <a href="https://yandex.ru/navi/org/geely_avtospetstsentr_dubrovka/45834037513?si=6ttvt4kacg8xh1utkr3nyjb8zr" target="_blank" class="btn-link" style="top: 71.0%; left: 5.5%; width: 90%; height: 7.2%;"></a>

        <!-- Кнопка 4: Сохранить контакт (Дублирует звонок / для вызова меню) -->
        <a href="tel:+79096262358" class="btn-link" style="top: 78.2%; left: 5.5%; width: 78%; height: 6.8%;"></a>

        <!-- Кнопка 5: Нижний блок с адресом (Ведет на Яндекс Карты) -->
        <a href="https://yandex.ru/navi/org/geely_avtospetstsentr_dubrovka/45834037513?si=6ttvt4kacg8xh1utkr3nyjb8zr" target="_blank" class="btn-link" style="top: 86.0%; left: 3.0%; width: 90%; height: 8.0%;"></a>
    </div>

</body>
</html>
