<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Харитонов Игорь Валентинович - Geely АвтоСпецЦентр Дубровка</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: #ffffff;              /* белый фон */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            min-height: 100dvh;                     /* корректная высота на iOS/Android */
            font-family: sans-serif;
            padding: 16px;
            -webkit-text-size-adjust: 100%;         /* не увеличивать шрифт при повороте */
        }

        .card-container {
            position: relative;
            width: 100%;
            max-width: 720px;
            margin: 0 auto;
        }

        .card-container img {
            width: 100%;
            height: auto;
            display: block;
            border-radius: 16px;                    /* скругление, можно убрать */
            user-select: none;
            -webkit-user-drag: none;
        }

        /* Кликабельные зоны поверх картинки */
        .btn-link {
            position: absolute;
            display: block;
            cursor: pointer;
            border-radius: 10px;
            transition: background-color .15s ease;

            /* Мобильные улучшения */
            -webkit-tap-highlight-color: transparent; /* убрать серый квадрат при тапе */
            touch-action: manipulation;               /* убрать задержку 300 мс и зум по двойному тапу */

            /* Отладка: раскомментируй, чтобы увидеть точные границы кнопок */
            /* background: rgba(255, 0, 0, 0.25); */
            /* outline: 1px dashed red; */
        }

        /* Подсветка на ПК */
        .btn-link:hover {
            background: rgba(0, 0, 0, 0.04);
        }

        /* Отклик на тап на мобилках */
        .btn-link:active {
            background: rgba(0, 0, 0, 0.06);
        }

        /* На тач-устройствах отключаем hover, чтобы не «залипал» */
        @media (hover: none) {
            .btn-link:hover {
                background: transparent;
            }
        }
    </style>
</head>
<body>

    <div class="card-container">
        <img src="https://allwebs.ru/images/2026/10/23/c7f66b0ff4bf99a77de49277d6f5a5f7.png" alt="Визитная карточка">

        <!-- 1. Позвонить -->
<a href="tel:+79096262358" class="btn-link" aria-label="Позвонить"
   style="top: 57.2%; left: 5.5%; width: 54%; height: 6.8%;"></a>

<!-- 2. Telegram -->
<a href="https://t.me/IVkharitonov" target="_blank" rel="noopener" class="btn-link" aria-label="Написать в Telegram"
   style="top: 64.1%; left: 5.5%; width: 54%; height: 6.8%;"></a>

<!-- 3. Маршрут -->
<a href="https://yandex.ru/navi/org/geely_avtospetstsentr_dubrovka/45834037513?si=6ttvt4kacg8xh1utkr3nyjb8zr"
   target="_blank" rel="noopener" class="btn-link" aria-label="Построить маршрут"
   style="top: 71.0%; left: 5.5%; width: 54%; height: 7.2%;"></a>

<!-- 4. Сохранить контакт -->
<a href="tel:+79096262358" class="btn-link" aria-label="Сохранить контакт"
   style="top: 78.2%; left: 5.5%; width: 54%; height: 6.8%;"></a>

<!-- 5. Адрес -->
<a href="https://yandex.ru/navi/org/geely_avtospetstsentr_dubrovka/45834037513?si=6ttvt4kacg8xh1utkr3nyjb8zr"
   target="_blank" rel="noopener" class="btn-link" aria-label="Открыть адрес на карте"
   style="top: 86.0%; left: 5.5%; width: 54%; height: 8.0%;"></a>
    </div>

</body>
</html>
