# Blum Auto Clicker Footbal Event ⚽
Версия под футбольный ивент

Рекомендуемая область выделения:

 <img width="200" height="370" src="https://github.com/user-attachments/assets/08047b86-12e7-40e5-9e81-2c56a22866fe">


## Описание
Blum Auto Clicker - это утилита, которая помогает автоматизировать клики в приложении Blum.io. Кликер имитирует человеческие клики, что делает его использование безопасным и естественным, а также снижает риск блокировки аккаунта.

### Основные возможности
1. Оптимизированный основной цикл кликера.
2. Имитирует человеческие клики.
3. Пропускает около 5% поинтов для снижения риска блокировки (средний результат 180-200).
4. Удобный и интуитивно понятный пользовательский интерфейс.
    
### Демонстрация работы скрипта
<p align="center">
  <img width="200" height="300" src="https://github.com/user-attachments/assets/5b7438b5-cd34-4f5e-b2e0-18f8df4c6ff6">
  <img width="500" height="300"src="https://github.com/user-attachments/assets/c44f0f4b-cdd4-4e4a-b466-f4bff63df285">
  <img width="200" height="300" src="https://github.com/user-attachments/assets/151f07da-66ef-40c6-a205-45a24b1aef59">
</p>

    
## Скачивание и настройка Blum Auto Clicker

1. **Клонирование репозитория**
   - Откройте терминал и выполните следующую команду для клонирования репозитория:
     ```sh
     git clone https://github.com/IlyaKukharchuk/BlumClicker.git
     ```

2. **Перейдите в каталог проекта**
   - Перейдите в каталог клонированного репозитория:
     ```sh
     cd BlumClicker
     ```

3. **Создайте и активируйте виртуальное окружение (необязательно, но рекомендуется)**
   - Создайте виртуальное окружение:
     ```sh
     python -m venv venv
     ```
   - Активируйте виртуальное окружение:
     - На Windows:
       ```sh
       venv\Scripts\activate
       ```
     - На macOS/Linux:
       ```sh
       source venv/bin/activate
       ```

4. **Установите необходимые зависимости**
   - Установите зависимости:
     ```sh
     pip install -r requirements.txt
     ```

5. **Запустите приложение**
   - Чтобы запустить приложение, выполните следующую команду:
     ```sh
     python clicker_by_crypto_groove.py
     ```

### Запуск в IDE

Если вы предпочитаете запускать приложение в IDE, такой как PyCharm, VSCode или другой:

1. **Откройте проект в IDE**
   - Откройте вашу IDE и выберите каталог проекта `BlumClicker`.

2. **Настройте интерпретатор**
   - Убедитесь, что ваша IDE использует виртуальное окружение, созданное ранее.

3. **Установите зависимости в IDE**
   - Если IDE поддерживает это, используйте встроенный терминал или управление зависимостями для установки зависимостей из файла `requirements.txt`.

4. **Запустите приложение**
   - Найдите `clicker_by_crypto_groove.py` в проводнике проекта и запустите его.

### Компиляция в исполняемый файл (если кому-то нужно)

1. **Запустите PyInstaller**
   - Установите PyInstaller, если он еще не установлен:
     ```sh
     pip install pyinstaller
     ```
   - Запустите PyInstaller с файлом спецификации:
     ```sh
     pyinstaller clicker_by_crypto_groove.spec
     ```

2. **Найдите исполняемый файл**
   - После завершения процесса сборки исполняемый файл будет находиться в каталоге `dist/autoclicker_v3.0_by_crypto_groove`.

## Как использовать

### 1. Запуск приложения
- Откройте приложение автокликера Blum Auto Clicker.
- Вы увидите основное окно приложения с несколькими кнопками.

### 2. Задание области кликов
- Нажмите кнопку "Задать область кликов".
- Откроется полупрозрачное синее окно.
- Используйте мышь, чтобы выделить область экрана, в которой должны происходить клики. ОБЯЗАТЕЛЬНО область должна быть довольно узкой как на видео.
- После выделения области окно закроется, и область будет сохранена.

### 3. Указание кнопки старта
- Нажмите кнопку "Указать кнопку старта".
- Откроется полупрозрачное красное окно.
- Кликните по кнопке в игре, на которую должен ориентироваться автокликер для начала работы.
- Окно закроется, и координаты кнопки будут сохранены.

### 4. Запуск автокликера
- Нажмите кнопку "Запустить кликер" либо сочетание клавиш Ctrl+Alt+S.
- Чтобы приостановить или возобновить работу автокликера, используйте комбинацию клавиш Ctrl+Alt+S.

## Поддержка проекта
Если вам нравится этот проект 😊, вы можете поддержать меня, сделав донат на печеньки 🍪 (Возможно так быстрее выйдет версия под Mac):

| Валюта       | Адрес                                                                                       | QR-код                                                                                                                                     |
|--------------|----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| **Bitcoin (BTC)** | `bc1qdnck6tg6fcdydurfx5h5c2wx0ackl34vx6xl8g`                                               | <img width="200" height="250" src="https://github.com/user-attachments/assets/0b9b429a-2a05-4eef-85e0-e8c91dc709d5">                                             |
| **Ethereum (ETH)** | `0x1df1F807148713de041c7d4015aA1e4079341deb`                                               | <img width="200" height="250" src="https://github.com/user-attachments/assets/8b5b1688-8891-4c24-99e8-3441531d622b">                                            |
| **Toncoin (TON)** | `UQCMpjS0rqhf3O1GyWmCTAOF6kJhLoDbPE-ZZQbC7yoUF1Ty`                                        | <img width="200" height="250" src="https://github.com/user-attachments/assets/4cafc1b0-85f2-4fb4-ac62-26844a472ad8">                                         |
| **Tether (USDT) сеть TRC20** | `TTcp5iDQrZj2Xq9o3LCHxNubQxgi8GKtq5`                                                 | <img width="200" height="250" src="https://github.com/user-attachments/assets/16abf07d-7ffc-4026-a1a3-b9f688fcc119">                                  |


---

Скачайте Blum Auto Clicker и наслаждайтесь автоматизацией ваших кликов на Blum.io! 



