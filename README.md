# Задание 3. Найдите ошибки

В этом репозитории находится решение тестового задания «Найдите ошибки» для [17-й Школы разработки интерфейсов](https://yandex.ru/promo/academy/shri) (лето-2021, Москва).

В ходе выполения задания были найдены следущие ошибки:
  1. При первом запуске приложение не запустилось, что было вызвано отсутствием в type Action возвращаемого типа функции actionUpdate. Его добавление исправило ошибку при запуске.
  2. При клике на кнопку NEXT слайды переключались не вперед, а назад, поскольку диспатчился actionPrev вместо actionNext.
  3. По умолчанию должна использоваться темная тема, а использовалась светлая.