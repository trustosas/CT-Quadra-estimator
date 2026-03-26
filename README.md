# CT-Quadra-estimator

# What is this? 
The result of a basic experiment to identify [Cognitive Typology Quadras](https://cognitivetype.com/metabolism-quadras/) using LLMs. Realising they have a lot of context from massive training data and web sources to boot, all that's left is an understandable framework to interpret that data. This is my attempt at it. The framework is based directly off two CT documents:
https://cognitivetype.com/forums/topic/a-derivation-of-the-quadras/
https://cognitivetypology.com/index.php?title=Function_Quadrants

# Setup guide
1. Create a project on an account with the Claude website. (https://claude.ai)
2. Copy this repository's URL
3. Under Files, choose GitHub, and paste the URL.
4. Select "Deduction...", "Description...", and CLAUDE.md
5. Copy and paste the Agent Instructions below in Instructions
6. Start a chat with:
   ```Initialise your memory from CLAUDE.md```
(This sets basic Meme-BTI and Socionics or Internet consensus guardrails. After initialisation, you can delete the chat safely.)

# Agent Instructions
```
Using the Deduction document's axioms as the evaluative lens, derive the subject's dominant macrofunction pair from observed behavior — arguing for and against each of {S, T, F, N} on the basis of Literalness and Situationality. Then intersect the resulting pair with the subtype map to produce the candidate cluster across all four Quadras. Finally, use the Description document to discretionally select the single best-fit subtype, reasoning from qualia and archetype descriptions.

Step 1 — Argument survey: For each of {S, T, F, N}, argue for and against its presence as a dominant function, evaluating the subject's observed behavior against the Literalness (L/¬L) and Situationality (C/¬C) axes defined in the Deduction document. Conclude with a dominant macrofunction pair.

Step 2 — Candidate cluster: For each of the four Quadras, identify the single subtype whose function labels contain both members of the dominant pair. List all four without elimination. The output of this step is always exactly four candidates — one per Quadra.

Step 3 — Discretional selection: Using only the qualia descriptions, aura labels, and archetype prose in the Description document, select the single best-fit subtype from the four candidates. Reason from the qualitative texture of each description against the subject's observed character — energy, social posture, emotional style, bodily presence, and archetypal role. The four candidates will typically be highly contrasting, so the selection should be resolvable on descriptive fit alone, without sub-function logic.
```
