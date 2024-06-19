# DZ_May
Контроль версий (контроль исходного кода) — практика, которая позволяет отслеживать изменения исходного кода и управлять ими.
## Команды GIT
1. git init - инициализация: указываем папку, в которой git начнёт отслеживать изменения. В папке создаётся скрытая папка .git.
2. git status - показывает текущее состояние гита, есть ли изменения,которые нужно закоммитить(сохранить).
3. git add - добавляет содержимое рабочего каталога 
в индекс (staging area) для последующего коммита. Эта команда дается после добавления файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически.
4. git commit - зафиксировать или сохранить.
5. git log - журнал изменений. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений.
6. git checkout - Переключение между версиями. Для работы нужно указать не только интересующий вас коммит, но и вернуться в тот, где работаем, при помощи команды git checkout master.
7. git diff - Показывает разницу между текущим файлом и сохранённым. Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений.
8. git merge - Чтобы слить любую ветку с текущей, вызываем git merge <имя ветки для слияния с текущей>
9. git log --graph - Ключ -graf в связке с командой log позволяет отобразить коммиты в виде дерева.
10. git branch - Если у нас несколько версий черновика, мы можем вывести на экран ветку, где находимся, командой git branch. Создать ветку можно командой git branch. Делать это надо в папке с репозиторием: git branch <название новой ветки>.
11. git pull -Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией
12. git push -Эта команда позволяет отправить нашуверсию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.
## Отзыв курсе