
# Stylesheet 1.0.0

# Table of Contents

- [Preface](#preface)
- [1. Compounds and Word Formation](#1-compounds-and-word-formation)
	- [1.1. Closed compounds](#11-closed-compounds)
	- [1.2. Productive prefixes](#12-productive-prefixes)
- [2. Spelling and Suffixation](#2-spelling-and-suffixation)
	- [2.1. Base dialect](#21-base-dialect)
	- [2.2. House spellings](#22-house-spellings)
	- [2.3. Semantic spelling distinctions](#23-semantic-spelling-distinctions)
	- [2.4. Consonant doubling](#24-consonant-doubling)
	- [2.5. Silent-E before suffix](#25-silent-e-before-suffix)
	- [2.6. Adverbial -wards](#26-adverbial--wards)
	- [2.7. Diacritics](#27-diacritics)
	- [2.8. Data](#28-data)
	- [2.9. File extensions](#29-file-extensions)
- [3. Punctuation and Typographic Rhythm](#3-punctuation-and-typographic-rhythm)
	- [3.1. Oxford comma](#31-oxford-comma)
	- [3.2. House em dash](#32-house-em-dash)
	- [3.3. En dash](#33-en-dash)
	- [3.4. Ellipsis](#34-ellipsis)
	- [3.5. Singular possessives ending in -s](#35-singular-possessives-ending-in--s)
- [4. Capitalization](#4-capitalization)
	- [4.1. The Left and the Right](#41-the-left-and-the-right)
	- [4.2. Race and ethnicity](#42-race-and-ethnicity)
	- [4.3. Regions and cultural geography](#43-regions-and-cultural-geography)
	- [4.4. Institutional and expressive capitalization](#44-institutional-and-expressive-capitalization)
	- [4.5. No capitalization after a colon](#45-no-capitalization-after-a-colon)
	- [4.6. Celestial bodies](#46-celestial-bodies)
- [5. Numbers, Dates, Percentages, and Money](#5-numbers-dates-percentages-and-money)
	- [5.1. Dates](#51-dates)
	- [5.2. Statistical and measured quantities](#52-statistical-and-measured-quantities)
	- [5.3. Percent and percentage points](#53-percent-and-percentage-points)
	- [5.4. Money](#54-money)
	- [5.5. Whole numbers](#55-whole-numbers)
	- [5.6. Units and time](#56-units-and-time)
- [6. Titles, Decks, and Section Headings](#6-titles-decks-and-section-headings)
	- [6.1. Titles and section headings](#61-titles-and-section-headings)
	- [6.2. Decks](#62-decks)
- [7. Political and Election Style](#7-political-and-election-style)
	- [7.1. Districts](#71-districts)
	- [7.2. Partisan lean](#72-partisan-lean)
	- [7.3. Party and ballot lines](#73-party-and-ballot-lines)
- [8. Names, Quotations, Translations, and Apparatus](#8-names-quotations-translations-and-apparatus)
	- [8.1. Names](#81-names)
	- [8.2. Quotations](#82-quotations)
	- [8.3. Foreign language quotations and translation](#83-foreign-language-quotations-and-translation)
	- [8.4. Footnotes](#84-footnotes)
	- [8.5. Abbreviations and initialisms](#85-abbreviations-and-initialisms)

# Preface

This is a house stylesheet for my own prose— as published on *The Hudson Line* and as drafted for publication elsewhere in manuscript form. It attempts to standardize a slew of long-ago learned behaviors to make copyediting less of a pain for my editors and me. To state it plainly or dramatically or both, it brings order to chaos. It nixes some choices I made consistently[^1] and applies others more aggressively, which may be experimental and may just stick. It is also not static, which is why I have chosen a Markdown file with Git version control. It is so very convenient to have the canonical version of this stylesheet as an easily linked `README.md` on GitHub and to edit it within my Obsidian environment.

The *raison d'être*, above all else, is to make my work more consistent. English is this great fractal of so many forms inherited from different languages, so many different regional and register distinctions that do not look, sound, or read identically, and to learn to write English is, at its most fundamental, to inherit many of them unevenly. I prefer to systematize those choices rather than reach for them and "correct" them in copyediting inconsistently across my work. The internet may already be far along in altering English towards shared conventions, but some distinctions deserve a second look. **Program/programme** and **dialogue/dialog**, for instance, carry semantic distinctions that can be useful for narrowing a word's meaning in context. In turn, **judgement** and **likeable** keep more of the base word after suffixation, while words like **travelled** reflect the doubled-consonant forms I strongly prefer to the majority position in American English. And, at times, preference is pure preference and that is okay. No grouping of stylistic choices can be turned into a rulebook of universal heuristics and that is no reason unto itself to abandon them.

Words have **eyefeel** as well as mouthfeel, as does punctuation. Eyefeel is not a lesser category of judgement in writing. Prose is viewed with the eye as well as subconsciously parsed by the generally accepted rules of grammar and syntax and the rest.

Staying on eyefeel, there is also the inconsistency of compounds. English may not be German, but German's comfort with treating concepts as one word more liberally has merit. That is not to say we should create clunky messes like *Streichholzschachtel*. We compound that same concept as *matchbox*. Technical English— in the sciences, in the tech world, all the way out to organizing spaces— tends to compound words far quicker than dictionaries or editorial staff update. We speak some phrases so often that the written internal space or hyphen melts away even as its written compound still carries a quality of strangeness. I am therefore a friend to prospective closed compounds that more likely than not will in several decades be written closed.

Yet some words, even those already deep in the compounding process, may benefit from keeping their hyphen. This is most clear with productive prefixes such as ***anti-***, ***pro-***, and ***co-***, which preserve a relationship between prefix and base word that benefits from the extra-millisecond of a hyphen.

Some house tics survived this standardization. This stylesheet keeps the house em dash, with one space after and no space before the dash. I do not know how I began writing em dashes this way[^2], but I have come to find it preferable on that same principle of *eyefeel*. An unspaced em dash compresses too much to my eye, a spaced one looks too weighty, and, in my opinion, that asymmetric spacing gives the underlying clause both a feeling of subordination to what preceded it (and what comes after in the case of two em dashes) and a sudden pause I find more conducive to how such sentences would be read aloud. Diacritics are relatively maximal without slipping into the overreaching register of *The New Yorker*'s *reëlection* and *coöperate*. Some house tics are annihilated in turn, such as my preference to use hyphens over an en dash in all situations that would usually call for one. Some are revitalized; I revert[^3] to ordinal dates as opposed to cardinal dates, and I clarify my preference for apostrophe-alone possession in cases where a name or noun ends in *-s*.

American English is the base on which all else is built; the spelling of **Merriam-Webster** and the mechanics of ***The Chicago Manual of Style*** are operative except where overridden by this stylesheet. Yet it is easy when choosing to go against the grain to make that your guiding principle; house forms should not be established for the sake of novelty to the detriment of the principles laid out in this preface. At the end of the day, even after this effort to externalize all of this, house style creates a precedent that can be safely broken when a given rule applied in a given moment breaks the flow.

I repeat that this is a living document and exists primarily for reference and personal growth. The canonical version will take effect with the publication of "Tell Us of the End."

[^1]: For instance, I seemed to adore writing the word *eke* as *eeke*, which I interpret retrospectively as an earnest attempt to make the spelling look more like it is pronounced. Unfortunately for past-me, it just looks like a typo.

[^2]: Were I to guess, it's either a quirk of some word processor I used long ago or an errant choice to style it like a colon, comma, semicolon, period, etc.

[^3]: My personal preference in my notes is actually a secret third thing, day–month–year as in 13 October 2026. This is simply too jarring for an American audience to make it into prose.

# 1. Compounds and Word Formation

## 1.1. Closed compounds

Closed compounds are to be used when a given common expression no longer feels like two independent words. It does not need to be in the dictionary, but some kind of established specialist or at least emerging usage should be established. Google Ngram and English-Corpora are good sources for seeing this happen over time.

House forms include, yet are hardly limited to:

**stylesheet  
datapoint  
whitepaper  
artform  
ebike  
factcheck, factchecker, factchecking  
phonebank, phonebanker, phonebanking  
textbank, textbanking**

With all that said, a good heuristic is if the compounded word looks way too gimmicky or draws attention to itself in a way detrimental to the reader, it was a mistake. Discretion advised.

## 1.2. Productive prefixes

A compound often is in the process of closing because the words lose their sense of modification. A **productive prefix**, meanwhile, tends to benefit from retaining a visible break in the word because the prefix modifies the base word in some essential way.

Hyphens are best with prefixes like **co-**, **anti-**, **pro-**, **re-**, **pre-**, and **post-** when it is desired for readers to perceive a slight seam between the prefix and the base word itself.

Prefer:

**co-author  
co-chair  
co-founder  
co-inventor  
co-op**

**anti-trans  
anti-Cuomo  
anti-lynching**

**pro-Israel  
pro-Palestinian  
pro-slavery**

**re-elect  
re-elected  
re-election**

**pre-existing  
pre-written  
pre-certification**

**post-war  
post-election  
post-Mamdani  
post-COVID**

This should not be applied universally simply because a word begins with these prefixes. Sometimes a word is fully lexicalized in typical use for very good reason. At the end of the day, discretion is paramount.

Where parallel compounds share a final element, use a suspended hyphen:

> pre- and post-election polling
> two- and three-point swings

Where a prefix modifies an open compound or some other unit of multiple words, use an en dash in place of an ordinary hyphen where it clarifies structure:

> post–New Deal
> pre–World War II

### Antisemitism

Precedent (including Chicago) has mostly shifted from the form *anti-Semitism* to *antisemitism*, in part as the hyphenated form may imply the existence of some coherent category called *Semitism* to which one is opposed. The term itself emerged in the nineteenth century from a linguistic term referring to all Semitic languages and peoples as a designation for hostility towards Jews. I do not think it is my place to impose my heuristic on all that history, and so **antisemitism** is preferred here.

# 2. Spelling and Suffixation

## 2.1. Base dialect

**American English** remains, fundamentally, the base dialect. Any modifications to it within this section only apply narrowly.

Barring carve-outs here, ordinary American spellings apply unless this guide includes a house spelling[^4]. That means we keep **color**, **center**, **defense**, etc.

[^4]: I found my High COVID Era online AP exams the other day and was quite horrified to learn that I once wrote *favourite*, *colour*, and the like without blinking. How does that even happen?
## 2.2. House spellings

Not everything can be covered by a rule, despite my brain's pleadings.

Prefer:

**grey  
moustache  
advisor  
preventive  
adapter  
alright  
axe**

And to be used freely, though sparingly:

**amongst  
amidst  
whom**

Use the *-t* forms **burnt**, **dreamt**, **leapt**, etc. freely, as in:

> "The house burnt down."  
> "a burnt field"

**Burned** and the like remain useful as finite verbs where it reads better.

> "The campfire burned with an orange glow."

## 2.3. Semantic spelling distinctions

Sometimes different dialects of English or even dated forms preserve a useful distinction.

### check/cheque

**check**: ordinary senses  
**cheque**: banking document with a payee, drawee, etc.

### dependent/dependant

**dependent**: adjective  
**dependant**: a person who depends on another for support

### program/programme

**program**: computing and software  
**programme**: organized agenda, broadcast, initiative, or comparable non-computing sense

### disk/disc

**disk**: computing and magnetic storage  
**disc**: optical or other physical disc, ordinary non-computing sense

### dialogue/dialog

**dialogue**: human, literary, political, or conceptual conversation  
**dialog**: computing or GUI context

### analogue/analog

**analogue**: correspondence, comparison, or counterpart  
**analog**: technical sense, especially in opposition to digital

### license/licence

**license**: verb  
**licence**: noun

Some are a bit more jarring to readers and should be used only after thirty seconds of contemplation.

Generally reject:

### story/storey

*story*: narrative, account  
*storey*: level of a building

And:

### meter/metre

*meter*: instrument that takes a measurement  
*metre*: metric unit of length

To paraphrase back in 1.1: if it looks gimmicky enough to draw unwarranted attention to itself, it was a mistake.

## 2.4. Consonant doubling

Where current English usage permits both a single- and doubled-consonant suffixed form, **prefer the doubled form**. This is most visible with the Commonwealth-preferred doubled-L.

Use:

**travel -> travelling, travelled, traveller  
cancel -> cancelling, cancelled, cancellable  
label -> labelling, labelled, labeller, labellable  
model -> modelling, modelled, modeller, modellable  
signal -> signalling, signalled, signaller, signallable  
fuel -> fuelling, fuelled, fueller  
channel -> channelling, channelled, channeller, channellable  
panel -> panelling, panellist  
level -> levelled, levelling, leveller  
total -> totalling, totalled  
dial -> dialling, dialled, dialler  
trial -> trialling, trialled, trialler  
initial -> initialling, initialled**

Also:

**marvellous  
libellous  
counsellor  
councillor** (in cases where it is not a title or proper noun)  
**medallist  
duellist  
crueller, cruellest  
woollen  
jeweller, jewellery, jewelled**

And for doubled-P, T, R, etc.:

**worshipped, worshipping, worshipper  
benefitted, benefitting  
combatted, combatting  
transferrable  
referrable  
inferrable  
conferrable  
deferrable**

This rule is importantly **selective among existing spellings**. Ngram or the styleguides used in other countries can be consulted for what forms actually exist.

For example, there is no doubled consonant form of:

**targeted  
budgeted  
developed  
offered**

### Doubled-S exception

The consonant-doubling rule does not apply to base words ending in *-s*. It simply looks too noisy and jarring.

Use ordinary spelling:

**focused, focusing  
biased, biasing**

## 2.5. Silent-E before suffix

American English often drops silent-E before a suffix. Here we prefer to **retain the *e* before a suffix when the underlying base word is at least as long as the suffix while dropping it when the suffix is longer than the base word.** This is a proprietary algorithm and admittedly me winging it.

Do not include any productive prefix attached as part of the base. Thus *reuse*'s base word for our purposes is *use*, not *reuse*. Google Ngram is a great source for determining where competing forms exist.

Examples include:

**like + able -> likeable**  
base 4, suffix 4: retain

**move + able -> moveable**  
base 4, suffix 4: retain

**blame + able -> blameable**  
base 5, suffix 4: retain

**trade + able -> tradeable**  
base 5, suffix 4: retain

**use + able -> usable**  
base 3, suffix 4, drop

**reuse + able -> reusable**  
the underlying base remains use, so drop

The rule applies across suffixes:

**age + ing -> ageing**

as *age* and *-ing* both have a `char` length of three.

Other spellings this rule accepts include:

**acknowledgement  
judgement  
abridgement  
sizeable  
liveable  
loveable  
unshakeable**

Again, this is not generative. This does not create forms like *arguement* or *desireable* or *valueable* which have no precedent in English as written today.

Scary LaTeX version:

$$
E:D\to A,
\qquad
D=\lbrace (w,s)\in W_e\times S : ws\in A \ \text{and}\ (w-\text{e})s\in A \rbrace
$$

where $W_e$ is the set of attested English base words that end in silent *e*, $S$ is the set of applicable suffixes, and $A$ is the set of attested English spellings. The domain $D$ contains only those base–suffix pairs for which both variants are attested.

$$
E(w,s)=
\begin{cases}
ws, & \text{if } |B(w)| \ge |s|,\\
\bigl(w-\text{e}\bigr)s, & \text{if } |B(w)| < |s|,
\end{cases}
$$

where $B(w)$ is the underlying base of $w$, excluding any productive prefix.

$$
\begin{aligned}
E(\text{like},\text{able}) &= \text{likeable} && (4 \ge 4),\\
E(\text{move},\text{able}) &= \text{moveable} && (4 \ge 4),\\
E(\text{blame},\text{able}) &= \text{blameable} && (5 \ge 4),\\
E(\text{use},\text{able}) &= \text{usable} && (3 < 4),\\
E(\text{reuse},\text{able}) &= \text{reusable} && (|\text{use}| = 3 < 4),\\
E(\text{age},\text{ing}) &= \text{ageing} && (3 \ge 3).
\end{aligned}
$$

## 2.6. Adverbial -wards

It is house style to favor **-wards** in adverbs over the more common *-ward*:

**towards  
afterwards  
backwards  
forwards  
upwards  
downwards  
inwards  
outwards  
onwards**

That said, *-ward* is okay as an adjective, phrasal verb, etc.:

> "a forward motion"  
> "look forward to"

## 2.7. Diacritics

Prefer the accented form of words that came to English through other languages when that form remains in use even as a minority position in contemporary English:

**cliché  
café  
résumé  
naïve  
façade  
décor  
communiqué  
protégé  
exposé**

When referring to a proper noun, use its spelling verbatim irrespective of this rule.

## 2.8. Data

**Data** is a singular mass noun for our purposes, not dissimilar from *music* or *knowledge* or even *sand*:

> "The data is incomplete."  
> "The data suggests…"

Extending from this, **datapoint** is preferred to *datum*.

## 2.9. File extensions

File extensions, when referred to in running prose, retain a period:

> "…a .pdf on…"

They are pluralized and made possessive in normal fashion:

> "…too many .pdfs about…"
> "…the .pdf's point was not to…"
> "The .css' style is…"

# 3. Punctuation and Typographic Rhythm

## 3.1. Oxford comma

Per Chicago, the **Oxford comma** is always used, regardless of whether or not it is strictly necessary in the parsing of a given sentence.

> "rent, transit, and groceries."

## 3.2. House em dash

Use the house em dash, with no space before and one after:

> "The facts would be clear— eventually."

Exceptions to this particular spacing include (but are not limited to!) identifying a quoted source after a blockquote.

> "A place belongs forever to whoever claims it hardest, remembers it most obsessively, wrenches it from itself, shapes it, renders it, loves it so radically that he remakes it in his image."

_—Joan Didion, "In the Islands"_

## 3.3. En dash

**En dashes** are to be used when referring to ranges of values, scores, and other comparable paired quantities:

**1998–2005  
August 23rd–25th  
57–23%  
31–21  
5–4**

They may also be used to join coordinate terms when neither element straightforwardly modifies another:

**Mamdani–Cuomo race  
labor–management relations  
north–south divide**

Worth noting that districts continue to use hyphens. See 7.1.

They may also attach a modifier to an open compound where a hyphen would look to modify only the word it abuts:

> "New York–based"  
> "post–New Deal"

## 3.4. Ellipsis

Use the Unicode single character ellipsis `U+2026`:

**…**

## 3.5. Singular possessives ending in -s

Apostrophe-only possessive is always used in cases where a given noun or name ends in *-s*, irrespective of pronunciation or any other rule:

**James'  
Harris'  
Congress'  
the boss'  
the witness'  
the IRS'**

# 4. Capitalization

## 4.1. The Left and the Right

**The Left** and **the Right** should be capitalized as proper nouns when referring to political-cultural ecosystems as opposed to simple ideological tendencies in a directional or adjectival way. A bit of a fuzzy concept but clear in context:

> "the institutional Left"  
> "the American Right"  
> "the balance of power on the Left"

Render as lowercase in other such uses of those terms, even in political contexts:

> "a left challenge"  
> "left-wing voters"  
> "moved right"

## 4.2. Race and ethnicity

Racial and ethnic categories should be capitalized except when quoting a source:

**Black  
White  
Asian  
Latino**

## 4.3. Regions and cultural geography

Established names of regions that get their names from directional qualities should be capitalized, even when local sources are inconsistent. Lowercase them in other uses.

> "Upstate's patchwork of counties"  
> "Uptown's socialist past"

> "travelling upstate"  
> "breakfast uptown"

## 4.4. Institutional and expressive capitalization

Common nouns can be capitalized when it is of service to the piece in question to personify or otherwise give them an implied extraordinary quality.

Examples:

**the Twelfth  
Clan Kennedy  
the Republic  
the War**

This can also apply to the titles of political offices, even without a name suffixing them.

**the Mayor of New York  
the President of the United States**

Meanwhile in generic descriptive use:

**the mayor of Lisbon  
the president of the European Council**

Expressive capitalization is permissible in place of italics when that capitalization serves to establish a distinct register. This may be used, for example, to define concepts, or even to inject humor.

Compare:

> "In the *year of our Lord 2026.*"  
> "In the Year of Our Lord Two Thousand and Twenty-Six"

> "Here we find *serious California* and we find *stupid California*, only to find…"  
> "Here we find Serious California and we find Stupid California, only to find…"

Expressive capitalization is of most merit when it is rare. If there are multiple expressive capitalizations repeating on the page close together, consider revisions.

## 4.5. No capitalization after a colon

Lowercase the first word after a colon, even when, standing alone, it could constitute a complete sentence, even if multiple sentences follow. Obvious exception for other capitalization rules such as with proper nouns.

> "He had made himself clear: there would be no further negotiations."

## 4.6. Celestial bodies

Capitalize celestial bodies when being literally referred to:

**the Sun  
the Earth**

But:

> "Andrew Cuomo was the _very sun around which the City of New York rotates…_ until he was not."


# 5. Numbers, Dates, Percentages, and Money

## 5.1. Dates

Ordinal dates are to be used:

**August 23rd, 1949  
February 20th, 1861  
September 27th, 2026**

## 5.2. Statistical and measured quantities

When it comes to statistical and measured quantities, especially non-integers, numerals should almost always be used.

Use the percent sign with numerical percentages:

**31.9%**

A true minus sign − `U+2212` should be used over a hyphen for negative quantities:

**−3.8%**

These rules can be broken sparingly for emphasis, selective humor, and other discretionary purposes.

## 5.3. Percent and percentage points

**Percent** and **percentage points** are easily conflated, but far from interchangeable. It must always be very clear to the reader which is being referred to when writing on statistics.

In shorthand, percentage points should look something like:

> "a 5-point margin"  
> "an 11.6-point swing"

## 5.4. Money

Avoid overly compressed notation such as:

*$299k  
$2.7M*

Prefer:

**$299,000  
$2.7 million**

Again, break this rule sparingly when of service to emphasis, humor, etc.

## 5.5. Whole numbers

When not dealing with statistics, spell whole numbers from zero through one hundred. Also spell out integer multiples of hundred, thousand, million, etc. where they read naturally.

Use numerals for other whole numbers unless spelling them out for emphasis or some other purpose.

## 5.6. Units and time

Abbreviated units generally take a space after a numeral:

**5 mi**  
**22 lb**  

Percents meanwhile should remain closed:

**31.9%**

In running prose, **per** is generally preferable over a slash:

> "sixty miles per hour"

References to time should generally use numerals with **a.m.** and **p.m.**

**7:30 p.m.  
11 a.m.**

Break this rule if stylistically advised.

# 6. Titles, Decks, and Section Headings

## 6.1. Titles and section headings

Titles and section headers strongly default to Chicago 18 title case.

This gets us:

**Morning Along the Hudson  
The Canary in the Coal Mine  
Happiness Is a Warm Gun  
When the World Stopped Making Sense**

Sometimes, though, this may be broken for stylistic reasons.

## 6.2. Decks

Sentence case is always used. Single-sentence decks take **no terminal period**:

**The world comes to the mayor**

Of course, a deck can in theory end with a question mark, exclamation point, etc.

If the deck contains multiple complete sentences or even sentence fragments that are not better presented with a semicolon or comma, periods are fine:

**They didn't all come back. Enough did.**

# 7. Political and Election Style

## 7.1. Districts

Use:

**NY-07**: US House district  
**AD-36**: New York Assembly district  
**SD-07**: New York State Senate district  
**CD-39**: New York City Council district

Pad single-digit district numbers to two digits. Use hyphens, not en dashes.

## 7.2. Partisan lean

Generic partisan lean (such as Cook PVI) is fundamentally dubious and usually to be avoided as a description of political geographies in favor of specific races.

If truly needed:

**D+5  
R+3**

But generally preferred is:

**Harris +0.5  
Mamdani +32.9  
Trump +40.8 in 2024**

Round to the nearest tenth. Disambiguate with year in prose where relevant for clarity in context.

## 7.3. Party and ballot lines

Use compact parenthetical notation like so:

**(D)  
(R)**

In New York, where electoral fusion is relevant:

**(D, WF)  
(R, C)**

Try to only use these in the context of ballot lines listed on the ballot in an upcoming election. Minor ballot lines are inconsistent enough that using such notation for past races may lead the reader to assume more relation between the candidate and minor party than is relevant.

# 8. Names, Quotations, Translations, and Apparatus

## 8.1. Names

Use a person's full name on first substantive reference unless there is a very good reason not to.

From there, surname is generally used. Exceptions may include instances where their common formal name in English is not their surname (e.g., **Lula**) or where their title is preferred, especially in cases where said title is load-bearing or otherwise worth emphasis. Then it may be attached to their surname or even standalone.

**Mayor Mamdani  
The Mayor**

Use the official Latin-alphabet spellings, punctuation, capitalization, and diacritics wherever possible.

## 8.2. Quotations

Preserve quotations exactly, except when using a well-sourced translation or applying terminal punctuation in running prose. Use **[sic]** where needed, sometimes even for humor.

Editorial omission inside a quotation takes:

**[…]**

This is common in continental European academia, and helps clarify that an ellipsis is referring to said omission as opposed to being in the quoted text itself.

## 8.3. Foreign language quotations and translation

Inline foreign phrases should be italicized, but when quoted otherwise, their native system of quotation marks is preferred where not distracting:

**French**: « … » (narrow nonbreaking spaces inside guillemets, `U+202F`)
**Russian, Italian, etc.**: «…»
**German, Icelandic, etc.**: „…“

When I am translating from French or straightforward Spanish myself, I usually find it best to be **accurate in both meaning and form** so long as in doing so the passage does not become unforgivably clunky.

> "Bullard’s Spad VII biplane, with his painted motto _« Tout sang qui coule est rouge »_— "All blood that flows is red" (French Air and Space Force)."

Compare to the often-cited translation:

> "All Blood Runs Red"

That said, if a sourced translation is satisfactory, don't try to be smart.

If a phrase is already fairly known to well-read English speakers, a translation may disrupt the flow of the piece more than serve it.

## 8.4. Footnotes

Footnotes do not behave in the house style as generally conceived of. They are more of a secondary, optional register the reader may explore at their pleasure. They may be encountered as their markers appear on first read, clustered at the bottom after they finish the piece, or never read at all. They are architecture. The general idea is to include such material when writing it as a parenthetical or as subordinate to an em dash or a colon would damage the piece's rhythm or emphasis.

We are not, however, full-David-Foster-Wallacing[^5]. Due to said optionality, material in the footnotes should never quite be load-bearing to the prose of the body. They should never need to be encountered in a particular order or at a particular moment. That said, they may expand or provide more evidence for it, or even just provide comic observations. They can be thought of as somewhere between the cutting-room floor and the main prose— though in truth they are simply their own thing. They have slowly taken over some of the job of parenthetical and em dash asides, though nowhere near entirely.

Attach the marker to the **word of relevance** as opposed to the typical rule of marking a footnote at the end of a sentence.

[^5]: Though at times, in the "Consider the Lobster" sense, perhaps yes?

## 8.5. Abbreviations and initialisms

Unfamiliar abbreviations should use full name and then be defined in a parenthetical when said abbreviation shall recur. Full name is to be used when no abbreviation is used.

> "CUNY's Center for Urban Research (CUR)"

Normal pluralization applies:

**PACs  
CDs**