# University of Velen – Edge Delivery Services

A modern university website built using **Adobe Experience Manager (AEM) Edge Delivery Services (EDS)**. The project demonstrates document-based content authoring, reusable blocks, custom styling, and a responsive university website experience.

## Live Website

- **Preview:** https://main--udpc-eds--suresh-k-9226.aem.page/
- **Live:** https://main--udpc-eds--suresh-k-9226.aem.live/

## Project Overview

University of Velen is a university website developed using Adobe Experience Manager Edge Delivery Services.

The project focuses on delivering a modern, accessible, and responsive digital experience while using document-based authoring to manage website content.

The website showcases university information, academic programs, faculty, campus life, and admissions-related content through reusable EDS blocks.

## Key Features

- Modern university homepage.
- Responsive website layout.
- Custom hero section with calls to action.
- University highlights and feature cards.
- Academic program showcase.
- Faculty information section.
- Campus life and events section.
- Reusable header and footer.
- Custom CSS and JavaScript blocks.
- Document-based content authoring through Google Drive.
- AEM Code Sync integration with GitHub.

## Technology Stack

| Technology | Purpose |
|---|---|
| Adobe Experience Manager Edge Delivery Services | Website delivery and content management |
| HTML5 | Website structure |
| CSS3 | Styling and responsive layouts |
| JavaScript | Interactive functionality |
| Google Drive | Document-based content source |
| GitHub | Source code management |
| AEM Code Sync | Synchronization between GitHub and AEM |
| Node.js and npm | Local development and package management |
| ESLint | JavaScript code quality |
| Stylelint | CSS code quality |

## Project Architecture

The project follows the Edge Delivery Services architecture, using document-based authoring and reusable blocks.

### Content Authoring

Website content is managed through Google Drive, configured as the project's content source.

### AEM Code Sync

AEM Code Sync connects the GitHub repository with the AEM Edge Delivery Services environment.

### Frontend Rendering

EDS uses project scripts, styles, and reusable blocks to transform authored content into the website experience.

## Custom Blocks

The project includes the following custom blocks:

| Block | Description |
|---|---|
| Hero | Main homepage banner and call-to-action section |
| Cards | Reusable card-based content presentation |
| Columns | Multi-column content layouts |
| Header | Website navigation and branding |
| Footer | Website footer and navigation |
| Fragment | Reusable content fragments |
| Widget | Custom widget functionality |

Each block contains its own JavaScript and CSS files where applicable.

## Project Structure

```text
udpc-eds/
│
├── blocks/
│   ├── cards/
│   │   ├── cards.css
│   │   └── cards.js
│   ├── columns/
│   │   ├── columns.css
│   │   └── columns.js
│   ├── footer/
│   │   ├── footer.css
│   │   └── footer.js
│   ├── fragment/
│   │   ├── fragment.css
│   │   └── fragment.js
│   ├── header/
│   │   ├── header.css
│   │   └── header.js
│   ├── hero/
│   │   ├── hero.css
│   │   └── hero.js
│   └── widget/
│       ├── widget.css
│       └── widget.js
│
├── fonts/
├── icons/
├── scripts/
│   ├── aem.js
│   ├── consent-check.js
│   ├── consented.js
│   └── scripts.js
│
├── styles/
│   ├── fonts.css
│   ├── lazy-styles.css
│   └── styles.css
│
├── .github/
├── head.html
├── 404.html
├── package.json
├── package-lock.json
└── README.md
```

## AEM Configuration

The project is configured with Adobe Experience Manager Edge Delivery Services.

| Configuration | Details |
|---|---|
| GitHub Repository | `suresh-k-9226/udpc-eds` |
| Content Source | Google Drive |
| Content Authoring | Document-based authoring |
| AEM Code Sync | Configured |
| Site User | Administrator |

### Content Source

Website content is managed through the configured Google Drive folder:

[University of Velen – Content Folder](https://drive.google.com/drive/folders/1jwxm5XtCkYsGrlp9Tt3OkOO7muRj4dP2)

## Installation and Setup

### Prerequisites

- Node.js
- npm
- Git
- Visual Studio Code or another code editor
- Adobe AEM CLI

### Clone the Repository

```bash
git clone https://github.com/suresh-k-9226/udpc-eds.git
```

Navigate to the project:

```bash
cd udpc-eds
```

### Install Dependencies

```bash
npm install
```

### Start Local Development

Install the AEM CLI:

```bash
npm install -g @adobe/aem-cli
```

Start the AEM development proxy:

```bash
aem up
```

Open the local website:

```text
http://localhost:3000
```

## Code Quality and Linting

The project uses ESLint and Stylelint to maintain code quality.

Run JavaScript linting:

```bash
npm run lint:js
```

Run CSS linting:

```bash
npm run lint:css
```

Run all lint checks:

```bash
npm run lint
```

Automatically fix supported linting issues:

```bash
npm run lint:fix
```

## Deployment and Preview

AEM Edge Delivery Services provides preview and live environments for the website.

- **Preview:** Used to review content and implementation changes.
- **Live:** The published website environment.

The project is connected to GitHub through AEM Code Sync.

## Future Enhancements

- Improve accessibility and usability.
- Enhance responsive layouts across devices.
- Introduce additional reusable EDS blocks.
- Improve website performance and loading behavior.
- Expand university content and academic program information.

## Author

**Suresh Kandregula**

GitHub: [Suresh-k-9226](https://github.com/Suresh-k-9226)

---

Built with Adobe Experience Manager Edge Delivery Services.