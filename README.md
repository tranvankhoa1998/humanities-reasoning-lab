# Humanities Reasoning Lab — MVP 0.1

A small, dependency-free Digital Humanities argument-mapping prototype, with a Vietnamese UI.

## Run locally

Open `index.html` in a modern browser. No install, backend, API key or build step needed.

## Features

- Edit research question and scope
- Create claims, premises, objections, conclusions
- Link nodes via supports / objects to / qualifies
- View argument map and list of links
- Persist locally in `localStorage`
- Import/export a case as JSON
- Example question: *Can AI have authorship?*

## Known limitations

- Graph is illustrative, not an inference engine or empirically validated cognitive model
- No account, collaboration, semantic validation, automated literature retrieval or server storage
- Graph layout becomes crowded on large cases
- External links in references are treated as text only
- Browser storage can be cleared; export regularly

## Suggested pilot

Ask 3–5 users to enter one contentious question, at least 5 claims, 3 relations, and 2 bibliographic sources. Observe clarity, correctness of relations, and which features are missing. Record evidence before expanding scope.

## Publish on GitHub Pages

Create an **empty public repository**, add `index.html` and `README.md` to its root, and enable **Settings → Pages → Deploy from a branch → main / (root)**. GitHub Pages will display the static demo after deployment finishes.

## Research integrity

Nodes and edges reflect the user's representation of arguments. They do not establish validity or truth of the underlying propositions. No scholarly citations are invented in the sample case.

License: MIT (see `LICENSE`).
