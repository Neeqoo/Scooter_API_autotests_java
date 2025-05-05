### 🚀 API Autotests (Java) 

Репозиторий с автотестами для API запросов на Java. Проект предназначен для автоматизированного тестирования веб-интерфейса Яндекс.Самокат.

---

### 📌 Стек технологий

 - Язык: Java 11
 - Фреймворк: [Gson]
 - Сборка: Maven
 - Тест-раннер: JUnit 4
 - Отчет: Allure

--- 

### 🏗 Структура проекта

```
src/
├── test/java/ru/yandex/
    ├── apitests/
    │   ├── couriers/
    │   │   ├── CreateCourierTests    # Тесты для создания курьеров
    │   │   └── LoginCourierTests     # Тесты для авторизации курьеров
    │   └── orders/
    │       ├── CreateOrderTests      # Тесты для создания заказов
    │       └── GetOrdersListTests    # Тесты для получения заказов
    └── objects/
        ├── communication/
        │   ├── CourierRequest        # Методы для запросов (курьеры)
        │   ├── CourierResponse       # Методы для ответов (курьеры)
        │   ├── OrderRequest          # Методы для запросов (заказы)
        │   └── OrderResponse         # Методы для ответов (заказы)
        ├── http/
        │   ├── BaseHTTP              # Gson преобразования (основные)
        │   ├── CouriersHTTP          # Gson преобразования (для запросов с курьерами)
        │   └── OrdersHTTP            # Gson преобразования (для запросов с заказами)
        ├── methods/
        │   ├── CouriersMethods       # Методы (курьеры)
        │   └── OrdersMethods         # Методы (заказы)
        └── resource/
            ├── Api                   # Ключи (ручки) для API
            └── Urls                  # Рабочие web ссылки (рабочий сайт) 

```

