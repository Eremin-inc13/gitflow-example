# gitflow-example

GitFlow

1. Создать репозиторий и клонировать его на комп
2. Создать ветку разработки develop от главной ветки(main, master)
3. Создать от ветки develop feature/-ветки и мержить feature/-ветки в develop, когда фичи будут готовы
4. Создание ветки release/0.1.0 от develop
5. Когда ветка release закончена она мержится в develop и main и затем удаляется
6. Если в ветке main обнаруживается ошибка, то создается hotfix-ветка
7. Когда работа в над hotfix-веткой завершается, то ее нужно мержить в develop и main
