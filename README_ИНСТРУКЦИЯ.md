# Белая Дача Орск — Сайт

Сайт для фермерского хозяйства «Белая Дача» (г. Орск)

## Структура

```
farm-website/
├── index.html              # Главная страница
├── style.css               # Стили
├── script.js               # Анимация и меню
├── images/                 # Фото овощей
│   ├── corn.jpg           # Кукуруза
│   ├── cucumbers.jpg      # Огурцы
│   ├── peppers.jpg        # Перец
│   ├── sprouts.jpg        # Рассада
│   ├── tomatoes_close.jpg # Помидоры крупно
│   ├── tomatoes_harvest.jpg # Сбор урожая
│   └── watermelon.jpg     # Арбуз
└── README_ИНСТРУКЦИЯ.md   # Этот файл
```

## Размещение на GitHub Pages

### Шаг 1: Создайте аккаунт на GitHub
1. Перейдите на https://github.com
2. Нажмите "Sign up" и зарегистрируйтесь
3. Подтвердите email

### Шаг 2: Создайте репозиторий
1. В правом верхнем углу нажмите "+" → "New repository"
2. **Важно:** Введите имя репозитория в формате: `ваше-имя.github.io`
   - Например: `belayadacha-orsk.github.io` или `ivanov56.github.io`
3. Сделайте репозиторий **Public**
4. Нажмите "Create repository"

### Шаг 3: Загрузите файлы

#### Вариант А: Через браузер (проще)
1. В созданном репозитории нажмите "uploading an existing file"
2. Перетащите **все файлы** из папки `farm-website`:
   - `index.html`
   - `style.css`
   - `script.js`
   - **Папку `images`** со всеми фотографиями
3. Внизу введите сообщение "Initial commit" и нажмите "Commit changes"

#### Вариант Б: Через Git командой
```powershell
cd C:\Users\stroi\farm-website

# Настройте Git (один раз)
git config --global user.name "Ваше Имя"
git config --global user.email "ваш-email@example.com"

# Инициализируйте репозиторий
git init
git add .
git commit -m "Initial commit"

# Добавьте удалённый репозиторий (замените USERNAME на ваш логин GitHub)
git remote add origin https://github.com/USERNAME/USERNAME.github.io.git

# Отправьте файлы
git branch -M main
git push -u origin main
```

### Шаг 4: Включите GitHub Pages
1. В репозитории перейдите в **Settings** → **Pages**
2. В разделе "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** → папка **/(root)**
3. Нажмите **Save**

### Шаг 5: Готово!
Через 1-3 минуты сайт будет доступен по адресу:
```
https://ваше-имя.github.io
```

## Контакты на сайте
- Telegram канал: @bd5656
- По вопросам: @belay_dahj
- Регион: Оренбургская область, г. Орск

## Как обновлять
1. Внесите изменения в файлы локально
2. Загрузите новые версии через браузер
3. Или через Git:
   ```powershell
   git add .
   git commit -m "Описание изменений"
   git push
   ```
