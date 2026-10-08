# FlyRank AI Fluency - Ardi Riyadi

Public assignment evidence for the FlyRank AI Fluency track.

## The Prompt Ladder

**Experiment date:** 8 October 2026. **Selected runs:** six independent Codex responses, V0 through V5.

The real task was to review the [Internship Progress Copilot API README](https://github.com/ardiradi/flyrank-10x-solution) against a fixed implementation and verification bundle. Each selected version adds exactly one instruction layer: table format, evidence requirements, audience, a length constraint, and final review instructions.

- [Submission PDF - 10 pages](prompt-ladder/Ardi_Riyadi_The_Prompt_Ladder.pdf): all six exact prompts, representative actual outputs, four reflection notes for each version, measured counts, and the reusable template.
- [Full report in Markdown](prompt-ladder/The_Prompt_Ladder_Report.md)
- [Reusable template](prompt-ladder/Final_Reusable_Template.txt)
- [Complete evidence ZIP](prompt-ladder/Ardi_Riyadi_The_Prompt_Ladder_Complete.zip): full unedited prompts and outputs, the four fixed source files, report, template, PDF, counts, and SHA-256 manifest.

The vague baseline prompt already produced a useful answer because the fixed context was informative. Adding an audience alone did not clearly improve the result. A 240-word cap reduced coverage; the final review instruction improved caution but retained those omissions. The recommended template removes that cap and is clearly labeled as an untested synthesis, rather than a seventh measured run.

The ZIP also preserves an excluded exploratory branch under `exploratory-*`. It combined more than one instruction layer and is not counted among the six selected runs. The corrected V3-V5 were rerun independently.

## Verification scope

The supplied command record reports that the backend capstone's `npm test` passed all six tests on 8 October 2026 (exit code 0). Those tests used deterministic local AI. They do not establish real-provider execution, production reliability, external adoption, a measured preparation-time baseline, or tenfold savings.

Every selected output is retained as generated. This is a qualitative, single-response comparison per version; an exact model identifier and fixed sampling seed were not recorded. The PDF's ten rendered pages were visually checked, and the ZIP's CRC and all 26 manifest entries were verified before publication.

This repository contains the Prompt Ladder deliverable only. It does not submit assignments to the FlyRank portal automatically.
