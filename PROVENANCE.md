# Provenance

This repository was split from VIVIAN-LCTL-Agent-Team-1.0.0 on 2026-10-04.
The display name is **Best Reply**; its original policy identifier is `player_best_reply`.
The policy triple and Python execution adapter were copied without modification.
The standalone runner, tests, examples and these repository documents are new.

The source package used the native compiler supplied by
`BOTTLE_ROCKET_5.0.1_VM_110K_RC`. Its source authority is frozen at 4.7.0 within
the 5.0.1 maintenance RC. `brim_ref.py` is preserved unchanged from that scaffold.

| Artifact | SHA-256 |
| --- | --- |
| `player_best_reply.lctlc` | `7645ffa4d1e20cd1b300b22ea985f1f496ebeb02888e7a240aa8f098bc6a989c` |
| `player_best_reply.brir` | `23447d00c5bf5b82e603e57a10cf1827df30143e8cd577bbe84663e357da1b1b` |
| `player_best_reply.brimg` | `a54c6c0185fd684bb45f33f105a22cfda2f2a38a592e1e8be5f715cbfc0d0db4` |
| `brim_ref.py` | `333b8bcf2c876efb6aec1373f24aa21da83e26036fecedd5bdcb99f10cae3056` |
| `runtime.py` | `04ba038237bf1416869483dfd0f37d3ae51deb486ff8305e6d32e406235343a3` |

Conceptual references used in the original team implementation:

- Giacomo Bonanno, *Game Theory* (2015), supplied PDF `1512.06808v1.pdf`:
  explicit players/actions/preferences, declared utility assumptions, and
  distinctions among strategic concepts.
- *Understanding Harness Engineering*, supplied PDF: bounded execution,
  provenance, explicit handoffs, and independent acceptance checks.
- `awesome-ai-agents-main.zip`: a catalogue of agent project descriptions,
  used as design context. AutoGen/crewAI and LangGraph informed coordination;
  Agent Argue and Quorum informed evidence/critique separation. Their code was
  not imported and these policies are not copies of those projects.

The six strategies, the coordination reward model, and the staged BRIM handoff
are implementation choices, not guarantees attributed to those references.
The original PDFs, catalogue archive, full scaffold archive, private logs,
backups, machine paths and model-training files are not redistributed here.
