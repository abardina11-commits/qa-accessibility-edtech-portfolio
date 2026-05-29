# Инструкция по установке и настройке инструментов accessibility-тестирования

## 1. WAVE (Web Accessibility Evaluation Tool)

### Установка
1. Откройте браузер **Google Chrome**.
2. Перейдите в Chrome Web Store: [WAVE Extension](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
3. Нажмите **«Установить»**.
4. После установки в правом верхнем углу браузера появится иконка WAVE.

### Проверка работы
- Откройте любую страницу (например, https://demoqa.com).
- Нажмите на иконку WAVE. Должна появиться панель с отчётом об ошибках доступности.

## 2. Lighthouse (встроен в Chrome DevTools)

### Использование
Lighthouse не требует установки, так как встроен в Chrome DevTools.
1. Откройте нужную страницу.
2. Нажмите `F12` (или `Ctrl+Shift+I`) для открытия DevTools.
3. Перейдите на вкладку **«Lighthouse»** (если не видите, нажмите `>>`).
4. Выберите категории (например, Accessibility, Best Practices, SEO) и устройство (Desktop/Mobile).
5. Нажмите **«Generate report»**.
6. После завершения можно экспортировать отчёт в HTML (три точки → `Export report`).

## 3. axe DevTools

### Установка
1. Перейдите в Chrome Web Store: [axe DevTools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)
2. Нажмите **«Установить»**.
3. После установки в DevTools появится вкладка **«axe DevTools»**.

### Проверка работы
- Откройте DevTools (`F12`).
- Найдите вкладку **«axe DevTools»** (обычно справа от вкладки Lighthouse).
- Нажмите **«Scan»** для проверки текущей страницы.
- Будут показаны нарушения с пояснениями и ссылками на WCAG.

## Скриншоты работы инструментов

Скриншоты сохранены в папке `assets/screenshots/`:
- `wave_extension.png`
- `lighthouse_report.png`
- `axe_devtools.png`

---

**Дата установки:** 2026-05-29  
**Установщик:** Анастасия Бардина
EAQ-4: add tools installation guide and screenshots
