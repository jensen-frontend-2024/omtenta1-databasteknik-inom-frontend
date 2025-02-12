### **1. Beskriv kortfattat vad som kännetecknar en relationsdatabas.**

**_(3 poäng)_**

- Hur struktureras data i en relationsdatabas?
- Vad är en primärnyckel och varför är den viktig?
- Hur kan tabeller kopplas ihop i en relationsdatabas?

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att nämna att data struktureras i tabeller med rader och kolumner.
- **1 poäng** för att nämna att varje rad identifieras unikt med en primärnyckel.
- **1 poäng** för att nämna att tabeller kan kopplas ihop med hjälp av främmande nycklar (foreign keys).

</details>

---

### **2. Hur lagrar en icke-relationell databas _(NoSQL)_ data?**

**_(2 poäng)_**

Beskriv ett sätt som en icke-relationell databas kan lagra data på. Du behöver inte gå in i detalj, men ge ett exempel på en typ av lagring. Ge också ett exempel på en sådan databas för bonuspoäng.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att redogöra för ett sätt som data lagras på i en NoSQL-databas. Det räcker att nämna typen och kort beskriva hur den fungerar, t.ex. dokumentdatabas, key-value-databas, grafdatabas eller kolumnbaserad databas.
- **1 poäng** för att namnge datasen som använder sig av det lagringssättet som beskrivs.

</details>

---

### **3. Vilka typer av relationer kan finnas mellan tabeller i en relationsdatabas?**

**_(4 poäng)_**

Beskriv följande typer av relationer mellan tabeller i en relationsdatabas:

- En-till-en-relation (1-1)
- En-till-många-relation (1-m)
- Många-till-många-relation (m-m)

Förklara också hur många-till-många-relationer vanligtvis hanteras i en relationsdatabas.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt beskriva en en-till-en-relation (1-1).
- **1 poäng** för att korrekt beskriva en en-till-många-relation (1-m).
- **1 poäng** för att korrekt beskriva en många-till-många-relation (m-m).
- **1 poäng** för att förklara att många-till-många-relationer oftast hanteras genom en korsningstabell (junction table).

</details>

Här är en omskriven version av frågan, med ett tydligare fokus och vägledning för studenterna:

---

### **4. Vad är ett ER-diagram _(ERD)_ och varför används det?**

**_(1 poäng)_**

Förklara kortfattat vad ett ER-diagram är och dess syfte vid arbete med databaser.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en korrekt och tillräcklig förklaring av vad ett ER-diagram är och varför det används, till exempel för att visualisera och planera relationer mellan olika entiteter i en databas.

</details>

---

Självklart! Här är en ny version med ett annat exempel:

---

### **5. Hur skulle ett ER-diagram _(ERD)_ kunna se ut utifrån denna beskrivning?**

**_(3 poäng)_**

En bokhandel vill registrera information om sina kunder och de böcker de har köpt.

- Varje kund har ett unikt id, ett namn och en e-postadress.
- Varje bok har ett unikt ISBN-nummer, en titel och en författare.
- En kund kan köpa flera böcker, men varje bok kan endast köpas av en kund.

Rita eller beskriv ett ER-diagram som visar relationen mellan kunder och böcker.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt beskriva två tabeller, en för kunder och en för böcker, med rätt attribut i respektive tabell.
- **1 poäng** för att identifiera ISBN-nummer som primärnyckel i bok-tabellen.
- **1 poäng** för att tydligt visa en en-till-många-relation mellan kunder och böcker.

</details>

---

### **6. Hur skulle ett ER-diagram _(ERD)_ kunna se ut utifrån denna beskrivning?**

**_(4 poäng)_**

En universitet vill hålla reda på sina kurser, studenter, och de lärare som undervisar kurserna.

- Varje kurs har ett unikt kurs-ID, en kursnamn, och antal poäng.
- Studenterna har ett student-ID, namn, och e-postadress.
- Lärarna har ett lärar-ID, namn, telefonnummer, och expertområde.
- En lärare kan undervisa flera kurser, men en kurs har endast en lärare.
- Flera studenter kan gå en och samma kurs, och varje student kan läsa flera kurser.

