# nasin toki pona—a good way to speak
*by jan Juli (kili pan Juli / cile pa n-Ile)*

In this document I aim to provide a comprehensive grammar of toki pona.
Since toki pona is a very personal language, this will reflect my own opinions and style decisions.
That said, nothing about this `nasin toki` is unusual.
If you follow this grammar, you will be well understood by most (if not all) toki pona speakers.


## lipu toki / Table of Contents

- [basics](https://github.com/kilipan/nasin-toki#basics)
  - [how to read](https://github.com/kilipan/nasin-toki#how-to-read-this-grammar)
  - [general principles](https://github.com/kilipan/nasin-toki#general-principles)
  - [word types](https://github.com/kilipan/nasin-toki#word-types)
    - [particles](https://github.com/kilipan/nasin-toki#particles),
      [pseudo-particles](https://github.com/kilipan/nasin-toki#pseudo-particles)
    - [content words](https://github.com/kilipan/nasin-toki#content-words):
      [pronouns](https://github.com/kilipan/nasin-toki#pronouns),
      [prepositions](https://github.com/kilipan/nasin-toki#prepositions),
      [preverbs](https://github.com/kilipan/nasin-toki#preverbs)
  - [sentence structure](https://github.com/kilipan/nasin-toki#sentence-structure)
  - [compounds](https://github.com/kilipan/nasin-toki#compounds)


# basics

## how to read this grammar
- Throughout this document, I will use variables (e.g. `X`, `Y`, `Z`).
These represent any valid toki pona [*content word*](https://github.com/kilipan/nasin-toki#content-words).
- Code-blocks of text contain valid toki pona sentences.
Brackets mark the bracketed part as optional, e.g. `[toki] ni li pona`
- All translations are mere suggestions.
Since toki pona is highly **context-sensitive**, there is never only a single valid interpretation of a given sentence.


## general principles
- no recursion
- conjunction by repeating the appropriate particle


## word types
This sections lists the types of words in toki pona.
Some people might analyze certain things differently.
Importantly, when these word types are mentioned in this document, the corresponding words listed here are what is referred to.

### particles
`en`, `li`, `e`, `la`, `pi`, `o`, `a`

*Particles* are words that have no semantic meaning on their own.
They are purely grammatical words that exist to mark parts of speech, context, modifier-order, and emotional emphasis.

#### pseudo-particles
`taso`, `anu`

The *pseudo-particles* are mostly used as conjunctions (meaning "but" and "or", respectively).
Rare usage: Sometimes, they also act as content words with semantic fields around the concepts of "alone" and "choice", respectively.

### content words
Literally every other word in toki pona is a *content word* with semantic meaning attached.
Every content word can work like all of what is called "adjective", "adverb", "verb", "noun" in English.
Some of these are part of special groupings that give them additional grammatical functions.
All the words that aren't mentioned in this section are pure content words.

#### pronouns
`mi`, `sina`, `ona`, `ni`

The *pronouns*, like all content words in toki pona, are *both* singular and plural (quite like the English "you").

#### prepositions
`lon`, `tawa`, `tan`, `sama`, `kepeken`

*Prepositions* are used to further describe the manner of the predicate.
They indicate information about where, whither, whence, how, or whereby the predicate is performed.

#### preverbs
(pu) `wile`, `sona`, `awen`, `kama`, `ken`, `lukin`  
(popular usage) `open`, `pini`, `alasa`

The *preverbs* are special words that modify the meaning of the predicate.
Unlike all other modification in toki pona, they occur *before* the predicate they are modifying.

## sentence structure
A basic toki pona sentence looks like this:

`X li Y [e Z]`[^li-dropping]

(more [complex sentence structures (TODO)](https://github.com/kilipan/nasin-toki#complex-sentence-structure) are of course possible)

[^li-dropping]: Whenever our main character, the subject `X` is exactly the word `mi` (and nothing else) or exactly the word `sina` (and nothing else), the particle `li` is dropped from the sentence.
  Examples:
  *only* `mi`: `mi lukin e ona` ("I see them.");
  *not only* `mi`: `tomo mi li lili` ("My house is small.")
  
Example: `soweli li moku e kili` ("An animal eats fruit.")

#### the subject
- `X` is the main character of our sentence, the **subject**
  - It can be a person, a thing, an idea, anything really
  - The important part is that our sentence describes what `X` is or is doing
#### the predicate
- `Y` is this thing they are or are doing, the **predicate**
  - It can be an action; like working, playing, talking
  - ... a description; like blue, good, tall
  - ... or a thing; like house, animal, food
#### the object
- `Z` is the thing that the action is done to, the **direct object**
  - it can also be basically anything
  - it is either the reciever of the action `Y` performed by `X`, e.g `soweli li pali e tomo` ~ "The animal builds a nest."
  - ... or the stimulus that `X` experiences through doing `Y`, e.g. `soweli li lukin e kili` ~ "The animal sees a fruit."


## building questions
There are three different ways to build a question.

### `X ala X`
This construction is used for simple yes-or-no questions: `Y li X ala X`
It asks the listener whether the sentence `Y li X` is true.  
To answer an `X ala X` question, simply repeat the predicate for yes (`X`) or the predicate followed by `ala` for "no" (`X ala`).
Of course it is always possible to answer in a full sentence instead.

Example:  
`soweli loje li moku ala moku e kili` ("Do foxes eat vegetables?")  
`moku ala` ("No.")

### `anu seme`
The second way to ask a yes-or-no question is `X li Y anu seme`.
This is not much different from the first, but it suggests a less simple answer than just "yes" or "no" may be expected.
It is answered the same way as the `X ala X` question.

Example:  
`lete li lon ma sina anu seme` ("Is it cold where you are?")  
`lete. taso suno pini li seli a` ("Yes, but yesterday it was very warm!")

### `seme`
If we replace the thing that is asked for with `seme`, we can ask an open question.
Using this construction, we ask the listener to fill the place of `seme` with the appropriate information.
These types of question are best answered with a full sentence.

Examples:
`jan seme li toki` ("Who is speaking?")  
`mi toki.` ("I am.")

`ona li seme` ("What did they do?")  
`ona li tawa tomo ona` ("They walked home.")

`sina lukin e seme` ("What are you watching?")  
`mi lukin e waso` ("I am watching birds.")


## compounds
Since toki pona has a very minimalist lexicon, all the content words cover broad semantic fields.
To specify what we are talking about, we can build *compounds*.  
A compound consists of a main content word, the **head**, and at least one additional content word, the **modifier(s)**.
Since toki pona is *head-initial*, the first word in a compound is the head, all following ones are modifiers.

Example: In `tomo waso` ("bird-house"), the word `tomo` is the head while `waso` modifies it.
We are talking first and foremost about a `tomo`.
The modifier tells us that the `tomo` is in some way related to `waso`.


## how to use prepositions
The [prepositions](https://github.com/kilipan/nasin-toki#prepositions) are appended to the predicate they modify.
They are followed by a content word that describes .


## how to use preverbs


# in-depth


## more info on particles

### the particle `en`

### the particle `li`

### the particle `e`

### the particle `la`

### the particle `pi`

### the particle `o`

### the particle `a`


## a comparative analysis of prepositions
