# James Dye

### AI-native systems builder · GIS, field operations, data pipelines, and evidence systems

[Portfolio](https://www.xyflowinnovations.com/portfolio) · [LinkedIn](https://www.linkedin.com/in/xyflow/) · [Email](mailto:founder@xyflowinnovations.com) · Columbus, Ohio / remote

I turn unfamiliar, messy workflows into explicit rules, working software, and evidence that the software behaves correctly. AI writes a substantial share of the implementation. I own the problem framing, architecture, decomposition, acceptance criteria, adversarial review, and release decisions.

## Start with working proof

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://sourcedeck.vercel.app"><img src="https://www.xyflowinnovations.com/media/sourcedeck-command-center.png" alt="SourceDeck evidence command center" width="100%"></a>
      <h3>SourceDeck</h3>
      A deployed React/TypeScript evidence system for turning PDFs, DOCX files, and notes into source-chained quotes and fail-closed evidence packets. Its published gauntlet passes 63 hostile-input cases covering prompt injection, citation integrity, redaction leaks, and packet tampering.
      <br><br>
      <a href="https://sourcedeck.vercel.app"><strong>Live demo</strong></a> · <a href="https://github.com/Xyloth/SourceDeck">code</a> · <a href="https://github.com/Xyloth/SourceDeck/actions/workflows/ci.yml">CI</a> · <a href="https://github.com/Xyloth/SourceDeck/blob/main/TRUST_MODEL.md">trust model and honest limits</a> · <a href="https://github.com/Xyloth/SourceDeck/blob/main/reports/source-gauntlet-report.md">63-case report</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://xyloth.github.io/dosekeeper/"><img src="https://raw.githubusercontent.com/Xyloth/dosekeeper/main/docs/screenshots/caregiver.png" alt="DoseKeeper caregiver view" width="100%"></a>
      <h3>DoseKeeper</h3>
      A live Flutter/Riverpod care-coordination demo in which Patient, Caregiver, and Provider views share one state graph. Deterministic time, local persistence, correction flows, widget tests, CI, and web/Windows release builds make the behavior inspectable rather than implied.
      <br><br>
      <a href="https://xyloth.github.io/dosekeeper/"><strong>Live demo</strong></a> · <a href="https://github.com/Xyloth/dosekeeper">code</a> · <a href="https://github.com/Xyloth/dosekeeper/actions/workflows/ci.yml">CI</a> · <a href="https://github.com/Xyloth/dosekeeper/blob/main/DESIGN.md">design decisions</a>
    </td>
  </tr>
</table>

## More public engineering evidence

**[GNSS Clock Pipeline](https://github.com/Xyloth/gnss-clock-pipeline)** — Python ETL for four satellite constellations and space-weather feeds, with RINEX parsing, validated Arrow/Parquet schemas, partitioned outputs, fixtures, tests, and CI. The most important artifact is the [results writeup](https://github.com/Xyloth/gnss-clock-pipeline/blob/main/docs/results.md): the ML objective did not become operationally useful, and the repository explains why instead of hiding it.

**[Generation Engine](https://github.com/Xyloth/Generation-Engine)** — local-first Windows writing and research software with a Python standard-library backend, vanilla-JS frontend, Electron shell, file-led storage, SSE streaming, multiple model backends, portable packaging, and source-state gates for nonfiction. Its [engineering notes](https://github.com/Xyloth/Generation-Engine#engineering-notes) document both the architecture and the abandoned autonomy approach that produced worse writing.

**[Attractor Observatory](https://github.com/Xyloth/Attractor-Observatory)** — a public AI-collaboration and research-control-room artifact: agent roles, task-estimation telemetry, doctrine derived from failures, audit logs, reproducibility evidence, and a Streamlit observability surface. The repository explicitly separates its shipped public runtime from privately held scientific engines.

**[ChirpWise](https://github.com/Xyloth/ChirpWise)** — an offline Android bird-call trainer and Python data pipeline covering 1,084 species and 1,114 clips. It includes local progress, quiz flows, per-recording provenance, tests, screenshots, and a row-level licensing audit that clearly blocks a commercial release until replacement audio is secured.

## How I use AI without outsourcing accountability

1. Turn the real workflow into states, invariants, inputs, outputs, and failure rules.
2. Split the work across architect, builder, reviewer, and red-team roles.
3. Inspect the resulting code and trace how state and data move through the system.
4. Write deterministic tests and adversarial gauntlets around the claims that matter.
5. Publish the limits, failed approaches, and release boundary alongside the demo.

That process shows up repeatedly across healthcare coordination, document evidence, GNSS data engineering, field surveying, desktop software, mobile training, and research tooling. The domain changes; the operating discipline does not.

## Repository visibility

This account currently contains **29 repositories: 10 public and inspectable here, plus 19 private product, competition, and internal-tool repositories**. I do not present the private repositories as public proof. They include a near-launch survey-field app, a C++/.NET camera-SDK integration, a Unity Editor QA tool, and a seven-product local-first operations suite; I can walk through the relevant work when appropriate.

## What I am looking for

I am pursuing software, applied-AI, AI QA/evaluation, implementation, and geospatial-technology work where fast domain learning, system judgment, and accountable delivery matter. My path is nontraditional, so I prefer to be evaluated through a working artifact, architecture discussion, debugging exercise, or practical build.

**Contact:** [founder@xyflowinnovations.com](mailto:founder@xyflowinnovations.com) · [LinkedIn](https://www.linkedin.com/in/xyflow/) · [portfolio](https://www.xyflowinnovations.com/portfolio)