Rita eller beskriv ett ER-diagram som visar relationerna mellan kurser, studenter och lärare.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en korrekt beskrivning av entiteterna (kurser, studenter och lärare) och deras attribut.
- **1 poäng** för korrekt relation mellan kurser och lärare (en-till-många).
- **2 poäng** för korrekt relation mellan studenter och kurser (många-till-många) samt dess korstabell.
- **1 poäng** för korrekt beskrivning av alla primärnycklar och främmande nycklar. Primärnyckeln för relationen mellan studenter och kurser ska även vara sammansatt.

</details>

---

### **7. Vad är normalisering av en databas, och vad innebär den första normalformen (1NF)?**

**_(2 poäng)_**

1. Förklara kortfattat vad normalisering innebär och varför det används i databaser.
2. Beskriv vad den första normalformen (1NF) innebär och vilka krav som måste uppfyllas för att en tabell ska vara i 1NF.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en tillfredsställande förklaring av normalisering. Svaret bör nämna att det används för att minska upprepning och redundans.
- **1 poäng** för en korrekt beskrivning av den första normalformen (1NF), inklusive att varje kolumn endast innehåller atomiska värden och att alla värden i en kolumn är av samma typ.

</details>

---

### **8. Hur kan du skriva en SQL-fråga för att hämta all information från tabellen "users"?**

**_(1 poäng)_**

Skriv en SQL-query som returnerar alla kolumner och alla rader från tabellen "users".

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en korrekt query:

```sql
SELECT * FROM users;
```

</details>

---

### **9. Hur kan du skriva en SQL-fråga för att hämta specifik information om en produkt?**

**_(1 poäng)_**

Skriv en SQL-query som hämtar `product_id`, `product_name` och `price` från tabellen `products` för produkten med `product_id` lika med 101.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en korrekt query:

```sql
SELECT product_id, product_name, price FROM products WHERE product_id = 101;
```

</details>

---

### **10. Se databasstrukturen nedan. Hur kan du skriva en query för att plocka ut en anställd och vilken avdelning de arbetar på?**

**_(2 poäng)_**

```
      ┌──────────────┐                ┌────────────────┐
      │ departments  │<───────────────│   employees    │
      │──────────────│                │────────────────│
      │ dept_id (PK) │ 1           *  │ emp_id (PK)    │
      │ dept_name    │                │ first_name     │
      └──────────────┘                │ last_name      │
                                      │ dept_id (FK)   │
                                      └────────────────┘
```

Skriv en SQL-query som hämtar information om en anställd med förnamn "Anna" och efternamn "Bergström", samt vilken avdelning hon arbetar på.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt skriva `SELECT`-delen av queryn.
- **1 poäng** för att korrekt skriva `JOIN`-delen av queryn.

```sql
SELECT employees.emp_id, employees.first_name, employees.last_name, departments.dept_name
FROM employees
JOIN departments ON employees.dept_id = departments.dept_id
WHERE employees.first_name = 'Anna' AND employees.last_name = 'Bergström';
```

</details>

---

### **11. Vad används HTTP till, och varför är det viktigt för webbapplikationer?**

**_(2 poäng)_**

Förklara kort vad HTTP är och vilken funktion det fyller i kommunikationen mellan klienter och servrar i webbapplikationer. Bonuspoäng om du kan skriva ut vad HTTP står för.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för en tillfredsställande förklaring, exempelvis:

  > HTTP är ett protokoll som används för att överföra data mellan en klient (t.ex. en webbläsare) och en server. Det är grunden för kommunikation på webben.

- **1 bonuspoäng** för att ange att HTTP står för HyperText Transfer Protocol.

</details>

### **12. Vad representerar de olika kategorierna av HTTP-statuskoder?**

**_(5 poäng)_**

HTTP-statuskoder delas in i olika kategorier beroende på vad de representerar. De vanligaste kategorierna som används i webbapplikationer är:

- **2xx**
- **4xx**
- **5xx**

Dessa är grundläggande att känna till. Förklara vad varje kategori betyder och ge gärna exempel på vad de kan användas till.

Vill du visa bredare kunskap, kan du även beskriva de mindre vanliga kategorierna:

- **1xx**
- **3xx**

Du kan samla upp till 5 poäng totalt, där varje korrekt beskrivning ger 1 poäng.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng per kategori** för en korrekt beskrivning. Poängen fördelas som följer:
  - **1xx:** Beskriv vad dessa koder indikerar.
  - **2xx:** Beskriv vad dessa koder indikerar.
  - **3xx:** Beskriv vad dessa koder indikerar.
  - **4xx:** Beskriv vad dessa koder indikerar.
  - **5xx:** Beskriv vad dessa koder indikerar.

