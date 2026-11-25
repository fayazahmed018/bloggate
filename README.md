# Blog Gate

A static HTML blog quality evaluator. Python evaluation runs in the browser through Pyodide, using `blog_gate.py` for the rule checks.

## Run locally

Serve the folder over HTTP:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`.

## Deploy on GitHub Pages

1. Push `index.html` and `blog_gate.py` to the `main` branch.
2. Open the repository **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Save and open the generated GitHub Pages URL.
