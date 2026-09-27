# Sara Hatamleh — Portfolio

A responsive, static portfolio for Sara Hatamleh. No build step, framework, account, or API key is needed.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` inside this directory and visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a new GitHub repository and upload **the contents of this folder** to the repository root (`index.html`, `styles.css`, `script.js`, and `assets/`).
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Open the URL shown in Pages after the deployment finishes.

If using Git commands, from inside this folder:

```bash
git init
git add .
git commit -m "Add Sara portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Create the remote GitHub repository before the final two commands. Replace `YOUR-USERNAME` and `YOUR-REPO` with your values.

## Content and assets

- `index.html` — page structure and copy.
- `styles.css` — responsive visual design.
- `script.js` — mobile navigation, subtle entrance effects, and current year.
- `assets/prediction-inputs.png`, `prediction-result.png`, `model-training.png`, `model-evaluation.png` — supplied project screenshots; the first two are displayed on the page.
- `assets/customer-service-dashboard.pbix` — supplied Power BI report, linked as a download.

The LoRa project is described from Sara’s supplied LinkedIn screenshots; no implementation details beyond the reported design and presentation were assumed. Her OFFTEC AI internship, Yarmouk education, and skill list also come from those screenshots. The Power BI card uses an editorial illustration of the report, not a live rendered Power BI screenshot. Its three page descriptions were checked against the supplied `.pbix` metadata. The 87.34% figure comes from the supplied model evaluation screenshot. The project summary and two July 2026 LinkedIn Learning certifications came from the provided text. The first certificate has a credential link; a credential URL for the second was not supplied. No GitHub profile, email address, or further projects were assumed.

To update the portfolio, edit the text and URLs in `index.html`. Verify Sara's preferred public details with her before publishing.
