**Подключение google test из базового репозитория**

*Добавляем подмодуль к проекту*

git submodule add https://github.com/google/googletest.git third_party/gtest

*Заливаем изменения*

git add .gitmodules third_party/gtest

git commit -m "Add GoogleTest as submodule"

git push

*Путь к тестам*

third_party\gtest\googletest\include\gtest

*После клонирования репозитория*

git submodule init

git submodule update
