## Завдання: Управління адресною книгою

**Опис:** Розробити систему для управління адресною книгою з такими сутностями:

- **Field**: базовий клас для полів запису.
- **Name**: зберігає ім'я контакту (обов'язкове поле).
- **Phone**: зберігає номер телефону (з перевіркою формату).
- **Record**: зберігає контактну інформацію, включаючи ім'я та список телефонів.
- **AddressBook**: управляє всіма записами.

**Функціональність:**
- **AddressBook**:
  - Додавання записів.
  - Пошук за іменем.
  - Видалення за іменем.
- **Record**:
  - Додавання, видалення та редагування телефонів.
  - Пошук телефону.