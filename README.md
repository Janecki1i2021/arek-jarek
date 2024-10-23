plik = open('liczby.txt', 'r')
liczby = plik.read().splitlines()
plik.close()

licznik_unikalnych = 0

for liczba in liczby:
    cyfry = str(liczba)
    if len(cyfry) == len(set(cyfry)):
        licznik_unikalnych += 1

print("Liczba liczb z unikalnymi cyframi:", licznik_unikalnych)
####################

plik = open('liczby.txt', 'r')
liczby = plik.read().splitlines()
plik.close()

licznik_palindromow = 0

for liczba in liczby:
    liczba_int = int(liczba)
    licznik_palindromow_w_systemach = 0
    
    for podstawa in range(2,9):
        liczba_system = ''
        temp_liczba = liczba_int
        
        while temp_liczba > 0:
            liczba_system = str(temp_liczba % system) + liczba_system
            temp_liczba //= system
        
        
        if liczba_system == liczba_system[::-1]:
            licznik_palindromow_w_systemach += 1

    if licznik_palindromow_w_systemach >= 2:
        licznik_palindromow += 1

print("Liczba liczb palindromicznych w przynajmniej dwóch systemach:", licznik_palindromow)
