jsfuck cheat sheet
================================

Basic values
----------------------------------------
- ``undefined`` > ``[][[]]``
- ``false`` > ``![]``
- ``true`` > ``!![]``
- ``NaN`` > ``+[![]]``
- ``0`` > ``+[]``
- ``1`` > ``+!+[]``
- ``2`` > ``!+[]+!+[]``

Basic strings
----------------------------------------
- ``''`` > ``[]+[]``
- ``'undefined'`` > ``[]+[][[]]``
- ``'false'`` > ``[]+![]``
- ``'true'`` > ``[]+!![]``
- ``'NaN'`` > ``[]+(+[![]])``
- ``'0'`` > ``[]+(+[])``
- ``'1'`` > ``[]+(+!+[])``
- ``'2'`` > ``[]+(!+[]+!+[])``
- ``'10'`` > ``[+!+[]]+[+[]]``
- ``'11'`` > ``[+!+[]]+[+!+[]]``
- ``'100'`` > ``[+!+[]]+[+[]]+(+[])``

Higher numbers
----------------------------------------

- ``10`` > ``+([+!+[]]+[+[]])``
- ``11`` > ``+([+!+[]]+[+!+[]])``
- ``100`` > ``+([+!+[]]+[+[]]+(+[]))``

String alphabet
----------------------------------------
- ``'a'`` > ``([]+![])[+!+[]]``
- ``'d'`` > ``([]+[][[]])[+!+[]+!+[]]``
- ``'e'`` > ``([]+!+[])[+!+[]+!+[]+!+[]]``
- ``'f'`` > ``([]+![])[+[]]``
- ``'i'`` > ``([]+[][[]])[+!+[]+!+[]+!+[]+!+[]+!+[]]``
- ``'l'`` > ``([]+![])[+!+[]+!+[]]``
- ``'n'`` > ``([]+[][[]])[+!+[]]``
- ``'r'`` > ``([]+!+[])[+!+[]]``
- ``'s'`` > ``([]+![])[+!+[]+!+[]+!+[]]``
- ``'t'`` > ``([]+!+[])[+[]]``
- ``'u'`` > ``([]+!+[])[+!+[]+!+[]]``
