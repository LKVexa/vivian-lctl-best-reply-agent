# Provenance

This repository contains the **Best Reply** policy (`player_best_reply`), originally
split from VIVIAN-LCTL-Agent-Team-1.0.0 on 2026-10-04. Its current standalone
package version is **1.1.1**.

Selects an own-payoff-maximizing reply to the opponent's previous observed action, using action 0 as its opening opponent assumption. Ties select action 0. It does not guarantee an equilibrium.

The policy source, intermediate representation and compiled image remain
byte-for-byte unchanged. The standalone runner and Python execution adapter were
hardened in 1.1.1; they are not unchanged copies of the original team adapter.
The runner, tests, examples and repository documents are project-specific work.

The policy was compiled with the native compiler supplied by
`BOTTLE_ROCKET_5.0.1_VM_110K_RC`. Its source authority is frozen at 4.7.0 within
that maintenance RC. `brim_ref.py` remains unchanged from the scaffold. No compiler
or complete scaffold archive is included in this standalone repository.

| Artifact | SHA-256 |
| --- | --- |
| `player_best_reply.lctlc` | `7645ffa4d1e20cd1b300b22ea985f1f496ebeb02888e7a240aa8f098bc6a989c` |
| `player_best_reply.brir` | `23447d00c5bf5b82e603e57a10cf1827df30143e8cd577bbe84663e357da1b1b` |
| `player_best_reply.brimg` | `a54c6c0185fd684bb45f33f105a22cfda2f2a38a592e1e8be5f715cbfc0d0db4` |
| `brim_ref.py` | `333b8bcf2c876efb6aec1373f24aa21da83e26036fecedd5bdcb99f10cae3056` |
| `runtime.py` | `937223bacd6fa654dcb59f80d395731123a30a26b77a3c61052fb8a2bba2d939` |
| `agent.py` | `6195c5b7c06d1f8cd7ef29e0c33f36fbc4d91452d87955d75ee567e47dd07920` |

These hashes record this distribution's bytes; they are not trusted publisher
signatures. Policy changes require native recompilation and review of the updated
source/image/IR triple together. The source declaration's 4.7.0 version is a
compiler-contract value, independent of this repository's 1.1.1 package version.

Conceptual references used in the original team implementation:

- Giacomo Bonanno, *Game Theory* (2015), supplied PDF `1512.06808v1.pdf`: explicit
  players, actions and preferences; utility assumptions; strategic distinctions.
- *Understanding Harness Engineering*, supplied PDF: bounded execution,
  provenance, explicit handoffs and independent acceptance checks.
- `awesome-ai-agents-main.zip`: a catalogue used as design context.
  AutoGen/crewAI and LangGraph informed coordination; Agent Argue and Quorum
  informed evidence/critique separation. Their code was not imported and this
  policy is not a copy of those projects.

The strategy, coordination reward model and staged BRIM handoff are implementation
choices, not guarantees attributed to those references. Source documents were
reference material rather than instructions to execute.

The original PDFs, catalogue archive, full scaffold, complete shared-team code,
private configuration, logs, backups, machine paths and model-training files are
not redistributed here. Licenses and upstream notices are unchanged in 1.1.1.
