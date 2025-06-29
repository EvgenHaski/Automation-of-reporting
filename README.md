# ⚙️ Automation of Reporting

Этот репозиторий содержит примеры автоматизированных отчётов, которые я создавал в рамках своей работы аналитиком данных.  
Здесь находятся только те отчеты, которые не попадают под NDA.

---

## 🧠 Используемые технологии

- Python (`pandas`, `numpy`, `requests`)
- Работа с Excel-файлами (`openpyxl`, `xlrd`)
- Интеграция с Outlook
- Упаковка скриптов в `.exe` с помощью `PyInstaller` (для простоты использования другими сотрудниками)

---

## 📂 Содержание

### 📌 1. `New-products-on-PBL`

**Что делает:**  
Извлекает и обрабатывает данные из Excel-файлов, чтобы автоматически сформировать отчёт, отвечающий на вопрос: **можно ли пропустить новый товар через цепочку PBL (сокращённая цепочка поставок)**.

**Результат:**  
Автоматическая проверка и логическое обоснование допуска товара.  
Существенно ускоряет работу категорийных менеджеров и аналитиков.

---

### 📌 2. `Pallet-sorting-report`

**Что делает:**  
Скачивает множество Excel-таблиц с корпоративного сайта, объединяет и обрабатывает их. Расчёт доли переборки паллет после поставки на склад.

**Результат:**  
Автоматический расчёт **процента переборки паллет**.  
Помогает следить за качеством переборки паллет и снижать операционные издержки.

---

### 📌 3. `Processing-letters`

**Что делает:**  
Читает письма с вложениями Excel, обрабатывает информацию о цепочках поставок поставщика и формирует **ответное письмо в Outlook** с необходимыми комментариями.

**Результат:**  
Значительно ускоряет коммуникацию с коллегами и стандартизирует ответ.  
Позволяет формировать обоснованные рекомендации по структуре цепей поставок.

---

## 🚀 Эффект автоматизации

- ⏱️ **Сокращение времени подготовки отчётов** с 1 часа до нескольких минут
- ❌ **Уменьшение количества ошибок** за счёт стандартизации обработки
- 🔁 Возможность обновлять данные **в один клик**
- 📦 Упаковка в `.exe`-файлы для запуска без среды разработки

---

## 🔒 Примечание

Количество автоматизированных отчётов на практике было больше, однако многие из них содержат данные, защищённые соглашением о неразглашении (NDA), и не могут быть представлены в открытом доступе.

---
