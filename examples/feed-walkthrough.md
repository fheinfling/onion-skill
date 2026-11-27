# Feed mode: a walkthrough

Five Wikipedia articles about reading and information, run through the skill in Claude Code on 27 November 2026. Each block is one turn: what was typed, then Claude's answer, unedited. In this run, Claude read the pages with its web fetch tool, which returns short verbatim excerpts rather than the whole page; it says so in its first answer.

Sources: [SQ3R](https://en.wikipedia.org/wiki/SQ3R), [Stretchtext](https://en.wikipedia.org/wiki/StretchText), [Information overload](https://en.wikipedia.org/wiki/Information_overload), [Progressive disclosure](https://en.wikipedia.org/wiki/Progressive_disclosure), [Skimming (reading)](https://en.wikipedia.org/wiki/Skimming_(reading)) (redirects to Speed reading). Wikipedia text is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); the quotes below are short excerpts from those articles, checked word for word against them.

---

**You:** `/onion https://en.wikipedia.org/wiki/SQ3R https://en.wikipedia.org/wiki/StretchText https://en.wikipedia.org/wiki/Information_overload https://en.wikipedia.org/wiki/Progressive_disclosure https://en.wikipedia.org/wiki/Skimming_(reading)`

1. **SQ3R**
   SQ3R is a five-step reading method (survey, question, read, recite, review) that offers a less passive way to read textbooks.
   > "a less passive approach to reading textbook material"

2. **StretchText**
   Stretchtext is a hypertext feature that lets readers expand or contract text in place, unlike a link, which replaces the current text.
   > "StretchText expands or contracts" · "A link completely replaces the current piece"

3. **Information overload**
   Information overload is the difficulty of understanding an issue and making decisions effectively when someone has too much information about it.
   > "when one has too much information (TMI)"

   *Note: I read the first 100,000 of the page's 109,717 characters. The core comes from the lead.*

4. **Progressive disclosure**
   Progressive disclosure is an interaction design pattern used to make software applications easier to learn and less prone to errors.
   > "easier to learn and less error-prone"

5. **Skimming (reading)**
   Speed-reading techniques claim to make reading faster, but there is little scientific evidence about them, so their value seems uncertain.
   > "little scientific evidence regarding speed reading"

   *Note: this URL redirects to the article "Speed reading", so that's the one summarized.*

I got the text with the WebFetch tool, which only quotes short passages word for word. Downloading the full pages directly needed an approval this session couldn't give, so I didn't.

Pick a number to go deeper: key facts (30 s) · points (2 min) · details (5 min) · full text

---

**You:** `2`

**Core:** Stretchtext is a hypertext feature that lets readers expand or contract text in place, unlike a link, which replaces the current text.

**Key facts: StretchText**

- Ted Nelson coined the term in *Computer Decisions* in September 1970. (¶ beginning *Ted Nelson coined the*, section "Ted Nelson's 1970 definition")
- Nelson had already described the idea years earlier. ("as early as 1967")
- Because stretchtext expands in place instead of jumping to a new page, the surrounding text stays visible as context. ("the existing hypertext serves as context")
- Nelson pictured a screen with two throttles: one to move through the text and one to expand it. (¶ beginning *Nelson imagined a screen*)
- Stretchtext hasn't caught on widely on the Web, but it has been used in electronic literature, including *Victory Garden* (1991), *The Jew's Daughter* (1998) and the novella *Pry*. (lead, ¶ beginning *Stretchtext has not gained*; section "Usage in electronic literature")

next: points (2 min) · details (5 min) · full text · `list` for all items

---

**You:** `next`

**Core:** Stretchtext is a hypertext feature that lets readers expand or contract text in place, unlike a link, which replaces the current text.

**Points: StretchText**

- **It shows more detail only when the reader asks for it.** A demo in the article lists the propositions of Wittgenstein's *Tractatus Logico-Philosophicus* and reveals his further commentary as the reader expands each one. (lead, image caption)
- **It is still studied and used for art, though the Web never adopted it widely.** It remains a subject of hypertext and hypermedia research, and it has been used for literary and poetic effect in electronic literature and interactive cinema. (lead, ¶ beginning *Stretchtext has not gained*)
- **Nelson came up with it as a teaching tool.** He argued that computer-assisted instruction would beat traditional schooling because students could follow their own interests. He saw hypertext, a term he coined in 1965, as the best way to organize this, and stretchtext was one of several types he described. (¶ beginning *Ted Nelson coined the*)
- **Navigating with throttles seemed less odd in 1970.** The article says computer interfaces weren't standardized yet. Its photo, from 1969, shows someone editing hypertext with a light pen. (image caption beginning *In 1970, interfaces for*)
- **Nelson demonstrated the idea with a text that describes itself.** He gave a short sample about stretchtext, then an expanded version of it. The longer version calls stretchtext a kind of hypertext closely related to prose, which grows by adding words and phrases and shrinks by removing them. (¶ beginning *Nelson offers this text*; block quote beginning *Stretchtext, a kind of*)
- **The idea has spread beyond text.** Anders Fagerjord described "stretchfilm" in 2005. (¶ beginning *The idea has also*)
- **Critics single out one work in particular.** Mark Bernstein called Judd Morrisey's *The Jew's Daughter* "perhaps the most artistically successful stretchtext fiction". Agnieszka Przybyszewska (2016) discussed *Pry*, a novella designed for the iPad. (section "Usage in electronic literature")

next: details (5 min) · full text · `list` for all items

---

**You:** `full text`

**Core:** Stretchtext is a hypertext feature that lets readers expand or contract text in place, unlike a link, which replaces the current text.

**Full text: StretchText (Wikipedia)**

[Open the passage behind the core](https://en.wikipedia.org/wiki/StretchText#:~:text=A%20link%20completely%20replaces%20the%20current%20piece)

The passage is in the section **"Ted Nelson's 1970 definition"**, in the sentence that compares stretchtext with links. Browsers that support text fragments will scroll to it and highlight it; other browsers just open the page.

**Outline**
- (Lead)
- Ted Nelson's 1970 definition
- Usage in electronic literature
- References

`list` shows all five items again (StretchText is at full text, the other four at the core).

---

**You:** `list`

1. **SQ3R** *(core)*
   SQ3R is a five-step reading method (survey, question, read, recite, review) that offers a less passive way to read textbooks.
   > "a less passive approach to reading textbook material"

2. **StretchText** *(full text)*
   Stretchtext is a hypertext feature that lets readers expand or contract text in place, unlike a link, which replaces the current text.
   > "StretchText expands or contracts" · "A link completely replaces the current piece"

3. **Information overload** *(core)*
   Information overload is the difficulty of understanding an issue and making decisions effectively when someone has too much information about it.
   > "when one has too much information (TMI)"

   *Note: I read the first 100,000 of the page's 109,717 characters. The core comes from the lead.*

4. **Progressive disclosure** *(core)*
   Progressive disclosure is an interaction design pattern used to make software applications easier to learn and less prone to errors.
   > "easier to learn and less error-prone"

5. **Skimming (reading)** *(core)*
   Speed-reading techniques claim to make reading faster, but there is little scientific evidence about them, so their value seems uncertain.
   > "little scientific evidence regarding speed reading"

   *Note: this URL redirects to the article "Speed reading", so that's the one summarized.*

Pick a number to go deeper. StretchText has no deeper layers left except details (5 min), which you can still open with `2` then `details`.
