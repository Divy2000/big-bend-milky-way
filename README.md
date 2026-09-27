# big-bend-milky-way

A one-page, spontaneous Big Bend trip proposal: an interactive night sky (slide the moon away to reveal the Milky Way), two trip options with honest trade-offs, a 3-day plan and a packing list.

Personalize with a query string: `index.html?name=FirstName`

## Deploy to GitHub Pages
```bash
git init && git add . && git commit -m "Big Bend Milky Way proposal"
gh repo create big-bend-milky-way --public --source=. --push
gh api -X POST repos/{owner}/big-bend-milky-way/pages -f "source[branch]=main" -f "source[path]=/"
```
