# HTTP/2 vs HTTP/1.x - Demonstracija performansi
## Opis projekta
Ovaj projekt ima za cilj demonstrirati prednosti protokola HTTP/2 u odnosu na HTTP/1.x na primjeru vlastite web stranice. Cilj je pokazati kako HTTP/2 omogućava brži prijenos resursa (slike, CSS, JS datoteke) zahvaljujući mehanizmima kao što su server push i binarno komprimiranje podataka.

## Prvi dio: Instalacija i konfiguracija
- Instaliraj web poslužitelj nginx na Windows.
- Kreiraj vlastiti SSL certifikat.
- Aktiviraj HTTPS/SSL protokol na serveru.
- Konfiguriraj HTTP/2 podršku u nginx konfiguraciji.
- Aktiviraj HTTP/2 protokol i potvrdi njegovu aktivaciju.

## Referencijalni resursi:
- Nginx dokumentacija
- Nginx SSL konfiguracija
- Omogućavanje HTTP/2 na nginx-u

## Drugi dio: Web stranica i testiranje
- Razvijanje vlastite web stranice s HTML sadržajem, CSS datotekama, JS datotekama
- Testirati performanse stranice za HTTP/2 protokol, HTTP/1.x protokol

## Generirati:
- Screenshotove konzole preglednika (http2.jpg i no_http2.jpg)
- Dvije HAR datoteke: no_http2.har – bez HTTP/2 podrške, http2.har – sa HTTP/2 podrškom

## Cilj projekta
- Prikazati kako HTTP/2 optimizira prijenos sadržaja na web stranici.
- Prikupiti HAR datoteke i screenshotove kao dokaze o performansama.
- Validirati zahtjeve kroz logiranje i analizu.
- 
## Tehnologije
- Nginx – web poslužitelj
- OpenSSL – za generiranje SSL certifikata
- Google Developer Tools – za analizu HAR datoteka
- Windows OS – platforma za testiranje
