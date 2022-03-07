# Mnemonische deutsche Wortlisten

## Was ist Diceware?

"Diceware ist eine einfache Methode, sichere und leicht erinnerbare Passwörter und Passphrasen mit Hilfe eines oder mehrerer Würfel zu erzeugen." ([Wikipedia](https://de.wikipedia.org/wiki/Diceware))

Da die Verwendkarkeit von Diceware von der Qualität der Wortlisten abhängt, sollte eine Wortliste aus möglichst bekannten und leicht merkbaren Wörtern bestehen. Die bekannteste deutsche Diceware-Wortliste [diceware_german.txt](https://theworld.com/~reinhold/diceware_german.txt) erfüllt diese Bedingungen nicht. Sie enthält Sonderzeichen, Zahlen, Buchstabenfolgen, die weder eine Abkürzung noch ein Wort sind (z. B. zv, zw, zx, zy, zz, zzz und zzzz) und Buchstabenfolgen, die Wörtern ähneln, jedoch selbst keine Wörter der deutschen Sprache sind.

Wir möchten deshalb eine neue Liste für die deutsche Sprache zusammenstellen. Dabei orientieren wir uns an den Ausarbeitungen der [EFF](https://www.eff.org/de/deeplinks/2016/07/new-wordlists-random-passphrases), die bereits eine kurze (1296 Wörter) und eine lange (7776 Wörter) Wortliste in englischer Sprache erstellt hat.

## Monero

Viele Kryptowährungen nutzen mnemonische Wortlisten, um eine Wallet zu generieren. Entgegen der Konvention enthält die [deutsche Wortliste bei Monero](https://github.com/monero-project/monero/blob/master/src/mnemonics/german.h) auch Großbuchstaben, Sonderzeichen wie ä, ö, ü und ß (wobei derartige Sonderzeichen auch in manch anderen Wortlisten enthalten sind), ein paar weniger geläufige Wörter und auch Eigennamen. Auch wenn die Einführung einer neuen Wortliste mit Aufwand verbunden ist, halten wir diese neue Liste langfristig für besser. Dazu haben wir Kontakt mit dem Monero-Entwicklungsteam aufgenommen.

## BIP39

Trotz einer großen deutschsprachigen Community existiert bislang keine offizielle deutsche Wortliste für Kryptowährungen wie z. B. Bitcoin und Ethereum, die den Bitcoin-Wortlistenstandard [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039/bip-0039-wordlists.md) verwenden. Derzeit läuft dazu jedoch eine [Diskussion](https://github.com/bitcoin/bips/pull/1071).

## de-2048

Wir haben die Tabelle `history/de_2048.md` als Grundlage für folgende drei Listen verwendet:

- kurze Diceware-Liste (1296 Wörter)
- Wortliste für Monero (1626 Wörter)
- BIP39-Wortliste (2048 Wörter)

Dabei galten folgende Regeln:

1. Wörter sind vier bis acht Zeichen lang.
2. Wörter können nach Eingabe der ersten vier Buchstaben eindeutig bestimmt werden.
3. Kein Wort enthält die Zeichen ä, ö, ü und ß.
4. Es sollten möglichst nur bekannte Substantive, Verben und Adjektive enthalten sein, und zwar in ihrer Grundform (Substantive im Singular, Verben im Infinitiv, Adjektive in ihrer unflektierten Form).
5. Keine Eigennamen, Regionen, Religionen, Vereinigungen oder Personen.
6. Keine besonders negativ konnotierten Wörter.
7. Das "männliche" grammatikalische Geschlecht wird bevorzugt. (Dies ist Standard bei BIP39.)

## de-7776

Die Wortliste `de-7776` eignet sich als Diceware-Wortliste für fünf Würfel. Sie ist unabhängig von den zuvor genannten, die Wörter sind ab dem fünften Buchstaben eindeutig. Darüber hinaus orientiert sie sich größtenteils, jedoch nicht hundertprozentig, an diesen Regeln:

1. Wörter sind drei bis zwölf Zeichen lang.
2. Kein Wort enthält die Zeichen ä, ö, ü und ß.
3. Es sollten möglichst nur bekannte Substantive, Verben und Adjektive enthalten sein, und zwar in ihrer Grundform (Substantive im Singular, Verben im Infinitiv, Adjektive in ihrer unflektierten Form).
4. Keine Eigennamen, Regionen, Religionen, Vereinigungen oder Personen.
5. Keine besonders negativ konnotierten Wörter.
6. Das "männliche" grammatikalische Geschlecht wird bevorzugt. (Dies ist Standard bei BIP39.)

## License

This work is dual-licensed under Unlicense and CC0. You can choose between one of them if you use this work.