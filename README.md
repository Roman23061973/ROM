написать программу, кокоторая из мфссива мфссива строк формирует новый мвссивиз строк, длина которых ментше либо равна 3символам.первоначальный массив можно ввести с помощью кочбинации,либо нажать на начало выполнения алгоритма. не рекомендуется использовать коллекции, лучше всего собирать уникальные массивы.
алгоритм:
В функции входит начальный массив строк. первым делом возникаетпромежуточный массив иакого же размера, что и изначального, и индекс  = 0. Затемв цикле каждой строки возникает массив, возникает состояние - размер меньше или равен 3 символов. если состояние стойкое,закономерность заменяется в промежуточном массиве,индексувеличивается на 1.После выполнения цикла, возникает результирующийразмер массивного массива индекса. В него копируются ненулевыеэлементы промежуточного массива (до индекса). Функция ыозвращает массивы с обработанными значениями.