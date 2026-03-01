---
layout: post
title: "Syllable Boundaries 1: Validity"
author: Reductive Group
tags: [lesson]
---

There are two major components of spelling in rook script. The first, and more important, is the sequence of letters. The second is placing syllable boundaries correctly. This post focuses on the first basic rule for syllable boundaries, *validity*. Future posts will focus on other considerations, including stress and allophony.

## Syllable boundaries

Rook script is a syllablic alphabet, meaning words are broken up into syllables. When writinng linearly, the simplest way to assign each letter to a syllable is to indicate the boundary points between syllables in a word. For instance once you have broken a word “function” into sounds, /fəŋkʃən/, since it is two syllables you need to find the point where one syllable ends and the next begins. In Latin transcriptions of rook spellings of words, an interpunct symbol “·” indicates the end of one syllable and the start of the next. In this case the official rook spelling is “function\|fəngk·shən”, meaning the two syllables are “fəngk” and “shən”.

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

Furthermore, the morphological patterns that allow 4 coda consonants only appear at the ends of words. So for finding syllable breaks, any time 4 or more consonants appear together some must fall on either side of the boundary. For example the sequence /kstr/ in “jockstrap” must be split over two syllables. Indeed, the rook spelling is “jockstrap\|jok·strap”.

In spoken English, it’s common to pronounce some syllables without articulating a vowel. In unstressed syllables, the consonants /m/, /n/, and /l/ can all be pronounced *syllabically* in place of a vowel. For instance, when saying the word “girdle”, the /d/ sound is released laterally, meaning that the /l/ sound begins directly aftwerwards without a vowel in between. In rook script, a syllabic consonant is always written as ə followed by the consonant, so we have for example “girdle\|gərd·əl”.

Relatedly, the sound combination /əɹ/ is often realized as a single sound, but I view that sound as a vowel rather than a syllabic consonant. It is also always spelled with ə in rook script, for instance “after\|aft·ər”.

## Onset and coda constraints

The /ŋ/ sound does not appear in onsets. The sounds /h/, /w/, and /y/ do not appear in codas. Two examples of words where this constraint guides boundary placement are the words “singing\|siing·iing” and “cahoots\|kə·huuts”. The theoretical syllables “ngiing” and “kəh” are invalid, leaving only one possible position for the syllable boundary.

## Voicing assimilation

Voiced and unvoiced consonants do not appear in an onset or coda together. For example, the word “absolute” has /b/ (voiced) followed by /s/ (unvoiced), so there must be a syllable break between them: “absolute\|ab·sə·luut”.

Recall that nasals and approximants are considered neutrally voiced, so they may appear in an onset or coda with voiced consonants or unvoiced consonants. Consider for example the words “clash\|klash” and “glass\|glas”: the /l/ sound appears with both /k/ (unvoiced) and /g/ (voiced) in the onset. The same is true for /n/ in the coda of “find\|faind” and “plant\|plant”.

In handwritten rook script, the *voicing stroke* can be treated almost as a letter in itself. It is typically written after all letters of the cluster, whether onset or coda, and crosses through all letters. Furthermore, voiced onsets are limited to 2 consonants and voiced codas are limited to 3 consonants; both as a consequence of sonorance progression.

Note that exceptions exist, but the syllables they form are not technically valid. For example, in the word “width\|width”, the /d/ is voiced while the /θ/ is unvoiced and they appear together in the coda. When handwriting it is acceptable to withhold the voicing stroke, essentially spelling it “width\|witth”, in recognition of the fact that the word is typically pronounced \[witθ\]; however, the official rook spelling remains “width\|width”.

## Cluster constraints

Syllable validity can be determined by pairs of consonants that are allowed to appear together. Here is a list of what it is.

### Onset clusters

I don’t know how to explain exactly how it works. There are two joints here: /s/ + core letter + approximant.

<table>
  <tr>
    <td></td>
    <th> /p/ </th>
    <th> /t/ </th>
    <th> /k/ </th>
    <th> /m/ </th>
    <th> /n/ </th>
  </tr>
  <tr>
    <th> /s/ </th>
    <td> /sp/ </td>
    <td> /st/ </td>
    <td> /sk/ </td>
    <td> /sm/ </td>
    <td> /sn/ </td>
  </tr>
