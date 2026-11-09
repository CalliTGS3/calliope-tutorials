# Klickzähler

## Einleitung @unplugged

Um einfach Dinge oder Personen zu zählen, verwendet man oft sogenannte Handzähler oder Klickzähler.
Man kann solche Handzähler zum Beispiel benutzen, um die Personen in einem Raum zu zählen, auch wenn ständig jemand hineingeht oder herauskommt.


## Schritt 1 @fullscreen

Auf dem 5x5 Display des Calliope mini wollen wir die gezählten Dinge oder Personen anzeigen.
Wir nehmen aus dem Bereich ``||basic:Grundlagen ||`` den Block ``||basic: Zeige Zahl||``. <br>
Dieser wird in den Block ``||basic:Dauerhaft||`` geschoben. Im Simulator wird dir nun die Zahl angezeigt, welche im Block ``||basic: Zeige Zahl||`` steht. <br>
Diese Zahl wollen wir mit den Knöpfen A und B des Calliope mini verändern können. 

```blocks
basic.forever(function () {
basic.showNumber(0)
})
```