</details>

Självklart, här kommer en anpassad version med en poängfördelning som tydligt beskriver API:s huvudsakliga syfte på en nivå som passar nybörjare:

---

### **13. Vad är ett API, och varför används det?**

**_(2 poäng)_**

Förklara vad ett API är och dess huvudsakliga syfte. Bonuspoäng om du kan skriva ut vad förkortningen API står för.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att ange vad API står för (Application Programming Interface).
- **1 poäng** för en tillfredsställande beskrivning av dess syfte, exempelvis:
  - Ett API är som en bro mellan olika program eller tjänster, som gör det möjligt för dem att kommunicera med varandra. Det förenklar processen genom att tillhandahålla tydliga regler och funktioner, så att utvecklare kan använda data eller funktioner från andra system utan att behöva förstå alla tekniska detaljer bakom dem.

</details>

---

Absolut, vi kan förenkla jämförelsen så att den blir lättare att förstå för studenter som är nybörjare. Här är en omformulerad version:

---

### **14. Varför är JSON ett vanligt dataformat i API:er?**

**_(5 poäng)_**

Förklara varför JSON används så ofta som dataformat i API:er. Din förklaring bör inkludera:

- Vad JSON står för.
- Vilka fördelar JSON har för utvecklare och datorer.
- Varför JSON är kompatibelt med många programmeringsspråk.
- Varför JSON är ett smidigt format att använda vid datautbyte över nätverk.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt ange vad JSON står för (JavaScript Object Notation).
- **1 poäng** för att beskriva att JSON är lätt att läsa och skriva för människor och datorer.
- **1 poäng** för att förklara att JSON är ett lättviktsformat som fungerar väl med de flesta programmeringsspråk.
- **1 poäng** för att nämna att JSON är textbaserat och därför enkelt att skicka och ta emot över nätverk.
- **1 poäng** för att beskriva att JSON är enkelt och effektivt jämfört med mer komplexa format, utan att behöva ge specifika exempel som XML.

</details>

---

### **15. Vad betyder förkortningen REST, och vad är dess huvudsakliga syfte i nätverkskommunikation?**

**_(2 poäng)_**

Förklara vad REST står för och ge en kort beskrivning av dess roll inom nätverkskommunikation.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt ange att REST står för "Representational State Transfer".
- **1 poäng** för en kort och tydlig beskrivning, exempelvis:
  - REST är en arkitekturprincip för nätverkskommunikation som används för att bygga API:er. Det bygger på HTTP och använder resurser (URL:er) för att skapa, läsa, uppdatera och ta bort data genom standardmetoder som GET, POST, PUT och DELETE.

</details>

---

### **16. Vad innebär principen _Statelessness_ i REST?**

**_(2 poäng)_**

Förklara vad principen _Statelessness_ innebär i REST och hur den påverkar kommunikationen mellan klient och server.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att beskriva att varje begäran från klienten till servern ska innehålla all information som behövs för att förstå och bearbeta begäran.
- **1 poäng** för att förklara hur _Statelessness_ gör att servern inte behöver lagra någon information om tidigare förfrågningar, vilket förenklar skalbarheten.

Exempel på korrekt beskrivning:

- _Statelessness_ innebär att varje förfrågan som skickas från klienten till servern är oberoende av tidigare förfrågningar. Servern lagrar ingen information om tidigare interaktioner, vilket gör det enklare att hantera stora mängder samtidiga förfrågningar.

</details>

---

### **17. Vad identifierar en URI i ett GET-request?**

**_(2 poäng)_**

Tänk dig att en GET-förfrågan skickas till följande URI:  
`https://api.shop.com/products/567`

1. Vilken typ av resurs förväntar vi oss att få tillbaka?
2. Vad berättar siffran `567` i URI:n om resursen?

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att identifiera att resursen är av typen "Product".
- **1 poäng** för att beskriva att siffran `567` identifierar en specifik produkt.

Exempel på korrekt svar:

- Resursen är en "Product".
- URI:n identifierar den specifika produkten med ID `567`.

</details>

---

### **18. Skapa en GET-route i Express som returnerar dynamisk JSON-data baserat på en route-parameter.**

