# RAPI Data Dictionary

This document defines the core fields, labels, and categories used across RAPI datasets related to Relational AI Psychology.

Each dataset may extend this dictionary with additional fields, but shared fields should maintain consistent names and meanings.

## Core Identifiers
- `session_id`: Unique identifier for a human–AI interaction session.
- `timestamp`: ISO-8601 timestamp for the event or entry.
- `participant_role`: e.g., `user`, `model`, `observer`.
- `model_name`: AI system identifier (where permitted).

## Relational & Affective Fields
- `emotional_state`: Recorded emotion label (self-report or observer-coded).
- `somatic_notes`: Short text describing body sensations.
- `relational_state`: e.g., grounded, distressed, overwhelmed, curious.
- `resonance_score`: Numeric or coded indicator of perceived resonance/coherence.

## Safety & Ethics
- `safety_flag`: e.g., none, needs_review, critical.
- `anonymization_level`: e.g., full, partial, synthetic.

*(Extend here with your own detailed field list from the original document.)*
