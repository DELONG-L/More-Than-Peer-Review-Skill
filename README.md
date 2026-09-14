# More Than Peer Review

More Than Peer Review is a local Codex skill for producing focused academic peer
reviews from PDF or DOCX manuscripts.

The private analysis may scan the whole paper. The final review does something more
selective. It identifies one review thesis and normally one or two decisive faults in
the motivation, design, algorithm, system model, or claim mechanism. It then develops
at least three and normally four connected comments from those roots. The comments
need not be independent.

Candidate findings are first rated privately from P0 to P3. Fatal P0 or P1-high
failures receive sustained treatment. Remediable P1-low or P2 issues receive concrete
repair advice and are not stretched into artificial fatal flaws. Recommendation
thresholds are then calibrated to a supplied journal quartile or conference CORE
rank, while technical severity and professional tone remain unchanged.

The prose stage supports reviewer-authored attacks and counterexamples, uneven point
lengths, direct questions, and restrained first person. It rejects page and line
locators, em dashes, semicolons, and colons in the submission prose.

Bundled utilities perform local document preflight, workspace initialization,
claim-evidence checks, statistical and reproducibility audits, scaffold generation,
and final structure validation. They make no network or model calls.

## Install

```bash
git clone https://github.com/DELONG-L/More-Than-Peer-Review-Skill.git
cd More-Than-Peer-Review-Skill
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
ln -s "$(pwd)/more-than-peer-review" \
  "${CODEX_HOME:-$HOME/.codex}/skills/more-than-peer-review"
```

Then invoke it with:

```text
Use $more-than-peer-review to review this manuscript.
```

## Requirements and tests

- Python 3.11 or later
- Recommended PDF tools include `qpdf`, Poppler, and Tesseract

```bash
python3 -m unittest discover -s tests -v
python3 -m py_compile more-than-peer-review/scripts/*.py tests/*.py
```

Use synthetic fixtures only. Never commit manuscripts, review text, security reports,
credentials, venue correspondence, or reviewer identity.

## License

MIT. See [LICENSE](LICENSE) and [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
