# Crown Credit Repair Command Center

**Kingdom Financial Services** - Credit dispute management & client tracking platform.

## Features

- **Three.js animated background** with golden particle system
- **Kingdom brand theme** - dark UI with gold accents
- **6-phase dispute workflow** from preparation to maintenance
- **Interactive checklists** that persist across sessions (localStorage)
- **Multi-client support** - onboard unlimited clients with template workflows
- **LetterStream integration** - track certified mail jobs & tracking numbers
- **Decision tree** - interactive "what if" guidance for every scenario
- **Export/Import** - backup and restore client data as JSON
- **Print-ready** - clean print layout for paper records

## Live Demo

Visit: [https://jelfferyduran.github.io/credit-repair-cmd/](https://jelfferyduran.github.io/credit-repair-cmd/)

## Local Development

```bash
# Clone
git clone https://github.com/JelfferyDuran/credit-repair-cmd.git
cd credit-repair-cmd

# Serve locally (any static server works)
python -m http.server 8080
# Then open http://localhost:8080
```

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Vanilla JS + CSS (single-page app) |
| 3D Effects | Three.js (r128) |
| Data Store | localStorage (client-side DB) |
| Deployment | GitHub Pages |
| Version Control | Git + GitHub |

## File Structure

```
credit-repair-cmd/
├── index.html          # Main application (self-contained)
├── logo.png            # KFS Kingdom logo
├── README.md           # This file
├── .gitignore          # Git rules
└── docs/               # Future: API docs, templates
```

## Roadmap

### Current (MVP)
- [x] Three.js Kingdom background
- [x] 6-phase dispute workflow
- [x] Interactive checklists (persistent)
- [x] Multi-client support
- [x] LetterStream job tracking
- [x] Certified mail tracking table
- [x] Decision tree (9 scenarios)
- [x] Export/Import JSON
- [x] Print support

### Next Phase
- [ ] Backend API (Node.js/Express)
- [ ] PostgreSQL database
- [ ] PDF dispute letter generator
- [ ] Email notifications (deadline reminders)
- [ ] Client portal (separate login)
- [ ] Automated bureau report parsing (MISMO XML)
- [ ] Template library (100+ dispute strategies)
- [ ] Mobile responsive improvements

### Future
- [ ] Electron desktop app
- [ ] Docker deployment option
- [ ] Tailscale private access
- [ ] Zapier/n8n integrations

## Data Privacy

- All client data stored **locally in browser** (localStorage)
- No server-side data collection
- Export feature for manual backups
- Print support for paper records

## License

Proprietary - Kingdom Financial Services

## Support

Contact: jelfferyduran@proton.me

---

*Built with the Crown of Excellence*
