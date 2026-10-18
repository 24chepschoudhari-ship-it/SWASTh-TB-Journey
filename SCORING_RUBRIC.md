# TB Journey — scoring notes

The score is a small reflection feature for this fictional educational game. It is not a medical assessment, and it should not be used to judge a real patient, family member or healthcare worker.

## Points for each choice

- **3 points:** a helpful next step that supports appropriate care, clear information, privacy or follow-up.
- **2 points:** a useful step that helps, but does not address the whole situation.
- **1 point:** a limited response that leaves important questions or practical needs unresolved.
- **0 points:** a response that risks delay, unsupported diagnosis, missed follow-up, misinformation or stigma.

Each option has a score set for its specific scene in `js/game.js`. The explanation shown after the choice is meant to help the player understand the reasoning.

## Final result

The score shown at the end is the points earned divided by the maximum possible points for that run, with a percentage. The maximum is three points for each decision made, so routes with different numbers of scenes can still be compared fairly within a single run.

The feedback bands are:

- **85–100%:** helpful choices across the run.
- **70–84%:** mostly helpful choices, with a few decisions to revisit.
- **50–69%:** a mix of helpful choices and gaps worth reviewing.
- **Below 50%:** replay the story and explore another route.

The labels are supportive rather than pass/fail. A score reflects only the choices made in the game—not a person's character or what they would do in real life. In real healthcare situations, options and constraints can be more complicated.

## Review before publication

The rubric was drafted with AI assistance. The iGEM ICT Mumbai 2026 team should read the score assignments scene by scene and adjust them where the explanation and points do not align. A TB/diagnostic reviewer should check the scientific framing. Do not describe the scoring as clinically validated or as evidence that the game changes real-world behaviour.
