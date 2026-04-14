# **Glossary**

## **Governance as Versioning | Release 1.0**

Each term is defined in plain language, with a concrete analogy and a reference to the corresponding step in the 21 Steps. If you come across one of these terms in any article in the series and cannot remember what it means, look it up here.

This glossary has 22 entries. Twenty-one form the series' correlation table (21 concepts × 21 steps × 21 articles). One, Deploy, sits outside the table for a reason explained in its own entry: it belongs to execution, not to versioning.

---

### **1. Access (freedom 0)**

**Step 1**

The right to see. Anyone can read everything that has been decided, without needing to ask anyone's permission.

*Like:* The minutes book on the table in the meeting room, not locked in the building manager's cabinet.

---

### **2. Participation (freedom 1)**

**Step 2**

The right to propose. Anyone can suggest changes, without needing to be elected or appointed.

*Like:* The open microphone at the homeowner association meeting. Any resident can ask to speak.

---

### **3. Adaptation (freedom 2)**

**Step 3**

The right to adjust. You can take what exists and modify it to fit your reality, without asking permission.

*Like:* The family recipe you inherit and season your own way.

---

### **4. Distribution (freedom 3)**

**Step 4**

The right to pass it on. What you adapted, others can use too. No one locks up knowledge.

*Like:* Someone who learns to bake bread and teaches the neighbor. Knowledge does not diminish when it is passed on.

---

### **5. Cathedral**

**Step 5**

A way of working where a small group designs everything in secret and delivers it finished, like an architect who draws the entire building before showing it to anyone. No one from outside sees, suggests, or corrects anything until the product is "complete."

The problem: if the architect made an important mistake, everyone is already committed to the finished work. Costly errors appear late.

*Like:* A building where the manager hires the renovation company, negotiates the price, and signs the contract — and the residents only find out when the bill arrives.

---

### **6. Bazaar**

**Step 6**

A way of working where anyone can contribute, review, and improve at any time, like an open market where each vendor sets up their stall, any customer can comment, and the whole square sees what is happening.

It is noisier. But errors appear faster, because many eyes look from different angles. It is not chaos: it is a square with clear rules about who can propose and how proposals are evaluated.

This series chooses the bazaar.

*Like:* An open assembly where any resident can propose, anyone can comment, and the final decision is recorded for everyone to see.

---

### **7. MAIN (main branch)**

**Step 7**

The official version. The main document where everything that has been decided and is currently in effect is recorded. When there is doubt about what is official, the answer is here.

**A note on names:** In software projects, this version may be called `main`, `master`, `trunk`, or any other name the group chooses. `main` is the most widely accepted convention today, after a gradual migration process that began around 2020. The name does not matter: what matters is that there is a single official version, with a clear name, that everyone recognizes as the source of truth.

*Like:* The official notice board in the building: what is posted there is what applies, not what someone said on the staircase.

---

### **8. README**

**Step 8**

The house manual. The document that explains how the group works: how to propose, how to review, who decides when there is a tie, what the limits are on what can be changed.

*Like:* The internal regulations posted at the entrance to the meeting room, visible to everyone, before any meeting begins.

---

### **9. Issue**

**Step 9**

A written proposal. Every idea, complaint, or request for change becomes a text with a date and a signature. Nothing changes verbally. The issue stays visible to everyone and can be answered, debated, or archived — but it does not disappear.

*Like:* The suggestion box where each note has a name, a date, and a public response.

---

### **10. Branch**

**Step 10**

A copy of the official version (MAIN) made at that exact moment. From that point, you work on the copy without touching the original — you can draft, test, make mistakes, and redo as many times as needed. The original remains intact.

Sometimes the official version advances while you are still working on your draft. When that happens, you can update your copy with what has changed in the original — it is like asking someone to catch you up on what you missed while you were away, and incorporating that into your work. If there are conflicting sections, the group decides what stays.

*Like:* A blank sheet of paper for drafting while the original document stays intact on the table.

---

### **11. Commit**

**Step 10 — second gesture**

A signed photograph of the current state of your draft at that moment. You record: "day 15, version with the majority-vote rule, including the adjustments that Maria suggested." That photograph becomes a fixed point in history.

The commit is not the final decision — that comes with the merge. It is the record of where you have arrived, frozen so it is not lost. It allows you to return to that point later (revert), compare it with other moments, or incorporate parts of it into the official document (merge).

In practice: the meeting ended, you wrote the current version of the proposal in the team's notebook with those changes, everyone saw it and signed it confirming that this is the photograph of the moment. No one can deny afterward that they reached that point.

*Like:* Taking a photograph of the draft in the notebook and signing it with the date. Not the published book. The record of where the work stood at that instant.

**A note on Step 10:** Branch and Commit are two gestures within the same operational step. Branch is opening the draft. Commit is taking the signed photograph of the point you have reached. In the series' correlation table (21×21×21), both gestures share the same step and the same reference article. There is no conflict: the step describes the complete workflow of working in draft.

