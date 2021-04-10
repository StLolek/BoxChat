# BOXCHAT

Cały czat będzie startowany lokalnie z wykorzystaniem kontenerów docker/docker-compose.

## Plan:

### Sprint 1

#### Stworzenie czatu:

[x] Stworzony w środowisku Node.JS
[x] Utworzenie kontenerów w docker/docker-compose
[x] W tej fazie będzie najprostszą wersją naszego czatu z podziałem na podkanały

#### Logowanie/Konta

[ ] Z czatu będzie można korzystać przy pomocy prostego konta (przypisany nick do którego można dostać się tylko przy pomocy hasła, z możliwością odzyskania hasła jeśli podasz mail), bądź logować się "jednorazowo" poprzez wpisanie nicku oraz przepisanie kodu captcha (dla zabezpieczenia przed botami). Drugi sposób jest "gorszy" pod tym względem, że Twój nick będzie dostępny dla każdego.
[ ] Stworzenie mailera do odzyskiwania hasła.
[ ] Zrobienie Captchy przy wchodzeniu przez "gościa"
[ ] Dane do logowania będą trzymane w bazie MySQL

### Sprint 2

#### Dodanie możliwości pisania wiadomości prywatnych

#### Dodanie czatu z przypadkowymi osobami

#### (?)Dodanie możliwości tworzenia własnych pokoi

- Pokój będzie utrzymywany dopóki na kanale będzie co najmniej 1 osoba, w momencie w którym ostatnia osoba wyjdzie z pokoju, czat zniknie
- Pokój będzie mógł być zabezpieczony poprzez hasło (hasło będzie trzymane jako zmienna na serwerze, przypisana do pokoju)

#### (?) Dodanie możliwości administrowania

- możliwość zgłoszenia wiadomości do administratora który będzie miał trzy opcje przy każdym zgłoszeniu - wyrzuć, zbanuj, zostaw

### Sprint 3

#### Dodanie obsługi języków

- Dodanie opcji wyboru języka w którym wszystkie wiadomości będą wyświetlane
- Do pokoi będzie dodana opcja ustawienia języka w którym będą musiały być pisane wszystkie wiadomości

#### Dodanie preferencji wyszukiwania do czatu z przypadkowymi osobami

#### Dodanie listy znajomych

### Sprint 4

#### Dodanie do czatu obsługi speech to text oraz text to speech

- Do napisania wiadomości będzie można użyć swojego głosu
- Możliwość włączenia czytania każdej otrzymanej wiadomości (tylko na czacie prywatnym/na czacie do o kreślonej[bardzo małej] ilości osób)

##### (?) - jest to opcjonalne/niepewne czy będziemy wiedzieć jak to zrobić
