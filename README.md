# cdog2897.github.io

Static GitHub Pages site with a Terms of Service and Privacy Policy.

## Structure
- `index.html`: Home with links to legal pages
- `terms.html`: Terms of Service
- `privacy.html`: Privacy Policy
- `styles.css`: Minimal styling
- `.nojekyll`: Ensures GitHub Pages serves files without Jekyll processing

## Preview locally
```bash
cd /Users/luberdoodle/Documents/AppleDeveloper/cdog2897.github.io
python3 -m http.server 4000
# Open http://localhost:4000
```

## Deploy
Push to `main` to publish at `https://cdog2897.github.io`.
```bash
cd /Users/luberdoodle/Documents/AppleDeveloper/cdog2897.github.io
git add .
git commit -m "Add Terms and Privacy pages"
git push origin main
```

## Customize
- Update the header brand text in each HTML file.
- Edit legal text in `terms.html` and `privacy.html`. Update the “Last updated” dates.
- Adjust styles in `styles.css` as desired.