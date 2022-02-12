# C2.B9.3.4


## Задание

Оригинальная формулировка задания приведена [здесь](./TASK.md).


## Решение

1. Установил composer локально к себе в проект.
1. Установил библиотеку swiftmailer.
1. Обновил её до самой актуальной версии.
1. Сделал коммит с нужными файлами и папками, чтобы при «разворачивании» проекта другими разработчиками не потерялась установка библиотеки swiftmailer, но и лишнего в репозиторий не добавлял.

## Примечания

Настроил игнорирование локально установленного composer в .gitignore.
Проигнорировал предупреждение composer: "Package swiftmailer/swiftmailer is abandoned, you should avoid using it. Use symfony/mailer instead.",-
и настоял на установке и обновлении swiftmailer.
