

Horror survival game | HTML5 + Canvas | No dependencies | Play in browser


🎮 Описание
Забытый Дом — хоррор-игра о выживании в духе 80-х.
Твой дедушка Виктор пропал три года назад в старом доме. Ты — Алекс — приходишь найти его.
Внутри тебя ждут призраки, тени, монстры и загадочный Страж.
Твоё единственное оружие — фонарик. Свет жжёт призраков.

✨ Особенности
ФичаОписание🕯 Реалистичный светRaycast с отражениями от стен👻 4 типа враговПризрак, Тень, Монстр, Призрак Дьявол (редкий)💀 Финальный босс3 фазы, спавн призраков, орбы тьмы📖 СюжетДневник деда, диалоги, 3 концовки🦜 Попугай КеоПитомец-компаньон, всегда летит за тобой⚡ СпидранТаймер, сплиты по комнатам, рекорды🏆 8 достиженийОхотник, Спидраннер, Экзорцист и др.🎵 Атмосферная музыкаWeb Audio API — дрон, пианино, скрипы🔒 РежимыИстория → разблокировка Охоты на боссов📱 MobileD-pad поддержка для телефонов

🎯 Управление
WASD / ←↑↓→   Движение
Shift          Бег
E / Пробел     Взаимодействие / войти в дверь
F              Фонарик вкл/выкл
Мышь           Направление фонарика
ESC            Пауза

🏠 Структура проекта
forgotten-house/
├── index.html          # Вся игра (single-file)
├── README.md           # Этот файл
├── LICENSE             # MIT License
├── .gitignore          # Git ignore
├── CHANGELOG.md        # История изменений
├── docs/
│   ├── GAMEPLAY.md     # Гайд по игре
│   ├── LORE.md         # Лор и сюжет
│   └── DEPLOY.md       # Инструкция по деплою
└── assets/
    └── screenshot.png  # Скриншот (добавь сам)

🚀 Быстрый старт
Играть локально
bashgit clone https://github.com/YOUR-USERNAME/forgotten-house.git
cd forgotten-house
# Просто открой index.html в браузере!
open index.html
Запустить через сервер (рекомендуется для аудио)
bash# Python 3
python3 -m http.server 8080

# Node.js
npx serve .

# Затем открой http://localhost:8080

🌐 Деплой на GitHub Pages

Создай репозиторий на GitHub
Залей файлы:

bashgit init
git add .
git commit -m "🎮 Initial release"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/forgotten-house.git
git push -u origin main

Зайди в Settings → Pages → Source: main branch
Игра будет доступна по адресу:
https://YOUR-USERNAME.github.io/forgotten-house/


📱 Play Market (Android)
Используй Capacitor для обёртки в APK:
bashnpm install -g @capacitor/cli
npm init -y
npm install @capacitor/core @capacitor/android

npx cap init "Forgotten House" "com.yourname.forgottenhouse"
npx cap add android

# Скопируй index.html в папку www/
cp index.html www/

npx cap sync
npx cap open android
# Собери APK в Android Studio

🛠 Технологии

HTML5 Canvas 2D — вся графика
Web Audio API — процедурная музыка
Vanilla JS — без фреймворков и зависимостей
localStorage — сохранение рекордов и прогресса
Raycast — реалистичный свет с отражениями


📊 Статистика кода
МетрикаЗначениеФайлов1 (single-file app)Строк кода~2400Зависимостей0Размер~85 KB

🗺 Roadmap

 Звуковые эффекты (шаги, удары)
 Система крафта (костёр из дерева)
 Случайная генерация карты
 Мультиплеер (WebSocket)
 Мобильное приложение (Capacitor)
 Таблица рекордов (Firebase)
 Новые боссы и комнаты
 Русский / Английский язык





👤 Автор
Сделано с ❤️ и попугаем Кео.

"Свет побеждает тьму. Всегда." — Дед Виктор
