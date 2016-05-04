# Игра Орел или Решка
Lesson 2

Игра поддерживает 3 режима:

+ 1 режим - игровой, запуск файла из консоли без каких либо флагов

        > node index.js

  При этом игра попросит выбрать орел или решка, надо будет ввести 1 или 2 соответсвенно.
  Если угадаете верно вас поздравят с победой, если не угадаете, вас так же об этом оповестят.
  После произойдет выход из игры.
  Результаты всех запусков игры записываются в файл log.txt.

+ 2 режим - отладочный, запускается с флагом log.txt

        > node index.js log.txt

  При запуске игры с данной командой выведется список о количестве сыгранных партий, количестве побед и проигрышей, их соотношении и количестве максимально идущих подряд выигрышей или проигрышей.

+ 3 режим - очистка, запускается с флагом -с или --clear

        > node index.js -c

  При этом файл будет очищен и можно будет собирать новую статистику о пройденных игр.

В новой версии добавлены дополнительные команды для запуска приложения:
+ Игра

        > npm run play

+ Просмотр статистики

        > npm run stat

+ Очистка статистики

        > npm run clear
