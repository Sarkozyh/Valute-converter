# Valute-converter
C# app for converting valutes

Конвертер валют

При загрузке формы программа скачивает json-файл с указанного в задании сайта, преобразует его в несколько объектов класса Valute 
и помещает их в один массив, откуда в дальнейшем будет браться информация о валютах.

После запуска появляется основное окно программы. Оно содержит два поля для ввода, куда необходимо ввести число единиц каждой из валют.
На ввод принимаются только символы, которыми могут записываться числа в формате double. Также окно содержит надписи,
показывающие какая из валют выбрана для каждого текстового поля и надписи, при нажатии на которые открывается окно выбора валют.

Окно выбора валют представляет собой listBox, куда при инициализации этого окна добавляются элементы, представляющие каждую из валют.
При нажатии на любую из них окно передаст индекс выбранной валюте на первое окно и закроется. В результате валюта на первом окне
поменяется на выбранную во втором окне.
