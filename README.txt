
CON_News - NOVA VERSAO (GitHub-ready)
Files:
- index.html (main app)
- map.html (full screen map)
- assets/style.css
- assets/app_v7_final.js (main logic)
- data/mock_data.json (sample data)
- data/rodovias.json (DNIT curated list)
- data/concessionarias.json (concessionárias with links)
- README.txt (this file)

Deploy to GitHub Pages:
1. Create a repo (e.g., CON_News_site)
2. Upload contents of the 'nova versao' folder to the repository root
3. In GitHub, Settings -> Pages -> Source: Branch: main / root
4. Wait a minute and visit https://<username>.github.io/<repo>/

Notes:
- CSV export intentionally excludes the 'link' column for security. The UI still opens sources in new tabs when available.
- Email alerts use EmailJS; fill IDs in Config modal when running the site.
- Some RSS sources may be blocked by CORS or rss2json limits; if many sources fail, consider a small server-side proxy.