**_(4 poäng)_**

Skriv en Express-route som svarar på en GET-förfrågan till `/greet/:name` och returnerar följande JSON-data:

Om route-parametern `name` är exempelvis `Alice` (t.ex. `/greet/Alice`):

```json
{ "message": "Hello, Alice!" }
```

Om ingen route-parameter anges (t.ex. `/greet`):

```json
{ "message": "Hello, Guest!" }
```

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt definiera GET-routen för `/greet/:name`.
- **1 poäng** för att korrekt läsa av route-parametern med `req.params`.
- **1 poäng** för att hantera JSON-svar baserat på den angivna parametern `name`.
- **1 poäng** för att hantera JSON-svar med en fallback om ingen parameter anges.

Exempel på korrekt lösning:

```js
const express = require("express");
const app = express();

app.get("/greet/:name?", (req, res) => {
  const name = req.params.name || "Guest";
  res.json({ message: `Hello, ${name}!` });
});
```

</details>

---

### **19. Skapa flera GET-rutter i Express som svarar med olika texter.**

**_(4 poäng)_**

Skriv ett Express-program med följande funktionalitet:

1. En GET-route till `/hello` som svarar med texten:

   ```
   Hello there!
   ```

2. En GET-route till `/goodbye` som svarar med texten:

   ```
   Goodbye, see you soon!
   ```

3. En fallback-route för alla andra GET-förfrågningar som svarar med texten:
   ```
   Route not found.
   ```

**Tips:** Du kan använda en fallback-route med `*` som route-path för att fånga upp alla övriga förfrågningar som inte matchar någon av de tidigare definierade ruterna.

Inkludera nödvändiga imports och konfigurationer.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt definiera `/hello`-routen.
- **1 poäng** för att korrekt definiera `/goodbye`-routen.
- **1 poäng** för att implementera en fallback-route som använder `*`.
- **1 poäng** för korrekt hantering av imports och `app.listen`.

Exempel på korrekt lösning:

```js
const express = require("express");
const app = express();

app.get("/hello", (req, res) => {
  res.send("Hello there!");
});

app.get("/goodbye", (req, res) => {
  res.send("Goodbye, see you soon!");
});

// Fallback-route
app.get("*", (req, res) => {
  res.send("Route not found.");
});

app.listen(3000, () => {
  console.log("Server is running on port 3000");
});
```

</details>

---

### **20. Skapa en POST-route i Express för att lägga till en ny resurs med validering och databaslagring.**

**_(8 poäng)_**

Skriv en POST-route för `/items` i en Express-applikation som gör följande:

1. Accepterar data i JSON-format för att skapa en ny resurs.
2. Validerar att fältet `name` finns i den inkommande datan.
3. Validerar att fältet `name` är en sträng och inte är tomt.
4. Lagrar resursen i en databas genom att använda en **INSERT query**.
5. Returnerar statuskoden `201` (Created) och ett meddelande som bekräftar att resursen har lagts till om `name` är korrekt.
6. Returnerar statuskoden `400` (Bad Request) och ett felmeddelande om `name` saknas eller är ogiltigt.

Använd följande databasuppkoppling:

```js
const db = require("better-sqlite3")("database.db");
```

Inkludera nödvändiga imports och konfigurationer.

<details open>
<summary>Poängbedömning</summary>

Poäng tilldelas på följande sätt:

- **1 poäng** för att korrekt definiera POST-routen för `/items`.
- **1 poäng** för att hantera JSON-data från `req.body`.
- **1 poäng** för att validera att fältet `name` finns.
- **1 poäng** för att validera att `name` är en sträng och inte är tomt.
- **2 poäng** för att korrekt implementera och använda en **INSERT query** för att lagra datan i databasen.
- **1 poäng** för att returnera korrekt statuskod och meddelande vid framgång (201).
- **1 poäng** för att returnera korrekt statuskod och meddelande vid fel (400).

Exempel på korrekt lösning:

