# Nootropics — Evidence Map

An interactive educational map for separating **self-reported impact**, documented claims, source quality, and uncertainty across behaviors and other interventions. Community ratings are observations, not proof of effectiveness or safety.

## Explore online

[**Open the interactive evidence map**](https://luckygithub777.github.io/nootropics-evidence-map/) in a modern browser. The published experience uses the same bundled records and client-side app as this repository. No account, tracker or personal-data upload is required.

## Explore locally

From the repository root:

```bash
python -m http.server 8000
```

Open `http://127.0.0.1:8000/web/index.html`. A local HTTP server is required because the browser reads the bundled JSON files in `data/`.

Source records have citations and review dates, but their inclusion does not independently verify clinical efficacy. **No personalized medical advice, supplement dosing, safety guarantee, or substitute for professional care** is provided.

**Use and rights:** The original [LICENSE](LICENSE) reserves reuse rights; publication does not make the source open-source. [MANIFEST.sha256](MANIFEST.sha256) records the released files.
