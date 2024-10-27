## 01 Iskazna formula

Rok za predaju:  *4.11.2024* \
Naslov mejla:    `[AR] Domaći zadatak 01_iskazna_logika` \
U prilogu mejla: *main.cpp (i ostale datoteke, ako ih ima)*

U programskom jeziku C++ realizovati sledeće.

1. Implementirati strukture za predstavljanje iskaznih formula koje se sastoje
iz atoma, negacije, konjunkcije i disjunkcije.
1. Dubina čvora u stablu definiše se kao broj grana na jedinstvenom putu od
korena stabla do tog čvora. Dubina stabla definiše se kao maksimum dubina svih
čvorova. Dubina iskazne formule definiše se kao dubina stabla kojim je formula
predstavljena. Implementirati funkciju kojom se određuje dubina zadate iskazne
formule.
1. Po uzoru na implementaciju funkcije `cnf` implementirati funkciju
`NormalForm dnf(FormulaPtr formula)` kojom se određuje disjunktivna normalna
forma date formule. Pretpostavlja se da je zadata formula već svedena na
negacionu normalnu formu.
1. U `main` funkciji programa definisati formulu `(p & (~q | r)) | q`. Na
standardni izlaz ispisati dubinu i DNF zadate formule.
