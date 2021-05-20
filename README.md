# Titel des Tutorials

Hier kommen optionale Einstellungen für das Tutorial hin:
- Hinweise immer einbleden: @explicitHints
- Unterschiede zwischen den Schritten in Codeblöcken anzeigen: @diffs
- alle verfügbaren Blöcke anzeigen: @flyoutOnly

### @diffs true
### @flyoutOnly true

Zusätzlich verfügbare Blöcke definieren:
```ghost
let x = 0
```

Startcode definieren:
```template
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Heart)
})
```

## Der erste Schritt @unplugged

Willkomen zum Tutorial.

Geschrieben wird in anlehnung an [MarkDown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### Formatierungen:
- *Kursiv*
- **Fett**
- ***Fett-Kursiv***

## Der zweite Schritt @fullscreen

Als alternative zu `|@explicitHints|` kann für einzelne schritte auch `|@fullscreen|` gesetzt werden.

```
```

Text hinter den Blöcken oder einem Bild wird auch im Hinweis angezeigt.


## Dritter Schritt
Setze einen `||led:plot||` Block in die `||basic:Dauerhaft||` Schleife.

```blocks
basic.forever(function () {
   led.plot(0, 0)
})
```

## Vierter schritt mit Änderung am Code

Wir fügen noch einen `||basic:zeige Symbol||` Block hinzu

```blocks
basic.forever(function () {
   led.plot(0, 0)
   basic.showIcon(IconNames.Heart)
})
```


## 5) Einen Codeblock hervorheben

Wir fügen noch einen `||basic:zeige Symbol||` Block hinzu

```blocks
basic.forever(function () {
   led.plot(0, 0)
   // @highlight
   basic.showIcon(IconNames.Heart)
})
```

## 6) Bilder

Bilder können über öffentliche Links eingebunden werden.

![Animation A und B Buttons](https://github.com/Amerlander/tutorials/raw/master/calliope/tutorials/03_smiley_button_animation.gif)


## 7) Links

 Du hast Fragen? Besuche das [Forum](https://forum.calliope.cc) und hole dir Hilfe aus der Community

Oder mit sichtbarem Link: https://forum.calliope.cc

## 8) Tutorial sperren
Um das Tutorial zu sperren und zu verhindern, dass User das Tutorial verlassen können kann die URL vor dem Teilen angepasst werden:

**?lockedEditor=1** vor **#tutorial:** setzen:
https://makecode.calliope.cc/#tutorial:84629-36395-36880-66802 zu https://makecode.calliope.cc/?lockedEditor=1#tutorial:84629-36395-36880-66802