</table>

<table>
  <tr>
    <td></td>
    <th> /w/ </th>
    <th> /ɹ/ </th>
    <th> /l/ </th>
    <th> /y/ </th>
  </tr>
  <tr>
    <th> /p/ </th>
    <td> – </td>
    <td> /pɹ/ </td>
    <td> /pl/ </td>
    <td> /pj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /b/ </th>
    <td> – </td>
    <td> /bɹ/ </td>
    <td> /bl/ </td>
    <td> /bj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /f/ </th>
    <td> – </td>
    <td> /fɹ/ </td>
    <td> /fl/ </td>
    <td> /fj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /v/ </th>
    <td> – </td>
    <td> /vɹ/<sup>2</sup> </td>
    <td> /vl/<sup>2</sup> </td>
    <td> /vj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /t/ </th>
    <td> /tw/ </td>
    <td> /tɹ/<sup>3</sup> </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /d/ </th>
    <td> /dw/ </td>
    <td> /dɹ/<sup>3</sup> </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /θ/ </th>
    <td> /θw/<sup>2</sup> </td>
    <td> /θɹ/ </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /ð/ </th>
    <td> – </td>
    <td> – </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /k/ </th>
    <td> /kw/ </td>
    <td> /kɹ/ </td>
    <td> /kl/ </td>
    <td> /kj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /g/ </th>
    <td> /gw/<sup>2</sup> </td>
    <td> /gɹ/ </td>
    <td> /gl/ </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /h/ </th>
    <td> – </td>
    <td> – </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /s/ </th>
    <td> /sw/ </td>
    <td> – </td>
    <td> /sl/ </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /z/ </th>
    <td> /zw/<sup>2</sup> </td>
    <td> – </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /ʃ/ </th>
    <td> /ʃw/<sup>2</sup> </td>
    <td> /ʃɹ/ </td>
    <td> /ʃl/<sup>2</sup> </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /ʒ/ </th>
    <td> – </td>
    <td> – </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /tʃ/ </th>
    <td> – </td>
    <td> –<sup>3</sup> </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /dʒ/ </th>
    <td> – </td>
    <td> –<sup>3</sup> </td>
    <td> – </td>
    <td> – </td>
  </tr>
  <tr>
    <th> /m/ </th>
    <td> /mw/<sup>2</sup> </td>
    <td> – </td>
    <td> – </td>
    <td> /mj/<sup>1</sup> </td>
  </tr>
  <tr>
    <th> /n/ </th>
    <td> /nw/<sup>2</sup> </td>
    <td> – </td>
    <td> – </td>
    <td> – </td>
  </tr>
</table>  
<sup>1</sup> Only appears with vowel /u/  
<sup>2</sup> Marginal  
<sup>3</sup> /tɹ/ is realized as \[tʃɹ\] and /dɹ/ is realized as \[dʒɹ\]. In rook script, the sequences /tʃɹ/ and /dʒɹ/ are considered invalid and the sound sequences are always spelled tr and dr, respectively

### Coda clusters

Codas are largely reversed from onsets. Rather than /s/ + obstruent + approximant, codas are build as approximant + semi-obstruent + obstruent + /s/, /z/, /t/, /d/.

<table>
  <tr>
    <td></td>
    <th> /ɹ/ </th>
    <th> /l/ </th>
  </tr>
</table>

### Sonorance progression remarks

At a high level, onsets should increase in sonorance toward the vowel and codas should decrease afterwards. A limited number of additional sounds may be added to the beginning or end of a syllable: /s/ at the start of onset, and /s/, /z/, /t/, and /d/ at the end of a coda. 

There are exceptions, but the outline of a typical syllable’s sonorance over time is hump-shaped, peaking at the vowel.

(insert graph)

As mentioned above, onsets are limited to 3 consonants and codas are limited to 4. The onset limit is a consequence of the obstruence progression rules. However, the limiting of codas to 4 consonants is artificial. In fact, a word with alternating /t/ and /s/ could go on forever without a limiting rule, though no words do. Furthermore, the word “angsts” is analyzed by some as /eiŋksts/ (5 coda consonants) though it is spelled in rook script as “angsts\|eingsts” (4 coda consonants) under the view that the \[k\] is not phonemic.

## Other invalid combinations

[Home](/)
