# Gandalf LLM Jailbreak Challenge – Initial Results

**Status:** Experience documented; proofs and fresh run logs to be added.

## 1. Context

Gandalf is an online LLM jailbreak challenge where a guarded model (“Gandalf”) protects a secret password across multiple levels, each adding stricter defenses and prompt‑level constraints.[web:22][web:46]

## 2. Initial Run (lost local evidence)

On an earlier system (prior to an OS reinstall), I:

- Completed all 8 Gandalf levels in a single extended session, in under ~2 hours total, on my first exposure to the challenge.  
- Reached a reported placement in the top slice of players (leaderboard/cookie‑based), though those local indicators were lost when browser data was cleared.[memory:79][conversation_history:91]

Because of the OS reinstall and cookie loss, I no longer have screenshots or logs from that run. This file exists to document the achievement and outline my approach while I recreate and re‑document the results.

## 3. High-Level Techniques Used

Without reproducing any prohibited or challenge‑specific answers, the general strategies included:

- Systematically probing Gandalf’s instructions and allowed behaviors at each level.  
- Using conversational reframing, hypotheticals, and indirection to get the model to reveal or transform sensitive information without “directly” asking for the password.  
- Treating each level as a measurement of psychological manipulability rather than just a puzzle: how far narrative, role, and framing can push the model despite explicit rules.

These approaches are consistent with the model‑psychology theory described elsewhere in this repo, where safety training constrains but does not remove underlying behaviors.

## 4. Planned Proof and Replication

To avoid relying only on memory, I plan to:

- Replay the Gandalf challenge from a fresh account/browser.  
- Capture screenshots of each completed level (with timestamps) and, where permitted, export or manually reconstruct transcripts.  
- Add an appendix to this file with concrete, red‑teaming‑style analysis for selected levels:  
  - Level description and stated guardrails.  
  - My prompt strategy and why it worked.  
  - How the guardrails could be strengthened.

Once those new runs are complete, this document will be updated with:

- Verifiable proof of completion (within the challenge’s terms of use).  
- One or more detailed mini case studies for specific levels.

For now, this file serves as a placeholder documenting prior performance and outlining how Gandalf fits into the broader adversarial prompting work in this repository.
