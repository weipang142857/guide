# Writing Pet Peeves

## Grammar and Style

+ Stay in the same tense! Some authors like to describe experiments in the past tense, e.g., "The user received a push notification and clicked on it." Others like to describe experiments in the present tense, e.g., "The user receives a push notification and clicks on it." Both are fine, but stay consistent in the same tense. Don't write, "The user receives a push notification and clicks on it. The click was then recorded by the server."

+ "Related work", **not** "related works". "Work" is a collective noun, like "staff". You don't say "research staffs".

+ Common noun-verb (note that in Latex this would be an en-dash, see below) agreement issue: "number of sample increases", not "increase". The verb agrees with the head noun, which is number, singular in this case.

## Latex

### Finer Points of Punctuation

+ Learn the difference between [an hyphen, en-dash, and em-dash](http://www.thepunctuationguide.com/hyphen-and-dashes.html).

  + It's `key--value` as in `key--value` store, not `key-value`.

  + It's `human--computer interaction`. Note that the [Wikipedia article](https://en.wikipedia.org/wiki/Human%E2%80%93computer_interaction) gets it right and [this incorrect URL](https://en.wikipedia.org/wiki/Human-computer_interaction) redirects to the correct article.

+ Footnotes go after the punctuation, as in `End of sentence.\footnote{...}`. Note, there is _no_ space between punctuation and the footnote.

+ There is a difference between end-of-sentence spacing and intra-sentence spacing after a period. For example, `cat vs.\ dog` but `I like cats. She likes dogs.`

### Citations

+ Cite a reference as `Lin et al.~\cite{Lin}`. Note `~` prevents ugly breaks.

+ **NEVER** *ever* begin a sentence with a citation. e.g., "[5] explored the use of..."

+ A citation is not a noun phrase, e.g., "is shown in [5]" is bad; should be "is shown by Smith et al. [5]". (Although I break this rule myself sometimes.)

+ Name your proceeding volumes consistently in the bibliography.

### Misc

+ Latex does weird hyphenation on line breaks sometimes. For example, analysis might get hyphenated as "anal-ysis", which just looks dirty. MapReduce gets hyphenated as "MapRe-duce", which bugs me. Insert in the preamble `\hyphenation{Map-Reduce}` to specify particular hyphenations you want, or use `\mbox{...}` to suppress hyphenation.