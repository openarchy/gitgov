[![](https://substackcdn.com/image/fetch/$s_!ndzo!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F21dddcae-c07d-4cee-b4be-062e790f884a_2500x2500.png)](https://substackcdn.com/image/fetch/$s_!ndzo!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F21dddcae-c07d-4cee-b4be-062e790f884a_2500x2500.png)

At age 32, Claude Shannon measured something nobody had measured before: information. Not as a concept. As a number. Shannon proved this with mathematics in 1948. This article explains the difference between data, information, and noise.

* * *

### **The man who weighed an idea.**

#### **Article 05 of 21 of the "Governance as Versioning" series.**

* * *

_This is Article 05 of the series. The thinker: Claude Shannon. The central Git concept: Branch + Commit (Step 10 of the 21 Steps). Shannon answers a question the previous four articles left open: what exactly is the information that flows through decentralized governance systems? His answer is precise enough to measure._

* * *

**What you’ll find here.**

Have you ever sat through a meeting where everyone talked a lot and no one quite knew what had been decided by the end? Or received a ten-page report that changed nothing you already knew?

Shannon would have said, “Those meetings and those reports contained no information.” They were well-formatted noises.

* * *

## **1\. Where it all begins.**

New Jersey, July 1948. A 32-year-old engineer, lean, long-faced, delivers a 55-page article to the Bell System Technical Journal. The title is dry: “A Mathematical Theory of Communication.” No manifesto. Equations, graphs, diagrams.

Shannon was not a politician, philosopher, or activist. He was the kind of person who rode a unicycle through the Bell Labs hallways while juggling. He built a chess-playing machine at a time when almost no one knew what a computer was. He invented a box with a button: you switch it on, a mechanical hand comes out, turns the switch off, and retreats. The most useless toy in the world, built by one of the century’s most useful minds.

Those 55 pages did something no one had managed before: turn information—something vague, subjective, philosophical—into a number—something concrete, measurable, objective. Before Shannon, information was conversation. After Shannon, it was mathematics. And what can be measured can be compressed, transmitted, copied, protected, and corrected.

Together, Shannon and journalist James Gleick (who told this story in the 2011 book _The Information answers_ a question the previous four articles left hanging: Locke spoke of consent, Popper of correction, Hayek of dispersed knowledge, and Mises of spontaneous order. But what exactly is the information that flows through those systems?

Shannon gave the answer.

* * *

## **2\. Historical context**

In 1948, the world was trying to rebuild. The Cold War was beginning. The practical problem consuming engineers was simple to state and brutal to solve: How do you send messages through channels full of noise without them arriving illegible?

The telephone had existed since 1876. Radio since 1895. But no one had a general theory of communication. There was no precise definition of information. No way to measure how much information a message carried. No formula to know whether error-free transmission was even possible.

Shannon solved all three problems in a single article.

* * *

## **3\. The central idea**

Shannon’s thesis fits in one sentence that sounds simple and is devastating: information is what reduces uncertainty.

Consider this. You’re waiting for the result of a medical test. The phone rings. If the doctor says “your test came back normal,” and you already expected that (95% chance everything was fine), the message carries little information. You already knew. If the doctor says “we found something” and you weren’t expecting it, the message carries a great deal of information. It changed your state of knowledge.

Shannon’s insight: information has nothing to do with meaning. It has to do with surprise. A message that tells you what you already know contains no information, however eloquent. A message that changes what you do contains a great deal, even if it’s a single number.

Before Shannon, “information” was a synonym for data, knowledge, and opinion. Everything lumped together. After Shannon, those things separated. Data are raw material. Information is what reduces uncertainty. Knowledge is processed information. An opinion may contain no information at all (if it repeats what everyone already knows, it’s noise).

Shannon created a unit of measure: the bit (short for binary digit). One bit is the amount of information you gain when you receive the answer to a question with two equally likely options. Heads or tails? The coin result gives you 1 bit. Every file on your phone is measured in bits. Every video call, every photo, every bank transaction. Shannon gave the digital world its fundamental unit.

* * *

## **4\. Developments**

### **Surprise has a formula.**

Shannon borrowed from physics a concept called entropy (which measures disorder in a system) and applied it to communication. Informational entropy measures how much surprise a message carries. The more unpredictable, the more entropy, the more information.

Example: The sentence “The sun rose today” has low entropy. You expected it. The sentence “the sun did not rise today” has extremely high entropy. You did not expect it. The second sentence carries more information, even though it’s absurd.

Gleick, in the 2011 book, shows that this principle extends far beyond engineering. African drums transmitted messages across miles using built-in redundancy to compensate for noise. DNA stores instructions in four chemical “letters,” with error-correction mechanisms. Shannon did not invent information. He discovered that everything that transmits or stores information follows the same rules.

Practical consequence: redundant messages can be compressed without loss. “AAAAAAAAAA” (ten letter A’s) becomes “10xA.” Did you lose information? No. You can reconstruct the original. Every ZIP file, every MP3, and every YouTube video depends on this principle.

### **Noise doesn’t kill if you know how to correct it.**

The second stroke of genius was the Shannon-Hartley theorem. Shannon proved that it is possible to transmit information with near-zero error even through channels full of noise, as long as the transmission rate stays below a limit (called the channel capacity).

It’s counterintuitive. The channel has interference. Parts of the message are lost. But Shannon showed: if you add intelligent redundancy (not dumb repetition, but error-correction codes), you can recover the original message. Not almost. Perfectly.

This is why satellites send photos of Mars without blurring. This is why you make video calls even when data packets are lost along the way. Engineers built the digital world on top of this proof: noise is inevitable, but correction is possible.

* * *

## **5\. Historical legacy**

In 1949, Shannon published a second article, “Communication Theory of Secrecy Systems,” applying his theory to cryptography. He proved that a cryptographic system is truly unbreakable only if the key is as long as the message and used only once (the so-called one-time pad).

This result is the root of all modern digital security. Every online purchase, every email, every mobile banking session depends on cryptography descended from Shannon. Public-key cryptography (RSA, 1970s) was born trying to solve the practical problem he identified: How do you distribute keys securely?

Gleick documented how information theory spread to biology (DNA as code), linguistics (redundancy in natural languages), physics (information as the universe’s basic unit, in John Wheeler’s work: “it from bit”), and economics (prices as information signals, picking up Hayek by another route). Shannon opened a door. The entire world walked through it.

Shannon died in 2001 at 84. Almost no one outside academia knew who he was.

* * *

## **6\. Contradictions and limitations**

Shannon separated information from meaning and purpose. For the theory to work, “the cat sat on the mat” and “launch the bomb” are equivalent: what matters is the probability of the symbols, not what they mean.

That is both the strength and the limit. The strength: It allows you to measure, compress, and transmit anything. The limit: it says nothing about whether information is true, useful, or ethical. A system can transmit lies with perfect efficiency.

Gleick acknowledges this tension. The information age brought abundance but also overload. More bits do not always mean more understanding. Shannon measured the quantity. No one has measured quality in a comparable way since.

* * *

## **7\. The translation into versioning**

Shannon never saw a Git repository. He died before GitHub existed. But his theory explains why versioning works as if he had written the manual.

An objection comes up here frequently: information theory is telecommunications engineering. What do bits and channels have to do with meeting minutes, city council decisions, and cooperative deliberations? The answer is that any system of collective decision-making is a communication system. A proposal is a message. Debate is a channel. A vote is decoded. A record is storage. Shannon did not theorize about phone calls. He theorized how any information moves, gets lost, and is recovered. Governance has the same problems.

**Step 10 — Branch + Commit:** Shannon defined information as what reduces uncertainty. A commit (the record of a change to the official document) is pure information in Shannon’s sense: it says what changed, when, who made it, and why. If the commit does not reduce uncertainty (a generic message like “misc adjustments”), it contains no real information. It is noise dressed up as a record. The branch (the separate track where an idea is developed before being incorporated) is Shannon’s separate channel: it allows transmission and testing without contaminating the main channel while the signal isn’t clean. You propose on the branch. It only becomes a commit on MAIN after review.

**Review is error correction.** Shannon proved that noisy channels can transmit clean information if there are correction mechanisms. Peer review is governance’s error-correction code. Each reviewer adds intelligent redundancy: a different angle, a different bias. It doesn’t eliminate all errors, but it reduces the rate to something tolerable.

**Redundancy is protection, not waste.** Shannon showed that copies protect against failure. In Git, every clone is a complete copy. If the server dies, any clone restores everything. In governance, if only one person knows how the system works, the system is fragile. If ten people hold that knowledge and the record is public, the system survives any individual departure.

**Transparency is the noise-free channel.** Shannon showed that the more you measure and correct, the better the transmission. In governance: the more transparency (everything recorded, everything visible), the easier it is to detect errors. Decisions made in private conversations that never become a record are a channel clogged with noise. Without preserved information, there is no audit, no correction.

Watchdog alert: Shannon measured quantity, not quality. A repository can have a thousand commits a day and contain no useful information. Heavy activity disguises a thin substance. Versioning needs Shannon (measure, record, transmit), but it also needs what he didn’t cover: judging whether the information is worth anything.

* * *

## **8\. Practical implication**

In 1901, Austrian physician Karl Landsteiner discovered that human blood is not all the same. Mixing blood from different people sometimes caused fatal clotting, sometimes not. Landsteiner identified the pattern: there were different types — A, B, and O — and compatibility between them followed precise rules.

Before him, a blood transfusion was a shot in the dark: sometimes it worked, sometimes it killed. Afterward, a three-bit question (What is the donor’s type? What is the recipient’s type? Are they compatible?) reduced uncertainty to near zero. Shannon would describe the mathematics of this process decades later: the amount of information in a message is inversely proportional to the probability of what it reveals. Landsteiner found the right questions—the ones that made the outcome predictable. That is exactly what information does: it collapses an enormous space of possibilities into something manageable. One good question is worth more than a thousand raw data points.

Now imagine a cooperative that stores everything on the president’s computer. The president travels. The computer breaks. Five years of decisions: gone. If that cooperative used redundancy (every member with a copy), commit as information (record what changed and why), and a noise-free channel (transparency), any member could audit any decision. The system would depend on the record, not on one person’s memory.

* * *

## **9\. Lessons learned**

Information is not what you know. It is what reduces your uncertainty. If a meeting changed nothing, it produced no information; it produced noise.

Redundancy is not waste. It is insurance against catastrophe. Distributed copies are saved.

Noise is inevitable. Correction is possible. The secret is not to avoid errors: it is to have mechanisms that detect and fix them.

More data does not mean more understanding. Volume without interpretation is an overload. The system needs filters, not just volume.

* * *

## **10\. Exploring paths and connections.**

This is the fifth article in the core series. Locke: consent. Popper: correction. Hayek: dispersal. Mises: emergence. Shannon: information measured, transmitted, protected.

Five foundations interlocked: consent, correction, dispersal, emergence, information.

But Shannon measured information as an engineer: bits, channels, probabilities. He did not ask how ideas are born, compete, and die. He did not ask why certain ideas survive for centuries while others disappear in weeks.

In 1976, a British biologist proposed a disturbing answer. Richard Dawkins suggested that ideas behave like living organisms: they are born, replicate, mutate, and compete for attention. The ones that survive are not the most true. They are the best at copying themselves. He called these units “memes,” long before the internet turned the word into a joke. The original concept had nothing funny about it.

* * *

Previous articles, the preface, the introduction, and full documentation are available here:

https://codeberg.org/openarchy/gitgov

https://github.com/openarchy/gitgov

All content is fully open source and accessible to everyone. Licensed under CC BY-SA 4.0: read, share, translate, adapt, and improve — as long as you keep attribution and distribute derivatives under the same license.

If you find an error, have an idea, or want to propose an improvement, just open an issue or fork it on Codeberg or GitHub. Contributions are welcome. That’s exactly the point.

* * *

## **11\. References**

  1. GLEICK, James. **The Information: A History, a Theory, a Flood**. New York: Pantheon Books, 2011.

  2. LANDSTEINER, Karl. Zur Kenntnis der antifermentativen, lytischen und agglutinierenden Wirkungen des Blutserums und der Lymphe. **Zentralblatt für Bakteriologie** , v. 27, p. 357-362, 1900. (No English edition available.)

  3. SHANNON, Claude E. A Mathematical Theory of Communication. **Bell System Technical Journal** , v. 27, p. 379-423; 623-656, 1948.

  4. SHANNON, Claude E. Communication Theory of Secrecy Systems. **Bell System Technical Journal** , v. 28, n. 4, p. 656-715, 1949.



