# Zadatak

## 1.	Library Carpentry
Library Carpentry bavi se razvojem lekcija i radionica za osobe koje rade u knjižničnom i informacijskom okruženju. Cilj Library Carpentry-a je stvoriti poveznicu za osnaživanje tog okruženja kako bi se mogli koristiti softveri i podaci u vlastitom radu, kao i zagovaranje i osposobljavanje drugih za učinkovite, djelotvorne i ponovljive prakse podataka i softvera. 
Lekcije koje nude Library Cerpentry dijele se na osnovni kurikulum te na prošireni kurikulum. Lekcije koje spadaju u osnovni kurikulum su: uvod u podatke, UNIX ljuska, OpenRefine te uvod u Git. U prošireni kurikulum, s druge strane spadaju: uredni podaci, SQL, Web scraping, uvod u Phyton te uvod u podatke za arhiviste

## 2.	Data Carpentry

Data Carpentry olakšava i razvija lekcije za svoje radionice. Lekcije se distribuiraju pod CC-BY livenvom i slobodne su za ponovnu uporabu ili prilagodbu, uz atribuciju. Radionice su specifične za domenu, tako da istraživače podučavaju vještinama koje su najrelevantnije za njihovu domenu, koristeći primjere iz takve vrste posla. Stoga postoji nekoliko vrsta radionica, a kurikulum je organiziran po domenama.
Radionice: Kurikulum za ekologiju, Genomički kurikulum, Kurikulum društvenih znanosti, Nastavni plan i program za geoprostorne podatke. Materijali za radionice koji su u razvoju ili se razmatraju: Kurikulum za digitalne humanistike, Kurikulum za analizu slike, Nastavni program ekonomije, Nastavni plan i program za astronomiju. Također se nude materijali za cijeli semestar iz biologije, te materijali koje su pridonijeli članovi zajednice. 

## 3.	Software Carpentry

Software Carpentry od 1998. godine podučava polaznike tečajeva računalnim vještinama koje su im potrebne da bi se postiglo više, u manje vremena i s manje napora. Svim materijalima se može slobodno pristupiti i koristiti ih pod licencom Creative Commons – Attribution. 
Lekcije koje nude podijeljene su na engleski i španjolski jezik i u sekciju dodatne lekcije. Lekcije se odnose na rad s Unix ljuskom, Phytonom, Git-om i sl.

## 4.	Lekcije povezane s informacijskim djelatnostima

Lekcije programa Library Carpentry koje se vežu uz informacijske i knjižnične djelatnosti su lekcije: uvod u podatke, UNIX ljuska, OpenRefine, GitHub, uredni podaci, SQL, Web scraping te Phyton.

###### 4.1.	Uvod u podatke

Kao što Andromeda Yelton navodi u svome radu *Kodiranje za knjižničare: učenje pomoću primjera* 
>kod je knjižničarima način da preuzmu kontrolu nad praksom i da osnaže sebe i svoju organizaciju kako bi zadovoljili potrebe korisnika na fleksibilan način.

S druge strane, knjižničari igraju ključnu ulogu u kultiviranju istraživanja na svjetskoj razini. U većini područja, istraživanja se oslanjaju na korištenje softvera. Upravo zbog toga, knjižničari koji su ovladali softverskim vještinama imaju dobru poziciju da nastave s kultiviranjem istraživanja na svjetskoj razini.  
Strukturiranjem podataka, oni se mogu učiniti računalno čitljivima i time mogu pospješiti bolje pretraživanje i razmjenjivanje podataka u knjižničnoj/informacijskoj zajednici i struci.

###### 4.2.	UNIX ljuska

