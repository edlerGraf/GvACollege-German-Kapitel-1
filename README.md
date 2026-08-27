# Graf von Anderson's College German – Kapitel 1, Übungen online

Three browser exercises that continue the book's Exercises A–D:

- **E · Richtig!** – replace the noun with its pronoun, typed, with scoring.
- **F · Am Hof des Grafen** – du / ihr / Sie and the matching form of *sein*.
- **G · Die verlorene Nachricht** – write a scene, hand over the pronoun-only version, see what survives.

One file, no dependencies, no build step.

## Publishing on GitHub Pages

1. Put `index.html` in the root of the repository (or in a `docs/` folder).
2. Settings → Pages → Source: *Deploy from a branch*, choose the branch and the root (or `/docs`).
3. The page appears at `https://<user>.github.io/<repo>/`.

## Editing the content

Everything lives near the top of the `<script>` block in `index.html`:

- `NOUNS` – the Exercise B vocabulary with gender, plural, and a `tricky` flag (worth two points in E).
- `ADJ` – the Exercise C adjectives.
- `E_POOL` – the sentences for Exercise E (noun, plural?, adjective).
- `SITUATIONS` and `ROLES` – the encounters and role cards for Exercise F.
