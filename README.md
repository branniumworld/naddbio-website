# NADDBio Website

**Live Site:** https://www.naddbio.com

## Overview

NADDBio is a biopharmaceutical R&D consultancy based in Cambridge, Massachusetts. This repository contains the source code for the company website.

## Technology Stack

- **Hosting:** Azure Static Web Apps
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Fonts:** Google Fonts (Cormorant, Work Sans)
- **Contact Form:** Web3Forms
- **Assets CDN:** Azure Blob Storage

## Pages

| Page | Desktop | Mobile |
|------|---------|--------|
| Homepage | index.html | index_mobile.html |
| Services | naddbio_services.html | naddbio_services_mobile.html |
| About | naddbio-about-mockup.html | naddbio-about-mockup_mobile.html |
| Contact | naddbio_contact.html | naddbio_contact_mobile.html |
| Therapeutic Areas | naddbio_therapeutic_areas.html | naddbio_therapeutic_areas_mobile.html |
| Meet the Team | naddbio_meet_the_team.html | naddbio_meet_the_team_mobile.html |
| Leadership | naddbio_leadership.html | naddbio_leadership_mobile.html |
| Privacy Policy | privacy-policy.html | — |

## Deployment

The site is deployed to Azure Static Web Apps. Deployment is done via the SWA CLI:

```bash
npx @azure/static-web-apps-cli deploy . --env production
```

## Contact

- **Client:** NADDBio (kingsley.urakpo@naddbio.com)
- **Developer:** Brannium (design@brannium.com)

---

*Vibed in [Wippli](https://wippli.ai) by [Brannium](https://brannium.com)*
