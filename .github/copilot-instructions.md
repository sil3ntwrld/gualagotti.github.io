# Repository Overview

This is a GitHub Pages repository for the custom domain `nextlevelhoops.me`. It's a minimal website repository currently containing only a CNAME configuration file and a README.

## Project Type

- **Type**: GitHub Pages static website
- **Domain**: nextlevelhoops.me (configured via CNAME)
- **Languages**: HTML, CSS, JavaScript (potential)
- **Framework**: Static HTML/CSS or Jekyll (GitHub Pages default)

## Repository Structure

```
.
├── .github/
│   └── copilot-instructions.md (this file)
├── CNAME                        (custom domain configuration)
└── README.md                    (repository description)
```

## Build and Deployment

This repository uses GitHub Pages for automatic deployment:

- **Deployment**: Automatic via GitHub Pages when changes are pushed to the main branch
- **No build steps required**: Static files are served directly
- **Custom domain**: Configured via CNAME file pointing to nextlevelhoops.me

### Important Notes

- The CNAME file must contain only the domain name without protocol (e.g., `nextlevelhoops.me`)
- GitHub Pages automatically deploys changes from the repository root
- No local build or test commands are needed for basic HTML/CSS/JS files
- If using Jekyll, GitHub Pages builds it automatically server-side

## Development Guidelines

### File Structure
- Place HTML files in the root directory or appropriate subdirectories
- CSS files typically go in a `/css` or `/styles` directory
- JavaScript files typically go in a `/js` or `/scripts` directory
- Images typically go in an `/images` or `/assets` directory

### Testing Changes
- **Local testing**: Use `python3 -m http.server 8000` or similar HTTP server in the repository root to test locally
- **Preview**: Changes will be live at nextlevelhoops.me after being pushed to the main branch (may take 1-2 minutes)

### Common Tasks
- **Adding new pages**: Create `.html` files in the root or subdirectories
- **Updating domain**: Modify the CNAME file (must be a single line with just the domain)
- **Adding assets**: Create appropriate directories (css, js, images) as needed

## Validation Steps

Before pushing changes:
1. Ensure CNAME file remains intact with just the domain name
2. Validate HTML syntax if adding HTML files
3. Test locally using a simple HTTP server if possible
4. Ensure file paths are relative and will work when deployed

## GitHub Workflows

Currently, there are no custom GitHub Actions workflows. GitHub Pages handles deployment automatically.
