# GTM Practice Website Preview

Static HTML/CSS/JavaScript website. No build step or package installation is required.

## Project structure

```text
/
├── index.html
├── assets/
│   └── work.css
└── work/
    ├── institutional-rwa-case-study.html
    ├── gtm-strategy-blueprint.html
    ├── market-intelligence-explorer.html
    └── gtm-systems-architecture.html
```

## Preview locally

Open `index.html` in a browser. The linked pages use relative paths, so keep the folder structure intact. For a local server, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Upload the complete project folder contents to the repository root. Do not upload the ZIP itself.
2. Keep `index.html` at the repository root and preserve the `assets/` and `work/` folders.
3. In repository Settings, open Pages.
4. Select Deploy from a branch, choose `main` and `/ (root)`, then save.
5. Open the Pages URL after deployment completes.

## Content and data status

- The GTM Strategy Blueprint uses a fictional B2B operations software scenario.
- The Market Intelligence Explorer uses fictional companies, accounts, events and scores. All are illustrative sample data.
- The GTM Systems Architecture is a conceptual workflow demonstration. It is not connected to live systems.
- The Kaizen page is a review draft based on project proposal and service-scope materials. It distinguishes documented diagnosis, proposed scope and delivery status. It does not claim unverified outcomes or completed deliverables.
- The Kaizen page is marked `noindex` while delivery status and publication permission are being reviewed. Remove that directive only after approval for public release.
- The case page includes a client-name toggle so the named and anonymised presentation can be reviewed. Confirm the client's permission before publishing the named version.

## Before public release

Confirm which Kaizen workstreams were completed and accepted, which assets went live, what outcomes can be evidenced, and whether the client name may be published. Do not replace the current status notes with claims until supporting records are available.
