# SEO-Organic-
Brochure where I include all my tobacco selling websites for SEO and advertising.

Blog static în română ("Ghidul Tutunului"): `index.html`, `despre.html`, 13 articole în `articole/`, stiluri în `css/style.css`, plus `sitemap.xml` și `robots.txt`. Conținut informativ, doar 18+.

## Structură
- `index.html` — lista de articole; `despre.html` — cine operează blogul
- `magazine.html` — pagina „Magazinele noastre” (singurul link din footer către magazine)
- `articole/` — cele 13 articole; maximum un link către un magazin per articol, cu anchor descriptiv
- `css/style.css`, `sitemap.xml`, `robots.txt`; `.claude/agents/` — agenții folosiți pentru redactare și verificare

## Publicare pe GitHub Pages
1. Pe GitHub, deschide repo-ul, apoi **Settings > Pages**.
2. La **Build and deployment** alege **Source: Deploy from a branch**.
3. Selectează branch-ul **main** și folderul **/ (root)**, apoi **Save**.
4. După 1-2 minute site-ul este la https://xlaalx87.github.io/SEO-Organic-/

## Domeniu propriu
Dacă folosești un domeniu custom, înlocuiește baza `https://xlaalx87.github.io/SEO-Organic-/` cu noul URL în: `<link rel="canonical">`, `og:url` (index, despre și articole), `sitemap.xml` și linia `Sitemap:` din `robots.txt`. Exemplu: `grep -rl "xlaalx87.github.io/SEO-Organic-" . | xargs sed -i 's#https://xlaalx87.github.io/SEO-Organic-/#https://domeniul-tau.ro/#g'`
