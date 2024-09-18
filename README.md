# Spickzettel

# Übersicht HTML und CSS Befehle

Hier findet ihr eine fortlaufende Übersicht über unsere bislang kennengelernten Elemente in HTML und die CSS Eigenschaften. Die Übersicht wird in den nächsten Tagen immer um die neuen Werte ergänzt.
<br><br>

## Übersicht
1. [HTML-Elemente](#html-elemente)
   - [Grundstruktur](#0-grundstruktur-einer-html-seite)
   - [Head-Elemente](#1-head-elemente-erscheinen-nicht-auf-der-seite-sondern-nur-infos-für-den-browser-und-google)
   - [Body-Elemente](#2-body-elemente-der-sichtbare-bereich-eurer-webseite)
       - [Block Elemente](#21-block-elemente-nehmen-die-gesamte-breite-des-elternelements-ein)
       - [Inline Elemente](#22-inline-elemente-nehmen-nur-die-breite-ihres-inhalts)
2. [CSS-Eigenschaften](#css-eigenschaften)
    <!-- - [Textformatierung](#textformatierung)
    - [Größen](#größen)
    - [Hintergrund](#hintergrund) -->
  
3. [Nützliche Tastenkombinationen](#nützliche-tastenkombinationen-windows)

<br><br><br>

## HTML-Elemente

**HTML** steht für ***Hypertext Markup Language*** und ist eine Auszeichnungssprache, die verwendet wird, um den Inhalt einer Webseite zu strukturieren und zu kennzeichnen. Mit HTML können verschiedene Elemente wie Überschriften, Absätze, Bilder und Links definiert werden. Diese Elemente können dann mit CSS gestaltet werden, um eine ansprechende Webseite zu erstellen. <br>
Folgende Elemente haben wir bislang kennengelernt: 

### 0. Grundstruktur einer HTML-Seite

| HTML-Element    | Beschreibung                                    | Beispiel                              |
|:---------------:|:-----------------------------------------------:|:-------------------------------------:|
| `<!DOCTYPE html>`| Definiert den Dokumenttyp und die HTML-Version  | `<!DOCTYPE html>`                     |
| `<html>`        | Wurzelelement einer HTML-Seite                  | `<html>...</html>`                    |
| `<head>`        | Enthält Metadaten und Links zu Stylesheets etc. | `<head>...</head>`                    |
| `<body>`        | Enthält den sichtbaren Inhalt der Webseite      | `<body>...</body>`                    |
<br>

***Beispiel***

```
<!DOCTYPE html>
<html>
    <head>...</head>
    <body>...</body>
</html>
```

<br>

### 1. Head-Elemente (erscheinen nicht auf der Seite, sondern nur Infos für den Browser und Google)

| HTML-Element | Beschreibung                                           | Beispiel                                 |
|:------------:|:------------------------------------------------------:|:----------------------------------------:|
| `<title>`    | Titel der Webseite, erscheint in der Browser-Tab-Leiste | `<title>Meine Webseite</title>`          |
| `<meta>`     | Metainformationen, z.B. Zeichensatz oder Keywords       | `<meta charset="UTF-8">`                 |
| `<link>`     | Verknüpfung mit externen Dateien, z.B. CSS-Stylesheets  | `<link rel="stylesheet" href="style.css">`|


### 2. Body-Elemente (der sichtbare Bereich eurer Webseite)
    
#### 2.1 Block-Elemente (nehmen die gesamte Breite des Elternelements ein)

| HTML-Element  | Beschreibung                               | Beispiel                             |
|:-------------:|:------------------------------------------:|:------------------------------------:|
| `<h1>`...`<h6>` | Überschriften                            | `<h1>Überschrift</h1>`               |
| `<p>`          | Textabsatz                                | `<p>Textabsatz</p>`                  |
 | `<ul>`         | Ungeordnete Liste                         | `<ul><li>Element</li></ul>`          |
| `<ol>`         | Geordnete Liste                           | `<ol><li>Erstes Element</li></ol>`   |
| `<li>`         | Listenelement                             | `<li>Listeneintrag</li>`             |
| `<div>`        | Containerelement                          | `<div>Inhalt</div>`                  |

<!-- #####  zusätzliche semantische Containerelemente

| HTML-Element  | Beschreibung                               | Beispiel                             |
|:-------------:|:------------------------------------------:|:------------------------------------:|
| `<header>`    | Definiert den Kopfbereich eines Dokuments oder einer Sektion. | `<header>Kopfbereich</header>`       |
| `<main>`      | Hauptinhalt des Dokuments, sollte einzigartig sein. | `<main>Hauptinhalt</main>`           |
| `<footer>`    | Definiert den Fußbereich eines Dokuments oder einer Sektion. | `<footer>Fußbereich</footer>`        |
| `<section>`   | Thematisch zusammenhängender Bereich eines Dokuments. | `<section>Abschnitt</section>`       |
| `<nav>`       | Definiert eine Gruppe von Navigationslinks. | `<nav>Navigation</nav>`              |
| `<article>`   | Unabhängiger Artikel, der in sich geschlossen ist. | `<article>Artikel</article>`         | -->


   
#### 2.2 Inline Elemente (nehmen nur die Breite ihres Inhalts)

| HTML-Element | Beschreibung                    | Beispiel                              |
|:------------:|:-------------------------------:|:-------------------------------------:|
| `<a>`        | Hyperlink (intern, extern)      | `<a href="url">Linktext</a>`          |
| `<img>`      | Bild einfügen                                 | `<img src="url" alt="Bildbeschreibung">`  |
<!-- | `<br>`       | Spezielles leeres Element für Zeilenumbrüche  | `Dies ist ein Text<br>neue Zeile`         | -->


<br><br><br>
## CSS-Eigenschaften
**CSS** steht für ***Cascading Style Sheets*** und wird verwendet, um das Aussehen von HTML-Elementen auf einer Webseite zu definieren. Mit CSS können verschiedene Eigenschaften wie Farbe, Schriftart und Positionierung definiert werden. Durch die Trennung von Inhalt und Design wird das Ändern des Aussehens der Webseite einfacher, da nur das CSS geändert werden muss, ohne den HTML-Code zu bearbeiten.

## Selektoren
| Selektor              | Beschreibung                                          | Beispiel                            |
|-----------------------|-------------------------------------------------------|-------------------------------------|
| Elementselektor       | Wählt alle Elemente eines bestimmten Typs aus.        | `p { color: blue; }`                |
| Klassen-Selektor      | Wählt alle Elemente mit einer bestimmten Klasse aus.  | `.classname { color: red; }`        |
<!-- | Nachfahren-Selektor   | Wählt alle Elemente innerhalb eines bestimmten Elternteils aus. | `div p { color: green; }`          | -->
<!-- | `:hover`              | Pseudoklasse für den Hover-Zustand eines Elements.    | `a:hover { color: red; }`           | -->



 ### Textformatierung
| Eigenschaft       | Beschreibung                                   | Beispiel                        |
|-------------------|------------------------------------------------|---------------------------------|
| `color`           | Setzt die Textfarbe.                           | `color: blue;`                  |
| `font-size`       | Bestimmt die Schriftgröße.                     | `font-size: 16px;`              |
| `text-decoration` | Fügt Dekorationen wie Unterstreichungen hinzu. | `text-decoration: underline;`   |
| `font-weight`     | Definiert die Dicke der Schrift.               | `font-weight: bold;`            |
| `font-family`     | Bestimmt die Schriftart.                       | `font-family: Arial, sans-serif;`|
| `font-style`      | Legt den Stil der Schrift fest (z.B. kursiv).  | `font-style: italic;`           |

<!-- 
### Größen, Abstände und Rahmen (Boxmodel)
| Eigenschaft | Beschreibung                            | Beispiel              |
|-------------|-----------------------------------------|-----------------------|
| `width`     | Setzt die Breite eines Elements.        | `width: 100px;`       |
| `height`    | Bestimmt die Höhe eines Elements.       | `height: 200px;`      |
| `margin`    | Bestimmt den Außenabstand eines Elements. | `margin: 20px;`       |
| `padding`   | Setzt den Innenabstand eines Elements.  | `padding: 15px;`      |
| `border`    | Definiert die Rahmenlinie eines Elements. | `border: 1px solid black;` |

## Hintergrund
| Eigenschaft           | Beschreibung                                          | Beispiel                            |
|-----------------------|-------------------------------------------------------|-------------------------------------|
| `background-color`    | Legt die Hintergrundfarbe fest.                       | `background-color: yellow;`         | 
<!-- | `background-size`     | Bestimmt die Größe des Hintergrundbildes.             | `background-size: cover;`           |
| `background-repeat`   | Legt fest, ob und wie das Hintergrundbild wiederholt wird. | `background-repeat: no-repeat;`     |
| `background-position` | Definiert die Position des Hintergrundbildes.         | `background-position: center;`      |
| `background-attachment` | Legt fest, ob das Hintergrundbild scrollt oder fixiert ist. | `background-attachment: fixed;` | -->


<!-- ## Flex (erste Schritte)
| Eigenschaft      | Beschreibung                                            | Beispiel                        |
|------------------|---------------------------------------------------------|---------------------------------|
| `display`        | Legt den flexiblen Container fest und stellt so Kinder nebeneinander.    (Achtung: display wird nicht nur für flex verwendet!)                   | `display: flex;`                |
| `justify-content`| Bestimmt die Ausrichtung der flexiblen Elemente entlang der Hauptachse. (hier horizontal) | `justify-content: center;`      |
| `align-items`    | Bestimmt die Ausrichtung der flexiblen Elemente entlang der Querachse. (hier: vertikal) | `align-items: center;`          |
| `gap`            | Legt den Abstand zwischen den flexiblen Elementen fest. | `gap: 10px;`                    |
| `flex-wrap`      | Bestimmt, ob die flexiblen Elemente in einer einzigen Zeile oder in mehreren Zeilen angezeigt werden. | `flex-wrap: wrap;`              | -->

<!-- 
## Erweiterte CSS-Effekte
| Eigenschaft           | Beschreibung                                          | Beispiel                            |
|-----------------------|-------------------------------------------------------|-------------------------------------|
| `transition`          | Definiert Übergangseffekte zwischen zwei Zuständen eines Elements. | `transition: all 0.3s ease;`       |
| `box-shadow`          | Fügt einem Element einen Schatten hinzu.              | `box-shadow: 0px 4px 8px rgba(0,0,0,0.3);` | --> -->




<br><br><br>
## Nützliche Tastenkombinationen (Windows)

Es ist hilfreich einige Tastenkombinationen für häufige Handlungen zu lernen. Mit der Tastatur könnt ihr schneller arbeiten und es entstehen weniger Fehler als bei der Benutzung mit der Maus (Touchpad). Vielleicht seit ihr am Anfang etwas langsamer, aber auf lange Sicht lohnt sich das Lernen.


### Allgemeine Tastenkombinationen

Tastenkombinationen, die in **VS Code** und anderen Programmen funktionieren:

- Fenster wechseln --> `Alt` + `Tab`
- Kopieren        --> `STRG` + `c`
- Ausschneiden    --> `STRG` + `x`
- Einfügen        --> `STRG` + `v`
- Suchen          --> `STRG` + `f`
- Speichern       --> `STRG` + `s`
- alles markieren --> `STRG` + `a`


### VS-Code

Diese praktischen Kombinationen funktionieren nur in VS Code:
- `Alt` + `Pfeiltaste`  --> Zeilen verschieben, hoch/runter
- `Alt` + `z`           --> Zeilenumbruch anschalten/ausschalten
- `STRG`+ `#`           --> erzeugt einen Kommentar 
- `STRG`+ `l`           --> Zeile markieren


#### Emmet Abkürzungen in VS Code

Emmet sind Kurzformen, die VS Code zu Code umschreibt, hier einige kurze Beispiele für ***HTML***:
- `!`               --> erzeugt in einen Boilerplate-Code (Grundstruktur)
- `lorem50`         --> erzeugt einen Lorem-Text mit 50 Worten
- `div.box`         --> erzeugt eine `<div class="box">`
- `ul>li*3`         --> erzeugt eine `<ul>` mit 3 `<li>`Elementen
- `a{weiterlesen}`  --> erzeugt ein `<a href="">weiterlesen</a>`
- `section>img+p+a` --> erzeugt eine Sektion und darin ein `<img>`, `<p>`und ein `<a>`

Ihr könnt diese Elemente miteinander kombinieren und damit sehr umfangreiche Codeblöcke bauen. Benutzt diese aber erst, wenn ihr euch mit eurem html sicher seid. Je länger eure Kombinationen sind, desto leichter könnt ihr Fehler produzieren und den Überblick verlieren. Es gibt diese Emmet Abkürzungen auch für CSS. Einen (sehr) umfangreichen Überblick über die verschiedenen Möglichkeiten findet ihr hier:
***[Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)***
