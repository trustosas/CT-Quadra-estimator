# CT-Quadra-estimator

# What is this? 
The result of a basic experiment to identify [Cognitive Typology Quadras](https://cognitivetype.com/metabolism-quadras/) using LLMs. Realising they have a lot of context from massive training data and web sources to boot, all that's left is an understandable framework to interpret that data. This is my attempt at it. The framework is based directly off two CT documents:
https://cognitivetype.com/forums/topic/a-derivation-of-the-quadras/
https://cognitivetypology.com/index.php?title=Function_Quadrants

# Setup guide
1. Create a project on an account with the Claude website. (https://claude.ai)
2. Enable Memory in Settings > Privacy
3. Copy this repository's URL
4. Under Files, choose GitHub, and paste the URL.
5. Select "Deduction...", "Description...", and CLAUDE.md
6. Copy and paste the Agent Instructions below in Instructions
7. Start a chat with:
```
Read the CLAUDE.md file and update your memory from it
```
(This sets basic Meme-BTI and Socionics or Internet consensus guardrails. After initialisation, you can delete the chat safely.)

NOTE: Sonnet with Extended Thinking produces the best results on the free tier.

# Agent Instructions
```
Step 1 — Argument survey: For each of {S, T, F, N}, argue for and against its presence as a dominant function, evaluating the subject's observed behavior against the Literalness (L/¬L) and Situationality (C/¬C) axes defined in the Deduction document. Conclude with a dominant macrofunction pair.

Step 2 — Candidate cluster: For each of the four Quadras, identify the single subtype whose function labels contain both members of the dominant pair. List all four without elimination. The output of this step is always exactly four candidates — one per Quadra.

Step 3 — Discretional selection:

Stage 3a — J-axis cut: Determine whether the character's evaluative energy proceeds from within the self outward (Radial/Fi-Te: Gamma or Delta), or is organized by an object, cause, or ideal that sits beyond the self (Gravitic/Fe-Ti: Alpha or Beta). This halves the candidate cluster to two.

Stage 3b — P-axis cut: From the two surviving candidates, use only the qualia descriptions, aura labels, and archetype prose in the Description document to select the single best-fit subtype. Reason from the qualitative texture of each description against the subject's observed character — energy, social posture, emotional style, bodily presence, and archetypal role.
```
