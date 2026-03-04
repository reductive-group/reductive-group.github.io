---
layout: post
title: "Syllable Boundaries Overview"
author: Reductive Group
tags: [lesson]
---

Under construction

There are two major components of spelling in rook script. The first, and more important, is the sequence of letters. The second, more unique to rook script, is breaking words into syllables. This post overviews the considerations with some examples; more complete descriptions of the rules and principles in consideration will be covered in future posts.

In a word in rook script, every vowel is at the center of its own syllable, and every consonant needs to be assigned to the syllable of either the preceding or following vowel. In standard romanization, *syllable boundaries* are marked with an interpunct symbol “·”. For example, the word “biome” can be broken into sounds as /baioum/, which has two vowel sounds, /ai/ and /ou/. There are no consonants between them so the only possible place the syllable boundary can go is directly between them. We have “biome\|bai·oum”.

The set of consonants in a syllable that comes before the vowel is known as the *onset*. The set of consonants that follows the vowel is the *coda*. If a consonant is to the left of a syllable boundary, then it is a coda consonant (of the preceding syllable), and to the right it is an onset consonant. The sequence of consonants in an onset or coda form a *cluster*. The vowel and coda together form the *rhyme* of a syllable.

There are several considerations when placing syllable boundaries:
1. phonotactics
2. allophony
3. vowel checking
4. relative stress
6. morphology
7. onset maximizing

These considerations should be taken into account in order, though typically multiple considerations will point in the same direction.

## Phonotactic Constraints

*Phonotactic constraints* are rules that tell us what sounds or sound combinations are difficult to pronounce. They are specific to languages or even indiviual speakers, and come in a range of strength from impossible to slightly awkward. For the purposes of finding syllable boundaries, the most important phonotactics are sequences of sounds that exist in English but are difficult to say together within a single word. Each syllable should be reasonably comfortable to pronounce as if it were a standalone word. A syllable that does not violate phonotactic constraints is said to be phonotactically *compliant*. Some correctly spelled words have syllables that are not completely compliant, but the most important rule in assigning syllable boundaries is not violate unnecessary constraints.

In rook script, there are five types of relevant phonotactic constraints: pairs of consononants that are not allowed in onsets, pairs of consonants that are not allowed in codas, consonants that only ever appear in the onset or in the coda, vowel-consonant pairs that are not allowed in the rhyme, and the letter y appearing between any onset other consonant and any vowel other than uu.

Consider the word “sigma”. It is pronounced /sɪgmə/, which has two syllables. The three possible positions for the syllable break are (i) before the g, (ii) between the g and the m, and (iii) after the m. However, option (i) would leave the second syllable as “gmə”, which is difficult to pronounce because gm is not allowed in an onset. Similarly, (iii) gives “sigm” for the first syllable, and gm is not allowed in a coda. The remaining, and correct, placement of the syllable boundary is option (ii). The correct spelling is “sigma\|sig·mə”.

As another example, consider the name “Magdalene”, pronounced /mægdələn/. The combination gd is not allowed in either onset or coda, so the syllable boundary goes between g and d and the correct spelling is “Magdalene\|mag·də·lən”. Note that the constraint that gd is not allowed in coda is far from obligatory—many English words, like “flagged\|flagd” clearly must have gd in coda. However, this combination is typically restricted to past tense verbs. In any case, it is easy to avoid having gd together in an onset in the word “Magdalene”, so for phonotactic compliance the d must be placed in the onset of the second syllable.

The words “cohort\|kou·hourt” and “singing\|siing·iing” both have syllable boundaries determined by letters that either never appear in coda or never in onset. Additionally, the letters w and y do not appear in codas. Note there are exceptions in all four cases, for example, the names “Gohberg\|goh·bərg” and “Ngô\|ngou” and the interjections “ew\|iiw” and “aww\|ow”.

When appearing in coda, the letters r, and l are restrictive about which vowels can appear before them. (The letter ng is too, but it can only appear in coda so it is not relevant for placing syllable boundaries.) Only the vowels ii, ei, o, ou, u, and ə may appear before r, and any vowel may appear before l except for ai and oi. This helps us correctly spell the words “boiler\|boi·lər” and “virus\|vai·ris”.

## Allophony

Define phoneme and allophone

In rook script analysis, many sounds have allophony described by position in onset or coda. The most important examples are the /t/, the effect of sonorants in coda (“Taylor\|tei·lər” vs “tailor\|teil·ər”, “Bahrain\|bo·rein“), and the combination of /tr/ or /dr/ (“bedrock\|bed·rok” vs “redraw\|rii·dro”).

## Vowel checking

Rook script has 6 checked vowels and 8 unchecked vowels. (The unstressed /ə/ is unchecked while the stressed /ʌ/ is checked, though both are represented by the letter ə.)

If it does not violate an above rule, checked vowels must have codas. There are exceptions. Look at the words “valid\|val·id” and “satire\|sa·tai·ər”. Also “yeah\|ya” and “uh\|ə”.

Weird thing with “spatula\|spat·chuu·lə”, “Patrick\|pat·trik”, and “address (n.)\|ad·dres”

## Relative stress

Tough to explain. Also I don’t have good examples ready that aren’t actually determined by allophony. I guess look at clusters like “under”.

This is determinate when a stressed syllable is adjacent to an unstressed syllable, but less so between two similarly-stressed or unstressed syllables.

## Morphology

Words break into morphemes. If it‘s clear where morpheme boundaries are, it’s better for them to align with syllable boundaries. This is a tie-breaking consideration.

## Onset maximaization

This mostly ends up affecting multisyllabic suffixes like “-ify\|-ə·fai” and proper nouns.

[Home](/)
