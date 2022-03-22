# Inicijalne upute za izradu zadaća
Poštovane kolegice i kolege, 

čestitamo vam jer ste uspješno kreirali **repozitorij** koji ćete koristiti za pišanje vaših zadaća, što će uključivati izradu dokumentacije ali i programskog koda.

Molim vas izmijenite ovaj dokument kako bi u njega naveli naziv i kratak opisa projekta koji obrađujete u vašim zadaćama, kao i vaše osobne podatke. Za upute o sintaksi koju možete koristiti u ovom dokumentu i kod pisanje vaše projektne dokumentacije pogledajte [ovaj link](https://guides.github.com/features/mastering-markdown/) ali i upute o sintaksi koji će uskoro biti dostupan na Moodle-u. 

A sada, vrijeme je da malo izmijenite ovaj dokument. Za upis/opis vašeg programskog proizvoda molimo vas koristite **predložak** koji je naveden u nastavku, a započnite tako da kliknete na *olovku* u desnom gornjem kutu ovoga dokumenta, te izbrišite sve što je iznad Naziva projekta, kao i sve upute koje su navedene u zagradama u predlošku ispod :) 

# Softver za praćenje analize uzoraka krvi i urina u mikrobiološkom laboratoriju


## Podaci o studentu


Ime i prezime     |  E-mail adresa (FOI) |    JMBAG    | Github korisničko ime
----------------  |  ------------------  | ----------- | ---------------------
Vilim Trakoštanec |  vtrakosta20@foi.hr  | 0016150912  |      vtrakosta20


## Opis domene
U trenutnom načinu rada radnici u mikrobiološkom laboratoriju za obavljanje svog rada koriste papirnati radni nalog koji moraju ručno ispunjavati. Također nemaju sofisticirani način praćenja uzoraka kako bi se znalo u kojoj se fazi obrade nalazi uzorak. 
Ovo programsko rješenje će riješiti problem papirnatog radnog naloga potpunom digitalizacijom, također će omogućiti djelomično automatsko unošenje podataka iz strojeva za analizu, u digitalni radni nalog, a dio bi se unosio ručno, također treba postojati mogućnost  davanja komentara za svaki dio naloga sve dok je otvoren. Problem praćenja uzoraka riješio bi se pomoću QR ili bar kodova kojima bi se uzorci označili pri ulasku u laboratorij, a također unutar sustava dodijelili pacijentu. Radni nalog, bez obzira je li otvoren ili zatvoren mora se moći pronaći unutar sustava pretragom po svim mogućim kriterijima, a ako je nalog otvoren treba biti prikazano u kojoj je fazi obrade. Za svakog pacijenta sustav mora pokazati povijest analiza. Radni nalog bi zaključavao specijalist koji bi ga po završetku obrade pregledao uz moguće dodavanje komentara. Sustav mora prepoznavati uloge i pripadajuće ovlasti zaposlenika. 
Kako ne bi došlo do pogrešne interpretacije rezultat sustav će prepoznavati uloge zaposlenika, a oni će imati različita ograničenja za pristup dijelovima sustava. 
Najveći problem kod ovog rješenja je ako dođe do pogrešnog rada OCR tehnologije. 
Softversko rješenje bi se zvalo MicroBio Manager s obzirom na to da se bavi mikrobiološkom analizom. Softver bi bio potpuno novo programsko rješenje, koje neće pratiti uzorke koji nemaju pridružen QR/bar kod. Također se neće moći voditi evidencija drugih uzoraka poput stolice ili sline.


## Specifikacija projekta
MicroBio Manager je softversko riješenje za digitalizaciju radnog naloga u mikrobiološkom laboratoriju. Sustav omogućava prijavu, izradu novog radnog naloga i izradu novog pacijenta. Sustav može djelomično automatski pohranjivati podatke u radni nalog pomoću OCR tehnologije, ali također omogućava ručni unos i ispravljanje rezultata analize u slučaju pogreške OCR tehnologije. Specijalisti imaju mogućnost  dodaovanja komentara za rezultate analize. Sustav može prikazati statistiku rezutltata pretraga za pacijenta i može prikazati statittiku poslovanja. 

## Zadatak
https://github.com/foivz/pi22-zadace-vtrakosta20/blob/master/Korisni%C4%8Dki%20zahtjevi%20ZS%20-%20mikrobiolo%C5%A1ki%20laboratorij.pdf


