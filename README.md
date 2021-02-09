# Code coloring
Практическое задание № 2, вариант:  
В первом - программа работает так же, как на первом этапе. Во втором режиме программа должна взять из командной строки указание типа токена и распечатать в лексикографическом порядке все токены этого типа из входного файла с указанием номера строки и номера позиции каждого вхождения этого токена.

На вход программе подается файл с кодом программы на языке Си. Имя входного файла должно быть указано как параметр при запуске программы.
Параметры запуска: сначала файл, затем режим: 0 - как обычно, 1 - с сортировкой, затем указывается тип токена по которому будет идти сортировка для режима 1(в случае, если режим 0, то второй параметр может быть любым целым числом). 

Приведены соответствия номеров с типами токенов:

ЦВЕТ     НОМЕР   СООТВЕТСТВИЕ
CLASSIC = 0, // unknown tokens 
YELLOW = 1, // keywords
ORANGE = 2, // identifiers
RED = 3, // real constants
BLUE = 4, // literal
MAGENTA = 5, // operations
GREEN = 6 // comment

Вывод программы производится в стандартный поток вывода.
Требования варианта - 
Все ключевые слова из второго столбца - Жёлтый
Все виды идентификаторов - Оранжевый (немного сливается с жёлтым)
Все виды вещественных констант - Красный
Все виды строковых литералов - Синий
Знаки операций из 3-й, 5-й и 7-й строки - Розовый (изменён на пурпурный)
Все виды комменариев - Зеленый
