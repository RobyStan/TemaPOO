# Pong
#### Ping Pong 2D. Scopul jocului este acela de a nu lăsa mingea să treacă de paletă

## Known Bugs
### Bug la Coliziuni în Colțuri
- Dacă mingea ajunge fix în colț este imposibil de lovit
- La viteze mari mingea poate trece prin paletă
- Mingea trece prin pereții din mijloc

### Tema 0

- [x] Nume proiect (poate fi schimbat ulterior)
- [x] Scurtă descriere a temei alese, ce v-ați propus să implementați

## Tema 1

#### Cerințe
- [x] definirea a minim **3-4 clase** folosind compunere
- [x] constructori de inițializare
- [x] pentru o clasă: constructor de copiere, `operator=` de copiere, destructor
<!-- - [ ] pentru o altă clasă: constructor de mutare, `operator=` de mutare, destructor -->
<!-- - [ ] pentru o altă clasă: toate cele 5 funcții membru speciale -->
- [x] `operator<<` pentru toate clasele pentru afișare (std::ostream)
- [x] cât mai multe `const` (unde este cazul)
- [x] implementarea a minim 3 funcții membru publice pentru funcționalități specifice temei alese
- [x] scenariu de utilizare a claselor definite:
  - crearea de obiecte și apelarea tuturor funcțiilor membru publice în main
  - vor fi adăugate în fișierul `tastatura.txt` exemple de date de intrare de la tastatură (dacă există)
- [x] tag de `git`: de exemplu `v0.1`
- [x] serviciu de integrare continuă (CI); exemplu: GitHub Actions

## Tema 2

#### Cerințe
- [x] separarea codului din clase în `.h` (sau `.hpp`) și `.cpp`
- [x] moșteniri:
  - minim o clasă de bază și **3 clase derivate**
  - ierarhia trebuie să fie cu bază proprie, nu derivată dintr-o clasă predefinită
  - [x] clasă cu atribut de tip pointer la o clasă de bază cu derivate
  - [x] funcții virtuale (pure) apelate prin pointeri de bază din clasa care conține atributul de tip pointer de bază
    - minim o funcție virtuală va fi **specifică temei** (e.g. nu simple citiri/afișări)
    - constructori virtuali (clone): sunt necesari, dar nu se consideră funcții specifice temei
  - [x] apelarea constructorului din clasa de bază din constructori din derivate
  - [ ] smart pointers (recomandat, opțional)
  - [x] `dynamic_cast`/`std::dynamic_pointer_cast` pentru downcast cu sens
- [x] suprascris cc/op= pentru copieri/atribuiri corecte, copy and swap
- [x] excepții
  - [x] ierarhie proprie cu baza `std::exception` sau derivată din `std::exception`; minim 2 clase pentru erori
    specifice
  - [x] utilizare cu sens: de exemplu, `throw` în constructor, `try`/`catch` în `main`
- [x] funcții și atribute `static`
- [x] STL
- [x] cât mai multe `const`
- [x] la sfârșit: commit separat cu adăugarea unei noi clase derivate fără a modifica restul codului, pe lângă cele 3
  derivate deja adăugate
  - noua derivată nu poate fi una existentă care a fost ștearsă și adăugată din nou
- [x] tag de `git`: de exemplu `v0.2`

## Tema 3

#### Cerințe
- [ ] 2 șabloane de proiectare (design patterns)
- [ ] o clasă șablon cu sens; minim **2 instanțieri**
  - [ ] preferabil și o funcție șablon (template) cu sens; minim 2 instanțieri
<!-- - [ ] o specializare pe funcție/clasă șablon -->
- [ ] tag de `git`: de exemplu `v0.3` sau `v1.0`

## Resurse

- [digestpp](https://github.com/kerukuro/digestpp/tree/4ec4106677e652a90716ad929d657a622089ef16) (Unlicense)
- [random](https://github.com/effolkronium/random/tree/a8f6fd27f8ac53e6bcd3c30053999f37d07869b0) (MIT)
- [rlutil](https://github.com/tapio/rlutil/tree/821fdca0191b314ee07b0fad2abe4ea973e45575) (WTFPL)
- [csv-parser](https://github.com/vincentlaucsb/csv-parser/tree/9d5f796a32c6cdecd83a2f778ca6db0500948d27) (MIT)
- [date](https://github.com/HowardHinnant/date/tree/22ceabf205d8d678710a43154da5a06b701c5830) (MIT)
- adăugați trimiteri către resursele externe care v-au ajutat sau pe care le-ați folosit
