---
authors:
- Franziska Pradel
- Franziska Deeg
- Lea Kaftan
date: "2019-03-08"
description: Guide to emoji usage in Hugo
images:
- emoji-support.jpg
tags:
- emoji-support
title: Preliminary Schedule - Kurs Outline
---


# Einf?hrung in R und Data Science


# Daten sammeln & Web Scraping 

Habt ihr schon einmal Daten aus dem Internet h?ndisch abgeschrieben? In diesem Kurs lernt ihr, wie ihr gr??ere Mengen von Daten schnell, einfach und legal mithilfe von Algorithmen herunterladen k?nnt, ohne daf?r einen Stift in die Hand nehmen zu m?ssen oder Copy-Paste zu dr?cken. Dabei lernt ihr zuerst Grundlagen von HTML kennen - der Sprache, in der die Struktur von Webseiten geschrieben wird. Mithilfe von HTML und der Open Source-Software R, die ihr bereits am ersten Kurstag kennengelernt habt, lernen wir dann, einzelne Inhalte auf Webseiten gezielt anzusprechen, herunterzuladen und in einem Datensatz abzuspeichern. 
Web Scraping wird nicht nur in der Wissenschaft, sondern auch in Unternehmen immer h?ufiger verwendet, um kosteng?nstig, schnell und systematisch Informationen zu wichtigen Themen zu erhalten.


# Daten analysieren und darstellen


# Daten pr?sentieren & Shiny Apps

Wer interessante Ergebnisse und sch?ne Visualisierungen zu bieten hat, will diese nat?rlich auch pr?sentieren! Wir zeigen euch wie ihr, im letzten Schritt unseres Kurses, mit Hilfe von R Shiny App die Resultate eurer Arbeit pr?sentierbar macht. Hier verbinden wir alles zuvor gelernte, die essentiellen Basics, eure gesammelten Daten, sowie deren Analyse und Visualisierung, in einem Tool. Im Verlauf des Kurses werdet ihr ein eigenes Gruppenprojekt umsetzen und uns das finale Produkt dann am letzten Tag pr?sentieren. 


Emoji can be enabled in a Hugo project in a number of ways. 
<!--more-->
The [`emojify`](https://gohugo.io/functions/emojify/) function can be called directly in templates or [Inline Shortcodes](https://gohugo.io/templates/shortcode-templates/#inline-shortcodes). 

To enable emoji globally, set `enableEmoji` to `true` in your site’s [configuration](https://gohugo.io/getting-started/configuration/) and then you can type emoji shorthand codes directly in content files; e.g.


<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>

The [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) is a useful reference for emoji shorthand codes.

***

**N.B.** The above steps enable Unicode Standard emoji characters and sequences in Hugo, however the rendering of these glyphs depends on the browser and the platform. To style the emoji you can either use a third party emoji font or a font stack; e.g.

{{< highlight html >}}
.emoji {
font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
}
{{< /highlight >}}

{{< css.inline >}}
<style>
.emojify {
	font-family: Apple Color Emoji,Segoe UI Emoji,NotoColorEmoji,Segoe UI Symbol,Android Emoji,EmojiSymbols;
	font-size: 2rem;
	vertical-align: middle;
}
@media screen and (max-width:650px) {
    .nowrap {
	display: block;
	margin: 25px 0;
}
}
</style>
{{< /css.inline >}}
