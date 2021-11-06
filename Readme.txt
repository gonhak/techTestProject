W tym pliku postaram się po krotce opisać, dlaczego i po co wykorzystuje te wszystkie NARZĘDZIA do tworzenia stron internetowych.

Użyte NARZĘDZIA:
1 - npm
2 - node
3 - gulp
4 - buble
5 - sass/scss
6 - minifikatory
7 - kity
8 - github

Osobiście, aby streścić wam, dlaczego zdecydowałem się do wykorzystywania podanych wyżej narzędzi ułatwiających tworzenie stron
internetowych mógłbym przytoczyć pewne zjawisko występujące u nas w życiu codzinnym jest nim nic innego jak wykorzystywanie
powrzechnych nam narzędzi. Jak dobrze wiemy, jeśli będziemy musieli coś wywiercić użyjemy wiertarki jeśli zaparzyć wodę użyjemy
czajnika a nie tostera. W przypadku tworzenia stron internetowych sytuacja jest identyczna. Jak można zauważyć ten projekt nie
wymagał jak i nigdy nie będzie wymagał tylu wykorzystanych narzędzi. Zrobiłem to głównie dlatego, aby zademonstrować ich działanie.
Biorąc na przykład wcześniej wymienionego gulp'a odpowiada on za to, aby stworzyć nam live server naszego projektu, jak i umożliwia
on zamienię naszego routera w mini server, który będzie umożliwiaj notowanie jak i zmienianie rzeczy na naszej stronie. Live server
wykonany przez gulp'a będzie widoczny, jak i w pełni funkcjonalny dla każdej osoby znajdującej się w naszej sieci domowej. Wymieniłem
wcześniej równierz pojęcie, jakim jest minifikacja naszego kodu. Pojęcie minifikacji ułatwia przeglądarce czytanie naszego kodu, czyli usuwa ono każde znaki białe, które dla przeglądarki są bezużyteczne. Dzięki temu zabiegowi pliki naszej strony automatycznie
są minifikowane przez co nie musimy się potem o to martwić. Aby wykorzystać pełną moc narzędzia, jakim jest gulp w połączeniu z
node'm, jak i npm'em musimy utworzyć standardową strukturę naszego projektu, która jest indywidualna dla każdego programisty ze
względu na to, że każda pojedyncza osoba może posiadać inaczej skonfigurowany plik gulp'a, jak i package.json wykorzystywany do
informowania npm'a, jakich jego wtyczek będziemy używać. W moim przypadku posiadam w swojej konfiguracji minifaktory kodu, które
optymalizują kod dla przeglądarki, live server, abym był w stanie oglądać stronę nie tylko na komputerze, lecz także telefonie, który jest podpięty do tej samej sieci. Moja konfiguracja zawiera również optymalizator zdjęć, którego zadaniem jest zmniejszanie
ich wielkości co skutkuje później szybszym ładowaniem się strony dla naszego użytkownika co jest bardzo ważne gdyż każda sekunda
wczytywania się strony jest na wagę złota. Cały ten projekt znajduje się również w repozytorium udostępnionym na github'ie, czyli
niczym innym jak kontrolerem wersji. Służy on głównie do przechowywania zdalnego naszych projektów jak i ułatwia on pracę w zespole
co w przypadku programistów jest naprawdę częstym zabiegiem. Warto też zapamiętać to, że każde użycie narzędzia, które tutaj wymieniłem
jest u nas lokalnie czyli w tym przypadku nie wrzucamy każdego pojedyńczego pliku na serwer lecz tylko i wyłącznie te obrobione, które
są również plikami finalnymi. Ten zabieg łatwo jest zauważyć przy linkowaniu styli css, czyli gulp prze konwertował plik z rozszerzeniem
scss (używamy tego formatu, ponieważ jest on bardziej czytelny dla innego programisty, jak i łatwiej się w nim orientować) oraz automatycznie
go zminifikował i umieścił wynik tego zabiegu w specjalnym wytyczonym w konfiguracji folderze pod nazwą dist/css. Chciałbym również
poprosić o zrozumienie ze względu na to, że każde pojedyncze zagadnienie użyte w tej ala dokumentacji zostało jak najbardziej uproszczone
co łatwo jest zauważyć po tym że do każdego z tych zagadnien istnieją kursy które potrafią trwać po 24 godziny wykładów przez co opisanie
ich w formie takiej aby była ona zrozumiała jak i przystępna dla każdego jest strasznie trudna w razie pytań zapraszam do kontaktu
natanek291@gmail.com