# Digipedia

## Web aplikacija nalik Wikipedi-i

Projekt Digipedia je nastao na faksu kao projekt za konstrukcijske vježbe iz predmeta **Web programiranje na strani poslužitelja** i **Skriptni programski jezici**.

Tema projekta je bila kreirati program koji će služiti kao informativni portal nalik Wikipedi-i sa autorizacijom korisnika. Program treba sadržavati kategorije, članke i podčlanke koji su dostupni svima te administrativno sučelje za admina pomoću kojeg će moći upravljati svime na stranici.

Stranica prikazuje sva naučena znanja o sljedećim web tehnologijama: **AngularJs v1.6.9** uz **jQuery 3.2.1**, **PHP 7** i korišten je **Bootstrap 3.3.7** za dizajn. A za bazu se koristio **MySQL**.

[![My Skills](https://skills.thijs.gg/icons?i=angular,jquery,php,bootstrap,mysql)](https://skills.thijs.gg)

---

### Stranica sadrži 3 vrste pregleda:

1.  Za običnog gosta stranice koji može pristupiti svim člancima na stranici te mu je sve _read-only_.
1.  Za prijavljenog korisnika koji može dodavati članke i podčlanke, te dati ocjenu svim člancima. Isto tako ima svu kontrolu nad svojim člancima i podčlancima jer ih može uređivati i brisati.
1.  Za prijavljenog admina koji može upravljati svim korisnicima, kategorijama i članicam, znači dodavat, uređivat i brisati ih. Također ima i uvid u povijest uređivanja članaka gdje može vidjeti tko je kada i koji članak uređivao.

---

### Pokretanje projekta

Potrebno je instalirati [XAMPP](https://www.apachefriends.org), te preko toga pokrenuti **Apache** i **MySQL**.

Potom zalijepiti mapu **Digipedia** u `C:\xampp\htdocs\`.

Link za pristup bazi: [http://localhost/phpmyadmin/index.php](http://localhost/phpmyadmin/index.php).

Zatim u **phpmyadmin** kreirati bazu koja se zove `wikipedia`(Character Set neka bude **Collation**) te potom importati `wikipedia.sql` koji se nalazi ovdje u root-u projekta.

Link za pristup aplikaciji: [http://localhost/digipedia/index.php#!/](http://localhost/digipedia/index.php#!/).
