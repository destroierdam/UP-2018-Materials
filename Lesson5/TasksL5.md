# Задачи

## Сума на числа

Програмата трябва да прочита цели числа докато не срещне нула и да изведе сумата им.

**Пример:**

Вход: 5 2 1 3 6 4 0

Изход: 21

## Четни цифри (evenDig)
По дадено цяло число N определете колко четни цифри има то.

**Примери:**

Вход: 123

Изход: 1

Вход: 0

Изход: 1

## Вариации (vars)

По дадени n и k - естествени числа, пресметнете броя вариации на n елемента k-ти клас. Пресмята се по формулата n!/(n-k)!.

**Примери:**

Вход: 12 5

Изход: 95040

Вход: 0 15

Изход: 0

Вход: 0 0

Изход: 1

## Комбинации (nchoosek)

Напишете програма, която по дадени n и k - естествени числа, намира броя комбинации от n елемента k-ти клас. Пресмята се по формулата n!/(k! * (n-k)!).

**Примери:**

Вход: 10 7

Изход: 120

Вход: 5 5

Изход: 1

## Таблица за умножение (multTable)

Напишете програма, която по дадено естествено число N принтира таблицата за умножение до N.

**Пример:**

Вход: 10

Изход:

	1		2       3       4       5       6       7       8       9       10
	2       4       6       8       10      12      14      16      18      20
	3       6       9       12      15      18      21      24      27      30
	4       8       12      16      20      24      28      32      36      40
	5       10      15      20      25      30      35      40      45      50
	6       12      18      24      30      36      42      48      54      60
	7       14      21      28      35      42      49      56      63      70
	8       16      24      32      40      48      56      64      72      80
	9       18      27      36      45      54      63      72      81      90
	10      20      30      40      50      60      70      80      90      100

## Съкратена таблица за умножение в "долнотриъгълен вид" (multTableLower)

Напишете програма, която по дадено естествено число N принтира съкратена таблица за умножение в "долноотриъгълен вид" до N.

**Пример:**

Вход: 

	10

Изход:

	1
	2       4
	3       6       9
	4       8       12      16
	5       10      15      20      25
	6       12      18      24      30      36
	7       14      21      28      35      42      49
	8       16      24      32      40      48      56      64
	9       18      27      36      45      54      63      72      81
	10      20      30      40      50      60      70      80      90      100
	

## Съкратена таблица за умножение в "горнотриъгълен вид" (multTableUpper)

Напишете програма, която по дадено естествено число N принтира съкратена таблица за умножение в "горнотриъгълен вид" до N.

**Пример:**

Вход: 

	10

Изход:

	1       2       3       4       5       6       7       8       9       10
       		4       6       8       10      12      14      16      18      20
                	9       12      15      18      21      24      27      30
                        	16      20      24      28      32      36      40
                                	25      30      35      40      45      50
                                        	36      42      48      54      60
                                                	49      56      63      70
                                                       		64      72      80
                                                                	81      90
                                                                        	100

## Трайчо смята стипендия (scolarship)

Сесията е приключила и Трайчо се чуди дали ще вземе стипендия. За да кандидатства за стипендия той трябва да има минимум 4.50 средна оценка и да не е скъсан по нито един предмет, т. е. да няма нито една двойка.

Напишете програма, която по дадени оценки проверява дали Трайчо може да кандидатства за стипендия.

**Вход:** Първото число N показва колко оценки има Трайчо. Следват N реда - оценките на Трайчо (реално число).

**Изход:** Програмата трябва да изведе дали Трайчо може да кандидатства за стипендия.

**Примери:**

Вход: 

5 

4 5 6 3 4

Изход: YES

Вход:

6

6 5 3 3 2 4

Изход: NO

Вход:

5

3 3 3 4 6

Изход: NO