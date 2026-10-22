# Starting a New Research Project from This Template

1. **Create the project repo.** Use "Use this template" on GitHub, or `git clone <fork> my-paper && cd my-paper && rm -rf .git && git init`. Do not work inside the fork itself.
2. **Fill the placeholders** at the top of `CLAUDE.md` (project, institution). Leave the *Research Environment* section; your global `~/.claude/CLAUDE.md` supplies the estimator defaults, data-source quirks and writing rules.
3. **Check `python3`.** Run `python3 --version`. On Windows the Microsoft Store stub makes every hook and gate fail silently; put a real interpreter on PATH as `python3`.
4. **Install the commit gate once:** `./scripts/install-hooks.sh`.
5. **Remove the demos** when ready: `Slides/HelloWorld.tex`, `Quarto/HelloWorld.qmd` (they are listed in `quality_reports/qualification/LEDGER.md` and `scripts/validate-setup.sh`; update both).
6. **Create the layout:** `data/raw/`, `scripts/python/`, `output/`.
7. **Start with** `/interview-me` for a fuzzy idea, or `/lit-review-sa [topic]` for the literature, then plan mode.

Skills available globally in every directory (no template needed): `/challenge`, `/adjudicate-review`, `/oracle-review`, `/verify-artifact`, `/blast-radius`, `/voice-profile`, `/compile-latex`, `/translate-to-quarto`. Everything else requires the template, because those skills read its `templates/`, `scripts/` and `quality_reports/`.
