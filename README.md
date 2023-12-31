# Homework_9

# Простий Консольний Бот-Асистент

Цей консольний бот-асистент дозволяє вам зберігати контакти з іменами та номерами телефонів, а також виконувати декілька корисних команд. Він ідеально підходить для ведення списку контактів та швидкого пошуку номерів телефонів.

## Як користуватися

Для запуску бота, просто виконайте файл `main.py` у вашому терміналі:

```
python main.py
```

Після запуску ви будете здатні взаємодіяти з ботом за допомогою команд, введених у консолі. Ось доступні команди:

- `hello`: Виводить вітання та запит на вашу команду.
- `add [ім'я] [номер]`: Додає новий контакт у ваш список. Наприклад, `add John 123456789`.
- `change [ім'я] [номер]`: Змінює номер телефону існуючого контакту. Наприклад, `change John 987654321`.
- `phone [ім'я]`: Виводить номер телефону для вказаного контакту. Наприклад, `phone John`.
- `show all`: Показує всі контакти, які ви зберегли разом з їхніми номерами телефонів.
- `good bye`, `close`, `exit`: Завершує роботу бота.

## Помилки та Валідація

Бот обробляє помилки вводу даних та повідомляє вас про них. Наприклад, якщо ви введете неправильну команду або неповну інформацію, бот надішле вам відповідне повідомлення про помилку.

## Залежності

Цей бот створено без використання будь-яких сторонніх бібліотек та фреймворків. Він використовує стандартний введення/виведення в консоль для взаємодії з користувачем.

---

Тепер ви готові до використання цього простого консольного бота-асистента для зберігання контактів та керування ними. Насолоджуйтесь!