UNIX ljuska, ili samo ljuska program je koji omogućuje interakciju s računalom pomoću tipkanih tekstualnih naredbi. To je primarno sučelje koje se koristi na Linux i Unix sustavima, kao što je MacOS, te se može dodatno instalirati na druge operativne sustave kao što je Windows. Shell (ljuska) je zapravo primjer „sučelja komandne linije“, gdje se upute daju računalu upisivanjem naredbi, bez korištenja miša, a računalo odgovara izvršavanjem zadatka ili generiranjem outputa. Ovaj output je često usmjeren na zaslon, ali može biti usmjeren na datoteku, ili čak druge naredbe, stvarajući tako snažne lance djelovanja s vrlo malo truda. 
Korištenje ljuske odvija se kroz upisivanje naredbi koje su jezgrovite (često se sastoje od samo nekoliko znakova), njihova imena mogu biti zagonetna a rezultat je redak teksta a ne vizualni prikaz. No ipak, sa samo nekoliko naredbi, ljuska omogućava kombiniranje postojećih alata u moćne cjevovode i automatsko rukovanje velikim količinama podataka. 
Ovakva automatizacija korisnika može učiniti vrlo produktivnim, a radnim tijekovima poboljšava reproduktivnost omogućujući njihovo spremanje i ponavljanje u bilo kojem trenutku. Razumijevanje ljuske pruža vrlo koristan temelj za učenje i razumijevanje programiranja budući da se tako nauče koncepti poput petlje, vrijednosti i varijable.
Koristi od ljuske koje se mogu upotrijebiti u struci knjižničara i informacijskog stručnjaka su brojne, s obzirom na to da ne postoji ograničenje u zadacima koji se mogu obaviti u ljusci. Ljuska omogućava navigaciju kroz direktorije, komuniciranje s datotekama u naredbenom retku: čitanje, otvaranje, pokretanje i uređivanje; i kopiranje, premještanje i kombiniranje više datoteka. Pomoću funkcije petlje u ljusci se može poboljšati produktivnost i brzina obavljanja zadatka jer tako izvršavamo naredbe koje se ponavljaju. Podaci se mogu brojati i rudirati, takve naredbe mogu poslužiti knjižničnoj struci jer oponašaju vrste bibliotečnih podataka koje korisnici knjižnica mogu koristiti. Unix ljuska također može poslužiti za brzo prebrojavanje datoteka ili generiranje brojeva iz svih datoteka što može biti vrlo korisno. Ukratko, neki knjižnični podaci, osobito digitalizirani dokumenti, mnogo su „neuredniji“ od tabličnih metapodataka. Upravo se zbog toga, sortiranjem, prebrojavanjem, čitanjem i uređivanjem takvih podataka na brz i jednostavan način, uz pomoć Unix ljuske, može postići mnogo uz minimalan napor.

###### 4.3. OpenRefine

OpenRefine služi se jednom od vrlo korisnih značajki koja uvelike olakšava preglednost podataka u projektu, a to su fasete. Pomoću njih, vrlo je jednostavno filtrirati podatke i uvesti dosljednost u podatke. Uz filtriranje fasetama, OpenRefine nudi mogućnost filtriranja teksta pomoću kojeg se mogu pretražiti određeni dijelovi teksta u stupcu. Pored tekstualnih, OpenRefine pruža mogućnost filtriranja brojčanih faseta, faseta vremenske linije (za datume), prilagođene aspekte te fasetne raspone. Nadalje, funkcija klastera grupira slične, ali nekonzistentne vrijednosti u danom stupcu i omogućuje spajanje tih nekonzistentnih vrijednosti u jednu vrijednost koja se odabere. Ovo je vrlo učinkovito kada se radi o podacima s manjim varijacijama u vrijednostima podataka, npr. imena ljudi, organizacije, mjesta, pojmovi klasifikacije. Nakon fasetiranja, filtriranja i klastera svi podaci se mogu transformirati na način da im se daju zajedničke vrijednosti, čak i za one podatke koje je teže transformirati (adrese, micanje interpunkcija i sl.). Jedna od naprednih i vrlo korisnih značajki koju nudi OpenRefine je dohvaćanje podataka iz URL-ova. Ovo se može koristiti na različite načine, uključujući traženje dodatnih informacija iz udaljene usluge, na temelju informacija u postojećim OpenRefine podacima. Primjerice, mogu se potražiti imena prema Virtualnoj međunarodnoj datoteci ovlasti (VIAF) i dohvatiti dodatne informacije kao što su datumi rođenja / smrti i identifikatori.
Prema navedenom, vrlo je lako zaključiti kako je OpenRefine jedan od vrlo korisnih alata koji se može koristiti u knjižničnoj zajednici i struci informacijskih znanosti. Upravljanje raznim *prljavim* podacima vrlo je često, a sama struka zahtjeva čišćenje, filtriranje, fasetiranje i klasteriranje takvih podataka, kao i dohvaćanje raznih podataka koji se vežu na postojeće.

###### 4.4.	GitHub

Postoje određene razlike između Git-a i GitHub-a. Git je besplatan alat otvorenog koda preko kojega se mogu bilježiti sve promjene koje su napravljene u grupi određenih računalnih datoteka. Može se koristiti za lokalno upravljanje verzijama datoteka na vlastitom računalu, ali je najsnažniji kada se koristi za koordinaciju istovremenog rada na grupi datoteka koje se dijele među distribuiranim skupinama ljudi.
S druge strane, GitHub je popularna web-lokacija za udaljeno hostanje i dijeljenje Git repozitorija. Ona nudi web sučelje i pruža funkcionalnost usluge za rad s takvim repozitorijima. Najviše se koristi za projekte poput časopisa otvorenog pristupa, blogova i konstantno ažuriranih udžbenika.
Korist GitHub-a za knjižnice je značajna s obzirom na to da omogućava stvaranje mnogih projekata s otvorenim licencama i dopušta bilo kojem korisniku da razdvoji svaki javni projekt. Klikom na gumb „fork“, bilo koji GitHub korisnik može gotovo trenutno stvoriti vlastitu verziju postojećeg projekta i takav projekt se može koristiti kao osnova za novi projekt, ili za izradu novih značajki koje se mogu stvoriti natrag u izvornik. Na ovaj način, knjižnica ima mogućnost javnog dijeljenja npr. Fotografija i naknadnog uređivanja ili stvaranja novih projekata na osnovu prvog. Nadalje, uz mogućnost praćenja promjena i rješavanja sukoba u projektu, GitHub se može koristiti za hostanje projekata kako bi korisnici mogli surađivati i pregledavati promjene. Ova funkcija je od velikog značaja jer tako se omogućuje grupi ljudi da na jednostavan način uspješno rade na istom projektu.

