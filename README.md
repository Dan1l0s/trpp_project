# ToDo List

Проект по ТРПП, РТУ МИРЭА, 4 семестр.
Работа выполнена студентами ИКБО-03-21 Антоновым Данилой Сергеевичем и Ахминым Максимом Сергеевичем.

## Изменение приложения

Если у Вас есть необходимость как-либо изменить под себя код приложения, то Вам необходимо:

1. Клонировать репозиторий проекта
2. Добавить файл-ключ для Firebase в корень проекта
3. Заменить соответствующие вхождения ключа на свои
4. Изменить код по свои нужды
5. Внутри Android Studio создать APK-файл, через который необходимо устанавливать приложение на свои устройства.

## Особенности приложения

### Создание персонального аккаунта

Для работы с приложением необходимо зарегистрироваться через почту, а также подтвердить регистрацию, перейдя по ссылке на почте.
Это позволяет иметь общий аккаунт для работы с нескольких устройств (соответственно, с синхронизацией данных)

### Добавление заданий с крайним сроком выполнения

При создании задания пользователю предлагается (опционально) указать дату и время крайнего срока выполнения задания.
В списке заданий происходит автоматическая сортировка заданий по статусу (выполнено, не выполнено, просрочено).
Также задания сортируются в порядке срочности, т.е. выше находятся те, которые нужно выполнить раньше других.

## Распределение обязанностей

Коллективная работа над проектом позволяет распределить обязанности, что упрощает взаимодействие участников команды.
В данном проекте мы выбрали следующее распределение обязанностей:

Антонов Данила Сергеевич - клиентская часть приложения, сортировка заданий, проверка корректности серверной части.
Ахмин Максим Сергеевич - взаимодействие с серверной частью приложения, проверка корректности клиентской части.