---

### **12. Pull request**

**Step 11**

The formal request for approval. You do not push your change directly into the official document: you ask the group to evaluate what you did in your draft before anything is incorporated.

*Like:* Submitting an amendment to the secretary to be voted on, not editing the minutes yourself.

---

### **13. Review**

**Step 12**

Peer review. No one approves their own work. Always another pair of eyes. Not distrust: architecture. The system assumes that everyone makes mistakes, and that someone on the outside sees what someone on the inside no longer sees.

*Like:* The doctor who does not operate on themselves. Not from incompetence: from lack of distance.

---

### **14. Merge**

**Step 13**

Incorporation. The approved draft enters the official version. The approval process is complete. What was in the parallel notebook becomes part of the document everyone uses.

*Like:* The amendment approved at the assembly that becomes part of the bylaws. It does not replace the bylaws: it integrates.

---

### **15. Transparency / Audit trail**

**Step 15**

The permanent record. Everything has a date, an author, and a history. Nothing is erased. Anyone can see who decided what, when, and why.

*Like:* The bank statement you cannot erase. Each entry has a date and a description. Not to punish: to know.

---

### **16. Revert**

**Step 16**

The scalpel. Undoes a specific decision without touching the others. You know exactly what you are undoing.

*Like:* Cancelling a law passed in March without touching the other laws from the same year. The scalpel operates where you point it.

Difference from rollback: revert is surgical. Rollback takes everything back.

---

### **17. Rollback**

**Step 17**

The time machine. Restores everything to how it was at a specific date. Used when several cascading decisions went wrong and undoing them one by one would be chaos.

*Like:* Voiding everything approved since January and going back to how things were in December.

Difference from revert: revert undoes one thing. Rollback takes everything back to an earlier point.

---

### **18. Hotfix**

**Step 18**

The emergency fix. Goes directly into the official version without going through the normal process, because the urgency does not allow waiting.

**Attention:** An emergency has a deadline and accountability. Whoever triggered the hotfix explains to the group afterward. The emergency decision enters the history like any other. Every dictatorship starts with an emergency without a deadline. Define the deadline before, not during the crisis.

*Like:* Fixing the burst pipe now. The planned renovation comes later.

---

### **19. Fork**

**Step 19**

The branch. Someone takes the official version, makes a complete copy, and follows a different path from that point on. Same origin, different directions. Not a betrayal: the recognition that the conflict is irresolvable within the current system.

**Important limit:** Fork works for rules, documents, and processes. For shared physical resources — money, space, equipment — fork does not resolve things on its own: you cannot split the school yard in two. In those cases, arbitration with real consequences is needed.

*Like:* A branch office that becomes independent from the headquarters. Both continue to exist. Neither needs to destroy the other.

---

### **20. Tag / Release**

**Step 20**

The stability stamp. When the group reaches a point where things are working well, they mark that version with a name and a date. It serves as a future reference and as a point of return if things worsen afterward.

*Like:* The edition of a book: "version 1.0, approved in March 2025." Not perfection. It means: up to here, it works.

---

### **21. Merge Conflict**

**Step 10 — specific situation**

The moment when two different drafts made changes to the same section of the official document and the system cannot decide on its own which version stays. Not an error: a sign that two people were thinking about the same problem at the same time. Someone needs to read both sides and decide.

*Like:* Two people rewrote the same paragraph of the regulations at the same time. The system alerts: "there is a conflict here." The group sits down and resolves which version goes in, or combines the two.

**Note:** Merge Conflict arises during work on the Branch (Step 10) and is resolved before the Pull Request (Step 11). It is a situation, not a separate step. It integrates the 21×21×21 table as concept number 21.

---

### **Deploy (outside the 21×21×21 table)**

**Step 14**

Execution. The approved decision becomes concrete action. It needs a name (who does it), a deadline (by when), and a verification criterion (how the group confirms it was done). A decision without a responsible party is an intention, not governance.

*Like:* Approving the painting of the hallway and naming who hires the painters, with what budget, by when. Without those three, the paint never leaves the can.

**Why Deploy sits outside the table:** Deploy describes what happens when the decision leaves the versioning system and meets the real world — who executes it, with what deadline, how it is verified. It is a necessary operational concept in practice, but it does not belong to versioning itself: it belongs to execution. All the other 21 concepts describe operations within the record-keeping system. Deploy describes what comes after. That is why it is part of the 21 Steps protocol (which is operational) but not part of the correlation table (which maps the isomorphism between the versioning system and the governance system). The table closes at 21×21×21. Deploy remains in the glossary and the protocol as a concept with full standing.

---

## **Final note**

This glossary has 22 entries. Twenty-one form the correlation table with the 21 steps and the 21 articles of the series. One, Deploy, sustains the operational protocol without integrating the table. The three systems — concepts, steps, articles — are isomorphic: not merely similar, but structurally equivalent. That equivalence is documented in the series' Appendix.

---

*Governance as Versioning | Release 1.0*
