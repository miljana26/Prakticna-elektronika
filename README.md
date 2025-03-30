# Generator slučajnih brojeva

## Opis  
Ovaj repozitorijum sadrži sve relevantne materijale vezane za projekat **"Generator slučajnih brojeva"**. Projekat se bavi realizacijom uređaja koji generiše slučajan broj iz određenog opsega pritiskom na taster. Uređaj prikazuje generisani broj na 7-segmentnom displeju.  
Projekat obuhvata detaljnu analizu problema, opis svih segmenata uređaja, 3D modelovanje i štampu kutije, dizajn PCB pločice, simulaciju u Micro-Cap-u, kao i merenja i proračune.

## Ključne reči  
NE555 tajmer, CD4026 brojač, 7SEG displej, debouncing, PCB dizajn, 3D modelovanje  

## Kratak sadržaj projekta  
Projekat **"Generator slučajnih brojeva"** obuhvata sledeće ključne tačke:

### 1. Uvod  
- Predstavljanje ideje projekta i ciljeva.

### 2. Analiza problema  
- Podela realizacije na generisanje signala i prikaz brojeva.  
- Razmatranje različitih načina prikaza brojeva.

### 3. Opis svih segmenata uređaja  

#### Napajanje  
- Korišćenje 9V baterije za prenosivost uređaja.

#### NE555 tajmer  
- Generisanje takt signala za brojač.

#### Debouncing  
- Rešenje problema poskakivanja tastera.

#### Brojač CD4026  
- Generisanje nasumičnog broja i prikaz na 7SEG displeju.

#### 7SEG displej  
- Prikaz generisanog broja.

#### 3D modelovanje i štampa  
- Dizajn i štampa kutije za uređaj.  
- Korišćenje **Autodesk Inventor 2021** i **Cura 5.0.0** za 3D modelovanje.  
- Materijal: **PLA**.

#### PCB dizajn  
- Dizajn PCB pločice u **Altium Designer**.  
- Eksportovanje u **Gerber** fajl i fizička realizacija pločice.

#### Micro-Cap simulacija  
- Testiranje rada kola u simulatoru **Micro-Cap 12**.  
- Tranzijentna analiza.

#### Merenja i proračuni  
- Detaljna merenja potrošnje struje za različite komponente i stanja uređaja.  
- Proračuni vezani za pragove komparatora, periode punjenja i pražnjenja kondenzatora, frekvenciju.

### 4. Zaključak  
- Evaluacija postignutih rezultata.  
- Diskusija o mogućim poboljšanjima kao što su:  
  - Proširenje opsega brojenja.  
  - Smanjenje dimenzija uređaja.  
  - Različiti dizajnovi kutije.  
  - Povećanje životnog veka baterije.  
  - Korišćenje punjive baterije.
