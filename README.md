_We are creating mnemonic German word lists with 1296, 1626, 2048 and 7776 words. Contributions to the shorter lists are welcome until May 7, 2021 – read on if you're good in German._

# Mnemonische deutsche Wortlisten

## Was ist Diceware?

"Diceware ist eine einfache Methode, sichere und leicht erinnerbare Passwörter und Passphrasen mit Hilfe eines oder mehrerer Würfel zu erzeugen." ([Wikipedia](https://de.wikipedia.org/wiki/Diceware))

Da die Verwendkarkeit von Diceware von der Qualität der Wortlisten abhängt, sollte eine Wortliste aus möglichst bekannten und leicht merkbaren Wörtern bestehen. Die bekannteste deutsche Diceware-Wortliste [diceware_german.txt](https://theworld.com/~reinhold/diceware_german.txt) erfüllt diese Bedingungen nicht. Sie enthält Sonderzeichen, Zahlen, Buchstabenfolgen, die weder eine Abkürzung noch ein Wort sind (z. B. zv, zw, zx, zy, zz, zzz und zzzz) und Buchstabenfolgen, die Wörtern ähneln, jedoch selbst keine Wörter der deutschen Sprache sind.

Wir möchten deshalb eine neue Liste für die deutsche Sprache zusammenstellen. Dabei orientieren wir uns an den Ausarbeitungen der [EFF](https://www.eff.org/de/deeplinks/2016/07/new-wordlists-random-passphrases), die bereits eine kurze (1296 Wörter) und eine lange (7776 Wörter) Wortliste in englischer Sprache erstellt hat.

## Monero

Viele Kryptowährungen nutzen mnemonische Wortlisten, um eine Wallet zu generieren. Entgegen der Konvention enthält die [deutsche Wortliste bei Monero](https://github.com/monero-project/monero/blob/master/src/mnemonics/german.h) auch Großbuchstaben, Sonderzeichen wie ä, ö, ü und ß (wobei derartige Sonderzeichen auch in manch anderen Wortlisten enthalten sind), ein paar weniger geläufige Wörter und auch Eigennamen. Auch wenn die Einführung einer neuen Wortliste mit Aufwand verbunden ist, halten wir diese neue Liste langfristig für besser.

## BIP39

Trotz einer großen deutschsprachigen Community existiert bislang keine deutsche Wortliste für Kryptowährungen wie z. B. Bitcoin und Ethereum, die den Bitcoin-Wortlistenstandard [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md) verwenden. Das möchten wir ändern.

## Neue Listen

Wir schlagen vor, die Tabelle `de_2048.md` als Grundlage für folgende drei Listen zu verwenden:

- kurze Diceware-Liste (1296 Wörter)
- Wortliste für Monero (1626 Wörter)
- BIP39-Wortliste (2048 Wörter)

Dabei sollen folgende Regeln gelten:

1. Wörter sind vier bis acht Zeichen lang.
2. Wörter können nach Eingabe der ersten vier Buchstaben eindeutig bestimmt werden.
3. Kein Wort enthält die Zeichen ä, ö, ü und ß.
4. Es sollten möglichst nur bekannte Substantive, Verben und Adjektive enthalten sein, und zwar in ihrer Grundform (Substantive im Singular, Verben im Infinitiv, Adjektive in ihrer unflektierten Form).
5. Keine Eigennamen, Regionen, Religionen, Vereinigungen oder Personen.
6. Keine besonders negativ konnotierten Wörter.
7. Das "männliche" grammatikalische Geschlecht wird bevorzugt. (Dies ist Standard bei BIP39.)

Hinzu kommt ein weiterer Entwurf einer langen Diceware-Wortliste, der jedoch unabhängig von den zuvor genannten ist und noch in Arbeit ist. Er wird voraussichtlich am oder nach dem 8. Mai 2021 veröffentlicht. Für sie sollen folgende Regeln gelten:

1. Wörter sind drei bis zwölf Zeichen lang.
2. Kein Wort enthält die Zeichen ä, ö, ü und ß.
3. Es sollten möglichst nur bekannte Substantive, Verben und Adjektive enthalten sein, und zwar in ihrer Grundform (Substantive im Singular, Verben im Infinitiv, Adjektive in ihrer unflektierten Form).
4. Keine Eigennamen, Regionen, Religionen, Vereinigungen oder Personen.
5. Keine besonders negativ konnotierten Wörter.
6. Das "männliche" grammatikalische Geschlecht wird bevorzugt. (Dies ist Standard bei BIP39.)

Wir haben bereits eine lange Liste mit 7776 Wörtern (`de_7776_old.txt`) erstellt, die ab dem fünften Buchstaben eindeutig sind und in manchen Punkten von den oben genannten Regeln abweicht. Wir möchten sie nicht weiter verwenden, aber vielleicht ist sie für dich nützlich.

## Mitarbeit

**Bis zum 7. Mai 2021 um 14:00 CET** sind Pull-Requests mit Verbesserungsvorschlägen der kurzen Liste (`de_2048.md`) willkommen. Danach werden wir sie als Version 1.0 markieren und als Pull Request in die Repositorys von [Bitcoin (BIP39)](https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md) und [Monero](https://github.com/monero-project/monero/blob/master/src/mnemonics/) einreichen.

Der Fokus von Verbesserungsvorschlägen sollte auf den Wörtern selbst liegen. Die Auswahl, welche der Wörter in die Listen für BIP39, Diceware und Monero kommen, behalten wir uns selbst vor.

Reicht neue Wortvorschläge bitte wie folgt an passender Stelle ein:

`| neueswort	|		|		|		|		|`
