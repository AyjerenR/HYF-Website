---
aliases:
- migrate-from-jekyl
authors:
- FP, FD, LK, IR, AR
categories:
- themes
- syntax
date: "2019-03-11"
description: Sample article showcasing basic Markdown syntax and formatting for HTML
  elements.
images:
- markdown-syntax.jpg
series:
- Themes Guide
tags:
- markdown
- css
- html
- themes
title: About Data Science
---

Einführung in R und Data Science


# Daten sammeln & Web Scraping 

Habt ihr schon einmal Daten aus dem Internet händisch abgeschrieben? In diesem Kurs lernt ihr, wie ihr größere Mengen von Daten schnell, einfach und legal mithilfe von Algorithmen herunterladen könnt, ohne dafür einen Stift in die Hand nehmen zu müssen oder Copy-Paste zu drücken. Dabei lernt ihr zuerst Grundlagen von HTML kennen - der Sprache, in der die Struktur von Webseiten geschrieben wird. Mithilfe von HTML und der Open Source-Software R, die ihr bereits am ersten Kurstag kennengelernt habt, lernen wir dann, einzelne Inhalte auf Webseiten gezielt anzusprechen, herunterzuladen und in einem Datensatz abzuspeichern. 
Web Scraping wird nicht nur in der Wissenschaft, sondern auch in Unternehmen immer häufiger verwendet, um kostengünstig, schnell und systematisch Informationen zu wichtigen Themen zu erhalten.


# Daten analysieren und darstellen


# Daten präsentieren & Shiny Apps

Wer interessante Ergebnisse und schöne Visualisierungen zu bieten hat, will diese natürlich auch präsentieren! Wir zeigen euch wie ihr, im letzten Schritt unseres Kurses, mit Hilfe von R Shiny App die Resultate eurer Arbeit präsentierbar macht. Hier verbinden wir alles zuvor gelernte, die essentiellen Basics, eure gesammelten Daten, sowie deren Analyse und Visualisierung, in einem Tool. Im Verlauf des Kurses werdet ihr ein eigenes Gruppenprojekt umsetzen und uns das finale Produkt dann am letzten Tag präsentieren. 







Data Science (von englisch data „Daten“ und science „Wissenschaft“, im Deutschen auch Datenwissenschaft) bezeichnet generell die Extraktion von Wissen aus Daten.
<!--more-->

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Data Science ist ein interdisziplinäres Wissenschaftsfeld, welches wissenschaftlich fundierte Methoden, Prozesse, Algorithmen und Systeme zur Extraktion von Erkenntnissen, Mustern und Schlüssen sowohl aus strukturierten als auch unstrukturierten Daten ermöglicht.

Der Studiengang Data Science verwendet Techniken und Theorien aus den Fächern Mathematik, Statistik und Informationstechnologie, einschließlich der Signalverarbeitung, verwendet Wahrscheinlichkeitsmodelle des maschinellen Lernens, des statistischen Lernens, der Programmierung, der Datentechnik, der Mustererkennung, der Prognostik, der Modellierung von Unsicherheiten und der Datenlagerung.


## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>


[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Inline&nbsp;&nbsp;&nbsp;     | Markdown&nbsp;&nbsp;&nbsp;  | In&nbsp;&nbsp;&nbsp;                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code`     |

## Code Blocks

#### Code block with backticks

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Item
1. First Sub-item
2. Second Sub-item

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.

