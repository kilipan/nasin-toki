# nasin toki pona - dobry sposób na mówienie
*autor: jan Juli (kili pan Juli / cile pa n-Ile)*
*tłumaczenie: jan Paweli*

W tym dokumencie staram się przedstawić kompleksową gramatykę toki pona.

Ponieważ toki pona jest bardzo osobistym językiem, ten dokument odzwierciedla moje własne **opinie** i **decyzje stylistyczne**. To powiedziawszy, nic w tej *nasin toki* nie jest niezwykłe.

Jeśli będziesz przestrzegać tej gramatyki, będziesz dobrze zrozumiany przez większość (jeśli nie przez wszystkich) mówiących w toki pona.

💚 [toki pona](https://www.tokipona.org/) została stworzona przez Sonję Lang. Moje podziękowania i szacunek, jan Sonja o!
💚 Chcę również podziękować społeczności, szczególnie wszystkim, którzy poświęcili czas na przeczytanie tego i udzielenie opinii!
💚 jan Ke Tami o. kulupu poki o. tonsi Asi o. jan Seli o. jan Lilin o. sina pona a tan toki sona sina

## wprowadzenie

Dokument jest w przybliżeniu podzielony na trzy części.

Pierwszy, krótki rozdział wprowadzający omówi niektóre nazewnictwo i konwencje, które będą używane w całym dokumencie.

Drugi rozdział "[podstawy](https://github.com/kilipan/nasin-toki/blob/main/pl.md#basics)" przedstawi przegląd konstrukcji gramatycznych i jak są one rozmieszczone w zdaniu, podając kilka przykładów dla łatwiejszego zrozumienia.

Trzeci rozdział "[szczegóły](https://github.com/kilipan/nasin-toki/blob/main/pl.md#in-depth)" omówi wszystkie słowa `pu` jedno po drugim. Zacznie od wszystkich słów, które mają specjalne funkcje gramatyczne, a następnie omówi czyste słowa treści, przechodząc przez przykłady, eksploracje możliwości semantycznych i interakcje z różnymi strukturami gramatycznymi.
(Część dotycząca słów treściowych będzie przez pewien czas w toku.)

<details>
<summary><h2>spis treści</h2></summary>

- [nasin toki pona](https://github.com/kilipan/nasin-toki/blob/main/pl.md#nasin-toki-ponaa-good-way-to-speak)
    - [jak czytać](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-read-this-grammar)
    - [zasady ogólne](https://github.com/kilipan/nasin-toki/blob/main/pl.md#general-principles)
    - [rodzaje słów](https://github.com/kilipan/nasin-toki/blob/main/pl.md#word-types):
        - [partykuły](https://github.com/kilipan/nasin-toki/blob/main/pl.md#particles),
          [czyste partykuły](https://github.com/kilipan/nasin-toki/blob/main/pl.md#pure-particles),
          [emotikle](https://github.com/kilipan/nasin-toki/blob/main/pl.md#emoticle)
        - [pseudopartykuły](https://github.com/kilipan/nasin-toki/blob/main/pl.md#pseudo-particles)
        - [słowa treści](https://github.com/kilipan/nasin-toki/blob/main/pl.md#content-words):
          [zaimki](https://github.com/kilipan/nasin-toki/blob/main/pl.md#pronouns),
          [przyimki](https://github.com/kilipan/nasin-toki/blob/main/pl.md#prepositions),
          [przedczasowniki](https://github.com/kilipan/nasin-toki/blob/main/pl.md#preverbs),
          [słowo pytające](https://github.com/kilipan/nasin-toki/blob/main/pl.md#question-word)
        - [zapożyczenia](https://github.com/kilipan/nasin-toki/blob/main/pl.md#loan-words)

- [podstawy](https://github.com/kilipan/nasin-toki/blob/main/pl.md#basics)
    - [struktura zdania](https://github.com/kilipan/nasin-toki/blob/main/pl.md#sentence-structure)
    - [frazy](https://github.com/kilipan/nasin-toki/blob/main/pl.md#phrases)
        - [negacja](https://github.com/kilipan/nasin-toki/blob/main/pl.md#negation)
        - [wiele modyfikatorów](https://github.com/kilipan/nasin-toki/blob/main/pl.md#multiple-modifiers)
        - [partykuła `pi`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-pi)
    - [jak używać przyimków](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-use-prepositions)
    - [jak używać przedczasowników](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-use-preverbs)
    - [jak powiedzieć "i"](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-say-and)
    - [pytania](https://github.com/kilipan/nasin-toki/blob/main/pl.md#questions):
      [`X ala X`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#x-ala-x),
      [`anu seme`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#anu-seme),
      [`seme`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#seme)
    - ["zdania względne"](https://github.com/kilipan/nasin-toki/blob/main/pl.md#relative-clauses)
    - [porządkowe](https://github.com/kilipan/nasin-toki/blob/main/pl.md#ordinals)
    - [porównania](https://github.com/kilipan/nasin-toki/blob/main/pl.md#comparisons)
    - [przechodnie](https://github.com/kilipan/nasin-toki/blob/main/pl.md#transitives)
    - [wykrzyknienia](https://github.com/kilipan/nasin-toki/blob/main/pl.md#interjections)
    - [kontekst](https://github.com/kilipan/nasin-toki/blob/main/pl.md#context)

- [szczegóły](https://github.com/kilipan/nasin-toki/blob/main/pl.md#in-depth)
    - [więcej informacji na temat struktury zdania](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-sentence-structure)
    - [więcej informacji na temat cząstek](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-particles)
        - [partykuła `en`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-en)
        - [partykuła `li`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-li)
        - [partykuła `e`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-e)
        - [partykuła `la`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-la)
        - [partykuła `pi`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-pi-1)
        - [partykuła `o`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-o)
        - [partykuła `anu`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-particle-anu)
        - [emotikle `a`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-emoticle-a)
    - [więcej informacji na temat `ni`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-ni)
    - [więcej informacji na temat pseudocząstek](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-particles)
        - [pseudopartykuła `nanpa`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-pseudo-particle-nanpa)
        - [pseudopartykuła `ala`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-pseudo-particle-ala)
        - [pseudopartykuła `taso`](https://github.com/kilipan/nasin-toki/blob/main/pl.md#the-pseudo-particle-taso)
    - [analiza porównawcza przyimków](https://github.com/kilipan/nasin-toki/blob/main/pl.md#a-comparative-analysis-of-prepositions)
    - [więcej informacji na temat przedczasowników](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-preverbs)
    - [więcej informacji na temat słów treści (WIP)](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-content-words)
</details>

## jak czytać tę gramatykę

- W całym dokumencie będę używał:
  - pojedynczych wielkich liter (np. `X`), aby reprezentować dowolne prawidłowe [*słowo treści*](https://github.com/kilipan/nasin-toki/blob/main/pl.md#content-words) lub [*fraza*](https://github.com/kilipan/nasin-toki/blob/main/pl.md#phrases) toki pona;
  - `<prep>`, aby odnieść się do dowolnego z
    [*przyimków*](https://github.com/kilipan/nasin-toki/blob/main/pl.md#prepositions);
  - `<preverb>`, aby odnieść się do dowolnego z
    [*przedczasowników*](https://github.com/kilipan/nasin-toki/blob/main/pl.md#preverbs);
- Bloki kodu zawierają poprawne wyrażenia toki pona (po zastąpieniu wyżej wymienionych skrótów rzeczywistymi słowami).
- Nawiasy oznaczają, że część w nawiasie jest opcjonalna, np. `toki [ni] li pona`
- Wszystkie tłumaczenia są **tylko sugestiami**. Ponieważ toki pona jest bardzo **wrażliwy na kontekst**, nigdy nie ma tylko jednej poprawnej interpretacji danego zdania.

## ogólne zasady

Kiedy używasz toki pona, warto mieć na uwadze następujące ogólne zasady.

### domyślna grzeczność

Nie ma potrzeby stosowania formalnych zwrotów takich jak "proszę" i "dziękuję" w toki pona. Generalnie, grzeczność jest przyjmowana za domyślną. Nie oznacza to jednak, że nie możesz powiedzieć komuś, za co jesteś wdzięczny. Zamiast używać pustych, schematycznych zwrotów wdzięczności, powiedz, dlaczego i jak jesteś wdzięczny, albo że są dobrzy!

### brak rekurencji na poziomie zdania

W wielu naturalnych językach możemy zagnieżdżać całe zdania w innych zdaniach (zdania złożone). To jest to, co nazywam tutaj rekurencją na poziomie zdania. Na przykład, robimy to w języku angielskim, budując zdania względne. W zdaniu "Patrzę na osobę, która idzie do domu." zdanie względne to "…, która idzie do domu.", które w zasadzie może być kompletnym zdaniem samym w sobie: "Osoba idzie do domu.".

W toki pona nie możemy zagnieżdżać zdań w innych zdaniach w ten sposób. Zamiast tego, są one rozdzielone na kilka zdań: `mi lukin e jan ni: ona li tawa tomo` - "Patrzę na osobę, która idzie do domu."

### brak jednego słowa na "i"
Aby powiedzieć "i", zamiast tego powtórz odpowiednią partykułę (por. sekcja o tym, [jak powiedzieć "i"](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-say-and)).

### brak oznaczenia czasu
W toki pona nie oznaczamy orzeczenia dla czasu.
Wszystkie zdania, które nie mają wyraźnych odniesień do czasu w innych częściach (jak dopełnienie dalsze lub fraza kontekstowa), mogą być interpretowane jako przeszłość, teraźniejszość, przyszłość (lub dowolny inny czas).

## rodzaje słów

Ta sekcja kategoryzuje słowa w toki pona. Niektórzy mogą podejść fo tego zagadnienia inaczej. Ważne jest, że kiedy w tym dokumencie wspomina się o tych rodzajach słów, odnosi się to do odpowiadających im słów wymienionych tutaj.

### partykuły

*Partykuły* to zazwyczaj małe słowa, które mają jedynie lub głównie funkcje gramatyczne.

Szczegóły użycia znajdują się w odpowiednich sekcjach o *partykułach* w [części szczegółowej](https://github.com/kilipan/nasin-toki/blob/main/pl.md#in-depth).

#### partykuły właściwe

`en`, `li`, `e`, `la`, `pi`, `o`, `anu`

*Partykuły właściwe* to słowa, które same w sobie nie mają znaczenia semantycznego. Są to czysto gramatyczne słowa, które istnieją, aby oznaczać części mowy, kontekst i kolejność modyfikatorów.

#### wykrzyknienia

`a`

Słowo `a` nie pasuje dobrze do innych kategorii i dlatego zajmuje tu swoje własne miejsce jako *wykrzyknienie*. Służy ono do dodawania emocjonalnego nacisku do słów, fraz lub całych zdań.

### pseudopartykuły

`nanpa`, `ala`, `taso`, `kin`

*Pseudopartykuły* to słowa, które mają właściwości cząstek, ale mogą być również używane jak słowa treści, dlatego są one wymienione jako własna kategoria.

Podobnie jak w przypadku cząstek, sprawdź odpowiednie sekcje w [części szczegółowej](https://github.com/kilipan/nasin-toki/blob/main/pl.md#in-depth) po więcej szczegółów.

### "słowa treści"

Dosłownie każde inne słowo w toki pona to *słowo treści* z przypisanym znaczeniem semantycznym.

Każde *słowo treści* może działać jak to, co w języku polskim nazywa się "przymiotnikiem", "przysłówkiem", "czasownikiem", "rzeczownikiem".

Niektóre z nich są częścią specjalnych grup, które nadają im dodatkowe funkcje gramatyczne.

Wszystkie słowa, które nie są wyraźnie wspomniane tutaj, są czystymi *słowami treści*.

#### zaimki

`mi`, `sina`, `ona`, `ni`

*Zaimki*, jak wszystkie słowa treści w toki pona, są *zarówno* liczbą pojedynczą, jak i mnogą (podobnie jak angielskie "you").

#### przyimki

`lon`, `tawa`, `tan`, `sama`, `kepeken`

*Przyimki* są używane do dalszego opisu sposobu wykonania orzeczenia. Wskazują one informacje o tym, gdzie, dokąd, skąd, jak lub za pomocą czego jest wykonywane orzeczenie. Mogą również występować bez poprzedzającego orzeczenia i przekształcać się w orzeczenie, opisując działania podmiotu.

#### "przedczasowniki"

`wile`, `sona`, `awen`, `kama`, `ken`, `lukin`

*Przedczasowniki* to specjalne słowa, które mogą zmieniać znaczenie orzeczenia w sposób, w jaki normalne modyfikatory nie mogą.

W przeciwieństwie do wszelkich innych modyfikacji w toki pona, występują przed orzeczeniem, do którego się odnoszą.

#### słowo pytające

`seme`

*Słowo pytające* `seme` zachowuje się jak słowo treści z punktu widzenia gramatyki.

Ważne jest, że w przeciwieństwie do różnych języków naturalnych, nie może być używane jako zaimek względny.

### zapożyczenia

Wszystkie słowa z wielkiej litery to nazwy rzeczy. Gramatycznie są podobne do *słów treści*, ale zazwyczaj nie występują jako główne.

## podstawy

## struktura zdania

Podstawowe zdanie w toki pona wygląda tak:

`X li Y [e Z]`[^li-dropping]

Bardziej złożone struktury zdań są oczywiście możliwe, jeśli naprawdę konieczne (np. [tutaj](https://github.com/kilipan/nasin-toki/blob/main/pl.md#combining-different-conjunctions)).

[^li-dropping]: Kiedy naszym głównym bohaterem, czyli podmiotem `X`, jest dokładnie słowo `mi` (i nic więcej) lub dokładnie słowo `sina` (i nic więcej), partykuła `li` jest pomijana w zdaniu.
  Przykłady:
  *tylko* `mi`: `mi lukin e ona` - "Widzę ich.";
  *nie tylko* `mi`: `tomo mi li lili` - "Mój dom jest mały."

Przykład:
`soweli li moku e kili` - "Zwierzę je owoce."

#### podmiot

- W powyższym przykładzie `X` jest głównym bohaterem naszego zdania, czyli **podmiotem**.
  - Może to być osoba, rzecz, idea… cokolwiek.
  - Ważne jest, że nasze zdanie opisuje, czym `X` jest lub co robi.

#### orzeczenie

- W powyższym przykładzie `Y` to coś, czym jest lub co robi, czyli **orzeczenie**.
  - Może to być czynność; jak pracowanie, granie, mówienie;
  - ... opis: jak niebieski, dobry, wysoki;
  - ... lub rzecz: jak dom, zwierzę, jedzenie.

#### dopełnienie bliższe

- W powyższym przykładzie `Z` to rzecz, na którą działanie jest skierowane, czyli **dopełnienie bliższe**.
  - Może to być również praktycznie dowolna rzecz lub istota.
  - Jest to albo odbiorca działania `Y` wykonywanego przez `X`, np. `soweli li pali e tomo` - "Zwierzę buduje gniazdo.";
  - ... albo bodziec, który `X` doświadcza przez wykonywanie `Y`, np. `soweli li lukin e kili` - "Zwierzę widzi owoc.".

## frazy

Ponieważ toki pona ma bardzo minimalistyczny leksykon, wszystkie *słowa treści* obejmują szerokie pole semantyczne.

Aby sprecyzować, o czym mówimy, możemy budować frazy wielowyrazowe. Ogólnie rzecz biorąc, fraza składa się z głównego *słowa treści*, czyli **bazy**, i zera lub więcej dodatkowych słów treści, czyli **modyfikatorów**.

Baza to główna rzecz, o której mówimy, podczas gdy modyfikatory dodatkowo precyzują bardzo szerokie pole semantyczne bazy. Gdy usuniemy dowolne modyfikatory, sama fraza będzie nadal odnosić się do tej samej rzeczy co wcześniej, ale stanie się mniej precyzyjna (wyjątek stanowi modyfikacja z `ala` - patrz niżej).

Przykład:
W `tomo waso` ("ptaszarnia"), słowo `tomo` jest bazą, podczas gdy `waso` je modyfikuje. Mówimy przede wszystkim o `tomo`. Modyfikator mówi nam, że `tomo` jest w jakiś sposób związane z polem semantycznym `waso`.

Używamy *zapożyczeń* jak każdego innego modyfikatora: `ma Kanata li suli` - "Ziemia zwana Kanadą jest duża."

`lipu kulupu Wikipesija li sona e ijo mute` - "Dokument społecznościowy Wikipedia zna wiele rzeczy."

### negacja

Aby zanegować frazę, wystarczy dodać słowo `ala`.

Przykłady:
`mi pali ala` - "Nie będę pracować."
`jan ala li lon tomo ni` - "Nikogo nie ma w tym domu."
`sina utala ala e waso suli` - "Nie walczyłeś z kaczką wielkości konia."
`ilo li tawa e ijo ala` - "Robot nie porusza przedmiotów."

### wiele modyfikatorów

Jeśli występuje wiele modyfikatorów, wszystkie odnoszą się do bazy frazy. Możemy po prostu dodać kolejne modyfikatory.

Zatem `X Y Z` to `X`, które jest związane z `Y` i z `Z`.

Często kolejność występowania modyfikatorów nie jest bardzo ważna, poza lekką zmianą akcentu. Wyjątkiem jest modyfikacja za pomocą słowa `ala`.

Przykłady:
`soweli suli pimeja` - "ciemne duże zwierzę"
`soweli pimeja suli` - "duże ciemne zwierzę"
`jan lawa pona` - "dobry władca"
`jan pona lawa` - "władczy dobry człowiek"
`tomo ala mute` - "wiele nie-domów"
`tomo mute ala` - "nie wiele domów"

### partykuła `pi`

Aby zmodyfikować bazę jednej frazy inną frazą zamiast pojedynczego *słowa treści*, poprzedzamy tę drugą frazę partykułą `pi`.

Przykład:
`poki pi telo wawa` - "pojemnik na mocny płyn", np. filiżanka kawy, ale…
`poki telo wawa` - "mocny pojemnik na płyn", np. diamentowa butelka

### brak dopełnień w frazach

Zasadniczo dopełnienia nie mogą być częścią fraz. Są one rodzajem rekurencji, której zazwyczaj nie stosuje się w toki pona.[^objects-in-phrases]

W związku z tym, możemy używać przyimków jako *słów treści* we frazach.

[^objects-in-phrases]: Choć jest to uniwersalnie prawdziwe dla dopełnień bliższych (oznaczanych `e`), niektórzy ludzie używają dopełnień pośrednich, przyimkowych we frazach.
  Osobiście unikam takich konstrukcji, ponieważ nie podoba mi się kilka rzeczy na ich temat:
  (1) Ich użycie utrudnia stosowanie przyimków w ich wersjach *słów treści* we frazach.
  (2) Często można je wyrazić poprzez usunięcie *przyimka* (jeśli po nim występuje jedno słowo) lub zastąpienie *przyimka* `pi` (jeśli po nim występuje wiele słów).
  (3) One, jak wszystkie inne rodzaje dopełnień, prowadzą do rekurencji, którą nie uważam za **pona**.

## jak używać przyimków

*[Przyimki](https://github.com/kilipan/nasin-toki/blob/main/pl.md#prepositions)* są zazwyczaj używane do oznaczania różnych rodzajów dopełnień pośrednich. Mogą być używane na dwa sposoby. Są albo dodawane do orzeczenia, które modyfikują (mogą obejmować również dopełnienie bliższe), albo występują bezpośrednio po `li` i stają się orzeczeniem.
- `X li Y [e Z] <prep> W`: fraza przyimkowa opisuje orzeczenie `Y`;
- `X li <prep> Y`: przyimkowe orzeczenie opisuje działanie lub stan podmiotu `X`.

Ważne jest, aby nie używać `e` do oznaczania dopełnień przyimkowych!

Przykład:
`kasi li suli tan wawa suno` - "Rośliny są duże z powodu mocy słońca."
`mi sama sina` - "Jestem jak ty."
`ona li kepeken ilo` - "Oni używają narzędzi."

### negacja przyimków

Zazwyczaj *przyimków* nie można modyfikować, gdy są używane w swojej funkcji gramatycznej. Możemy jednak dodać za nimi *partykułę* `ala`. To neguje *przyimek*.

`mi lon ala tomo` - "Nie jestem w domu."
`soweli li tawa ala kasi` - "Kret nie idzie w stronę bakłażana."

## jak używać przedczasowników

*[Przedczasowniki](https://github.com/kilipan/nasin-toki/blob/main/pl.md#preverbs)* są używane do zmiany pola semantycznego w sposób, w jaki proste modyfikatory nie mogą.
Dodawane są przed orzeczeniem, do którego się odnoszą.

`X li <preverb> Y [e Z]`

Zauważ, że dopełnienie bliższe (tutaj `Z`) odnosi się do orzeczenia (tutaj `Y`), a **nie** do *przedczasownika*.
Poszczególne *przedczasowniki* są szczegółowo omówione [tutaj](https://github.com/kilipan/nasin-toki/blob/main/pl.md#more-info-on-preverbs).

### negacja przedczasowników

Podobnie jak *przyimki*, *przedczasowniki* nie mogą być modyfikowane, gdy są używane w swojej funkcji gramatycznej. Ale możemy również dodać za nimi *partykułę* `ala`, co neguje *przedczasownik*.

`mi wile ala toki` - "Nie chcę rozmawiać."
`waso li kama ala suli` - "Ptak nie stał się ważny."

## jak powiedzieć "i"

Słowo "i" nie ma tłumaczenia w toki pona. Zamiast tego ogólną zasadą jest po prostu powtórzenie odpowiedniej *partykuły*, aby utworzyć koniunkcje.

#### wiele podmiotów

Aby połączyć różne frazy w podmiot, używamy słowa `en`.

`X en Y li Z`
`A en B en C li D`

#### wiele orzeczeń

Aby powiedzieć, że podmiot `X` robi dwie rzeczy, `Y` i `Z`, po prostu powtarzamy *partykułę* orzeczenia `li` w ten sposób:

`X li Y li Z`

Zauważ, że `X` i `Y` tutaj mogą również być orzeczeniami przyimkowymi.

Jeśli podmiotem jest `mi` lub `sina`, nie mamy `li` do powtórzenia, więc w takim przypadku po prostu zaczynamy nowe zdanie.[^extended-li-note]

[^extended-li-note]: W *lipu pu* jest to jedyny sposób na posiadanie wielu
  orzeczeń z `mi` i `sina`, ale niektórzy ludzie dodają również nowe orzeczenia z
  `li`. Jeśli podmiotem jest `mi` lub `sina`, pomijają pierwsze `li`, jak
  zwykle, ale nadal używają go dla wszelkich następnych orzeczeń: `mi X li Y li Z`. To
  prowadzi do nowych dwuznaczności i osobiście polecam stosowanie stylu *pu*.

`mi X. mi Y. mi Z`

#### wiele dopełnień bliższych

Aby dodać wiele dopełnień, po prostu powtórz *partykułę* `e`.

`A li B e C e D`

#### wiele fraz przyimkowych

Możemy również dodać wiele fraz przyimkowych do zdania.

`A li B <prep> C <prep> D

Oto kilka przykładów, jak powiedzieć lub nie powiedzieć "i" w kontekstach przyimkowych:

`waso li musi kepeken wawa kepeken kon` - "Ptaki bawią się, używając siły i powietrza."
`jan Pin li sama jan Po li sama jan Kiko.` - "Finn jest jak Bob i jak Rico." (Zauważ dodatkowe `li`.)
`jan Pin li sama jan Po sama jan Kiko.` - "Finn, jak Rico, jest jak Bob."

Zauważ różnicę między tymi dwoma ostatnimi przykładami! W drugiej wersji bez dodatkowego `li`, drugie `sama` jest frazą przyimkową opisującą (przyimkowe) orzeczenie.

#### w frazach `pi`

Choć ogólna zasada sugeruje, że wszystkie frazy pi powinny po prostu odnosić się do ogólnej głowy frazy, kontekst często może wskazywać, że wewnętrzny `pi` odnosi się do bazy zewnętrznej frazy `pi`.

Ogólnie rzecz biorąc, powinniśmy unikać używania wielu `pi` w jednej dużej frazie, ponieważ krótsze frazy są łatwiejsze do przetworzenia i mniej gramatycznie dwuznaczne.

#### łączenie różnych spójników

Kiedy występuje wiele orzeczeń, może być niejasne, do których orzeczeń odnoszą się dopełnienia i *przyimki*.

Przykład:
`jan li pali li pakala e tomo e ilo lon ma kepeken luka` - "Osoba buduje i niszczy domy i narzędzia na polu za pomocą rąk."
Zauważ, że ta dwuznaczność występuje również w języku polskim: "Osoba buduje i niszczy domy i narzędzia na polu za pomocą rąk."

Często możemy rozwiązać dwuznaczność, zmieniając strukturę zdania, w zależności od tego, co naprawdę mamy na myśli:
`jan li pali e tomo lon ma li pakala e ilo kepeken luka` - "Osoba buduje dom na polu i niszczy narzędzia za pomocą rąk."
`jan li pali e tomo e ilo kepeken luka li pakala e ona lon ma` - "Osoba buduje domy i narzędzia za pomocą rąk i niszczy je na polu."

## pytania

Są trzy różne sposoby tworzenia pytania. Zauważ, że ponieważ wszystkie one jednoznacznie oznaczają zdanie jako pytanie, nie potrzebujemy znaku zapytania w toki pona.

### `X ala X`

Ta konstrukcja jest używana do prostych pytań tak-nie: `Y li X ala X`. Pytamy słuchacza, które z zdań `Y li X` i `Y li X ala` jest prawdziwe.

Aby odpowiedzieć na pytanie `X ala X`, po prostu powtarzamy orzeczenie (`X`), aby powiedzieć, że `Y li X` jest prawdziwe, lub orzeczenie z `ala` (`X ala`), aby powiedzieć, że `Y li X ala` jest prawdziwe.[^lon-answer]

W drugim przypadku możemy również po prostu powiedzieć `ala`.

Oczywiście zawsze można odpowiedzieć pełnym zdaniem.

[^lon-answer]: Niektórzy ludzie również odpowiadają na tego rodzaju pytania słowem `lon`, co oznacza "prawda" lub "poprawne". Odradzam to, ponieważ w konstrukcji `X ala X` nie jest jasne, która z opcji jest wyraźnie pytana.

Przykład:
`soweli loje li moku ala moku e kili` - "Czy lisy jedzą warzywa?"
`moku ala` - "Nie."

Specjalne przypadki:
- Jeśli przed orzeczeniem znajduje się *[przedczasownik](https://github.com/kilipan/nasin-toki/blob/main/pl.md#preverbs)*, zastosuj `X ala X` do *przedczasownika* zamiast głównego orzeczenia, np. `kili li kama ala kama suli` ("Czy owoc urósł duży?").
- Jeśli orzeczeniem jest [fraza](https://github.com/kilipan/nasin-toki/blob/main/pl.md#phrases), możesz po prostu powtórzyć bazę, np. `jan li pana ala pana pi wawa mute e sike` ("Czy osoba rzuca kulę?").
- Aby podkreślić, o co pytasz, możesz również zastosować `X ala X` do innych części zdania, np. `soweli ala soweli li nasin e sina` ("Czy **zwierzę** cię prowadziło?")

### `anu seme`

Drugim sposobem zadania pytania tak-nie jest `X li Y anu seme`.

Nie różni się to wiele od pierwszego, ale sugeruje, że można oczekiwać mniej prostych odpowiedzi niż tylko "tak" lub "nie". Odpowiada się na to w taki sam sposób, jak na pytanie `X ala X`.

Przykład:
`ma sina li lete anu seme` - "Czy jest zimno tam, gdzie jesteś?"
`lete. taso suno pini li seli a` - "Tak, ale wczoraj było bardzo ciepło!"

Uwaga: `anu seme` można interpretować jako po prostu wariant normalnego pytania `seme` (patrz poniżej) w połączeniu z partykułą `anu`.

### `seme`

Jeśli zastąpimy rzecz, o którą pytamy, `seme`, możemy zadać pytanie otwarte.

Używając tej konstrukcji, prosimy słuchacza o wypełnienie miejsca `seme` odpowiednią informacją. Tego rodzaju pytania często są odpowiadane pełnym zdaniem. Można również po prostu podać frazę.

Przykłady:
`jan seme li toki` - "Kto mówi?"
`mi toki.` - "Ja mówię."

`ona li seme` ("Co zrobił?")
`ona li tawa tomo ona` ("Poszedł do domu.")

`sina lukin e seme` ("Co oglądasz?")
`mi lukin e waso` ("Oglądam ptaki.")

## "zdania względne"

W toki pona, budowanie zdań podobnych do zdań względnych wymaga kilku zdań (często tylko dwóch). Możemy to zrobić, używając słowa `ni`, aby oznaczyć słowo, które chcemy opisać dalej, a następnie odroczyć dalszy opis na koniec bieżącego zdania.

Można również umieścić opis przed resztą zdania.

Przykłady:
`jan ni li pona tawa mi: ona li mama e kasi` - "Ludzie, którzy opiekują się roślinami, są dla mnie dobrzy."
`soweli li lukin e waso ni: ona li tawa lon ma kasi` - "Zwierzę obserwuje ptaki, które latają przez las."

Inna strategia to przenieść opisowe zdanie na początek i dodać główne zdanie.

Przykłady:
`jan li mama e kasi. jan ni li pona tawa mi` - "Ludzie, którzy opiekują się roślinami, są dla mnie dobrzy."
lub `jan li mama e kasi. ona li pona tawa mi` - "Ludzie, którzy opiekują się roślinami, są dla mnie dobrzy."
`waso li tawa lon ma kasi. soweli li lukin e waso ni` - "Zwierzę obserwuje ptaki, które latają przez las."
lub `waso li tawa lon ma kasi. soweli li lukin e ona` - "Zwierzę obserwuje ptaki, które latają przez las."

## liczebniki porządkowe

Aby wyrazić liczebniki porządkowe, wystarczy dodać pseudo-partykułę `nanpa`, a następnie liczbę. Użycie `nanpa` eliminuje potrzebę użycia `pi`, więc nie należy go dodawać.

Przykłady:
`sina jan nanpa wan lon tomo ni` - "Jesteś pierwszą osobą w tym budynku."
`ilo nanpa wan li pona. ilo nanpa tu tu li pona ala` - "Pierwsze narzędzie jest dobre. Czwarte narzędzie nie jest dobre."

## porównania

Aby wyrazić porównania, istnieje kilka możliwych konstrukcji. Najłatwiej nauczyć się tego na przykładach:
`jan Ipe li suli. jan Sunsi li lili` - "Sunsi jest mniejszy od Ipe."
`tomo mi la tomo sina li loje mute` - "Twój dom jest bardziej czerwony niż mój."

Superlatywy można wyrazić za pomocą liczebnika porządkowego `nanpa wan` ("pierwszy"):
`pona la toki ni li nanpa wan` - "Jeśli chodzi o dobroć, ten język jest najlepszy."
`toki ni li pona nanpa wan` - "To jest najlepszy język."

## czasowniki przechodnie

Czasami natrafiamy na dziwne konstrukcje w toki pona.
Rzeczy takie jak `mi tomo e waso`[^ke-tami] mogą na początku wydawać się mylące, ale istnieją proste strategie, aby to zinterpretować.

[^ke-tami]: Dziękuję za świetny przykład, jan Ke Tami!

Kiedy używamy konstrukcji `X li Y e Z`, zazwyczaj mamy na myśli jedną z dwóch rzeczy, w zależności od [kontekstu](https://github.com/kilipan/nasin-toki/blob/main/pl.md#context):

- Podmiot powoduje, że obiekt jest Y, "X powoduje, że Z jest Y.". W terminach toki pona, możemy to przekształcić na `X li pali e ni: Z li Y`.
  `mi pona e tomo` - np. "Sprawiamy, że pokój jest dobry.", lub "Naprawiam dom."
  `mi tomo e waso` - np. "Przemieniamy ptaka w dom." (Może to być bardzo duży ptak i możemy mieszkać w jego upierzeniu!)
- Podmiot stosuje Y do obiektu, "X stosuje Y do Z.".
  `mi luka e soweli len` - np. "Głaszczę ukrytego psa.", lub "Uderzam pluszową zabawkę."
  `mi tomo e waso` - np. "Stosuję dom do ptaka, czyli wkładam ptaka do domu"
  `sina telo e sina` - np. "Myjecie się.", lub "Rozlewasz wodę na siebie."

## wykrzyknienia

Sposobem na komentowanie rzeczy bez budowania pełnych zdań są *wykrzyknienia*.

Zazwyczaj składają się one z prostej frazy, frazy przyimkowej lub obu. Już widzieliśmy przykład prostych wykrzyknień w sekcji o [pytaniach](https://github.com/kilipan/nasin-toki/blob/main/pl.md#questions), szczególnie podczas odpowiadania na pytania tak-nie. Inne zastosowania obejmują (ale nie ograniczają się do) krótkie komentarze na temat rzeczy, które aktualnie doświadczamy lub czujemy, oraz wyrażanie naszych opinii na temat rzeczy.

Przykłady:
`pona a` - "tak miło!"
`waso suwi` - "słodki nietoperz!"
`wawa tawa sina` - "niech moc będzie z tobą!"
`tan seme a` - "dlaczego?!"
`a` - "och!", "ah!", "wow!", …

## kontekst

Jeśli kiedykolwiek zapytałeś `jan pi toki pona`, jak powiedzieć jakieś słowo z języka naturalnego, prawdopodobnie słyszałeś o *kontekście*. Jest to wszechmocny rozstrzygacz, rzecz, która kondensuje rozległe pola semantyczne naszej wypowiedzi do zarządzalnych wymiarów. Pozwala nam zrozumieć, czy ktoś mówi o norze lisa, zoo, czy domu w kształcie kota.

Kontekst zdania obejmuje całe doświadczenie, jakie mają mówca i słuchacz podczas komunikacji. W jednej sytuacji `mi o tawa` oznacza "Powinienem odejść.", w innej "Chodźmy!".

Początkujący często konstruują dzikie formu w pojedynczych frazach. Układają `pi` za `pi`, dodają więcej i więcej modyfikatorów, i kończą z nieporęczną konstrukcją, która jest trudna do zinterpretowania (w najlepszym przypadku) i jeszcze trudniejsza do wymyślenia na poczekaniu  Kiedy brakuje kontekstu, wszystkie elementy frazy mogą być źle zinterpretowane. Dlatego musimy *ummowić się na* odpowiedni kontekst w toki pona, zanim będziemy mogli powiedzieć rzeczy, które chcemy powiedzieć. Zamiast wrzucać wszystkie informacje o zamierzonym słowie do jednej frazy, powinniśmy opisać to w wielu krótkich i łatwych do zinterpretowania zdaniach.

Zdobycie poczucia kontekstu to coś, czego ten dokument nie może nauczyć. Musimy ćwiczyć toki pona z innymi mówcami, szczególnie z tymi, którzy mają pewne opanowanie języka.

## szczegóły

Ta sekcja zawiera bardziej szczegółowe informacje na temat tego, jak używać i nie używać konkretnych słów i konstrukcji.

## więcej informacji na temat struktury zdania

Bardziej kompletna struktura zdania w toki pona jest podana tutaj. Zauważ, że jeśli podmiotem jest *tylko* `mi` lub *tylko* `sina`, należy pominąć pierwsze `li` w zdaniu, co nie jest wyraźnie zaznaczone poniżej.

`[(A|<prep> A|<sentence>) la]* B [en C]* {li [<preverb>]* D [e F]* [<prep> G]*}+`

- `<sentence>` oznacza tutaj dowolne poprawnie sformułowane zdanie;
- `(X|Y|Z)` oznacza "wybierz `X`, `Y` lub `Z`";
- Gwiazdka (`*`) oznacza, że obiekt o tej samej formie jak poprzedni może wystąpić dowolną liczbę razy (w tym zero);
- Plus (`+`) oznacza, że obiekt o tej samej formie jak poprzedni może wystąpić dowolną liczbę razy (z wyłączeniem zera);

Zauważ, że ogólnie zdania są **znacznie (!)** prostsze i nie używają dużo tej potencjalnej złożoności. Jeśli zauważymy, że piszemy długie i złożone zdania, powinniśmy rozważyć podzielenie myśli na mniejsze części.

## więcej informacji o partykułach

### partykuła `en`

Partykuła `en` jest wskaźnikiem podmiotu, który jest zawsze pomijany dla pierwszego podmiotu.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Nie jest to ogólny spójnik (zob. [jak powiedzieć "i"](https://github.com/kilipan/nasin-toki/blob/main/pl.md#how-to-say-and)), ale często jest mylony z nim przez nowych uczących się.

Przykłady:
`jan en soweli li sama mute` - "Ludzie i zwierzęta są bardzo podobni."
`sina en mi li toki` - "Ty i ja rozmawiamy."
`tenpo mute la kon en telo li wawa` - "Wiatr i deszcz są często silne."
`jan An en jan Pita en jan Sen en jan Ton li lon` - "Ann, Peter, Sam i Tom są tutaj."

### partykuła `li`

Partykuła `li` jest wskaźnikiem orzeczenia.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Jest pomijana tylko wtedy, gdy podmiotem jest *dokładnie* i *tylko* `mi`, lub *dokładnie* i *tylko* `sina`. Zatem, mówimy `mi pali`, ponieważ podmiotem jest `mi`, ale ani w `pali mi li pona` (podmiot: `pali mi`) ani w `mi taso li lon tomo` (podmiot: `mi taso`) ani w `sina en mi li toki` (podmiot: `sina en mi`) nie można pominąć `li`.

Jeśli chcemy dodać więcej niż jedno orzeczenie do zdania, które zaczyna się od `mi` lub `sina`, możemy po prostu zacząć nowe zdanie.

Często możemy stwierdzić, że brak `li` oznacza, że wypowiedź nie jest pełnym zdaniem. Oczywiście jest to prawdziwe tylko wtedy, gdy podmiotem nie jest `mi` lub `sina` i jeśli `li` nie zostało zastąpione przez `o` (patrz poniżej).

Przykłady:
`soweli li suwi` - "Zwierzę jest urocze."
`mi kama. mi oko. mi anpa` - "Przyszedłem, zobaczyłem, zwyciężyłem."
`ona li pali mute li lape lili` - "Oni dużo pracują i mało śpią."

### partykuła `e`

Partykuła `e` jest wskaźnikiem dopełnienia bliższego.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Dopełnienie bliższe w zdaniach jest albo *obiektem* działania, albo *bodźcem* doświadczenia.

*Obiekt* działania to rzecz, którą podmiot zmienia, wykonując czynność opisaną przez orzeczenie.

Przykład: `soweli li pakala e kasi` - "Zwierzę łamie roślinę."

*Bodziec* to coś, co podmiot postrzega, czuje lub myśli.

Przykład: `mi lukin e mun` - "Patrzę na gwiazdy."

Nie używamy `e` do oznaczania dopełnień pośrednich (przyimkowych). Nie są one ani obiektem, ani bodźcem. Zamiast tego są oznaczane przyimkami.

Przykład: `mi pali lon tomo` - "Pracuję w pokoju."
Zauważ różnicę: `mi pali e tomo` - "Buduję pokój."

Jak wyżej, `e` nie jest używane do oznaczania dopełnień przyimkowych, nawet w zdaniach, w których orzeczenie jest pominięte.

Przykład: `ona li tawa tomo` - "Idą do domu."
Zauważ różnicę: `ona li tawa e tomo` - "Przemieszczają dom."

Wreszcie, `e` *nigdy* nie może wystąpić wewnątrz fraz, np. w podmiocie lub w frazie `pi`.

Więcej przykładów:
`waso li mama e waso lili` - "Ptak opiekuje się pisklętami."
`jan Ali li sona e toki Alapi e toki Lasina e toki Inli e toki Putonwa` - "Ali zna arabski, łacinę, angielski i mandaryński."

### partykuła `la`

Partykuła `la` oznacza frazy kontekstowe i zdania.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Umieszczamy kontekst najpierw, następnie `la`, a następnie zdanie, które powinno być interpretowane w danym kontekście: `X la Y li Z` - "W kontekście X, Y jest/robi Z."

`la` można używać do dodawania różnych rodzajów informacji, np. czasu, sposobu, miejsca, dowodu, itp. Możemy również używać go do zdań warunkowych, jeśli przed `la` występuje pełne zdanie.  Co więcej, możemy umieścić frazy przyimkowe przed `la` i będzie to oznaczało to samo, co dodanie tej samej frazy (choć z innym naciskiem):

Przykłady:
`tenpo lon la mi sitelen e lipu sona` - "Teraz piszę dokument wiedzy."
`mi la ni li pona` - "Dla mnie, to jest miłe."
`jan Pala la suno li wawa a` - "Barbara powiedziała mi, że słońce jest intensywne!"
`supa tomo li jaki la jan li telo e ona` - "Jeśli podłoga jest brudna, to ludzie ją myją."
`kepeken ilo telo wawa la mi weka e jaki tan supa` - "Czyszczę mocno ganek."

### partykuła `pi`

Partykuła `pi` oznacza bazę frazy, która działa jako modyfikator dla innej głowy. Nigdy nie jest używana do modyfikatorów jednowyrazowych.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Domyślnie modyfikatory są stosowane od lewej do prawej do głowy. Jeśli dodamy `pi`, wszystko, co następuje po `pi`, staje się własną frazą, która z kolei modyfikuje bazę poprzedzającą `pi` jako całość.

Przykłady:
`jan lawa mute` - "wielu przywódców" (np. "wielu liderów")
`jan pi lawa mute` - "osoba o wielu głowach"
`ilo tawa lili mute` - "wiele małych narzędzi do poruszania się" (np. "wiele deskorolek")
`ilo pi tawa lili mute` - "narzędzie związane z wieloma małymi ruchami" (np. "elektryczna szczoteczka do zębów")
`ilo tawa pi lili mute` - "bardzo małe narzędzie do poruszania się"

Choć technicznie możliwe jest użycie wielu fraz `pi` wewnątrz siebie, ogólna zasada unikania rekurencji sugeruje, że lepiej jest po prostu używać zdań, aby opisać złożone szczegóły.  Jeśli z jakiegoś powodu będziemy zmuszeni użyć wielu `pi` w jednej frazie, musimy być świadomi, że istnieje dwuznaczność, czy wszystkie odnoszą się do ogólnej głowy, czy do najmniejszej frazy, którą poprzedzają.

### partykuła `o`

Partykuła `o` jest drugim wskaźnikiem orzeczenia, a także wskaźnikiem wołacza.

Podobnie jak wszystkie partykuły, nie ma żadnego znaczenia semantycznego.

Jest używana zamiast `li`, gdy wydajemy polecenia lub opisujemy życzenia lub pragnienia.

W bezpośrednich poleceniach do słuchacza podmiot `sina` może być pominięty.
`[sina] o tawa pona` - "Jedź ostrożnie!"

Aby wyrazić życzenia, pragnienia i nadzieje, zastępujemy `li` przez `o`. (To również nazywa się trybem optatywnym.)
`ona o lape` - "Powinni spać."

W przeciwieństwie do `li`, `o` nie może być pominięte przy `mi` lub `sina`.
`mi o toki pona` - "Powinienem mówić wyraźnie."

Do wołacza `o` może być dodane do frazy, aby zwrócić się do rzeczy opisanej przez tę frazę.
`jan Su o` - "Hej Su!"

Łączenie wołacza i imperatywu jest również łatwe:
`jan Su o lape pona` - "Hej Su, śpij dobrze!"

Zauważ, że optatyw/imperatyw i wołacz nie są rozróżnialne, gdy jest tylko jeden podmiot.

### partykuła `anu`

Informacje na temat słowa `anu` zawsze były notorycznie trudne do znalezienia, podczas gdy jednocześnie użycie go przez społeczność jest znacznie bardziej zróżnicowane niż w przypadku innych słów.

Ogólnie rzecz biorąc, `anu` to spójnik oznaczający "lub" (zarówno wyłączny, jak i włączny). Możemy go używać do łączenia różnych części mowy w kontekstowo odpowiednią *frazę `anu`.* To, co nazywam tutaj frazą `anu`, składa się z dwóch poprawnych fraz połączonych słowem `anu`. Te frazy następnie działają jako nowa fraza, która może wystąpić w podmiocie, orzeczeniu i (dopełnieniach bliższych i pośrednich). Unikanie używania `anu` wewnątrz fraz `pi` jest zalecane ze względu na powstające dwuznaczności.

Przykłady:
`waso anu kala li tawa` - "Ptak lub ryba porusza się."
`waso li pali anu pakala e tomo` - "Ptaki budują lub niszczą gniazdo."
`soweli li pali e tomo anu lupa` - "Zwierzęta budują gniazda lub nory."

### wykrzyknienie `a`

Słowo `a` może być dodane do każdego słowa, frazy lub zdania, aby dodać emocjonalny nacisk. Może być również używane samodzielnie do wyrażania okrzyków jak "ah!", "och!", "wow!", itp.

Przykłady:
`pona a` - "Tak dobrze!"
`ike a` - "Och, nie!"
`o lukin e pali mi a` - "Zobacz na moją pracę!" \[np. implikując dumę lub smutek, w zależności od kontekstu]
`ni li musi a tawa mi` - "To jest tak zabawne!"

## więcej informacji o `ni`

`ni` może oznaczać dowolne z poniższych w odpowiednim kontekście:
- "to/tamto/te/tamte"
- jako modyfikator: "związane z tym/tamtym/tymi/tamtymi", "w ten/tamten/te/tamte sposoby"
- jako orzeczenie: "robić to/tamto/te/tamte", "być tym/tamtym/tymi/tamtymi"

Przykłady:
`ni li pona` - "To jest spokojne."
`ona li oko e ni` - "Patrzą na to."
`tomo li suwi. jan li ni kin` - "Dom jest uroczy. Osoba też jest."
`soweli li len e kili lon ma. ona li ni tan tenpo lete` - "Wiewiórka chowa orzechy w ziemi. Robi to z powodu zimy."


## więcej informacji o pseudopartykułach

### pseudopartykuła `nanpa`

Jak opisano w sekcji o [liczebnikach
porządkowych](https://github.com/kilipan/nasin-toki/blob/main/pl.md#ordinals),
pseudopartykuła `nanpa` jest używana do wyrażania kolejności bazy, gdy jest bezpośrednio dodana do frazy.

Gdy jest również obecne `pi`, musimy uważać na kolejność rzeczy:
`ilo pi akesi suwi nanpa wan` - "narzędzie pierwszego aksolotla"
`ilo nanpa wan pi akesi suwi` - "pierwsze narzędzie aksolotla"

Gdy `nanpa` występuje jako baza, opisuje odpowiednią liczbę zamiast liczebników porządkowych:
`nanpa tu li nanpa pona tawa mi` - "Lubię liczbę dwa."
`len pi nanpa wan li loje` - "Koszula z numerem 1 na niej jest czerwona."

Możemy nieco rozszerzyć użycie `nanpa`, wskazując na następny lub ostatni element w uporządkowanej liście:
`sitelen tawa nanpa pini li musi a` - "Ostatnie wideo było tak zabawne!"
`mi toki lon kalama pana nanpa kama` - "Będę mówić w następnym odcinku podcastu."

### pseudopartykuła `kin`

`kin` jest wskaźnikiem dodatku, który opisuje, że fraza *jest* lub *robi* coś *również*, lub ma coś robione dla niej również. Jest używana podobnie do angielskiego słowa "too".

Może być dodana jak modyfikator do dowolnej frazy, ale nie może występować jako głowa sama w sobie. Jedynym wyjątkiem jest fraza kontekstowa `kin la`, gdzie oznacza całe następne zdanie jako dodatek do tego, co już zostało powiedziane. Często lepiej jest bardziej precyzyjnie określić, w jaki sposób zdanie jest *również*, np. z `sama la` ("równoważnie", "podobnie", ...) lub `ante la` ("również, niepowiązanie", "z drugiej strony", ...).

Przykłady:
`jan li ken pona kin` - "Ludzie mogą również być spokojni."
`kin la ma li sike e suno` - "Ponadto, ziemia kręci się wokół słońca."

Przykłady różnego rozmieszczenia:
`ona kin li pali e lipu` - "*Oni piszą* również książkę [wśród innych pisarzy książek]."
`ona li pali kin e lipu` - "Oni *piszą* również książkę [wśród innych rzeczy, które robią dla książki]."
`ona li pali e lipu kin` - "Oni piszą *książkę*, również [wśród innych rzeczy, które tworzą]."

Zauważ, że te zdania można przetłumaczyć tak samo w języku angielskim, potencjalnie z różnicami w nacisku. Chociaż mają nieco różny nacisk, interpretowanie tego zbyt ściśle nie jest zalecane.

### pseudopartykuła `ala`

Jak widzieliśmy w sekcji o [negacji](https://github.com/kilipan/nasin-toki/blob/main/pl.md#negation), pseudopartykuła `ala` może być używana dokładnie jak słowo treści podczas negacji wewnątrz fraz.

Poza tym, może być sama bazą, z semantycznymi konotacjami "nicości", "pustki", itp.

Dodatkowo, możemy negować przedczasowniki i przyimki za pomocą niej, w sposób, który żaden inny modyfikator nie może:
`mi sona ala pali e tomo` - "Nie wiedziałem, jak zbudować dom."
`kala li moku kepeken ala ilo` - "Ryba jadła bez użycia narzędzi."

### pseudopartykuła `taso`

Słowo `taso` stosuje się podobnie jak `kin` w kontekscie tego *gdzie* może występować. Jego znaczenie jest oczywiście inne. Używając go jako modyfikatora, możemy wskazać, że zaznaczona fraza jest "jedyną" rzeczą, której dotyczy stwierdzenie zdania. Na początku zdania oznacza całe zdanie jako przeciwstawne do poprzedniego stwierdzenia, jak angielskie "but". W niektórych kontekstach może nawet działać jako główny rzeczownik.

Przykłady:
`soweli li ken pona taso` - "Zwierzęta mogą być tylko dobre."
`taso ma li sike e suno` - "Ale ziemia kręci się wokół słońca."

Przykłady różnego rozmieszczenia:
`ona taso li pali e lipu` - "Tylko oni piszą książkę."
`ona li pali taso e lipu` - "Oni tylko piszą książkę."
`ona li pali e lipu taso` - "Oni piszą tylko książkę."

Przykłady główny rzeczownik taso:
`ona li taso` - "Oni są sami."
`mi pilin ike ala tan taso mi` - "Nie czuję się źle z powodu bycia samemu."

## analiza porównawcza przyimków

Ta sekcja zawiera analizę porównawczą, jak działają przyimki w toki pona. Należy pamiętać, że piąty blok zawiera nietypowe konstrukcje, których nie wszyscy mogą zrozumieć.

*idea*
`X li Y e Z` ≈ `X li pali e ni: Z li Y`

*przyimki*
- `tawa` - do, w stronę, z perspektywy
- `lon` - w, na, przy
- `sama` - jak, podobny do
- `tan` - od, z powodu
- `kepeken` - używając, za pomocą

*frazy przyimkowe*
- `mi pana e ijo tawa ona` - "Daję im rzecz."
- `mi awen lon tomo` - "Zostaję w domu."
- `mi pali sama ona` - "Pracuję jak oni."
- `mi suli tan moku` - "Jestem duży z powodu jedzenia."
- `mi toki kepeken kalama` - "Mówię za pomocą dźwięku."

*frazy przyimkowe bez orzeczeń*
- `mi tawa tomo` - "Idę do domu."
- `mi lon telo` - "Jestem w wodzie."
- `mi sama ona` - "Jestem jak oni."
- `mi tan ma Apese` - "Jestem z Abc-land."
- `mi kepeken ilo` - "Robię coś za pomocą narzędzi."

*frazy przechodnie z wersjami słów treści przyimków*
- `mi tawa e soweli` - "Przemieszczam zwierzę \[w stronę nieokreślonego miejsca]."
- `mi lon e kala` - "Istnieję rybę (sprawiam, że ryba istnieje) \[w nieokreślonym miejscu/czasie/sposobie]."
- `mi sama e akesi` - "Upodabniam żabę (sprawiam, że żaba jest podobna) \[do czegoś nieokreślonego]."
- `mi tan e ona` - "Sprawiam, że są wynikiem \[czegoś nieokreślonego]."
- `mi kepeken e ona` - "Sprawiam, że używają \[czegoś nieokreślonego]."

*frazy przechodnie z orzeczeniami przyimkowymi* (nietypowe!)
- `mi tawa supa e soweli` - "Przemieszczam zwierzę w stronę stołu **lub** "Przemieszczam powierzchnię zwierzęcia."
- `mi lon telo e kala` - "Istnieję rybę (sprawiam, że ryba istnieje) w wodzie."
- `mi sama jan e akesi` - "Upodabniam żabę (sprawiam, że żaba jest podobna) do osoby."
- `mi tan utala e ona` - "Sprawiam, że są wynikiem konfliktu."
- `mi kepeken ilo e ona` - "Sprawiam, że używają narzędzia."


## więcej informacji na temat przedczasowników

### przedczasowniki *pu*

#### `wile`

Słowo `wile` można używać do wyrażania potrzeb, chęci, pragnień oraz zamiarów.

Jako przedczasownik, `wile` oznacza orzeczenie stojące za nim jako cel, który podmiot chce osiągnąć.

Przykłady:
`ona li wile pana e kili` - "Chcą podarować rzepę."
`jan lili li wile suli` - "Dziecko chce być dorosłym."
`mi wile tawa lon nasin noka` - "Muszę chodzić po ścieżce."
`soweli suli li wile lape lon tenpo lete` - "Niedźwiedzie muszą spać w okresie zimnym."

#### `sona`

Przedczasownik `sona` wyraża, że podmiot wie, w jaki sposób być lub robić to, co wyraża orzeczenie.

Przykłady:
`mi sona toki pona` - "Wiem, jak mówić prosto."
`waso li sona pali e tomo` - "Ptaki wiedzą, jak budować gniazda."
`jan Oto li sona musi.` - "Otto wie, jak być zabawnym."

#### `awen`

Przedczasownik `awen` wyraża ciągły stan lub ciągłą/powtarzaną czynność określiną orzeczeniem stojącym za nim.

Przykłady:
`o awen pali e ijo` - "Kontynuuj pracę nad rzeczą!"
`mi awen wile e ni` - "Wciąż tego chcę."
`ona li awen weka` - "Oni pozostają daleko."

#### `kama`

Przedczasownik `kama` oznacza, że orzeczenie stało się / staje się / stanie się prawdziwe. Oznacza to, że podmiot zaczął być lub robić coś, czego wcześniej nie robił lub nie był.

Przykłady:
`mi kama sona e toki pona` - "Nauczyłem się toki pona." (Nie znałem tego, a potem poznałem.)
`akesi li kama lon nasin telo` - "Krokodyl dotarł do rzeki."
`tomo li kama suli` - "Dom stał się duży." (Np. widząc nowo wybudowany dom, który widzieliśmy, gdy był znacznie mniejszy.)

#### `ken`

Słowo `ken` wyraża zdolność do zrobienia czegoś. Używamy go jako przedczasownika, aby pokazać, że podmiot jest w stanie być lub robić orzeczenie, lub że jest możliwe, że podmiot jest lub robi orzeczenie.

Przykłady:
`sina ken toki tawa mi` - "Możesz rozmawiać ze mną."
`jan li ken lape lon ma kasi ni` - "Ludzie mogą spać w tym lesie."
`kala li ken soweli` - "Zwierzęta morskie mogą być ssakami."

#### `lukin`

Przedczasownik `lukin` odpowiada próbie, poszukiwaniu lub zamiarze, aby być lub robić coś. Ponieważ `oko` i `lukin` są wprowadzone jako synonimy w *lipu pu*, możemy również używać `oko` jako przedczasownika. Jest to rzadko robione, jednak.

Przykłady:
`mi lukin pini e

 lipu ni` - "Próbuję ukończyć ten dokument."
`ona li lukin tawa waso` - "Usiłują latać."
`mi oko jo e tomo lili lon ma kasi` - "Próbuję mieć małą chatkę w lesie."

## inne "przedczasowniki"

Te słowa są czasem używane jako przedczasowniki, choć nie zostały zdefiniowane jako takie w *lipu pu.* Wiele osób ich nie używa i osobiście również tego nie zalecam. Istnieją bardzo łatwe obejścia, aby kontekstowo powiedzieć to samo, porównaj alternatywne (niepełne!) wersje oznaczone jako "niektóre opcje pu". Każdy dodatkowy przedczasownik sprawia, że gramatyka staje się bardziej dwuznaczna, porównaj domyślne, nie-przedczasownikowe odczyty podane dla porównania (po "LUB").

#### `open`

Używane do rozpoczęcia bycia lub robienia czegoś, przedczasownik `open` wprowadza nowe dwuznaczności do gramatyki.

Przykłady:
`ona li open pakala e lupa tomo` - "Zaczynają łamać drzwi." LUB "Przypadkowo otwierają drzwi."
niektóre opcje pu: `ona li open e pakala pi lupa tomo` lub `ona li lukin pakala e lupa tomo`
`jan li open pona e ma` - "Ludzie zaczną być dobrzy dla natury." LUB "Ludzie dobrze otwierają ziemię." (np. kopią)
niektóre opcje pu: `pona ma la jan li open` lub `jan li kama pona e ma`

#### `pini`

Analogicznie, słowo `pini`, gdy jest używane do wskazania, że skończyliśmy być lub robić coś. Wprowadza to podobne dwuznaczności.

Przykłady:
`mi pini tawa tomo sona` - "Skończyłem chodzić do szkoły." LUB "Jestem skończony z perspektywy szkoły."
niektóre opcje pu: `mi awen ala tawa tomo sona` lub `mi kama lon tomo sona`
`soweli li pini jaki e tomo` - "Pies skończył brudzić dom." LUB "Pies skończył dom w obrzydliwy sposób."
niektóre opcje pu: `tomo li kama jaki tan soweli` lub po prostu `soweli li jaki e tomo`

#### `alasa`

Bardzo podobny do `lukin`, przedczasownik `alasa` może być używany do wskazania próby bycia lub robienia czegoś. W porównaniu do `lukin` czasami mówi się, że wydaje się być bardziej skoncentrowany i ukierunkowany. Wprowadzenie takiego rozróżnienia do prostego toki pona wydaje się wątpliwe. Dla zalecanej opcji pu, po prostu zastąp `alasa` przez `lukin`.

Przykłady:
`mi alasa sitelen e lipu pona` - "Próbuję napisać dobry dokument." LUB "Zbieram dokumenty dobrych książek."
`jan sona li alasa sona e ijo mute` - "Mędrzec próbuje wiedzieć wiele rzeczy." LUB "Mędrzec mądrze poluje na wiele rzeczy."

## więcej informacji o słowach treści

[TODO]
