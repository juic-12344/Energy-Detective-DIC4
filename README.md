# Energy Detective — DIC4 IEEE Conference Draft

Independent DIC4 course assignment based on the Energy Detective DIC3 proposal. The DIC3 repository is not part of this project and remains unchanged.

## Deliverables

- [IEEE conference paper (LaTeX)](paper/main.tex) — [build instructions](paper/README.md)
- [DIC4 research workflow / Myplan](myplan/DIC4-plan.md)
- [OpenSpec change](openspec/changes/draft-conference-paper/) — proposal, design, requirements, tasks
- [Compiled IEEE PDF](deliverables/Energy_Detective_DIC4_IEEE_Draft.pdf)
- [Overleaf import ZIP](deliverables/Energy_Detective_DIC4_Overleaf.zip)

## OpenSpec

```bash
npm install -g @fission-ai/openspec@2.2.0
openspec status --change draft-conference-paper
openspec validate draft-conference-paper --strict
```

## Status

Four-page IEEE conference draft compiled locally; strict OpenSpec validation passed. Experiments remain planned, not performed. This is the independent DIC4 repository. Overleaf project import and author-name confirmation are pending. The manuscript was prepared from DIC3 sources retrieved through GitHub MCP.

## Research provenance

[DIC3 source snapshot](https://github.com/juic-12344/Energy-Detective-DIC3/tree/42fc6d7940a93bf856fa35193ac756c2c1778178). The DIC4 manuscript coherently restates this research design without modifying it.
