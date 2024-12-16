# Домашнее задание к занятию "`Работа с roles`" - `Бакулев Евгений`

# Решение:

1. В старом playbook создал файл requirements.yml с указанным содержимым:

![img_1.png](IMG/img_1.png)

2. Скачал роль с помощью `ansible-galaxy`, появилась директория `roles` с субдиректорией `clickhouse`, в которой находится playbook для установки роли clickhouse.

3. С помощью `ansible-galaxy role init vector-role` создал роль `vector-role`.

4. Заполнил новую роль, разнес переменные по соответствующим директориям.

5. Перенес шаблоны конфигов в `templates` роли.

6. Сделал описание для созданных ролей в файлах `README.md`.

7. Повторил все шаги для роли `lighthouse-role`.

8. Выложил роли в репозитории. Ссылки на репозитории ролей:

https://github.com/garrkiss/vector-role

https://github.com/garrkiss/lighthouse-role

9. Изменил playbook на использование roles.

10. Выложил playbook в репозиторий. Ссылка на playbook: 

---
