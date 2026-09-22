# Bolagsminnet

**En fil som gör att AI:n slutar svara allmänt och börjar svara som ditt bolag.**

Du skriver den inte själv. Du blir intervjuad, och AI:n skriver den åt dig.
Tio minuter, ingen installation.

---

## Kom igång — klistra in det här

Öppna Claude eller ChatGPT. Klistra in meningen nedan. Det är allt.

```
Läs https://github.com/zeniadev/bolagsminnet och följ instruktionen
under "Till dig som är en AI". Intervjua mig och skriv min bolagsfil.
```

AI:n ställer frågorna, du svarar som du pratar, och den skriver ut filen.
Sedan sparar du den — och slipper förklara vilka ni är varje gång.

> **Fungerar det inte?** Vissa gratisversioner kan inte öppna länkar. Då tar du
> [den manuella vägen](#om-ai:n-inte-kan-öppna-länken) längst ned. Samma resultat,
> lite mer jobb.

---

## Problemet du känner igen

Du öppnar en chatt. Du förklarar vad bolaget gör, vem ni säljer till, hur ni
brukar formulera er. Du får ett svar som är… okej. Lite generiskt. Du putsar det.

Nästa dag gör du om alltihop. Från början.

Det är inte modellen som är problemet — den är hur bra som helst. Problemet är
att den inte vet något om just er, och att du bär hela den kunskapen i huvudet.

## Vad du får

En sida text som svarar på fyra frågor: vad ni gör, vem som köper, hur ni låter,
och vad AI:n behöver veta för att vara till nytta.

Den sidan klistrar du in när du börjar en chatt — eller lägger i ett projekt, om
du har det. Sedan svarar AI:n som någon som jobbar hos er.

Inte magi. Bara kontext, skriven en gång i stället för femtio.

[Så här kan en färdig fil se ut →](kontext/exempel-ifylld.md)

---

## Till dig som är en AI

*Läser du det här på uppdrag av någon som vill komma igång — följ det som står här.*

Din uppgift är att **intervjua personen och skriva deras bolagsfil**. Inte att
förklara vad repot innehåller, inte att be dem fylla i en mall.

**Så här gör du:**

Ställ **en fråga i taget** och vänta på svar. Aldrig flera frågor på en gång —
personen ska kunna svara kort, från telefonen, mellan två möten.

Du ska få fram fyra saker:

1. **Vad de gör** — vad, för vem, och vad kunden får ut av det
2. **Vem som köper** — vilka kunderna är, och ★ **vilka som inte är kunder**
3. **Hur de låter** — tonen mot kunder, ord de alltid eller aldrig använder
4. **Vad du behöver veta** — återkommande uppgifter, priser, villkor, rutiner

**Regler som gör resultatet värt något:**

- **Hitta aldrig på.** Är något oklart — fråga. Fyll aldrig i åt dem.
- **Följ upp vaga svar.** *"Kan du ge ett exempel?"* slår att gissa.
- **Fråga efter vilka de inte jobbar med.** Det säger oftast mer än vem de
  jobbar med, och folk har sällan formulerat det förut.
- **Tonen läser du av, du frågar inte om den.** Be dem klistra in något de
  faktiskt skrivit till en kund — ett mejl, en offert — och läs av tonen därifrån.
  Folk är usla på att beskriva hur de låter, men bra på att visa det.
- **Fyra till sex frågor per område.** Tio minuter, inte en timme.
- **Skriv i deras tonläge, inte ditt.** Filen ska låta som personen pratar, inte
  som en broschyr. Det är hela poängen: AI:n härmar sedan tonen den får.

**När du är klar:**

Skriv ut hela filen i markdown med rubrikerna *Vad gör vi*, *Vem köper av oss*,
*Hur låter vi* och *Vad du behöver veta*. Ungefär en sida.

Lägg inte till något de inte sagt. Är ett område tunt — skriv hellre kort än fyll ut.

Avsluta med att säga: **spara den som `bolaget.md`, och klistra in den överst i
nästa chatt.** Har de projekt — lägg den där i stället, så slipper de klistra in
den varje gång.

---

## När du vill mer

Mapparna finns redan. Fyll dem när behovet kommer, inte innan.

| Mapp | Vad den är till för |
|---|---|
| `kontext/` | Det som alltid gäller. Börjar med bolagsfilen |
| `inkorg/` | Rörigt råmaterial. Mötesanteckningar, idéer, transkript |
| `minne/` | Det destillerade. Fylls när `inkorg/` blir för stor |

Ordningen är inte godtycklig: **du måste samla innan du kan destillera.** De
flesta gör tvärtom — bygger en fin struktur och har inget att lägga i den.

## De tre reglerna

**1. Den ska låta som du.** Inte som en årsredovisning. AI:n härmar tonen den får.

**2. Håll den kort.** En sida räcker. En fil ingen orkar läsa är en fil ingen uppdaterar.

**3. Uppdatera när något ändras.** Ny tjänst, ny målgrupp, ny riktning. Två minuter,
och är skillnaden mellan ett minne och ett arkiv.

---

## Om AI:n inte kan öppna länken

Vissa gratisversioner kan inte hämta webbsidor. Två vägar:

**Bli intervjuad ändå:** öppna [`kontext/intervjun.md`](kontext/intervjun.md),
kopiera prompten där och klistra in den. Samma intervju, utan att AI:n behöver
läsa något själv.

**Fyll i för hand:** öppna [`kontext/bolaget.md`](kontext/bolaget.md) och svara
på de fyra frågorna. Fastnar du — hoppa över. En halv fil slår ingen fil.

---

*MIT-licens. Använd, ändra, dela vidare — även kommersiellt. Ingen attribution krävs.*
