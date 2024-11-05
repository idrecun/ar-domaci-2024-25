
## 02 Čist literal

Domaći zadatak se predaje mejlom na `ivan.drecun@matf.bg.ac.rs`. Rok za slanje je zaključno sa naznačenim datumom.

Rok za predaju:  *11.11.2024* \
Naslov mejla:    `[AR] Domaći zadatak 02_cist_literal` \
U prilogu mejla: *main.cpp (i ostale datoteke, ako ih ima)*

U programskom jeziku C++ realizovati sledeće.

1. U okviru fajla *04_sat/sat.cpp* repozitorijuma *ar-materijali* implementirati
funkciju `bool isPureLiteral(Literal l, NormalForm& f)` kojom se proverava da li
se literal `l` pojavljuje samo u datom polaritetu u formuli `f`. Na primer, u
formuli `{{1, -2}, {-1, -2, 3}}` pozivi funkcije `isPureLiteral(-2, f)` i
`isPureLiteral(3, f)` vraćaju `true`, dok pozivi `isPureLiteral(1, f)` i
`isPureLiteral(2, f)` vraćaju `false`.
