# Core List — Scope, Inclusion Criteria and Reading Notes

Reference notes for **[corelist.md](corelist.md)**, the core edition of the *American English Homophone Reference*: **1,282 homophone sets / 2,843 words** of differently spelled words that sound alike. This file says what the list contains and what it deliberately leaves out, how to read an entry, and how the sets were derived. The entries themselves are in `corelist.md`; the companion edition of same-word form pairs is [possessive.md](possessive.md).

## What the list is

`corelist.md` is a dictionary-format list of homophone sets. One numbered entry per line is one set: two or more headwords that share a pronunciation while being different words. Each headword carries a part of speech and a WordNet gloss, and the set carries a single General American phonemic transcription.

* **Main list** — entries **1–812**: ordinary vocabulary.
* **Appendix** — entries **A1–A470**: personal names, surnames, place names, brands and other proper nouns, numbered separately so the two ranges never collide.

## Inclusion criteria

1. **Same pronunciation, stress included.** The members of a set share an identical sequence of phonemes, primary and secondary stress included. A pair that differs in stress or vowel quality is not a homophone for this reference.
2. **Different words only.** Every member must be a word in its own right, not a grammatical form of another member. Sets built from forms of one headword — *engine's / engines*, *year's / years*, *act's / acts* — are in `possessive.md`.
3. **No possessive that exists only by adding *-'s*.** A possessive written with an apostrophe is a form of its base word, so it is not a headword here. This is the rule that shapes the edition most; it is set out in full below.
4. **Possessive words spelled without an apostrophe are ordinary vocabulary** and do stay: *its / it's*, *yore / your*, *hours / ours*. These are words in their own right, not a base word with an ending added.
5. **Contractions stay.** *it's / its*, *let's / lets*, *we're / were*, *where's / wares / wears*, *you'll / yule* are kept, because a contraction is a word of its own rather than a possessive, even when it ends in *-'s*.
6. **Frequency floor.** At least one member of a set occurs in modern English prose at a rate of roughly one in three million words or better, so dictionary-only collisions do not crowd out the words people use.
7. **Accent-dependent sets** are included where General American treats the vowels as identical — chiefly the cot–caught merger (*cot / caught*) and the father–bother merger (*balm / bomb*).
8. **Names are kept out of the main list** and collected in the appendix.

### The *-'s* rule in detail

A possessive such as *ad's* or *engine's* is the base word with a possessive ending attached, so it is not a separate word and is not listed. The same applies to name possessives: *taylor's*, *wolfe's*, *graham's* and *barber's* are out, exactly as *ad's* is.

Standalone possessive words are unaffected, because nothing is added to them: *its*, *your*, *ours* are spelled that way in the dictionary and remain ordinary headwords, as in *it's / its* (entry 390), *yore / your* (A469) and *hours / ours* (A233).

Applying the rule to the earlier 1,384-entry core list changed it in three ways:

* **320 possessive headwords were removed** from the sets that contained them — *,ad's*, *aid's*, *bay's*, *hour's*, *wolf's*, *taylor's* and the rest.
* **101 sets were dropped** because fewer than two words remained once the possessive left: *bee's / bees*, *cross's / crosses*, *doe's / doze*, *dec's / decks*, *wolfe's / wolf's*. A set needs at least two distinct words to be a homophone set.
* **One appendix set was merged.** *hour's / hours / ours* collapsed to *hours / ours*, which duplicated an existing entry, so the two became one.

Where a possessive form does pair with something in speech, that pair consists of forms of the same word (*engine's / engines*) and belongs in `possessive.md`, not here.

## How to read an entry

```
**1.** /əˈsɛtɪk/ — **acetic** *adj.* relating to or containing acetic acid · **ascetic** *n.* someone who practices self denial as a spiritual discipline
```

* Entries are numbered in bold for cross-reference, one entry per line, followed by a blank line.
* The transcription between slashes is a General American phonemic transcription (IPA), with primary stress marked ˈ and secondary stress ˌ.
* Each bold headword is followed by its part of speech and a short WordNet gloss; notes such as *(pl. of engine)* identify an inflected form that remains inside a set of different words.
* The appendix continues the numbering with the prefix **A**.

## Pronunciation key

| Symbol | Example | Symbol | Example |
| --- | --- | --- | --- |
| /ɑ/ | f**a**ther | /æ/ | c**a**t |
| /ʌ/ | c**u**p | /ɛ/ | b**e**d |
| /ə/ | **a**bout | /ɝ/ | b**i**rd |
| /ɚ/ | butt**er** | /aɪ/ | t**i**me |
| /ɔɪ/ | b**o**y | /θ/ | th**in** |
| /ʃ/ | **sh**ip | /tʃ/ | **ch**in |
| /ɡ/ | **g**o | /h/ | **h**at |

## Coverage at a glance

| Measure | Count |
| --- | --- |
| Homophone sets | 1,282 |
| Words covered | 2,843 |
| Sets of two words | 1,075 |
| Sets of three words | 159 |
| Sets of four or more | 48 |
| Main list (ordinary vocabulary) | 812 sets / 1,700 words |
| Appendix (names and proper nouns) | 470 sets / 1,143 words |
| Companion file (possessive.md) | 1,396 sets / 2,795 words |
| Combined | 2,678 sets / 5,638 words |

## Method

Candidate pronunciations were taken from CMUdict (American English, 126,052 headwords) and grouped by identical phoneme strings with stress retained. Headwords were validated against a US English spell-checking dictionary to remove misspellings, and against WordNet to separate ordinary vocabulary from names. A set is retained when at least one member occurs in modern English prose at a rate of roughly one in three million words or better. Every set was reviewed by hand; false collisions produced by erroneous pronunciations in the source dictionary were removed. The surviving sets were then reduced to their dictionary lemmas: sets whose members all resolve to a single headword went to `possessive.md`, and possessive forms written with *-'s* were removed from the sets that remain here.

## Relationship to possessive.md

`corelist.md` (1,282 sets / 2,843 words) and `possessive.md` (1,396 sets / 2,795 words) are exact complements: no set appears in both, and together they hold 2,678 sets / 5,638 words. `possessive.md` keeps the same reading conventions and carries its own front matter, with the pronunciation key and inclusion notes repeated there so that either file can be used alone.

## Sources and license

Pronunciations are derived from CMUdict, definitions from WordNet 3.0, spelling validation from hunspell `en_US`, the frequency floor from `wordfreq`, and name detection from the 2010 US Census surname list and a public baby-names list. What each source supplied, and on what terms, is set out in [NOTICE](NOTICE). The compilation — selection, arrangement, numbering, form notes and export structure — is licensed under [Creative Commons Attribution 4.0](LICENSE); the transcription and gloss data keep their upstream terms.
