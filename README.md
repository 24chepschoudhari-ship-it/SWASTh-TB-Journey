# SWASTh-TB — The TB Journey

A small browser game by iGEM ICT Mumbai 2026 that follows three TB-related stories: a person seeking care, a healthcare worker, and a family or community member.

## What's included in this build

- The original Patient, Healthcare Worker and Family / Community journeys.
- Four choices at each story scene, with the existing branches and convergence points preserved.
- A scene-exploration counter that reflects the scenes visited in the current run. Replaying a role lets visitors explore another branch.
- A choice review panel, short explanations after each decision, and end-of-biology navigation to replay, choose another role or return home.
- A 0–3 point score for each choice. The final screen shows the points earned, maximum possible points, a percentage and a short reflection. The scoring is part of the learning game, not a judgement of the player.
- Responsive layouts, keyboard focus indicators, a skip-to-content link, reduced-motion support and improved screen-reader labels.
- English, Hindi, Marathi and Gujarati interface/navigation labels. **The story scenes themselves are currently in English**, which is stated in the role-selection screen.
- A plain-language educational disclaimer. The proposed biosensor is not presented as a clinically validated diagnostic.
- A visible WHO sources panel on the About screen; links are opened only if a player selects them.

## Run locally

Open `index.html` in a browser. No build step, package installation, external font, image library, JavaScript library or CDN is required.

## Files

- `index.html` — page structure and screens
- `css/style.css` — visual design and responsive/accessibility styles
- `js/game.js` — role-based branching logic and interactions
- `languages/content.js` — interface text in four languages
- `SOURCES.md` — scientific framing and references
- `SCORING_RUBRIC.md` — how points are assigned and how the final percentage is explained
- `AI_ASSISTANCE.md` — draft disclosure for team review
- `DEPLOYMENT.md` — deployment and final checks

## How the score works

Each option has a score set for its situation: **3** for the most helpful next step, **2** for a useful but incomplete step, **1** for a limited response, and **0** where a choice risks delay, misinformation or stigma. The score is shown after each choice and added at the end of the run. Different branches can contain different numbers of choices, so the result shows both the points earned and the maximum possible for that run.

The team should review the score assignments before publication. They are educational judgements about these fictional scenarios, not a clinical measure and not a statement that real-life situations are always simple.

## Scientific framing

The simulator is for education and reflection, not diagnosis or individual medical advice. Symptoms alone are not presented as proof of TB. The SWASTh-TB mechanism is described as a proposed research concept; an observed colour signal alone is not evidence of clinical validity.

## iGEM review and attribution

This package avoids Google-sourced images, AI-generated artwork, external fonts, external libraries and CDNs. The interface styling and accessibility updates were developed with AI assistance; see `AI_ASSISTANCE.md`. Team members should review and understand the code, verify the scientific wording, and accurately disclose AI use and all external contributions through the applicable 2026 iGEM processes. This package is a standalone GitHub Pages app, not an integrated iGEM wiki build. Do not embed it as an external iframe or load its assets from GitHub Pages into the official wiki. To run it inside the official 2026 wiki, adapt it to the official team repository and iGEM-hosted asset workflow. This package is **not a certification of full iGEM compliance**; review the current official competition rules, AI policy, attribution requirements and communication/wiki requirements before publication.

## Local checks performed for this build

- JavaScript syntax checked for the game and language files.
- All 43 story scenes across the three roles are reachable from their role's starting scene.
- All 172 choices (four per scene) point to a valid scene or to the biology pathway.
- Logic-checked all role routes, score assignments and score calculations. The first-choice route in each role reaches the biology sequence and produces the expected full score.
- The recent score-card changes still need a final visual check in a normal browser at 320, 375, 430, 768, 1024 and 1440 pixels, followed by testing on the deployed URL.

These checks do not replace the team's final content review or testing of the published GitHub Pages URL.
