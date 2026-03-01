---
layout: post
title: Making Valid Syllables
author: Reductive Group
tags: [lesson]
---

There are two major components of spelling in rook script. The first, and more important, is the sequence of letters. The second is placing syllable boundaries correctly. This post focuses on the first basic rule for syllable boundaries, *validity*. Future posts will focus on other considerations, including stress and allophony.

## Syllable boundaries

Rook script is a syllablic alphabet, meaning words are broken up into syllables. When writinng linearly, the simplest way to assign each letter to a syllable is to indicate the boundary points between syllables in a word. In Latin transcriptions of rook spellings of words, an interpunct symbol “·” indicates the end of one syllable and the start of the next.

There are several considerations when placing syllable boundaries:
1. validity
2. allophony
3. vowel checking
4. relative stress
5. letter-specific tendencies
6. morphology

This post focuses on validity. A syllable is *valid* if it can be pronounced on its own. A rule that would prevent a sequence of sounds from being pronounceable as a single syllable is a *phonotactic constraint*. The relevant phonotactic constraints for rook script are those of General American English; speakers of other languages and dialects face different phonotactic constraints. For instance, Russian speakers have no trouble saying “где” (pronounced \[gdʲe\]) but often do have trouble voicing the /d/ at the end of the English word “bad”.

Phonotactic constraints exist on a spectrum, ranging from unpronounceable to rarely unattested, and different speakers might find certain sounds fall in different categories. The primary purpose of syllable validity is to find syllable boundaries, so this post may treat constraints as inviolable even where counterexamples exist. In particular, a typing system must be able to accommodate many more syllables than are strictly valid.

There are millions of rook valid syllables. I haven’t done the calculations to find either the exact number (though I know it is no more than 21 million) or the number attested in English (probably in the tens of thousands).

## Syllable patterns

An English syllable has 3 components: onset, vowel, and coda. All of the letters in an onset or coda are consonants. The longest onsets in English have 3 sounds, and the longest codas have 4. Not every syllable has any sounds in the onset or coda, but every syllable has a vowel. All together, we can say the structure of an English syllable is 3 optional consonants, followed by one obligatory vowel, and then 4 optional consonants:
> (CCC)V(CCCC)

Furthermore, the morphological patterns that allow 4 coda consonants only appear at the ends of words. So for finding syllable breaks, any time 4 or more consonants appear together some must fall on either side of the boundary. For example the sequence /kstr/ in “jockstrap” must be split over both syllables. Indeed, the rook spelling is “jockstrap\|jok·strap”

In spoken English, it’s actually common to pronounce some syllables without articulating a vowel. In unstressed syllables, the consonants /m/, /n/, and /l/ can all be pronounced *syllabically* in place of a vowel. For instance, when saying the word “girdle”, the /d/ sound is released laterally, meaning that the /l/ sound begins directly aftwerwards without a vowel in between. In rook script, a syllabic consonant is always written as ə followed by the consonant, so we have “girdle\|gərd·əl”.

Relatedly, the sound combination /əɹ/ is often realized as a single sound, but I view that sound as a vowel rather than a syllabic consonant. It is also always spelled with ə in rook script, for instance “after\|aft·ər”.

## Onset and coda constraints

The /ŋ/ sound does not appear in onsets. The sounds /h/, /w/, and /y/ do not appear in codas. Two examples of words where these sounds appear in the middle are “singer\|siing·ər” and “cahoots\|kə·huuts”.

## Voicing assimilation

Voiced and unvoiced consonants do not appear in an onset or coda together. For example, the word “absolute” has /b/ (voiced) followed by /s/ (unvoiced), so there must be a syllable break between them: “absolute\|ab·sə·luut”.

Recall that nasals and approximants are considered neutrally voiced, so they may appear in an onset or coda with voiced consonants or unvoiced consonants. Consider for example the words “clash\|klash” and “glass\|glas”: the /l/ sound appears with both /k/ (unvoiced) and /g/ (voiced) in the onset. The same is true for /n/ in the coda of “find\|faind” and “plant\|plant”.

In handwritten rook script, the *voicing stroke* can be treated almost as a letter in itself. It is typically written after all letters of the cluster, whether onset or coda, and crosses through all letters. Furthermore, voiced onsets are limited to 2 consonants and voiced codas are limited to 3 consonants; both as a consequence of sonorance progression.

Exceptions should be limited to one-syllable words, such as “width\|width”. When handwriting it is acceptable to withhold the voicing stroke, essentially spelling it “width\|witth”.

## Manner constraints

Many phonotactic constraints can be described in terms of manner of the consonants.

### Onset clusters

An onset has 3 slots, each of which may be empty or filled. The first slot can only be filled with /s/, and only if the second slot is filled with /p/, /t/, /k/, /m/, /n/, /w/, or /l/. The following table lists all the valid combinations of the second and third slots. The second slot is for stops, fricatives, sibilants, and nasals while the third is exclusively for approximants.

<table>
  <tr>
    <td>↓2  3→</td>
    <th> /w/ </th>
    <th> /r/ </th>
    <th> /l/ </th>
    <th> /y/ </th>
  </tr>
</table>

### Sonorance progression in coda

### Sonorance progression remarks

At a high level, onsets should increase in sonorance toward the vowel and codas should decrease afterwards. A limited number of additional sounds may be added to the beginning or end of a syllable: /s/ at the start of onset, and /s/, /z/, /t/, and /d/ at the end of a coda. 

There are exceptions, but the outline of a typical syllable’s sonorance over time is hump-shaped, peaking at the vowel.

(insert graph)

As mentioned above, onsets are limited to 3 consonants and codas are limited to 4. The onset limit is a consequence of the obstruence progression rules. However, the limiting of codas to 4 consonants is artificial. In fact, a word with alternating /t/ and /s/ could go on forever without a limiting rule, though no words do. Furthermore, the word “angsts” is analyzed by some as /eiŋksts/ (5 coda consonants) though it is spelled in rook script as “angsts\|eingsts” (4 coda consonants) under the view that the \[k\] is not phonemic.

## Other invalid combinations

[Home](/)
