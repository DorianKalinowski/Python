import random

proba = 0
liczba = random.randint(1, 100)

imie = input('Cześć :) Jestem komputerem, dlatego będę wdzięczny, jeśli podasz mi swoje imię lub pseudonim.\n Łatwiej będzie nam razem zagrać\n')
print ('Hej',imie,':-)')
wartosc = int(input('Wylosowałem liczbę od 1 do 100. Spróbuj trafić, będę podpowiadał.\n'))
if wartosc == liczba:
    print('Brawo, za pierwszym razem!')

while (wartosc != liczba):
    proba += 1
    print ('To był twój', proba, "strzał.")
    if wartosc > liczba:
        print(imie,", podpowiem że liczba jest mniejsza")
    else:
        print(imie,", podpowiem że liczba jest wieksza")
    wartosc = int(input('Podaj prosze liczbe od 1 do 100\n'))
print('\n Brawo',imie,':) Liczba została trafiona. Chodziło o' ,liczba,)
