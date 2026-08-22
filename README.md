# Memory Vending Machine

> A machine that dispenses receipts for memories that may never have happened.

**Live exhibit:** https://jean-tmk.github.io/memory-vending-machine/

## What it is

The machine is a generative writing toy, not a memory-recovery tool. A word, age setting, distortion level, department, and machine state become ingredients for a fictional recollection with metadata, sensory details, confidence, and a printable archival receipt.

## What a visitor can do

1. Insert a word or short phrase.
2. Tune the age, distortion, warmth, and department controls.
3. Pull the lever to vend a memory.
4. Use the secondary controls, sound toggle, and archive to inspect or save results.

## How it works

- Python contains the canonical vocabulary, deterministic seed logic, memory compositor, distortion rules, receipt metadata, archive behavior, and browser-runtime template.
- Running the generator rebuilds the static JavaScript runtime and JSON catalogue.
- The browser page provides the machine controls, synthesized sound, receipt rendering, and local archive without an API.

## Repository map

| Path | What it does |
|---|---|
| `.gitattributes` | GitHub Linguist classification rules for the documented language composition. |
| `.github/workflows/pages.yml` | GitHub Actions workflow that validates, builds, and/or deploys the exhibit. |
| `generate.py` | Domain, engine, tooling, or specification source in the repository’s polyglot architecture. |
| `index.html` | The deployable HTML shell: metadata, accessible structure, controls, and script/style entry points. |
| `legibility.css` | A focused style layer for this named area of the experience. |
| `machine-image.css` | A focused style layer for this named area of the experience. |
| `machine.css` | A focused style layer for this named area of the experience. |
| `memory-data.json` | Structured data or generated report consumed by the project or its audits. |
| `redesign.css` | A focused style layer for this named area of the experience. |
| `runtime.js` | The checked-in browser runtime used by the static deployment. |
| `assets/` | 1 production illustration/icon files loaded by the live interface. |
| `polyglot/` | 59 isolated language-atlas files plus the majority registry and manifest; these never load in the visible frontend. |

## Languages and why they are here

Percentages below are calculated from the byte counts currently returned by GitHub Linguist. Tiny language-atlas modules are intentionally isolated from the production frontend.

| Language | GitHub | Role |
|---|---:|---|
| Python | 88.3% | the majority generator, catalogue, and runtime compiler |
| HTML | 2.3% | the static machine shell |
| Assembly | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| C++ | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| BrighterScript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Propeller Spin | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Fortran | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| JetBrains MPS | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Objective-C++ | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| SystemVerilog | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| AppleScript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Classic ASP | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| SourcePawn | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| TypeScript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| MAXScript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Redscript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| AMPL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Portugol | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Futhark | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| LabVIEW | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Nemerle | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Carbon | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Cython | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| EdgeQL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Racket | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Scenic | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Bicep | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Brainfuck | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| COBOL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Dhall | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Logos | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| MeTTa | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| PLSQL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Slang | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| UnrealScript | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| AIDL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Hurl | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Imba | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Noir | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Pawn | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Ruby | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Shell | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Yacc | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| Ada | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| FreeBASIC | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| GSC | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| HCL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| JCL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| KRL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| VCL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| WDL | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| F# | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |
| XC | 0.2% | an isolated language-atlas adapter used to broaden the comparative polyglot collection without changing the exhibit UI |

### About the language atlas

Where present, `polyglot/language-atlas.json` is the machine-readable index of the languages assigned to this repository. `polyglot/languages/` contains one small, independent signature module per assignment, and `polyglot/majority/` contains the larger registry that preserves the intended majority language. These files are documentation and comparative code specimens: the live site does not download or execute them.

## Local development

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` unless the framework development server prints a different local address.

## Privacy and access

- No sign-in is required.
- No API key is required for the live exhibit.
- No visitor text is sent to an AI service.
- Any saved progress stays in local browser storage unless the README explicitly describes an optional external architecture.
- Sound begins only after a user gesture where browser autoplay rules require it.

## Deployment

The public version is a static GitHub Pages deployment. The workflow in `.github/workflows/` is the source of truth for its exact build and publish steps. The favicon is stored with the deployed app so browser tabs and bookmarks use the project’s own mark.
