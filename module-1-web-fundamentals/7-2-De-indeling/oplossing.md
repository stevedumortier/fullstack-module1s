# Oplossing 7.2 — De indeling

**Lesdag 3 — HTML: structuur en semantiek** · uit hoofdstuk 11 — *Oplossingen bij lesdag 3*  
Letterlijk uit `Module-01-cursusbundel.docx`. De opgave staat in [`opgave.md`](opgave.md).

**De code staat ook in:** [`oplossing.html`](oplossing.html)

---

**Waar je dit vindt:** hoofdstuk 3 — *Blok 1, deel 2 — Semantiek, lijsten, links en media*, 3.2 *De vaste bouwstenen van een pagina*.

Het geraamte van de pagina. De inhoud uit oefening 2 blijft staan; alleen de
omhulsels komen erbij.

```html
  <body>
    <header>
      <h1>Fietsatelier De Ketting</h1>
      <nav>
        <ul>
          <li><a href="#diensten">Onze diensten</a></li>
          <li><a href="#tarieven">Tarieven</a></li>
          <li><a href="#praktisch">Praktisch</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <p>Wij herstellen al vijftien jaar fietsen in het centrum van Gent…</p>

      <section id="diensten">
        <h2>Onze diensten</h2>
        <!-- de drie diensten, zie Oplossing 7.3 -->
      </section>

      <section id="tarieven">
        <h2>Tarieven</h2>
      </section>

      <section id="praktisch">
        <h2>Praktisch</h2>
        <h3>Openingsuren</h3>
        <h3>Waar vind je ons?</h3>
      </section>
    </main>

    <aside>
      <h2>Goed om te weten</h2>
      <p>Op dinsdagvoormiddag is het meestal rustig: dan hoef je zelden te
        wachten.</p>
    </aside>

    <footer>
      <p>Fietsatelier De Ketting — Kettingstraat 8, 9000 Gent — 09 224 33 11</p>
    </footer>
  </body>
```

*Bestand:* [`oplossing.html`](oplossing.html)

Let op drie dingen:

1. de `h1` staat in de `header`, niet in de `main`. Beide zijn verdedigbaar;
   deze cursus houdt de `h1` bij de naam van de zaak in de `header`;
2. het menu staat in een `nav` **binnen** de `header`;
3. de `footer` staat **buiten** `main`, want hij staat op elke pagina hetzelfde.

---
