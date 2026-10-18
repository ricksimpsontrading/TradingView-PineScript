# TradingView PineScript

Mes scripts Pine Script pour TradingView : indicateurs et stratégies.

## Organisation

| Dossier | Contenu |
|---|---|
| [Published](Published/) | Scripts terminés, testés et publiés sur TradingView |
| [Work-in-progress](Work-in-progress/) | Scripts en cours de développement |
| [Experimental](Experimental/) | Idées, prototypes et tests |

## Cycle de vie d'un script

```
Experimental  →  Work-in-progress  →  Published
```

Pour faire passer un script d'un dossier à l'autre dans Working Copy : appui long sur le fichier → **Move**, puis **Commit** + **Push**. L'historique du fichier est conservé.

## Conventions

- Extension `.pine` pour chaque script
- Noms sans espaces ni accents : `rsi-divergence.pine`, `ema-cross-strategy.pine`
- Un en-tête en haut de chaque script :

```pine
// Nom         : RSI Divergence
// Version     : 1.0
// Description : Détecte les divergences entre le prix et le RSI
// TradingView : (lien de publication, si publié)

//@version=6
indicator("RSI Divergence", overlay = false)
```
