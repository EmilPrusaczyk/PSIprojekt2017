Projekt został wykonany z pomocą NodeJS, ExpressJS oraz mongoDB. Aby uruchomić stronę należy zainstalować moduły nodejs
**npm install**
oraz uruchomić mongoDB
**mongo\mongod -dbpath database**
i uruchomić plik server.js.
**npm start**

Aplikacja składa się ze strony głównej, czyli galerii obrazków. Zarejestrowani użytkownicy mogą dodawać obrazki oraz je komentować. Niezalogowane osoby będą przekierowane do strony logowania. Administratorzy mogą usuwać obrazki.
Aby stworzyć konto administratora trzeba odwiedzić stronę **/createadmin**. Potem można zalogować się przy pomocy danych: login: admin, hasło: admin.
Administrator może przeglądać i usuwać użytkowników wchodząc w Profil > Lista użytkowników.
