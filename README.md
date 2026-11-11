# Keys Partners • Reality • Developing • Inžiniering

Moderná, čistá a luxusná úvodná rázcestníková stránka navrhnutá pre spoločnosť **Keys Partners** pôsobiacu v oblasti nehnuteľností, developmentu a stavebného inžinieringu.

## 🎨 Dizajnové prvky
- **Paleta farieb:** Hlboká tmavomodrá (Midnight Navy `#060b14` - `#0f1d36`) v kombinácii s prestížnou architektonickou zlatou (`#D4AF37`, `#F8E7BE`).
- **Dominantné prvky:** 3 veľké, vizuálne atraktívne kruhové navigačné bubliny umiestnené v strede stránky:
  - **Reality** → `https://keyspartner.netlify.app/` (Predaj a prenájom nehnuteľností - Keys Partner)
  - **Developing** → `/developing` (Investičné a rezidenčné projekty)
  - **Inžiniering** → `/inziniering` (Povoľovacie procesy, TDI a kolaudácie)
- **Hlavička (Header):** Oficiálne kruhové zlaté logo Keys Partners a sociálne siete (Facebook, Instagram, YouTube).
- **Pozadie:** Jemná technická blueprint sieť (architektonický raster) s diskrétnou zlatou žiarou a ambientným osvetlením.
- **Interaktivita:** Plynulé vznášanie pri prechode myšou (hover), rotujúci zlatý prstenec, zvýraznenie a elegantná odozva ikon.
- **Responzívnosť:** Plná optimalizácia pre stolné počítače, tablety aj smartfóny.

## 🌐 Automatický deployment (Netlify & GitHub)
Projekt je pripravený pre kontinuálny deployment na Netlify:
- Konfigurácia v `netlify.toml` zabezpečuje publikovanie statického webu z koreňového adresára (`publish = "."`).
- Automatické presmerovania pre čisté URL (`/developing`, `/inziniering`) a priamy redirect pre `/reality` na `https://keyspartner.netlify.app/`.
- Každý `git push` do vetvy `main` na GitHube automaticky spúšťa nový produkčný build na Netlify v reálnom čase.

## 🚀 Lokálne spustenie projektu
1. **Otvorenie priamo v prehliadači:**
   - Dvakrát kliknite na `index.html`. Vstavaný skript automaticky prispôsobí odkazy pre lokálne prezeranie súborov.
2. **Lokálny webový server:**
   ```bash
   # Pomocou Node.js / npx:
   npx serve .

   # Alebo pomocou Pythonu:
   python -m http.server 8000
   ```
   Následne otvorte v prehliadači `http://localhost:8000`.
