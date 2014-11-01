![Logo](./images/sticker.png)

OpenAlt 2014

Tomáš Raděj, ![Twitter logo](./images/twitter.png) [@tomasradej](http://twitter.com/tomasradej)



## O mně

Tomáš Raděj, Brno

**3 roky** *<span style="color:navy">Fedora</span> + <span style="color: #880000">Red Hat</span>*

**2 roky** *<span style="color: #008A7A">Python</span>*

**1 rok** *DevAssistant*



## O DevAssistantu

~ 2 roky ve vývoji

Napsán v **<span style="color: #008A7A">Python</span>**u

Příkazová řádka + GUI

<!-- .element: class="fragment" -->
**<span style="color:navy">Fedora</span>** (primárně)



## Problém

Začít psát software ≠ otevřít editor

<!-- .element: class="fragment" -->
Závislosti

<!-- .element: class="fragment" -->
Nastavení editoru

<!-- .element: class="fragment" -->
Adresářová struktura

<!-- .element: class="fragment" -->
Soubory



## Správa kódu

Publikování

Distribuce (RPM, kontejnery)

Závislosti



## Cíl DevAssistantu

(Jednotné) nastavení prostředí

Automatizace

Publikování kódu (<span style="color: #770000">GitHub</span>)

Sdílení prostředí v týmu (<span style="color: #0055BB">Docker</span>)

1 kliknutí / 1 příkaz




## Cílová skupina

Začínající vývojáři 

Vývojáři z různých platforem - **<span style="color:navy">Linux</span>, <span style="color:purple">OSX</span>**

Týmy - unifikované prostředí



## Architektura

**Jádro** - GUI, příkazová řádka

<!-- .element: class="fragment" -->
*vyvíjíme my*

<!-- .element: class="fragment" -->
**Skripty** - Assistanty, Snippety

<!-- .element: class="fragment" -->
*vyvíjí komunita*

<!-- .element: class="fragment" -->
**Index** - Server se skripty



## Jádro

**<span style="color: #008A7A">Python</span>** 2 + 3

Nezávislé na skriptech

1 skript funguje v GUI i v příkazové řádce



## Skripty (Assistanty)

4 druhy - **Create - Tweak - Prepare - Extras**

**YAML** - značkovací jazyk

**PingPong** - komunikace s ostatními jazyky

<!-- .element: class="fragment" -->
(nyní pouze **<span style="color: #008A7A">Python</span>**)



## Index

DevAssistant Package Index **(DAPI)**

Členové komunity nahrávají balíky se skripty

Odsud stahujete nové balíky

Hodnocení uživateli



## GUI

![GUI](./images/gui.png)



## GUI II.

![GUI](./images/gui2.png)



## Příkazová řádka

<span style="font-family: Aurulent Sans Mono; background-color: #EEEEEE">
    da create python flask --name MyApp --venv
<span>



## Integrace (<span style="color: #770000">GitHub</span>)

Vytváření repozitářů

Fork

Push



## Integrace (<span style="color: navy">Fedora</span>)

Bash completion

Infrastruktura, COPR (v budoucnu)



## Integrace (<span style="color: #0055BB">Docker</span>)

Vytvoření vývojového prostředí v kontejneru

Sdílení prostředí v týmu (každý dostane stejný Assistant)

Build image pro deployment



## Ukázka I. (Nový projekt)

**Flask** - Webový framework v **<span style="color: #008A7A">Python</span>**u

Obsahuje webserver

Vyžaduje závislosti, pevnou adresářovou strukturu



## Ukázka II. (Existující kód)

Vytvoření repozitáře na **<span style="color: #770000">GitHub</span>**u

Push existujícího kódu



## Ukázka III. (Fork na <span style="color: #770000">GitHub</span>u)

Fork existujícího repozitáře

Stažení kódu a příprava prostředí



## Děkuji za pozornost

&nbsp;

#### Pro uživatele

![DA](./images/da.png) <https://www.devassistant.org>

**Index** <https://dapi.devassistant.org>

&nbsp;

#### Pro vývojáře

![ReadTheDocs](./images/rtd.png) <http://docs.devassistant.org>

![GitHub](./images/github.png) <https://www.github.com/devassistant>

&nbsp;

<small>Prezentace vytvořena pomocí **reveal.js**, ke stažení na <https://www.github.com/tradej/openalt-2014></small>
