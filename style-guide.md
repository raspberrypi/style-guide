# Raspberry Pi style guide

This document is being updated continuously; refer to GitHub for the most up-to-date version or, if you rely on a local copy of the style guide, check that you have the most recent version on your machine. If there’s something you think we should add or correct, create a pull request for us to review.

When creating content for Raspberry Pi, we aim for a clear, friendly, and conversational tone. To help with this, this style guide provides practical guidance and examples for written content at Raspberry Pi. For matters not covered in this style guide, consult the ***New Hart's Rules: The Oxford Guide to Style***.

## Quick reference

The table below summarises key style rules for quick reference, ordered according to the main headings in this style guide.

|Rule|Style|
|---|---|
|[Language](#language)| Use British English (default) for UK and international audiences; use AP for US-only audiences. Consult the [Word list](#word-list) for exceptions in a computing context, such as 'program' when referring to a computer program.|
|[Emphasis](#emphasis)| Use *Italics* for narrative writing; use **bold** for technical writing; use `monospace` for code, file names, and paths.|
|[Lists](#lists)| Use bullets for unordered lists and numbers for ordered lists; use Oxford commas, placed before the final item in a list of three or more; use semicolons for lists with internal punctuation.
|[Punctuation](#punctuation)| Use hyphens, en dashes, and em dashes for specified purposes; don't use apostrophes in acronyms; don't use an ampersand (**&**) instead of 'and' or a forward slash (**/**) instead of 'or'.
|[Compounds](#compounds)|Use hyphenated and closed compounds (for example, 'real-time' and 'setup') for clarity depending on sentence structure; use open compounds (for example, 'user manual' and 'open source') where common usage dictates.|
|[Titles of other works](#titles-of-other-works)| Use title case and italics to refer to titles of work (books, films, games, and so on).|
|[Raspberry Pi products](#raspberry-pi-products) | Don't add 'the' before the product names of Raspberry Pi computers, microcontrollers, or camera modules unless referring to a specific device; don't shorten 'Raspberry Pi' to 'Pi'.|
|[Capitalisation](#capitalisation) | Use sentence case for headings and subheadings; avoid starting titles with lowercase trademarks (for example, 'iPad').|
|[Abbreviations](#abbreviations)| Unless well known, spell out an abbreviation on first use, followed by the abbreviation in parentheses in a section. For a list of accepted abbreviations, see the [Abbreviation list](#abbreviation-list).|
|[Numbers](#numbers)|Spell out one to twelve; use numerals for 13 onwards; avoid starting sentences with numerals; use SI unit spacing; for a list of unit suffixes and guidance on their spacing, see [Measurement suffixes](#measurement-suffixes).|
|[Time and date](#time-and-date)|Use the 12-hour clock with a colon (for example, 8:30pm); use day-month-year format (for example, 21 January 2006); spell out decades (for example, the eighties); don't use apostrophes in decades.|
|[Cultural sensitivity](#cultural-sensitivity)|Use people-first, gender-neutral language; use 'disabled' as an adjective, not a noun.|
|[Screenshots and images](#screenshots-and-images)|Avoid dark mode; use full-desktop screenshots; don't overlap windows or visible cursors; provide accessible text descriptions.|
|[FAQs](#FAQs)|Avoid FAQs. Restructure the information so that it appears in context.
|[Links](#links)| Omit http://www from URLs in print; use hyperlinks in online content. For scannability, make links meaningful outside the context of the sentence.
|[Word list](#word-list)| Check correct word and abbreviation usage, including spelling, capitalisation, pluralisation, spacing, and hyphenation rules; be mindful of [words and phrases to avoid](#words-and-phrases-to-avoid).

## Language

Generally speaking, we use British English and plain language, but this depends on the intended audience. We aim to avoid jargon, unnecessarily technical terms, and obscure words. We also avoid non-English or Latin phrases that can be misused or make translation harder. Opt for precise, spelled-out, widely understood English equivalents.

### British English

Most of our content is written in British English, with the exception of:

* References to the names of international organisations, for example, 'The John F Kennedy Space *Center*'.
* Specific words that are written in American English as an industry standard in computing or measurement. For examples (such as 'computer program' and 'multimeter'), see the [Word list](#word-list).
* Content written for a primarily American audience. When content is intended specifically for a US audience, write in American English and refer to ***The Associated Press Stylebook*** for guidance.

For **UK and international audiences**, which is most of our content, write in British English, keeping possible exceptions listed in the [Word list](#word-list) in mind. If a particular spelling or hyphenation choice isn't specified here, refer to the ***Oxford English Dictionary***.

Avoid non-English words, phrases, and abbreviations. Aside from people often using these terms incorrectly (for example, 'de facto' means 'in reality', not 'by default'), non-English words in English documents make translation harder. Similarly, avoid common Latin words, phrases, and abbreviations like 'e.g.' and 'i.e.', especially in technical writing, because these cause the same issues (translation and incorrect usage), and often reduce the clarity of what you’re trying to say. In less technical content, consider using the intended, precise English wording instead (such as 'for example' instead of 'e.g.') unless space is limited. For a list of words, phrases, and abbreviations to avoid, see [Words and phrases to avoid](#words-and-phrases-to-avoid).

### Plain language

Aim to use clear, straightforward language that's easy to understand and read:

* Choose words and phrases that are commonly used.
* Choose simpler alternatives to long, formal, or complicated words. For examples, see [Words with simpler alternatives](#words-with-simpler-alternatives).
* Avoid technical, education, and publishing industry language and jargon in public-facing documentation (for example, 'bookazine' or 'southbridge' to refer to an I/O controller chip).
* If you must use a technical term, define it clearly the first time it's used and ensure it's appropriate for the skills of the intended audience.

## Emphasis

The type of emphasis you use is a context-driven decision:

* Use *italics* for less formal or narrative content.
* Use **bold** for technical content that benefits from elements like UI labels or product names being visually scannable.

Avoid using `monospace` for general emphasis or visual styling. Use `monospace` to format technical elements that appear in (or relate to) code or command-line usage, such as:

* File names and extensions, for example, `config.txt` and `.img`.
* Code elements, including variables, functions, and parameters, for example, `GPIO_PIN`, `gpio_set_value()`, and `baud_rate`.
* Commands and terminal inputs, for example, `pwd` and `raspi-config`.
* Terminal outputs, for example `Hello, world!`.
* Path names and directory structures, for example, `/home/pi/documents` and `/boot/config.text`.

### Narrative writing

*Italics* are a lighter form of emphasis that is generally more appropriate for less formal or narrative writing, such as blog posts, magazine content, and books.

Using *italics* for emphasis aligns with our current usage and reflects the conversational tone common in much of our content. While we previously used **bold** for emphasis, usage has shifted naturally toward italics, and there’s no need to retroactively update older content that uses bold.

### Technical writing

For technical and instructional materials, including datasheets, HTML documentation, and tutorials, **bold** is still preferred. Use bold for specific reasons:

* Reserve bold to highlight important, scannable elements, such as product names, labels, UI elements, settings, navigational elements, and other key details requiring quick visual recognition.
* Avoid bolding whole phrases or sentences; this trains the reader to skim over important content rather than read it. Consider restructuring the content to emphasise important information effectively.
* Avoid bolding words that you just want to emphasise. Use italics instead, but do so very sparingly in technical writing.

## Lists

Use an Oxford (serial) comma immediately before a conjunction (usually 'and' or 'or') in a list of three or more items. For example:

> We photographed the components, a sandwich, and a magnet.

Use semicolons for lists with internal commas. For example:

> We received bouquets from Chris, in California; Jim, in Belgium; and Bob, in Liverpool.

Use bulleted or numbered lists to improve readability and break up content. Complicated lists are usually better presented typographically with bullets or numbers, but don't resort to bulleted lists just because it's the easiest option; consider narrative flow and page layout. Choose the format that best suits the content and structure. If visually breaking up list items with bullets or numbers:

* Use bullets for lists of items with no hierarchy.
* Use numbers for lists of items with an explicit hierarchy, or for steps in a process (such as tutorials).
* Never use letters or Roman numerals for list points.

When creating a bulleted or numbered list, observe the following guidance:

* Use parallel phrasing between bullet points.
* Capitalise the first word of each item.
* Use full stops when the list items are complete sentences.
* Don't use full stops for lists that consist only of short phrases or fragments, unless other list items are longer and thus use full stops.
* If list items are complex or contain internal punctuation, use semicolons.

A bulleted list should be introduced with a colon. For example:

> This is a bulleted list:
> *   First list item
> *   Second list item
> *   Third list item

For consistency, if an item in a bulleted list includes a sentence (thus requiring a full stop), then end every item in that list with a full stop, even fragments. For an example, see [Titles of other works](#Titles-of-other-works) in this style guide.

## Punctuation

Use punctuation to help readability and comprehension. Don't overuse punctuation marks. This section of the style guide provides guidance on the following:

- [Full stops](#full-stops)
- [Commas and semicolons](#commas-and-semicolons)
- [Colons](#colons)
- [Hyphens and dashes](#hyphens-and-dashes)
- [Quotation marks](#quotation-marks)
- [Apostrophes](#apostrophes)
- [Symbols](#symbols)

### Full stops

Only use one space after a full stop. The use of two spaces after a full stop is a typewriter convention used to help visually distinguish between sentences written in monospaced fonts. Computer fonts are usually proportional, making it easier to see the end of a sentence with just one space.

Don't add full stops in the following scenarios:

|Scenario|Do|Don't
|---|---|---|
Heading|**Introducing Raspberry Pi 5**|**Introducing Raspberry Pi 5.**
Fragment, such as a definition| **fragment** (noun): An isolated or incomplete part of something|**fragment** (noun): An isolated or incomplete part of something.
Email or web address (unless part of a full sentence)| Website: [www.raspberrypi.com](www.raspberrypi.com)|Website: [www.raspberrypi.com](www.raspberrypi.com).
Acronym or initialism | URL| U.R.L.

When part of a full sentence, ensure that the link text doesn't include the full stop. For example:

> For more information, see our [Style Guide](#style-Guide).

### Commas and semicolons

Commas separate parts of a sentence so that the meaning is clear. Sentence structure determines their correct use.

#### Oxford (serial) commas

Use an Oxford (serial) comma after the second-to-last item in a list. Always use an Oxford comma, even when it seems like the meaning is obvious; they resolve ambiguity and should be used everywhere that they apply for consistency.

#### Relative clauses

A relative clause is introduced by a relative pronoun like 'that', 'which', 'who', 'whose', 'where' and 'when'.

* Use a comma before the relative pronoun when the relative clause is non-restrictive (provides additional information).
* Don't use a comma before the relative pronoun when the relative clause is restrictive (provides essential or defining information).

If you're unsure about which to use, consider whether the relative clause identifies which noun you mean or whether it adds information about an already identified noun. Could the relative and main clauses form different sentences and still carry the same meaning? For example:

|Example|Type|Meaning|
|---|---|---|
|I like the person who is the kindest.|Restrictive|There are multiple people but I like the kindest one.|
|I like the person, who is the kindest.|Non-restrictive|I like the person and they are also the kindest.|
|I like the person. They are the kindest.|Multiple sentences| I like the person and they are also the kindest.|

Although non-restrictive relative clauses don't limit or define the noun they modify, they can still offer useful contextual information, such as an explanation, reason, or contrast between the relative clause and the main clause. The clause might not be *grammatically* essential because the noun is already clear without the clause, but it's still informationally useful.

In British English, '**that**' is preferred for restrictive clauses and doesn't require a comma before it; '**which**' is preferred for non-restrictive clauses and requires a comma before it. For example:

|Example|Type|Meaning|
|---|---|---|
|I like the jam **that** has a purple label.|Restrictive|There are multiple jams and I like the one with a purple label.|
|I like the jam, **which** has a purple label.|Non-restrictive| I like the jam and it has a purple label.|
|I like the jam. It has a purple label.|Multiple sentences| I like the jam and it has a purple label.|

#### Semicolons

If you find yourself adding more commas to make your sentence readable, consider splitting it into two sentences instead. If a full stop feels too abrupt, you can use a semicolon instead. For example:

> At Raspberry Pi, we're committed to railing against the death of the semicolon; it's a very useful piece of punctuation.

However, you should be careful not to overuse semicolons. Use a semicolon to separate two or more clauses that hold equal significance and are connected; they bind two sentences together more closely than a full stop.

Ensure there is a full sentence on both sides of the semicolon, unless using the semicolon in a list to separate items with internal punctuation, like commas. For an example, see [**Lists**](#lists) in this style guide.

### Colons

Don't confuse colons with semicolons. A colon (**:**) introduces information, such as lists, explanations, or examples. The capitalisation after a colon depends on the context.

|Context rule| Example|
|---|---|
|When a colon is used in free text, the letter following the colon should be lowercase. |I have three dogs: a small one, a medium one, and a big one.|
| When a colon is preceded by a header-style construction, the letter following the colon should be uppercase. |**Note:** This sentence wouldn’t look so great starting with a lower-case 't'.|
|When a colon is used in a title, the letter following the colon should be upper-case.| Raspberry Pi Radio Module 2: A wireless communication module for Raspberry Pi microcontrollers|

### Hyphens and dashes

Don't confuse hyphens with en dashes or em dashes. Follow the guidance in this section to decide when and how to use a hyphen, en dash, or em dash.

#### Hyphens (-)

A hyphen (**-**) joins words or parts of words together, helping to clarify their meaning. It isn't interchangeable with other types of dashes.

Use hyphens in the following cases. Where the en dash rules in this style guide don't help, consult ***New Hart's Rules: The Oxford Guide to Style***.

##### Prefixes and suffixes

Use a hyphen if the prefix or suffix creates a double vowel or consonant that could confuse the reader. For example:

- re-enter
- shell-like
- multi-industry

Most prefixes don't require a hyphen, but this depends on the context and includes some exceptions.

|Prefix|Guidance|Examples|
|---|---|---|
|co|Use a hyphen to join words that form a new word; don't use a hyphen for words that already include 'co'; use a hyphen where dictated by standard British English.|co-workers; coincidence; co-ordinate; co-author|
|macro| Usually no hyphen, unless the root word starts with a vowel or a capital letter.|macroscale; macro-economics|
|mega| Usually no hyphen, unless the root word starts with a vowel or a capital letter.|megabyte; mega-event|
|micro|Often no hyphen; depending on the word, it is sometimes used with a space, and sometimes used without a space. Check the [**Word list**](#Word-list).|microchip; microSD; micro USB; micro HDMI|
|mini|Usually no hyphen; used with a space if 'mini' is being used as a standalone modifier.|minicomputer; mini USB; mini fridge|
|multi|Usually no hyphen, unless the root word starts with a vowel or a capital letter; see the [**Word list**](#Word-list) for the 'multi-touch' and 'multi-word' exceptions.| multicore; multi-industry; multi-touch|
|over|Usually no hyphen.|overclock; overload|
|pre| Usually no hyphen, unless the root word starts with an 'e' or a capital letter; see the [**Word list**](#Word-list) for the 'pre-soldered' exception.|preprandial; pre-election; pre-MP3; pre-soldered|
|re|Don't use a hyphen for words with the 're' prefix unless you need to distinguish the word from a similar word, the following word begins with an 'e', or the root word starts with a capital letter.|rewrite; re-evaluate; re-form (form again) versus reform (make changes)|
|sub|Usually no hyphen, unless the root word starts with a 'b' or a capital letter.|subnetwork; subdomain; sub-boot; sub-Victorian|
|super|Usually no hyphen.|superuser; supercapacitor|
|under|Usually no hyphen.|underflow|

##### Adjectives before a noun

Hyphenate multi-word adjectives appearing before a noun. For example:

> - up-to-date advice
> - real-time data

No hyphen is needed for multi-word adjectives appearing after a noun. For example:

> - advice that is up to date
> - processed in real time

For full guidance on hyphenating multi-word adjectives, see [**Compounds**](#compounds) below.

##### Two or more modifiers before a noun

Hyphenate two or more modifiers before a noun unless the first modifier is an adjective that modifies the complete noun phrase. The following example hyphenates 'fascist-robot', which creates a single, combined idea describing the people (enthusiasts of fascist robots):

> The moderators are fascist-robot enthusiasts.

The following phrase doesn't hyphenate 'fascist robot'. This changes the meaning of the sentence, now describing the people (robot enthusiasts) as fascists, rather than the robots:

> The moderators are fascist robot enthusiasts.

##### Adverbs ending in -ly

Don't hyphenate adjectival compounds starting with adverbs ending in -ly. For example:

> It was an exclusively designed device.

##### Compound nouns and adjectives

Hyphenate words functioning as adjectives; leave open as nouns. For example:

> - There was a brute-force attack (*adj.*)
> - It was solved by brute force (*noun*)

For full guidance on compound nouns and adjectives, see [**Compounds**](#compounds) below.

##### Verb phrases becoming nouns or adjectives

When the verb phrase becomes a noun (thing) or an adjective (modifying a noun), it solidifies into a compound. Some phrases require a hyphen to indicate that they are now compounds. For example:

> - We have an opt-in policy (*noun*)
> - The user must opt in (*verb phrase*)

**Note:** Sometimes, you can omit hyphens in familiar compound nouns (for example, social network). For more examples, see [**Familiar open compounds**](#familiar-open-compounds) below.

Not all verb phrases becoming nouns or adjectives require a hyphen. Some cases remove the space between the words instead (for example, 'setup instructions'). For full guidance on verb phrases becoming nouns or adjectives, including more examples, see [**Compounds**](#compounds) below.

##### Suspended hyphens

When two or more related modifiers share the same ending, you can avoid repetition by using suspended hyphens. If the sentence feels complex or confusing, write out the full hyphenated phrase each time it appears.

|Suspended hyphen examples | Full phrase examples|
|---|---|
|A 12- and 15-month subscription | A 12-month and 15-month subscription|
|Full- and part-time jobs |Full-time and part-time jobs|
|10-, 20-, and 30-year plans |10-year, 20-year, and 30-year plans

#### En dashes (**–**) and em dashes (**––**):

In British English, the en dash serves several distinct purposes and is more common than the em dash. An en dash (**–**) is longer than a hyphen (**-**) but shorter than an em dash (**––**).

Em dashes are more widely used in American English. In British English, em dashes tend to be reserved for denoting interrupted speech. For readability, some publishers also use open em dashes instead of open en dashes for parenthesis. At Raspberry Pi, we recommend using the open em dash for parenthesis, as outlined in [**Open en and em dashes**](#open-en-and-em-dashes), below.

##### Closed en dashes

In British English, closed en dashes (with no space on either side) are used for:

|Use|Description|Examples|Notes|
|---|---|---|---|
|Ranges|The en dash denotes the word 'to' in a range.|Monday–Friday; pages 7–17|For clarity, consider using the word 'to' instead of an en dash.|
|Connections and relationships|The en dash expresses a link between two places, people, or entities.|Amsterdam–London train; Dover–Calais crossing; Williams–Navratilova match||
|Complex compound modifiers| The en dash connects elements within a complex compound, for example, when one element is an open compound (e.g., 'Raspberry Pi') or a hyphenated compound (e.g., 'e-book').|Raspberry Pi–powered; e-book–only publisher; public school–educated; post–World War II era|For information about compounds, including examples, see [**Compounds**](#compounds) below.|

##### Open en and em dashes

In British English, open en dashes (with a space on either side) are typically used for emphasis, pause, and parenthesis for a phrase or clause.

At Raspberry Pi, we often use *open em dashes* instead for visual clarity. If writing in American English, em dashes with no space around them would be used instead. This is because it's more readable in blog posts and other online writing.

Due to their stylistic nature and possible ambiguity, avoid open en and em dashes in **technical writing**; use the specific, intended punctuation instead.

|Use|Description|Examples|Notes|
|---|---|---|---|
|Introduction|An en or em dash is used in place of a colon to introduce information.|I didn't have an educated background –– Dad was a farm labourer.|This is a stylistic and informal style that's more common in journalism and creative writing.|
|Emphasis or pause|An en or em dash is used to mark a break in a sentence, often for emphasis.|We decided to go ahead –– despite the risks.|This is a stylistic and informal style that's more common in journalism and creative writing.|
|Parenthesis|A pair of en or em dashes are used to make a parenthetical statement in the middle of a sentence, often to express a more pronounced break in the sentence than commas but less of a break than brackets.|The family –– my mum, dad, and sister –– were all coming for dinner. |If using punctuation in the parenthetical part, the closing dash may be preceded by an exclamation mark or a question mark without the following word being capitalised, unless it's a proper noun.|

Don't overuse open en or em dashes. En and em dashes are versatile and typically more informal, but they should be used sparingly to avoid overloading a sentence with interruptions.

#### Quotation marks

Don't use scare quotes –– double quotation marks put around a word or phrase in a written sentence to show that the word is being used in a special way, or in a way that might not be correct or true. Scare quotes make for vague, sensationalist writing.

Use single quotes to highlight a word or phrase when needed, such as when you introduce a new term or need to offset a title.

> - Ask what the word 'system' means.
> - Hand out the 'Bicycle system' activity sheet.

Be judicious in your use of quotation marks in this way. If the word or phrase stands out to the reader without them, leave them out; if the reader might stumble over the word or phrase without them, put them in.

Use double quotation marks to indicate quoted speech and single quotation marks to indicate quoted speech inside quoted speech. In large sections of quoted speech, put double quotation marks at the end of each paragraph rather than omitting them, in accordance with the ***Oxford Guide to Style***.

#### Apostrophes

Use apostrophes to show possession and contractions.

Don't use apostrophes in abbreviated plurals. For example:

> - PCs
> - BGAs

Apostrophes may be used when an abbreviation is turned into a verb, although it's best practice to avoid doing this altogether. For example:

> My mother won't stop DM'ing me.

#### Symbols

The following symbols should be avoided in favour of the words that they are intended to denote:

* The 'at' symbol (**@**); reserve this symbol for email addresses.
* The percent symbol prefacing 'age' (**%age**); spell out **percentage** (used when you don’t specify a quantity, for example, 'a large percentage of time').
* Ampersand (**&**); always use 'and'. The exception might be in a print article for one of our magazines, where space is at a premium.
* Forward slash (**/**); choose between 'and' and 'or'. This includes the phrase **and/or**. If a slash _is_ needed, don't include a space either side of it. The exception for the forward slash is when it's used in a unit of measure (for example, Mb/s)

You can usually use 'or' instead of a slash, but sometimes 'and' might be more appropriate. The following table provides some examples:

|Example| Correct alternative|
|---|---|
| You can pay by credit/debit card. | You can pay by credit or debit card.|
| Submit feedback by phone/email. | Submit feedback by phone or email.|
| This feature is available for desktop/mobile users. | This feature is available for both desktop and mobile users.|
|Developers are prohibited from collecting, storing, and/or using personally identifiable  data. | Developers are prohibited from collecting, storing, or using personally identifiable data.|
| Choose option 1 and/or option 2. | Choose one or both of the following two options.
|When listing several products and/or models ... | When listing several products or models ...|

## Compounds

A compound is a word or phrase made up of two or more words that function as a single unit, often creating a new meaning. Compounds come in different forms.

- Hyphenated compounds, for example, 'well-known author' and 'real-time processing'.
- Closed compounds, for example, 'notebook' and 'setup'.
- Open compounds, for example, 'open source', and 'user manual'.

### Compound modifiers

Compound modifiers are multi-word adjectives that appear directly before a noun and are usually hyphenated (and sometimes closed into a single word, for example, 'frontend'). In the following examples, 'up-to-date' and 'real-time' need to be hyphenated to clarify that the words function as a single modifier:

> - What's a good place for up-to-date advice on hyphenation?
> - We collect real-time data.

Don't hyphenate (or close) compound modifiers when they appear *after* the noun they modify. In the following example, you don't need to hyphenate 'up to date' because it follows the noun 'advice':

> We try to make sur that our advice on hyphenation remains up to date.

Don't hyphenate (or close) compound modifiers when they appear after a preposition or linking verb. In the following example, you don't need to hyphenate 'real time' because it is a noun phrase, not a compound modifier before a noun:

> The data is processed in real time.

**Note:** There are exceptions to this rule like 'well-known', 'industry-wide', 'self-employed', and 'word-of-mouth', which typically always include hyphens no matter where they are in a sentence.

Words that can appear in compound modifiers often exist in open form as nouns or adverbs and, in these cases, aren't hyphenated or closed. Use hyphens (or close the word as appropriate) when the words function as an adjective (i.e., when they modify a noun); leave the words open (no hyphen) when they function as a noun or adverbial phrase. For example:

|Adjective|Noun or adverbial phrase|Examples|
|---|---|---|
|all-expenses-paid|all expenses paid|It's an **all-expenses-paid trip** (*adj.*); The trip has **all expenses paid** (*noun phrase*)|
|all-ones|all ones|It's an **all-ones value** (*adj.*); The value is **all ones** (*noun phrase*)|
|all-zeros|all zeros|It's an **all-zeros value** (*adj.*); The value is **all zeros** (*noun phrase*)|
|backend|back end|They are a **backend developer** (*adj.*); The back end of the banking app handles secure transactions and updates records (*noun*)|
|back-to-school|back to school|There's a **back-to-school sale** (*adj.*); It's time to go **back to school** (*adverbial phrase*)|
|brute-force|brute force|It was a **brute-force attack** (*adj.*); It was solved by **brute force** (*noun phrase*)|
|end-of-year|[No standard noun or adverbial form]|I need to submit an **end-of-year report** (*adj.*)|
|floating-point|floating point|It's a **floating-point number** (*adj.*); Errors can occur in **floating point** (*noun phrase*)|
|frontend|front end|They are a **frontend developer** (*adj.*); The front end of the banking app displays account balances (*noun*)|
|real-time|real time|We collect **real-time data** (*adj.*); The data is processed in **real time** (*adverbial phrase*)|
|word-processing|word processing|It's a **word-processing program** (*adj.*); They specialise in **word processing** (*noun*)|

### Compound nouns and adjectives

When the verb phrase becomes a noun (thing) or adjective (modifying a noun), it solidifies into a compound. Depending on the compound, remove the space or add a hyphen to signify that the words form one conceptual unit rather than separate words performing an action. For example:

|Noun or adjective|Open verb phrase|Examples|
|---|---|---|
|drag-and-drop|drag and drop|The product includes **drag-and-drop functionality** (*adj.*); You can **drag and drop** files (*verb*)|
|backup|back up|Take a **backup** first (*noun*); **Back up** your files (*verb*)|
|cut-out| cut out|There's a **cut-out** in the side of the case for the camera cable (*noun*); **Cut out** that paragraph (*verb*)|
|grown-up|grown up|Talk to an **grown-up** (*noun*); They made a **grown-up** decision (*adj.*); The students were all **grown up** (*verb*)
|livestream| live stream|The **livestream** was recorded (*noun*); We're setting up a **livestream event** (*adj.*); We will **live stream** the event (*verb*)|
|lookup|look up|The database contains a **lookup** of all IDs (*noun*); Create a **lookup table** (*adj.*); I need to **look up** the definition (*verb*)|
|meetup|meet up|There's a **meetup event** (*adj.*); Let's **meet up** later (*verb*)|
|opt-in|opt in|There's an **opt-in policy** (*adj.*); The user must **opt in** (*verb*)|
|pop-up|pop up|A **pop-up** appeared on my screen (*noun*); A **pop-up window** appears (*adj.*); The app can **pop up** notifications (*verb*)|
|sign-in|sign in|There's a **sign-in process** (*adj.*); **Sign in** to your account (*verb*)|
|sign-out|sign out|There's a **sign-out process** (*adj.*); **Sign out** of your account (*verb*)|
|sign-up|sign up|Complete your **sign-up** first (noun); A **sign-up form** is available online (*adj.*); **Sign up** for an account (verb)|
|setup|set up| The **setup** took 5 minutes (*noun*); Follow the **setup instructions** (*adj.*); **Set up** your Raspberry Pi (*verb*)|
|shutdown|shut down|The unexpected **shutdown** caused data loss (*noun*); We performed a **shutdown procedure** (*adj.*); **Shut down** the computer (*verb*)|
|spellcheck|spell check|Run a **spellcheck** before submitting (*noun*); The app includes a **spellcheck feature** (*adj.*); **Spell check** your document (*verb*)|
|startup|start up|The **startup** is seeking investors (*noun*); **Start up** your system (*verb*)|
|walkthrough|walk through| Give me a **walkthrough** (a guided set of instructions) of the software (*noun*); The **walkthrough guide** was helpful (*adj.*); Let’s **walk through** the installation process (*verb*)|

### Familiar open compounds

No hyphen is needed in the following examples because they are familiar, established, multi-word compounds that don't cause confusion:

> - Science fiction, for example, "I like science fiction novels".
> - Social network, for example, "I'm conducting social network analysis".
> - Labour market, for example, "This is labour market liberalisation".
> - Machine vision, for example, "I like machine vision applications".
> - Number one, for example, "It's my number one love".
> - Open source, for example, "This is open source content".
> - Edge AI, for example, "This is an edge AI approach".

## Titles of other works

Set titles of other works in title case. For guidance on title case, see [**Capitalisation**](#capitalisation).

For software titles, use the capitalisation style chosen by the developer or publisher. Many examples of software title capitalisation are included in the [**Word list**](#Word-list) below; if you encounter more that you think we should add, open a pull request on this style guide.

Treatment of titles depends on the type of work. In general, titles should be set in *italics*.

Italicise the titles of the following types of works:

* Artworks
* Books, book chapters, and other parts of books
* CDs and albums
* DVDs
* Lectures
* Magazines and newspapers
* Films, operas, and plays
* Songs and poems
* Speeches with titles
* Television, podcast, and radio programmes, including episodes
* Web shows, webinars, and online videos

Don't italicise titles if they fall under one of the following categories:

* Blogs (unless the blog publishes posts under a date only)
* Games (computer games, board games, card games, arcade games)
* Magazine and newspaper articles
* Websites
* Software

Instead, use single quotation marks for items in the above list.

If compiling a numbered or bulleted list consisting only of titles, you don't need to set the titles in italics because they don't need to stand out from any surrounding text. For example:

> Jemima's favourite old movies are:
>
> *   Gone With the Wind
> *   Singin' in the Rain
> *   The Third Man

For a list of items that doesn't consist only of titles, set any titles in italics. For example:

> These are a few of my favourite things:
>
> *   Sausages
> *   Banditry
> *   *Anne of Green Gables*

## Raspberry Pi products

This section describes how you should refer to Raspberry Pi computers, microcontroller devices, microcontroller boards, camera modules, and other Raspberry Pi devices, accessories, and peripherals.

Official nomenclature exists in the internal Product Names Register on Cognidox and the external [products page](https://www.raspberrypi.com/products/). See also the [Product naming list](#product-naming-list) below.

### Articles

Consider whether you're referring to Raspberry Pi as a concept, or to a specific Raspberry Pi device.

If writing about our product line, avoid adding 'the'. For example:

> 'Raspberry Pi 5 is a single-board computer (SBC)'; not '*The* Raspberry Pi 5 is a single-board computer (SBC)'.

If writing about a specific Raspberry Pi –– one that your reader is using in a project or the one you're holding in your hand –– use the appropriate article. For example:

> - Pick up a Raspberry Pi.
> - Insert a microSD card into your Raspberry Pi.
> - Mount the HAT on the Raspberry Pi.

Sometimes, for reasons of flow and readability, an article might be better used where we wouldn't usually use one according to the strict terms of this document. Exercise stylistic judgement.

### Plurals

The plural of 'Raspberry Pi' is 'Raspberry Pis', with no apostrophe.

To avoid adding an 's' to 'Pi', add a word like 'computers' or 'devices' where possible. For example:

> - Raspberry Pi computers
> - Raspberry Pi devices
> - Raspberry Pi microcontrollers
> - Raspberry Pi radio modules

### Shortening

'Pi' is always preceded by 'Raspberry'. Never write things like 'Pi 4' or 'Pi Zero'. If you want to shorten the name of a model, you can do so in the following way:

> Raspberry Pi 2 Model B >> Raspberry Pi 2B.

When listing several products or models, you can usually omit the full name of each product or model after the first one.

|Full| Shortened|Shorter|
|---|---|---|
Raspberry Pi Zero 2 W, Raspberry Pi 2, Raspberry Pi 3, Raspberry Pi 3+, and Raspberry Pi Compute Module 3. | Raspberry Pi Zero 2 W, Raspberry Pi 2, 3, and 3+; and Raspberry Pi Compute Module 3.|Raspberry Pi 2, 3, 3+, and Zero 2 W; and Raspberry Pi Compute Module 3.

Be careful with when using **Raspberry Pi 1** — the **1** is only necessary when you need to clearly distinguish it from other models; be aware that **Raspberry Pi 1** could be confused with **RP1**, which is a chip we use rather than a single-board computer.

Almost all accessories, peripheral, and add-on boards can take a definite article ('the') before their product name. For example:

> - The Raspberry Pi Sense HAT
> - The Raspberry Pi Mouse
> - The Raspberry Pi High Quality Camera

**Note:** Raspberry Pi Touch Displays, AI HATs, and Camera Modules don't take a definite article, even though other accessories like the Raspberry Pi High Quality Camera does; that's to do with how clunky things like 'the Raspberry Pi Camera Module _n_' sounds.

Unless needed, omit 'Raspberry Pi' from the name in most instances following the first mention. For example:

> You can do all kinds of experiments with the **Raspberry Pi Sense HAT**, which is why there are two of them on the International Space Station. The **Sense HAT** has an array of sensors, a five-button joystick, and an 8 x 8 RGB LED matrix. [...] We recommend using the **Raspberry Pi USB-C Power Supply**, which represents excellent value.

### Product naming list

This section lists the official names of Raspberry Pi products, including their shortened form. Devices are grouped by type and then listed in reverse chronological order, with the most recent model listed first.

#### Single-board computers (SBC)

None of the following flagship SBCs include 'the' before them unless referring to a specific Raspberry Pi in front of the user.

**Note:** Only refer specifically to **Raspberry Pi 1** when you need to distinguish it from other models. Not to be confused with **RP1**, which is a chip used in **Raspberry Pi 5**.

##### Model B variants

**Model B** indicates the presence of an Ethernet port. Newer models don't specify **Model B** because the Ethernet port now comes as standard.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Raspberry Pi 5**|None; don't shorten to 'Pi 5'|||
|**Raspberry Pi 4 Model B**|**Raspberry Pi 4B**; don't shorten to 'Pi 4' or 'Pi 4B'|||
|**Raspberry Pi 3 Model B+**|**Raspberry Pi 3B+**; don't shorten to 'Pi 3B+'||Upgraded to a 1.4 GHz CPU, faster Ethernet, dual-band Wi-Fi, and PoE support.|
|**Raspberry Pi 3 Model B**|**Raspberry Pi 3B**; don't shorten to 'Pi 3B' or just '3B'||Upgraded to a 1.2 GHz CPU, Wi-Fi, Bluetooth, and USB boot support.|
|**Raspberry Pi 2 Model B**|**Raspberry Pi 2B**; don't shorten to 'Pi 2B' or just '2B'||Upgraded to a 900 MHz CPU and 1 GB of RAM.|
|**Raspberry Pi Model B**|None; don't shorten to 'Pi 1B'|Don't refer to this model as **Raspberry Pi 1**. Instead, refer specifically to **Raspberry Pi Model B**.||

##### Model A variants

**Model A** indicates a lower-cost model with the same key features as **Model B**, but with less RAM and a smaller form factor.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Raspberry Pi 3 Model A+**|**Raspberry Pi 3A+**; don't shorten to 'Pi 3A+'||Same features as Raspberry Pi 3B+, but with 512 MB RAM and a smaller form factor.|
|**Raspberry Pi Model A**|None; don't shorten to 'Pi 1A' or just '1A'| Don't refer to '**Raspberry Pi 1**' unless overtly distinguishing it from later models. Instead, refer specifically to **Raspberry Pi Model A**.|Same features as **Model A**, but with 256 MB RAM, no Ethernet, and fewer USB ports.|

#### Keyboard computers

Raspberry Pi keyboard computers are named in line with the flagship SBC they're based on. For example, Raspberry Pi 400 is a keyboard computer based on Raspberry Pi 4.

As with SBCs, none of the following keyboard computers include 'the' before them unless referring to a specific keyboard computer in front of the user.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Raspberry Pi 500+**|None; don't shorten to 'Pi 500+'|Named with a plus sign (**+**) because it's based on **Raspberry Pi 500**, with the same processor, but also some changes.|Added more RAM, an M.2 slot, and mechanical keys with RGB backlighting.|
|**Raspberry Pi 500**|None; don't shorten to 'Pi 500'|Named because it's based on **Raspberry Pi 5** (without the PCIe interface).|Upgraded to 2.4 GHz CPU and 8 GB of RAM.|
|**Raspberry Pi 400**|None; don't shorten to 'Pi 400'|Named because it's based on **Raspberry Pi 4**.||

#### Zero series

Zero devices are compact, low-cost, low-power SBCs that provide basic functionality and Linux compatibility for minimal, embedded computing applications.

None of the following Zero-series models include 'the' before them unless referring to a specific Raspberry Pi Zero in front of the user.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Raspberry Pi Zero 2 W with headers**|**Zero 2 W with headers**; don't shorten to 'Pi 0 2WH'|**W** indicates wireless; **with headers** indicates pre-soldered header pins; unlike **Zero WH**, ‘**headers**’ isn’t shortened to ‘**H**’.|Added pre-soldered pins.|
|**Raspberry Pi Zero 2 W**|**Zero 2 W**; don't shorten to 'Pi 0 2W'|**W** indicates wireless.|Upgraded to a faster CPU and introduced wireless as standard.|
|**Raspberry Pi Zero WH**|**Zero WH**; don't shorten to 'Pi 0 WH'|**W** indicates wireless; **H** indicates pre-soldered header pins.|Added pre-soldered pins.|
|**Raspberry Pi Zero W**|**Zero W**; don't shorten to 'Pi 0 W'|**W** indicates wireless.|Introduced Wi-Fi and Bluetooth.|
|**Raspberry Pi Zero v1.3**|**Zero v1.3**; don't shorten to 'Pi Zero 1.3'||Added camera connector.|
|**Raspberry Pi Zero**|**Zero**; don't shorten to 'Pi Zero'|||

#### Pico series

Pico devices are compact microcontroller boards based on Raspberry Pi–designed silicon chips: **RP2040** and **RP2350** (also referred to as **microcontrollers**). Unlike other Raspberry Pi devices, they don't run Linux or support removable storage, and are instead programmed by flashing binaries to the on-board flash memory.

None of the following Pico series models include 'the' before them unless referring to a specific Raspberry Pi Pico in front of the user.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Raspberry Pi Pico 2 W with headers**|None; don't shorten to 'Pico 2 WH'|**W** indicates wireless; **with headers** indicates pre-soldered header pins; unlike **Pico WH**, ‘**headers**’ isn’t shortened to ‘**H**’.|Includes Wi-Fi, Bluetooth, and pre-soldered pins in one device.|
|**Raspberry Pi Pico 2 W**|None; don't shorten to 'Pico 2 W'|**W** indicates wireless.|Introduced Wi-Fi and Bluetooth.|
|**Raspberry Pi Pico 2**|None; don't shorten to 'Pico 2'||Introduced the RP2350 microcontroller (chip).|
|**Raspberry Pi Pico WH**|None; don't shorten to 'Pico WH'|**W** indicates wireless; **H** indicates pre-soldered header pins.|Includes Wi-Fi, Bluetooth, and pre-soldered pins in one device.|
|**Raspberry Pi Pico W**|None; don't shorten to 'Pico W'|**W** indicates wireless.|Introduced Wi-Fi and Bluetooth.|
|**Raspberry Pi Pico H**|None; don't shorten to 'Pico H'|**H** indicates pre-soldered header pins.|Added pre-soldered pins.|
|**Raspberry Pi Pico**|None; don't shorten to 'Pico'|||

#### Compute Modules

Compute Modules are boards designed for embedded and industrial applications that provide the same hardware as flagship SBCs but in a smaller form factor with no on-board connectors. Instead, they connect to separate carrier boards (which can be **Raspberry Pi [Compute Module IO boards](#compute-module-io-boards)**) that supply the necessary ports and pins.

None of the following Compute Module models include 'the' before them unless referring to a specific Raspberry Pi Compute Module in front of the user.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Compute Module Zero Lite**|**CM0Lite**; don't shorten to 'Compute Module 0 Lite'|Name based on **Compute Module Zero** but with no storage.||
|**Compute Module Zero**|**CM0**; don't shorten to 'Compute Module 0'|Named based on **Raspberry Pi Zero**.||
|**Compute Module 5 Lite**|**CM5Lite**|Name based on **Compute Module 5** but with no storage.||
|**Compute Module 5**|**CM5**|Named based on **Raspberry Pi 5**.||
|**Compute Module 4 Lite**|**CM4Lite**|Name based on **Compute Module 4** but with no storage.||
|**Compute Module 4**|**CM4**|Named based on **Raspberry Pi 4**.|Two 100-pin high-density connectors in a smaller footprint.|
|**Compute Module 4S**|**CM4S**|Named based on **Raspberry Pi 4**.||
|**Compute Module 3+**|**CM3+**|Named based on **Raspberry Pi 3 Model B+**.||
|**Compute Module 3**|**CM3**|Named based on **Raspberry Pi 3**.||
|**Compute Module 1**|**CM1**|Named based on the original Raspberry Pi.||

#### Compute Module IO boards

Compute Module IO boards are carrier boards designed to provide the physical connectors needed for **[Compute Modules](#compute-modules)**. They can also be used as a design reference for bespoke carrier boards.

Compute Module IO boards do include 'the' because you're referring to the carrier board, not the Compute Module.

|Official name|Shortened version|Naming notes|Key product difference|
|---|---|---|---|
|**Compute Module 5 IO board**|**CM5IO**|Named based on corresponding **Compute Module 5**.||
|**Compute Module 4 IO board**|**CM4IO**|Named based on corresponding **Compute Module 4**.|Designed to fit the new Compute Module form factor.|
|**Compute Module IO board version 3**|**CMIO3**|Named based on corresponding **Compute Module 3**.|Added a microSD card slot.
|**Compute Module IO board version 1**|**CMIO**; **CMIO1**|Named based on the original Compute Module.||

## Capitalisation

In most instances, only capitalise proper nouns and reserve title case for top-level headings and titles. Title case involves capitalising all words in the title *except* for:

- Articles (a, an, the).
- Prepositions of three or fewer letters (in, of, on).
- Co-ordinating conjunctions of three or fewer letters (and, but, or).

With title case, always capitalise the first and last words of the title, regardless of their length or part of speech. Also capitalise small words like 'if', 'how', and 'why'.

Use sentence case for chapter and website headings and subheadings, as well as technical content. Sentence case means capitalising only the first word and any proper nouns or trademarked names. For example:

> Raspberry Pi Radio Module 2: A wireless communication module for Raspberry Pi microcontrollers

In all text, avoid using a trademark whose initial letter is in lowercase (for example, iPad) at the start of a sentence or title. For example: a heading like 'iPad sales soar' is only acceptable if typography means that there is insufficient space for 'Sales of iPad soar'.

## Abbreviations

Spell out abbreviations, acronyms, and initialisms in the first instance in a chapter section, followed by the abbreviation in parentheses. Thereafter use the abbreviation. For example:

> Raspberry Pi's brain is a system on a chip (SoC), made by stacking a memory chip on top of a processor chip. Using an SoC keeps the area of the Raspberry Pi board low.

The full phrase for a common abbreviation, acronym, or initialism isn’t necessarily capitalised when written out in full. For example, 'ASAP' when written out in full isn't 'As Soon As Possible'. Check the [List of abbreviations](#abbreviation-list) or Google the organisation if you're unsure about whether the expanded form should be capitalised.

Abbreviations, acronyms, and initialisms shouldn't be marked in bold, like in the following example: ***S**ystem **o**n a **C**hip*.

For a list of correct capitalisation for abbreviations, acronyms, and initialisms, see [List of abbreviations](#abbreviation-list) in this style guide.

## Numbers

Be consistent in your use of numbers. When you write about numbers used in examples, duplicate them exactly as they appear on the product or in the UI. In all other content, follow the guidelines below.

### Numbers as words

Unless you're dealing with code, units of computer storage, or maths materials and equations, spell out numbers one to twelve; express 13 and higher numbers as a numeral *unless* at the start of a sentence. For example:

> - Eighteen bagpipers were shown to the door.
> - There were 18 bagpipers.

Spell out large round numbers (thousand, million, billion, and so on) when they appear in inline text. For example:

> - There are a thousand reasons to use a Raspberry Pi.
> - A total of 68 million Raspberry Pis have been sold worldwide.

### Numbers as numerals

Use numerals for the following:

|Use|Example|
|---|---|
|Measurements (for more guidance, see [Measurements](#measurements)), below. | 4 KB; 5 cm|
|Dimensions (for more guidance, see [Measurements](#measurements)), below.|5 mm × 9 mm|
|Time of day (for more guidance, see [Time and date](#time-and-date), below).| 10am; 7:30pm |
|Percentages (for more guidance, see [Measurements](#measurements)), below.| 5%|
|Coordinates of tables and numbered sections of documents.| row 3; page 5|
| Binary | binary 1; binary 0 |
|A round number of 1 million or more. Don't hyphenate the numeral, even before a noun. If you're forming a compound adjective, use a hyphen.| 2 billion people; 4-million-year schedule|

### Ranges

For a range of numbers, keep a consistent format. For example:

> - Coding clubs for children aged 9-13
> - Most of the children at the Jam were aged 11-16
> - One to twenty

For school grades (USA), spell out the first through ninth grade, and use figures for 10th grade or higher. Try to keep a consistent format for ranges, as above.

### Commas in numbers

In general, use commas in numbers of more than four digits (for example, 10,000).

Don't use commas in numbers for technical documentation, especially for international audiences (in some languages, a comma is used as a decimal separator); commas can cause confusion, and it's usually better to use thin spaces instead.

For years, pixels, and baud, only use commas when the number has five or more digits, for example:

> - The year 1999
> - The year 20,000
> - 1920 × 1080 pixels
> - 10,240 × 4320 pixels
> - 9600 baud
> - 14,400 baud.

### Measurements

|Guidance|Example|Exception|
|---|---|---|
|Use numerals for measurements of distance, temperature, volume, size, weight, pixels, points, and so on, even if the number is less than 10.| 20 KB; 2 ohm; 8 GB; 5 KiB/s; 1 MiB||
| Use a space between a value and its International System (SI) unit, or hyphenate if the measurement modifies a noun. |13.5 inch; 13.5-inch display|Percent symbol (**%**), for example, **50%**|
| Add a zero before the decimal point for decimal fractions less than one. | 0.75 cm ||
| Use the multiplication symbol (**×**) when required for dimensions, not the letter '**x**'. Use a space before and after the multiplication symbol. | 16 × 16 pixels||
|Use abbreviations with numbers in specific measurements.| 20 KB (rather than twenty KB) | |
|Don't follow abbreviated units with a full stop unless it's the end of a sentence.| 20 KB| Abbreviation for inch (**in.**), for example **5 in.**|
|When no number is present, spell out the unit.| The diagram shows the mechanical measurements in millimetres (mm). ||
|Don't use **k** or **K** to denote 1,000| 5,000 (rather then 5k or 5K)||
|Don't use **k** as an abbreviation for kilobytes| 32 kB (rather then 32 k)||

## Time and date

|Guidance|Example|
|---|---|
| Use the 12-hour clock.|8pm|
| Include the appropriate time zone abbreviation for North American events.|9 am PDT|
| Use a colon to separate hours and minutes. |8:20pm|
| Don't separate the time and 'am' or 'pm' with a space.| 6pm|
| Use 'noon' and 'midnight' to express 12.00 and 00.00, respectively.| noon; midnight |
| Express dates in the following format: **DD Month YYYY**. This avoids confusion with month-day ordering for some readers outside the UK. |21 January, 2006|
| If it's necessary to include the day of the week, express the date in the following format: **Day, DD Month, YYYY**. | Thursday, 14 April, 2022 |
| If necessary to save space, abbreviate months to the first three letters. | Jan |
| Don't capitalise season names. | In the summer, we have a party.|
| If writing something like the following, 'an x-week period', include a hyphen between the number and period of time |In a six-week period|
| When referring to decades, don't abbreviate to 'the '80s'; use 'the eighties' or 'the 1980s' instead. | It was acceptable in the eighties.|
| When referring to two decades, write each decade in full, regardless of how it's typically said out loud.| The 1970s and 1980s (instead of 'the 1970s and '80s')|
|When using the name of a decade to define a social or cultural period, write it as a word. | The sixties were a time of major social change in Britain.|

## Cultural sensitivity
This section provides some guidelines for talking about race, gender, and disability. For a more complete list of problematic words and phrases, including alternative wording, see [Words and phrases to avoid](#words-and-phrases-to-avoid).

|Rule| Use | Don't use|
|---|---|---|
| Use people-first language for race. | Indian people |Indians|
|Use 'they' as a singular pronoun instead of alternating between 'he' and 'she' |When a developer writes code, they should ensure it’s well-documented. When a tester finds a bug, they should report it immediately.|When a developer writes code, he should ensure it’s well-documented. When a tester finds a bug, she should report it immediately.|
Where possible, make nouns and pronouns plural |Students should enter their passwords.| Each student should enter his or her password.|
|Avoid gendered job titles; there is usually an alternative| Firefighter; flight attendant|Fireman; stewardess|
|Be as gender neutral as possible. | Person; humankind; human-created; effort | Man; mankind; man-made; manpower|
| Use 'disabled' as an adjective, never a noun. | Disabled people | The disabled|

Example access statement for Picademy:

> The venue is described as being accessible for people with limited mobility. If you will need to use a car to access the venue, or if you have other access requirements or would like further information, please get in touch via email and let us know how we can help.

For more examples, see [www.accessibilityguides.org/prepare](www.accessibilityguides.org/prepare).

## Screenshots and images

- Don't use dark mode when taking a screenshot of a window, terminal, or any other interfaces that don't provide scalable fonts. Use a white background and black text for readability.
- Take a screenshot of the whole desktop. The design team will crop to fit the relevant templates.
- Ensure that the mouse cursor isn't visible unless it is relevant to the screenshot.
- If taking a screenshot of multiple windows, there should be no overlapping. (If an author requests overlapping windows for a specific reason, please let the design team know; it can be achieved manually, but should be avoided where possible.)
- Provide screenshots as PNG files.
- Don't add annotations to your screenshot or image. Send the annotations separately, to be added in the design process.
- Don't over-rely on annotations in screenshots and images. Whatever is shown in a screenshot or image should be understood written in the main body of the text.
- For the benefit of screen readers, include written copy describing the screenshot or image.

## FAQs

FAQs tend to become a 'dumping ground' of information that fails to take into account the customer experience. They show that you’ve thought about what your users should know, but haven’t thought about the user experience.

FAQs feel like a good idea from our perspective as writers, but they’re poor customer service because they create more work for readers:

* Questions are longer and harder to scan than headings.
* We can’t front load questions with terms that most people are looking for.
* FAQs are provided out of context.
* FAQs create duplication in search results.
* Readers don’t always word questions in the same way we’ve presented them.
* A list of questions is a friction-heavy experience, where the customer has to dig through many questions to find an answer to one question.

FAQs also set the wrong tone because they’re typically sought when the documentation or user journey has failed. Information is more effective for the reader when it’s in context, and pre-emptively answers questions that would otherwise cause people to search in FAQs.

**Restructure your content before adding FAQs.**

Most FAQs aren’t really 'frequently asked' but, rather, indicate that the company hasn’t put in the effort to make documentation easy to follow or to optimise the customer journey (or both).

If a question really is frequently asked, you likely need to add or restructure the content. Often, the perceived need for FAQs actually indicates that readers can’t find what they need where they’d reasonably expect to find it.

**If you do add FAQs:**

* Only include questions that are actually frequently asked.
    * Don’t assume what customers might ask.
    * Don’t include vanity questions.
* Don't use an FAQ section as a substitute for good documentation.
* Don’t use an FAQ section to defend shortcomings.
* Provide detailed, meaningful answers to specific questions based on what readers need to know.
* Spell out 'Frequently asked questions', rather than relying on initialism (FAQ).
* Keep FAQs specific to your product or page.

## Links

* Omit http://www from URLs in print.
* Don’t include punctuation or preceding articles in the link.
* Avoid using the URL as link text unless:
    - The user needs to know the URL rather than follow the link to complete the task.
    - The name of the destination is the same as the URL.
* Use hyperlinks in online content.
* Avoid phrases like 'this page' or 'click here' as hyperlinks. Introduce links properly instead. For examples, see the last bullet point.
* In technical writing, avoid using wiki-style links. Introduce links properly instead. For examples, see the last bullet point.
* Where possible, make links descriptive so that they make sense without the surrounding text. You can do this by:
    - Writing a description of the destination page to use as the link text, capitalised as if it's part of the sentence. For example: 'You can [update your Raspberry Pi software](https://www.raspberrypi.com/documentation/computers/os.html).'
    - **[Preferred]** Front loading a hyperlink with information about what the user can expect if they open it. For example: 'For more information, see [Raspberry Pi OS](https://www.raspberrypi.com/documentation/computers/os.html).'

If using the preferred example style, introduce the link and then hyperlink the actual name of the webpage. Use the original capitalisation of the linked webpage.

## Word list

The word list consists of accepted terms that can cause confusion or that we take a stance on for how the term is used or written.

Bolded terms within the description of another term indicate that the bolded term is listed elsewhere with its own description and usage guidance. For example, part of the guidance for the **Linux** entry is: 'Capitalised, but not in the same way as **UNIX**'. The bolding of **UNIX** indicates that you can find more information about **UNIX** in one of the following locations:

* This [Word list](#word-list), which is structured into alphabetised groups.
* The [Abbreviation list](#abbreviation-list), which includes a list of [Acronyms and initialisms](#acronyms-and-initialisms) (for example, **DoS** and **HTML**) and of [Measurement suffixes](#measurement-suffixes) (for example, **b** and **mm**).
* [Words and phrases to avoid](#words-and-phrases-to-avoid), which includes alternative words to use for insensitive, violent, system-focussed, ambiguous, non-English, colloquial, idiomatic, subjective, marketing and sales, technical, outdated, and unnecessarily complicated terms.

In this particular example, **UNIX** is included as an entry in [Acronyms and initialisms](#acronyms-and-initialisms), a subsection of the [Abbreviation list](#abbreviation-list).

**Note:** 'Capitalise' means 'capitalise the first letter or specified letters'; 'all caps' means 'capitalise all letters'.

### &#35;

|Term|Description|Notes|Don't use|
|---|---|---|---|
|2D, 3D|Two-dimensional; three-dimensional|No hyphen| 2-D; 3-D|
|3G, 4G, 5G | Phone networks |No space|3 G; 4 G; 5 G|
|4K|Screen resolution|Uppercase 'K'; if you add a modifier, don't add a space (e.g., 4Kp60)|4K p60
|50–50|An equal division or a 50% probability|En dash; use numerals|50-50; fifty-fifty|
|7-inch screen|A display screen with a diagonal measurement of 7 inches|Hyphenate|7 inch screen|
|8-bit microprocessor|A microprocessor that processes data in 8-bit chunks|Hyphenate|8 bit micropressor|
|8×, 16× | CD or DVD drive speeds|Use the multiplication symbol, not the letter **x**| 8x, 16x|

### A

|Use| Description |Notes|Don't use|
|---|---|---|---|
|AA batteries|A type of battery|Capitalise 'AA'|double-A-batteries|
|adapter|A device for connecting pieces of equipment that can't be connected directly|Spell with 'er' rather than 'or'|adaptor|
|ad blocker|Extension that prevents adverts from being displayed on websites, videos, or apps|Two words; no hyphen|ad-blocker|
|add-on board|Secondary circuit board that adds functionality to a computer or device|Hyphenate; don't use 'card' to mean 'add-onboard'|add on board; card|
|Advanced Error Reporting| PCI Express (PCIe) feature for reporting and diagnosing errors|Capitalise all words as a defined technical term|advanced error reporting|
|adware|Software that automatically displays or downloads adverts  |One word; lowercase|ad-ware|
|artificial intelligence (see also **AI** in [Acronyms and initialisms](#acronyms-and-initialisms))|What we call AI today are software systems that use **machine-learning models**, such as **LLMs** and **VLMs**, trained on large datasets to recognise patterns and predict likely output; AI isn't self-aware, and doesn't truly think or understand|Two words; lowercase unless shortened to the acronym (AI)|Artificial Intelligence|
|A level; A-level students|Subject-based qualifications in England and Wales|Only capitalise the 'A'; hyphenate when modifying the next word (e.g., A-level students)|A Level|
|Allen key|Hexagonal wrench used to drive bolts or screws with hexagonal sockets|Proper noun (capitalise 'Allen')|allen key|
|all-ones (*adj.*) |Describes a binary value filled with bits set to `1`|Hyphenate when used as a modifier (for example, 'all-ones value')|all ones|
|all-zeros (*adj.*) |Describes a binary value filled with bits set to `0`|Hyphenate when used as a modifier (for example, 'all-zeros value')|all zeros|
|ALSA|Advanced Linux Sound Architecture (software framework for audio on Linux)|Acronym; always all-caps|Alsa; alsa|
|AlsaMixer| Terminal-based mixer utility for ALSA sound system|One word; capital 'A' and 'M'|Alsamixer; alsamixer; ALSAMixer|
|aluminium|A lightweight, corrosion-resistant metal used as a heat conductor|British English spelling|aluminum (American English)|
|amp; ampere (see also **A** in [Measurement suffixes](#measurement-suffixes))|Unit of electric current|Lowercase unless using the abbreviation; abbreviation preferred |3 Amps|
|analogue|Data transmitted in waves rather than digitally|Always British English spelling |analog|
|antennae|Plural of 'antenna' in a biological context||antennas (in a biological context)|
|antennas|Plural of 'antenna' in engineering and tech contexts||antennae (in an engineering or tech context)|
|antivirus|Software designed to detect and remove malware  |One word|anti-virus; antivirus|
|app|Short for application|Don't use if there's potential for confusion||
|Apple| Trademark | Don't add an 's' to make plural; add the device after instead (for example, 'Apple computers')|Apples|
|applications processor | Processor designed specifically for running applications on mobile devices|Lowercase; 'applications' is plural|application processor|
|apt|Advanced Package Tool for managing software in Debian Linux| Lowercase; not an acronym| APT|
|Arm architecture|Family of RISC-based processor architectures developed by Arm Ltd.|Capitalise 'Arm' (proper noun); 'Arm' isn't an acronym| ARM architecture|
|Arm chipset|System-on-Chip (SoC) or integrated circuit based on **Arm** architecture|Capitalise 'Arm' (proper noun); 'Arm' isn't an acronym|ARM chipset|
|Arm Holdings|Company name; rebranded from ARM|Capitalise 'A' and 'H' only| ARM Holdings|
|Armv6, Armv7|Versions of the **Arm** architecture instruction set|Capitalise 'Arm' with lowercase 'v' and numeral; no spaces|ARMv6; Arm V7|
|AS level; AS-level students|The first year of **AS-level** course content in England and Wales|Only capitalise the 'AS'; hyphenate when modifying the next word (e.g., AS-level students)|AS Level|
|assembly language| Low-level programming language closely related to machine code | Lowercase; always 'assembly', not 'assembler'| Assembly Language; assembler language|
|autofocus|Automatic camera lens adjustment to focus on a subject|One word|auto focus; auto-focus|
|avatar|Icon or figure representing a person|Lowercase|Avatar|

### B

|Use|Description |Notes|Don't use|
|---|---|---|---|
|backdoor|Hidden method of bypassing normal security|One word when referring to computer security or hacking|back door; back-door|
|backlight| Lighting from behind a screen | One word| back light; back-light|
|backlit| Lit from behind; typically referring to displays and keyboards | One word| back lit; back-lit|
|barcode|Machine-readable code of lines and spaces|One word|bar code|
|Bash|Stands for 'bourne-again shell'; a Unix shell and command language|Capitalise 'Bash' when referring to the shell|bash|
|BBC BASIC|	A version of BASIC developed by Acorn for the BBC Micro|Use full form to distinguish from other BASIC dialects|BASIC|
|BBC Micro|	An early 1980s British microcomputer made by Acorn for the BBC Computer Literacy Project|Capitalise 'Micro'; always include a space between 'BBC' and 'Micro'|BBC micro; BBCmicro; BBCMicro|
|BBC Model A|A model of the **BBC Micro** with fewer features|Use full form with capital letters|BBC model A; BBC model a|
|BBC Model B|A more popular and feature-rich model of the **BBC Micro**|Use full form with capital letters|BBC model B; BBC model b|
|BCM2XXX (e.g., BCM2835, BCM2837, BCM2711)|SoCs made by Broadcom, used in Raspberry Pi computers|Use full designation on first use; shorten to 2XXX after that||
|BeagleBoard|A low-power, open-source hardware single-board computer|Use the full term without a space and capitalise each 'B'|Beagle Board; beagle board|
|beta|Pre-release version|Don't capitalise unless part of an official product line|Beta|
|big-endian|Byte order in which the most significant byte is stored first|Hyphenate|bigendian; big endian|
|binary| Relating to a system using only '0' and '1'|Use lowercase when referring to binary files and numbers|Binary|
|binary blob| Non-free software distributed in binary form; pejorative term in the free software community |Don't use to describe the GPU in Raspberry Pi||
|bit (see also **b** in [Measurement suffixes](#measurement-suffixes))|The most basic unit of information in computing and digital communication; a portmanteau of 'binary' and 'digit'|Lowercase; hyphenate when used as a compound adjective (for example, 'It's a 16-bit home video game'); don't hyphenate when used as a quantifier (for example, 'These 3 bits control the foo')|3 Bits|
|bitstream| A stream of bits transmitted over a communication channel|One word| bit stream' bit-stream|
|B key| Edge connector standard for M.2 cards that support SATA or up to two PCIe lanes	|Used to differentiate connector types (for example, M key)||
|BlackBerry (devices) | Mobile device brand owned by Research In Motion (RIM)	|Use the full term without a space and capitalise each 'B'; plural is 'BlackBerry devices'| Blackberry; Black Berry; BlackBerrys|
|blog|Online journal or article-style website| Lowercase (generic term) | The Blog|
|Blogger| Google's trademark when referring to the blogging platform | Capitalise when referring to the platform|Google blogger|
|blogroll|List of recommended or linked blogs on a blog site|One word| blog roll; blog-roll|
|Blu-ray| A Blu-ray Disc Association (BDA) trademark | Capitalise the 'B' only; always hyphenate; no 'e' after 'Blu'; use as an adjective only| blu-ray; Blu-Ray; Blu ray; Bluray; Blue-ray|
|Blu Tack (noun); Blu-Tack (verb)| Noun: Adhesive putty by Bostik; verb: to attach using Blu-Tak| Two words; capitalise the 'B' and 'T'; no 'e' after 'Blu'| Blu tack; Blue Tack; BluTack|
|Bluetooth|Wireless technology standard	| One word; capitalised; only use as an adjective| Blue Tooth; Blue tooth; bluetooth|
|Bluetooth Classic |Standard Bluetooth protocol	| Capitalised| Blue Tooth Classic; bluetooth classic|
|Bluetooth Low Energy; Bluetooth LE | Bluetooth Low Energy protocol	| Capitalised| Blue Tooth Low Energy; bluetooth LE|
|boot ROM| A small piece of memory containing the first code executed by the processor on startup | Two words unless referring directly to `bootrom` in the code; capitalise ROM| bootrom|
|breadcrumb | Website navigation | One word | bread crumb|
|Broadcom| Semiconductor manufacturer| Capitalise | broadcom|
|byte (see also **B** in [Measurement suffixes](#measurement-suffixes))|8 **bits**|Lowercase; hyphenate when used as a compound adjective (for example, 'It's a 2-byte register'); don't hyphenate when used as a quantifier (for example, '3 bytes')|3 Bytes|

### C

|Use|Description |Notes|Don't use|
|---|---|---|---|
|C|Programming language|Use uppercase 'C'; don't confuse with '**°C**' for temperature|c (when referring to the language)|
|C++|Programming language|Successor to **C**; use exact spelling with two plus signs|C plus plus; C double plus|
|C#|Programming language developed by Microsoft|Pronounced 'C-sharp' but written with a hashtag symbol|C-Sharp; Csharp|
Camera Module, Camera Module v2 |The official Raspberry Pi camera add-on| Capitalise product names|Camera module|
|Celsius (see also **°C** in [Measurement suffixes](#measurement-suffixes))| Temperature unit| Can always be abbreviated to **°C** | centigrade; degrees Celsius (unless context demands it)|
|Centimetre| Unit of measurement | British English spelling | Centimeter|
|Certified Educator|Graduate of Picademy|Capitalise; always use full term|Picademy Certified, certified educator|
|champion|Raspberry Pi volunteer or organiser|Lowercase|Raspberry Pi Champion|
|checkbox| A box on a form or in the UI for selecting an option|One word; lowercase	| check box|
|client–server (noun phrase)| A network architecture where clients interact with servers|Lowercase; use an en dash|client-server; Client/Server|
|cloud computing| Accessing services or data over the internet |Use for both noun and adjective||
|codebase|Collection of source code for a project	|One word| code base|
|CoderDojo|Network of coding clubs| One word| Coder Dojo; Coderdojo|
|command line|Text-based interface for interacting with the operating system|Two words; no hyphen even when modifying the word 'interface', for example, 'command line interface'; (see also **CLI** in [Acronyms and initialisms](#acronyms-and-initialisms))| commandline|
|Compute Module, Compute Module X, Compute Module X Lite |Raspberry Pi embedded compute boards, where 'X' represents a number, for example, Compute Module 4| Capitalise and preface with 'Raspberry Pi' on first use; only abbreviate after first use if repetition would be cumbersome: CM1, CM3, CM3Lite||
|computer science| Academic discipline|Lowercase|computing science|
|computing| Academic discipline| Always lowercase, even when referring to the school subject |Computing|
|cookie|Small file stored on user’s device for tracking; also a biscuit| Lowercase for both tracking and biscuits| Cookie
|corrupted|A state in which data or files that have become unusable or unreadable| Don't shorten |corrupt (as an adjective)|
|COVID; COVID-19|Stands for coronavirus disease 2019, which is an infectious disease caused by SARS-CoV-2, first identified in 2019 and then became a pandemic in 2020|All caps|Covid; covid; Covid-19|
|crawl|Used by search engines to index the web	|Acceptable as a transitive verb, for example, 'Google crawls pages'|scrape|
|Creative Commons|Licensing framework	|Always capitalised when referring to the brand or license	|creative commons|
|cron|Time-based job scheduler in Unix-like systems	|Lowercase|Cron|
|crontab|cron table; configuration file for `cron` that specifies shell commands to run periodically on a given schedule|One word; lowercase|cron tab|
Cascading Style Sheets (CSS)| A style sheet language| Capitalise; lowercase **style sheets** can be used to refer to CSS documents, for example, 'Cascading Style Sheets (CSS) enable a web designer to use style sheets to lay out a web page.'| cascading style sheets|
|CubeSat |Miniature satellite| Capitalise as one word with camel casing	| cubesat; cube sat|
|curriculum, curricula |Course of study |Latin plural preferred: curricula| curriculums|

### D

|Use|Description |Notes|Don't use|
|---|---|---|---|
|data|Information such as facts and numbers|Treat as a mass noun, for example: 'The data is lost'|datum; 'the data are lost'|
|database|	An organised collection of structured data|One word|data base|
|datasheet|A technical reference document that describes hardware details of a Raspberry Pi product, used by engineers, developers, and advanced hobbyists|One word|data sheet|
|D-Bus|An inter-process communication (message bus) system|Capitalise the 'D' and 'B'; short for 'Desktop Bus'|dbus, Dbus, D Bus|
|Debian|An open-source Linux-based operating system|Capitalise |debian|
|delta-sigma PWM|A pulse-width modulation technique using delta-sigma modulation|Lowercase; hyphenate 'delta-sigma'|Delta-Sigma PWM; delta sigma PWM|
|device tree|A means of representing devices on Raspberry Pi|Lowercase |Device Tree|
|dialog box|A temporary window on a computer screen that prompts users for input, displays information, or confirms actions|American spelling in a computing or technology context only. Otherwise, use British spelling for the word 'dialogue'|dialogue box|
|dioptre|Unit of measurement|British spelling|diopter|
|disc| Optical media and storage, for example, compact disc (CD)|||
|disk| Magnetic media and storage, for example, floppy disk|||
|disk space| Available space on a magnetic storage device|Two words; unhyphenated| disk-space; diskspace|
|Document Object Model (see also **DOM** in [Acronyms and initialism](#acronyms-and-initialisms))| Programming interface for HTML and XML documents| Capitalise each word; use acronym where appropriate|document object model|
|dos and don'ts| Accepted and discouraged practices| No apostrophe before either 's'|do's and don'ts; do's and don't's|
|double-click|Pressing a mouse button twice in quick succession to select something|Hyphenate|double click|
|dreamt; dreamed|Past tense of 'dream'|Both versions are correct in British English, though 'dreamt' is encouraged in Raspberry Pi content||
|drag-and-drop (*adj.*)| Describing a feature or capability|Hyphenate| 'It has drag and drop functionality'|
|drag and drop (*verb*) |To select, hold, move, and release an item on screen | Don't hyphenate | 'Drag-and-drop the file onto your desktop'|
|dropdown menu|A menu that expands into a list when selected|'dropdown' is one word; consider shortening to 'menu'|pull down menu; pull-down menu; pulldown menu|

### E

|Use|Description |Notes|Don't use|
|---|---|---|---|
|e-book |	A digital version of a printed book| Hyphenate| ebook|
|e-commerce| Commercial transactions conducted electronically	|Hyphenate|ecommerce|
|E-Mark; E-Marked|Electronically Marked; protocol controller for USB cables|Capitalise the 'E' and 'M'; hyphenate|e-mark; eMarked|
|e-paper|Electronic paper display technology| Hyphenate	|epaper|
|earth|Soil|Lowercase when referring to soil|Buried in Earth|
|Earth|Our planet|Capitalise when referring to the planet|Planet earth|
|eBay|An online marketplace| No hyphen; capitalise 'B' |e-Bay; ebay|
|Ed and Izzy| The two Astro Pi units sent to the ISS with Tim Peake|Capitalise both names; always refer to them together unless context dictates otherwise| Ed & Izzy; ed and izzy|
|egde AI|The deployment of AI models directly on local devices|Two words (no hyphen); 'AI' in all caps|edge-AI; Edge AI|
|email|Electronic mail| No hyphen |e-mail|
|emoji, emojis|Pictographic characters used in digital communication|Plural is emojis (no 'e' before the 's')|emojies|
|Emotiv| Company producing EEG headsets for neuro-signal work|Capitalise; no 'e' at the end| emotiv; Emotive
|endianness| Byte order within digital word data| Lowercase; technical term|Endianness|
| ePub | Electronic publication; an open-standard file format for e-books | Capitalise the 'P'; no hyphen| epub; e-Pub |
|Ethernet | Networking technology	| Capitalise | ethernet|

### F
| Use | Description| Notes| Don’t use|
|---|---|---|---|
|Fahrenheit (see also **°F** in [Measurement suffixes](#measurement-suffixes))| Temperature unit| Can always be abbreviated to **°F**| fahrenheit; degrees Fahrenheit (unless context demands it)|
| fan page| A web page dedicated to a person, show, group, brand, or topic| Two words| fanpage|
| fan site | A website created by fans | Two words| fansite |
| fanbase| Group of dedicated followers| One word| fan base|
|fax | facsimile  |No need to spell out in full|facsimile|
|fediverse| Network of federated servers that inter-communicate | Lowercase; technical term |Fediverse |
|feed reader| Software for reading syndicated web feeds| Two words| feedreader|
|fetch-decode-execute cycle| Fundamental CPU instruction cycle | Hyphenate all three components | fetch decode execute cycle|
| FFmpeg| Open-source software project | Capitalised exactly as **FFmpeg** (lowercase 'mpeg')| FFMPEG, ffmpeg|
| file name| Name of a file| Two words| filename|
| file system| Method of storing and organising files| Two words | filesystem |
| firewall| Network security system| One word| fire wall|
| FireWire | Trademarked high-speed interface| Capitalise| firewire|
| Flash (Adobe)| Deprecated multimedia platform | Capitalise when referring to **Adobe Flash**  |flash |
| flash memory | Non-volatile storage technology | Lowercase | Flash memory |
| Flat Flexible Cable | Type of ribbon cable | Capitalise all words; **FFC** acceptable | flat flexible cable|
| flatsat| Ground-based CubeSat test hardware | One word; Lowercase | FlatSat, flat sat|
| focussed | Past tense of 'focus' | Preferred spelling, but 'focused' with one 's' is also technically correct in British English|  |
| forgo| To do without| Correct spelling| forego |                  |
| frame rate | Frequency at which frames appear | Two words| framerate |
| friend (verb)| Add someone as a friend on Facebook; see also **unfriend**| Lowercase | Friend|
| full-screen | Display mode occupying entire screen | Hyphenate| fullscreen, full screen |
| function keys | Keys such as F1–F12 on a keyboard | Lowercase | Function keys|

### G

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|games console| Electronic device used for playing video games| British English adds an 's' to 'game'| game console (American English)|
|gibibit (see also **Gib** in [Measurement suffixes](#measurement-suffixes))| 2<sup>30</sup> b = 1073741824 b; unit of binary bits | Lowercase; abbreviation preferred if using as a suffix |9 Gibibit|
|gigabit (see also **Gb** in [Measurement suffixes](#measurement-suffixes))| 10<sup>9</sup> b = 1000000000 b; unit of decimal bits | Lowercase; abbreviation preferred if using as a suffix |9 Gigabit|
|gibibyte (see also **GiB** in [Measurement suffixes](#measurement-suffixes))| 2<sup>30</sup> B = 1073741824 B; unit of binary bytes| Lowercase; abbreviation preferred if using as a suffix; preferred unit of measure for a technical audience; for a general audience, use **GB** (when correct) |9 Gibibyte|
|gigabyte (see also **GB** in [Measurement suffixes](#measurement-suffixes))| 10<sup>9</sup> B = 1000000000 B; unit of decimal bytes| Lowercase; abbreviation preferred if using as a suffix; preferred unit of measure for a general audience; for a technical audience, use **GiB** (when correct) |9 Gigabyte|
|GitHub|Developer platform | One word; capital 'G' and 'H'|Github, github|
|Generation X; Gen X| Demographic cohort born approximately between 1965 and 1980| Capitalise | Generation x; Generation Xer|
|Generation Y (see also **Millenial**)| Demographic cohort born approximately between 1981 and 1996; **Millenial** is preferred and more widely recognised| Capitalise | Generation y; gen y; Gen y|
|Generation Z; Gen Z (see also **Zoomers**)| Demographic cohort born approximately between 1997 and 2012; **Gen Z** is more common; **Zoomers** is also acceptable| Capitalise | gen z; Generation z|
|geolocation| Geographic location of an object| One word; no hyphen; lowercase | Geolocation; geo-location|
|geotagging|The process of adding geographical identification metadata to media or data| One word; no hyphen; lowercase | Geotagging | geo-tagging|
|gigahertz (see also **GHz** in [Measurement suffixes](#measurement-suffixes))|10<sup>9</sup> Hz = 1,000,000,000 Hz; unit of frequency| Lowercase; abbreviation preferred if using as a suffix| 9 Gigahertz|
|GNU Linux (see **GNU** in [Measurement suffixes](#measurement-suffixes))| Operating system combining GNU software and the Linux kernel| Often shortened to Linux| |
|GPIO Zero; gpiozero |The name of a project (**GPIO Zero**)| **gpiozero** is an acceptable alternative when referring to the module|GPIO 0|
|Gigatransfers | Data transfer unit used in PCIe specifications; rates measured in **GT/s**, though **MB/s** is often preferred by users	|Capitalise|gigatransfer|
|gram|Unit of weight (see also **g** in [Measurement suffixes](#measurement-suffixes))| Lowercase; abbreviation preferred if using as a suffix |9 Grams|
|grey|Colour|British English unless writing specifically for an American audience|gray|
|GStreamer|A pipeline-based multimedia framework|Capitalise 'G' and 'S'||
|guizero|A Python 3 library for creating simple GUIs|Lowercase|GUIzero|

### H

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|Hackspace (see also **maker space**)|A community-run workspace where people with shared interests collaborate and build projects| Often used interchangeably with **maker space**, but preferred for branding (for example, HackSpace magazine); use the organisation’s chosen term if referring to a specific location	||
|HackSpace magazine| Publication produced by Raspberry Pi Press | Capitalise 'H' and 'S'; you can drop 'magazine' if appropriate| Hackspace magazine|
|Hall effect sensor| A sensor that detects magnetic fields based on the Hall effect | Capitalise 'Hall'| hall effect sensor|
|HAT+ (see also **Power HAT+**)| HAT specificiation, beginning Dec 2023| All caps| Hat plus; Hat+|
|heatsink|A passive cooling component designed to absorb heat from electronic or mechanical components|One word; lowercase|heat sink|
|HMDI®| Proprietary technology used to transmit high-quality audio and video signals between devices | All caps; use the ® symbol on first mention|hdmi|
|help desk| Support service or department| Two words|helpdesk|
|hi-fi|High-fidelity audio system|Hyphenated|Hi-Fi; hifi|
|homepage|Main page of a website|One word; lowercase|home page|
|hot swap| The ability to add or remove hardware without shutting down the system|Don't use in technical documentation||
|hotspot (for Wi-Fi)|A Wi-Fi access point|One word for wireless access; use hot spot for non-tech contexts (such as restaurants)|hot spot (for Wi-Fi)|

### I

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|identification (see also **ID** in [Acronyms and initialisms](#acronyms-and-initialisms))|A document, card, or code that proves a person's identity|Avoid using **ID** as a verb unless space is restricted (for example, don't use phrases like 'The bouncer ID’s drinkers'; use 'The bouncer checks drinkers' identification' instead); use apostrophe in verb form | ID (as a verb)|
|internet|Global network connecting computers|Don't capitalise|Internet|
|I-frame| Intra frame | Video term (don't confuse with **iframe**)|iframe|
|iframe| Inline frame tag in HTML|One word; lowercase|i-frame; iFrame|
|inch|Unit of length (see also **in.** in [Measurement suffixes](#measurement-suffixes))| Lowercase; abbreviation preferred if using as a suffix |9 Inches|
|index; indices|A data structure or listing of references|Plural is 'indices'|indexes|
|information and communications technology (see also **ICT** in [Acronyms and initialisms](#acronyms-and-initialisms)) |Field covering computing, telecommunications, and related technologies|Always include 's' in 'communications'|information and communication technology|
|infrared (see also **IR** in [Acronyms and initialisms](#acronyms-and-initialisms))|Electromagnetic radiation just beyond visible red light|One word; lowercase|infra-red|
|inkjet| Type of printer that sprays ink onto paper	|One word; lowercase|ink jet; ink-jet|
|install|To set up software or hardware	|Use install *on* a computer; install *to* a hard drive|
|Internet of Things (see also **IoT** in [Acronyms and initialisms](#acronyms-and-initialisms))|Network of interconnected devices with sensors or software|Capitalise as shown|Internet of things|
|iPad |Apple trademark| Don't add an 's' to make plural| iPads|
|iPhone |Apple trademark| Don't add an 's' to make plural| iPhones|
|iPod |Apple trademark| Don't add an 's' to make plural| iPods|

### J

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|Java|Programming language used for building applications|Capitalise|java|
|JavaScript|Programming language primarily used for web development	|One word with camel case; capitalise 'J' and 'S'|Javascript; java script|

### K

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|kibibit (see also **Kib** in [Measurement suffixes](#measurement-suffixes))| 2<sup>10</sup> b = 1024 b; unit of binary data| Lowercase; abbreviation preferred if using as a suffix ||
|kibibyte (see also **KiB** in [Measurement suffixes](#measurement-suffixes))| 2<sup>10</sup> B = 1024 B; unit of binary data | Lowercase; abbreviation preferred if using as a suffix ||
|kilobit (see also **kb** in [Measurement suffixes](#measurement-suffixes))| 10<sup>3</sup> b = 1000 b; unit of digital data| Lowercase; abbreviation preferred if using as a suffix ||
|kilobyte (see also **kB** in [Measurement suffixes](#measurement-suffixes))| 10<sup>3</sup> B = 1000 B; unit of digital data | Lowercase; rarely used (consider using **KiB** instead); abbreviation preferred if using as a suffix ||
|kilogram (see also **kg** in [Measurement suffixes](#measurement-suffixes))|Unit of weight|Lowercase|KG|
|kilohertz (see also **kHz** in [Measurement suffixes](#measurement-suffixes))|Unit of frequency|Lowercase|KHZ; khz|
|kilometre (see also **km** in [Measurement suffixes](#measurement-suffixes))|Unit of length|Lowercase|KM|
|keylogger|Software that records keystrokes	|One word| key logger|
|key press|The action of pressing a key on a keyboard| Two words| keypress|
|keyword|Search engine term|One word ('Use the right keywords in your web page.')||
|key word|A reference to a specific word|Two words  ('The key word was "almost".')||

### L

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|language model|A type of **machine-learning model** trained on large collections of text to recognise patterns in language and predict the most likely next word or sequence of words.|Lowercase|Language Model|
|large language model (see also **LLM** in [Acronyms and initialisms](#acronyms-and-initialisms))|A **language model** trained on very large datasets to generate, summarise, and translate text with flexibility.|Two words; lowercase unless shortened to the acronym (LLM)|Large Language Model|
|learnt; learned|Past tense of 'learn'|Both versions are correct in British English, though 'learnt' is encouraged in Raspberry Pi content||
|legacy|Describes a product that is no longer actively promoted or sold (for example, 'legacy API')|Lowercase; not a title| Legacy API; Legacy stack|
|LEGO; Lego| A company (The LEGO Group) and the bricks that this company makes| Always capitalise at least the first letter; the plural of Lego is 'Lego' or 'Lego bricks'|Legos|
|litre (see also **l** in [Measurement suffixes](#measurement-suffixes))| Unit of volume| Lowercase|9 Litres|
|libcamera| Software library| One word; lowercase; don't use at the start of a sentence|Libcamera; lib camera|
|Li-ion| A type of battery: **lithium-ion**|Capitalise unless writing out in full rather than using this shortened form; hyphenate|li-ion|
|licence (*noun*)| Noun: an official document that grants permission | Don't confuse the British English spellings between the noun and the verb||
|license (*verb*)|Verb: to give official permission or formal authorisation | Don't confuse the British English spellings between the noun and the verb||
|like (*verb*)| React with a thumb's up icon| Lowercase; use with quotation marks (unless the word is hyperlinked), for example: 'Thousands of people "like" Raspberry Pi on Facebook' | Like|
|LiPo| Lithium polymer; a kind of battery | One word; capitalise the 'L' and 'P'|Lipo; Li Po; Li-Po|
|lithium-ion (see also **Li-ion**) |A type of battery|Lowercase|Lithium-ion|
|Linux | A trademarked family of open-source operating systems, based on the Linux kernel | Capitalised, but not in the same way as **UNIX**|LINUX|
|little-endian |A **data** format|Hyphenate|little endian|
|logic 0; logic 1| Describes **binary** digital logic states|Write the number as a digit|logic zero; logic one|
|login|Adjective: use as a modifying noun (for example, 'login details' or 'login page')|One word; don't use as a verb (use **sign in** instead, which is less technical and also helps to delineate a login page from the process of signing in)|log in|
|low speed serial interface (see also **LoSSI** in [Acronyms and initialisms](#acronyms-and-initialisms))|A low-bandwidth serial interface used in computing|Capitalise as shown; use acronym after first mention|LOSSI|

### M

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|M key| Edge connector standard for M.s PCIe peripherals; used to differentiate connector types (for example, B key)|Capitalise 'M' only |M Key|
|M.2|Specification for internally mounted computer expansion cards and connectors|Capitalise; always include a full stop between 'M' and '2'|M2, m.2|
|Mac|Macintosh; an **Apple** line of personal computers|Capitalise when referring to the computer  |mac; MAC|
|Mac address|Media Access Control address; hardware identifier for a network interface|Lowercase 'address'; not related to Apple **Mac**|MAC address; Mac Address|
|MacBook; MacBook Air; MacBook Pro | **Apple** trademarks| Don't add an 's to pluralise|Macbooks|
|machine learning|A subset of **artificial intelligence** focussed on algorithms that learn patterns from data through training rather than through explicit programming; it doesn't involve understanding or awareness.|Lowercase|Machine Learning|
|machine-learning model|A mathematical or statistical model created through machine-learning algorithms; it doesn't possess understanding, intent, or awareness.|Lowercase|Machine-Learning Model|
|macOS|Operating system for Apple **Mac** computers|One word; lowercase 'mac'|MacOS; Mac OS; Mac OS X; OS X; OSX|
|The MagPi| The old name for **Raspberry Pi Official Magazine**|'MagPi' is one word; capitalise 'M' and 'P'; use only when referring to historical branding|The Mag Pi; The Magpi|
|mailbox|A digital message storage location (email context) or hardware mailbox (in electronics)|One word; lowercase|Mailbox; mail box|
|maker movement|Grassroots movement focussed on DIY tech, crafting, and engineering|Lowercase|Maker Movement|
|maker space| Community-oriented creative or tech space| Use varies: makespace, maker lab, hackspace, maker shed. **Hackspace** often preferred for branding. Use org-specific naming if referring to a real one.||
|malware|Malicious software designed to harm or exploit systems	|Lowercase|Malware|
|mass storage device|Any device used to store large amounts of data|Lowercase|Mass Storage Device|
|Master Boot Record|Legacy system partitioning scheme|Capitalise all three words|master boot record; MBR (unless context demands it)|
|maths|Mathematics|British English spelling|math|
|mebibit (see also **Mib** in [Measurement suffixes](#measurement-suffixes)) | 2<sup>20</sup> b = 1048576 b; unit of digital information used to express **binary** data sizes | Lowercase; use in contexts where **binary** precision is important (such as networking and memory)| Mebibit|
|mebibyte (see also **MiB** in [Measurement suffixes](#measurement-suffixes)) |  2<sup>20</sup> B = 1,048,576 bytes; unit of digital information used to express **binary** data sizes | Lowercase; use when **binary** precision matters (for example, memory)| Mebibyte|
|media|Collective term for communication outlets such as TV, newspapers, and online platforms|Treat as a mass noun with singular verb (for example, 'The media is'). Use plural verb if referring to distinct mediums (for example, 'Various media are')||
|megabit (see also **Mb** in [Measurement suffixes](#measurement-suffixes))|Unit of data equal to 1 million bits|Lowercase |Megabit|
|megabyte (see also **MB** in [Measurement suffixes](#measurement-suffixes))|Unit of digital information equal to 1,000,000 bytes (decimal) or 1,048,576 bytes (**binary**, depending on context)|Lowercase |Megabyte|
|megahertz (see also **MHz** in [Measurement suffixes](#measurement-suffixes))|Unit of frequency equal to one million hertz|Lowercase |Megahertz|
|megapixel (see also **MP** in [Measurement suffixes](#measurement-suffixes))|Unit of image resolution equal to one million pixels	|Lowercase |Megapixel|
|membership of|Belonging to a group, club, or organisation|Use 'membership of' rather than 'membership in' in British English	|membership in|
|metadata|Data about data| One word; lowercase| meta data; Meta Data|
|metre (see also **m** in [Measurement suffixes](#measurement-suffixes))|Unit of length|Lowercase; British spelling |Metre; meter|
|metatag|Tags embedded in web pages to describe content	|One word; lowercase|meta tag; Meta Tag|
|mic|Short for microphone||mike|
|microchip|A tiny piece of material that contains electronic circuits|One word; lowercase| micro chip|
|micro HDMI| A smaller HDMI connector type|No hyphen unless modifying a proceeding word; lowercase 'micro'|Micro HDMI; micro-HDMI|
|micro USB| A smaller USB connector type|Two words; no hyphen; lowercase 'micro'|Micro USB; micronUSB|
|micro:bit|Pocket-sized microcontroller board for education	|Lowercase with colon; avoid starting a sentence with 'micro:bit'; add 'BBC' to the beginning if you have to use it at the beginning of a sentence|Microbit; microbit|
|Micro:bit Educational Foundation|The company behind the **micro:bit**| Capitalise all three words; use full name when referring to the organisation| micro:bit Educational Foundation|
|microarchitecture; microarchitectural|The internal design of a processor|Use instead of 'architecture' when referring to hardware design||
|microcontroller|Integrated circuit that includes a processor, memory, and **I/O**|One word; lowercase|Microcontroller; MicroController; Micro Controller; micro controller|
|microprocessor|Central processing unit on a single chip|One word; lowercase|Microprocessor; MicroProcessor; Micro Processor; micro processor|
MicroPython|Python implementation for microcontrollers|One word; capital 'M' and 'P'|micropython; Micro Python|
|microSD|A small **SD card** (SanDisk trademark); a proprietary, non-volatile, **flash** memory card format|One word; lowercase 'micro'|micro SD; MircoSD|
|microsite|A small or focussed website, often part of a campaign	|One word; lowercase|micro site; Micro Site|
|Microsoft .Net	|Microsoft’s branding for its developer platform|Use 'Microsoft .Net' in full on first mention|
|Microsoft Windows (see also **Windows**)|Operating system by Microsoft|Use full name on first mention if branding clarity is needed; otherwise use **Windows**|Windows OS (unless unavoidable)|
|minute|Unit of time|Preferred to the abbreviation (**min.**), even as a suffix||
|milligram (see also **mg** in [Measurement suffixes](#measurement-suffixes))| Unit of mass | Lowercase; abbreviation preferred if using as a suffix ||
|millilitre (see also **ml** in [Measurement suffixes](#measurement-suffixes))| Unit of volume | Lowercase; abbreviation preferred if using as a suffix ||
|millimetre (see also **mm** in [Measurement suffixes](#measurement-suffixes))| Unit of length | Lowercase; abbreviation preferred if using as a suffix ||
|miniSD|Flash memory card format, smaller than standard SD but larger than microSD	|One word; lowercase 'mini'| mini SD; MiniSD|
|mini HDMI|A smaller version of the standard HDMI connector|Two words; lowercase 'mini'|Mini HDMI; mini-HDMI|
|mini USB|A smaller USB connector used on older devices	|Two words; don't hyphenate; lowercase 'mini'|Mini USB; mini USB|
|mobile|Short for mobile phone|Use sparingly as a noun|cellphone|
|(the) Moon|The large round object that circles the Earth| Capitalise when referring to the Earth's Moon|the moon|
|moon|Any moon other than the Earth's Moon|Don't capitalise unless referring to the Earth's Moon|'Jupiter has 95 recognised Moons'|
|mouse; mice|Input device|Plural is 'mice', even for computer peripherals|mouses|
|MPEG-2 transport stream|A container format defined in the **MPEG-2** standard|All caps|Mpeg-2|
|multi-touch|A touchscreen or trackpad that can recognise two or more points of contact simultaneously|Hyphenate because 'multi-touch' is the logical opposite of 'single-touch' and easier to read, with the repeated 't' in close proximity|multitouch|
|multi-word|An expression composed of two or more words that function together as a single concept, often as a compound modifier|Hyphenate because it's not yet recognised as a single word|multiword|
|multimeter|Device for measuring electrical values|Spelled 'er' at the end, even in British English|multimetre|

### N

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|nano|Linux text editor|Lowercase; full name is 'GNU nano'|Nano|
|NeoPixels|Adafruit trademark|One word; capitalise 'N' and 'P'|Neopixels; neopixels; Neo Pixels|
|news feed|A continuously updated stream of content on a website, app, or social media platform|Two words| newsfeed|
|newsreader|Job title and **RSS (news) feed**|One word| news reader|
|nickel-metal hydride (see also **Ni-MH** in [Acronyms and initialisms](#acronyms-and-initialisms))| A type of battery|Lowercase; hyphen between 'nickel' and 'metal'|nickel metal hydride|
|Node-RED|A visual tool for wiring the **Internet of Things**|Hyphenate; Capitalise 'N'; 'RED' in all caps|Node RED|
|Node.js|A runtime environment that allows you to run JavaScript code outside of a web browser|Capitalise and include a full stop as shown|node.js; NodeJS|
|no one| Nobody |Two words; don't hyphenate|no-one|
|NOOBS|Deprecated Raspberry Pi software that stands for 'New Out Of Box Software', used to install an OS on a Raspberry Pi|All caps|Noobs; noobs|
|Non-secure|The TrustZone security domain of the same name|Capitalise only in this context|non-secure (in the context of TrustZone)|

### O

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|object-oriented programming (see also **OOP** in [Acronyms and initialisms](#acronyms-and-initialisms))|A programming paradigm based on the concept of 'objects'|Hyphenate|object oriented programming|
|offline|Not connected to the internet or a network	|One word|off-line|
|offshoot|Something that branches off from a main system or idea|One word|off-shoot|
|ohm (see also **Ω** in [Measurement suffixes](#measurement-suffixes))|Unit of electrical resistance|Lowercase despite being a proper name; use **Ω** for values, not **R**|Ohm; 4 ohm; 4R|
|on-board (*adj.*); on board (*adverb*)|Describes components on a circuit board|'There is an on-board wireless antenna'; 'There is a wireless antenna on board'|onboard (in the context of computers)|
|onboard (*adj.*); on board (*adverb*)| Refers to vessels or vehicles|'There are two Raspberry Pi computers on board the International Space Station'; 'Input from sensors in the hull is sent to the ship's onboard computer'|on-board (in the context of vessels or vehicles)|
|online|Connected to or available through the internet|One word|on-line; on line|
|off-screen|Not visible on the display or outside the visible display area|Always hyphenated|off screen; offscreen|
|on-screen|Visible on the display or occurring within the display area|Always hyphenated|on screen; onscreen|
|OpenOCD| Open On-Chip Debugger	|One word; capitalise as shown|Open OCD; openOCD|
|open source|Software with freely available source code	|Lowercase; no hyphen whether used as a noun or adjective|open-source|
|overclocking (*noun*); overclock (*verb*)|Increasing a component’s clock rate beyond specifications|Never use clock as a verb unless context is clear (for example, dynamic frequency clocking)|Clock (as a verb for this context(|
|overcurrent|Excess current	|One word|over current; over-current|
|overvoltage|Excess voltage	|One word|over voltage; over-voltage|
|overwrite |Replace existing data	|One word|over write; over-write|

### P

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|page view|An instance of a page being loaded or viewed|Two words|pageview|
|passcode|A numeric code for authentication|One word|pass code|
|passphrase|A sequence of words used for authentication|One word|pass phrase|
|password|A string used for authentication|One word|pass word|
|password-protect|To secure something using a password|Hyphenated verb|password protect|
| PCIe 3.0 x 1 (see also **PCIe** in [Abbreviation list](#abbreviation-list))|A PCI Express specification| Use the letter 'x', not multiplication symbol|PCIe 3.0 × 1|
|peer-to-peer (see also **P2P** in [Abbreviation list](#abbreviation-list))| Direct interaction between nodes or devices | Hyphenated adjective	|peer to peer|
|percent| Unit expressing proportion per hundred|One word|per cent|
|Peripheral Address Map| Structured table of memory addresses for peripherals|Capitalise all three words|peripheral address map|
|Perl|A programming language|Capitalise|perl; pearl|
|pharming|Redirecting traffic from a legitimate-looking site to a spoofed site|Lowercase|Pharming|
|Phillips screwdrivers, Phillips screw|A specific type of cross-head tool or screw|Proper noun, not a trademark; capital 'P'; unrelated to Philips the company (one 'l')|Philips screwdriver; phillips screwdriver|
|phishing|Tricking someone into giving out sensitive information using an email or text message that looks legitimate|Lowercase|Phishing; fishing|
|photobooth|A compact installation or app for taking photos|One word| photo booth|
|Photoshop|Adobe trademark| Use as an adjective or proper noun, never a verb|photoshop (as a verb); photoshopped|
|picamera, picamera2|Software libraries that provide a pure Python interface to Raspberry Pi cameras; includes the `PiCamera` class|One word; lowercase|PiCamera (when referring to the library name)|
|Pi-hole|A network-level ad blocker for Raspberry Pi|Hyphenate; capitalise 'P'|pi-hole; Pihole|
|PiServer|Software for centrally controlling many Raspberry Pis (for example, in a classroom)|Capitalise 'P' and 'S'; no space|Pi-server|
|Pi In The Sky (PITS) board |A high-altitude ballooning telemetry board| Capitalise each word| Pi in the sky; Pi in the Sky; pits board|
|Picademy|Training courses for teachers|One word; capitalise; if possible, pluralise by adding 'sessions', 'courses', or similar|Pi-cademy; picademy|
|PipeWire| A multimedia framework for Linux|One word; capitalise 'P' and 'W'|Pipe Wire; pipewire|
|playlist| A list of media items (such as songs or videos) grouped for playback| One word; lowercase|play list|
|podcast|A digital audio program available for download or streaming|One word| pod cast|
|polyfuse|Resettable fuse for electronics|One word; lowercase|poly fuse|
|Post-it| 3M trademark|Hyphenate and capitalise; don't use as a noun; add 'notes' to make it plural (Post-it notes)|post-its|
|Power HAT+|Expansion board for Raspberry Pi providing additional power options|Capitalise 'P' and 'HAT'|power HAT; Power hat|
|pre-soldered|An electronic component or part that already has solder applied to its pins or pads during manufacturing|An exception to the hyphenation rule for the 'pre' prefix. For more information, see [Prefixes and suffixes](#prefixes-and-suffixes) |presoldered|
|printout (*noun*)|Physical copy of printed material|One word; lowercase|print out|
|print off (*verb*)|Action of printing a document|Two words; lowercase|
|pro forma (income) statement|Financial statement showing projected results|Two words|pro-forma; proforma|
|program (computer; computing)|A computer application or software| American spelling only in the context of computing|computer programme (in a computing context)|
|programme|British spelling of 'program' outside of computing|British English; see **program** above for the exception in computing|'television program'|
|pseudocode|Informal description of an algorithm|One word; lowercase|pseudo-code|
|pull-up resistor|Resistor used in electronic logic circuits| Hyphenate; can be shortened to PU resistor during repeated heavy usage|pullup resistor; pull up resistor|
|pull-down resistor|Resistor used in electronic logic circuits| Hyphenate; can be shortened to PD resistor during repeated heavy usage|pulldown resistor; pull down resistor|
|PuTTY| Popular SSH/Telnet software used to access Raspberry Pi|Capitalise as shown (lowercase 'u')|putty; Putty
|Pygame|Python library for game development|Capitalise|pygame|
|Pygame Zero|Python library for beginner-friendly game development|Capitalise each word|pygame zero|
|Python (language)|Programming language used on Raspberry Pi|Capitalise| python|

### Q

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|QR code (see also [Acronyms and initialisms](#acronyms-and-initialisms))|A machine-readable code consisting of an array of black and white squares, typically used for storing URLs or other information for reading by the camera on a **smartphone**|Don't hyphenate; capitalise 'QR'|QR-code|
|quad core (*noun*); quad-cor (*adj.*)|A processor with four independent cores that can run tasks simultaneously|Hyphenated when modifying a noun, for example, quad-core processor||
|QuickTime|Apple trademark |One word; capitalise 'Q' and 'T'|Quicktime; Quick Time|
|Qt|A cross-platform application development framework used to create applications|Capitalise as shown (lowercase 't')|qt; QT|
|QtGL (Qt OpenGL module)|An extension of **Qt** that allows integration of OpenGL graphics into Qt applications|One word; capitalise as shown (lowercase 't')|QTGL|

### R

| Use | Description| Notes| Don’t use|
|---|---|---|---|
|Raspberry Pi|A small **single-board computer** developed by the **Raspberry Pi Foundation**.|Don't abbreviate; plural is 'Raspberry Pis', but adding another word to make it plural is preferred, for example 'Raspberry Pi devices'|Raspberry; Pi; Raspberry Pi's|
|Raspberry Pi 2; Raspberry Pi 3B+ (and so on)|Specific models of Raspberry Pi computers, differentiated by generation and features|Always include 'Raspberry' before 'Pi'; don't abbreviate to just 'Pi'|Pi 5|
|Raspberry Pi icon|Official graphical representation of a Raspberry Pi device|Don't drop 'Raspberry' or 'Pi'; lowercase 'icon'|Raspberry Pi Icon; Pi icon; Raspberry icon;|
|Raspberry Pi menu|The software menu in the Raspberry Pi OS interface|Don't drop 'Raspberry' or 'Pi'; lowercase 'menu'|Raspberry Pi Menu; Pi menu; Raspberry menu;|
|(the) Raspberry Pi Foundation|The Raspberry Pi charity that develops **Raspberry Pi** computers and educational resources|Requires a definite article: The Raspberry Pi Foundation|Raspberry Pi Foundation|
|Raspberry Pi OS|The official operating system for Raspberry Pi computers, formerly known as **Raspbian**|Capitalise; doesn't take a definite article, for example, 'Raspberry Pi OS is our official recommended operating system'; capitalise|The Raspberry Pi OS|
|Raspberry Pi OS Lite|A minimal version of **Raspberry Pi OS** without a desktop environment|Capitalise|Raspberry Pi lite|
|Raspberry Pi Weekly|A weekly email newsletter|Capitalise|Raspberry Pi weekly|
|Raspberry Pi Zero|A smaller, lower-cost version of Raspberry Pi|Capitalise; spell out 'Zero'|Raspberry Pi zero; Raspberry Pi 0|
|Raspberry Pi Zero W|A **Raspberry Pi Zero** with built-in Wi-Fi and Bluetooth|Don't use 'wireless' instead of 'W'|Raspberry Pi Zero Wireless|
|Raspbian|The former name of **Raspberry Pi OS**, a Debian-based operating system for Raspberry Pi computers|||
|Raspbian Lite|A minimal version of **Raspbian** (now **Raspberry Pi OS Lite**) without a desktop environment.|||
|Resource Repository|A collection of teaching materials, software, and documentation provided by the NCCE for Raspberry Pi projects|Capitalised when referring to the NCCE Resource Repository|resource repository|
|RetroPie|Software platform for emulating classic video game consoles on Raspberry Pi and other devices|Two words; capital 'R' and 'P'|Retropie; RetroPiE|
|right-click|An action performed by pressing the secondary button on a mouse or touchpad|Hyphenate|right click|
|ringtone|A sound played by a mobile phone to indicate an incoming call|One word| ring tone|
|Roku|Company name and the name of a streaming media device (trademark)|Don't add an 's' to make plural (add 'boxes' or 'devices' instead)|Rokus|
|RP1|The companion chip used in Raspberry Pi 5 to provide system-level I/O control.|All caps; not an acronym; not to be confused with the first Raspberry Pi|Raspberry Pi 1|
|RP2040|The full name of a microcontroller|Don't add Raspberry Pi| Raspberry Pi RP2040|
|RP2350|The full name of a microcontroller|Don't add Raspberry Pi| Raspberry Pi RP2350|
|RS Components|A global distributor of electronic, electrical, and industrial components|Name of the company (capitalise 'RS' and 'C'); use full name in the first instance in a chapter section; then just RS|RS components|
|RSS (news) feed; RSS newsreader (See also **RSS** in [Abbreviation list](#abbreviation-list))|A standardised system for the distribution of content from an online publisher.|Don't use 'RSS' in isolation|RSS|

### S

| Use | Description| Notes|Don’t use|
|---|---|---|---|
|SanDisk|A company that produces flash memory products, including SD cards, USB drives, and solid-state drives|One word; capitalise 'S' and 'D'|Sandisk; San Disk|
|Schmitt trigger|An electronic circuit that converts a noisy input signal into a clean digital output|Capitalise 'Schmitt'| schmitt trigger|
|screen|The display surface of a computer monitor or television|Don't use to refer to a page on a website|
|screen name|The name or handle used to identify a user in a software application or online service|Two words; lowercase|screenname|
|screen reader|An accessibility tool that reads out text and interface elements on a screen|Two words; lowercase|screenreader|
|screencast| A video recording of a computer screen, often with audio narration|One word; lowercase|screen cast|
|screensaver|A program that activates when a computer is idle|One word; lowercase| screen saver; screen-saver|
|screenshot|An image of the on-screen display of a computer or mobile device|One word; preferred over 'screengrab'|screen shot; screengrab; screen grab|
|scroll bar|A graphical interface element that allows the user to scroll content vertically or horizontally|Two words; lowercase|scrollbar|
|scroll wheel|The wheel on a mouse used for scrolling content up or down|Two words; lowercase|scrollwheel|
|SD Association (see also **SDA** in [Acronyms and initialisms](#acronyms-and-initialisms))| Developers of **SD** and **SDHC** cards|Capitalise|SD association|
|SD card|Secure Digital memory card format|Don't capitalise 'card'|SD Card|
|SDHC card|Secure Digital High-Capacity card |Don't capitalise 'card'|SDHC Card|
|Secure|Reference to the TrustZone domain of the same name|Capitalise only in this context|secure (when referring to the TrustZone domain)|
|Secure Boot|A security feature that ensures only trusted software (signed and verified) can run on a device during startup; things can boot securely without adhering to the standard|Capitalise both words|Secure boot; secure boot|
|security key|A hardware device or token used for authentication, typically for two-factor authentication|Lowercase|Security Key|
|short code|A shortened number used for SMS messaging or mobile services|Two words when referring to a mobile phone|shortcode|
|sidebar|A vertical column in a user interface that contains navigation or supplementary information|One word |side bar|
|sign in (to)|Verb: authenticate to gain access to a system or service|Two words, hyphenated as appropriate (see [Compound modifiers](#compound-modifiers)); use instead of 'log in' or 'log on'; don't use as a verb (use **login** instead of 'signin'); 'in' and 'to' are separate words|signin; sign into|
|sign-out (noun, adjective); sign out (verb)|Action or process of ending an authenticated session in a system or service|Two words, hyphenate as appropriate|signout|
|sign-up (noun, adjective); sign up (verb)|Action or process of registering for a service or account|Two words, hyphenate as appropriate|signup|
|SIM card|subscriber identity module card|Don't spell out 'SIM'|Subscriber identity module card|
|single-board computer (see also **SBC** in [Acronyms and initialisms](#acronyms-and-initialisms))|A complete computer built on a single circuit board, like a **Raspberry Pi**|Hyphenate 'single-board'|single board computer||
|system in package (see also **SiP** in [Acronyms and initialisms](#acronyms-and-initialisms))|A microelectronic device that integrates multiple ICs into a single package|lowercase|System in Package|
|sitemap|A visual or textual representation of the structure of a website|One word |site map|
|slideshow|A sequence of images or slides presented on a screen|One word; lowercase|slide show|
|smart card|A card used for authentication, payment, or identification|Two words; lowercase|smartcard; smart-card|
|smartphone|A mobile phone with advanced computing capabilities and internet connectivity|One word; lowercase|smart phone; smart-phone|
|SODIMM (see also **SBC** in [Acronyms and initialisms](#acronyms-and-initialisms))| A type of compact memory module used in laptops and small computers|No hyphen|SO-DIMM|
|Software|Collective noun for computer programs|When singular, never write 'a software'; use 'a piece of software' (preferred) or 'a software program'|a software|
|sound bite|A short extract from a recorded speech or interview|Two words|soundbite|
|soundcheck|Testing and adjusting audio equipment before a performance or recording session|One word| sound check|
|soundstage|An acoustically treated environment|One word| sound stage|
|spellchecker| A tool for identifying spelling (and sometimes grammatical) errors |One word|spell checker; spell-checker|
|splot|The individual nubble on a Lego brick, for example, a Raspberry Pi fits into a case measuring 7 × 11 splots| Lowercase|Splot|
|spyware|Malicious software designed to gather information about a person or organisation without their knowledge|One word|spy ware|
|standalone|Something that can operate independently without additional components|One word, no hyphen| stand-alone|
|STL file| File format (stereolithography) used for 3D-printing models|Though the extension itself is `stl`, in running text, write STL in all-caps with no dot before it| .stl; .STL|
|style sheet| A document that defines the presentation of structured documents (such as HTML or XML)|Lowercase, even when referring to CSS, for example, 'Cascading Style Sheets (CSS) is a **style sheet** language'; see also **CSS** in [Acronyms and initialisms](#acronyms-and-initialisms)||
|substring|A contiguous sequence of characters within a string|One word|sub-string|
|sulphur|A chemical element (S)|British English spelling|sulfur|
|sync, synched, synching |Short for 'synchronise', 'synchronised', and 'synchronising'| Omit the 'h' in 'sync'; add the 'h' for derivatives|synch; synced; syncing|

### T

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|T-shirt|A short-sleeved casual top|Capital 'T'; hyphenated|t-shirt; Tshirt|
|TensorFlow|Open-source machine learning framework|One word; capitalise 'T' and 'F'|Tensor Flow; Tensorflow|
|terminal|The command line in a GUI (for example, 'Enter the command into the terminal')|Lowercase when talking about the command line more generally|Open a Terminal window|
|Terminal|A proper noun when referring to the Terminal application on Raspberry Pi OS and when referring to a different Terminal applicaiton on an Apple computer|Only Capitalise when talking about the named application on Raspberry Pi OS or an Apple computer|Raspberry Pi terminal|
|thin client|A lightweight computer that relies on a server for processing|Two words|thin-client|
|third-party|External vendors or services|Spell out 'third'; hyphenate|3rd party; 3rd-party|
|timelapse|Photography or video technique|One word; lowercase| time lapse; Timelapse|
|timeshift|Video or broadcast term|One word|time shift, time-shift|
|title bar|Top bar of a window showing the document or program name|Two words; lowercase|Title Bar|
|TiVo|Trademarked digital video recorder brand|Capitalise 'T' and 'V'; don't use as a verb or add an 's' to make plural|Tivo; TiVos|
|to-do; to-dos (*pl.*)|Task list item|Hyphenate for this particular meaning|todo; to do|
|toolbar|UI element with buttons or controls|One word; lowercase|Toolbar; tool bar|
|tooltip|UI element that displays additional information on hover|One word; lowercase|Tooltip; tool tip|
|touchpad|A touch-sensitive surface, usually on a laptop, that allows you to control a computer's pointer and perform other actions by moving your fingers on its surface|One word; lowercase; prefer over 'trackpad'|Touchpad; touch pad; trackpad|
|touchscreen|A display device with touch input capabilities|One word; lowercase|Touchscreen; touch screen|
|towards|Directional term| British English spelling|toward|
|trackball|Input device|One word; lowercase|Trackball; track ball|
|trade show|Event for showcasing products or services|Two words| tradeshow|
|transport stream|MPEG-2 transport stream; a standard digital container format for transmission and storage of audio, video, and Program and System Information Protocol data|Lowercase except for proper acronym|Transport Stream|
|Trinket|Online platform and organisation (trinket.io)|Capitalise; use judgement based on context|trinket (when referring to the service or organisation)|
|trinket; trinkets|Projects on **Trinket**|Lowercase|Trinkets for projects|
|Trojan horse|Malware type or historical term|Two words; capitalise first word|trojan horse|
|troubleshoot|Identify and resolve a problem|One word|trouble-shoot|

### U

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|USB-C; USB Type-C|USB Type-C connector|Hyphenate as shown; see also **USB-C** in [Acronyms and initialism](#acronyms-and-initialisms) for guidance on when to use which version||
|USB flash drive|Portable flash storage device|Only capitalise the initialism|USB Flash Drive|
|USB On-The-Go (OTG)|USB feature for device-to-device connection|Hyphenate and capitalise as shown|USB on-the-go|
|undervoltage|Electrical condition of lower than expected voltage|One word|under voltage|
|unfriend (verb)|Action to remove someone as you friend on Facebook; see also **friend**|Lowercase|Unfriend|
|Unix; UNIX|Operating system| Prefer Unix (as is common usage, though trademark is UNIX)|unix|
|user base|Collection of users for a product or service|Two words|userbase|
|username|Identifier used by a user to **sign in**|One word|user name|
|userland|OS software that does not belong in the kernel|One word|user land|

### V

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|video camera|Device for recording video|Two words|videocamera|
|video game|Electronic game played on a computer or console|Two words|videogame|
|videoconference|Meeting conducted through a video link|One word|video conference; video-conference|
|vision-language model (see also **VLM** in [Acronyms and initialisms](#acronyms-and-initialisms))|A multimodal **machine-learning model** trained on visual and textual data to interpret images in relation to language and generate or respond to text grounded in visual inputs.|Hyphenate 'vision-language; lowercase unless shortened to the acronym (VLM)|vision language model; Vision-Language Model|
|voicemail|System for storing voice messages|One word|voice mail; voice-mail|
|volt (see also **V** in [Measurement suffixes](#measurement-suffixes))|Unit of electric potential|Lowercase unless using the abbreviation|3.3 Volts; 3.3 v; 3V3|

### W

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|wallpaper|Background image for a screen|One word|wall paper|
|watt (see also **W** in [Measurement suffixes](#measurement-suffixes))|the standard scientific unit of power, representing the rate at which energy is transferred or consumed|Lowercase unless using the abbreviation|Watts|
|web|See **World Wide Web**|Lowercase|Web|
|webcam|Video camera connected to a computer or internet|One word|web cam; web-cam|
|webcast|Streaming media over the internet|One word| web case; web-cast|
|webinar|Online seminar|Prefer 'online seminar'; lowercase|Webinar|
|webmaster|Person who maintains a website|One word|web master|
|web page|A single page on a website|Two words|webpage|
|web server|Server delivering web content|Two words|web server|
|website|Collection of web pages|One word| web site|
|whilst|Used only to mean 'during the time that'|British English spelling; for clarity, don't use to mean 'although' or 'when'|while (American English)|
|white paper|Authoritative report or guide|Two words; lowercase|whitepaper|
|widescreen|Display format|One word|wide screen; wide-screen|
|Wi-Fi&reg; (see also **Wi-Fi** in [Acronyms and initialisms](#acronyms-and-initialisms))|Wireless networking technology|Hyphenate; capitalise 'W' and 'F'|wi-fi; WiFi|
|wiki|Collaborative website|Lowercase; plural is wikis|Wiki|
|word mark|Text-based version of a logo|Two words|wordmark|
|word-of-mouth|Informal communication or recommendations|Hyphenated|word of mouth|
|workflow|Sequence of processes|One word|work flow|
|World Wide Web (see also **WWW** in [Acronyms and initialisms](#acronyms-and-initialisms))|The system of interlinked hypertext documents accessed through the **internet**, typically using a web browser|Capitalise|world wide web|
|writable|Capable of being written to|No 'e' in the middle of the word|writeable|

### X

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|X|Social network formerly known as Twitter|Not an abbreviation; use language like 'X, formerly known as Twitter'|Twitter instead of X|
|X-ray|Imaging technique using X-rays|Hyphenate|Xray|
|x86 architecture|Processor architecture|Lowercase 'x', numbers closed up|X86; X-86|
|X Windows|GUI framework for Unix-like systems|No hyphen; capitalise 'X' and 'W'|X-Windows

### Y-Z

|Use| Description|Notes| Don’t use|
|---|---|---|---|
|Yahoo!|Web services company and brand (trademark)|Include exclamation mark|Yahoo|
|zip file|Compressed archive file format|Two words; lowercase|Zip file; .zip file (in running text)|

## Abbreviation list

This section lists acceptable acronyms, initialisms, and shorthand notations of units of measurement.

### Acronyms and initialisms

Unless specified in the **Usage** column, the following acronyms don't typically need to be spelled out on first use. However, use your best judgement as to whether spelling something out on first mention would be useful to the audience. This might be because:

* It's less well-known for the audience (for example, **GSM**).
* It has more than one meaning (for example, **ISP**).

Don't spell out the full phrase that an acronym or initialism represents on first use if:

* The acronym or initialism is more common than the full phrase it represents (for example, **ATM** or **www**).
* Most people don't know the full phrase that an acronym or initialism represents (for example, **URL** or **PDF**).
* The acronym or initialism is the main name of a company or product (for example, **IBM** or **IMAX**).

#### A-B

|Abbreviation| Meaning| Usage|
|---|---|---|
|AI|See **artificial intelligence** in [Word list](#word-list)||
|AWG|American Wire Gauge||
|BGA|Ball grid array||
|BIOS| Basic Input/Output System||
|BSD | Berkeley Software Distribution ||
|BMP| Bitmap||

#### C-D

|Abbreviation| Meaning| Usage|
|---|---|---|
|CAN bus|Controller Area Network bus||
|CAPTCHA|Completely Automated Public Turing Test to Tell Computers and Humans Apart	||
|CAS| Computing at School|Spell out on first use for clarity|
|CD| Compact disc| Plural is 'CDs'|
|CD-R| CD-recordable| Plural is 'CD-Rs'|
|CD-ROM| CD-read-only memory | Plural is 'CD-ROMs'|
|CD-RW| CD-rewritable| Plural is 'CD-RWs'|
|CGI| Computer-generated imaging ***or*** common gateway interface ***or*** computer graphics interface| Be explicit on first use which meaning applies	|
|CLI| command line interface||
|codec|	coder; decoder|Used in video and audio contexts|
|CPU| central processing unit||
|CSS| Cascading Style Sheets||
|CSV| comma-separated values||
|DOM| See **Document Object Model** in [Word list](#word-list)||
|DoS |Denial-of-Service attack ||
|DOS (see also **MS-DOS**) |Disk Operating System | Acronym for several closely related operating systems|
|DV | digital video. ||
|DVD | digital video disc||
|DVR | digital video recorder||

#### E-F

|Abbreviation| Meaning| Usage|
|---|---|---|
|EEG |Electroencephalogram ||
|EPROM |erasable programmable read only memory ||
|ESP |email service provider ||
|EULA | end-user licence agreement||
|FAQ| frequently asked questions| Avoid using FAQs|
|FourCC | Four-character code for media files ||
|FTP| File Transfer Protocol   ||

#### G-H

|Abbreviation| Meaning| Usage|
|---|---|---|
|GPIO|General-Purpose Input/Output|All caps; don't spell out unless needed|
|GIF| Graphic Interchange Format| Plural is 'GIFs'|
|GNU |The GNU Project (a recursive acronym)| GNU is not UNIX|
|GPU| graphics processing unit ||
|GSM| Global System for Mobile Communications||
|GUI| graphical user interface ||
|HAT| Hardware Attached on Top |Describing various add-on boards such as the Sense HAT|
|HDTV|high-definition television ||
|HD audio|high-definition audio	|Full HD audio is 192kHz, HD audio is 96kHz|
|HDMI&reg;| High-Definition Multimedia Interface | See **HDMI** in word list for more detail; drop the &reg; symbol after first use|
|HTML| Hypertext Markup Language ||

#### I-J

|Abbreviation| Meaning| Usage|
|---|---|---|
|I2C|Inter-Integrated Circuit|Used for peripherals on Raspberry Pi; no superscript|
|IBM| Company name||
|IC| integrated circuit||
|ICT|information and communications technology||
|ID|identification|Plural is 'IDs' but try not to use|
|IDLE |Python IDE installed on Raspbian, found under the 'Programming' menu as 'Python 3 (IDLE)'|
|IMAX| Trademark| Use as an adjective, not a noun |
|IoT| See **Internet of Things** in [Word list](#word-list)||
|I/O| Input/Output|Don't use 'IO'; see also **PIO**|
|IP|intellectual property ***or*** Internet Protocol|Be clear about which one you mean when you mention it on first use|
|IR|infrared||
|ISP|internet service provider ***or*** image signal processor (not image sensor pipeline, which is now deprecated)|Be clear about which one you mean when you mention it on first use|
|IT|information technology||
|JPEG|Joint Photographic Experts Group ||

#### K-L

|Abbreviation| Meaning| Usage|
|---|---|---|
|LAN| local area network ||
|LCD|liquid-crystal display |Plural is LCDs|
|LED|light-emitting diode|Plural is LEDs|
|LLM|See **large language model** in [Word list](#word-list)||
|LoSSI|See **Low speed serial interface** in [Word list](#word-list)|Abbreviate after spelling it out on first use|
|LXDE |Lightweight X11 Desktop Environment ||

#### M-N

|Abbreviation| Meaning| Usage|
|---|---|---|
|MP3|MPEG-1 Audio Layer 3||
|MPEG |Moving Picture Experts Group; also refers to a compression methodology whose standards are set by this group||
|MPEG-2|A standard for the encoding of video and audio||
|MS-DOS (see also **DOS**)|Microsoft Disk Operating System; trademark for a Microsoft operating system from the DOS family||
|Ni-MH |See **nickel-metal hydride** in [Word list](#word-list)|Capitalisation differs on expansion|
|NIC|network interface card||
|NLP|natural language processing||
|NPU|neural processing unit|

#### O-P

|Abbreviation| Meaning| Usage|
|---|---|---|
|OEM|original equipment manufacturer | Preferable to **factory** when talking about the place where Raspberry Pi computers are made |
|OK|The American phonicisation of OK, which is derived from military banter ('oll korrect')|OK isn't actually short for 'okay'|
|OOP|See **object-oriented programming** in [Word list](#word-list)|Spell out and define on first use|
|OS| operating system| Plural is 'OSes'|Abbreviate after spelling it out on first use|
|P2P| peer-to-peer  ||
|PC| personal computer|Abbreviate after spelling it out on first use to avoid confusion with 'politically correct'|
|PCB|printed circuit board||
|PCIe|Peripheral Component Interconnect Express||
|PDF |Portable Document Format (Adobe file format)|Only use the abbreviation|
|PhD| Doctor of Philosophy||
|PIO|programmable I/O| Not PI/O or any other form|
|PITS|See **Pi In The Sky** in [Word list](#word-list)||
|PIN|personal identification number|No need to include 'number' after 'PIN'|
|PoE|Power over Ethernet ||
|PS2; PS3; PS4; PS5|PlayStation 2, 3, 4, or 5||
|PU resistor|pull-up resistor|Only use the abbreviation for heavily repeated usage|
|PD resistor|pull-down resistor|Only use the abbreviation for heavily repeated usage|

#### Q-R

|Abbreviation| Meaning| Usage|
|---|---|---|
|Q&A|Question and answer||
|QR code|Quick-response code|Only use the abbreviation|
|RAM|Random access memory|Only use the abbreviation|
|ROM|Read-Only Memory||
|RSS|Really Simple Syndication|Use in combination with 'feed' or 'newsreader'|
|RTC|real-time clock||

#### S-T

|Abbreviation| Meaning| Usage|
|---|---|---|
|SDA|See **SD Association** in [Word list](#word-list)||
|SIM|See **SIM card** in [Word list](#word-list)|Use in combination with 'card'|
|SBC|See **single-board computer** in [Word list](#word-list)||
|SiP|system in package||
|SMS|short message service||
|SoC| system on chip ||
|SODDIM|Small Outline Dual In-line Memory Module. See also **SODDIM** in [Word list](#word-list)||
|SoM| system on module ||
|SSH|Secure Shell||
|STL| See **STL file** in [Word list](#word-list)||
|SWD | Serial Wire Debug||
|TOS| Terms of Service||
|TV|television||

#### U-V

|Abbreviation| Meaning| Usage|
|---|---|---|
|UART|universal asynchronous receiver/transmitter||
|UF2|File format for flashing microcontrollers||
|UI|user interface||
|UK|United Kingdom||
|UN|United Nations||
|URL|Uniform Resource Locator|Only use the abbreviation|
|USA|United States of America||
|USB|Universal Serial Bus|Only use the abbreviation|
|USB-C|See **USB-C; USB Type-C** in [Word list](#word-list)|USB-C in blog posts, magazine articles, or books; **USB Type-C** acceptable in technical writing like datasheets|
|USB 2.0; USB 3.0|USB connector or version||
|USB OTG|See **USB On-The-Go** in [Word list](#word-list)||
|VGA|Video Graphics Array||
|VLM|See **vision-language model** in [Word list](#word-list)||
|VoIP|Voice over Internet Protocol|
|VPN|Virtual Private Network|Abbreviation is always acceptable|

#### W-X

|Abbreviation| Meaning| Usage|
|---|---|---|
|WAN|Wide Area Network||
|Wi-Fi&reg;|See **Wi-Fi** in [Word list](#word-list)|Only use the abbreviation; drop the &reg; symbol after first use |
|WWW|See **World Wide Web** in [Word list](#word-list)||
|WYSIWYG|See **What You See Is What You Get** in [Word list](#word-list)||
|xHCI|Extensible Host Controller Interface (USB standard)|Capitalise as shown|
|XHTML|Extensible Hypertext Markup Language||
|XML|Extensible Markup Language||

### Measurement suffixes

Unless otherwise stated, most of the following units of measure:

* Should only be used as a suffix, otherwise, spell out the full word that it represents.
* Require a space between the number and the unit, preferably a non-breaking space.

|Abbreviation| Meaning| Use|Example|
|---|---|---|---|
|°C |See **Celsius** in [Word list](#word-list)|Uppercase; no space between the number and the unit|25°C|
|°F |See **Fahrenheit** in [Word list](#word-list)|Uppercase; no space between the number and the unit, for example|72°F|
|%|Percent; don't use instead of 'percentage'|No space between the number and the symbol|5%|
|Ω|See **ohm** in [Word list](#word-list)|Don't use 'R' in place of 'Ω'|9 Ω|
|A|See **ampere** in [Word list](#word-list)|Uppercase; no space between the number and the unit| 5 V at 3 A (15 W)|
|b|See **bit** in [Word list](#word-list)|Lowercase| 16 b|
|B|see **Byte** in [Word list](#word-list)|Uppercase|16 B|
|b/s|Bits per second|Lowercase|100 b/s|
|B/s|Bytes per second|Uppercase 'B'|100 B/s|
|g| See **gram** in [Word list](#word-list) | Lowercase| 9 g|
|Gb| See **gigabit** in [Word list](#word-list) |Uppercase 'G'| 9 Gb|
|Gb/s| Gigabits per second |Uppercase 'G'|9 Gb/s|
|Gib| See **gibibit** in [Word list](#word-list) | Uppercase 'G'|9 Gib|
|Gib/s| Gibibits per second |Uppercase 'G'| 9 Gib/s|
|GiB (see also **GB**)| See **gibibyte** in [Word list](#word-list) |  Uppercase 'G' and 'B'; use only for a technical audience; **GB** preferred for a general audience|9 GiB|
|GiB/s|Gibibytes per second | Uppercase 'G' and 'B'| 9 GiB/s|
|GB| See **gigabyte** in [Word list](#word-list) | All caps| 9 GB|
|GB/s| Gigabytes per second |Uppercase;|9 GB/s|
|GHz |See **gigahertz** in [Word list](#word-list) | Uppercase 'GH'|9 GHz|
|GT |See **Gigatransfers** in [Word list](#word-list) | Uppercase 'GT'; used in specific hardware contexts (e.g., PCIe) and not technically an SI unit||
|GT/s| GigaTransfers per second; see also **Gigatransfers** in [Word list](#word-list) |Uppercase 'GT'; **MB/s** preferred for a general audience| 9 GT/s|
|in.|See **inch** in [Word list](#word-list)|Lowercase; include a full stop after 'in'|9 in.|
|kb|See **kilobit** in [Word list](#word-list) |Lowercase|9 kb|
|kb/s| Kilobits per second |Lowercase |9 kb/s|
|kB|See **kilobyte** in [Word list](#word-list) | Uppercase 'B'|9 kB|
|kB/s| Kilobytes per second | Uppercase 'B'|9 kB/s|
|Kib|See **kibibit** in [Word list](#word-list) | Uppercase 'K'|9 Kib|
|Kib/s|Kibibits per second|Uppercase 'K'| 9 Kib/s|
|kg| See **kilogram** in [Word list](#word-list) | Lowercase|9 kg|
|kHz| See **kilohertz** in [Word list](#word-list) | Uppercase 'H'| 9 kHz|
|km| See **kilometre** in [Word list](#word-list) | Lowercase|9 km|
|km/h|kilometres per hour| Lowercase|9 km/h|
|l|See **litre** in [Word list](#word-list)|Lowercase, unless there is a high likelihood of it being misread as a capital 'I'or '1', in which case, uppercase is acceptabel|9 l; 9 L|
|m|See **metre** in [Word list](#word-list)|Lowercase|9 m|
|Mb|See **megabit** in [Word list](#word-list) |Uppercase 'M'|9 Mb|
|MB|See **megabyte** in [Word list](#word-list)|All caps| 9 MB|
|Mb/s|Megabits per second|Uppercase 'M'|9 Mb/s|
|MB/s|Megabytes per second|Uppercase 'MB'|9 MB/s|
|MHz|see **megahertz** in [Word list](#word-list)|Uppercase 'MH'|9 MHz|
|Mib |See **mebibit** in [Word list](#word-list)|Uppercase 'M'|9 Mib|
|MiB|See **mebibyte** in [Word list](#word-list)|Uppercase| 9 MiB|
|Mib/s|Mebibits per second|Uppercase 'M'|9 Mib/s|
|MiB/s|Mebibytes per second|Uppercase 'M'; rarely used (consider **MB/s** instead)|9 MiB/s|
|min.| Minute|Use only where space is at a premium; include a full stop after 'min'| 9 min.|
|MIPS|million instructions per second|All caps|9 MIPS|
|mg|See **milligram** in [Word list](#word-list)|Lowercase|9 mg|
|ml|See **millilitre** in [Word list](#word-list)|Lowercase|9 ml|
|mm|See **millimetre** in [Word list](#word-list)|Lowercase|9 mm|
|MP|See **megapixel** in [Word list](#word-list)|All caps|9 MP|
|mpg|Miles per gallon|Lowercase| 9 mpg|
|mph|Miles per hour|Lowercase| 9 mph|
|V|See **volt** in [Word list](#word-list)|Uppercase| 3.3 V (not 3V3)|
|W|See **watt** in [Word list](#word-list)|Uppercase| 60 W|

## Words and phrases to avoid

This section highlights words and phrases to avoid, and provides preferred alternatives, grouped as follows:

- **[Insensitive words and phrases](#insensitive-words-and-phrases).** Avoid ableist, gendered, or culturally problematic terms.
- **[Violent words and phrases](#violent-words-and-phrases).** Choose neutral alternatives that reduce aggressive connotations.
- **[System-focussed words](#system-focussed-words-and-phrases).** Refer to user actions rather than device actions.
- **[Ambiguous words and phrases](#ambiguous-words-and-phrases).** Clarify meaning in instructions and technical content.
- **[Non-English words and phrases](#non-english-words-and-phrases).** Use precise English alternatives to common non-English terms (for example, 'faux pas') and Latin terms (for example, 'vice versa') for clarity and easier translation.
- **[Colloquialisms and idioms](#colloquialisms-and-idioms).** Avoid slang, metaphors, and expressions that are not globally understood.
- **[Subjective and marketing words](#subjective-and-marketing-words).** Focus on being factual and avoid terms that could be true for one person but not for another (for example, describing something as 'easy').
- **[Technically incorrect and outdated terminology](#violent-words-and-phrases).** Use accurate, modern language that's easier to understand for the wider audience.
- **[Words with simpler alternatives](#words-with-simpler-alternatives).** Prefer short, clear, everyday words wherever possible.
- **[Overusing polite words and phrases](#overusing-polite-words-and-phrases).** Be considerate but concise, avoiding unnecessary wordiness or insincere-sounding platitudes.

### Insensitive words and phrases

The following words and phrases are problematic because they have ablest, gendered, racial, or carry other culturally problematic undertones.

|Avoid	|Use instead	| Exceptions|
|---|---|---|
|abort|	end; leave; stop; exit; cancel	|When making direct reference to a UI element that includes the word 'abort'|
|agnostic|	platform-independent	||
|blacklist (see also **whitelist**)	| blocklist; exclude list; deny list|	When referring to proper noun or making direct reference to a UI element that includes the word 'blacklist'
| black box testing (see also **white box testing**)|functional testing; acceptance testing	||
|black hat hacker (see also **white hat hacker**)	| bad actor; unauthorized user; malicious hacker	||
|blind	| anonymous; ignore	||
| dummy data/value | placeholder data/value; sample data/value	||
|exploit| use||
|female|socket; port; jack; slot ||
| hand (as in 'right-hand side of the screen')	| NA – remove word, e.g., 'right side of the screen'||
| hands-off	| automatic|
| hands-on |direct; manual||
| male|connector; plug; pin; header||
| man hours	| person hours; time; resources; effort	||
| man-in-the-middle	|attacker-in-the-middle; on-path attacker; or name the specific attack type	||
|master	|main; primary; lead(er)	| When referring to proper noun or making direct reference to a UI element that includes the word 'master'.
|mating| connecting; corresponding; paired; interfacing||
|mute	|silence	||
|native	|built-in	||
|owner	| lead, manager, expert	||
| sanity check	| smoke test; confidence check; coherence check	||
| slave	|secondary; subordinate; follower	||
| white glove |	high-touch; premium	||
|whitelist (see also **blacklist**)	|allowlist; include list|	When referring to proper noun or making direct reference to a UI element that includes the word 'whitelist'.
| white box testing (see also **black box testing**) | glass box testing; clear box testing	|
|white hat hacker (see also **black hat hacker**)	| A specific job title, e.g., 'Cyber Defense Analyst'	||

### Violent words and phrases

The following words and phrases might be common in developer contexts, but have violent connotations in everyday contexts.

|Avoid|Use instead|
|---|---|
|execute|run |
|hang	| freeze; stop responding; not responding; halt |
| hit	| select; press; type |
| kill	| end; stop |
|scrape|crawl|
| strip(ped)	| remove(d); replace(d) |
|target	|anchor; deliver; choose; point to; position; direct(ed); select; insert; activate; send to |
| terminate	| stop; exit; cancel; end |
|trigger	|prompt; start; generate; initiate|

### System-focussed words and phrases
Avoid talking about mouse and keyboard actions. Instead, refer to *user* actions.

|Avoid|Use instead| Exceptions|
|---|---|---|
|click	|select; choose |	When you have to refer specifically to mouse actions, for example, 'select the option by right-clicking on the button'|
|hover (see also **mouseover**) | hold; pass; move [your cursor over]||
|mouseover; mouse over (see also **hover**) |roll; move your cursor over|
|press (see also **type**)	| enter||
| scroll |	move through||
|text box	| box; field|	|
|type (see also **press**)| enter||
|toggle on/off	| turn on using the toggle; turn off using the toggle||

### Technically incorrect and outdated terminology

Avoid using outdated terms, especially those that are ambiguous or no longer reflect current usage. Use modern, inclusive, and accurate language that aligns with current industry standards and audience expectations. When replacing older terms, aim for clarity and specificity.

|Avoid|Use instead|Exceptions|
|---|---|---|
|bookazine||
|code, coding|computer programming; software engineering||
digital age, digital native, digital divide|NA – don't use||
|cyber|| If you do need to use it, don't hyphenate, for example: cyberattack; cyberterrorism|
|dongle|USB drive; (USB) flash drive; (USB) memory stick|
|k (see also [Numbers](#numbers))|thousand; kilobytes; kB||
|KB|kB; KiB||
|KB/s|kB/s; KiB/s||
|machine|computer|When not talking about a computer|
|microblog|social media platform (or the specific brand)||
|PCIe connector (a standard that Raspberry Pi 5 **isn't** using)| Raspberry Pi connector for PCIe|When not referring to Raspberry Pi|
|southbridge|Input/Output Controller Hub; I/O Controller Hub (ICH)|
|snail mail | the post; mail |
|thumb drive|USB drive; USB flash drive; memory stick|
|Twitter|X|When specifically referring to the former name of X|
|tweet|post on X (formerly Twitter)||
|weblog|blog|When explaining etymology of **blog**|
|web browser|browser||

### Words with simpler alternatives

Choose short, simple, everyday words over long, formal, or complicated words.

|Avoid|Use instead| Exceptions|
|---|---|---|
|access	|see; edit; find; use; view	||
|allow (see also **enable**)	| let	||
|assistance	|help	|
|comprises	|consists of; contains; includes	||
|enable (see also **allow**)	|let	||
|for instance	| for example; such as||
|further	|more|	|
|ingest	|load; import	||
|in order to	|to |	When the word 'to' is in the middle of a sentence and 'in order to' would clarify the meaning.|
|leverage	|use|	|
|navigate	|go|	Sentences other than 'Navigate to', for example, 'This allows you to stay updated without having to navigate away from the page'.
|navigation	| menu	||
|possible	|can	| setting expectations about what might go wrong, for example, 'It is possible for data to change'.|
|proceeding| following; next||
|utilise	|use	||

### Overusing polite words and phrases

Be considerate, not over-polite. Avoid overusing 'please', 'thank you', and 'sorry', especially for normal operations. Adding these phrases might be polite, but they can seem disingenuous and slow users down with wordiness.

|Avoid|Use instead| Exceptions|
|---|---|---|
|'Please in the context of normal product usage, even if you’re explaining a difficult task|	NA – remove word	| When asking for permission or forgiveness, for example, when what you’re asking for only benefits Raspberry Pi, inconveniences the user, or suggests a potential issue.
| 'Please note' to start a sentence	| Use a callout box prefaced with 'Note:' in bold	||
| 'Sorry' in the context of normal product functioning|	NA – remove word|	Use only in situations that cause problems for the user, such as a system crash or data loss.
|'Thank you' for any notice or action|NA – remove word|	Use when you’re asking someone to provide input.|

### Words and phrases to avoid in technical writing

The following subsections are applied strictly to **technical writing**, but should also be considered for other forms of writing. The following guidance helps to maximise clarity, minimise inaccuracy, and optimise localisation. For example, unless space is limited, consider using 'specifically' instead of 'i.e.' or 'for example' instead of 'e.g.'; these spelled-out English alternatives are more specific, are less prone to incorrect use, and are easier to translate into other languages.

#### Ambiguous words and phrases
The following words and phrases are problematic, especially in **technical writing**, because they can be interpreted in different ways. Instructional content in particular needs to be unambiguous, especially for describing whether something must or can be done, and when considering the hypothetical future 'will' and 'should'.

|Avoid|Use instead| Exceptions|
|---|---|---|
|above (see also **below**)| previous; earlier||
|as (see also, **since**)|because||
| below (see also **above**)| later; the following	||
| biannually; bi-annually| twice a year	||
| biennial| every two years	||
| bimonthly; bi-monthly| twice a month; every two months||
| biweekly; bi-weekly| twice a week; every two weeks||
| could | can ||
|disable | disconnect; deactivate; turn off	|When no other word is accurate|
| may| might; can |	When referring specifically to permission|
| new; newer (see also **old**) | latest; later	||
|old; older (see also **new**)	| earlier; legacy	|
| once	|when; after |	When referring specifically to a singular occasion	|
|should	|must; is expected; we recommend; might; can		||
|surface	| expose; uncover; reveal; make available	||
| since (see also **as**)|	because	||
| will | then (for example, 'the system then boots' instead of 'the system will boot')
| wish	| want; need	||
| would	|can; is then||

#### Prose abbreviations and non-English terminology
Avoid using prose abbreviations and non-English words and phrases, especially in **technical writing**. Many of the following examples can reduce clarity and make translation more difficult. Readers and writers also often use the following examples incorrectly, especially Latin phrases and abbreviations. For example, readers and writers frequently use 'i.e.' and 'e.g. interchangeably. Using the intended word or phrase in full removes this inconsistency and ensures accuracy.

|Avoid|Use instead|Exceptions|
|---|---|---|
|ad hoc	|as needed; after||
|AKA|also known as; or; formerly known as|If you must use it (in non-technical writing, for example, to save space), don't include full stops between the letters.|
|e.g. (preferred to **ex.** if using the shortened form)	|for example; such as; like|In non-technical documentation or when space is tight; if you use it, include full stops (**e.g.**) and use it with commas as if the phrase 'for example' is being used|
|etc.	|and so on|
|ergo	|thus, therefore|
|ex. (prefer **e.g.** if using the shortened form)| for example; such as; like||
|faux pas|mistake||
|i.e.	|specifically|In non-technical documentation or when space is tight; if you use it, include full stops (**i.e.**) and use it with commas as if the phrase 'specifically' is being used|
|per| for each|
|per se| by itself|
|via	|through|
|vice versa	|NA – write out the reverse in technical writing, for example, 'There might be detractors and no promoters, or there might be promoters and no detractors.'|
|vs.|	versus|

#### Colloquialisms and idioms

In **technical writing**, avoid phrases that require special, local, or cultural knowledge, and colloquialisms or slang. These can be less precise but also can be problematic for translating into other languages (Raspberry Pi is a globally recognised and used product). Avoid idioms, expressions, metaphors, clichés, irony, and humour.

|Avoid|Use instead|
|---|---|
|at the end of the day	|N/A –– remove word|
| deep dive (see also **drill down** and **dig in**)	|Use specific phrases, for example 'view the details'|
|dig in (see also **drill down** and **deep dive**)	|Use specific phrases, for example 'view the details'|
|drill down (see also **dig in** and **deep dive**)	| Use specific phrases, for example 'view the details'|
|fine-tune| refine; adjust||
| from the jump	| from the start; from the beginning |
| get the hang of |	get familiar with |
| handy	| convenient|
| isn't exactly rocket science | straightforward|
| jump (straight) in| start; begin|

#### Subjective and marketing words

Avoid subjective marketing and sales language in **technical writing**; this is to avoid a subjective tone created by value judgements and stance adjuncts. Instead, be specific and factual about the benefits.

|Avoid|Use instead|
|---|---|
amazing	| NA – remove word |
easily; easy| Remove word because the same meaning can usually be conveyed without it; if necessary, use 'straightforward' instead |
just (see also **only**)	| NA – remove word |
latest	| If necessary, use 'up to date' |
obviously	| NA – remove word |
only (see also **just**)	| NA – remove word |
quick; quickly	| Remove word because the same meaning can usually be conveyed without it; if necessary, refer to the number of steps instead |
simple; simply	| NA – remove word |