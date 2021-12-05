Usługa LAMP oparta na trzech komponentach składowych: 
* serwerze Apache v. 2.4.51 opartej na Alpine Linux (odpowiadającym za front-end i back-end)
* serwerze PHP (odpowiadającym za back-end)
* bazie danych MySQL (Model danych w Model-View-Controller)

Serwer Apache jest ustawiony na ekspozycję na porcie 6666:66.
Serwer PHP korzysta z obrazu php:7.3-rc-fpm-alpine, a serwer bazy danych działa na ostatniej
znanej wersji (latest). Dla serwera PHP i MySQL używane są domyślne porty.
