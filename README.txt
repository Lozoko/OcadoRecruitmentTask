Instrukcja uruchomienia:

java -jar OcadoRecruitmentProject-1.0-SNAPSHOT.jar grid.txt job.txt

Projekt napisany przy użyciu Javy w wersji 18.0.1
Wykorzystałem Apache Maven jako narzędzie do zbudowania projektu.


Opis projektu:
Do rozwiązania problemu z zadania wykorzystałem algorytm Dijkstry do znajdowania najkrótszych ścieżek w grafie. 
Algorytm ten pozwala na znalezienie najkrótszej ścieżki od miejsca początkowego do wszystkich innych dostępnych miejsc 
w grafie. Dzięki temu można wyznaczyć najkrótszą ścieżkę od robota do wszystkich egzemplarzy produktu z zadania dla bota. 
W taki sam sposób można wyznaczyć najkrótszą ścieżkę od stacji odbiorczej do wszystkich produktów. 
Po uzyskaniu tych częściowych ścieżek, należy je połączyć w jedną całą ścieżkę w taki sposób, żeby sumaryczny 
czas potrzebny do pokonania trasy (plus załadunek towaru) był jak najkrótszy 
