# TradingView PineScript

My Pine Script code for TradingView: indicators and strategies.

## Structure

| Folder | Contents |
|---|---|
| [Published](Published/) | Finished, tested scripts published on TradingView |
| [Work-in-progress](Work-in-progress/) | Scripts under active development |
| [Experimental](Experimental/) | Ideas, prototypes and tests |

## Script lifecycle

```
Experimental  →  Work-in-progress  →  Published
```

To move a script from one folder to another in Working Copy: long-press the file → **Move**, then **Commit** + **Push**. The file's history is preserved.

## Conventions

- `.pine` extension for every script
- File names without spaces or accents: `rsi-divergence.pine`, `ema-cross-strategy.pine`
- A header at the top of every script:

```pine
// Name        : RSI Divergence
// Version     : 1.0
// Description : Detects divergences between price and RSI
// TradingView : (publication link, if published)

//@version=6
indicator("RSI Divergence", overlay = false)
```
