# Asseria Gradnja Website

Ovo je web stranica za **Asseria Gradnja** (http://asseria-gradnja.com.hr).

## 🚀 Postavljanje na GitHub Pages

1. Preimenuj glavni HTML fajl u **index.html**.
2. Na GitHubu kreiraj novi repozitorij (npr. `asseria-gradnja`).
3. Uploadaj fajl `index.html`, sve slike koje koristi stranica (`logo.png`, `pozadina.jpg`, `alat.jpg`) i **CNAME** fajl.
4. Idi u **Settings → Pages**.
5. Pod *Source* odaberi `main branch`.
6. GitHub će generirati link: `https://tvoje-korisnicko-ime.github.io/asseria-gradnja/`.

## 🌐 Vlastita domena
Ako koristiš domenu **asseria-gradnja.com.hr**:
1. U repozitoriju dodaj fajl po imenu **CNAME**.
2. U njega upiši:
   ```
   asseria-gradnja.com.hr
   ```
3. U DNS postavkama svoje domene dodaj CNAME zapis koji pokazuje na `tvoje-korisnicko-ime.github.io`.

### 📄 CNAME fajl
```
asseria-gradnja.com.hr
```

### ⚙️ Primjer DNS postavki
U kontrolnom panelu kod tvog registrara (gdje si kupio domenu) dodaj:

- **CNAME zapis**
  - Ime/Host: `www`
  - Vrijednost: `tvoje-korisnicko-ime.github.io`
  - TTL: 3600 (ili default)

- **A zapisi** (opcionalno, ako želiš da domena radi i bez `www`):
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`

---

## 📂 Struktura projekta
```
asseria-gradnja/
│
├── index.html       # Glavna stranica
├── CNAME            # Fajl za custom domenu
├── logo.png         # Logo firme (dodaj svoju sliku)
├── pozadina.jpg     # Pozadinska slika
├── alat.jpg         # Primjer artikla
└── /assets          # (opcionalno) dodatne slike i video
```

## 📞 Kontakt
- Telefon: +385 91 123 4567
- Email: info@asseria-gradnja.hr
