[![](https://substackcdn.com/image/fetch/$s_!jaiu!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F31c4b79c-1bd2-4388-b734-570fea537d88_730x350.png)](https://substackcdn.com/image/fetch/$s_!jaiu!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F31c4b79c-1bd2-4388-b734-570fea537d88_730x350.png)

### **The anxiety of knowing too much**

#### **Article 11 of 21 of the Governance as Versioning series**

* * *

 _This is Article 11 of the Governance as Versioning series. The thinker is Richard Saul Wurman. The central Git concept is README — the document that reduces informational anxiety at the first opening of any repository. The corresponding step is Step 8 of the 21 Steps._

* * *

**What will you find here?**

Have you ever opened a system, minutes, a report, or a spreadsheet full of data and had no idea where to start? Have you ever felt that the more information arrived, the less you understood what was happening?

Wurman named that feeling. And discovered that the problem wasn’t yours.

* * *

## **1\. Where it all begins**

Los Angeles, 1989. Richard Saul Wurman, 54 years old, a trained architect who had traded buildings for diagrams, looked at his own desk and couldn’t find the desk. Stacks of newspapers, magazines, reports, faxes, memos, clippings. He subscribed to eleven periodicals. He read four newspapers a day. And the more he read, the less he understood.

It wasn’t laziness. It was the opposite of laziness. Wurman consumed information like someone drinking saltwater: each sip increased the thirst.

He stopped. Looked at that mountain of paper and named what he felt. He called it information anxiety — the distance between what we know and what we think we should know. It wasn’t a clinical diagnosis. It was an architectural one. The problem wasn’t in Wurman’s head. It was in the way information reached him.

That year he published the book that named the problem: _Information Anxiety_. The thesis fit in one sentence: we are drowning in data and thirsting for understanding. More information does not mean more understanding. In most cases, it means less. Because information without organization is not knowledge. It’s noise.

The Sunday edition of The New York Times, Wurman calculated, contained more information than a person in the seventeenth century would encounter in an entire lifetime. It wasn’t rhetorical exaggeration. It was math done by an architect who took numbers seriously. If it was already like that in 1989, what about 2025, when we produce in two days more data than all of humanity accumulated through 2003?

Volume exploded. Human processing capacity did not.

* * *

## **2\. Historical context**

Wurman wrote at a moment when the world celebrated the information explosion as pure progress. More television channels, more specialized magazines, more electronic databases. The commercial internet did not yet exist, but the tide was already rising. The dominant narrative was simple: more information generates more democracy, better decisions, and more enlightened citizens.

Wurman overturned that table. He said that more information without organization generates paralysis, anxiety, and worse decisions. He wasn’t against information. He was against the illusion that quantity solves anything. The same argument Hayek made about dispersed knowledge (article 3), Wurman made about volume: it doesn’t matter if you have the data if it arrives without shape, without context, or without hierarchy. The brain stalls.

* * *

## **3\. The central idea**

The distinction is simple and almost no one makes it: data is not information, information is not knowledge, knowledge is not wisdom.

“42” is data. “42% of residents approve the building renovation” is information. “Approval drops every time the cost exceeds R$ 500 per unit” is knowledge. “Present the proposal in two phases to keep the cost below the psychological threshold” is wisdom.

What do most governance systems produce? Data. Tons of data. 47-page minutes that nobody reads. Spreadsheets with two hundred rows and no summary. Reports that repeat the obvious and hide what matters. Information that does not reduce uncertainty (Shannon, article 5) is not information: it is noise with a serious appearance.

Wurman wasn’t talking about ignorance. He was talking about intelligent people who feel stupid because information arrives in a way the human brain cannot process. Do you feel bad for not understanding the public budget? Your fault? No. The budget was built for accountants, not for citizens. The law regulating your neighborhood was written in legalese for lawyers, not for the people who live there. The system was designed for whoever created it, not for whoever needs it.

Anxiety is not personal weakness. It is a symptom of bad architecture.

* * *

## **4\. Developments**

### **The five drawers of the world**

Wurman made a discovery that seems small but is enormous: all information can be organized in only five ways. Five. Not six, not ten. He created the acronym LATCH.

**L for Location:** Organize by place. A map of dengue cases by neighborhood. You see where the problem is concentrated.

**A for Alphabet:** organize alphabetically. A list of residents. You find who you’re looking for.

**T for Time:** Organize by timeline. The history of assembly decisions over the last two years. You see the evolution.

**C for Category:** Organize by type. Proposals are separated into “maintenance,” “security,” and “recreation.” You compare what is comparable.

**H for Hierarchy:** organize by importance, size, or priority. Expenses from largest to smallest. You see where the money goes.

Any information organization that works uses one of these five forms or a combination of them. And the part that matters: the choice of organization changes what you understand. The same budget organized alphabetically by department is useless. Organized by expenditure hierarchy, it’s clear in five seconds where the money goes. The form is not neutral. The form is editorial.

### **The architect of understanding**

Wurman was not a programmer or a computer scientist. He was an architect. And he brought to information the same reasoning he used for buildings: if people get lost in the space, the problem is the design, not the people. If residents can’t find the emergency exit, the architect made a mistake. If the citizen doesn’t understand the bill, whoever wrote it made a mistake.

That inversion is radical. Stop blaming the user. Start blaming the design. And the design can be fixed.

Wurman founded the TED conference in 1984 (five years before the book) with exactly that obsession: short presentations, visual, without jargon. TED is Wurman applied: it doesn’t simplify content, it simplifies the form. The content remains complex. The packaging stops getting in the way.

* * *

## **5\. Historical legacy**

The book _Information Anxiety_ sold modestly. The TED conference became a global phenomenon. The irony is that TED became more famous than the principle that generated it. Wurman left TED in 2002, sold the rights, and watched the creature grow without him.

But the contribution that crossed decades was LATCH. Edward Tufte, the foremost theorist of data visualization, worked in neighboring territory, but Wurman was the one who systematized the prior question: before visualizing, how do you organize? The answer (five forms, no more) appears today in corporate dashboards, search interfaces, project management systems, and code repositories. Almost no one knows Wurman’s name. Everyone uses his ideas.

* * *

## **6\. Contradictions and limitations**

Wurman was better at diagnosing the problem than solving it at scale. His books on cities and information are brilliant hand-drawn maps, but for a few. The TED conference solved the presentation, not the participation: the audience watches, it doesn’t build. It’s a cathedral, not a bazaar (Raymond, article from the introduction).

LATCH also has a blind spot: it works for static information but handles poorly information that changes all the time. A public budget that is amended every week needs more than five drawers. It needs versioning.

* * *

## **7\. The translation into versioning**

Wurman never saw a Git repository. At 89 years old, after six decades dedicated to making information comprehensible, he probably never will. But the system he described, without knowing it, is the exact description of how a well-organized repository works.

An objection comes up frequently: “Git already solves Wurman’s problem automatically. Commits have timestamps, branches have names, tags exist. The structure is given.” The objection is right about the structure. It is wrong about curation. Git provides the containers. Wurman is talking about what you put inside them and how. A commit with the message “adjustments” uses the Git timestamp, but contains no Wurman information: nobody knows what changed, why, or what it affects. The repository has time structure (T in LATCH). It has no informational content. Those are different things.

**Step 8 — README:** the README is Wurman’s antidote inside the repository. It is not technical documentation for specialists. It is an architecture of comprehension for anyone who opens the project for the first time. A well-written README answers in under two minutes: what this project is, who can participate, how to get started, what has already been decided, and where the open proposals are. It reduces informational anxiety at first reading. If someone opens the repository and doesn’t know where to begin, the README failed. Not the reader. The README’s architect. Wurman would call it bad architecture. The system was designed for those who already know it, not for those who need to understand it.

**LATCH is the grammar of the repository.** Tags organize by category (C). The commit timeline is organized by time (T). Priority labels organize by hierarchy (H). The README organizes by location within the project (L). Even the list of collaborators follows alphabetical order (A). Each of Wurman’s five forms has a direct equivalent in Git. A repository without organization is what Wurman called an informational dump: everything is there, nobody finds anything.

**The data/information distinction in the commit.** The difference between a commit that says “adjustments” and one that says “fixed condominium fee calculation that was charging 15% instead of 10%, affecting 43 units since January” is the difference between data and information. The first is data. The second reduces uncertainty. It says what, why, who, and when. Shannon would measure: the second commit has more bits of real information. Wurman would say the second commit was architected for the reader, not for the author.

**Informational anxiety in the poorly maintained repository.** Three hundred open issues without labels. Fifty branches without descriptive names. A commit history that reads like a teenager’s diary: “attempt 1,” “attempt 2,” “here we go,” and “I think this time it’ll actually work.” The participant opens the system, feels the same thing Wurman felt looking at his desk in 1989, and closes it. Paralysis. The opposite of governance.

Wurman’s warning to any versioning system is direct: organization is not decoration; it is infrastructure. Open and incomprehensible code is the same as closed code. The freedom to see (Step 1 of the 21) only works if what you see makes sense.

* * *

## **8\. Practical implication**

On January 28, 1986, the Space Shuttle Challenger exploded 73 seconds after launch. Seven astronauts died. The subsequent investigation revealed that engineers at Morton Thiokol had produced charts showing the correlation between low temperature and seal joint failures in the solid rocket boosters. That information existed. It was documented. It was available to the managers who made the decision to launch on a morning of 34°F, overriding technical recommendations.

The problem was one of informational architecture, in exactly Wurman’s sense. The temperature and failure data were presented in a format that obscured the pattern rather than revealing it: charts that mixed variables, scales that compressed the critical data, organization that prioritized technical appearance over comprehension. The result was that decision-makers did not see what the data was saying. The information was there. The architecture prevented it from arriving as information. It arrived as unreadable data in a moment when time was pressing and Kahneman’s System 1 was in command.

An illustrative example: a recycling cooperative in Porto Alegre records everything—minutes, spreadsheets, contracts, and schedules. Information is not lacking. Organization is. Result: nobody consults anything, decisions are made from memory, and when someone asks “how much cardboard did we sell in June?”, three people give three different numbers. Apply LATCH: organize by time (monthly history), by category (type of material), and by hierarchy (volume from largest to smallest). With three filters, the cooperative goes from “we have everything, but can’t find anything” to “any new person understands the system in ten minutes.”

* * *

## **9\. Lessons learned**

More information without organization worsens decisions; it doesn’t improve them. Volume is not a virtue.

If someone doesn’t understand, the problem belongs to whoever organized it. Stop blaming the reader.

All information fits in five drawers: location, alphabet, time, category, and hierarchy. Choose the right one before you begin.

The way you present data changes what people understand. Organization is an editorial decision, not a technical one.

A repository without curation is a dead archive disguised as a living system.

* * *

## **10\. Exploring paths and connections**

Part II of the series has been stacking obstacles. Weber (article 8) showed that the system seizes up from within: bureaucracy devours the purpose. Lippmann (article 9) showed that reality arrives distorted: the pseudo-environment replaces the world. Kahneman (article 10) showed that the processor is crooked: built-in biases warp judgment. Now Wurman completes the picture: even if the system doesn’t seize up, reality arrives clean, and the processor works, volume can stall everything. Four layers of problem, each one different.

But one question remains that none of these four answered: if governance deals with shared resources—collective money, public space, open code—how do real groups care for those resources without privatizing or nationalizing them? Is there a path between “this belongs to everyone” and “this belongs to no one”?

In 1990, an American political scientist named Elinor Ostrom published a book that irritated economists and surprised the world. Ostrom went to study communities that managed pastures, forests, and collective irrigation systems — without government and without markets. And she found something that theory said was impossible: commons that worked. Not by accident, but by principles.

If Wurman taught us to organize information, Ostrom will teach us to organize people.

* * *

Previous articles, the preface, the introduction, and full documentation are available here:

[https://codeberg.org/openarchy/gitgov](https://codeberg.org/openarchy/gitgov)

[https://github.com/openarchy/gitgov](https://github.com/openarchy/gitgov)

All content is fully open source and accessible to everyone. Licensed under CC BY-SA 4.0: read, share, translate, adapt, and improve — as long as you keep attribution and distribute derivatives under the same license.

If you find an error, have an idea, or want to propose an improvement, just open an issue or fork it on Codeberg or GitHub. Contributions are welcome. That’s exactly the point.

* * *

## **11\. References**

  1. GLEICK, James. **The Information: A History, a Theory, a Flood**. New York: Pantheon Books, 2011.

  2. PRESIDENTIAL COMMISSION ON THE SPACE SHUTTLE CHALLENGER ACCIDENT. **Report of the Presidential Commission on the Space Shuttle Challenger Accident**. Washington: U.S. Government Printing Office, 1986. 5 v.

  3. WURMAN, Richard Saul. **Information Anxiety**. New York: Doubleday, 1989.

  4. WURMAN, Richard Saul. **Information Anxiety 2**. Indianapolis: Que Publishing, 2001.



