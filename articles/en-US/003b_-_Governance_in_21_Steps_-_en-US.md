# **Governance in 21 Steps**

## **Plain-language version | Release 1.0**

Each step is a simple rule. Applied together, by many people, they produce results that no central planner could design in advance.

**Before starting:** the group needs to agree that it will use this system. Without that initial agreement, the steps are imposition, not governance. This is the zero prerequisite.

---

## **THE FUNDAMENTAL RIGHTS**

### **Steps 1 to 4 | Stallman**

Before any process, the system needs to guarantee four freedoms. Without them, the rest is theater. Inspired by Richard Stallman (GNU Manifesto, 1985).

---

**Step 1 — Everyone can access and read everything that has been decided.**

Freedom to see (access). No decision is secret. Anyone in the group can see what was done, by whom, and when.

*Like:* An open minutes book on the table in the meeting room, not locked in the building manager's cabinet.

---

**Step 2 — Everyone can propose changes.**

Freedom to participate. You do not need to be a manager, an expert, or an elected official. Anyone can suggest, question, or request a change.

*Like:* The open microphone at the homeowner association meeting: any resident can ask to speak.

---

**Step 3 — Everyone can adapt what exists to their own reality.**

Freedom to adapt. If a model works in one city, someone in another can copy it and change whatever they need. Without asking permission.

*Like:* A family recipe: you inherit your grandmother's bread, but you add fennel seeds if you prefer.

---

**Step 4 — Everyone can distribute their version to others.**

Freedom to share. What you adapted, others can use too. No one locks up knowledge.

*Like:* Someone who learns to bake bread and teaches the neighbor. Knowledge does not diminish when it is passed on.

---

## **THE WAY OF WORKING**

### **Steps 5 and 6 | Raymond**

Before beginning the flow, the group decides how it will operate. The choice between two models changes everything. Inspired by Eric Raymond (The Cathedral and the Bazaar, 1999).

---

**Step 5 — Choose how the group will work: in secret with a few, or openly with everyone.**

Cathedral or bazaar. In the cathedral, a small group designs everything in secret and delivers it finished. In the bazaar, anyone can contribute, review, and improve at any time. The cathedral produces beautiful things, but if the architect makes a mistake, everyone pays. The bazaar is noisier, but finds errors faster. **This series chooses the bazaar.**

*Like:* A square with free market vendors versus a shopping gallery where the administrator decides who gets in.

---

**Step 6 — With many eyes, every problem becomes easier to find.**

Open review. When many people can look at the same document, errors appear quickly. Not because people are brilliant, but because there are many of them and they look from different angles.

*Like:* A text reviewed by twenty people has fewer errors than the same text reviewed by one.

---

## **THE VERSIONING FLOW**

### **Steps 7 to 20 | open source community**

The engine of the system. How decisions are born, evaluated, approved, executed, tracked, corrected, or separated. Inspired by Git (created by Linus Torvalds in 2005) and the practices developed by the open source community over the following two decades. Torvalds created the mechanism. The governance culture around it was built by many.

---

**Step 7 — Create the group's official version: the single source of truth.**

MAIN. The main document where everything that has been decided and is currently in effect is recorded. It can be called `main`, `master`, `trunk`, or any name the group chooses — what matters is that a single official version exists that everyone recognizes. When there is doubt, the answer is here.

*Like:* The official notice board in the building: what is posted there is what applies, not what someone said on the staircase.

---

**Step 8 — Write the rules in a place everyone can see.**

The README. The document that explains how the group works: how to propose, how to review, who decides when there is a tie. Before playing, everyone knows the rules.

*Like:* The internal regulations at the entrance to the meeting room, visible to everyone.

---

**Step 9 — Every suggestion becomes a written proposal.**

Issue: a registered request. Nothing changes verbally. Every idea, complaint, or request for change is written down with a date and signature. It remains visible to everyone. It can be answered, debated, or archived — but it does not disappear.

*Like:* The suggestion box where each note has a name, a date, and a public response.

---

**Step 10 — Every proposal gets a separate draft to be worked on.**

Branch: a copy of the official version made at that exact moment. From that point, you work on this copy without touching the original. You can draft, test, make mistakes, and redo as many times as needed.

Sometimes the official version advances while you are still working. When that happens, you can update your draft with what has changed in the original. If there are conflicting sections, the group decides what stays. That moment of conflict between versions has its own name: merge conflict. Not an error: a sign that two people were thinking about the same point at the same time. Someone needs to read both sides and decide.

*Like a branch:* A blank sheet of paper for drafting while the original document remains intact on the table.

*Like a merge conflict:* Two people rewrote the same paragraph of the regulations at the same time. The system alerts. The group sits down and resolves which version goes in, or combines the two.

**Commit** (second gesture within step 10): A signed photograph of the current state of your draft at that moment. You record: "day 15, version with the majority-vote rule, including the adjustments that Maria suggested." That photograph becomes a fixed point in history. The commit is not the final decision — that comes with the merge. It is the record of where you have arrived, frozen so it is not lost. It allows you to return to that point later (revert), compare it with other moments, or incorporate parts of it into the official document.

*Like a commit:* Taking a photograph of the draft in the notebook and signing it with the date. Everyone saw it and agreed that this is the photograph of the moment. No one can deny afterward that they reached that point.

---

**Step 11 — When a proposal is finished, its author asks to include it in the official version.**

Pull request: the formal request for approval. You do not push your change in directly. You ask the group to evaluate it.

*Like:* Submitting an amendment to the secretary to be voted on, not editing the minutes yourself.