```js
const express = require("express");
const app = express();
const db = require("better-sqlite3")("database.db");

app.use(express.json());

app.post("/items", (req, res) => {
  const { name } = req.body;

  // Validera att fältet 'name' finns och är en icke-tom sträng
  if (!name || typeof name !== "string" || name.trim() === "") {
    return res
      .status(400)
      .send("Fältet 'name' är obligatoriskt och måste vara en icke-tom sträng.");
  }

  // Lagra resursen i databasen
  try {
    const stmt = db.prepare("INSERT INTO items (name) VALUES (?)");
    stmt.run(name);
    return res.status(201).send(`Resurs med namn ${name} har lagts till.`);
  } catch (error) {
    return res.status(500).send("Ett fel inträffade vid lagring av resursen.");
  }
});

app.listen(3000, () => {
  console.log("Server is running on port 3000");
});
```

</details>

---

### **21. Skapa en PUT-route i Express för att uppdatera en produkt.**

**_(VG-fråga, 15 poäng)_**

Du ska skapa en **PUT-route** för endpointen `/api/product/:id` som uppdaterar en produkts `pris`, `lagerantal` och `namn` enligt följande krav:

### **Validering och felhantering**

1. Route-parametern `id` måste:
   - Vara ett nummer och större än 0, annars returnera statuskoden `400` med ett felmeddelande.
2. Body måste:
   - Vara ett objekt som innehåller fälten `pris`, `lagerantal` och `namn`, annars returnera statuskoden `400` med ett felmeddelande.
3. Om en produkt med det angivna `id` inte finns:
   - Returnera statuskoden `404` med ett felmeddelande.

### **Databasinteraktion och uppdatering**

1. Hämta produkten från databasen innan uppdateringen.
2. Om produkten existerar:
   - Uppdatera dess `pris`, `lagerantal` och `namn`.
3. Om ett oväntat fel inträffar, hantera detta med en `try-catch` och returnera statuskoden `500`.

Använd följande databasuppkoppling:

```js
const db = require("better-sqlite3")("database.db");
```

Glöm inte att inkludera importer och så vidare. Var så nog som möjligt.

<details open>
<summary>Poängbedömning</summary>

### **Poängfördelning (15 poäng)**

1. **Validering av `id` (3 poäng):**

   - **1 poäng**: Kontrollera att `id` är ett nummer.
   - **1 poäng**: Kontrollera att `id > 0`.
   - **1 poäng**: Returnera korrekt statuskod och felmeddelande om valideringen misslyckas.

2. **Validering av body (4 poäng):**

   - **1 poäng**: Kontrollera att body inte är tom.
   - **3 poäng**: Kontrollera att body innehåller `pris`, `lagerantal` och `namn`, samt hantera fel med statuskod `400` och ett meningsfullt meddelande.

3. **Kontroll av produktexistens (3 poäng):**

   - **1 poäng**: Hämta produkten från databasen.
   - **2 poäng**: Returnera statuskod `404` och ett meningsfullt felmeddelande om produkten inte hittas.

4. **Uppdatering av produkten (3 poäng):**

   - **1 poäng**: Anropa korrekt `UPDATE` query.
   - **1 poäng**: Returnera statuskod `200` vid lyckad uppdatering.
   - **1 poäng**: Returnera ett bekräftande meddelande.

5. **Felhantering (2 poäng):**
   - **2 poäng**: Använd `try-catch` för att fånga oväntade fel och returnera statuskod `500` med ett generellt felmeddelande.

</details>

---

### **Lösningsexempel**

```js
const express = require("express");
const app = express();
const db = require("better-sqlite3")("store.db");

app.use(express.json());

app.put("/api/product/:id", (req, res) => {
  const id = parseInt(req.params.id);

  // Validering av id
  if (isNaN(id) || id <= 0) {
    return res.status(400).json({ error: "Ogiltigt id" });
  }

  // Validering av body
  const { pris, lagerantal, namn } = req.body;
  if (!pris || !lagerantal || !namn) {
    return res.status(400).json({
      error: "Body måste innehålla pris, lagerantal och namn",
    });
  }

  try {
    // Kontrollera om produkten finns
    const product = db.prepare("SELECT * FROM products WHERE id = ?").get(id);

    if (!product) {
      return res.status(404).json({ error: "Produkten hittades inte" });
    }

    // Uppdatera produkten
    db.prepare("UPDATE products SET pris = ?, lagerantal = ?, namn = ? WHERE id = ?").run(
      pris,
      lagerantal,
      namn,
      id
    );

    return res.status(200).json({ message: "Produkten uppdaterades" });
  } catch (error) {
    return res.status(500).json({ error: "Ett serverfel inträffade" });
  }
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
```
