# 24.1. Разметка markdown
## Сценарии использования
**Оформление листа заказа**

**Цель:** Оформить лист заказа, чтобы заказать выбранную пиццу

**Основной сценарий:**
1. Система показывает полное меню
2. Пользователь выбирает пиццу
3. Система добавляет пиццу в лист заказа
4. Пользователь добавляет топпинги к пицце
5. Система добавляет топпинги в лист заказа
6. Пользователь проверяет лист заказа и оформляет заказ
   
**Альтернативный сценарий (с  шага 6 основного сценария необходима альтернативная ветка):**

6. Пользователь удаляет топпинг к пицце 
7. Возврат к пункту 6 основного сценария

**Сценарий исключение: (с  шага 4 основного сценария необходима альтернативная ветка):**

4. Пользователь удаляет выбранную пиццу
5. Система удаляет пиццу из листа заказа
6. Пользователь не заказывает пиццу

Итог для Исключения - возвращение к основному сценарию не выполнено, т.к. цель разная
