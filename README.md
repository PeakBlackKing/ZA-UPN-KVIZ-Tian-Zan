q# za-uip-projekt-kviz

Na začetku kviza sveti zelena LED dioda, kar pomeni, da še noben igralec ni pritisnil svoje tipke in je kviz pripravljen na začetek. Ko katerikoli igralec pritisne eno izmed tipk A, B ali C, se zelena LED ugasne, prižge pa se rumena LED, ki nakazuje, da je kviz v teku in da je vsaj en igralec že sodeloval.Vsakič, ko igralec pritisne svojo tipko, se njegov pritisk zabeleži v točnem vrstnem redu. Ta vrstni red se nato sproti izpiše na LCD zaslon, tako da vsi vidijo, kdo je bil prvi, drugi in tretji.
Ko so bile pritisnjene vse tri tipke – torej so sodelovali vsi trije igralci – se rumena LED ugasne in začne utripati rdeča LED dioda, kar pomeni, da je kviz končan in se rezultati ne spreminjajo več.
Za ponoven začetek kviza mora uporabnik pritisniti tipko R (reset). S tem se izklopi rdeča LED, znova prižge zelena LED, izbriše se vrstni red na LCD zaslonu in kviz je pripravljen za novo igro.

KOSOVINA(Potrebni elementi):

| Količina | Element            | Opomba                   |
| -------- | ------------------ | ------------------------ |
| 1x       | Arduino Uno        | Glavni krmilnik          |
| 1x       | LCD zaslon 16x2    | Z vmesnikom ali brez     |
| 3x       | Tipke (A, B, C)    | NO (normally open)       |
| 1x       | Tipka za reset (R) | NO (normally open)       |
| 3x       | Upor 10kΩ          | Pull-down upori za gumbe |
| 3x       | LED diode          | Zelena, rumena, rdeča    |
| 3x       | Upor 220Ω          | Serijski upori za LED    |
| Žice     |                    | Za povezavo              |
| 1x       | Breadboard         | Za sestavo               |
