# :partying_face: Pseudo-Party

Heute werden wir mit Pseudo-Klasses stylen und ein... yay!

Das Tagesziel:

1. [Pseudo-Input](https://github.com/AmyraRadwan/Pseudo-Class-Party/tree/main#1-input)

   - [Was sind Pseudo-Klassen?](https://github.com/AmyraRadwan/Pseudo-Class-Party#face_with_spiral_eyes-was-sind-pseudo-klassen)
   - [Was sind Pseudo-Elemente?](https://github.com/AmyraRadwan/Pseudo-Class-Party#face_with_spiral_eyes-was-sind-pseudo-elemente)

2. [Pseudo-Index]()

   - [Tolle Pseudo-Klassen]()
   - [Tolle Pseudo-Elemente]()

Auf geht's!

# 1. Pseudo-Input

## :face_with_spiral_eyes: Was sind Pseudo-Klassen?

CSS Pseudo-Klassen sind Keywords mit einem Doppelpunkt davor, die sich auf bestimmte Zustände von Elementen beziehen. Bei `:hover` wird z.B. ein Maus abhängiger Zustand angesprochen. Pseudo-Klassen bestehen aus einem Doppelpunkt `:` gefolgt von einem Namen (z.B., `:hover`).

### Syntax

```
selector:pseudo-class {
  property: value;
}
```

Es gibt funktionale Pseudo-Klassen mit Klammern dahinter die Argumente enthalten (z.B., `:dir()`). Das Element auf das sich die Pseudo-Klasse bezieht nennt man _anchor element_ (z.B., `button` bei `button:hover`).

Mit Pseudo-Klassen lassen sich nicht nur Elemente in Relation zum inhaltlichen HTML Dokumentaufbau stylen sondern auch in Relation zu externen Faktoren wie die Interaktion von Nutzer\*innen (z.B., `:visited`), den Status des Inhalts (z.B., `:checked`) oder die Position der Maus (z.B., `:hover`).

## :face_with_spiral_eyes: Was sind Pseudo-Elemente?

CSS Pseudo-Elemente sind Keywords die zu einem Selektor hinzugefügt werden um damit einen speziellen Teil des Elements zu stylen. `::first-line` z.B. wird benutzt um die erste Zeile eines Paragraphen zu stylen. Pseudo-Elemente bestehen aus zwei Doppelpunkten `::` gefolgt von dem Namen (z.B., `::marker`).

### Syntax

```
selector::pseudo-element {
  property: value;
}
```

Die ersten Pseudo-Klassen wurden 1996 mit CSS1 herausgebracht. Pseudo soll hier soviel bedeuten wie falsch, unreal, oder fake. Der Prefix Pseudo- wird somit verwendet um Klassen und Elemente zu referenzieren die nicht "real" sind. Nicht real bedeutet in dem Kontext nicht Teil des DOM (Document Object Model) sondern virtuell erzeugte Elemente/Klassen die nur zu styling Zwecken kreiert werden.

# 2. Pseudo-Index
