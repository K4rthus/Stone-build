# Stone

**«Stone»** — это атмосферная игра в жанре приключения с мистическим сюжетом. Игроку предстоит исследовать мрачный мир, взаимодействовать с объектами, избегать опасностей и принимать решения, влияющие на концовоку.

---

## Установка и запуск

### Инструкции:
1. Скачайте архив с игрой из репозитория.
2. Распакуйте файлы.
3. Запустите `stone.exe`.

### Требования:
- **ОС**: Windows 10 или новее
- **Процессор**: Intel Core i3 / AMD эквивалент (1.8 ГГц+)
- **ОЗУ**: 4 ГБ
- **Видеокарта**: NVIDIA GTX 960 / AMD Radeon R9 280
- **Разрешение экрана**: 320x180 (или кратно, например 1920x1080)
- **Дополнительно**: Клавиатура, мышь

---

## Управление
- **Движение влево**: `A` / `←`
- **Движение вправо**: `D` / `→`
- **Сделать фото**: `E`
- **Меню паузы**: `Esc`

---

## Особенности игры
- **Несколько концовок**: Ваши решения влияют на финал.
- **Атмосферный саундтрек**: Эмбиентные звуки и эффекты.

---

## Технологии
- **Движок**: Unity 6000.0.22f1
- **Среда разработки**: Visual Studio
- **Язык**: C#
- **Графика**: Pixel Art (Aseprite), анимации в Unity

---

## Структура проекта
```plaintext
stone/
├── D3D12/                     # Содержит библиотеки Direct3D 12 для рендеринга графики на Windows.
├── MonoBleedingEdge/          # Включает среду выполнения Mono для исполнения C#-скриптов в Unity. 
├── stone_Data/                # Основные данные игры: ресурсы (текстуры, звуки), настройки, сцены.
├── README.md                  # сам readme файл.
├── UnityCrashHandler64.exe/   # Обработчик аварийных завершений игры.
├── UnityPlayer.dll/           # Главная DLL-библиотека движка Unity.
└── stone.exe/                 # Исполняемый файл игры.