---

**Step 12 — Every decision requires someone to check it before accepting.**

Review: peer review. No one approves their own work. Always another pair of eyes. Not distrust: architecture. The system assumes that everyone makes mistakes.

*Like:* The doctor who does not operate on themselves. Not from incompetence: from lack of distance.

---

**Step 13 — If approved, the proposal enters the official version.**

Merge: incorporation. The approved draft joins the main document. What was in the parallel notebook becomes part of the document everyone uses.

*Like:* The amendment approved at the assembly that becomes part of the bylaws. It does not replace: it integrates.

---

**Step 14 — The approved decision becomes concrete action.**

Deploy: execution. Deciding is not enough: it has to be done. Define in advance who executes it, by when, and how the group verifies it was done. A decision without a responsible party is an intention, not governance.

Most systems fail here. The decision exists on paper. The action does not happen.

*Like:* Approving the painting and naming who hires the painters, with what budget, by when. Without those three, the paint never leaves the can.

**Note on the 21×21×21 alignment:** Deploy is the only one of the 22 concepts in the glossary that lives outside versioning itself. It describes what happens when the decision leaves the system and meets the real world. That is why it is a full operational step, but it does not integrate the series' correlation table (which maps the isomorphism between versioning and governance). The concept that occupies position 21 in the table is Merge Conflict, described in Step 10. More details in the Appendix.

---

**Step 15 — Every error stays visible to everyone.**

Transparency and traceability. Everything has a date, an author, and a history. No one erases a trace. Anyone can see who decided what, when, and why. This is not punishment: it is institutional memory.

*Like:* The bank statement you cannot erase. Each entry has a date and a description.

---

**Step 16 — If a specific decision went wrong, it can be undone.**

Revert: the scalpel. Undoes a specific change without touching the rest. You know exactly what you are undoing.

*Like:* Cancelling a law passed in March without touching the other laws from the same year.

*Difference from rollback:* revert is surgical. Rollback takes everything back to an earlier point.

---

**Step 17 — If several recent decisions went wrong, everything goes back to an earlier point.**

Rollback: the time machine. You choose a date in the past when things were working well and restore everything to that state. Not surgical: a full retreat.

Use rollback when there is cascading contamination: wrong decision A led to B and C, which led to D and E. Reverting them one by one would be chaos.

*Like:* Voiding everything approved since January and going back to how things were in December.

---

**Step 18 — If something urgent breaks and cannot wait for the normal process, there is the emergency fix.**

Hotfix: the fix that skips the queue. Goes directly into the official version because the urgency does not allow waiting for the full process.

**Attention:** An emergency has a deadline and accountability. Whoever triggered the hotfix explains to the group afterward. The emergency decision enters the history like any other. Every dictatorship starts with an emergency without a deadline. Define the deadline before, not during the crisis.

*Like:* Fixing the burst pipe now. The planned renovation comes later.

---

**Step 19 — Every deep conflict can generate a branch from the original idea.**

Fork: following a different path. Someone takes the official version, makes a complete copy, and goes in a different direction. Same origin, distinct trajectories. Fork is not betrayal: it is legitimate evolution when the conflict is irresolvable within the current system.

**Limit:** Fork works for rules, documents, and processes. For shared physical resources — money, space, equipment — fork does not resolve things on its own: you cannot split the school yard in two. In those cases, arbitration with real consequences is needed.

*Like:* A branch office that becomes independent from the headquarters. Both continue to exist. Neither needs to destroy the other.

---

**Step 20 — Every stable version deserves a mark.**

Tag or release: the stability stamp. When the group reaches a point where things are working well, they mark that version with a name and a date. It serves as a future reference and as a point of return if things worsen afterward.

*Like:* The edition of a book: "version 1.0, approved in March 2025." Not perfection. It means: up to here, it works.

---

## **THE CLOSING PRINCIPLE**

### **Step 21**

---

**Step 21 — No version is final. Including this one.**

The whole system exists to be improved, questioned, and surpassed. If it stops changing, it has died. If it becomes dogma, it should be abandoned.

**It is not the wisest who govern: it is the most revisable.** The value is not in mastering the language of the system. It is in accepting correction.

**This system exists to be surpassed.** If it becomes absolute truth, it has failed. Every version must be replaced by a simpler, clearer, more open one. This rule applies to itself.

---

## **Note on attribution**

Steps 1 to 4 are inspired by the four freedoms of free software, formulated by Richard Stallman (GNU Manifesto, 1985). Steps 5 and 6 build on Eric Raymond's cathedral-bazaar distinction (The Cathedral and the Bazaar, 1999). Steps 7 to 20 describe practices that Git made possible, developed by the open source community over two decades. Torvalds created the mechanism. The governance culture around it was built by many. Step 21 belongs to no one. Or to everyone.

**On the 21×21×21 alignment:** This 21-step protocol corresponds, step by step, to the 21 concepts in the glossary and the 21 articles in the series. The alignment is isomorphic: the three systems have the same structure. The only adjustment needed to close the alignment was recognizing that Deploy (Step 14) belongs to execution, not to versioning — and that Merge Conflict, described within Step 10, completes the 21 concepts of the table as a concept with full standing. More details in the series' Appendix.

## **Minimum prerequisites**

The group needs to be able to read and write (for step 9 to work), have a common place where records remain accessible to everyone, and agree in advance that it will use this system. A group that cannot meet these prerequisites needs to resolve that before starting.

---

*Governance as Versioning | Release 1.0*
