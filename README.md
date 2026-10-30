# Muzeul Orașului Necunoscut — landing page (demo)

Versiune demo, statică, a paginii principale a Muzeului Orașului Necunoscut (Mizil), construită pe ghidul de identitate al brandului MON.

## Structură

- `index.html` — pagina completă (HTML + CSS + un mic script pentru meniul mobil)
- `assets/img/` — fotografii de arhivă și logo-ul (SVG)

Nu are dependențe și nu necesită build. Fontul Raleway se încarcă de pe Google Fonts; textul curent folosește Helvetica Neue / Helvetica / Arial.

## Publicare

Se copiază conținutul folderului în rădăcina site-ului de pe server (Apache, Nginx etc.), de exemplu:

```bash
git clone <repo> /var/www/mon
```

sau, pentru actualizări:

```bash
cd /var/www/mon && git pull
```

## De completat

- Linkurile „Răsfoiește arhiva” și „Trimite povestea ta” duc deocamdată la ancore din pagină.
- Paginile individuale ale sălilor nu există încă (linkurile sunt `#sala-...`).