###### 4.5.	Uredni podaci

Pojam uredni podaci odnosi se na podatke ili unos podataka u proračunske tablice na adekvatan način. To uključuje: unos podataka, organiziranje podataka, podrezivanje i razvrstavanje podataka, statistiku, pregled proračunske tablice te planiranje. 
Znanje adekvatnog unosa i korištenja samih podataka vrlo je važno u knjižničarskoj zajednici i struci informacijskih znanosti jer se u ovakvim zanimanjima često dolazi do potrebe za unošenjem podataka u tablice, ali i organiziranju samih podataka. Proračunske tablice također mogu poslužiti struci za izradu podataka za publikacije, za generiranje sažetih statistika i izradu procjena. 

###### 4.6.	SQL

SQL (*Structured Query Language*) jezik je koji se koristi za ispitivanje i upravljanje relacijskim bazama podataka. Ovo nije opći programski jezik za pisanje cijelog programa, već se s njime mogu pozvati upiti iz programskih jezika da bi bilo koji program mogao raditi s bazama podataka. Pomoću SQL-a podaci se mogu držati odvojenima od analize, nema rizika od slučajnog mijenjanja podataka kada se vrši analiza. Ako se kojim slučajem podaci promijene, spremljeni upit se može ponovno pokrenuti kako bi se analizirali novi podaci. SQL je optimiziran za rukovanje velikim količinama podataka, što znači da će program dignuti pogrešku u slučaju da se u mjesto predviđeno za broj pokuša unijeti tekst. Na ovaj se način uvelike olakšava baratanje s velikim brojem podataka i pospješuje razumijevanje grešaka. 
Knjižničarstvo, koje se odnosi na upravljanje informacijama može imati velike koristi od SQL-a jer SQL pomaže pri sortiranju i organiziranju informacija te pomaže ljudima da pronađu informacije. Sa SQL-om se može izravno konstruirati upit baze podataka bez ograničenja, a sam SQL je idealan za pretraživanje baza podataka. Konstruiranje upita pomoću SQL-a je jednostavno te predstavlja drugačiji i izravniji način pronalaženja informacija što će svakako koristiti knjižničarima.

###### 4.7.	Web scraping

Web scraping je proces automatizacije izdvajanja podataka s web stranica. Web scraping omogućuje pretvorbu ne-tabličnih ili loše strukturiranih podataka u upotrebljiv i strukturiran format, kao što je csv. datoteka ili proračunska tablica. Pomaže i da se dobiju podaci koji su nedostupni načinom na koji su prikazani na mreži. Web scraping je više od samog prikupljanja podataka, može pomoći u praćenju promjena podataka na mreži i pomoću arhiviranju podataka. 
Za razliku od Google-a koji analizira cijele stranice za svoje indekse, Web scraping cilja samo određene informacije na posjećenim stranicama što omogućava lakše i efikasnije pretraživanje. Kao takav, sve se više koristi za stvaranje skupova podataka za projekte rudarenja teksta kao npr. za zbirke članaka u časopisima ili digitaliziranim tekstovima. 
Web scraping može se obavljati putem raznih programa i alata. Neki od njih su Phyton, Scrapy, Scraper Chrome extension, Xpath.
Prema navedenom, može se zaključiti kako Web scraping ima veliku ulogu u pretraživanju informacija i brzom dolasku do rezultata što je glavni zadatak kojeg ispunjava informacijski stručnjak i knjižničar. 

###### 4.8.	Phyton

Phyton je jedan od poznatijih programskih jezika, te je on programski jezik opće namjene. Za knjižničare i informacijske stručnjake je od iznimne važnosti jer poznavanjem programiranja, knjižničar i informacijski stručnjak na jednostavan način mogu pridonijeti razvoju i radu knjižnice tako da razvijaju programe knjižnice, rade aplikacije ili nadziru programiranje knjižničnog sustava. Od velike je koristi i kod organiziranja podataka.
