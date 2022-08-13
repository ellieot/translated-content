---
title: margin-bottom
slug: Web/CSS/margin-bottom
tags:
  - CSS
  - CSS Referenz
translation_of: Web/CSS/margin-bottom
---
{{ CSSRef() }}

## Übersicht

Die `margin-bottom` Eigenschaft legt den unteren Außenabstand eines Elements fest. Negative Werte sind erlaubt.

- Standardwert: `0`
- Anwendbar auf: alle Elemente, in Tabellen nur auf Elemente mit [display](/de/CSS/display "de/CSS/display") `table`, `table-caption` und `inline-table`
- Vererbbar: Nein
- Prozentwerte: beziehen sich immer auf die [Breite](/de/CSS/width "de/CSS/width") des umschließenden Blocks.
- Medium: visuell
- berechneter Wert: eine Prozentzahl wie festgelegt oder die absolute Länge.

## Syntax

    margin-bottom: <Längenangabe> | <Prozentzahl> | auto | inherit

### Werte

- \<Längenangabe>
  - : Legt eine bestimmte [Länge](/de/CSS/Einheiten#L.c3.a4ngen "de/CSS/Einheiten#L.c3.a4ngen") fest. Negative Werte sind erlaubt.
- \<Prozentzahl>
  - : Ein [prozentualer](/de/CSS/Einheiten#Prozent "de/CSS/Einheiten#Prozent") Wert, der sich auf die Breite des umschließenden Blocks (_containing block_) bezieht. Negative Werte sind erlaubt.
- auto
  - : `auto` wird von einem passendem Wert ersetzt, wobei die horizontalen bzw. vertikalen Dimensionen berücksichtigt werden.
- inherit
  - : Der Wert des Elternelements wird geerbt.

## Beispiele

    .content { margin-bottom: 5%; }
    .sidebox { margin-bottom: 10px; }
    .logo    { margin-bottom: -5px; }

## Browser Kompatibilität

| Browser           | ab Version | `auto` Wert       |
| ----------------- | ---------- | ----------------- |
| Internet Explorer | 3.0        | 6.0 (strict mode) |
| Firefox (Gecko)   | 1.0 (1.0)  | 1.0 (1.0)         |
| Opera             | 3.5        | 3.5               |
| Safari (WebKit)   | 1.0 (85)   | 1.0 (85)          |

## Spezifikation

- [CSS 2.1 Visual formatting #margin](http://www.w3.org/TR/CSS21/box.html#margin-properties)

## Siehe auch

- [`margin`](/de/CSS/margin "de/CSS/margin"), [`margin-right`](/de/CSS/margin-right "de/CSS/margin-right"), [`margin-top`](/de/CSS/margin-top "de/CSS/margin-top"), [`margin-left`](/de/CSS/margin-left "de/CSS/margin-left")
- [`-moz-margin-start`](/de/CSS/-moz-margin-start "de/CSS/-moz-margin-start"), [`-moz-margin-end`](/de/CSS/-moz-margin-end "de/CSS/-moz-margin-end")
- [`padding`](/de/CSS/padding "de/CSS/padding")

{{ languages( { "en": "en/CSS/margin-bottom", "ja": "ja/CSS/margin-bottom" } ) }}