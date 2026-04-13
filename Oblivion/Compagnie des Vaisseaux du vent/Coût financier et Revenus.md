# Coûts

## Dépenses par Gondolfière par jour

### En vol

| Poste de dépense      | **Coût Journalier (po)** | **Détails**                                                                         |
| --------------------- | ------------------------ | ----------------------------------------------------------------------------------- |
| Salaires Équipage     | 36                       | Aéromarin (2 po x10) / Maître d'équipage (3 po) / Cocher (3 po) / Capitaine (10 po) |
| Vivres Équipage       | 7                        | 13 bouches à nourrir (qualité standard)                                             |
| Vivres Hippogriffes   | 4                        | 4 hippogriffes (viande fraîche / soins)                                             |
| Maintenance & Khayolt | 5                        | Matériel, réparations et nutriments                                                 |
| **TOTAL**             | 52                       | Coût de fonctionnement total                                                        |
<!-- TBLFM: @>$2=sum(@I..@-1) -->

### A quai

| Poste de dépense      | **Coût Journalier (po)** | **Détails**                                                                         |
| --------------------- | ------------------------ | ----------------------------------------------------------------------------------- |
| Salaires Équipage     | 36                       | Aéromarin (2 po x10) / Maître d'équipage (3 po) / Cocher (3 po) / Capitaine (10 po) |
| Vivres Équipage       | 5                        | 13 bouches à nourrir (qualité standard)                                             |
| Vivres Hippogriffes   | 4                        | 4 hippogriffes (viande fraîche / soins)                                             |
| Maintenance & Khayolt | 5                        | Matériel, réparations et nutriments                                                 |
| **TOTAL**             | 50                       | oût de fonctionnement total                                                         |
<!-- TBLFM: @>$2=sum(@I..@-1) -->

## Frais fixes par décade

| Poste de dépense          | Coût par décade (po) | Détails                                        |
| ------------------------- | -------------------- | ---------------------------------------------- |
| Comptoir d'Ikhâr          | 150                  | Entretien des bâtiments et logistique Khayolt. |
| Gardes de la capitainerie | 80                   | 2 po/jour x4                                   |
| Comptoirs                 | 553                  |                                                |
| La Comptable              | 520                  | En vol (route Village Skiam, depuis J+32)      |
| Nef des PJs (Le Kernös)   | 520                  | En vol (terres boréales, depuis J+23)          |
| Le Colporteur             | 520                  | En vol (route Carcéa)                          |
| [Sans nom] (Brottin)      | 520                  | En vol (route Madi'Maluk, depuis J+32)         |
| **TOTAL**                 | 2863                 | **Total des frais fixes (4 gondolfières)**     |
<!-- TBLFM: @>$2=sum(@I..@-1) -->

## Frais de comptoirs par décade

- Gérant : 3 po/jour
- Gardes : 2 po/jour chacun
- Manouvriers : 1 po/jour chacun

| Comptoir   | Salaires par décade (Gérant + 2 Gardes + 4 manouvriers) | Loyer & Taxes Locales par décade | Détails                                                                          |
| ---------- | ------------------------------------------------------- | -------------------------------- | -------------------------------------------------------------------------------- |
| Carcéa     | 110                                                     | 200                              | **L'Empire est gourmand :** Taxes impériales élevées, pots-de-vin aux douaniers. |
| Madi'Maluk | 143                                                     | 100                              | **Compétition féroce :** Loyers de quai, "taxe de guilde" locale.                |
| **TOTAL**  | 253                                                     | 300                              | TOTAL : 563                                                                      |
<!-- TBLFM: @>$2=sum(@I..@-1) -->
<!-- TBLFM: @>$3=sum(@I..@-1) -->

### Frais de comptoirs détails

| Type de Territoire         | Salaires (Garde : 2po/jour, Gérant : 3 po/jour) par décade | Loyer & Taxes Locales (po par décade) | Description                                             |
| -------------------------- | ---------------------------------------------------------- | ------------------------------------- | ------------------------------------------------------- |
| **Provinces Impériales**   | 110                                                        | 200                                   | Haute sécurité. Taxes administratives lourdes.          |
| **Cités États Naines**     | 110                                                        | 190                                   | Solide et fiable. Affinité avec les nains.              |
| **Marches Impériales**     | 143 (Prime de risque +30%)                                 | 100                                   | Zone de guerre potentielle. Salaires + élevés (risque). |
| **Protectorats**           | 110                                                        | 150                                   | Mix entre diplomatie et commerce libre.                 |
| **Territoires Extérieurs** | 165 (Prime de risque +50%)                                 | 60                                    | Dangereux. Peu de taxes, mais recrutement cher.         |
# Revenus par décade

## Carcéa : 

| **Poste**                      | **Flux Financier (po)** |
| ------------------------------ | ----------------------- |
| **Bénéfice Net**               | 1750                    |
| **Revenus : Comptoir d'Ikhâr** | 50                      |
| **Frais fixes**                | -2863                   |
| **SOLDE GLOBAL**               | -1063                   |
<!-- TBLFM: @>$2=sum(@I..@-1) -->

Route seule : déficitaire. Combinée avec Madi'Maluk, la perte tombe à ~246 po/décade.
## Madi'Maluk

| **Poste**                      | **Flux Financier (po)** |
| ------------------------------ | ----------------------- |
| **Bénéfice Net**               | 1400                    |
| **Revenus : Comptoir d'Ikhâr** | 50                      |
| **Frais fixes**                | -2863                   |
| **SOLDE GLOBAL**               | -1413                   |
<!-- TBLFM: @>$2=sum(@I..@-1) -->

Route seule : déficitaire. Combinée avec Carcéa, la perte tombe à ~246 po/décade.

## Carcéa + Madi'Maluk (combiné)

Sur 3 décades (cycle naturel : 2 voyages Carcéa × 1750 po + 3 voyages Madi'Maluk × 1400 po) :

| **Poste**                        | **Flux Financier (po)** |
| -------------------------------- | ----------------------- |
| **Revenus Carcéa × 2**           | +3500                   |
| **Revenus Madi'Maluk × 3**       | +4200                   |
| **Revenus Comptoir Ikhâr × 3**   | +150                    |
| **Frais fixes × 3 décades**      | -8589                   |
| **SOLDE SUR 3 DÉCADES**          | -739                    |
| **SOLDE PAR DÉCADE**             | **-246**                |

La compagnie est presque à l'équilibre. L'ouverture du comptoir de Village Skiam permettrait de basculer en positif.