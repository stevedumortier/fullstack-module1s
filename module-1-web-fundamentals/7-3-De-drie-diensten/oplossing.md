# Oplossing 7.3 — De drie diensten

**Lesdag 3 — HTML: structuur en semantiek** · uit hoofdstuk 11 — *Oplossingen bij lesdag 3*  
Letterlijk uit `Module-01-cursusbundel.docx`. De opgave staat in [`opgave.md`](opgave.md).

**De code staat ook in:** [`oplossing-a.html`](oplossing-a.html), [`oplossing-b.txt`](oplossing-b.txt)

---

**Waar je dit vindt:** hoofdstuk 3 — *Blok 1, deel 2 — Semantiek, lijsten, links en media*, 3.1 *Waarom semantiek* en 3.2 *De vaste bouwstenen van een pagina*.

Het juiste element is **`article`**. Elke dienst is op zichzelf te begrijpen: je
zou "Herstellingen" kunnen losknippen en in een folder of een zoekresultaat
zetten, en het zou nog steeds kloppen.

```html
      <section id="diensten">
        <h2>Onze diensten</h2>

        <article>
          <h3>Herstellingen</h3>
          <p>…</p>
        </article>

        <article>
          <h3>Tweedehandsfietsen</h3>
          <p>…</p>
        </article>

        <article>
          <h3>Verhuur</h3>
          <p>…</p>
        </article>
      </section>
```

*Bestand:* [`oplossing-a.html`](oplossing-a.html)

De drie `article`-elementen zitten samen in één `section`, want samen vormen ze
het thema "Onze diensten" — en dat thema is op zichzelf níét te verplaatsen.

Een verdedigbaar alternatief is drie `section`-elementen. Wat **niet** goed is:
drie `div`-elementen, of geen omhulsel zodat de koppen los in de `main` hangen.

Voorbeeld van een commitboodschap die de keuze verantwoordt:

```text
Zet elke dienst in een article, want elke dienst is los te begrijpen
```

*Bestand:* [`oplossing-b.txt`](oplossing-b.txt)

---
