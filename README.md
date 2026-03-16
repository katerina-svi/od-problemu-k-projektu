# Od problému k projektu

Interaktivní nástroj pro výběr tématu projektu v kurzu **CŽV AI v praxi** (KISK FF MUNI, jaro 2026).

🔗 **[Spustit nástroj](https://TVUJ-USERNAME.github.io/od-problemu-k-projektu/)**  
*(po publikaci nahraďte `TVUJ-USERNAME` svým GitHub uživatelským jménem)*

## Co to je?

Facilitovaný miniworkshop ve formě webové aplikace, který účastníkům kurzu pomůže najít téma projektu. Nástroj provede účastníka třemi otázkami, doporučí projektový směr s příklady od spolužáků a nabídne canvas pro rozpracování nápadu.

### Průchod nástrojem

1. **Kde žije váš problém?** — práce, vzdělávání, osobní život, komunita
2. **Co chcete s problémem udělat?** — zlepšit, vytvořit, propojit, zpřístupnit
3. **Pro koho to bude?** — já, tým, klienti, komunita
4. **Projektový profil** — doporučený směr + příklady z dotazníku
5. **Projektový canvas** — rozpracování: Problém → Pro koho → Typ řešení → První krok
6. **Shrnutí** — kompletní přehled s možností zkopírovat jako Markdown

## Jak publikovat na GitHub Pages

1. Vytvořte nový repozitář na GitHubu (např. `od-problemu-k-projektu`)
2. Nahrajte soubor `index.html` do repozitáře
3. Jděte do **Settings → Pages**
4. V sekci **Source** vyberte **Deploy from a branch**
5. Vyberte větev `main` a složku `/ (root)`
6. Klikněte **Save**
7. Za pár minut bude nástroj dostupný na `https://TVUJ-USERNAME.github.io/od-problemu-k-projektu/`

## Jak vložit do interaktivní osnovy (IS MUNI)

Nástroj je jeden HTML soubor bez externích závislostí. Můžete ho:

- **Vložit jako iframe** do interaktivní osnovy:
  ```html
  <iframe src="https://TVUJ-USERNAME.github.io/od-problemu-k-projektu/" width="100%" height="800" style="border:none;border-radius:12px;"></iframe>
  ```
- **Sdílet jako odkaz** přímo na GitHub Pages URL

## Technické detaily

- Jeden soubor (`index.html`), žádné závislosti
- Vanilla JavaScript, žádný framework
- Responzivní design
- Funguje offline po prvním načtení
- Export projektového záměru jako Markdown (kopírování do schránky)

## Kurz

**CŽV AI v praxi — Od nápadu k prototypu**  
KISK FF MUNI · Jaro 2026  
Mgr. Kateřina Švidrnochová

## Licence

Tento nástroj je volně k dispozici pro vzdělávací účely.
