# Governed Chat Agent Demo

This repository demonstrates a simple but important idea:

> An AI model can generate text, but only a human can approve it.
> A governance log determines which outputs are considered valid.

## What this shows

- The same AI model can produce multiple answers
- Some answers are rejected by a human governor
- Only approved outputs are considered authoritative
- A log records decisions in a transparent, auditable way

This demonstrates:
- separation of cognition and authority
- fail-closed behavior
- tolerance of AI hallucinations without unsafe commitment

## Files

- `chat_log.txt` — the governance log showing rejected and approved outputs
- `approved_output.txt` — the approved public explanation
- `screenshots/` — visual evidence of the process running locally

No code is required to understand this demo.
