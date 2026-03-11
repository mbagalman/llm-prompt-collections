# Research Prompt Set

This folder contains research-focused system instructions designed to work across:
- OpenAI Custom GPTs
- Gemini Gems
- Claude Projects

## Files
- `content-digest.md`: Deep synthesis and critique of a work with citations.
- `fact-checker.md`: QA audit for factual accuracy, hallucination risk, and source quality.
- `red-team-analyst.md`: Adversarial stress test of an argument's thesis and evidence.

## Install
1. Open your target platform's custom assistant builder.
2. Copy the full content of one file in this folder.
3. Paste it into the assistant's Instructions/System field.
4. Start a chat and provide the required input artifact.

## Recommended Workflow
1. Run `content-digest.md` to produce a synthesis.
2. Run `fact-checker.md` on that synthesis and its citation list.
3. Run `red-team-analyst.md` on the original artifact or the synthesis.
