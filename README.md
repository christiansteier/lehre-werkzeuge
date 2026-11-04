# Teaching and learning with digital tools

[Deutsch](README.de.md)

Two small static web guides, served with GitHub Pages:

- **`prompts/`**: Prompting tips for students. Build a prompt from five blocks (context, role, task, format, check request), fill in templates for academic writing and exam preparation, copy the result. Nothing is stored except your language choice.
- **`werkzeuge/`**: “Goal first, then the tool”, a guide for teachers. It suggests Moodle and AI tools for seven learning goals, based on Anderson & Krathwohl and TPACK. It includes an A3 poster (PDF, German and English).

Both pages work in German and English, offline as single files, in dark mode and with a keyboard.

## Run locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Sources and updates

`werkzeuge/` is a build output. Its source (`werkzeuge.json`, `bauen.py`) lives in a separate, non-public repository. Edit it there, rebuild, and copy `werkzeuguebersicht.html` to `werkzeuge/index.html` together with both posters.

## Licence

Content: CC BY-NC-SA 4.0, Christian-Maximilian Steier, Hochschule Düsseldorf. The tool guide adapts the Moodle Tool Guide (Joyce Seitzinger, Gavin Henrick; German version by Hilgenstock, Gebauer, Hartwig; FH Düsseldorf 2013). Icons: Lucide (ISC licence).
