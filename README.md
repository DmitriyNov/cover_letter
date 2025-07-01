# Сопроводительное письмо для Red Collar

[GitHub Pages](https://dmitriynov.github.io/cover_letter/)

[Макет Figma](https://www.figma.com/design/Fun0vhkMs0o7NTLPNug1Rk/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D0%BE%D0%B5-%D0%B4%D0%BB%D1%8F-%D1%84%D1%80%D0%BE%D0%BD%D1%82-%D1%88%D0%BA%D0%BE%D0%BB%D1%8B?node-id=64-189&t=2mV2HYhPgVd1Uf8z-0)

---

### Локальный запуск

```bash
git clone https://github.com/DmitriyNov/cover_letter.git
cd cover_letter
npm i
npm run dev
```

---

### Используемые технологии

- **HTML**
- **SCSS**
- **Vite**

---

### Структура

```
cover_letter/
├── .github/
│   └── workflows/
│       └── deploy.yml          # Настройки Github Actions
├── src/
│   ├── assets/
│   │   ├── favicons/           # Иконка для сайта
│   │   ├── fonts/              # Шрифты
│   │   ├── icons/              # Иконки
│   │   └── images/             # Изображения
│   │
│   ├── styles/
│   │   ├── base/
│   │   │   ├── fonts.scss      # Подключение шрифтов
│   │   │   ├── globals.scss    # Глобальные стили
│   │   │   ├── reset.scss      # Сброс стандартных стилей
│   │   │   └── variables.scss  # SCSS-переменные
│   │   │
│   │   ├── components/
│   │   │   ├── _about.scss     # Стили компонента "About"
│   │   │   └── _contacts.scss  # Стили компонента "Contacts"
│   │   │
│   │   ├── utils/
│   │   │   └── _mixins.scss    # SCSS-миксины
│   │   │
│   │   └── main.scss          # Главный файл стилей
│   │
│   ├── main.js                 # Главный JS-файл
│   └── index.html              # Точка входа
│
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── vite.config.js
```

---

**Новокрещёнов Дмитрий**
**2025**
