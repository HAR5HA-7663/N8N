# N8N Workflow Import Guide

This repository contains n8n workflow files to automate newsletter management. Follow the steps below to install n8n, download the workflow files, and import them into your n8n instance.

## Prerequisites
- **Node.js**: Version 14 or later installed on your computer.
- **n8n**: Installed globally using npm.
- A basic understanding of JSON files and workflow automation.

---

## Installing n8n

### Install Node.js:
1. Download Node.js from [Node.js Official Website](https://nodejs.org/).
2. Install it by following the on-screen instructions.

### Install n8n:
1. Open your terminal or command prompt.
2. Run the following command:
   ```bash
   npm install n8n --location=global
   ```
3. Start n8n with:
   ```bash
   npx n8n
   ```

### Access n8n:
- Open your browser and navigate to [http://localhost:5678](http://localhost:5678).

---

## Downloading Workflow Files

1. Navigate to the repository's main page.
2. Click on the desired file (e.g., `newsletter_automation (2).json`).
3. Click the "Raw" button at the top right of the file view.
4. Right-click and select "Save As..." to download the file.
5. Repeat for all workflow files you need.

**Alternatively**:
- Download all files by clicking the green "Code" button and selecting "Download ZIP".
- Extract the ZIP file after downloading.

---

## Importing Workflows into n8n

1. Open your n8n interface in a browser ([http://localhost:5678](http://localhost:5678)).
2. Click on the "+" button in the left sidebar to create a new workflow.
3. Click on the three dots (`...`) in the top-right corner of the editor.
4. Select **"Import from File..."**.
5. Choose the JSON file you downloaded and click "Open".
6. The workflow will appear in your editor.

---

## Configuring and Saving Workflows

1. Review each node in the imported workflow to ensure all configurations are correct.
2. Set up any required credentials for services (e.g., email providers, APIs).
3. Save your workflow by clicking the "Save" button in the top-right corner.

---

## Troubleshooting

### Installation Errors:
- Ensure you have Node.js installed and updated.
- Use administrator privileges if necessary.

### Port Issues:
- If [http://localhost:5678](http://localhost:5678) is unavailable, try starting n8n on a different port:
  ```bash
  npx n8n start --port=5679
  ```

### Import Errors:
- Ensure you downloaded a valid JSON file from this repository.
