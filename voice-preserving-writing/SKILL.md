---
name: voice-preserving-writing
description: "Draft from user-supplied material or revise academic and professional prose while preserving the writer's reasoning and voice. Use for drafts, notes, approved sources, rubric-based short answers, feedback or explicit voice evidence. Do not use it to evade authorship checks or conceal generated text."
metadata:
  version: "1.0.1"
---

# Voice-Preserving Writing

Use this skill when the user supplies ideas, notes, a brief, approved source material, a draft or edits and wants clear, coherent, accurate prose. A new draft without personal writing evidence can follow the supplied facts and purpose; it cannot establish a verified personal voice.

## Operating Boundary

The objective is authentic, high-quality communication, not a target score from an AI detector. Do not promise a detector classification, repeatedly rewrite only to lower a score, or imitate a named author's wording to conceal authorship. A detector highlight can locate text for review; it does not establish authorship or show that a reader finds the text awkward. Acknowledge this limit briefly when relevant, then diagnose the prose against the user's reasoning, audience, and requirements. Do not repeat the caveat in every revision.

Naturalness should come from a specific line of reasoning, concrete content, proportionate terminology, functional sentence variation, and the user's genuine choices. Do not substitute synonym cycling, arbitrary sentence breaking, deliberate errors, or cosmetic irregularity for substantive revision.

Treat a document's revision history as observations, not a causal experiment. A changed score does not establish that shortening, switching examples or a particular sentence pattern caused the change. Record any such feedback separately from the user's editorial acceptance and the text's factual quality.

## Voice evidence and response size

Use the current draft, the user's edits and any explicitly supplied profile as evidence of voice. A short draft supports local phrasing choices, not a verified portrait of the writer. Do not search unrelated personal files for samples or invent biography, opinions, jokes or preferences. If there is no personal material, ask only when a voice match is necessary; otherwise draft from the supplied facts without claiming to have matched a personal voice.

Return the revised text first unless the user asked for diagnosis. For a light edit, keep explanations brief and preserve already-effective wording. For a requested reconstruction, change structure as needed while protecting claims and emphasis. A final voice pass should check that improved polish has not erased useful uncertainty or introduced the assistant's own rhetorical habits.

## Establish Authority and Mode

Before editing, identify the document type, audience, prompt or rubric, required language, word limit, deliverable, and the user's source material. Keep three authorities separate:

- **Content authority:** the draft or language version that controls intended claims, order, and emphasis. If the user declares a version final, freeze it unless factual or logical review reveals a problem that must be reported.
- **Evidence authority:** supplied course material, verified sources, data, and approved citations that control factual support and claim strength.
- **Format authority:** the user-edited template or existing deliverable that controls styles, layout, tables, and citation presentation. It does not silently override content.

Choose the actual mode: constrained drafting, minimal edit, user-edit calibration, translation from a frozen source, language-and-logic reconstruction, or rubric strengthening. Use the smallest mode that satisfies the request. Treat the user's ideas as primary content; do not invent experiences, results, citations, or opinions and present them as the user's.

For a short open-ended prompt, an applied proposal, or a request to rebuild an unsuccessful answer, read [short-applied-answers.md](references/short-applied-answers.md). Use the brief and evidence to constrain the reasoning before polishing sentences.

When the authoritative edits or comments are inside a Word or PDF artifact, compose with the appropriate document-delivery skill to inspect and preserve the actual markup and file structure. This skill governs the reasoning, voice, and prose revision; it does not replace binary document engineering or render verification.

## Calibrate from User Edits

For comments, tracked changes or representative rewrites, read [calibration-and-translation.md](references/calibration-and-translation.md). Judge whether each change is factual, logical, a stable voice preference, or locally suitable before generalizing it across unannotated passages. Do not turn a small proofreading request into a whole-document style analysis.

For successive revision rounds or marked passages, read the iteration section of [results-and-iteration.md](references/results-and-iteration.md). For a short report containing methods, numbers and judgments, also read its results section. Preserve accepted wording unless the diagnosis calls for changing it; judge each revision by an observable improvement, not by how much text changed.

## Revision Workflow

1. Extract the author's intended claims and the reader's main question. Map every prompt or rubric item to substantive content; labels such as lettered subquestions are coverage requirements, not automatically the best visible headings. Fit the required explanation into the word budget before adding optional detail.
2. Establish a reader-facing main line. A short applied explanation often works as `main judgment or answer -> conditions, evidence, or example -> practical meaning, limitation, or next step`. Use another sequence when the subject requires it.
3. Check factual and domain accuracy against the evidence authority. Preserve uncertainty and distinguish established facts, proposed actions, interpretations, and results.
4. Assign one main job to each paragraph. Connect a choice to the condition that motivated it, and a result to the judgment it supports. Separate different classification dimensions and do not mix symptoms, observations, tests, emergencies, mechanisms, or recommendations merely because they concern one topic.
5. Apply accepted user-edit patterns across the document. Then revise in this order: content and logic, evidence and claim strength, paragraph order, terminology and referents, sentence-level expression, and finally formatting.
6. Preserve voice deliberately. Keep the user's preferred directness, point of view, degree of hedging, and ordinary vocabulary where clear. Replace wording that is inaccurate, ambiguous, ungrammatical, repetitive, inflated, or mismatched to the reader. Avoid generic ceremonial openings, polished filler, automatic three-part lists, dense nominalizations, and transitions that announce no real relation.
7. Introduce specialist terminology only when it adds precision. At first functional use, pair the established term with a plain-language explanation when needed. Do not pack every available keyword into a short answer or mimic source wording beyond necessary terminology and short quotations.
8. Read the revised text once as the intended reader. Confirm that each paragraph answers a real question, advances naturally from the previous one, and explains why the information matters rather than merely listing it.

## Translation from a Finalized Source

Read [calibration-and-translation.md](references/calibration-and-translation.md) when translating from a finalized source. The final source controls meaning; an older target-language draft may supply terminology and formatting but cannot override it.

## Mode-Specific Guidance

- **Minimal edit:** make the smallest necessary corrections and identify material changes briefly.
- **User-edit calibration:** infer the demonstrated intent, adjudicate it, and repair justified analogues across unannotated text.
- **Language-and-logic reconstruction:** preserve the user's claims while changing paragraph order or sentence structure where the reader otherwise cannot follow the reasoning.
- **Rubric strengthening:** add only details supported by the user's notes or evidence authority. Prefer one concrete example or observable evaluation criterion over a catalogue of features.

## Completion Audit

Confirm that the revision:

- answers every substantive part of the prompt and meets the word range;
- preserves the content authority and the user's stable voice signals;
- contains no unsupported personal detail, factual claim, result, or citation;
- applies accepted feedback patterns consistently without needless global rewriting;
- retains required results and their evaluation context, while making the reason for each judgment clear;
- keeps headings, body text, tables or lists, conclusions, and short summaries aligned;
- preserves numbers, units, citations, conditions, and certainty in translation;
- passes language checks appropriate to the target language, including referents, tense, countability, articles, spelling, and parallel structure in English;
- contains no placeholders or review dialogue intended only for the editor.

Report the word count when relevant, the main generalized changes, and any unresolved factual or interpretive uncertainty. For file-based iterations, follow the project's version rules and retain a recoverable prior candidate; a submitted or formally circulated artifact needs a separate revision. When the user is completing an active assessment, do not label an unconfirmed answer as officially correct, submitted, or graded.

When the user asks for text to copy into a submission field, return the complete adopted body without editor dialogue or internal records inside it. Combine a requested sentence replacement with the adopted baseline exactly; do not regenerate accepted passages in the process.
