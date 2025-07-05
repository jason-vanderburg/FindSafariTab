# Alfred Workflows

A collection of Alfred 5 workflows to streamline common macOS tasks.  
Each workflow lives in its own subfolder and can be imported into Alfred individually.

---

## Repository Structure

```
alfred-workflows/
├── FindSafariTab/                # “Find Safari Tab” workflow
│   ├── FindSafariTab.alfredworkflow
│   └── README.md                 # Workflow-specific instructions
├── another-workflow/             # e.g. “Email Formatter” workflow
│   ├── email-formatter.alfredworkflow
│   └── README.md
└── README.md                     # ← This file
```

---

## Installation

1. **Clone this repo:**  
   ```bash
   git clone git@github.com:jason-vanderburg/alfred-workflows.git
   cd alfred-workflows
   ```

2. **Import workflows one by one:**  
   For each subfolder (e.g. `FindSafariTab/`), double-click the `.alfredworkflow` file inside.  
   Alfred will open and ask if you want to import.

3. **Grant Permissions:**  
   Open **System Settings → Privacy & Security → Accessibility**  
   & **Automation**, then allow **Alfred 5** to control any apps used by your workflows (e.g. Safari).

---

## Usage

- After importing, trigger each workflow according to its instructions (see each subfolder’s `README.md`).  
- You can also enable or disable any workflow from Alfred Preferences → Workflows.

---

## License

MIT © Jason Vanderburg  
