# OctopusGarage Pages

Static organization website for OctopusGarage.

## Live Site

- Website: https://octopusgarage.github.io/
- llms.txt: https://octopusgarage.github.io/llms.txt
- Full AI profile: https://octopusgarage.github.io/llms-full.txt
- Project data: https://octopusgarage.github.io/projects.json

## What This Contains

- `index.html` - public organization homepage.
- `styles.css` - lightweight responsive styling.
- `assets/octopusgarage-*.svg` - website logo and GitHub profile artwork.
- `robots.txt` - search and AI crawler policy.
- `llms.txt` - short AI-readable organization summary.
- `llms-full.txt` - long-form AI-readable organization profile.
- `projects.json` - structured public project data.
- `projects/*.md` - Markdown knowledge pages for public projects.
- `sitemap.xml` - crawlable URL list.

The AI-readable files are intentionally available at stable URLs but are not listed in the visible homepage navigation. Private and archived repositories are excluded from the public website and GEO files.

Project manuals own detailed product facts. Keep each project's summary consistent
across the homepage, `projects.json`, its Markdown profile and the llms exports;
link to the owning manual instead of duplicating instructions or release versions.
Mesh-Talk's manual and generated project sitemap are maintained in the Mesh-Talk
repository. Its project sitemap is advertised by this host's `robots.txt`; deploy
the project build that generates it before relying on that discovery URL. Training
and search access remain separate policies.
