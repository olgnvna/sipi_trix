# Документация пользователя для турагентства "Путешествуй с нами"

## Содержание
1. [Регистрация и вход](#регистрация-и-вход)
2. [Личный кабинет клиента](#личный-кабинет-клиента)
3. [Работа с бронированиями](#работа-с-бронированиями)
4. [Панель администратора](#панель-администратора)
5. [Частые вопросы](#частые-вопросы)
6. [Обратная связь](#обратная-связь)

---

## Регистрация и вход

### Регистрация нового клиента
1. Перейдите на страницу регистрации (register.php)
2. Заполните обязательные поля:
   - Имя и фамилия
   - Email (будет использоваться для входа)
   - Номер телефона
   - Паспортные данные
   - Пароль (не менее 6 символов)
3. Нажмите кнопку "Зарегистрироваться"
4. После успешной регистрации вы автоматически войдёте в систему

### Вход в систему
1. Перейдите на страницу входа (login.php)
2. Введите:
   - Email (указанный при регистрации)
   - Пароль
3. Нажмите кнопку "Войти"
4. После успешного входа вы будете перенаправлены в личный кабинет

---

## Личный кабинет клиента

После входа вы попадёте на страницу `client_dashboard.php`, где доступны:

### Просмотр бронирований
- Таблица со всеми вашими турами
- По каждому туру отображается:
  - ID бронирования
  - Дата и время вылета
  - Название отеля
  - Общая стоимость (рейс + отель)
  - Текущий статус

### Поиск и фильтрация
Вы можете искать бронирования по:
- Конкретной дате вылета
- Названию отеля (можно частичное совпадение)
- Статусу бронирования:
  - Активно
  - Ожидает отмены
  - Отменено

---

## Работа с бронированиями

### Отмена бронирования
1. Найдите нужное бронирование в списке
2. Нажмите кнопку "Отменить" (доступна только для активных бронирований)
3. Подтвердите отмену во всплывающем окне
4. Статус изменится на "Ожидает отмены"
5. Администратор обработает вашу заявку в течение 24 часов

### Просмотр деталей
- Вся информация о бронировании отображается в таблице
- Для получения дополнительной информации обратитесь к администратору

---

## Панель администратора

Доступна по адресу `admin_dashboard.php` после входа под учётной записью администратора.

### Управление бронированиями
- Просмотр всех бронирований
- Подтверждение/отклонение заявок на отмену
- Ручная отмена бронирований
- Удаление отменённых бронирований

### Добавление новых элементов
1. **Рейсы**:
   - Дата и время вылета
   - Направление
   - Стоимость перелёта

2. **Отели**:
   - Название
   - Адрес
   - Стоимость за ночь

3. **Туры**:
   - Выбор клиента
   - Выбор рейса и отеля
   - Назначение ответственного сотрудника
   - Дополнительная информация

---

## Частые вопросы

### Для клиентов:
❓ **Как изменить свои данные?**  
➡️ Обратитесь к администратору через форму обратной связи

❓ **Можно ли восстановить пароль?**  
➡️ В текущей версии системы требуется обращение к администратору

❓ **Когда спишутся деньги за тур?**  
➡️ Оплата производится при подтверждении бронирования администратором

### Для администраторов:
❓ **Как добавить нового сотрудника?**  
➡️ Через прямое добавление в таблицу Workers базы данных

❓ **Где посмотреть статистику?**  
➡️ В текущей версии статистика доступна только через SQL-запросы

---

## Обратная связь

По всем вопросам обращайтесь:
📧 Email: sonvhx@icloud.com  
☎ Телефон: +7 (XXX) XXX-XX-XX (уточняйте у администратора)

Техническая поддержка работает с 9:00 до 18:00 по московскому времени.

---

Версия системы: 1.0  
Последнее обновление: апрель 2024
