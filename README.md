plik = open('liczby.txt', 'r')
liczby = plik.read().splitlines()
plik.close()

licznik_unikalnych = 0

for liczba in liczby:
    cyfry = str(liczba)
    if len(cyfry) == len(set(cyfry)):
        licznik_unikalnych += 1

print("Liczba liczb z unikalnymi cyframi:", licznik_unikalnych)
