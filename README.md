# service.subtitles.titlovi  
Unofficial Kodi subtitles addon for Titlovi.com v1.3.0  
System Requirements: Kodi v19 (matrix) or higher  

Prerađen oficijalni Titlovi.com addon v1.2.0...

Dodato:
- srpski jezik interfejsa
- prikaz logo-a
- izmene tektualno-vizuelne i u strukturi fajlova

Ispravke:
- pronalaženje titlova serija koje u imenu fajla imaju naziv epizode
- pronalaženje i prikaz i ćiriličnih titlova ukoliko je izabran srpski jezik
- pronalaženje sezonskih titlova (cela sezona u jednom fajlu, netflix), posledica toga je da za pojedinačne titlove izbacuje u prikazu sve titlove sezone umesto samo za datu epizodu
- omogućena i jednocifrena pretraga sezona i epizoda (dozvoljen format je 'S##E##', broj ## je ranga 0-99)
- sređena notifikacija/greška koja izlazi ukoliko ne nađe nikakav rezultat
- sređen prikaz svih notifikacija/grešaka
- izmenjen prikaz rezultata pretrage, radi lakšeg izbora titla:
	- ispis naziva serije/filma
	- dodata godina (naročito korisno kod filmova sa istim nazivom iz različitih godina)
	- sređen prikaz sezone/epizode
- sređeno sortiranje titlova iz zip fajla sezone, koji se randomizirao ukoliko je već skinut i čita se iz keša

Tip:  
Kada koristite ručno pretraživanje za TV serije koristite format za sezonu i epizodu kao u ovom primeru:  
  The Wire S01E01 ili The Wire S1E1  
Za precizniju ručnu pretragu umesto naziva filma/serije možete koristiti IMDb tag, na pr. tt1234567  
Za pretragu sezonskih titlova, kada su u jednom zip fajlu, koristite pored oznake sezone i format E0 ili E00 za epizodu  
Za pretragu titlova svih sezona u jednom fajlu koristite S0E0 ili S00E00  
