# clicker_2023_06_02
программа делает авто кликер куда вы наводите мышкой спомощью кнопки s это программа очень хорошая поэтому смотрите ещё мои программы и мои программы самые интересные заходите ещё.

Эта программа представляет собой автоматического кликера для мыши. Она использует библиотеку pynput для контроля мыши и клавиатуры.

В программе создается поток clicking_thread, который выполняет функцию clicker(). Эта функция в бесконечном цикле проверяет значение переменной clicking. Если clicking равно True, то функция выполняет клик левой кнопкой мыши с помощью mouse.click(Button.left, 1) и затем приостанавливается на 0.1 секунды с помощью time.sleep(0.1).

Функция toggel_event() вызывается при нажатии клавиши. Если нажатая клавиша совпадает с toggle_key, то переменная clicking меняет свое значение на противоположное.

Функция main() запускает поток clicking_thread и создает объект Listener, который слушает нажатия клавиш. Когда происходит нажатие, вызывается функция toggel_event(). Программа продолжает работу до тех пор, пока не будет нажата клавиша, указанная в toggle_key.

Таким образом, эта программа позволяет пользователю включать и выключать автоматическое кликание левой кнопкой мыши, нажимая определенную клавишу.
