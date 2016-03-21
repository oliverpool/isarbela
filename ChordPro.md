# ChordPro Datei

Ein ChordPro Datei ist einfach ein *.txt oder *.doc Datei, wo die Akkorde eine besondere Stelle haben. Hier ist ein Beispiel:

```
{lang: en}
{title: Let Her Go}
{artist: Passenger}

{sob}
    [C G C Em D C D Em] Well...
{eob}

{soc}
    You only need the [C]light when it's burning low[G]
    Only miss the [D]sun when it starts to snow[Em]
    Only know you [C]love her when you let her go[G D]
    [D] Only know you've been [C]high when you're feeling low[G]
    Only hate the [D]road when you're missing home[Em]
    Only know your [C]love her when you've let her go[G D]
{eoc}

{sob}
    And you let her go[Em C D Bm Em C D]
{eob}


[Em]Staring at the bottom of your [C]glass
Hoping one[D] day you will make a dream [Bm]last
But dreams come slow[Em] and they go so[C] fast[D]
[Em]You see her when you close your [C]eyes
Maybe one[D] day you will understand [Bm]why
Everything you [Em]touch surely dies[C D], but...


[Em]Staring at the ceiling in the [C]dark
Same old e[D]mpty feeling in your [Bm]heart
'Cause love come slow[Em] and it goes so[C] fast[D]
Well, you [Em]see her when you fall asleep[C]
But to never to touch[D] and never to keep[Bm]
'Cause you loved her to [Em]much and you dived too[C] deep[D], but...

{sob}
    And you let her go[Em] [C] [D] {repeat: 2}
    Well, you let her go[Em C D Bm Em C D]
{eob}
```

## Anfang

Am Anfang muss man zwischen geschweifte Klammer ein paar Infos schreiben:

* die Sprache (en/de) `{lang: de}`
* den Title `{title: Let Her Go}`
* den Interpret `{artist: Passenger}`

## Absätze

Ein Lied hat drei Absatztypen:

* der Refrain musst zwischen `{soc}` und `{eoc}` geschrieben werden (*start/end of chorus*)
* die Strophe (nur ein Zeilenumbruch davor)
* die *Bridge* zwischen `{sob}` und `{eob}`


# Akkorde

Die akkorde sind zwischen eckige Klammer geschrieben, vor dem Buchstabe (oder Leerzeichen), wenn sie gespielt werden müssen.

Zu Beispiel:
```
[Am]Allzeit bereit,[G] wir kennen keine [Am]Grenzen
```

* Der erste `Am` ist auf *All-* gespielt
* `G` muss man zwischen *bereit* und *wir* spielen
* Der 2. `Am` ist auf *Gren-* gespielt

---

Mit dieser Datei kannst du einfach einen [Beitrag schreiben](https://github.com/oliverpool/isarbela/issues/new) (du brauchst ein Github-Konto) oder uns eine E-Mail schicken an oliverpool@hotmail.fr.
