# Elektronika – simulatori za e-učenje

Interaktivni simulatori elektroničkih sklopova izrađeni kao nastavni materijal uz predavanja iz elektronike. Svaki simulator radi izravno u web-pregledniku – ne treba ništa instalirati.

## Simulatori

| Simulator | Opis | Pokreni |
|---|---|---|
| **Ispravljači** | Poluvalni, punovalni sa srednjim izvodom, mosni i poluvalni ispravljač s kapacitivnim filtrom. Prikaz ulaznog i izlaznog napona, struja dioda, srednje i efektivne vrijednosti, faktora valovitosti i zapornog napona diode. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/ispravljaci_simulator.html) |
| **Stabilizator sa Zenerovom diodom** | Karakteristika Zenerove diode s radnim pravcem, utjecaj ulaznog napona, predotpora i trošila, potiskivanje valovitosti te granice I<sub>Zmin</sub> i P<sub>Zmax</sub>. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/zener_stabilizator_simulator.html) |
| **n-kanalni MOSFET** | Presjek tranzistora s induciranim kanalom, izlazne i prijenosna karakteristika, područja rada (zapiranje, triodno, zasićenje), strmina *g*<sub>m</sub> i izlazni otpor *r*<sub>d</sub>. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/mosfet_simulator.html) |
| **p-kanalni MOSFET** | Presjek s induciranim p-kanalom (šupljine), izlazne i prijenosna karakteristika s negativnim naponima i strujom, područja rada te usporedba s n-kanalnim tranzistorom. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/mosfet_p_simulator.html) |
| **Pojačalo u spoju zajedničkog uvoda** | n-kanalni MOSFET s trošilom R<sub>T</sub>: radni pravac i radna točka Q, prijenosna karakteristika sklopa s područjima rada, valni oblici ulaza i izlaza (protufaza, izobličenje), pojačanje iz modela za mali signal i izmjereno pojačanje. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/pojacalo_zajednicki_uvod_simulator.html) |
| **Radna točka MOSFET-a** | Podešavanje statičke radne točke naponskim djelilom (fiksni *U*<sub>GSQ</sub>) i uvodskom degeneracijom (*R*<sub>S</sub>): pravac podešavanja, radni pravac, utjecaj rasipanja parametara *K* i *U*<sub>GS0</sub> na struju *I*<sub>DQ</sub>. | [Otvori](https://jkonjevod.github.io/Elektronika-simulatori-za-e-ucenje/mosfet_radna_tocka_simulator.html) |
## Kako se koriste

- **Klizačima** se mijenjaju parametri sklopa (napon, otpor, kapacitet …), a grafovi i izračunate vrijednosti mijenjaju se odmah.
- Gumb **Pokreni** pomiče vremenski kursor kroz periodu; kursor se može i povući mišem po grafu.
- Elementi koji vode **istaknuti su na shemi**, a ispod sheme piše što se u sklopu upravo događa.

## Za nastavnike

- Simulatori se mogu otvoriti na predavanju putem hiperveze sa slajda (u PowerPointu: **Ctrl + K**).
- Datoteke se mogu i preuzeti i otvoriti lokalno – rade bez interneta.
- Oznake veličina usklađene su s predavanjima (npr. *u*<sub>UL</sub>, *u*<sub>IZ</sub>, *R*<sub>T</sub>).

## Tehničke napomene

Svaki simulator je jedna samostalna HTML datoteka (HTML, CSS i JavaScript), bez vanjskih biblioteka. Prikaz se prilagođava zaslonu računala, tableta i mobitela.
