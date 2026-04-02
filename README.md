# T2I-BiasBench

T2I-BiasBench is a project website and evaluation artifact set for:

**"T2I-BiasBench: A Multi-Metric Framework for Auditing Demographic and Cultural Bias in Text-to-Image Models."**

## Website

Main page: `index.html`

Current website uses:
- project metadata + abstract from the draft paper
- framework figure from `assests/framework.png`
- curated web-safe result figures from `assests/image/web/`
- placeholder top buttons: `arXiv`, `Code`, `Benchmark Portal`, `Video`, `PPT`

## Repository Layout

- `index.html` - main project page
- `assests/framework.png` - framework figure shown in website
- `assests/image/web/` - renamed/clean figure files used directly by the website
- `T2IBiasBench.pdf` - raw paper draft (currently local/untracked unless explicitly added)

## Run Locally

From repo root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Update Placeholder Buttons

In `index.html`, edit the `href="#"` values in the hero button block:
- `arXiv`
- `Code`
- `Benchmark Portal`
- `Video`
- `PPT`

## Deploy From GitHub (Branch-Based)

1. GitHub repo `Settings` -> `Pages`
2. Source: `Deploy from a branch`
3. Branch: `main`
4. Folder: `/ (root)`
5. Save

## Notes

- The project currently keeps source/raw figure files and the web-safe copies side-by-side.
- `assests/` spelling is preserved to match existing paths in the website.
