# 1. Создайте пустой репозиторий на сервисе github.com (или gitlab.com, или bitbucket.com).

![](images/1.png)

# 2. Выполните инструкцию по созданию первого коммита на странице репозитория, созданного на предыдещем шаге.

![](images/2.png)

# 3. Создайте файл hello_world.cpp в локальной копии репозитория (который должен был появиться на шаге 2). Реализуйте программу Hello world на языке C++ используя плохой стиль кода. Например, после заголовочных файлов вставьте строку using namespace std;.

# 4. Добавьте этот файл в локальную копию репозитория.

![](images/3.png)

# 5. Закоммитьте изменения с осмысленным сообщением.

![](images/4.png)

# 6. Изменитьте исходный код так, чтобы программа через стандартный поток ввода запрашивалось имя пользователя. А в стандартный поток вывода печаталось сообщение Hello world from @name, где @name имя пользователя.

![](images/5.png)

# 7. Закоммитьте новую версию программы. 

![](images/6.png)

# 8. Запуште изменения в удалёный репозиторий.

![](images/7.png)



# 1. В локальной копии репозитория создайте локальную ветку patch1.

![](images/8.png)

# 2. Внесите изменения в ветке patch1 по исправлению кода и избавления от using namespace std;.

![](images/9.png)

# 3. commit, push локальную ветку в удалённый репозиторий.

![](images/10.png)

# 4. Проверьте, что ветка patch1 доступна в удалёный репозитории.

![](images/11.png)

# 5. Создайте pull-request patch1 -> master.

![](images/12.png)

# 6. В локальной копии в ветке patch1 добавьте в исходный код комментарии.

# 7. commit, push.

# 8. Проверьте, что новые изменения есть в созданном на шаге 5 pull-request

![](images/13.png)

# 9. В удалённый репозитории выполните слияние PR patch1 -> master и удалите ветку patch1 в удаленном репозитории.

![](images/18.png)

# 10. Локально выполните pull.

![](images/15.png)

# 11. С помощью команды git log просмотрите историю в локальной версии ветки master.

![](images/16.png)

# 12. Удалите локальную ветку patch1.

![](images/19.png)




# 1. Создайте новую локальную ветку patch2.

![](images/20.png)

# 2. Измените code style с помощью утилиты clang-format. Например, используя опцию -style=Mozilla.

![](images/21.png)

# 3. commit, push, создайте pull-request patch2 -> master.

![](images/22.png)

# 4. В ветке master в удаленном репозитории измените комментарии, например, расставьте знаки препинания, переведите комментарии на другой язык.

![](images/23.png)

# 5. Убедитесь, что в pull-request появились конфликтны.

# 6. Для этого локально выполните pull + rebase (точную последовательность команд, следует узнать самостоятельно). Исправьте конфликты.

![](images/24.png)

# 7. Сделайте force push в ветку patch2

![](images/25.png)

# 8. Убедитель, что в pull-request пропали конфликтны.

![](images/26.png)

# 9. Вмержите pull-request patch2 -> master.

![](images/27.png)




