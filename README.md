# Keys Partners • Reality • Development • Inžiniering

Moderná, čistá a luxusná úvodná rázcestníková stránka navrhnutá pre spoločnosť **Keys Partners** pôsobiacu v oblasti nehnuteľností, developmentu a stavebného inžinieringu.

## 🎨 Dizajnové prvky
- **Paleta farieb:** Hlboká prémiová čierna (`#111111`) v kombinácii s prestížnou architektonickou zlatou (`#DFBA73`, `#D4AF37`).
- **Dominantné prvky:** 3 elegantné vertikálne Glassmorphism karty umiestnené v strede stránky:
  - **Reality** → `https://keyspartner.netlify.app/` (Predaj a prenájom nehnuteľností - Keys Partner)
  - **Development** → `/development` (Investičné a rezidenčné projekty)
  - **Inžiniering** → `/inziniering` (Povoľovacie procesy, TDI a kolaudácie)
- **Hlavička (Header):** Oficiálne kruhové zlaté logo Keys Partners, motto a sociálne siete (Facebook, Instagram, YouTube).
- **Interaktivita:** Plynulé vznášanie pri prechode myšou (hover), zlaté zvýraznenie a elegantná odozva ikon.
- **Responzívnosť:** Plná optimalizácia pre stolné počítače, tablety aj smartfóny.

## 🌐 Automatický deployment (Netlify & GitHub)
Projekt je pripravený pre kontinuálny deployment na Netlify:
- Konfigurácia v `netlify.toml` zabezpečuje publikovanie statického webu z koreňového adresára (`publish = "."`).
- Automatické presmerovania pre čisté URL (`/development`, `/inziniering`) a priamy redirect pre `/reality` na `https://keyspartner.netlify.app/`.
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
