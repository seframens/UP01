LR13

5.1 Разработать приложение, позволяющее считывать и модифицировать
информацию в xml-файле, используя пакет xml.
5.2 Разработать приложение, позволяющее создавать и модифицировать wavфайл, используя модуль wave.
5.3 Разработать приложение, позволяющее считывать и модифицировать
информацию в таблицах базы данных SQLite, используя DB API.



LR14

5.1 Создать оконное приложение «Форма авторизации» с однострочными
полями Логин, Пароль, флажком «Запомнить пароль», подписями и кнопкой
Авторизоваться. Настроить размер формы 200х300 и заголовок окна.
5.2 Создать оконное приложение «Форма регистрации» со следующими
элементами и подписями:
- однострочные поля Логин, Пароль,
- многострочное поле О себе,
- переключатели для указания пола,
- список из пяти пунктов для выбора материка,
- кнопка Зарегистрироваться. 
Настроить цвет фона формы и элементов управления и заголовок окна.
5.3 Создать оконное приложение, в котором связать виджеты поле ввода,
флажок, переключатель с ассоциированными переменными-объектами (IntVar,
StringVar и т.д.) и, используя textvariable, определить текст-содержимое или текстнадпись виджетов. Написать скрипт, в котором значения ассоциированных
переменных должны отображаться в метке через запятую.
5.4 Создать приложение с меню, содержащим два пункта: Color и Size. Пункт
Color должен содержать три команды (Red, Green и Blue), меняющие цвет рамки на
главном окне. Пункт Size должен содержать две команды (500x500 и 700х400), изменяющие размер рамки. Привязать к пунктам меню «горячие клавиши» и
выполнение функций.




LR15

5.1 Написать оконное приложение, в которое добавить многострочное поле
ввода и кнопку Сохранить. При нажатии на кнопку или клавиши Ctrl-S должно
происходить открытие окна, позволяющего сохранить текст в файл. При нажатии
Esc форма должна закрываться.
5.2 Написать оконное приложение с тремя полями ввода. При нажатии на любое
из полей ввода левой кнопкой мыши в метку на форме должно выводиться название
активного поля ввода, при нажатии правой – в консоль. Для реализации подписки на
событие использовать root.bind_class.
5.3 Написать оконное приложение, на котором разместить метку с подписью
«Координаты мыши». При движении мыши выводить в метку координаты х и у
мыши (для этого в обработчике движения мыши есть свойства event.x, event.y).
5.4 Написать оконное приложение, на котором разместить метку с подписью
«Нажатые клавиши». При нажатии любой из клавиш добавлять в метку последний
нажатый символ (для этого в обработчике Key есть свойства event.char)
