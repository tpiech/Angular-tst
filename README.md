# Angular-tst
Testing Angular framework for presentation 

WYMAGANIA: 

* Node.js v12 or higher (using 14.17.0)
* npm v6 (using 6.14.13)
* TypeScript (using 4.2.4)
* Angular CLI

Strona instalacji dla Node.js i npm (jednocześnie instaluje obydwa): https://nodejs.org/en/


KOMENDY:
* npm install -g @angular/cli - instaluje Angulara
* npm install -g typescript - instaluje TypeScript
* ng new my-first-project - generowanie projektu
* ng serve - odpala projekt i serwer na localhost:4200 (musi być w folderze aplikacji)
* ng g component ./ścieżka/folder_z_nazwa_komponentu - generowanie komponentu


WAŻNE PLIKI:
* app.component.html - strona projektu
* app.component.css - wygląd strony projektu
* package.json - biblioteki i zależności (lista)
* node.modules - biblioteki i zależności (miejsce pobrania)


NOTATKI:
* NIE RESTARTOWAĆ APKI PO WPROWADZENIU ZMIAN, SAMA ROBI UPDATE!
* odwołanie do zmiennej z klasy, w pliku html - {{zmienna}}
* deklaracja zmiennych zmienna: typ; (np. name: string;)
* jeśli przy stworzeniu jest przypisanie, nie trzeba podawać typu (np name = 'dzialaj_projekcie')
* do głównego pliku html dodajemy komponenty za pomocą selektora <nazwa_selektora></nazwa_selektora> (zdefiniowany w @component{ selector: 'nazwa_selektora'  })
