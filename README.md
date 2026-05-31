# expressions_dl
# Expression Classification with CNN (FER-2013)

Dariel Riera  
Deep Learning

## Översikt
Detta projekt bygger ett faltningsneuralt nätverk (CNN) för att klassificera ansiktsuttryck i 7 känslor:  
`arg`, `avsky`, `rädsla`, `glad`, `neutral`, `ledsen`, `överraskad`.

Modellen tränas på datasetet **FER-2013** (gråskalebilder 48×48 pixlar).

## Resultat
- **Testaccuracy:** ~52 % (tränad på fulla datasetet, 15 epoker)
- Tydlig overfitting (träningsaccuracy ~65 %, valideringsaccuracy ~52 %)
- Sparad modell: `expression_model.keras`

## Hur man kör
1. Ladda ner FER-2013 från länken i uppgiften.
2. Packa upp mappen `FER-2013` i samma mapp som notebooken.  
   Mappen måste innehålla undermapparna `train/` och `test/` med klassmappar.
3. Installera nödvändiga paket:
   ```bash
   pip install tensorflow matplotlib numpy

## AI
Hjälp med kommentarer, edits, och diverse suggestions  