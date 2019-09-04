Stwórz plik docker-compose, który uruchomi:
* `drupal` w wersji `latest` (odnajdz jaka jest teraz jest wersja latest i uzyj najkonkretniejszego taga), dostepnym na adresie `localhost:8071`, zaleznego od kontenera `mysql`, z healthcheck na glowna strone
* `mysqla`, w wersji wymaganej przez wordpressa, z volumenem dockerowym na dane bazy danych, z healthcheckiem na działanie mysqla, z baza danych `CUKIERNIA`, uzytkownikiem `ponczek` i jakims haslem
* `phpmyadmina`, ktory bedzie laczyl sie do powyzszej bazy danych, dostepnym na adresie `localhost:8081`, zaleznego od kontenera mysql

Uruchom swój stack aplikacyjny
Sprawdz jakie sieci zostały stworzone
Sprawdz jakie volumenty zostaly stworzone
Sprawdz ile i jakie kontenery się uruchomiły